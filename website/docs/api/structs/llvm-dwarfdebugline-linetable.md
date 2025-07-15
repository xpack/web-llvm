---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfdebugline/linetable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LineTable` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFDebugLine::LineTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">llvm/DebugInfo/DWARF/DWARFDebugLine.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f57e6a0308c52bd5aa091e6859cdc7b">RowVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row">Row</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9d6a570c7f3e89db6b2f4515b09e7f">RowIter</a> = RowVector::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2919d6300605bda7a90fb31d50ce59b">SequenceVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence">Sequence</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a994aef4b8157328dee24fb9cf21073ee">SequenceIter</a> = SequenceVector::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd86b3d05fda5dda8b7fa48a59d6907">LineTable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade555a72097f42527f16b38deae6a164">appendRow</a> (const DWARFDebugLine::Row &amp;R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2fc136fdf278eea61ef4e3405fa3323">appendSequence</a> (const DWARFDebugLine::Sequence &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07f83f8b45826aae82ba63fef9bcb70c">lookupAddress</a> (object::SectionedAddress Address, bool *IsApproximateLine=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index of the row with file/line info for a given address, or UnknownRowIndex if there is no such row. <a href="#a07f83f8b45826aae82ba63fef9bcb70c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a910420e98a8f344483b3c461314898e3">lookupAddressRange</a> (object::SectionedAddress Address, uint64_t Size, std::vector&lt; uint32_t &gt; &amp;Result) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a4fc961700aac4d048071a4b5b8f39">hasFileAtIndex</a> (uint64_t FileIndex) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f2ba94afad1a1ef368d7d588ad5b33">getLastValidFileIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72aff7095112320360cc07670524728e">getFileNameByIndex</a> (uint64_t FileIndex, StringRef CompDir, DILineInfoSpecifier::FileLineInfoKind Kind, std::string &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts filename by its index in filename table in prologue. <a href="#a72aff7095112320360cc07670524728e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d28efc861659400235ff1b387c6aa3">getFileLineInfoForAddress</a> (object::SectionedAddress Address, bool Approximate, const char *CompDir, DILineInfoSpecifier::FileLineInfoKind Kind, DILineInfo &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fills the Result argument with the file and line information corresponding to Address. <a href="#a21d28efc861659400235ff1b387c6aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc4df37ed6fd36a653da7966308f0f5">getDirectoryForEntry</a> (const FileNameEntry &amp;Entry, std::string &amp;Directory) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts directory name by its Entry in include directories table in prologue. <a href="#a1bc4df37ed6fd36a653da7966308f0f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d8615950d1fa3c1d30f813b8b7d44c">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOptions) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc9bbef9145e28438bdceef1270a76d">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49eb2522e1fc6988c75f9936c3061bb6">parse</a> (DWARFDataExtractor &amp;DebugLineData, uint64_t *OffsetPtr, const DWARFContext &amp;Ctx, const DWARFUnit *U, function_ref&lt; void(Error)&gt; RecoverableErrorHandler, raw_ostream *OS=nullptr, bool Verbose=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse prologue and all rows. <a href="#a49eb2522e1fc6988c75f9936c3061bb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665ead7fd167e55705d4622336fb0b75">findRowInSeq</a> (const DWARFDebugLine::Sequence &amp;Seq, object::SectionedAddress Address) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad5c762f68ce8af77910e98e8d65cd9d">getSourceByIndex</a> (uint64_t FileIndex, DILineInfoSpecifier::FileLineInfoKind Kind) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66800b98bf8c472f8f9ffc707bbe03b3">lookupAddressImpl</a> (object::SectionedAddress Address, bool *IsApproximateLine=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee18d61e19c07d80c832dec784d96ff">lookupAddressRangeImpl</a> (object::SectionedAddress Address, uint64_t Size, std::vector&lt; uint32_t &gt; &amp;Result) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ad4224d48c9ee60e86bb37ef955a69">UnknownRowIndex</a> = UINT32_MAX</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an invalid row. <a href="#a21ad4224d48c9ee60e86bb37ef955a69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec306fc919df207db6e700f491872d71">Prologue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9f57e6a0308c52bd5aa091e6859cdc7b">RowVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f2df6a1aaacec42c6ded0585a11e4d">Rows</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa2919d6300605bda7a90fb31d50ce59b">SequenceVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada29eb4559f13bb34130942122c76ec7">Sequences</a></td>
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


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### RowIter {#a7a9d6a570c7f3e89db6b2f4515b09e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFDebugLine::LineTable::RowIter =  RowVector::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>

</div>
</div>

### RowVector {#a9f57e6a0308c52bd5aa091e6859cdc7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFDebugLine::LineTable::RowVector =  std::vector&lt;Row&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>

</div>
</div>

### SequenceIter {#a994aef4b8157328dee24fb9cf21073ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFDebugLine::LineTable::SequenceIter =  SequenceVector::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>

</div>
</div>

### SequenceVector {#aa2919d6300605bda7a90fb31d50ce59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFDebugLine::LineTable::SequenceVector =  std::vector&lt;Sequence&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LineTable() {#a7bd86b3d05fda5dda8b7fa48a59d6907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDebugLine::LineTable::LineTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>Reference <a href="#a4fc9bbef9145e28438bdceef1270a76d">clear</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendRow() {#ade555a72097f42527f16b38deae6a164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFDebugLine::LineTable::appendRow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row">DWARFDebugLine::Row</a> &amp; R)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#a08f2df6a1aaacec42c6ded0585a11e4d">Rows</a>.</p>

</div>
</div>

### appendSequence() {#aa2fc136fdf278eea61ef4e3405fa3323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFDebugLine::LineTable::appendSequence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence">DWARFDebugLine::Sequence</a> &amp; S)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#ada29eb4559f13bb34130942122c76ec7">Sequences</a>.</p>

</div>
</div>

### clear() {#a4fc9bbef9145e28438bdceef1270a76d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugLine::LineTable::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="#aec306fc919df207db6e700f491872d71">Prologue</a>, <a href="#a08f2df6a1aaacec42c6ded0585a11e4d">Rows</a> and <a href="#ada29eb4559f13bb34130942122c76ec7">Sequences</a>.</p>


<p>Referenced by <a href="#a7bd86b3d05fda5dda8b7fa48a59d6907">LineTable</a> and <a href="#a49eb2522e1fc6988c75f9936c3061bb6">parse</a>.</p>

</div>
</div>

### dump() {#ae2d8615950d1fa3c1d30f813b8b7d44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugLine::LineTable::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOptions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#ac3f903d6b8cf4b48c2f1c72dabfbee38">llvm::DWARFDebugLine::Row::dumpTableHeader</a>, <a href="#aec306fc919df207db6e700f491872d71">Prologue</a> and <a href="#a08f2df6a1aaacec42c6ded0585a11e4d">Rows</a>.</p>

</div>
</div>

### getDirectoryForEntry() {#a1bc4df37ed6fd36a653da7966308f0f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugLine::LineTable::getDirectoryForEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry">FileNameEntry</a> &amp; Entry, std::string &amp; Directory)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts directory name by its Entry in include directories table in prologue.</p>


<p>Returns true on success.</p>


<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1520 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="#aec306fc919df207db6e700f491872d71">Prologue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a>.</p>

</div>
</div>

### getFileLineInfoForAddress() {#a21d28efc861659400235ff1b387c6aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugLine::LineTable::getFileLineInfoForAddress (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address, bool Approximate, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CompDir, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3">DILineInfoSpecifier::FileLineInfoKind</a> Kind, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fills the Result argument with the file and line information corresponding to Address.</p>


<p>Returns true on success.</p>


<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1501 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#a93a4cbd3adbf703afef361afd4c0c08a">llvm::DWARFDebugLine::Row::Column</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#a4a41463a44a6f4e0a44d061579d1356a">llvm::DWARFDebugLine::Row::Discriminator</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#a4441d4ed4fe87fad35626d9c8a02b696">llvm::DWARFDebugLine::Row::File</a>, <a href="#a72aff7095112320360cc07670524728e">getFileNameByIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#a4045d634bf622d7852f9bde7d5644ae7">llvm::DWARFDebugLine::Row::Line</a>, <a href="#a07f83f8b45826aae82ba63fef9bcb70c">lookupAddress</a> and <a href="#a08f2df6a1aaacec42c6ded0585a11e4d">Rows</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>.</p>

</div>
</div>

### getFileNameByIndex() {#a72aff7095112320360cc07670524728e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugLine::LineTable::getFileNameByIndex (uint64_t FileIndex, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CompDir, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3">DILineInfoSpecifier::FileLineInfoKind</a> Kind, std::string &amp; Result)</td>
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

<p>Extracts filename by its index in filename table in prologue.</p>


<p>In Dwarf 4, the files are 1-indexed and the current compilation file name is not represented in the list. In DWARF v5, the files are 0-indexed and the primary source file has the index 0. Returns true on success.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#aec306fc919df207db6e700f491872d71">Prologue</a>.</p>


<p>Referenced by <a href="#a21d28efc861659400235ff1b387c6aa3">getFileLineInfoForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a55f204d9568a58fbc54ad04343452904">llvm::DWARFContext::getLineInfoForAddressRange</a>.</p>

</div>
</div>

### getLastValidFileIndex() {#a21f2ba94afad1a1ef368d7d588ad5b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DWARFDebugLine::LineTable::getLastValidFileIndex ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#aec306fc919df207db6e700f491872d71">Prologue</a>.</p>

</div>
</div>

### hasFileAtIndex() {#a45a4fc961700aac4d048071a4b5b8f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDebugLine::LineTable::hasFileAtIndex (uint64_t FileIndex)</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Reference <a href="#aec306fc919df207db6e700f491872d71">Prologue</a>.</p>

</div>
</div>

### lookupAddress() {#a07f83f8b45826aae82ba63fef9bcb70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DWARFDebugLine::LineTable::lookupAddress (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address, bool * IsApproximateLine=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the index of the row with file/line info for a given address, or UnknownRowIndex if there is no such row.</p>

<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a> and <a href="#a21ad4224d48c9ee60e86bb37ef955a69">UnknownRowIndex</a>.</p>


<p>Referenced by <a href="#a21d28efc861659400235ff1b387c6aa3">getFileLineInfoForAddress</a>.</p>

</div>
</div>

### lookupAddressRange() {#a910420e98a8f344483b3c461314898e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugLine::LineTable::lookupAddressRange (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address, uint64_t Size, std::vector&lt; uint32_t &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1365 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress/#aab5f6719f1bf1cfd6c53e95ebce09470">llvm::object::SectionedAddress::UndefSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a55f204d9568a58fbc54ad04343452904">llvm::DWARFContext::getLineInfoForAddressRange</a>.</p>

</div>
</div>

### parse() {#a49eb2522e1fc6988c75f9936c3061bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFDebugLine::LineTable::parse (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; DebugLineData, uint64_t * OffsetPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * OS=nullptr, bool Verbose=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse prologue and all rows.</p>

<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/parsingstate/opcodeadvanceresults/#af6d2c0991b6f5412ee553b2800dd4a80">llvm::DWARFDebugLine::ParsingState::OpcodeAdvanceResults::AddrDelta</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/parsingstate/specialopcodedelta/#a2891bfde0a32912b6c8233596b84f0c4">llvm::DWARFDebugLine::ParsingState::SpecialOpcodeDelta::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/parsingstate/addropindexdelta/#a1df7aab7a2e0e0abbd2a4719ad878382">llvm::DWARFDebugLine::ParsingState::AddrOpIndexDelta::AddrOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4fc9bbef9145e28438bdceef1270a76d">clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ad31a7a9cab8288e009f13cfabc5afc13">llvm::dwarf::computeTombstoneAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a0c3905b85f3ac726af3668b04cc9fa68">llvm::DWARFFormValue::createFromPValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a58762abf82ba4b9f2f46d3b89070d6c1">DenseMapInfo&lt; LocallyHashedType &gt;::Tombstone</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#ac0c5fbd2279527ccfc0c0ef76c19ddce">llvm::DWARFDebugLine::FileNameEntry::DirIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a0373b5360a46d14a991fea39390d7240">llvm::DWARFFormValue::dumpAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#ac3f903d6b8cf4b48c2f1c72dabfbee38">llvm::DWARFDebugLine::Row::dumpTableHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a727b157e8418a101ec69dcb2e9ceea39">llvm::DataExtractor::getAddressSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a17638a9e9146a6f6feef1adb50c53d2b">llvm::DataExtractor::getCStr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a01887ce3b95212d5c5b89887c93ad662">llvm::DWARFDataExtractor::getRelocatedAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor/#a814a7655e692e4f880b38eed143052fb">llvm::DWARFDataExtractor::getRelocatedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a88a902fb0c1d600e6b4fe880d770acdf">llvm::DataExtractor::getSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a45ee696c4102751e0194a0210c07dac0">llvm::DataExtractor::getU8</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a6f2f68613d44758a66e49320fb075a02">llvm::DataExtractor::getULEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba53a9e57a679708b2d8ff0ccd8ec96b18">llvm::illegal_byte_sequence</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad7e3a2f9134fa59a38cc0a86acaaf351">llvm::DataExtractor::isValidOffsetForDataOfSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#a1ad164d81f384c7382b578b6d3931e84">llvm::DWARFDebugLine::FileNameEntry::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/parsingstate/specialopcodedelta/#ac54d0cd323dc078ec0fd6b5dcc16b7a4">llvm::DWARFDebugLine::ParsingState::SpecialOpcodeDelta::Line</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga00d9040382b3320ada56754c971969ea">llvm::dwarf::LNExtendedString</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf2319ad7b6894302babb1769c87c13ef">llvm::dwarf::LNStandardString</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#a2cfc2ae9340176e7522776e16aff626b">llvm::DWARFDebugLine::FileNameEntry::ModTime</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/filenameentry/#a87729f4fadb52e26d3e6b551f476d331">llvm::DWARFDebugLine::FileNameEntry::Name</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/parsingstate/specialopcodedelta/#ad7e237002203fbb56b365546b6caafc6">llvm::DWARFDebugLine::ParsingState::SpecialOpcodeDelta::OpIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/parsingstate/addropindexdelta/#a6cc7a6f7d9ea63de24e73f146f796752">llvm::DWARFDebugLine::ParsingState::AddrOpIndexDelta::OpIndexDelta</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/parsingstate/opcodeadvanceresults/#a5b6dbeaf6c9d40d13565b5666152ef7e">llvm::DWARFDebugLine::ParsingState::OpcodeAdvanceResults::OpIndexDelta</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence/#a59805c2dc5142a4bad83a16d61e0fdeb">llvm::DWARFDebugLine::Sequence::orderByHighPC</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp/#aeada617013dbf8ce141cb2e6144edacb">parseULEB128</a>, <a href="#aec306fc919df207db6e700f491872d71">Prologue</a>, <a href="#a08f2df6a1aaacec42c6ded0585a11e4d">Rows</a>, <a href="#ada29eb4559f13bb34130942122c76ec7">Sequences</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad1f5d1feac4b501f815939a0ca847d41">llvm::DataExtractor::setAddressSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a13f08bc0715c6ccbe15c82f2fc9e61ca">llvm::DataExtractor::size</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#aa4c4043f99a1a5b283741ef4c7cf2464">llvm::DataExtractor::skip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a3453d69f4b4b74c0cf69808bc7d1c8b0">llvm::DataExtractor::Cursor::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a22c134bb6de5493faf9c7076ef4dfcac">llvm::DataExtractor::Cursor::tell</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findRowInSeq() {#a665ead7fd167e55705d4622336fb0b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DWARFDebugLine::LineTable::findRowInSeq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/sequence">DWARFDebugLine::Sequence</a> &amp; Seq, <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1288 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>

</div>
</div>

### getSourceByIndex() {#aad5c762f68ce8af77910e98e8d65cd9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; DWARFDebugLine::LineTable::getSourceByIndex (uint64_t FileIndex, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3">DILineInfoSpecifier::FileLineInfoKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1430 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>

</div>
</div>

### lookupAddressImpl() {#a66800b98bf8c472f8f9ffc707bbe03b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DWARFDebugLine::LineTable::lookupAddressImpl (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address, bool * IsApproximateLine=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1332 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>

</div>
</div>

### lookupAddressRangeImpl() {#a3ee18d61e19c07d80c832dec784d96ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDebugLine::LineTable::lookupAddressRangeImpl (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address, uint64_t Size, std::vector&lt; uint32_t &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>, definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Prologue {#aec306fc919df207db6e700f491872d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct Prologue llvm::DWARFDebugLine::LineTable::Prologue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a4fc9bbef9145e28438bdceef1270a76d">clear</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="#ae2d8615950d1fa3c1d30f813b8b7d44c">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter/#a81feed7a90b5abc9e58b574e7da2a360">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#ad43ae71d8137d5a78d559644f17eb162">llvm::dwarf_linker::classic::DwarfStreamer::emitLineTableForUnit</a>, <a href="#a1bc4df37ed6fd36a653da7966308f0f5">getDirectoryForEntry</a>, <a href="#a72aff7095112320360cc07670524728e">getFileNameByIndex</a>, <a href="#a21f2ba94afad1a1ef368d7d588ad5b33">getLastValidFileIndex</a>, <a href="#a45a4fc961700aac4d048071a4b5b8f39">hasFileAtIndex</a> and <a href="#a49eb2522e1fc6988c75f9936c3061bb6">parse</a>.</p>

</div>
</div>

### Rows {#a08f2df6a1aaacec42c6ded0585a11e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RowVector llvm::DWARFDebugLine::LineTable::Rows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#ade555a72097f42527f16b38deae6a164">appendRow</a>, <a href="#a4fc9bbef9145e28438bdceef1270a76d">clear</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="#ae2d8615950d1fa3c1d30f813b8b7d44c">dump</a>, <a href="#a21d28efc861659400235ff1b387c6aa3">getFileLineInfoForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a55f204d9568a58fbc54ad04343452904">llvm::DWARFContext::getLineInfoForAddressRange</a> and <a href="#a49eb2522e1fc6988c75f9936c3061bb6">parse</a>.</p>

</div>
</div>

### Sequences {#ada29eb4559f13bb34130942122c76ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SequenceVector llvm::DWARFDebugLine::LineTable::Sequences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#aa2fc136fdf278eea61ef4e3405fa3323">appendSequence</a>, <a href="#a4fc9bbef9145e28438bdceef1270a76d">clear</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a> and <a href="#a49eb2522e1fc6988c75f9936c3061bb6">parse</a>.</p>

</div>
</div>

### UnknownRowIndex {#a21ad4224d48c9ee60e86bb37ef955a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::DWARFDebugLine::LineTable::UnknownRowIndex = UINT32_MAX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an invalid row.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a>.</p>


<p>Referenced by <a href="#a07f83f8b45826aae82ba63fef9bcb70c">lookupAddress</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugline-h">DWARFDebugLine.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugline-cpp">DWARFDebugLine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
