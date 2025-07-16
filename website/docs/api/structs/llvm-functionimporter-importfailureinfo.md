---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/functionimporter/importfailureinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ImportFailureInfo` Struct Reference

<p>Information optionally tracked for candidates the importer decided not to import. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FunctionImporter::ImportFailureInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">llvm/Transforms/IPO/FunctionImport.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06685c8a4a85d550efbdde65c6b6b81c">ImportFailureInfo</a> (ValueInfo VI, CalleeInfo::HotnessType MaxHotness, ImportFailureReason Reason, unsigned Attempts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae07c2b6ff02f9a52d026a81babf6367b">VI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caa">CalleeInfo::HotnessType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0f7e50bd07acd1014109b6833a0a46">MaxHotness</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29">ImportFailureReason</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bfcd8f1fcfad8439961b4f04aac3c49">Reason</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b963b61ba717035deeff1e8ff3aead">Attempts</a></td>
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

<p>Information optionally tracked for candidates the importer decided not to import.</p>


<p>Used for optional stat printing.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">FunctionImport.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ImportFailureInfo() {#a06685c8a4a85d550efbdde65c6b6b81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionImporter::ImportFailureInfo::ImportFailureInfo (<a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> VI, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caa">CalleeInfo::HotnessType</a> MaxHotness, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29">ImportFailureReason</a> Reason, unsigned Attempts)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">FunctionImport.h</a>.</p>


<p>References <a href="#af5b963b61ba717035deeff1e8ff3aead">Attempts</a>, <a href="#a8c0f7e50bd07acd1014109b6833a0a46">MaxHotness</a>, <a href="#a9bfcd8f1fcfad8439961b4f04aac3c49">Reason</a> and <a href="#ae07c2b6ff02f9a52d026a81babf6367b">VI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Attempts {#af5b963b61ba717035deeff1e8ff3aead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionImporter::ImportFailureInfo::Attempts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">FunctionImport.h</a>.</p>


<p>Referenced by <a href="#a06685c8a4a85d550efbdde65c6b6b81c">ImportFailureInfo</a>.</p>

</div>
</div>

### MaxHotness {#a8c0f7e50bd07acd1014109b6833a0a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CalleeInfo::HotnessType llvm::FunctionImporter::ImportFailureInfo::MaxHotness</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">FunctionImport.h</a>.</p>


<p>Referenced by <a href="#a06685c8a4a85d550efbdde65c6b6b81c">ImportFailureInfo</a>.</p>

</div>
</div>

### Reason {#a9bfcd8f1fcfad8439961b4f04aac3c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImportFailureReason llvm::FunctionImporter::ImportFailureInfo::Reason</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">FunctionImport.h</a>.</p>


<p>Referenced by <a href="#a06685c8a4a85d550efbdde65c6b6b81c">ImportFailureInfo</a>.</p>

</div>
</div>

### VI {#ae07c2b6ff02f9a52d026a81babf6367b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueInfo llvm::FunctionImporter::ImportFailureInfo::VI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">FunctionImport.h</a>.</p>


<p>Referenced by <a href="#a06685c8a4a85d550efbdde65c6b6b81c">ImportFailureInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">FunctionImport.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
