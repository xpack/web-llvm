---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/support/endian/writer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Writer` Struct Reference

<p>Adapter to write values to a stream in a particular byte order. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::support::endian::Writer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">llvm/Support/EndianStream.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7bfd3d8cfcd87b225befeb8f70d939">Writer</a> (raw_ostream &amp;OS, endianness Endian)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16a69d4248bb11c84536099421ea833b">write</a> (ArrayRef&lt; value_type &gt; Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename value_type&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1edaf45d75710bd11bc254a371b8e47">write</a> (value_type Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6f1003a6933f07d06dbce84a8f26cb">OS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d6a0ba8131e3cfe0dd07409c1fdc77">Endian</a></td>
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

<p>Adapter to write values to a stream in a particular byte order.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Writer() {#afa7bfd3d8cfcd87b225befeb8f70d939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::support::endian::Writer::Writer (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">endianness</a> Endian)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>References <a href="#ad5d6a0ba8131e3cfe0dd07409c1fdc77">Endian</a> and <a href="#aea6f1003a6933f07d06dbce84a8f26cb">OS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### write() {#a16a69d4248bb11c84536099421ea833b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::Writer::write (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; value_type &gt; Val)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>References <a href="#ad5d6a0ba8131e3cfe0dd07409c1fdc77">Endian</a>, <a href="#aea6f1003a6933f07d06dbce84a8f26cb">OS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfmccodeemitter-cpp-/bpfmccodeemitter/#a76f5410dcaece835e30459df0a57c16c">anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/support/endian/anonymous-sampleprofwriter-cpp-/seekablewriter/#ad5e920c664979d35633d569df89641f4">llvm::support::endian::anonymous{SampleProfWriter.cpp}::SeekableWriter::pwrite</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a74ae6e240a1760c68a807fd885606fe6">llvm::OutlinedHashTreeRecord::serialize</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#aa6d6f1cad87cc3ed7f87784dd9ddff0f">llvm::StableFunctionMapRecord::serialize</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/anonymous-fdrtracewriter-cpp-/indexedwriter/#a1c231cc18850380661428875e8c99822">llvm::xray::anonymous{FDRTraceWriter.cpp}::IndexedWriter&lt; Index &gt;::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/anonymous-fdrtracewriter-cpp-/#a53787fd7c0f79784e176e673a77a071f">llvm::xray::anonymous{FDRTraceWriter.cpp}::writeMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a8da3b86e5070140af1716c64925a0495">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTable</a>.</p>

</div>
</div>

### write() {#ad1edaf45d75710bd11bc254a371b8e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename value_type&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::support::endian::Writer::write (value_type Val)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>References <a href="#ad5d6a0ba8131e3cfe0dd07409c1fdc77">Endian</a>, <a href="#aea6f1003a6933f07d06dbce84a8f26cb">OS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Endian {#ad5d6a0ba8131e3cfe0dd07409c1fdc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">endianness llvm::support::endian::Writer::Endian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>Referenced by <a href="#a16a69d4248bb11c84536099421ea833b">write</a>, <a href="#ad1edaf45d75710bd11bc254a371b8e47">write</a> and <a href="#afa7bfd3d8cfcd87b225befeb8f70d939">Writer</a>.</p>

</div>
</div>

### OS {#aea6f1003a6933f07d06dbce84a8f26cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::support::endian::Writer::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mclohdirective/#a31c388d4454133dfd0f5b26b0299f99d">llvm::MCLOHDirective::emit</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#aa6d6f1cad87cc3ed7f87784dd9ddff0f">llvm::StableFunctionMapRecord::serialize</a>, <a href="#a16a69d4248bb11c84536099421ea833b">write</a>, <a href="#ad1edaf45d75710bd11bc254a371b8e47">write</a> and <a href="#afa7bfd3d8cfcd87b225befeb8f70d939">Writer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endianstream-h">EndianStream.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
