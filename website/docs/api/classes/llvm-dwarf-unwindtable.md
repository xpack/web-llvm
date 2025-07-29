---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf/unwindtable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `UnwindTable` Class

<p>A class that contains all <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> objects for an <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a> or a single unwind row for a <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf::UnwindTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">llvm/DebugInfo/DWARF/DWARFDebugFrame.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce03b74193b41b66f2785fdddf68c02">RowContainer</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0b9b61eef1d9d28ef8c915c764ce312">iterator</a> = RowContainer::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46b7f4d9264ea5510899b04abb1155e">const_iterator</a> = RowContainer::const_iterator</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af91388239874b6f70e8ce5ea83b5290b">operator[]</a> (size_t Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55fa7ba0db72f9f6ed7698249caa893">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae0b9b61eef1d9d28ef8c915c764ce312">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a62f38691413241b28c4b5ed45476f">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad46b7f4d9264ea5510899b04abb1155e">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5409cd7f3af6bd405ab6e422310a7a3">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae0b9b61eef1d9d28ef8c915c764ce312">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8927dad5c5c52329ffac6f47cd1831d">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad46b7f4d9264ea5510899b04abb1155e">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63da96eaa149274a8acd5df62e308d60">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad613da68f9aaa8e973f1140df8761def">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts, unsigned IndentLevel=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> to the stream. <a href="#ad613da68f9aaa8e973f1140df8761def">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27a9e392fa6593b1149cd43e9dd59ed">parseRows</a> (const CFIProgram &amp;CFIP, UnwindRow &amp;CurrRow, const RegisterLocations *InitialLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the information in the <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram">CFIProgram</a> and update the CurrRow object that the state machine describes. <a href="#ac27a9e392fa6593b1149cd43e9dd59ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acce03b74193b41b66f2785fdddf68c02">RowContainer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06750058746671855aac9d3b821c10b7">Rows</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9fc943355498c6e4d88fa9dd01b557">EndAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The end address when data is extracted from a <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>. <a href="#a3f9fc943355498c6e4d88fa9dd01b557">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49db346e41a5b9f352648d0d99b63d57">create</a> (const CIE *Cie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> from a Common Information Entry (<a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>). <a href="#a49db346e41a5b9f352648d0d99b63d57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6074029e29715d542749847edf58e3c">create</a> (const FDE *Fde)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> from a Frame Descriptor Entry (<a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>). <a href="#ae6074029e29715d542749847edf58e3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class that contains all <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> objects for an <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a> or a single unwind row for a <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>.</p>


<p>To unwind an address the rows, which are sorted by start address, can be searched to find the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> with the lowest starting address that is greater than or equal to the address that is being looked up.</p>


<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ad46b7f4d9264ea5510899b04abb1155e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf::UnwindTable::const_iterator =  RowContainer::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### iterator {#ae0b9b61eef1d9d28ef8c915c764ce312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf::UnwindTable::iterator =  RowContainer::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### RowContainer {#acce03b74193b41b66f2785fdddf68c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf::UnwindTable::RowContainer =  std::vector&lt;UnwindRow&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#af91388239874b6f70e8ce5ea83b5290b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UnwindRow &amp; llvm::dwarf::UnwindTable::operator[] (size_t Index)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab55fa7ba0db72f9f6ed7698249caa893">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#ab9a62f38691413241b28c4b5ed45476f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::dwarf::UnwindTable::begin ()</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### begin() {#ad5409cd7f3af6bd405ab6e422310a7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::dwarf::UnwindTable::begin ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### dump() {#ad613da68f9aaa8e973f1140df8761def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnwindTable::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, unsigned IndentLevel=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> to the stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>the stream to use for output.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MRI</td>
<td class="doxyParamItemDescription"><p>register information that helps emit register names insteead of raw register numbers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsEH</td>
<td class="doxyParamItemDescription"><p>true if the DWARF Call Frame Information is from .eh_frame instead of from .debug_frame. This is needed for register number conversion because some register numbers differ between the two sections for certain architectures like x86.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IndentLevel</td>
<td class="doxyParamItemDescription"><p>specify the indent level as an integer. The <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> will be output to the stream preceded by 2 * IndentLevel number of spaces.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a3d665e7931973f7abe564f8f28caebc4">llvm::dwarf::operator&lt;&lt;</a>.</p>

</div>
</div>

