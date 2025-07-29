---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msp430attributeparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MSP430AttributeParser` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MSP430AttributeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">llvm/Support/MSP430AttributeParser.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24556d63d81ac54365f1695396fa987b">MSP430AttributeParser</a> (ScopedPrinter *SW)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a8689b406a7a55794611754ef34403d">MSP430AttributeParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9873315dd605fd2afcf49bdeb944948d">parseISA</a> (MSP430Attrs::AttrType Tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14496ae51bfa94b1a3c6447fcda3dd3d">parseCodeModel</a> (MSP430Attrs::AttrType Tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2385f271d12091717eee8757e6d76fa5">parseDataModel</a> (MSP430Attrs::AttrType Tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e810b7a35dc0612aa232d911645a13f">parseEnumSize</a> (MSP430Attrs::AttrType Tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a675739bc22917bf423819389940bc0fe">handler</a> (uint64_t Tag, bool &amp;Handled) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::array&lt; DisplayHandler, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec433642d21ca65cd5ac06facd39bb3">DisplayRoutines</a> = ...</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MSP430AttributeParser() {#a24556d63d81ac54365f1695396fa987b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MSP430AttributeParser::MSP430AttributeParser (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> * SW)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a4e104d3bf9f32e68ed3dacf1c6092931">llvm::ELFAttributeParser::ELFAttributeParser</a>.</p>

</div>
</div>

### MSP430AttributeParser() {#a7a8689b406a7a55794611754ef34403d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MSP430AttributeParser::MSP430AttributeParser ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a4e104d3bf9f32e68ed3dacf1c6092931">llvm::ELFAttributeParser::ELFAttributeParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### handler() {#a675739bc22917bf423819389940bc0fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSP430AttributeParser::handler (uint64_t Tag, bool &amp; Handled)</td>
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



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/msp430attributeparser-cpp">MSP430AttributeParser.cpp</a>.</p>

</div>
</div>

### parseCodeModel() {#a14496ae51bfa94b1a3c6447fcda3dd3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSP430AttributeParser::parseCodeModel (<a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2">MSP430Attrs::AttrType</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/msp430attributeparser-cpp">MSP430AttributeParser.cpp</a>.</p>

</div>
</div>

### parseDataModel() {#a2385f271d12091717eee8757e6d76fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSP430AttributeParser::parseDataModel (<a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2">MSP430Attrs::AttrType</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/msp430attributeparser-cpp">MSP430AttributeParser.cpp</a>.</p>

</div>
</div>

### parseEnumSize() {#a0e810b7a35dc0612aa232d911645a13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSP430AttributeParser::parseEnumSize (<a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2">MSP430Attrs::AttrType</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/support/msp430attributeparser-cpp">MSP430AttributeParser.cpp</a>.</p>

</div>
</div>

### parseISA() {#a9873315dd605fd2afcf49bdeb944948d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error MSP430AttributeParser::parseISA (<a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2">MSP430Attrs::AttrType</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/support/msp430attributeparser-cpp">MSP430AttributeParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### DisplayRoutines {#a7ec433642d21ca65cd5ac06facd39bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt; MSP430AttributeParser::DisplayHandler, 4 &gt; MSP430AttributeParser::DisplayRoutines</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
<div class="doxyVerbatim">{
        {{<a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2a4d25d5b65af344dd4b939cb17406b6b0">MSP430Attrs::TagISA</a>, &amp;MSP430AttributeParser::parseISA},
         {<a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2aaf6ddc682decf3aab85a609719eec5ef">MSP430Attrs::TagCodeModel</a>, &amp;MSP430AttributeParser::parseCodeModel},
         {<a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2a0c699a7ac7fd7947ab3740b46c70f9fc">MSP430Attrs::TagDataModel</a>, &amp;MSP430AttributeParser::parseDataModel},
         {<a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2a41c266908e316f3f3a96f955b4ff8d24">MSP430Attrs::TagEnumSize</a>, &amp;MSP430AttributeParser::parseEnumSize}}}
</div>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/msp430attributeparser-h">MSP430AttributeParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/msp430attributeparser-cpp">MSP430AttributeParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
