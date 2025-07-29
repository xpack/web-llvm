---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/labelsym
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LabelSym` Class



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::LabelSym { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">llvm/DebugInfo/CodeView/SymbolRecord.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecord">SymbolRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26721bbf19ca006f7046e97a9cf61e2">LabelSym</a> (SymbolRecordKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2cd40280b2cfa3f8c0df34f4e5ed637">LabelSym</a> (uint32_t RecordOffset)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4de0a54d8af00d8f03c3e171bceca439">getRelocationOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a3be3fe78d5c3e1f9236f9852861ea">CodeOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93ccc3951ded5f45d28e8641569dcdc2">Segment</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0cc2805b6b89a94c5b5983f95367168c">ProcSymFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa7f886d4835fda38b7fe4ca6f7e2a1">Flags</a> = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0cc2805b6b89a94c5b5983f95367168ca6adf97f83acf6453d4a6a4b1070f3754">ProcSymFlags::None</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa120a6abac9e719a718a4236e5c34cd6">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70b9ffb9e6110a68a565735f2f3c623">RecordOffset</a> = 0</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eeaf138afe8ae8b5dd57c8214813aad">RelocationOffset</a> = 4</td>
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


<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LabelSym() {#ac26721bbf19ca006f7046e97a9cf61e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::LabelSym::LabelSym (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a718bd404e8a87ee5e1a21b0c267cde17">SymbolRecordKind</a> Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecord/#a70c9046ac3e018331204b9f904641d13">llvm::codeview::SymbolRecord::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecord/#a51a0afc589bb5038be677a47f781d39e">llvm::codeview::SymbolRecord::SymbolRecord</a>.</p>


<p>Referenced by <a href="#ac2cd40280b2cfa3f8c0df34f4e5ed637">LabelSym</a>.</p>

</div>
</div>

### LabelSym() {#ac2cd40280b2cfa3f8c0df34f4e5ed637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::LabelSym::LabelSym (uint32_t RecordOffset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>References <a href="#ac26721bbf19ca006f7046e97a9cf61e2">LabelSym</a>, <a href="#ae70b9ffb9e6110a68a565735f2f3c623">RecordOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecord/#a51a0afc589bb5038be677a47f781d39e">llvm::codeview::SymbolRecord::SymbolRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocationOffset() {#a4de0a54d8af00d8f03c3e171bceca439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LabelSym::getRelocationOffset ()</td>
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



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>Reference <a href="#ae70b9ffb9e6110a68a565735f2f3c623">RecordOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CodeOffset {#ac1a3be3fe78d5c3e1f9236f9852861ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LabelSym::CodeOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>

</div>
</div>

### Flags {#afaa7f886d4835fda38b7fe4ca6f7e2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProcSymFlags llvm::codeview::LabelSym::Flags = <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0cc2805b6b89a94c5b5983f95367168ca6adf97f83acf6453d4a6a4b1070f3754">ProcSymFlags::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>

</div>
</div>

### Name {#aa120a6abac9e719a718a4236e5c34cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::codeview::LabelSym::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>

</div>
</div>

### RecordOffset {#ae70b9ffb9e6110a68a565735f2f3c623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LabelSym::RecordOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>Referenced by <a href="#a4de0a54d8af00d8f03c3e171bceca439">getRelocationOffset</a> and <a href="#ac2cd40280b2cfa3f8c0df34f4e5ed637">LabelSym</a>.</p>

</div>
</div>

### Segment {#a93ccc3951ded5f45d28e8641569dcdc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::codeview::LabelSym::Segment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### RelocationOffset {#a0eeaf138afe8ae8b5dd57c8214813aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::LabelSym::RelocationOffset = 4</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
