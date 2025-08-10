---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/machobuilder/section
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Section` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::MachOBuilder::Section { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">llvm/ExecutionEngine/Orc/MachOBuilder.h</a>"
</div>

## Base structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MachOTraits::Section</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget">RelocTarget</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa23e563fc1b4cb6192ce8ea87e0154df">Section</a> (MachOBuilder &amp;Builder, StringRef SecName, StringRef SegName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget">RelocTarget</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc7b92885232560e16403a8902bd5814">addSymbol</a> (int32_t Offset, StringRef Name, uint8_t Type, uint16_t Desc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0016a9824659b3dbac689af3327cdbd1">addReloc</a> (int32_t Offset, RelocTarget Target, bool PCRel, unsigned Length, unsigned Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">auto &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3351cc1094b40204b708cbc5b255ee27">rawStruct</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder">MachOBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd9cb34ffcfc79afdf91502fe41bee4">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/sectioncontent">SectionContent</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d67b829b44bc9ccd1d5855a105a146">Content</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe3483efada19b316f5343333419f03">SectionNumber</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">SymbolContainer</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01aa0c31e7114849e4160b9934dcd1ec">SC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/reloc">Reloc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20026fc040d73bc606adba08a070e2fc">Relocs</a></td>
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


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Section() {#aa23e563fc1b4cb6192ce8ea87e0154df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Section (<a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder">MachOBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SegName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afbd9cb34ffcfc79afdf91502fe41bee4">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/#acf9640c61b9402f751474184c88ac75e">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::MachOBuilder</a>, <a href="#a3351cc1094b40204b708cbc5b255ee27">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::rawStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget/#abf645ac73ddd0dd0cebef818b89da277">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::RelocTarget</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addReloc() {#a0016a9824659b3dbac689af3327cdbd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::addReloc (int32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget">RelocTarget</a> Target, bool PCRel, unsigned Length, unsigned Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a20026fc040d73bc606adba08a070e2fc">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Relocs</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget/#abf645ac73ddd0dd0cebef818b89da277">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::RelocTarget</a>.</p>

</div>
</div>

### addSymbol() {#adc7b92885232560e16403a8902bd5814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RelocTarget llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::addSymbol (int32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint8_t Type, uint16_t Desc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="#afbd9cb34ffcfc79afdf91502fe41bee4">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#aaca65700aad8ca31abbb94cbb03227eda149563e67229adecb388a1b15854f767">llvm::MachO::N_SECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3fe4514c83ad4544e3e72db2d9fc33a4a840723dd9839c1d65c8728aa31ee6b08">llvm::MachO::NO_SECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget/#abf645ac73ddd0dd0cebef818b89da277">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::RelocTarget</a> and <a href="#a01aa0c31e7114849e4160b9934dcd1ec">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::SC</a>.</p>

</div>
</div>

### rawStruct() {#a3351cc1094b40204b708cbc5b255ee27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto &amp; llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::rawStruct ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#aa23e563fc1b4cb6192ce8ea87e0154df">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Section</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Builder {#afbd9cb34ffcfc79afdf91502fe41bee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOBuilder&amp; llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#adc7b92885232560e16403a8902bd5814">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::addSymbol</a> and <a href="#aa23e563fc1b4cb6192ce8ea87e0154df">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Section</a>.</p>

</div>
</div>

### Content {#a41d67b829b44bc9ccd1d5855a105a146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionContent llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Content</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>

</div>
</div>

### Relocs {#a20026fc040d73bc606adba08a070e2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Reloc&gt; llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Relocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#a0016a9824659b3dbac689af3327cdbd1">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::addReloc</a>.</p>

</div>
</div>

### SC {#a01aa0c31e7114849e4160b9934dcd1ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolContainer llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::SC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#adc7b92885232560e16403a8902bd5814">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::addSymbol</a>.</p>

</div>
</div>

### SectionNumber {#a0fe3483efada19b316f5343333419f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::SectionNumber = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
