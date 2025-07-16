---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf/unwindrow
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UnwindRow` Class Reference

<p>A class that represents a single row in the unwind table that is decoded by parsing the DWARF Call Frame Information opcodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf::UnwindRow { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">llvm/DebugInfo/DWARF/DWARFDebugFrame.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb190f316b45043cb43eb55ec4638ec">UnwindRow</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af82b4cc76b1d6facda99155ac4532322">hasAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the address is valid in this object. <a href="#af82b4cc76b1d6facda99155ac4532322">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8f758606628b44835ad3dc5f48395f">getAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the address for this row. <a href="#a4e8f758606628b44835ad3dc5f48395f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24aee0f8d2d5507f47e8cf9b64c0ccdb">setAddress</a> (uint64_t Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the address for this <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a>. <a href="#a24aee0f8d2d5507f47e8cf9b64c0ccdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2549477fe3b82c30914ad2dff01a55a8">slideAddress</a> (uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset the address for this <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a>. <a href="#a2549477fe3b82c30914ad2dff01a55a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73c8bcfeae0f153bbf5df532d134376a">getCFAValue</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aad620cc303324b851e3b2c7701ffb7">getCFAValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf/registerlocations">RegisterLocations</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac95a2b3beafa08219a6cf16b999beef3">getRegisterLocations</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf/registerlocations">RegisterLocations</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf2598c82d6bd0b40feb8e87e71f630">getRegisterLocations</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059c7ec610310aaef931a57658b9ee98">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts, unsigned IndentLevel=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> to the stream. <a href="#a059c7ec610310aaef931a57658b9ee98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba45488ba90cdb6e4b748e39c4d280a">Address</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The address will be valid when parsing the instructions in a <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>. <a href="#a7ba45488ba90cdb6e4b748e39c4d280a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindlocation">UnwindLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35bd4bf271084f77269499894a0ed9c7">CFAValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How to unwind the Call Frame Address (CFA). <a href="#a35bd4bf271084f77269499894a0ed9c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf/registerlocations">RegisterLocations</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46739d519e5d44a60ffd3130eb2a3db8">RegLocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How to unwind all registers in this list. <a href="#a46739d519e5d44a60ffd3130eb2a3db8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class that represents a single row in the unwind table that is decoded by parsing the DWARF Call Frame Information opcodes.</p>


<p>The row consists of an optional address, the rule to unwind the CFA and all rules to unwind any registers. If the address doesn't have a value, this row represents the initial instructions for a <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>. If the address has a value the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> represents a row in the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> for a <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>. The address is the first address for which the CFA location and register rules are valid within a function.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> objects are created by parsing opcodes in the DWARF Call Frame Information and <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> objects are lazily populated and pushed onto a stack in the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a> when evaluating this state machine. Accessors are needed for the address, CFA value, and register locations as the opcodes encode a state machine that produces a sorted array of <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> objects</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindtable">UnwindTable</a>.</p></dd>
</dl>


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnwindRow() {#a4fb190f316b45043cb43eb55ec4638ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf::UnwindRow::UnwindRow ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a059c7ec610310aaef931a57658b9ee98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnwindRow::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, unsigned IndentLevel=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a> to the stream.</p>


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

<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp">DWARFDebugFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#af82b4cc76b1d6facda99155ac4532322">hasAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>.</p>

</div>
</div>

### getAddress() {#a4e8f758606628b44835ad3dc5f48395f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf::UnwindRow::getAddress ()</td>
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

<p>Get the address for this row.</p>


<p>Clients should only call this function after verifying it has a valid address with a call to</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#af82b4cc76b1d6facda99155ac4532322">hasAddress()</a>.</p></dd>
</dl>


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### getCFAValue() {#a73c8bcfeae0f153bbf5df532d134376a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation &amp; llvm::dwarf::UnwindRow::getCFAValue ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### getCFAValue() {#a7aad620cc303324b851e3b2c7701ffb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UnwindLocation &amp; llvm::dwarf::UnwindRow::getCFAValue ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### getRegisterLocations() {#ac95a2b3beafa08219a6cf16b999beef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterLocations &amp; llvm::dwarf::UnwindRow::getRegisterLocations ()</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### getRegisterLocations() {#a6bf2598c82d6bd0b40feb8e87e71f630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterLocations &amp; llvm::dwarf::UnwindRow::getRegisterLocations ()</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### hasAddress() {#af82b4cc76b1d6facda99155ac4532322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf::UnwindRow::hasAddress ()</td>
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

<p>Returns true if the address is valid in this object.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>


<p>Referenced by <a href="#a059c7ec610310aaef931a57658b9ee98">dump</a>.</p>

</div>
</div>

### setAddress() {#a24aee0f8d2d5507f47e8cf9b64c0ccdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf::UnwindRow::setAddress (uint64_t Addr)</td>
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

<p>Set the address for this <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a>.</p>


<p>The address represents the first address for which the CFAValue and RegLocs are valid within a function.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### slideAddress() {#a2549477fe3b82c30914ad2dff01a55a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf::UnwindRow::slideAddress (uint64_t Offset)</td>
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

<p>Offset the address for this <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow">UnwindRow</a>.</p>


<p>The address represents the first address for which the CFAValue and RegLocs are valid within a function. Clients must ensure that this object already has an address (</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#af82b4cc76b1d6facda99155ac4532322">hasAddress()</a>) prior to calling this <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>.</p></dd>
</dl>


<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Address {#a7ba45488ba90cdb6e4b748e39c4d280a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::dwarf::UnwindRow::Address</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The address will be valid when parsing the instructions in a <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>.</p>


<p>If invalid, this object represents the initial instructions of a <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>. Address for row in <a href="/web-llvm/docs/api/classes/llvm/dwarf/fde">FDE</a>, invalid for <a href="/web-llvm/docs/api/classes/llvm/dwarf/cie">CIE</a>.</p>


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### CFAValue {#a35bd4bf271084f77269499894a0ed9c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnwindLocation llvm::dwarf::UnwindRow::CFAValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How to unwind the Call Frame Address (CFA).</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

</div>
</div>

### RegLocs {#a46739d519e5d44a60ffd3130eb2a3db8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterLocations llvm::dwarf::UnwindRow::RegLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How to unwind all registers in this list.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugframe-h">DWARFDebugFrame.h</a>.</p>

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
