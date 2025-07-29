---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-elf-ppc64-cpp-/tlsinfotablemanager-elf-ppc64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TLSInfoTableManager_ELF_ppc64` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;llvm::endianness Endianness&gt;
class anonymous{ELF_ppc64.cpp}::TLSInfoTableManager_ELF_ppc64&lt;Endianness&gt; { ... }
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd7abf544be1364aa64435a8bc0be7cc">visitEdge</a> (LinkGraph &amp;G, Block *B, Edge &amp;E)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b932a2f74c995a1150db705ae263e62">createEntry</a> (LinkGraph &amp;G, Symbol &amp;Target)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e7296120ee9f16af6d7b3f88982f595">getTLSInfoSection</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8127c586e49b1a435f5e6c6587188277">getTLSInfoEntryContent</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29f47be6abdd757d3176e5b141d33371">TLSInfoTable</a> = nullptr</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5226c30384cab140c14ca4c63b1a9786">getSectionName</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a075380f137515374ef5cb5e455d1e56c">TLSInfoEntryContent</a>[16]</td>
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


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### createEntry() {#a3b932a2f74c995a1150db705ae263e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; anonymous{ELF_ppc64.cpp}::TLSInfoTableManager_ELF_ppc64&lt; Endianness &gt;::createEntry (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a62e5186b5b7eee2c22dd5735802711d8a35104bd2d350c94d154842e63096099c">llvm::jitlink::ppc64::Pointer64</a>.</p>

</div>
</div>

### visitEdge() {#abd7abf544be1364aa64435a8bc0be7cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ELF_ppc64.cpp}::TLSInfoTableManager_ELF_ppc64&lt; Endianness &gt;::visitEdge (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> * B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a62e5186b5b7eee2c22dd5735802711d8a208d06ad3405d944c445dd9cb4b876aa">llvm::jitlink::ppc64::Delta34</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#aa7e3f0047da154572ebef76ceee273d3">llvm::jitlink::TableManager&lt; TLSInfoTableManager_ELF_ppc64&lt; Endianness &gt; &gt;::getEntryForTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a62e5186b5b7eee2c22dd5735802711d8af8e4dff79b8ebb15b6a0507ea61530e6">llvm::jitlink::ppc64::RequestTLSDescInGOTAndTransformToDelta34</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a62e5186b5b7eee2c22dd5735802711d8a1d56faaaf3676f55c53f948247267ee7">llvm::jitlink::ppc64::RequestTLSDescInGOTAndTransformToTOCDelta16HA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a62e5186b5b7eee2c22dd5735802711d8ac5d30e291a54fa2a02d0e940b6e6caf3">llvm::jitlink::ppc64::RequestTLSDescInGOTAndTransformToTOCDelta16LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a62e5186b5b7eee2c22dd5735802711d8a49e40be62398c90fc457740b224662b3">llvm::jitlink::ppc64::TOCDelta16HA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a62e5186b5b7eee2c22dd5735802711d8ac0f8ae47549b69efe5d94a7c7d242d3f">llvm::jitlink::ppc64::TOCDelta16LO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getTLSInfoEntryContent() {#a8127c586e49b1a435f5e6c6587188277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; char &gt; anonymous{ELF_ppc64.cpp}::TLSInfoTableManager_ELF_ppc64&lt; Endianness &gt;::getTLSInfoEntryContent ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>

</div>
</div>

### getTLSInfoSection() {#a2e7296120ee9f16af6d7b3f88982f595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section &amp; anonymous{ELF_ppc64.cpp}::TLSInfoTableManager_ELF_ppc64&lt; Endianness &gt;::getTLSInfoSection (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TLSInfoTable {#a29f47be6abdd757d3176e5b141d33371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section* anonymous{ELF_ppc64.cpp}::TLSInfoTableManager_ELF_ppc64&lt; Endianness &gt;::TLSInfoTable = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSectionName() {#a5226c30384cab140c14ca4c63b1a9786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{ELF_ppc64.cpp}::TLSInfoTableManager_ELF_ppc64&lt; Endianness &gt;::getSectionName ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/anonymous-elf-ppc64-cpp-/#a8398c589a7a6b3d2560d03cc09890150">anonymous{ELF_ppc64.cpp}::ELFTLSInfoSectionName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### TLSInfoEntryContent {#a075380f137515374ef5cb5e455d1e56c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t anonymous{ELF_ppc64.cpp}::TLSInfoTableManager_ELF_ppc64&lt; Endianness &gt;::TLSInfoEntryContent[16]</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
