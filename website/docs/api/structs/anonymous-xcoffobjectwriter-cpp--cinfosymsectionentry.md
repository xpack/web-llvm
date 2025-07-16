---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CInfoSymSectionEntry` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d3f85342813ea8fa3b77f57f63477b">CInfoSymSectionEntry</a> (StringRef N, int32_t Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19ae80063f52897b94293ad30d07ca4">~CInfoSymSectionEntry</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a334d64c463e1593b8832dddc19972">addEntry</a> (std::unique_ptr&lt; CInfoSymInfo &gt; NewEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4552327f5441d641c7f94d8d0e7bca">reset</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosyminfo">CInfoSymInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eb1592323654ad315c3cbba5c41ecbc">Entry</a></td>
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


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CInfoSymSectionEntry() {#ae0d3f85342813ea8fa3b77f57f63477b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::CInfoSymSectionEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> N, int32_t Flags)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a43297ddf29aff0dc8daaf408bc68a77a">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a6b7a3c345f4636c39dc88bff87582e91">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::SectionEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CInfoSymSectionEntry() {#af19ae80063f52897b94293ad30d07ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::~CInfoSymSectionEntry ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEntry() {#a40a334d64c463e1593b8832dddc19972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::addEntry (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosyminfo">CInfoSymInfo</a> &gt; NewEntry)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="#a1eb1592323654ad315c3cbba5c41ecbc">Entry</a> and <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a0e85309a668accd0bc8312380eede902">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::Size</a>.</p>

</div>
</div>

### reset() {#a0a4552327f5441d641c7f94d8d0e7bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::reset ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="#a1eb1592323654ad315c3cbba5c41ecbc">Entry</a> and <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#aae5bccba64a708971b098ea24f5a49c0">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Entry {#a1eb1592323654ad315c3cbba5c41ecbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CInfoSymInfo&gt; anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::Entry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/xcoffobjectwriter-cpp">XCOFFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a40a334d64c463e1593b8832dddc19972">addEntry</a> and <a href="#a0a4552327f5441d641c7f94d8d0e7bca">reset</a>.</p>

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
