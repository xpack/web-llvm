---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/dpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `DPP` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::DPP { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DppCtrl : unsigned { <a href="#aa27612400d9f4f18653d361495d67b08">...</a> }</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DppFiMode { <a href="#aa19c007b0d0fdcbf3db8462eeb72c059">...</a> }</td>
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

### DppCtrl {#aa27612400d9f4f18653d361495d67b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::DPP::DppCtrl : unsigned</td>
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
<td class="doxyEnumItemName">QUAD_PERM_FIRST<a id="aa27612400d9f4f18653d361495d67b08af5b48aa11d36e4d173d82e645b804525"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QUAD_PERM_ID<a id="aa27612400d9f4f18653d361495d67b08a18d159624c8e4526316dcf4b34243a88"></a></td>
<td class="doxyEnumItemDescription"> (= 0xE4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QUAD_PERM_LAST<a id="aa27612400d9f4f18653d361495d67b08a52db1e058f20f51d26ebb9624c52b240"></a></td>
<td class="doxyEnumItemDescription"> (= 0xFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED1<a id="aa27612400d9f4f18653d361495d67b08a01e5da7e6376e18c3d69a3c01817ed88"></a></td>
<td class="doxyEnumItemDescription"> (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHL0<a id="aa27612400d9f4f18653d361495d67b08a8455c27cf732f14fba7f304f67b1af16"></a></td>
<td class="doxyEnumItemDescription"> (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHL_FIRST<a id="aa27612400d9f4f18653d361495d67b08aa0a9df192d678c0644b5c20d4a233f24"></a></td>
<td class="doxyEnumItemDescription"> (= 0x101)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHL_LAST<a id="aa27612400d9f4f18653d361495d67b08a6d004b84dbcce828942fabd5c60507d8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED2<a id="aa27612400d9f4f18653d361495d67b08aea015d153c806aa1a5c75338d55017b5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x110)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHR0<a id="aa27612400d9f4f18653d361495d67b08afd209d91926fdad77e731e4e6c0eb39b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x110)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHR_FIRST<a id="aa27612400d9f4f18653d361495d67b08a121b7c6d9f56fbb503056805b749e883"></a></td>
<td class="doxyEnumItemDescription"> (= 0x111)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHR_LAST<a id="aa27612400d9f4f18653d361495d67b08aa2621413a00a0fa1a667feb51cdfc333"></a></td>
<td class="doxyEnumItemDescription"> (= 0x11F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED3<a id="aa27612400d9f4f18653d361495d67b08a8f197cdbb473b5d83dfa9024cb2d4e1b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x120)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_ROR0<a id="aa27612400d9f4f18653d361495d67b08a6a76159d546c808a0450aebeab7b5f37"></a></td>
<td class="doxyEnumItemDescription"> (= 0x120)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_ROR_FIRST<a id="aa27612400d9f4f18653d361495d67b08a9e08c85c7d6f60d087e8455a4577bd69"></a></td>
<td class="doxyEnumItemDescription"> (= 0x121)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_ROR_LAST<a id="aa27612400d9f4f18653d361495d67b08aa4ec018c5346887664d316f13c690611"></a></td>
<td class="doxyEnumItemDescription"> (= 0x12F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WAVE_SHL1<a id="aa27612400d9f4f18653d361495d67b08ab9dead8d5e63143c1abb4a508d4c6f30"></a></td>
<td class="doxyEnumItemDescription"> (= 0x130)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED4_FIRST<a id="aa27612400d9f4f18653d361495d67b08aa109aa58f369471dd6f77dd44809a21f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x131)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED4_LAST<a id="aa27612400d9f4f18653d361495d67b08a22fbd464cb18592187bbe332ce44abc9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x133)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WAVE_ROL1<a id="aa27612400d9f4f18653d361495d67b08a4461ff64de7ad86800306bfc3c8769e8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x134)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED5_FIRST<a id="aa27612400d9f4f18653d361495d67b08ab118342ef68df0708e1c6c1a9822e11f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x135)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED5_LAST<a id="aa27612400d9f4f18653d361495d67b08afd69a50c5cc7f76e5361087c82338cca"></a></td>
<td class="doxyEnumItemDescription"> (= 0x137)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WAVE_SHR1<a id="aa27612400d9f4f18653d361495d67b08aa27c2292be22c82ea2f2497c76d99118"></a></td>
<td class="doxyEnumItemDescription"> (= 0x138)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED6_FIRST<a id="aa27612400d9f4f18653d361495d67b08a0946b16bcd77f9e3d92cc2b1f6ce7fca"></a></td>
<td class="doxyEnumItemDescription"> (= 0x139)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED6_LAST<a id="aa27612400d9f4f18653d361495d67b08adfdacd1625ea09362131dda6be04997b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x13B)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WAVE_ROR1<a id="aa27612400d9f4f18653d361495d67b08abbdea5eaa8b53c3c3ddc5446a1883d0e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x13C)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED7_FIRST<a id="aa27612400d9f4f18653d361495d67b08ab8caa6d2ed1f1e46f7de55d0d437a3c3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x13D)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED7_LAST<a id="aa27612400d9f4f18653d361495d67b08af24eb5ee59a5e5bf84df58dcf64c92c0"></a></td>
<td class="doxyEnumItemDescription"> (= 0x13F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_MIRROR<a id="aa27612400d9f4f18653d361495d67b08a6e43e3dca210502505e9966c05ef55d5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x140)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_HALF_MIRROR<a id="aa27612400d9f4f18653d361495d67b08a9077097914bb8e7879a908764fe0f37d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x141)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BCAST15<a id="aa27612400d9f4f18653d361495d67b08a60f0e8dd618af278da015b2945a34b4e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x142)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BCAST31<a id="aa27612400d9f4f18653d361495d67b08a9db0c6cdc58a23822de98f246145a788"></a></td>
<td class="doxyEnumItemDescription"> (= 0x143)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED8_FIRST<a id="aa27612400d9f4f18653d361495d67b08a31b0c3c70775b8b23f65b9d769606e78"></a></td>
<td class="doxyEnumItemDescription"> (= 0x144)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_UNUSED8_LAST<a id="aa27612400d9f4f18653d361495d67b08a24b903655c85bb90074e7d4c20ad665b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x14F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_NEWBCAST_FIRST<a id="aa27612400d9f4f18653d361495d67b08aa1fb933a07c862608a52170e730163de"></a></td>
<td class="doxyEnumItemDescription"> (= 0x150)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_NEWBCAST_LAST<a id="aa27612400d9f4f18653d361495d67b08a0217c93a90ee9ecf413f258cf8ff0eb2"></a></td>
<td class="doxyEnumItemDescription"> (= 0x15F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHARE0<a id="aa27612400d9f4f18653d361495d67b08a2f3fae2173d7705ec1d3fd3bf5859632"></a></td>
<td class="doxyEnumItemDescription"> (= 0x150)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHARE_FIRST<a id="aa27612400d9f4f18653d361495d67b08a7c1b7d231bccabb7234e9b353c87a904"></a></td>
<td class="doxyEnumItemDescription"> (= 0x150)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_SHARE_LAST<a id="aa27612400d9f4f18653d361495d67b08aa5784dd41d677a97d692a6ff9dce9864"></a></td>
<td class="doxyEnumItemDescription"> (= 0x15F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_XMASK0<a id="aa27612400d9f4f18653d361495d67b08a5f1c3d726459f1265e11ed544ee4be53"></a></td>
<td class="doxyEnumItemDescription"> (= 0x160)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_XMASK_FIRST<a id="aa27612400d9f4f18653d361495d67b08a175c7c2cfb13bbb127dbbfe8ab44e6fe"></a></td>
<td class="doxyEnumItemDescription"> (= 0x160)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROW_XMASK_LAST<a id="aa27612400d9f4f18653d361495d67b08a40ba804f3ab3eae632ab10e37179a2e9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x16F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_LAST<a id="aa27612400d9f4f18653d361495d67b08a229a44fa66049a4fe6b24c7bfdcd986e"></a></td>
<td class="doxyEnumItemDescription"> (= ROW_XMASK_LAST)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### DppFiMode {#aa19c007b0d0fdcbf3db8462eeb72c059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::DPP::DppFiMode </td>
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
<td class="doxyEnumItemName">DPP_FI_0<a id="aa19c007b0d0fdcbf3db8462eeb72c059aea6c49b9f1e3f242a5bc3a69a00215b2"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP_FI_1<a id="aa19c007b0d0fdcbf3db8462eeb72c059acb1490082afd25589521c543fec236b7"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP8_FI_0<a id="aa19c007b0d0fdcbf3db8462eeb72c059a86bc62297264c5c421f06a54985349a1"></a></td>
<td class="doxyEnumItemDescription"> (= 0xE9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP8_FI_1<a id="aa19c007b0d0fdcbf3db8462eeb72c059a470b8d8ac84510a78711e68988cb0d6b"></a></td>
<td class="doxyEnumItemDescription"> (= 0xEA)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
