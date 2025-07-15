---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/allocapackedvalues
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AllocaPackedValues` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::AllocaPackedValues { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">llvm/Bitcode/BitcodeCommon.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54703ef934fa504b4c9c5f23c2e19f84">AlignLower</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; unsigned, 0, 5 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed6c4b282d36b8766b601c6a833c7c6">UsedWithInAlloca</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; bool, <a href="/web-llvm/docs/api/structs/llvm/bitfield/element/#ac97bc0b40f8f7b458e734291ef255f93">AlignLower::NextBit</a>, 1 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd6ffbf6e1ae5e524f5866f1fdb74d9b">ExplicitType</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; bool, <a href="/web-llvm/docs/api/structs/llvm/bitfield/element/#ac97bc0b40f8f7b458e734291ef255f93">UsedWithInAlloca::NextBit</a>, 1 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a52b6305f5c9f377748c774af9ecd3">SwiftError</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; bool, <a href="/web-llvm/docs/api/structs/llvm/bitfield/element/#ac97bc0b40f8f7b458e734291ef255f93">ExplicitType::NextBit</a>, 1 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9d105030b0253402c7d78e947fb63c">AlignUpper</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/bitfield/element/#ac97bc0b40f8f7b458e734291ef255f93">SwiftError::NextBit</a>, 3 &gt;</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">BitcodeCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AlignLower {#a54703ef934fa504b4c9c5f23c2e19f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AllocaPackedValues::AlignLower =  Bitfield::Element&lt;unsigned, 0, 5&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">BitcodeCommon.h</a>.</p>

</div>
</div>

### AlignUpper {#a9c9d105030b0253402c7d78e947fb63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AllocaPackedValues::AlignUpper =  Bitfield::Element&lt;unsigned, SwiftError::NextBit, 3&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">BitcodeCommon.h</a>.</p>

</div>
</div>

### ExplicitType {#abd6ffbf6e1ae5e524f5866f1fdb74d9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AllocaPackedValues::ExplicitType =  Bitfield::Element&lt;bool, UsedWithInAlloca::NextBit, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">BitcodeCommon.h</a>.</p>

</div>
</div>

### SwiftError {#ac1a52b6305f5c9f377748c774af9ecd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AllocaPackedValues::SwiftError =  Bitfield::Element&lt;bool, ExplicitType::NextBit, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">BitcodeCommon.h</a>.</p>

</div>
</div>

### UsedWithInAlloca {#a1ed6c4b282d36b8766b601c6a833c7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AllocaPackedValues::UsedWithInAlloca =  Bitfield::Element&lt;bool, AlignLower::NextBit, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">BitcodeCommon.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">BitcodeCommon.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
