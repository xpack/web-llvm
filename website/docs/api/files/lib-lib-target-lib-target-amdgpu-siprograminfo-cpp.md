---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SIProgramInfo.cpp` File

<p>The <a href="/web-llvm/docs/api/structs/llvm/siprograminfo">SIProgramInfo</a> tracks resource usage and hardware flags for kernels and entry functions. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-h">SIProgramInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Utils/AMDGPUBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a> (const SIProgramInfo &amp;ProgInfo, const GCNSubtarget &amp;ST)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a> (const SIProgramInfo &amp;ProgInfo, CallingConv::ID CC, const GCNSubtarget &amp;ST)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a> (const SIProgramInfo &amp;ProgInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af999327aaf208e1dcb5c3c60d6c2452c">MaskShift</a> (const MCExpr *Val, uint32_t Mask, uint32_t Shift, MCContext &amp;Ctx)</td>
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

<p>The <a href="/web-llvm/docs/api/structs/llvm/siprograminfo">SIProgramInfo</a> tracks resource usage and hardware flags for kernels and entry functions.</p>

<div class="doxySectionDef">

## Functions

### getComputePGMRSrc1Reg() {#ac6fc5bd19383b302adec32a29dfc5be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getComputePGMRSrc1Reg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/siprograminfo">SIProgramInfo</a> &amp; ProgInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a318ee6169e857c53dd1dc7472a14cdb0">llvm::SIProgramInfo::DebugMode</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ab1f897a9290b5c279ed238deced93619">llvm::SIProgramInfo::DX10Clamp</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a5dfd735278d1730ed3cffdb755ede0d2">llvm::SIProgramInfo::FloatMode</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ab70748f1e7c51f2ea41b9057f5b4c829">llvm::SIProgramInfo::IEEEMode</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#af398e438530ebe1daa0614d7e7e799b8">llvm::SIProgramInfo::MemOrdered</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a3977267b8b812445d53063e0182fd891">llvm::SIProgramInfo::Priority</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a02e8df47424dd56e889739b63859838a">llvm::SIProgramInfo::Priv</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a22d671c4238537a22dfe82266e71c16c">llvm::SIProgramInfo::RrWgMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a753e18af437042ff34b2f182be50a838">S_00B848_DEBUG_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#acbb30ea10770fc01c162625968e545bd">S_00B848_DX10_CLAMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#af5f71d8ec86ce3be8722a15c2d5d9f93">S_00B848_FLOAT_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ae2684a5724ae2c9738411ef51dec8373">S_00B848_IEEE_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a4ab7b070d55d46145ded8ccdd0cd5db5">S_00B848_MEM_ORDERED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#add53b53cdd8870abfaeb28b29e397d13">S_00B848_PRIORITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a7f2ac7de878c5b5a76540ef9720a6984">S_00B848_PRIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a5c1ffc09a261988d7e26a19fedb27f18">S_00B848_RR_WG_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ac3678dc8908060a15fa8b872ec67cf09">S_00B848_WGP_MODE</a> and <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ac559e84953a041d04f27c9a1063a1c59">llvm::SIProgramInfo::WgpMode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a4c73e82c5082e2f77d5647e1034eb81d">llvm::SIProgramInfo::getComputePGMRSrc1</a>.</p>

</div>
</div>

### getComputePGMRSrc2Reg() {#a0a8ec285561c2428cdcd450331e5aca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getComputePGMRSrc2Reg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/siprograminfo">SIProgramInfo</a> &amp; ProgInfo)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a4121a9a2cc6c5455abb250cca03eb76c">llvm::SIProgramInfo::EXCPEnable</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ae4aba4a78b1ad27400e6848896387b88">llvm::SIProgramInfo::EXCPEnMSB</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a9e3ecd7aff6a81fb011bc32cde4cde1b">llvm::SIProgramInfo::LdsSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a08dabd310008611a3b7bdfc25e2f0024">S_00B84C_EXCP_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#aca087bdb87f73f738c447ddb35113750">S_00B84C_EXCP_EN_MSB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a94057ab16d8ffe2cc375c043d2f8ac71">S_00B84C_LDS_SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a7f899f3398694cba8a77c2fa9a2eec23">S_00B84C_TG_SIZE_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a6cdd30a73244b929b291741ca7418f3a">S_00B84C_TGID_X_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#aad4aa25ffce1f6b2f3ab0687a278a2ca">S_00B84C_TGID_Y_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a1b3aecf9ee6c197d3f55f628513fd6cc">S_00B84C_TGID_Z_EN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a839fb95cbee310bf346610f8798a8d0e">S_00B84C_TIDIG_COMP_CNT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a9e98ce60ac6e6bfe7cefb284cfe69777">S_00B84C_TRAP_HANDLER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a9850b7225811ed88fce361146fb3f1bc">S_00B84C_USER_SGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ab35b3af4fafc168fbce390b14d8d7c1d">llvm::SIProgramInfo::TGIdXEnable</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#aee9920690b34cda0c1b7c6e1726f7bd0">llvm::SIProgramInfo::TGIdYEnable</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a337ffd0352d50d9047725b0bff184106">llvm::SIProgramInfo::TGIdZEnable</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ad3f34d529ea36932d1daad83cb0f8806">llvm::SIProgramInfo::TGSizeEnable</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a1d9d692d70a3cefe821356b7bc77ae0e">llvm::SIProgramInfo::TIdIGCompCount</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a71ed738417d64ca247cfdbfcf5165b07">llvm::SIProgramInfo::TrapHandlerEnable</a> and <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a59acec45cbd34d0a113b177c4b2ccbae">llvm::SIProgramInfo::UserSGPR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a318d26ac513db990b9466b1ce9380032">llvm::SIProgramInfo::getComputePGMRSrc2</a>.</p>

</div>
</div>

### getPGMRSrc1Reg() {#a10b96dfed259151764cb09bce829818a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getPGMRSrc1Reg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/siprograminfo">SIProgramInfo</a> &amp; ProgInfo, CallingConv::ID CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6f08d1631b96043fe0201973d84e5539">llvm::CallingConv::AMDGPU_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca5c0f66e45afd7c51f4ee51552d8fb606">llvm::CallingConv::AMDGPU_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca91283117ce67ebdae50cc7730694d8f8">llvm::CallingConv::AMDGPU_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a318ee6169e857c53dd1dc7472a14cdb0">llvm::SIProgramInfo::DebugMode</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ab1f897a9290b5c279ed238deced93619">llvm::SIProgramInfo::DX10Clamp</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a5dfd735278d1730ed3cffdb755ede0d2">llvm::SIProgramInfo::FloatMode</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ab70748f1e7c51f2ea41b9057f5b4c829">llvm::SIProgramInfo::IEEEMode</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#af398e438530ebe1daa0614d7e7e799b8">llvm::SIProgramInfo::MemOrdered</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a3977267b8b812445d53063e0182fd891">llvm::SIProgramInfo::Priority</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a02e8df47424dd56e889739b63859838a">llvm::SIProgramInfo::Priv</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a22d671c4238537a22dfe82266e71c16c">llvm::SIProgramInfo::RrWgMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a1930b8f62e101a99c1a43f941bdf33d3">S_00B028_MEM_ORDERED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ab513c7765a36b59d286261097d8f48de">S_00B128_MEM_ORDERED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a4eac162ce066122ef62521b9d4039e26">S_00B228_MEM_ORDERED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a33bc1a6b0012bfe8b96c03a4f7de759b">S_00B228_WGP_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a1190b275cd1fa4304697d22a8f95e6fc">S_00B428_MEM_ORDERED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a7b0776941c2d49e4a3bb14a709dfab56">S_00B428_WGP_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a753e18af437042ff34b2f182be50a838">S_00B848_DEBUG_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#acbb30ea10770fc01c162625968e545bd">S_00B848_DX10_CLAMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#af5f71d8ec86ce3be8722a15c2d5d9f93">S_00B848_FLOAT_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ae2684a5724ae2c9738411ef51dec8373">S_00B848_IEEE_MODE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#add53b53cdd8870abfaeb28b29e397d13">S_00B848_PRIORITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a7f2ac7de878c5b5a76540ef9720a6984">S_00B848_PRIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a5c1ffc09a261988d7e26a19fedb27f18">S_00B848_RR_WG_MODE</a> and <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#ac559e84953a041d04f27c9a1063a1c59">llvm::SIProgramInfo::WgpMode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#abe52a78f5c8a6b91ae15c4635ccf564e">llvm::SIProgramInfo::getPGMRSrc1</a>.</p>

</div>
</div>

### MaskShift() {#af999327aaf208e1dcb5c3c60d6c2452c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * MaskShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, uint32_t Mask, uint32_t Shift, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp">SIProgramInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a37d8557c5bc9e9a92ce9b663e21f5e47">llvm::MCBinaryExpr::createAnd</a> and <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#ac3fa97ac31d48ef7708ba959db34f38d">llvm::MCBinaryExpr::createShl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#a4c73e82c5082e2f77d5647e1034eb81d">llvm::SIProgramInfo::getComputePGMRSrc1</a>, <a href="/web-llvm/docs/api/structs/llvm/siprograminfo/#abe52a78f5c8a6b91ae15c4635ccf564e">llvm::SIProgramInfo::getPGMRSrc1</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a165830656f5ebd0521d278a2cf583a28">tryToRecognizePopCount</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
