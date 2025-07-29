---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-x86asmbackend-cpp-/cu
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `CU` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{X86AsmBackend.cpp}::CU { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CompactUnwindEncodings { <a href="#a53d1137279e003417f6eea1132ee2067">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compact unwind encoding values. <a href="#a53d1137279e003417f6eea1132ee2067">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### CompactUnwindEncodings {#a53d1137279e003417f6eea1132ee2067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86AsmBackend.cpp}::CU::CompactUnwindEncodings </td>
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
<td class="doxyEnumItemName">UNWIND_MODE_BP_FRAME<a id="a53d1137279e003417f6eea1132ee2067a6a430d800822edae2d2e36131395615d"></a></td>
<td class="doxyEnumItemDescription">[RE]BP based frame where [RE]BP is pused on the stack immediately after the return address, then [RE]SP is moved to [RE]BP (= 0x01000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_MODE_STACK_IMMD<a id="a53d1137279e003417f6eea1132ee2067ad96614bec64aaa57a8bac8c6f07181d7"></a></td>
<td class="doxyEnumItemDescription">A frameless function with a small constant stack size (= 0x02000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_MODE_STACK_IND<a id="a53d1137279e003417f6eea1132ee2067abc74b2c720b10e4cc1347bd310a930b4"></a></td>
<td class="doxyEnumItemDescription">A frameless function with a large constant stack size (= 0x03000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_MODE_DWARF<a id="a53d1137279e003417f6eea1132ee2067a525c66164a17a018715e2943f976b565"></a></td>
<td class="doxyEnumItemDescription">No compact unwind encoding is available (= 0x04000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_BP_FRAME_REGISTERS<a id="a53d1137279e003417f6eea1132ee2067af4ab9f398422d0b86cd487c6edd95736"></a></td>
<td class="doxyEnumItemDescription">Mask for encoding the frame registers (= 0x00007FFF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_FRAMELESS_STACK_REG_PERMUTATION<a id="a53d1137279e003417f6eea1132ee2067a0d782a80c0c846892bebe03111c8372a"></a></td>
<td class="doxyEnumItemDescription">Mask for encoding the frameless registers (= 0x000003FF)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
