---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/minidumpyaml/exceptionstream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ExceptionStream` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/exceptionstream">ExceptionStream</a> minidump stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MinidumpYAML::ExceptionStream { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854447e65002e3db37ec4fc8f25c7290">ExceptionStream</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12dcb76ca0e43de560b19380b6a03df6">ExceptionStream</a> (const minidump::ExceptionStream &amp;MDExceptionStream, ArrayRef&lt; uint8_t &gt; ThreadContext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/minidump/exceptionstream">minidump::ExceptionStream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628efc7b1f9a5920c74cd05ed2b29d84">MDExceptionStream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe626bc8a19acbb9c961d8f87936ad33">ThreadContext</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05fa02674c2982f09a3786c72c5dd35">classof</a> (const Stream *S)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/exceptionstream">ExceptionStream</a> minidump stream.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ExceptionStream() {#a854447e65002e3db37ec4fc8f25c7290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::ExceptionStream::ExceptionStream ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abcab0d4998a26f5b5742ad38c4af8817e32">llvm::MinidumpYAML::Stream::Exception</a>, <a href="#a628efc7b1f9a5920c74cd05ed2b29d84">MDExceptionStream</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a8522621888f28e27ba36290efcdc04bc">llvm::MinidumpYAML::Stream::Stream</a>.</p>

</div>
</div>

### ExceptionStream() {#a12dcb76ca0e43de560b19380b6a03df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MinidumpYAML::ExceptionStream::ExceptionStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidump/exceptionstream">minidump::ExceptionStream</a> &amp; MDExceptionStream, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; ThreadContext)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abcab0d4998a26f5b5742ad38c4af8817e32">llvm::MinidumpYAML::Stream::Exception</a>, <a href="#a628efc7b1f9a5920c74cd05ed2b29d84">MDExceptionStream</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a8522621888f28e27ba36290efcdc04bc">llvm::MinidumpYAML::Stream::Stream</a> and <a href="#afe626bc8a19acbb9c961d8f87936ad33">ThreadContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MDExceptionStream {#a628efc7b1f9a5920c74cd05ed2b29d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">minidump::ExceptionStream llvm::MinidumpYAML::ExceptionStream::MDExceptionStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="#a854447e65002e3db37ec4fc8f25c7290">ExceptionStream</a>, <a href="#a12dcb76ca0e43de560b19380b6a03df6">ExceptionStream</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp/#a334ff5caec6d220747f8c58bc2778729">layout</a>.</p>

</div>
</div>

### ThreadContext {#afe626bc8a19acbb9c961d8f87936ad33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::BinaryRef llvm::MinidumpYAML::ExceptionStream::ThreadContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>Referenced by <a href="#a12dcb76ca0e43de560b19380b6a03df6">ExceptionStream</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpemitter-cpp/#a334ff5caec6d220747f8c58bc2778729">layout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ac05fa02674c2982f09a3786c72c5dd35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MinidumpYAML::ExceptionStream::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream">Stream</a> * S)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/minidumpyaml-h">MinidumpYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#aef5260f83c38649509c6a7aac31c9abcab0d4998a26f5b5742ad38c4af8817e32">llvm::MinidumpYAML::Stream::Exception</a>, <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a492be506d939f72ca251976bc543d2a0">llvm::MinidumpYAML::Stream::Kind</a> and <a href="/web-llvm/docs/api/structs/llvm/minidumpyaml/stream/#a8522621888f28e27ba36290efcdc04bc">llvm::MinidumpYAML::Stream::Stream</a>.</p>

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
