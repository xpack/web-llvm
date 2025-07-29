---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/anonymous-lvcodeviewvisitor-cpp-/lvstringrecords
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LVStringRecords` Class



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVStringRecords { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d5a627144974cb5cb99114bce408891">StringEntry</a> = std::tuple&lt; uint32_t, std::string, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit">LVScopeCompileUnit</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8833a8a629ade40514fe5fbcf9e6a86b">StringIds</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a694a1d13a66d6e19327d8252c8059fdc">LVStringRecords</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764fbaf3d8c3662521c2a9cb1f1f2ad1">add</a> (TypeIndex TI, StringRef String)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049e81630786ef49fcb98fc4e430cf89">find</a> (TypeIndex TI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38d2fd1d01e56687b51eb970a3e83330">findIndex</a> (TypeIndex TI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6fcfe385c9b1964c7ca7397f5bbe40">addFilenames</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826a11c7c461ca42209d037b0e5f43eb">addFilenames</a> (LVScopeCompileUnit *Scope)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">StringIds</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1813c72d194e7664b6dd2419889c5ec">Strings</a></td>
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


<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### StringEntry {#a2d5a627144974cb5cb99114bce408891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVStringRecords::StringEntry =  std::tuple&lt;uint32_t, std::string, LVScopeCompileUnit *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### StringIds {#a8833a8a629ade40514fe5fbcf9e6a86b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVStringRecords::StringIds =  std::map&lt;TypeIndex, StringEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LVStringRecords() {#a694a1d13a66d6e19327d8252c8059fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVStringRecords::LVStringRecords ()</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a764fbaf3d8c3662521c2a9cb1f1f2ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVStringRecords::add (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> String)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>

</div>
</div>

### addFilenames() {#acb6fcfe385c9b1964c7ca7397f5bbe40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVStringRecords::addFilenames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>References <a href="#acb6fcfe385c9b1964c7ca7397f5bbe40">addFilenames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#af64c789b30b79a5f18889270bccef27ea49ee3087348e8d44e1feda1917443987">llvm::logicalview::Name</a> and <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a925491368f86809733afde389b3f9c5a">llvm::logicalview::transformPath</a>.</p>


<p>Referenced by <a href="#acb6fcfe385c9b1964c7ca7397f5bbe40">addFilenames</a> and <a href="#a826a11c7c461ca42209d037b0e5f43eb">addFilenames</a>.</p>

</div>
</div>

### addFilenames() {#a826a11c7c461ca42209d037b0e5f43eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVStringRecords::addFilenames (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopecompileunit">LVScopeCompileUnit</a> * Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>


<p>Reference <a href="#acb6fcfe385c9b1964c7ca7397f5bbe40">addFilenames</a>.</p>

</div>
</div>

### find() {#a049e81630786ef49fcb98fc4e430cf89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVStringRecords::find (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

### findIndex() {#a38d2fd1d01e56687b51eb970a3e83330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVStringRecords::findIndex (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> TI)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Strings {#ab1813c72d194e7664b6dd2419889c5ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringIds llvm::logicalview::anonymous{LVCodeViewVisitor.cpp}::LVStringRecords::Strings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/readers/lvcodeviewvisitor-cpp">LVCodeViewVisitor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
