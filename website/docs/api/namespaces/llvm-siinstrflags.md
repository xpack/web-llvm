---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/siinstrflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `SIInstrFlags` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::SIInstrFlags { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint64_t { <a href="#a63fe1ccb8fc5f327a64d2977fce181ec">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ClassFlags : unsigned { <a href="#aab1e56b694ff2c83f07ee874be04916f">...</a> }</td>
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

### anonymous enum  {#a63fe1ccb8fc5f327a64d2977fce181ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint64_t</td>
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
<td class="doxyEnumItemName">SALU<a id="a63fe1ccb8fc5f327a64d2977fce181ecab20a2dd15666d86af4e1fdeb88b1be7c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALU<a id="a63fe1ccb8fc5f327a64d2977fce181eca25bdad6e13bc9ed9f9ce690ae614db1c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SOP1<a id="a63fe1ccb8fc5f327a64d2977fce181ecaa1db6db58e0bae030fb7277723deb3a9"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SOP2<a id="a63fe1ccb8fc5f327a64d2977fce181eca2f0e3ce334e6b7fa59a2822e2770ab1d"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SOPC<a id="a63fe1ccb8fc5f327a64d2977fce181ecadad0f2be60062a72d37634705e8aed51"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SOPK<a id="a63fe1ccb8fc5f327a64d2977fce181eca95d3d9b72a40bcb9f88738fd86094a62"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SOPP<a id="a63fe1ccb8fc5f327a64d2977fce181eca3240de017ea18f8b8daf38bc4d927294"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOP1<a id="a63fe1ccb8fc5f327a64d2977fce181eca0dd2852ae8f20b7261f6d01eb354f1ff"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOP2<a id="a63fe1ccb8fc5f327a64d2977fce181eca600d26b3fa43f262c5ca2270667c0be2"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOPC<a id="a63fe1ccb8fc5f327a64d2977fce181eca40767b966aa194931bb6ce67e3649de7"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOP3<a id="a63fe1ccb8fc5f327a64d2977fce181eca78562688e8d67f7ffa892e4b92311a98"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOP3P<a id="a63fe1ccb8fc5f327a64d2977fce181eca4b3bb80273571c42a8b35d5e952034c9"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VINTRP<a id="a63fe1ccb8fc5f327a64d2977fce181eca0bd36c4d359999d7043f5fdf440b0c7c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDWA<a id="a63fe1ccb8fc5f327a64d2977fce181eca3cb08b10c27a453c57a2708e83859b47"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPP<a id="a63fe1ccb8fc5f327a64d2977fce181eca06434d3505958806f243119630f8c976"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRANS<a id="a63fe1ccb8fc5f327a64d2977fce181eca6edf620aaa09a9f39b50177b8fa809d4"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUBUF<a id="a63fe1ccb8fc5f327a64d2977fce181eca2fca87a5855f045ac7f07d8c2814e81f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MTBUF<a id="a63fe1ccb8fc5f327a64d2977fce181eca4863f895381859543f89e4423126a73f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMRD<a id="a63fe1ccb8fc5f327a64d2977fce181eca30118e93ea743944a8fa1d846dcbaf37"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIMG<a id="a63fe1ccb8fc5f327a64d2977fce181eca0666b703f5fe8ee884171492fb6a685a"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VIMAGE<a id="a63fe1ccb8fc5f327a64d2977fce181ecaffe2f0079ddf5f206b323cdecec1e655"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSAMPLE<a id="a63fe1ccb8fc5f327a64d2977fce181eca68afea1b16331758f09fc0d8c229b86f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXP<a id="a63fe1ccb8fc5f327a64d2977fce181eca3f6b33151573e94a6ef7f14b809dbe70"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLAT<a id="a63fe1ccb8fc5f327a64d2977fce181ecab0e8527c8c81d2caa91d9b2bd1852574"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DS<a id="a63fe1ccb8fc5f327a64d2977fce181eca953a5ba3766c4aea8d9b8eeeba722679"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Spill<a id="a63fe1ccb8fc5f327a64d2977fce181ecaa444d6850530e37d8af98558ce5b25f5"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDSDIR<a id="a63fe1ccb8fc5f327a64d2977fce181ecafe9bf84e87ab9f272db7a7145eb59758"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VINTERP<a id="a63fe1ccb8fc5f327a64d2977fce181eca1440c15f5bea6a1ebb07324b7be433c3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VM_CNT<a id="a63fe1ccb8fc5f327a64d2977fce181ecaf5dfd8c9db8b07c80292e662aa96c6a7"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXP_CNT<a id="a63fe1ccb8fc5f327a64d2977fce181eca39d5973dbb8033fc504c01227f3eaecf"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 33)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LGKM_CNT<a id="a63fe1ccb8fc5f327a64d2977fce181ecaee110070224119e12075fafd4909dc9c"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 34)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WQM<a id="a63fe1ccb8fc5f327a64d2977fce181ecae51b91ec89e9fd6502c3339d1360c147"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 35)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DisableWQM<a id="a63fe1ccb8fc5f327a64d2977fce181ecae0063a0501793fcbc332d543bd1541bc"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Gather4<a id="a63fe1ccb8fc5f327a64d2977fce181eca1fb3a3c9d73c11f77861315b283e3fde"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Reserved0<a id="a63fe1ccb8fc5f327a64d2977fce181ecabee140fc1b825a6d2690183c503c3040"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCALAR_STORE<a id="a63fe1ccb8fc5f327a64d2977fce181ecadaafc9c279a6480f1729929b26a4ad05"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 39)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIXED_SIZE<a id="a63fe1ccb8fc5f327a64d2977fce181eca3f90dc3ee0272479ff77f144e37b8abc"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Reserved1<a id="a63fe1ccb8fc5f327a64d2977fce181eca1d721d77b01814df2b05e636aabf51b7"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 41)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOP3_OPSEL<a id="a63fe1ccb8fc5f327a64d2977fce181ecaf0ca8c082f70a5a7bf5d1cee50db3d07"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 42)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">maybeAtomic<a id="a63fe1ccb8fc5f327a64d2977fce181eca55d8f9babd910d3931296db01832f171"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 43)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">renamedInGFX9<a id="a63fe1ccb8fc5f327a64d2977fce181ecacff05c63e6ff81eab46dc98fbb55791c"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPClamp<a id="a63fe1ccb8fc5f327a64d2977fce181eca4c00f2292227a96409b86e250bac9b87"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 45)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntClamp<a id="a63fe1ccb8fc5f327a64d2977fce181ecaeac247ab12a49434e1142ece1a35379b"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 46)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ClampLo<a id="a63fe1ccb8fc5f327a64d2977fce181eca1f248cc663b917010c5d5ea2cff9445f"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 47)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ClampHi<a id="a63fe1ccb8fc5f327a64d2977fce181eca52880c64f523a9a892d8e4d33c3375dd"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 48)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsPacked<a id="a63fe1ccb8fc5f327a64d2977fce181ecaacf639f4528a313767923c5575e1828e"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 49)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">D16Buf<a id="a63fe1ccb8fc5f327a64d2977fce181ecadf3e0b276b086c14975adb3e2f00aa2c"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 50)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlatGlobal<a id="a63fe1ccb8fc5f327a64d2977fce181eca125415c6b554fcb76cedd65841141a92"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 51)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPDPRounding<a id="a63fe1ccb8fc5f327a64d2977fce181ecade5bdaea3c9b894b4d8d07410372c7f1"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 52)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPAtomic<a id="a63fe1ccb8fc5f327a64d2977fce181ecaccce8eb3ea48e8b0d5f5b7e9e011cc19"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 53)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsMAI<a id="a63fe1ccb8fc5f327a64d2977fce181ecaa0bc33f3818c02a577a8b209d98766cb"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 54)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsDOT<a id="a63fe1ccb8fc5f327a64d2977fce181ecabd8ac36f299f3add1ff63d49475d51a5"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 55)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlatScratch<a id="a63fe1ccb8fc5f327a64d2977fce181eca9a72e6ffd62dc38f5f4b7fd3e1f778da"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 56)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsAtomicNoRet<a id="a63fe1ccb8fc5f327a64d2977fce181eca9dbc1631e11296bf1f8e95a2111a1bb9"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 57)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsAtomicRet<a id="a63fe1ccb8fc5f327a64d2977fce181eca046343a654627954ce26d0e7531e12f7"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 58)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsWMMA<a id="a63fe1ccb8fc5f327a64d2977fce181ecadb719433b001db91973f66b4bc3b6dc8"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 59)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TiedSourceNotRead<a id="a63fe1ccb8fc5f327a64d2977fce181eca4777a05ca68d18f5d938d481ea0127c3"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 60)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsNeverUniform<a id="a63fe1ccb8fc5f327a64d2977fce181eca31a282e99b9ec37019e46aa2481190e9"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 61)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GWS<a id="a63fe1ccb8fc5f327a64d2977fce181eca0f98bad3dd2f0146ac2135da67847c9d"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 62)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsSWMMAC<a id="a63fe1ccb8fc5f327a64d2977fce181eca2b696c2aeb385ace4a1088a1169606a4"></a></td>
<td class="doxyEnumItemDescription"> (= UINT64_C(1) &lt;&lt; 63)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### ClassFlags {#aab1e56b694ff2c83f07ee874be04916f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SIInstrFlags::ClassFlags : unsigned</td>
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
<td class="doxyEnumItemName">S_NAN<a id="aab1e56b694ff2c83f07ee874be04916fa652acf31b995a544cc606af5d8547895"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Q_NAN<a id="aab1e56b694ff2c83f07ee874be04916fa3b711cc2011cca9d0656fb9f576ce06c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N_INFINITY<a id="aab1e56b694ff2c83f07ee874be04916faa724c17a66503402aa8d105d0c9f3d20"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N_NORMAL<a id="aab1e56b694ff2c83f07ee874be04916fa35d63c63b47d7e803ae4b7f3154bf9c3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N_SUBNORMAL<a id="aab1e56b694ff2c83f07ee874be04916fab01b38d29f480c7f254c6cf82e24cac3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">N_ZERO<a id="aab1e56b694ff2c83f07ee874be04916fa33a84ea8c7168a7b8a2993ee22b7748d"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">P_ZERO<a id="aab1e56b694ff2c83f07ee874be04916fae5d476f6be0ea2fa04d5dccbf605823a"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">P_SUBNORMAL<a id="aab1e56b694ff2c83f07ee874be04916faac5799ae9795275bfc6370dfa74bcba3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">P_NORMAL<a id="aab1e56b694ff2c83f07ee874be04916fa6f2b19adb58a87c191bdc0669c8a2951"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">P_INFINITY<a id="aab1e56b694ff2c83f07ee874be04916fac3642a81e1e79c9359572b4c9bc9cb45"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

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
