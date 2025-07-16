---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/minidumpyaml/memoryinfoliststream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MemoryInfoListStream` Struct Reference

<p>A structure containing the list of MemoryInfo entries comprising a MemoryInfoList stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MinidumpYAML::MemoryInfoListStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">llvm/ObjectYAML/MinidumpYAML.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base class for all minidump streams. <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7fef3cc0762a4a59e3f25a811f33b4">MemoryInfoListStream</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c42e5c535708b19ea98273f92aca5c">MemoryInfoListStream</a> (iterator_range&lt; object::MinidumpFile::MemoryInfoIterator &gt; Range)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/minidump/memoryinfo">minidump::MemoryInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de6355421cb60263877a0f39e18f4a3">Infos</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b3cd0c59c94feaac459a5a290f91aa">classof</a> (const Stream *S)</td>
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

## Description {#details}

<p>A structure containing the list of MemoryInfo entries comprising a MemoryInfoList stream.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemoryInfoListStream() {#a1f7fef3cc0762a4a59e3f25a811f33b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::MemoryInfoListStream::MemoryInfoListStream ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca9c3d5de61a6e11627540121a95ec339f">llvm::MinidumpYAML::Stream::MemoryInfoList</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a8522621888f28e27ba36290efcdc04bc">llvm::MinidumpYAML::Stream::Stream</a>.</p>

</div>
</div>

### MemoryInfoListStream() {#a28c42e5c535708b19ea98273f92aca5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::MemoryInfoListStream::MemoryInfoListStream (<a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/memoryinfoiterator">object::MinidumpFile::MemoryInfoIterator</a> &gt; Range)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="#a9de6355421cb60263877a0f39e18f4a3">Infos</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca9c3d5de61a6e11627540121a95ec339f">llvm::MinidumpYAML::Stream::MemoryInfoList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a8522621888f28e27ba36290efcdc04bc">llvm::MinidumpYAML::Stream::Stream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Infos {#a9de6355421cb60263877a0f39e18f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;minidump::MemoryInfo&gt; llvm::MinidumpYAML::MemoryInfoListStream::Infos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp/#a9572de1ba76b89eae1eb07c8b446b143">layout</a> and <a href="#a28c42e5c535708b19ea98273f92aca5c">MemoryInfoListStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ac5b3cd0c59c94feaac459a5a290f91aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MinidumpYAML::MemoryInfoListStream::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a> * S)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a492be506d939f72ca251976bc543d2a0">llvm::MinidumpYAML::Stream::Kind</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abca9c3d5de61a6e11627540121a95ec339f">llvm::MinidumpYAML::Stream::MemoryInfoList</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a8522621888f28e27ba36290efcdc04bc">llvm::MinidumpYAML::Stream::Stream</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
