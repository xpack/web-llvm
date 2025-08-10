---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/exp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `Exp` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::Exp { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/amdgpu/exp/exptgt">ExpTgt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Target : unsigned { <a href="#af7592dc94276d1958420bcfb414b6998">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fcd9e7a60a23a941500f531dcc0379">getTgtName</a> (unsigned Id, StringRef &amp;Name, int &amp;Index)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac236558198da971873e571fa38d2b58a">getTgtId</a> (const StringRef Name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19cafb2b98160d416f6b684843fc4989">isSupportedTgtId</a> (unsigned Id, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/amdgpu/exp/exptgt">ExpTgt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a333540371328c116d4991e147b390949">ExpTgtInfo</a>[] = ...</td>
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

## Enumerations

### Target {#af7592dc94276d1958420bcfb414b6998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::Exp::Target : unsigned</td>
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
<td class="doxyEnumItemName">ET_MRT0<a id="af7592dc94276d1958420bcfb414b6998a45d5e746d6f7b53f0baf217b6c60daca"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_MRT7<a id="af7592dc94276d1958420bcfb414b6998a014717c3e0b4b0fa9168435d5c00209b"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_MRTZ<a id="af7592dc94276d1958420bcfb414b6998ab7925f1cbfe3c4fc5464da6219815d2c"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_NULL<a id="af7592dc94276d1958420bcfb414b6998a2f4f450132c7f1a5a8773ebd3fbc8e38"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_POS0<a id="af7592dc94276d1958420bcfb414b6998a819e373068289857bb1cef7f5b320c11"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_POS3<a id="af7592dc94276d1958420bcfb414b6998acbd1871d5025938eb11be563c08e6517"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_POS4<a id="af7592dc94276d1958420bcfb414b6998a7120ea14ee1a2b75be3fcbbcf2cd238a"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_POS_LAST<a id="af7592dc94276d1958420bcfb414b6998ac84234e8abdfe7d1a85fef7297734e49"></a></td>
<td class="doxyEnumItemDescription"> (= ET_POS4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_PRIM<a id="af7592dc94276d1958420bcfb414b6998a5bf174e4118cb43e895fda34b8cbdb51"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_DUAL_SRC_BLEND0<a id="af7592dc94276d1958420bcfb414b6998a8c000dbdd84cae416e103d023ca4f3bc"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_DUAL_SRC_BLEND1<a id="af7592dc94276d1958420bcfb414b6998a46aec9d69fc2301884b99597f4090df5"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_PARAM0<a id="af7592dc94276d1958420bcfb414b6998afe9e14fadada855231c900eecbea27f2"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_PARAM31<a id="af7592dc94276d1958420bcfb414b6998a6a774a598f798bc6a057d9a88a1427c0"></a></td>
<td class="doxyEnumItemDescription"> (= 63)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_NULL_MAX_IDX<a id="af7592dc94276d1958420bcfb414b6998ad54e3354f0aba668bbc7e074f1b6ed18"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_MRTZ_MAX_IDX<a id="af7592dc94276d1958420bcfb414b6998aa8c987d72b2b9bfebb87da0cc8333e54"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_PRIM_MAX_IDX<a id="af7592dc94276d1958420bcfb414b6998a3f125b615f9ce5c35545c3be2a0bdc01"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_MRT_MAX_IDX<a id="af7592dc94276d1958420bcfb414b6998a7c0a3c890504a43343b5104f8c8fa576"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_POS_MAX_IDX<a id="af7592dc94276d1958420bcfb414b6998ae29f0a5af13d540be374ed945bda9e92"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_DUAL_SRC_BLEND_MAX_IDX<a id="af7592dc94276d1958420bcfb414b6998a12be7bab3abcb1b9646c4168aebbf033"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_PARAM_MAX_IDX<a id="af7592dc94276d1958420bcfb414b6998a2b937886b062f2746a310334f52c6179"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ET_INVALID<a id="af7592dc94276d1958420bcfb414b6998a4b89c8394d5ab3580d6d73e057d3bbb9"></a></td>
<td class="doxyEnumItemDescription"> (= 255)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getTgtId() {#ac236558198da971873e571fa38d2b58a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READONLY unsigned llvm::AMDGPU::Exp::getTgtId (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#af7592dc94276d1958420bcfb414b6998a4b89c8394d5ab3580d6d73e057d3bbb9">ET_INVALID</a>, <a href="#a333540371328c116d4991e147b390949">ExpTgtInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a26a8456ca91f0f85ed2f854837b0dc29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseExpTgt</a>.</p>

</div>
</div>

### getTgtName() {#ab0fcd9e7a60a23a941500f531dcc0379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::Exp::getTgtName (unsigned Id, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name, int &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Reference <a href="#a333540371328c116d4991e147b390949">ExpTgtInfo</a>.</p>

</div>
</div>

### isSupportedTgtId() {#a19cafb2b98160d416f6b684843fc4989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READNONE bool llvm::AMDGPU::Exp::isSupportedTgtId (unsigned Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#af7592dc94276d1958420bcfb414b6998a8c000dbdd84cae416e103d023ca4f3bc">ET_DUAL_SRC_BLEND0</a>, <a href="#af7592dc94276d1958420bcfb414b6998a46aec9d69fc2301884b99597f4090df5">ET_DUAL_SRC_BLEND1</a>, <a href="#af7592dc94276d1958420bcfb414b6998a2f4f450132c7f1a5a8773ebd3fbc8e38">ET_NULL</a>, <a href="#af7592dc94276d1958420bcfb414b6998afe9e14fadada855231c900eecbea27f2">ET_PARAM0</a>, <a href="#af7592dc94276d1958420bcfb414b6998a6a774a598f798bc6a057d9a88a1427c0">ET_PARAM31</a>, <a href="#af7592dc94276d1958420bcfb414b6998a7120ea14ee1a2b75be3fcbbcf2cd238a">ET_POS4</a>, <a href="#af7592dc94276d1958420bcfb414b6998a5bf174e4118cb43e895fda34b8cbdb51">ET_PRIM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab07da835cd8eddcfffcfb4192dff59a6">llvm::AMDGPU::isGFX10Plus</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa5f3cd2ec6af3adbc143654720b1214b">llvm::AMDGPU::isGFX11Plus</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a26a8456ca91f0f85ed2f854837b0dc29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseExpTgt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ExpTgtInfo {#a333540371328c116d4991e147b390949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExpTgt llvm::AMDGPU::Exp::ExpTgtInfo[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {{"null"},           <a href="#af7592dc94276d1958420bcfb414b6998a2f4f450132c7f1a5a8773ebd3fbc8e38">ET_NULL</a>,            <a href="#af7592dc94276d1958420bcfb414b6998ad54e3354f0aba668bbc7e074f1b6ed18">ET_NULL_MAX_IDX</a>},
  {{"mrtz"},           <a href="#af7592dc94276d1958420bcfb414b6998ab7925f1cbfe3c4fc5464da6219815d2c">ET_MRTZ</a>,            <a href="#af7592dc94276d1958420bcfb414b6998aa8c987d72b2b9bfebb87da0cc8333e54">ET_MRTZ_MAX_IDX</a>},
  {{"prim"},           <a href="#af7592dc94276d1958420bcfb414b6998a5bf174e4118cb43e895fda34b8cbdb51">ET_PRIM</a>,            <a href="#af7592dc94276d1958420bcfb414b6998a3f125b615f9ce5c35545c3be2a0bdc01">ET_PRIM_MAX_IDX</a>},
  {{"mrt"},            <a href="#af7592dc94276d1958420bcfb414b6998a45d5e746d6f7b53f0baf217b6c60daca">ET_MRT0</a>,            <a href="#af7592dc94276d1958420bcfb414b6998a7c0a3c890504a43343b5104f8c8fa576">ET_MRT_MAX_IDX</a>},
  {{"pos"},            <a href="#af7592dc94276d1958420bcfb414b6998a819e373068289857bb1cef7f5b320c11">ET_POS0</a>,            <a href="#af7592dc94276d1958420bcfb414b6998ae29f0a5af13d540be374ed945bda9e92">ET_POS_MAX_IDX</a>},
  {{"dual_src_blend"}, <a href="#af7592dc94276d1958420bcfb414b6998a8c000dbdd84cae416e103d023ca4f3bc">ET_DUAL_SRC_BLEND0</a>, <a href="#af7592dc94276d1958420bcfb414b6998a12be7bab3abcb1b9646c4168aebbf033">ET_DUAL_SRC_BLEND_MAX_IDX</a>},
  {{"param"},          <a href="#af7592dc94276d1958420bcfb414b6998afe9e14fadada855231c900eecbea27f2">ET_PARAM0</a>,          <a href="#af7592dc94276d1958420bcfb414b6998a2b937886b062f2746a310334f52c6179">ET_PARAM_MAX_IDX</a>},
}
</div>
</dd>
</dl>

<p>Definition at line 1760 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac236558198da971873e571fa38d2b58a">getTgtId</a> and <a href="#ab0fcd9e7a60a23a941500f531dcc0379">getTgtName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
