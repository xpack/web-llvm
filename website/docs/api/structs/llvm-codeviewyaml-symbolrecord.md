---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codeviewyaml/symbolrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SymbolRecord` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CodeViewYAML::SymbolRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamlsymbols-h">llvm/ObjectYAML/CodeViewYAMLSymbols.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">codeview::CVSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a42428c7b61b45d15ce9223a1c466c">toCodeViewSymbol</a> (BumpPtrAllocator &amp;Allocator, codeview::CodeViewContainer Container) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordbase">detail::SymbolRecordBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698a492ea07c641f685ac6f3700891d9">Symbol</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/symbolrecord">SymbolRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923d8bc53463d8d83d4f78e94d9115dc">fromCodeViewSymbol</a> (codeview::CVSymbol Symbol)</td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamlsymbols-h">CodeViewYAMLSymbols.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### toCodeViewSymbol() {#a31a42428c7b61b45d15ce9223a1c466c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CVSymbol CodeViewYAML::SymbolRecord::toCodeViewSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">codeview::CodeViewContainer</a> Container)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamlsymbols-h">CodeViewYAMLSymbols.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>Reference <a href="#a698a492ea07c641f685ac6f3700891d9">Symbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Symbol {#a698a492ea07c641f685ac6f3700891d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;detail::SymbolRecordBase&gt; llvm::CodeViewYAML::SymbolRecord::Symbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamlsymbols-h">CodeViewYAMLSymbols.h</a>.</p>


<p>Referenced by <a href="#a923d8bc53463d8d83d4f78e94d9115dc">fromCodeViewSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp/#a40f025c89c1dd1b8036e86f07018de8d">mapSymbolRecordImpl</a> and <a href="#a31a42428c7b61b45d15ce9223a1c466c">toCodeViewSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromCodeViewSymbol() {#a923d8bc53463d8d83d4f78e94d9115dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CodeViewYAML::SymbolRecord &gt; CodeViewYAML::SymbolRecord::fromCodeViewSymbol (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">codeview::CVSymbol</a> Symbol)</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamlsymbols-h">CodeViewYAMLSymbols.h</a>, definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0e494c491fad71e29cc10efce7c59f6ca7e4105e7f11aef8db54945155c4b3907">llvm::codeview::corrupt_record</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp/#aec5a44cc552a3197f37eef0f35afae51">fromCodeViewSymbolImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="#a698a492ea07c641f685ac6f3700891d9">Symbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlsymbolssubsection/#a3e9bc9ee10900fa54b28a92efd48103e">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLSymbolsSubsection::fromCodeViewSubsection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/codeviewyamlsymbols-h">CodeViewYAMLSymbols.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp">CodeViewYAMLSymbols.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
