---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-fileoutputbuffer-cpp-/ondiskbuffer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OnDiskBuffer` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{FileOutputBuffer.cpp}::OnDiskBuffer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a> - This interface provides simple way to create an in-memory buffer which will be written to a file. <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7a7eb5cdc4c740bde5f4bd2b661a83">OnDiskBuffer</a> (StringRef Path, fs::TempFile Temp, fs::mapped_file_region Buf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65f4d22985f5976d4a4785953e8f2be">~OnDiskBuffer</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b4420f9fd8b6fe06ea65ce1bab891b">getBufferStart</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the start of the buffer. <a href="#a60b4420f9fd8b6fe06ea65ce1bab891b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34015e473dcfe2fc880d68a72f3ce723">getBufferEnd</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the end of the buffer. <a href="#a34015e473dcfe2fc880d68a72f3ce723">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4fd5a73cc9f5a25c8a82f76e9dbaf04">getBufferSize</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of the buffer. <a href="#ad4fd5a73cc9f5a25c8a82f76e9dbaf04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a138cd3bcdff42739b4b0111fa28c4b45">commit</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flushes the content of the buffer to its file and deallocates the buffer. <a href="#a138cd3bcdff42739b4b0111fa28c4b45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a985e9c77b5e84d9fb441cbd1152323ef">discard</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This removes the temporary file (unless it already was committed) but keeps the memory mapping alive. <a href="#a985e9c77b5e84d9fb441cbd1152323ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">fs::mapped_file_region</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3ed587ef23b23d59f6371a7e247bee">Buffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/tempfile">fs::TempFile</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f255c9e6b72b3931927e6383054f21">Temp</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OnDiskBuffer() {#acc7a7eb5cdc4c740bde5f4bd2b661a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::OnDiskBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/tempfile">fs::TempFile</a> Temp, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">fs::mapped_file_region</a> Buf)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a92df6484e65e47b575a10a4f2080ae1b">llvm::FileOutputBuffer::FileOutputBuffer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~OnDiskBuffer() {#ab65f4d22985f5976d4a4785953e8f2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::~OnDiskBuffer ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### commit() {#a138cd3bcdff42739b4b0111fa28c4b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::commit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flushes the content of the buffer to its file and deallocates the buffer.</p>


<p>If <a href="#a138cd3bcdff42739b4b0111fa28c4b45">commit()</a> is not called before this object's destructor is called, the file is deleted in the destructor. The optional parameter is used if it turns out you want the file size to be smaller than initially requested.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#afa260e26c967de39c8006b90831d428d">llvm::FileOutputBuffer::FinalPath</a>.</p>

</div>
</div>

### discard() {#a985e9c77b5e84d9fb441cbd1152323ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::discard ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This removes the temporary file (unless it already was committed) but keeps the memory mapping alive.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>.</p>

</div>
</div>

### getBufferEnd() {#a34015e473dcfe2fc880d68a72f3ce723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::getBufferEnd ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the end of the buffer.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>

</div>
</div>

### getBufferSize() {#ad4fd5a73cc9f5a25c8a82f76e9dbaf04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::getBufferSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of the buffer.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>

</div>
</div>

### getBufferStart() {#a60b4420f9fd8b6fe06ea65ce1bab891b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t * anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::getBufferStart ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the start of the buffer.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffer {#a9e3ed587ef23b23d59f6371a7e247bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fs::mapped_file_region anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>

</div>
</div>

### Temp {#ac2f255c9e6b72b3931927e6383054f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fs::TempFile anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::Temp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
