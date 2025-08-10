---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-acceltable-cpp-/acceltablewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AccelTableWriter` Class

<p>Base class for writing out Accelerator tables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AccelTable.cpp}::AccelTableWriter { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter">AppleAccelTableWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter">Dwarf5AccelTableWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class responsible for emitting a DWARF v5 Accelerator Table. <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b0b0a6559169f7508cff3c9311946a">AccelTableWriter</a> (AsmPrinter *Asm, const AccelTableBase &amp;Contents, bool SkipIdenticalHashes)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705045ebd290d3840b1a2b72bb424c06">emitHashes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637e26f48b1c1e072264db82f1ebbf1d">emitOffsets</a> (const MCSymbol *Base) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit offsets to lists of entries with identical names. <a href="#a637e26f48b1c1e072264db82f1ebbf1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047163be3726b86f4d519feac5285381">Asm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destination. <a href="#a047163be3726b86f4d519feac5285381">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/acceltablebase">AccelTableBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c33c0cb3b4ac527800f9e14057e941b">Contents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data to emit. <a href="#a2c33c0cb3b4ac527800f9e14057e941b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77c3dcce85f3af6ce04fdf3f71376b4a">SkipIdenticalHashes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Controls whether to emit duplicate hash and offset table entries for names with identical hashes. <a href="#a77c3dcce85f3af6ce04fdf3f71376b4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class for writing out Accelerator tables.</p>


<p>It holds the common functionality for the two Accelerator table types.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AccelTableWriter() {#ad8b0b0a6559169f7508cff3c9311946a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AccelTable.cpp}::AccelTableWriter::AccelTableWriter (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/acceltablebase">AccelTableBase</a> &amp; Contents, bool SkipIdenticalHashes)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="#a047163be3726b86f4d519feac5285381">Asm</a>, <a href="#a2c33c0cb3b4ac527800f9e14057e941b">Contents</a> and <a href="#a77c3dcce85f3af6ce04fdf3f71376b4a">SkipIdenticalHashes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#a83227e4651c7d8881ea5eff7450dd607">anonymous{AccelTable.cpp}::AppleAccelTableWriter::AppleAccelTableWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter/#ac9fcce12a4cf8ec49ed9cb6aaf1abb62">anonymous{AccelTable.cpp}::Dwarf5AccelTableWriter::Dwarf5AccelTableWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### emitHashes() {#a705045ebd290d3840b1a2b72bb424c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AccelTableWriter::emitHashes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="#a047163be3726b86f4d519feac5285381">Asm</a>, <a href="#a2c33c0cb3b4ac527800f9e14057e941b">Contents</a> and <a href="#a77c3dcce85f3af6ce04fdf3f71376b4a">SkipIdenticalHashes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#acfd63413de95475625faeecc96bef75f">anonymous{AccelTable.cpp}::AppleAccelTableWriter::emit</a> and <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter/#adf16303e57e2bd8a12ca84436de012be">anonymous{AccelTable.cpp}::Dwarf5AccelTableWriter::emit</a>.</p>

</div>
</div>

### emitOffsets() {#a637e26f48b1c1e072264db82f1ebbf1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AccelTableWriter::emitOffsets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Base)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit offsets to lists of entries with identical names.</p>


<p>The offsets are relative to the Base argument.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>References <a href="#a047163be3726b86f4d519feac5285381">Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="#a2c33c0cb3b4ac527800f9e14057e941b">Contents</a> and <a href="#a77c3dcce85f3af6ce04fdf3f71376b4a">SkipIdenticalHashes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#acfd63413de95475625faeecc96bef75f">anonymous{AccelTable.cpp}::AppleAccelTableWriter::emit</a> and <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter/#adf16303e57e2bd8a12ca84436de012be">anonymous{AccelTable.cpp}::Dwarf5AccelTableWriter::emit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Asm {#a047163be3726b86f4d519feac5285381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter* const anonymous{AccelTable.cpp}::AccelTableWriter::Asm</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destination.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>Referenced by <a href="#ad8b0b0a6559169f7508cff3c9311946a">AccelTableWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#a83227e4651c7d8881ea5eff7450dd607">anonymous{AccelTable.cpp}::AppleAccelTableWriter::AppleAccelTableWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter/#ac9fcce12a4cf8ec49ed9cb6aaf1abb62">anonymous{AccelTable.cpp}::Dwarf5AccelTableWriter::Dwarf5AccelTableWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#acfd63413de95475625faeecc96bef75f">anonymous{AccelTable.cpp}::AppleAccelTableWriter::emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter/#adf16303e57e2bd8a12ca84436de012be">anonymous{AccelTable.cpp}::Dwarf5AccelTableWriter::emit</a>, <a href="#a705045ebd290d3840b1a2b72bb424c06">emitHashes</a> and <a href="#a637e26f48b1c1e072264db82f1ebbf1d">emitOffsets</a>.</p>

</div>
</div>

### Contents {#a2c33c0cb3b4ac527800f9e14057e941b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AccelTableBase&amp; anonymous{AccelTable.cpp}::AccelTableWriter::Contents</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Data to emit.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>Referenced by <a href="#ad8b0b0a6559169f7508cff3c9311946a">AccelTableWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#a83227e4651c7d8881ea5eff7450dd607">anonymous{AccelTable.cpp}::AppleAccelTableWriter::AppleAccelTableWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter/#ac9fcce12a4cf8ec49ed9cb6aaf1abb62">anonymous{AccelTable.cpp}::Dwarf5AccelTableWriter::Dwarf5AccelTableWriter</a>, <a href="#a705045ebd290d3840b1a2b72bb424c06">emitHashes</a>, <a href="#a637e26f48b1c1e072264db82f1ebbf1d">emitOffsets</a> and <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/appleacceltablewriter/#a916ddc9f4023fb6f2b28aa80dbf07b06">anonymous{AccelTable.cpp}::AppleAccelTableWriter::print</a>.</p>

</div>
</div>

### SkipIdenticalHashes {#a77c3dcce85f3af6ce04fdf3f71376b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{AccelTable.cpp}::AccelTableWriter::SkipIdenticalHashes</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Controls whether to emit duplicate hash and offset table entries for names with identical hashes.</p>


<p>Apple tables don't emit duplicate entries, DWARF v5 tables do.</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a>.</p>


<p>Referenced by <a href="#ad8b0b0a6559169f7508cff3c9311946a">AccelTableWriter</a>, <a href="#a705045ebd290d3840b1a2b72bb424c06">emitHashes</a> and <a href="#a637e26f48b1c1e072264db82f1ebbf1d">emitOffsets</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/acceltable-cpp">AccelTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
