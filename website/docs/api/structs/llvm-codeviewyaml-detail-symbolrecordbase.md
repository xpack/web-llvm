---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeviewyaml/detail/symbolrecordbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SymbolRecordBase` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CodeViewYAML::detail::SymbolRecordBase { ... }
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordimpl">SymbolRecordImpl&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord">UnknownSymbolRecord</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072bf2ce5285b17d28580f5e2b6b626f">SymbolRecordBase</a> (codeview::SymbolKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a865852ecbf71d8f7ea0115d6fd049531">~SymbolRecordBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4d482d62eb5b5f3221274457327649">map</a> (yaml::IO &amp;io)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">codeview::CVSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7491e46ce93cd3be1141ffe8e2504774">toCodeViewSymbol</a> (BumpPtrAllocator &amp;Allocator, CodeViewContainer Container) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7970c0baab2d2afb1fdebf52a167e5c">fromCodeViewSymbol</a> (codeview::CVSymbol Type)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">codeview::SymbolKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd1ca0cbc1691c30e45c6d60ef3dd8f">Kind</a></td>
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


<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SymbolRecordBase() {#a072bf2ce5285b17d28580f5e2b6b626f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeViewYAML::detail::SymbolRecordBase::SymbolRecordBase (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">codeview::SymbolKind</a> K)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>Reference <a href="#a4bd1ca0cbc1691c30e45c6d60ef3dd8f">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordimpl/#aadbb3d901f554d3ee2facf47df6789ed">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::SymbolRecordImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#a7c0fc91d2c7b8e0b2101e7cc04341275">llvm::CodeViewYAML::detail::UnknownSymbolRecord::UnknownSymbolRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SymbolRecordBase() {#a865852ecbf71d8f7ea0115d6fd049531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::CodeViewYAML::detail::SymbolRecordBase::~SymbolRecordBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fromCodeViewSymbol() {#ab7970c0baab2d2afb1fdebf52a167e5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::CodeViewYAML::detail::SymbolRecordBase::fromCodeViewSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">codeview::CVSymbol</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>

</div>
</div>

### map() {#a6f4d482d62eb5b5f3221274457327649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::CodeViewYAML::detail::SymbolRecordBase::map (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">yaml::IO</a> &amp; io)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>

</div>
</div>

### toCodeViewSymbol() {#a7491e46ce93cd3be1141ffe8e2504774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual codeview::CVSymbol llvm::CodeViewYAML::detail::SymbolRecordBase::toCodeViewSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">CodeViewContainer</a> Container)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Kind {#a4bd1ca0cbc1691c30e45c6d60ef3dd8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::SymbolKind llvm::CodeViewYAML::detail::SymbolRecordBase::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#a20ab345d5cce9e08d1319607834b711f">llvm::CodeViewYAML::detail::UnknownSymbolRecord::fromCodeViewSymbol</a>, <a href="#a072bf2ce5285b17d28580f5e2b6b626f">SymbolRecordBase</a> and <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#ae627646dd2634baf0552725fc07be047">llvm::CodeViewYAML::detail::UnknownSymbolRecord::toCodeViewSymbol</a>.</p>

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
