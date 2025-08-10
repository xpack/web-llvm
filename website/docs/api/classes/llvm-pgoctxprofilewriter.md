---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pgoctxprofilewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PGOCtxProfileWriter` Class

<p>Write one or more ContextNodes to the provided <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PGOCtxProfileWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">llvm/ProfileData/PGOCtxProfWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e14ee9078852ac00c52462c0110b2f6">PGOCtxProfileWriter</a> (raw_ostream &amp;Out, std::optional&lt; unsigned &gt; VersionOverride=std::nullopt)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8219793abc9af652837cb67db88e9954">~PGOCtxProfileWriter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1815eac622ceabfe9d2e6bf0288b564">write</a> (const ctx_profile::ContextNode &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad980cea83fd0e7cdc62a0145cf1d2d">writeCounters</a> (const ctx_profile::ContextNode &amp;Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae1a004e8e45f4b3e16a6b7fab3cca0">writeImpl</a> (std::optional&lt; uint32_t &gt; CallerIndex, const ctx_profile::ContextNode &amp;Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4307771e01351eff2b94fa007b64c7c">Writer</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa517b7b0fff8dec01ea1d4f2a120835a">CodeLen</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5085a773e7301c23235738d9cd38ef11">CurrentVersion</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dcbfac5963074dc8c24addba3776acb">VBREncodingBits</a> = 6</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a655e5b7398d33b96fb414894717f2d96">ContainerMagic</a> = "CTXP"</td>
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

<p>Write one or more ContextNodes to the provided <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a>.</p>


<p>The caller must destroy the <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofilewriter">PGOCtxProfileWriter</a> object before closing the stream. The design allows serializing a bunch of contexts embedded in some other file. The overall format is:</p>


<p>[... other data written to the stream...] SubBlock(ProfileMetadataBlockID) Version SubBlock(ContextNodeBlockID) [RECORDS] SubBlock(ContextNodeBlockID) [RECORDS] [... more SubBlocks] EndBlock EndBlock</p>


<p>The "RECORDS" are bitsream records. The IDs are in CtxProfileCodes (except) for Version, which is just for metadata). All contexts will have Guid and Counters, and all but the roots have CalleeIndex. The order in which the records appear does not matter, but they must precede any subcontexts, because that helps keep the reader code simpler.</p>


<p>Subblock containment captures the context-&gt;subcontext relationship. The "next()" relationship in the raw profile, between call targets of indirect calls, are just modeled as peer subblocks where the callee index is the same.</p>


<p>Versioning: the writer may produce additional records not known by the reader. The version number indicates a more structural change. The current version, in particular, is set up to expect optional extensions like value profiling - which would appear as additional records. For example, value profiling would produce a new record with a new record <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, containing the profiled values (much like the counters)</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PGOCtxProfileWriter() {#a9e14ee9078852ac00c52462c0110b2f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PGOCtxProfileWriter::PGOCtxProfileWriter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, std::optional&lt; unsigned &gt; VersionOverride=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0a600cb28fa209fd6a46efb849315390f5">llvm::CalleeIndex</a>, <a href="#a655e5b7398d33b96fb414894717f2d96">ContainerMagic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0a9d56757e26d5a3bd902f8ec1a1964a18ef24afd46cef21c4406c391b05f932">llvm::ContextNodeBlockID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0a1825325dad32bd15f145220a44e0c010">llvm::Counters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0acb957607a78494ea70db887d1463437c">llvm::Guid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0a9d56757e26d5a3bd902f8ec1a1964ad620c73a18ab95fc44362e02508ee2be">llvm::ProfileMetadataBlockID</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PGOCtxProfileWriter() {#a8219793abc9af652837cb67db88e9954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PGOCtxProfileWriter::~PGOCtxProfileWriter ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### write() {#aa1815eac622ceabfe9d2e6bf0288b564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PGOCtxProfileWriter::write (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ctx_profile::ContextNode</a> &amp; RootNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a40f4f75fb4f4f3a69abd8360d590c93a">llvm::createCtxProfFromYAML</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### writeCounters() {#a6ad980cea83fd0e7cdc62a0145cf1d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PGOCtxProfileWriter::writeCounters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ctx_profile::ContextNode</a> &amp; Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>

</div>
</div>

### writeImpl() {#a2ae1a004e8e45f4b3e16a6b7fab3cca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PGOCtxProfileWriter::writeImpl (std::optional&lt; uint32_t &gt; CallerIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ctx-profile/contextnode">ctx_profile::ContextNode</a> &amp; Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Writer {#af4307771e01351eff2b94fa007b64c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitstreamWriter llvm::PGOCtxProfileWriter::Writer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### CodeLen {#aa517b7b0fff8dec01ea1d4f2a120835a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PGOCtxProfileWriter::CodeLen = 2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>.</p>

</div>
</div>

### ContainerMagic {#a655e5b7398d33b96fb414894717f2d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PGOCtxProfileWriter::ContainerMagic = "CTXP"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>.</p>


<p>Referenced by <a href="#a9e14ee9078852ac00c52462c0110b2f6">PGOCtxProfileWriter</a>.</p>

</div>
</div>

### CurrentVersion {#a5085a773e7301c23235738d9cd38ef11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PGOCtxProfileWriter::CurrentVersion = 1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>.</p>

</div>
</div>

### VBREncodingBits {#a4dcbfac5963074dc8c24addba3776acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PGOCtxProfileWriter::VBREncodingBits = 6</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofwriter-h">PGOCtxProfWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofwriter-cpp">PGOCtxProfWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
