---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/chainedfixupssegment
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ChainedFixupsSegment` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::object::ChainedFixupsSegment { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">llvm/Object/MachO.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5593ac5afca215cd9ff6782ec4e9ee37">ChainedFixupsSegment</a> (uint8_t SegIdx, uint32_t Offset, const MachO::dyld_chained_starts_in_segment &amp;Header, std::vector&lt; uint16_t &gt; &amp;&amp;PageStarts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13627e086bf022bcbe1646db04e10213">SegIdx</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af61500980aff05b5d43ccdd81aded8c4">Offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-segment">MachO::dyld_chained_starts_in_segment</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ad985610beb118307ece50312b8f75">Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42866b74d118b9e226122aeb1003fd8d">PageStarts</a></td>
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


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ChainedFixupsSegment() {#a5593ac5afca215cd9ff6782ec4e9ee37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::ChainedFixupsSegment::ChainedFixupsSegment (uint8_t SegIdx, uint32_t Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/dyld-chained-starts-in-segment">MachO::dyld_chained_starts_in_segment</a> &amp; Header, std::vector&lt; uint16_t &gt; &amp;&amp; PageStarts)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>References <a href="#a19ad985610beb118307ece50312b8f75">Header</a>, <a href="#af61500980aff05b5d43ccdd81aded8c4">Offset</a>, <a href="#a42866b74d118b9e226122aeb1003fd8d">PageStarts</a> and <a href="#a13627e086bf022bcbe1646db04e10213">SegIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Header {#a19ad985610beb118307ece50312b8f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::dyld_chained_starts_in_segment llvm::object::ChainedFixupsSegment::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a5593ac5afca215cd9ff6782ec4e9ee37">ChainedFixupsSegment</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>.</p>

</div>
</div>

### Offset {#af61500980aff05b5d43ccdd81aded8c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::ChainedFixupsSegment::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a5593ac5afca215cd9ff6782ec4e9ee37">ChainedFixupsSegment</a>.</p>

</div>
</div>

### PageStarts {#a42866b74d118b9e226122aeb1003fd8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint16_t&gt; llvm::object::ChainedFixupsSegment::PageStarts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a5593ac5afca215cd9ff6782ec4e9ee37">ChainedFixupsSegment</a>.</p>

</div>
</div>

### SegIdx {#a13627e086bf022bcbe1646db04e10213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::ChainedFixupsSegment::SegIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a>.</p>


<p>Referenced by <a href="#a5593ac5afca215cd9ff6782ec4e9ee37">ChainedFixupsSegment</a> and <a href="/web-llvm/docs/api/classes/llvm/object/machochainedfixupentry/#a1ac5316af2beb36b1eee67c09c7448f8">llvm::object::MachOChainedFixupEntry::moveNext</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/macho-h">MachO.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
