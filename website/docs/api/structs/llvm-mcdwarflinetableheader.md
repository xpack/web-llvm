---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcdwarflinetableheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MCDwarfLineTableHeader` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MCDwarfLineTableHeader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a963f2a8622c9d127e8e3df28e5d7e306">MCDwarfLineTableHeader</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af400fb04adbd61dff400a8a4a756aff9">tryGetFile</a> (StringRef &amp;Directory, StringRef &amp;FileName, std::optional&lt; MD5::MD5Result &gt; Checksum, std::optional&lt; StringRef &gt; Source, uint16_t DwarfVersion, unsigned FileNumber=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90af7c354814308d90b77d5e412f02b4">Emit</a> (MCStreamer *MCOS, MCDwarfLineTableParams Params, std::optional&lt; MCDwarfLineStr &gt; &amp;LineStr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b87cc4b647fd0f14ea7c46227ae2d58">Emit</a> (MCStreamer *MCOS, MCDwarfLineTableParams Params, ArrayRef&lt; char &gt; SpecialOpcodeLengths, std::optional&lt; MCDwarfLineStr &gt; &amp;LineStr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef263c9700b23b4eded9121d7563b119">resetMD5Usage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a6b092f84e61da1d053edab331e1519">trackMD5Usage</a> (bool MD5Used)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8deab721718b132d134944e98fa79640">isMD5UsageConsistent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9baf1c9512eb7700e11f762934a1c5d">setRootFile</a> (StringRef Directory, StringRef FileName, std::optional&lt; MD5::MD5Result &gt; Checksum, std::optional&lt; StringRef &gt; Source)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79279323e3c7181aefba2bc5c64930d">resetFileTable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1326bb7f4ebb54f9e6f400b0e07c9c7d">emitV2FileDirTables</a> (MCStreamer *MCOS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80dafec99dbdd3400469e41c903f838f">emitV5FileDirTables</a> (MCStreamer *MCOS, std::optional&lt; MCDwarfLineStr &gt; &amp;LineStr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bac9024dd5a33408f0ebf808a80f600">Label</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::string, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9074ee903a6f64c136e6a501bbb212af">MCDwarfDirs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile">MCDwarfFile</a>, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34e105dc9f3e8714802b7eb2b6649307">MCDwarfFiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeba95afcdd13498a5c19c48d54eab08">SourceIdMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c23fa8efd911fa7a16faca7402b01c9">CompilationDir</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcdwarffile">MCDwarfFile</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a432c9e68eeaa5f4c9a43e23cb4818f91">RootFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae192b8b3f9d7c3ffdec1442cc298d0fb">HasAnySource</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08418bc54f8386d1b971acb049da6757">HasAllMD5</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f80f83d83ab2d085cc1b0cd6e1716d">HasAnyMD5</a> = false</td>
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


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCDwarfLineTableHeader() {#a963f2a8622c9d127e8e3df28e5d7e306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCDwarfLineTableHeader::MCDwarfLineTableHeader ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Emit() {#a90af7c354814308d90b77d5e412f02b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; MCSymbol *, MCSymbol * &gt; MCDwarfLineTableHeader::Emit (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams">MCDwarfLineTableParams</a> Params, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr">MCDwarfLineStr</a> &gt; &amp; LineStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams/#aa098ab41af3f8cee8b1939003d55a776">llvm::MCDwarfLineTableParams::DWARF2LineOpcodeBase</a> and <a href="#a90af7c354814308d90b77d5e412f02b4">Emit</a>.</p>


<p>Referenced by <a href="#a90af7c354814308d90b77d5e412f02b4">Emit</a>.</p>

</div>
</div>

### Emit() {#a1b87cc4b647fd0f14ea7c46227ae2d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; MCSymbol *, MCSymbol * &gt; MCDwarfLineTableHeader::Emit (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams">MCDwarfLineTableParams</a> Params, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; SpecialOpcodeLengths, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr">MCDwarfLineStr</a> &gt; &amp; LineStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#abc3534e4318dd6126f55a94635209c93">DWARF2_LINE_DEFAULT_IS_STMT</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams/#afddded28f79b1eccb3a948a4bdd0f6a3">llvm::MCDwarfLineTableParams::DWARF2LineBase</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableparams/#ac75e30002379b9f61625bc8d2b4b1919">llvm::MCDwarfLineTableParams::DWARF2LineRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a8061d1e593a8f095f0efe3ba0d793531">llvm::MCStreamer::emitAbsoluteSymbolDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7f1677ad2db297b0202a720530693157">llvm::MCStreamer::emitDwarfLineStartLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a392206962fc4ac790aede10497c7e10b">llvm::MCStreamer::emitDwarfUnitLength</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d412a2cef594fc0f45de176d51fee3b">llvm::MCStreamer::emitInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#affd5fd4fc8ca1b0f483c51543e58108d">llvm::MCAsmInfo::getCodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae871de84d03670534d73ae7448b6b6d9">llvm::MCContext::getDwarfFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a99c58fcbed2434b9535b866015cd0259">llvm::MCContext::getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a2c92e93d2452cf0ad4bc91c46685425b">llvm::MCAsmInfo::getMinInstAlignment</a>, <a href="#a9bac9024dd5a33408f0ebf808a80f600">Label</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### isMD5UsageConsistent() {#a8deab721718b132d134944e98fa79640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfLineTableHeader::isMD5UsageConsistent ()</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="#a34e105dc9f3e8714802b7eb2b6649307">MCDwarfFiles</a>.</p>

</div>
</div>

### resetFileTable() {#af79279323e3c7181aefba2bc5c64930d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCDwarfLineTableHeader::resetFileTable ()</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="#ae192b8b3f9d7c3ffdec1442cc298d0fb">HasAnySource</a>, <a href="#a9074ee903a6f64c136e6a501bbb212af">MCDwarfDirs</a>, <a href="#a34e105dc9f3e8714802b7eb2b6649307">MCDwarfFiles</a>, <a href="#aef263c9700b23b4eded9121d7563b119">resetMD5Usage</a> and <a href="#a432c9e68eeaa5f4c9a43e23cb4818f91">RootFile</a>.</p>

</div>
</div>

### resetMD5Usage() {#aef263c9700b23b4eded9121d7563b119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCDwarfLineTableHeader::resetMD5Usage ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#af79279323e3c7181aefba2bc5c64930d">resetFileTable</a>.</p>

</div>
</div>

### setRootFile() {#ab9baf1c9512eb7700e11f762934a1c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCDwarfLineTableHeader::setRootFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source)</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>References <a href="#a9c23fa8efd911fa7a16faca7402b01c9">CompilationDir</a>, <a href="#ae192b8b3f9d7c3ffdec1442cc298d0fb">HasAnySource</a>, <a href="#a432c9e68eeaa5f4c9a43e23cb4818f91">RootFile</a> and <a href="#a1a6b092f84e61da1d053edab331e1519">trackMD5Usage</a>.</p>

</div>
</div>

### trackMD5Usage() {#a1a6b092f84e61da1d053edab331e1519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCDwarfLineTableHeader::trackMD5Usage (bool MD5Used)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#ab9baf1c9512eb7700e11f762934a1c5d">setRootFile</a> and <a href="#af400fb04adbd61dff400a8a4a756aff9">tryGetFile</a>.</p>

</div>
</div>

### tryGetFile() {#af400fb04adbd61dff400a8a4a756aff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; MCDwarfLineTableHeader::tryGetFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; FileName, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source, uint16_t DwarfVersion, unsigned FileNumber=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9c23fa8efd911fa7a16faca7402b01c9">CompilationDir</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="#ae192b8b3f9d7c3ffdec1442cc298d0fb">HasAnySource</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a316a87d22716c281f8e9320a97ea5acf">isRootFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a9074ee903a6f64c136e6a501bbb212af">MCDwarfDirs</a>, <a href="#a34e105dc9f3e8714802b7eb2b6649307">MCDwarfFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>, <a href="#a432c9e68eeaa5f4c9a43e23cb4818f91">RootFile</a>, <a href="#aaeba95afcdd13498a5c19c48d54eab08">SourceIdMap</a> and <a href="#a1a6b092f84e61da1d053edab331e1519">trackMD5Usage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitV2FileDirTables() {#a1326bb7f4ebb54f9e6f400b0e07c9c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDwarfLineTableHeader::emitV2FileDirTables (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>

</div>
</div>

### emitV5FileDirTables() {#a80dafec99dbdd3400469e41c903f838f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDwarfLineTableHeader::emitV5FileDirTables (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr">MCDwarfLineStr</a> &gt; &amp; LineStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CompilationDir {#a9c23fa8efd911fa7a16faca7402b01c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCDwarfLineTableHeader::CompilationDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#ab9baf1c9512eb7700e11f762934a1c5d">setRootFile</a> and <a href="#af400fb04adbd61dff400a8a4a756aff9">tryGetFile</a>.</p>

</div>
</div>

### HasAnySource {#ae192b8b3f9d7c3ffdec1442cc298d0fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfLineTableHeader::HasAnySource = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#af79279323e3c7181aefba2bc5c64930d">resetFileTable</a>, <a href="#ab9baf1c9512eb7700e11f762934a1c5d">setRootFile</a> and <a href="#af400fb04adbd61dff400a8a4a756aff9">tryGetFile</a>.</p>

</div>
</div>

### Label {#a9bac9024dd5a33408f0ebf808a80f600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCDwarfLineTableHeader::Label = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#a1b87cc4b647fd0f14ea7c46227ae2d58">Emit</a>.</p>

</div>
</div>

### MCDwarfDirs {#a9074ee903a6f64c136e6a501bbb212af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::string, 3&gt; llvm::MCDwarfLineTableHeader::MCDwarfDirs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#af79279323e3c7181aefba2bc5c64930d">resetFileTable</a> and <a href="#af400fb04adbd61dff400a8a4a756aff9">tryGetFile</a>.</p>

</div>
</div>

### MCDwarfFiles {#a34e105dc9f3e8714802b7eb2b6649307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MCDwarfFile, 3&gt; llvm::MCDwarfLineTableHeader::MCDwarfFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#a8deab721718b132d134944e98fa79640">isMD5UsageConsistent</a>, <a href="#af79279323e3c7181aefba2bc5c64930d">resetFileTable</a> and <a href="#af400fb04adbd61dff400a8a4a756aff9">tryGetFile</a>.</p>

</div>
</div>

### RootFile {#a432c9e68eeaa5f4c9a43e23cb4818f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfFile llvm::MCDwarfLineTableHeader::RootFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#af79279323e3c7181aefba2bc5c64930d">resetFileTable</a>, <a href="#ab9baf1c9512eb7700e11f762934a1c5d">setRootFile</a> and <a href="#af400fb04adbd61dff400a8a4a756aff9">tryGetFile</a>.</p>

</div>
</div>

### SourceIdMap {#aaeba95afcdd13498a5c19c48d54eab08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; llvm::MCDwarfLineTableHeader::SourceIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#af400fb04adbd61dff400a8a4a756aff9">tryGetFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasAllMD5 {#a08418bc54f8386d1b971acb049da6757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfLineTableHeader::HasAllMD5 = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### HasAnyMD5 {#a44f80f83d83ab2d085cc1b0cd6e1716d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfLineTableHeader::HasAnyMD5 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
