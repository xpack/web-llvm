---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetlowering/ptrauthinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PtrAuthInfo` Struct Reference

<p>This structure contains the information necessary for lowering pointer-authenticating indirect calls. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetLowering::PtrAuthInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae203b9ab7e0ed6bd3f276761b284f50">Key</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a93e8a6f545418b2aa567a0076efb4">Discriminator</a></td>
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

<p>This structure contains the information necessary for lowering pointer-authenticating indirect calls.</p>


<p>It is equivalent to the "ptrauth" operand bundle found on the call instruction, if any.</p>


<p>Definition at line 4520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Discriminator {#ab8a93e8a6f545418b2aa567a0076efb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::TargetLowering::PtrAuthInfo::Discriminator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

### Key {#aae203b9ab7e0ed6bd3f276761b284f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::TargetLowering::PtrAuthInfo::Key</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">TargetLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
