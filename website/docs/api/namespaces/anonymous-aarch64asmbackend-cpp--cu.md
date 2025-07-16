---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-aarch64asmbackend-cpp-/cu
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `CU` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{AArch64AsmBackend.cpp}::CU { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CompactUnwindEncodings { <a href="#a16405a544a6b03e51579487ecb9e37f6">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compact unwind encoding values. <a href="#a16405a544a6b03e51579487ecb9e37f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### CompactUnwindEncodings {#a16405a544a6b03e51579487ecb9e37f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AArch64AsmBackend.cpp}::CU::CompactUnwindEncodings </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compact unwind encoding values.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_MODE_FRAMELESS<a id="a16405a544a6b03e51579487ecb9e37f6a05eeb1b0006cfbee46a3ac9fb0d5a96c"></a></td>
<td class="doxyEnumItemDescription">A "frameless" leaf function, where no non-volatile registers are saved (= 0x02000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_MODE_DWARF<a id="a16405a544a6b03e51579487ecb9e37f6aa773994800d86f27b3280d8b97fc7576"></a></td>
<td class="doxyEnumItemDescription">No compact unwind encoding available (= 0x03000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_MODE_FRAME<a id="a16405a544a6b03e51579487ecb9e37f6abd0383c872b2d87cf76523b8b4886101"></a></td>
<td class="doxyEnumItemDescription">This is a standard arm64 prologue where FP/LR are immediately pushed on the stack, then SP is copied to FP (= 0x04000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_X19_X20_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6aba9c409a7664833e2847bb1ccf07419c"></a></td>
<td class="doxyEnumItemDescription">Frame register pair encodings (= 0x00000001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_X21_X22_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6a79bdc6acbe6e112f61db72f4957d099c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_X23_X24_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6a04b731c3240e635e185ccd51b4bdf6f3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_X25_X26_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6a4f25a0a71f42af3084ec8b5e1b0f6bd1"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_X27_X28_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6a68942402a85c709fe1f44d789311372a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000010)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_D8_D9_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6a6ad85562e2e0bdfe6b0d7087f0be3219"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_D10_D11_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6adac808bcc3f35561b42dee2cd280c1ef"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_D12_D13_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6a0af2a34b6a8638fcc6b17f368f145ed0"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000400)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM64_FRAME_D14_D15_PAIR<a id="a16405a544a6b03e51579487ecb9e37f6ad83c76554f0a5b2335d1d1fa329c3744"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000800)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
