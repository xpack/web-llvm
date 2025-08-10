---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-dwarfemitter-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{DWARFEmitter.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{DWARFEmitter.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dwarfemitter-cpp-/pooloffsetsanddata">PoolOffsetsAndData</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b9cd710db1ece98dc23d86c22bdb5b">emitDebugNamesHeader</a> (raw_ostream &amp;OS, bool IsLittleEndian, uint32_t NameCount, uint32_t AbbrevSize, uint32_t CombinedSizeOtherParts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the header for a DebugNames section. <a href="#a95b9cd710db1ece98dc23d86c22bdb5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c05d71f45113bde19ee9259d49c7ce">emitDebugNamesAbbrev</a> (ArrayRef&lt; DWARFYAML::DebugNameAbbreviation &gt; Abbrevs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the abbreviations for a DebugNames section. <a href="#a60c05d71f45113bde19ee9259d49c7ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b45ec946683b16ca96763c103bc1cb">emitDebugNamesCUOffsets</a> (bool IsLittleEndian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a simple <a href="/web-llvm/docs/api/namespaces/cu">CU</a> offsets list for a DebugNames section containing a single <a href="/web-llvm/docs/api/namespaces/cu">CU</a> at offset 0. <a href="#aa2b45ec946683b16ca96763c103bc1cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157d897bbd822c5ca7a4dd59536d0945">emitDebugNamesNameTable</a> (bool IsLittleEndian, const DenseMap&lt; uint32_t, std::vector&lt; DWARFYAML::DebugNameEntry &gt; &gt; &amp;Entries, ArrayRef&lt; uint32_t &gt; EntryPoolOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the "NameTable" for a DebugNames section; according to the spec, it consists of two arrays: an array of string offsets, followed immediately by an array of entry offsets. <a href="#a157d897bbd822c5ca7a4dd59536d0945">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/debugnameentry">DWARFYAML::DebugNameEntry</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1bf4dd7055050ee35f58c6d76476ec6">groupEntries</a> (ArrayRef&lt; DWARFYAML::DebugNameEntry &gt; Entries)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Groups entries based on their name (strp) code and returns a map. <a href="#ab1bf4dd7055050ee35f58c6d76476ec6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2dce2d77f65b46dcc8187d9eb10a8bf">getNonZeroDataSizesFor</a> (uint32_t AbbrevCode, ArrayRef&lt; DWARFYAML::DebugNameAbbreviation &gt; Abbrevs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the abbreviation whose code is AbbrevCode and returns a list containing the expected size of all non-zero-length forms. <a href="#ab2dce2d77f65b46dcc8187d9eb10a8bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-dwarfemitter-cpp-/pooloffsetsanddata">PoolOffsetsAndData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaace979016d4a76769f1fb2b49524361">emitDebugNamesEntryPool</a> (bool IsLittleEndian, const DenseMap&lt; uint32_t, std::vector&lt; DWARFYAML::DebugNameEntry &gt; &gt; &amp;StrpToEntries, ArrayRef&lt; DWARFYAML::DebugNameAbbreviation &gt; Abbrevs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the entry pool and returns an array of offsets containing the start offset for the entries of each unique name. <a href="#aaace979016d4a76769f1fb2b49524361">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### emitDebugNamesAbbrev() {#a60c05d71f45113bde19ee9259d49c7ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{DWARFEmitter.cpp}::emitDebugNamesAbbrev (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/debugnameabbreviation">DWARFYAML::DebugNameAbbreviation</a> &gt; Abbrevs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the abbreviations for a DebugNames section.</p>

<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a60c05d71f45113bde19ee9259d49c7ce">emitDebugNamesAbbrev</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>.</p>


<p>Referenced by <a href="#a60c05d71f45113bde19ee9259d49c7ce">emitDebugNamesAbbrev</a>.</p>

</div>
</div>

### emitDebugNamesCUOffsets() {#aa2b45ec946683b16ca96763c103bc1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{DWARFEmitter.cpp}::emitDebugNamesCUOffsets (bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits a simple <a href="/web-llvm/docs/api/namespaces/cu">CU</a> offsets list for a DebugNames section containing a single <a href="/web-llvm/docs/api/namespaces/cu">CU</a> at offset 0.</p>

<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#aa2b45ec946683b16ca96763c103bc1cb">emitDebugNamesCUOffsets</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a>.</p>


<p>Referenced by <a href="#aa2b45ec946683b16ca96763c103bc1cb">emitDebugNamesCUOffsets</a>.</p>

</div>
</div>

### emitDebugNamesEntryPool() {#aaace979016d4a76769f1fb2b49524361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; PoolOffsetsAndData &gt; anonymous{DWARFEmitter.cpp}::emitDebugNamesEntryPool (bool IsLittleEndian, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/debugnameentry">DWARFYAML::DebugNameEntry</a> &gt; &gt; &amp; StrpToEntries, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/debugnameabbreviation">DWARFYAML::DebugNameAbbreviation</a> &gt; Abbrevs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the entry pool and returns an array of offsets containing the start offset for the entries of each unique name.</p>


<p>Verifies that the provided number of data values match those expected by the abbreviation table.</p>


<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#aaace979016d4a76769f1fb2b49524361">emitDebugNamesEntryPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="#ab2dce2d77f65b46dcc8187d9eb10a8bf">getNonZeroDataSizesFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe90bd018550a621549fa13700c0f762">llvm::make_second_range</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a19010bf2388f505d1262e23f9f87a813">llvm::zip_equal</a>.</p>


<p>Referenced by <a href="#aaace979016d4a76769f1fb2b49524361">emitDebugNamesEntryPool</a>.</p>

</div>
</div>

### emitDebugNamesHeader() {#a95b9cd710db1ece98dc23d86c22bdb5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DWARFEmitter.cpp}::emitDebugNamesHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian, uint32_t NameCount, uint32_t AbbrevSize, uint32_t CombinedSizeOtherParts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the header for a DebugNames section.</p>

<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="#a95b9cd710db1ece98dc23d86c22bdb5b">emitDebugNamesHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a>.</p>


<p>Referenced by <a href="#a95b9cd710db1ece98dc23d86c22bdb5b">emitDebugNamesHeader</a>.</p>

</div>
</div>

### emitDebugNamesNameTable() {#a157d897bbd822c5ca7a4dd59536d0945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{DWARFEmitter.cpp}::emitDebugNamesNameTable (bool IsLittleEndian, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint32_t, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/debugnameentry">DWARFYAML::DebugNameEntry</a> &gt; &gt; &amp; Entries, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; EntryPoolOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the "NameTable" for a DebugNames section; according to the spec, it consists of two arrays: an array of string offsets, followed immediately by an array of entry offsets.</p>


<p>The string offsets are emitted in the order provided in <span class="doxyComputerOutput">Entries</span>.</p>


<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a157d897bbd822c5ca7a4dd59536d0945">emitDebugNamesNameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f02feabe2798347395e53d18da48f96">llvm::make_first_range</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a>.</p>


<p>Referenced by <a href="#a157d897bbd822c5ca7a4dd59536d0945">emitDebugNamesNameTable</a>.</p>

</div>
</div>

### getNonZeroDataSizesFor() {#ab2dce2d77f65b46dcc8187d9eb10a8bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SmallVector&lt; uint8_t &gt; &gt; anonymous{DWARFEmitter.cpp}::getNonZeroDataSizesFor (uint32_t AbbrevCode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/debugnameabbreviation">DWARFYAML::DebugNameAbbreviation</a> &gt; Abbrevs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finds the abbreviation whose code is AbbrevCode and returns a list containing the expected size of all non-zero-length forms.</p>

<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa03b0ad8792b784269332332eb61d8ad">llvm::dwarf::getFixedFormByteSize</a>, <a href="#ab2dce2d77f65b46dcc8187d9eb10a8bf">getNonZeroDataSizesFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aaace979016d4a76769f1fb2b49524361">emitDebugNamesEntryPool</a> and <a href="#ab2dce2d77f65b46dcc8187d9eb10a8bf">getNonZeroDataSizesFor</a>.</p>

</div>
</div>

### groupEntries() {#ab1bf4dd7055050ee35f58c6d76476ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; uint32_t, std::vector&lt; DWARFYAML::DebugNameEntry &gt; &gt; anonymous{DWARFEmitter.cpp}::groupEntries (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/debugnameentry">DWARFYAML::DebugNameEntry</a> &gt; Entries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Groups entries based on their name (strp) code and returns a map.</p>

<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>Reference <a href="#ab1bf4dd7055050ee35f58c6d76476ec6">groupEntries</a>.</p>


<p>Referenced by <a href="#ab1bf4dd7055050ee35f58c6d76476ec6">groupEntries</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
