---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/siprograminfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SIProgramInfo` Struct Reference

<p>Track resource usage for kernels / entry functions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SIProgramInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">Target/AMDGPU/SIProgramInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c356d31810e2e705f15b1b3b058872">SIProgramInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72726562d2c74f257bb14d331c90300">reset</a> (const MachineFunction &amp;MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c73e82c5082e2f77d5647e1034eb81d">getComputePGMRSrc1</a> (const GCNSubtarget &amp;ST, MCContext &amp;Ctx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the value of the ComputePGMRsrc1 register. <a href="#a4c73e82c5082e2f77d5647e1034eb81d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe52a78f5c8a6b91ae15c4635ccf564e">getPGMRSrc1</a> (CallingConv::ID CC, const GCNSubtarget &amp;ST, MCContext &amp;Ctx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318d26ac513db990b9466b1ce9380032">getComputePGMRSrc2</a> (MCContext &amp;Ctx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the value of the ComputePGMRsrc2 register. <a href="#a318d26ac513db990b9466b1ce9380032">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15f8b9a5641db8dcff762d1190a285dc">getPGMRSrc2</a> (CallingConv::ID CC, MCContext &amp;Ctx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3688ae99640628e4a97f11753bcab0c9">VGPRBlocks</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa590ea054ee40115a9612e345df72146">SGPRBlocks</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3977267b8b812445d53063e0182fd891">Priority</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dfd735278d1730ed3cffdb755ede0d2">FloatMode</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e8df47424dd56e889739b63859838a">Priv</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f897a9290b5c279ed238deced93619">DX10Clamp</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318ee6169e857c53dd1dc7472a14cdb0">DebugMode</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab70748f1e7c51f2ea41b9057f5b4c829">IEEEMode</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac559e84953a041d04f27c9a1063a1c59">WgpMode</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af398e438530ebe1daa0614d7e7e799b8">MemOrdered</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d671c4238537a22dfe82266e71c16c">RrWgMode</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3752448069c8c6edb67b57e0ac92f85">ScratchSize</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d631fd6083ae4bbbee5024eb00867a">LDSBlocks</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403f09379ebb1045ef45a83925a0ed70">ScratchBlocks</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772aff37f042ff311ff9c8d3af5e3f5f">ScratchEnable</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59acec45cbd34d0a113b177c4b2ccbae">UserSGPR</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ed738417d64ca247cfdbfcf5165b07">TrapHandlerEnable</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab35b3af4fafc168fbce390b14d8d7c1d">TGIdXEnable</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee9920690b34cda0c1b7c6e1726f7bd0">TGIdYEnable</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337ffd0352d50d9047725b0bff184106">TGIdZEnable</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f34d529ea36932d1daad83cb0f8806">TGSizeEnable</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d9d692d70a3cefe821356b7bc77ae0e">TIdIGCompCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4aba4a78b1ad27400e6848896387b88">EXCPEnMSB</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3ecd7aff6a81fb011bc32cde4cde1b">LdsSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4121a9a2cc6c5455abb250cca03eb76c">EXCPEnable</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2726c754bff1649eb44f467f0e3b25c3">ComputePGMRSrc3GFX90A</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad1837db2b83530ed07c95b6bac0744b">NumVGPR</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e3860d5b04a57cde52d2bffad6138c">NumArchVGPR</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ea97b3ad31203bdf6769b105caa624">NumAccVGPR</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a57c3dc5eea14cd27e6db65d14bc32">AccumOffset</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad97de4ab417f94b2cdca16c80bbcfc62">TgSplit</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a030caf65eb1d46c0fc1045e197e0ed">NumSGPR</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095bee11d087163ba9b7edc3a55310f7">SGPRSpill</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02e81a66cc884be2f44db9572bf9d79">VGPRSpill</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf43be02eb6dd6450cf63b501f0f8f34">LDSSize</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a0d44841a613a758bdd61ccccd0d42">FlatUsed</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accfcf1299fb2b19aeba31bc533560e59">NumSGPRsForWavesPerEU</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ccab82d407519b9d648b03505332de">NumVGPRsForWavesPerEU</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc73b7fe494d43b1b5d5ee421823a28">Occupancy</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3a05260c49da2e5a9401472ca63d77">DynamicCallStack</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c703813acc50a1147c33ba50fe9bfb">VCCUsed</a> = nullptr</td>
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

<p>Track resource usage for kernels / entry functions.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIProgramInfo() {#a98c356d31810e2e705f15b1b3b058872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SIProgramInfo::SIProgramInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a4c73e82c5082e2f77d5647e1034eb81d">getComputePGMRSrc1</a>, <a href="#a318d26ac513db990b9466b1ce9380032">getComputePGMRSrc2</a>, <a href="#abe52a78f5c8a6b91ae15c4635ccf564e">getPGMRSrc1</a>, <a href="#a15f8b9a5641db8dcff762d1190a285dc">getPGMRSrc2</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getComputePGMRSrc1() {#a4c73e82c5082e2f77d5647e1034eb81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * SIProgramInfo::getComputePGMRSrc1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the value of the ComputePGMRsrc1 register.</p>

<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a6b303b433f43b901194dbf17adfb562c">llvm::MCBinaryExpr::createOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#af999327aaf208e1dcb5c3c60d6c2452c">MaskShift</a>, <a href="#aa590ea054ee40115a9612e345df72146">SGPRBlocks</a> and <a href="#a3688ae99640628e4a97f11753bcab0c9">VGPRBlocks</a>.</p>


<p>Referenced by <a href="#abe52a78f5c8a6b91ae15c4635ccf564e">getPGMRSrc1</a> and <a href="#a98c356d31810e2e705f15b1b3b058872">SIProgramInfo</a>.</p>

</div>
</div>

### getComputePGMRSrc2() {#a318d26ac513db990b9466b1ce9380032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * SIProgramInfo::getComputePGMRSrc2 (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the value of the ComputePGMRsrc2 register.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a6b303b433f43b901194dbf17adfb562c">llvm::MCBinaryExpr::createOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#a772aff37f042ff311ff9c8d3af5e3f5f">ScratchEnable</a>.</p>


<p>Referenced by <a href="#a15f8b9a5641db8dcff762d1190a285dc">getPGMRSrc2</a> and <a href="#a98c356d31810e2e705f15b1b3b058872">SIProgramInfo</a>.</p>

</div>
</div>

### getPGMRSrc1() {#abe52a78f5c8a6b91ae15c4635ccf564e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * SIProgramInfo::getPGMRSrc1 (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a6b303b433f43b901194dbf17adfb562c">llvm::MCBinaryExpr::createOr</a>, <a href="#a4c73e82c5082e2f77d5647e1034eb81d">getComputePGMRSrc1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5688c3d8cf734f824f2637b7bc91e2cb">llvm::AMDGPU::isCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#af999327aaf208e1dcb5c3c60d6c2452c">MaskShift</a>, <a href="#aa590ea054ee40115a9612e345df72146">SGPRBlocks</a> and <a href="#a3688ae99640628e4a97f11753bcab0c9">VGPRBlocks</a>.</p>


<p>Referenced by <a href="#a98c356d31810e2e705f15b1b3b058872">SIProgramInfo</a>.</p>

</div>
</div>

### getPGMRSrc2() {#a15f8b9a5641db8dcff762d1190a285dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * SIProgramInfo::getPGMRSrc2 (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="#a318d26ac513db990b9466b1ce9380032">getComputePGMRSrc2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5688c3d8cf734f824f2637b7bc91e2cb">llvm::AMDGPU::isCompute</a>.</p>


<p>Referenced by <a href="#a98c356d31810e2e705f15b1b3b058872">SIProgramInfo</a>.</p>

</div>
</div>

### reset() {#ae72726562d2c74f257bb14d331c90300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIProgramInfo::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="#a89a57c3dc5eea14cd27e6db65d14bc32">AccumOffset</a>, <a href="#a2726c754bff1649eb44f467f0e3b25c3">ComputePGMRSrc3GFX90A</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="#a318ee6169e857c53dd1dc7472a14cdb0">DebugMode</a>, <a href="#ab1f897a9290b5c279ed238deced93619">DX10Clamp</a>, <a href="#a9e3a05260c49da2e5a9401472ca63d77">DynamicCallStack</a>, <a href="#a4121a9a2cc6c5455abb250cca03eb76c">EXCPEnable</a>, <a href="#ae4aba4a78b1ad27400e6848896387b88">EXCPEnMSB</a>, <a href="#a70a0d44841a613a758bdd61ccccd0d42">FlatUsed</a>, <a href="#a5dfd735278d1730ed3cffdb755ede0d2">FloatMode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="#ab70748f1e7c51f2ea41b9057f5b4c829">IEEEMode</a>, <a href="#a34d631fd6083ae4bbbee5024eb00867a">LDSBlocks</a>, <a href="#abf43be02eb6dd6450cf63b501f0f8f34">LDSSize</a>, <a href="#a9e3ecd7aff6a81fb011bc32cde4cde1b">LdsSize</a>, <a href="#af398e438530ebe1daa0614d7e7e799b8">MemOrdered</a>, <a href="#a98ea97b3ad31203bdf6769b105caa624">NumAccVGPR</a>, <a href="#a27e3860d5b04a57cde52d2bffad6138c">NumArchVGPR</a>, <a href="#a0a030caf65eb1d46c0fc1045e197e0ed">NumSGPR</a>, <a href="#accfcf1299fb2b19aeba31bc533560e59">NumSGPRsForWavesPerEU</a>, <a href="#aad1837db2b83530ed07c95b6bac0744b">NumVGPR</a>, <a href="#aa8ccab82d407519b9d648b03505332de">NumVGPRsForWavesPerEU</a>, <a href="#abfc73b7fe494d43b1b5d5ee421823a28">Occupancy</a>, <a href="#a3977267b8b812445d53063e0182fd891">Priority</a>, <a href="#a02e8df47424dd56e889739b63859838a">Priv</a>, <a href="#a22d671c4238537a22dfe82266e71c16c">RrWgMode</a>, <a href="#a403f09379ebb1045ef45a83925a0ed70">ScratchBlocks</a>, <a href="#a772aff37f042ff311ff9c8d3af5e3f5f">ScratchEnable</a>, <a href="#ac3752448069c8c6edb67b57e0ac92f85">ScratchSize</a>, <a href="#aa590ea054ee40115a9612e345df72146">SGPRBlocks</a>, <a href="#a095bee11d087163ba9b7edc3a55310f7">SGPRSpill</a>, <a href="#ab35b3af4fafc168fbce390b14d8d7c1d">TGIdXEnable</a>, <a href="#aee9920690b34cda0c1b7c6e1726f7bd0">TGIdYEnable</a>, <a href="#a337ffd0352d50d9047725b0bff184106">TGIdZEnable</a>, <a href="#ad3f34d529ea36932d1daad83cb0f8806">TGSizeEnable</a>, <a href="#ad97de4ab417f94b2cdca16c80bbcfc62">TgSplit</a>, <a href="#a1d9d692d70a3cefe821356b7bc77ae0e">TIdIGCompCount</a>, <a href="#a71ed738417d64ca247cfdbfcf5165b07">TrapHandlerEnable</a>, <a href="#a59acec45cbd34d0a113b177c4b2ccbae">UserSGPR</a>, <a href="#a55c703813acc50a1147c33ba50fe9bfb">VCCUsed</a>, <a href="#a3688ae99640628e4a97f11753bcab0c9">VGPRBlocks</a>, <a href="#af02e81a66cc884be2f44db9572bf9d79">VGPRSpill</a> and <a href="#ac559e84953a041d04f27c9a1063a1c59">WgpMode</a>.</p>


<p>Referenced by <a href="#a98c356d31810e2e705f15b1b3b058872">SIProgramInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AccumOffset {#a89a57c3dc5eea14cd27e6db65d14bc32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::AccumOffset = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### ComputePGMRSrc3GFX90A {#a2726c754bff1649eb44f467f0e3b25c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::ComputePGMRSrc3GFX90A = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### DebugMode {#a318ee6169e857c53dd1dc7472a14cdb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::DebugMode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### DX10Clamp {#ab1f897a9290b5c279ed238deced93619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::DX10Clamp = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### DynamicCallStack {#a9e3a05260c49da2e5a9401472ca63d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::DynamicCallStack = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### EXCPEnable {#a4121a9a2cc6c5455abb250cca03eb76c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::EXCPEnable = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a34c7390935d69413b21319ee19d783db">EmitPALMetadataCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### EXCPEnMSB {#ae4aba4a78b1ad27400e6848896387b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::EXCPEnMSB = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### FlatUsed {#a70a0d44841a613a758bdd61ccccd0d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::FlatUsed = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### FloatMode {#a5dfd735278d1730ed3cffdb755ede0d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::FloatMode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### IEEEMode {#ab70748f1e7c51f2ea41b9057f5b4c829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::IEEEMode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a34c7390935d69413b21319ee19d783db">EmitPALMetadataCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### LDSBlocks {#a34d631fd6083ae4bbbee5024eb00867a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::LDSBlocks = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### LdsSize {#a9e3ecd7aff6a81fb011bc32cde4cde1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::LdsSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a34c7390935d69413b21319ee19d783db">EmitPALMetadataCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### LDSSize {#abf43be02eb6dd6450cf63b501f0f8f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::LDSSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### MemOrdered {#af398e438530ebe1daa0614d7e7e799b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::MemOrdered = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a34c7390935d69413b21319ee19d783db">EmitPALMetadataCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### NumAccVGPR {#a98ea97b3ad31203bdf6769b105caa624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::NumAccVGPR = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### NumArchVGPR {#a27e3860d5b04a57cde52d2bffad6138c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::NumArchVGPR = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### NumSGPR {#a0a030caf65eb1d46c0fc1045e197e0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::NumSGPR = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### NumSGPRsForWavesPerEU {#accfcf1299fb2b19aeba31bc533560e59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::NumSGPRsForWavesPerEU = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### NumVGPR {#aad1837db2b83530ed07c95b6bac0744b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::NumVGPR = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### NumVGPRsForWavesPerEU {#aa8ccab82d407519b9d648b03505332de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::NumVGPRsForWavesPerEU = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### Occupancy {#abfc73b7fe494d43b1b5d5ee421823a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::Occupancy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### Priority {#a3977267b8b812445d53063e0182fd891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::Priority = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### Priv {#a02e8df47424dd56e889739b63859838a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::Priv = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### RrWgMode {#a22d671c4238537a22dfe82266e71c16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::RrWgMode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### ScratchBlocks {#a403f09379ebb1045ef45a83925a0ed70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::ScratchBlocks = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### ScratchEnable {#a772aff37f042ff311ff9c8d3af5e3f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::ScratchEnable = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#a318d26ac513db990b9466b1ce9380032">getComputePGMRSrc2</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### ScratchSize {#ac3752448069c8c6edb67b57e0ac92f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::ScratchSize = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### SGPRBlocks {#aa590ea054ee40115a9612e345df72146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::SGPRBlocks = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#a4c73e82c5082e2f77d5647e1034eb81d">getComputePGMRSrc1</a>, <a href="#abe52a78f5c8a6b91ae15c4635ccf564e">getPGMRSrc1</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### SGPRSpill {#a095bee11d087163ba9b7edc3a55310f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIProgramInfo::SGPRSpill = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### TGIdXEnable {#ab35b3af4fafc168fbce390b14d8d7c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::TGIdXEnable = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### TGIdYEnable {#aee9920690b34cda0c1b7c6e1726f7bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::TGIdYEnable = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### TGIdZEnable {#a337ffd0352d50d9047725b0bff184106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::TGIdZEnable = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### TGSizeEnable {#ad3f34d529ea36932d1daad83cb0f8806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::TGSizeEnable = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### TgSplit {#ad97de4ab417f94b2cdca16c80bbcfc62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::TgSplit = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### TIdIGCompCount {#a1d9d692d70a3cefe821356b7bc77ae0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::TIdIGCompCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### TrapHandlerEnable {#a71ed738417d64ca247cfdbfcf5165b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::TrapHandlerEnable = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a34c7390935d69413b21319ee19d783db">EmitPALMetadataCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### UserSGPR {#a59acec45cbd34d0a113b177c4b2ccbae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::UserSGPR = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### VCCUsed {#a55c703813acc50a1147c33ba50fe9bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::VCCUsed = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### VGPRBlocks {#a3688ae99640628e4a97f11753bcab0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr* llvm::SIProgramInfo::VGPRBlocks = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#a4c73e82c5082e2f77d5647e1034eb81d">getComputePGMRSrc1</a>, <a href="#abe52a78f5c8a6b91ae15c4635ccf564e">getPGMRSrc1</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### VGPRSpill {#af02e81a66cc884be2f44db9572bf9d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SIProgramInfo::VGPRSpill = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

### WgpMode {#ac559e84953a041d04f27c9a1063a1c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIProgramInfo::WgpMode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a34c7390935d69413b21319ee19d783db">EmitPALMetadataCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a22f77187b94b2e4b729590a1f9a6ba51">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getHSAKernelProps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> and <a href="#ae72726562d2c74f257bb14d331c90300">reset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
