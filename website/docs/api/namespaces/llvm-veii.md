---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/veii
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `VEII` Namespace Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/veii">VEII</a> - This namespace holds all of the Aurora <a href="/web-llvm/docs/api/namespaces/llvm/ve">VE</a> target-specific per-instruction flags. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::VEII { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a1fa0d60ae54a9f71c3ed44055053891b">...</a> }</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/veii">VEII</a> - This namespace holds all of the Aurora <a href="/web-llvm/docs/api/namespaces/llvm/ve">VE</a> target-specific per-instruction flags.</p>


<p>These must match the corresponding definitions in VEInstrFormats.td.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a1fa0d60ae54a9f71c3ed44055053891b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">VE_Vector<a id="a1fa0d60ae54a9f71c3ed44055053891ba80a47316d09b2e7ef7e6fa7fff45c703"></a></td>
<td class="doxyEnumItemDescription">VE_Vector - This instruction is Vector <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VE_VLInUse<a id="a1fa0d60ae54a9f71c3ed44055053891ba5b2c11a64ad30872f6aa7e60022ef9e7"></a></td>
<td class="doxyEnumItemDescription">VE_VLInUse - This instruction has a vector register in its operands (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VE_VLShift<a id="a1fa0d60ae54a9f71c3ed44055053891ba29f0bb87c2d91435fcdb9e194cf42613"></a></td>
<td class="doxyEnumItemDescription">VE_VLMask/Shift - This is a bitmask that selects the index number where an instruction holds vector length informatio (0 to 6, 7 means undef).n (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VE_VLMask<a id="a1fa0d60ae54a9f71c3ed44055053891bae1c02176a3fd8a52cb6560c86c963704"></a></td>
<td class="doxyEnumItemDescription"> (= 0x07 &lt;&lt; VE_VLShift)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-h">VEInstrInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-h">VEInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