### end() {#ab8927dad5c5c52329ffac6f47cd1831d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::dwarf::UnwindTable::end ()</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### end() {#a63da96eaa149274a8acd5df62e308d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::dwarf::UnwindTable::end ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### size() {#ab55fa7ba0db72f9f6ed7698249caa893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::dwarf::UnwindTable::size ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>


<p>Referenced by <a href="#af91388239874b6f70e8ce5ea83b5290b">operator[]</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### parseRows() {#ac27a9e392fa6593b1149cd43e9dd59ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error UnwindTable::parseRows (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram">CFIProgram</a> &amp; CFIP, <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> &amp; CurrRow, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf/registerlocations">RegisterLocations</a> * InitialLocs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the information in the <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram">CFIProgram</a> and update the CurrRow object that the state machine describes.</p>


<p>This is an internal implementation that emulates the state machine described in the DWARF Call Frame Information opcodes and will push CurrRow onto the Rows container when needed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CFIP</td>
<td class="doxyParamItemDescription"><p>the CFI program that contains the opcodes from a <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a> or <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CurrRow</td>
<td class="doxyParamItemDescription"><p>the current row to modify while parsing the state machine.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InitialLocs</td>
<td class="doxyParamItemDescription"><p>If non-NULL, we are parsing a <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a> and this contains the initial register locations from the <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>. If NULL, then a <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>'s opcodes are being parsed and this is not needed. This is used for the DW_CFA_restore and DW_CFA_restore_extended opcodes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EndAddress {#a3f9fc943355498c6e4d88fa9dd01b557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::dwarf::UnwindTable::EndAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The end address when data is extracted from a <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>.</p>


<p>This value will be invalid when a <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> is extracted from a <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>.</p>


<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### Rows {#a06750058746671855aac9d3b821c10b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RowContainer llvm::dwarf::UnwindTable::Rows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a49db346e41a5b9f352648d0d99b63d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; UnwindTable &gt; UnwindTable::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a> * Cie)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> from a Common Information Entry (<a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Cie</td>
<td class="doxyParamItemDescription"><p>The Common Information Entry to extract the table from. The <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram">CFIProgram</a> is retrieved from the <em>Cie</em> object and used to create the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error if the DWARF Call Frame Information opcodes have state machine errors, or a valid <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> otherwise.</p></dd>
</dl>


<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf/frameentry/#a3d7e66a7f247e5469c8c03e856afa72c">llvm::dwarf::FrameEntry::cfis</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram/#aa27a439f680456d46e55ec2616d1ce34">llvm::dwarf::CFIProgram::empty</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation/#a6fbbea6b3966c62608feb63d6d203ed5add7aa992a49f11aaaf8acb7bde4df002">llvm::dwarf::UnwindLocation::Unspecified</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie/#ad37449ab3df9cdf881d320defb0a9c20">llvm::dwarf::CIE::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde/#aac5d33bcc6ae2563f3756bd749c2e0d7">llvm::dwarf::FDE::dump</a>.</p>

</div>
</div>

### create() {#ae6074029e29715d542749847edf58e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; UnwindTable &gt; UnwindTable::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a> * Fde)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> from a Frame Descriptor Entry (<a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fde</td>
<td class="doxyParamItemDescription"><p>The Frame Descriptor Entry to extract the table from. The <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram">CFIProgram</a> is retrieved from the <em>Fde</em> object and used to create the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error if the DWARF Call Frame Information opcodes have state machine errors, or a valid <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> otherwise.</p></dd>
</dl>


<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf/frameentry/#a3d7e66a7f247e5469c8c03e856afa72c">llvm::dwarf::FrameEntry::cfis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram/#aa27a439f680456d46e55ec2616d1ce34">llvm::dwarf::CFIProgram::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde/#a02265302ebbef60876aa94c264256283">llvm::dwarf::FDE::getAddressRange</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde/#a054068af1069b82b93e1bfef2bb9b678">llvm::dwarf::FDE::getInitialLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde/#a3f568b29938c7d410731e95098e20872">llvm::dwarf::FDE::getLinkedCIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/frameentry/#ad4283237120fe503e9e2a733b517b417">llvm::dwarf::FrameEntry::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation/#a6fbbea6b3966c62608feb63d6d203ed5add7aa992a49f11aaaf8acb7bde4df002">llvm::dwarf::UnwindLocation::Unspecified</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
