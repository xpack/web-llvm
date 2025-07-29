---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcopy/elf/ihexelfbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IHexELFBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::objcopy::elf::IHexELFBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ObjCopy/ELF/ELFObject.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/basicelfbuilder">BasicELFBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a650a0ab266d5865dcee7f81110fbe">IHexELFBuilder</a> (const std::vector&lt; IHexRecord &gt; &amp;Records)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object">Object</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1fb9c0a732defd1d594da8794d32a7">build</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5c812b2e2a55e753eb073e8baccd9f">addDataSections</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord">IHexRecord</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab3bad52fb1e9e93b06950bc887b407">Records</a></td>
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


<p>Definition at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IHexELFBuilder() {#a18a650a0ab266d5865dcee7f81110fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcopy::elf::IHexELFBuilder::IHexELFBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/objcopy/elf/ihexrecord">IHexRecord</a> &gt; &amp; Records)</td>
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



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### build() {#abd1fb9c0a732defd1d594da8794d32a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Object &gt; &gt; IHexELFBuilder::build ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/basicelfbuilder/#a46bf4a5a8c7c2180cc146f232e4f7f6d">llvm::objcopy::elf::BasicELFBuilder::addStrTab</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/basicelfbuilder/#a62e4794b651253df24ca9cd5fe61340a">llvm::objcopy::elf::BasicELFBuilder::addSymTab</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/basicelfbuilder/#a53156fa08af05b511e0e9c0f476c1545">llvm::objcopy::elf::BasicELFBuilder::initFileHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/basicelfbuilder/#a5598313252548691a55e2e29dbe69e8c">llvm::objcopy::elf::BasicELFBuilder::initHeaderSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/basicelfbuilder/#ac573c6c02b8dea91c6c3831eac21b0ea">llvm::objcopy::elf::BasicELFBuilder::initSections</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/basicelfbuilder/#a74927e6bf86dae4692a942b02375e7d9">llvm::objcopy::elf::BasicELFBuilder::Obj</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexreader/#ab555c94f27e6468da42830c081be3bff">llvm::objcopy::elf::IHexReader::create</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDataSections() {#a4e5c812b2e2a55e753eb073e8baccd9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IHexELFBuilder::addDataSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>, definition at line 1349 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Records {#abab3bad52fb1e9e93b06950bc887b407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt;IHexRecord&gt;&amp; llvm::objcopy::elf::IHexELFBuilder::Records</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp">ELFObject.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-h">ELFObject.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
