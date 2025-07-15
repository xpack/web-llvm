---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/cu
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
namespace CU { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CompactUnwindEncodings { <a href="#aa1c28fd974153b1db771befc0ff80092">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compact unwind encoding values. <a href="#aa1c28fd974153b1db771befc0ff80092">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### CompactUnwindEncodings {#aa1c28fd974153b1db771befc0ff80092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum CU::CompactUnwindEncodings </td>
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
<td class="doxyEnumItemName">UNWIND_ARM_MODE_MASK<a id="aa1c28fd974153b1db771befc0ff80092abeec58fa661efb6206b55d5e7b45dd4c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0F000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_MODE_FRAME<a id="aa1c28fd974153b1db771befc0ff80092a849502cca8db931610472d93900ff660"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_MODE_FRAME_D<a id="aa1c28fd974153b1db771befc0ff80092acd4b65d0bf4a0aeebd2083809532f573"></a></td>
<td class="doxyEnumItemDescription"> (= 0x02000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_MODE_DWARF<a id="aa1c28fd974153b1db771befc0ff80092a55fbd510ae9a93faa302922c20fbdff6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x04000000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_STACK_ADJUST_MASK<a id="aa1c28fd974153b1db771befc0ff80092a7c304c8e9eada676f5590fd629c32563"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00C00000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_FIRST_PUSH_R4<a id="aa1c28fd974153b1db771befc0ff80092a69a6fb8e04526bcc33df0e2406d095a6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_FIRST_PUSH_R5<a id="aa1c28fd974153b1db771befc0ff80092ace5c74e75c5a3c569ab52b33731eee9b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_FIRST_PUSH_R6<a id="aa1c28fd974153b1db771befc0ff80092a4ea8e23c29d637a9929367f607fc4ab4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_SECOND_PUSH_R8<a id="aa1c28fd974153b1db771befc0ff80092a77df01764f5d91561b69d45ad653ec0f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_SECOND_PUSH_R9<a id="aa1c28fd974153b1db771befc0ff80092a7432b5a7bd445bf460702fb4ddbc3aa9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000010)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_SECOND_PUSH_R10<a id="aa1c28fd974153b1db771befc0ff80092a01dbba723e50b0f02038e99f52bde068"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000020)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_SECOND_PUSH_R11<a id="aa1c28fd974153b1db771befc0ff80092a4f00ba2716ad01bd0867b62f13c06140"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000040)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_SECOND_PUSH_R12<a id="aa1c28fd974153b1db771befc0ff80092a9be55167f28808386e5bfebb09886aab"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000080)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_FRAME_D_REG_COUNT_MASK<a id="aa1c28fd974153b1db771befc0ff80092ab6eeb4476f6690260a915c835f7af270"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00000F00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNWIND_ARM_DWARF_SECTION_OFFSET<a id="aa1c28fd974153b1db771befc0ff80092a5e65951c28b7ad45f95f0a3ffb2ef411"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00FFFFFF)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
