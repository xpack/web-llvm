---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/hwreg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `Hwreg` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::Hwreg { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/hwreg/hwregsize">HwregSize</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29c0bb06c39f5e6d116476d03a102b8">HwregId</a> = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfield">EncodingField</a>&lt; 5, 0 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d4abfb17ba753fee8d67043c7b8c206">HwregOffset</a> = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfield">EncodingField</a>&lt; 10, 6 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbe2d3fed04c19c62f14f5a559698f0">HwregEncoding</a> = <a href="/web-llvm/docs/api/structs/llvm/amdgpu/encodingfields">EncodingFields</a>&lt; <a href="#ac29c0bb06c39f5e6d116476d03a102b8">HwregId</a>, <a href="#a6d4abfb17ba753fee8d67043c7b8c206">HwregOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/hwreg/hwregsize">HwregSize</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Id { <a href="#a018924463515df5f66f3c5a039750da8">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Offset : unsigned { <a href="#a6110fc30bc7311a6cf99814530362e21">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ModeRegisterMasks : uint32_t { <a href="#ae232cf241cf407f0ed06634494dba2e8">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1239c572a3a6f1217bdd41ef597c56a">getHwregId</a> (StringRef Name, const MCSubtargetInfo &amp;STI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1adafb91ec70799ab3384542bb6f0a92">getHwreg</a> (uint64_t Encoding, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/amdgpu/customoperand">CustomOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d2fac8ce8e9f1d3469d6416cca183b">Operands</a>[]</td>
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

## Typedefs

### HwregEncoding {#afcbe2d3fed04c19c62f14f5a559698f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AMDGPU::Hwreg::HwregEncoding =  EncodingFields&lt;HwregId, HwregOffset, HwregSize&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

### HwregId {#ac29c0bb06c39f5e6d116476d03a102b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AMDGPU::Hwreg::HwregId =  EncodingField&lt;5, 0&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

### HwregOffset {#a6d4abfb17ba753fee8d67043c7b8c206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AMDGPU::Hwreg::HwregOffset =  EncodingField&lt;10, 6&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Id {#a018924463515df5f66f3c5a039750da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::Hwreg::Id </td>
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
<td class="doxyEnumItemName">ID_MODE<a id="a018924463515df5f66f3c5a039750da8aebfc48ed48afe18e84417d0de513b6bb"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_STATUS<a id="a018924463515df5f66f3c5a039750da8a814cd773000e4ba3bd1e9bcbb71bd4e9"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_TRAPSTS<a id="a018924463515df5f66f3c5a039750da8a12601e1f7c9c510e01f7a019d3d249b9"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_HW_ID<a id="a018924463515df5f66f3c5a039750da8ab8a095e28868e821efd524ee3466802e"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_GPR_ALLOC<a id="a018924463515df5f66f3c5a039750da8a2a53b7ed799f909454dbd49f508e5849"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_LDS_ALLOC<a id="a018924463515df5f66f3c5a039750da8a3751af73bf71f400d3df87c11cf5080a"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_IB_STS<a id="a018924463515df5f66f3c5a039750da8a15f7a7d91c92c18838905e73145d3a30"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_PERF_SNAPSHOT_DATA_gfx12<a id="a018924463515df5f66f3c5a039750da8a753fbb85942e51349e398585016b2c2a"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_PERF_SNAPSHOT_PC_LO_gfx12<a id="a018924463515df5f66f3c5a039750da8a6abd0cce80946d0a2b4ddf4bccd95ae4"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_PERF_SNAPSHOT_PC_HI_gfx12<a id="a018924463515df5f66f3c5a039750da8a9d63f82b2028a0395523a7259063d7cd"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_MEM_BASES<a id="a018924463515df5f66f3c5a039750da8ae2d2ec42fd2de0e4c99b4c3c9cbbd04b"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_TBA_LO<a id="a018924463515df5f66f3c5a039750da8a39d048309e86fa839e031126c3ad007a"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_TBA_HI<a id="a018924463515df5f66f3c5a039750da8a4c38c9a3b504ae3bd7c73875bf3c089f"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_TMA_LO<a id="a018924463515df5f66f3c5a039750da8a28edffd87e7a3edb197d998340d32778"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_TMA_HI<a id="a018924463515df5f66f3c5a039750da8a74d30fdfde793ffadcc7b2cda9495c53"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_FLAT_SCR_LO<a id="a018924463515df5f66f3c5a039750da8a9ca9cd82114aa167d099f725f52fe872"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_FLAT_SCR_HI<a id="a018924463515df5f66f3c5a039750da8ac1cdbd3a45dbc76f966e87d8985e3f28"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_XNACK_MASK<a id="a018924463515df5f66f3c5a039750da8a6aaf7f2c8ebb5aff361aa54382f7ac4a"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_HW_ID1<a id="a018924463515df5f66f3c5a039750da8af1596e4452d04cf32d920577fd2561a3"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_HW_ID2<a id="a018924463515df5f66f3c5a039750da8af3e4fa5dbc9aef8c677766a34a873e3a"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_POPS_PACKER<a id="a018924463515df5f66f3c5a039750da8ac62d1b06629396f25ff283b338304f6f"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_PERF_SNAPSHOT_DATA_gfx11<a id="a018924463515df5f66f3c5a039750da8a83b4e7e8583940604268327bbd1ee816"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SHADER_CYCLES<a id="a018924463515df5f66f3c5a039750da8af27e718d6789499c01908ebae080dcc5"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SHADER_CYCLES_HI<a id="a018924463515df5f66f3c5a039750da8a429e5dec4b13503ee5a1b6346c5a0321"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_DVGPR_ALLOC_LO<a id="a018924463515df5f66f3c5a039750da8a5e2054cac81fdbd792b905c6e1336f4e"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_DVGPR_ALLOC_HI<a id="a018924463515df5f66f3c5a039750da8aa52dbb2d514b506fc8413d3d6692a962"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_PERF_SNAPSHOT_PC_LO_gfx11<a id="a018924463515df5f66f3c5a039750da8a21117ff0416f9a53520ed7eb47bb7e71"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_PERF_SNAPSHOT_PC_HI_gfx11<a id="a018924463515df5f66f3c5a039750da8a16c869698fe9f46e504ddc4d6295abe2"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_STATE_PRIV<a id="a018924463515df5f66f3c5a039750da8ac6a9dd0f8ec70df45bee29446b7099d9"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_PERF_SNAPSHOT_DATA1<a id="a018924463515df5f66f3c5a039750da8af41be9adb05aafd75002307aac0f1283"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_PERF_SNAPSHOT_DATA2<a id="a018924463515df5f66f3c5a039750da8aedd888478933d8eb4621c67693028fb1"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_EXCP_FLAG_PRIV<a id="a018924463515df5f66f3c5a039750da8a1d26080d4a071789cd08d5122614c8e0"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_EXCP_FLAG_USER<a id="a018924463515df5f66f3c5a039750da8a43a480d4d338ab078448b118f0d56b89"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_TRAP_CTRL<a id="a018924463515df5f66f3c5a039750da8a5e9102540fdb52c93f7b228df5365a91"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_XCC_ID<a id="a018924463515df5f66f3c5a039750da8a4d097a0b752490bdeab72e504d851a8c"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SQ_PERF_SNAPSHOT_DATA<a id="a018924463515df5f66f3c5a039750da8a54757e26d2872c72da53fff167de309b"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SQ_PERF_SNAPSHOT_DATA1<a id="a018924463515df5f66f3c5a039750da8a4035310462066ece815a61874a26a91d"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SQ_PERF_SNAPSHOT_PC_LO<a id="a018924463515df5f66f3c5a039750da8a3d88524aa1bf4311507232fd236d9be6"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SQ_PERF_SNAPSHOT_PC_HI<a id="a018924463515df5f66f3c5a039750da8ac7e1f230307278cff4933210bc07df44"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### ModeRegisterMasks {#ae232cf241cf407f0ed06634494dba2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::Hwreg::ModeRegisterMasks : uint32_t</td>
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
<td class="doxyEnumItemName">FP_ROUND_MASK<a id="ae232cf241cf407f0ed06634494dba2e8ae1dd8b5019d16c7b9249d4962d8a1837"></a></td>
<td class="doxyEnumItemDescription"> (= 0xf &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FP_DENORM_MASK<a id="ae232cf241cf407f0ed06634494dba2e8ad93e6c9077b03c6315a0917bf12847c7"></a></td>
<td class="doxyEnumItemDescription"> (= 0xf &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DX10_CLAMP_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a75dcf0660bc5f1739a309aac83c2cfa4"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IEEE_MODE_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a72f76798b60cb8a15c5d21d91069e503"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOD_CLAMP_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a468971412bef52e82138916c740a5716"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DEBUG_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a59ac18a7658d872ce52251fefd6147fc"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXCP_EN_INVALID_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a7b0e490cbf5bd826fd49ce43e0d7a614"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXCP_EN_INPUT_DENORMAL_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a867a4682d3b79a947daec559d82fb2e2"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXCP_EN_FLOAT_DIV0_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a2c1d983ccfb883de8fbf898488fc2824"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXCP_EN_OVERFLOW_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a903b60e230b64cf78fae1a7034a33900"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXCP_EN_UNDERFLOW_MASK<a id="ae232cf241cf407f0ed06634494dba2e8ac033781d0acb6ce8df1b57aa92ee58ed"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXCP_EN_INEXACT_MASK<a id="ae232cf241cf407f0ed06634494dba2e8adbfe1b9ad5efdeb8cf7d0026b410b244"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXCP_EN_INT_DIV0_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a052dc72ece22a760bb7a4ac8cadb3240"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GPR_IDX_EN_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a40bd4e8079aea46d4e58955739486220"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSKIP_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a359be52cd5a0dbc03ac9c7ab3d1dfb94"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSP_MASK<a id="ae232cf241cf407f0ed06634494dba2e8a49d447f6e2a2ee37f15bebb4a11ff2fd"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7u &lt;&lt; 29)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### Offset {#a6110fc30bc7311a6cf99814530362e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::Hwreg::Offset : unsigned</td>
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
<td class="doxyEnumItemName">OFFSET_MEM_VIOL<a id="a6110fc30bc7311a6cf99814530362e21a5f5ea4d21be21db24860fadecde0fce1"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getHwreg() {#a1adafb91ec70799ab3384542bb6f0a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::AMDGPU::Hwreg::getHwreg (uint64_t Encoding, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a89e90b3784550781a7cb87657a8b417f">llvm::AMDGPU::getNameFromOperandTable</a> and <a href="#ae3d2fac8ce8e9f1d3469d6416cca183b">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a7306dff221a5075d2166c3cf6b740b35">llvm::AMDGPUInstPrinter::printHwreg</a>.</p>

</div>
</div>

### getHwregId() {#ac1239c572a3a6f1217bdd41ef597c56a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::AMDGPU::Hwreg::getHwregId (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2ee72f856a2116efe64cf999f14f277d">llvm::AMDGPU::getEncodingFromOperandTable</a> and <a href="#ae3d2fac8ce8e9f1d3469d6416cca183b">Operands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Operands {#ae3d2fac8ce8e9f1d3469d6416cca183b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CustomOperand llvm::AMDGPU::Hwreg::Operands[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a1adafb91ec70799ab3384542bb6f0a92">getHwreg</a> and <a href="#ac1239c572a3a6f1217bdd41ef597c56a">getHwregId</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">AMDGPUBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
