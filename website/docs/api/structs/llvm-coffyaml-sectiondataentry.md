---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/coffyaml/sectiondataentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SectionDataEntry` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::COFFYAML::SectionDataEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">llvm/ObjectYAML/COFFYAML.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af270eca07887b59b7e5ef37f71820aed">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94cbaff94af650d56d4f1379c1fbde36">writeAsBinary</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9644a742da4b7fe1eabe5073355fdae">UInt32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref">yaml::BinaryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeb88e88cf3e83a3396ba44bf82387fb">Binary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/coff-load-configuration32">object::coff_load_configuration32</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77217e95d24a497ba1367d6d4f200e49">LoadConfig32</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/coff-load-configuration64">object::coff_load_configuration64</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268e72a361dce35f03341a750a4b469a">LoadConfig64</a></td>
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


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### size() {#af270eca07887b59b7e5ef37f71820aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t COFFYAML::SectionDataEntry::size ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="#aeeb88e88cf3e83a3396ba44bf82387fb">Binary</a>, <a href="#a77217e95d24a497ba1367d6d4f200e49">LoadConfig32</a>, <a href="#a268e72a361dce35f03341a750a4b469a">LoadConfig64</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#ab9644a742da4b7fe1eabe5073355fdae">UInt32</a>.</p>

</div>
</div>

### writeAsBinary() {#a94cbaff94af650d56d4f1379c1fbde36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void COFFYAML::SectionDataEntry::writeAsBinary (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>, definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a>.</p>


<p>References <a href="#aeeb88e88cf3e83a3396ba44bf82387fb">Binary</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a67c3d5a0a2c5da7283eddf9e09f8290a">binary_le</a>, <a href="#a77217e95d24a497ba1367d6d4f200e49">LoadConfig32</a>, <a href="#a268e72a361dce35f03341a750a4b469a">LoadConfig64</a>, <a href="#ab9644a742da4b7fe1eabe5073355fdae">UInt32</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a749770911c6d0f9c6b687d28a5ea9d7d">writeLoadConfig</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Binary {#aeeb88e88cf3e83a3396ba44bf82387fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::BinaryRef llvm::COFFYAML::SectionDataEntry::Binary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="#af270eca07887b59b7e5ef37f71820aed">size</a> and <a href="#a94cbaff94af650d56d4f1379c1fbde36">writeAsBinary</a>.</p>

</div>
</div>

### LoadConfig32 {#a77217e95d24a497ba1367d6d4f200e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;object::coff_load_configuration32&gt; llvm::COFFYAML::SectionDataEntry::LoadConfig32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="#af270eca07887b59b7e5ef37f71820aed">size</a> and <a href="#a94cbaff94af650d56d4f1379c1fbde36">writeAsBinary</a>.</p>

</div>
</div>

### LoadConfig64 {#a268e72a361dce35f03341a750a4b469a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;object::coff_load_configuration64&gt; llvm::COFFYAML::SectionDataEntry::LoadConfig64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="#af270eca07887b59b7e5ef37f71820aed">size</a> and <a href="#a94cbaff94af650d56d4f1379c1fbde36">writeAsBinary</a>.</p>

</div>
</div>

### UInt32 {#ab9644a742da4b7fe1eabe5073355fdae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint32_t&gt; llvm::COFFYAML::SectionDataEntry::UInt32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a>.</p>


<p>Referenced by <a href="#af270eca07887b59b7e5ef37f71820aed">size</a> and <a href="#a94cbaff94af650d56d4f1379c1fbde36">writeAsBinary</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/coffyaml-h">COFFYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp">COFFEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
