---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `InlineInfo.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">llvm/DebugInfo/GSYM/InlineInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/fileentry-h">llvm/DebugInfo/GSYM/FileEntry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">llvm/DebugInfo/GSYM/FileWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">llvm/DebugInfo/GSYM/GsymReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
#include &lt;inttypes.h&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc3ed6ceeeace8a7eb5804423cd30bc">getInlineStackHelper</a> (const InlineInfo &amp;II, uint64_t Addr, std::vector&lt; const InlineInfo * &gt; &amp;InlineStack)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05a52a6d1ce8dda0f50063c9c22e5f4">skip</a> (DataExtractor &amp;Data, uint64_t &amp;Offset, bool SkippedRanges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Skip an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object in the specified data at the specified offset. <a href="#ac05a52a6d1ce8dda0f50063c9c22e5f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> (const GsymReader &amp;GR, DataExtractor &amp;Data, uint64_t &amp;Offset, uint64_t BaseAddr, uint64_t Addr, SourceLocations &amp;SrcLocs, llvm::Error &amp;Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A Lookup helper functions. <a href="#a5db99f4b7f8744e0b1c8b50dba8ec5a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af862e87da17b134b4d6875d052bbbc88">decode</a> (DataExtractor &amp;Data, uint64_t &amp;Offset, uint64_t BaseAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> in Data at the specified offset. <a href="#af862e87da17b134b4d6875d052bbbc88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad937528fd3e0fc9de4dc3ebf05567c72">GetTotalNumChildren</a> (const InlineInfo &amp;II)</td>
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

### decode() {#af862e87da17b134b4d6875d052bbbc88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; InlineInfo &gt; decode (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t &amp; Offset, uint64_t BaseAddr)</td>
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

<p>Decode an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> in Data at the specified offset.</p>


<p>A local helper function to decode <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects. This function is called recursively when parsing child <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The data extractor to decode from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>The offset within <em>Data</em> to decode from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The base address to use when decoding address ranges.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> or an error describing the issue that was encountered during decoding.</p></dd>
</dl>


<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#af862e87da17b134b4d6875d052bbbc88">decode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a633a66f4b93fb7bdf56cac67cd76ffd5">llvm::gsym::decodeRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#af862e87da17b134b4d6875d052bbbc88">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d9799b3fbd93955c7584681187805f">encodeCnt</a>.</p>

</div>
</div>

### getInlineStackHelper() {#a8fc3ed6ceeeace8a7eb5804423cd30bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getInlineStackHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &amp; II, uint64_t Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> * &gt; &amp; InlineStack)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="#a8fc3ed6ceeeace8a7eb5804423cd30bc">getInlineStackHelper</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo/#a6ddf4ca5eba1a243b409b9afe1a9a6e0">llvm::gsym::InlineInfo::getInlineStack</a> and <a href="#a8fc3ed6ceeeace8a7eb5804423cd30bc">getInlineStackHelper</a>.</p>

</div>
</div>

### GetTotalNumChildren() {#ad937528fd3e0fc9de4dc3ebf05567c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t GetTotalNumChildren (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &amp; II)</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="#ad937528fd3e0fc9de4dc3ebf05567c72">GetTotalNumChildren</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="#ad937528fd3e0fc9de4dc3ebf05567c72">GetTotalNumChildren</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo/#a5334ef65a442bb11580a5a4779555253">llvm::gsym::InlineInfo::operator&lt;</a>.</p>

</div>
</div>

### lookup() {#a5db99f4b7f8744e0b1c8b50dba8ec5a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> &amp; GR, <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t &amp; Offset, uint64_t BaseAddr, uint64_t Addr, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#af56cdce2bbbfcdafb057bce7c90bf419">SourceLocations</a> &amp; SrcLocs, <a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a> &amp; Err)</td>
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

<p>A Lookup helper functions.</p>


<p>Used during the InlineInfo::lookup() call to quickly only parse an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object if the address falls within this object. This avoids allocations by not appending child <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects to the InlineInfo::Children array and also skips any <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects that do not contain the address we are looking up.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>The byte offset within <em>Data</em>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The address that the relative address range offsets are relative to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#a05bfc8d6292b7916993f0f2a32307c88">llvm::gsym::SourceLocation::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a633a66f4b93fb7bdf56cac67cd76ffd5">llvm::gsym::decodeRanges</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#a9c40347d10af7c2cefe3d77e8487f4b7">llvm::gsym::SourceLocation::Dir</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a25ce2405debe5fa88ce06de770ce4bf0">llvm::gsym::GsymReader::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a65ec9133639d066dcf6843b1fc3ae79c">llvm::gsym::GsymReader::getString</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#a158cfb1f977ca6fa5202d0925b97197b">llvm::gsym::SourceLocation::Line</a>, <a href="#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#acc0de9bcc407c170aff5069c335bb961">llvm::gsym::SourceLocation::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#a5ac9d3eb9c18ab3a8da5b084d034c158">llvm::gsym::SourceLocation::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#ac05a52a6d1ce8dda0f50063c9c22e5f4">skip</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#afd5821362beb37693123202b5e35d15a">llvm::DwarfCompileUnit::finishSubprogramDefinition</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/nametoidxmap/#a744628409313ef0d9796cefc17cb846f">anonymous{ELFEmitter.cpp}::NameToIdxMap::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#a168c086b440ac3edbfc53840cae70183">llvm::DWARFDebugNames::Entry::getCUIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry/#ac1a86813500814b851f934a1298ef89c">llvm::AppleAcceleratorTable::Entry::getCUOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry/#a97c30b96f55985fda53f4448dcb82c59">llvm::AppleAcceleratorTable::Entry::getDIESectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#a68d9def68ebcbb770eb26c987b5e0548">llvm::DWARFDebugNames::Entry::getDIEUnitOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxregisterinfo/#ae271370eae878e78d2bad43aa2d68e1d">llvm::NVPTXRegisterInfo::getDwarfRegNum</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ac94862da33ca9821ea2321bf87645526">llvm::X86InstrInfo::getExecutionDomain</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#a9d29998e353ecb9f57c17b956670e2ae">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::getMetadataIfResolved</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#a7bdb3e65ba30c7b30437f48960cc9dc6">llvm::DWARFDebugNames::Entry::getParentDIEEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#a135d424639be046fd6d58dbaaa831f82">llvm::DWARFDebugNames::Entry::getRelatedCUIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/entry/#ab72464ee65b0699a8517a57ad370928d">llvm::AppleAcceleratorTable::Entry::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#aabddaaf3a1568deb8177b99810ee0054">llvm::DWARFDebugNames::Entry::getTUIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/entry/#aa52b75e81f83faaff001fdf8f6433144">llvm::DWARFDebugNames::Entry::hasParentInformation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f04318888b610cbdd037adc9b1b17e3">llvm::isAtLeastOrStrongerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af21b12b7c8de1504a945c4c974e06bff">llvm::isStrongerThan</a>, <a href="#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aa391568da257769298bd1a405148c5bb">llvm::X86InstrInfo::setExecutionDomain</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ab54b3f7d3fa59aeeb9c5c46e44ee0163">llvm::X86InstrInfo::setExecutionDomainCustom</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a66e6f90f41f1ea69d5ee532384f0af4e">llvm::toCABI</a>.</p>

</div>
</div>

### skip() {#ac05a52a6d1ce8dda0f50063c9c22e5f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool skip (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t &amp; Offset, bool SkippedRanges)</td>
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

<p>Skip an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object in the specified data at the specified offset.</p>


<p>Used during the InlineInfo::lookup() call to quickly skip child <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects where the addres ranges isn't contained in the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object or its children. This avoids allocations by not appending child <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects to the InlineInfo::Children array.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>The byte offset within <em>Data</em>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SkippedRanges</td>
<td class="doxyParamItemDescription"><p>If true, address ranges have already been skipped.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#ac05a52a6d1ce8dda0f50063c9c22e5f4">skip</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a737818489808bd60446fcf82c7946f5e">llvm::gsym::skipRanges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a8d3e918d874e8e80cf9a403e8ea59e32">canBeFeederToNewValueJump</a>, <a href="#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="#ac05a52a6d1ce8dda0f50063c9c22e5f4">skip</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
