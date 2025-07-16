---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonattributeparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonAttributeParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonAttributeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributeparser-h">llvm/Support/HexagonAttributeParser.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elfattributeparser">ELFAttributeParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab61282f496d523cd7b78dded004f3f20">HexagonAttributeParser</a> (ScopedPrinter *SP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297734e496c2c405d4d5400f47aa9c10">HexagonAttributeParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac81412b443eaf8b5166a1071fce65c6">handler</a> (uint64_t Tag, bool &amp;Handled) override</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DisplayHandler</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad714f91695c3dcea219d4975ace80594">DisplayRoutines</a>[] = ...</td>
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


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributeparser-h">HexagonAttributeParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonAttributeParser() {#ab61282f496d523cd7b78dded004f3f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HexagonAttributeParser::HexagonAttributeParser (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> * SP)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributeparser-h">HexagonAttributeParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a4e104d3bf9f32e68ed3dacf1c6092931">llvm::ELFAttributeParser::ELFAttributeParser</a>.</p>

</div>
</div>

### HexagonAttributeParser() {#a297734e496c2c405d4d5400f47aa9c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HexagonAttributeParser::HexagonAttributeParser ()</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributeparser-h">HexagonAttributeParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a4e104d3bf9f32e68ed3dacf1c6092931">llvm::ELFAttributeParser::ELFAttributeParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### handler() {#aac81412b443eaf8b5166a1071fce65c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error HexagonAttributeParser::handler (uint64_t Tag, bool &amp; Handled)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributeparser-h">HexagonAttributeParser.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/hexagonattributeparser-cpp">HexagonAttributeParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### DisplayRoutines {#ad714f91695c3dcea219d4975ace80594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonAttributeParser::DisplayHandler HexagonAttributeParser::DisplayRoutines</td>
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
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/hexagonattrs/#a9273648ff11b0cd9cc6c1fca21757b0aadf72f328baf0f5acf40009bfc48dabb3">HexagonAttrs::ARCH</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/hexagonattrs/#a9273648ff11b0cd9cc6c1fca21757b0aac5818b77afe27e45bb4800bc6ccf19ba">HexagonAttrs::HVXARCH</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/hexagonattrs/#a9273648ff11b0cd9cc6c1fca21757b0aa473fdbf9b41b7242e1d5b95a3cd91753">HexagonAttrs::HVXIEEEFP</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/hexagonattrs/#a9273648ff11b0cd9cc6c1fca21757b0aa7f4e1b73534a3e4fe81b45dfa70e4fa8">HexagonAttrs::HVXQFLOAT</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/hexagonattrs/#a9273648ff11b0cd9cc6c1fca21757b0aa7616170e3a6a5aa236da071bf245f9fb">HexagonAttrs::ZREG</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/hexagonattrs/#a9273648ff11b0cd9cc6c1fca21757b0aae726e716c8bf8c371147056555698773">HexagonAttrs::AUDIO</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        },
        {
            <a href="/web-llvm/docs/api/namespaces/llvm/hexagonattrs/#a9273648ff11b0cd9cc6c1fca21757b0aaab7a5dc2a04b0f4ee795b3b9254a46cd">HexagonAttrs::CABAC</a>,
            &amp;<a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a3e050c88f97b0583ca8a9ccb9df7f9af">ELFAttributeParser::integerAttribute</a>,
        }}
</div>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributeparser-h">HexagonAttributeParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hexagonattributeparser-h">HexagonAttributeParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/hexagonattributeparser-cpp">HexagonAttributeParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
