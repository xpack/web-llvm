---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/machobuilder/segment
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Segment` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::MachOBuilder::Segment { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">llvm/ExecutionEngine/Orc/MachOBuilder.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/machobuilderloadcommand">MachOBuilderLoadCommand&lt;LCType&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483c24f3e678c049cf305bc40281fb08">Segment</a> (MachOBuilder &amp;Builder, StringRef SegName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section">Section</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a42588ddf27706bd8ad5d8c9bcc4fd5">addSection</a> (StringRef SecName, StringRef SegName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2e2b77c9766de0a759b271cd5fe61f">write</a> (MutableArrayRef&lt; char &gt; Buf, size_t Offset, bool SwapStruct) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc7f01d7dc2942afb6d225eaa2828400">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilder/section">Section</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade0a7036b8ad844c24958878014204a">Sections</a></td>
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


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Segment() {#a483c24f3e678c049cf305bc40281fb08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Segment (<a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder">MachOBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SegName)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adc7f01d7dc2942afb6d225eaa2828400">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/#acf9640c61b9402f751474184c88ac75e">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::MachOBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilderloadcommand/#ad502ec4b0c0c25dbebcc851791f6fde4">llvm::orc::MachOBuilderLoadCommand&lt; MachOTraits::SegmentCmd &gt;::MachOBuilderLoadCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783a459028b54c6de464c939b7a148dee815">llvm::MachO::VM_PROT_EXECUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783a9dccfb77c950352acfcae05d2002d5d4">llvm::MachO::VM_PROT_READ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a113815f0ead74239386436bbebdbd783acca2a1b89bc84f63aa45c62455c7fcae">llvm::MachO::VM_PROT_WRITE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSection() {#a6a42588ddf27706bd8ad5d8c9bcc4fd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section &amp; llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::addSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SegName)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="#adc7f01d7dc2942afb6d225eaa2828400">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Builder</a> and <a href="#aade0a7036b8ad844c24958878014204a">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Sections</a>.</p>

</div>
</div>

### write() {#abf2e2b77c9766de0a759b271cd5fe61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::write (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Buf, size_t Offset, bool SwapStruct)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/machobuilderloadcommand/#ad502ec4b0c0c25dbebcc851791f6fde4">llvm::orc::MachOBuilderLoadCommand&lt; MachOTraits::SegmentCmd &gt;::MachOBuilderLoadCommand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#aade0a7036b8ad844c24958878014204a">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Sections</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3da63e49444198a2e47dad26fb6feb67">llvm::orc::writeMachOStruct</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Builder {#adc7f01d7dc2942afb6d225eaa2828400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOBuilder&amp; llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#a6a42588ddf27706bd8ad5d8c9bcc4fd5">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::addSection</a> and <a href="#a483c24f3e678c049cf305bc40281fb08">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Segment</a>.</p>

</div>
</div>

### Sections {#aade0a7036b8ad844c24958878014204a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Section&gt; &gt; llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::Sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#a6a42588ddf27706bd8ad5d8c9bcc4fd5">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::addSection</a> and <a href="#abf2e2b77c9766de0a759b271cd5fe61f">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Segment::write</a>.</p>

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
