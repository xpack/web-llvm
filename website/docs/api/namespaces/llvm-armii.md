---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/armii
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ARMII` Namespace Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/armii">ARMII</a> - This namespace holds all of the target specific flags that instruction info tracks. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::ARMII { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IndexMode { <a href="#ac3c83a9ce4f6ef1a90d63ebe5722b2b9">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Index Modes. <a href="#ac3c83a9ce4f6ef1a90d63ebe5722b2b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AddrMode { <a href="#ace99f086a3cd38c7477a8f038dae7ff4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Addressing Modes. <a href="#ace99f086a3cd38c7477a8f038dae7ff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TOF { <a href="#ac33037e230d127af6de7945ce02e7e5a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum. <a href="#ac33037e230d127af6de7945ce02e7e5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a3c06fab2f468e615484900041c216ef4">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ebee24b01a327206fea442c3a9ba32c">AddrModeToString</a> (AddrMode addrmode)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/armii">ARMII</a> - This namespace holds all of the target specific flags that instruction info tracks.</p>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a3c06fab2f468e615484900041c216ef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">AddrModeMask<a id="a3c06fab2f468e615484900041c216ef4aeda154c828d692cd52ca6cce8765f9ae"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1f)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IndexModeShift<a id="a3c06fab2f468e615484900041c216ef4ac928721626de611c1e5c7acfd4e05f79"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IndexModeMask<a id="a3c06fab2f468e615484900041c216ef4a090893e44b7d8da1ed8e65cc6b586ae8"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; IndexModeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FormShift<a id="a3c06fab2f468e615484900041c216ef4aeb065ca21ad29e8a7d32c082ede45a66"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FormMask<a id="a3c06fab2f468e615484900041c216ef4a2adb030227483dbcc19765434c480053"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3f &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pseudo<a id="a3c06fab2f468e615484900041c216ef4aed92c669415789f4004e04ce570c8f1c"></a></td>
<td class="doxyEnumItemDescription"> (= 0  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MulFrm<a id="a3c06fab2f468e615484900041c216ef4a006df21e89b915d452a0a769edbd1c64"></a></td>
<td class="doxyEnumItemDescription"> (= 1  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BrFrm<a id="a3c06fab2f468e615484900041c216ef4a02160fd481cae2cd1b67c3972fda2397"></a></td>
<td class="doxyEnumItemDescription"> (= 2  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BrMiscFrm<a id="a3c06fab2f468e615484900041c216ef4a08700a751be869c90ae442a171afe858"></a></td>
<td class="doxyEnumItemDescription"> (= 3  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPFrm<a id="a3c06fab2f468e615484900041c216ef4abcecd5036b40b4aebaf01b2304f9c002"></a></td>
<td class="doxyEnumItemDescription"> (= 4  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPSoRegFrm<a id="a3c06fab2f468e615484900041c216ef4a653792773bc83f55fb36b21305e6de5e"></a></td>
<td class="doxyEnumItemDescription"> (= 5  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LdFrm<a id="a3c06fab2f468e615484900041c216ef4a54e0e908afc2e3d77d473f3d9abaa419"></a></td>
<td class="doxyEnumItemDescription"> (= 6  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StFrm<a id="a3c06fab2f468e615484900041c216ef4aeee41de1ecfcbcd5fef848c94b559712"></a></td>
<td class="doxyEnumItemDescription"> (= 7  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LdMiscFrm<a id="a3c06fab2f468e615484900041c216ef4ae03ef20f695068dc8dbf598c887ea700"></a></td>
<td class="doxyEnumItemDescription"> (= 8  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StMiscFrm<a id="a3c06fab2f468e615484900041c216ef4a7b4be3b089abbb825c716a376f3e114e"></a></td>
<td class="doxyEnumItemDescription"> (= 9  &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LdStMulFrm<a id="a3c06fab2f468e615484900041c216ef4a97c22f7cbddcad1dbeb521c20ba84de5"></a></td>
<td class="doxyEnumItemDescription"> (= 10 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LdStExFrm<a id="a3c06fab2f468e615484900041c216ef4a0400fa94ac704cb3984523d5c16e8bb0"></a></td>
<td class="doxyEnumItemDescription"> (= 11 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ArithMiscFrm<a id="a3c06fab2f468e615484900041c216ef4aa5488270aef645f4683a4b7439dfa11e"></a></td>
<td class="doxyEnumItemDescription"> (= 12 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SatFrm<a id="a3c06fab2f468e615484900041c216ef4a37835bffd4595083a55ada78410fe71d"></a></td>
<td class="doxyEnumItemDescription"> (= 13 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtFrm<a id="a3c06fab2f468e615484900041c216ef4a7f14067fceeb0b3b0639686c496e060e"></a></td>
<td class="doxyEnumItemDescription"> (= 14 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPUnaryFrm<a id="a3c06fab2f468e615484900041c216ef4a8cdaddf1a0ccd3d3f65afa9da3eb1ff6"></a></td>
<td class="doxyEnumItemDescription"> (= 15 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPBinaryFrm<a id="a3c06fab2f468e615484900041c216ef4a55a0264b50af6c9521be3cca1fc11deb"></a></td>
<td class="doxyEnumItemDescription"> (= 16 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPConv1Frm<a id="a3c06fab2f468e615484900041c216ef4ace98e5833d0ad68d4dfd21a7bbb36628"></a></td>
<td class="doxyEnumItemDescription"> (= 17 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPConv2Frm<a id="a3c06fab2f468e615484900041c216ef4a7e043cecc6009d49df47e8d074a19c60"></a></td>
<td class="doxyEnumItemDescription"> (= 18 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPConv3Frm<a id="a3c06fab2f468e615484900041c216ef4ae60d56f8279fc06daae3281e3449fe0b"></a></td>
<td class="doxyEnumItemDescription"> (= 19 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPConv4Frm<a id="a3c06fab2f468e615484900041c216ef4a9b54c591f98cde359c5c2857c7ab2d99"></a></td>
<td class="doxyEnumItemDescription"> (= 20 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPConv5Frm<a id="a3c06fab2f468e615484900041c216ef4a440645dc8daf6b8f44950cdc6201260e"></a></td>
<td class="doxyEnumItemDescription"> (= 21 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPLdStFrm<a id="a3c06fab2f468e615484900041c216ef4a083e564b421567ee4954f484ba5ece1a"></a></td>
<td class="doxyEnumItemDescription"> (= 22 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPLdStMulFrm<a id="a3c06fab2f468e615484900041c216ef4acaab8ffeec66c151991cdf71966cd843"></a></td>
<td class="doxyEnumItemDescription"> (= 23 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VFPMiscFrm<a id="a3c06fab2f468e615484900041c216ef4a4cc69ded331759e666b971b4d14628c5"></a></td>
<td class="doxyEnumItemDescription"> (= 24 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThumbFrm<a id="a3c06fab2f468e615484900041c216ef4a9fbfad472c878dd4554adbfae06693a9"></a></td>
<td class="doxyEnumItemDescription"> (= 25 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MiscFrm<a id="a3c06fab2f468e615484900041c216ef4a06dd044ed6acb9826d80386eb15221da"></a></td>
<td class="doxyEnumItemDescription"> (= 26 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NGetLnFrm<a id="a3c06fab2f468e615484900041c216ef4a52b6190553781624b764a3c8454cda16"></a></td>
<td class="doxyEnumItemDescription"> (= 27 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NSetLnFrm<a id="a3c06fab2f468e615484900041c216ef4a61e15e5537018c68c1dc4c8c7af1eb77"></a></td>
<td class="doxyEnumItemDescription"> (= 28 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NDupFrm<a id="a3c06fab2f468e615484900041c216ef4a19ab1060b2d8a62e0de9f7661e166dbe"></a></td>
<td class="doxyEnumItemDescription"> (= 29 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NLdStFrm<a id="a3c06fab2f468e615484900041c216ef4abf321dee38fdea651747214ea2ea1ffc"></a></td>
<td class="doxyEnumItemDescription"> (= 30 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N1RegModImmFrm<a id="a3c06fab2f468e615484900041c216ef4a813add07fa7b80b98d9a16d2edad426a"></a></td>
<td class="doxyEnumItemDescription"> (= 31 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N2RegFrm<a id="a3c06fab2f468e615484900041c216ef4a20ef9d68e9f16d0358a8dfdd2ea68700"></a></td>
<td class="doxyEnumItemDescription"> (= 32 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NVCVTFrm<a id="a3c06fab2f468e615484900041c216ef4ad5f777a9436bbde8ff5c4e862bc0a796"></a></td>
<td class="doxyEnumItemDescription"> (= 33 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NVDupLnFrm<a id="a3c06fab2f468e615484900041c216ef4a517430e55d5079566447a04c0489d06a"></a></td>
<td class="doxyEnumItemDescription"> (= 34 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N2RegVShLFrm<a id="a3c06fab2f468e615484900041c216ef4abf176c7758ef5168e5e59cd24e8101b7"></a></td>
<td class="doxyEnumItemDescription"> (= 35 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N2RegVShRFrm<a id="a3c06fab2f468e615484900041c216ef4a6e76a8fcd56b5f6a73eb780d8fc8d22c"></a></td>
<td class="doxyEnumItemDescription"> (= 36 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N3RegFrm<a id="a3c06fab2f468e615484900041c216ef4ad38e890e4c084c45101c55cd233a9dbf"></a></td>
<td class="doxyEnumItemDescription"> (= 37 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N3RegVShFrm<a id="a3c06fab2f468e615484900041c216ef4a169b6db4b5b9264244cd4166a78b1b70"></a></td>
<td class="doxyEnumItemDescription"> (= 38 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NVExtFrm<a id="a3c06fab2f468e615484900041c216ef4a48ed4454dbda05b840f1874c8d9689a4"></a></td>
<td class="doxyEnumItemDescription"> (= 39 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NVMulSLFrm<a id="a3c06fab2f468e615484900041c216ef4a6b9b9c5631dba89b4b76a1c87ba2f6f0"></a></td>
<td class="doxyEnumItemDescription"> (= 40 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NVTBLFrm<a id="a3c06fab2f468e615484900041c216ef4a5764adb65f2701530fbe23f4df0fe3f9"></a></td>
<td class="doxyEnumItemDescription"> (= 41 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N3RegCplxFrm<a id="a3c06fab2f468e615484900041c216ef4ac259adb2a48175d5fb0a15c4fa2da02e"></a></td>
<td class="doxyEnumItemDescription"> (= 43 &lt;&lt; FormShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnaryDP<a id="a3c06fab2f468e615484900041c216ef4afef2da459a1ccbc0366f94e72d46a443"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Xform16Bit<a id="a3c06fab2f468e615484900041c216ef4a4366f74e8766401ae0662bc25f409fce"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThumbArithFlagSetting<a id="a3c06fab2f468e615484900041c216ef4a357fee59a6e283ccb47175016e6f9af1"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ValidForTailPredication<a id="a3c06fab2f468e615484900041c216ef4a6f4d311cce1cd30c215499f79215051c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RetainsPreviousHalfElement<a id="a3c06fab2f468e615484900041c216ef4aa25c5be216c7a89861b0ef6822601465"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HorizontalReduction<a id="a3c06fab2f468e615484900041c216ef4a9e2a02c8e15c43cfe03fee48f85f76cf"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DoubleWidthResult<a id="a3c06fab2f468e615484900041c216ef4a1d1ee0a18b878ed2571430f0b9ba7441"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecSizeShift<a id="a3c06fab2f468e615484900041c216ef4a07023b4966d755e56b328349ef01a237"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecSize<a id="a3c06fab2f468e615484900041c216ef4a479711d0ab662307550fc709665589ea"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; VecSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DomainShift<a id="a3c06fab2f468e615484900041c216ef4aa012182c14f9c2482a58fa3364d1eb0d"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DomainMask<a id="a3c06fab2f468e615484900041c216ef4a96db53f04326f6421725b16e4ee7a596"></a></td>
<td class="doxyEnumItemDescription"> (= 15 &lt;&lt; DomainShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DomainGeneral<a id="a3c06fab2f468e615484900041c216ef4a97f18b4a92c5fb6c0a355460b38972f7"></a></td>
<td class="doxyEnumItemDescription"> (= 0 &lt;&lt; DomainShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DomainVFP<a id="a3c06fab2f468e615484900041c216ef4a0fecec4134a451feb93566a8a0a75ae1"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; DomainShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DomainNEON<a id="a3c06fab2f468e615484900041c216ef4a0f4e17fd43419980264bba50ce572d60"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; DomainShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DomainNEONA8<a id="a3c06fab2f468e615484900041c216ef4a23ab698d5fa355a202fb1f18b173f811"></a></td>
<td class="doxyEnumItemDescription"> (= 4 &lt;&lt; DomainShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DomainMVE<a id="a3c06fab2f468e615484900041c216ef4ab5112bfba90c616984021580dd1131b8"></a></td>
<td class="doxyEnumItemDescription"> (= 8 &lt;&lt; DomainShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ShiftTypeShift<a id="a3c06fab2f468e615484900041c216ef4ad1438da72fa84bb6273b19642b30102d"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">M_BitShift<a id="a3c06fab2f468e615484900041c216ef4a00618e8ddecff544a382f17eee5b1f17"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ShiftImmShift<a id="a3c06fab2f468e615484900041c216ef4a94937c6fd582b2b1c2e513261e2a9f80"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ShiftShift<a id="a3c06fab2f468e615484900041c216ef4a2d3a85693ba6b152664ce982d29ef6c9"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N_BitShift<a id="a3c06fab2f468e615484900041c216ef4ae5d393a29f5b96b3f5734c9befd48fe8"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmHiShift<a id="a3c06fab2f468e615484900041c216ef4aee6c849e05dd360134f0dfc493fbf5ee"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SoRotImmShift<a id="a3c06fab2f468e615484900041c216ef4ac6cab4f074287de9ba63f7c7ddebca89"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegRsShift<a id="a3c06fab2f468e615484900041c216ef4a9f2608a8d94538cd4232d031fca8bb46"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtRotImmShift<a id="a3c06fab2f468e615484900041c216ef4a28ff2a20bba10e44877b2411edbe56da"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegRdLoShift<a id="a3c06fab2f468e615484900041c216ef4a25cbf3b6626bd02e6a550b889ee26164"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegRdShift<a id="a3c06fab2f468e615484900041c216ef4adec90df1e2b27389e60353f2422929c9"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegRdHiShift<a id="a3c06fab2f468e615484900041c216ef4a35364c7a76e6b2ce75528767f3ab8ce4"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegRnShift<a id="a3c06fab2f468e615484900041c216ef4a9d7f7bfd2c073070a0e5ff0c5e50961e"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_BitShift<a id="a3c06fab2f468e615484900041c216ef4a73612ad488b92b52c6e6290dfc010c64"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">W_BitShift<a id="a3c06fab2f468e615484900041c216ef4addcc7038e5a00aa5613be7c281e890da"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AM3_I_BitShift<a id="a3c06fab2f468e615484900041c216ef4a31dc8b6b925501ece3070d3c9aac0441"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">D_BitShift<a id="a3c06fab2f468e615484900041c216ef4a220850d35e7d055471ce7aaec0761da2"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">U_BitShift<a id="a3c06fab2f468e615484900041c216ef4adf470c249d18957dba8b679fad3d55a0"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">P_BitShift<a id="a3c06fab2f468e615484900041c216ef4a5976e5fe0a3c2b3be52cfaf8662fbb2e"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I_BitShift<a id="a3c06fab2f468e615484900041c216ef4aaf198a659911e3a9f40ee0744794cd6d"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CondShift<a id="a3c06fab2f468e615484900041c216ef4a7803690ce38a1b0032a1c19d8c750c54"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a>.</p>

</div>
</div>

### AddrMode {#ace99f086a3cd38c7477a8f038dae7ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMII::AddrMode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Addressing Modes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeNone<a id="ace99f086a3cd38c7477a8f038dae7ff4a7231462a5c39f1e6f5277b897908683e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrMode1<a id="ace99f086a3cd38c7477a8f038dae7ff4a9e413b3d35ed41939d4632ff7a855725"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrMode2<a id="ace99f086a3cd38c7477a8f038dae7ff4a7d9742a01ea175053d76a714474d88a6"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrMode3<a id="ace99f086a3cd38c7477a8f038dae7ff4a3e943d975799a4c55333c54eac1a7991"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrMode4<a id="ace99f086a3cd38c7477a8f038dae7ff4a9dbb177d004cae6c3474b6aadc8ae07e"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrMode5<a id="ace99f086a3cd38c7477a8f038dae7ff4a0209ae669364c237e24dbc0c4df6036e"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrMode6<a id="ace99f086a3cd38c7477a8f038dae7ff4a8388bb748b26edbdb8bb5d5ab6f16853"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT1_1<a id="ace99f086a3cd38c7477a8f038dae7ff4abfbcc124d3a4fa763e275b5b199fd81b"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT1_2<a id="ace99f086a3cd38c7477a8f038dae7ff4a45c1a7867d7bed69326c02dca510e4cc"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT1_4<a id="ace99f086a3cd38c7477a8f038dae7ff4a27e4e6aef06beef44d8cc58e32c22fdc"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT1_s<a id="ace99f086a3cd38c7477a8f038dae7ff4a147ee44cd2b5425325839f5f0fa897ad"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_i12<a id="ace99f086a3cd38c7477a8f038dae7ff4a4f27c00983ba7efdb7177e52c27584b9"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_i8<a id="ace99f086a3cd38c7477a8f038dae7ff4a976ddbecac99af6819d058790e33e137"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_i8pos<a id="ace99f086a3cd38c7477a8f038dae7ff4aab60d264e38d6e79c407317e0524fcce"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_i8neg<a id="ace99f086a3cd38c7477a8f038dae7ff4a8b4dc1a6ebdfa338bb66daa0dac9e6f5"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_so<a id="ace99f086a3cd38c7477a8f038dae7ff4af53086c6fc70088a1be00db2e4e3c928"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_pc<a id="ace99f086a3cd38c7477a8f038dae7ff4af9852c0cf1e5c1418ab8ac2b480e1190"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_i8s4<a id="ace99f086a3cd38c7477a8f038dae7ff4af3a6218c9c9bd03381633c799e5226d9"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrMode_i12<a id="ace99f086a3cd38c7477a8f038dae7ff4a44874e651b75b372574cc861fee08896"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrMode5FP16<a id="ace99f086a3cd38c7477a8f038dae7ff4a3747b57333522e1d11664379a2d9917a"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_ldrex<a id="ace99f086a3cd38c7477a8f038dae7ff4a8e8bd0fde548250887530336fa6ee2da"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_i7s4<a id="ace99f086a3cd38c7477a8f038dae7ff4aac7571d8c1b21260b02bd8b7d3bb637d"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_i7s2<a id="ace99f086a3cd38c7477a8f038dae7ff4a686f044e7ff2a5ff778e03d30e7acacb"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrModeT2_i7<a id="ace99f086a3cd38c7477a8f038dae7ff4a987c9c423c608a5f21f3a2c16bf9dff4"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a>.</p>

</div>
</div>

### IndexMode {#ac3c83a9ce4f6ef1a90d63ebe5722b2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMII::IndexMode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Index Modes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IndexModeNone<a id="ac3c83a9ce4f6ef1a90d63ebe5722b2b9a02d5ab304efd1b563cbe831bd5f7ba40"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IndexModePre<a id="ac3c83a9ce4f6ef1a90d63ebe5722b2b9abf29846376f4da85457ab5fbc9dfcc70"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IndexModePost<a id="ac3c83a9ce4f6ef1a90d63ebe5722b2b9ab9fd312a3c788e0bd21fc94e46cf5ab2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IndexModeUpd<a id="ac3c83a9ce4f6ef1a90d63ebe5722b2b9a8170f98efa38651a1ae5d7a27d0ae19c"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a>.</p>

</div>
</div>

### TOF {#ac33037e230d127af6de7945ce02e7e5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMII::TOF </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_NO_FLAG<a id="ac33037e230d127af6de7945ce02e7e5aac8d5b41e417b81d1460929338ac1466e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LO16<a id="ac33037e230d127af6de7945ce02e7e5aa2caa393204bf9261fbdca805199923a8"></a></td>
<td class="doxyEnumItemDescription">MO_LO16 - On a symbol operand, this represents a relocation containing lower 16 bit of the address (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_HI16<a id="ac33037e230d127af6de7945ce02e7e5aa7cbf61a60ec67440fb388b9373dc1148"></a></td>
<td class="doxyEnumItemDescription">MO_HI16 - On a symbol operand, this represents a relocation containing higher 16 bit of the address (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_OPTION_MASK<a id="ac33037e230d127af6de7945ce02e7e5aa0e45cd4ab4a729746f756f8d92e231b4"></a></td>
<td class="doxyEnumItemDescription">MO_OPTION_MASK - Most flags are mutually exclusive; this mask selects just that part of the flag set (= 0xf03)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_COFFSTUB<a id="ac33037e230d127af6de7945ce02e7e5aafbf06a19f49d98cf37ed7aed51b56f02"></a></td>
<td class="doxyEnumItemDescription">MO_COFFSTUB - On a symbol operand "FOO", this indicates that the reference is actually to the ".refptr.FOO" symbol (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT<a id="ac33037e230d127af6de7945ce02e7e5aaeea291fff7f2b259205744614e6662e4"></a></td>
<td class="doxyEnumItemDescription">MO_GOT - On a symbol operand, this represents a GOT relative relocation (= 0x8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_SBREL<a id="ac33037e230d127af6de7945ce02e7e5aa6e0069022b9ec2f92ca5b23c03fe4485"></a></td>
<td class="doxyEnumItemDescription">MO_SBREL - On a symbol operand, this represents a static base relative relocation (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DLLIMPORT<a id="ac33037e230d127af6de7945ce02e7e5aaa0968323e2f2cf5c8fdb022281f1342f"></a></td>
<td class="doxyEnumItemDescription">MO_DLLIMPORT - On a symbol operand, this represents that the reference to the symbol is for an import stub (= 0x20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_SECREL<a id="ac33037e230d127af6de7945ce02e7e5aabaa947d15677c50bad001c76a42f74b0"></a></td>
<td class="doxyEnumItemDescription">MO_SECREL - On a symbol operand this indicates that the immediate is the offset from beginning of section (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_NONLAZY<a id="ac33037e230d127af6de7945ce02e7e5aa423a53db845fec016f1d73e6d066481f"></a></td>
<td class="doxyEnumItemDescription">MO_NONLAZY - This is an independent flag, on a symbol operand "FOO" it represents a symbol which, if indirect, will get special Darwin mangling as a non-lazy-ptr indirect symbol (i.e (= 0x80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LO_0_7<a id="ac33037e230d127af6de7945ce02e7e5aa334b1addbb0ed4daecacf272c6015ce0"></a></td>
<td class="doxyEnumItemDescription">MO_LO_0_7 - On a symbol operand, this represents a relocation containing bits 0 through 7 of the address (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LO_8_15<a id="ac33037e230d127af6de7945ce02e7e5aa41164ff73c8cdecde5d7defd47f7a5e4"></a></td>
<td class="doxyEnumItemDescription">MO_LO_8_15 - On a symbol operand, this represents a relocation containing bits 8 through 15 of the address (= 0x200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_HI_0_7<a id="ac33037e230d127af6de7945ce02e7e5aadcdbb51d3e91fb2eaf39fabde37e36f7"></a></td>
<td class="doxyEnumItemDescription">MO_HI_0_7 - On a symbol operand, this represents a relocation containing bits 16 through 23 of the address (= 0x400)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_HI_8_15<a id="ac33037e230d127af6de7945ce02e7e5aa5ed8a37ef2b6b38554cd0f15f1d5f930"></a></td>
<td class="doxyEnumItemDescription">MO_HI_8_15 - On a symbol operand, this represents a relocation containing bits 24 through 31 of the address (= 0x800)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### AddrModeToString() {#a6ebee24b01a327206fea442c3a9ba32c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::ARMII::AddrModeToString (<a href="#ace99f086a3cd38c7477a8f038dae7ff4">AddrMode</a> addrmode)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a>.</p>


<p>References <a href="#ace99f086a3cd38c7477a8f038dae7ff4a9e413b3d35ed41939d4632ff7a855725">AddrMode1</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a7d9742a01ea175053d76a714474d88a6">AddrMode2</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a3e943d975799a4c55333c54eac1a7991">AddrMode3</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a9dbb177d004cae6c3474b6aadc8ae07e">AddrMode4</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a0209ae669364c237e24dbc0c4df6036e">AddrMode5</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a3747b57333522e1d11664379a2d9917a">AddrMode5FP16</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a8388bb748b26edbdb8bb5d5ab6f16853">AddrMode6</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a44874e651b75b372574cc861fee08896">AddrMode_i12</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a7231462a5c39f1e6f5277b897908683e">AddrModeNone</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4abfbcc124d3a4fa763e275b5b199fd81b">AddrModeT1_1</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a45c1a7867d7bed69326c02dca510e4cc">AddrModeT1_2</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a27e4e6aef06beef44d8cc58e32c22fdc">AddrModeT1_4</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a147ee44cd2b5425325839f5f0fa897ad">AddrModeT1_s</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a4f27c00983ba7efdb7177e52c27584b9">AddrModeT2_i12</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a987c9c423c608a5f21f3a2c16bf9dff4">AddrModeT2_i7</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a686f044e7ff2a5ff778e03d30e7acacb">AddrModeT2_i7s2</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4aac7571d8c1b21260b02bd8b7d3bb637d">AddrModeT2_i7s4</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a976ddbecac99af6819d058790e33e137">AddrModeT2_i8</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a8b4dc1a6ebdfa338bb66daa0dac9e6f5">AddrModeT2_i8neg</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4aab60d264e38d6e79c407317e0524fcce">AddrModeT2_i8pos</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4af3a6218c9c9bd03381633c799e5226d9">AddrModeT2_i8s4</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4a8e8bd0fde548250887530336fa6ee2da">AddrModeT2_ldrex</a>, <a href="#ace99f086a3cd38c7477a8f038dae7ff4af9852c0cf1e5c1418ab8ac2b480e1190">AddrModeT2_pc</a> and <a href="#ace99f086a3cd38c7477a8f038dae7ff4af53086c6fc70088a1be00db2e4e3c928">AddrModeT2_so</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">ARMBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
