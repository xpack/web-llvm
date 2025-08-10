---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/elfattributeparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFAttributeParser` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ELFAttributeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">llvm/Support/ELFAttributeParser.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armattributeparser">ARMAttributeParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskyattributeparser">CSKYAttributeParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonattributeparser">HexagonAttributeParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msp430attributeparser">MSP430AttributeParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/riscvattributeparser">RISCVAttributeParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e104d3bf9f32e68ed3dacf1c6092931">ELFAttributeParser</a> (ScopedPrinter *sw, TagNameMap tagNameMap, StringRef vendor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f1ba395da37cb67d8b53f8cc704fc56">ELFAttributeParser</a> (TagNameMap tagNameMap, StringRef vendor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7efb6f565f0140e7b6040503539fb2a">~ELFAttributeParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e050c88f97b0583ca8a9ccb9df7f9af">integerAttribute</a> (unsigned tag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8125ecaffe4cb18a746e29ec30bc74c5">stringAttribute</a> (unsigned tag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9587b0ef9788175b49acc32e1c898642">parse</a> (ArrayRef&lt; uint8_t &gt; section, llvm::endianness endian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a207779d13fed42f02893a3096e8ff328">getAttributeValue</a> (unsigned tag) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083d0eedffe19bf92df537fd8a11571d">getAttributeString</a> (unsigned tag) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf641c6eb9421f15fc9015e7032b71fb">printAttribute</a> (unsigned tag, unsigned value, StringRef valueDesc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf992f403d584a1d6b24de79a3a658b5">parseStringAttribute</a> (const char *name, unsigned tag, ArrayRef&lt; const char * &gt; strings)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb88a873af45ca9f6207336e0b468856">parseAttributeList</a> (uint32_t length)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2d289101e52d2729fd86ac7ca68772">parseIndexList</a> (SmallVectorImpl&lt; uint8_t &gt; &amp;indexList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d8a789e50e085fa66aac9180bb03f3">parseSubsection</a> (uint32_t length)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e06169ca2f03a40e79318702704cb1">setAttributeString</a> (unsigned tag, StringRef value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf650cd29f0ab60c7104fca128c62e35">handler</a> (uint64_t tag, bool &amp;handled)=0</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a967d07f3cace8ee5af66bff6585e03e7">sw</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ba0ebd86185aea94f29ed853c4dd97f">TagNameMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3c8aaff4a817ff6c9aae5df0bbe584">tagToStringMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa099e08a0997abcb0f937dffb3957418">de</a> {<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;{}, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, 0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor">DataExtractor::Cursor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a> {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22f72d456dc53c91ba29ab365a4bb62">vendor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7909c56988c2bcaf961eed5a16ce2e8">attributes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a02897cf2eb33f72a52cc7cc078c4e5">attributesStr</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ELFAttributeParser() {#a4e104d3bf9f32e68ed3dacf1c6092931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ELFAttributeParser::ELFAttributeParser (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> * sw, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ba0ebd86185aea94f29ed853c4dd97f">TagNameMap</a> tagNameMap, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> vendor)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>References <a href="#a967d07f3cace8ee5af66bff6585e03e7">sw</a> and <a href="#afa3c8aaff4a817ff6c9aae5df0bbe584">tagToStringMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armattributeparser/#a498c870c5a55dfc5aa1c12cbafab18b8">llvm::ARMAttributeParser::ARMAttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/armattributeparser/#a545be58faa673963fbfc0e98bd0b35c4">llvm::ARMAttributeParser::ARMAttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyattributeparser/#aad841970297b7647ffd84c5994d0a3ec">llvm::CSKYAttributeParser::CSKYAttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyattributeparser/#a8874ef465443bdd1fd195925c79e63f1">llvm::CSKYAttributeParser::CSKYAttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonattributeparser/#a297734e496c2c405d4d5400f47aa9c10">llvm::HexagonAttributeParser::HexagonAttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonattributeparser/#ab61282f496d523cd7b78dded004f3f20">llvm::HexagonAttributeParser::HexagonAttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430attributeparser/#a7a8689b406a7a55794611754ef34403d">llvm::MSP430AttributeParser::MSP430AttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430attributeparser/#a24556d63d81ac54365f1695396fa987b">llvm::MSP430AttributeParser::MSP430AttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvattributeparser/#ab8e18d04814ec8608af0c5e45746c2b4">llvm::RISCVAttributeParser::RISCVAttributeParser</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvattributeparser/#a0fc87f311de36e8b0566898d44951ff0">llvm::RISCVAttributeParser::RISCVAttributeParser</a>.</p>

</div>
</div>

### ELFAttributeParser() {#a5f1ba395da37cb67d8b53f8cc704fc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ELFAttributeParser::ELFAttributeParser (<a href="/web-llvm/docs/api/namespaces/llvm/#a8ba0ebd86185aea94f29ed853c4dd97f">TagNameMap</a> tagNameMap, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> vendor)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>References <a href="#a967d07f3cace8ee5af66bff6585e03e7">sw</a> and <a href="#afa3c8aaff4a817ff6c9aae5df0bbe584">tagToStringMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ELFAttributeParser() {#ae7efb6f565f0140e7b6040503539fb2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::ELFAttributeParser::~ELFAttributeParser ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>Reference <a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAttributeString() {#a083d0eedffe19bf92df537fd8a11571d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; llvm::ELFAttributeParser::getAttributeString (unsigned tag)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getAttributeValue() {#a207779d13fed42f02893a3096e8ff328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::ELFAttributeParser::getAttributeValue (unsigned tag)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### integerAttribute() {#a3e050c88f97b0583ca8a9ccb9df7f9af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ELFAttributeParser::integerAttribute (unsigned tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a66b1304ca72d9916db93a0ab9a55697c">llvm::ELFAttrs::attrTypeAsString</a>, <a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a>, <a href="#aa099e08a0997abcb0f937dffb3957418">de</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a967d07f3cace8ee5af66bff6585e03e7">sw</a> and <a href="#afa3c8aaff4a817ff6c9aae5df0bbe584">tagToStringMap</a>.</p>


<p>Referenced by <a href="#aeb88a873af45ca9f6207336e0b468856">parseAttributeList</a>.</p>

</div>
</div>

### parse() {#a9587b0ef9788175b49acc32e1c898642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ELFAttributeParser::parse (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; section, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> endian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a>, <a href="#aa099e08a0997abcb0f937dffb3957418">de</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a98edb75fed695278964e1ea77f18859eae7742b85dba4e5f75602e8141161f3aa">llvm::ELFAttrs::Format_Version</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="#a02d8a789e50e085fa66aac9180bb03f3">parseSubsection</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="#a967d07f3cace8ee5af66bff6585e03e7">sw</a>.</p>

</div>
</div>

### stringAttribute() {#a8125ecaffe4cb18a746e29ec30bc74c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ELFAttributeParser::stringAttribute (unsigned tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a66b1304ca72d9916db93a0ab9a55697c">llvm::ELFAttrs::attrTypeAsString</a>, <a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a>, <a href="#aa099e08a0997abcb0f937dffb3957418">de</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a01e06169ca2f03a40e79318702704cb1">setAttributeString</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a967d07f3cace8ee5af66bff6585e03e7">sw</a> and <a href="#afa3c8aaff4a817ff6c9aae5df0bbe584">tagToStringMap</a>.</p>


<p>Referenced by <a href="#aeb88a873af45ca9f6207336e0b468856">parseAttributeList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### parseAttributeList() {#aeb88a873af45ca9f6207336e0b468856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ELFAttributeParser::parseAttributeList (uint32_t length)</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a>, <a href="#aa099e08a0997abcb0f937dffb3957418">de</a>, <a href="#a3e050c88f97b0583ca8a9ccb9df7f9af">integerAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="#a8125ecaffe4cb18a746e29ec30bc74c5">stringAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="#a02d8a789e50e085fa66aac9180bb03f3">parseSubsection</a>.</p>

</div>
</div>

### parseIndexList() {#abf2d289101e52d2729fd86ac7ca68772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFAttributeParser::parseIndexList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint8_t &gt; &amp; indexList)</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a>.</p>


<p>References <a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a>, <a href="#aa099e08a0997abcb0f937dffb3957418">de</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a02d8a789e50e085fa66aac9180bb03f3">parseSubsection</a>.</p>

</div>
</div>

### parseStringAttribute() {#abf992f403d584a1d6b24de79a3a658b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ELFAttributeParser::parseStringAttribute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * name, unsigned tag, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; strings)</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a>, <a href="#aa099e08a0997abcb0f937dffb3957418">de</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, <a href="#adf641c6eb9421f15fc9015e7032b71fb">printAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parseSubsection() {#a02d8a789e50e085fa66aac9180bb03f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ELFAttributeParser::parseSubsection (uint32_t length)</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a450168715df2bd34e4977ecff04bde9c">cursor</a>, <a href="#aa099e08a0997abcb0f937dffb3957418">de</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#aa46aca112d24ab2b441b7d20c1347d5bac426776933be86220f05be6639a95c73">llvm::ELFAttrs::File</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#abb1344e353958db14e66ec7ab574001a">llvm::StringRef::lower</a>, <a href="#aeb88a873af45ca9f6207336e0b468856">parseAttributeList</a>, <a href="#abf2d289101e52d2729fd86ac7ca68772">parseIndexList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#aa46aca112d24ab2b441b7d20c1347d5baf632635dd81ad2bef6f5c7503326dfe8">llvm::ELFAttrs::Section</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a967d07f3cace8ee5af66bff6585e03e7">sw</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#aa46aca112d24ab2b441b7d20c1347d5ba9d8eedd05cd730bd23ef530cb80040ee">llvm::ELFAttrs::Symbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp/#accde124e99d0861db753f470d59550c9">tagNames</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>


<p>Referenced by <a href="#a9587b0ef9788175b49acc32e1c898642">parse</a>.</p>

</div>
</div>

### printAttribute() {#adf641c6eb9421f15fc9015e7032b71fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ELFAttributeParser::printAttribute (unsigned tag, unsigned value, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> valueDesc)</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elfattrs/#a66b1304ca72d9916db93a0ab9a55697c">llvm::ELFAttrs::attrTypeAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a967d07f3cace8ee5af66bff6585e03e7">sw</a> and <a href="#afa3c8aaff4a817ff6c9aae5df0bbe584">tagToStringMap</a>.</p>


<p>Referenced by <a href="#abf992f403d584a1d6b24de79a3a658b5">parseStringAttribute</a>.</p>

</div>
</div>

### setAttributeString() {#a01e06169ca2f03a40e79318702704cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ELFAttributeParser::setAttributeString (unsigned tag, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>Referenced by <a href="#a8125ecaffe4cb18a746e29ec30bc74c5">stringAttribute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### handler() {#acf650cd29f0ab60c7104fca128c62e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::ELFAttributeParser::handler (uint64_t tag, bool &amp; handled)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### cursor {#a450168715df2bd34e4977ecff04bde9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataExtractor::Cursor llvm::ELFAttributeParser::cursor {0}</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>Referenced by <a href="#a3e050c88f97b0583ca8a9ccb9df7f9af">integerAttribute</a>, <a href="#a9587b0ef9788175b49acc32e1c898642">parse</a>, <a href="#aeb88a873af45ca9f6207336e0b468856">parseAttributeList</a>, <a href="#abf2d289101e52d2729fd86ac7ca68772">parseIndexList</a>, <a href="#abf992f403d584a1d6b24de79a3a658b5">parseStringAttribute</a>, <a href="#a02d8a789e50e085fa66aac9180bb03f3">parseSubsection</a>, <a href="#a8125ecaffe4cb18a746e29ec30bc74c5">stringAttribute</a> and <a href="#ae7efb6f565f0140e7b6040503539fb2a">~ELFAttributeParser</a>.</p>

</div>
</div>

### de {#aa099e08a0997abcb0f937dffb3957418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataExtractor llvm::ELFAttributeParser::de {<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;{}, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, 0}</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>Referenced by <a href="#a3e050c88f97b0583ca8a9ccb9df7f9af">integerAttribute</a>, <a href="#a9587b0ef9788175b49acc32e1c898642">parse</a>, <a href="#aeb88a873af45ca9f6207336e0b468856">parseAttributeList</a>, <a href="#abf2d289101e52d2729fd86ac7ca68772">parseIndexList</a>, <a href="#abf992f403d584a1d6b24de79a3a658b5">parseStringAttribute</a>, <a href="#a02d8a789e50e085fa66aac9180bb03f3">parseSubsection</a> and <a href="#a8125ecaffe4cb18a746e29ec30bc74c5">stringAttribute</a>.</p>

</div>
</div>

### sw {#a967d07f3cace8ee5af66bff6585e03e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedPrinter* llvm::ELFAttributeParser::sw</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armattributeparser/#a545be58faa673963fbfc0e98bd0b35c4">llvm::ARMAttributeParser::ARMAttributeParser</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyattributeparser/#a8874ef465443bdd1fd195925c79e63f1">llvm::CSKYAttributeParser::CSKYAttributeParser</a>, <a href="#a4e104d3bf9f32e68ed3dacf1c6092931">ELFAttributeParser</a>, <a href="#a5f1ba395da37cb67d8b53f8cc704fc56">ELFAttributeParser</a>, <a href="#a3e050c88f97b0583ca8a9ccb9df7f9af">integerAttribute</a>, <a href="#a9587b0ef9788175b49acc32e1c898642">parse</a>, <a href="#a02d8a789e50e085fa66aac9180bb03f3">parseSubsection</a>, <a href="#adf641c6eb9421f15fc9015e7032b71fb">printAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvattributeparser/#a0fc87f311de36e8b0566898d44951ff0">llvm::RISCVAttributeParser::RISCVAttributeParser</a> and <a href="#a8125ecaffe4cb18a746e29ec30bc74c5">stringAttribute</a>.</p>

</div>
</div>

### tagToStringMap {#afa3c8aaff4a817ff6c9aae5df0bbe584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagNameMap llvm::ELFAttributeParser::tagToStringMap</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>


<p>Referenced by <a href="#a4e104d3bf9f32e68ed3dacf1c6092931">ELFAttributeParser</a>, <a href="#a5f1ba395da37cb67d8b53f8cc704fc56">ELFAttributeParser</a>, <a href="#a3e050c88f97b0583ca8a9ccb9df7f9af">integerAttribute</a>, <a href="#adf641c6eb9421f15fc9015e7032b71fb">printAttribute</a> and <a href="#a8125ecaffe4cb18a746e29ec30bc74c5">stringAttribute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### attributes {#ae7909c56988c2bcaf961eed5a16ce2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;unsigned, unsigned&gt; llvm::ELFAttributeParser::attributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>

</div>
</div>

### attributesStr {#a0a02897cf2eb33f72a52cc7cc078c4e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;unsigned, StringRef&gt; llvm::ELFAttributeParser::attributesStr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>

</div>
</div>

### vendor {#ab22f72d456dc53c91ba29ab365a4bb62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ELFAttributeParser::vendor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/elfattributeparser-h">ELFAttributeParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/elfattributeparser-cpp">ELFAttributeParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
