---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-adce-cpp-/instinfotype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InstInfoType` Struct Reference

<p>Information about Instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ADCE.cpp}::InstInfoType { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e775fbbd8bc8e2e4f9ebe75aebcdea2">Live</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the associated instruction is live. <a href="#a2e775fbbd8bc8e2e4f9ebe75aebcdea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c10d6cd40ec0910e8db4b3f600bafc">Block</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Quick access to information for block containing associated <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#a72c10d6cd40ec0910e8db4b3f600bafc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Information about Instructions.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Block {#a72c10d6cd40ec0910e8db4b3f600bafc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct BlockInfoType* anonymous{ADCE.cpp}::InstInfoType::Block = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Quick access to information for block containing associated <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

### Live {#a2e775fbbd8bc8e2e4f9ebe75aebcdea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ADCE.cpp}::InstInfoType::Live = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the associated instruction is live.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/adce-cpp">ADCE.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
