---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/coffyaml/symbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Symbol` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::COFFYAML::Symbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">llvm/ObjectYAML/COFFYAML.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2420d8dc1859c4eaf6bd33192a371d60">Symbol</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coff/symbol">COFF::symbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35bd85cfc78930e17ef056502f395dc">Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae70d6ec501d52a8d624abd6e944a94f2">COFF::SymbolBaseType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee57ee55d505ec20c4631bc4b3cbbbc8">SimpleType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae70d6ec501d52a8d624abd6e944a94f2a42fd3c0cc883414b77e63cdf35ac9929">COFF::IMAGE_SYM_TYPE_NULL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120">COFF::SymbolComplexType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66535c65f9f53b0fa000ed504c4c9859">ComplexType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120a33430600d344c962f55f3c48635d0e3d">COFF::IMAGE_SYM_DTYPE_NULL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/coff/auxiliaryfunctiondefinition">COFF::AuxiliaryFunctionDefinition</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2eda34e819af47f44115fd35648403c">FunctionDefinition</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/coff/auxiliarybfandefsymbol">COFF::AuxiliarybfAndefSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491d282975bbef7f421aece3f0950513">bfAndefSymbol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/coff/auxiliaryweakexternal">COFF::AuxiliaryWeakExternal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7aada19a5e4c32457015dc03c317f0">WeakExternal</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e40803220820fbbf40041ed0bcd071d">File</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/coff/auxiliarysectiondefinition">COFF::AuxiliarySectionDefinition</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71646e47dac64f5fb9fdf4a4a49fe581">SectionDefinition</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/coff/auxiliaryclrtoken">COFF::AuxiliaryCLRToken</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa0c2f283643549b5297c91bec22214e">CLRToken</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1682b575ce647d6ac43c6bfb864aa290">Name</a></td>
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


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Symbol() {#a2420d8dc1859c4eaf6bd33192a371d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::COFFYAML::Symbol::Symbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffyaml-cpp">COFFYAML.cpp</a>.</p>


<p>Reference <a href="#ad35bd85cfc78930e17ef056502f395dc">Header</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### bfAndefSymbol {#a491d282975bbef7f421aece3f0950513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;COFF::AuxiliarybfAndefSymbol&gt; llvm::COFFYAML::Symbol::bfAndefSymbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>.</p>

</div>
</div>

### CLRToken {#afa0c2f283643549b5297c91bec22214e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;COFF::AuxiliaryCLRToken&gt; llvm::COFFYAML::Symbol::CLRToken</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>.</p>

</div>
</div>

### ComplexType {#a66535c65f9f53b0fa000ed504c4c9859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFF::SymbolComplexType llvm::COFFYAML::Symbol::ComplexType = <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120a33430600d344c962f55f3c48635d0e3d">COFF::IMAGE_SYM_DTYPE_NULL</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a> and <a href="/web-llvm/docs/api/structs/anonymous-coffemitter-cpp-/coffparser/#aa379fd1a67e18fc3082a611e349a8ac5">anonymous{COFFEmitter.cpp}::COFFParser::parseSymbols</a>.</p>

</div>
</div>

### File {#a4e40803220820fbbf40041ed0bcd071d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::COFFYAML::Symbol::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>.</p>

</div>
</div>

### FunctionDefinition {#ac2eda34e819af47f44115fd35648403c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;COFF::AuxiliaryFunctionDefinition&gt; llvm::COFFYAML::Symbol::FunctionDefinition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>.</p>

</div>
</div>

### Header {#ad35bd85cfc78930e17ef056502f395dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFF::symbol llvm::COFFYAML::Symbol::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/anonymous-coffemitter-cpp-/coffparser/#aa379fd1a67e18fc3082a611e349a8ac5">anonymous{COFFEmitter.cpp}::COFFParser::parseSymbols</a>, <a href="#a2420d8dc1859c4eaf6bd33192a371d60">Symbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>.</p>

</div>
</div>

### Name {#a1682b575ce647d6ac43c6bfb864aa290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::COFFYAML::Symbol::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/anonymous-coffemitter-cpp-/coffparser/#aa379fd1a67e18fc3082a611e349a8ac5">anonymous{COFFEmitter.cpp}::COFFParser::parseSymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>.</p>

</div>
</div>

### SectionDefinition {#a71646e47dac64f5fb9fdf4a4a49fe581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;COFF::AuxiliarySectionDefinition&gt; llvm::COFFYAML::Symbol::SectionDefinition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>.</p>

</div>
</div>

### SimpleType {#aee57ee55d505ec20c4631bc4b3cbbbc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFF::SymbolBaseType llvm::COFFYAML::Symbol::SimpleType = <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ae70d6ec501d52a8d624abd6e944a94f2a42fd3c0cc883414b77e63cdf35ac9929">COFF::IMAGE_SYM_TYPE_NULL</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a> and <a href="/web-llvm/docs/api/structs/anonymous-coffemitter-cpp-/coffparser/#aa379fd1a67e18fc3082a611e349a8ac5">anonymous{COFFEmitter.cpp}::COFFParser::parseSymbols</a>.</p>

</div>
</div>

### WeakExternal {#a0c7aada19a5e4c32457015dc03c317f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;COFF::AuxiliaryWeakExternal&gt; llvm::COFFYAML::Symbol::WeakExternal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffyaml-cpp">COFFYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
