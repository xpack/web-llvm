---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/objectyaml/coffemitter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `COFFEmitter.cpp` File Reference

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> component of yaml2obj. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/stringsandchecksums-h">llvm/DebugInfo/CodeView/StringsAndChecksums.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/objectyaml-h">llvm/ObjectYAML/ObjectYAML.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/yaml2obj-h">llvm/ObjectYAML/yaml2obj.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/binarystreamwriter-h">llvm/Support/BinaryStreamWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">llvm/Support/WithColor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;optional&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-coffemitter-cpp-">anonymous{COFFEmitter.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/yaml">yaml</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-coffemitter-cpp-/coffparser">COFFParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This parses a yaml stream that represents a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> object file. <a href="/web-llvm/docs/api/structs/anonymous-coffemitter-cpp-/coffparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/binary-le-impl">binary_le_impl&lt;value_type&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/zeros-impl">zeros_impl&lt;NumBytes&gt;</a></td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f1e7fc31749b7af6e259adf5d1c95ec">operator&lt;&lt;</a> (raw_ostream &amp;OS, const binary_le_impl&lt; value_type &gt; &amp;BLE)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t NumBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a72da78454e254c8fe7398f8ceba5ed88">operator&lt;&lt;</a> (raw_ostream &amp;OS, const zeros_impl&lt; NumBytes &gt; &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af88a245b37141c9003534e148976e1f7">layoutOptionalHeader</a> (COFFParser &amp;CP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref">yaml::BinaryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc86b574116e1475520ba834befd71d">toDebugS</a> (ArrayRef&lt; CodeViewYAML::YAMLDebugSubsection &gt; Subsections, const codeview::StringsAndChecksums &amp;SC, BumpPtrAllocator &amp;Allocator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4325a03ac1ac35e4acf00b9cfbab5016">layoutCOFF</a> (COFFParser &amp;CP)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a67c3d5a0a2c5da7283eddf9e09f8290a">binary_le</a> (value_type V) -&gt; <a href="/web-llvm/docs/api/structs/binary-le-impl">binary_le_impl</a>&lt; value_type &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8be394aeae56944a10be3be0f82d252d">zeros</a> (const T &amp;) -&gt; <a href="/web-llvm/docs/api/structs/zeros-impl">zeros_impl</a>&lt; sizeof(T)&gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8da1aa0d43fec4647107eb0bc2d07c8d">initializeOptionalHeader</a> (COFFParser &amp;CP, uint16_t Magic, T Header)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a> (COFFParser &amp;CP, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a749770911c6d0f9c6b687d28a5ea9d7d">writeLoadConfig</a> (T &amp;S, raw_ostream &amp;OS)</td>
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

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> component of yaml2obj.</p>

<div class="doxySectionDef">

## Operators

### operator&lt;&lt;() {#a9f1e7fc31749b7af6e259adf5d1c95ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; operator&lt;&lt; (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/binary-le-impl">binary_le_impl</a>&lt; value_type &gt; &amp; BLE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/binary-le-impl/#af32f2d876ea8c303585e7fe4d81629f0">binary_le_impl&lt; value_type &gt;::Value</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a72da78454e254c8fe7398f8ceba5ed88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t NumBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; operator&lt;&lt; (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/zeros-impl">zeros_impl</a>&lt; NumBytes &gt; &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### binary\_le() {#a67c3d5a0a2c5da7283eddf9e09f8290a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">binary_le_impl&lt; value_type &gt; binary_le (value_type V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/coffyaml/sectiondataentry/#a94cbaff94af650d56d4f1379c1fbde36">llvm::COFFYAML::SectionDataEntry::writeAsBinary</a> and <a href="#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>.</p>

</div>
</div>

### initializeOptionalHeader() {#a8da1aa0d43fec4647107eb0bc2d07c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t initializeOptionalHeader (COFFParser &amp; CP, uint16_t Magic, T Header)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad54307f6fcaef777aaf18ac13b93b7d4">llvm::COFF::section::Characteristics</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#ad6a2da5a048669e81507f249863c4232">llvm::COFFYAML::Section::Header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa2b3dbe611464bb08a83985d56d7bc67b">llvm::COFF::IMAGE_SCN_CNT_CODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa4e1f40f2bdf9b194d4156c7707d047ba">llvm::COFF::IMAGE_SCN_CNT_UNINITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#a9153b22f78d286f54bf7c7510841d891">llvm::COFFYAML::Section::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad3e9101ad4377b3deaee59ffd486518a">llvm::COFF::section::SizeOfRawData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#af3d598cf4a6dbc5fa44f268098a6aa2c">llvm::COFF::section::VirtualAddress</a> and <a href="/web-llvm/docs/api/structs/llvm/coff/section/#a26b78e958606ea8e956c02d249def931">llvm::COFF::section::VirtualSize</a>.</p>


<p>Referenced by <a href="#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>.</p>

</div>
</div>

### layoutCOFF() {#a4325a03ac1ac35e4acf00b9cfbab5016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool layoutCOFF (COFFParser &amp; CP)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref/#a14c551d5c5951cce16714126f6cadcee">llvm::yaml::BinaryRef::binary_size</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad54307f6fcaef777aaf18ac13b93b7d4">llvm::COFF::section::Characteristics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b9d675b34f20ba67f1f3213e63935d6">llvm::DataSize</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#ab22a4c6e2cb7a6af361cd8256d6a6201">llvm::COFFYAML::Section::DebugH</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#abbeaefc54b52383725f9bd8d8f92429c">llvm::COFFYAML::Section::DebugP</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#a002c702c2d05d717c9415447d904228d">llvm::COFFYAML::Section::DebugS</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#a9759ac4cb01c23b65fdf09f1e9d60ed5">llvm::COFFYAML::Section::DebugT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-coffemitter-cpp-/#adff731eb01a3cfd24fd869dff5257f24aaec9a690c4699ee0687ccea1fb7f42da">anonymous{COFFEmitter.cpp}::DOSStubSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#ad6a2da5a048669e81507f249863c4232">llvm::COFFYAML::Section::Header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa7a0c196168bd2cee7fedcbcf0a5c8bf1">llvm::COFF::IMAGE_SCN_LNK_NRELOC_OVFL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#a42bdb5c08478e7021d28c6dd92b7e0e8">llvm::CodeViewYAML::initializeStringsAndChecksums</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#a9153b22f78d286f54bf7c7510841d891">llvm::COFFYAML::Section::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad9daf03141c72e95d1897cd54c037dc0">llvm::COFF::section::NumberOfRelocations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#aece3d8774b856cfd520c842bf134d4a0">llvm::COFF::PEMagic</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#a8c515c541f79c6d138d046c667902c19">llvm::COFF::section::PointerToRawData</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#a653bb8a76d7ffe84f3901ef7a1551d2a">llvm::COFF::section::PointerToRelocations</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#af8f9cf229b864087470ca43427e4ff28">llvm::COFFYAML::Section::Relocations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bdaf42dc67370019b06e0185840756d3b51">llvm::COFF::RelocationSize</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#aae94ccbef3e63ded99dade5b69e7ca4c">llvm::COFFYAML::Section::SectionData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bdad6041a54e670e50494068b9840a7b657">llvm::COFF::SectionSize</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad3e9101ad4377b3deaee59ffd486518a">llvm::COFF::section::SizeOfRawData</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#a290429e401cb45b709ea5ac7c5ad5470">llvm::COFFYAML::Section::StructuredData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a>, <a href="#a7cc86b574116e1475520ba834befd71d">toDebugS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#af58593eb129f43d4702895fe00596dd9">llvm::CodeViewYAML::toDebugT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4d6a2ded1cd4aa254c797df12e8b3feb">llvm::yaml::yaml2coff</a>.</p>

</div>
</div>

### layoutOptionalHeader() {#af88a245b37141c9003534e148976e1f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool layoutOptionalHeader (COFFParser &amp; CP)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4d6a2ded1cd4aa254c797df12e8b3feb">llvm::yaml::yaml2coff</a>.</p>

</div>
</div>

### toDebugS() {#a7cc86b574116e1475520ba834befd71d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::BinaryRef toDebugS (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/yamldebugsubsection">CodeViewYAML::YAMLDebugSubsection</a> &gt; Subsections, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksums">codeview::StringsAndChecksums</a> &amp; SC, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#aca01561b138b36094fd95b16a740393bae0eb7a9cb03e604669fce7805f7aafce">llvm::COFF::DEBUG_SECTION_MAGIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#a60bfd268a9634bf18e34825e171528fe">llvm::CodeViewYAML::toCodeViewSubsectionList</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a344647bc1c4a4b53334296eba145d408">llvm::BinaryStreamWriter::writeInteger</a>.</p>


<p>Referenced by <a href="#a4325a03ac1ac35e4acf00b9cfbab5016">layoutCOFF</a>.</p>

</div>
</div>

### writeCOFF() {#ab42bb96f4eedf10f2f2437b807a77f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool writeCOFF (COFFParser &amp; CP, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/dos-header/#a3513bee06e2bd6174d4862b1cfffb39e">llvm::object::dos_header::AddressOfNewExeHeader</a>, <a href="/web-llvm/docs/api/structs/llvm/object/dos-header/#a0d28b46e6748707e232e8bacf41e50df">llvm::object::dos_header::AddressOfRelocationTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/object/pe32-header/#aa3935e78f0f7066d707856f2124aceac">llvm::object::pe32_header::BaseOfData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae89cd5cd0f88610c3b724d104f6f0fd8">llvm::COFF::BigObjMagic</a>, <a href="#a67c3d5a0a2c5da7283eddf9e09f8290a">binary_le</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref/#a14c551d5c5951cce16714126f6cadcee">llvm::yaml::BinaryRef::binary_size</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad54307f6fcaef777aaf18ac13b93b7d4">llvm::COFF::section::Characteristics</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-coffemitter-cpp-/#adff731eb01a3cfd24fd869dff5257f24aaec9a690c4699ee0687ccea1fb7f42da">anonymous{COFFEmitter.cpp}::DOSStubSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a59d59f7f8aa89b08f44ad6a87e8ebb1a">llvm::WithColor::error</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#ad6a2da5a048669e81507f249863c4232">llvm::COFFYAML::Section::Header</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/symbol/#ad35bd85cfc78930e17ef056502f395dc">llvm::COFFYAML::Symbol::Header</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a3b426e5bcc52a3693b62bdbf03dca30e">llvm::COFF::IMAGE_FILE_MACHINE_UNKNOWN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa7a0c196168bd2cee7fedcbcf0a5c8bf1">llvm::COFF::IMAGE_SCN_LNK_NRELOC_OVFL</a>, <a href="#a8da1aa0d43fec4647107eb0bc2d07c8d">initializeOptionalHeader</a>, <a href="/web-llvm/docs/api/structs/llvm/object/dos-header/#a1445ca1e7ee5ff08466449162115804f">llvm::object::dos_header::Magic</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/bigobjheader/#ad65c26a9ca959e73682acb723a9a963da35098a5e6c71482140d6a477ec7f56ea">llvm::COFF::BigObjHeader::MinBigObjectVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ae3f859e92e664e6b19ce1d65c3d4577e">llvm::COFF::section::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/symbol/#a1682b575ce647d6ac43c6bfb864aa290">llvm::COFFYAML::Symbol::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda084ca1f72ecd10e22d3d8867548e0f61">llvm::COFF::NameSize</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/symbol/#a6a1989558c7cf0aeb1df2c2e951375af">llvm::COFF::symbol::NumberOfAuxSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#a7a0ae4f282361a25fe99b8de25988bc2">llvm::COFF::section::NumberOfLineNumbers</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad9daf03141c72e95d1897cd54c037dc0">llvm::COFF::section::NumberOfRelocations</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#abc0c07f7d6a56897523b6afed3893f7ca45e745ee43281b1eeea2857b1b2af577">llvm::COFF::PE32Header::PE32</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/pe32header/#abc0c07f7d6a56897523b6afed3893f7ca3aafcbfebffbf0013d5242afe9a4fcc7">llvm::COFF::PE32Header::PE32_PLUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#aece3d8774b856cfd520c842bf134d4a0">llvm::COFF::PEMagic</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#afc1c897880b84207d8b14a4eb41704fa">llvm::COFF::section::PointerToLineNumbers</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#a8c515c541f79c6d138d046c667902c19">llvm::COFF::section::PointerToRawData</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#a653bb8a76d7ffe84f3901ef7a1551d2a">llvm::COFF::section::PointerToRelocations</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#af8f9cf229b864087470ca43427e4ff28">llvm::COFFYAML::Section::Relocations</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#aae94ccbef3e63ded99dade5b69e7ca4c">llvm::COFFYAML::Section::SectionData</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad3e9101ad4377b3deaee59ffd486518a">llvm::COFF::section::SizeOfRawData</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#a290429e401cb45b709ea5ac7c5ad5470">llvm::COFFYAML::Section::StructuredData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda9f43dd1c5232bf4075ec3837633e1a64">llvm::COFF::Symbol16Size</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#af3d598cf4a6dbc5fa44f268098a6aa2c">llvm::COFF::section::VirtualAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#a26b78e958606ea8e956c02d249def931">llvm::COFF::section::VirtualSize</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref/#afc171c69b8c4ca66beae66513b4b1ab4">llvm::yaml::BinaryRef::writeAsBinary</a> and <a href="#a8be394aeae56944a10be3be0f82d252d">zeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4d6a2ded1cd4aa254c797df12e8b3feb">llvm::yaml::yaml2coff</a>.</p>

</div>
</div>

### writeLoadConfig() {#a749770911c6d0f9c6b687d28a5ea9d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeLoadConfig (T &amp; S, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a06288f4d38e1d74fc7a1d10056d88373">llvm::raw_ostream::write_zeros</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/coffyaml/sectiondataentry/#a94cbaff94af650d56d4f1379c1fbde36">llvm::COFFYAML::SectionDataEntry::writeAsBinary</a>.</p>

</div>
</div>

### zeros() {#a8be394aeae56944a10be3be0f82d252d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">zeros_impl&lt; sizeof(T)&gt; zeros (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
