---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DebugLineSectionEmitter` Class

<p>This class emits specified line table into the .debug_line section. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DebugLineSectionEmitter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DWARFLinker/Parallel/DebugLineSectionEmitter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a976c30dae98aaea582c811c9f30e37ea">DebugLineSectionEmitter</a> (const Triple &amp;TheTriple, DwarfUnit &amp;U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81feed7a90b5abc9e58b574e7da2a360">emit</a> (const DWARFDebugLine::LineTable &amp;LineTable)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27db9603e334c12c5f9c1ab569db4955">init</a> (Triple TheTriple)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af06d88e59f35c4e81bff57cd604c591f">emitLineTablePrologue</a> (const DWARFDebugLine::Prologue &amp;P, SectionDescriptor &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e347489cb7f459fb5573eb5a78f607">emitLineTablePrologueV2IncludeAndFileTable</a> (const DWARFDebugLine::Prologue &amp;P, SectionDescriptor &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4991d9ab4b8602cecb85b310fca58e6">emitLineTablePrologueV5IncludeAndFileTable</a> (const DWARFDebugLine::Prologue &amp;P, SectionDescriptor &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d5e214cc675a6167c1101c3fc1996f">emitLineTableProloguePayload</a> (const DWARFDebugLine::Prologue &amp;P, SectionDescriptor &amp;Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4344a2f9004096b184ada2956f0a9c92">emitLineTableRows</a> (const DWARFDebugLine::LineTable &amp;LineTable, SectionDescriptor &amp;Section)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb299e54271b59b639b62079c350c982">TheTriple</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c865cf8aa37c86c3b31310a7da0c5c9">U</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800284b7f40709f9afe31517cf3ae7fb">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443356ad76b2bb6af8c39199fa93361c">MAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8784683ba954fce2ecf3d56e78d7352">MC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c0bf6d829edc1e6aad0e5f0d9eabf37">MSTI</a></td>
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

<p>This class emits specified line table into the .debug_line section.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DebugLineSectionEmitter() {#a976c30dae98aaea582c811c9f30e37ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::DebugLineSectionEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a> &amp; U)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a81feed7a90b5abc9e58b574e7da2a360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> &amp; LineTable)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a5e7ab4547b66cde4652390ba796d97a1">llvm::dwarf_linker::parallel::SectionDescriptor::apply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a64dbaf07475300f47afcfd402de0a403">llvm::dwarf_linker::DebugLine</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a25a7fc71830bebb1aa3eda2441838cd6">llvm::dwarf_linker::parallel::SectionDescriptor::emitUnitLength</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a235a5f4eedbfa7b5583ba320309d408f">llvm::dwarf::FormParams::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a2c022a96c1e5b992978a5b39a946fd56">llvm::dwarf_linker::parallel::SectionDescriptorBase::getFormParams</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#aec306fc919df207db6e700f491872d71">llvm::DWARFDebugLine::LineTable::Prologue</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/methods/#gaf5ad0e93c4f3b97d0e8d192675945746">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugLine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitLineTablePrologue() {#af06d88e59f35c4e81bff57cd604c591f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emitLineTablePrologue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; Section)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### emitLineTableProloguePayload() {#a68d5e214cc675a6167c1101c3fc1996f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emitLineTableProloguePayload (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; Section)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### emitLineTablePrologueV2IncludeAndFileTable() {#a13e347489cb7f459fb5573eb5a78f607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emitLineTablePrologueV2IncludeAndFileTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; Section)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### emitLineTablePrologueV5IncludeAndFileTable() {#ab4991d9ab4b8602cecb85b310fca58e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emitLineTablePrologueV5IncludeAndFileTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; Section)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### emitLineTableRows() {#a4344a2f9004096b184ada2956f0a9c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emitLineTableRows (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> &amp; LineTable, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; Section)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### init() {#a27db9603e334c12c5f9c1ab569db4955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::dwarf_linker::parallel::DebugLineSectionEmitter::init (<a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TheTriple)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MAI {#a443356ad76b2bb6af8c39199fa93361c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCAsmInfo&gt; llvm::dwarf_linker::parallel::DebugLineSectionEmitter::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### MC {#aa8784683ba954fce2ecf3d56e78d7352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCContext&gt; llvm::dwarf_linker::parallel::DebugLineSectionEmitter::MC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### MRI {#a800284b7f40709f9afe31517cf3ae7fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCRegisterInfo&gt; llvm::dwarf_linker::parallel::DebugLineSectionEmitter::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### MSTI {#a7c0bf6d829edc1e6aad0e5f0d9eabf37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCSubtargetInfo&gt; llvm::dwarf_linker::parallel::DebugLineSectionEmitter::MSTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### TheTriple {#aeb299e54271b59b639b62079c350c982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::dwarf_linker::parallel::DebugLineSectionEmitter::TheTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

### U {#a8c865cf8aa37c86c3b31310a7da0c5c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfUnit&amp; llvm::dwarf_linker::parallel::DebugLineSectionEmitter::U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/debuglinesectionemitter-h">DebugLineSectionEmitter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
