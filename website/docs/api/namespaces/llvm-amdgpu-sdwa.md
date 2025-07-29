---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/sdwa
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `SDWA` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::SDWA { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SdwaSel : unsigned { <a href="#a487d59303b94fbf4adddd9a08c30da0a">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DstUnused : unsigned { <a href="#a4473412439e8285e235ccafa0c3824b6">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SDWA9EncValues : unsigned { <a href="#a2e7c5b3eadddc4646a24e9b546a96cb5">...</a> }</td>
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

### DstUnused {#a4473412439e8285e235ccafa0c3824b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::SDWA::DstUnused : unsigned</td>
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
<td class="doxyEnumItemName">UNUSED_PAD<a id="a4473412439e8285e235ccafa0c3824b6aa32d1badbd5e9ff382591dfe33772591"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNUSED_SEXT<a id="a4473412439e8285e235ccafa0c3824b6ac242f41ca07c86e2cba62a617b640b66"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNUSED_PRESERVE<a id="a4473412439e8285e235ccafa0c3824b6a58f19664e2b69107495d2085514f7874"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### SDWA9EncValues {#a2e7c5b3eadddc4646a24e9b546a96cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::SDWA::SDWA9EncValues : unsigned</td>
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
<td class="doxyEnumItemName">SRC_SGPR_MASK<a id="a2e7c5b3eadddc4646a24e9b546a96cb5a7cdc0d1831641a3e2a71dfde8d4926c8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC_VGPR_MASK<a id="a2e7c5b3eadddc4646a24e9b546a96cb5a8e175d1e9b7d8ca70701afa131ca71f8"></a></td>
<td class="doxyEnumItemDescription"> (= 0xFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOPC_DST_VCC_MASK<a id="a2e7c5b3eadddc4646a24e9b546a96cb5a52c526632a771dd5ba61cabf8039d7a6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOPC_DST_SGPR_MASK<a id="a2e7c5b3eadddc4646a24e9b546a96cb5a137137a84f5edf57505301d38e2681e5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC_VGPR_MIN<a id="a2e7c5b3eadddc4646a24e9b546a96cb5aaad17b74b3bbdd80c81e125583b888cc"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC_VGPR_MAX<a id="a2e7c5b3eadddc4646a24e9b546a96cb5af329e92bfda091dc8a403c47bdef4b66"></a></td>
<td class="doxyEnumItemDescription"> (= 255)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC_SGPR_MIN<a id="a2e7c5b3eadddc4646a24e9b546a96cb5a7b827a6f489ec60c7de60f8b01145ba2"></a></td>
<td class="doxyEnumItemDescription"> (= 256)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC_SGPR_MAX_SI<a id="a2e7c5b3eadddc4646a24e9b546a96cb5a9d9916590006b204b5357b0088adfaf8"></a></td>
<td class="doxyEnumItemDescription"> (= 357)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC_SGPR_MAX_GFX10<a id="a2e7c5b3eadddc4646a24e9b546a96cb5a6f964e76859658e88d1b32c01879dd6e"></a></td>
<td class="doxyEnumItemDescription"> (= 361)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC_TTMP_MIN<a id="a2e7c5b3eadddc4646a24e9b546a96cb5ad3cbbf4fed2354620fbb99fc62b171be"></a></td>
<td class="doxyEnumItemDescription"> (= 364)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRC_TTMP_MAX<a id="a2e7c5b3eadddc4646a24e9b546a96cb5a033e72094a74e91253d06ffce8ea9178"></a></td>
<td class="doxyEnumItemDescription"> (= 379)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 919 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### SdwaSel {#a487d59303b94fbf4adddd9a08c30da0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::SDWA::SdwaSel : unsigned</td>
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
<td class="doxyEnumItemName">BYTE_0<a id="a487d59303b94fbf4adddd9a08c30da0aac0ba270133e0411b25c5e9f0a60db124"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BYTE_1<a id="a487d59303b94fbf4adddd9a08c30da0aabc18aa07471905caf14b86b02d05d867"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BYTE_2<a id="a487d59303b94fbf4adddd9a08c30da0aa90653661c47f66711e6360a8972032fd"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BYTE_3<a id="a487d59303b94fbf4adddd9a08c30da0aa4516f5e8a7d4dabec1b8130b105e1414"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORD_0<a id="a487d59303b94fbf4adddd9a08c30da0aaf4e7a9b6898b774104bfcd24a211d7e3"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WORD_1<a id="a487d59303b94fbf4adddd9a08c30da0aa3bd07eb171e650bc021c8e2517e175d0"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DWORD<a id="a487d59303b94fbf4adddd9a08c30da0aaddbc3f8d705f646af626fd73cdf3618b"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
