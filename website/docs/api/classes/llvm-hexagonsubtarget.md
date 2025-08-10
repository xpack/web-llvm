---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonsubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HexagonSubtarget` Class



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">Target/Hexagon/HexagonSubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/hexagongensubtargetinfo">HexagonGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">HexagonProcFamilyEnum { <a href="#ac09549e5328f8d7fc7e94f2f6534f9eb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f194fc9ae635216053fb7435c6c90d6">HexagonSubtarget</a> (const Triple &amp;TT, StringRef CPU, StringRef FS, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4923bda28e40cedcaf2f3350c10f8cbf">getTargetTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae149928280a2de27fd012da2bf4f6bff">isEnvironmentMusl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04231da378b720f5baf6a00b9e5f7bea">getInstrItineraryData</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getInstrItins - Return the instruction itineraries based on subtarget selection. <a href="#a04231da378b720f5baf6a00b9e5f7bea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e692502cb75b1488e8b4047000ace6">getInstrInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ae6b411360f4516d2765ada63756ef">getRegisterInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering">HexagonTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c3b4dcf1147e2a5751c44f886bdc61">getTargetLowering</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering">HexagonFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c84076c19ef4da8c43ea3dc2850c382">getFrameLowering</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo">HexagonSelectionDAGInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83fd14b912d9840c6b08cc81f5f9d29">getSelectionDAGInfo</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget">HexagonSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a> (StringRef CPU, StringRef FS)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27bfd722814a82ed88683127e3ead1a">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options. <a href="#ab27bfd722814a82ed88683127e3ead1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f9ab5cfe7d9e86a258745a1d5d25dc">isXRaySupported</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc270801cd17a0ab1a7edadbf0cfd3b2">hasV5Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda7f16d5ff9558ab105e8388b67e0e6">hasV5OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b287c242508ffc7b35692e0c72ec44f">hasV55Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3526f6f9a216c3363df78797dac9bac1">hasV55OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab330d9a1d4b705737ae86e52903d09b1">hasV60Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea116a0b6893783c76a0f377843d92cf">hasV60OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ba32267969bff4e5b1e703f84e9675">hasV62Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f7033eb58ebf0cbe6012bc66280f10">hasV62OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61a073a966a5810f636cfc5df331b0d">hasV65Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a679e88a5d1eaefa6c4042839d57c89ea">hasV65OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa90c2f9f296885052ba54672934e9e">hasV66Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa40963557dec513d42a8906b23e8d7b2">hasV66OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ebedf2823aef6e5cc57518db091a298">hasV67Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa977e9a3c9d4b388fe942a34fa8d8ab7">hasV67OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4402a7b4f645cde406c8e6370f1d8668">hasV68Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12380bd4a6ffbca5f1aa0196aee2f52e">hasV68OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a1cab7d385f6812d44edceffe92bbb4">hasV69Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e2a65d72b6b763d69a57bf837e83ea">hasV69OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26d592c28f848dc3f466c565d47682a">hasV71Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a42c20a5b3d2c61afde353ea85d61b4">hasV71OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f7f7536cd58ff77b54497b76325f328">hasV73Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d8c5ded5ea6aab0182d3d29815d399">hasV73OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad10fb6a31302f1379b3901024a390c1c">hasV75Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a4f907b7c52cc681bddb0c885537a8">hasV75OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449d9d8c24a8cf419e2244f7dc0f535f">hasV79Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc85f0f9731bf5156cadc953427418d">hasV79OpsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789ed44d3831323b838377a863a3f1b2">useHVXV79Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f9b8aaadc4e2231bd6c7d64e602129d">useAudioOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae985bf28dbaab9f290ad3ac55584c563">useCompound</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f82fda8d0d6a2a78ea8b62ab810e559">useLongCalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12c8a98edc96da2bbf3db9f2cc069a7">useMemops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1121dcba5dd41ac9da579abeacb6164f">usePackets</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4f8c2a4561a351c35d77026726cedd">useNewValueJumps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d604322cbfb8bb0555b16ce5552f2f0">useNewValueStores</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d7460f115f8d49f96b1ed4a3b5b2ae">useSmallData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a14ccaf837849f5c76e7dccacb8ab4">useUnsafeMath</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c50d9de8e13f959e3db1ba331d4991a">useZRegOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c0cd84f445272a19a746e377692300">useCabac</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7177361294da2d18570223cd53ea1d73">isTinyCore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01fc2b3f6ef35df5b21d5767a1dcb431">isTinyCoreWithDuplex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc77d0bcb90eab8697d7db912ab43360">useHVXIEEEFPOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa04cc639c41e950cec23a7a21e37645e">useHVXQFloatOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b1869eba731ea30c0aa035d783c8b9">useHVXFloatingPoint</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f3ded462c921c93c8e72dea64d3dcc0">useHVXOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae71fdd407983ba148acaafe6a62f6fa7">useHVXV60Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d92ce10bb43e5416d67b95161c23582">useHVXV62Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb9589fcc8ff5b3324247deca5e4b3c">useHVXV65Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66bfc8c2bdf824190ee320dff7ede1e">useHVXV66Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a8f55a72245874c4babe736695eef9">useHVXV67Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab461254272bf62003e540ec997ab6795">useHVXV68Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf43b90b6f9a932bcafab27f6c9293f">useHVXV69Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c3496f281892d263a81bf41f025ba3">useHVXV71Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2e40f648c6665a7952436a76b7fa25">useHVXV73Ops</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45dc50ca02597d905c7ec255463c831">useHVX128BOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9af3793adb551553795f6838a2429f">useHVX64BOps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83394c53a62fca8bff6920261f711fd0">hasMemNoShuf</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a197d993764af990262e233650452e46d">hasReservedR19</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131532019288db2e0e660c37e88ea418">usePredicatedCalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fa62f0b1966e49bae7d95445603b9c1">noreturnStackElim</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72e804006fb285ff4da19a7eab85c37">useBSBScheduling</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b6fb1294d29cd20bcac717ef753694">enableMachineScheduler</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a1a9c12b156b837631305efe54a22a">enableMachineSchedDefaultSched</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">AntiDepBreakMode</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3663a77d60f4b331fe5cb4721a3135a">getAntiDepBreakMode</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb1ad3f15064ff9a8556c17b534b8fcd">enablePostRAScheduler</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run a scheduler after register allocation. <a href="#adb1ad3f15064ff9a8556c17b534b8fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876fb1471c55b3ed80077b2795be4561">enableSubRegLiveness</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea4e412c6e277fdc81cccf814c6fca4b">getCPUString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436">Hexagon::ArchEnum</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c62386550e4380dc9d9ddcabfa4207e">getPostRAMutations</a> (std::vector&lt; std::unique_ptr&lt; ScheduleDAGMutation &gt; &gt; &amp;Mutations) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36cabe7f24b39998bab7c36d439731f2">getSMSMutations</a> (std::vector&lt; std::unique_ptr&lt; ScheduleDAGMutation &gt; &gt; &amp;Mutations) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af94fdaeffe4b4d40fe328351f509e954">useAA</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable use of alias analysis during code generation (during MI scheduling, DAGCombine, etc.). <a href="#af94fdaeffe4b4d40fe328351f509e954">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101c3c30a65314c6f3fe10fbc1fa1539">adjustSchedDependency</a> (SUnit *Def, int DefOpIdx, SUnit *Use, int UseOpIdx, SDep &amp;Dep, const TargetSchedModel *SchedModel) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform target specific adjustments to the latency of a schedule dependency. <a href="#a101c3c30a65314c6f3fe10fbc1fa1539">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1e8dd04fa58d7f6ec1e166de2762012">getVectorLength</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f7589e84b9f713e9ec1a246e3233e7">getHVXElementTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae994bed1e8455738510f5d0d5906029b">isHVXElementType</a> (MVT Ty, bool IncludeBool=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40892ab1e0ab2dcb208fdedac55ebd2b">isHVXVectorType</a> (EVT VecTy, bool IncludeBool=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac04b69adb2b2657b80c8e86eb8e04099">isTypeForHVX</a> (Type *VecTy, bool IncludeBool=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9061e70c36dd5f85c5566b0d4ee40b67">getTypeAlignment</a> (MVT Ty) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2a029b207c1b8e6adae0324103e65b">getL1CacheLineSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72ab7e505379f677d0c955e547b65abc">getL1PrefetchDistance</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1eb4b5b3f31528f4b6fca7f19910e37">getIntrinsicId</a> (unsigned Opc) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac74eecdcdb128d7c7141403f2a949e91">anchor</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ce6c69fd71f3986bf4fe215d8ce8e9">updateLatency</a> (MachineInstr &amp;SrcInst, MachineInstr &amp;DstInst, bool IsArtificial, int Latency) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8cd34e04a2544ff1433cfb4448cd2ac">restoreLatency</a> (SUnit *Src, SUnit *Dst) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3623004d2b8264ebdeeb806e443732">changeLatency</a> (SUnit *Src, SUnit *Dst, unsigned Lat) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the latency between the two SUnits. <a href="#abc3623004d2b8264ebdeeb806e443732">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102a7c44edfd516cc0b10519c609bb79">isBestZeroLatency</a> (SUnit *Src, SUnit *Dst, const HexagonInstrInfo *TII, SmallSet&lt; SUnit *, 4 &gt; &amp;ExclSrc, SmallSet&lt; SUnit *, 4 &gt; &amp;ExclDst) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436">Hexagon::ArchEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067325d8c2e5fca1acc31de2a7074fde">HexagonArchVersion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436">Hexagon::ArchEnum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> = <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a31ca3cae0b846c9a58d52c656d28b5e0">Hexagon::ArchEnum::NoArch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a449c0a0b2fed37ce27a74867d7bad">OptLevel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ecae06c10fab8169b03e2a74476b909">UseBSBScheduling</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the target should use Back-Skip-Back scheduling. <a href="#a6ecae06c10fab8169b03e2a74476b909">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3759d78ae6ccba291288657b6b2ee22">UseHVX64BOps</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c7a2df14621a0757aeebdbbe7bedbd">UseHVX128BOps</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a366c106297a9cbe9a95cf51fdf6f74ab">UseAudioOps</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf5f1c5d90ced3448b578bff544ff9c1">UseCompound</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf220a16c4bbe7988276d249036039f0">UseLongCalls</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f80b1d42cc8c92fddb09f0d7346aefc">UseMemops</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bea9cd5b3b43c696cd3efe7a9cdd707">UsePackets</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58feeeda10fbc6ef1d960a3cb115f68">UseNewValueJumps</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e6cd646b3050f646a2722796d3dc82c">UseNewValueStores</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade6a5cc32dd2e1dfad12db1508053799">UseSmallData</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4997a606d886e6eed6b5b367561365b9">UseUnsafeMath</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d68294aaf034dc59aee230c929cf83">UseZRegOps</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ac981429e51915a5162fc8ef02a7d8">UseHVXIEEEFPOps</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c703f9734d50a81bbee6539d0940b40">UseHVXQFloatOps</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8372e01e20894021cdd76a5e41b68759">UseHVXFloatingPoint</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3dc1ed2575f01759ca1eaa3cc16441a">UseCabac</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7471bcc95585608cb01001b104d67d03">HasPreV65</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5110011594c3de279a8734e0de28785">HasMemNoShuf</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a801999547d6eb50e32c81034a0c87f04">EnableDuplex</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae098ce44f130769abbaafa657a193ee9">ReservedR19</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a419f8edc308b2852223c24641f17f4af">NoreturnStackElim</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f736a4a9eeb8a364f99605a7651b64c">CPUString</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">HexagonProcFamilyEnum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a372768649f7b9986101c1457b8986235">HexagonProcFamily</a> = Others</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1854e0d51d7c101b274173c410d2bf24">TargetTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdef3ffc401cc62a4629d50c11ad769b">InstrInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e994ca60480d99ebd2feb2b364ce5a">RegInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering">HexagonTargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07828117299f13c7bdad3e1e6386697a">TLInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo">HexagonSelectionDAGInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5681a5036cda4fc91753e2e04d58fc59">TSInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering">HexagonFrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad112f847ca36884cfaee03010f976adf">FrameLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6e15d00d1653b58efae32ea31137f9">InstrItins</a></td>
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


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### HexagonProcFamilyEnum {#ac09549e5328f8d7fc7e94f2f6534f9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::HexagonSubtarget::HexagonProcFamilyEnum </td>
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
<td class="doxyEnumItemName">Others<a id="ac09549e5328f8d7fc7e94f2f6534f9ebac5f8197a34deb0ca3b60b7cebaf6db20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TinyCore<a id="ac09549e5328f8d7fc7e94f2f6534f9ebaa57738290a17d88b926e56845b52b17c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HexagonSubtarget() {#a3f194fc9ae635216053fb7435c6c90d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonSubtarget::HexagonSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#ab3006e90ba5c4717808c3c35e1a778a5">llvm::Hexagon_MC::addArchSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a> and <a href="#aa1a449c0a0b2fed37ce27a74867d7bad">OptLevel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/callmutation/#a6cd9122ce8216f80dd0921f844f7b7e1">llvm::HexagonSubtarget::CallMutation::apply</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustSchedDependency() {#a101c3c30a65314c6f3fe10fbc1fa1539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonSubtarget::adjustSchedDependency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Def, int DefOpIdx, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Use, int UseOpIdx, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Dep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SchedModel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform target specific adjustments to the latency of a schedule dependency.</p>

<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4ab4c0bfcb70883e983a325153b5a44e">llvm::HexagonInstrInfo::canExecuteInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a76b3fc7c102561fb5210d5151531e409">llvm::SmallSet&lt; T, N, C &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp/#a05ab02fcc996e2b95a0c3e9421146a15">EnableDotCurSched</a>, <a href="#a21e692502cb75b1488e8b4047000ace6">getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a5eca2019521fd47b79fe5ef66d02fd43">llvm::SDep::getLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a75b245e9ae0e3d67d8485468580f360f">llvm::SDep::isArtificial</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1912d4fbc40c61a12b1f770ad54dfd74">llvm::MachineInstr::isCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8d97d09150ddcbcf5039f938111358ee">llvm::MachineInstr::isRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4475ef8d36797ed68e422e259b7b4cf">llvm::HexagonInstrInfo::isToBeScheduledASAP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a> and <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a>.</p>

</div>
</div>

### enableMachineSchedDefaultSched() {#a20a1a9c12b156b837631305efe54a22a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::enableMachineSchedDefaultSched ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### enableMachineScheduler() {#ac8b6fb1294d29cd20bcac717ef753694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonSubtarget::enableMachineScheduler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp/#a0219695421888f7100677aa949ac5bc1">DisableHexagonMISched</a>.</p>

</div>
</div>

### enablePostRAScheduler() {#adb1ad3f15064ff9a8556c17b534b8fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::enablePostRAScheduler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the subtarget should run a scheduler after register allocation.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### enableSubRegLiveness() {#a876fb1471c55b3ed80077b2795be4561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonSubtarget::enableSubRegLiveness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### getAntiDepBreakMode() {#aa3663a77d60f4b331fe5cb4721a3135a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AntiDepBreakMode llvm::HexagonSubtarget::getAntiDepBreakMode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### getCPUString() {#aea4e412c6e277fdc81cccf814c6fca4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::HexagonSubtarget::getCPUString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### getFrameLowering() {#a2c84076c19ef4da8c43ea3dc2850c382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonFrameLowering * llvm::HexagonSubtarget::getFrameLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a9c2ee381172db4d044e61d3438031d6b">llvm::HexagonDAGToDAGISel::emitFunctionEntryCode</a>.</p>

</div>
</div>

### getHexagonArchVersion() {#a3620461f348db5265fc4b3b602f497d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Hexagon::ArchEnum &amp; llvm::HexagonSubtarget::getHexagonArchVersion ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Reference <a href="#a067325d8c2e5fca1acc31de2a7074fde">HexagonArchVersion</a>.</p>


<p>Referenced by <a href="#a7b287c242508ffc7b35692e0c72ec44f">hasV55Ops</a>, <a href="#a3526f6f9a216c3363df78797dac9bac1">hasV55OpsOnly</a>, <a href="#abc270801cd17a0ab1a7edadbf0cfd3b2">hasV5Ops</a>, <a href="#afda7f16d5ff9558ab105e8388b67e0e6">hasV5OpsOnly</a>, <a href="#ab330d9a1d4b705737ae86e52903d09b1">hasV60Ops</a>, <a href="#aea116a0b6893783c76a0f377843d92cf">hasV60OpsOnly</a>, <a href="#ad6ba32267969bff4e5b1e703f84e9675">hasV62Ops</a>, <a href="#a75f7033eb58ebf0cbe6012bc66280f10">hasV62OpsOnly</a>, <a href="#ad61a073a966a5810f636cfc5df331b0d">hasV65Ops</a>, <a href="#a679e88a5d1eaefa6c4042839d57c89ea">hasV65OpsOnly</a>, <a href="#a4aa90c2f9f296885052ba54672934e9e">hasV66Ops</a>, <a href="#aa40963557dec513d42a8906b23e8d7b2">hasV66OpsOnly</a>, <a href="#a6ebedf2823aef6e5cc57518db091a298">hasV67Ops</a>, <a href="#aa977e9a3c9d4b388fe942a34fa8d8ab7">hasV67OpsOnly</a>, <a href="#a4402a7b4f645cde406c8e6370f1d8668">hasV68Ops</a>, <a href="#a12380bd4a6ffbca5f1aa0196aee2f52e">hasV68OpsOnly</a>, <a href="#a8a1cab7d385f6812d44edceffe92bbb4">hasV69Ops</a>, <a href="#ab2e2a65d72b6b763d69a57bf837e83ea">hasV69OpsOnly</a>, <a href="#ad26d592c28f848dc3f466c565d47682a">hasV71Ops</a>, <a href="#a9a42c20a5b3d2c61afde353ea85d61b4">hasV71OpsOnly</a>, <a href="#a8f7f7536cd58ff77b54497b76325f328">hasV73Ops</a>, <a href="#a87d8c5ded5ea6aab0182d3d29815d399">hasV73OpsOnly</a>, <a href="#ad10fb6a31302f1379b3901024a390c1c">hasV75Ops</a>, <a href="#a63a4f907b7c52cc681bddb0c885537a8">hasV75OpsOnly</a>, <a href="#a449d9d8c24a8cf419e2244f7dc0f535f">hasV79Ops</a> and <a href="#a2bc85f0f9731bf5156cadc953427418d">hasV79OpsOnly</a>.</p>

</div>
</div>

### getHVXElementTypes() {#a73f7589e84b9f713e9ec1a246e3233e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MVT &gt; llvm::HexagonSubtarget::getHVXElementTypes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#a74b1869eba731ea30c0aa035d783c8b9">useHVXFloatingPoint</a> and <a href="#ab461254272bf62003e540ec997ab6795">useHVXV68Ops</a>.</p>


<p>Referenced by <a href="#ae994bed1e8455738510f5d0d5906029b">isHVXElementType</a> and <a href="#a40892ab1e0ab2dcb208fdedac55ebd2b">isHVXVectorType</a>.</p>

</div>
</div>

### getInstrInfo() {#a21e692502cb75b1488e8b4047000ace6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonInstrInfo * llvm::HexagonSubtarget::getInstrInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#a101c3c30a65314c6f3fe10fbc1fa1539">adjustSchedDependency</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/callmutation/#a6cd9122ce8216f80dd0921f844f7b7e1">llvm::HexagonSubtarget::CallMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0bd4071843f49d48f53401da3603c0e9">llvm::HexagonPacketizerList::HexagonPacketizerList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonlooprescheduling/#a3289c50be003939c64bcb6f7f4d92887">anonymous{HexagonBitSimplify.cpp}::HexagonLoopRescheduling::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbranchrelaxation-cpp-/hexagonbranchrelaxation/#a2b6209babcc2f74c534636c926aff40f">anonymous{HexagonBranchRelaxation.cpp}::HexagonBranchRelaxation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonhardwareloops-cpp-/hexagonhardwareloops/#a227e7ddfafd6bce13cfb1473136e8230">anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#a496cd4b644f69f478410a8ceb1f187aa">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagontfrcleanup-cpp-/hexagontfrcleanup/#aa7619322b2d38567f6b30b0bc454a28e">anonymous{HexagonTfrCleanup.cpp}::HexagonTfrCleanup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvliwpacketizer-cpp-/hexagonpacketizer/#a84914fb49b671ec22a8cb348237182c7">anonymous{HexagonVLIWPacketizer.cpp}::HexagonPacketizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a7f154b7960df132b1db218bad3216197">llvm::HexagonDAGToDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmask/#aa03b20a7ba7848884bffbac603f06871">llvm::HexagonMask::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonconvergingvliwscheduler/#a5b1da83188ad8ac357edfd719ce2680f">llvm::HexagonConvergingVLIWScheduler::SchedulingCost</a>.</p>

</div>
</div>

### getInstrItineraryData() {#a04231da378b720f5baf6a00b9e5f7bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData * llvm::HexagonSubtarget::getInstrItineraryData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getInstrItins - Return the instruction itineraries based on subtarget selection.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### getIntrinsicId() {#ac1eb4b5b3f31528f4b6fca7f19910e37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID HexagonSubtarget::getIntrinsicId (unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#aa1e8dd04fa58d7f6ec1e166de2762012">getVectorLength</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### getL1CacheLineSize() {#abe2a029b207c1b8e6adae0324103e65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HexagonSubtarget::getL1CacheLineSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### getL1PrefetchDistance() {#a72ab7e505379f677d0c955e547b65abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HexagonSubtarget::getL1PrefetchDistance ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### getPostRAMutations() {#a4c62386550e4380dc9d9ddcabfa4207e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonSubtarget::getPostRAMutations (std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> &gt; &gt; &amp; Mutations)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### getRegisterInfo() {#a33ae6b411360f4516d2765ada63756ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonRegisterInfo * llvm::HexagonSubtarget::getRegisterInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0bd4071843f49d48f53401da3603c0e9">llvm::HexagonPacketizerList::HexagonPacketizerList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a4a8e77e619417aa3e56a24caf68d6820">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopytocombine-cpp-/hexagoncopytocombine/#a9c768afdfbc0a2c828dfe51e2d05e662">anonymous{HexagonCopyToCombine.cpp}::HexagonCopyToCombine::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonhardwareloops-cpp-/hexagonhardwareloops/#a227e7ddfafd6bce13cfb1473136e8230">anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorprint-cpp-/hexagonvectorprint/#a0da76ecb9da0a3d09d047a3a4ed0863d">anonymous{HexagonVectorPrint.cpp}::HexagonVectorPrint::runOnMachineFunction</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#ac83fd14b912d9840c6b08cc81f5f9d29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonSelectionDAGInfo * llvm::HexagonSubtarget::getSelectionDAGInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### getSMSMutations() {#a36cabe7f24b39998bab7c36d439731f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonSubtarget::getSMSMutations (std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> &gt; &gt; &amp; Mutations)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### getTargetLowering() {#a54c3b4dcf1147e2a5751c44f886bdc61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonTargetLowering * llvm::HexagonSubtarget::getTargetLowering ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac04b69adb2b2657b80c8e86eb8e04099">isTypeForHVX</a>.</p>

</div>
</div>

### getTargetTriple() {#a4923bda28e40cedcaf2f3350c10f8cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::HexagonSubtarget::getTargetTriple ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### getTypeAlignment() {#a9061e70c36dd5f85c5566b0d4ee40b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::HexagonSubtarget::getTypeAlignment (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#aa1e8dd04fa58d7f6ec1e166de2762012">getVectorLength</a> and <a href="#a40892ab1e0ab2dcb208fdedac55ebd2b">isHVXVectorType</a>.</p>

</div>
</div>

### getVectorLength() {#aa1e8dd04fa58d7f6ec1e166de2762012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::HexagonSubtarget::getVectorLength ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#aa45dc50ca02597d905c7ec255463c831">useHVX128BOps</a>, <a href="#add9af3793adb551553795f6838a2429f">useHVX64BOps</a> and <a href="#a9f3ded462c921c93c8e72dea64d3dcc0">useHVXOps</a>.</p>


<p>Referenced by <a href="#ac1eb4b5b3f31528f4b6fca7f19910e37">getIntrinsicId</a>, <a href="#a9061e70c36dd5f85c5566b0d4ee40b67">getTypeAlignment</a> and <a href="#a40892ab1e0ab2dcb208fdedac55ebd2b">isHVXVectorType</a>.</p>

</div>
</div>

### hasMemNoShuf() {#a83394c53a62fca8bff6920261f711fd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasMemNoShuf ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### hasReservedR19() {#a197d993764af990262e233650452e46d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasReservedR19 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a3372d351ec7fac9fb1066e77d36f1276">llvm::HexagonRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### hasV55Ops() {#a7b287c242508ffc7b35692e0c72ec44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV55Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a7e2f25174ce09de028190095cc693a5e">llvm::Hexagon::V55</a>.</p>

</div>
</div>

### hasV55OpsOnly() {#a3526f6f9a216c3363df78797dac9bac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV55OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a7e2f25174ce09de028190095cc693a5e">llvm::Hexagon::V55</a>.</p>

</div>
</div>

### hasV5Ops() {#abc270801cd17a0ab1a7edadbf0cfd3b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV5Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8cff5423006469332e8ae5e3a8c8559c">llvm::Hexagon::V5</a>.</p>

</div>
</div>

### hasV5OpsOnly() {#afda7f16d5ff9558ab105e8388b67e0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV5OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8cff5423006469332e8ae5e3a8c8559c">llvm::Hexagon::V5</a>.</p>

</div>
</div>

### hasV60Ops() {#ab330d9a1d4b705737ae86e52903d09b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV60Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8336608773c499fd7e37000fac2f9cfd">llvm::Hexagon::V60</a>.</p>


<p>Referenced by <a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### hasV60OpsOnly() {#aea116a0b6893783c76a0f377843d92cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV60OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8336608773c499fd7e37000fac2f9cfd">llvm::Hexagon::V60</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a006a3e1788b7d4a381385cd00ed19508">cannotCoexistAsymm</a>.</p>

</div>
</div>

### hasV62Ops() {#ad6ba32267969bff4e5b1e703f84e9675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV62Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a113b0d77002193057e4a99b66ceb8264">llvm::Hexagon::V62</a>.</p>

</div>
</div>

### hasV62OpsOnly() {#a75f7033eb58ebf0cbe6012bc66280f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV62OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a113b0d77002193057e4a99b66ceb8264">llvm::Hexagon::V62</a>.</p>

</div>
</div>

### hasV65Ops() {#ad61a073a966a5810f636cfc5df331b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV65Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436aa7903c0ef33fd8000b9fded2bd20f6cb">llvm::Hexagon::V65</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### hasV65OpsOnly() {#a679e88a5d1eaefa6c4042839d57c89ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV65OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436aa7903c0ef33fd8000b9fded2bd20f6cb">llvm::Hexagon::V65</a>.</p>

</div>
</div>

### hasV66Ops() {#a4aa90c2f9f296885052ba54672934e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV66Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a2267b8c0f3b8c12c5bbbf66978544a0d">llvm::Hexagon::V66</a>.</p>

</div>
</div>

### hasV66OpsOnly() {#aa40963557dec513d42a8906b23e8d7b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV66OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a2267b8c0f3b8c12c5bbbf66978544a0d">llvm::Hexagon::V66</a>.</p>

</div>
</div>

### hasV67Ops() {#a6ebedf2823aef6e5cc57518db091a298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV67Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a0db1fd5100de9dcbc5f2949df2a2dbf7">llvm::Hexagon::V67</a>.</p>

</div>
</div>

### hasV67OpsOnly() {#aa977e9a3c9d4b388fe942a34fa8d8ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV67OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a0db1fd5100de9dcbc5f2949df2a2dbf7">llvm::Hexagon::V67</a>.</p>

</div>
</div>

### hasV68Ops() {#a4402a7b4f645cde406c8e6370f1d8668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV68Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a52cd6998d793235c390b570fba7d206c">llvm::Hexagon::V68</a>.</p>


<p>Referenced by <a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### hasV68OpsOnly() {#a12380bd4a6ffbca5f1aa0196aee2f52e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV68OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a52cd6998d793235c390b570fba7d206c">llvm::Hexagon::V68</a>.</p>

</div>
</div>

### hasV69Ops() {#a8a1cab7d385f6812d44edceffe92bbb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV69Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a08c198530a951b0d1adc8c0f38967bb1">llvm::Hexagon::V69</a>.</p>

</div>
</div>

### hasV69OpsOnly() {#ab2e2a65d72b6b763d69a57bf837e83ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV69OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a08c198530a951b0d1adc8c0f38967bb1">llvm::Hexagon::V69</a>.</p>

</div>
</div>

### hasV71Ops() {#ad26d592c28f848dc3f466c565d47682a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV71Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a21f8c41b215c6879bfc46b10e506d2d4">llvm::Hexagon::V71</a>.</p>

</div>
</div>

### hasV71OpsOnly() {#a9a42c20a5b3d2c61afde353ea85d61b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV71OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a21f8c41b215c6879bfc46b10e506d2d4">llvm::Hexagon::V71</a>.</p>

</div>
</div>

### hasV73Ops() {#a8f7f7536cd58ff77b54497b76325f328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV73Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a4084fbfbf7c3d3e99fcda5f126a1e494">llvm::Hexagon::V73</a>.</p>

</div>
</div>

### hasV73OpsOnly() {#a87d8c5ded5ea6aab0182d3d29815d399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV73OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a4084fbfbf7c3d3e99fcda5f126a1e494">llvm::Hexagon::V73</a>.</p>

</div>
</div>

### hasV75Ops() {#ad10fb6a31302f1379b3901024a390c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV75Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436ab1cab2dc211faa7bcebb331fd40454fb">llvm::Hexagon::V75</a>.</p>

</div>
</div>

### hasV75OpsOnly() {#a63a4f907b7c52cc681bddb0c885537a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV75OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436ab1cab2dc211faa7bcebb331fd40454fb">llvm::Hexagon::V75</a>.</p>

</div>
</div>

### hasV79Ops() {#a449d9d8c24a8cf419e2244f7dc0f535f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV79Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a98a8f93c2a6e174b45fc01e59ccf8ffe">llvm::Hexagon::V79</a>.</p>

</div>
</div>

### hasV79OpsOnly() {#a2bc85f0f9731bf5156cadc953427418d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::hasV79OpsOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a98a8f93c2a6e174b45fc01e59ccf8ffe">llvm::Hexagon::V79</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#ac33e274ca277cfe840f699acc1b8a814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonSubtarget &amp; HexagonSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#af579a881fa0a6fe785ecf91fcc9ccaaa">llvm::SubtargetFeatures::AddFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#aee59f67f23fccbef39abc4ecd6092d54">llvm::Hexagon_MC::completeHVXFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp/#a8ebd1fe367feb3f63e30b4181e0d11cb">EnableBSBSched</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#afd5440e15db345bf9daf9a8961192663">llvm::Hexagon::getCpu</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a39a9e8ebdc3fdfb710357fdb5e724abe">llvm::SubtargetFeatures::getFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#aaa9679917091c7e93f866894599f923e">llvm::SubtargetFeatures::getString</a>, <a href="#ab330d9a1d4b705737ae86e52903d09b1">hasV60Ops</a>, <a href="#a4402a7b4f645cde406c8e6370f1d8668">hasV68Ops</a>, <a href="#a067325d8c2e5fca1acc31de2a7074fde">HexagonArchVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae67719f41ce92d645a687f546ccffccc">llvm::HexagonDisableDuplex</a>, <a href="#a7177361294da2d18570223cd53ea1d73">isTinyCore</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp/#a1e40da697ab45e776c8d2a13dfc78809">OverrideLongCalls</a>, <a href="#ab27bfd722814a82ed88683127e3ead1a">ParseSubtargetFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a20907c2cbc50e3cad93df4c7e49e2b3b">llvm::FeatureBitset::reset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="#a6ecae06c10fab8169b03e2a74476b909">UseBSBScheduling</a> and <a href="#ab461254272bf62003e540ec997ab6795">useHVXV68Ops</a>.</p>


<p>Referenced by <a href="#a3f194fc9ae635216053fb7435c6c90d6">HexagonSubtarget</a>.</p>

</div>
</div>

### isEnvironmentMusl() {#ae149928280a2de27fd012da2bf4f6bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::isEnvironmentMusl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a332336ad935952ff734309ce432de6d1">llvm::Triple::Musl</a>.</p>

</div>
</div>

### isHVXElementType() {#ae994bed1e8455738510f5d0d5906029b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonSubtarget::isHVXElementType (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> Ty, bool IncludeBool=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="#a73f7589e84b9f713e9ec1a246e3233e7">getHVXElementTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="#a9f3ded462c921c93c8e72dea64d3dcc0">useHVXOps</a>.</p>

</div>
</div>

### isHVXVectorType() {#a40892ab1e0ab2dcb208fdedac55ebd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonSubtarget::isHVXVectorType (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VecTy, bool IncludeBool=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="#a73f7589e84b9f713e9ec1a246e3233e7">getHVXElementTypes</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ad3ff408f213bef998f49952c6c3711fb">llvm::MVT::getVectorElementType</a>, <a href="#aa1e8dd04fa58d7f6ec1e166de2762012">getVectorLength</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab8967b7214f38cdea9c0158dbe2ffa31">llvm::EVT::isScalableVector</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a9f3ded462c921c93c8e72dea64d3dcc0">useHVXOps</a>.</p>


<p>Referenced by <a href="#a9061e70c36dd5f85c5566b0d4ee40b67">getTypeAlignment</a> and <a href="#ac04b69adb2b2657b80c8e86eb8e04099">isTypeForHVX</a>.</p>

</div>
</div>

### isTinyCore() {#a7177361294da2d18570223cd53ea1d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::isTinyCore ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a> and <a href="#a01fc2b3f6ef35df5b21d5767a1dcb431">isTinyCoreWithDuplex</a>.</p>

</div>
</div>

### isTinyCoreWithDuplex() {#a01fc2b3f6ef35df5b21d5767a1dcb431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::isTinyCoreWithDuplex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Reference <a href="#a7177361294da2d18570223cd53ea1d73">isTinyCore</a>.</p>

</div>
</div>

### isTypeForHVX() {#ac04b69adb2b2657b80c8e86eb8e04099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonSubtarget::isTypeForHVX (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * VecTy, bool IncludeBool=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ae3fa2c1ecfbe3c0d2ac014720ad520a0">llvm::HexagonTargetLowering::getPreferredVectorAction</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="#a54c3b4dcf1147e2a5751c44f886bdc61">getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="#a40892ab1e0ab2dcb208fdedac55ebd2b">isHVXVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#adde2b3c4de4c4ded2b80ff32f1020b9b">llvm::MVT::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a5290057031a9bc71850f61e757cb940e">llvm::TargetLoweringBase::TypeWidenVector</a> and <a href="#a74b1869eba731ea30c0aa035d783c8b9">useHVXFloatingPoint</a>.</p>

</div>
</div>

### isXRaySupported() {#af6f9ab5cfe7d9e86a258745a1d5d25dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::isXRaySupported ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### noreturnStackElim() {#a3fa62f0b1966e49bae7d95445603b9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::noreturnStackElim ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#ab27bfd722814a82ed88683127e3ead1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseSubtargetFeatures - Parses features string setting specified subtarget options.</p>


<p>Definition of function is auto generated by tblgen.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### useAA() {#af94fdaeffe4b4d40fe328351f509e954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonSubtarget::useAA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable use of alias analysis during code generation (during MI scheduling, DAGCombine, etc.).</p>

<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="#aa1a449c0a0b2fed37ce27a74867d7bad">OptLevel</a>.</p>

</div>
</div>

### useAudioOps() {#a1f9b8aaadc4e2231bd6c7d64e602129d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useAudioOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### useBSBScheduling() {#ae72e804006fb285ff4da19a7eab85c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useBSBScheduling ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Reference <a href="#a6ecae06c10fab8169b03e2a74476b909">UseBSBScheduling</a>.</p>

</div>
</div>

### useCabac() {#a30c0cd84f445272a19a746e377692300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useCabac ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### useCompound() {#ae985bf28dbaab9f290ad3ac55584c563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useCompound ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### useHVX128BOps() {#aa45dc50ca02597d905c7ec255463c831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVX128BOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Reference <a href="#a9f3ded462c921c93c8e72dea64d3dcc0">useHVXOps</a>.</p>


<p>Referenced by <a href="#aa1e8dd04fa58d7f6ec1e166de2762012">getVectorLength</a>.</p>

</div>
</div>

### useHVX64BOps() {#add9af3793adb551553795f6838a2429f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVX64BOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Reference <a href="#a9f3ded462c921c93c8e72dea64d3dcc0">useHVXOps</a>.</p>


<p>Referenced by <a href="#aa1e8dd04fa58d7f6ec1e166de2762012">getVectorLength</a>.</p>

</div>
</div>

### useHVXFloatingPoint() {#a74b1869eba731ea30c0aa035d783c8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXFloatingPoint ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#a73f7589e84b9f713e9ec1a246e3233e7">getHVXElementTypes</a> and <a href="#ac04b69adb2b2657b80c8e86eb8e04099">isTypeForHVX</a>.</p>

</div>
</div>

### useHVXIEEEFPOps() {#abc77d0bcb90eab8697d7db912ab43360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXIEEEFPOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Reference <a href="#a9f3ded462c921c93c8e72dea64d3dcc0">useHVXOps</a>.</p>

</div>
</div>

### useHVXOps() {#a9f3ded462c921c93c8e72dea64d3dcc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a31ca3cae0b846c9a58d52c656d28b5e0">llvm::Hexagon::NoArch</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ae400dd9b7f2e7a80439b14ccec7353d6">llvm::HexagonTargetLowering::CanLowerReturn</a>, <a href="#aa1e8dd04fa58d7f6ec1e166de2762012">getVectorLength</a>, <a href="#ae994bed1e8455738510f5d0d5906029b">isHVXElementType</a>, <a href="#a40892ab1e0ab2dcb208fdedac55ebd2b">isHVXVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8a7cb54f8347286b106be184c8c125e1">llvm::HexagonRegisterInfo::shouldCoalesce</a>, <a href="#aa45dc50ca02597d905c7ec255463c831">useHVX128BOps</a>, <a href="#add9af3793adb551553795f6838a2429f">useHVX64BOps</a> and <a href="#abc77d0bcb90eab8697d7db912ab43360">useHVXIEEEFPOps</a>.</p>

</div>
</div>

### useHVXQFloatOps() {#aa04cc639c41e950cec23a7a21e37645e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXQFloatOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a52cd6998d793235c390b570fba7d206c">llvm::Hexagon::V68</a>.</p>

</div>
</div>

### useHVXV60Ops() {#ae71fdd407983ba148acaafe6a62f6fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV60Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a8336608773c499fd7e37000fac2f9cfd">llvm::Hexagon::V60</a>.</p>

</div>
</div>

### useHVXV62Ops() {#a4d92ce10bb43e5416d67b95161c23582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV62Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a113b0d77002193057e4a99b66ceb8264">llvm::Hexagon::V62</a>.</p>

</div>
</div>

### useHVXV65Ops() {#acfb9589fcc8ff5b3324247deca5e4b3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV65Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436aa7903c0ef33fd8000b9fded2bd20f6cb">llvm::Hexagon::V65</a>.</p>

</div>
</div>

### useHVXV66Ops() {#ab66bfc8c2bdf824190ee320dff7ede1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV66Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a2267b8c0f3b8c12c5bbbf66978544a0d">llvm::Hexagon::V66</a>.</p>

</div>
</div>

### useHVXV67Ops() {#a10a8f55a72245874c4babe736695eef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV67Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a0db1fd5100de9dcbc5f2949df2a2dbf7">llvm::Hexagon::V67</a>.</p>

</div>
</div>

### useHVXV68Ops() {#ab461254272bf62003e540ec997ab6795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV68Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a52cd6998d793235c390b570fba7d206c">llvm::Hexagon::V68</a>.</p>


<p>Referenced by <a href="#a73f7589e84b9f713e9ec1a246e3233e7">getHVXElementTypes</a> and <a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### useHVXV69Ops() {#a7cf43b90b6f9a932bcafab27f6c9293f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV69Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a08c198530a951b0d1adc8c0f38967bb1">llvm::Hexagon::V69</a>.</p>

</div>
</div>

### useHVXV71Ops() {#a91c3496f281892d263a81bf41f025ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV71Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a21f8c41b215c6879bfc46b10e506d2d4">llvm::Hexagon::V71</a>.</p>

</div>
</div>

### useHVXV73Ops() {#abe2e40f648c6665a7952436a76b7fa25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV73Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a4084fbfbf7c3d3e99fcda5f126a1e494">llvm::Hexagon::V73</a>.</p>

</div>
</div>

### useHVXV79Ops() {#a789ed44d3831323b838377a863a3f1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useHVXV79Ops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>References <a href="#a2f543c2a442b130d745fcbf7f090067a">HexagonHVXVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a98a8f93c2a6e174b45fc01e59ccf8ffe">llvm::Hexagon::V79</a>.</p>

</div>
</div>

### useLongCalls() {#a1f82fda8d0d6a2a78ea8b62ab810e559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useLongCalls ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### useMemops() {#af12c8a98edc96da2bbf3db9f2cc069a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useMemops ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### useNewValueJumps() {#a9d4f8c2a4561a351c35d77026726cedd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useNewValueJumps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>.</p>

</div>
</div>

### useNewValueStores() {#a6d604322cbfb8bb0555b16ce5552f2f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useNewValueStores ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### usePackets() {#a1121dcba5dd41ac9da579abeacb6164f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::usePackets ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### usePredicatedCalls() {#a131532019288db2e0e660c37e88ea418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonSubtarget::usePredicatedCalls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp/#ac69f757ff0273e66d33662bce2148032">EnablePredicatedCalls</a>.</p>

</div>
</div>

### useSmallData() {#a31d7460f115f8d49f96b1ed4a3b5b2ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useSmallData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### useUnsafeMath() {#a06a14ccaf837849f5c76e7dccacb8ab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useUnsafeMath ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### useZRegOps() {#a9c50d9de8e13f959e3db1ba331d4991a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::useZRegOps ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#ac74eecdcdb128d7c7141403f2a949e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonSubtarget::anchor ()</td>
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



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### changeLatency() {#abc3623004d2b8264ebdeeb806e443732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonSubtarget::changeLatency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Dst, unsigned Lat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the latency between the two SUnits.</p>

<p>Declaration at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### isBestZeroLatency() {#a102a7c44edfd516cc0b10519c609bb79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonSubtarget::isBestZeroLatency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Dst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> * TII, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 4 &gt; &amp; ExclSrc, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 4 &gt; &amp; ExclDst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### restoreLatency() {#ad8cd34e04a2544ff1433cfb4448cd2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonSubtarget::restoreLatency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

### updateLatency() {#ab0ce6c69fd71f3986bf4fe215d8ce8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int HexagonSubtarget::updateLatency (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; SrcInst, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DstInst, bool IsArtificial, int Latency)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### HexagonArchVersion {#a067325d8c2e5fca1acc31de2a7074fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hexagon::ArchEnum llvm::HexagonSubtarget::HexagonArchVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#a3620461f348db5265fc4b3b602f497d1">getHexagonArchVersion</a> and <a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a>.</p>

</div>
</div>

### HexagonHVXVersion {#a2f543c2a442b130d745fcbf7f090067a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Hexagon::ArchEnum llvm::HexagonSubtarget::HexagonHVXVersion = <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#ac51913459c748e1d7176ab02946c4436a31ca3cae0b846c9a58d52c656d28b5e0">Hexagon::ArchEnum::NoArch</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#a9f3ded462c921c93c8e72dea64d3dcc0">useHVXOps</a>, <a href="#aa04cc639c41e950cec23a7a21e37645e">useHVXQFloatOps</a>, <a href="#ae71fdd407983ba148acaafe6a62f6fa7">useHVXV60Ops</a>, <a href="#a4d92ce10bb43e5416d67b95161c23582">useHVXV62Ops</a>, <a href="#acfb9589fcc8ff5b3324247deca5e4b3c">useHVXV65Ops</a>, <a href="#ab66bfc8c2bdf824190ee320dff7ede1e">useHVXV66Ops</a>, <a href="#a10a8f55a72245874c4babe736695eef9">useHVXV67Ops</a>, <a href="#ab461254272bf62003e540ec997ab6795">useHVXV68Ops</a>, <a href="#a7cf43b90b6f9a932bcafab27f6c9293f">useHVXV69Ops</a>, <a href="#a91c3496f281892d263a81bf41f025ba3">useHVXV71Ops</a>, <a href="#abe2e40f648c6665a7952436a76b7fa25">useHVXV73Ops</a> and <a href="#a789ed44d3831323b838377a863a3f1b2">useHVXV79Ops</a>.</p>

</div>
</div>

### OptLevel {#aa1a449c0a0b2fed37ce27a74867d7bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel llvm::HexagonSubtarget::OptLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#a3f194fc9ae635216053fb7435c6c90d6">HexagonSubtarget</a> and <a href="#af94fdaeffe4b4d40fe328351f509e954">useAA</a>.</p>

</div>
</div>

### UseBSBScheduling {#a6ecae06c10fab8169b03e2a74476b909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseBSBScheduling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the target should use Back-Skip-Back scheduling.</p>


<p>This is the default for V60.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<p>Referenced by <a href="#ac33e274ca277cfe840f699acc1b8a814">initializeSubtargetDependencies</a> and <a href="#ae72e804006fb285ff4da19a7eab85c37">useBSBScheduling</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CPUString {#a3f736a4a9eeb8a364f99605a7651b64c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::HexagonSubtarget::CPUString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### EnableDuplex {#a801999547d6eb50e32c81034a0c87f04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::EnableDuplex = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### FrameLowering {#ad112f847ca36884cfaee03010f976adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonFrameLowering llvm::HexagonSubtarget::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### HasMemNoShuf {#af5110011594c3de279a8734e0de28785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::HasMemNoShuf = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### HasPreV65 {#a7471bcc95585608cb01001b104d67d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::HasPreV65 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### HexagonProcFamily {#a372768649f7b9986101c1457b8986235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonProcFamilyEnum llvm::HexagonSubtarget::HexagonProcFamily = Others</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### InstrInfo {#acdef3ffc401cc62a4629d50c11ad769b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonInstrInfo llvm::HexagonSubtarget::InstrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### InstrItins {#a9b6e15d00d1653b58efae32ea31137f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrItineraryData llvm::HexagonSubtarget::InstrItins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### NoreturnStackElim {#a419f8edc308b2852223c24641f17f4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::NoreturnStackElim = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### RegInfo {#a27e994ca60480d99ebd2feb2b364ce5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonRegisterInfo llvm::HexagonSubtarget::RegInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### ReservedR19 {#ae098ce44f130769abbaafa657a193ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::ReservedR19 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### TargetTriple {#a1854e0d51d7c101b274173c410d2bf24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::HexagonSubtarget::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### TLInfo {#a07828117299f13c7bdad3e1e6386697a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonTargetLowering llvm::HexagonSubtarget::TLInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### TSInfo {#a5681a5036cda4fc91753e2e04d58fc59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonSelectionDAGInfo llvm::HexagonSubtarget::TSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseAudioOps {#a366c106297a9cbe9a95cf51fdf6f74ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseAudioOps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseCabac {#ad3dc1ed2575f01759ca1eaa3cc16441a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseCabac = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseCompound {#aaf5f1c5d90ced3448b578bff544ff9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseCompound = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseHVX128BOps {#a37c7a2df14621a0757aeebdbbe7bedbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseHVX128BOps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseHVX64BOps {#ad3759d78ae6ccba291288657b6b2ee22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseHVX64BOps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseHVXFloatingPoint {#a8372e01e20894021cdd76a5e41b68759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseHVXFloatingPoint = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseHVXIEEEFPOps {#a57ac981429e51915a5162fc8ef02a7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseHVXIEEEFPOps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseHVXQFloatOps {#a1c703f9734d50a81bbee6539d0940b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseHVXQFloatOps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseLongCalls {#acf220a16c4bbe7988276d249036039f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseLongCalls = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseMemops {#a5f80b1d42cc8c92fddb09f0d7346aefc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseMemops = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseNewValueJumps {#aa58feeeda10fbc6ef1d960a3cb115f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseNewValueJumps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseNewValueStores {#a4e6cd646b3050f646a2722796d3dc82c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseNewValueStores = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UsePackets {#a1bea9cd5b3b43c696cd3efe7a9cdd707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UsePackets = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseSmallData {#ade6a5cc32dd2e1dfad12db1508053799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseSmallData = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseUnsafeMath {#a4997a606d886e6eed6b5b367561365b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseUnsafeMath = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

### UseZRegOps {#aa8d68294aaf034dc59aee230c929cf83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonSubtarget::UseZRegOps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
