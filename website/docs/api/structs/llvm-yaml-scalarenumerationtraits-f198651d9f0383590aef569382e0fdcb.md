---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalarenumerationtraits-f198651d9f0383590aef569382e0fdcb
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ScalarEnumerationTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::ScalarEnumerationTraits&lt;XCOFF::DwarfSectionSubtypeFlags&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">llvm/ObjectYAML/XCOFFYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4da318299c6766c9c7f2ee6210228361">enumeration</a> (IO &amp;IO, XCOFF::DwarfSectionSubtypeFlags &amp;Value)</td>
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


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### enumeration() {#a4da318299c6766c9c7f2ee6210228361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::DwarfSectionSubtypeFlags &gt;::enumeration (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440">XCOFF::DwarfSectionSubtypeFlags</a> &amp; Value)</td>
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



<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/xcoffyaml-cpp">XCOFFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/wasm-cpp/#a8c36a148929ce5ee501d6c5e99ed059b">ECase</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#ac656ce8032e2f91b5320566fde65dba1">llvm::yaml::IO::enumFallback</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440a4667e9175300d42a5f7d9c7a8a623c92">llvm::XCOFF::SSUBTYP_DWABREV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440a04b13a24683ab33744016c4b39db2185">llvm::XCOFF::SSUBTYP_DWARNGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440a328a22a45a49b076716cd9208117a05f">llvm::XCOFF::SSUBTYP_DWFRAME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440a5bac5756c6b8d0af4e27cd2d046f9cc4">llvm::XCOFF::SSUBTYP_DWINFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440aec17bb51c8254d5d916947eaadff0743">llvm::XCOFF::SSUBTYP_DWLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440a706b772496f4db5525d2c9f639ec85b1">llvm::XCOFF::SSUBTYP_DWLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440a74e95ef0ee0aab9964cecdec25379f9c">llvm::XCOFF::SSUBTYP_DWMAC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440ac95bd855f756dbe9bdf775161dd8e42f">llvm::XCOFF::SSUBTYP_DWPBNMS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440ad63489b6370030fcce1380b8d0d615b5">llvm::XCOFF::SSUBTYP_DWPBTYP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440a60ff01ad45b24bdb9abdd7a8bdade24d">llvm::XCOFF::SSUBTYP_DWRNGES</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440afb84ff02c888aaa98ea208005ff3ffdd">llvm::XCOFF::SSUBTYP_DWSTR</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/xcoffyaml-cpp">XCOFFYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
