---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/functionloweringinfo/statepointrelocationrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `StatepointRelocationRecord` Struct Reference

<p>Helper object to track which of three possible relocation mechanisms are used for a particular value being relocated over a statepoint. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FunctionLoweringInfo::StatepointRelocationRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">llvm/CodeGen/FunctionLoweringInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RelocType { <a href="#ae85ec708fd4e537d4b331ce7f94acb2c">...</a> }</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#ae85ec708fd4e537d4b331ce7f94acb2c">llvm::FunctionLoweringInfo::StatepointRelocationRecord::RelocType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71262a52679c1bff78fbec385a79a000">type</a> = <a href="#ae85ec708fd4e537d4b331ce7f94acb2cae1c6c7a77fab355eb08576b3bd29b924">NoRelocate</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/unions/llvm/functionloweringinfo/statepointrelocationrecord/payload-t">llvm::FunctionLoweringInfo::StatepointRelocationRecord::payload_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b35426a048cac6e35a0d4eeb04ba7b5">payload</a></td>
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

<p>Helper object to track which of three possible relocation mechanisms are used for a particular value being relocated over a statepoint.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### RelocType {#ae85ec708fd4e537d4b331ce7f94acb2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::FunctionLoweringInfo::StatepointRelocationRecord::RelocType </td>
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
<td class="doxyEnumItemName">NoRelocate<a id="ae85ec708fd4e537d4b331ce7f94acb2cae1c6c7a77fab355eb08576b3bd29b924"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Spill<a id="ae85ec708fd4e537d4b331ce7f94acb2ca4e2303faf0f163fb7a4af33f778884e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VReg<a id="ae85ec708fd4e537d4b331ce7f94acb2cad7321692f596ba5573d414ce3452c26f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDValueNode<a id="ae85ec708fd4e537d4b331ce7f94acb2cafcf3e806047173bc7c8581b355375870"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### payload {#a3b35426a048cac6e35a0d4eeb04ba7b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::FunctionLoweringInfo::StatepointRelocationRecord::payload_t llvm::FunctionLoweringInfo::StatepointRelocationRecord::payload</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### type {#a71262a52679c1bff78fbec385a79a000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::FunctionLoweringInfo::StatepointRelocationRecord::RelocType llvm::FunctionLoweringInfo::StatepointRelocationRecord::type = <a href="#ae85ec708fd4e537d4b331ce7f94acb2cae1c6c7a77fab355eb08576b3bd29b924">NoRelocate</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
