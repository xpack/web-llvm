---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalarbitsettraits-5fd0c59f5fca4e85d5ae4ba594ef2b3d
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ScalarBitSetTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::ScalarBitSetTraits&lt;XCOFF::SectionTypeFlags&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">llvm/ObjectYAML/XCOFFYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3528958420101c3f811341af85a9cdb0">bitset</a> (IO &amp;IO, XCOFF::SectionTypeFlags &amp;Value)</td>
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


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### bitset() {#a3528958420101c3f811341af85a9cdb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::ScalarBitSetTraits&lt; XCOFF::SectionTypeFlags &gt;::bitset (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389ae">XCOFF::SectionTypeFlags</a> &amp; Value)</td>
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



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/xcoffyaml-cpp">XCOFFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/wasm-cpp/#a8c36a148929ce5ee501d6c5e99ed059b">ECase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeacb24e90dcfcba01d1c251bcf8b399ef2">llvm::XCOFF::STYP_BSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1e3f056d2214669889fba21e3d949ca3">llvm::XCOFF::STYP_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea91ad18218d1a31d6e08723d07b3df9ba">llvm::XCOFF::STYP_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1dddb836146cb79d721a0eb775a670ab">llvm::XCOFF::STYP_DWARF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeabda15739c5c07c0ac38280faaa4a2306">llvm::XCOFF::STYP_EXCEPT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea1f498f3fbb898ea8e37f18e59cf23e39">llvm::XCOFF::STYP_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea18317b81fd433739e8c447d1b1b93d32">llvm::XCOFF::STYP_LOADER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeac5d245ccdee6f92a2b232f49c0b4c41e">llvm::XCOFF::STYP_OVRFLO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeaad2dde9fb3e75239c7e4da9337eecd9d">llvm::XCOFF::STYP_PAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aeadcf57b5531bdb50652a3604cf820b71d">llvm::XCOFF::STYP_TBSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea233a82ca0336e9be851e053af95ecb5d">llvm::XCOFF::STYP_TDATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea625db7b5bb9b798cf7c4eac884e7722b">llvm::XCOFF::STYP_TEXT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#af30dc250fcc756ed99640fe2d10389aea096fc439e418e4b17ce41780ff4a9f8d">llvm::XCOFF::STYP_TYPCHK</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
