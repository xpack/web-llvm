---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpupalmetadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUPALMetadata` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUPALMetadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">Target/AMDGPU/Utils/AMDGPUPALMetadata.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95159cc93ee576de359dcc922fb6df3f">RegisterExprMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d8a5bd0e7677224b9705f4bea047f9">readFromIR</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79e9fa4a072af1febbd776cab9e74da5">setFromBlob</a> (unsigned Type, StringRef Blob)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00b11d53bda23b5ae530c39378258f4">setRsrc1</a> (unsigned CC, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a39843c47442c7dd6e7451a2fbc47f">setRsrc1</a> (unsigned CC, const MCExpr *Val, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afafff19dbfe21b91be73d6b391e0ac88">setRsrc2</a> (unsigned CC, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57137a7715a5daeb569a1f420cb81555">setRsrc2</a> (unsigned CC, const MCExpr *Val, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e39667eb0bfdab052b6e5195a3dc85">setSpiPsInputEna</a> (unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a139cae5fab8c0b6b80b8c1b5dc57c5ee">setSpiPsInputAddr</a> (unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547583d1108b1d2cf5c0cab7d18745a2">getRegister</a> (unsigned Reg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a> (unsigned Reg, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fe092bd112e2eb16c1cba213922aca">setRegister</a> (unsigned Reg, const MCExpr *Val, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17deb320c80f737750ffe34cf3fdc2ca">setEntryPoint</a> (unsigned CC, StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab960dcfb8dbb02f9ee3712e9cd4fdd">setNumUsedVgprs</a> (unsigned CC, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a997da932e61fd728685fcc9e78d1e">setNumUsedVgprs</a> (unsigned CC, const MCExpr *Val, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a69dd5135cc503d2e52ff5e98c1586">setNumUsedAgprs</a> (unsigned CC, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a2b7d6a2b255369890c405743ae1f9">setNumUsedAgprs</a> (unsigned CC, const MCExpr *Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6cf8c77ed58e349541abd675c3aebe">setNumUsedSgprs</a> (unsigned CC, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f41beaf9dd48255b076cd4219a26430">setNumUsedSgprs</a> (unsigned CC, const MCExpr *Val, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91fb6e5a8cd6fbae08887418de54c6dc">setScratchSize</a> (unsigned CC, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8554373c20f9a9f2d8a4946ba983729">setScratchSize</a> (unsigned CC, const MCExpr *Val, MCContext &amp;Ctx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9c390c6b3a93653d9334d054b1ee74">setFunctionScratchSize</a> (StringRef FnName, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af492274f31637afb6d77322572c3e0b0">setFunctionLdsSize</a> (StringRef FnName, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d187487b5f8a6d615df6a9a78c583e7">setFunctionNumUsedVgprs</a> (StringRef FnName, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0974d8f97a1fed70cf6fd43f5e0bb6bf">setFunctionNumUsedVgprs</a> (StringRef FnName, const MCExpr *Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e272c1b4818a5963243e7ba4d3b7d7d">setFunctionNumUsedSgprs</a> (StringRef FnName, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e1632c01d6e435bc578dd279cc4e240">setFunctionNumUsedSgprs</a> (StringRef FnName, const MCExpr *Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb9cf30692ba3299314ede6c8703be4">setWave32</a> (unsigned CC)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af405cf94e28aca3f12c108ff0b858aee">toString</a> (std::string &amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41f2994ff7727a6749e0002ba3852a9a">setFromString</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194297d42c7fc8aa48a8be43a3ec9fca">getVendor</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803f31e2dc0f9d21ac3d3c19ca8ce927">getType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc533e5af74bf82cb31e1f9699e063b">toBlob</a> (unsigned Type, std::string &amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/document">msgpack::Document</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6743acc4ce0c12a67ccd8727a860abc">getMsgPackDoc</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe2819e85575e21b3a8016e976687aa">setLegacy</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab89081b5ac9aa4994fe0d2915209d27">getPALMajorVersion</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6435f147a3ee82e6212eff30c2670ecb">getPALMinorVersion</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da1122651a3e237458b08e5c037dd6b">setHwStage</a> (unsigned CC, StringRef field, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a318df7194c09c5b55ed86acee4a7e">setHwStage</a> (unsigned CC, StringRef field, bool Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11564662410ba56ff488967d968af438">setHwStage</a> (unsigned CC, StringRef field, msgpack::Type Type, const MCExpr *Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde8671864c6e96e485c027f2d002209">setComputeRegisters</a> (StringRef field, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc23c71a526a6b2a211ea63138db1ea4">setComputeRegisters</a> (StringRef field, bool Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69cd2e7535c3f0c06e9c24e491198f5b">refComputeRegister</a> (StringRef field)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9cb93d8e26870ae612fc9d8c0a2e1cd">checkComputeRegisters</a> (StringRef field, unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbe07926d164ca5df909bd51b351da8">checkComputeRegisters</a> (StringRef field, bool Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6056a3c6f7669f404bcfc6e72a20b79">setGraphicsRegisters</a> (StringRef field, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94315eca5d01f862a6c69f78d88dd9e6">setGraphicsRegisters</a> (StringRef field, bool Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05271bfa4b5c9622a2ac926306563998">setGraphicsRegisters</a> (StringRef field1, StringRef field2, unsigned Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fa9b47373a37aef822af6bdd83c2e45">setGraphicsRegisters</a> (StringRef field1, StringRef field2, bool Val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3cc411bac033c6b3b5a4e7d6764cb94">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f7236f21b8b85f55402f2ca4deffe7d">resolvedAllMCExpr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06bf78f874067f17bc3c762d6acab53">isLegacy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac319985ab6820ce615298e748a306fb2">refRegisters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bfb78f7883ad05aca0a52ba75abbfa1">getRegisters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b564f3742b208e27db5a3e5fba8749e">refShaderFunctions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1780a09a0f5598f0dcdf59868158b27">getShaderFunctions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae466034428c9fbd8abe129b0107cf70d">getShaderFunction</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20cd9a9118955a6fa990a56a241eb434">refComputeRegisters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4332b3f68dc16361c3deafbc1cb47107">getComputeRegisters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9a459b8f366f85d2c330ba6ad5c1b78">refGraphicsRegisters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa839405795d026aa9250b5bdf006131a">getGraphicsRegisters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af566c0759c533e1f88358ae8ab281b12">refHwStage</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode">msgpack::MapDocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc04e5d6c6c5f6b8466d0544a8b3be0">getHwStage</a> (unsigned CC)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab148e085508538fb3ff84614519b45">getPALVersion</a> (unsigned idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6e56d089338eb04ad3b2d6f48209fa">setFromLegacyBlob</a> (StringRef Blob)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d14647c4f48a87caf221788ccc6e16a">setFromMsgPackBlob</a> (StringRef Blob)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96cd6b823abda99861ad65fe34b6ee88">toLegacyBlob</a> (std::string &amp;Blob)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8794ae8788275480b04538929339461d">toMsgPackBlob</a> (std::string &amp;Blob)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf624db4d5ecb3653def12812e771bc1">BlobType</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/document">msgpack::Document</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae038fb70241f90e80a5eed8167b98eb1">MsgPackDoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f89129a79bfa371792b9e9979b47bc2">Registers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684120ab74a620fb65bf37c5e23d01bf">HwStages</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6b6d1ec0ffaede37cb5fa9042726bc0">ShaderFunctions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73b524b786e277022bba2c966cfd3f3">VersionChecked</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f2c9e526ea0948703cbf419eba13f16">Version</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2aad663f78b79b265e4a1e701fec0f">ComputeRegisters</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode">msgpack::DocNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3309711162f153c2c7ff777c32c09c75">GraphicsRegisters</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/delayedmcexprs">DelayedMCExprs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a45bc3404d11562eed7c7fcff8080c">DelayedExprs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a95159cc93ee576de359dcc922fb6df3f">RegisterExprMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea47223b6cd2e09332bf236d5d1eee9">REM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd147e1e63e46aad5add5993ddae05c0">ResolvedAll</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### RegisterExprMap {#a95159cc93ee576de359dcc922fb6df3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AMDGPUPALMetadata::RegisterExprMap =  DenseMap&lt;unsigned, const MCExpr *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkComputeRegisters() {#ad9cb93d8e26870ae612fc9d8c0a2e1cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPALMetadata::checkComputeRegisters (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a69cd2e7535c3f0c06e9c24e491198f5b">refComputeRegister</a>.</p>

</div>
</div>

### checkComputeRegisters() {#a4cbe07926d164ca5df909bd51b351da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPALMetadata::checkComputeRegisters (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, bool Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a69cd2e7535c3f0c06e9c24e491198f5b">refComputeRegister</a>.</p>

</div>
</div>

### getMsgPackDoc() {#ab6743acc4ce0c12a67ccd8727a860abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::Document * llvm::AMDGPUPALMetadata::getMsgPackDoc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### getPALMajorVersion() {#aab89081b5ac9aa4994fe0d2915209d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUPALMetadata::getPALMajorVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### getPALMinorVersion() {#a6435f147a3ee82e6212eff30c2670ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUPALMetadata::getPALMinorVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1043 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### getRegister() {#a547583d1108b1d2cf5c0cab7d18745a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUPALMetadata::getRegister (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### getType() {#a803f31e2dc0f9d21ac3d3c19ca8ce927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUPALMetadata::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a595765b8c36eef76cb8f2a6dfd10c277">llvm::AMDGPUTargetELFStreamer::finish</a>.</p>

</div>
</div>

### getVendor() {#a194297d42c7fc8aa48a8be43a3ec9fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * AMDGPUPALMetadata::getVendor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/elfnote/#a9c117e2bdb138b1a81a4d318f0eae388">llvm::AMDGPU::ElfNote::NoteNameV2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/elfnote/#aefb41dbb5c30115f2597db8083cfcb0a">llvm::AMDGPU::ElfNote::NoteNameV3</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a595765b8c36eef76cb8f2a6dfd10c277">llvm::AMDGPUTargetELFStreamer::finish</a>.</p>

</div>
</div>

### readFromIR() {#a93d8a5bd0e7677224b9705f4bea047f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::readFromIR (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad7ca5290dc5789cbeae763690e6edccf">llvm::mdconst::dyn_extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5298f27e75d05e13c7a4f2da4b0d9be3acf4fd0c45eb532bfad88dd48b5d5e6ee">llvm::ELF::NT_AMD_PAL_METADATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ae01999f6bb8613fd9cad067b9e8e83b4acd3865a0ae5a4a85ae17d89a549267d3">llvm::ELF::NT_AMDGPU_METADATA</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### refComputeRegister() {#a69cd2e7535c3f0c06e9c24e491198f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode * AMDGPUPALMetadata::refComputeRegister (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1067 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a4cbe07926d164ca5df909bd51b351da8">checkComputeRegisters</a> and <a href="#ad9cb93d8e26870ae612fc9d8c0a2e1cd">checkComputeRegisters</a>.</p>

</div>
</div>

### reset() {#af3cc411bac033c6b3b5a4e7d6764cb94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1010 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#acb6335c5fc14b12bc6987411a8e2b03c">llvm::AMDGPUTargetAsmStreamer::finish</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a595765b8c36eef76cb8f2a6dfd10c277">llvm::AMDGPUTargetELFStreamer::finish</a>.</p>

</div>
</div>

### resolvedAllMCExpr() {#a6f7236f21b8b85f55402f2ca4deffe7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPALMetadata::resolvedAllMCExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setComputeRegisters() {#afde8671864c6e96e485c027f2d002209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setComputeRegisters (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1059 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setComputeRegisters() {#abc23c71a526a6b2a211ea63138db1ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setComputeRegisters (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, bool Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1063 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setEntryPoint() {#a17deb320c80f737750ffe34cf3fdc2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setEntryPoint (unsigned CC, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

### setFromBlob() {#a79e9fa4a072af1febbd776cab9e74da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPALMetadata::setFromBlob (unsigned Type, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5298f27e75d05e13c7a4f2da4b0d9be3acf4fd0c45eb532bfad88dd48b5d5e6ee">llvm::ELF::NT_AMD_PAL_METADATA</a>.</p>

</div>
</div>

### setFromString() {#a41f2994ff7727a6749e0002ba3852a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPALMetadata::setFromString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ae01999f6bb8613fd9cad067b9e8e83b4acd3865a0ae5a4a85ae17d89a549267d3">llvm::ELF::NT_AMDGPU_METADATA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a27118326006d3829667a400ad23d5d98">llvm::msgpack::String</a>.</p>

</div>
</div>

### setFunctionLdsSize() {#af492274f31637afb6d77322572c3e0b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setFunctionLdsSize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setFunctionNumUsedSgprs() {#a7e272c1b4818a5963243e7ba4d3b7d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setFunctionNumUsedSgprs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setFunctionNumUsedSgprs() {#a8e1632c01d6e435bc578dd279cc4e240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setFunctionNumUsedSgprs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### setFunctionNumUsedVgprs() {#a6d187487b5f8a6d615df6a9a78c583e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setFunctionNumUsedVgprs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setFunctionNumUsedVgprs() {#a0974d8f97a1fed70cf6fd43f5e0bb6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setFunctionNumUsedVgprs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### setFunctionScratchSize() {#a2e9c390c6b3a93653d9334d054b1ee74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setFunctionScratchSize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setGraphicsRegisters() {#ad6056a3c6f7669f404bcfc6e72a20b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setGraphicsRegisters (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setGraphicsRegisters() {#a94315eca5d01f862a6c69f78d88dd9e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setGraphicsRegisters (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, bool Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setGraphicsRegisters() {#a05271bfa4b5c9622a2ac926306563998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setGraphicsRegisters (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field1, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field2, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setGraphicsRegisters() {#a9fa9b47373a37aef822af6bdd83c2e45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setGraphicsRegisters (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field1, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field2, bool Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1098 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setHwStage() {#a9da1122651a3e237458b08e5c037dd6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setHwStage (unsigned CC, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a34c7390935d69413b21319ee19d783db">EmitPALMetadataCommon</a>, <a href="#a47a2b7d6a2b255369890c405743ae1f9">setNumUsedAgprs</a>, <a href="#a4f41beaf9dd48255b076cd4219a26430">setNumUsedSgprs</a>, <a href="#aa2a997da932e61fd728685fcc9e78d1e">setNumUsedVgprs</a> and <a href="#af8554373c20f9a9f2d8a4946ba983729">setScratchSize</a>.</p>

</div>
</div>

### setHwStage() {#a96a318df7194c09c5b55ed86acee4a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setHwStage (unsigned CC, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, bool Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1050 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

### setHwStage() {#a11564662410ba56ff488967d968af438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setHwStage (unsigned CC, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> field, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6">msgpack::Type</a> Type, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1054 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

### setLegacy() {#a6fe2819e85575e21b3a8016e976687aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setLegacy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1005 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5298f27e75d05e13c7a4f2da4b0d9be3acf4fd0c45eb532bfad88dd48b5d5e6ee">llvm::ELF::NT_AMD_PAL_METADATA</a>.</p>

</div>
</div>

### setNumUsedAgprs() {#ad1a69dd5135cc503d2e52ff5e98c1586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setNumUsedAgprs (unsigned CC, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>.</p>

</div>
</div>

### setNumUsedAgprs() {#a47a2b7d6a2b255369890c405743ae1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setNumUsedAgprs (unsigned CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a9da1122651a3e237458b08e5c037dd6b">setHwStage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### setNumUsedSgprs() {#afc6cf8c77ed58e349541abd675c3aebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setNumUsedSgprs (unsigned CC, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a10741674b01fc9ce52c7e9fdbbd98f5a">getScratchSizeKey</a>, <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaaa1122a4036f5367968666b48be3512e">llvm::AMDGPU::PALMD::VS_NUM_USED_SGPRS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaa877b99713f4c66fbceef23318070041">llvm::AMDGPU::PALMD::VS_SCRATCH_SIZE</a>.</p>

</div>
</div>

### setNumUsedSgprs() {#a4f41beaf9dd48255b076cd4219a26430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setNumUsedSgprs (unsigned CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a10741674b01fc9ce52c7e9fdbbd98f5a">getScratchSizeKey</a>, <a href="#a9da1122651a3e237458b08e5c037dd6b">setHwStage</a>, <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaaa1122a4036f5367968666b48be3512e">llvm::AMDGPU::PALMD::VS_NUM_USED_SGPRS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaa877b99713f4c66fbceef23318070041">llvm::AMDGPU::PALMD::VS_SCRATCH_SIZE</a>.</p>

</div>
</div>

### setNumUsedVgprs() {#a4ab960dcfb8dbb02f9ee3712e9cd4fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setNumUsedVgprs (unsigned CC, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a10741674b01fc9ce52c7e9fdbbd98f5a">getScratchSizeKey</a>, <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa59dd4aee3a964062e5cfdf3e4d838dbd">llvm::AMDGPU::PALMD::VS_NUM_USED_VGPRS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaa877b99713f4c66fbceef23318070041">llvm::AMDGPU::PALMD::VS_SCRATCH_SIZE</a>.</p>

</div>
</div>

### setNumUsedVgprs() {#aa2a997da932e61fd728685fcc9e78d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setNumUsedVgprs (unsigned CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a10741674b01fc9ce52c7e9fdbbd98f5a">getScratchSizeKey</a>, <a href="#a9da1122651a3e237458b08e5c037dd6b">setHwStage</a>, <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa59dd4aee3a964062e5cfdf3e4d838dbd">llvm::AMDGPU::PALMD::VS_NUM_USED_VGPRS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaa877b99713f4c66fbceef23318070041">llvm::AMDGPU::PALMD::VS_SCRATCH_SIZE</a>.</p>

</div>
</div>

### setRegister() {#a97fc9eaaed21f58ee95b42903afabb90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setRegister (unsigned Reg, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>


<p>Referenced by <a href="#a93d8a5bd0e7677224b9705f4bea047f9">readFromIR</a>, <a href="#a4f41beaf9dd48255b076cd4219a26430">setNumUsedSgprs</a>, <a href="#afc6cf8c77ed58e349541abd675c3aebe">setNumUsedSgprs</a>, <a href="#aa2a997da932e61fd728685fcc9e78d1e">setNumUsedVgprs</a>, <a href="#a4ab960dcfb8dbb02f9ee3712e9cd4fdd">setNumUsedVgprs</a>, <a href="#ad6a39843c47442c7dd6e7451a2fbc47f">setRsrc1</a>, <a href="#aa00b11d53bda23b5ae530c39378258f4">setRsrc1</a>, <a href="#a57137a7715a5daeb569a1f420cb81555">setRsrc2</a>, <a href="#afafff19dbfe21b91be73d6b391e0ac88">setRsrc2</a>, <a href="#af8554373c20f9a9f2d8a4946ba983729">setScratchSize</a>, <a href="#a91fb6e5a8cd6fbae08887418de54c6dc">setScratchSize</a>, <a href="#a139cae5fab8c0b6b80b8c1b5dc57c5ee">setSpiPsInputAddr</a>, <a href="#aa2e39667eb0bfdab052b6e5195a3dc85">setSpiPsInputEna</a> and <a href="#abbb9cf30692ba3299314ede6c8703be4">setWave32</a>.</p>

</div>
</div>

### setRegister() {#a44fe092bd112e2eb16c1cba213922aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setRegister (unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a6b303b433f43b901194dbf17adfb562c">llvm::MCBinaryExpr::createOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### setRsrc1() {#aa00b11d53bda23b5ae530c39378258f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setRsrc1 (unsigned CC, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a68759c6954b5a8ed6ca3563cc13148b1">getRsrc1Reg</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### setRsrc1() {#ad6a39843c47442c7dd6e7451a2fbc47f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setRsrc1 (unsigned CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a68759c6954b5a8ed6ca3563cc13148b1">getRsrc1Reg</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### setRsrc2() {#afafff19dbfe21b91be73d6b391e0ac88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setRsrc2 (unsigned CC, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a68759c6954b5a8ed6ca3563cc13148b1">getRsrc1Reg</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### setRsrc2() {#a57137a7715a5daeb569a1f420cb81555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setRsrc2 (unsigned CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a68759c6954b5a8ed6ca3563cc13148b1">getRsrc1Reg</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### setScratchSize() {#a91fb6e5a8cd6fbae08887418de54c6dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setScratchSize (unsigned CC, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a10741674b01fc9ce52c7e9fdbbd98f5a">getScratchSizeKey</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### setScratchSize() {#af8554373c20f9a9f2d8a4946ba983729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setScratchSize (unsigned CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp/#a10741674b01fc9ce52c7e9fdbbd98f5a">getScratchSizeKey</a>, <a href="#a9da1122651a3e237458b08e5c037dd6b">setHwStage</a>, <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a0b1291eded63143ac04709711274785a">llvm::msgpack::UInt</a>.</p>

</div>
</div>

### setSpiPsInputAddr() {#a139cae5fab8c0b6b80b8c1b5dc57c5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setSpiPsInputAddr (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa7c8be07496801d83b597c6a4b0d5e8e5">llvm::AMDGPU::PALMD::R_A1B4_SPI_PS_INPUT_ADDR</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### setSpiPsInputEna() {#aa2e39667eb0bfdab052b6e5195a3dc85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setSpiPsInputEna (unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa20d4442174a4473479a515e8875b6c38">llvm::AMDGPU::PALMD::R_A1B3_SPI_PS_INPUT_ENA</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### setWave32() {#abbb9cf30692ba3299314ede6c8703be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::setWave32 (unsigned CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca16c3e679fa61136bfeb3c5c9b7542d9f">llvm::CallingConv::AMDGPU_CS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6f08d1631b96043fe0201973d84e5539">llvm::CallingConv::AMDGPU_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca5c0f66e45afd7c51f4ee51552d8fb606">llvm::CallingConv::AMDGPU_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca91283117ce67ebdae50cc7730694d8f8">llvm::CallingConv::AMDGPU_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa4ae76377ba7eded90a5929319d13a308">llvm::AMDGPU::PALMD::R_2E00_COMPUTE_DISPATCH_INITIATOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa0e769b1d46ce1dfd5581cd8d9e6cd999">llvm::AMDGPU::PALMD::R_A1B6_SPI_PS_IN_CONTROL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa60d4d90dfa2502ea43fd8142fcf02d81">llvm::AMDGPU::PALMD::R_A2D5_VGT_SHADER_STAGES_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a7f597874693d6d230dcd8c37d2a090ba">S_00B800_CS_W32_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a21d3a0b8d58b342a8403b88178895950">S_0286D8_PS_W32_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a9ef8ad0ae1f031501a953979d1cd2687">S_028B54_GS_W32_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ac38a4026e022475e079f4616141b9da0">S_028B54_HS_W32_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ac1acc9f661e32db0086f878e7891eed1">S_028B54_VS_W32_EN</a> and <a href="#a97fc9eaaed21f58ee95b42903afabb90">setRegister</a>.</p>

</div>
</div>

### toBlob() {#adfc533e5af74bf82cb31e1f9699e063b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::toBlob (unsigned Type, std::string &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5298f27e75d05e13c7a4f2da4b0d9be3acf4fd0c45eb532bfad88dd48b5d5e6ee">llvm::ELF::NT_AMD_PAL_METADATA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetelfstreamer/#a595765b8c36eef76cb8f2a6dfd10c277">llvm::AMDGPUTargetELFStreamer::finish</a>.</p>

</div>
</div>

### toString() {#af405cf94e28aca3f12c108ff0b858aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::toString (std::string &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#a1cb9ed110f803fda0c8dc1d3c9587f36">llvm::AMDGPU::PALMD::AssemblerDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#a2ed75550f1758e49da7beadad0ae54c7">llvm::AMDGPU::PALMD::AssemblerDirectiveBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af686707ee13e7427f9a298054f7b358a">llvm::AMDGPU::PALMD::AssemblerDirectiveEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a17b4520610e0151c3ea791c6adf27d07">getRegisterName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/#afdae9da66bac09f4b2bfc0fd9f0559e6a4da8b7eb2c3f2007cf8238334401ef51">llvm::msgpack::Nil</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#acb6335c5fc14b12bc6987411a8e2b03c">llvm::AMDGPUTargetAsmStreamer::finish</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getComputeRegisters() {#a4332b3f68dc16361c3deafbc1cb47107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::MapDocNode AMDGPUPALMetadata::getComputeRegisters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### getGraphicsRegisters() {#aa839405795d026aa9250b5bdf006131a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::MapDocNode AMDGPUPALMetadata::getGraphicsRegisters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### getHwStage() {#a4cc04e5d6c6c5f6b8466d0544a8b3be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::MapDocNode AMDGPUPALMetadata::getHwStage (unsigned CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### getPALVersion() {#a1ab148e085508538fb3ff84614519b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUPALMetadata::getPALVersion (unsigned idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### getRegisters() {#a0bfb78f7883ad05aca0a52ba75abbfa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::MapDocNode AMDGPUPALMetadata::getRegisters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### getShaderFunction() {#ae466034428c9fbd8abe129b0107cf70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::MapDocNode AMDGPUPALMetadata::getShaderFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### getShaderFunctions() {#ac1780a09a0f5598f0dcdf59868158b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::MapDocNode AMDGPUPALMetadata::getShaderFunctions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### isLegacy() {#ad06bf78f874067f17bc3c762d6acab53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPALMetadata::isLegacy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### refComputeRegisters() {#a20cd9a9118955a6fa990a56a241eb434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode &amp; AMDGPUPALMetadata::refComputeRegisters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 914 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### refGraphicsRegisters() {#ad9a459b8f366f85d2c330ba6ad5c1b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode &amp; AMDGPUPALMetadata::refGraphicsRegisters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### refHwStage() {#af566c0759c533e1f88358ae8ab281b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode &amp; AMDGPUPALMetadata::refHwStage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### refRegisters() {#ac319985ab6820ce615298e748a306fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode &amp; AMDGPUPALMetadata::refRegisters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### refShaderFunctions() {#a7b564f3742b208e27db5a3e5fba8749e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode &amp; AMDGPUPALMetadata::refShaderFunctions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setFromLegacyBlob() {#ace6e56d089338eb04ad3b2d6f48209fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPALMetadata::setFromLegacyBlob (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### setFromMsgPackBlob() {#a8d14647c4f48a87caf221788ccc6e16a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPALMetadata::setFromMsgPackBlob (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Blob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### toLegacyBlob() {#a96cd6b823abda99861ad65fe34b6ee88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::toLegacyBlob (std::string &amp; Blob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

### toMsgPackBlob() {#a8794ae8788275480b04538929339461d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPALMetadata::toMsgPackBlob (std::string &amp; Blob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>, definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlobType {#adf624db4d5ecb3653def12812e771bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPUPALMetadata::BlobType = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### ComputeRegisters {#aed2aad663f78b79b265e4a1e701fec0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode llvm::AMDGPUPALMetadata::ComputeRegisters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### DelayedExprs {#a78a45bc3404d11562eed7c7fcff8080c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DelayedMCExprs llvm::AMDGPUPALMetadata::DelayedExprs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### GraphicsRegisters {#a3309711162f153c2c7ff777c32c09c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode llvm::AMDGPUPALMetadata::GraphicsRegisters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### HwStages {#a684120ab74a620fb65bf37c5e23d01bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode llvm::AMDGPUPALMetadata::HwStages</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### MsgPackDoc {#ae038fb70241f90e80a5eed8167b98eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::Document llvm::AMDGPUPALMetadata::MsgPackDoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### Registers {#a7f89129a79bfa371792b9e9979b47bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode llvm::AMDGPUPALMetadata::Registers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### REM {#acea47223b6cd2e09332bf236d5d1eee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterExprMap llvm::AMDGPUPALMetadata::REM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### ResolvedAll {#afd147e1e63e46aad5add5993ddae05c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUPALMetadata::ResolvedAll = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### ShaderFunctions {#ad6b6d1ec0ffaede37cb5fa9042726bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode llvm::AMDGPUPALMetadata::ShaderFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### Version {#a0f2c9e526ea0948703cbf419eba13f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">msgpack::DocNode llvm::AMDGPUPALMetadata::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

### VersionChecked {#ae73b524b786e277022bba2c966cfd3f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUPALMetadata::VersionChecked = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
