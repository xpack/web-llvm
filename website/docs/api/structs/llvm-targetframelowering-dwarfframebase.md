---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetframelowering/dwarfframebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DwarfFrameBase` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::TargetFrameLowering::DwarfFrameBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">llvm/CodeGen/TargetFrameLowering.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FrameBaseKind { <a href="#a69b8f7941a5f3d374f3a4ef2fd86516b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a69b8f7941a5f3d374f3a4ef2fd86516b">llvm::TargetFrameLowering::DwarfFrameBase::FrameBaseKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d82d53acc347a5ab75ea59da93c298">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be6e48131f5c6e93e48b52a903a720e">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3e9e851be1c3d4d7276752c0c2d330">Offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac491fefadf04fa5c85142a5fab3f3d9d">WasmLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/targetframelowering/dwarfframebase">llvm::TargetFrameLowering::DwarfFrameBase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82acb7f3bcf1d1f621a2afbcc936e85b">Location</a></td>
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


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">TargetFrameLowering.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FrameBaseKind {#a69b8f7941a5f3d374f3a4ef2fd86516b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetFrameLowering::DwarfFrameBase::FrameBaseKind </td>
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
<td class="doxyEnumItemName">Register<a id="a69b8f7941a5f3d374f3a4ef2fd86516ba52b328d5d033b938104b2f391ec0b6c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CFA<a id="a69b8f7941a5f3d374f3a4ef2fd86516ba17f65ba058c6314a928497bd58cb6623"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WasmFrameBase<a id="a69b8f7941a5f3d374f3a4ef2fd86516ba3222f8588ce31d0c0e708b231e8f7ffc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">TargetFrameLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Kind {#ab9d82d53acc347a5ab75ea59da93c298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::TargetFrameLowering::DwarfFrameBase::FrameBaseKind llvm::TargetFrameLowering::DwarfFrameBase::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">TargetFrameLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#a6333ba79d4dc675d66a3813c0d61054b">llvm::NVPTXFrameLowering::getDwarfFrameBase</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aca49f4bdff5eb8f32e4b650f33d6f98e">llvm::X86FrameLowering::getDwarfFrameBase</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### Location {#a82acb7f3bcf1d1f621a2afbcc936e85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::TargetFrameLowering::DwarfFrameBase llvm::TargetFrameLowering::DwarfFrameBase::Location</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">TargetFrameLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#a6333ba79d4dc675d66a3813c0d61054b">llvm::NVPTXFrameLowering::getDwarfFrameBase</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aca49f4bdff5eb8f32e4b650f33d6f98e">llvm::X86FrameLowering::getDwarfFrameBase</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### Offset {#a0f3e9e851be1c3d4d7276752c0c2d330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::TargetFrameLowering::DwarfFrameBase::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">TargetFrameLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#a6333ba79d4dc675d66a3813c0d61054b">llvm::NVPTXFrameLowering::getDwarfFrameBase</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aca49f4bdff5eb8f32e4b650f33d6f98e">llvm::X86FrameLowering::getDwarfFrameBase</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### Reg {#a7be6e48131f5c6e93e48b52a903a720e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetFrameLowering::DwarfFrameBase::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">TargetFrameLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

### WasmLoc {#ac491fefadf04fa5c85142a5fab3f3d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct WasmFrameBase llvm::TargetFrameLowering::DwarfFrameBase::WasmLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">TargetFrameLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">TargetFrameLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
