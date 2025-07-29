---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-31f56d02e9ae3cab7c6017d1111afe46
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MappingTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;std::unique_ptr&lt; XCOFFYAML::AuxSymbolEnt &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">llvm/ObjectYAML/XCOFFYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d56e0cfd3aa559dd8e7255488e3c31">mapping</a> (IO &amp;IO, std::unique_ptr&lt; XCOFFYAML::AuxSymbolEnt &gt; &amp;AuxSym)</td>
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


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#ac0d56e0cfd3aa559dd8e7255488e3c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; std::unique_ptr&lt; XCOFFYAML::AuxSymbolEnt &gt; &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/xcoffyaml/auxsymbolent">XCOFFYAML::AuxSymbolEnt</a> &gt; &amp; AuxSym)</td>
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



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/xcoffyaml-h">XCOFFYAML.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/xcoffyaml-cpp">XCOFFYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/xcoffyaml/#aa1f52c7eab3a1cc132fe21a2941d8545a13b13d0dc53232d68abb185beb51969d">llvm::XCOFFYAML::AUX_CSECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoffyaml/#aa1f52c7eab3a1cc132fe21a2941d8545a3386dcfc40a741e9823f53503c8ba204">llvm::XCOFFYAML::AUX_EXCEPT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoffyaml/#aa1f52c7eab3a1cc132fe21a2941d8545acf7645443d7aaaf821151307352dd140">llvm::XCOFFYAML::AUX_FCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoffyaml/#aa1f52c7eab3a1cc132fe21a2941d8545aa0083a8914b59f559d057f1f9bd6128e">llvm::XCOFFYAML::AUX_FILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoffyaml/#aa1f52c7eab3a1cc132fe21a2941d8545a2fbea89ced04d25e1569c11f894f52fb">llvm::XCOFFYAML::AUX_SECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoffyaml/#aa1f52c7eab3a1cc132fe21a2941d8545af06e4783cc144e2f5694c3de7dbbea2c">llvm::XCOFFYAML::AUX_STAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoffyaml/#aa1f52c7eab3a1cc132fe21a2941d8545a1c3dd265ba61752999ab77dc401d15f7">llvm::XCOFFYAML::AUX_SYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aded39f8b0259eaa22d99db5f4fe31917">llvm::yaml::auxSymMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a9602206972cc02cc749acfca45487271">llvm::yaml::IO::getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoffyaml/object/#ab0a58d2250d59123dd5ea7908249b0ac">llvm::XCOFFYAML::Object::Header</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoffyaml/fileheader/#a3012c667ad2ef7c821fbc77243db765c">llvm::XCOFFYAML::FileHeader::Magic</a>, <a href="#ac0d56e0cfd3aa559dd8e7255488e3c31">mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a3f9abe4cc7cc808cb6025ed882bcbb7d">llvm::yaml::IO::outputting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aeb803606db5e73c05a10f7f4e6982830">llvm::yaml::ResetAuxSym</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a930906994b5dc96a35696936fe705c15">llvm::yaml::IO::setError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#aee8f7e420a81c0a58e0febda6902a6f6aaf686a3cf0f7adb2f4f0f3b1c01e0d8a">llvm::XCOFF::XCOFF64</a>.</p>


<p>Referenced by <a href="#ac0d56e0cfd3aa559dd8e7255488e3c31">mapping</a>.</p>

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
