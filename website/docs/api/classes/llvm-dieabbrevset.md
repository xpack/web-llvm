---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dieabbrevset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DIEAbbrevSet` Class

<p>Helps unique <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> objects and assigns abbreviation numbers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIEAbbrevSet { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">llvm/CodeGen/DIE.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e83dd8cb7de630638e17887abc1d76">DIEAbbrevSet</a> (BumpPtrAllocator &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fd19f2ffd1e62aefd56a2197a96abe">~DIEAbbrevSet</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd0912271cf17bd2b546eec9350021fa">uniqueAbbreviation</a> (DIE &amp;Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the abbreviation declaration for a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and return a pointer to the generated abbreviation. <a href="#acd0912271cf17bd2b546eec9350021fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d601668e33175cdf6b766ebc3f2d790">Emit</a> (const AsmPrinter *AP, MCSection *Section) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print all abbreviations using the specified asm printer. <a href="#a6d601668e33175cdf6b766ebc3f2d790">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010a43d954def201fa44441aa6fdc169">Alloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bump allocator to use when creating <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> objects in the uniqued storage container. <a href="#a010a43d954def201fa44441aa6fdc169">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e3153b5822dd17b755b217dcbbc7449">AbbreviationsSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> that uniques the abbreviations. <a href="#a5e3153b5822dd17b755b217dcbbc7449">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1af1758486bf21e3a80dc6a09199c9">Abbreviations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of all the unique abbreviations in use. <a href="#afb1af1758486bf21e3a80dc6a09199c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helps unique <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> objects and assigns abbreviation numbers.</p>


<p>This class will unique the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> abbreviations for a <a href="/web-llvm/docs/api/classes/llvm/die">llvm::DIE</a> object and assign a unique abbreviation number to each unique <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> object it finds. The resulting collection of <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> objects can then be emitted into the .debug_abbrev section.</p>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DIEAbbrevSet() {#ab1e83dd8cb7de630638e17887abc1d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIEAbbrevSet::DIEAbbrevSet (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; A)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DIEAbbrevSet() {#a44fd19f2ffd1e62aefd56a2197a96abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEAbbrevSet::~DIEAbbrevSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Emit() {#a6d601668e33175cdf6b766ebc3f2d790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DIEAbbrevSet::Emit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * AP, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print all abbreviations using the specified asm printer.</p>

<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa1be0c2d757c08ab5a681f4cf1c675aa">llvm::AsmPrinter::emitDwarfAbbrevs</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>

</div>
</div>

### uniqueAbbreviation() {#acd0912271cf17bd2b546eec9350021fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEAbbrev &amp; DIEAbbrevSet::uniqueAbbreviation (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the abbreviation declaration for a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and return a pointer to the generated abbreviation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Die</td>
<td class="doxyParamItemDescription"><p>the debug info entry to generate the abbreviation for.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A reference to the uniqued abbreviation declaration that is owned by this class.</p></dd>
</dl>


<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#a47e67f02f858b710768cbecf7fd08244">llvm::DIE::generateAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#af069b02ba0f553e53d79932413de7375">llvm::DIEAbbrev::Profile</a> and <a href="/web-llvm/docs/api/classes/llvm/die/#ab1516bd8f1676ec9e541a375a0dea5b1">llvm::DIE::setAbbrevNumber</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/die/#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">llvm::DIE::computeOffsetsAndAbbrevs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Abbreviations {#afb1af1758486bf21e3a80dc6a09199c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DIEAbbrev *&gt; llvm::DIEAbbrevSet::Abbreviations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of all the unique abbreviations in use.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### AbbreviationsSet {#a5e3153b5822dd17b755b217dcbbc7449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;DIEAbbrev&gt; llvm::DIEAbbrevSet::AbbreviationsSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> that uniques the abbreviations.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### Alloc {#a010a43d954def201fa44441aa6fdc169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator&amp; llvm::DIEAbbrevSet::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The bump allocator to use when creating <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> objects in the uniqued storage container.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
