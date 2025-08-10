---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/line
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# table emission



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6bbbda77751245651d8a0b64406dd40a">emitLineTablePrologue</a> (const DWARFDebugLine::Prologue &amp;P, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga97a657954ce847425a852e577f83b113">emitLineTableString</a> (const DWARFDebugLine::Prologue &amp;P, const DWARFFormValue &amp;String, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga75f24ccccb80b2ec795ac0e5148c72f9">emitLineTableProloguePayload</a> (const DWARFDebugLine::Prologue &amp;P, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab9eb50627b554fd10d2438155d8601ee">emitLineTablePrologueV2IncludeAndFileTable</a> (const DWARFDebugLine::Prologue &amp;P, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4f6ac912f85770e18de12b1fbff1d0f2">emitLineTablePrologueV5IncludeAndFileTable</a> (const DWARFDebugLine::Prologue &amp;P, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga779f98344ec2bd623e8f88b2244d36aa">emitLineTableRows</a> (const DWARFDebugLine::LineTable &amp;LineTable, MCSymbol *LineEndSym, unsigned AddressByteSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9ce50e5791a6b42e431dd4a36c0966a0">emitIntOffset</a> (uint64_t Offset, dwarf::DwarfFormat Format, uint64_t &amp;SectionSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabbfb6a9e55c2f7737c37e4f0ad7ecc6c">emitLabelDifference</a> (const MCSymbol *Hi, const MCSymbol *Lo, dwarf::DwarfFormat Format, uint64_t &amp;SectionSize)</td>
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


<div class="doxySectionDef">

## Functions

### emitIntOffset() {#ga9ce50e5791a6b42e431dd4a36c0966a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitIntOffset (uint64_t Offset, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> Format, uint64_t &amp; SectionSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1184 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitLabelDifference() {#gabbfb6a9e55c2f7737c37e4f0ad7ecc6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLabelDifference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Hi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Lo, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> Format, uint64_t &amp; SectionSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitLineTablePrologue() {#ga6bbbda77751245651d8a0b64406dd40a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLineTablePrologue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugLineStrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitLineTableProloguePayload() {#ga75f24ccccb80b2ec795ac0e5148c72f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLineTableProloguePayload (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugLineStrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 999 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitLineTablePrologueV2IncludeAndFileTable() {#gab9eb50627b554fd10d2438155d8601ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLineTablePrologueV2IncludeAndFileTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugLineStrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitLineTablePrologueV5IncludeAndFileTable() {#ga4f6ac912f85770e18de12b1fbff1d0f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLineTablePrologueV5IncludeAndFileTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugLineStrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 894 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitLineTableRows() {#ga779f98344ec2bd623e8f88b2244d36aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLineTableRows (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> &amp; LineTable, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * LineEndSym, unsigned AddressByteSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

### emitLineTableString() {#ga97a657954ce847425a852e577f83b113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfStreamer::emitLineTableString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/prologue">DWARFDebugLine::Prologue</a> &amp; P, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> &amp; String, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugStrPool, <a href="/web-llvm/docs/api/namespaces/llvm/#aca9ad9fe13b3bf966c4c7dd96cec79df">OffsetsStringPool</a> &amp; DebugLineStrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarfstreamer-h">DWARFStreamer.h</a>, definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarfstreamer-cpp">DWARFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
