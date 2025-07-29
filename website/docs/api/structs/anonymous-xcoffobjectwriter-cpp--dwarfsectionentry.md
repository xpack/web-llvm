---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DwarfSectionEntry` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry">SectionEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6cfee84ea7b7e4ff3b5ec82038da80b">DwarfSectionEntry</a> (StringRef N, int32_t Flags, std::unique_ptr&lt; XCOFFSection &gt; Sect)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e285ace1400b5258f44b88c3e6b8bd">DwarfSectionEntry</a> (DwarfSectionEntry &amp;&amp;s)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff71b641750c51e3d83780d570a26918">~DwarfSectionEntry</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e903678691749d5a7fd6015f16a739">advanceFileOffset</a> (const uint64_t MaxRawDataSize, const uint64_t RawPointer) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/xcoffsection">XCOFFSection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57228755c33bafd46df17503bfca4c44">DwarfSect</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a63a540d5154756cbb5df060c1ff21d">MemorySize</a></td>
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


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DwarfSectionEntry() {#ae6cfee84ea7b7e4ff3b5ec82038da80b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::DwarfSectionEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> N, int32_t Flags, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/xcoffsection">XCOFFSection</a> &gt; Sect)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a57228755c33bafd46df17503bfca4c44">DwarfSect</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a43297ddf29aff0dc8daaf408bc68a77a">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Flags</a>, <a href="#a7a63a540d5154756cbb5df060c1ff21d">MemorySize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a2a540b4ce534a52cb75ccec11e9a08d2">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a9a03aac7419558e56bd606aeab244118">llvm::XCOFF::NameSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a6b7a3c345f4636c39dc88bff87582e91">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::SectionEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1dddb836146cb79d721a0eb775a670ab">llvm::XCOFF::STYP_DWARF</a>.</p>


<p>Referenced by <a href="#a68e285ace1400b5258f44b88c3e6b8bd">DwarfSectionEntry</a>.</p>

</div>
</div>

### DwarfSectionEntry() {#a68e285ace1400b5258f44b88c3e6b8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::DwarfSectionEntry (<a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry">DwarfSectionEntry</a> &amp;&amp; s)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="#ae6cfee84ea7b7e4ff3b5ec82038da80b">DwarfSectionEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DwarfSectionEntry() {#aff71b641750c51e3d83780d570a26918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::~DwarfSectionEntry ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advanceFileOffset() {#a06e903678691749d5a7fd6015f16a739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::advanceFileOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t MaxRawDataSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t RawPointer)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a3b1cc0022448deeaecc47e779d34121e">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::FileOffsetToData</a> and <a href="#a7a63a540d5154756cbb5df060c1ff21d">MemorySize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DwarfSect {#a57228755c33bafd46df17503bfca4c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;XCOFFSection&gt; anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::DwarfSect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#ae6cfee84ea7b7e4ff3b5ec82038da80b">DwarfSectionEntry</a>.</p>

</div>
</div>

### MemorySize {#a7a63a540d5154756cbb5df060c1ff21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::MemorySize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a06e903678691749d5a7fd6015f16a739">advanceFileOffset</a> and <a href="#ae6cfee84ea7b7e4ff3b5ec82038da80b">DwarfSectionEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
