---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/extaddrmode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ExtAddrMode` Struct

<p>Used to describe addressing mode similar to <a href="/web-llvm/docs/api/structs/llvm/extaddrmode">ExtAddrMode</a> in CodeGenPrepare. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ExtAddrMode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Formula { <a href="#af4e263f5ba20144fc8b9e5b8d9097ce9">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82f3fba049bb3d862f79bc626d5edba3">ExtAddrMode</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2404b5dd8b0a6746487c699291c54927">BaseReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243a500ecf43f8be3648cd935b943165">ScaledReg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20bc007be03337ee451abb60d74260b">Scale</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a401a868b47dfbf62f962c746579675">Displacement</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af4e263f5ba20144fc8b9e5b8d9097ce9">Formula</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a264484b5504b59804cf5b2589388a747">Form</a> = <a href="#af4e263f5ba20144fc8b9e5b8d9097ce9a972e73b7a882d0802a4e3a16946a2f94">Formula::Basic</a></td>
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

<p>Used to describe addressing mode similar to <a href="/web-llvm/docs/api/structs/llvm/extaddrmode">ExtAddrMode</a> in CodeGenPrepare.</p>


<p>It holds the register values, the scale value and the displacement. It also holds a descriptor for the expression used to calculate the address from the operands.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Formula {#af4e263f5ba20144fc8b9e5b8d9097ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ExtAddrMode::Formula </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Basic<a id="af4e263f5ba20144fc8b9e5b8d9097ce9a972e73b7a882d0802a4e3a16946a2f94"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SExtScaledReg<a id="af4e263f5ba20144fc8b9e5b8d9097ce9af6dcb4ded13e5a77a3ceafb0e1f844e8"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZExtScaledReg<a id="af4e263f5ba20144fc8b9e5b8d9097ce9ac58efd56ac0f1b362477a5609004f78d"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ExtAddrMode() {#a82f3fba049bb3d862f79bc626d5edba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ExtAddrMode::ExtAddrMode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BaseReg {#a2404b5dd8b0a6746487c699291c54927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::ExtAddrMode::BaseReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a4d52ee98b63ac121fc09f1a5b04358ed">llvm::AArch64InstrInfo::getAddrModeFromMemoryOp</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>.</p>

</div>
</div>

### Displacement {#a6a401a868b47dfbf62f962c746579675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::ExtAddrMode::Displacement = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a4d52ee98b63ac121fc09f1a5b04358ed">llvm::AArch64InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ab8740d2af86692fb934b288974085b13">llvm::X86InstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### Form {#a264484b5504b59804cf5b2589388a747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Formula llvm::ExtAddrMode::Form = <a href="#af4e263f5ba20144fc8b9e5b8d9097ce9a972e73b7a882d0802a4e3a16946a2f94">Formula::Basic</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ab8740d2af86692fb934b288974085b13">llvm::X86InstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### Scale {#ae20bc007be03337ee451abb60d74260b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::ExtAddrMode::Scale = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a0cd7231f32d51864a9e307330e798de9">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::compare</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a4d52ee98b63ac121fc09f1a5b04358ed">llvm::AArch64InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#af16961a6894c56bc7f08641a2538167d">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::isTrivial</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#a13013613b2600aea6438d155a7e4c21b">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#af313a30da49e08d08e305c3e72b32619">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::SetCombinedField</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ab8740d2af86692fb934b288974085b13">llvm::X86InstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### ScaledReg {#a243a500ecf43f8be3648cd935b943165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::ExtAddrMode::ScaledReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a4d52ee98b63ac121fc09f1a5b04358ed">llvm::AArch64InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ab8740d2af86692fb934b288974085b13">llvm::X86InstrInfo::verifyInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">TargetInstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
