---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-90fa4b4bf1f65b5e4684b9a1c116c7f5
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MappingTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;ArchYAML::Archive::Child&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/archiveyaml-h">llvm/ObjectYAML/ArchiveYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97458d286b2cbcb3fdfaab5b757f23c4">mapping</a> (IO &amp;IO, ArchYAML::Archive::Child &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb17ab0e84d95cfa91b473a5ca86323">validate</a> (IO &amp;, ArchYAML::Archive::Child &amp;C)</td>
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


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/archiveyaml-h">ArchiveYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#a97458d286b2cbcb3fdfaab5b757f23c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; ArchYAML::Archive::Child &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; IO, <a href="/web-llvm/docs/api/structs/llvm/archyaml/archive/child">ArchYAML::Archive::Child</a> &amp; C)</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/archiveyaml-h">ArchiveYAML.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/archiveyaml-cpp">ArchiveYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a9602206972cc02cc749acfca45487271">llvm::yaml::IO::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### validate() {#acbb17ab0e84d95cfa91b473a5ca86323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::yaml::MappingTraits&lt; ArchYAML::Archive::Child &gt;::validate (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/archyaml/archive/child">ArchYAML::Archive::Child</a> &amp; C)</td>
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



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/archiveyaml-h">ArchiveYAML.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/archiveyaml-cpp">ArchiveYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/archiveyaml-h">ArchiveYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/archiveyaml-cpp">ArchiveYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
