---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-registercoalescer-cpp-/registercoalescer/phivalpos
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PHIValPos` Struct

<p>Position and VReg of a PHI instruction during coalescing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::PHIValPos { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e0e8115620fb29401623e1095bd6846">SI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Slot where this PHI occurs. <a href="#a3e0e8115620fb29401623e1095bd6846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accacbe7e8b6158be53f9b7db6dae7645">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VReg the PHI occurs in. <a href="#accacbe7e8b6158be53f9b7db6dae7645">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09f8557c599ccd6d51db4e9b6d329660">SubReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Qualifying subregister for Reg. <a href="#a09f8557c599ccd6d51db4e9b6d329660">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Position and VReg of a PHI instruction during coalescing.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Reg {#accacbe7e8b6158be53f9b7db6dae7645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::PHIValPos::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VReg the PHI occurs in.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### SI {#a3e0e8115620fb29401623e1095bd6846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::PHIValPos::SI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Slot where this PHI occurs.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### SubReg {#a09f8557c599ccd6d51db4e9b6d329660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::PHIValPos::SubReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Qualifying subregister for Reg.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
