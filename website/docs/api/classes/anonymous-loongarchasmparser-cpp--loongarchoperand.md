---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoongArchOperand` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{LoongArchAsmParser.cpp}::LoongArchOperand { ... }
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#a88777e9423e0bcab835bbcd69b93d456">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b925bab042333221adce070329a2ba">LoongArchOperand</a> (KindTy K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa412c6bc58b609379a1ba0ce71ae4c6f">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#aa412c6bc58b609379a1ba0ce71ae4c6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6398a0f44c47a1303f4139dfc493b1d">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#ad6398a0f44c47a1303f4139dfc493b1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9510f9bf2865b18109172f2b13a2de6">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#ab9510f9bf2865b18109172f2b13a2de6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b4ae2709f93fcdc7e443bf75890eb1">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#ae2b4ae2709f93fcdc7e443bf75890eb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad908b8d88f8e0fa88513652fbb4a496b">setReg</a> (MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446365cc4939cf2022f8376f32214c7b">isGPR</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N, int P = 0&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N, unsigned S = 0&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833cc28225e638366be9525d746e76c8">isBareSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d4a503d589ec40623d5d5d80acc9520">isTPRelAddSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a321b7047e2d89cb9e934daba399f5">isUImm1</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49239e9d32d047c7524d74c5982baf5e">isUImm2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0075a1e90993ad1cd313f231366d54">isUImm2plus1</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97237e3277b3ad3c6c2f97453b244f4a">isUImm3</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae684e6412c8d4ffdc41a8de3a5d60f83">isUImm4</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1259a700ef8ce4e748c8ea6bbacf7d5">isSImm5</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669b1c53fe7a73bde0b92b7f052e1970">isUImm5</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad388d4156d70b8e0d107d13184383011">isUImm6</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1cc44322a2a808a96e01620b81d25bc">isUImm7</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6347309cb182a029185af444067af4b2">isSImm8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab25fb6bf77115e18a2bb3f30738b020f">isSImm8lsl1</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc2cd9181dc39f5e23825e0ebd6ac39">isSImm8lsl2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f1409c9369b54b1a6b1b6faa939c21b">isSImm8lsl3</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c7199bcc5d2c05439ba8c3f1963a23">isUImm8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca47b61ee08662ce135e4f3fc7936192">isSImm9lsl3</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8d50f8704e30816dc269ff2031aa035">isSImm10</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3144738d6ace1c9851b3328b274affd6">isSImm10lsl2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a5d223ec9e1510e588a5e9345316396">isSImm11lsl1</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89f415b26df9ed072d53169fca7054be">isSImm12</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58fa85243ecc7987f30746b24e78814e">isSImm12addlike</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cdd4f4fb1fb8021271baf9744fd9f97">isSImm12lu52id</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40f46259b47e2fa7b08763ea9a4a8bad">isUImm12</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b0d1682d6c5d386162e94a79d02b3f">isUImm12ori</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e2aa95cd4ad77a7d399c69810162c9e">isSImm13</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef21c948c1e5c6521726d9bae643ef6">isUImm14</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefef91e2f78fd635d477446833540725">isUImm15</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3296df650453fb07546938d625d1fd69">isSImm14lsl2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a93a5ebfeb8d0e3dd835373ccbdc0b8">isSImm16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a616bedb534439b0fcf7af17daf289928">isSImm16lsl2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c16f6ed3026eb01eb8c5ef68e3fd83">isSImm20</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4724f9de28ee2e6fc029afdb82429919">isSImm20pcalau12i</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abecd6ad1bfa7d1c7cae4bc001ec0d6af">isSImm20lu12iw</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76062d95e087f6d34c2342f7864d0375">isSImm20lu32id</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593a4288b0b64c8ac07b9223f925e5b4">isSImm20pcaddu18i</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad045bbc3b96a4edfa9d6442e007ba60b">isSImm20pcaddi</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe6c9282287b819df475fc48ab35e59">isSImm21lsl2</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f664176dd5afd5051b83fa17e5cb2c">isSImm26Operand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d093f533764db46218463f473f6b0d">isImm32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32303eaaa310fc67f31e35bb0dae5aca">isImm64</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f102c2e3d5c8a9cf2638796219ed94f">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets location of the first token of this operand. <a href="#a7f102c2e3d5c8a9cf2638796219ed94f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8833669f8298721ef0996694f8db495a">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets location of the last token of this operand. <a href="#a8833669f8298721ef0996694f8db495a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae81641d8c15622e0247da67233e5caa1">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb24d144c7394b0ca7ae26c4afe3a5e">getToken</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7a7958d8950902186c344eb8162e3ff">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#af7a7958d8950902186c344eb8162e3ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7589c38fd0a2e2644d73a92624904d1">addExpr</a> (MCInst &amp;Inst, const MCExpr *Expr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987343bc203c352faf89653f4e162c8e">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a680203d02fe1028bb553895c4c017">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e56db9a2433c4cfc7600da1d5ca31c0">Tok</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a7a01cd10c43332fe1237042d35385">Reg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{LoongArchAsmParser.cpp}::LoongArchOperand::KindTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84a651a14bf52e3eca9c3d2cfc508170">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20fb45b242a233c6f41765fc84ed3e13">StartLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0701d067665f2b7019d87b682fce3f28">EndLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{LoongArchAsmParser.cpp}<a href="#a46b925bab042333221adce070329a2ba">::LoongArchOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998e980c7296c91d2055f21ec450592b"></a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a> (const MCExpr *Expr, int64_t &amp;Imm, LoongArchMCExpr::VariantKind &amp;VK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand">LoongArchOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb489ae7b6afbc0215e9fba6e8dc8a6">createToken</a> (StringRef Str, SMLoc S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand">LoongArchOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe843ee0aa7c22fb14c66ce4381c7a5a">createReg</a> (MCRegister Reg, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand">LoongArchOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a7deb740ede39c45b35d058b88b172">createImm</a> (const MCExpr *Val, SMLoc S, SMLoc E)</td>
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


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindTy {#a88777e9423e0bcab835bbcd69b93d456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::KindTy </td>
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
<td class="doxyEnumItemName">Token<a id="a88777e9423e0bcab835bbcd69b93d456a459a6f79ad9b13cbcb5f692d2cc7a94d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="a88777e9423e0bcab835bbcd69b93d456a0ba7583639a274c434bbe6ef797115a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Immediate<a id="a88777e9423e0bcab835bbcd69b93d456a43f6615bbb2c40a5306ff804094420b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoongArchOperand() {#a46b925bab042333221adce070329a2ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::LoongArchOperand (KindTy K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#a116eebce8e7768c60749aa19af77f817">llvm::MCParsedAsmOperand::MCParsedAsmOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addExpr() {#af7589c38fd0a2e2644d73a92624904d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::addExpr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a70a680203d02fe1028bb553895c4c017">addImmOperands</a>.</p>

</div>
</div>

### addImmOperands() {#a70a680203d02fe1028bb553895c4c017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="#af7589c38fd0a2e2644d73a92624904d1">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#a987343bc203c352faf89653f4e162c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getEndLoc() {#a8833669f8298721ef0996694f8db495a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::getEndLoc ()</td>
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

<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### getImm() {#a9cba83e98f78cf16c41e600cee91f3ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::getImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>.</p>


<p>Referenced by <a href="#a70a680203d02fe1028bb553895c4c017">addImmOperands</a>, <a href="#a833cc28225e638366be9525d746e76c8">isBareSymbol</a>, <a href="#a32303eaaa310fc67f31e35bb0dae5aca">isImm64</a>, <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>, <a href="#a58fa85243ecc7987f30746b24e78814e">isSImm12addlike</a>, <a href="#a0cdd4f4fb1fb8021271baf9744fd9f97">isSImm12lu52id</a>, <a href="#a616bedb534439b0fcf7af17daf289928">isSImm16lsl2</a>, <a href="#abecd6ad1bfa7d1c7cae4bc001ec0d6af">isSImm20lu12iw</a>, <a href="#a76062d95e087f6d34c2342f7864d0375">isSImm20lu32id</a>, <a href="#ad045bbc3b96a4edfa9d6442e007ba60b">isSImm20pcaddi</a>, <a href="#a593a4288b0b64c8ac07b9223f925e5b4">isSImm20pcaddu18i</a>, <a href="#a4724f9de28ee2e6fc029afdb82429919">isSImm20pcalau12i</a>, <a href="#aabe6c9282287b819df475fc48ab35e59">isSImm21lsl2</a>, <a href="#a51f664176dd5afd5051b83fa17e5cb2c">isSImm26Operand</a>, <a href="#a6d4a503d589ec40623d5d5d80acc9520">isTPRelAddSymbol</a>, <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>, <a href="#a76b0d1682d6c5d386162e94a79d02b3f">isUImm12ori</a> and <a href="#af7a7958d8950902186c344eb8162e3ff">print</a>.</p>

</div>
</div>

### getReg() {#ae81641d8c15622e0247da67233e5caa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::getReg ()</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a85a7a01cd10c43332fe1237042d35385">Reg</a>.</p>

</div>
</div>

### getStartLoc() {#a7f102c2e3d5c8a9cf2638796219ed94f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::getStartLoc ()</td>
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

<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### getToken() {#a1cb24d144c7394b0ca7ae26c4afe3a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::getToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6e56db9a2433c4cfc7600da1d5ca31c0">Tok</a>.</p>

</div>
</div>

### isBareSymbol() {#a833cc28225e638366be9525d746e76c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isBareSymbol ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>.</p>

</div>
</div>

### isGPR() {#a446365cc4939cf2022f8376f32214c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isGPR ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#a85a7a01cd10c43332fe1237042d35385">Reg</a>.</p>

</div>
</div>

### isImm() {#ab9510f9bf2865b18109172f2b13a2de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isImm ()</td>
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

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### isImm32() {#a02d093f533764db46218463f473f6b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isImm32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a> and <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isImm64() {#a32303eaaa310fc67f31e35bb0dae5aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isImm64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>.</p>

</div>
</div>

### isMem() {#ae2b4ae2709f93fcdc7e443bf75890eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isMem ()</td>
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

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### isReg() {#ad6398a0f44c47a1303f4139dfc493b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isReg ()</td>
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

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### isSImm() {#ad4bcc7c632ba30551ac54adf68e20a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N, unsigned S = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>.</p>


<p>Referenced by <a href="#a02d093f533764db46218463f473f6b0d">isImm32</a>, <a href="#ad8d50f8704e30816dc269ff2031aa035">isSImm10</a>, <a href="#a3144738d6ace1c9851b3328b274affd6">isSImm10lsl2</a>, <a href="#a4a5d223ec9e1510e588a5e9345316396">isSImm11lsl1</a>, <a href="#a89f415b26df9ed072d53169fca7054be">isSImm12</a>, <a href="#a4e2aa95cd4ad77a7d399c69810162c9e">isSImm13</a>, <a href="#a3296df650453fb07546938d625d1fd69">isSImm14lsl2</a>, <a href="#a4a93a5ebfeb8d0e3dd835373ccbdc0b8">isSImm16</a>, <a href="#a09c16f6ed3026eb01eb8c5ef68e3fd83">isSImm20</a>, <a href="#ac1259a700ef8ce4e748c8ea6bbacf7d5">isSImm5</a>, <a href="#a6347309cb182a029185af444067af4b2">isSImm8</a>, <a href="#ab25fb6bf77115e18a2bb3f30738b020f">isSImm8lsl1</a>, <a href="#a6cc2cd9181dc39f5e23825e0ebd6ac39">isSImm8lsl2</a>, <a href="#a3f1409c9369b54b1a6b1b6faa939c21b">isSImm8lsl3</a> and <a href="#aca47b61ee08662ce135e4f3fc7936192">isSImm9lsl3</a>.</p>

</div>
</div>

### isSImm10() {#ad8d50f8704e30816dc269ff2031aa035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm10 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm10lsl2() {#a3144738d6ace1c9851b3328b274affd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm10lsl2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm11lsl1() {#a4a5d223ec9e1510e588a5e9345316396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm11lsl1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm12() {#a89f415b26df9ed072d53169fca7054be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm12addlike() {#a58fa85243ecc7987f30746b24e78814e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm12addlike ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa5a27ca526e9322089661bd5d5765acf">llvm::LoongArchMCExpr::VK_LoongArch_GOT_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa317df8b349d62bcc6b0f2f714cf4e3f2">llvm::LoongArchMCExpr::VK_LoongArch_PCALA_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa83c43c389321317ab727415951d89d3b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_LD</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac40aea5222f770df6bef19887ff6e95f">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa7999ca8a77cee84f4ab594113d188745">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_PC_LO12</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fabd4f5bd7211c4e6ab85c3e964360b290">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_LO12_R</a>.</p>

</div>
</div>

### isSImm12lu52id() {#a0cdd4f4fb1fb8021271baf9744fd9f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm12lu52id ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa5a1b61e6eda817ed9e2b3cd6056990b1">llvm::LoongArchMCExpr::VK_LoongArch_ABS64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa311598ad7d07257815082808e9ac1fdf">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa942bf7e81e85ddb89b17479502489554">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_PC_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fadb040d152ed1e4e61470d230855861e6">llvm::LoongArchMCExpr::VK_LoongArch_PCALA64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33f37781402f6b86afbef475c4161894">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faca511db33a132c4018d5125fbfecf380">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_PC_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa5ed5ac4f2e54048bf799310defa548ba">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faeef04231f1e5fdc1e0422183470183f1">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_PC_HI12</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa11590762cd7e097ca71309aea2b89768">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE64_HI12</a>.</p>

</div>
</div>

### isSImm13() {#a4e2aa95cd4ad77a7d399c69810162c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm13 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm14lsl2() {#a3296df650453fb07546938d625d1fd69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm14lsl2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm16() {#a4a93a5ebfeb8d0e3dd835373ccbdc0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm16lsl2() {#a616bedb534439b0fcf7af17daf289928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm16lsl2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa9d404502c90b9f06080fc97fe12110ae">llvm::LoongArchMCExpr::VK_LoongArch_B16</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa317df8b349d62bcc6b0f2f714cf4e3f2">llvm::LoongArchMCExpr::VK_LoongArch_PCALA_LO12</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa213239ed6908fdf8c514ee7b9fde83c7">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_CALL</a>.</p>

</div>
</div>

### isSImm20() {#a09c16f6ed3026eb01eb8c5ef68e3fd83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm20lu12iw() {#abecd6ad1bfa7d1c7cae4bc001ec0d6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20lu12iw ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa203b677b6d91643eee403c74f5370303">llvm::LoongArchMCExpr::VK_LoongArch_ABS_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa2968ccf12fee2fe568d6673d83632eba">llvm::LoongArchMCExpr::VK_LoongArch_GOT_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa53d1c9f539eb44d3f293cd3d40931e62">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa3c1cd75405441118fd8be8c2193532b1">llvm::LoongArchMCExpr::VK_LoongArch_TLS_GD_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa389a7ab7f07286be92f09eecb6d16e1c">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa20401cf1e3c1c674bc022e8a039770a3">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LD_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faaf90da3f79d9695756216166cfcce205">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_HI20</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa36359bd9320b3a5a9d7c042872cc31ff">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_HI20_R</a>.</p>

</div>
</div>

### isSImm20lu32id() {#a76062d95e087f6d34c2342f7864d0375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20lu32id ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fafa717809c42ea7a735c4ba7cd7cc9b0d">llvm::LoongArchMCExpr::VK_LoongArch_ABS64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac47fcc37d78a9b3eec4e00531ab622a7">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3facfb29225eda9c946dfa6a9cd6319bd2a">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_PC_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa1e2680ca0caa8430901cf1c4cac7904">llvm::LoongArchMCExpr::VK_LoongArch_PCALA64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac54f5d108b9b10b10dbde7fcc8360a27">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa889c7dda330f4512b92b10d6037ae968">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_PC_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa6d762b588d0bfd42e24afb9b4943c710">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa69ddebf16c8e84b6872be8e80989431b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_PC_LO20</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa0e31177c652aeaa8dc62b3692c15f10">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE64_LO20</a>.</p>

</div>
</div>

### isSImm20pcaddi() {#ad045bbc3b96a4edfa9d6442e007ba60b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20pcaddi ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa1c6d9ba2e4a6e6a8fff0f16a0e390cbb">llvm::LoongArchMCExpr::VK_LoongArch_PCREL20_S2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa27fb2e3f2b14071e67978225162fc6ef">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_PCREL20_S2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa99900bd2b4f973f1a5267ab4fccf1ffb">llvm::LoongArchMCExpr::VK_LoongArch_TLS_GD_PCREL20_S2</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fae135875cdc076b203e8930a288d51547">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LD_PCREL20_S2</a>.</p>

</div>
</div>

### isSImm20pcaddu18i() {#a593a4288b0b64c8ac07b9223f925e5b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20pcaddu18i ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fad6c8d6e7d5e229e681e7d585f69faaab">llvm::LoongArchMCExpr::VK_LoongArch_CALL36</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>.</p>

</div>
</div>

### isSImm20pcalau12i() {#a4724f9de28ee2e6fc029afdb82429919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm20pcalau12i ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa657565a0ac647cc547c2ac36f3f72a55">llvm::LoongArchMCExpr::VK_LoongArch_GOT_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa09957a91a71c9ef48220738c683a6664">llvm::LoongArchMCExpr::VK_LoongArch_PCALA_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fae6e3232ea5ed35bcff53b2870ab91caa">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac8447557b79aea88da30a7924a415a4d">llvm::LoongArchMCExpr::VK_LoongArch_TLS_GD_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa9578c303dbb56ea59546a31685a7e7b4">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_PC_HI20</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa112bf038550f50622ec2a2fae1597a1b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LD_PC_HI20</a>.</p>

</div>
</div>

### isSImm21lsl2() {#aabe6c9282287b819df475fc48ab35e59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm21lsl2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa898fbeff95eaf12a8ea019722e6d0d3e">llvm::LoongArchMCExpr::VK_LoongArch_B21</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>.</p>

</div>
</div>

### isSImm26Operand() {#a51f664176dd5afd5051b83fa17e5cb2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm26Operand ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa013d74af246487fe165cb00b45c3a09d">llvm::LoongArchMCExpr::VK_LoongArch_B26</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa1966ed6149cfdacca4a00fe4c47c84b2">llvm::LoongArchMCExpr::VK_LoongArch_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa7eb27ee3028b06cba41393d751fe1fb5">llvm::LoongArchMCExpr::VK_LoongArch_CALL_PLT</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>.</p>

</div>
</div>

### isSImm5() {#ac1259a700ef8ce4e748c8ea6bbacf7d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm5 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm8() {#a6347309cb182a029185af444067af4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm8lsl1() {#ab25fb6bf77115e18a2bb3f30738b020f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm8lsl1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm8lsl2() {#a6cc2cd9181dc39f5e23825e0ebd6ac39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm8lsl2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm8lsl3() {#a3f1409c9369b54b1a6b1b6faa939c21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm8lsl3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isSImm9lsl3() {#aca47b61ee08662ce135e4f3fc7936192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isSImm9lsl3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>.</p>

</div>
</div>

### isToken() {#aa412c6bc58b609379a1ba0ce71ae4c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isToken ()</td>
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

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### isTPRelAddSymbol() {#a6d4a503d589ec40623d5d5d80acc9520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isTPRelAddSymbol ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac93f74665b151febca74a33966c42f24">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_ADD_R</a>.</p>

</div>
</div>

### isUImm() {#aed369dc44d69c66771b08d0d09b98273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N, int P = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>.</p>


<p>Referenced by <a href="#a02d093f533764db46218463f473f6b0d">isImm32</a>, <a href="#a93a321b7047e2d89cb9e934daba399f5">isUImm1</a>, <a href="#a40f46259b47e2fa7b08763ea9a4a8bad">isUImm12</a>, <a href="#a8ef21c948c1e5c6521726d9bae643ef6">isUImm14</a>, <a href="#aefef91e2f78fd635d477446833540725">isUImm15</a>, <a href="#a49239e9d32d047c7524d74c5982baf5e">isUImm2</a>, <a href="#a9d0075a1e90993ad1cd313f231366d54">isUImm2plus1</a>, <a href="#a97237e3277b3ad3c6c2f97453b244f4a">isUImm3</a>, <a href="#ae684e6412c8d4ffdc41a8de3a5d60f83">isUImm4</a>, <a href="#a669b1c53fe7a73bde0b92b7f052e1970">isUImm5</a>, <a href="#ad388d4156d70b8e0d107d13184383011">isUImm6</a>, <a href="#af1cc44322a2a808a96e01620b81d25bc">isUImm7</a> and <a href="#a24c7199bcc5d2c05439ba8c3f1963a23">isUImm8</a>.</p>

</div>
</div>

### isUImm1() {#a93a321b7047e2d89cb9e934daba399f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm12() {#a40f46259b47e2fa7b08763ea9a4a8bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm12 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm12ori() {#a76b0d1682d6c5d386162e94a79d02b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm12ori ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchasmparser/#a9fd40942a15dc31532f69d4f88eb1c22">anonymous{LoongArchAsmParser.cpp}::LoongArchAsmParser::classifySymbolRef</a>, <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa4b6341fa13f1dc1e47baacdcf69e8c41">llvm::LoongArchMCExpr::VK_LoongArch_ABS_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa88122daedcca01675ef8906b58578b5c">llvm::LoongArchMCExpr::VK_LoongArch_GOT_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa5a27ca526e9322089661bd5d5765acf">llvm::LoongArchMCExpr::VK_LoongArch_GOT_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa317df8b349d62bcc6b0f2f714cf4e3f2">llvm::LoongArchMCExpr::VK_LoongArch_PCALA_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa8f6f6db2e883c43aeade25c0437dbed0">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa4ed58231825db10243f5d7200bf8d09">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa7999ca8a77cee84f4ab594113d188745">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_PC_LO12</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa5ad2126dc889178bc845a3243170a252">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_LO12</a>.</p>

</div>
</div>

### isUImm14() {#a8ef21c948c1e5c6521726d9bae643ef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm14 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm15() {#aefef91e2f78fd635d477446833540725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm15 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm2() {#a49239e9d32d047c7524d74c5982baf5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm2plus1() {#a9d0075a1e90993ad1cd313f231366d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm2plus1 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm3() {#a97237e3277b3ad3c6c2f97453b244f4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm4() {#ae684e6412c8d4ffdc41a8de3a5d60f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm4 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm5() {#a669b1c53fe7a73bde0b92b7f052e1970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm5 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm6() {#ad388d4156d70b8e0d107d13184383011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm6 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm7() {#af1cc44322a2a808a96e01620b81d25bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm7 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### isUImm8() {#a24c7199bcc5d2c05439ba8c3f1963a23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::isUImm8 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a>.</p>

</div>
</div>

### print() {#af7a7958d8950902186c344eb8162e3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter/#aaafed19006fc584bf51288b747681986">llvm::LoongArchInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20237283e8b9e354abec8dc5ab16bd16">llvm::getToken</a>, <a href="#a85a7a01cd10c43332fe1237042d35385">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>.</p>

</div>
</div>

### setReg() {#ad908b8d88f8e0fa88513652fbb4a496b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::setReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#a85a7a01cd10c43332fe1237042d35385">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Imm {#a87befe9abbd6551b6227e1aa2b155164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ImmOp anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#ade2b133b2bd9b6271e9b29a51d74a7da">evaluateConstantImm</a>, <a href="#a9cba83e98f78cf16c41e600cee91f3ca">getImm</a>, <a href="#a833cc28225e638366be9525d746e76c8">isBareSymbol</a>, <a href="#a32303eaaa310fc67f31e35bb0dae5aca">isImm64</a>, <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>, <a href="#a58fa85243ecc7987f30746b24e78814e">isSImm12addlike</a>, <a href="#a0cdd4f4fb1fb8021271baf9744fd9f97">isSImm12lu52id</a>, <a href="#a616bedb534439b0fcf7af17daf289928">isSImm16lsl2</a>, <a href="#abecd6ad1bfa7d1c7cae4bc001ec0d6af">isSImm20lu12iw</a>, <a href="#a76062d95e087f6d34c2342f7864d0375">isSImm20lu32id</a>, <a href="#ad045bbc3b96a4edfa9d6442e007ba60b">isSImm20pcaddi</a>, <a href="#a593a4288b0b64c8ac07b9223f925e5b4">isSImm20pcaddu18i</a>, <a href="#a4724f9de28ee2e6fc029afdb82429919">isSImm20pcalau12i</a>, <a href="#aabe6c9282287b819df475fc48ab35e59">isSImm21lsl2</a>, <a href="#a51f664176dd5afd5051b83fa17e5cb2c">isSImm26Operand</a>, <a href="#a6d4a503d589ec40623d5d5d80acc9520">isTPRelAddSymbol</a>, <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a> and <a href="#a76b0d1682d6c5d386162e94a79d02b3f">isUImm12ori</a>.</p>

</div>
</div>

### Reg {#a85a7a01cd10c43332fe1237042d35385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct RegOp anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#afe843ee0aa7c22fb14c66ce4381c7a5a">createReg</a>, <a href="#ae81641d8c15622e0247da67233e5caa1">getReg</a>, <a href="#a446365cc4939cf2022f8376f32214c7b">isGPR</a>, <a href="#af7a7958d8950902186c344eb8162e3ff">print</a> and <a href="#ad908b8d88f8e0fa88513652fbb4a496b">setReg</a>.</p>

</div>
</div>

### Tok {#a6e56db9a2433c4cfc7600da1d5ca31c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a1cb24d144c7394b0ca7ae26c4afe3a5e">getToken</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#a998e980c7296c91d2055f21ec450592b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{LoongArchAsmParser.cpp}::LoongArchOperand anonymous{LoongArchAsmParser.cpp}::LoongArchOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### EndLoc {#a0701d067665f2b7019d87b682fce3f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### Kind {#a84a651a14bf52e3eca9c3d2cfc508170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::KindTy anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### StartLoc {#a20fb45b242a233c6f41765fc84ed3e13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createImm() {#ad2a7deb740ede39c45b35d058b88b172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LoongArchOperand &gt; anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::createImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### createReg() {#afe843ee0aa7c22fb14c66ce4381c7a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LoongArchOperand &gt; anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::createReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>Reference <a href="#a85a7a01cd10c43332fe1237042d35385">Reg</a>.</p>

</div>
</div>

### createToken() {#abdb489ae7b6afbc0215e9fba6e8dc8a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; LoongArchOperand &gt; anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::createToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>

</div>
</div>

### evaluateConstantImm() {#ade2b133b2bd9b6271e9b29a51d74a7da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::evaluateConstantImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, int64_t &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3f">LoongArchMCExpr::VariantKind</a> &amp; VK)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a87befe9abbd6551b6227e1aa2b155164">Imm</a>.</p>


<p>Referenced by <a href="#a833cc28225e638366be9525d746e76c8">isBareSymbol</a>, <a href="#a32303eaaa310fc67f31e35bb0dae5aca">isImm64</a>, <a href="#ad4bcc7c632ba30551ac54adf68e20a99">isSImm</a>, <a href="#a58fa85243ecc7987f30746b24e78814e">isSImm12addlike</a>, <a href="#a0cdd4f4fb1fb8021271baf9744fd9f97">isSImm12lu52id</a>, <a href="#a616bedb534439b0fcf7af17daf289928">isSImm16lsl2</a>, <a href="#abecd6ad1bfa7d1c7cae4bc001ec0d6af">isSImm20lu12iw</a>, <a href="#a76062d95e087f6d34c2342f7864d0375">isSImm20lu32id</a>, <a href="#ad045bbc3b96a4edfa9d6442e007ba60b">isSImm20pcaddi</a>, <a href="#a593a4288b0b64c8ac07b9223f925e5b4">isSImm20pcaddu18i</a>, <a href="#a4724f9de28ee2e6fc029afdb82429919">isSImm20pcalau12i</a>, <a href="#aabe6c9282287b819df475fc48ab35e59">isSImm21lsl2</a>, <a href="#a51f664176dd5afd5051b83fa17e5cb2c">isSImm26Operand</a>, <a href="#a6d4a503d589ec40623d5d5d80acc9520">isTPRelAddSymbol</a>, <a href="#aed369dc44d69c66771b08d0d09b98273">isUImm</a> and <a href="#a76b0d1682d6c5d386162e94a79d02b3f">isUImm12ori</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp">LoongArchAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
