---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DXILPrettyPrinter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-h">DXILPrettyPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceanalysis-h">DXILResourceAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directx-h">DirectX.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatadapters-h">llvm/Support/FormatAdapters.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-dxilprettyprinter-cpp-">anonymous{DXILPrettyPrinter.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatresourcedimension">FormatResourceDimension</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindingid">FormatBindingID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindinglocation">FormatBindingLocation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindingsize">FormatBindingSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dxilprettyprinter-cpp-/dxilprettyprinterlegacy">DXILPrettyPrinterLegacy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad842a1e93ebfc30d2a69b46a8e88823a">getRCName</a> (dxil::ResourceClass RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778108379731dfe2259171c68d23e2b2">getRCPrefix</a> (dxil::ResourceClass RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7798652700f5ca1003d76faa77ccfaa9">getFormatName</a> (const dxil::ResourceTypeInfo &amp;RI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583750bf0c04237987cf08357494cb23">getTextureDimName</a> (dxil::ResourceKind RK)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b48396e87e416debd788f0948eee89d">prettyPrintResources</a> (raw_ostream &amp;OS, const DXILBindingMap &amp;DBM, DXILResourceTypeMap &amp;DRTM, const dxil::Resources &amp;MDResources)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6328e1cd0513593c138d4b79e2bf4e">INITIALIZE_PASS_BEGIN</a> (DXILPrettyPrinterLegacy, "dxil-pretty-printer", "DXIL Metadata Pretty Printer", true, true) INITIALIZE_PASS_END(DXILPrettyPrinterLegacy</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil pretty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97eec4cd1bdbc225c1aaf199eec5c97f">printer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil pretty DXIL <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Pretty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">dxil pretty DXIL <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Pretty</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc18f9bedd5a458320ead44c4a6ba0a4">true</a></td>
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


<div class="doxySectionDef">

## Functions

### getFormatName() {#a7798652700f5ca1003d76faa77ccfaa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getFormatName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo">dxil::ResourceTypeInfo</a> &amp; RI)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcetypeinfo/typedinfo/#aece1edf692f952783c46dc7563b4f60d">llvm::dxil::ResourceTypeInfo::TypedInfo::ElementTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a56d8353718e6fdc78b8d69078a2cdb94">llvm::dxil::F16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a44ad4ef5a76e6aa6fb3e3fa079a54fda">llvm::dxil::F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a1ad5f6f3069070ec4cbbdc94d5e61e0e">llvm::dxil::F64</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a39e4b5d1b12d30d8c969d9171c55ef39">llvm::dxil::ResourceTypeInfo::getTyped</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0aa18c217c4f2a811afcaaf5052945e31b">llvm::dxil::I1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0abcd774f891b5f9df7099f3ea75dadf8d">llvm::dxil::I16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0ad878ea6016bfe01729548bf442de5a8b">llvm::dxil::I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0ae7e62f6928f76df671b5a0379793fab6">llvm::dxil::I64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a2854da2d6e1e5a85f4abdae5319ddc35">llvm::dxil::ResourceTypeInfo::isCBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a1f38896d47f03dde9704d64b669c135e">llvm::dxil::ResourceTypeInfo::isSampler</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#ad5ffe17eb014d8227e03af37547ebf39">llvm::dxil::ResourceTypeInfo::isStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a20e1156c776fa816c593792d6c8ec269">llvm::dxil::ResourceTypeInfo::isTyped</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0ad49746d0d706d396a09cdbd533adbb49">llvm::dxil::PackedS8x32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a07b9bfc15d832cb058af7943f3f1eb58">llvm::dxil::PackedU8x32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a8d29a0d0f0055807a1679a8eed993384">llvm::dxil::SNormF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a90315c4523113b9931857bb2c2342cd9">llvm::dxil::SNormF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a394dc44928458a185fc05d5558bef66a">llvm::dxil::SNormF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0aef9ef3ebca4d2b64b6ec83808bafa5f2">llvm::dxil::U16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0ac8bd5bedff8ef192d39a962afc0e19ee">llvm::dxil::U32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a31d65cccd6593e4101db93fb878abcaa">llvm::dxil::U64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a04c1fb3a9689c66612d74f6c2acb7ff7">llvm::dxil::UNormF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a6812f7bb99b7c468860b2346e1b61867">llvm::dxil::UNormF32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a7cddbe82c3630d7f1084d7da360436d0a1b1a9cb50b4bffe8e5eafb4c21090823">llvm::dxil::UNormF64</a>.</p>


<p>Referenced by <a href="#a0b48396e87e416debd788f0948eee89d">prettyPrintResources</a>.</p>

</div>
</div>

### getRCName() {#ad842a1e93ebfc30d2a69b46a8e88823a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getRCName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687">dxil::ResourceClass</a> RC)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687ab71ecf0b186ac1b938e15483f792b7db">llvm::dxil::SRV</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a6902d76cea698982754404da77e5e08a">llvm::dxil::UAV</a>.</p>


<p>Referenced by <a href="#a0b48396e87e416debd788f0948eee89d">prettyPrintResources</a>.</p>

</div>
</div>

### getRCPrefix() {#a778108379731dfe2259171c68d23e2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getRCPrefix (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687">dxil::ResourceClass</a> RC)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687ab71ecf0b186ac1b938e15483f792b7db">llvm::dxil::SRV</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a6902d76cea698982754404da77e5e08a">llvm::dxil::UAV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindingid/#a8326f8bdde6735a38601fb0e0ac78c11">anonymous{DXILPrettyPrinter.cpp}::FormatBindingID::format</a> and <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindinglocation/#a15443027d777f78ca94fd23c346f0d22">anonymous{DXILPrettyPrinter.cpp}::FormatBindingLocation::format</a>.</p>

</div>
</div>

### getTextureDimName() {#a583750bf0c04237987cf08357494cb23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getTextureDimName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31">dxil::ResourceKind</a> RK)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a06a59eef30545f33a5df0fea71dcaf2e">llvm::dxil::FeedbackTexture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a43ae21351e78d50ee79f0146ed43caf7">llvm::dxil::FeedbackTexture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a4bbb8f967da6d1a610596d7257179c2b">llvm::dxil::Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a452680a33afbbf29c211d803c9484b64">llvm::dxil::NumEntries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ac6001c2a0a70c0657652163419784125">llvm::dxil::RawBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a8fc1460bf51b8b7bd628c575d831ad91">llvm::dxil::RTAccelerationStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5bca2f066df1fe641b2b779db2a63c0a">llvm::dxil::Sampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab4c372f84a6f9b749ede9fbab15b27fd">llvm::dxil::StructuredBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a61247dae2236d3488fc521b1b1e4f6f1">llvm::dxil::TBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31adc7f989aa32631adaea4eb6a609b0de4">llvm::dxil::Texture1D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a9506a77553ace6035c9096f86b0a5e8d">llvm::dxil::Texture1DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31aa6e2bae752d3bf4e34cb392bca789995">llvm::dxil::Texture2D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a5452f0008bbc07c796bb4ac7d284928d">llvm::dxil::Texture2DArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a72b48d523e1388e5cca2a10f16d740c5">llvm::dxil::Texture2DMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ad0871f59703267cbdada0c91924963be">llvm::dxil::Texture2DMSArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a89c915587e16bcf8963be7cf41a0d9fd">llvm::dxil::Texture3D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a0a152d9f3e1df14068c5857fb3352505">llvm::dxil::TextureCube</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31ab134787bfc1bdfe2d470e04468c1aa72">llvm::dxil::TextureCubeArray</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0e8254c15e0d398ad66b4d52568a5c31a27537f55d5c31f22fc4eaa63d0a785b6">llvm::dxil::TypedBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatresourcedimension/#af4b6748ab65963226264db9a8b0ec348">anonymous{DXILPrettyPrinter.cpp}::FormatResourceDimension::format</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a7d6328e1cd0513593c138d4b79e2bf4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (DXILPrettyPrinterLegacy, "dxil-pretty-printer", "DXIL <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Pretty Printer", <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### prettyPrintResources() {#a0b48396e87e416debd788f0948eee89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void prettyPrintResources (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxilbindingmap">DXILBindingMap</a> &amp; DBM, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap">DXILResourceTypeMap</a> &amp; DRTM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dxil/resources">dxil::Resources</a> &amp; MDResources)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a7bf035b9e85217bdc1a135c04fac8c9a">llvm::dxil::CBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>, <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindingid/#a2d7e241ecb54492444c2a493c5cd4883">anonymous{DXILPrettyPrinter.cpp}::FormatBindingID::FormatBindingID</a>, <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindinglocation/#a7719d1f8efaa729d4461c1db01cd70e5">anonymous{DXILPrettyPrinter.cpp}::FormatBindingLocation::FormatBindingLocation</a>, <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatbindingsize/#aab2ecb6491e5404b2a324a3c5c14e17a">anonymous{DXILPrettyPrinter.cpp}::FormatBindingSize::FormatBindingSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-dxilprettyprinter-cpp-/formatresourcedimension/#ac719f0f929437f6a7dd3fbb8bafdcbe4">anonymous{DXILPrettyPrinter.cpp}::FormatResourceDimension::FormatResourceDimension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#a7798652700f5ca1003d76faa77ccfaa9">getFormatName</a>, <a href="#ad842a1e93ebfc30d2a69b46a8e88823a">getRCName</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a019b4eed93ea6b85c916c8957b04e3fb">llvm::dxil::ResourceTypeInfo::getResourceClass</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#af3c0f21d561d7cb2b2b9858f1b8744ae">llvm::dxil::Resources::hasCBuffers</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#a87bafd9a99b84743b04303b76e1763eb">llvm::dxil::Resources::hasUAVs</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#aeccc967338a23aaf0392de3d0b84bdd3">llvm::dxil::Resources::printCBuffers</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#adcb0a0862be18e7a3f204477d1c37262">llvm::dxil::Resources::printUAVs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88caa1fa27779242b4902f7ae3bdd5c6d508">Type</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687a6902d76cea698982754404da77e5e08a">llvm::dxil::UAV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxilprettyprinterpass/#a80163db1be8afd66500bc24bb7275747">llvm::DXILPrettyPrinterPass::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-dxilprettyprinter-cpp-/dxilprettyprinterlegacy/#aeaafee5be83e13663d74d9b75bdcd4f3">anonymous{DXILPrettyPrinter.cpp}::DXILPrettyPrinterLegacy::runOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### printer {#a97eec4cd1bdbc225c1aaf199eec5c97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil pretty printer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#aa9760bc95c80c10f22e94040a42d2ed1">llvm::AArch64MCInstLower::AArch64MCInstLower</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#a131a0c5016fec35e4483f8a44a7ea236">llvm::BPFMCInstLower::BPFMCInstLower</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a528f3b8c204e96bf6a9b2680f22b4af6">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::MCAsmStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#ad77eb512a89d5c9cb62ee914963b7e66">llvm::MSP430MCInstLower::MSP430MCInstLower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a78ac25e87531ad102d4d06066cdf6680">llvm::cl::printOptionDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/arminstprinter-cpp/#a2702adfb6cd2c487fc9d8c38d20e040c">printRegImmShift</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a20f10ba801c94c7af36e5a64a20ecaed">llvm::WebAssemblyMCInstLower::WebAssemblyMCInstLower</a>.</p>

</div>
</div>

### Printer {#aa60cf1897c36e79b878a6f3c6300cfba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil pretty DXIL Metadata Pretty Printer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#acf14ffe7608cbfcc75f2858e0eaa38e7">llvm::CodeGenTargetMachineImpl::addAsmPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a230d5dad7ea2d94e1671a4aa222a2e15">llvm::MCInst::dump_pretty</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolgroup/#aa42da7db0106042194a64a1b57f07951">llvm::pdb::SymbolGroup::formatFromChecksumsOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolgroup/#a6eff6e72f9b8cf2cdc35119572635103">llvm::pdb::SymbolGroup::formatFromFileName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/inputfile-cpp/#a3271c625d3a4c5a238f327fcb6391576">formatInternal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugutils-cpp-/#a3e5dd3fc582ce67a904121b6b9360f53">anonymous{DebugUtils.cpp}::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a65a4bfcd0f7b8f67d9fa6e835a0a49e7">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#ad59ca8a8dc03bd18b7c3a7c9a6eb4c83">printAmdKernelCodeField</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a064c339f401589b34437e61d8108d8d8">llvm::VPlan::printDOT</a>, <a href="/web-llvm/docs/api/classes/llvm/scopedprinter/#a8d8b7f9d291d6ed993814a0ed7e38589">llvm::ScopedPrinter::printList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a60b22edc59b0e3919841d92a72a8ef">llvm::printMIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aff82033771977413104f16ed617d2b4f">llvm::codeview::printTypeIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolgroup/#aa0b9d665e343bc839dab14961670fcc1">llvm::pdb::SymbolGroup::SymbolGroupIterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#af7fa07d6c1b002682729091f44ed713f">writeDIArgList</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae63e2c24c65979ed0c3a52704a8d6c29">writeDIAssignID</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab007fb7393c2c55689a30b5c9f9b54e7">writeDIBasicType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa4ab58811d85ab06ba2589190e42c409">writeDICommonBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#abf928d48c46a6de39967c53eecfb6320">writeDICompileUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a187176da17ddab193a07b2cde86c2297">writeDICompositeType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a6f6d9d4bb9a4379614584f1dc6ec07cc">writeDIDerivedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ad48e4b73f1c3fda1be498800e79bb2d1">writeDIEnumerator</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a593a29eb296078e4adc21c4735cbf089">writeDIFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac7cbec4f02d601d51217c096e1462805">writeDIGenericSubrange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3a754075676cf28fe91f2d0bb1b5fc44">writeDIGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a0f3f4b6a41a95ba9e3750a121736c90e">writeDIGlobalVariableExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b805938ab35a8870fff225c689a3019">writeDIImportedEntity</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a6d889ad151bdaf0e37c410381812c17e">writeDILabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae839d5f52524ed2102d25ae1ffe92deb">writeDILexicalBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#accd701498a663907e97c9dcedfa7a54a">writeDILexicalBlockFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab6bcc5e28f19737a3b0ec69ff062c0f9">writeDILocalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a9d08596bb6d02dac5a3629abda510174">writeDILocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a01d062dbede1f91bf1c960a57fd349dc">writeDIMacro</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#afd6c1602b1a0ffbb1aad2c7cc9bac1d6">writeDIMacroFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a5584c0a21c6481a943ab39406bd62098">writeDIModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a9d3673e478e66c19b06dcbfb588686c2">writeDINamespace</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a8197c96b5ae5517644ec4c331c648782">writeDIObjCProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3480bb9edd827c6105a2a28652142d9c">writeDIStringType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a82755caf4693707060eaa24ed59ebd2a">writeDISubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac7e7ff419d64524657abe5c1389f34dc">writeDISubrange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a5fbddbd7054d4a95232371b2c436ab7b">writeDISubroutineType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab9f46d7b60f100ca64722051bf8401b1">writeDITemplateTypeParameter</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#af836f3f665f5c5c4ba40edc1db6ab530">writeDITemplateValueParameter</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab51487913b1d80a22af63de2ff1dcb89">writeGenericDINode</a>.</p>

</div>
</div>

### true {#afc18f9bedd5a458320ead44c4a6ba0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxil pretty DXIL Metadata Pretty true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp">DXILPrettyPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
