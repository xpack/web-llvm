---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/linkingglobaldata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LinkingGlobalData` Class

<p>This class keeps data and services common for the whole linking process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::LinkingGlobalData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinker/Parallel/DWARFLinkerGlobalData.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a4e82d98d22361038741bca9bd34bca85">llvm::parallel::PerThreadBumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af56aae571dbc48a80f80f6bc5fca0484">getAllocator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns global per-thread allocator. <a href="#af56aae571dbc48a80f80f6bc5fca0484">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpool">StringPool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c472d9461a75e6b9122f1d3f023b1b4">getStringPool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns global string pool. <a href="#a9c472d9461a75e6b9122f1d3f023b1b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkeroptions">DWARFLinkerOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f4587714d255c918f0e0c659fac37d">getOptions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns linking options. <a href="#a39f4587714d255c918f0e0c659fac37d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a791ea0b58e5fcb4088765a0cc94da8ef">setWarningHandler</a> (MessageHandlerTy Handler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set warning handler. <a href="#a791ea0b58e5fcb4088765a0cc94da8ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4634136a66c62d624497559373d4e0d6">setErrorHandler</a> (MessageHandlerTy Handler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set error handler. <a href="#a4634136a66c62d624497559373d4e0d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392281dd0eb4dba44c61b52e2b8004b0">warn</a> (const Twine &amp;Warning, StringRef Context, const DWARFDie *DIE=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report warning. <a href="#a392281dd0eb4dba44c61b52e2b8004b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4430fdd1c34d0b9d5014d3cbbddc9916">warn</a> (Error Warning, StringRef Context, const DWARFDie *DIE=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report warning. <a href="#a4430fdd1c34d0b9d5014d3cbbddc9916">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476dbecec9ff9fa8130cfc45b3763501">error</a> (const Twine &amp;Err, StringRef Context, const DWARFDie *DIE=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report error. <a href="#a476dbecec9ff9fa8130cfc45b3763501">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7568407b9d745b41102b67fab20774a6">error</a> (Error Err, StringRef Context, const DWARFDie *DIE=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report error. <a href="#a7568407b9d745b41102b67fab20774a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a716de5336a08b726d057c6b7ed287ce5">setTargetTriple</a> (const Triple &amp;TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set target triple. <a href="#a716de5336a08b726d057c6b7ed287ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::reference_wrapper&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4955c14d8328cf5fb3b7ac211a5cc36">getTargetTriple</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optionally return target triple. <a href="#ab4955c14d8328cf5fb3b7ac211a5cc36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a4e82d98d22361038741bca9bd34bca85">llvm::parallel::PerThreadBumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b57a7742bcf6335816aa43a28d051f3">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpool">StringPool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04dfd5580e10d8552aefd20006602d00">Strings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkeroptions">DWARFLinkerOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31757b06282b3db90dfeceb6b0863585">Options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#af378e877afcc692f3c5a240ebef817ca">MessageHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe5527612657a5c570cb7573f5aa66e">WarningHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#af378e877afcc692f3c5a240ebef817ca">MessageHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab770f4486b704032ad1211dc67b109f3">ErrorHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9799b2e7f33a51343b80a494034e3c">TargetTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> for output data. <a href="#a5b9799b2e7f33a51343b80a494034e3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc90ab96f8935aac04de7e239f6a0e5b">DWARFLinkerImpl</a></td>
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

<p>This class keeps data and services common for the whole linking process.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### error() {#a476dbecec9ff9fa8130cfc45b3763501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::LinkingGlobalData::error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Err, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> * DIE=nullptr)</td>
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

<p>Report error.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Reference <a href="#ab770f4486b704032ad1211dc67b109f3">ErrorHandler</a>.</p>

</div>
</div>

### error() {#a7568407b9d745b41102b67fab20774a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::LinkingGlobalData::error (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> * DIE=nullptr)</td>
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

<p>Report error.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### getAllocator() {#af56aae571dbc48a80f80f6bc5fca0484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::parallel::PerThreadBumpPtrAllocator &amp; llvm::dwarf_linker::parallel::LinkingGlobalData::getAllocator ()</td>
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

<p>Returns global per-thread allocator.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Reference <a href="#a5b57a7742bcf6335816aa43a28d051f3">Allocator</a>.</p>

</div>
</div>

### getOptions() {#a39f4587714d255c918f0e0c659fac37d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFLinkerOptions &amp; llvm::dwarf_linker::parallel::LinkingGlobalData::getOptions ()</td>
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

<p>Returns linking options.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Reference <a href="#a31757b06282b3db90dfeceb6b0863585">Options</a>.</p>

</div>
</div>

### getStringPool() {#a9c472d9461a75e6b9122f1d3f023b1b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringPool &amp; llvm::dwarf_linker::parallel::LinkingGlobalData::getStringPool ()</td>
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

<p>Returns global string pool.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Reference <a href="#a04dfd5580e10d8552aefd20006602d00">Strings</a>.</p>

</div>
</div>

### getTargetTriple() {#ab4955c14d8328cf5fb3b7ac211a5cc36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::reference_wrapper&lt; const Triple &gt; &gt; llvm::dwarf_linker::parallel::LinkingGlobalData::getTargetTriple ()</td>
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

<p>Optionally return target triple.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Reference <a href="#a5b9799b2e7f33a51343b80a494034e3c">TargetTriple</a>.</p>

</div>
</div>

### setErrorHandler() {#a4634136a66c62d624497559373d4e0d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::LinkingGlobalData::setErrorHandler (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#af378e877afcc692f3c5a240ebef817ca">MessageHandlerTy</a> Handler)</td>
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

<p>Set error handler.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Reference <a href="#ab770f4486b704032ad1211dc67b109f3">ErrorHandler</a>.</p>

</div>
</div>

### setTargetTriple() {#a716de5336a08b726d057c6b7ed287ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::LinkingGlobalData::setTargetTriple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
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

<p>Set target triple.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Reference <a href="#a5b9799b2e7f33a51343b80a494034e3c">TargetTriple</a>.</p>

</div>
</div>

### setWarningHandler() {#a791ea0b58e5fcb4088765a0cc94da8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::LinkingGlobalData::setWarningHandler (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#af378e877afcc692f3c5a240ebef817ca">MessageHandlerTy</a> Handler)</td>
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

<p>Set warning handler.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Reference <a href="#a9fe5527612657a5c570cb7573f5aa66e">WarningHandler</a>.</p>

</div>
</div>

### warn() {#a392281dd0eb4dba44c61b52e2b8004b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::LinkingGlobalData::warn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Warning, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> * DIE=nullptr)</td>
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

<p>Report warning.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a> and <a href="#a9fe5527612657a5c570cb7573f5aa66e">WarningHandler</a>.</p>


<p>Referenced by <a href="#a4430fdd1c34d0b9d5014d3cbbddc9916">warn</a>.</p>

</div>
</div>

### warn() {#a4430fdd1c34d0b9d5014d3cbbddc9916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::LinkingGlobalData::warn (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Warning, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> * DIE=nullptr)</td>
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

<p>Report warning.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="#a392281dd0eb4dba44c61b52e2b8004b0">warn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Allocator {#a5b57a7742bcf6335816aa43a28d051f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::parallel::PerThreadBumpPtrAllocator llvm::dwarf_linker::parallel::LinkingGlobalData::Allocator</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Referenced by <a href="#af56aae571dbc48a80f80f6bc5fca0484">getAllocator</a>.</p>

</div>
</div>

### ErrorHandler {#ab770f4486b704032ad1211dc67b109f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MessageHandlerTy llvm::dwarf_linker::parallel::LinkingGlobalData::ErrorHandler</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Referenced by <a href="#a476dbecec9ff9fa8130cfc45b3763501">error</a> and <a href="#a4634136a66c62d624497559373d4e0d6">setErrorHandler</a>.</p>

</div>
</div>

### Options {#a31757b06282b3db90dfeceb6b0863585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinkerOptions llvm::dwarf_linker::parallel::LinkingGlobalData::Options</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Referenced by <a href="#a39f4587714d255c918f0e0c659fac37d">getOptions</a>.</p>

</div>
</div>

### Strings {#a04dfd5580e10d8552aefd20006602d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringPool llvm::dwarf_linker::parallel::LinkingGlobalData::Strings</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Referenced by <a href="#a9c472d9461a75e6b9122f1d3f023b1b4">getStringPool</a>.</p>

</div>
</div>

### TargetTriple {#a5b9799b2e7f33a51343b80a494034e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Triple&gt; llvm::dwarf_linker::parallel::LinkingGlobalData::TargetTriple</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> for output data.</p>


<p>May be not set if generation of output data is not requested.</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Referenced by <a href="#ab4955c14d8328cf5fb3b7ac211a5cc36">getTargetTriple</a> and <a href="#a716de5336a08b726d057c6b7ed287ce5">setTargetTriple</a>.</p>

</div>
</div>

### WarningHandler {#a9fe5527612657a5c570cb7573f5aa66e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MessageHandlerTy llvm::dwarf_linker::parallel::LinkingGlobalData::WarningHandler</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>


<p>Referenced by <a href="#a791ea0b58e5fcb4088765a0cc94da8ef">setWarningHandler</a> and <a href="#a392281dd0eb4dba44c61b52e2b8004b0">warn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DWARFLinkerImpl {#acc90ab96f8935aac04de7e239f6a0e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::dwarf_linker::parallel::LinkingGlobalData::DWARFLinkerImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerglobaldata-h">DWARFLinkerGlobalData.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
