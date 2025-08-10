---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/palmd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `PALMD` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::PALMD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Key : uint32_t { <a href="#af892c75285b0f64d58ca76cb73059adf">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PAL metadata keys. <a href="#af892c75285b0f64d58ca76cb73059adf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb9ed110f803fda0c8dc1d3c9587f36">AssemblerDirective</a>[] = ".amd_amdgpu_pal_metadata"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PAL metadata (old linear format) assembler directive. <a href="#a1cb9ed110f803fda0c8dc1d3c9587f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed75550f1758e49da7beadad0ae54c7">AssemblerDirectiveBegin</a>[] = ".amdgpu_pal_metadata"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PAL metadata (new MsgPack format) beginning assembler directive. <a href="#a2ed75550f1758e49da7beadad0ae54c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af686707ee13e7427f9a298054f7b358a">AssemblerDirectiveEnd</a>[] = ".end_amdgpu_pal_metadata"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PAL metadata (new MsgPack format) ending assembler directive. <a href="#af686707ee13e7427f9a298054f7b358a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### Key {#af892c75285b0f64d58ca76cb73059adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::PALMD::Key : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PAL metadata keys.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_2E12_COMPUTE_PGM_RSRC1<a id="af892c75285b0f64d58ca76cb73059adfa47b5dd75a05ac951542e4b707b40f157"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2e12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_2D4A_SPI_SHADER_PGM_RSRC1_LS<a id="af892c75285b0f64d58ca76cb73059adfa34bd0b71f988311fcab297827be719e5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2d4a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_2D0A_SPI_SHADER_PGM_RSRC1_HS<a id="af892c75285b0f64d58ca76cb73059adfa42a587e0bf3890eddb269b3e706c7bc5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2d0a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_2CCA_SPI_SHADER_PGM_RSRC1_ES<a id="af892c75285b0f64d58ca76cb73059adfaecdb8c2efb203c2cd34039a83666e573"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2cca)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_2C8A_SPI_SHADER_PGM_RSRC1_GS<a id="af892c75285b0f64d58ca76cb73059adfabf9bf10a8944f18c5cff4158a3c9b7ae"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2c8a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_2C4A_SPI_SHADER_PGM_RSRC1_VS<a id="af892c75285b0f64d58ca76cb73059adfa3ccc5e169a3777e02f535f7d9571908f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2c4a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_2C0A_SPI_SHADER_PGM_RSRC1_PS<a id="af892c75285b0f64d58ca76cb73059adfaa669d5d787649ad8af3e7bed5e33638b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2c0a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_2E00_COMPUTE_DISPATCH_INITIATOR<a id="af892c75285b0f64d58ca76cb73059adfa4ae76377ba7eded90a5929319d13a308"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2e00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_A1B3_SPI_PS_INPUT_ENA<a id="af892c75285b0f64d58ca76cb73059adfa20d4442174a4473479a515e8875b6c38"></a></td>
<td class="doxyEnumItemDescription"> (= 0xa1b3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_A1B4_SPI_PS_INPUT_ADDR<a id="af892c75285b0f64d58ca76cb73059adfa7c8be07496801d83b597c6a4b0d5e8e5"></a></td>
<td class="doxyEnumItemDescription"> (= 0xa1b4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_A1B6_SPI_PS_IN_CONTROL<a id="af892c75285b0f64d58ca76cb73059adfa0e769b1d46ce1dfd5581cd8d9e6cd999"></a></td>
<td class="doxyEnumItemDescription"> (= 0xa1b6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">R_A2D5_VGT_SHADER_STAGES_EN<a id="af892c75285b0f64d58ca76cb73059adfa60d4d90dfa2502ea43fd8142fcf02d81"></a></td>
<td class="doxyEnumItemDescription"> (= 0xa2d5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LS_NUM_USED_VGPRS<a id="af892c75285b0f64d58ca76cb73059adfa204a29cc738548798cec57b848b78df3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000021)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HS_NUM_USED_VGPRS<a id="af892c75285b0f64d58ca76cb73059adfa1d5c38a62114a84fc18b1714d6a63675"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000022)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ES_NUM_USED_VGPRS<a id="af892c75285b0f64d58ca76cb73059adfad6630f54d95734f12ac9b07d580cb718"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000023)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GS_NUM_USED_VGPRS<a id="af892c75285b0f64d58ca76cb73059adfa83b02bd46c5db8151f270c8299f8fec3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000024)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VS_NUM_USED_VGPRS<a id="af892c75285b0f64d58ca76cb73059adfa59dd4aee3a964062e5cfdf3e4d838dbd"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000025)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PS_NUM_USED_VGPRS<a id="af892c75285b0f64d58ca76cb73059adfab22149611c6c910280848e1b17a71831"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000026)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CS_NUM_USED_VGPRS<a id="af892c75285b0f64d58ca76cb73059adfa425282f84ef39780de39d372fc20f763"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000027)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LS_NUM_USED_SGPRS<a id="af892c75285b0f64d58ca76cb73059adfa7927ef08fab277ac3ae280c42df65481"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000028)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HS_NUM_USED_SGPRS<a id="af892c75285b0f64d58ca76cb73059adfabf090b6055fe04aa545f72f7a1d85233"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000029)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ES_NUM_USED_SGPRS<a id="af892c75285b0f64d58ca76cb73059adfaa76129097eb2515b353f5beca08ae0b4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000002a)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GS_NUM_USED_SGPRS<a id="af892c75285b0f64d58ca76cb73059adfacea22a771ea15d322c55594ccb0c545e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000002b)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VS_NUM_USED_SGPRS<a id="af892c75285b0f64d58ca76cb73059adfaaa1122a4036f5367968666b48be3512e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000002c)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PS_NUM_USED_SGPRS<a id="af892c75285b0f64d58ca76cb73059adfaae61a3449a4a4e41a71852179b7a8db1"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000002d)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CS_NUM_USED_SGPRS<a id="af892c75285b0f64d58ca76cb73059adfa21f9ed798e67ae01819726307b9fb3fe"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000002e)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LS_SCRATCH_SIZE<a id="af892c75285b0f64d58ca76cb73059adfaf775622df54284a235a10735ad6720c9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000044)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HS_SCRATCH_SIZE<a id="af892c75285b0f64d58ca76cb73059adfa7e3f3ce46b233ee5b0fd59f5536f49ee"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000045)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ES_SCRATCH_SIZE<a id="af892c75285b0f64d58ca76cb73059adfa3e82516325e38bbd5dac65fc62555340"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000046)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GS_SCRATCH_SIZE<a id="af892c75285b0f64d58ca76cb73059adfa459720ca07965c4eab1c9034eec19baa"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000047)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VS_SCRATCH_SIZE<a id="af892c75285b0f64d58ca76cb73059adfaa877b99713f4c66fbceef23318070041"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000048)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PS_SCRATCH_SIZE<a id="af892c75285b0f64d58ca76cb73059adfa9f611faa24266ef71f697c5463309228"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10000049)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CS_SCRATCH_SIZE<a id="af892c75285b0f64d58ca76cb73059adfadc1dda00b52a85c10790420ea7fe9357"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000004a)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AssemblerDirective {#a1cb9ed110f803fda0c8dc1d3c9587f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::AMDGPU::PALMD::AssemblerDirective[] = ".amd_amdgpu_pal_metadata"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PAL metadata (old linear format) assembler directive.</p>

<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a52dd8abe6dc2354306df33d817dc3101">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::ParseDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af405cf94e28aca3f12c108ff0b858aee">llvm::AMDGPUPALMetadata::toString</a>.</p>

</div>
</div>

### AssemblerDirectiveBegin {#a2ed75550f1758e49da7beadad0ae54c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::AMDGPU::PALMD::AssemblerDirectiveBegin[] = ".amdgpu_pal_metadata"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PAL metadata (new MsgPack format) beginning assembler directive.</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a52dd8abe6dc2354306df33d817dc3101">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::ParseDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af405cf94e28aca3f12c108ff0b858aee">llvm::AMDGPUPALMetadata::toString</a>.</p>

</div>
</div>

### AssemblerDirectiveEnd {#af686707ee13e7427f9a298054f7b358a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::AMDGPU::PALMD::AssemblerDirectiveEnd[] = ".end_amdgpu_pal_metadata"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PAL metadata (new MsgPack format) ending assembler directive.</p>

<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#af405cf94e28aca3f12c108ff0b858aee">llvm::AMDGPUPALMetadata::toString</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpumetadata-h">AMDGPUMetadata.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
