---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SectionEntry` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{XCOFFObjectWriter.cpp}::SectionEntry { ... }
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry">CInfoSymSectionEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry">CsectSectionEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry">DwarfSectionEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptionsectionentry">ExceptionSectionEntry</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a> (StringRef N, int32_t Flags)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110acdf12727eeca7799da739791d787">~SectionEntry</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088f385ba94b7695cb8577ace2dd1420">advanceFileOffset</a> (const uint64_t MaxRawDataSize, const uint64_t RawPointer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae5bccba64a708971b098ea24f5a49c0">reset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a540b4ce534a52cb75ccec11e9a08d2">Name</a>[XCOFF::NameSize]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a181bdb0a7e584b0e91caf97e93e2e">Address</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e85309a668accd0bc8312380eede902">Size</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b1cc0022448deeaecc47e779d34121e">FileOffsetToData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa5cd6224ac853360b5f70b38298d98">FileOffsetToRelocations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e0a1b0773c5053e33757940027d140">RelocationCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43297ddf29aff0dc8daaf408bc68a77a">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc0c6e980c4184cba78bf08036a6cc4">Index</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca6ac79c703d2fd803ec070c57709798">UninitializedIndex</a> = ...</td>
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


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SectionEntry() {#a6b7a3c345f4636c39dc88bff87582e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::SectionEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> N, int32_t Flags)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="#a67a181bdb0a7e584b0e91caf97e93e2e">Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3b1cc0022448deeaecc47e779d34121e">FileOffsetToData</a>, <a href="#afaa5cd6224ac853360b5f70b38298d98">FileOffsetToRelocations</a>, <a href="#a43297ddf29aff0dc8daaf408bc68a77a">Flags</a>, <a href="#a2cc0c6e980c4184cba78bf08036a6cc4">Index</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a2a540b4ce534a52cb75ccec11e9a08d2">Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a9a03aac7419558e56bd606aeab244118">llvm::XCOFF::NameSize</a>, <a href="#a40e0a1b0773c5053e33757940027d140">RelocationCount</a>, <a href="#a0e85309a668accd0bc8312380eede902">Size</a> and <a href="#aca6ac79c703d2fd803ec070c57709798">UninitializedIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry/#ae0d3f85342813ea8fa3b77f57f63477b">anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::CInfoSymSectionEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry/#acbc7352200a105080886a8652f3b77da">anonymous{XCOFFObjectWriter.cpp}::CsectSectionEntry::CsectSectionEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry/#ae6cfee84ea7b7e4ff3b5ec82038da80b">anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::DwarfSectionEntry</a> and <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptionsectionentry/#a5025bde0980a70bcfa30bbbf8b3d7b37">anonymous{XCOFFObjectWriter.cpp}::ExceptionSectionEntry::ExceptionSectionEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SectionEntry() {#a110acdf12727eeca7799da739791d787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{XCOFFObjectWriter.cpp}::SectionEntry::~SectionEntry ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advanceFileOffset() {#a088f385ba94b7695cb8577ace2dd1420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::advanceFileOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t MaxRawDataSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t RawPointer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="#a3b1cc0022448deeaecc47e779d34121e">FileOffsetToData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#a0e85309a668accd0bc8312380eede902">Size</a>.</p>

</div>
</div>

### reset() {#aae5bccba64a708971b098ea24f5a49c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{XCOFFObjectWriter.cpp}::SectionEntry::reset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="#a67a181bdb0a7e584b0e91caf97e93e2e">Address</a>, <a href="#a3b1cc0022448deeaecc47e779d34121e">FileOffsetToData</a>, <a href="#afaa5cd6224ac853360b5f70b38298d98">FileOffsetToRelocations</a>, <a href="#a2cc0c6e980c4184cba78bf08036a6cc4">Index</a>, <a href="#a40e0a1b0773c5053e33757940027d140">RelocationCount</a>, <a href="#a0e85309a668accd0bc8312380eede902">Size</a> and <a href="#aca6ac79c703d2fd803ec070c57709798">UninitializedIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry/#a0a4552327f5441d641c7f94d8d0e7bca">anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::reset</a> and <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry/#afafe0646e267674832019f097bb9e9ce">anonymous{XCOFFObjectWriter.cpp}::CsectSectionEntry::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Address {#a67a181bdb0a7e584b0e91caf97e93e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Address</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#aae5bccba64a708971b098ea24f5a49c0">reset</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

### FileOffsetToData {#a3b1cc0022448deeaecc47e779d34121e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::FileOffsetToData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry/#a06e903678691749d5a7fd6015f16a739">anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::advanceFileOffset</a>, <a href="#a088f385ba94b7695cb8577ace2dd1420">advanceFileOffset</a>, <a href="#aae5bccba64a708971b098ea24f5a49c0">reset</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

### FileOffsetToRelocations {#afaa5cd6224ac853360b5f70b38298d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::FileOffsetToRelocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#aae5bccba64a708971b098ea24f5a49c0">reset</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

### Flags {#a43297ddf29aff0dc8daaf408bc68a77a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry/#ae0d3f85342813ea8fa3b77f57f63477b">anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::CInfoSymSectionEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry/#acbc7352200a105080886a8652f3b77da">anonymous{XCOFFObjectWriter.cpp}::CsectSectionEntry::CsectSectionEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry/#ae6cfee84ea7b7e4ff3b5ec82038da80b">anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::DwarfSectionEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptionsectionentry/#a5025bde0980a70bcfa30bbbf8b3d7b37">anonymous{XCOFFObjectWriter.cpp}::ExceptionSectionEntry::ExceptionSectionEntry</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

### Index {#a2cc0c6e980c4184cba78bf08036a6cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#aae5bccba64a708971b098ea24f5a49c0">reset</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

### Name {#a2a540b4ce534a52cb75ccec11e9a08d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Name[XCOFF::NameSize]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry/#acbc7352200a105080886a8652f3b77da">anonymous{XCOFFObjectWriter.cpp}::CsectSectionEntry::CsectSectionEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry/#ae6cfee84ea7b7e4ff3b5ec82038da80b">anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::DwarfSectionEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptionsectionentry/#a5025bde0980a70bcfa30bbbf8b3d7b37">anonymous{XCOFFObjectWriter.cpp}::ExceptionSectionEntry::ExceptionSectionEntry</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

### RelocationCount {#a40e0a1b0773c5053e33757940027d140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::RelocationCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#aae5bccba64a708971b098ea24f5a49c0">reset</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

### Size {#a0e85309a668accd0bc8312380eede902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry/#a40a334d64c463e1593b8832dddc19972">anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::addEntry</a>, <a href="#a088f385ba94b7695cb8577ace2dd1420">advanceFileOffset</a>, <a href="#aae5bccba64a708971b098ea24f5a49c0">reset</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### UninitializedIndex {#aca6ac79c703d2fd803ec070c57709798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t anonymous{XCOFFObjectWriter.cpp}::SectionEntry::UninitializedIndex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      XCOFF::ReservedSectionNum::N_DEBUG - 1
</div>
</dd>
</dl>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#aae5bccba64a708971b098ea24f5a49c0">reset</a> and <a href="#a6b7a3c345f4636c39dc88bff87582e91">SectionEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
