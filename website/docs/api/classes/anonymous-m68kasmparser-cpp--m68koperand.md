---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-m68kasmparser-cpp-/m68koperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `M68kOperand` Class

<p>An parsed <a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> assembly operand. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{M68kAsmParser.cpp}::M68kOperand { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> <a href="#a747e9913aeb4463b8abb97ea4caf0012">Base</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#aea20267cd188b8838de13e814aa3ed73">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcadf46711e9b4a58af7334376820148">M68kOperand</a> (KindTy Kind, SMLoc Start, SMLoc End)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7890c0dabd5a30c051cfe7946e18333f">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#a7890c0dabd5a30c051cfe7946e18333f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5cb3b8a574ab064c05602c73a95b135">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#ac5cb3b8a574ab064c05602c73a95b135">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51e09477144479de5e681236a2d0597c">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a51e09477144479de5e681236a2d0597c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad332ccd15c37a1ec43ab534796d321cb">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#ad332ccd15c37a1ec43ab534796d321cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5f8cb267b1652470dac931a81b9439">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#acf5f8cb267b1652470dac931a81b9439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad355c84be7fb2addbe5af81abb643d69">isAReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e034c80e4d87f0b999ffc01efa6acfc">isDReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96abbf8cdda0c2a93959d4e02f650209">isFPDReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9801a59a9613c4d188937207f2b80d46">isFPCReg</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e1e8f00b7416eeb61f28746f8670e5">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e9b31563dafd04ae8a3f4c1114e8f75">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6829f1a9ba3421b36ffe3bb448aaf3">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#abe6829f1a9ba3421b36ffe3bb448aaf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9360e5ec499a9c72060b083fbb2457ef">getToken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2747f6a5c239eef0d5d388e14188c76">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#ac2747f6a5c239eef0d5d388e14188c76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3467f0da9b2fdeb58a8078f5fb66e1c9">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac84738583081af3cc607f4d9ba29eeeb">isTrapImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef67029c53526e93fdbb13e9213bbea8">isBkptImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad22b8b6e14a6adcfc345b6d76f99b1e9">isMoveMask</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd23b62012f429a2e2edb2cb30c21b7">addMoveMaskOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594a6135384e308b91dd5e4171f10c66">isAddr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50708183c7ca4bd45fea5d1519cb8f75">isAddr8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedb890be079e1bb3213b4c0368571a0a">isAddr16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb98cc3ebac54fb3d45c8e9adf3e9b67">isAddr32</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6237dab111d9b5ff6d9d9df8f71807ea">addAddrOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaee3dab6f65cc3086575cdca6d8aed5">isARI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9678d5d40dc29d922920d97fe2e108">addARIOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf28d1dda0fa56a54f6a70527efecda2">isARID</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5767e266948d2da6a968bed7c234af">addARIDOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a5e4fcc5bc9cda0f46d052c220ff0b">isARII</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b36bcd58d06ed763e3ff606ef787d61">addARIIOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec19c567b3fae8ea0e67d96c9c133d5d">isARIPD</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa408301e2671cf7040584011da1ca4ee">addARIPDOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacacc5c46caece3094774a5724ae2f09">isARIPI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6d1110d5731551b614fc041a5e100e">addARIPIOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e22fc9af57a3017440ab00bd3f80ac">isPCD</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81edd91f1a089308e078a5c86ca07ae4">addPCDOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc971668b7bcfe8d2cc71043333842b7">isPCI</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5faf5d7c3df5946555e8a6b9e76c33">addPCIOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a606865327a3998227d8a11f8474bf034">isAddrN</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a606865327a3998227d8a11f8474bf034">isAddrN</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af92ccabc890167df67e028907fe972">Token</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade23fc6f8270db40ec2c7a5aaca34804">Expr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop">M68kMemOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">KindTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c4c3c614ae604016e971553799e815">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20924bd510c83c73733ace696241d9c">Start</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b52e26e8926e2eea04d5c8f595a6dc">End</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{M68kAsmParser.cpp}<a href="#abcadf46711e9b4a58af7334376820148">::M68kOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803c8a4d15f1bf2685a4e95b1e9019dd"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e27ec9bcfe6b34b7270dc44cc0cc486">addExpr</a> (MCInst &amp;Inst, const MCExpr *Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand">M68kOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49fae0d82f184f89de3cc68f0d55cb5">createMemOp</a> (M68kMemOp MemOp, SMLoc Start, SMLoc End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand">M68kOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e5a43093388b60bd2f22db298db003">createToken</a> (StringRef Token, SMLoc Start, SMLoc End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand">M68kOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141f1c9e336dc819d9aee29a20f589cb">createImm</a> (const MCExpr *Expr, SMLoc Start, SMLoc End)</td>
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

<p>An parsed <a href="/web-llvm/docs/api/namespaces/llvm/m68k">M68k</a> assembly operand.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#a747e9913aeb4463b8abb97ea4caf0012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef MCParsedAsmOperand anonymous{M68kAsmParser.cpp}::M68kOperand::Base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### KindTy {#aea20267cd188b8838de13e814aa3ed73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{M68kAsmParser.cpp}::M68kOperand::KindTy </td>
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
<td class="doxyEnumItemName">Invalid<a id="aea20267cd188b8838de13e814aa3ed73a4bbb8f967da6d1a610596d7257179c2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Token<a id="aea20267cd188b8838de13e814aa3ed73a459a6f79ad9b13cbcb5f692d2cc7a94d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm<a id="aea20267cd188b8838de13e814aa3ed73ada9470e1aa5be1858e667318254dcb4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemOp<a id="aea20267cd188b8838de13e814aa3ed73a33d2873b27c32fae6c504cf50d742381"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### M68kOperand() {#abcadf46711e9b4a58af7334376820148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{M68kAsmParser.cpp}::M68kOperand::M68kOperand (KindTy Kind, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAddrOperands() {#a6237dab111d9b5ff6d9d9df8f71807ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addAddrOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#a6e27ec9bcfe6b34b7270dc44cc0cc486">addExpr</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addARIDOperands() {#a0e5767e266948d2da6a968bed7c234af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addARIDOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#a6e27ec9bcfe6b34b7270dc44cc0cc486">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addARIIOperands() {#a8b36bcd58d06ed763e3ff606ef787d61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addARIIOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#a6e27ec9bcfe6b34b7270dc44cc0cc486">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addARIOperands() {#aef9678d5d40dc29d922920d97fe2e108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addARIOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addARIPDOperands() {#aa408301e2671cf7040584011da1ca4ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addARIPDOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addARIPIOperands() {#a2a6d1110d5731551b614fc041a5e100e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addARIPIOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmOperands() {#a3467f0da9b2fdeb58a8078f5fb66e1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#a6e27ec9bcfe6b34b7270dc44cc0cc486">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ade23fc6f8270db40ec2c7a5aaca34804">Expr</a>, <a href="#ac2747f6a5c239eef0d5d388e14188c76">isImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMoveMaskOperands() {#a9cd23b62012f429a2e2edb2cb30c21b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addMoveMaskOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp/#aa488184778f95826dfd1bc1807a7480d">getRegisterIndex</a>, <a href="#ad22b8b6e14a6adcfc345b6d76f99b1e9">isMoveMask</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a3791fc9668cfd0e7e10650add3cacf6d">anonymous{M68kAsmParser.cpp}::M68kMemOp::Reg</a>.</p>

</div>
</div>

### addPCDOperands() {#a81edd91f1a089308e078a5c86ca07ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addPCDOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#a6e27ec9bcfe6b34b7270dc44cc0cc486">addExpr</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addPCIOperands() {#afc5faf5d7c3df5946555e8a6b9e76c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addPCIOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#a6e27ec9bcfe6b34b7270dc44cc0cc486">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#a0e9b31563dafd04ae8a3f4c1114e8f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a28e1e8f00b7416eeb61f28746f8670e5">getReg</a>, <a href="#acf5f8cb267b1652470dac931a81b9439">isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getEndLoc() {#ac5cb3b8a574ab064c05602c73a95b135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{M68kAsmParser.cpp}::M68kOperand::getEndLoc ()</td>
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

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### getReg() {#a28e1e8f00b7416eeb61f28746f8670e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister M68kOperand::getReg ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acf5f8cb267b1652470dac931a81b9439">isReg</a> and <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a>.</p>


<p>Referenced by <a href="#a0e9b31563dafd04ae8a3f4c1114e8f75">addRegOperands</a>, <a href="#ad355c84be7fb2addbe5af81abb643d69">isAReg</a>, <a href="#a0e034c80e4d87f0b999ffc01efa6acfc">isDReg</a>, <a href="#a9801a59a9613c4d188937207f2b80d46">isFPCReg</a>, <a href="#a96abbf8cdda0c2a93959d4e02f650209">isFPDReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68kasmparser/#ae883c185ab1d52bf467bcfb57f6793ad">anonymous{M68kAsmParser.cpp}::M68kAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### getStartLoc() {#a7890c0dabd5a30c051cfe7946e18333f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{M68kAsmParser.cpp}::M68kOperand::getStartLoc ()</td>
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

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### getToken() {#a9360e5ec499a9c72060b083fbb2457ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef M68kOperand::getToken ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abe6829f1a9ba3421b36ffe3bb448aaf3">isToken</a> and <a href="#a6af92ccabc890167df67e028907fe972">Token</a>.</p>

</div>
</div>

### isAddr() {#a594a6135384e308b91dd5e4171f10c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isAddr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a3649a5e29ad648f3cfe3eea1a93d2f78">anonymous{M68kAsmParser.cpp}::M68kMemOp::Addr</a>, <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a> and <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a>.</p>


<p>Referenced by <a href="#a606865327a3998227d8a11f8474bf034">isAddrN</a>.</p>

</div>
</div>

### isAddr16() {#aedb890be079e1bb3213b4c0368571a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kAsmParser.cpp}::M68kOperand::isAddr16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### isAddr32() {#aeb98cc3ebac54fb3d45c8e9adf3e9b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kAsmParser.cpp}::M68kOperand::isAddr32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### isAddr8() {#a50708183c7ca4bd45fea5d1519cb8f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kAsmParser.cpp}::M68kOperand::isAddr8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### isAddrN() {#a606865327a3998227d8a11f8474bf034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kAsmParser.cpp}::M68kOperand::isAddrN ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#a594a6135384e308b91dd5e4171f10c66">isAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a>.</p>

</div>
</div>

### isAReg() {#ad355c84be7fb2addbe5af81abb643d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isAReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp/#a4047740df73f0bb66ab47bb81527704c">checkRegisterClass</a>, <a href="#a28e1e8f00b7416eeb61f28746f8670e5">getReg</a> and <a href="#acf5f8cb267b1652470dac931a81b9439">isReg</a>.</p>

</div>
</div>

### isARI() {#adaee3dab6f65cc3086575cdca6d8aed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isARI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11ad32d620e804cea958979648ec4827694">anonymous{M68kAsmParser.cpp}::M68kMemOp::RegIndirect</a>.</p>

</div>
</div>

### isARID() {#aaf28d1dda0fa56a54f6a70527efecda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isARID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a62d05a726cb690398e49d6c2f0853781">anonymous{M68kAsmParser.cpp}::M68kMemOp::RegIndirectDisplacement</a>.</p>

</div>
</div>

### isARII() {#a72a5e4fcc5bc9cda0f46d052c220ff0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isARII ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11ae264775fd80eeadd391fbfedbadf032f">anonymous{M68kAsmParser.cpp}::M68kMemOp::RegIndirectDisplacementIndex</a>.</p>

</div>
</div>

### isARIPD() {#aec19c567b3fae8ea0e67d96c9c133d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isARIPD ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a6e0e619b9305c9816d0eea2f15fd9147">anonymous{M68kAsmParser.cpp}::M68kMemOp::RegPreDecrement</a>.</p>

</div>
</div>

### isARIPI() {#aacacc5c46caece3094774a5724ae2f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isARIPI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a1471f2be91a3ba94687bbc12cb3c02f9">anonymous{M68kAsmParser.cpp}::M68kMemOp::RegPostIncrement</a>.</p>

</div>
</div>

### isBkptImm() {#aef67029c53526e93fdbb13e9213bbea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isBkptImm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#ade23fc6f8270db40ec2c7a5aaca34804">Expr</a>, <a href="#ac2747f6a5c239eef0d5d388e14188c76">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isDReg() {#a0e034c80e4d87f0b999ffc01efa6acfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isDReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp/#a4047740df73f0bb66ab47bb81527704c">checkRegisterClass</a>, <a href="#a28e1e8f00b7416eeb61f28746f8670e5">getReg</a> and <a href="#acf5f8cb267b1652470dac931a81b9439">isReg</a>.</p>

</div>
</div>

### isFPCReg() {#a9801a59a9613c4d188937207f2b80d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isFPCReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp/#a4047740df73f0bb66ab47bb81527704c">checkRegisterClass</a>, <a href="#a28e1e8f00b7416eeb61f28746f8670e5">getReg</a> and <a href="#acf5f8cb267b1652470dac931a81b9439">isReg</a>.</p>

</div>
</div>

### isFPDReg() {#a96abbf8cdda0c2a93959d4e02f650209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isFPDReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp/#a4047740df73f0bb66ab47bb81527704c">checkRegisterClass</a>, <a href="#a28e1e8f00b7416eeb61f28746f8670e5">getReg</a> and <a href="#acf5f8cb267b1652470dac931a81b9439">isReg</a>.</p>

</div>
</div>

### isImm() {#ac2747f6a5c239eef0d5d388e14188c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isImm ()</td>
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

<p>isImm - Is this an immediate operand?</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a3467f0da9b2fdeb58a8078f5fb66e1c9">addImmOperands</a>, <a href="#aef67029c53526e93fdbb13e9213bbea8">isBkptImm</a> and <a href="#ac84738583081af3cc607f4d9ba29eeeb">isTrapImm</a>.</p>

</div>
</div>

### isMem() {#ad332ccd15c37a1ec43ab534796d321cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kAsmParser.cpp}::M68kOperand::isMem ()</td>
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

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### isMemOp() {#af6cdc67c438610bb1434630b74af3b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kAsmParser.cpp}::M68kOperand::isMemOp ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a594a6135384e308b91dd5e4171f10c66">isAddr</a>, <a href="#adaee3dab6f65cc3086575cdca6d8aed5">isARI</a>, <a href="#aaf28d1dda0fa56a54f6a70527efecda2">isARID</a>, <a href="#a72a5e4fcc5bc9cda0f46d052c220ff0b">isARII</a>, <a href="#aec19c567b3fae8ea0e67d96c9c133d5d">isARIPD</a>, <a href="#aacacc5c46caece3094774a5724ae2f09">isARIPI</a>, <a href="#ad22b8b6e14a6adcfc345b6d76f99b1e9">isMoveMask</a>, <a href="#a64e22fc9af57a3017440ab00bd3f80ac">isPCD</a> and <a href="#abc971668b7bcfe8d2cc71043333842b7">isPCI</a>.</p>

</div>
</div>

### isMoveMask() {#ad22b8b6e14a6adcfc345b6d76f99b1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isMoveMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp/#aa488184778f95826dfd1bc1807a7480d">getRegisterIndex</a>, <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a3791fc9668cfd0e7e10650add3cacf6d">anonymous{M68kAsmParser.cpp}::M68kMemOp::Reg</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a667dc7bc6e41ed4734647d326c41d1f7">anonymous{M68kAsmParser.cpp}::M68kMemOp::RegMask</a>.</p>


<p>Referenced by <a href="#a9cd23b62012f429a2e2edb2cb30c21b7">addMoveMaskOperands</a>.</p>

</div>
</div>

### isPCD() {#a64e22fc9af57a3017440ab00bd3f80ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isPCD ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a62d05a726cb690398e49d6c2f0853781">anonymous{M68kAsmParser.cpp}::M68kMemOp::RegIndirectDisplacement</a>.</p>

</div>
</div>

### isPCI() {#abc971668b7bcfe8d2cc71043333842b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isPCI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#af6cdc67c438610bb1434630b74af3b33">isMemOp</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11ae264775fd80eeadd391fbfedbadf032f">anonymous{M68kAsmParser.cpp}::M68kMemOp::RegIndirectDisplacementIndex</a>.</p>

</div>
</div>

### isReg() {#acf5f8cb267b1652470dac931a81b9439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isReg ()</td>
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

<p>isReg - Is this a register operand?</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop/#a0d9a124d40e47a8ba9501716d8a56e11a3791fc9668cfd0e7e10650add3cacf6d">anonymous{M68kAsmParser.cpp}::M68kMemOp::Reg</a>.</p>


<p>Referenced by <a href="#a0e9b31563dafd04ae8a3f4c1114e8f75">addRegOperands</a>, <a href="#a28e1e8f00b7416eeb61f28746f8670e5">getReg</a>, <a href="#ad355c84be7fb2addbe5af81abb643d69">isAReg</a>, <a href="#a0e034c80e4d87f0b999ffc01efa6acfc">isDReg</a>, <a href="#a9801a59a9613c4d188937207f2b80d46">isFPCReg</a>, <a href="#a96abbf8cdda0c2a93959d4e02f650209">isFPDReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68kasmparser/#ae883c185ab1d52bf467bcfb57f6793ad">anonymous{M68kAsmParser.cpp}::M68kAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isToken() {#abe6829f1a9ba3421b36ffe3bb448aaf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isToken ()</td>
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

<p>isToken - Is this a token operand?</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a9360e5ec499a9c72060b083fbb2457ef">getToken</a>.</p>

</div>
</div>

### isTrapImm() {#ac84738583081af3cc607f4d9ba29eeeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kOperand::isTrapImm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#ade23fc6f8270db40ec2c7a5aaca34804">Expr</a>, <a href="#ac2747f6a5c239eef0d5d388e14188c76">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### print() {#a51e09477144479de5e681236a2d0597c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="#ade23fc6f8270db40ec2c7a5aaca34804">Expr</a>, <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a> and <a href="#a6af92ccabc890167df67e028907fe972">Token</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isAddrN() {#a606865327a3998227d8a11f8474bf034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kAsmParser.cpp}::M68kOperand::isAddrN ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Expr {#ade23fc6f8270db40ec2c7a5aaca34804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* anonymous{M68kAsmParser.cpp}::M68kOperand::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a6e27ec9bcfe6b34b7270dc44cc0cc486">addExpr</a>, <a href="#a3467f0da9b2fdeb58a8078f5fb66e1c9">addImmOperands</a>, <a href="#a141f1c9e336dc819d9aee29a20f589cb">createImm</a>, <a href="#aef67029c53526e93fdbb13e9213bbea8">isBkptImm</a>, <a href="#ac84738583081af3cc607f4d9ba29eeeb">isTrapImm</a> and <a href="#a51e09477144479de5e681236a2d0597c">print</a>.</p>

</div>
</div>

### MemOp {#a5451b1ec485efb20756cb1ba63676282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68kMemOp anonymous{M68kAsmParser.cpp}::M68kOperand::MemOp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a6237dab111d9b5ff6d9d9df8f71807ea">addAddrOperands</a>, <a href="#a0e5767e266948d2da6a968bed7c234af">addARIDOperands</a>, <a href="#a8b36bcd58d06ed763e3ff606ef787d61">addARIIOperands</a>, <a href="#aef9678d5d40dc29d922920d97fe2e108">addARIOperands</a>, <a href="#aa408301e2671cf7040584011da1ca4ee">addARIPDOperands</a>, <a href="#a2a6d1110d5731551b614fc041a5e100e">addARIPIOperands</a>, <a href="#a9cd23b62012f429a2e2edb2cb30c21b7">addMoveMaskOperands</a>, <a href="#a81edd91f1a089308e078a5c86ca07ae4">addPCDOperands</a>, <a href="#afc5faf5d7c3df5946555e8a6b9e76c33">addPCIOperands</a>, <a href="#ab49fae0d82f184f89de3cc68f0d55cb5">createMemOp</a>, <a href="#a28e1e8f00b7416eeb61f28746f8670e5">getReg</a>, <a href="#a594a6135384e308b91dd5e4171f10c66">isAddr</a>, <a href="#a606865327a3998227d8a11f8474bf034">isAddrN</a>, <a href="#adaee3dab6f65cc3086575cdca6d8aed5">isARI</a>, <a href="#aaf28d1dda0fa56a54f6a70527efecda2">isARID</a>, <a href="#a72a5e4fcc5bc9cda0f46d052c220ff0b">isARII</a>, <a href="#aec19c567b3fae8ea0e67d96c9c133d5d">isARIPD</a>, <a href="#aacacc5c46caece3094774a5724ae2f09">isARIPI</a>, <a href="#ad22b8b6e14a6adcfc345b6d76f99b1e9">isMoveMask</a>, <a href="#a64e22fc9af57a3017440ab00bd3f80ac">isPCD</a>, <a href="#abc971668b7bcfe8d2cc71043333842b7">isPCI</a>, <a href="#acf5f8cb267b1652470dac931a81b9439">isReg</a> and <a href="#a51e09477144479de5e681236a2d0597c">print</a>.</p>

</div>
</div>

### Token {#a6af92ccabc890167df67e028907fe972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{M68kAsmParser.cpp}::M68kOperand::Token</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ab1e5a43093388b60bd2f22db298db003">createToken</a>, <a href="#a9360e5ec499a9c72060b083fbb2457ef">getToken</a> and <a href="#a51e09477144479de5e681236a2d0597c">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a803c8a4d15f1bf2685a4e95b1e9019dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{M68kAsmParser.cpp}::M68kOperand anonymous{M68kAsmParser.cpp}::M68kOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### End {#ad8b52e26e8926e2eea04d5c8f595a6dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{M68kAsmParser.cpp}::M68kOperand::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### Kind {#a89c4c3c614ae604016e971553799e815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KindTy anonymous{M68kAsmParser.cpp}::M68kOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

### Start {#af20924bd510c83c73733ace696241d9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{M68kAsmParser.cpp}::M68kOperand::Start</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### addExpr() {#a6e27ec9bcfe6b34b7270dc44cc0cc486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kOperand::addExpr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#ade23fc6f8270db40ec2c7a5aaca34804">Expr</a>.</p>


<p>Referenced by <a href="#a6237dab111d9b5ff6d9d9df8f71807ea">addAddrOperands</a>, <a href="#a0e5767e266948d2da6a968bed7c234af">addARIDOperands</a>, <a href="#a8b36bcd58d06ed763e3ff606ef787d61">addARIIOperands</a>, <a href="#a3467f0da9b2fdeb58a8078f5fb66e1c9">addImmOperands</a>, <a href="#a81edd91f1a089308e078a5c86ca07ae4">addPCDOperands</a> and <a href="#afc5faf5d7c3df5946555e8a6b9e76c33">addPCIOperands</a>.</p>

</div>
</div>

### createImm() {#a141f1c9e336dc819d9aee29a20f589cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; M68kOperand &gt; M68kOperand::createImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Reference <a href="#ade23fc6f8270db40ec2c7a5aaca34804">Expr</a>.</p>

</div>
</div>

### createMemOp() {#ab49fae0d82f184f89de3cc68f0d55cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; M68kOperand &gt; M68kOperand::createMemOp (<a href="/web-llvm/docs/api/structs/anonymous-m68kasmparser-cpp-/m68kmemop">M68kMemOp</a> MemOp, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Reference <a href="#a5451b1ec485efb20756cb1ba63676282">MemOp</a>.</p>

</div>
</div>

### createToken() {#ab1e5a43093388b60bd2f22db298db003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; M68kOperand &gt; M68kOperand::createToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Token, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a>.</p>


<p>Reference <a href="#a6af92ccabc890167df67e028907fe972">Token</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68kasmparser/#a6ed1f4d7f56e05cf30cc258a8f248bf7">anonymous{M68kAsmParser.cpp}::M68kAsmParser::parseInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp">M68kAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
