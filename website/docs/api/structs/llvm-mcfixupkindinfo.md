---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcfixupkindinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MCFixupKindInfo` Struct

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> independent information on a fixup kind. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MCFixupKindInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">llvm/MC/MCFixupKindInfo.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FixupKindFlags { <a href="#a8f6613f5c0a6dc7dfebce3761963659d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe93ffd2107b04ad99c00d56cfc380c">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A target specific name for the fixup kind. <a href="#a2fe93ffd2107b04ad99c00d56cfc380c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fca5e59be378bc89daa6d2b13eeb27b">TargetOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bit offset to write the relocation into. <a href="#a5fca5e59be378bc89daa6d2b13eeb27b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcb94e2996dda3707eaa1eb1cb79f80">TargetSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bits written by this fixup. <a href="#acfcb94e2996dda3707eaa1eb1cb79f80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae92461ded3785b1595f975afc7d42cb9">Flags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags describing additional information on this fixup kind. <a href="#ae92461ded3785b1595f975afc7d42cb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> independent information on a fixup kind.</p>

<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">MCFixupKindInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### FixupKindFlags {#a8f6613f5c0a6dc7dfebce3761963659d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCFixupKindInfo::FixupKindFlags </td>
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
<td class="doxyEnumItemName">FKF_IsPCRel<a id="a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007"></a></td>
<td class="doxyEnumItemDescription">Is this fixup kind PCrelative? (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FKF_IsAlignedDownTo32Bits<a id="a8f6613f5c0a6dc7dfebce3761963659da4736f387c937299570b8ac87f9d9dd08"></a></td>
<td class="doxyEnumItemDescription">Should this fixup kind force a 4-byte aligned effective PC value? (= (1 &lt;&lt; 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FKF_IsTarget<a id="a8f6613f5c0a6dc7dfebce3761963659da21d215ec80c4375e0df4cf9843b2706c"></a></td>
<td class="doxyEnumItemDescription">Should this fixup be evaluated in a target dependent manner? (= (1 &lt;&lt; 2))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FKF_Constant<a id="a8f6613f5c0a6dc7dfebce3761963659da7e4694d9a51952437c63681c2962873e"></a></td>
<td class="doxyEnumItemDescription">This fixup kind should be resolved if defined (= 1 &lt;&lt; 3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">MCFixupKindInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#ae92461ded3785b1595f975afc7d42cb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCFixupKindInfo::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags describing additional information on this fixup kind.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">MCFixupKindInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a56f972d8aca0c842218ea5b0fd4559a8">llvm::MachObjectWriter::isFixupKindPCRel</a> and <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a73aed7794053594cfb9536d55eac30fd">llvm::ELFObjectWriter::recordRelocation</a>.</p>

</div>
</div>

### Name {#a2fe93ffd2107b04ad99c00d56cfc380c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::MCFixupKindInfo::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A target specific name for the fixup kind.</p>


<p>The names will be unique for distinct kinds on any given target.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">MCFixupKindInfo.h</a>.</p>

</div>
</div>

### TargetOffset {#a5fca5e59be378bc89daa6d2b13eeb27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCFixupKindInfo::TargetOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The bit offset to write the relocation into.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">MCFixupKindInfo.h</a>.</p>

</div>
</div>

### TargetSize {#acfcb94e2996dda3707eaa1eb1cb79f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCFixupKindInfo::TargetSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bits written by this fixup.</p>


<p>The bits are assumed to be contiguous.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">MCFixupKindInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a78aafef1cfb9e7f16f7cd87ac1f806bc">llvm::AVRAsmBackend::adjustFixupValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmbackend-cpp-/lanaiasmbackend/#add6d8b6bffc49d914c7c9de795b39abe">anonymous{LanaiAsmBackend.cpp}::LanaiAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/systemzmcasmbackend/#a9b897519cd359a1020496070eab065a5">anonymous{SystemZMCAsmBackend.cpp}::SystemZMCAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmbackend/#aa68834049f70b768351aa29223d33a44">llvm::MipsAsmBackend::applyFixup</a> and <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#acaeae6c0754ca9264b9ad0bb5c4f5916">llvm::AVRAsmBackend::shouldForceRelocation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixupkindinfo-h">MCFixupKindInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
