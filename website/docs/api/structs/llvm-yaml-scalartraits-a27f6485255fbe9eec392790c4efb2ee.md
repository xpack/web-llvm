---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalartraits-a27f6485255fbe9eec392790c4efb2ee
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
struct llvm::yaml::ScalarTraits&lt;ELFYAML::YAMLFlowString&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b39254a1394efed347834baae72167">output</a> (const ELFYAML::YAMLFlowString &amp;Val, void *, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29230f70cb95a83a37749cc787412da4">input</a> (StringRef Scalar, void *, ELFYAML::YAMLFlowString &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afefcb4ff123497fa1f4e41b118941dd4">mustQuote</a> (StringRef S)</td>
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


<p>Definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### input() {#a29230f70cb95a83a37749cc787412da4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::ScalarTraits&lt; ELFYAML::YAMLFlowString &gt;::input (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Scalar, void *, ELFYAML::YAMLFlowString &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a388c981224806a01d8de4172d5322d3daf60357a8d17e45793298323f1b372a74">llvm::yaml::Scalar</a>.</p>

</div>
</div>

### mustQuote() {#afefcb4ff123497fa1f4e41b118941dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QuotingType llvm::yaml::ScalarTraits&lt; ELFYAML::YAMLFlowString &gt;::mustQuote (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1215 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>

</div>
</div>

### output() {#a74b39254a1394efed347834baae72167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::ScalarTraits&lt; ELFYAML::YAMLFlowString &gt;::output (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ELFYAML::YAMLFlowString &amp; Val, void *, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1206 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfyaml-cpp">ELFYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
