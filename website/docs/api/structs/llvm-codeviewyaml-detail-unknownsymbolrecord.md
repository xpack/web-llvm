---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `UnknownSymbolRecord` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CodeViewYAML::detail::UnknownSymbolRecord { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordbase">SymbolRecordBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c0fc91d2c7b8e0b2101e7cc04341275">UnknownSymbolRecord</a> (codeview::SymbolKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706f3a14442a38ad2ae15efa1aaaa3b8">map</a> (yaml::IO &amp;io) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae627646dd2634baf0552725fc07be047">toCodeViewSymbol</a> (BumpPtrAllocator &amp;Allocator, CodeViewContainer Container) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ab345d5cce9e08d1319607834b711f">fromCodeViewSymbol</a> (CVSymbol CVS) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3969d5f4a55f0e3a750f74f731ba63">Data</a></td>
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


<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UnknownSymbolRecord() {#a7c0fc91d2c7b8e0b2101e7cc04341275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeViewYAML::detail::UnknownSymbolRecord::UnknownSymbolRecord (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">codeview::SymbolKind</a> K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordbase/#a072bf2ce5285b17d28580f5e2b6b626f">llvm::CodeViewYAML::detail::SymbolRecordBase::SymbolRecordBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fromCodeViewSymbol() {#a20ab345d5cce9e08d1319607834b711f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeViewYAML::detail::UnknownSymbolRecord::fromCodeViewSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> CVS)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="#a0c3969d5f4a55f0e3a750f74f731ba63">Data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordbase/#a4bd1ca0cbc1691c30e45c6d60ef3dd8f">llvm::CodeViewYAML::detail::SymbolRecordBase::Kind</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#aaeef9f2a2d0dc09ec00ec9b38242c706">llvm::codeview::CVRecord&lt; Kind &gt;::kind</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#abf24508852ac431412daa99def7d29ae">llvm::codeview::CVRecord&lt; Kind &gt;::RecordData</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### map() {#a706f3a14442a38ad2ae15efa1aaaa3b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeViewYAML::detail::UnknownSymbolRecord::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">yaml::IO</a> &amp; io)</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="#a0c3969d5f4a55f0e3a750f74f731ba63">Data</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a3f9abe4cc7cc808cb6025ed882bcbb7d">llvm::yaml::IO::outputting</a>.</p>

</div>
</div>

### toCodeViewSymbol() {#ae627646dd2634baf0552725fc07be047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVSymbol llvm::CodeViewYAML::detail::UnknownSymbolRecord::toCodeViewSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">CodeViewContainer</a> Container)</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="#a0c3969d5f4a55f0e3a750f74f731ba63">Data</a> and <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordbase/#a4bd1ca0cbc1691c30e45c6d60ef3dd8f">llvm::CodeViewYAML::detail::SymbolRecordBase::Kind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Data {#a0c3969d5f4a55f0e3a750f74f731ba63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint8_t&gt; llvm::CodeViewYAML::detail::UnknownSymbolRecord::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>Referenced by <a href="#a20ab345d5cce9e08d1319607834b711f">fromCodeViewSymbol</a>, <a href="#a706f3a14442a38ad2ae15efa1aaaa3b8">map</a> and <a href="#ae627646dd2634baf0552725fc07be047">toCodeViewSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
