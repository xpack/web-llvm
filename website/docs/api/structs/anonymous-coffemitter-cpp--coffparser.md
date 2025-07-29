---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-coffemitter-cpp-/coffparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `COFFParser` Struct

<p>This parses a yaml stream that represents a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{COFFEmitter.cpp}::COFFParser { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c03850084975b16adb3381ee2d7b30">COFFParser</a> (COFFYAML::Object &amp;Obj, yaml::ErrorHandler EH)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77314708bdfa7a97beb09c47b038a9e1">useBigObj</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a760164ca4dd1bd32ab7b7ebc04d784f3">isPE</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3083f55e42962a3360aa4aff794273bc">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52fda6ad7f5df9a493bbf6fc410780ca">getFileAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768970a3bbf63801291353e6cfae9433">getHeaderSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8444daa4c8d2fab90849d933893d680c">getSymbolSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a147dc0a9d4884bcb75d94bafe67ae2">parseSections</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa379fd1a67e18fc3082a611e349a8ac5">parseSymbols</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27df255cc4f44a4daababb7b85029583">parse</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995465ddb5a1db493f8cb35bc6b7cce0">getStringIndex</a> (StringRef Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coffyaml/object">COFFYAML::Object</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae80855da891a730eb61b12982682c225">Obj</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/stringsandchecksums">codeview::StringsAndChecksums</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bdda7520b68820b08c5bbbabf61da93">StringsAndChecksums</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507439204b36938e44658c72eb7ce275">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44aecc3a2c2be80e3dd56a7c29b79bbb">StringTableMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a70d89713d2fd57d245cee63955e7f9">StringTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7b94dc2918e409aa55c7ec75108a6e">SectionTableStart</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64af902a801d77825c1c630ca6e82b8">SectionTableSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4f9dfab3b02d41c6e26e306c90eab66b">yaml::ErrorHandler</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f51e4bc546d58a4c33556ab0cfdc45e">ErrHandler</a></td>
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

## Description {#details}

<p>This parses a yaml stream that represents a <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> object file.</p>


<p>See docs/yaml2obj for the yaml scheema.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### COFFParser() {#af0c03850084975b16adb3381ee2d7b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{COFFEmitter.cpp}::COFFParser::COFFParser (<a href="/web-llvm/docs/api/structs/llvm/coffyaml/object">COFFYAML::Object</a> &amp; Obj, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4f9dfab3b02d41c6e26e306c90eab66b">yaml::ErrorHandler</a> EH)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="#a3f51e4bc546d58a4c33556ab0cfdc45e">ErrHandler</a>, <a href="#ae80855da891a730eb61b12982682c225">Obj</a>, <a href="#aa64af902a801d77825c1c630ca6e82b8">SectionTableSize</a>, <a href="#aca7b94dc2918e409aa55c7ec75108a6e">SectionTableStart</a> and <a href="#a3a70d89713d2fd57d245cee63955e7f9">StringTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFileAlignment() {#a52fda6ad7f5df9a493bbf6fc410780ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{COFFEmitter.cpp}::COFFParser::getFileAlignment ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Reference <a href="#ae80855da891a730eb61b12982682c225">Obj</a>.</p>

</div>
</div>

### getHeaderSize() {#a768970a3bbf63801291353e6cfae9433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{COFFEmitter.cpp}::COFFParser::getHeaderSize ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda9caa383c393442d03c183f9f59d15d84">llvm::COFF::Header16Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bdab3eacd7d91695370d192e268933c9eb7">llvm::COFF::Header32Size</a> and <a href="#a77314708bdfa7a97beb09c47b038a9e1">useBigObj</a>.</p>

</div>
</div>

### getStringIndex() {#a995465ddb5a1db493f8cb35bc6b7cce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{COFFEmitter.cpp}::COFFParser::getStringIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="#a3a70d89713d2fd57d245cee63955e7f9">StringTable</a> and <a href="#a44aecc3a2c2be80e3dd56a7c29b79bbb">StringTableMap</a>.</p>

</div>
</div>

### getSymbolSize() {#a8444daa4c8d2fab90849d933893d680c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{COFFEmitter.cpp}::COFFParser::getSymbolSize ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda9f43dd1c5232bf4075ec3837633e1a64">llvm::COFF::Symbol16Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bdae80f6675b239298e2a8e462cb7ca69dc">llvm::COFF::Symbol32Size</a> and <a href="#a77314708bdfa7a97beb09c47b038a9e1">useBigObj</a>.</p>

</div>
</div>

### is64Bit() {#a3083f55e42962a3360aa4aff794273bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFEmitter.cpp}::COFFParser::is64Bit ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acb6f88f4307d83ce7c625a0775f2b512">llvm::COFF::is64Bit</a> and <a href="#ae80855da891a730eb61b12982682c225">Obj</a>.</p>

</div>
</div>

### isPE() {#a760164ca4dd1bd32ab7b7ebc04d784f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFEmitter.cpp}::COFFParser::isPE ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Reference <a href="#ae80855da891a730eb61b12982682c225">Obj</a>.</p>

</div>
</div>

### parse() {#a27df255cc4f44a4daababb7b85029583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFEmitter.cpp}::COFFParser::parse ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="#a5a147dc0a9d4884bcb75d94bafe67ae2">parseSections</a> and <a href="#aa379fd1a67e18fc3082a611e349a8ac5">parseSymbols</a>.</p>

</div>
</div>

### parseSections() {#a5a147dc0a9d4884bcb75d94bafe67ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFEmitter.cpp}::COFFParser::parseSections ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#a59361b5a8461d9ef678b909873feea56">llvm::COFFYAML::Section::Alignment</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ad54307f6fcaef777aaf18ac13b93b7d4">llvm::COFF::section::Characteristics</a>, <a href="#a3f51e4bc546d58a4c33556ab0cfdc45e">ErrHandler</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvelement-cpp/#a0a0a5465a81f37e6f33be77ca0cc85e4">getStringIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#ad6a2da5a048669e81507f249863c4232">llvm::COFFYAML::Section::Header</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/section/#ae3f859e92e664e6b19ce1d65c3d4577e">llvm::COFF::section::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/section/#a9153b22f78d286f54bf7c7510841d891">llvm::COFFYAML::Section::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda084ca1f72ecd10e22d3d8867548e0f61">llvm::COFF::NameSize</a> and <a href="#ae80855da891a730eb61b12982682c225">Obj</a>.</p>


<p>Referenced by <a href="#a27df255cc4f44a4daababb7b85029583">parse</a>.</p>

</div>
</div>

### parseSymbols() {#aa379fd1a67e18fc3082a611e349a8ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFEmitter.cpp}::COFFParser::parseSymbols ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/coffyaml/symbol/#a66535c65f9f53b0fa000ed504c4c9859">llvm::COFFYAML::Symbol::ComplexType</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvelement-cpp/#a0a0a5465a81f37e6f33be77ca0cc85e4">getStringIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/symbol/#ad35bd85cfc78930e17ef056502f395dc">llvm::COFFYAML::Symbol::Header</a>, <a href="/web-llvm/docs/api/structs/llvm/coff/symbol/#ac3ca53058710046654e7e970b2a0a58e">llvm::COFF::symbol::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/symbol/#a1682b575ce647d6ac43c6bfb864aa290">llvm::COFFYAML::Symbol::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a008162b24bc184867edc5c39bd3969bda084ca1f72ecd10e22d3d8867548e0f61">llvm::COFF::NameSize</a>, <a href="#ae80855da891a730eb61b12982682c225">Obj</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#afb00b34885d4708e35781d81eb6e6120af01942289377f5c52c8771699eea5144">llvm::COFF::SCT_COMPLEX_TYPE_SHIFT</a>, <a href="/web-llvm/docs/api/structs/llvm/coffyaml/symbol/#aee57ee55d505ec20c4631bc4b3cbbbc8">llvm::COFFYAML::Symbol::SimpleType</a> and <a href="/web-llvm/docs/api/structs/llvm/coff/symbol/#a6a549c6aaf5dbcb141c0b4ffe21556bd">llvm::COFF::symbol::Type</a>.</p>


<p>Referenced by <a href="#a27df255cc4f44a4daababb7b85029583">parse</a>.</p>

</div>
</div>

### useBigObj() {#a77314708bdfa7a97beb09c47b038a9e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{COFFEmitter.cpp}::COFFParser::useBigObj ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad3097c5eaf4198579c34562fd89a240e">llvm::COFF::MaxNumberOfSections16</a> and <a href="#ae80855da891a730eb61b12982682c225">Obj</a>.</p>


<p>Referenced by <a href="#a768970a3bbf63801291353e6cfae9433">getHeaderSize</a> and <a href="#a8444daa4c8d2fab90849d933893d680c">getSymbolSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Allocator {#a507439204b36938e44658c72eb7ce275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator anonymous{COFFEmitter.cpp}::COFFParser::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>

</div>
</div>

### ErrHandler {#a3f51e4bc546d58a4c33556ab0cfdc45e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::ErrorHandler anonymous{COFFEmitter.cpp}::COFFParser::ErrHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Referenced by <a href="#af0c03850084975b16adb3381ee2d7b30">COFFParser</a> and <a href="#a5a147dc0a9d4884bcb75d94bafe67ae2">parseSections</a>.</p>

</div>
</div>

### Obj {#ae80855da891a730eb61b12982682c225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFYAML::Object&amp; anonymous{COFFEmitter.cpp}::COFFParser::Obj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Referenced by <a href="#af0c03850084975b16adb3381ee2d7b30">COFFParser</a>, <a href="#a52fda6ad7f5df9a493bbf6fc410780ca">getFileAlignment</a>, <a href="#a3083f55e42962a3360aa4aff794273bc">is64Bit</a>, <a href="#a760164ca4dd1bd32ab7b7ebc04d784f3">isPE</a>, <a href="#a5a147dc0a9d4884bcb75d94bafe67ae2">parseSections</a>, <a href="#aa379fd1a67e18fc3082a611e349a8ac5">parseSymbols</a> and <a href="#a77314708bdfa7a97beb09c47b038a9e1">useBigObj</a>.</p>

</div>
</div>

### SectionTableSize {#aa64af902a801d77825c1c630ca6e82b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{COFFEmitter.cpp}::COFFParser::SectionTableSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Referenced by <a href="#af0c03850084975b16adb3381ee2d7b30">COFFParser</a>.</p>

</div>
</div>

### SectionTableStart {#aca7b94dc2918e409aa55c7ec75108a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{COFFEmitter.cpp}::COFFParser::SectionTableStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Referenced by <a href="#af0c03850084975b16adb3381ee2d7b30">COFFParser</a>.</p>

</div>
</div>

### StringsAndChecksums {#a0bdda7520b68820b08c5bbbabf61da93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::StringsAndChecksums anonymous{COFFEmitter.cpp}::COFFParser::StringsAndChecksums</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>

</div>
</div>

### StringTable {#a3a70d89713d2fd57d245cee63955e7f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{COFFEmitter.cpp}::COFFParser::StringTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Referenced by <a href="#af0c03850084975b16adb3381ee2d7b30">COFFParser</a> and <a href="#a995465ddb5a1db493f8cb35bc6b7cce0">getStringIndex</a>.</p>

</div>
</div>

### StringTableMap {#a44aecc3a2c2be80e3dd56a7c29b79bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; anonymous{COFFEmitter.cpp}::COFFParser::StringTableMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>Referenced by <a href="#a995465ddb5a1db493f8cb35bc6b7cce0">getStringIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
