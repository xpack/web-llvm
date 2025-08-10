---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AMDGPUPALMetadata.cpp` File

<p>This class has methods called by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter">AMDGPUAsmPrinter</a> to accumulate and print the PAL metadata. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-h">AMDGPUPALMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuptnote-h">AMDGPUPTNote.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">llvm/Support/AMDGPUMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68759c6954b5a8ed6ca3563cc13148b1">getRsrc1Reg</a> (CallingConv::ID CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10741674b01fc9ce52c7e9fdbbd98f5a">getScratchSizeKey</a> (CallingConv::ID CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d83a826390ace8634bc2530b52cdf1e">getRegisterName</a> (unsigned RegNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed95a9ae53612706e69e2f63a25b90d0">getStageName</a> (CallingConv::ID CC)</td>
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

<p>This class has methods called by <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter">AMDGPUAsmPrinter</a> to accumulate and print the PAL metadata.</p>

<div class="doxySectionDef">

## Functions

### getRegisterName() {#a8d83a826390ace8634bc2530b52cdf1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getRegisterName (unsigned RegNum)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaa669d5d787649ad8af3e7bed5e33638b">llvm::AMDGPU::PALMD::R_2C0A_SPI_SHADER_PGM_RSRC1_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa3ccc5e169a3777e02f535f7d9571908f">llvm::AMDGPU::PALMD::R_2C4A_SPI_SHADER_PGM_RSRC1_VS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfabf9bf10a8944f18c5cff4158a3c9b7ae">llvm::AMDGPU::PALMD::R_2C8A_SPI_SHADER_PGM_RSRC1_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaecdb8c2efb203c2cd34039a83666e573">llvm::AMDGPU::PALMD::R_2CCA_SPI_SHADER_PGM_RSRC1_ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa42a587e0bf3890eddb269b3e706c7bc5">llvm::AMDGPU::PALMD::R_2D0A_SPI_SHADER_PGM_RSRC1_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa34bd0b71f988311fcab297827be719e5">llvm::AMDGPU::PALMD::R_2D4A_SPI_SHADER_PGM_RSRC1_LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa4ae76377ba7eded90a5929319d13a308">llvm::AMDGPU::PALMD::R_2E00_COMPUTE_DISPATCH_INITIATOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa47b5dd75a05ac951542e4b707b40f157">llvm::AMDGPU::PALMD::R_2E12_COMPUTE_PGM_RSRC1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa20d4442174a4473479a515e8875b6c38">llvm::AMDGPU::PALMD::R_A1B3_SPI_PS_INPUT_ENA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa7c8be07496801d83b597c6a4b0d5e8e5">llvm::AMDGPU::PALMD::R_A1B4_SPI_PS_INPUT_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa0e769b1d46ce1dfd5581cd8d9e6cd999">llvm::AMDGPU::PALMD::R_A1B6_SPI_PS_IN_CONTROL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa60d4d90dfa2502ea43fd8142fcf02d81">llvm::AMDGPU::PALMD::R_A2D5_VGT_SHADER_STAGES_EN</a>.</p>

</div>
</div>

### getRsrc1Reg() {#a68759c6954b5a8ed6ca3563cc13148b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getRsrc1Reg (CallingConv::ID CC)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad61318e853e529ac703f52a853efa1d1">llvm::CallingConv::AMDGPU_ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6f08d1631b96043fe0201973d84e5539">llvm::CallingConv::AMDGPU_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca5c0f66e45afd7c51f4ee51552d8fb606">llvm::CallingConv::AMDGPU_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf2c5be679d7769a9f3e5e308f73a9ff8">llvm::CallingConv::AMDGPU_LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca91283117ce67ebdae50cc7730694d8f8">llvm::CallingConv::AMDGPU_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaa669d5d787649ad8af3e7bed5e33638b">llvm::AMDGPU::PALMD::R_2C0A_SPI_SHADER_PGM_RSRC1_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa3ccc5e169a3777e02f535f7d9571908f">llvm::AMDGPU::PALMD::R_2C4A_SPI_SHADER_PGM_RSRC1_VS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfabf9bf10a8944f18c5cff4158a3c9b7ae">llvm::AMDGPU::PALMD::R_2C8A_SPI_SHADER_PGM_RSRC1_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaecdb8c2efb203c2cd34039a83666e573">llvm::AMDGPU::PALMD::R_2CCA_SPI_SHADER_PGM_RSRC1_ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa42a587e0bf3890eddb269b3e706c7bc5">llvm::AMDGPU::PALMD::R_2D0A_SPI_SHADER_PGM_RSRC1_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa34bd0b71f988311fcab297827be719e5">llvm::AMDGPU::PALMD::R_2D4A_SPI_SHADER_PGM_RSRC1_LS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa47b5dd75a05ac951542e4b707b40f157">llvm::AMDGPU::PALMD::R_2E12_COMPUTE_PGM_RSRC1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#ad6a39843c47442c7dd6e7451a2fbc47f">llvm::AMDGPUPALMetadata::setRsrc1</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#aa00b11d53bda23b5ae530c39378258f4">llvm::AMDGPUPALMetadata::setRsrc1</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a57137a7715a5daeb569a1f420cb81555">llvm::AMDGPUPALMetadata::setRsrc2</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#afafff19dbfe21b91be73d6b391e0ac88">llvm::AMDGPUPALMetadata::setRsrc2</a>.</p>

</div>
</div>

### getScratchSizeKey() {#a10741674b01fc9ce52c7e9fdbbd98f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getScratchSizeKey (CallingConv::ID CC)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad61318e853e529ac703f52a853efa1d1">llvm::CallingConv::AMDGPU_ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6f08d1631b96043fe0201973d84e5539">llvm::CallingConv::AMDGPU_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca5c0f66e45afd7c51f4ee51552d8fb606">llvm::CallingConv::AMDGPU_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf2c5be679d7769a9f3e5e308f73a9ff8">llvm::CallingConv::AMDGPU_LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca91283117ce67ebdae50cc7730694d8f8">llvm::CallingConv::AMDGPU_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfadc1dda00b52a85c10790420ea7fe9357">llvm::AMDGPU::PALMD::CS_SCRATCH_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa3e82516325e38bbd5dac65fc62555340">llvm::AMDGPU::PALMD::ES_SCRATCH_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa459720ca07965c4eab1c9034eec19baa">llvm::AMDGPU::PALMD::GS_SCRATCH_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa7e3f3ce46b233ee5b0fd59f5536f49ee">llvm::AMDGPU::PALMD::HS_SCRATCH_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaf775622df54284a235a10735ad6720c9">llvm::AMDGPU::PALMD::LS_SCRATCH_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfa9f611faa24266ef71f697c5463309228">llvm::AMDGPU::PALMD::PS_SCRATCH_SIZE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/palmd/#af892c75285b0f64d58ca76cb73059adfaa877b99713f4c66fbceef23318070041">llvm::AMDGPU::PALMD::VS_SCRATCH_SIZE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a4f41beaf9dd48255b076cd4219a26430">llvm::AMDGPUPALMetadata::setNumUsedSgprs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#afc6cf8c77ed58e349541abd675c3aebe">llvm::AMDGPUPALMetadata::setNumUsedSgprs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#aa2a997da932e61fd728685fcc9e78d1e">llvm::AMDGPUPALMetadata::setNumUsedVgprs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a4ab960dcfb8dbb02f9ee3712e9cd4fdd">llvm::AMDGPUPALMetadata::setNumUsedVgprs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af8554373c20f9a9f2d8a4946ba983729">llvm::AMDGPUPALMetadata::setScratchSize</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a91fb6e5a8cd6fbae08887418de54c6dc">llvm::AMDGPUPALMetadata::setScratchSize</a>.</p>

</div>
</div>

### getStageName() {#aed95a9ae53612706e69e2f63a25b90d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getStageName (CallingConv::ID CC)</td>
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



<p>Definition at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpupalmetadata-cpp">AMDGPUPALMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad61318e853e529ac703f52a853efa1d1">llvm::CallingConv::AMDGPU_ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f9824c54cfd32b3e38c01d5331f318b">llvm::CallingConv::AMDGPU_Gfx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6f08d1631b96043fe0201973d84e5539">llvm::CallingConv::AMDGPU_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca5c0f66e45afd7c51f4ee51552d8fb606">llvm::CallingConv::AMDGPU_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf2c5be679d7769a9f3e5e308f73a9ff8">llvm::CallingConv::AMDGPU_LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca91283117ce67ebdae50cc7730694d8f8">llvm::CallingConv::AMDGPU_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
