---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objectyaml/dwarfemitter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DWARFEmitter.cpp` File Reference

<p>The DWARF component of yaml2obj. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfemitter-h">llvm/ObjectYAML/DWARFEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dwarfyaml-h">llvm/ObjectYAML/DWARFYAML.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/swapbyteorder-h">llvm/Support/SwapByteOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-">anonymous{DWARFEmitter.cpp}</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a> (T Integer, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a> (uint64_t Integer, size_t Size, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb7e677ef1f781489e3e391caf5af2f">ZeroFillBytes</a> (raw_ostream &amp;OS, size_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ee8400bf54ced7c7746edad96d09bd">writeInitialLength</a> (const dwarf::DwarfFormat Format, const uint64_t Length, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06165ab70e15cc2ceca18bd8839afca2">writeDWARFOffset</a> (uint64_t Offset, dwarf::DwarfFormat Format, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa371f7d58f8c4b09db71516e37bf45f4">emitPubSection</a> (raw_ostream &amp;OS, const DWARFYAML::PubSection &amp;Sect, bool IsLittleEndian, bool IsGNUPubSec=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6559672807a3455fb24c680ac42dc6">writeDIE</a> (const DWARFYAML::Data &amp;DI, uint64_t CUIndex, uint64_t AbbrevTableID, const dwarf::FormParams &amp;Params, const DWARFYAML::Entry &amp;Entry, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23875c46eead910ec10551d31420a75d">emitFileEntry</a> (raw_ostream &amp;OS, const DWARFYAML::File &amp;File)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e1598cefbf424412afe2ea557d7a27a">writeExtendedOpcode</a> (const DWARFYAML::LineTableOpcode &amp;Op, uint8_t AddrSize, bool IsLittleEndian, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca5d3a2ec00a3a63ddc150b943337e9">writeLineTableOpcode</a> (const DWARFYAML::LineTableOpcode &amp;Op, uint8_t OpcodeBase, uint8_t AddrSize, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd08ae81a5ab88c62ed7ee7d55c6a5c5">getStandardOpcodeLengths</a> (uint16_t Version, std::optional&lt; uint8_t &gt; OpcodeBase)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fbec7515ca1c665315334c1a67d3a5">checkOperandCount</a> (StringRef EncodingString, ArrayRef&lt; yaml::Hex64 &gt; Values, uint64_t ExpectedOperands)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea61050e03d2b5de9ef6621624e66122">writeListEntryAddress</a> (StringRef EncodingName, raw_ostream &amp;OS, uint64_t Addr, uint8_t AddrSize, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d1c89a919275d8aa033388862d7771e">writeDWARFExpression</a> (raw_ostream &amp;OS, const DWARFYAML::DWARFOperation &amp;Operation, uint8_t AddrSize, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ac83b81cafa1a8062aaf24af05346d">writeListEntry</a> (raw_ostream &amp;OS, const DWARFYAML::RnglistEntry &amp;Entry, uint8_t AddrSize, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a563a2cfcb7521ea43f914110e6336fc4">writeListEntry</a> (raw_ostream &amp;OS, const DWARFYAML::LoclistEntry &amp;Entry, uint8_t AddrSize, bool IsLittleEndian)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename EntryType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a> (raw_ostream &amp;OS, ArrayRef&lt; DWARFYAML::ListTable&lt; EntryType &gt; &gt; Tables, bool IsLittleEndian, bool Is64BitAddrSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf0b70372e2ca4b1e9540e9c4f8aa41">emitDebugSectionImpl</a> (const DWARFYAML::Data &amp;DI, StringRef Sec, StringMap&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; &amp;OutputBuffers)</td>
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

<p>The DWARF component of yaml2obj.</p>


<p>Provided as library code for tests.</p>


<div class="doxySectionDef">

## Functions

### checkOperandCount() {#a99fbec7515ca1c665315334c1a67d3a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error checkOperandCount (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EncodingString, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; yaml::Hex64 &gt; Values, uint64_t ExpectedOperands)</td>
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



<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a9d1c89a919275d8aa033388862d7771e">writeDWARFExpression</a>, <a href="#a563a2cfcb7521ea43f914110e6336fc4">writeListEntry</a> and <a href="#a58ac83b81cafa1a8062aaf24af05346d">writeListEntry</a>.</p>

</div>
</div>

### emitDebugSectionImpl() {#a1bf0b70372e2ca4b1e9540e9c4f8aa41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error emitDebugSectionImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data">DWARFYAML::Data</a> &amp; DI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Sec, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt; &amp; OutputBuffers)</td>
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



<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9bde8a0a70fe79e96ac7232738deabff">llvm::DWARFYAML::getDWARFEmitterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9feb9f5ca88b1a9d4f6e702a39d35060">llvm::DWARFYAML::emitDebugSections</a>.</p>

</div>
</div>

### emitFileEntry() {#a23875c46eead910ec10551d31420a75d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitFileEntry (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/file">DWARFYAML::File</a> &amp; File)</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a> and <a href="#a8e1598cefbf424412afe2ea557d7a27a">writeExtendedOpcode</a>.</p>

</div>
</div>

### emitPubSection() {#aa371f7d58f8c4b09db71516e37bf45f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error emitPubSection (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection">DWARFYAML::PubSection</a> &amp; Sect, bool IsLittleEndian, bool IsGNUPubSec=false)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection/#aa7d70a440908435d75aa26a2ef7586ac">llvm::DWARFYAML::PubSection::Entries</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection/#a0aca485d66fa11d5819b71fc34fff92a">llvm::DWARFYAML::PubSection::Format</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection/#a7bd1b2f3fd6741749047a3422077e11a">llvm::DWARFYAML::PubSection::Length</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection/#a950060fa7f543dc47953d5f73a7e404c">llvm::DWARFYAML::PubSection::UnitOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection/#a383d6433525ee49af486a91840196ca9">llvm::DWARFYAML::PubSection::UnitSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/pubsection/#a9f84a7f72d6f9889434e8a03ab76f8a9">llvm::DWARFYAML::PubSection::Version</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>, <a href="#ac8ee8400bf54ced7c7746edad96d09bd">writeInitialLength</a> and <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a6fb5811ad2c492fe44774e9aeac6a6e4">llvm::DWARFYAML::emitDebugGNUPubnames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aa2deb4bf15d78c73e0e1f4f341379c74">llvm::DWARFYAML::emitDebugGNUPubtypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aac8bbdfe4333871ee70d90676f5a304f">llvm::DWARFYAML::emitDebugPubnames</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ad5b39b3c318d6af879ffdc19bbcfe09e">llvm::DWARFYAML::emitDebugPubtypes</a>.</p>

</div>
</div>

### getStandardOpcodeLengths() {#acd08ae81a5ab88c62ed7ee7d55c6a5c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint8_t &gt; getStandardOpcodeLengths (uint16_t Version, std::optional&lt; uint8_t &gt; OpcodeBase)</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>.</p>

</div>
</div>

### writeDIE() {#abe6559672807a3455fb24c680ac42dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; writeDIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data">DWARFYAML::Data</a> &amp; DI, uint64_t CUIndex, uint64_t AbbrevTableID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> &amp; Params, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/entry">DWARFYAML::Entry</a> &amp; Entry, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a6892519cfb3ec739ebd611d7bd82ea2e">llvm::dwarf::FormParams::AddrSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/abbrev/#a2287108826400bc45b35b6e76ef4a1d1">llvm::DWARFYAML::Abbrev::Attributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data/#a36e38be107ad1f885b0ed61bc831d263">llvm::DWARFYAML::Data::DebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data/#a52ac21f4a38a14d4151a066ffc40005a">llvm::DWARFYAML::Data::getAbbrevTableInfoByID</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a235a5f4eedbfa7b5583ba320309d408f">llvm::dwarf::FormParams::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a6385ddcd0042b7b98875ab684a115f2e">llvm::dwarf::FormParams::getRefAddrByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41972fe6f3fab862543b7b835a714f9b">llvm::utostr</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>, <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a> and <a href="#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>.</p>

</div>
</div>

### writeDWARFExpression() {#a9d1c89a919275d8aa033388862d7771e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; writeDWARFExpression (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/dwarfoperation">DWARFYAML::DWARFOperation</a> &amp; Operation, uint8_t AddrSize, bool IsLittleEndian)</td>
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



<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="#a99fbec7515ca1c665315334c1a67d3a5">checkOperandCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baa55e82356e9721946aa9ba954733c6f0">llvm::not_supported</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5b2aa9d3f9f3a7b2d123fef7c5328b8f">Operation</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gad20f8c5eb7af765400eea967ff2645b3">llvm::dwarf::OperationEncodingString</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3beda524b0772ca36035db4399a6a571">llvm::utohexstr</a> and <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a>.</p>


<p>Referenced by <a href="#a563a2cfcb7521ea43f914110e6336fc4">writeListEntry</a>.</p>

</div>
</div>

### writeDWARFLists() {#a27a0ea7c31356a5938a3fe32e8eb3103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename EntryType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error writeDWARFLists (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/listtable">DWARFYAML::ListTable</a>&lt; EntryType &gt; &gt; Tables, bool IsLittleEndian, bool Is64BitAddrSize)</td>
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



<p>Definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>, <a href="#a06165ab70e15cc2ceca18bd8839afca2">writeDWARFOffset</a>, <a href="#ac8ee8400bf54ced7c7746edad96d09bd">writeInitialLength</a>, <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a> and <a href="#a58ac83b81cafa1a8062aaf24af05346d">writeListEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a98a827d6dc5e0b9852b362a6303a4c04">llvm::DWARFYAML::emitDebugLoclists</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a8427f4b409530028e8e344a02aef72a1">llvm::DWARFYAML::emitDebugRnglists</a>.</p>

</div>
</div>

### writeDWARFOffset() {#a06165ab70e15cc2ceca18bd8839afca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDWARFOffset (uint64_t Offset, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> Format, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a> and <a href="#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>.</p>

</div>
</div>

### writeExtendedOpcode() {#a8e1598cefbf424412afe2ea557d7a27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeExtendedOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/linetableopcode">DWARFYAML::LineTableOpcode</a> &amp; Op, uint8_t AddrSize, bool IsLittleEndian, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#a23875c46eead910ec10551d31420a75d">emitFileEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>, <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a> and <a href="#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a>.</p>


<p>Referenced by <a href="#a3ca5d3a2ec00a3a63ddc150b943337e9">writeLineTableOpcode</a>.</p>

</div>
</div>

### writeInitialLength() {#ac8ee8400bf54ced7c7746edad96d09bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInitialLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> Format, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Length, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4adc3aedef0caeccf6d845a430da6d3f8d">llvm::dwarf::DW_LENGTH_DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a34b4d38e06d609b405f4a79c223ed8d2">llvm::dwarf::DWARF64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aca49747266152cead6b515f84225e351">llvm::DWARFYAML::emitDebugAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>, <a href="#aa371f7d58f8c4b09db71516e37bf45f4">emitPubSection</a> and <a href="#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>.</p>

</div>
</div>

### writeInteger() {#a7d09dee266df5fb62a8791100b24c5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInteger (T Integer, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aca49747266152cead6b515f84225e351">llvm::DWARFYAML::emitDebugAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#aa2b45ec946683b16ca96763c103bc1cb">anonymous{DWARFEmitter.cpp}::emitDebugNamesCUOffsets</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#a95b9cd710db1ece98dc23d86c22bdb5b">anonymous{DWARFEmitter.cpp}::emitDebugNamesHeader</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#a157d897bbd822c5ca7a4dd59536d0945">anonymous{DWARFEmitter.cpp}::emitDebugNamesNameTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a08aae9cc5950db0fa5c9a00e95a3492c">llvm::DWARFYAML::emitDebugStrOffsets</a>, <a href="#aa371f7d58f8c4b09db71516e37bf45f4">emitPubSection</a>, <a href="#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>, <a href="#a9d1c89a919275d8aa033388862d7771e">writeDWARFExpression</a>, <a href="#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>, <a href="#a8e1598cefbf424412afe2ea557d7a27a">writeExtendedOpcode</a>, <a href="#a3ca5d3a2ec00a3a63ddc150b943337e9">writeLineTableOpcode</a>, <a href="#a563a2cfcb7521ea43f914110e6336fc4">writeListEntry</a>, <a href="#a58ac83b81cafa1a8062aaf24af05346d">writeListEntry</a> and <a href="#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a>.</p>

</div>
</div>

### writeLineTableOpcode() {#a3ca5d3a2ec00a3a63ddc150b943337e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeLineTableOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/linetableopcode">DWARFYAML::LineTableOpcode</a> &amp; Op, uint8_t OpcodeBase, uint8_t AddrSize, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
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



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="#a8e1598cefbf424412afe2ea557d7a27a">writeExtendedOpcode</a> and <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>.</p>

</div>
</div>

### writeListEntry() {#a58ac83b81cafa1a8062aaf24af05346d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; writeListEntry (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/rnglistentry">DWARFYAML::RnglistEntry</a> &amp; Entry, uint8_t AddrSize, bool IsLittleEndian)</td>
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



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#a99fbec7515ca1c665315334c1a67d3a5">checkOperandCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga01f206798c5c6fc8bf8ee1c8e83e37e4">llvm::dwarf::RangeListEncodingString</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a> and <a href="#aea61050e03d2b5de9ef6621624e66122">writeListEntryAddress</a>.</p>


<p>Referenced by <a href="#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>.</p>

</div>
</div>

### writeListEntry() {#a563a2cfcb7521ea43f914110e6336fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; writeListEntry (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/loclistentry">DWARFYAML::LoclistEntry</a> &amp; Entry, uint8_t AddrSize, bool IsLittleEndian)</td>
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



<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="#a99fbec7515ca1c665315334c1a67d3a5">checkOperandCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga579df9d304fa35f6c02846b389469dd4">llvm::dwarf::LocListEncodingString</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>, <a href="#a9d1c89a919275d8aa033388862d7771e">writeDWARFExpression</a>, <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a> and <a href="#aea61050e03d2b5de9ef6621624e66122">writeListEntryAddress</a>.</p>

</div>
</div>

### writeListEntryAddress() {#aea61050e03d2b5de9ef6621624e66122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error writeListEntryAddress (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EncodingName, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Addr, uint8_t AddrSize, bool IsLittleEndian)</td>
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



<p>Definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a> and <a href="#a5626523faa24e3e575e266f43be2a387">writeVariableSizedInteger</a>.</p>


<p>Referenced by <a href="#a563a2cfcb7521ea43f914110e6336fc4">writeListEntry</a> and <a href="#a58ac83b81cafa1a8062aaf24af05346d">writeListEntry</a>.</p>

</div>
</div>

### writeVariableSizedInteger() {#a5626523faa24e3e575e266f43be2a387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error writeVariableSizedInteger (uint64_t Integer, size_t Size, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baa55e82356e9721946aa9ba954733c6f0">llvm::not_supported</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aca49747266152cead6b515f84225e351">llvm::DWARFYAML::emitDebugAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#aaace979016d4a76769f1fb2b49524361">anonymous{DWARFEmitter.cpp}::emitDebugNamesEntryPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a258100c512356fe24a12a14fc7ad9d78">llvm::DWARFYAML::emitDebugRanges</a>, <a href="#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>, <a href="#a06165ab70e15cc2ceca18bd8839afca2">writeDWARFOffset</a>, <a href="#a8e1598cefbf424412afe2ea557d7a27a">writeExtendedOpcode</a>, <a href="#ac8ee8400bf54ced7c7746edad96d09bd">writeInitialLength</a> and <a href="#aea61050e03d2b5de9ef6621624e66122">writeListEntryAddress</a>.</p>

</div>
</div>

### ZeroFillBytes() {#a1cb7e677ef1f781489e3e391caf5af2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ZeroFillBytes (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, size_t Size)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp">DWARFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a2d42b869454e23ae5fcad0cd11719a30">llvm::DWARFYAML::emitDebugAranges</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a258100c512356fe24a12a14fc7ad9d78">llvm::DWARFYAML::emitDebugRanges</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
