---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalartraits-a4f0c68a7a5b628e681fe71e26204a68
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ScalarTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::ScalarTraits&lt;uuid_t&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">llvm/ObjectYAML/MachOYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8da63936a6b179c9ae510cc242773e">output</a> (const uuid_t &amp;Val, void *, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa184c37a136841d78c514c29e5e1f42b">input</a> (StringRef Scalar, void *, uuid_t &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757">QuotingType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a497bcb1254d71ae3dc4f160141d4a5f2">mustQuote</a> (StringRef S)</td>
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


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### input() {#aa184c37a136841d78c514c29e5e1f42b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::ScalarTraits&lt; uuid_t &gt;::input (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Scalar, void *, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a0b852a813738256442248c54c81b163d">uuid_t</a> &amp; Val)</td>
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



<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoyaml-cpp">MachOYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aceda0d316aed2b818b731917d21b88bc">llvm::getAsUnsignedInteger</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a388c981224806a01d8de4172d5322d3daf60357a8d17e45793298323f1b372a74">llvm::yaml::Scalar</a>.</p>

</div>
</div>

### mustQuote() {#a497bcb1254d71ae3dc4f160141d4a5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QuotingType llvm::yaml::ScalarTraits&lt; uuid_t &gt;::mustQuote (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoyaml-cpp">MachOYAML.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a92b68a49e0ce87d4d52c24f060af0502">llvm::yaml::needsQuotes</a>.</p>

</div>
</div>

### output() {#a4e8da63936a6b179c9ae510cc242773e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::ScalarTraits&lt; uuid_t &gt;::output (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a0b852a813738256442248c54c81b163d">uuid_t</a> &amp; Val, void *, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoyaml-cpp">MachOYAML.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a4e6042cae3a8ab74080998736eabd3fa">llvm::raw_ostream::write_uuid</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/machoyaml-h">MachOYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoyaml-cpp">MachOYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
