---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-elf-x86-64-cpp-/tlsinfotablemanager-elf-x86-64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TLSInfoTableManager_ELF_x86_64` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ELF_x86_64.cpp}::TLSInfoTableManager_ELF_x86_64 { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager">TableManager&lt;TableManagerImplT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP base for tables that are built on demand, e.g. <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17752bb83c93e2b27cd3dc2e9436d28">visitEdge</a> (LinkGraph &amp;G, Block *B, Edge &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab300a3a847ff2e42c2291be4345e13">createEntry</a> (LinkGraph &amp;G, Symbol &amp;Target)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab70e5ae5ab402542fc3e11a9912aaf08">getTLSInfoSection</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd71b432b961d2d4379898af06268c28">getTLSInfoEntryContent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab649623e26528bfb7ba81c46913896af">TLSInfoTable</a> = nullptr</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d828834f23509ab883271b9f6c3a9f4">getSectionName</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c2a93e1c789eb0836b4d288fc1575d">TLSInfoEntryContent</a>[16] = ...</td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### createEntry() {#a6ab300a3a847ff2e42c2291be4345e13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; anonymous{ELF_x86_64.cpp}::TLSInfoTableManager_ELF_x86_64::createEntry (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1aa9b0fce35f44572f2bddf0fe8a2c64e4">llvm::jitlink::x86_64::Pointer64</a>.</p>

</div>
</div>

### visitEdge() {#af17752bb83c93e2b27cd3dc2e9436d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ELF_x86_64.cpp}::TLSInfoTableManager_ELF_x86_64::visitEdge (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> * B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1ae8b3d9d60bcce88f74377f0b3a845a3c">llvm::jitlink::x86_64::Delta32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#aa7e3f0047da154572ebef76ceee273d3">llvm::jitlink::TableManager&lt; TLSInfoTableManager_ELF_x86_64 &gt;::getEntryForTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1a11eeb5ae49b11ea2ebf2a6ac6c4c7bd8">llvm::jitlink::x86_64::RequestTLSDescInGOTAndTransformToDelta32</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getTLSInfoEntryContent() {#acd71b432b961d2d4379898af06268c28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; anonymous{ELF_x86_64.cpp}::TLSInfoTableManager_ELF_x86_64::getTLSInfoEntryContent ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a>.</p>

</div>
</div>

### getTLSInfoSection() {#ab70e5ae5ab402542fc3e11a9912aaf08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section &amp; anonymous{ELF_x86_64.cpp}::TLSInfoTableManager_ELF_x86_64::getTLSInfoSection (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TLSInfoTable {#ab649623e26528bfb7ba81c46913896af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section* anonymous{ELF_x86_64.cpp}::TLSInfoTableManager_ELF_x86_64::TLSInfoTable = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSectionName() {#a6d828834f23509ab883271b9f6c3a9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{ELF_x86_64.cpp}::TLSInfoTableManager_ELF_x86_64::getSectionName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/anonymous-elf-x86-64-cpp-/#a2a99b597e42aecc2540a88bd05a9630d">anonymous{ELF_x86_64.cpp}::ELFTLSInfoSectionName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### TLSInfoEntryContent {#ae5c2a93e1c789eb0836b4d288fc1575d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t anonymous{ELF_x86_64.cpp}::TLSInfoTableManager_ELF_x86_64::TLSInfoEntryContent</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 
    0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00  
}
</div>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-x86-64-cpp">ELF_x86_64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
