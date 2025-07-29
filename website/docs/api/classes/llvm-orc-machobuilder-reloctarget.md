---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/machobuilder/reloctarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RelocTarget` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::MachOBuilder::RelocTarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">llvm/ExecutionEngine/Orc/MachOBuilder.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section">Section</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf645ac73ddd0dd0cebef818b89da277">RelocTarget</a> (const Section &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b59ff8add484951ac4094ad69d6709d">RelocTarget</a> (SymbolContainer &amp;SC, size_t Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07147061ac91ffa869c256cdaf3e9a32">isSymbol</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e378475fd2557292cf2f043b7e4f57">getSymbolNum</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc266911591108d10b703465380a68a4">getSectionId</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MachOTraits::NList &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b43edd789d692e5503f8b2a253f9c0">nlist</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section">Section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd268b6a1faa3eaab86b1c3c12d7c52f">S</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">SymbolContainer *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58e727cbd920b5bc10d5f5ffbd6991a">SC</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget">llvm::orc::MachOBuilder::RelocTarget</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0edc0062632d8b48784d74ce757151b"></a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc740cdc689fe684bbcebeab39fd17e">Idx</a></td>
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


<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RelocTarget() {#abf645ac73ddd0dd0cebef818b89da277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::RelocTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section">Section</a> &amp; S)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Reference <a href="#acd268b6a1faa3eaab86b1c3c12d7c52f">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::S</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section/#a0016a9824659b3dbac689af3327cdbd1">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::addReloc</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section/#adc7b92885232560e16403a8902bd5814">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::addSymbol</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section/#aa23e563fc1b4cb6192ce8ea87e0154df">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Section::Section</a>.</p>

</div>
</div>

### RelocTarget() {#a7b59ff8add484951ac4094ad69d6709d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::RelocTarget (SymbolContainer &amp; SC, size_t Idx)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Reference <a href="#aa58e727cbd920b5bc10d5f5ffbd6991a">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::SC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSectionId() {#afc266911591108d10b703465380a68a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::getSectionId ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a07147061ac91ffa869c256cdaf3e9a32">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::isSymbol</a> and <a href="#acd268b6a1faa3eaab86b1c3c12d7c52f">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::S</a>.</p>

</div>
</div>

### getSymbolNum() {#a75e378475fd2557292cf2f043b7e4f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::getSymbolNum ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a07147061ac91ffa869c256cdaf3e9a32">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::isSymbol</a> and <a href="#aa58e727cbd920b5bc10d5f5ffbd6991a">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::SC</a>.</p>

</div>
</div>

### isSymbol() {#a07147061ac91ffa869c256cdaf3e9a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::isSymbol ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#afc266911591108d10b703465380a68a4">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::getSectionId</a>, <a href="#a75e378475fd2557292cf2f043b7e4f57">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::getSymbolNum</a> and <a href="#a80b43edd789d692e5503f8b2a253f9c0">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::nlist</a>.</p>

</div>
</div>

### nlist() {#a80b43edd789d692e5503f8b2a253f9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOTraits::NList &amp; llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::nlist ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a07147061ac91ffa869c256cdaf3e9a32">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::isSymbol</a> and <a href="#aa58e727cbd920b5bc10d5f5ffbd6991a">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::SC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### S {#acd268b6a1faa3eaab86b1c3c12d7c52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Section* llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::S</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#afc266911591108d10b703465380a68a4">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::getSectionId</a> and <a href="#abf645ac73ddd0dd0cebef818b89da277">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::RelocTarget</a>.</p>

</div>
</div>

### SC {#aa58e727cbd920b5bc10d5f5ffbd6991a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolContainer* llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::SC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#a75e378475fd2557292cf2f043b7e4f57">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::getSymbolNum</a>, <a href="#a80b43edd789d692e5503f8b2a253f9c0">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::nlist</a> and <a href="#a7b59ff8add484951ac4094ad69d6709d">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::RelocTarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#aa0edc0062632d8b48784d74ce757151b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::orc::MachOBuilder::RelocTarget llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>

</div>
</div>

### Idx {#adfc740cdc689fe684bbcebeab39fd17e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::MachOBuilder&lt; MachOTraits &gt;::RelocTarget::Idx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
