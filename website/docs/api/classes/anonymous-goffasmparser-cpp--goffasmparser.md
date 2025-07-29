---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-goffasmparser-cpp-/goffasmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GOFFAsmParser` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{GOFFAsmParser.cpp}::GOFFAsmParser { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension">MCAsmParserExtension</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic interface for extending the <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a>, which is implemented by target and object file assembly parser implementations. <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a123886a156b40144409a9877cd81f">GOFFAsmParser</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb9151f16b7b4e5c5baef65216d8f4e5">Initialize</a> (MCAsmParser &amp;Parser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the extension for parsing using the given <span class="doxyComputerOutput">Parser</span>. <a href="#afb9151f16b7b4e5c5baef65216d8f4e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool(GOFFAsmParser::*)(StringRef, SMLoc) HandlerMethod&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac27e18efde466fc48fd802008bb2be37">addDirectiveHandler</a> (StringRef Directive)</td>
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


<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/goffasmparser-cpp">GOFFAsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GOFFAsmParser() {#a42a123886a156b40144409a9877cd81f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GOFFAsmParser.cpp}::GOFFAsmParser::GOFFAsmParser ()</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/goffasmparser-cpp">GOFFAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Initialize() {#afb9151f16b7b4e5c5baef65216d8f4e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GOFFAsmParser.cpp}::GOFFAsmParser::Initialize (<a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; Parser)</td>
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

<p>Initialize the extension for parsing using the given <span class="doxyComputerOutput">Parser</span>.</p>


<p>The extension should use the AsmParser interfaces to register its parsing routines.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/goffasmparser-cpp">GOFFAsmParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a77a335167c72ea8bc771501825f81696">llvm::MCAsmParserExtension::Initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDirectiveHandler() {#ac27e18efde466fc48fd802008bb2be37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool(GOFFAsmParser::*)(StringRef, SMLoc) HandlerMethod&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GOFFAsmParser.cpp}::GOFFAsmParser::addDirectiveHandler (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
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



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/goffasmparser-cpp">GOFFAsmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/goffasmparser-cpp">GOFFAsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
