---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64Operand` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> - Instances of this class represent a parsed <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64AsmParser.cpp}::AArch64Operand { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#a01896a57dfa18fd9bb5afd21bf21b836">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">VecListIndexType { <a href="#a8b7fe4a86d1fc278bc8a784a5841c47d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a746de2acde56369f5eb419d1e448c5">AArch64Operand</a> (KindTy K, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a> (const AArch64Operand &amp;o)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa7c931bd41a8e31636c1f1960f0550f">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#aaa7c931bd41a8e31636c1f1960f0550f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310a3d48b265069745c2b08f1ad49d3d">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#a310a3d48b265069745c2b08f1ad49d3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69c86c3f6d0cb218cb21fdff76b52061">getToken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a214b786a70ead5ef3d4ce375a99571e2">isTokenSuffix</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe33538658ff5ed08e6c4aa63e597f9d">getShiftedImmVal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95653df7fe73ba4cac906726630b7b82">getShiftedImmShift</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af39600298b97e7a4b4f8877f51edba9a">getFirstImmVal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb40063c81db44668a2d42579dd1d899">getLastImmVal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47eab7aa29bf67fd06806c3d7773e80a">getCondCode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe43ce294e9f0705c6f51289b1057d16">getFPImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a98536dd501b77d6c855f7031a25e8">getFPImmIsExact</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51269ef5293d0098e7191bdb7ff580c9">getBarrier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f4c80dd445035027357cb39b58ce38">getBarrierName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d715a0837669084b837c5f8d35100e5">getBarriernXSModifier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fea0718404532d427bb085c3d096eba">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6c9765bc0f705dbb376478576625b3">getMatrixReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a273f1e0056964b595836b6841da5d62e">getMatrixElementWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#ae85d8088eed863a1562f8d66049518a1">MatrixKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16ee56c2954762ecb13b4b909c89e4c">getMatrixKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75916f715b269b8c18090dcab1d50a2">getMatrixTileListRegMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#adf99bb1304f6eacbd9d3efdc3aa43bfc">RegConstraintEqualityTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c102f52588775a1538fcb2b716a77f">getRegEqualityTy</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347e0dad95df4d701ccef02e0e69a891">getVectorListStart</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa773f3fcc176fc95d3c7a11df57e2848">getVectorListCount</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadfb2ce8425322833201803c3dadd4aa">getVectorListStride</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73c5be75abb0824d924de7bbb051b4be">getVectorIndex</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c8a2eff9a3bbb47486f39a7a256340">getSysReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0372e03254511a04907d691d623a1ab9">getSysCR</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b07c78cf7e27b8cf4a2e73395d47588">getPrefetch</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fc9ae60ad902441966be44a7aaa4aa3">getPSBHint</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd267b7333794825dbcbe73772833b2">getPHint</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab357d8a823ad62eedc521a7f28bf68c">getPSBHintName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc81c5d305908130290ef7aec6713368">getPHintName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae064fea0649422b53e39309580f50784">getBTIHint</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76657580467f9c30a243c70d77a1834">getBTIHintName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41603fd7c0667cb139207752e90036d">getSVCR</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb7a4223e386379eb5fdc9d7ef46322f">getPrefetchName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f9e1ccafa17c5328c20c4fef98e470">hasShiftExtendAmount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea91f2a32c29a629c3d67afe5c31440b">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#aea91f2a32c29a629c3d67afe5c31440b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae298b03ad92d819463618f443c401b59">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#ae298b03ad92d819463618f443c401b59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d0b74dbf90ea3967907f05a88b06a2">isUImm6</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16f360ccfa1eb023fac00431ac79543b">isSImm</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Bits, int Scale&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a97fe28e7c116a9a926e26133f5ee3adb">isSImmScaled</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Bits, int Scale, int Offset = 0, bool IsRange = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b9b954fffe0be9433ada4a9cc7fee9b">isUImmScaled</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Bits, int Scale, bool IsRange = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a18544038561f8c08b8ea6d6da02784">isImmScaled</a> (bool Signed) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ede1b5501f32283fb6084a02528b20">isSVEPattern</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5781cadb65dde47dd3d4fa07c5021091">isSVEVecLenSpecifier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af609eb8e37538160d693e8e47e1f87bd">isSymbolicUImm12Offset</a> (const MCExpr *Expr) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Scale&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82e2a376717221b4993b1fc95415bde9">isUImm12Offset</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int N, int M&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f6c1755e5ae566a87d87508d3cee9dc">isImmInRange</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d689d56ccbeb5bad8afd84d615d31b7">isLogicalImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05b315cc338b1b8eb7e3f9bf564e5e6b">isShiftedImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76154ce7fc1f5f0efbe6666cb8d6c67f">isImmRange</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a> () const -&gt; std::optional&lt; std::pair&lt; int64_t, unsigned &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the immediate value as a pair of (imm, shift) if the immediate is a shifted immediate by value 'Shift' or '0', or if it is an unshifted immediate that can be shifted by 'Shift'. <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40e6dd1a68e37d4348480f3c10858f8">isAddSubImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1ceb39d04bc1c073d4dacdf7b5a6f04">isAddSubImmNeg</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78d9bb4d126d1c4906dfee221ec64e5b">isSVECpyImm</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a23b2900efc3dc7b9ab2e4655fd3874ca">isSVEAddSubImm</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa980e8ae2ed3b758a3d93a9e0a888a4f">isSVEPreferredLogicalImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cd6066e0c6cd47f87bb1941f9a981bf">isCondCode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1892421b1a924f86a66c28974d47c7d">isSIMDImmType10</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6502fd15601fbefa6de9a3c3f2a15a0d">isBranchTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3802559d2c75d983cd9101cd12ac5c57">isMovWSymbol</a> (ArrayRef&lt; AArch64MCExpr::VariantKind &gt; AllowedModifiers) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a162468b3d99ecab971492c5500b8a2">isMovWSymbolG3</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f70b77525355a42babc1c101bd55f8a">isMovWSymbolG2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3c15231badddd02b4095368f9ca5641">isMovWSymbolG1</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3fde429a245f53c871307e383e526a">isMovWSymbolG0</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int RegWidth, int Shift&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21f95622afbe879f8b6fab324bb71a17">isMOVZMovAlias</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int RegWidth, int Shift&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a018eb3f34b1fe02b8d60532cf5713ba7">isMOVNMovAlias</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab81555068a211eb808e86d91d8ec390c">isFPImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4ab945870d6b64c113a39bad07114d4">isBarrier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32f890d2609e2fe06eb669f122d1d93">isBarriernXS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1adba96b3a79ec99156cee8455a4900b">isSysReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927364ec8999f2481c4e15389b2cc8b2">isMRSSystemRegister</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845e6e739c47f4a01d42409a778e8851">isMSRSystemRegister</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1020b599fae66259f4fea308c1219d38">isSystemPStateFieldWithImm0_1</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a883e4f7f94c6e62e7e0b9a0c31b6358f">isSystemPStateFieldWithImm0_15</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b381a1d754f73924bf089e383b5345c">isSVCR</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1214b42d8c13e2b88c7e7dec09dc768f">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#a1214b42d8c13e2b88c7e7dec09dc768f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f514cef6cf063a09ae1b48a1ac4c73">isVectorList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6b9947463eebe84f16bdc7c39a26f0">isScalarReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfbd51eeaf0c3673cd8f29350209280f">isNeonVectorReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f46afc52463b826e5bfa8c7039bac0d">isNeonVectorRegLo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b52b9f1137ba53299e66263d422f51">isNeonVectorReg0to7</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee7b25fcfb704f1d60f03cc019c1f4d">isMatrix</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7013ea61d621beb9dde0936079716c">isMatrixTileList</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Class&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a658c552c0a2ffb525fdf9049ef7ff38c">isSVEPredicateAsCounterReg</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Class&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0a4a1525f0b03c1db7189d13e5dae79">isSVEVectorReg</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Class&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a50f8a02f56b23d90871849510ddc3696">isFPRasZPR</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int ElementWidth, unsigned Class&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9e000099eb23f2a702495218265f3512">isSVEPredicateVectorRegOfWidth</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int ElementWidth, unsigned Class&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a71399ecd50196774ab996901b18c2170">isSVEPredicateOrPredicateAsCounterRegOfWidth</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int ElementWidth, unsigned Class&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a504f15f35c5d8db3437e75dce512b5d4">isSVEPredicateAsCounterRegOfWidth</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int ElementWidth, unsigned Class&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6a8c1f03eb7bbfac873e12ecd63ee41a">isSVEDataVectorRegOfWidth</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abc43845557a2bbe9fe7f3612b197fe97">isSVEDataVectorRegWithShiftExtend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b507a511fbcaafb076607adf8f5a26b">isGPR32as64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177e778238e7f752fcff2460443afb39">isGPR64as32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78533c925280ebb9b2d0e3244141e3e7">isGPR64x8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf6802bde80df76dc31c984f5f7ce063">isWSeqPair</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9684e332b7d1b66ab9b6c7124cf81ba7">isXSeqPair</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8a148bfce41fb17538cb3625b0612f">isSyspXzrPair</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int64_t Angle, int64_t Remainder&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a512f38d8a6227cc7ebd485d3d46bc365">isComplexRotation</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned RegClassID&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c97678587f4aabaf8237328391007d3">isGPR64</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned RegClassID, int ExtWidth&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16d3b435ab22364600eb3af46fec4b29">isGPR64WithShiftExtend</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c9f19db01e9020f9fda38bf694463be">isImplicitlyTypedVectorList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a vector list with the type implicit (presumably attached to the instruction itself)? <a href="#a9c9f19db01e9020f9fda38bf694463be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a62c3fc6bf060a795cb66bf5544af58d0">isTypedVectorList</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd7238ce7f28b58aefe19170d4c9f934">isTypedVectorListMultiple</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abbf2aa6a208882a12d8264f5c0e76e31">isTypedVectorListStrided</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Min, int Max&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e1bd40daf5e75a7ac655914e7499238">isVectorIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8164483cb400880f28c00d1f1050d147">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#a8164483cb400880f28c00d1f1050d147">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7240770a4389825ad34599244815758d">isTokenEqual</a> (StringRef Str) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a140a1f49fb8f0998628efd4cfb5a1cd8">isSysCR</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b96fb57483cff5727815d80f80f103b">isPrefetch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557de9464647a140b174bd3b86f0a649">isPSBHint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b354e9615f1a0cc8a66ee6242ca3a26">isPHint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd57ad7ad3cabdfb0f446aaf5871853d">isBTIHint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e240631b5dac6b7b4f7caab3e2abde6">isShiftExtend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf4eecc5d7b370b00cfb6608e4e9dea">isShifter</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ImmEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21b5aaa8f0eba3c0ece98cdc86d90dec">isExactFPImm</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ImmA, unsigned ImmB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8e72c14218f0af593f125225ded4d3c">isExactFPImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4596bc58bb52249e577a5b3ac193766">isExtend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765373e23aa809a4c85b60411a1dc021">isExtend64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf323a9890c80ec88255035c5655c35f">isExtendLSL64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6010873a7d304b002621c1caf466e89">isLSLImm3Shift</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af1da8768651416a2ccadd7e59af0d003">isMemXExtend</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af9bc3c08d8b9f44b326ea7d10fa0b9d1">isMemWExtend</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad672c4920253428db94773cb2be92dc1">isArithmeticShifter</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab2a97a552049bfe30c944b6dde3b6d5">isLogicalShifter</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cdecbf48af2c861d8f1acce127123a5">isMovImm32Shifter</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6614d8eec367d62f580c299b237389e">isMovImm64Shifter</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70566006f8429c9ceca4aadce19cc626">isLogicalVecShifter</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1a3019908cfff5330263a2752a9d33">isLogicalVecHalfWordShifter</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dbb9683c3cc8c356d44f3cd88623439">isMoveVecShifter</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3fa25d9cd8faa372bf7e6c3fcb618997">isSImm9OffsetFB</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4bea02bcb8b770deb2d6ea439c3f642">isAdrpLabel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80247423cff6ce10b85e83fe46850605">isAdrLabel</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;MatrixKind Kind, unsigned EltSize, unsigned RegClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/diagnosticpredicate">DiagnosticPredicate</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad81b99aea193e203aeb95e1c5bdba7f4">isMatrixRegOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f7622e49d7747dc8b2b9ee2f586a4c9">isPAuthPCRelLabel16Operand</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a> (MCInst &amp;Inst, const MCExpr *Expr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a834f5cf804b7eb070f1fb2cd8498f7eb">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a9b33a2e0d8bab36c2c5cb7b36d610">addMatrixOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f56500894c6c3ca92c54b569cc42a7">addGPR32as64Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45d96b1d1611280239c5f5ec90e1d22">addGPR64as32Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Width&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a693bc5d80a94144221ae8311989c4652">addFPRasZPRRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f2b9dd674ec50e06b69b98a88e00317">addPPRorPNRRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9931ba36928eed8dcf2595c04ba489">addPNRasPPRRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b12b775c6f9e800fb7fd722fd6a5e90">addVectorReg64Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69eda91bc353715ea7d51bc6d0d2e849">addVectorReg128Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac4e8905e8ea71e68562f82797840d6d">addVectorRegLoOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a4ccdc548344f69822f6914bb40e35">addVectorReg0to7Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ec1a2d3550a48035bda06364865c408">addVectorListOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned NumRegs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adbe61948d3299303dc25faf037775ae3">addStridedVectorListOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705e1e39d5002641f1a1a2730612b728">addMatrixTileListOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d1858fef112dddb614e924ca0c714b4">addVectorIndexOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned ImmIs0, unsigned ImmIs1&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9644f19a682324b158710b3222d190eb">addExactFPImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1209139ff48f61a284639b683997350">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Shift&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6d217a1a1a9c4c03289d555a4404aed">addImmWithOptionalShiftOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Shift&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab1e3f86f5e35a49ad9969616da8ee130">addImmNegWithOptionalShiftOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5120ff8db5e8098a3f9551e139d8aeaf">addCondCodeOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab44f4b2113b7a3876bd7e61758319c6f">addAdrpLabelOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a575b6ba91338eaa06fd666dad94bc35c">addAdrLabelOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Scale&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aade413b77f569da1d358d025182ced99">addUImm12OffsetOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc87770d7b78bdaebb4b74db9dfd78f">addUImm6Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Scale&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad09ecb52e79c8bef77dea3fa313c9a31">addImmScaledOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Scale&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3dfb11dc7e2fe62f40ada900f6e9e176">addImmScaledRangeOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae997d5e3fd8015241b318c4b0da0c194">addLogicalImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9056346261cb779a567f627676c37068">addLogicalImmNotOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a275d93f01f3c0461c602869aa89a1fad">addSIMDImmType10Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1448a1c0dc861047a4abeab5dfa3d57">addBranchTarget26Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94b3cbab03d77b6119bf4ffb8dc5b21d">addPAuthPCRelLabel16Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418048be5c0be53d70dec5000e5d4a7b">addPCRelLabel19Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbecf14320c5f3c8b0156ccc7a9ee39b">addPCRelLabel9Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab7d7b59c23bda548073770ccaaa1f54">addBranchTarget14Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc0596f177340a6d088aa4b9084263d">addFPImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a591114c0fea921bbe5364d31fbef1b64">addBarrierOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48edf5070960702e2bdb4809a21e342e">addBarriernXSOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4beaf9b78d7eb225552cd94b0149b024">addMRSSystemRegisterOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8b498e080d62622a43e79e74556aa3">addMSRSystemRegisterOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941d8c4c599c4ae4ed4da18d83b17b72">addSystemPStateFieldWithImm0_1Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0f3af336e424eb47c2d849c53a9c99">addSVCROperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b5e0864f1dbb517a90f7e7a92946f5">addSystemPStateFieldWithImm0_15Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f086ffb95e53ca2321121772ddc00a">addSysCROperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6f3578ca5c81d7b4fdfb0abd1dbfd6">addPrefetchOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff9fa54c3161ee17b37acc2b5546ea8">addPSBHintOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab862de3d6c862e4a282cd88b928b9de4">addPHintOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8745b3f6e84510f5123c608560d067c3">addBTIHintOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad007797dfd6b5c922a9818fd215aebd0">addShifterOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa032e057f6912df64dddaffa3eaadf91">addLSLImm3ShifterOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a536cdad3a9f844e78b6003550707b214">addSyspXzrPairOperand</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2b0c34d3cfaf2fa1561bfaf6182700">addExtendOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ebb7021420c49a1338058e4db7f435">addExtend64Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2a8c70306e9fdd7c8450d043f183e2">addMemExtendOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f0eb14b728a80df813a4da2e6ea7a7">addMemExtend8Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Shift&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e23ebca490a6a436d047976a01e7d2f">addMOVZMovAliasOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Shift&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a937ca41eef356bc1388ad88f951238b7">addMOVNMovAliasOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd4ed46a8bba14b6e611e0e34a5e02cc">addComplexRotationEvenOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e16e22e5918c7110f0f7658b61f53e8">addComplexRotationOddOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a763e5d73a932a30d95c888b81f45a0c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60bb6fba3a328904a2c49fca0fff3908">Tok</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72f955625b09945025a13deb0635690">MatrixReg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a590f01c7cbd3ec2afbe9c4fca46fbb4c">MatrixTileList</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ba073805f2c16be2635d9364688fa5">VectorIndex</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a173d50c9ec45e6ef19632f49986b2672">ShiftedImm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b973934d0703fadc85f6e179814f46">ImmRange</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef042e56aeccc2de3ef8d0681e16de0">CondCode</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a007c5108691de8314bda7d4e918e6be6">FPImm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa071bb32c71be50385b1ce5ad9201c4">Barrier</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc173b2bba5c1cf36d6376ca304d6f7">SysCRImm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9b0f1bfbee3723b641f53759139f019">Prefetch</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac5ed90c079ad32f0a8e7f33a0159cb">PSBHint</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade03d07197bb5b8ccaab62ec581da32f">PHint</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401e3a0e1e293e67ea9952558fb9edbf">BTIHint</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa471f43252f2060615bada15e9a9a14d">ShiftExtend</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c2f36b7a65bbf6b93f1da1faaeb0ed">SVCR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{AArch64AsmParser.cpp}::AArch64Operand::KindTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0761d4efa262dd3c3f91a1884297c0a7">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3fb02a75f6688ee3a080319768aa6e2">StartLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59212f5d499ab6c4960c10a71663e5b6">EndLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{AArch64AsmParser.cpp}<a href="#a2a746de2acde56369f5eb419d1e448c5">::AArch64Operand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3110f2c44bd232d1c81d76cc2ee34dc"></a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd33780ddbefa933cd4face7895549cd">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9716ea33305039a90a7740e0096e0a1c">CreateToken</a> (StringRef Str, SMLoc S, MCContext &amp;Ctx, bool IsSuffix=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7a28dcef468d7f382405644a61ebdb6">CreateReg</a> (unsigned RegNum, RegKind Kind, SMLoc S, SMLoc E, MCContext &amp;Ctx, RegConstraintEqualityTy EqTy=RegConstraintEqualityTy::EqualsReg, AArch64_AM::ShiftExtendType ExtTy=AArch64_AM::LSL, unsigned ShiftAmount=0, unsigned HasExplicitAmount=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ed7e81802b458392ce9f886b11a514">CreateVectorReg</a> (unsigned RegNum, RegKind Kind, unsigned ElementWidth, SMLoc S, SMLoc E, MCContext &amp;Ctx, AArch64_AM::ShiftExtendType ExtTy=AArch64_AM::LSL, unsigned ShiftAmount=0, unsigned HasExplicitAmount=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f33fa8dea06aa9e477c99e0ea87f14">CreateVectorList</a> (unsigned RegNum, unsigned Count, unsigned Stride, unsigned NumElements, unsigned ElementWidth, RegKind RegisterKind, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a961cc170babf61f916a4976b7d970481">CreateVectorIndex</a> (int Idx, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d4237cdecde8dee7028b1aad03c5e7">CreateMatrixTileList</a> (unsigned RegMask, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab92b093e430b26d0fe06b8365fc1ebd8">ComputeRegsForAlias</a> (unsigned Reg, SmallSet&lt; unsigned, 8 &gt; &amp;OutRegs, const unsigned ElementWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8877c1117570555c9ce5a0bf965e8a35">CreateImm</a> (const MCExpr *Val, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b60185b9fe801fec888a33a13abd6a8">CreateShiftedImm</a> (const MCExpr *Val, unsigned ShiftAmount, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f5000e71169f8618f53309a0039b1e">CreateImmRange</a> (unsigned First, unsigned Last, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac7110ce867b04e527060890c1da67c">CreateCondCode</a> (AArch64CC::CondCode Code, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830996c6ee01a4fc50c18055a48a02a8">CreateFPImm</a> (APFloat Val, bool IsExact, SMLoc S, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094dc88f2420640fa11bdef5527e7974">CreateBarrier</a> (unsigned Val, StringRef Str, SMLoc S, MCContext &amp;Ctx, bool HasnXSModifier)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02115a580903fb8d978b48da6a948add">CreateSysReg</a> (StringRef Str, SMLoc S, uint32_t MRSReg, uint32_t MSRReg, uint32_t PStateField, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101b4e6a4d46db6b024269607e4d7e30">CreatePHintInst</a> (unsigned Val, StringRef Str, SMLoc S, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dba4834c00b0a7fbceacb5ab9b48750">CreateSysCR</a> (unsigned Val, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ed4fe3bfe1eb8afbb0a987d7f1a69c">CreatePrefetch</a> (unsigned Val, StringRef Str, SMLoc S, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f40f983ca2184621ac68b3c043e5a6">CreatePSBHint</a> (unsigned Val, StringRef Str, SMLoc S, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426a1e25f5aee438dd5c055157695761">CreateBTIHint</a> (unsigned Val, StringRef Str, SMLoc S, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa35c4eacc80abc11a98a64511331a7">CreateMatrixRegister</a> (unsigned RegNum, unsigned ElementWidth, MatrixKind Kind, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6830b8929f4c1f0f70df41b11e41a40">CreateSVCR</a> (uint32_t PStateField, StringRef Str, SMLoc S, MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf837ce33cf1cae1b786722ae02f4388">CreateShiftExtend</a> (AArch64_AM::ShiftExtendType ShOp, unsigned Val, bool HasExplicitAmount, SMLoc S, SMLoc E, MCContext &amp;Ctx)</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> - Instances of this class represent a parsed <a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> machine instruction.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindTy {#a01896a57dfa18fd9bb5afd21bf21b836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AArch64AsmParser.cpp}::AArch64Operand::KindTy </td>
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
<td class="doxyEnumItemName">k_Immediate<a id="a01896a57dfa18fd9bb5afd21bf21b836af4024c786cebc904dd6df44f286b35f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_ShiftedImm<a id="a01896a57dfa18fd9bb5afd21bf21b836a144beb0698dd441c3fd7ba390c7cfe51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_ImmRange<a id="a01896a57dfa18fd9bb5afd21bf21b836ab7a0c41dded058d907f276bfa820410f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_CondCode<a id="a01896a57dfa18fd9bb5afd21bf21b836ac1948c5f8cf6847e83b9d02393e157bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_Register<a id="a01896a57dfa18fd9bb5afd21bf21b836a4c1e4c6b292fab4736adca1470c40792"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_MatrixRegister<a id="a01896a57dfa18fd9bb5afd21bf21b836a829bd08a0b44e2b9d9cc89dfa2f56514"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_MatrixTileList<a id="a01896a57dfa18fd9bb5afd21bf21b836a661eb847dd00d5193e606bcc68018629"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_SVCR<a id="a01896a57dfa18fd9bb5afd21bf21b836a64ea16630353f896e3fd26734afbf31d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_VectorList<a id="a01896a57dfa18fd9bb5afd21bf21b836a06abeef442cf078b315a8c8686c230c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_VectorIndex<a id="a01896a57dfa18fd9bb5afd21bf21b836a48753e5d47dc3111f003d691390c9bba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_Token<a id="a01896a57dfa18fd9bb5afd21bf21b836aba81e85b41401d93ab63a931bffc9cf0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_SysReg<a id="a01896a57dfa18fd9bb5afd21bf21b836af44b5c160bde49bb9750c6c083ee241d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_SysCR<a id="a01896a57dfa18fd9bb5afd21bf21b836a842d8ef7d5e3b16482da6d019ec90a26"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_Prefetch<a id="a01896a57dfa18fd9bb5afd21bf21b836a6f9c02741d9c64b6448de869e8876f9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_ShiftExtend<a id="a01896a57dfa18fd9bb5afd21bf21b836a28b133ff96ded493d37766e13f51b366"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_FPImm<a id="a01896a57dfa18fd9bb5afd21bf21b836a5191c42fe6ca70bd4bde7ed1aade9139"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_Barrier<a id="a01896a57dfa18fd9bb5afd21bf21b836a9c640f3b4ae2d478a887172322fdd3e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_PSBHint<a id="a01896a57dfa18fd9bb5afd21bf21b836a8528aa22ba904729eda9db9094c3be01"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_PHint<a id="a01896a57dfa18fd9bb5afd21bf21b836a7bdca5eeed6c26047a239d6e07a709c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">k_BTIHint<a id="a01896a57dfa18fd9bb5afd21bf21b836a55c4ac21cf235066286858dbcecd060c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### VecListIndexType {#a8b7fe4a86d1fc278bc8a784a5841c47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AArch64AsmParser.cpp}::AArch64Operand::VecListIndexType </td>
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
<td class="doxyEnumItemName">VecListIdx_DReg<a id="a8b7fe4a86d1fc278bc8a784a5841c47da69a96cf4d50ca04ec602f2dc34fb6bfd"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecListIdx_QReg<a id="a8b7fe4a86d1fc278bc8a784a5841c47da514e1c0ba50b4b895dcb4cd4ec58c224"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecListIdx_ZReg<a id="a8b7fe4a86d1fc278bc8a784a5841c47daacc0c6c874c1e8d62cc1eaf0345f7cda"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecListIdx_PReg<a id="a8b7fe4a86d1fc278bc8a784a5841c47da47d5caa1c4aca9cc0433d220fd7c4486"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AArch64Operand() {#a2a746de2acde56369f5eb419d1e448c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64AsmParser.cpp}::AArch64Operand::AArch64Operand (KindTy K, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>.</p>

</div>
</div>

### AArch64Operand() {#a2164d8c44abd99cb1354a75459eeb7dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64AsmParser.cpp}::AArch64Operand::AArch64Operand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand">AArch64Operand</a> &amp; o)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a2a746de2acde56369f5eb419d1e448c5">AArch64Operand</a>, <a href="#aaa071bb32c71be50385b1ce5ad9201c4">Barrier</a>, <a href="#a401e3a0e1e293e67ea9952558fb9edbf">BTIHint</a>, <a href="#a5ef042e56aeccc2de3ef8d0681e16de0">CondCode</a>, <a href="#a007c5108691de8314bda7d4e918e6be6">FPImm</a>, <a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a>, <a href="#aa6b973934d0703fadc85f6e179814f46">ImmRange</a>, <a href="#ae72f955625b09945025a13deb0635690">MatrixReg</a>, <a href="#a590f01c7cbd3ec2afbe9c4fca46fbb4c">MatrixTileList</a>, <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a116eebce8e7768c60749aa19af77f817">llvm::MCParsedAsmOperand::MCParsedAsmOperand</a>, <a href="#ade03d07197bb5b8ccaab62ec581da32f">PHint</a>, <a href="#ab9b0f1bfbee3723b641f53759139f019">Prefetch</a>, <a href="#a0ac5ed90c079ad32f0a8e7f33a0159cb">PSBHint</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>, <a href="#a173d50c9ec45e6ef19632f49986b2672">ShiftedImm</a>, <a href="#aa471f43252f2060615bada15e9a9a14d">ShiftExtend</a>, <a href="#a72c2f36b7a65bbf6b93f1da1faaeb0ed">SVCR</a>, <a href="#a7bc173b2bba5c1cf36d6376ca304d6f7">SysCRImm</a>, <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>, <a href="#a60bb6fba3a328904a2c49fca0fff3908">Tok</a>, <a href="#a41ba073805f2c16be2635d9364688fa5">VectorIndex</a> and <a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAdrLabelOperands() {#a575b6ba91338eaa06fd666dad94bc35c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addAdrLabelOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2006 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#af1209139ff48f61a284639b683997350">addImmOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addAdrpLabelOperands() {#ab44f4b2113b7a3876bd7e61758319c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addAdrpLabelOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBarriernXSOperands() {#a48edf5070960702e2bdb4809a21e342e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBarriernXSOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a51269ef5293d0098e7191bdb7ff580c9">getBarrier</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBarrierOperands() {#a591114c0fea921bbe5364d31fbef1b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBarrierOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a51269ef5293d0098e7191bdb7ff580c9">getBarrier</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBranchTarget14Operands() {#aab7d7b59c23bda548073770ccaaa1f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBranchTarget14Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBranchTarget26Operands() {#aa1448a1c0dc861047a4abeab5dfa3d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBranchTarget26Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2066 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addBTIHintOperands() {#a8745b3f6e84510f5123c608560d067c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBTIHintOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#ae064fea0649422b53e39309580f50784">getBTIHint</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addComplexRotationEvenOperands() {#acd4ed46a8bba14b6e611e0e34a5e02cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addComplexRotationEvenOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addComplexRotationOddOperands() {#a0e16e22e5918c7110f0f7658b61f53e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addComplexRotationOddOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addCondCodeOperands() {#a5120ff8db5e8098a3f9551e139d8aeaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addCondCodeOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1992 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#aaa07fe2265bce961279f7e11bb2f4408">getCondCode</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addExactFPImmOperands() {#a9644f19a682324b158710b3222d190eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ImmIs0, unsigned ImmIs1&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExactFPImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1953 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a21b5aaa8f0eba3c0ece98cdc86d90dec">isExactFPImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addExpr() {#a30cd1f96ee2fa28938de227cf1b47f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExpr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#ab44f4b2113b7a3876bd7e61758319c6f">addAdrpLabelOperands</a>, <a href="#aab7d7b59c23bda548073770ccaaa1f54">addBranchTarget14Operands</a>, <a href="#aa1448a1c0dc861047a4abeab5dfa3d57">addBranchTarget26Operands</a>, <a href="#af1209139ff48f61a284639b683997350">addImmOperands</a>, <a href="#ab6d217a1a1a9c4c03289d555a4404aed">addImmWithOptionalShiftOperands</a>, <a href="#a4e23ebca490a6a436d047976a01e7d2f">addMOVZMovAliasOperands</a>, <a href="#a94b3cbab03d77b6119bf4ffb8dc5b21d">addPAuthPCRelLabel16Operands</a>, <a href="#a418048be5c0be53d70dec5000e5d4a7b">addPCRelLabel19Operands</a> and <a href="#acbecf14320c5f3c8b0156ccc7a9ee39b">addPCRelLabel9Operands</a>.</p>

</div>
</div>

### addExtend64Operands() {#a12ebb7021420c49a1338058e4db7f435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExtend64Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a35905b769bf1afa2cc7e2a223191e57e">llvm::AArch64_AM::getArithExtendImm</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ad2f6771d4027a09ba1d0de2e5ea54470">llvm::AArch64_AM::UXTX</a>.</p>

</div>
</div>

### addExtendOperands() {#a8a2b0c34d3cfaf2fa1561bfaf6182700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExtendOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a35905b769bf1afa2cc7e2a223191e57e">llvm::AArch64_AM::getArithExtendImm</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d">llvm::AArch64_AM::UXTW</a>.</p>

</div>
</div>

### addFPImmOperands() {#aadc0596f177340a6d088aa4b9084263d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addFPImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aa3b818e0d89b7804a311b48c18080a4f">llvm::AArch64_AM::getFP64Imm</a>, <a href="#abe43ce294e9f0705c6f51289b1057d16">getFPImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addFPRasZPRRegOperands() {#a693bc5d80a94144221ae8311989c4652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addFPRasZPRRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1812 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addGPR32as64Operands() {#ac4f56500894c6c3ca92c54b569cc42a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR32as64Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1787 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a88977138a65e44f5f302342e4a00b501">llvm::MCRegisterInfo::getEncodingValue</a>, <a href="#a7fea0718404532d427bb085c3d096eba">getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#ae179799df1c5f01dc1c55e7ff4868743">llvm::MCRegisterInfo::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass/#ac33acd2efcc170ca04a2229d8c365629">llvm::MCRegisterClass::getRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### addGPR64as32Operands() {#ac45d96b1d1611280239c5f5ec90e1d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR64as32Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1799 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a88977138a65e44f5f302342e4a00b501">llvm::MCRegisterInfo::getEncodingValue</a>, <a href="#a7fea0718404532d427bb085c3d096eba">getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#ae179799df1c5f01dc1c55e7ff4868743">llvm::MCRegisterInfo::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass/#ac33acd2efcc170ca04a2229d8c365629">llvm::MCRegisterClass::getRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### addImmNegWithOptionalShiftOperands() {#ab1e3f86f5e35a49ad9969616da8ee130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Shift&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmNegWithOptionalShiftOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1983 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmOperands() {#af1209139ff48f61a284639b683997350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a575b6ba91338eaa06fd666dad94bc35c">addAdrLabelOperands</a>.</p>

</div>
</div>

### addImmScaledOperands() {#ad09ecb52e79c8bef77dea3fa313c9a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Scale&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmScaledOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2029 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmScaledRangeOperands() {#a3dfb11dc7e2fe62f40ada900f6e9e176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Scale&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmScaledRangeOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2036 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#af39600298b97e7a4b4f8877f51edba9a">getFirstImmVal</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmWithOptionalShiftOperands() {#ab6d217a1a1a9c4c03289d555a4404aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Shift&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmWithOptionalShiftOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1968 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="#a95653df7fe73ba4cac906726630b7b82">getShiftedImmShift</a>, <a href="#abe33538658ff5ed08e6c4aa63e597f9d">getShiftedImmVal</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a>, <a href="#a05b315cc338b1b8eb7e3f9bf564e5e6b">isShiftedImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addLogicalImmNotOperands() {#a9056346261cb779a567f627676c37068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmNotOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2051 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a832ad315a355f4ddcc32f189f34e28a9">llvm::AArch64_AM::encodeLogicalImmediate</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addLogicalImmOperands() {#ae997d5e3fd8015241b318c4b0da0c194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2042 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a832ad315a355f4ddcc32f189f34e28a9">llvm::AArch64_AM::encodeLogicalImmediate</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addLSLImm3ShifterOperands() {#aa032e057f6912df64dddaffa3eaadf91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLSLImm3ShifterOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMatrixOperands() {#a52a9b33a2e0d8bab36c2c5cb7b36d610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMatrixOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1782 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a8b6c9765bc0f705dbb376478576625b3">getMatrixReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMatrixTileListOperands() {#a705e1e39d5002641f1a1a2730612b728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMatrixTileListOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#ac75916f715b269b8c18090dcab1d50a2">getMatrixTileListRegMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMemExtend8Operands() {#ac9f0eb14b728a80df813a4da2e6ea7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMemExtend8Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ac5f9e1ccafa17c5328c20c4fef98e470">hasShiftExtendAmount</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">llvm::AArch64_AM::SXTW</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4">llvm::AArch64_AM::SXTX</a>.</p>

</div>
</div>

### addMemExtendOperands() {#a4c2a8c70306e9fdd7c8450d043f183e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMemExtendOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">llvm::AArch64_AM::SXTW</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4">llvm::AArch64_AM::SXTX</a>.</p>

</div>
</div>

### addMOVNMovAliasOperands() {#a937ca41eef356bc1388ad88f951238b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Shift&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMOVNMovAliasOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMOVZMovAliasOperands() {#a4e23ebca490a6a436d047976a01e7d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Shift&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMOVZMovAliasOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMRSSystemRegisterOperands() {#a4beaf9b78d7eb225552cd94b0149b024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMRSSystemRegisterOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>

</div>
</div>

### addMSRSystemRegisterOperands() {#a1c8b498e080d62622a43e79e74556aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMSRSystemRegisterOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>

</div>
</div>

### addPAuthPCRelLabel16Operands() {#a94b3cbab03d77b6119bf4ffb8dc5b21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPAuthPCRelLabel16Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2080 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addPCRelLabel19Operands() {#a418048be5c0be53d70dec5000e5d4a7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPCRelLabel19Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addPCRelLabel9Operands() {#acbecf14320c5f3c8b0156ccc7a9ee39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPCRelLabel9Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a30cd1f96ee2fa28938de227cf1b47f02">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addPHintOperands() {#ab862de3d6c862e4a282cd88b928b9de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPHintOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a5fd267b7333794825dbcbe73772833b2">getPHint</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addPNRasPPRRegOperands() {#a6c9931ba36928eed8dcf2595c04ba489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPNRasPPRRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addPPRorPNRRegOperands() {#a5f2b9dd674ec50e06b69b98a88e00317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPPRorPNRRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### addPrefetchOperands() {#aba6f3578ca5c81d7b4fdfb0abd1dbfd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPrefetchOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a9b07c78cf7e27b8cf4a2e73395d47588">getPrefetch</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addPSBHintOperands() {#abff9fa54c3161ee17b37acc2b5546ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPSBHintOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a3fc9ae60ad902441966be44a7aaa4aa3">getPSBHint</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#a834f5cf804b7eb070f1fb2cd8498f7eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addShifterOperands() {#ad007797dfd6b5c922a9818fd215aebd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addShifterOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aeae88f12b667477f90db9b726556b337">llvm::AArch64_AM::getShifterImm</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addSIMDImmType10Operands() {#a275d93f01f3c0461c602869aa89a1fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSIMDImmType10Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2059 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a73d57b024abd09c15c27e89d3bea29b0">llvm::AArch64_AM::encodeAdvSIMDModImmType10</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addStridedVectorListOperands() {#adbe61948d3299303dc25faf037775ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned NumRegs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addStridedVectorListOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a347e0dad95df4d701ccef02e0e69a891">getVectorListStart</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addSVCROperands() {#aec0f3af336e424eb47c2d849c53a9c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSVCROperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a72c2f36b7a65bbf6b93f1da1faaeb0ed">SVCR</a>.</p>

</div>
</div>

### addSysCROperands() {#a32f086ffb95e53ca2321121772ddc00a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSysCROperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a0372e03254511a04907d691d623a1ab9">getSysCR</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addSyspXzrPairOperand() {#a536cdad3a9f844e78b6003550707b214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSyspXzrPairOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a88977138a65e44f5f302342e4a00b501">llvm::MCRegisterInfo::getEncodingValue</a>, <a href="#a7fea0718404532d427bb085c3d096eba">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#ae179799df1c5f01dc1c55e7ff4868743">llvm::MCRegisterInfo::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass/#ac33acd2efcc170ca04a2229d8c365629">llvm::MCRegisterClass::getRegister</a>, <a href="#a2b6b9947463eebe84f16bdc7c39a26f0">isScalarReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### addSystemPStateFieldWithImm0\_15Operands() {#a58b5e0864f1dbb517a90f7e7a92946f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSystemPStateFieldWithImm0_15Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>

</div>
</div>

### addSystemPStateFieldWithImm0\_1Operands() {#a941d8c4c599c4ae4ed4da18d83b17b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSystemPStateFieldWithImm0_1Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>

</div>
</div>

### addUImm12OffsetOperands() {#aade413b77f569da1d358d025182ced99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Scale&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addUImm12OffsetOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addUImm6Operands() {#a3cc87770d7b78bdaebb4b74db9dfd78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addUImm6Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2022 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addVectorIndexOperands() {#a7d1858fef112dddb614e924ca0c714b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorIndexOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1947 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a73c5be75abb0824d924de7bbb051b4be">getVectorIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addVectorListOperands() {#a4ec1a2d3550a48035bda06364865c408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;VecListIndexType RegTy, unsigned NumRegs, bool IsConsecutive = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorListOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1874 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a347e0dad95df4d701ccef02e0e69a891">getVectorListStart</a>, <a href="#aadfb2ce8425322833201803c3dadd4aa">getVectorListStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a8b7fe4a86d1fc278bc8a784a5841c47da47d5caa1c4aca9cc0433d220fd7c4486">VecListIdx_PReg</a> and <a href="#a8b7fe4a86d1fc278bc8a784a5841c47daacc0c6c874c1e8d62cc1eaf0345f7cda">VecListIdx_ZReg</a>.</p>

</div>
</div>

### addVectorReg0to7Operands() {#ac6a4ccdc548344f69822f6914bb40e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg0to7Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1860 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addVectorReg128Operands() {#a69eda91bc353715ea7d51bc6d0d2e849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg128Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1848 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addVectorReg64Operands() {#a1b12b775c6f9e800fb7fd722fd6a5e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg64Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addVectorRegLoOperands() {#aac4e8905e8ea71e68562f82797840d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorRegLoOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1855 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getBarrier() {#a51269ef5293d0098e7191bdb7ff580c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getBarrier ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaa071bb32c71be50385b1ce5ad9201c4">Barrier</a>.</p>


<p>Referenced by <a href="#a48edf5070960702e2bdb4809a21e342e">addBarriernXSOperands</a>, <a href="#a591114c0fea921bbe5364d31fbef1b64">addBarrierOperands</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getBarrierName() {#a91f4c80dd445035027357cb39b58ce38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmParser.cpp}::AArch64Operand::getBarrierName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaa071bb32c71be50385b1ce5ad9201c4">Barrier</a>.</p>


<p>Referenced by <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getBarriernXSModifier() {#a7d715a0837669084b837c5f8d35100e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::getBarriernXSModifier ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aaa071bb32c71be50385b1ce5ad9201c4">Barrier</a>.</p>


<p>Referenced by <a href="#ad4ab945870d6b64c113a39bad07114d4">isBarrier</a> and <a href="#af32f890d2609e2fe06eb669f122d1d93">isBarriernXS</a>.</p>

</div>
</div>

### getBTIHint() {#ae064fea0649422b53e39309580f50784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getBTIHint ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a401e3a0e1e293e67ea9952558fb9edbf">BTIHint</a>.</p>


<p>Referenced by <a href="#a8745b3f6e84510f5123c608560d067c3">addBTIHintOperands</a>.</p>

</div>
</div>

### getBTIHintName() {#ad76657580467f9c30a243c70d77a1834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmParser.cpp}::AArch64Operand::getBTIHintName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a401e3a0e1e293e67ea9952558fb9edbf">BTIHint</a>.</p>


<p>Referenced by <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getCondCode() {#a47eab7aa29bf67fd06806c3d7773e80a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64CC::CondCode anonymous{AArch64AsmParser.cpp}::AArch64Operand::getCondCode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5ef042e56aeccc2de3ef8d0681e16de0">CondCode</a>.</p>


<p>Referenced by <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getEndLoc() {#a310a3d48b265069745c2b08f1ad49d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AArch64AsmParser.cpp}::AArch64Operand::getEndLoc ()</td>
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

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### getFirstImmVal() {#af39600298b97e7a4b4f8877f51edba9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getFirstImmVal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa6b973934d0703fadc85f6e179814f46">ImmRange</a>.</p>


<p>Referenced by <a href="#a3dfb11dc7e2fe62f40ada900f6e9e176">addImmScaledRangeOperands</a>, <a href="#a4a18544038561f8c08b8ea6d6da02784">isImmScaled</a>, <a href="#a2b9b954fffe0be9433ada4a9cc7fee9b">isUImmScaled</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getFPImm() {#abe43ce294e9f0705c6f51289b1057d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat anonymous{AArch64AsmParser.cpp}::AArch64Operand::getFPImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a007c5108691de8314bda7d4e918e6be6">FPImm</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>.</p>


<p>Referenced by <a href="#aadc0596f177340a6d088aa4b9084263d">addFPImmOperands</a>, <a href="#a21b5aaa8f0eba3c0ece98cdc86d90dec">isExactFPImm</a>, <a href="#ab81555068a211eb808e86d91d8ec390c">isFPImm</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getFPImmIsExact() {#a06a98536dd501b77d6c855f7031a25e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::getFPImmIsExact ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a007c5108691de8314bda7d4e918e6be6">FPImm</a>.</p>


<p>Referenced by <a href="#a21b5aaa8f0eba3c0ece98cdc86d90dec">isExactFPImm</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getImm() {#a5f596578202f6176f0a0d90fb310c1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{AArch64AsmParser.cpp}::AArch64Operand::getImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a>.</p>


<p>Referenced by <a href="#ab44f4b2113b7a3876bd7e61758319c6f">addAdrpLabelOperands</a>, <a href="#aab7d7b59c23bda548073770ccaaa1f54">addBranchTarget14Operands</a>, <a href="#aa1448a1c0dc861047a4abeab5dfa3d57">addBranchTarget26Operands</a>, <a href="#acd4ed46a8bba14b6e611e0e34a5e02cc">addComplexRotationEvenOperands</a>, <a href="#a0e16e22e5918c7110f0f7658b61f53e8">addComplexRotationOddOperands</a>, <a href="#af1209139ff48f61a284639b683997350">addImmOperands</a>, <a href="#ad09ecb52e79c8bef77dea3fa313c9a31">addImmScaledOperands</a>, <a href="#ab6d217a1a1a9c4c03289d555a4404aed">addImmWithOptionalShiftOperands</a>, <a href="#a9056346261cb779a567f627676c37068">addLogicalImmNotOperands</a>, <a href="#ae997d5e3fd8015241b318c4b0da0c194">addLogicalImmOperands</a>, <a href="#a937ca41eef356bc1388ad88f951238b7">addMOVNMovAliasOperands</a>, <a href="#a4e23ebca490a6a436d047976a01e7d2f">addMOVZMovAliasOperands</a>, <a href="#a94b3cbab03d77b6119bf4ffb8dc5b21d">addPAuthPCRelLabel16Operands</a>, <a href="#a418048be5c0be53d70dec5000e5d4a7b">addPCRelLabel19Operands</a>, <a href="#acbecf14320c5f3c8b0156ccc7a9ee39b">addPCRelLabel9Operands</a>, <a href="#a275d93f01f3c0461c602869aa89a1fad">addSIMDImmType10Operands</a>, <a href="#aade413b77f569da1d358d025182ced99">addUImm12OffsetOperands</a>, <a href="#a3cc87770d7b78bdaebb4b74db9dfd78f">addUImm6Operands</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a>, <a href="#ae40e6dd1a68e37d4348480f3c10858f8">isAddSubImm</a>, <a href="#a6502fd15601fbefa6de9a3c3f2a15a0d">isBranchTarget</a>, <a href="#a512f38d8a6227cc7ebd485d3d46bc365">isComplexRotation</a>, <a href="#a0f6c1755e5ae566a87d87508d3cee9dc">isImmInRange</a>, <a href="#a4a18544038561f8c08b8ea6d6da02784">isImmScaled</a>, <a href="#a9d689d56ccbeb5bad8afd84d615d31b7">isLogicalImm</a>, <a href="#a018eb3f34b1fe02b8d60532cf5713ba7">isMOVNMovAlias</a>, <a href="#a3802559d2c75d983cd9101cd12ac5c57">isMovWSymbol</a>, <a href="#a21f95622afbe879f8b6fab324bb71a17">isMOVZMovAlias</a>, <a href="#a4f7622e49d7747dc8b2b9ee2f586a4c9">isPAuthPCRelLabel16Operand</a>, <a href="#aa1892421b1a924f86a66c28974d47c7d">isSIMDImmType10</a>, <a href="#a23b2900efc3dc7b9ab2e4655fd3874ca">isSVEAddSubImm</a>, <a href="#a78d9bb4d126d1c4906dfee221ec64e5b">isSVECpyImm</a>, <a href="#af6ede1b5501f32283fb6084a02528b20">isSVEPattern</a>, <a href="#a5781cadb65dde47dd3d4fa07c5021091">isSVEVecLenSpecifier</a>, <a href="#a82e2a376717221b4993b1fc95415bde9">isUImm12Offset</a>, <a href="#a36d0b74dbf90ea3967907f05a88b06a2">isUImm6</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getLastImmVal() {#afb40063c81db44668a2d42579dd1d899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getLastImmVal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aa6b973934d0703fadc85f6e179814f46">ImmRange</a>.</p>


<p>Referenced by <a href="#a2b9b954fffe0be9433ada4a9cc7fee9b">isUImmScaled</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getMatrixElementWidth() {#a273f1e0056964b595836b6841da5d62e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getMatrixElementWidth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae72f955625b09945025a13deb0635690">MatrixReg</a>.</p>


<p>Referenced by <a href="#ad81b99aea193e203aeb95e1c5bdba7f4">isMatrixRegOperand</a>.</p>

</div>
</div>

### getMatrixKind() {#aa16ee56c2954762ecb13b4b909c89e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixKind anonymous{AArch64AsmParser.cpp}::AArch64Operand::getMatrixKind ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae72f955625b09945025a13deb0635690">MatrixReg</a>.</p>


<p>Referenced by <a href="#ad81b99aea193e203aeb95e1c5bdba7f4">isMatrixRegOperand</a>.</p>

</div>
</div>

### getMatrixReg() {#a8b6c9765bc0f705dbb376478576625b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getMatrixReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae72f955625b09945025a13deb0635690">MatrixReg</a>.</p>


<p>Referenced by <a href="#a52a9b33a2e0d8bab36c2c5cb7b36d610">addMatrixOperands</a>, <a href="#ad81b99aea193e203aeb95e1c5bdba7f4">isMatrixRegOperand</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getMatrixTileListRegMask() {#ac75916f715b269b8c18090dcab1d50a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getMatrixTileListRegMask ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aba7013ea61d621beb9dde0936079716c">isMatrixTileList</a> and <a href="#a590f01c7cbd3ec2afbe9c4fca46fbb4c">MatrixTileList</a>.</p>


<p>Referenced by <a href="#a705e1e39d5002641f1a1a2730612b728">addMatrixTileListOperands</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getPHint() {#a5fd267b7333794825dbcbe73772833b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getPHint ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ade03d07197bb5b8ccaab62ec581da32f">PHint</a>.</p>


<p>Referenced by <a href="#ab862de3d6c862e4a282cd88b928b9de4">addPHintOperands</a>.</p>

</div>
</div>

### getPHintName() {#afc81c5d305908130290ef7aec6713368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmParser.cpp}::AArch64Operand::getPHintName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ade03d07197bb5b8ccaab62ec581da32f">PHint</a>.</p>


<p>Referenced by <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getPrefetch() {#a9b07c78cf7e27b8cf4a2e73395d47588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getPrefetch ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab9b0f1bfbee3723b641f53759139f019">Prefetch</a>.</p>


<p>Referenced by <a href="#aba6f3578ca5c81d7b4fdfb0abd1dbfd6">addPrefetchOperands</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getPrefetchName() {#adb7a4223e386379eb5fdc9d7ef46322f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmParser.cpp}::AArch64Operand::getPrefetchName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab9b0f1bfbee3723b641f53759139f019">Prefetch</a>.</p>


<p>Referenced by <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getPSBHint() {#a3fc9ae60ad902441966be44a7aaa4aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getPSBHint ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0ac5ed90c079ad32f0a8e7f33a0159cb">PSBHint</a>.</p>


<p>Referenced by <a href="#abff9fa54c3161ee17b37acc2b5546ea8">addPSBHintOperands</a>.</p>

</div>
</div>

### getPSBHintName() {#aab357d8a823ad62eedc521a7f28bf68c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmParser.cpp}::AArch64Operand::getPSBHintName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0ac5ed90c079ad32f0a8e7f33a0159cb">PSBHint</a>.</p>


<p>Referenced by <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getReg() {#a7fea0718404532d427bb085c3d096eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{AArch64AsmParser.cpp}::AArch64Operand::getReg ()</td>
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



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>


<p>Referenced by <a href="#ac4f56500894c6c3ca92c54b569cc42a7">addGPR32as64Operands</a>, <a href="#ac45d96b1d1611280239c5f5ec90e1d22">addGPR64as32Operands</a>, <a href="#a536cdad3a9f844e78b6003550707b214">addSyspXzrPairOperand</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getRegEqualityTy() {#a55c102f52588775a1538fcb2b716a77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegConstraintEqualityTy anonymous{AArch64AsmParser.cpp}::AArch64Operand::getRegEqualityTy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### getShiftedImmShift() {#a95653df7fe73ba4cac906726630b7b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getShiftedImmShift ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a173d50c9ec45e6ef19632f49986b2672">ShiftedImm</a>.</p>


<p>Referenced by <a href="#ab6d217a1a1a9c4c03289d555a4404aed">addImmWithOptionalShiftOperands</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getShiftedImmVal() {#abe33538658ff5ed08e6c4aa63e597f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{AArch64AsmParser.cpp}::AArch64Operand::getShiftedImmVal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a173d50c9ec45e6ef19632f49986b2672">ShiftedImm</a>.</p>


<p>Referenced by <a href="#ab6d217a1a1a9c4c03289d555a4404aed">addImmWithOptionalShiftOperands</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getShiftedVal() {#a83c5e95fb85aaef96207fc9e9ddfccc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; int64_t, unsigned &gt; &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::getShiftedVal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the immediate value as a pair of (imm, shift) if the immediate is a shifted immediate by value 'Shift' or '0', or if it is an unshifted immediate that can be shifted by 'Shift'.</p>

<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="#a95653df7fe73ba4cac906726630b7b82">getShiftedImmShift</a>, <a href="#abe33538658ff5ed08e6c4aa63e597f9d">getShiftedImmVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="#a05b315cc338b1b8eb7e3f9bf564e5e6b">isShiftedImm</a>.</p>


<p>Referenced by <a href="#ab1e3f86f5e35a49ad9969616da8ee130">addImmNegWithOptionalShiftOperands</a>, <a href="#ab6d217a1a1a9c4c03289d555a4404aed">addImmWithOptionalShiftOperands</a>, <a href="#ae40e6dd1a68e37d4348480f3c10858f8">isAddSubImm</a>, <a href="#aa1ceb39d04bc1c073d4dacdf7b5a6f04">isAddSubImmNeg</a>, <a href="#a23b2900efc3dc7b9ab2e4655fd3874ca">isSVEAddSubImm</a> and <a href="#a78d9bb4d126d1c4906dfee221ec64e5b">isSVECpyImm</a>.</p>

</div>
</div>

### getShiftExtendAmount() {#acf520862ca47f73eff607fa5d2d189eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getShiftExtendAmount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="#aa471f43252f2060615bada15e9a9a14d">ShiftExtend</a>.</p>


<p>Referenced by <a href="#a12ebb7021420c49a1338058e4db7f435">addExtend64Operands</a>, <a href="#a8a2b0c34d3cfaf2fa1561bfaf6182700">addExtendOperands</a>, <a href="#aa032e057f6912df64dddaffa3eaadf91">addLSLImm3ShifterOperands</a>, <a href="#a4c2a8c70306e9fdd7c8450d043f183e2">addMemExtendOperands</a>, <a href="#ad007797dfd6b5c922a9818fd215aebd0">addShifterOperands</a>, <a href="#ad672c4920253428db94773cb2be92dc1">isArithmeticShifter</a>, <a href="#ae4596bc58bb52249e577a5b3ac193766">isExtend</a>, <a href="#acf323a9890c80ec88255035c5655c35f">isExtendLSL64</a>, <a href="#a16d3b435ab22364600eb3af46fec4b29">isGPR64WithShiftExtend</a>, <a href="#aab2a97a552049bfe30c944b6dde3b6d5">isLogicalShifter</a>, <a href="#a2f1a3019908cfff5330263a2752a9d33">isLogicalVecHalfWordShifter</a>, <a href="#a70566006f8429c9ceca4aadce19cc626">isLogicalVecShifter</a>, <a href="#aa6010873a7d304b002621c1caf466e89">isLSLImm3Shift</a>, <a href="#af9bc3c08d8b9f44b326ea7d10fa0b9d1">isMemWExtend</a>, <a href="#af1da8768651416a2ccadd7e59af0d003">isMemXExtend</a>, <a href="#a6dbb9683c3cc8c356d44f3cd88623439">isMoveVecShifter</a>, <a href="#a7cdecbf48af2c861d8f1acce127123a5">isMovImm32Shifter</a>, <a href="#ac6614d8eec367d62f580c299b237389e">isMovImm64Shifter</a>, <a href="#abc43845557a2bbe9fe7f3612b197fe97">isSVEDataVectorRegWithShiftExtend</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getShiftExtendType() {#a61664d5453b445203df60352a2557912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64_AM::ShiftExtendType anonymous{AArch64AsmParser.cpp}::AArch64Operand::getShiftExtendType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="#aa471f43252f2060615bada15e9a9a14d">ShiftExtend</a>.</p>


<p>Referenced by <a href="#a12ebb7021420c49a1338058e4db7f435">addExtend64Operands</a>, <a href="#a8a2b0c34d3cfaf2fa1561bfaf6182700">addExtendOperands</a>, <a href="#ac9f0eb14b728a80df813a4da2e6ea7a7">addMemExtend8Operands</a>, <a href="#a4c2a8c70306e9fdd7c8450d043f183e2">addMemExtendOperands</a>, <a href="#ad007797dfd6b5c922a9818fd215aebd0">addShifterOperands</a>, <a href="#ad672c4920253428db94773cb2be92dc1">isArithmeticShifter</a>, <a href="#ae4596bc58bb52249e577a5b3ac193766">isExtend</a>, <a href="#a765373e23aa809a4c85b60411a1dc021">isExtend64</a>, <a href="#acf323a9890c80ec88255035c5655c35f">isExtendLSL64</a>, <a href="#a16d3b435ab22364600eb3af46fec4b29">isGPR64WithShiftExtend</a>, <a href="#aab2a97a552049bfe30c944b6dde3b6d5">isLogicalShifter</a>, <a href="#a2f1a3019908cfff5330263a2752a9d33">isLogicalVecHalfWordShifter</a>, <a href="#a70566006f8429c9ceca4aadce19cc626">isLogicalVecShifter</a>, <a href="#aa6010873a7d304b002621c1caf466e89">isLSLImm3Shift</a>, <a href="#af9bc3c08d8b9f44b326ea7d10fa0b9d1">isMemWExtend</a>, <a href="#af1da8768651416a2ccadd7e59af0d003">isMemXExtend</a>, <a href="#a6dbb9683c3cc8c356d44f3cd88623439">isMoveVecShifter</a>, <a href="#a7cdecbf48af2c861d8f1acce127123a5">isMovImm32Shifter</a>, <a href="#ac6614d8eec367d62f580c299b237389e">isMovImm64Shifter</a>, <a href="#a6cf4eecc5d7b370b00cfb6608e4e9dea">isShifter</a>, <a href="#abc43845557a2bbe9fe7f3612b197fe97">isSVEDataVectorRegWithShiftExtend</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getStartLoc() {#aaa7c931bd41a8e31636c1f1960f0550f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AArch64AsmParser.cpp}::AArch64Operand::getStartLoc ()</td>
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

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### getSVCR() {#ab41603fd7c0667cb139207752e90036d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmParser.cpp}::AArch64Operand::getSVCR ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a72c2f36b7a65bbf6b93f1da1faaeb0ed">SVCR</a>.</p>


<p>Referenced by <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getSysCR() {#a0372e03254511a04907d691d623a1ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getSysCR ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7bc173b2bba5c1cf36d6376ca304d6f7">SysCRImm</a>.</p>


<p>Referenced by <a href="#a32f086ffb95e53ca2321121772ddc00a">addSysCROperands</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getSysReg() {#ad1c8a2eff9a3bbb47486f39a7a256340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmParser.cpp}::AArch64Operand::getSysReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>


<p>Referenced by <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getToken() {#a69c86c3f6d0cb218cb21fdff76b52061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64AsmParser.cpp}::AArch64Operand::getToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a60bb6fba3a328904a2c49fca0fff3908">Tok</a>.</p>


<p>Referenced by <a href="#a7240770a4389825ad34599244815758d">isTokenEqual</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getVectorIndex() {#a73c5be75abb0824d924de7bbb051b4be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{AArch64AsmParser.cpp}::AArch64Operand::getVectorIndex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a41ba073805f2c16be2635d9364688fa5">VectorIndex</a>.</p>


<p>Referenced by <a href="#a7d1858fef112dddb614e924ca0c714b4">addVectorIndexOperands</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getVectorListCount() {#aa773f3fcc176fc95d3c7a11df57e2848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getVectorListCount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a6f78bf7ab651e1b9fadc25f23bf541dc">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::areEqualRegs</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getVectorListStart() {#a347e0dad95df4d701ccef02e0e69a891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getVectorListStart ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a>.</p>


<p>Referenced by <a href="#adbe61948d3299303dc25faf037775ae3">addStridedVectorListOperands</a>, <a href="#a4ec1a2d3550a48035bda06364865c408">addVectorListOperands</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### getVectorListStride() {#aadfb2ce8425322833201803c3dadd4aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AArch64AsmParser.cpp}::AArch64Operand::getVectorListStride ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a>.</p>


<p>Referenced by <a href="#a4ec1a2d3550a48035bda06364865c408">addVectorListOperands</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### hasShiftExtendAmount() {#ac5f9e1ccafa17c5328c20c4fef98e470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::hasShiftExtendAmount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="#aa471f43252f2060615bada15e9a9a14d">ShiftExtend</a>.</p>


<p>Referenced by <a href="#ac9f0eb14b728a80df813a4da2e6ea7a7">addMemExtend8Operands</a>, <a href="#abc43845557a2bbe9fe7f3612b197fe97">isSVEDataVectorRegWithShiftExtend</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### isAddSubImm() {#ae40e6dd1a68e37d4348480f3c10858f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isAddSubImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a714bb267b4fc2935142836b944e9bef8">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::classifySymbolRef</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#a05b315cc338b1b8eb7e3f9bf564e5e6b">isShiftedImm</a>, <a href="#a173d50c9ec45e6ef19632f49986b2672">ShiftedImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfad1e341aea3471c4a8356b69bfad7a772">llvm::AArch64MCExpr::VK_DTPREL_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae976f5dddffeb8a77e5ecc471343842d">llvm::AArch64MCExpr::VK_DTPREL_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa690cf2259632dd195b29cb7ad0cd16b7">llvm::AArch64MCExpr::VK_DTPREL_LO12_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa2f76c31f5c93ff69cd59e817abd85223">llvm::AArch64MCExpr::VK_GOT_AUTH_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985afc40a65d8cb0da3855201ee24f549aa6">llvm::MCSymbolRefExpr::VK_GOTPAGEOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfac273d7a8ebcef5784a4904ffe145aefe">llvm::AArch64MCExpr::VK_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa68dd5cbd2bf672acbe601e89ccf676a">llvm::MCSymbolRefExpr::VK_PAGEOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfad8bf44f54a45b38024a2cdc10226cb3a">llvm::AArch64MCExpr::VK_SECREL_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaee5e353993b28f25d23e1b76e1b295a2">llvm::AArch64MCExpr::VK_SECREL_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfacf90d92f6c5b8b5972b2631c72eb5dde">llvm::AArch64MCExpr::VK_TLSDESC_AUTH_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae86e7fb84bad4ed1be1f5772229a8d58">llvm::AArch64MCExpr::VK_TLSDESC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985af0a99c543167803572c2fb1642f17010">llvm::MCSymbolRefExpr::VK_TLVPPAGEOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa65b0bb155666aed0ad6a4a61dc4f76b6">llvm::AArch64MCExpr::VK_TPREL_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa69a04395c63763644a14a6a929075fb0">llvm::AArch64MCExpr::VK_TPREL_LO12</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa2d3ca49c7f86aedb741b49d223fce16">llvm::AArch64MCExpr::VK_TPREL_LO12_NC</a>.</p>

</div>
</div>

### isAddSubImmNeg() {#aa1ceb39d04bc1c073d4dacdf7b5a6f04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isAddSubImmNeg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="#a05b315cc338b1b8eb7e3f9bf564e5e6b">isShiftedImm</a>.</p>

</div>
</div>

### isAdrLabel() {#a80247423cff6ce10b85e83fe46850605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isAdrLabel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isAdrpLabel() {#ac4bea02bcb8b770deb2d6ea439c3f642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isAdrpLabel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1709 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ada202c1d243056ec19cb505fa77ad18b">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isArithmeticShifter() {#ad672c4920253428db94773cb2be92dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isArithmeticShifter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a2f11475361161d9ce95a2f7be74de342">llvm::AArch64_AM::ASR</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a6cf4eecc5d7b370b00cfb6608e4e9dea">isShifter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a7e1384a3b7d612a03b54d9c8f2071a04">llvm::AArch64_AM::LSR</a>.</p>

</div>
</div>

### isBarrier() {#ad4ab945870d6b64c113a39bad07114d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isBarrier ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="#a7d715a0837669084b837c5f8d35100e5">getBarriernXSModifier</a>.</p>

</div>
</div>

### isBarriernXS() {#af32f890d2609e2fe06eb669f122d1d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isBarriernXS ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="#a7d715a0837669084b837c5f8d35100e5">getBarriernXSModifier</a>.</p>

</div>
</div>

### isBranchTarget() {#a6502fd15601fbefa6de9a3c3f2a15a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isBranchTarget ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isBTIHint() {#acd57ad7ad3cabdfb0f446aaf5871853d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isBTIHint ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isComplexRotation() {#a512f38d8a6227cc7ebd485d3d46bc365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int64_t Angle, int64_t Remainder&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isComplexRotation ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>.</p>

</div>
</div>

### isCondCode() {#a3cd6066e0c6cd47f87bb1941f9a981bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isCondCode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isExactFPImm() {#a21b5aaa8f0eba3c0ece98cdc86d90dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ImmEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isExactFPImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ac83df2fb4fcefd0a95deb09db83a0635">llvm::APFloat::convertFromString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0596fb939ff753151c9c37ed2b671b4c">llvm::errorToBool</a>, <a href="#abe43ce294e9f0705c6f51289b1057d16">getFPImm</a>, <a href="#a06a98536dd501b77d6c855f7031a25e8">getFPImmIsExact</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a482d9cf95b588eb05cefeaa5c05be9a3">llvm::APFloatBase::rmTowardZero</a>.</p>


<p>Referenced by <a href="#a9644f19a682324b158710b3222d190eb">addExactFPImmOperands</a> and <a href="#af8e72c14218f0af593f125225ded4d3c">isExactFPImm</a>.</p>

</div>
</div>

### isExactFPImm() {#af8e72c14218f0af593f125225ded4d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned ImmA, unsigned ImmB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isExactFPImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a21b5aaa8f0eba3c0ece98cdc86d90dec">isExactFPImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>.</p>

</div>
</div>

### isExtend() {#ae4596bc58bb52249e577a5b3ac193766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isExtend ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a1e240631b5dac6b7b4f7caab3e2abde6">isShiftExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ac3bdf1b8c8fd1f36afa7af40bb1a1a59">llvm::AArch64_AM::SXTB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ae52597f63d00aac32d655ca8d67a689b">llvm::AArch64_AM::SXTH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">llvm::AArch64_AM::SXTW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4">llvm::AArch64_AM::SXTX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a59dcdcd32661c3deea19d0b4c00aeb09">llvm::AArch64_AM::UXTB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a822b65b0f419881e5f0352e2f4f33d29">llvm::AArch64_AM::UXTH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d">llvm::AArch64_AM::UXTW</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ad2f6771d4027a09ba1d0de2e5ea54470">llvm::AArch64_AM::UXTX</a>.</p>


<p>Referenced by <a href="#a765373e23aa809a4c85b60411a1dc021">isExtend64</a>, <a href="#acf323a9890c80ec88255035c5655c35f">isExtendLSL64</a>, <a href="#af9bc3c08d8b9f44b326ea7d10fa0b9d1">isMemWExtend</a> and <a href="#af1da8768651416a2ccadd7e59af0d003">isMemXExtend</a>.</p>

</div>
</div>

### isExtend64() {#a765373e23aa809a4c85b60411a1dc021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isExtend64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ae4596bc58bb52249e577a5b3ac193766">isExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ac3bdf1b8c8fd1f36afa7af40bb1a1a59">llvm::AArch64_AM::SXTB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ae52597f63d00aac32d655ca8d67a689b">llvm::AArch64_AM::SXTH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">llvm::AArch64_AM::SXTW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a59dcdcd32661c3deea19d0b4c00aeb09">llvm::AArch64_AM::UXTB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a822b65b0f419881e5f0352e2f4f33d29">llvm::AArch64_AM::UXTH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d">llvm::AArch64_AM::UXTW</a>.</p>

</div>
</div>

### isExtendLSL64() {#acf323a9890c80ec88255035c5655c35f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isExtendLSL64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ae4596bc58bb52249e577a5b3ac193766">isExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4">llvm::AArch64_AM::SXTX</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ad2f6771d4027a09ba1d0de2e5ea54470">llvm::AArch64_AM::UXTX</a>.</p>

</div>
</div>

### isFPImm() {#ab81555068a211eb808e86d91d8ec390c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isFPImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aa3b818e0d89b7804a311b48c18080a4f">llvm::AArch64_AM::getFP64Imm</a> and <a href="#abe43ce294e9f0705c6f51289b1057d16">getFPImm</a>.</p>

</div>
</div>

### isFPRasZPR() {#a50f8a02f56b23d90871849510ddc3696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Class&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isFPRasZPR ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>

</div>
</div>

### isGPR32as64() {#a2b507a511fbcaafb076607adf8f5a26b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isGPR32as64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>

</div>
</div>

### isGPR64() {#a9c97678587f4aabaf8237328391007d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned RegClassID&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isGPR64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>


<p>Referenced by <a href="#a16d3b435ab22364600eb3af46fec4b29">isGPR64WithShiftExtend</a> and <a href="#a4d8a148bfce41fb17538cb3625b0612f">isSyspXzrPair</a>.</p>

</div>
</div>

### isGPR64as32() {#a177e778238e7f752fcff2460443afb39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isGPR64as32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>

</div>
</div>

### isGPR64WithShiftExtend() {#a16d3b435ab22364600eb3af46fec4b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned RegClassID, int ExtWidth&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isGPR64WithShiftExtend ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a9c97678587f4aabaf8237328391007d3">isGPR64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>

</div>
</div>

### isGPR64x8() {#a78533c925280ebb9b2d0e3244141e3e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isGPR64x8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>

</div>
</div>

### isImm() {#aea91f2a32c29a629c3d67afe5c31440b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImm ()</td>
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

<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isImmInRange() {#a0f6c1755e5ae566a87d87508d3cee9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int N, int M&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImmInRange ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isImmRange() {#a76154ce7fc1f5f0efbe6666cb8d6c67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImmRange ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a4a18544038561f8c08b8ea6d6da02784">isImmScaled</a> and <a href="#a2b9b954fffe0be9433ada4a9cc7fee9b">isUImmScaled</a>.</p>

</div>
</div>

### isImmScaled() {#a4a18544038561f8c08b8ea6d6da02784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Bits, int Scale, bool IsRange = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImmScaled (bool Signed)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#af39600298b97e7a4b4f8877f51edba9a">getFirstImmVal</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#a76154ce7fc1f5f0efbe6666cb8d6c67f">isImmRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>


<p>Referenced by <a href="#a97fe28e7c116a9a926e26133f5ee3adb">isSImmScaled</a> and <a href="#a2b9b954fffe0be9433ada4a9cc7fee9b">isUImmScaled</a>.</p>

</div>
</div>

### isImplicitlyTypedVectorList() {#a9c9f19db01e9020f9fda38bf694463be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RegKind VectorKind, unsigned NumRegs, bool IsConsecutive = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImplicitlyTypedVectorList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this a vector list with the type implicit (presumably attached to the instruction itself)?</p>

<p>Definition at line 1453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a>.</p>

</div>
</div>

### isLogicalImm() {#a9d689d56ccbeb5bad8afd84d615d31b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isLogicalImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a262431cccd14e6063eacc180130a5882">llvm::AArch64_AM::isLogicalImmediate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="#aa980e8ae2ed3b758a3d93a9e0a888a4f">isSVEPreferredLogicalImm</a>.</p>

</div>
</div>

### isLogicalShifter() {#aab2a97a552049bfe30c944b6dde3b6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isLogicalShifter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1634 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a2f11475361161d9ce95a2f7be74de342">llvm::AArch64_AM::ASR</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a6cf4eecc5d7b370b00cfb6608e4e9dea">isShifter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a7e1384a3b7d612a03b54d9c8f2071a04">llvm::AArch64_AM::LSR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1abb1fa5a6016bfee1580a7b989a454c9a">llvm::AArch64_AM::ROR</a>.</p>

</div>
</div>

### isLogicalVecHalfWordShifter() {#a2f1a3019908cfff5330263a2752a9d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isLogicalVecHalfWordShifter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1679 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a70566006f8429c9ceca4aadce19cc626">isLogicalVecShifter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>.</p>

</div>
</div>

### isLogicalVecShifter() {#a70566006f8429c9ceca4aadce19cc626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isLogicalVecShifter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a6cf4eecc5d7b370b00cfb6608e4e9dea">isShifter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>.</p>


<p>Referenced by <a href="#a2f1a3019908cfff5330263a2752a9d33">isLogicalVecHalfWordShifter</a>.</p>

</div>
</div>

### isLSLImm3Shift() {#aa6010873a7d304b002621c1caf466e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isLSLImm3Shift ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a1e240631b5dac6b7b4f7caab3e2abde6">isShiftExtend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>.</p>

</div>
</div>

### isMatrix() {#a0ee7b25fcfb704f1d60f03cc019c1f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMatrix ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ad81b99aea193e203aeb95e1c5bdba7f4">isMatrixRegOperand</a>.</p>

</div>
</div>

### isMatrixRegOperand() {#ad81b99aea193e203aeb95e1c5bdba7f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;MatrixKind Kind, unsigned EltSize, unsigned RegClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMatrixRegOperand ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a273f1e0056964b595836b6841da5d62e">getMatrixElementWidth</a>, <a href="#aa16ee56c2954762ecb13b4b909c89e4c">getMatrixKind</a>, <a href="#a8b6c9765bc0f705dbb376478576625b3">getMatrixReg</a>, <a href="#a0ee7b25fcfb704f1d60f03cc019c1f4d">isMatrix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>.</p>

</div>
</div>

### isMatrixTileList() {#aba7013ea61d621beb9dde0936079716c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMatrixTileList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ac75916f715b269b8c18090dcab1d50a2">getMatrixTileListRegMask</a>.</p>

</div>
</div>

### isMem() {#ae298b03ad92d819463618f443c401b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMem ()</td>
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

<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isMemWExtend() {#af9bc3c08d8b9f44b326ea7d10fa0b9d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMemWExtend ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ae4596bc58bb52249e577a5b3ac193766">isExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">llvm::AArch64_AM::SXTW</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d">llvm::AArch64_AM::UXTW</a>.</p>

</div>
</div>

### isMemXExtend() {#af1da8768651416a2ccadd7e59af0d003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMemXExtend ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ae4596bc58bb52249e577a5b3ac193766">isExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1ae2de16560eda6fb0ee38a2173c863ba4">llvm::AArch64_AM::SXTX</a>.</p>

</div>
</div>

### isMoveVecShifter() {#a6dbb9683c3cc8c356d44f3cd88623439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMoveVecShifter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1689 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a1e240631b5dac6b7b4f7caab3e2abde6">isShiftExtend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a5b297b24d84fef366a94098c36f07c3a">llvm::AArch64_AM::MSL</a>.</p>

</div>
</div>

### isMovImm32Shifter() {#a7cdecbf48af2c861d8f1acce127123a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMovImm32Shifter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a6cf4eecc5d7b370b00cfb6608e4e9dea">isShifter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>.</p>

</div>
</div>

### isMovImm64Shifter() {#ac6614d8eec367d62f580c299b237389e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMovImm64Shifter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a6cf4eecc5d7b370b00cfb6608e4e9dea">isShifter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>.</p>

</div>
</div>

### isMOVNMovAlias() {#a018eb3f34b1fe02b8d60532cf5713ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int RegWidth, int Shift&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMOVNMovAlias ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a178fae9db42f799d5a2c3c4b3819d8bb">llvm::AArch64_AM::isMOVNMovAlias</a>.</p>

</div>
</div>

### isMovWSymbol() {#a3802559d2c75d983cd9101cd12ac5c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMovWSymbol (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bf">AArch64MCExpr::VariantKind</a> &gt; AllowedModifiers)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a714bb267b4fc2935142836b944e9bef8">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::classifySymbolRef</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="#adc3fde429a245f53c871307e383e526a">isMovWSymbolG0</a>, <a href="#ad3c15231badddd02b4095368f9ca5641">isMovWSymbolG1</a>, <a href="#a1f70b77525355a42babc1c101bd55f8a">isMovWSymbolG2</a> and <a href="#a6a162468b3d99ecab971492c5500b8a2">isMovWSymbolG3</a>.</p>

</div>
</div>

### isMovWSymbolG0() {#adc3fde429a245f53c871307e383e526a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMovWSymbolG0 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a3802559d2c75d983cd9101cd12ac5c57">isMovWSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa35474485d868b25489fc57669a9c27f9">llvm::AArch64MCExpr::VK_ABS_G0</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa65e6d1b5482060081af43ab78352964d">llvm::AArch64MCExpr::VK_ABS_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa7eb9497609b61ca20e383022f9ab3290">llvm::AArch64MCExpr::VK_ABS_G0_S</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa752f95c69e8b43369d83833adb099345">llvm::AArch64MCExpr::VK_DTPREL_G0</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfab73ae607357b58d9d3de5256d5558284">llvm::AArch64MCExpr::VK_DTPREL_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa9c3e5cca2bdd09fc0ecb532f2c5d7e45">llvm::AArch64MCExpr::VK_GOTTPREL_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa8f3aaf6805e534003f15c7e878acdf32">llvm::AArch64MCExpr::VK_PREL_G0</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfab793dd2a7b912aeaae778108094a5689">llvm::AArch64MCExpr::VK_PREL_G0_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaeb8c93fb135d2775c869861178d11807">llvm::AArch64MCExpr::VK_TPREL_G0</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa6e1d58609fc75b55166830312b91d2df">llvm::AArch64MCExpr::VK_TPREL_G0_NC</a>.</p>

</div>
</div>

### isMovWSymbolG1() {#ad3c15231badddd02b4095368f9ca5641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMovWSymbolG1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a3802559d2c75d983cd9101cd12ac5c57">isMovWSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae40f238af3f6fe589641a720ab4f97a8">llvm::AArch64MCExpr::VK_ABS_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa1f931e50ae5f4c5f77e050447b2e3320">llvm::AArch64MCExpr::VK_ABS_G1_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa53f60806897246321227204c69d467c3">llvm::AArch64MCExpr::VK_ABS_G1_S</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa1ea6131fa4bc346a2285f73b1e3b2b88">llvm::AArch64MCExpr::VK_DTPREL_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa1ea81fd8999cf2538b39f1e012f4a9cc">llvm::AArch64MCExpr::VK_DTPREL_G1_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa818d75cf614986328128098bb46084ed">llvm::AArch64MCExpr::VK_GOTTPREL_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfab0d49b0ffa4753b61465eb29942f838c">llvm::AArch64MCExpr::VK_PREL_G1</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfadf42ca6f959ddac98d35254c0914af09">llvm::AArch64MCExpr::VK_PREL_G1_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa5027a58d31c5e57b7483970eaf6cd602">llvm::AArch64MCExpr::VK_TPREL_G1</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa11bfd951d2f6ec25329b879f8d428fa9">llvm::AArch64MCExpr::VK_TPREL_G1_NC</a>.</p>

</div>
</div>

### isMovWSymbolG2() {#a1f70b77525355a42babc1c101bd55f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMovWSymbolG2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a3802559d2c75d983cd9101cd12ac5c57">isMovWSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa284689a52a5f79b95b051a057c54fb1e">llvm::AArch64MCExpr::VK_ABS_G2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa1089df68239d0e46c2fba2190c4c0eb8">llvm::AArch64MCExpr::VK_ABS_G2_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa536c18c873600b1e2aba9d9f894e9213">llvm::AArch64MCExpr::VK_ABS_G2_S</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa8f5d53560d98ded247f3bc911c00260d">llvm::AArch64MCExpr::VK_DTPREL_G2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae308678726c12af491f9647e76f3f1b9">llvm::AArch64MCExpr::VK_PREL_G2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa432b91e82080f70cff564bc1f0db2b17">llvm::AArch64MCExpr::VK_PREL_G2_NC</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa4b1b25eea13543bbbe0d904a4776d430">llvm::AArch64MCExpr::VK_TPREL_G2</a>.</p>

</div>
</div>

### isMovWSymbolG3() {#a6a162468b3d99ecab971492c5500b8a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMovWSymbolG3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a3802559d2c75d983cd9101cd12ac5c57">isMovWSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa963191759d19cf8d90bc0c40435c8cb8">llvm::AArch64MCExpr::VK_ABS_G3</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa9a4ed17656f61247e51858d2f8d9203d">llvm::AArch64MCExpr::VK_PREL_G3</a>.</p>

</div>
</div>

### isMOVZMovAlias() {#a21f95622afbe879f8b6fab324bb71a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int RegWidth, int Shift&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMOVZMovAlias ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7a923906a7a2b0e53a9d71fc27c39210">llvm::AArch64_AM::isMOVZMovAlias</a>.</p>

</div>
</div>

### isMRSSystemRegister() {#a927364ec8999f2481c4e15389b2cc8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMRSSystemRegister ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a1adba96b3a79ec99156cee8455a4900b">isSysReg</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>

</div>
</div>

### isMSRSystemRegister() {#a845e6e739c47f4a01d42409a778e8851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMSRSystemRegister ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a1adba96b3a79ec99156cee8455a4900b">isSysReg</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>

</div>
</div>

### isNeonVectorReg() {#acfbd51eeaf0c3673cd8f29350209280f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isNeonVectorReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a83730a49d198ed8acdf9191509313ca2">anonymous{AArch64AsmParser.cpp}::NeonVector</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### isNeonVectorReg0to7() {#a22b52b9f1137ba53299e66263d422f51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isNeonVectorReg0to7 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a83730a49d198ed8acdf9191509313ca2">anonymous{AArch64AsmParser.cpp}::NeonVector</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### isNeonVectorRegLo() {#a3f46afc52463b826e5bfa8c7039bac0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isNeonVectorRegLo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a83730a49d198ed8acdf9191509313ca2">anonymous{AArch64AsmParser.cpp}::NeonVector</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### isPAuthPCRelLabel16Operand() {#a4f7622e49d7747dc8b2b9ee2f586a4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isPAuthPCRelLabel16Operand ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1752 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isPHint() {#a8b354e9615f1a0cc8a66ee6242ca3a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isPHint ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isPrefetch() {#a5b96fb57483cff5727815d80f80f103b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isPrefetch ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isPSBHint() {#a557de9464647a140b174bd3b86f0a649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isPSBHint ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isReg() {#a1214b42d8c13e2b88c7e7dec09dc768f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isReg ()</td>
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

<p>Definition at line 1237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isScalarReg() {#a2b6b9947463eebe84f16bdc7c39a26f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isScalarReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>


<p>Referenced by <a href="#a536cdad3a9f844e78b6003550707b214">addSyspXzrPairOperand</a>.</p>

</div>
</div>

### isShiftedImm() {#a05b315cc338b1b8eb7e3f9bf564e5e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isShiftedImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ab6d217a1a1a9c4c03289d555a4404aed">addImmWithOptionalShiftOperands</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a>, <a href="#ae40e6dd1a68e37d4348480f3c10858f8">isAddSubImm</a>, <a href="#aa1ceb39d04bc1c073d4dacdf7b5a6f04">isAddSubImmNeg</a>, <a href="#a23b2900efc3dc7b9ab2e4655fd3874ca">isSVEAddSubImm</a> and <a href="#a78d9bb4d126d1c4906dfee221ec64e5b">isSVECpyImm</a>.</p>

</div>
</div>

### isShifter() {#a6cf4eecc5d7b370b00cfb6608e4e9dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isShifter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1522 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a2f11475361161d9ce95a2f7be74de342">llvm::AArch64_AM::ASR</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#a1e240631b5dac6b7b4f7caab3e2abde6">isShiftExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a7e1384a3b7d612a03b54d9c8f2071a04">llvm::AArch64_AM::LSR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a5b297b24d84fef366a94098c36f07c3a">llvm::AArch64_AM::MSL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1abb1fa5a6016bfee1580a7b989a454c9a">llvm::AArch64_AM::ROR</a>.</p>


<p>Referenced by <a href="#ad672c4920253428db94773cb2be92dc1">isArithmeticShifter</a>, <a href="#aab2a97a552049bfe30c944b6dde3b6d5">isLogicalShifter</a>, <a href="#a70566006f8429c9ceca4aadce19cc626">isLogicalVecShifter</a>, <a href="#a7cdecbf48af2c861d8f1acce127123a5">isMovImm32Shifter</a> and <a href="#ac6614d8eec367d62f580c299b237389e">isMovImm64Shifter</a>.</p>

</div>
</div>

### isShiftExtend() {#a1e240631b5dac6b7b4f7caab3e2abde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isShiftExtend ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ae4596bc58bb52249e577a5b3ac193766">isExtend</a>, <a href="#aa6010873a7d304b002621c1caf466e89">isLSLImm3Shift</a>, <a href="#a6dbb9683c3cc8c356d44f3cd88623439">isMoveVecShifter</a> and <a href="#a6cf4eecc5d7b370b00cfb6608e4e9dea">isShifter</a>.</p>

</div>
</div>

### isSIMDImmType10() {#aa1892421b1a924f86a66c28974d47c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSIMDImmType10 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aacafb7aecc0ecc157dd1fbaac53bae38">llvm::AArch64_AM::isAdvSIMDModImmType10</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isSImm() {#a16f360ccfa1eb023fac00431ac79543b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="#a97fe28e7c116a9a926e26133f5ee3adb">isSImmScaled</a>.</p>


<p>Referenced by <a href="#a3fa25d9cd8faa372bf7e6c3fcb618997">isSImm9OffsetFB</a>.</p>

</div>
</div>

### isSImm9OffsetFB() {#a3fa25d9cd8faa372bf7e6c3fcb618997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Width&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSImm9OffsetFB ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1705 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a16f360ccfa1eb023fac00431ac79543b">isSImm</a> and <a href="#a82e2a376717221b4993b1fc95415bde9">isUImm12Offset</a>.</p>

</div>
</div>

### isSImmScaled() {#a97fe28e7c116a9a926e26133f5ee3adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Bits, int Scale&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSImmScaled ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="#a4a18544038561f8c08b8ea6d6da02784">isImmScaled</a>.</p>


<p>Referenced by <a href="#a16f360ccfa1eb023fac00431ac79543b">isSImm</a>.</p>

</div>
</div>

### isSVCR() {#a5b381a1d754f73924bf089e383b5345c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVCR ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="#a72c2f36b7a65bbf6b93f1da1faaeb0ed">SVCR</a>.</p>

</div>
</div>

### isSVEAddSubImm() {#a23b2900efc3dc7b9ab2e4655fd3874ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEAddSubImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#a05b315cc338b1b8eb7e3f9bf564e5e6b">isShiftedImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2ccd71fca66375c495f8c883988091b9">llvm::AArch64_AM::isSVEAddSubImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a> and <a href="#a173d50c9ec45e6ef19632f49986b2672">ShiftedImm</a>.</p>

</div>
</div>

### isSVECpyImm() {#a78d9bb4d126d1c4906dfee221ec64e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVECpyImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="#a83c5e95fb85aaef96207fc9e9ddfccc0">getShiftedVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="#a05b315cc338b1b8eb7e3f9bf564e5e6b">isShiftedImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a99509002d9fccdb280ff2c66af1505f9">llvm::AArch64_AM::isSVECpyImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a> and <a href="#a173d50c9ec45e6ef19632f49986b2672">ShiftedImm</a>.</p>


<p>Referenced by <a href="#aa980e8ae2ed3b758a3d93a9e0a888a4f">isSVEPreferredLogicalImm</a>.</p>

</div>
</div>

### isSVEDataVectorRegOfWidth() {#a6a8c1f03eb7bbfac873e12ecd63ee41a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int ElementWidth, unsigned Class&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEDataVectorRegOfWidth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#ad0a4a1525f0b03c1db7189d13e5dae79">isSVEVectorReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a6dd2423600dfa4e3e15b18c93adb39aa">anonymous{AArch64AsmParser.cpp}::SVEDataVector</a>.</p>


<p>Referenced by <a href="#abc43845557a2bbe9fe7f3612b197fe97">isSVEDataVectorRegWithShiftExtend</a>.</p>

</div>
</div>

### isSVEDataVectorRegWithShiftExtend() {#abc43845557a2bbe9fe7f3612b197fe97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int ElementWidth, unsigned Class, AArch64_AM::ShiftExtendType ShiftExtendTy, int ShiftWidth, bool ShiftWidthAlwaysSame&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEDataVectorRegWithShiftExtend ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ac5f9e1ccafa17c5328c20c4fef98e470">hasShiftExtendAmount</a>, <a href="#a6a8c1f03eb7bbfac873e12ecd63ee41a">isSVEDataVectorRegOfWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a13ed9069b0840f7eb3a47fce0878a5ad">llvm::AArch64_AM::SXTW</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a2620d8167a503c9942cc4afded7f830d">llvm::AArch64_AM::UXTW</a>.</p>

</div>
</div>

### isSVEPattern() {#af6ede1b5501f32283fb6084a02528b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEPattern ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>.</p>

</div>
</div>

### isSVEPredicateAsCounterReg() {#a658c552c0a2ffb525fdf9049ef7ff38c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Class&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEPredicateAsCounterReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a9ce9a80e57105c0d55c920f8732ae63c">anonymous{AArch64AsmParser.cpp}::SVEPredicateAsCounter</a>.</p>


<p>Referenced by <a href="#a504f15f35c5d8db3437e75dce512b5d4">isSVEPredicateAsCounterRegOfWidth</a> and <a href="#a71399ecd50196774ab996901b18c2170">isSVEPredicateOrPredicateAsCounterRegOfWidth</a>.</p>

</div>
</div>

### isSVEPredicateAsCounterRegOfWidth() {#a504f15f35c5d8db3437e75dce512b5d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int ElementWidth, unsigned Class&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEPredicateAsCounterRegOfWidth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a658c552c0a2ffb525fdf9049ef7ff38c">isSVEPredicateAsCounterReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a9ce9a80e57105c0d55c920f8732ae63c">anonymous{AArch64AsmParser.cpp}::SVEPredicateAsCounter</a>.</p>

</div>
</div>

### isSVEPredicateOrPredicateAsCounterRegOfWidth() {#a71399ecd50196774ab996901b18c2170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int ElementWidth, unsigned Class&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEPredicateOrPredicateAsCounterRegOfWidth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a658c552c0a2ffb525fdf9049ef7ff38c">isSVEPredicateAsCounterReg</a>, <a href="#a9e000099eb23f2a702495218265f3512">isSVEPredicateVectorRegOfWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a9ce9a80e57105c0d55c920f8732ae63c">anonymous{AArch64AsmParser.cpp}::SVEPredicateAsCounter</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a0409528c7a1e7ab49ebbb311a792fa29">anonymous{AArch64AsmParser.cpp}::SVEPredicateVector</a>.</p>

</div>
</div>

### isSVEPredicateVectorRegOfWidth() {#a9e000099eb23f2a702495218265f3512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int ElementWidth, unsigned Class&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEPredicateVectorRegOfWidth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#ad0a4a1525f0b03c1db7189d13e5dae79">isSVEVectorReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a0409528c7a1e7ab49ebbb311a792fa29">anonymous{AArch64AsmParser.cpp}::SVEPredicateVector</a>.</p>


<p>Referenced by <a href="#a71399ecd50196774ab996901b18c2170">isSVEPredicateOrPredicateAsCounterRegOfWidth</a>.</p>

</div>
</div>

### isSVEPreferredLogicalImm() {#aa980e8ae2ed3b758a3d93a9e0a888a4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEPreferredLogicalImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a9d689d56ccbeb5bad8afd84d615d31b7">isLogicalImm</a>, <a href="#a78d9bb4d126d1c4906dfee221ec64e5b">isSVECpyImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>.</p>

</div>
</div>

### isSVEVecLenSpecifier() {#a5781cadb65dde47dd3d4fa07c5021091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEVecLenSpecifier ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a>.</p>

</div>
</div>

### isSVEVectorReg() {#ad0a4a1525f0b03c1db7189d13e5dae79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Class&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSVEVectorReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a6dd2423600dfa4e3e15b18c93adb39aa">anonymous{AArch64AsmParser.cpp}::SVEDataVector</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a0409528c7a1e7ab49ebbb311a792fa29">anonymous{AArch64AsmParser.cpp}::SVEPredicateVector</a>.</p>


<p>Referenced by <a href="#a6a8c1f03eb7bbfac873e12ecd63ee41a">isSVEDataVectorRegOfWidth</a> and <a href="#a9e000099eb23f2a702495218265f3512">isSVEPredicateVectorRegOfWidth</a>.</p>

</div>
</div>

### isSymbolicUImm12Offset() {#af609eb8e37538160d693e8e47e1f87bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSymbolicUImm12Offset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a714bb267b4fc2935142836b944e9bef8">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::classifySymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae976f5dddffeb8a77e5ecc471343842d">llvm::AArch64MCExpr::VK_DTPREL_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa690cf2259632dd195b29cb7ad0cd16b7">llvm::AArch64MCExpr::VK_DTPREL_LO12_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa2f76c31f5c93ff69cd59e817abd85223">llvm::AArch64MCExpr::VK_GOT_AUTH_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa3e719e2fda5e6446235fedc1024897e">llvm::AArch64MCExpr::VK_GOT_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa5fbf97669aa58e6ffa919564aabc2f5f">llvm::AArch64MCExpr::VK_GOT_PAGE_LO15</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985afc40a65d8cb0da3855201ee24f549aa6">llvm::MCSymbolRefExpr::VK_GOTPAGEOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfad5dd2834fe1711d63b1b6c7ab4fdf5e1">llvm::AArch64MCExpr::VK_GOTTPREL_LO12_NC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfac273d7a8ebcef5784a4904ffe145aefe">llvm::AArch64MCExpr::VK_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa68dd5cbd2bf672acbe601e89ccf676a">llvm::MCSymbolRefExpr::VK_PAGEOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfad8bf44f54a45b38024a2cdc10226cb3a">llvm::AArch64MCExpr::VK_SECREL_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaee5e353993b28f25d23e1b76e1b295a2">llvm::AArch64MCExpr::VK_SECREL_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfacf90d92f6c5b8b5972b2631c72eb5dde">llvm::AArch64MCExpr::VK_TLSDESC_AUTH_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfae86e7fb84bad4ed1be1f5772229a8d58">llvm::AArch64MCExpr::VK_TLSDESC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985af0a99c543167803572c2fb1642f17010">llvm::MCSymbolRefExpr::VK_TLVPPAGEOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa69a04395c63763644a14a6a929075fb0">llvm::AArch64MCExpr::VK_TPREL_LO12</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa2d3ca49c7f86aedb741b49d223fce16">llvm::AArch64MCExpr::VK_TPREL_LO12_NC</a>.</p>


<p>Referenced by <a href="#a82e2a376717221b4993b1fc95415bde9">isUImm12Offset</a>.</p>

</div>
</div>

### isSysCR() {#a140a1f49fb8f0998628efd4cfb5a1cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSysCR ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isSyspXzrPair() {#a4d8a148bfce41fb17538cb3625b0612f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSyspXzrPair ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a9c97678587f4aabaf8237328391007d3">isGPR64</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### isSysReg() {#a1adba96b3a79ec99156cee8455a4900b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSysReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a927364ec8999f2481c4e15389b2cc8b2">isMRSSystemRegister</a>, <a href="#a845e6e739c47f4a01d42409a778e8851">isMSRSystemRegister</a>, <a href="#a1020b599fae66259f4fea308c1219d38">isSystemPStateFieldWithImm0_1</a> and <a href="#a883e4f7f94c6e62e7e0b9a0c31b6358f">isSystemPStateFieldWithImm0_15</a>.</p>

</div>
</div>

### isSystemPStateFieldWithImm0\_1() {#a1020b599fae66259f4fea308c1219d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSystemPStateFieldWithImm0_1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a1adba96b3a79ec99156cee8455a4900b">isSysReg</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>

</div>
</div>

### isSystemPStateFieldWithImm0\_15() {#a883e4f7f94c6e62e7e0b9a0c31b6358f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isSystemPStateFieldWithImm0_15 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a1adba96b3a79ec99156cee8455a4900b">isSysReg</a> and <a href="#a45eedf3715221e9fe42a351c5fb2aaff">SysReg</a>.</p>

</div>
</div>

### isToken() {#a8164483cb400880f28c00d1f1050d147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isToken ()</td>
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

<p>Definition at line 1511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isTokenEqual() {#a7240770a4389825ad34599244815758d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isTokenEqual (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="#a69c86c3f6d0cb218cb21fdff76b52061">getToken</a>.</p>

</div>
</div>

### isTokenSuffix() {#a214b786a70ead5ef3d4ce375a99571e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isTokenSuffix ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a60bb6fba3a328904a2c49fca0fff3908">Tok</a>.</p>

</div>
</div>

### isTypedVectorList() {#a62c3fc6bf060a795cb66bf5544af58d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RegKind VectorKind, unsigned NumRegs, unsigned NumElements, unsigned ElementWidth, unsigned Stride = 1&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isTypedVectorList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a>.</p>


<p>Referenced by <a href="#acd7238ce7f28b58aefe19170d4c9f934">isTypedVectorListMultiple</a> and <a href="#abbf2aa6a208882a12d8264f5c0e76e31">isTypedVectorListStrided</a>.</p>

</div>
</div>

### isTypedVectorListMultiple() {#acd7238ce7f28b58aefe19170d4c9f934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RegKind VectorKind, unsigned NumRegs, unsigned NumElements, unsigned ElementWidth, unsigned RegClass&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isTypedVectorListMultiple ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a62c3fc6bf060a795cb66bf5544af58d0">isTypedVectorList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a> and <a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a>.</p>

</div>
</div>

### isTypedVectorListStrided() {#abbf2aa6a208882a12d8264f5c0e76e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;RegKind VectorKind, unsigned NumRegs, unsigned Stride, unsigned ElementWidth&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isTypedVectorListStrided ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a62c3fc6bf060a795cb66bf5544af58d0">isTypedVectorList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a> and <a href="#a3b0b68a7478f7d73b34b73451edb3d05">VectorList</a>.</p>

</div>
</div>

### isUImm12Offset() {#a82e2a376717221b4993b1fc95415bde9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Scale&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isUImm12Offset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="#af609eb8e37538160d693e8e47e1f87bd">isSymbolicUImm12Offset</a>.</p>


<p>Referenced by <a href="#a3fa25d9cd8faa372bf7e6c3fcb618997">isSImm9OffsetFB</a>.</p>

</div>
</div>

### isUImm6() {#a36d0b74dbf90ea3967907f05a88b06a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isUImm6 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#a89859d5c7657c00986cd1f33cbcdb8ad">llvm::MCConstantExpr::getValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isUImmScaled() {#a2b9b954fffe0be9433ada4a9cc7fee9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Bits, int Scale, int Offset = 0, bool IsRange = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isUImmScaled ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#af39600298b97e7a4b4f8877f51edba9a">getFirstImmVal</a>, <a href="#afb40063c81db44668a2d42579dd1d899">getLastImmVal</a>, <a href="#a76154ce7fc1f5f0efbe6666cb8d6c67f">isImmRange</a>, <a href="#a4a18544038561f8c08b8ea6d6da02784">isImmScaled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### isVectorIndex() {#a0e1bd40daf5e75a7ac655914e7499238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Min, int Max&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticPredicate anonymous{AArch64AsmParser.cpp}::AArch64Operand::isVectorIndex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251ea6da89265a9a8b0b28eb4946bb2ec0c6d">llvm::Match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eade65cb7e6c9f9bfeaf3e82800465892d">llvm::NearMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a313a633eb3049b90e931206183e1251eac8b77721c677e0429241a9250972122d">llvm::NoMatch</a> and <a href="#a41ba073805f2c16be2635d9364688fa5">VectorIndex</a>.</p>

</div>
</div>

### isVectorList() {#a63f514cef6cf063a09ae1b48a1ac4c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isVectorList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### isWSeqPair() {#adf6802bde80df76dc31c984f5f7ce063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isWSeqPair ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>

</div>
</div>

### isXSeqPair() {#a9684e332b7d1b66ab9b6c7124cf81ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64AsmParser.cpp}::AArch64Operand::isXSeqPair ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957af60357a8d17e45793298323f1b372a74">anonymous{AArch64AsmParser.cpp}::Scalar</a>.</p>

</div>
</div>

### print() {#a763e5d73a932a30d95c888b81f45a0c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64Operand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 2304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="#a51269ef5293d0098e7191bdb7ff580c9">getBarrier</a>, <a href="#a91f4c80dd445035027357cb39b58ce38">getBarrierName</a>, <a href="#ad76657580467f9c30a243c70d77a1834">getBTIHintName</a>, <a href="#a47eab7aa29bf67fd06806c3d7773e80a">getCondCode</a>, <a href="#af39600298b97e7a4b4f8877f51edba9a">getFirstImmVal</a>, <a href="#abe43ce294e9f0705c6f51289b1057d16">getFPImm</a>, <a href="#a06a98536dd501b77d6c855f7031a25e8">getFPImmIsExact</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="#afb40063c81db44668a2d42579dd1d899">getLastImmVal</a>, <a href="#a8b6c9765bc0f705dbb376478576625b3">getMatrixReg</a>, <a href="#ac75916f715b269b8c18090dcab1d50a2">getMatrixTileListRegMask</a>, <a href="#afc81c5d305908130290ef7aec6713368">getPHintName</a>, <a href="#a9b07c78cf7e27b8cf4a2e73395d47588">getPrefetch</a>, <a href="#adb7a4223e386379eb5fdc9d7ef46322f">getPrefetchName</a>, <a href="#aab357d8a823ad62eedc521a7f28bf68c">getPSBHintName</a>, <a href="#a7fea0718404532d427bb085c3d096eba">getReg</a>, <a href="#a95653df7fe73ba4cac906726630b7b82">getShiftedImmShift</a>, <a href="#abe33538658ff5ed08e6c4aa63e597f9d">getShiftedImmVal</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a8a2bf23de615e193f526a0a23c304711">llvm::AArch64_AM::getShiftExtendName</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a22f623563f43de6d1aabcdfa9d341031">llvm::AArch64_AM::getShiftValue</a>, <a href="#ab41603fd7c0667cb139207752e90036d">getSVCR</a>, <a href="#a0372e03254511a04907d691d623a1ab9">getSysCR</a>, <a href="#ad1c8a2eff9a3bbb47486f39a7a256340">getSysReg</a>, <a href="#a69c86c3f6d0cb218cb21fdff76b52061">getToken</a>, <a href="#a73c5be75abb0824d924de7bbb051b4be">getVectorIndex</a>, <a href="#aa773f3fcc176fc95d3c7a11df57e2848">getVectorListCount</a>, <a href="#a347e0dad95df4d701ccef02e0e69a891">getVectorListStart</a>, <a href="#aadfb2ce8425322833201803c3dadd4aa">getVectorListStride</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="#ac5f9e1ccafa17c5328c20c4fef98e470">hasShiftExtendAmount</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Barrier {#aaa071bb32c71be50385b1ce5ad9201c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct BarrierOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::Barrier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a51269ef5293d0098e7191bdb7ff580c9">getBarrier</a>, <a href="#a91f4c80dd445035027357cb39b58ce38">getBarrierName</a> and <a href="#a7d715a0837669084b837c5f8d35100e5">getBarriernXSModifier</a>.</p>

</div>
</div>

### BTIHint {#a401e3a0e1e293e67ea9952558fb9edbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct BTIHintOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::BTIHint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#ae064fea0649422b53e39309580f50784">getBTIHint</a> and <a href="#ad76657580467f9c30a243c70d77a1834">getBTIHintName</a>.</p>

</div>
</div>

### CondCode {#a5ef042e56aeccc2de3ef8d0681e16de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct CondCodeOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::CondCode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a> and <a href="#a47eab7aa29bf67fd06806c3d7773e80a">getCondCode</a>.</p>

</div>
</div>

### FPImm {#a007c5108691de8314bda7d4e918e6be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct FPImmOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::FPImm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#abe43ce294e9f0705c6f51289b1057d16">getFPImm</a> and <a href="#a06a98536dd501b77d6c855f7031a25e8">getFPImmIsExact</a>.</p>

</div>
</div>

### Imm {#ada202c1d243056ec19cb505fa77ad18b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ImmOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a12ebb7021420c49a1338058e4db7f435">addExtend64Operands</a>, <a href="#a8a2b0c34d3cfaf2fa1561bfaf6182700">addExtendOperands</a>, <a href="#aa032e057f6912df64dddaffa3eaadf91">addLSLImm3ShifterOperands</a>, <a href="#ad007797dfd6b5c922a9818fd215aebd0">addShifterOperands</a>, <a href="#a5f596578202f6176f0a0d90fb310c1c2">getImm</a>, <a href="#a80247423cff6ce10b85e83fe46850605">isAdrLabel</a> and <a href="#ac4bea02bcb8b770deb2d6ea439c3f642">isAdrpLabel</a>.</p>

</div>
</div>

### ImmRange {#aa6b973934d0703fadc85f6e179814f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ImmRangeOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::ImmRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#af39600298b97e7a4b4f8877f51edba9a">getFirstImmVal</a> and <a href="#afb40063c81db44668a2d42579dd1d899">getLastImmVal</a>.</p>

</div>
</div>

### MatrixReg {#ae72f955625b09945025a13deb0635690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct MatrixRegOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::MatrixReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a273f1e0056964b595836b6841da5d62e">getMatrixElementWidth</a>, <a href="#aa16ee56c2954762ecb13b4b909c89e4c">getMatrixKind</a> and <a href="#a8b6c9765bc0f705dbb376478576625b3">getMatrixReg</a>.</p>

</div>
</div>

### MatrixTileList {#a590f01c7cbd3ec2afbe9c4fca46fbb4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct MatrixTileListOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::MatrixTileList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a> and <a href="#ac75916f715b269b8c18090dcab1d50a2">getMatrixTileListRegMask</a>.</p>

</div>
</div>

### PHint {#ade03d07197bb5b8ccaab62ec581da32f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct PHintOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::PHint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a5fd267b7333794825dbcbe73772833b2">getPHint</a> and <a href="#afc81c5d305908130290ef7aec6713368">getPHintName</a>.</p>

</div>
</div>

### Prefetch {#ab9b0f1bfbee3723b641f53759139f019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct PrefetchOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::Prefetch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a9b07c78cf7e27b8cf4a2e73395d47588">getPrefetch</a> and <a href="#adb7a4223e386379eb5fdc9d7ef46322f">getPrefetchName</a>.</p>

</div>
</div>

### PSBHint {#a0ac5ed90c079ad32f0a8e7f33a0159cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct PSBHintOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::PSBHint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a3fc9ae60ad902441966be44a7aaa4aa3">getPSBHint</a> and <a href="#aab357d8a823ad62eedc521a7f28bf68c">getPSBHintName</a>.</p>

</div>
</div>

### Reg {#a90ad0e42668730c0fa677d76d1940e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct RegOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#ac4f56500894c6c3ca92c54b569cc42a7">addGPR32as64Operands</a>, <a href="#ac45d96b1d1611280239c5f5ec90e1d22">addGPR64as32Operands</a>, <a href="#a5f2b9dd674ec50e06b69b98a88e00317">addPPRorPNRRegOperands</a>, <a href="#a536cdad3a9f844e78b6003550707b214">addSyspXzrPairOperand</a>, <a href="#ab92b093e430b26d0fe06b8365fc1ebd8">ComputeRegsForAlias</a>, <a href="#a7fea0718404532d427bb085c3d096eba">getReg</a>, <a href="#a55c102f52588775a1538fcb2b716a77f">getRegEqualityTy</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a>, <a href="#ac5f9e1ccafa17c5328c20c4fef98e470">hasShiftExtendAmount</a>, <a href="#a50f8a02f56b23d90871849510ddc3696">isFPRasZPR</a>, <a href="#a2b507a511fbcaafb076607adf8f5a26b">isGPR32as64</a>, <a href="#a9c97678587f4aabaf8237328391007d3">isGPR64</a>, <a href="#a177e778238e7f752fcff2460443afb39">isGPR64as32</a>, <a href="#a16d3b435ab22364600eb3af46fec4b29">isGPR64WithShiftExtend</a>, <a href="#a78533c925280ebb9b2d0e3244141e3e7">isGPR64x8</a>, <a href="#acfbd51eeaf0c3673cd8f29350209280f">isNeonVectorReg</a>, <a href="#a22b52b9f1137ba53299e66263d422f51">isNeonVectorReg0to7</a>, <a href="#a3f46afc52463b826e5bfa8c7039bac0d">isNeonVectorRegLo</a>, <a href="#a2b6b9947463eebe84f16bdc7c39a26f0">isScalarReg</a>, <a href="#a6a8c1f03eb7bbfac873e12ecd63ee41a">isSVEDataVectorRegOfWidth</a>, <a href="#a658c552c0a2ffb525fdf9049ef7ff38c">isSVEPredicateAsCounterReg</a>, <a href="#a504f15f35c5d8db3437e75dce512b5d4">isSVEPredicateAsCounterRegOfWidth</a>, <a href="#a71399ecd50196774ab996901b18c2170">isSVEPredicateOrPredicateAsCounterRegOfWidth</a>, <a href="#a9e000099eb23f2a702495218265f3512">isSVEPredicateVectorRegOfWidth</a>, <a href="#ad0a4a1525f0b03c1db7189d13e5dae79">isSVEVectorReg</a>, <a href="#a4d8a148bfce41fb17538cb3625b0612f">isSyspXzrPair</a>, <a href="#adf6802bde80df76dc31c984f5f7ce063">isWSeqPair</a>, <a href="#a9684e332b7d1b66ab9b6c7124cf81ba7">isXSeqPair</a> and <a href="#a763e5d73a932a30d95c888b81f45a0c3">print</a>.</p>

</div>
</div>

### ShiftedImm {#a173d50c9ec45e6ef19632f49986b2672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ShiftedImmOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::ShiftedImm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a95653df7fe73ba4cac906726630b7b82">getShiftedImmShift</a>, <a href="#abe33538658ff5ed08e6c4aa63e597f9d">getShiftedImmVal</a>, <a href="#ae40e6dd1a68e37d4348480f3c10858f8">isAddSubImm</a>, <a href="#a23b2900efc3dc7b9ab2e4655fd3874ca">isSVEAddSubImm</a> and <a href="#a78d9bb4d126d1c4906dfee221ec64e5b">isSVECpyImm</a>.</p>

</div>
</div>

### ShiftExtend {#aa471f43252f2060615bada15e9a9a14d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ShiftExtendOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::ShiftExtend</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#acf520862ca47f73eff607fa5d2d189eb">getShiftExtendAmount</a>, <a href="#a61664d5453b445203df60352a2557912">getShiftExtendType</a> and <a href="#ac5f9e1ccafa17c5328c20c4fef98e470">hasShiftExtendAmount</a>.</p>

</div>
</div>

### SVCR {#a72c2f36b7a65bbf6b93f1da1faaeb0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct SVCROp anonymous{AArch64AsmParser.cpp}::AArch64Operand::SVCR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#aec0f3af336e424eb47c2d849c53a9c99">addSVCROperands</a>, <a href="#ab41603fd7c0667cb139207752e90036d">getSVCR</a> and <a href="#a5b381a1d754f73924bf089e383b5345c">isSVCR</a>.</p>

</div>
</div>

### SysCRImm {#a7bc173b2bba5c1cf36d6376ca304d6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct SysCRImmOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::SysCRImm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a> and <a href="#a0372e03254511a04907d691d623a1ab9">getSysCR</a>.</p>

</div>
</div>

### SysReg {#a45eedf3715221e9fe42a351c5fb2aaff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct SysRegOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::SysReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a4beaf9b78d7eb225552cd94b0149b024">addMRSSystemRegisterOperands</a>, <a href="#a1c8b498e080d62622a43e79e74556aa3">addMSRSystemRegisterOperands</a>, <a href="#a58b5e0864f1dbb517a90f7e7a92946f5">addSystemPStateFieldWithImm0_15Operands</a>, <a href="#a941d8c4c599c4ae4ed4da18d83b17b72">addSystemPStateFieldWithImm0_1Operands</a>, <a href="#ad1c8a2eff9a3bbb47486f39a7a256340">getSysReg</a>, <a href="#a927364ec8999f2481c4e15389b2cc8b2">isMRSSystemRegister</a>, <a href="#a845e6e739c47f4a01d42409a778e8851">isMSRSystemRegister</a>, <a href="#a1020b599fae66259f4fea308c1219d38">isSystemPStateFieldWithImm0_1</a> and <a href="#a883e4f7f94c6e62e7e0b9a0c31b6358f">isSystemPStateFieldWithImm0_15</a>.</p>

</div>
</div>

### Tok {#a60bb6fba3a328904a2c49fca0fff3908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct TokOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a69c86c3f6d0cb218cb21fdff76b52061">getToken</a> and <a href="#a214b786a70ead5ef3d4ce375a99571e2">isTokenSuffix</a>.</p>

</div>
</div>

### VectorIndex {#a41ba073805f2c16be2635d9364688fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct VectorIndexOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::VectorIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#a73c5be75abb0824d924de7bbb051b4be">getVectorIndex</a> and <a href="#a0e1bd40daf5e75a7ac655914e7499238">isVectorIndex</a>.</p>

</div>
</div>

### VectorList {#a3b0b68a7478f7d73b34b73451edb3d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct VectorListOp anonymous{AArch64AsmParser.cpp}::AArch64Operand::VectorList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a2164d8c44abd99cb1354a75459eeb7dc">AArch64Operand</a>, <a href="#aa773f3fcc176fc95d3c7a11df57e2848">getVectorListCount</a>, <a href="#a347e0dad95df4d701ccef02e0e69a891">getVectorListStart</a>, <a href="#aadfb2ce8425322833201803c3dadd4aa">getVectorListStride</a>, <a href="#a9c9f19db01e9020f9fda38bf694463be">isImplicitlyTypedVectorList</a>, <a href="#a62c3fc6bf060a795cb66bf5544af58d0">isTypedVectorList</a>, <a href="#acd7238ce7f28b58aefe19170d4c9f934">isTypedVectorListMultiple</a> and <a href="#abbf2aa6a208882a12d8264f5c0e76e31">isTypedVectorListStrided</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#af3110f2c44bd232d1c81d76cc2ee34dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{AArch64AsmParser.cpp}::AArch64Operand anonymous{AArch64AsmParser.cpp}::AArch64Operand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### Ctx {#afd33780ddbefa933cd4face7895549cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; anonymous{AArch64AsmParser.cpp}::AArch64Operand::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### EndLoc {#a59212f5d499ab6c4960c10a71663e5b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AArch64AsmParser.cpp}::AArch64Operand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### Kind {#a0761d4efa262dd3c3f91a1884297c0a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AArch64AsmParser.cpp}::AArch64Operand::KindTy anonymous{AArch64AsmParser.cpp}::AArch64Operand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### StartLoc {#af3fb02a75f6688ee3a080319768aa6e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AArch64AsmParser.cpp}::AArch64Operand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### ComputeRegsForAlias() {#ab92b093e430b26d0fe06b8365fc1ebd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64AsmParser.cpp}::AArch64Operand::ComputeRegsForAlias (unsigned Reg, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; unsigned, 8 &gt; &amp; OutRegs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned ElementWidth)</td>
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



<p>Definition at line 2386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a> and <a href="#a90ad0e42668730c0fa677d76d1940e7d">Reg</a>.</p>

</div>
</div>

### CreateBarrier() {#a094dc88f2420640fa11bdef5527e7974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateBarrier (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, bool HasnXSModifier)</td>
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



<p>Definition at line 2467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateBTIHint() {#a426a1e25f5aee438dd5c055157695761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateBTIHint (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateCondCode() {#acac7110ce867b04e527060890c1da67c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateCondCode (<a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a> Code, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>.</p>

</div>
</div>

### CreateFPImm() {#a830996c6ee01a4fc50c18055a48a02a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateFPImm (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> Val, bool IsExact, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>.</p>

</div>
</div>

### CreateImm() {#a8877c1117570555c9ce5a0bf965e8a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a>.</p>

</div>
</div>

### CreateImmRange() {#ad0f5000e71169f8618f53309a0039b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateImmRange (unsigned First, unsigned Last, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>

</div>
</div>

### CreateMatrixRegister() {#adfa35c4eacc80abc11a98a64511331a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateMatrixRegister (unsigned RegNum, unsigned ElementWidth, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#ae85d8088eed863a1562f8d66049518a1">MatrixKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateMatrixTileList() {#a37d4237cdecde8dee7028b1aad03c5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateMatrixTileList (unsigned RegMask, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreatePHintInst() {#a101b4e6a4d46db6b024269607e4d7e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreatePHintInst (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreatePrefetch() {#a21ed4fe3bfe1eb8afbb0a987d7f1a69c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreatePrefetch (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>.</p>

</div>
</div>

### CreatePSBHint() {#ae5f40f983ca2184621ac68b3c043e5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreatePSBHint (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateReg() {#ab7a28dcef468d7f382405644a61ebdb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateReg (unsigned RegNum, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957">RegKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#adf99bb1304f6eacbd9d3efdc3aa43bfc">RegConstraintEqualityTy</a> EqTy=<a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#adf99bb1304f6eacbd9d3efdc3aa43bfcac7b97e13da2cc927a41c077fc4c7e39d">RegConstraintEqualityTy::EqualsReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a> ExtTy=AArch64_AM::LSL, unsigned ShiftAmount=0, unsigned HasExplicitAmount=false)</td>
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



<p>Definition at line 2318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#adf99bb1304f6eacbd9d3efdc3aa43bfcac7b97e13da2cc927a41c077fc4c7e39d">anonymous{AArch64AsmParser.cpp}::EqualsReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>.</p>


<p>Referenced by <a href="#a90ed7e81802b458392ce9f886b11a514">CreateVectorReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a72482e46711748fee7ce49e1d66002de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseGPROperand</a>.</p>

</div>
</div>

### CreateShiftedImm() {#a4b60185b9fe801fec888a33a13abd6a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateShiftedImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, unsigned ShiftAmount, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateShiftExtend() {#aaf837ce33cf1cae1b786722ae02f4388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateShiftExtend (<a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a> ShOp, unsigned Val, bool HasExplicitAmount, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2581 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateSVCR() {#aa6830b8929f4c1f0f70df41b11e41a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateSVCR (uint32_t PStateField, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateSysCR() {#a3dba4834c00b0a7fbceacb5ab9b48750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateSysCR (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateSysReg() {#a02115a580903fb8d978b48da6a948add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateSysReg (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, uint32_t MRSReg, uint32_t MSRReg, uint32_t PStateField, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateToken() {#a9716ea33305039a90a7740e0096e0a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, bool IsSuffix=false)</td>
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



<p>Definition at line 2307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aef98635d49b1c38ba8b291b28df6a62d">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEPredicateVector</a>.</p>

</div>
</div>

### CreateVectorIndex() {#a961cc170babf61f916a4976b7d970481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateVectorIndex (int Idx, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>

</div>
</div>

### CreateVectorList() {#a77f33fa8dea06aa9e477c99e0ea87f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateVectorList (unsigned RegNum, unsigned Count, unsigned Stride, unsigned NumElements, unsigned ElementWidth, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957">RegKind</a> RegisterKind, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 2353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#ac039137a2de44626abac897fe2382ef7">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseVectorList</a>.</p>

</div>
</div>

### CreateVectorReg() {#a90ed7e81802b458392ce9f886b11a514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AArch64Operand &gt; anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateVectorReg (unsigned RegNum, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957">RegKind</a> Kind, unsigned ElementWidth, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1">AArch64_AM::ShiftExtendType</a> ExtTy=AArch64_AM::LSL, unsigned ShiftAmount=0, unsigned HasExplicitAmount=false)</td>
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



<p>Definition at line 2337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab7a28dcef468d7f382405644a61ebdb6">CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#adf99bb1304f6eacbd9d3efdc3aa43bfcac7b97e13da2cc927a41c077fc4c7e39d">anonymous{AArch64AsmParser.cpp}::EqualsReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a83730a49d198ed8acdf9191509313ca2">anonymous{AArch64AsmParser.cpp}::NeonVector</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a6dd2423600dfa4e3e15b18c93adb39aa">anonymous{AArch64AsmParser.cpp}::SVEDataVector</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a9ce9a80e57105c0d55c920f8732ae63c">anonymous{AArch64AsmParser.cpp}::SVEPredicateAsCounter</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmparser-cpp-/#afecbf44fe4e0f0e4e4294a38ed025957a0409528c7a1e7ab49ebbb311a792fa29">anonymous{AArch64AsmParser.cpp}::SVEPredicateVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aef98635d49b1c38ba8b291b28df6a62d">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEPredicateVector</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp">AArch64AsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
