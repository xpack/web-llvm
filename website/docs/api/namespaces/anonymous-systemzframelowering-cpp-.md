---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-systemzframelowering-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{SystemZFrameLowering.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{SystemZFrameLowering.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-systemzframelowering-cpp-/szframesortingobj">SZFrameSortingObj</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-systemzframelowering-cpp-/szframesortingobj">SZFrameSortingObj</a> &gt; <a href="#a5372bf85b8411bff18f13fd2e3a04599">SZFrameObjVec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/spillslot">TargetFrameLowering::SpillSlot</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa678d946536814b5a995affc8ab614b">ELFSpillOffsetTable</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/spillslot">TargetFrameLowering::SpillSlot</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37a95e8eac44ed06d2fd6224b8f44f68">XPLINKSpillOffsetTable</a>[] = ...</td>
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

### SZFrameObjVec {#a5372bf85b8411bff18f13fd2e3a04599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;SZFrameSortingObj&gt; anonymous{SystemZFrameLowering.cpp}::SZFrameObjVec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ELFSpillOffsetTable {#afa678d946536814b5a995affc8ab614b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFrameLowering::SpillSlot anonymous{SystemZFrameLowering.cpp}::ELFSpillOffsetTable[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
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
  { SystemZ::R2D,  0x10 },
  { SystemZ::R3D,  0x18 },
  { SystemZ::R4D,  0x20 },
  { SystemZ::R5D,  0x28 },
  { SystemZ::R6D,  0x30 },
  { SystemZ::R7D,  0x38 },
  { SystemZ::R8D,  0x40 },
  { SystemZ::R9D,  0x48 },
  { SystemZ::R10D, 0x50 },
  { SystemZ::R11D, 0x58 },
  { SystemZ::R12D, 0x60 },
  { SystemZ::R13D, 0x68 },
  { SystemZ::R14D, 0x70 },
  { SystemZ::R15D, 0x78 },
  { SystemZ::F0D,  0x80 },
  { SystemZ::F2D,  0x88 },
  { SystemZ::F4D,  0x90 },
  { SystemZ::F6D,  0x98 }
}
</div>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>

</div>
</div>

### XPLINKSpillOffsetTable {#a37a95e8eac44ed06d2fd6224b8f44f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFrameLowering::SpillSlot anonymous{SystemZFrameLowering.cpp}::XPLINKSpillOffsetTable[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
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
    {SystemZ::R4D, 0x00},  {SystemZ::R5D, 0x08},  {SystemZ::R6D, 0x10},
    {SystemZ::R7D, 0x18},  {SystemZ::R8D, 0x20},  {SystemZ::R9D, 0x28},
    {SystemZ::R10D, 0x30}, {SystemZ::R11D, 0x38}, {SystemZ::R12D, 0x40},
    {SystemZ::R13D, 0x48}, {SystemZ::R14D, 0x50}, {SystemZ::R15D, 0x58}}
</div>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp">SystemZFrameLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
