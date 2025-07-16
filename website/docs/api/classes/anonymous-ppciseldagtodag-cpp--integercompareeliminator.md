---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppciseldagtodag-cpp-/integercompareeliminator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IntegerCompareEliminator` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExtOrTruncConversion { <a href="#a293938d62836b41ad57863233dccec34">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SetccInGPROpts { <a href="#afe2fee4548eb2aa03ea67065673596cb">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ZeroCompare { <a href="#acf51a1855781a5537af6359dfbade8fe">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d54fcc151434a5727fbbb229a2cfbd5">IntegerCompareEliminator</a> (SelectionDAG *DAG, PPCDAGToDAGISel *Sel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09fe3134a2922596d0704bf13f38560d">Select</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaebc3e2ef0c7c17dbb6d81117b1df4c">tryEXTEND</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e0e52d0c5d99a60c79f41040cbcc5f">tryLogicOpOfCompares</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76347c84821508b067e8e7c60bafb38b">computeLogicOpInGPR</a> (SDValue LogicOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb666cab1615585574d98a85a1e1a55">signExtendInputIfNeeded</a> (SDValue Input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the value isn't guaranteed to be sign-extended to 64-bits, extend it. <a href="#a8cb666cab1615585574d98a85a1e1a55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3df2f4ccab05de99625ca6bfe140a3d">zeroExtendInputIfNeeded</a> (SDValue Input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the value isn't guaranteed to be zero-extended to 64-bits, extend it. <a href="#ad3df2f4ccab05de99625ca6bfe140a3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18723b91ca76ae662f4b13a58bd0c4f">addExtOrTrunc</a> (SDValue NatWidthRes, ExtOrTruncConversion Conv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de7a54fac74c1efeb2ba10aa1e8bda7">getCompoundZeroComparisonInGPR</a> (SDValue LHS, SDLoc dl, ZeroCompare CmpTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d6f57fbd6cb298473df607f9b60c0eb">get32BitZExtCompare</a> (SDValue LHS, SDValue RHS, ISD::CondCode CC, int64_t RHSValue, SDLoc dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produces a zero-extended result of comparing two 32-bit values according to the passed condition code. <a href="#a3d6f57fbd6cb298473df607f9b60c0eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb6750b5fc7bfde4125609bd2a31c17">get32BitSExtCompare</a> (SDValue LHS, SDValue RHS, ISD::CondCode CC, int64_t RHSValue, SDLoc dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produces a sign-extended result of comparing two 32-bit values according to the passed condition code. <a href="#aafb6750b5fc7bfde4125609bd2a31c17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d1f78fcb7c437defc112efc6e183a8">get64BitZExtCompare</a> (SDValue LHS, SDValue RHS, ISD::CondCode CC, int64_t RHSValue, SDLoc dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produces a zero-extended result of comparing two 64-bit values according to the passed condition code. <a href="#ac1d1f78fcb7c437defc112efc6e183a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6def93402ba6be746b78a1b63a4d5b0">get64BitSExtCompare</a> (SDValue LHS, SDValue RHS, ISD::CondCode CC, int64_t RHSValue, SDLoc dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produces a sign-extended result of comparing two 64-bit values according to the passed condition code. <a href="#ab6def93402ba6be746b78a1b63a4d5b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e246c3623a788877f0b8c90233e7d24">getSETCCInGPR</a> (SDValue Compare, SetccInGPROpts ConvOpts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an equivalent of a SETCC node but with the result the same width as the inputs. <a href="#a8e246c3623a788877f0b8c90233e7d24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67b95495c9c5a3069726aaf50f38e979">CurDAG</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel">PPCDAGToDAGISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dee0424971a329fb739745f6d542b4c">S</a></td>
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


<p>Definition at line 2880 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ExtOrTruncConversion {#a293938d62836b41ad57863233dccec34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::ExtOrTruncConversion </td>
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
<td class="doxyEnumItemName">Ext<a id="a293938d62836b41ad57863233dccec34aba8a4045195a16296fdc366c22801255"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Trunc<a id="a293938d62836b41ad57863233dccec34a59b3bcb26b31fddb56a11119cf09094b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2885 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SetccInGPROpts {#afe2fee4548eb2aa03ea67065673596cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::SetccInGPROpts </td>
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
<td class="doxyEnumItemName">ZExtOrig<a id="afe2fee4548eb2aa03ea67065673596cba58df36870c00083e73f87ec5cf9e4bb8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZExtInvert<a id="afe2fee4548eb2aa03ea67065673596cba0aca97297da0bffb63d44812fa3b8c24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SExtOrig<a id="afe2fee4548eb2aa03ea67065673596cba0237a13640d3b4c1f432599ad17ad2b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SExtInvert<a id="afe2fee4548eb2aa03ea67065673596cbacdbd5c125778862968beeb8a48d6536c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### ZeroCompare {#acf51a1855781a5537af6359dfbade8fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::ZeroCompare </td>
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
<td class="doxyEnumItemName">GEZExt<a id="acf51a1855781a5537af6359dfbade8feaf24556482033c40ead2cb8a7988400b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GESExt<a id="acf51a1855781a5537af6359dfbade8feacc3ff5634f4be5907ca1929d4c679033"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LEZExt<a id="acf51a1855781a5537af6359dfbade8feaf9317eb0dc8cd4b936289814dd571033"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LESExt<a id="acf51a1855781a5537af6359dfbade8fea1528d3cfda5c65f41cfe4a219e7c51ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2903 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IntegerCompareEliminator() {#a0d54fcc151434a5727fbbb229a2cfbd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::IntegerCompareEliminator (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * DAG, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel">PPCDAGToDAGISel</a> * Sel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2924 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Select() {#a09fe3134a2922596d0704bf13f38560d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2930 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#abc05a2c90af0bfe474b0e38a7bf51732">CmpInGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af98288f640b90a42d9fa3219fc7a0159a1120ee27d21389fb4cbbc50ac551c9f3">ICGPR_None</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af98288f640b90a42d9fa3219fc7a0159a1c057dad85dd6eed8a1d671e4ae495c2">ICGPR_Sext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af98288f640b90a42d9fa3219fc7a0159ad896e7629dae1cf5b0c5910f48774879">ICGPR_SextI32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af98288f640b90a42d9fa3219fc7a0159a99254e699a51e90e00b627a2caa096dc">ICGPR_SextI64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af98288f640b90a42d9fa3219fc7a0159aeab9c0f3301b5859067f840751fc8ec8">ICGPR_Zext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af98288f640b90a42d9fa3219fc7a0159a0490775682f0c28a2244221f749f4bec">ICGPR_ZextI32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af98288f640b90a42d9fa3219fc7a0159a9f7e973a9c9f60f18a2087a937dac2f4">ICGPR_ZextI64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#aa5129e150e18937b6123e93990c1c903">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryIntCompareInGPR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addExtOrTrunc() {#af18723b91ca76ae662f4b13a58bd0c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::addExtOrTrunc (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> NatWidthRes, ExtOrTruncConversion Conv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2910 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### computeLogicOpInGPR() {#a76347c84821508b067e8e7c60bafb38b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::computeLogicOpInGPR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LogicOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2907 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### get32BitSExtCompare() {#aafb6750b5fc7bfde4125609bd2a31c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::get32BitSExtCompare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC, int64_t RHSValue, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produces a sign-extended result of comparing two 32-bit values according to the passed condition code.</p>

<p>Definition at line 2915 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### get32BitZExtCompare() {#a3d6f57fbd6cb298473df607f9b60c0eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::get32BitZExtCompare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC, int64_t RHSValue, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produces a zero-extended result of comparing two 32-bit values according to the passed condition code.</p>

<p>Definition at line 2913 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### get64BitSExtCompare() {#ab6def93402ba6be746b78a1b63a4d5b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::get64BitSExtCompare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC, int64_t RHSValue, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produces a sign-extended result of comparing two 64-bit values according to the passed condition code.</p>

<p>Definition at line 2919 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### get64BitZExtCompare() {#ac1d1f78fcb7c437defc112efc6e183a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::get64BitZExtCompare (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC, int64_t RHSValue, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produces a zero-extended result of comparing two 64-bit values according to the passed condition code.</p>

<p>Definition at line 2917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getCompoundZeroComparisonInGPR() {#a6de7a54fac74c1efeb2ba10aa1e8bda7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::getCompoundZeroComparisonInGPR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> dl, ZeroCompare CmpTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2911 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getSETCCInGPR() {#a8e246c3623a788877f0b8c90233e7d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::getSETCCInGPR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Compare, SetccInGPROpts ConvOpts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an equivalent of a SETCC node but with the result the same width as the inputs.</p>


<p>This can also be used for SELECT_CC if either the true or false values is a power of two while the other is zero.</p>


<p>Definition at line 2921 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### signExtendInputIfNeeded() {#a8cb666cab1615585574d98a85a1e1a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::signExtendInputIfNeeded (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the value isn't guaranteed to be sign-extended to 64-bits, extend it.</p>


<p>Otherwise just reinterpret it as a 64-bit value. Useful when emitting comparison code for 32-bit values without using the compare instruction (which only considers the lower 32-bits).</p>


<p>Definition at line 2908 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryEXTEND() {#aeaebc3e2ef0c7c17dbb6d81117b1df4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::tryEXTEND (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2905 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryLogicOpOfCompares() {#a36e0e52d0c5d99a60c79f41040cbcc5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::tryLogicOpOfCompares (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2906 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### zeroExtendInputIfNeeded() {#ad3df2f4ccab05de99625ca6bfe140a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::zeroExtendInputIfNeeded (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the value isn't guaranteed to be zero-extended to 64-bits, extend it.</p>


<p>Otherwise just reinterpret it as a 64-bit value. Useful when emitting comparison code for 32-bit values without using the compare instruction (which only considers the lower 32-bits).</p>


<p>Definition at line 2909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurDAG {#a67b95495c9c5a3069726aaf50f38e979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG* anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::CurDAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### S {#a4dee0424971a329fb739745f6d542b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCDAGToDAGISel* anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::S</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
