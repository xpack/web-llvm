---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-coffmasmparser-cpp-/coffmasmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `COFFMasmParser` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{COFFMasmParser.cpp}::COFFMasmParser { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc73e232ea30e12348154378e00ca99e">COFFMasmParser</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool(COFFMasmParser::*)(StringRef, SMLoc) HandlerMethod&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac27368048fd8dc84fe02ce845b50c153">addDirectiveHandler</a> (StringRef Directive)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c4ffda0d2da52050d3b875006afbf05">parseSectionSwitch</a> (StringRef SectionName, unsigned Characteristics)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425050f8b6f35c6cbddf2c9353c00089">parseSectionSwitch</a> (StringRef SectionName, unsigned Characteristics, StringRef COMDATSymName, COFF::COMDATType Type, Align Alignment)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be1fc4d3fd667a3f29672e78b71e0a7">parseDirectiveProc</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveProc TODO(epastor): Implement parameters and other attributes. <a href="#a6be1fc4d3fd667a3f29672e78b71e0a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d75043bfd9e4be16205da366077331">parseDirectiveEndProc</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367f44eddfeda59ee6583a92fcf93730">parseDirectiveSegment</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae295856d16c30f0412eace74b68da8">parseDirectiveSegmentEnd</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveSegmentEnd ::= identifier "ends" <a href="#a3ae295856d16c30f0412eace74b68da8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d72660b97dba6f8a53fad90bf5df18">parseDirectiveIncludelib</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveIncludelib ::= "includelib" identifier <a href="#a98d72660b97dba6f8a53fad90bf5df18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d8eb4f274bcfc96e9d8e026c1ba3fd">parseDirectiveOption</a> (StringRef, SMLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveOption ::= "option" option-list <a href="#a26d8eb4f274bcfc96e9d8e026c1ba3fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac101ba21c213419b95a0a5b7fbb1d4c4">parseDirectiveAlias</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae084e3c94d450c63a57403c4a03c8718">parseSEHDirectiveAllocStack</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1a4cf0616001ff0d21f51f795ab058">parseSEHDirectiveEndProlog</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0e2828ceaad9866d7791259a422735">IgnoreDirective</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dcba6dee36a828602f7f8b5aaf4ee99">Initialize</a> (MCAsmParser &amp;Parser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the extension for parsing using the given <span class="doxyComputerOutput">Parser</span>. <a href="#a5dcba6dee36a828602f7f8b5aaf4ee99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61de4a193cb6f97b2c69432159b13a06">parseSectionDirectiveCode</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3857887640500c1338434467005b1f35">parseSectionDirectiveInitializedData</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8191c443bc7d629ad89e3a8b400fe072">parseSectionDirectiveUninitializedData</a> (StringRef, SMLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde5e48badd2f7e0916826ed493e749e">CurrentProcedures</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack of active procedure definitions. <a href="#abde5e48badd2f7e0916826ed493e749e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; bool, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2119e041d3951b96c1f2131d62281981">CurrentProceduresFramed</a></td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### COFFMasmParser() {#afc73e232ea30e12348154378e00ca99e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{COFFMasmParser.cpp}::COFFMasmParser::COFFMasmParser ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDirectiveHandler() {#ac27368048fd8dc84fe02ce845b50c153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool(COFFMasmParser::*)(StringRef, SMLoc) HandlerMethod&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{COFFMasmParser.cpp}::COFFMasmParser::addDirectiveHandler (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### IgnoreDirective() {#a0f0e2828ceaad9866d7791259a422735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFMasmParser.cpp}::COFFMasmParser::IgnoreDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### Initialize() {#a5dcba6dee36a828602f7f8b5aaf4ee99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{COFFMasmParser.cpp}::COFFMasmParser::Initialize (<a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; Parser)</td>
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


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveAlias() {#ac101ba21c213419b95a0a5b7fbb1d4c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseDirectiveAlias (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEndProc() {#a94d75043bfd9e4be16205da366077331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseDirectiveEndProc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveIncludelib() {#a98d72660b97dba6f8a53fad90bf5df18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseDirectiveIncludelib (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveIncludelib ::= "includelib" identifier</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveOption() {#a26d8eb4f274bcfc96e9d8e026c1ba3fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseDirectiveOption (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveOption ::= "option" option-list</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveProc() {#a6be1fc4d3fd667a3f29672e78b71e0a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseDirectiveProc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveProc TODO(epastor): Implement parameters and other attributes.</p>


<p>::= label "proc" [[distance]] statements label "endproc"</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSegment() {#a367f44eddfeda59ee6583a92fcf93730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseDirectiveSegment (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSegmentEnd() {#a3ae295856d16c30f0412eace74b68da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseDirectiveSegmentEnd (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveSegmentEnd ::= identifier "ends"</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveCode() {#a61de4a193cb6f97b2c69432159b13a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFMasmParser.cpp}::COFFMasmParser::parseSectionDirectiveCode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveInitializedData() {#a3857887640500c1338434467005b1f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFMasmParser.cpp}::COFFMasmParser::parseSectionDirectiveInitializedData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseSectionDirectiveUninitializedData() {#a8191c443bc7d629ad89e3a8b400fe072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFMasmParser.cpp}::COFFMasmParser::parseSectionDirectiveUninitializedData (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseSectionSwitch() {#a3c4ffda0d2da52050d3b875006afbf05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseSectionSwitch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, unsigned Characteristics)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseSectionSwitch() {#a425050f8b6f35c6cbddf2c9353c00089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseSectionSwitch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, unsigned Characteristics, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> COMDATSymName, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45e">COFF::COMDATType</a> Type, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseSEHDirectiveAllocStack() {#ae084e3c94d450c63a57403c4a03c8718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseSEHDirectiveAllocStack (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### parseSEHDirectiveEndProlog() {#ace1a4cf0616001ff0d21f51f795ab058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COFFMasmParser::parseSEHDirectiveEndProlog (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directive, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentProcedures {#abde5e48badd2f7e0916826ed493e749e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StringRef, 1&gt; anonymous{COFFMasmParser.cpp}::COFFMasmParser::CurrentProcedures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stack of active procedure definitions.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

### CurrentProceduresFramed {#a2119e041d3951b96c1f2131d62281981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;bool, 1&gt; anonymous{COFFMasmParser.cpp}::COFFMasmParser::CurrentProceduresFramed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/coffmasmparser-cpp">COFFMasmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
