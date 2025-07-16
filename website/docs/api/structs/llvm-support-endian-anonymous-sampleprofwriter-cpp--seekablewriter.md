---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/support/endian/anonymous-sampleprofwriter-cpp-/seekablewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SeekableWriter` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::support::endian::anonymous{SampleProfWriter.cpp}::SeekableWriter { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaa844f01f132b7ef18931a02c3129a5">SeekableWriter</a> (raw_pwrite_stream &amp;OS, endianness Endian)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5e920c664979d35633d569df89641f4">pwrite</a> (ValueType Val, size_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f118db665882b4152a1d192ba080e6">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9ee4e687f5a5817157ab9cedf8578d">Endian</a></td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SeekableWriter() {#abaa844f01f132b7ef18931a02c3129a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::support::endian::anonymous{SampleProfWriter.cpp}::SeekableWriter::SeekableWriter (<a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> Endian)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#aff9ee4e687f5a5817157ab9cedf8578d">Endian</a> and <a href="#a01f118db665882b4152a1d192ba080e6">OS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### pwrite() {#ad5e920c664979d35633d569df89641f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::anonymous{SampleProfWriter.cpp}::SeekableWriter::pwrite (<a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> Val, size_t Offset)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>References <a href="#aff9ee4e687f5a5817157ab9cedf8578d">Endian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a01f118db665882b4152a1d192ba080e6">OS</a> and <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#a16a69d4248bb11c84536099421ea833b">llvm::support::endian::Writer::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Endian {#aff9ee4e687f5a5817157ab9cedf8578d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">endianness llvm::support::endian::anonymous{SampleProfWriter.cpp}::SeekableWriter::Endian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#ad5e920c664979d35633d569df89641f4">pwrite</a> and <a href="#abaa844f01f132b7ef18931a02c3129a5">SeekableWriter</a>.</p>

</div>
</div>

### OS {#a01f118db665882b4152a1d192ba080e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_pwrite_stream&amp; llvm::support::endian::anonymous{SampleProfWriter.cpp}::SeekableWriter::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a>.</p>


<p>Referenced by <a href="#ad5e920c664979d35633d569df89641f4">pwrite</a> and <a href="#abaa844f01f132b7ef18931a02c3129a5">SeekableWriter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofwriter-cpp">SampleProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
