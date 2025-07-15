---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUOperand` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand { ... }
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace54d060c027c4de4bd81706c19355fb">Ptr</a> = std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand">AMDGPUOperand</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#af9c6a8670c2e9f278e168dff44b39ada">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ImmTy { <a href="#aac6196abacab3897ea9874e72d3db8fc">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ImmKindTy { <a href="#aa817fddb7d8c888c671fcebc15b4b76a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819c0cb08510ccd01fd5615d66fe0955">AMDGPUOperand</a> (KindTy Kind_, const AMDGPUAsmParser *AsmParser_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d8227b613dc0aff33ca27637d41c74a">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#a5d8227b613dc0aff33ca27637d41c74a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ad7d3a52a625302db35bf74a9a3836">isSymbolRefExpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae14745a72acdb68188b6dc3991cc3dfe">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#ae14745a72acdb68188b6dc3991cc3dfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa64c48e281a33a5607fc828e5ad626">setImmKindNone</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a0ff009144236a6532b574438a50a45">setImmKindLiteral</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa62444e32183814cbc01fb3c82c10eee">setImmKindMandatoryLiteral</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8d2feece61e3394cb02d59351ea70f">setImmKindConst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5329f028dc85cb9c189110eb90309790">IsImmKindLiteral</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb66e6b20daee99ff51c1de598caaeda">IsImmKindMandatoryLiteral</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621031fa88ed3052303329e1d5f55c06">isImmKindConst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28800a685d06a879d56b4d178e85aa5">isInlinableImm</a> (MVT type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> (MVT type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6323b2f7c53b4ebcbd057da0f366ed8d">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#a6323b2f7c53b4ebcbd057da0f366ed8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a> (unsigned RCID, MVT type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ce1a2b844fbe612c836b788bb80b29">isRegOrImmWithInputMods</a> (unsigned RCID, MVT type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a8c1b3938fb3ef6a688675b0339f9bc">isRegOrImmWithInt16InputMods</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsFake16&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd3d0647b85d10a8da9106f4290e06ab">isRegOrImmWithIntT16InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2256f6dba15ab8a440e87b8f2c36e55d">isRegOrImmWithInt32InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c97b53b7bb05ac7715f45cb238dce9">isRegOrInlineImmWithInt16InputMods</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsFake16&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a252d5e0092300d4154a3715dc5a9cc67">isRegOrInlineImmWithIntT16InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d61a166ea5959093d03dc95da3d706e">isRegOrInlineImmWithInt32InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac07a510b855028d98f6b3572236646ce">isRegOrImmWithInt64InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd7023a581a2de433c0bbbf162f8136">isRegOrImmWithFP16InputMods</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsFake16&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d77f28353be6ab1cb39ff21a3f68b01">isRegOrImmWithFPT16InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde7d67294d883e68659a654836e5405">isRegOrImmWithFP32InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db6541d4d2950f6571cc47da6e47190">isRegOrImmWithFP64InputMods</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsFake16&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7a5daec5c981d176426ba0bec8901bc">isRegOrInlineImmWithFP16InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e4d40591500fa470657900a51c0be04">isRegOrInlineImmWithFP32InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6216d7cf4dff4ff6c0173315e212b030">isPackedFP16InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c96f84c9aa36358bca4552ba9d98e99">isPackedFP32InputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb91b96bac5323420834ff2ef15c8022">isVReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c384f6ec4cb38b1a921418ee06b19b0">isVReg32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e78a8f72b1a1d2cdc5616e36e501aa1">isVReg32OrOff</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a9c23ba883fb9aa73d55a43260e4a5">isNull</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab805317174b719e76b7063fe3800f002">isVRegWithInputMods</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsFake16&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afee6a95dc973633bcdc0374c5818d1c4">isT16_Lo128VRegWithInputMods</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsFake16&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acc384733bb6f91a5031c0e48c09962e1">isT16VRegWithInputMods</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a> (MVT type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ff4d1f7b2fc72dc15000bd7f7e75c3">isSDWAFP16Operand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa475558e94482db687222e7484523427">isSDWAFP32Operand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a870a78ded2114be969dd5f0179428df8">isSDWAInt16Operand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab1dc38460665f7240799afba15e8beb">isSDWAInt32Operand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a> (ImmTy ImmT) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;ImmTy Ty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66668629a5763bdbd767f1758ff8a240">isImmLiteral</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02a39c837b571df2b4d3712264ca6c2">isImmModifier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a186908fe05ef5b3f4f7ab2865c33e798">isOModSI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725441e4bc10087cf4158f40684ff7d3">isDim</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85291654688208306aa79041286e5deb">isR128A16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66954f4e62ba45315968d4c728d9d3d">isOff</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afabf375b8f9c73d52d1de145e35eb1f5">isExpTgt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489f00cf9dd045f774be9a4a5f8ba360">isOffen</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a00d1441baffd67cc30c446eb4dc6d">isIdxen</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da081c55cdc6b6177d44f16709f407f">isAddr64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed765d7340acfc511234e81438883ac">isSMEMOffsetMod</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f9c98bff2dbe6132bea65df3f2f948">isFlatOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fe560c5124729f869042921509ee5f4">isGDS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e4facce65c38df1b0b9ee5770d1c48">isLDS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31d84f19e1ed3db03f69e88510be043">isCPol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6127ce6559262384ffe1edf00a87d01f">isIndexKey8bit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7316456a666b503541d24406d2159c3c">isIndexKey16bit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a136032b6433e8780b837c9ea1f03af10">isTFE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a843ebc10c0fc3b71d7c5aeca93af90cc">isFORMAT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7601fdfd565704de9abe6c1097b4880">isDppFI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6a430fa695166d19782300671d284e">isSDWADstSel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed9e20d4ce1b2697a8973b48fc594bd">isSDWASrc0Sel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e1a34ff8c704eecc7afb4dedd6c6a75">isSDWASrc1Sel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b496d2ed1fcfdd11f8b6ff09ebd797">isSDWADstUnused</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c3b2574b178fb5d5f6fa38d5376101">isInterpSlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4037548ce62acb9759955250737db54">isInterpAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbee773b6ce142455d118167c39d9e55">isInterpAttrChan</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c277e4ac58fb3d467ee4b1e79ea8917">isOpSel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d165eefdb757f6ae3f552e561392a45">isOpSelHi</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32631c2127fa524dee333410f73efd22">isNegLo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4806e14047291615ddfd5da09e4db72">isNegHi</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec16843edbdec91c49ac0ea4857faa58">isBitOp3</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2eb5ae7782040f081faca112c8751a4">isRegOrImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a> (unsigned RCID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e920b8d255e42d5f25ba3523c4dfe2b">isInlineValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a> (unsigned RCID, MVT type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a2ef063e52411078a05ed38a78109e">isSCSrcB16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49dd06edf45844598430469eb5ba9c33">isSCSrcV2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b85dea51a8ac8ba36bcda3858f57d3">isSCSrc_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec5d0b1b4c78021f85cf22845451ccb6">isSCSrc_b64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cd80536eb806cf601df1ea92cfb52cb">isBoolReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe6e09d714d34f23900758bd87f8840">isSCSrcF16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a924611bf8f1ccdae769548e0bce49067">isSCSrcV2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59f84455f84ea23e797eb02a9672276">isSCSrcF32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cd938ff442d1602fe62d30e42fdfad8">isSCSrcF64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2d0919dd1d18d1f5617d78bbacf2ce">isSSrc_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27647c5594cbbc99deef54fc824e06de">isSSrc_b16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a712f50d2f4b81d8945bbf9366a4d0">isSSrcV2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa47329d14cc95ec2898485fe287da91a">isSSrc_b64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c8e83fc3517ec8e0ce5574d6ff94ef5">isSSrc_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3dd4fb92d28eff3e3fb6771ca9cb8d">isSSrcF64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70eccbfa6352784e4e85d731d7e22a5">isSSrc_bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b4e5caaf16b9360c9899c64e2de90e">isSSrc_f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad95bd09e4da4a6a947ba80810b577655">isSSrcV2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b1fbf5c0f35dedfd59c4434764a320">isSSrcV2FP32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41e42626c4597a8ad5bc997073936cb">isSCSrcV2FP32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7663128eb6e48b1bf5e9d1b01308c9c4">isSSrcV2INT32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af987d979d12e6ac245c32a643b27ecb7">isSCSrcV2INT32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe79b6c6fd5b7698a29f3f94fd63aef5">isSSrcOrLds_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386abcbedfd5b6ba371c9def37351539">isVCSrc_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b7dd4bb81142c5731321483e6461de">isVCSrcB64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af560048eb60aa005581bb74c8de8514d">isVCSrcT_b16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96bb4d26e71bd18c598c1174f675dc2">isVCSrcTB16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1ab4a403d410775f974625c9e8bbf3">isVCSrcFake16B16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb012d4dea6b0f079fbc05723333b7b6">isVCSrc_b16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b486e40ff3f48896dd1a7adfc3268c">isVCSrc_v2b16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8fe12b49b0c7a03fed208cbca0e4ede">isVCSrc_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff38d575b028c1596d28fc393300701">isVCSrcF64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9167f9ce445e37760af3e633cf57d325">isVCSrcTBF16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d3dc1d4b1f15d460b7eeb7508468a1">isVCSrcT_f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb147ce6f7b5c838d0c761a7cf09462c">isVCSrcT_bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af262eb98370b66d63ebaeafdc2435d">isVCSrcTBF16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be4c430001a4138b47e2191c44adf53">isVCSrcTF16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad95e4108e84a29408d15e70712fb49f8">isVCSrcFake16BF16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41866dfbf7988eec964552aba0e25b4e">isVCSrcFake16F16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefde2f5a23cfc9346c6b3fcd2d733706">isVCSrc_bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c42d206ee8811a9f5b9cf76893527cd">isVCSrc_f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c18028aeea66d1b21de23e923304210">isVCSrc_v2bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd8cf6dea6a755409a07542bd7396d1e">isVCSrc_v2f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767d856a1fe976716636a331ece309e9">isVSrc_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48e0b8ebc7807de5f0898b1c4efe077">isVSrc_b64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1d0c2fde62ae9db0243656cc4bec98">isVSrcT_b16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ccc21f1a73275dfb48b5b37c1c4060">isVSrcT_b16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61fd9a51e14f86a2df225d3f30593fa4">isVSrcFake16_b16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a78c8a10831c329069d19520bec727">isVSrc_b16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac4df4fbe4b2def95eea6a719f8256d">isVSrc_v2b16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a35e61723df0a4620d1d9eae399d99">isVCSrcV2FP32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5268a4e8a67b227599b70277e9bcfe3">isVSrc_v2f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99212127f032d6bd2f0c8e243b6261b2">isVCSrcV2INT32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa509fd036e9e1ff80630fbe94d3b36e9">isVSrc_v2b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d88e23ab028267294b352ba3376ba6">isVSrc_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c847f04f640a6cee8c84c6dc5d9a4e">isVSrc_f64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef8393558f2ea052f688e52a6fb29e2">isVSrcT_bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1bcb6e01cf7df4c9e5832e599f6871">isVSrcT_f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace883242feabf817dc39df76f18057b1">isVSrcT_bf16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69719e896a69ca1b37a8a67f1e44d577">isVSrcT_f16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7133ae6c0fc99a9a42ba41b5e7749d64">isVSrcFake16_bf16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236d692826d993d12f6820d2bd06a09f">isVSrcFake16_f16_Lo128</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897d91246a144118d006758146eee34f">isVSrc_bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6b62e40304b958fbc9cca21aedecd3">isVSrc_f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278fb6f3f94caa89b9314d30fb8b8a1d">isVSrc_v2bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1faab935a964d13e28192fc113617167">isVSrc_v2f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb61f4a732360d17f93370deb9a0ffa">isVISrcB32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a178aac9b3c39e55d78166a3e09c56e7c">isVISrcB16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05867ecb624c2ff25e21cf921a71f9ec">isVISrcV2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16acb91bfaa1c96465ad2395e6980503">isVISrcF32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131c1dbcb24973df3162c4cd9a895cfd">isVISrcF16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d80a1ce12bd91ba8f5230c642b18a5">isVISrcV2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e2eea2f7a2fbade058478bb110097d">isVISrc_64_bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8122749572963ed4ec689ca5a6aefcc6">isVISrc_64_f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff2536b26ed64bef015303a55940abdb">isVISrc_64_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d9842857b54a442327e0421f12cb3f">isVISrc_64B64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecd4934e735853a422536b1142bcd220">isVISrc_64_f64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2befae16afca427baf113c4df64ad092">isVISrc_64V2FP32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be977b78fccf3bc5e4bb0d010f39ed0">isVISrc_64V2INT32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98517a2db7a49a6e3cf65637fa85df29">isVISrc_256_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e9368cdd06cb54ca0451fe539ca7be">isVISrc_256_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06fae9684d40680c27a7cdff14002f02">isVISrc_256B64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a230c7d81808c760417814d1524204432">isVISrc_256_f64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eaa6cfdf4d9aadc2b73ad97384d4f4c">isVISrc_128B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a855cd2736fbdf94c18bd5186504f6b9c">isVISrc_128V2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a323f8926dc3bd4035059453c35b3dff9">isVISrc_128_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada6c673fa523d8ed4b27aa6c9dfad133">isVISrc_128_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a342368eb65fa4139f7d64d773b555d8e">isVISrc_256V2FP32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ae33d7993058b88ffbef2c248d61f4">isVISrc_256V2INT32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ebb36021dbe87001abf22690bc273be">isVISrc_512_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accad7afcfebb95cc57ce6dc9a836a81f">isVISrc_512B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f8b1e163f8200c5f0e82dcc3980935">isVISrc_512V2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b84b6963b10b8a12bc3fce984d1858">isVISrc_512_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc993de986625bbfc437c75fe36b754">isVISrc_512F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad62c657e989e0536612f05a9e1a82b84">isVISrc_512V2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47fb7cc273d3e0a8fd2b1c9e4bbda26e">isVISrc_1024_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0de0e3a0dcf9154063738604789bc3">isVISrc_1024B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab304ee93e082e3f47e25205e0f45a933">isVISrc_1024V2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc685f044aa966f04ae5cafc6699456">isVISrc_1024_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ecdaa0c6e9b2e2259d8833c16251cb">isVISrc_1024F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa84245e288c5d5ceed645db238f6e1c1">isVISrc_1024V2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c0497a12d3d5857c1aaedc1dec4d38">isAISrcB32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a155240358886ddf8bdb8525fe7d0f2c9">isAISrcB16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab092e95490cdda5de65352e15ac2f33">isAISrcV2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d81bab67f67c41b6ad5833c29a2bb0">isAISrcF32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db362c0804c514fcc45d18c8004b401">isAISrcF16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e135dbc8993f8360d074e0cfbc3e62">isAISrcV2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ea92abeaae74671df203996e48d2714">isAISrc_64B64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07abf1a41d284dd9ee34e54ccf972281">isAISrc_64_f64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8241bca4b084ae7c30de8a215e062f31">isAISrc_128_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04d5468adfa929c4dbc107db8cea8cd">isAISrc_128B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81187873c772dde14bd90d42355944a">isAISrc_128V2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339e281b608635aa01077365ca9ba376">isAISrc_128_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a875393cbb193f917d69c3ed5f7a7fa">isAISrc_128F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9c1d3dd41437af975cac9819bab3df">isAISrc_128V2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835e61a24dfefa5a604441666ad3bb7c">isVISrc_128_bf16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5789e1699b1429db70c4150f303a668b">isVISrc_128_f16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920e2a4d3c8db2d41206ab1a06aae1c2">isVISrc_128V2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59b7e82a58ede7b90f31614902e2469b">isAISrc_256B64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bcde68cada557cf2506a721b95719f3">isAISrc_256_f64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41645fcd448ffbc022e30f23567b4083">isAISrc_512_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85882dcf462a2c26de897ca3b106ea12">isAISrc_512B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a023ee3f1db11d78038e47a9085e6fe28">isAISrc_512V2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5301b95a566274a772d9b3b3b54c7ec">isAISrc_512_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa803d77b9fbb9f0240715f4a33562fe8">isAISrc_512F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af73bcda9e253825e20f800a6426db74d">isAISrc_512V2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5bc81f35b0c979591d85a4a1ceabe2f">isAISrc_1024_b32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bd39009eb8ad39027b877174b5c9743">isAISrc_1024B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa37f7d35c22396e2a8060145affa206e">isAISrc_1024V2B16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df4f843ee08dcb8c5e7133907600e9b">isAISrc_1024_f32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40dcd0145862cddcc3ce7282b6f4cec">isAISrc_1024F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd33b6a63869f4930b4593af4ca64037">isAISrc_1024V2F16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997e38fe6a99acde82974dd007db24d8">isKImmFP32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e93961df200447d993f3bf673734da1">isKImmFP16</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d7135568ebfdeac7f03af08d5427436">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#a5d7135568ebfdeac7f03af08d5427436">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88cac794786119f504d4a0c96540f2ea">isSOPPBrTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c0054ad59c38b9015bc4522023e642">isSWaitCnt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b920d223fc1391f3d0b298e14aad4d2">isDepCtr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070ae269bd64d87b22d8bd6474290d14">isSDelayALU</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b621f40430eff61b4be310112c329f">isHwreg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e0d5026a7c5e1db816e171c633138f">isSendMsg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ec6c77a10cfb30ff6aedee4aeb7b99">isSplitBarrier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9c78c380195227929c91cae16f23aad">isSwizzle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb5a5e1ff09682ce9e0d40839407b8c8">isSMRDOffset8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c22221c009d60df43824066d41c2b39">isSMEMOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae97de6c7f089682bbfde546a6dccf6f7">isSMRDLiteralOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae46c476b2f39ee08d2deee5f5f965c35">isDPP8</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73d4a40efb842b0d24538c757cc5a52">isDPPCtrl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f99228b449f1ba1ba74ef5b658642b">isBLGP</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2f761e92ec85c58fd2803b2b890d92">isGPRIdxMode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb79ad2db74dd301e79b8145b9abfd87">isS16Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c064b45288d866bb619ff92c4ee78dd">isU16Imm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef2786a586d928f359f6380de338ab64">isEndpgm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91dc40d3f31eba33d29114a252798dff">getPredicate</a> (std::function&lt; bool(const AMDGPUOperand &amp;Op)&gt; P) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9836d66cf9617f7396887c361cbbded0">getToken</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0cc54c4806ee12ce6186629b182240">setImm</a> (int64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aac6196abacab3897ea9874e72d3db8fc">ImmTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f901d3b6a8c3b686d2f3408de0fb817">getImmTy</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2d5cb768dd61ffc311e44a67d7b292">getReg</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630948d3f118fad4a7e9d4764ba76a90">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#a630948d3f118fad4a7e9d4764ba76a90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753fbc4ea0c4af9a66d0824699f0ec7f">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#a753fbc4ea0c4af9a66d0824699f0ec7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a079421c8e1001bd9051a6c0191dd2599">getLocRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers">Modifiers</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2051721c4ee3fcd990beca23c4aa40">setModifiers</a> (Modifiers Mods)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a33b1fc06b8891f726f8c241fe573ef">hasModifiers</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ece6ef27f16a3ea9528fd3063131057">hasFPModifiers</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7206d13152e3586c728658a12489aabc">hasIntModifiers</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3252f98d20c96f775dd0286d1a2f830">applyInputFPModifiers</a> (uint64_t Val, unsigned Size) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a> (MCInst &amp;Inst, unsigned N, bool ApplyModifiers=true) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa952aa5bfb51a38178c0d47e0fc7aa7b">addLiteralImmOperand</a> (MCInst &amp;Inst, int64_t Val, bool ApplyModifiers) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa66df54e14d6219d63e025455bfe52ae">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26bad8e09401457e56c428aa16473a53">addRegOrImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625e5c93b568541975f28a4ad8746c4c">addRegOrImmWithInputModsOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12cbac6ccf1479b95d5f037a4e0721ce">addRegOrImmWithFPInputModsOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd65dfd459b859d9234fac35f3513f6">addRegOrImmWithIntInputModsOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31034030d9e1080963a9033b29df4df8">addRegWithInputModsOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33dbb12eab27e5ccb053b79af2fc9686">addRegWithFPInputModsOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0bd16ede66efa2c0ef9f34924fbc39d">addRegWithIntInputModsOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f08b8953c3266dd113feccca78d6d12">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a6f08b8953c3266dd113feccca78d6d12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsFake16&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afee6a95dc973633bcdc0374c5818d1c4">isT16_Lo128VRegWithInputMods</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsFake16&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acc384733bb6f91a5031c0e48c09962e1">isT16VRegWithInputMods</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">TokOp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1720fbf7efeb1ec77165c477b8d425c6">Tok</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ImmOp</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b514e34f4f64815edf9cc75f16d1c3e">Reg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414289a5d7344879a8c5d516f3bdab86">Expr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{AMDGPUAsmParser.cpp}::AMDGPUOperand::KindTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab954bc1f2652c7944e9ff2879bbfea">Kind</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256f9a512e08b63e3f303e6ca808f196">StartLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa402a81bfaac6401d2c34e5621789452">EndLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser">AMDGPUAsmParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a178b1222a97385c6745ffc5f0fe4cb32">AsmParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{AMDGPUAsmParser.cpp}<a href="#a819c0cb08510ccd01fd5615d66fe0955">::AMDGPUOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9444ed4bbedf5ff68ed5bff8e2ee4d1"></a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219ae81b494ba96fd79663c2f27e6552">printImmTy</a> (raw_ostream &amp;OS, ImmTy Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ace54d060c027c4de4bd81706c19355fb">AMDGPUOperand::Ptr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d2ada1e702e79ab63562d3cbd03ee0">CreateImm</a> (const AMDGPUAsmParser *AsmParser, int64_t Val, SMLoc Loc, ImmTy Type=ImmTyNone, bool IsFPImm=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ace54d060c027c4de4bd81706c19355fb">AMDGPUOperand::Ptr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f085efcb427da17842f4447cea3d0d5">CreateToken</a> (const AMDGPUAsmParser *AsmParser, StringRef Str, SMLoc Loc, bool HasExplicitEncodingSize=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ace54d060c027c4de4bd81706c19355fb">AMDGPUOperand::Ptr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ceb192ff77adbd8ddbbddaa9a38ae99">CreateReg</a> (const AMDGPUAsmParser *AsmParser, MCRegister Reg, SMLoc S, SMLoc E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ace54d060c027c4de4bd81706c19355fb">AMDGPUOperand::Ptr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e67ee2af4aa2b58e472d12c10b2a427">CreateExpr</a> (const AMDGPUAsmParser *AsmParser, const class MCExpr *Expr, SMLoc S)</td>
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


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Ptr {#ace54d060c027c4de4bd81706c19355fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Ptr =  std::unique_ptr&lt;AMDGPUOperand&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ImmKindTy {#aa817fddb7d8c888c671fcebc15b4b76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmKindTy </td>
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
<td class="doxyEnumItemName">ImmKindTyNone<a id="aa817fddb7d8c888c671fcebc15b4b76aa9de751338cf92de88f4221d6ba6259ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmKindTyLiteral<a id="aa817fddb7d8c888c671fcebc15b4b76aa2bd93559ed7f83abbcde5cf9ecaeacb1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmKindTyMandatoryLiteral<a id="aa817fddb7d8c888c671fcebc15b4b76aa855228a5582f02236bfcb17481d6526e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmKindTyConst<a id="aa817fddb7d8c888c671fcebc15b4b76aa50e29a2fb9d43a6171af09db28869683"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### ImmTy {#aac6196abacab3897ea9874e72d3db8fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::ImmTy </td>
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
<td class="doxyEnumItemName">ImmTyNone<a id="aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyGDS<a id="aac6196abacab3897ea9874e72d3db8fcad673fd3693f21e595b61e0efcfebace7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyLDS<a id="aac6196abacab3897ea9874e72d3db8fca80ad15588035616b5caa13260dc56b08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyOffen<a id="aac6196abacab3897ea9874e72d3db8fca3fe0f6956d2f2effc84c174dc25a2b22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyIdxen<a id="aac6196abacab3897ea9874e72d3db8fcad781363033c69b70fe169821750b5382"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyAddr64<a id="aac6196abacab3897ea9874e72d3db8fca2e44e7cd0be59ea7aec6573e8ee82b11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyOffset<a id="aac6196abacab3897ea9874e72d3db8fca02f46f2486aed0107b1313c8c7bae9b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyInstOffset<a id="aac6196abacab3897ea9874e72d3db8fca45cf846b7e62d831b596bccad4de5315"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyOffset0<a id="aac6196abacab3897ea9874e72d3db8fca5f8d155a94f097a3022ae8a9b7d2e4f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyOffset1<a id="aac6196abacab3897ea9874e72d3db8fca584b3a4b355022c91b09dbbd3f2b1405"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTySMEMOffsetMod<a id="aac6196abacab3897ea9874e72d3db8fca0ccfbff250cbfb289053232b65749936"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyCPol<a id="aac6196abacab3897ea9874e72d3db8fcae93a1de3d01070de353bc7ac2c243eaf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyTFE<a id="aac6196abacab3897ea9874e72d3db8fca0d40ab857cb9338f800d4102f5a5fb3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyD16<a id="aac6196abacab3897ea9874e72d3db8fcade6e1db88c135faeb133cc36d84133db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyClamp<a id="aac6196abacab3897ea9874e72d3db8fcaf005c69ec582b7a5d66df13f4e317a1e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyOModSI<a id="aac6196abacab3897ea9874e72d3db8fcaf4e10bb6d0fda8ad54cca3f45eb2b143"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTySDWADstSel<a id="aac6196abacab3897ea9874e72d3db8fca5ef6d8d490dc55a1a768223f15a959a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTySDWASrc0Sel<a id="aac6196abacab3897ea9874e72d3db8fcae0c54cec4b9a48401c2fd0dc32b9da24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTySDWASrc1Sel<a id="aac6196abacab3897ea9874e72d3db8fca066b849c42884b62cdb679dd05d1c28d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTySDWADstUnused<a id="aac6196abacab3897ea9874e72d3db8fca38365958fa12a0f2acd965b2bc77ea00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDMask<a id="aac6196abacab3897ea9874e72d3db8fca1f29992c88d5b26bf766e3df3df8cd08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDim<a id="aac6196abacab3897ea9874e72d3db8fcaf6aeca3fc739d2f9fa57dfe5180bb8cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyUNorm<a id="aac6196abacab3897ea9874e72d3db8fca0c4e23b098ddd5180afbf78977ed41af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDA<a id="aac6196abacab3897ea9874e72d3db8fca81a6f096c7f264f016225663a3d4870e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyR128A16<a id="aac6196abacab3897ea9874e72d3db8fcaf99873ea3e78297b518afa494e67c3c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyA16<a id="aac6196abacab3897ea9874e72d3db8fca3927f830d00f75bb2e2aba10856298af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyLWE<a id="aac6196abacab3897ea9874e72d3db8fca0cfc729dac9bc32b37a71468c6bdf5d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyExpTgt<a id="aac6196abacab3897ea9874e72d3db8fca8b92c2d67ca16440f8c439f063c4c32b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyExpCompr<a id="aac6196abacab3897ea9874e72d3db8fca2ff55b791397522185702a9ff4701ef5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyExpVM<a id="aac6196abacab3897ea9874e72d3db8fca5b645a3daa82f94403a3ae30c2ab1089"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyFORMAT<a id="aac6196abacab3897ea9874e72d3db8fca86191e0af51710ca8b408b289300cf0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyHwreg<a id="aac6196abacab3897ea9874e72d3db8fcac8698f7407c44136e38a954eee31ec18"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyOff<a id="aac6196abacab3897ea9874e72d3db8fca96a2e9977c530f18cdc5cdde12de257b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTySendMsg<a id="aac6196abacab3897ea9874e72d3db8fcac149121124fe545cec0d7688ea39f435"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyInterpSlot<a id="aac6196abacab3897ea9874e72d3db8fcac16758e9406b631d54854588a576a29c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyInterpAttr<a id="aac6196abacab3897ea9874e72d3db8fca2d980b3c725150072bc1bca3b9717703"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyInterpAttrChan<a id="aac6196abacab3897ea9874e72d3db8fcadc4ee0d2f112f47edabec0e19de95b2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyOpSel<a id="aac6196abacab3897ea9874e72d3db8fcaf3ba690efda9412129e1195c93663d18"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyOpSelHi<a id="aac6196abacab3897ea9874e72d3db8fca7e67cef1f3b30e0fc5a6fc222f578c13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyNegLo<a id="aac6196abacab3897ea9874e72d3db8fca4ebfe90c5e76cde6ee3867f75a62f8a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyNegHi<a id="aac6196abacab3897ea9874e72d3db8fca2ee46e789b1dd972067b15f482dacf06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyIndexKey8bit<a id="aac6196abacab3897ea9874e72d3db8fca3b0787bbfe8d09244425732c5a8840d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyIndexKey16bit<a id="aac6196abacab3897ea9874e72d3db8fca4df6d1cb3360e33d52bed3dd55d9342e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDPP8<a id="aac6196abacab3897ea9874e72d3db8fcaf79a7cadd64c125693239a99d15776d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDppCtrl<a id="aac6196abacab3897ea9874e72d3db8fca9e3ba413ec741a423d42d99974585677"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDppRowMask<a id="aac6196abacab3897ea9874e72d3db8fca8bb6ce8b62f92662c470a40065d126af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDppBankMask<a id="aac6196abacab3897ea9874e72d3db8fca107c472f8bfeb150ed0737921a85e408"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDppBoundCtrl<a id="aac6196abacab3897ea9874e72d3db8fca9551790c26c1cb431ce82ab01f748a53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyDppFI<a id="aac6196abacab3897ea9874e72d3db8fca07d5a47db7db2fcf76162ad332f72686"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTySwizzle<a id="aac6196abacab3897ea9874e72d3db8fcae245f2c36be17caa96752cf101b62796"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyGprIdxMode<a id="aac6196abacab3897ea9874e72d3db8fcad4fc7a84a69230aae91424d2ef3daf73"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyHigh<a id="aac6196abacab3897ea9874e72d3db8fcab73f5f2d6a06746d900ab0d87a8e76e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyBLGP<a id="aac6196abacab3897ea9874e72d3db8fcaf1b6a24364959b43f2ba2a7cbe099577"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyCBSZ<a id="aac6196abacab3897ea9874e72d3db8fcac9aae4585818d04952ecfcdd0e508ba6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyABID<a id="aac6196abacab3897ea9874e72d3db8fcaff79a4732a62ef261c2666f8969ffbc2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyEndpgm<a id="aac6196abacab3897ea9874e72d3db8fca53303dcc815ab55f8a1f737852055ded"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyWaitVDST<a id="aac6196abacab3897ea9874e72d3db8fca17398b0656ee9d08f195d7bbe365a579"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyWaitEXP<a id="aac6196abacab3897ea9874e72d3db8fcadeeea91bbd0d55b997e0f5291a4a1a7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyWaitVAVDst<a id="aac6196abacab3897ea9874e72d3db8fca5420c16e9aeb6a59d9e86fd7e27fe1a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyWaitVMVSrc<a id="aac6196abacab3897ea9874e72d3db8fca5d154083374c99ac14f3f41fc325df26"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyByteSel<a id="aac6196abacab3897ea9874e72d3db8fca040e9137b23fb0a740bfb222d4911c49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmTyBitOp3<a id="aac6196abacab3897ea9874e72d3db8fcaeebf6baf32daa73a0a7b0357b663e6c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### KindTy {#af9c6a8670c2e9f278e168dff44b39ada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::KindTy </td>
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
<td class="doxyEnumItemName">Token<a id="af9c6a8670c2e9f278e168dff44b39adaa075eb44520b8854bef3a79124d4a06c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Immediate<a id="af9c6a8670c2e9f278e168dff44b39adaa97b09ddbddb105b84b7b0098f2d0637f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="af9c6a8670c2e9f278e168dff44b39adaa0ecd7d55231cfda6ccc537fbe35597af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Expression<a id="af9c6a8670c2e9f278e168dff44b39adaa2ffbc4b6991bd6c1390f8309ddf8e0ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AMDGPUOperand() {#a819c0cb08510ccd01fd5615d66fe0955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::AMDGPUOperand (KindTy Kind_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser">AMDGPUAsmParser</a> * AsmParser_)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ab8e8537ee53695e10c4b4d9e0f1da12e">addSrcModifiersAndSrc</a>, <a href="#a91dc40d3f31eba33d29114a252798dff">getPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ae58d7ce01c34f2ecb225e1dedfa736e3">isInvalidVOPDY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addImmOperands() {#aecc4bcb6c40064c4c0544f55facbb18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUOperand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N, bool ApplyModifiers=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1033 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aa952aa5bfb51a38178c0d47e0fc7aa7b">addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a414289a5d7344879a8c5d516f3bdab86">Expr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#a0398502ffb1ec5484d4135a1adf0d5fa">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::hasModifiers</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, <a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a>, <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>, <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7fba5af4359eeeef753f1c286ea8d0d7">llvm::AMDGPU::isSISrcOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#adfa64c48e281a33a5607fc828e5ad626">setImmKindNone</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="#a26bad8e09401457e56c428aa16473a53">addRegOrImmOperands</a> and <a href="#a625e5c93b568541975f28a4ad8746c4c">addRegOrImmWithInputModsOperands</a>.</p>

</div>
</div>

### addLiteralImmOperand() {#aa952aa5bfb51a38178c0d47e0fc7aa7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUOperand::addLiteralImmOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, int64_t Val, bool ApplyModifiers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="#ae3252f98d20c96f775dd0286d1a2f830">applyInputFPModifiers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a40c7fb73978096ed317dd71fb8a84cf4">llvm::MCInst::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#adddee5b33e7c032620042dfdb9fa1634">llvm::AMDGPU::getOperandSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ae548c8a19a1775280fbea6ecd754363f">getOpFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a901ba4ff66898215882da41143ddf69a">llvm::AMDGPU::isInlinableIntLiteral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a79ce723bbdcb8a66b32fec6499ecd9f9">llvm::AMDGPU::isInlinableLiteral32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af4cb2c8159c390d78b6a547ac87179ae">llvm::AMDGPU::isInlinableLiteral64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0243bafd9ec35896d5329c743ec1b545">llvm::AMDGPU::isInlinableLiteralBF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0d8a9668df772986cb7ab4cd7092b58e">llvm::AMDGPU::isInlinableLiteralFP16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#af9f73de55db8e160861464e29ab9ab39">isSafeTruncation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa773b952c1097dcbb09e99bd4cd3b802">llvm::AMDGPU::isSISrcFPOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7fba5af4359eeeef753f1c286ea8d0d7">llvm::AMDGPU::isSISrcOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3ad7da1b76e5799f53a399b7a96ba67437">llvm::Literal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a901112c493d3827cda924430a6fbc9f4">llvm::Lo_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af4b9cc7ae4320e5423baac7b35410470">llvm::AMDGPU::OPERAND_INLINE_SPLIT_BARRIER_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a887993ba93e1d73774d547bbe51e0317">llvm::AMDGPU::OPERAND_KIMM16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a09dd1263fb2164c20f99f89f69e01a6e">llvm::AMDGPU::OPERAND_KIMM32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a4a3081e798f991d04637c07ba0edf448">llvm::AMDGPU::OPERAND_REG_IMM_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a78981b9ce721164ac724d51f2c4f0a32">llvm::AMDGPU::OPERAND_REG_IMM_BF16_DEFERRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a7bcafeceef57e87bc524d5cc035837d5">llvm::AMDGPU::OPERAND_REG_IMM_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aff389f984e981455b4107b4708a77e5b">llvm::AMDGPU::OPERAND_REG_IMM_FP16_DEFERRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa7f8a98ec46b1d30189640d9ff59bc1e">llvm::AMDGPU::OPERAND_REG_IMM_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af8ac73c62f6f1da6175d32824633a064">llvm::AMDGPU::OPERAND_REG_IMM_FP32_DEFERRED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a96e7ee25f7665368353ac98b104770a1">llvm::AMDGPU::OPERAND_REG_IMM_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aea3ce103b7ba06ee5ca50925e7064101">llvm::AMDGPU::OPERAND_REG_IMM_INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a5df5b6b6089b9237400d2c422db445d8">llvm::AMDGPU::OPERAND_REG_IMM_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a206ff13aa7a98aac961a631569867e3d">llvm::AMDGPU::OPERAND_REG_IMM_INT64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a69bbd47f175c95849d7a6086a6550a66">llvm::AMDGPU::OPERAND_REG_IMM_V2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a20958300f68759315cb6cb2491d42cec">llvm::AMDGPU::OPERAND_REG_IMM_V2FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae0f1ac0de50b2280311f02d7e1f5b25e">llvm::AMDGPU::OPERAND_REG_IMM_V2FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a455e964e5660b09e16a498dd96cf0bd6">llvm::AMDGPU::OPERAND_REG_IMM_V2INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa3d68df7f69a18a66156e5e08c2c7504">llvm::AMDGPU::OPERAND_REG_IMM_V2INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a8c06c3c283a06956e261937775ff3838">llvm::AMDGPU::OPERAND_REG_INLINE_AC_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9eb871898b75ab91e808faf50f5f41a5">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa10ec5681f77906549e7a745593139a9">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae51ff25f16b928b2b8712a613e4fd3db">llvm::AMDGPU::OPERAND_REG_INLINE_AC_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9242629e3f7e6539015220a3d77d7dc7">llvm::AMDGPU::OPERAND_REG_INLINE_AC_INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9f903a56d49f51a4697c5198aaea3459">llvm::AMDGPU::OPERAND_REG_INLINE_AC_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5aa122eae99199c0ac86716819fde2efc9">llvm::AMDGPU::OPERAND_REG_INLINE_AC_V2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a52eeb3170ac03d3af5c8ea11b06ea93c">llvm::AMDGPU::OPERAND_REG_INLINE_AC_V2FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9dfb8a7518a9154161c7a05b644e6e47">llvm::AMDGPU::OPERAND_REG_INLINE_AC_V2INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a3d11c500720aebcbecc6b2b1291b468f">llvm::AMDGPU::OPERAND_REG_INLINE_C_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ae6c8f9b5c5805da722239e1e5d8cda5d">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ac073c33efc03a1882ee8155b8d68a794">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a2f2cb7a6e0c1e04d17d4a2d79dfc85ca">llvm::AMDGPU::OPERAND_REG_INLINE_C_FP64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a8d695369aef7c9f7e0589f5b4673ea46">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ad670957823c39ba1006b962d2023a19a">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a86ef6f68b415f39fcd28ae0dd431297c">llvm::AMDGPU::OPERAND_REG_INLINE_C_INT64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a431ef474cd3520ce1676091d1297cbac">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a9babf1fd52dcf14ed0effdd6fe207007">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5af49dc86d5a2c2386386ce4c0023cfd0f">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2FP32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5ad6dad922f054838a22df6973a79987be">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2INT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab7679ce5eab5937b9da9e7702aff8cc5a240a6f2882eded67e4b70c6bb2f18411">llvm::AMDGPU::OPERAND_REG_INLINE_C_V2INT32</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="#a6a8d2feece61e3394cb02d59351ea70f">setImmKindConst</a>, <a href="#a3a0ff009144236a6532b574438a50a45">setImmKindLiteral</a>, <a href="#aa62444e32183814cbc01fb3c82c10eee">setImmKindMandatoryLiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>


<p>Referenced by <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>.</p>

</div>
</div>

### addRegOperands() {#aa66df54e14d6219d63e025455bfe52ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUOperand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a12457438c2b018b673e22e0253e466c4">llvm::AMDGPU::getMCReg</a>, <a href="#a5c2d5cb768dd61ffc311e44a67d7b292">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a26bad8e09401457e56c428aa16473a53">addRegOrImmOperands</a>, <a href="#a625e5c93b568541975f28a4ad8746c4c">addRegOrImmWithInputModsOperands</a>, <a href="#a31034030d9e1080963a9033b29df4df8">addRegWithInputModsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#adfaf977dc82c560bd265a68c807cd1a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a57878d0e3afa7d6e659b92b9d71c0923">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a238abfd2ac2842861ab322354aec3d64">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSWMMAC</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac4e2add1506387486f82ff6117a6a0e4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVINTERP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a81d4a718e3a11c1c3507fb28db101cf6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af30bfdcbe6574a1d0de2c2c59c1a8f18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3Interp</a>.</p>

</div>
</div>

### addRegOrImmOperands() {#a26bad8e09401457e56c428aa16473a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>, <a href="#aa66df54e14d6219d63e025455bfe52ae">addRegOperands</a>, <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOrImmWithFPInputModsOperands() {#a12cbac6ccf1479b95d5f037a4e0721ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmWithFPInputModsOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a625e5c93b568541975f28a4ad8746c4c">addRegOrImmWithInputModsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7206d13152e3586c728658a12489aabc">hasIntModifiers</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ab8e8537ee53695e10c4b4d9e0f1da12e">addSrcModifiersAndSrc</a>.</p>

</div>
</div>

### addRegOrImmWithInputModsOperands() {#a625e5c93b568541975f28a4ad8746c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmWithInputModsOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="#aa66df54e14d6219d63e025455bfe52ae">addRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#ada136502e3d7a5a724a17eb1339b6c51">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::getModifiersOperand</a>, <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a12cbac6ccf1479b95d5f037a4e0721ce">addRegOrImmWithFPInputModsOperands</a> and <a href="#a9fd65dfd459b859d9234fac35f3513f6">addRegOrImmWithIntInputModsOperands</a>.</p>

</div>
</div>

### addRegOrImmWithIntInputModsOperands() {#a9fd65dfd459b859d9234fac35f3513f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmWithIntInputModsOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a625e5c93b568541975f28a4ad8746c4c">addRegOrImmWithInputModsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6ece6ef27f16a3ea9528fd3063131057">hasFPModifiers</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegWithFPInputModsOperands() {#a33dbb12eab27e5ccb053b79af2fc9686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegWithFPInputModsOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a31034030d9e1080963a9033b29df4df8">addRegWithInputModsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7206d13152e3586c728658a12489aabc">hasIntModifiers</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegWithInputModsOperands() {#a31034030d9e1080963a9033b29df4df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegWithInputModsOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="#aa66df54e14d6219d63e025455bfe52ae">addRegOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#ada136502e3d7a5a724a17eb1339b6c51">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::getModifiersOperand</a>, <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a33dbb12eab27e5ccb053b79af2fc9686">addRegWithFPInputModsOperands</a> and <a href="#ab0bd16ede66efa2c0ef9f34924fbc39d">addRegWithIntInputModsOperands</a>.</p>

</div>
</div>

### addRegWithIntInputModsOperands() {#ab0bd16ede66efa2c0ef9f34924fbc39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegWithIntInputModsOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a31034030d9e1080963a9033b29df4df8">addRegWithInputModsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6ece6ef27f16a3ea9528fd3063131057">hasFPModifiers</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### applyInputFPModifiers() {#ae3252f98d20c96f775dd0286d1a2f830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AMDGPUOperand::applyInputFPModifiers (uint64_t Val, unsigned Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#aa952aa5bfb51a38178c0d47e0fc7aa7b">addLiteralImmOperand</a>.</p>

</div>
</div>

### getEndLoc() {#a753fbc4ea0c4af9a66d0824699f0ec7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getEndLoc ()</td>
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

<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getImm() {#a9be6a3c0e7c06fd610c52d9654ee3f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="#aec16843edbdec91c49ac0ea4857faa58">isBitOp3</a>, <a href="#a43f99228b449f1ba1ba74ef5b658642b">isBLGP</a>, <a href="#ad73d4a40efb842b0d24538c757cc5a52">isDPPCtrl</a>, <a href="#a843ebc10c0fc3b71d7c5aeca93af90cc">isFORMAT</a>, <a href="#abb79ad2db74dd301e79b8145b9abfd87">isS16Imm</a>, <a href="#ae97de6c7f089682bbfde546a6dccf6f7">isSMRDLiteralOffset</a>, <a href="#adb5a5e1ff09682ce9e0d40839407b8c8">isSMRDOffset8</a>, <a href="#a1c064b45288d866bb619ff92c4ee78dd">isU16Imm</a> and <a href="#a6f08b8953c3266dd113feccca78d6d12">print</a>.</p>

</div>
</div>

### getImmTy() {#a9f901d3b6a8c3b686d2f3408de0fb817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmTy anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getImmTy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="#a43f99228b449f1ba1ba74ef5b658642b">isBLGP</a>, <a href="#ad73d4a40efb842b0d24538c757cc5a52">isDPPCtrl</a> and <a href="#a6f08b8953c3266dd113feccca78d6d12">print</a>.</p>

</div>
</div>

### getLocRange() {#a079421c8e1001bd9051a6c0191dd2599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getLocRange ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### getModifiers() {#a9635992e290c74d396d5f1ad11626fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Modifiers anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getModifiers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>, <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a> and <a href="#a4b514e34f4f64815edf9cc75f16d1c3e">Reg</a>.</p>


<p>Referenced by <a href="#a625e5c93b568541975f28a4ad8746c4c">addRegOrImmWithInputModsOperands</a>, <a href="#a31034030d9e1080963a9033b29df4df8">addRegWithInputModsOperands</a>, <a href="#a6ece6ef27f16a3ea9528fd3063131057">hasFPModifiers</a>, <a href="#a7206d13152e3586c728658a12489aabc">hasIntModifiers</a> and <a href="#a8a33b1fc06b8891f726f8c241fe573ef">hasModifiers</a>.</p>

</div>
</div>

### getPredicate() {#a91dc40d3f31eba33d29114a252798dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getPredicate (std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand">AMDGPUOperand</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>)&gt; P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a819c0cb08510ccd01fd5615d66fe0955">AMDGPUOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getReg() {#a5c2d5cb768dd61ffc311e44a67d7b292}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getReg ()</td>
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



<p>Definition at line 989 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a> and <a href="#a4b514e34f4f64815edf9cc75f16d1c3e">Reg</a>.</p>


<p>Referenced by <a href="#aa66df54e14d6219d63e025455bfe52ae">addRegOperands</a>, <a href="#a3e920b8d255e42d5f25ba3523c4dfe2b">isInlineValue</a> and <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a>.</p>

</div>
</div>

### getStartLoc() {#a630948d3f118fad4a7e9d4764ba76a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getStartLoc ()</td>
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

<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a6bffa32d06d1516ee01e79b5a250c72e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::matchAndEmitInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>.</p>

</div>
</div>

### getToken() {#a9836d66cf9617f7396887c361cbbded0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::getToken ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5d8227b613dc0aff33ca27637d41c74a">isToken</a> and <a href="#a1720fbf7efeb1ec77165c477b8d425c6">Tok</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3740088be499ac1b2813ea1d6904ef15">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isModifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a6bffa32d06d1516ee01e79b5a250c72e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a332d48815071fdb4e2e94e999c154559">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDimId</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab65e752ef8a4ee9e6df01039bfa00b0e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parsePrimaryExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abe4d54f7147e2f219afa02529b48a0d0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegister</a>.</p>

</div>
</div>

### hasFPModifiers() {#a6ece6ef27f16a3ea9528fd3063131057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::hasFPModifiers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>.</p>


<p>Referenced by <a href="#a9fd65dfd459b859d9234fac35f3513f6">addRegOrImmWithIntInputModsOperands</a> and <a href="#ab0bd16ede66efa2c0ef9f34924fbc39d">addRegWithIntInputModsOperands</a>.</p>

</div>
</div>

### hasIntModifiers() {#a7206d13152e3586c728658a12489aabc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::hasIntModifiers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>.</p>


<p>Referenced by <a href="#a12cbac6ccf1479b95d5f037a4e0721ce">addRegOrImmWithFPInputModsOperands</a> and <a href="#a33dbb12eab27e5ccb053b79af2fc9686">addRegWithFPInputModsOperands</a>.</p>

</div>
</div>

### hasModifiers() {#a8a33b1fc06b8891f726f8c241fe573ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::hasModifiers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>.</p>


<p>Referenced by <a href="#a6323b2f7c53b4ebcbd057da0f366ed8d">isReg</a> and <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAddr64() {#a5da081c55cdc6b6177d44f16709f407f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAddr64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca2e44e7cd0be59ea7aec6573e8ee82b11">ImmTyAddr64</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isAISrc\_1024\_b32() {#ab5bc81f35b0c979591d85a4a1ceabe2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_1024_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#abd33b6a63869f4930b4593af4ca64037">isAISrc_1024V2F16</a>.</p>

</div>
</div>

### isAISrc\_1024\_f32() {#a2df4f843ee08dcb8c5e7133907600e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_1024_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAISrc\_1024B16() {#a1bd39009eb8ad39027b877174b5c9743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_1024B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#aa37f7d35c22396e2a8060145affa206e">isAISrc_1024V2B16</a>.</p>

</div>
</div>

### isAISrc\_1024F16() {#ab40dcd0145862cddcc3ce7282b6f4cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_1024F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#abd33b6a63869f4930b4593af4ca64037">isAISrc_1024V2F16</a>.</p>

</div>
</div>

### isAISrc\_1024V2B16() {#aa37f7d35c22396e2a8060145affa206e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_1024V2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a1bd39009eb8ad39027b877174b5c9743">isAISrc_1024B16</a>.</p>

</div>
</div>

### isAISrc\_1024V2F16() {#abd33b6a63869f4930b4593af4ca64037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_1024V2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#ab5bc81f35b0c979591d85a4a1ceabe2f">isAISrc_1024_b32</a> and <a href="#ab40dcd0145862cddcc3ce7282b6f4cec">isAISrc_1024F16</a>.</p>

</div>
</div>

### isAISrc\_128\_b32() {#a8241bca4b084ae7c30de8a215e062f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_128_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a0b9c1d3dd41437af975cac9819bab3df">isAISrc_128V2F16</a>.</p>

</div>
</div>

### isAISrc\_128\_f32() {#a339e281b608635aa01077365ca9ba376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_128_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAISrc\_128B16() {#ab04d5468adfa929c4dbc107db8cea8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_128B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#af81187873c772dde14bd90d42355944a">isAISrc_128V2B16</a>.</p>

</div>
</div>

### isAISrc\_128F16() {#a0a875393cbb193f917d69c3ed5f7a7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_128F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a0b9c1d3dd41437af975cac9819bab3df">isAISrc_128V2F16</a>.</p>

</div>
</div>

### isAISrc\_128V2B16() {#af81187873c772dde14bd90d42355944a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_128V2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#ab04d5468adfa929c4dbc107db8cea8cd">isAISrc_128B16</a>.</p>

</div>
</div>

### isAISrc\_128V2F16() {#a0b9c1d3dd41437af975cac9819bab3df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_128V2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a8241bca4b084ae7c30de8a215e062f31">isAISrc_128_b32</a> and <a href="#a0a875393cbb193f917d69c3ed5f7a7fa">isAISrc_128F16</a>.</p>

</div>
</div>

### isAISrc\_256\_f64() {#a8bcde68cada557cf2506a721b95719f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_256_f64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAISrc\_256B64() {#a59b7e82a58ede7b90f31614902e2469b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_256B64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAISrc\_512\_b32() {#a41645fcd448ffbc022e30f23567b4083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_512_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#af73bcda9e253825e20f800a6426db74d">isAISrc_512V2F16</a>.</p>

</div>
</div>

### isAISrc\_512\_f32() {#ad5301b95a566274a772d9b3b3b54c7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_512_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAISrc\_512B16() {#a85882dcf462a2c26de897ca3b106ea12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_512B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a023ee3f1db11d78038e47a9085e6fe28">isAISrc_512V2B16</a>.</p>

</div>
</div>

### isAISrc\_512F16() {#aa803d77b9fbb9f0240715f4a33562fe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_512F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#af73bcda9e253825e20f800a6426db74d">isAISrc_512V2F16</a>.</p>

</div>
</div>

### isAISrc\_512V2B16() {#a023ee3f1db11d78038e47a9085e6fe28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_512V2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a85882dcf462a2c26de897ca3b106ea12">isAISrc_512B16</a>.</p>

</div>
</div>

### isAISrc\_512V2F16() {#af73bcda9e253825e20f800a6426db74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_512V2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a41645fcd448ffbc022e30f23567b4083">isAISrc_512_b32</a> and <a href="#aa803d77b9fbb9f0240715f4a33562fe8">isAISrc_512F16</a>.</p>

</div>
</div>

### isAISrc\_64\_f64() {#a07abf1a41d284dd9ee34e54ccf972281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_64_f64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAISrc\_64B64() {#a6ea92abeaae74671df203996e48d2714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrc_64B64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAISrcB16() {#a155240358886ddf8bdb8525fe7d0f2c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrcB16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#aab092e95490cdda5de65352e15ac2f33">isAISrcV2B16</a>.</p>

</div>
</div>

### isAISrcB32() {#aa5c0497a12d3d5857c1aaedc1dec4d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrcB32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ad9e135dbc8993f8360d074e0cfbc3e62">isAISrcV2F16</a>.</p>

</div>
</div>

### isAISrcF16() {#a0db362c0804c514fcc45d18c8004b401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrcF16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ad9e135dbc8993f8360d074e0cfbc3e62">isAISrcV2F16</a>.</p>

</div>
</div>

### isAISrcF32() {#ac8d81bab67f67c41b6ad5833c29a2bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrcF32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isAISrcV2B16() {#aab092e95490cdda5de65352e15ac2f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrcV2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a155240358886ddf8bdb8525fe7d0f2c9">isAISrcB16</a>.</p>

</div>
</div>

### isAISrcV2F16() {#ad9e135dbc8993f8360d074e0cfbc3e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isAISrcV2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aa5c0497a12d3d5857c1aaedc1dec4d38">isAISrcB32</a> and <a href="#a0db362c0804c514fcc45d18c8004b401">isAISrcF16</a>.</p>

</div>
</div>

### isBitOp3() {#aec16843edbdec91c49ac0ea4857faa58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isBitOp3 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaeebf6baf32daa73a0a7b0357b663e6c9">ImmTyBitOp3</a>, <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isBLGP() {#a43f99228b449f1ba1ba74ef5b658642b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isBLGP ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#a9f901d3b6a8c3b686d2f3408de0fb817">getImmTy</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaf1b6a24364959b43f2ba2a7cbe099577">ImmTyBLGP</a>, <a href="#ae14745a72acdb68188b6dc3991cc3dfe">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isBoolReg() {#a6cd80536eb806cf601df1ea92cfb52cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isBoolReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a6323b2f7c53b4ebcbd057da0f366ed8d">isReg</a>, <a href="#a55b85dea51a8ac8ba36bcda3858f57d3">isSCSrc_b32</a> and <a href="#aec5d0b1b4c78021f85cf22845451ccb6">isSCSrc_b64</a>.</p>

</div>
</div>

### isCPol() {#ad31d84f19e1ed3db03f69e88510be043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isCPol ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcae93a1de3d01070de353bc7ac2c243eaf">ImmTyCPol</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isDepCtr() {#a8b920d223fc1391f3d0b298e14aad4d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isDepCtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#abb79ad2db74dd301e79b8145b9abfd87">isS16Imm</a>.</p>

</div>
</div>

### isDim() {#a725441e4bc10087cf4158f40684ff7d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isDim ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcaf6aeca3fc739d2f9fa57dfe5180bb8cd">ImmTyDim</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isDPP8() {#ae46c476b2f39ee08d2deee5f5f965c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isDPP8 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcaf79a7cadd64c125693239a99d15776d4">ImmTyDPP8</a> and <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>.</p>

</div>
</div>

### isDPPCtrl() {#ad73d4a40efb842b0d24538c757cc5a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isDPPCtrl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#a9f901d3b6a8c3b686d2f3408de0fb817">getImmTy</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca9e3ba413ec741a423d42d99974585677">ImmTyDppCtrl</a>, <a href="#ae14745a72acdb68188b6dc3991cc3dfe">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isDppFI() {#ae7601fdfd565704de9abe6c1097b4880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isDppFI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca07d5a47db7db2fcf76162ad332f72686">ImmTyDppFI</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isEndpgm() {#aef2786a586d928f359f6380de338ab64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isEndpgm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 963 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca53303dcc815ab55f8a1f737852055ded">ImmTyEndpgm</a> and <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>.</p>

</div>
</div>

### isExpr() {#a72d2637b8226831e335bf142e7b3f352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isExpr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>, <a href="#a88cac794786119f504d4a0c96540f2ea">isSOPPBrTarget</a>, <a href="#a8d2d0919dd1d18d1f5617d78bbacf2ce">isSSrc_b32</a>, <a href="#a7c8e83fc3517ec8e0ce5574d6ff94ef5">isSSrc_f32</a>, <a href="#afe79b6c6fd5b7698a29f3f94fd63aef5">isSSrcOrLds_b32</a>, <a href="#a43ad7d3a52a625302db35bf74a9a3836">isSymbolRefExpr</a>, <a href="#a767d856a1fe976716636a331ece309e9">isVSrc_b32</a>, <a href="#aa6d88e23ab028267294b352ba3376ba6">isVSrc_f32</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>.</p>

</div>
</div>

### isExpTgt() {#afabf375b8f9c73d52d1de145e35eb1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isExpTgt ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca8b92c2d67ca16440f8c439f063c4c32b">ImmTyExpTgt</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isFlatOffset() {#ad0f9c98bff2dbe6132bea65df3f2f948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isFlatOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca45cf846b7e62d831b596bccad4de5315">ImmTyInstOffset</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca02f46f2486aed0107b1313c8c7bae9b7">ImmTyOffset</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isFORMAT() {#a843ebc10c0fc3b71d7c5aeca93af90cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isFORMAT ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca86191e0af51710ca8b408b289300cf0d">ImmTyFORMAT</a>, <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isGDS() {#a3fe560c5124729f869042921509ee5f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isGDS ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcad673fd3693f21e595b61e0efcfebace7">ImmTyGDS</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isGPRIdxMode() {#afd2f761e92ec85c58fd2803b2b890d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isGPRIdxMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcad4fc7a84a69230aae91424d2ef3daf73">ImmTyGprIdxMode</a> and <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>.</p>

</div>
</div>

### isHwreg() {#a93b621f40430eff61b4be310112c329f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isHwreg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcac8698f7407c44136e38a954eee31ec18">ImmTyHwreg</a> and <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>.</p>

</div>
</div>

### isIdxen() {#a99a00d1441baffd67cc30c446eb4dc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isIdxen ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcad781363033c69b70fe169821750b5382">ImmTyIdxen</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isImm() {#ae14745a72acdb68188b6dc3991cc3dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImm ()</td>
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

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a43f99228b449f1ba1ba74ef5b658642b">isBLGP</a>, <a href="#ad73d4a40efb842b0d24538c757cc5a52">isDPPCtrl</a>, <a href="#a070ae269bd64d87b22d8bd6474290d14">isSDelayALU</a>, <a href="#a62c0054ad59c38b9015bc4522023e642">isSWaitCnt</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>.</p>

</div>
</div>

### isImmKindConst() {#a621031fa88ed3052303329e1d5f55c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImmKindConst ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aa817fddb7d8c888c671fcebc15b4b76aa50e29a2fb9d43a6171af09db28869683">ImmKindTyConst</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### IsImmKindLiteral() {#a5329f028dc85cb9c189110eb90309790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::IsImmKindLiteral ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aa817fddb7d8c888c671fcebc15b4b76aa2bd93559ed7f83abbcde5cf9ecaeacb1">ImmKindTyLiteral</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### IsImmKindMandatoryLiteral() {#afb66e6b20daee99ff51c1de598caaeda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::IsImmKindMandatoryLiteral ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aa817fddb7d8c888c671fcebc15b4b76aa855228a5582f02236bfcb17481d6526e">ImmKindTyMandatoryLiteral</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isImmLiteral() {#a66668629a5763bdbd767f1758ff8a240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImmLiteral ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="#abb79ad2db74dd301e79b8145b9abfd87">isS16Imm</a>, <a href="#a7c22221c009d60df43824066d41c2b39">isSMEMOffset</a>, <a href="#ae97de6c7f089682bbfde546a6dccf6f7">isSMRDLiteralOffset</a>, <a href="#adb5a5e1ff09682ce9e0d40839407b8c8">isSMRDOffset8</a> and <a href="#a1c064b45288d866bb619ff92c4ee78dd">isU16Imm</a>.</p>

</div>
</div>

### isImmModifier() {#af02a39c837b571df2b4d3712264ca6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImmModifier ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### isImmTy() {#a6a85de263ff8282b792ad4dd660a4016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImmTy (<a href="#aac6196abacab3897ea9874e72d3db8fc">ImmTy</a> ImmT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>, <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>, <a href="#a5da081c55cdc6b6177d44f16709f407f">isAddr64</a>, <a href="#aec16843edbdec91c49ac0ea4857faa58">isBitOp3</a>, <a href="#ad31d84f19e1ed3db03f69e88510be043">isCPol</a>, <a href="#a725441e4bc10087cf4158f40684ff7d3">isDim</a>, <a href="#ae7601fdfd565704de9abe6c1097b4880">isDppFI</a>, <a href="#afabf375b8f9c73d52d1de145e35eb1f5">isExpTgt</a>, <a href="#ad0f9c98bff2dbe6132bea65df3f2f948">isFlatOffset</a>, <a href="#a843ebc10c0fc3b71d7c5aeca93af90cc">isFORMAT</a>, <a href="#a3fe560c5124729f869042921509ee5f4">isGDS</a>, <a href="#a99a00d1441baffd67cc30c446eb4dc6d">isIdxen</a>, <a href="#a66668629a5763bdbd767f1758ff8a240">isImmLiteral</a>, <a href="#a7316456a666b503541d24406d2159c3c">isIndexKey16bit</a>, <a href="#a6127ce6559262384ffe1edf00a87d01f">isIndexKey8bit</a>, <a href="#ae4037548ce62acb9759955250737db54">isInterpAttr</a>, <a href="#acbee773b6ce142455d118167c39d9e55">isInterpAttrChan</a>, <a href="#a67c3b2574b178fb5d5f6fa38d5376101">isInterpSlot</a>, <a href="#a74e4facce65c38df1b0b9ee5770d1c48">isLDS</a>, <a href="#ae4806e14047291615ddfd5da09e4db72">isNegHi</a>, <a href="#a32631c2127fa524dee333410f73efd22">isNegLo</a>, <a href="#ac66954f4e62ba45315968d4c728d9d3d">isOff</a>, <a href="#a489f00cf9dd045f774be9a4a5f8ba360">isOffen</a>, <a href="#a186908fe05ef5b3f4f7ab2865c33e798">isOModSI</a>, <a href="#a4c277e4ac58fb3d467ee4b1e79ea8917">isOpSel</a>, <a href="#a3d165eefdb757f6ae3f552e561392a45">isOpSelHi</a>, <a href="#a85291654688208306aa79041286e5deb">isR128A16</a>, <a href="#add6a430fa695166d19782300671d284e">isSDWADstSel</a>, <a href="#a24b496d2ed1fcfdd11f8b6ff09ebd797">isSDWADstUnused</a>, <a href="#a5ed9e20d4ce1b2697a8973b48fc594bd">isSDWASrc0Sel</a>, <a href="#a3e1a34ff8c704eecc7afb4dedd6c6a75">isSDWASrc1Sel</a>, <a href="#a1ed765d7340acfc511234e81438883ac">isSMEMOffsetMod</a>, <a href="#a136032b6433e8780b837c9ea1f03af10">isTFE</a> and <a href="#a8f2051721c4ee3fcd990beca23c4aa40">setModifiers</a>.</p>

</div>
</div>

### isImmTy() {#a59e678c16ae28bb40fd815e322e84b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;ImmTy Ty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isImmTy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>.</p>


<p>Referenced by <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>, <a href="#ae3252f98d20c96f775dd0286d1a2f830">applyInputFPModifiers</a>, <a href="#ae46c476b2f39ee08d2deee5f5f965c35">isDPP8</a>, <a href="#aef2786a586d928f359f6380de338ab64">isEndpgm</a>, <a href="#afd2f761e92ec85c58fd2803b2b890d92">isGPRIdxMode</a>, <a href="#a93b621f40430eff61b4be310112c329f">isHwreg</a>, <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>, <a href="#ab28800a685d06a879d56b4d178e85aa5">isInlinableImm</a>, <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a>, <a href="#a12e0d5026a7c5e1db816e171c633138f">isSendMsg</a> and <a href="#aa9c78c380195227929c91cae16f23aad">isSwizzle</a>.</p>

</div>
</div>

### isIndexKey16bit() {#a7316456a666b503541d24406d2159c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isIndexKey16bit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca4df6d1cb3360e33d52bed3dd55d9342e">ImmTyIndexKey16bit</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isIndexKey8bit() {#a6127ce6559262384ffe1edf00a87d01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isIndexKey8bit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca3b0787bbfe8d09244425732c5a8840d7">ImmTyIndexKey8bit</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isInlinableImm() {#ab28800a685d06a879d56b4d178e85aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isInlinableImm (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ab46ff1a80ee89c9e22ca17c179a89ab1">llvm::APFloatBase::BFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a5c1af79d4ba400e89ab28d0586484fae">canLosslesslyConvertToFPType</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aea8bc2b59cb3fa833eb7895a3a216abd">llvm::MVT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a79ce723bbdcb8a66b32fec6499ecd9f9">llvm::AMDGPU::isInlinableLiteral32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af4cb2c8159c390d78b6a547ac87179ae">llvm::AMDGPU::isInlinableLiteral64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a52a4ce97809e5b145044819f0a7de44d">isInlineableLiteralOp16</a>, <a href="#a3e920b8d255e42d5f25ba3523c4dfe2b">isInlineValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#af9f73de55db8e160861464e29ab9ab39">isSafeTruncation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3ad7da1b76e5799f53a399b7a96ba67437">llvm::Literal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>, <a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a> and <a href="#ac8ec6c77a10cfb30ff6aedee4aeb7b99">isSplitBarrier</a>.</p>

</div>
</div>

### isInlineValue() {#a3e920b8d255e42d5f25ba3523c4dfe2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isInlineValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a5c2d5cb768dd61ffc311e44a67d7b292">getReg</a>, <a href="#a3e920b8d255e42d5f25ba3523c4dfe2b">isInlineValue</a> and <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a>.</p>


<p>Referenced by <a href="#ab28800a685d06a879d56b4d178e85aa5">isInlinableImm</a> and <a href="#a3e920b8d255e42d5f25ba3523c4dfe2b">isInlineValue</a>.</p>

</div>
</div>

### isInterpAttr() {#ae4037548ce62acb9759955250737db54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInterpAttr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca2d980b3c725150072bc1bca3b9717703">ImmTyInterpAttr</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isInterpAttrChan() {#acbee773b6ce142455d118167c39d9e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInterpAttrChan ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcadc4ee0d2f112f47edabec0e19de95b2d">ImmTyInterpAttrChan</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isInterpSlot() {#a67c3b2574b178fb5d5f6fa38d5376101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInterpSlot ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcac16758e9406b631d54854588a576a29c">ImmTyInterpSlot</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isKImmFP16() {#a1e93961df200447d993f3bf673734da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isKImmFP16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 933 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a>.</p>

</div>
</div>

### isKImmFP32() {#a997e38fe6a99acde82974dd007db24d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isKImmFP32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a>.</p>

</div>
</div>

### isLDS() {#a74e4facce65c38df1b0b9ee5770d1c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isLDS ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca80ad15588035616b5caa13260dc56b08">ImmTyLDS</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isLiteralImm() {#a55cada066d6192320d0ca6c3033e9faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isLiteralImm (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a5c1af79d4ba400e89ab28d0586484fae">canLosslesslyConvertToFPType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers/#aad7378c29bc95c596341b83e689c3484">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Modifiers::hasFPModifiers</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#af9f73de55db8e160861464e29ab9ab39">isSafeTruncation</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a1e93961df200447d993f3bf673734da1">isKImmFP16</a>, <a href="#a997e38fe6a99acde82974dd007db24d8">isKImmFP32</a>, <a href="#a23ce1a2b844fbe612c836b788bb80b29">isRegOrImmWithInputMods</a>, <a href="#a27647c5594cbbc99deef54fc824e06de">isSSrc_b16</a>, <a href="#a8d2d0919dd1d18d1f5617d78bbacf2ce">isSSrc_b32</a>, <a href="#aa47329d14cc95ec2898485fe287da91a">isSSrc_b64</a>, <a href="#af70eccbfa6352784e4e85d731d7e22a5">isSSrc_bf16</a>, <a href="#ae7b4e5caaf16b9360c9899c64e2de90e">isSSrc_f16</a>, <a href="#a7c8e83fc3517ec8e0ce5574d6ff94ef5">isSSrc_f32</a>, <a href="#a4b3dd4fb92d28eff3e3fb6771ca9cb8d">isSSrcF64</a>, <a href="#afe79b6c6fd5b7698a29f3f94fd63aef5">isSSrcOrLds_b32</a>, <a href="#a54a78c8a10831c329069d19520bec727">isVSrc_b16</a>, <a href="#a767d856a1fe976716636a331ece309e9">isVSrc_b32</a>, <a href="#aa48e0b8ebc7807de5f0898b1c4efe077">isVSrc_b64</a>, <a href="#a897d91246a144118d006758146eee34f">isVSrc_bf16</a>, <a href="#a1d6b62e40304b958fbc9cca21aedecd3">isVSrc_f16</a>, <a href="#aa6d88e23ab028267294b352ba3376ba6">isVSrc_f32</a>, <a href="#a13c847f04f640a6cee8c84c6dc5d9a4e">isVSrc_f64</a>, <a href="#a2ac4df4fbe4b2def95eea6a719f8256d">isVSrc_v2b16</a>, <a href="#aa509fd036e9e1ff80630fbe94d3b36e9">isVSrc_v2b32</a>, <a href="#a278fb6f3f94caa89b9314d30fb8b8a1d">isVSrc_v2bf16</a>, <a href="#a1faab935a964d13e28192fc113617167">isVSrc_v2f16</a>, <a href="#ad5268a4e8a67b227599b70277e9bcfe3">isVSrc_v2f32</a>, <a href="#a61fd9a51e14f86a2df225d3f30593fa4">isVSrcFake16_b16_Lo128</a>, <a href="#a7133ae6c0fc99a9a42ba41b5e7749d64">isVSrcFake16_bf16_Lo128</a>, <a href="#a236d692826d993d12f6820d2bd06a09f">isVSrcFake16_f16_Lo128</a>, <a href="#a4a1d0c2fde62ae9db0243656cc4bec98">isVSrcT_b16</a>, <a href="#ac2ccc21f1a73275dfb48b5b37c1c4060">isVSrcT_b16_Lo128</a>, <a href="#a1ef8393558f2ea052f688e52a6fb29e2">isVSrcT_bf16</a>, <a href="#ace883242feabf817dc39df76f18057b1">isVSrcT_bf16_Lo128</a>, <a href="#a1f1bcb6e01cf7df4c9e5832e599f6871">isVSrcT_f16</a> and <a href="#a69719e896a69ca1b37a8a67f1e44d577">isVSrcT_f16_Lo128</a>.</p>

</div>
</div>

### isMem() {#a5d7135568ebfdeac7f03af08d5427436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isMem ()</td>
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

<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isNegHi() {#ae4806e14047291615ddfd5da09e4db72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isNegHi ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca2ee46e789b1dd972067b15f482dacf06">ImmTyNegHi</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isNegLo() {#a32631c2127fa524dee333410f73efd22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isNegLo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca4ebfe90c5e76cde6ee3867f75a62f8a8">ImmTyNegLo</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isNull() {#a25a9c23ba883fb9aa73d55a43260e4a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isNull ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a> and <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isOff() {#ac66954f4e62ba45315968d4c728d9d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isOff ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca96a2e9977c530f18cdc5cdde12de257b">ImmTyOff</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="#a1e78a8f72b1a1d2cdc5616e36e501aa1">isVReg32OrOff</a>.</p>

</div>
</div>

### isOffen() {#a489f00cf9dd045f774be9a4a5f8ba360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isOffen ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca3fe0f6956d2f2effc84c174dc25a2b22">ImmTyOffen</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isOModSI() {#a186908fe05ef5b3f4f7ab2865c33e798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isOModSI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcaf4e10bb6d0fda8ad54cca3f45eb2b143">ImmTyOModSI</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isOpSel() {#a4c277e4ac58fb3d467ee4b1e79ea8917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isOpSel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcaf3ba690efda9412129e1195c93663d18">ImmTyOpSel</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isOpSelHi() {#a3d165eefdb757f6ae3f552e561392a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isOpSelHi ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca7e67cef1f3b30e0fc5a6fc222f578c13">ImmTyOpSelHi</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isPackedFP16InputMods() {#a6216d7cf4dff4ff6c0173315e212b030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isPackedFP16InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isPackedFP32InputMods() {#a5c96f84c9aa36358bca4552ba9d98e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isPackedFP32InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isR128A16() {#a85291654688208306aa79041286e5deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isR128A16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcaf99873ea3e78297b518afa494e67c3c6">ImmTyR128A16</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isReg() {#a6323b2f7c53b4ebcbd057da0f366ed8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isReg ()</td>
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

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a8a33b1fc06b8891f726f8c241fe573ef">hasModifiers</a> and <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a>.</p>


<p>Referenced by <a href="#a6cd80536eb806cf601df1ea92cfb52cb">isBoolReg</a>.</p>

</div>
</div>

### isRegClass() {#a7849fd8a75f7cadefd2fbdd3ab6014bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isRegClass (unsigned RCID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a5c2d5cb768dd61ffc311e44a67d7b292">getReg</a> and <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a>.</p>


<p>Referenced by <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>, <a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a>, <a href="#afee6a95dc973633bcdc0374c5818d1c4">isT16_Lo128VRegWithInputMods</a>, <a href="#acc384733bb6f91a5031c0e48c09962e1">isT16VRegWithInputMods</a>, <a href="#adb91b96bac5323420834ff2ef15c8022">isVReg</a>, <a href="#a6c384f6ec4cb38b1a921418ee06b19b0">isVReg32</a> and <a href="#ab805317174b719e76b7063fe3800f002">isVRegWithInputMods</a>.</p>

</div>
</div>

### isRegKind() {#a19f81f50fd5f4905ff667d77173591f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegKind ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a26bad8e09401457e56c428aa16473a53">addRegOrImmOperands</a>, <a href="#a625e5c93b568541975f28a4ad8746c4c">addRegOrImmWithInputModsOperands</a>, <a href="#a31034030d9e1080963a9033b29df4df8">addRegWithInputModsOperands</a>, <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>, <a href="#a5c2d5cb768dd61ffc311e44a67d7b292">getReg</a>, <a href="#a3e920b8d255e42d5f25ba3523c4dfe2b">isInlineValue</a>, <a href="#a25a9c23ba883fb9aa73d55a43260e4a5">isNull</a>, <a href="#a6323b2f7c53b4ebcbd057da0f366ed8d">isReg</a>, <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a> and <a href="#a8f2051721c4ee3fcd990beca23c4aa40">setModifiers</a>.</p>

</div>
</div>

### isRegOrImm() {#ad2eb5ae7782040f081faca112c8751a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>.</p>

</div>
</div>

### isRegOrImmWithFP16InputMods() {#a1fd7023a581a2de433c0bbbf162f8136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithFP16InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isRegOrImmWithFP32InputMods() {#abde7d67294d883e68659a654836e5405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithFP32InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isRegOrImmWithFP64InputMods() {#a6db6541d4d2950f6571cc47da6e47190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithFP64InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isRegOrImmWithFPT16InputMods() {#a2d77f28353be6ab1cb39ff21a3f68b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsFake16&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithFPT16InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isRegOrImmWithInputMods() {#a23ce1a2b844fbe612c836b788bb80b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInputMods (unsigned RCID, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#adfaf977dc82c560bd265a68c807cd1a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a57878d0e3afa7d6e659b92b9d71c0923">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac4e2add1506387486f82ff6117a6a0e4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVINTERP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a81d4a718e3a11c1c3507fb28db101cf6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af30bfdcbe6574a1d0de2c2c59c1a8f18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3Interp</a>.</p>

</div>
</div>

### isRegOrImmWithInt16InputMods() {#a7a8c1b3938fb3ef6a688675b0339f9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInt16InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isRegOrImmWithInt32InputMods() {#a2256f6dba15ab8a440e87b8f2c36e55d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInt32InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isRegOrImmWithInt64InputMods() {#ac07a510b855028d98f6b3572236646ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithInt64InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isRegOrImmWithIntT16InputMods() {#acd3d0647b85d10a8da9106f4290e06ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsFake16&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImmWithIntT16InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#adc83f8e8a2d9e4e4b8861ec8197b9aa4">isRegOrImmWithInputMods</a>.</p>

</div>
</div>

### isRegOrInline() {#a2db076f2949adc01d15be741f71f607e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrInline (unsigned RCID, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#ab28800a685d06a879d56b4d178e85aa5">isInlinableImm</a> and <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a>.</p>


<p>Referenced by <a href="#a23ce1a2b844fbe612c836b788bb80b29">isRegOrImmWithInputMods</a>, <a href="#ab7a5daec5c981d176426ba0bec8901bc">isRegOrInlineImmWithFP16InputMods</a>, <a href="#a4e4d40591500fa470657900a51c0be04">isRegOrInlineImmWithFP32InputMods</a>, <a href="#ac3c97b53b7bb05ac7715f45cb238dce9">isRegOrInlineImmWithInt16InputMods</a>, <a href="#a6d61a166ea5959093d03dc95da3d706e">isRegOrInlineImmWithInt32InputMods</a>, <a href="#a252d5e0092300d4154a3715dc5a9cc67">isRegOrInlineImmWithIntT16InputMods</a> and <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isRegOrInlineImmWithFP16InputMods() {#ab7a5daec5c981d176426ba0bec8901bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsFake16&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrInlineImmWithFP16InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>.</p>

</div>
</div>

### isRegOrInlineImmWithFP32InputMods() {#a4e4d40591500fa470657900a51c0be04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrInlineImmWithFP32InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>.</p>

</div>
</div>

### isRegOrInlineImmWithInt16InputMods() {#ac3c97b53b7bb05ac7715f45cb238dce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrInlineImmWithInt16InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>.</p>

</div>
</div>

### isRegOrInlineImmWithInt32InputMods() {#a6d61a166ea5959093d03dc95da3d706e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrInlineImmWithInt32InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>.</p>

</div>
</div>

### isRegOrInlineImmWithIntT16InputMods() {#a252d5e0092300d4154a3715dc5a9cc67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsFake16&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrInlineImmWithIntT16InputMods ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>.</p>

</div>
</div>

### isRegOrInlineNoMods() {#a39f5fa2e7af47e815d3d702ae75be98d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrInlineNoMods (unsigned RCID, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a8a33b1fc06b8891f726f8c241fe573ef">hasModifiers</a> and <a href="#a2db076f2949adc01d15be741f71f607e">isRegOrInline</a>.</p>


<p>Referenced by <a href="#ab5bc81f35b0c979591d85a4a1ceabe2f">isAISrc_1024_b32</a>, <a href="#a2df4f843ee08dcb8c5e7133907600e9b">isAISrc_1024_f32</a>, <a href="#a1bd39009eb8ad39027b877174b5c9743">isAISrc_1024B16</a>, <a href="#ab40dcd0145862cddcc3ce7282b6f4cec">isAISrc_1024F16</a>, <a href="#a8241bca4b084ae7c30de8a215e062f31">isAISrc_128_b32</a>, <a href="#a339e281b608635aa01077365ca9ba376">isAISrc_128_f32</a>, <a href="#ab04d5468adfa929c4dbc107db8cea8cd">isAISrc_128B16</a>, <a href="#a0a875393cbb193f917d69c3ed5f7a7fa">isAISrc_128F16</a>, <a href="#a8bcde68cada557cf2506a721b95719f3">isAISrc_256_f64</a>, <a href="#a59b7e82a58ede7b90f31614902e2469b">isAISrc_256B64</a>, <a href="#a41645fcd448ffbc022e30f23567b4083">isAISrc_512_b32</a>, <a href="#ad5301b95a566274a772d9b3b3b54c7ec">isAISrc_512_f32</a>, <a href="#a85882dcf462a2c26de897ca3b106ea12">isAISrc_512B16</a>, <a href="#aa803d77b9fbb9f0240715f4a33562fe8">isAISrc_512F16</a>, <a href="#a07abf1a41d284dd9ee34e54ccf972281">isAISrc_64_f64</a>, <a href="#a6ea92abeaae74671df203996e48d2714">isAISrc_64B64</a>, <a href="#a155240358886ddf8bdb8525fe7d0f2c9">isAISrcB16</a>, <a href="#aa5c0497a12d3d5857c1aaedc1dec4d38">isAISrcB32</a>, <a href="#a0db362c0804c514fcc45d18c8004b401">isAISrcF16</a>, <a href="#ac8d81bab67f67c41b6ad5833c29a2bb0">isAISrcF32</a>, <a href="#a55b85dea51a8ac8ba36bcda3858f57d3">isSCSrc_b32</a>, <a href="#aec5d0b1b4c78021f85cf22845451ccb6">isSCSrc_b64</a>, <a href="#a76a2ef063e52411078a05ed38a78109e">isSCSrcB16</a>, <a href="#adbe6e09d714d34f23900758bd87f8840">isSCSrcF16</a>, <a href="#aa59f84455f84ea23e797eb02a9672276">isSCSrcF32</a>, <a href="#a7cd938ff442d1602fe62d30e42fdfad8">isSCSrcF64</a>, <a href="#afe79b6c6fd5b7698a29f3f94fd63aef5">isSSrcOrLds_b32</a>, <a href="#afb012d4dea6b0f079fbc05723333b7b6">isVCSrc_b16</a>, <a href="#a386abcbedfd5b6ba371c9def37351539">isVCSrc_b32</a>, <a href="#aefde2f5a23cfc9346c6b3fcd2d733706">isVCSrc_bf16</a>, <a href="#a7c42d206ee8811a9f5b9cf76893527cd">isVCSrc_f16</a>, <a href="#ad8fe12b49b0c7a03fed208cbca0e4ede">isVCSrc_f32</a>, <a href="#a93b7dd4bb81142c5731321483e6461de">isVCSrcB64</a>, <a href="#adff38d575b028c1596d28fc393300701">isVCSrcF64</a>, <a href="#abd1ab4a403d410775f974625c9e8bbf3">isVCSrcFake16B16_Lo128</a>, <a href="#ad95e4108e84a29408d15e70712fb49f8">isVCSrcFake16BF16_Lo128</a>, <a href="#a41866dfbf7988eec964552aba0e25b4e">isVCSrcFake16F16_Lo128</a>, <a href="#af560048eb60aa005581bb74c8de8514d">isVCSrcT_b16</a>, <a href="#acb147ce6f7b5c838d0c761a7cf09462c">isVCSrcT_bf16</a>, <a href="#ae2d3dc1d4b1f15d460b7eeb7508468a1">isVCSrcT_f16</a>, <a href="#ac96bb4d26e71bd18c598c1174f675dc2">isVCSrcTB16_Lo128</a>, <a href="#a9167f9ce445e37760af3e633cf57d325">isVCSrcTBF16</a>, <a href="#a1af262eb98370b66d63ebaeafdc2435d">isVCSrcTBF16_Lo128</a>, <a href="#a0be4c430001a4138b47e2191c44adf53">isVCSrcTF16_Lo128</a>, <a href="#a47fb7cc273d3e0a8fd2b1c9e4bbda26e">isVISrc_1024_b32</a>, <a href="#a7cc685f044aa966f04ae5cafc6699456">isVISrc_1024_f32</a>, <a href="#afe0de0e3a0dcf9154063738604789bc3">isVISrc_1024B16</a>, <a href="#a59ecdaa0c6e9b2e2259d8833c16251cb">isVISrc_1024F16</a>, <a href="#a323f8926dc3bd4035059453c35b3dff9">isVISrc_128_b32</a>, <a href="#a835e61a24dfefa5a604441666ad3bb7c">isVISrc_128_bf16</a>, <a href="#a5789e1699b1429db70c4150f303a668b">isVISrc_128_f16</a>, <a href="#ada6c673fa523d8ed4b27aa6c9dfad133">isVISrc_128_f32</a>, <a href="#a1eaa6cfdf4d9aadc2b73ad97384d4f4c">isVISrc_128B16</a>, <a href="#a98517a2db7a49a6e3cf65637fa85df29">isVISrc_256_b32</a>, <a href="#ae6e9368cdd06cb54ca0451fe539ca7be">isVISrc_256_f32</a>, <a href="#a230c7d81808c760417814d1524204432">isVISrc_256_f64</a>, <a href="#a06fae9684d40680c27a7cdff14002f02">isVISrc_256B64</a>, <a href="#a342368eb65fa4139f7d64d773b555d8e">isVISrc_256V2FP32</a>, <a href="#aa8ae33d7993058b88ffbef2c248d61f4">isVISrc_256V2INT32</a>, <a href="#a6ebb36021dbe87001abf22690bc273be">isVISrc_512_b32</a>, <a href="#ae2b84b6963b10b8a12bc3fce984d1858">isVISrc_512_f32</a>, <a href="#accad7afcfebb95cc57ce6dc9a836a81f">isVISrc_512B16</a>, <a href="#a6cc993de986625bbfc437c75fe36b754">isVISrc_512F16</a>, <a href="#aff2536b26ed64bef015303a55940abdb">isVISrc_64_b32</a>, <a href="#ac8e2eea2f7a2fbade058478bb110097d">isVISrc_64_bf16</a>, <a href="#a8122749572963ed4ec689ca5a6aefcc6">isVISrc_64_f16</a>, <a href="#aecd4934e735853a422536b1142bcd220">isVISrc_64_f64</a>, <a href="#ac4d9842857b54a442327e0421f12cb3f">isVISrc_64B64</a>, <a href="#a2befae16afca427baf113c4df64ad092">isVISrc_64V2FP32</a>, <a href="#a2be977b78fccf3bc5e4bb0d010f39ed0">isVISrc_64V2INT32</a>, <a href="#a178aac9b3c39e55d78166a3e09c56e7c">isVISrcB16</a>, <a href="#a1fb61f4a732360d17f93370deb9a0ffa">isVISrcB32</a>, <a href="#a131c1dbcb24973df3162c4cd9a895cfd">isVISrcF16</a> and <a href="#a16acb91bfaa1c96465ad2395e6980503">isVISrcF32</a>.</p>

</div>
</div>

### isS16Imm() {#abb79ad2db74dd301e79b8145b9abfd87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isS16Imm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 961 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#a66668629a5763bdbd767f1758ff8a240">isImmLiteral</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>


<p>Referenced by <a href="#a8b920d223fc1391f3d0b298e14aad4d2">isDepCtr</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>.</p>

</div>
</div>

### isSCSrc\_b32() {#a55b85dea51a8ac8ba36bcda3858f57d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrc_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a6cd80536eb806cf601df1ea92cfb52cb">isBoolReg</a>, <a href="#af987d979d12e6ac245c32a643b27ecb7">isSCSrcV2INT32</a>, <a href="#a8d2d0919dd1d18d1f5617d78bbacf2ce">isSSrc_b32</a> and <a href="#a7c8e83fc3517ec8e0ce5574d6ff94ef5">isSSrc_f32</a>.</p>

</div>
</div>

### isSCSrc\_b64() {#aec5d0b1b4c78021f85cf22845451ccb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrc_b64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a6cd80536eb806cf601df1ea92cfb52cb">isBoolReg</a>, <a href="#aa47329d14cc95ec2898485fe287da91a">isSSrc_b64</a> and <a href="#a4b3dd4fb92d28eff3e3fb6771ca9cb8d">isSSrcF64</a>.</p>

</div>
</div>

### isSCSrcB16() {#a76a2ef063e52411078a05ed38a78109e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrcB16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a49dd06edf45844598430469eb5ba9c33">isSCSrcV2B16</a>, <a href="#a27647c5594cbbc99deef54fc824e06de">isSSrc_b16</a>, <a href="#af70eccbfa6352784e4e85d731d7e22a5">isSSrc_bf16</a> and <a href="#ae7b4e5caaf16b9360c9899c64e2de90e">isSSrc_f16</a>.</p>

</div>
</div>

### isSCSrcF16() {#adbe6e09d714d34f23900758bd87f8840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrcF16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a924611bf8f1ccdae769548e0bce49067">isSCSrcV2F16</a>.</p>

</div>
</div>

### isSCSrcF32() {#aa59f84455f84ea23e797eb02a9672276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrcF32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ab41e42626c4597a8ad5bc997073936cb">isSCSrcV2FP32</a>.</p>

</div>
</div>

### isSCSrcF64() {#a7cd938ff442d1602fe62d30e42fdfad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrcF64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isSCSrcV2B16() {#a49dd06edf45844598430469eb5ba9c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrcV2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a76a2ef063e52411078a05ed38a78109e">isSCSrcB16</a>.</p>

</div>
</div>

### isSCSrcV2F16() {#a924611bf8f1ccdae769548e0bce49067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrcV2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#adbe6e09d714d34f23900758bd87f8840">isSCSrcF16</a>.</p>

</div>
</div>

### isSCSrcV2FP32() {#ab41e42626c4597a8ad5bc997073936cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrcV2FP32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aa59f84455f84ea23e797eb02a9672276">isSCSrcF32</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isSCSrcV2INT32() {#af987d979d12e6ac245c32a643b27ecb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSCSrcV2INT32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55b85dea51a8ac8ba36bcda3858f57d3">isSCSrc_b32</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isSDelayALU() {#a070ae269bd64d87b22d8bd6474290d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSDelayALU ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#ae14745a72acdb68188b6dc3991cc3dfe">isImm</a>.</p>

</div>
</div>

### isSDWADstSel() {#add6a430fa695166d19782300671d284e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSDWADstSel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca5ef6d8d490dc55a1a768223f15a959a3">ImmTySDWADstSel</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isSDWADstUnused() {#a24b496d2ed1fcfdd11f8b6ff09ebd797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSDWADstUnused ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca38365958fa12a0f2acd965b2bc77ea00">ImmTySDWADstUnused</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isSDWAFP16Operand() {#a44ff4d1f7b2fc72dc15000bd7f7e75c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSDWAFP16Operand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a>.</p>


<p>Referenced by <a href="#acc384733bb6f91a5031c0e48c09962e1">isT16VRegWithInputMods</a>.</p>

</div>
</div>

### isSDWAFP32Operand() {#aa475558e94482db687222e7484523427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSDWAFP32Operand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a>.</p>


<p>Referenced by <a href="#acc384733bb6f91a5031c0e48c09962e1">isT16VRegWithInputMods</a>.</p>

</div>
</div>

### isSDWAInt16Operand() {#a870a78ded2114be969dd5f0179428df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSDWAInt16Operand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a>.</p>


<p>Referenced by <a href="#acc384733bb6f91a5031c0e48c09962e1">isT16VRegWithInputMods</a>.</p>

</div>
</div>

### isSDWAInt32Operand() {#aab1dc38460665f7240799afba15e8beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSDWAInt32Operand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a>.</p>


<p>Referenced by <a href="#acc384733bb6f91a5031c0e48c09962e1">isT16VRegWithInputMods</a>.</p>

</div>
</div>

### isSDWAOperand() {#aeeeb9c242e92cf150ef24b421b0be771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSDWAOperand (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#ab28800a685d06a879d56b4d178e85aa5">isInlinableImm</a>, <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a> and <a href="#a6c384f6ec4cb38b1a921418ee06b19b0">isVReg32</a>.</p>


<p>Referenced by <a href="#a44ff4d1f7b2fc72dc15000bd7f7e75c3">isSDWAFP16Operand</a>, <a href="#aa475558e94482db687222e7484523427">isSDWAFP32Operand</a>, <a href="#a870a78ded2114be969dd5f0179428df8">isSDWAInt16Operand</a>, <a href="#aab1dc38460665f7240799afba15e8beb">isSDWAInt32Operand</a> and <a href="#acc384733bb6f91a5031c0e48c09962e1">isT16VRegWithInputMods</a>.</p>

</div>
</div>

### isSDWASrc0Sel() {#a5ed9e20d4ce1b2697a8973b48fc594bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSDWASrc0Sel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcae0c54cec4b9a48401c2fd0dc32b9da24">ImmTySDWASrc0Sel</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isSDWASrc1Sel() {#a3e1a34ff8c704eecc7afb4dedd6c6a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSDWASrc1Sel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca066b849c42884b62cdb679dd05d1c28d">ImmTySDWASrc1Sel</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isSendMsg() {#a12e0d5026a7c5e1db816e171c633138f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSendMsg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcac149121124fe545cec0d7688ea39f435">ImmTySendMsg</a> and <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>.</p>

</div>
</div>

### isSMEMOffset() {#a7c22221c009d60df43824066d41c2b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSMEMOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 955 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a66668629a5763bdbd767f1758ff8a240">isImmLiteral</a>.</p>

</div>
</div>

### isSMEMOffsetMod() {#a1ed765d7340acfc511234e81438883ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSMEMOffsetMod ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca0ccfbff250cbfb289053232b65749936">ImmTySMEMOffsetMod</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>

</div>
</div>

### isSMRDLiteralOffset() {#ae97de6c7f089682bbfde546a6dccf6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSMRDLiteralOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#a66668629a5763bdbd767f1758ff8a240">isImmLiteral</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isSMRDOffset8() {#adb5a5e1ff09682ce9e0d40839407b8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSMRDOffset8 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#a66668629a5763bdbd767f1758ff8a240">isImmLiteral</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isSOPPBrTarget() {#a88cac794786119f504d4a0c96540f2ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSOPPBrTarget ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isSplitBarrier() {#ac8ec6c77a10cfb30ff6aedee4aeb7b99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSplitBarrier ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#ab28800a685d06a879d56b4d178e85aa5">isInlinableImm</a>.</p>

</div>
</div>

### isSSrc\_b16() {#a27647c5594cbbc99deef54fc824e06de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrc_b16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a76a2ef063e52411078a05ed38a78109e">isSCSrcB16</a>.</p>


<p>Referenced by <a href="#a90a712f50d2f4b81d8945bbf9366a4d0">isSSrcV2B16</a>.</p>

</div>
</div>

### isSSrc\_b32() {#a8d2d0919dd1d18d1f5617d78bbacf2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrc_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a>, <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a55b85dea51a8ac8ba36bcda3858f57d3">isSCSrc_b32</a>.</p>


<p>Referenced by <a href="#a7663128eb6e48b1bf5e9d1b01308c9c4">isSSrcV2INT32</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isSSrc\_b64() {#aa47329d14cc95ec2898485fe287da91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrc_b64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#aec5d0b1b4c78021f85cf22845451ccb6">isSCSrc_b64</a>.</p>

</div>
</div>

### isSSrc\_bf16() {#af70eccbfa6352784e4e85d731d7e22a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrc_bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a76a2ef063e52411078a05ed38a78109e">isSCSrcB16</a>.</p>

</div>
</div>

### isSSrc\_f16() {#ae7b4e5caaf16b9360c9899c64e2de90e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrc_f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a76a2ef063e52411078a05ed38a78109e">isSCSrcB16</a>.</p>


<p>Referenced by <a href="#ad95bd09e4da4a6a947ba80810b577655">isSSrcV2F16</a>.</p>

</div>
</div>

### isSSrc\_f32() {#a7c8e83fc3517ec8e0ce5574d6ff94ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrc_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a>, <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a55b85dea51a8ac8ba36bcda3858f57d3">isSCSrc_b32</a>.</p>


<p>Referenced by <a href="#ae1b1fbf5c0f35dedfd59c4434764a320">isSSrcV2FP32</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isSSrcF64() {#a4b3dd4fb92d28eff3e3fb6771ca9cb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrcF64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#aec5d0b1b4c78021f85cf22845451ccb6">isSCSrc_b64</a>.</p>

</div>
</div>

### isSSrcOrLds\_b32() {#afe79b6c6fd5b7698a29f3f94fd63aef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrcOrLds_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a>, <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isSSrcV2B16() {#a90a712f50d2f4b81d8945bbf9366a4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrcV2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a27647c5594cbbc99deef54fc824e06de">isSSrc_b16</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isSSrcV2F16() {#ad95bd09e4da4a6a947ba80810b577655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrcV2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#ae7b4e5caaf16b9360c9899c64e2de90e">isSSrc_f16</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isSSrcV2FP32() {#ae1b1fbf5c0f35dedfd59c4434764a320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrcV2FP32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a7c8e83fc3517ec8e0ce5574d6ff94ef5">isSSrc_f32</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isSSrcV2INT32() {#a7663128eb6e48b1bf5e9d1b01308c9c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSSrcV2INT32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a8d2d0919dd1d18d1f5617d78bbacf2ce">isSSrc_b32</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isSWaitCnt() {#a62c0054ad59c38b9015bc4522023e642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSWaitCnt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#ae14745a72acdb68188b6dc3991cc3dfe">isImm</a>.</p>

</div>
</div>

### isSwizzle() {#aa9c78c380195227929c91cae16f23aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isSwizzle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fcae245f2c36be17caa96752cf101b62796">ImmTySwizzle</a> and <a href="#a59e678c16ae28bb40fd815e322e84b4b">isImmTy</a>.</p>

</div>
</div>

### isSymbolRefExpr() {#a43ad7d3a52a625302db35bf74a9a3836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isSymbolRefExpr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a414289a5d7344879a8c5d516f3bdab86">Expr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>.</p>

</div>
</div>

### isT16\_Lo128VRegWithInputMods() {#afee6a95dc973633bcdc0374c5818d1c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsFake16&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isT16_Lo128VRegWithInputMods ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### isT16\_Lo128VRegWithInputMods() {#afee6a95dc973633bcdc0374c5818d1c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsFake16&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isT16_Lo128VRegWithInputMods ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a>.</p>

</div>
</div>

### isT16VRegWithInputMods() {#acc384733bb6f91a5031c0e48c09962e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsFake16&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isT16VRegWithInputMods ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a44ff4d1f7b2fc72dc15000bd7f7e75c3">isSDWAFP16Operand</a>, <a href="#aa475558e94482db687222e7484523427">isSDWAFP32Operand</a>, <a href="#a870a78ded2114be969dd5f0179428df8">isSDWAInt16Operand</a>, <a href="#aab1dc38460665f7240799afba15e8beb">isSDWAInt32Operand</a> and <a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a>.</p>

</div>
</div>

### isT16VRegWithInputMods() {#acc384733bb6f91a5031c0e48c09962e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsFake16&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isT16VRegWithInputMods ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a>.</p>

</div>
</div>

### isTFE() {#a136032b6433e8780b837c9ea1f03af10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isTFE ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca0d40ab857cb9338f800d4102f5a5fb3c">ImmTyTFE</a> and <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isToken() {#a5d8227b613dc0aff33ca27637d41c74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isToken ()</td>
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

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a9836d66cf9617f7396887c361cbbded0">getToken</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a7e283edef71599b2ffccac2843fce5a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa54525f0109858da308fa32559539255">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDepCtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a332d48815071fdb4e2e94e999c154559">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDimId</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af1e3005e43d45d207eb661fa024b1753">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPPCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aae18974f031b21f7dd37b072a1cbe24d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFORMAT</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab65e752ef8a4ee9e6df01039bfa00b0e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a74b6654d186e55d185e29c67ebd46cc6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithFPInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a493337bf1e3308881e03af9142a5bb5a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSDelayALU</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aec6bf39ecab2cbc57a7ef96190d6019e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSP3NegModifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a066421d8538981830a93a7598a571e8f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac3b25b92e123263ee61ca38bdee04828">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSWaitCnt</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c71cb47a3f1bcc8147c44cc1395ed63">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVOPD</a>.</p>

</div>
</div>

### isU16Imm() {#a1c064b45288d866bb619ff92c4ee78dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isU16Imm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#a66668629a5763bdbd767f1758ff8a240">isImmLiteral</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>.</p>

</div>
</div>

### isVCSrc\_b16() {#afb012d4dea6b0f079fbc05723333b7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrc_b16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a92b486e40ff3f48896dd1a7adfc3268c">isVCSrc_v2b16</a> and <a href="#a54a78c8a10831c329069d19520bec727">isVSrc_b16</a>.</p>

</div>
</div>

### isVCSrc\_b32() {#a386abcbedfd5b6ba371c9def37351539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrc_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVCSrc\_bf16() {#aefde2f5a23cfc9346c6b3fcd2d733706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrc_bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a8c18028aeea66d1b21de23e923304210">isVCSrc_v2bf16</a> and <a href="#a897d91246a144118d006758146eee34f">isVSrc_bf16</a>.</p>

</div>
</div>

### isVCSrc\_f16() {#a7c42d206ee8811a9f5b9cf76893527cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrc_f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#abd8cf6dea6a755409a07542bd7396d1e">isVCSrc_v2f16</a> and <a href="#a1d6b62e40304b958fbc9cca21aedecd3">isVSrc_f16</a>.</p>

</div>
</div>

### isVCSrc\_f32() {#ad8fe12b49b0c7a03fed208cbca0e4ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrc_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a767d856a1fe976716636a331ece309e9">isVSrc_b32</a> and <a href="#aa6d88e23ab028267294b352ba3376ba6">isVSrc_f32</a>.</p>

</div>
</div>

### isVCSrc\_v2b16() {#a92b486e40ff3f48896dd1a7adfc3268c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrc_v2b16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#afb012d4dea6b0f079fbc05723333b7b6">isVCSrc_b16</a>.</p>

</div>
</div>

### isVCSrc\_v2bf16() {#a8c18028aeea66d1b21de23e923304210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrc_v2bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#aefde2f5a23cfc9346c6b3fcd2d733706">isVCSrc_bf16</a>.</p>

</div>
</div>

### isVCSrc\_v2f16() {#abd8cf6dea6a755409a07542bd7396d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrc_v2f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a7c42d206ee8811a9f5b9cf76893527cd">isVCSrc_f16</a>.</p>

</div>
</div>

### isVCSrcB64() {#a93b7dd4bb81142c5731321483e6461de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcB64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a99212127f032d6bd2f0c8e243b6261b2">isVCSrcV2INT32</a>.</p>

</div>
</div>

### isVCSrcF64() {#adff38d575b028c1596d28fc393300701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcF64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a13a35e61723df0a4620d1d9eae399d99">isVCSrcV2FP32</a>, <a href="#aa48e0b8ebc7807de5f0898b1c4efe077">isVSrc_b64</a> and <a href="#a13c847f04f640a6cee8c84c6dc5d9a4e">isVSrc_f64</a>.</p>

</div>
</div>

### isVCSrcFake16B16\_Lo128() {#abd1ab4a403d410775f974625c9e8bbf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcFake16B16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a61fd9a51e14f86a2df225d3f30593fa4">isVSrcFake16_b16_Lo128</a>.</p>

</div>
</div>

### isVCSrcFake16BF16\_Lo128() {#ad95e4108e84a29408d15e70712fb49f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcFake16BF16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a7133ae6c0fc99a9a42ba41b5e7749d64">isVSrcFake16_bf16_Lo128</a>.</p>

</div>
</div>

### isVCSrcFake16F16\_Lo128() {#a41866dfbf7988eec964552aba0e25b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcFake16F16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a236d692826d993d12f6820d2bd06a09f">isVSrcFake16_f16_Lo128</a>.</p>

</div>
</div>

### isVCSrcT\_b16() {#af560048eb60aa005581bb74c8de8514d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcT_b16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a4a1d0c2fde62ae9db0243656cc4bec98">isVSrcT_b16</a>.</p>

</div>
</div>

### isVCSrcT\_bf16() {#acb147ce6f7b5c838d0c761a7cf09462c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcT_bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVCSrcT\_f16() {#ae2d3dc1d4b1f15d460b7eeb7508468a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcT_f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a1f1bcb6e01cf7df4c9e5832e599f6871">isVSrcT_f16</a>.</p>

</div>
</div>

### isVCSrcTB16\_Lo128() {#ac96bb4d26e71bd18c598c1174f675dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcTB16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ac2ccc21f1a73275dfb48b5b37c1c4060">isVSrcT_b16_Lo128</a>.</p>

</div>
</div>

### isVCSrcTBF16() {#a9167f9ce445e37760af3e633cf57d325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcTBF16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a1ef8393558f2ea052f688e52a6fb29e2">isVSrcT_bf16</a>.</p>

</div>
</div>

### isVCSrcTBF16\_Lo128() {#a1af262eb98370b66d63ebaeafdc2435d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcTBF16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ace883242feabf817dc39df76f18057b1">isVSrcT_bf16_Lo128</a>.</p>

</div>
</div>

### isVCSrcTF16\_Lo128() {#a0be4c430001a4138b47e2191c44adf53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcTF16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a69719e896a69ca1b37a8a67f1e44d577">isVSrcT_f16_Lo128</a>.</p>

</div>
</div>

### isVCSrcV2FP32() {#a13a35e61723df0a4620d1d9eae399d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcV2FP32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#adff38d575b028c1596d28fc393300701">isVCSrcF64</a>.</p>

</div>
</div>

### isVCSrcV2INT32() {#a99212127f032d6bd2f0c8e243b6261b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVCSrcV2INT32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a93b7dd4bb81142c5731321483e6461de">isVCSrcB64</a>.</p>

</div>
</div>

### isVISrc\_1024\_b32() {#a47fb7cc273d3e0a8fd2b1c9e4bbda26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_1024_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#aa84245e288c5d5ceed645db238f6e1c1">isVISrc_1024V2F16</a>.</p>

</div>
</div>

### isVISrc\_1024\_f32() {#a7cc685f044aa966f04ae5cafc6699456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_1024_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_1024B16() {#afe0de0e3a0dcf9154063738604789bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_1024B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ab304ee93e082e3f47e25205e0f45a933">isVISrc_1024V2B16</a>.</p>

</div>
</div>

### isVISrc\_1024F16() {#a59ecdaa0c6e9b2e2259d8833c16251cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_1024F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#aa84245e288c5d5ceed645db238f6e1c1">isVISrc_1024V2F16</a>.</p>

</div>
</div>

### isVISrc\_1024V2B16() {#ab304ee93e082e3f47e25205e0f45a933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_1024V2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#afe0de0e3a0dcf9154063738604789bc3">isVISrc_1024B16</a>.</p>

</div>
</div>

### isVISrc\_1024V2F16() {#aa84245e288c5d5ceed645db238f6e1c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_1024V2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a47fb7cc273d3e0a8fd2b1c9e4bbda26e">isVISrc_1024_b32</a> and <a href="#a59ecdaa0c6e9b2e2259d8833c16251cb">isVISrc_1024F16</a>.</p>

</div>
</div>

### isVISrc\_128\_b32() {#a323f8926dc3bd4035059453c35b3dff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_128_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a920e2a4d3c8db2d41206ab1a06aae1c2">isVISrc_128V2F16</a>.</p>

</div>
</div>

### isVISrc\_128\_bf16() {#a835e61a24dfefa5a604441666ad3bb7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_128_bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_128\_f16() {#a5789e1699b1429db70c4150f303a668b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_128_f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a920e2a4d3c8db2d41206ab1a06aae1c2">isVISrc_128V2F16</a>.</p>

</div>
</div>

### isVISrc\_128\_f32() {#ada6c673fa523d8ed4b27aa6c9dfad133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_128_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_128B16() {#a1eaa6cfdf4d9aadc2b73ad97384d4f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_128B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a855cd2736fbdf94c18bd5186504f6b9c">isVISrc_128V2B16</a>.</p>

</div>
</div>

### isVISrc\_128V2B16() {#a855cd2736fbdf94c18bd5186504f6b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_128V2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a1eaa6cfdf4d9aadc2b73ad97384d4f4c">isVISrc_128B16</a>.</p>

</div>
</div>

### isVISrc\_128V2F16() {#a920e2a4d3c8db2d41206ab1a06aae1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_128V2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a323f8926dc3bd4035059453c35b3dff9">isVISrc_128_b32</a> and <a href="#a5789e1699b1429db70c4150f303a668b">isVISrc_128_f16</a>.</p>

</div>
</div>

### isVISrc\_256\_b32() {#a98517a2db7a49a6e3cf65637fa85df29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_256_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_256\_f32() {#ae6e9368cdd06cb54ca0451fe539ca7be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_256_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_256\_f64() {#a230c7d81808c760417814d1524204432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_256_f64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_256B64() {#a06fae9684d40680c27a7cdff14002f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_256B64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_256V2FP32() {#a342368eb65fa4139f7d64d773b555d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_256V2FP32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_256V2INT32() {#aa8ae33d7993058b88ffbef2c248d61f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_256V2INT32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_512\_b32() {#a6ebb36021dbe87001abf22690bc273be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_512_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ad62c657e989e0536612f05a9e1a82b84">isVISrc_512V2F16</a>.</p>

</div>
</div>

### isVISrc\_512\_f32() {#ae2b84b6963b10b8a12bc3fce984d1858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_512_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_512B16() {#accad7afcfebb95cc57ce6dc9a836a81f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_512B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ac2f8b1e163f8200c5f0e82dcc3980935">isVISrc_512V2B16</a>.</p>

</div>
</div>

### isVISrc\_512F16() {#a6cc993de986625bbfc437c75fe36b754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_512F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ad62c657e989e0536612f05a9e1a82b84">isVISrc_512V2F16</a>.</p>

</div>
</div>

### isVISrc\_512V2B16() {#ac2f8b1e163f8200c5f0e82dcc3980935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_512V2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#accad7afcfebb95cc57ce6dc9a836a81f">isVISrc_512B16</a>.</p>

</div>
</div>

### isVISrc\_512V2F16() {#ad62c657e989e0536612f05a9e1a82b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_512V2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a6ebb36021dbe87001abf22690bc273be">isVISrc_512_b32</a> and <a href="#a6cc993de986625bbfc437c75fe36b754">isVISrc_512F16</a>.</p>

</div>
</div>

### isVISrc\_64\_b32() {#aff2536b26ed64bef015303a55940abdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_64_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_64\_bf16() {#ac8e2eea2f7a2fbade058478bb110097d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_64_bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_64\_f16() {#a8122749572963ed4ec689ca5a6aefcc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_64_f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_64\_f64() {#aecd4934e735853a422536b1142bcd220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_64_f64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_64B64() {#ac4d9842857b54a442327e0421f12cb3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_64B64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_64V2FP32() {#a2befae16afca427baf113c4df64ad092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_64V2FP32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrc\_64V2INT32() {#a2be977b78fccf3bc5e4bb0d010f39ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrc_64V2INT32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrcB16() {#a178aac9b3c39e55d78166a3e09c56e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrcB16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#a05867ecb624c2ff25e21cf921a71f9ec">isVISrcV2B16</a>.</p>

</div>
</div>

### isVISrcB32() {#a1fb61f4a732360d17f93370deb9a0ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrcB32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ac2d80a1ce12bd91ba8f5230c642b18a5">isVISrcV2F16</a>.</p>

</div>
</div>

### isVISrcF16() {#a131c1dbcb24973df3162c4cd9a895cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrcF16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>


<p>Referenced by <a href="#ac2d80a1ce12bd91ba8f5230c642b18a5">isVISrcV2F16</a>.</p>

</div>
</div>

### isVISrcF32() {#a16acb91bfaa1c96465ad2395e6980503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrcF32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a39f5fa2e7af47e815d3d702ae75be98d">isRegOrInlineNoMods</a>.</p>

</div>
</div>

### isVISrcV2B16() {#a05867ecb624c2ff25e21cf921a71f9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrcV2B16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a178aac9b3c39e55d78166a3e09c56e7c">isVISrcB16</a>.</p>

</div>
</div>

### isVISrcV2F16() {#ac2d80a1ce12bd91ba8f5230c642b18a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVISrcV2F16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a1fb61f4a732360d17f93370deb9a0ffa">isVISrcB32</a> and <a href="#a131c1dbcb24973df3162c4cd9a895cfd">isVISrcF16</a>.</p>

</div>
</div>

### isVReg() {#adb91b96bac5323420834ff2ef15c8022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a>.</p>

</div>
</div>

### isVReg32() {#a6c384f6ec4cb38b1a921418ee06b19b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVReg32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a>.</p>


<p>Referenced by <a href="#aeeeb9c242e92cf150ef24b421b0be771">isSDWAOperand</a> and <a href="#a1e78a8f72b1a1d2cdc5616e36e501aa1">isVReg32OrOff</a>.</p>

</div>
</div>

### isVReg32OrOff() {#a1e78a8f72b1a1d2cdc5616e36e501aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVReg32OrOff ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#ac66954f4e62ba45315968d4c728d9d3d">isOff</a> and <a href="#a6c384f6ec4cb38b1a921418ee06b19b0">isVReg32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a04ee19cd4568c1352a7d3fce29933cc1">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::validateTargetOperandClass</a>.</p>

</div>
</div>

### isVRegWithInputMods() {#ab805317174b719e76b7063fe3800f002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUOperand::isVRegWithInputMods ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a7849fd8a75f7cadefd2fbdd3ab6014bb">isRegClass</a>.</p>

</div>
</div>

### isVSrc\_b16() {#a54a78c8a10831c329069d19520bec727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_b16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#afb012d4dea6b0f079fbc05723333b7b6">isVCSrc_b16</a>.</p>


<p>Referenced by <a href="#a2ac4df4fbe4b2def95eea6a719f8256d">isVSrc_v2b16</a>.</p>

</div>
</div>

### isVSrc\_b32() {#a767d856a1fe976716636a331ece309e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a>, <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#ad8fe12b49b0c7a03fed208cbca0e4ede">isVCSrc_f32</a>.</p>

</div>
</div>

### isVSrc\_b64() {#aa48e0b8ebc7807de5f0898b1c4efe077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_b64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#adff38d575b028c1596d28fc393300701">isVCSrcF64</a>.</p>


<p>Referenced by <a href="#aa509fd036e9e1ff80630fbe94d3b36e9">isVSrc_v2b32</a>.</p>

</div>
</div>

### isVSrc\_bf16() {#a897d91246a144118d006758146eee34f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#aefde2f5a23cfc9346c6b3fcd2d733706">isVCSrc_bf16</a>.</p>


<p>Referenced by <a href="#a278fb6f3f94caa89b9314d30fb8b8a1d">isVSrc_v2bf16</a>.</p>

</div>
</div>

### isVSrc\_f16() {#a1d6b62e40304b958fbc9cca21aedecd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a7c42d206ee8811a9f5b9cf76893527cd">isVCSrc_f16</a>.</p>


<p>Referenced by <a href="#a1faab935a964d13e28192fc113617167">isVSrc_v2f16</a>.</p>

</div>
</div>

### isVSrc\_f32() {#aa6d88e23ab028267294b352ba3376ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a72d2637b8226831e335bf142e7b3f352">isExpr</a>, <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#ad8fe12b49b0c7a03fed208cbca0e4ede">isVCSrc_f32</a>.</p>

</div>
</div>

### isVSrc\_f64() {#a13c847f04f640a6cee8c84c6dc5d9a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_f64 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#adff38d575b028c1596d28fc393300701">isVCSrcF64</a>.</p>


<p>Referenced by <a href="#ad5268a4e8a67b227599b70277e9bcfe3">isVSrc_v2f32</a>.</p>

</div>
</div>

### isVSrc\_v2b16() {#a2ac4df4fbe4b2def95eea6a719f8256d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_v2b16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a54a78c8a10831c329069d19520bec727">isVSrc_b16</a>.</p>

</div>
</div>

### isVSrc\_v2b32() {#aa509fd036e9e1ff80630fbe94d3b36e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_v2b32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#aa48e0b8ebc7807de5f0898b1c4efe077">isVSrc_b64</a>.</p>

</div>
</div>

### isVSrc\_v2bf16() {#a278fb6f3f94caa89b9314d30fb8b8a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_v2bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a897d91246a144118d006758146eee34f">isVSrc_bf16</a>.</p>

</div>
</div>

### isVSrc\_v2f16() {#a1faab935a964d13e28192fc113617167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_v2f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a1d6b62e40304b958fbc9cca21aedecd3">isVSrc_f16</a>.</p>

</div>
</div>

### isVSrc\_v2f32() {#ad5268a4e8a67b227599b70277e9bcfe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrc_v2f32 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a13c847f04f640a6cee8c84c6dc5d9a4e">isVSrc_f64</a>.</p>

</div>
</div>

### isVSrcFake16\_b16\_Lo128() {#a61fd9a51e14f86a2df225d3f30593fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcFake16_b16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#abd1ab4a403d410775f974625c9e8bbf3">isVCSrcFake16B16_Lo128</a>.</p>

</div>
</div>

### isVSrcFake16\_bf16\_Lo128() {#a7133ae6c0fc99a9a42ba41b5e7749d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcFake16_bf16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#ad95e4108e84a29408d15e70712fb49f8">isVCSrcFake16BF16_Lo128</a>.</p>

</div>
</div>

### isVSrcFake16\_f16\_Lo128() {#a236d692826d993d12f6820d2bd06a09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcFake16_f16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a41866dfbf7988eec964552aba0e25b4e">isVCSrcFake16F16_Lo128</a>.</p>

</div>
</div>

### isVSrcT\_b16() {#a4a1d0c2fde62ae9db0243656cc4bec98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcT_b16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#af560048eb60aa005581bb74c8de8514d">isVCSrcT_b16</a>.</p>

</div>
</div>

### isVSrcT\_b16\_Lo128() {#ac2ccc21f1a73275dfb48b5b37c1c4060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcT_b16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#ac96bb4d26e71bd18c598c1174f675dc2">isVCSrcTB16_Lo128</a>.</p>

</div>
</div>

### isVSrcT\_bf16() {#a1ef8393558f2ea052f688e52a6fb29e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcT_bf16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a9167f9ce445e37760af3e633cf57d325">isVCSrcTBF16</a>.</p>

</div>
</div>

### isVSrcT\_bf16\_Lo128() {#ace883242feabf817dc39df76f18057b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcT_bf16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a1af262eb98370b66d63ebaeafdc2435d">isVCSrcTBF16_Lo128</a>.</p>

</div>
</div>

### isVSrcT\_f16() {#a1f1bcb6e01cf7df4c9e5832e599f6871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcT_f16 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#ae2d3dc1d4b1f15d460b7eeb7508468a1">isVCSrcT_f16</a>.</p>

</div>
</div>

### isVSrcT\_f16\_Lo128() {#a69719e896a69ca1b37a8a67f1e44d577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isVSrcT_f16_Lo128 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a> and <a href="#a0be4c430001a4138b47e2191c44adf53">isVCSrcTF16_Lo128</a>.</p>

</div>
</div>

### print() {#a6f08b8953c3266dd113feccca78d6d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Definition at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#a414289a5d7344879a8c5d516f3bdab86">Expr</a>, <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#a9f901d3b6a8c3b686d2f3408de0fb817">getImmTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a2d1579b3e66d752d5d8ecae54574c9c8">llvm::AMDGPUInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20237283e8b9e354abec8dc5ab16bd16">llvm::getToken</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, <a href="#a219ae81b494ba96fd79663c2f27e6552">printImmTy</a> and <a href="#a4b514e34f4f64815edf9cc75f16d1c3e">Reg</a>.</p>

</div>
</div>

### setImm() {#a4f0cc54c4806ee12ce6186629b182240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImm (int64_t Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>

</div>
</div>

### setImmKindConst() {#a6a8d2feece61e3394cb02d59351ea70f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImmKindConst ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aa817fddb7d8c888c671fcebc15b4b76aa50e29a2fb9d43a6171af09db28869683">ImmKindTyConst</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="#aa952aa5bfb51a38178c0d47e0fc7aa7b">addLiteralImmOperand</a>.</p>

</div>
</div>

### setImmKindLiteral() {#a3a0ff009144236a6532b574438a50a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImmKindLiteral ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aa817fddb7d8c888c671fcebc15b4b76aa2bd93559ed7f83abbcde5cf9ecaeacb1">ImmKindTyLiteral</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="#aa952aa5bfb51a38178c0d47e0fc7aa7b">addLiteralImmOperand</a>.</p>

</div>
</div>

### setImmKindMandatoryLiteral() {#aa62444e32183814cbc01fb3c82c10eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImmKindMandatoryLiteral ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aa817fddb7d8c888c671fcebc15b4b76aa855228a5582f02236bfcb17481d6526e">ImmKindTyMandatoryLiteral</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="#aa952aa5bfb51a38178c0d47e0fc7aa7b">addLiteralImmOperand</a>.</p>

</div>
</div>

### setImmKindNone() {#adfa64c48e281a33a5607fc828e5ad626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setImmKindNone ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aa817fddb7d8c888c671fcebc15b4b76aa9de751338cf92de88f4221d6ba6259ef">ImmKindTyNone</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>.</p>


<p>Referenced by <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>.</p>

</div>
</div>

### setModifiers() {#a8f2051721c4ee3fcd990beca23c4aa40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::setModifiers (<a href="/web-llvm/docs/api/structs/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/modifiers">Modifiers</a> Mods)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbb76f965a3113c7f2c22e89c3ecc86d">Imm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>, <a href="#a19f81f50fd5f4905ff667d77173591f3">isRegKind</a> and <a href="#a4b514e34f4f64815edf9cc75f16d1c3e">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Expr {#a414289a5d7344879a8c5d516f3bdab86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>, <a href="#a4e67ee2af4aa2b58e472d12c10b2a427">CreateExpr</a>, <a href="#a43ad7d3a52a625302db35bf74a9a3836">isSymbolRefExpr</a> and <a href="#a6f08b8953c3266dd113feccca78d6d12">print</a>.</p>

</div>
</div>

### Imm {#afbb76f965a3113c7f2c22e89c3ecc86d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmOp anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#aecc4bcb6c40064c4c0544f55facbb18a">addImmOperands</a>, <a href="#aa952aa5bfb51a38178c0d47e0fc7aa7b">addLiteralImmOperand</a>, <a href="#ae3252f98d20c96f775dd0286d1a2f830">applyInputFPModifiers</a>, <a href="#a9be6a3c0e7c06fd610c52d9654ee3f59">getImm</a>, <a href="#a9f901d3b6a8c3b686d2f3408de0fb817">getImmTy</a>, <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>, <a href="#ad73d4a40efb842b0d24538c757cc5a52">isDPPCtrl</a>, <a href="#a621031fa88ed3052303329e1d5f55c06">isImmKindConst</a>, <a href="#a5329f028dc85cb9c189110eb90309790">IsImmKindLiteral</a>, <a href="#afb66e6b20daee99ff51c1de598caaeda">IsImmKindMandatoryLiteral</a>, <a href="#af02a39c837b571df2b4d3712264ca6c2">isImmModifier</a>, <a href="#a6a85de263ff8282b792ad4dd660a4016">isImmTy</a>, <a href="#ab28800a685d06a879d56b4d178e85aa5">isInlinableImm</a>, <a href="#a55cada066d6192320d0ca6c3033e9faf">isLiteralImm</a>, <a href="#a6f08b8953c3266dd113feccca78d6d12">print</a>, <a href="#a4f0cc54c4806ee12ce6186629b182240">setImm</a>, <a href="#a6a8d2feece61e3394cb02d59351ea70f">setImmKindConst</a>, <a href="#a3a0ff009144236a6532b574438a50a45">setImmKindLiteral</a>, <a href="#aa62444e32183814cbc01fb3c82c10eee">setImmKindMandatoryLiteral</a>, <a href="#adfa64c48e281a33a5607fc828e5ad626">setImmKindNone</a> and <a href="#a8f2051721c4ee3fcd990beca23c4aa40">setModifiers</a>.</p>

</div>
</div>

### Reg {#a4b514e34f4f64815edf9cc75f16d1c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegOp anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a9ceb192ff77adbd8ddbbddaa9a38ae99">CreateReg</a>, <a href="#a9635992e290c74d396d5f1ad11626fb7">getModifiers</a>, <a href="#a5c2d5cb768dd61ffc311e44a67d7b292">getReg</a>, <a href="#a6f08b8953c3266dd113feccca78d6d12">print</a> and <a href="#a8f2051721c4ee3fcd990beca23c4aa40">setModifiers</a>.</p>

</div>
</div>

### Tok {#a1720fbf7efeb1ec77165c477b8d425c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokOp anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a9836d66cf9617f7396887c361cbbded0">getToken</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#aa9444ed4bbedf5ff68ed5bff8e2ee4d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### AsmParser {#a178b1222a97385c6745ffc5f0fe4cb32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AMDGPUAsmParser* anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::AsmParser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### EndLoc {#aa402a81bfaac6401d2c34e5621789452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### Kind {#a8ab954bc1f2652c7944e9ff2879bbfea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::KindTy anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

### StartLoc {#a256f9a512e08b63e3f303e6ca808f196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CreateExpr() {#a4e67ee2af4aa2b58e472d12c10b2a427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUOperand::Ptr anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser">AMDGPUAsmParser</a> * AsmParser, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> class <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S)</td>
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



<p>Definition at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a414289a5d7344879a8c5d516f3bdab86">Expr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>.</p>

</div>
</div>

### CreateImm() {#aa6d2ada1e702e79ab63562d3cbd03ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUOperand::Ptr anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser">AMDGPUAsmParser</a> * AsmParser, int64_t Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="#aac6196abacab3897ea9874e72d3db8fc">ImmTy</a> Type=<a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, bool IsFPImm=false)</td>
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



<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aa817fddb7d8c888c671fcebc15b4b76aa9de751338cf92de88f4221d6ba6259ef">ImmKindTyNone</a> and <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa54525f0109858da308fa32559539255">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDepCtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c31665501f9b711e245f1b4e201683b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDim</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a59d9c798683c4a134a731c43840d62aa">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPP8</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af1e3005e43d45d207eb661fa024b1753">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPPCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a0b822486044ee842c7c868f39ff4830b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseEndpgm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a26a8456ca91f0f85ed2f854837b0dc29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseExpTgt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aae18974f031b21f7dd37b072a1cbe24d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFORMAT</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ad03402b69301c9df929a7ca211df947c">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseGPRIdxMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a16bbeaa5435876a2a30093aa9f7adc09">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseHwreg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c3abd5a0df4ec19738884622846a92b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abc5a32fe7c02fdcfc1484e926e376ce0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4bbb3e5e0e2e2c935c2a911665fff611">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab2ff8b8fa2100a684cea688b74d329ab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseNamedBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac9d07a4881948a410fcba201eeb36480">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperandArrayWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a493337bf1e3308881e03af9142a5bb5a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSDelayALU</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a7e026648ec951bc9ce02a0e99e31f583">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSendMsg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a11669d3b022f7e99114faaf694659b89">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac3b25b92e123263ee61ca38bdee04828">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSWaitCnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a45d3320cf47a5c534c3e884ea6501728">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSwizzle</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aad55de4993c720c50d992a7cbda3d8d3">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVReg32OrOff</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a971176e60129a0824a8c1e2a193e6b62">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::tryParseIndexKey</a>.</p>

</div>
</div>

### CreateReg() {#a9ceb192ff77adbd8ddbbddaa9a38ae99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUOperand::Ptr anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser">AMDGPUAsmParser</a> * AsmParser, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> S, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> E)</td>
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



<p>Definition at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Reference <a href="#a4b514e34f4f64815edf9cc75f16d1c3e">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abe4d54f7147e2f219afa02529b48a0d0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegister</a>.</p>

</div>
</div>

### CreateToken() {#a3f085efcb427da17842f4447cea3d0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUOperand::Ptr anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::CreateToken (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser">AMDGPUAsmParser</a> * AsmParser, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, bool HasExplicitEncodingSize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af09dfe84acccdfc6a55c91388892da8e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2f6673e616e48f8b6505d19ef64eddab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a40cae821d596ce5a10da36c3d1836dac">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTokenOp</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c71cb47a3f1bcc8147c44cc1395ed63">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVOPD</a>.</p>

</div>
</div>

### printImmTy() {#a219ae81b494ba96fd79663c2f27e6552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::printImmTy (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="#aac6196abacab3897ea9874e72d3db8fc">ImmTy</a> Type)</td>
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



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a>.</p>


<p>References <a href="#aac6196abacab3897ea9874e72d3db8fca3927f830d00f75bb2e2aba10856298af">ImmTyA16</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaff79a4732a62ef261c2666f8969ffbc2">ImmTyABID</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca2e44e7cd0be59ea7aec6573e8ee82b11">ImmTyAddr64</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaeebf6baf32daa73a0a7b0357b663e6c9">ImmTyBitOp3</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaf1b6a24364959b43f2ba2a7cbe099577">ImmTyBLGP</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca040e9137b23fb0a740bfb222d4911c49">ImmTyByteSel</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcac9aae4585818d04952ecfcdd0e508ba6">ImmTyCBSZ</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaf005c69ec582b7a5d66df13f4e317a1e">ImmTyClamp</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcae93a1de3d01070de353bc7ac2c243eaf">ImmTyCPol</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcade6e1db88c135faeb133cc36d84133db">ImmTyD16</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca81a6f096c7f264f016225663a3d4870e">ImmTyDA</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaf6aeca3fc739d2f9fa57dfe5180bb8cd">ImmTyDim</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca1f29992c88d5b26bf766e3df3df8cd08">ImmTyDMask</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaf79a7cadd64c125693239a99d15776d4">ImmTyDPP8</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca107c472f8bfeb150ed0737921a85e408">ImmTyDppBankMask</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca9551790c26c1cb431ce82ab01f748a53">ImmTyDppBoundCtrl</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca9e3ba413ec741a423d42d99974585677">ImmTyDppCtrl</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca07d5a47db7db2fcf76162ad332f72686">ImmTyDppFI</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca8bb6ce8b62f92662c470a40065d126af">ImmTyDppRowMask</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca53303dcc815ab55f8a1f737852055ded">ImmTyEndpgm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca2ff55b791397522185702a9ff4701ef5">ImmTyExpCompr</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca8b92c2d67ca16440f8c439f063c4c32b">ImmTyExpTgt</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca5b645a3daa82f94403a3ae30c2ab1089">ImmTyExpVM</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca86191e0af51710ca8b408b289300cf0d">ImmTyFORMAT</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcad673fd3693f21e595b61e0efcfebace7">ImmTyGDS</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcad4fc7a84a69230aae91424d2ef3daf73">ImmTyGprIdxMode</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcab73f5f2d6a06746d900ab0d87a8e76e1">ImmTyHigh</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcac8698f7407c44136e38a954eee31ec18">ImmTyHwreg</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcad781363033c69b70fe169821750b5382">ImmTyIdxen</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca4df6d1cb3360e33d52bed3dd55d9342e">ImmTyIndexKey16bit</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca3b0787bbfe8d09244425732c5a8840d7">ImmTyIndexKey8bit</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca45cf846b7e62d831b596bccad4de5315">ImmTyInstOffset</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca2d980b3c725150072bc1bca3b9717703">ImmTyInterpAttr</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcadc4ee0d2f112f47edabec0e19de95b2d">ImmTyInterpAttrChan</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcac16758e9406b631d54854588a576a29c">ImmTyInterpSlot</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca80ad15588035616b5caa13260dc56b08">ImmTyLDS</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca0cfc729dac9bc32b37a71468c6bdf5d5">ImmTyLWE</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca2ee46e789b1dd972067b15f482dacf06">ImmTyNegHi</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca4ebfe90c5e76cde6ee3867f75a62f8a8">ImmTyNegLo</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaa685e5bd5b6d415252efb40a82ce1a28">ImmTyNone</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca96a2e9977c530f18cdc5cdde12de257b">ImmTyOff</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca3fe0f6956d2f2effc84c174dc25a2b22">ImmTyOffen</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca02f46f2486aed0107b1313c8c7bae9b7">ImmTyOffset</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca5f8d155a94f097a3022ae8a9b7d2e4f0">ImmTyOffset0</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca584b3a4b355022c91b09dbbd3f2b1405">ImmTyOffset1</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaf4e10bb6d0fda8ad54cca3f45eb2b143">ImmTyOModSI</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaf3ba690efda9412129e1195c93663d18">ImmTyOpSel</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca7e67cef1f3b30e0fc5a6fc222f578c13">ImmTyOpSelHi</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcaf99873ea3e78297b518afa494e67c3c6">ImmTyR128A16</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca5ef6d8d490dc55a1a768223f15a959a3">ImmTySDWADstSel</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca38365958fa12a0f2acd965b2bc77ea00">ImmTySDWADstUnused</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcae0c54cec4b9a48401c2fd0dc32b9da24">ImmTySDWASrc0Sel</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca066b849c42884b62cdb679dd05d1c28d">ImmTySDWASrc1Sel</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcac149121124fe545cec0d7688ea39f435">ImmTySendMsg</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca0ccfbff250cbfb289053232b65749936">ImmTySMEMOffsetMod</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcae245f2c36be17caa96752cf101b62796">ImmTySwizzle</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca0d40ab857cb9338f800d4102f5a5fb3c">ImmTyTFE</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca0c4e23b098ddd5180afbf78977ed41af">ImmTyUNorm</a>, <a href="#aac6196abacab3897ea9874e72d3db8fcadeeea91bbd0d55b997e0f5291a4a1a7e">ImmTyWaitEXP</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca5420c16e9aeb6a59d9e86fd7e27fe1a1">ImmTyWaitVAVDst</a>, <a href="#aac6196abacab3897ea9874e72d3db8fca17398b0656ee9d08f195d7bbe365a579">ImmTyWaitVDST</a> and <a href="#aac6196abacab3897ea9874e72d3db8fca5d154083374c99ac14f3f41fc325df26">ImmTyWaitVMVSrc</a>.</p>


<p>Referenced by <a href="#a6f08b8953c3266dd113feccca78d6d12">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp">AMDGPUAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
