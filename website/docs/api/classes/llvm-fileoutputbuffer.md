---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fileoutputbuffer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FileOutputBuffer` Class

<p><a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a> - This interface provides simple way to create an in-memory buffer which will be written to a file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FileOutputBuffer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">llvm/Support/FileOutputBuffer.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-fileoutputbuffer-cpp-/inmemorybuffer">InMemoryBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-fileoutputbuffer-cpp-/ondiskbuffer">OnDiskBuffer</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#af1b284b267d7f4e6bac7b2e2f5916543">...</a> }</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92df6484e65e47b575a10a4f2080ae1b">FileOutputBuffer</a> (StringRef Path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f000f4de53568b0618c9271ba71ce01">~FileOutputBuffer</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this object was previously committed, the destructor just deletes this object. <a href="#a4f000f4de53568b0618c9271ba71ce01">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10eafd7021bff750e7cc5da3f6c83516">getBufferStart</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the start of the buffer. <a href="#a10eafd7021bff750e7cc5da3f6c83516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fa8358ab39c2f8ada5168ec36b5e446">getBufferEnd</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the end of the buffer. <a href="#a9fa8358ab39c2f8ada5168ec36b5e446">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe56ca0702b9a1b01ea3152df952f813">getBufferSize</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of the buffer. <a href="#abe56ca0702b9a1b01ea3152df952f813">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8608f2b468c9ff9ff7a890c12dffd4f9">getPath</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns path where file will show up if buffer is committed. <a href="#a8608f2b468c9ff9ff7a890c12dffd4f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb077585b21cdc78ea9bdd1c0624228">commit</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flushes the content of the buffer to its file and deallocates the buffer. <a href="#aafb077585b21cdc78ea9bdd1c0624228">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acec36e58ffe661130abcaec115178ee7">discard</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This removes the temporary file (unless it already was committed) but keeps the memory mapping alive. <a href="#acec36e58ffe661130abcaec115178ee7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa260e26c967de39c8006b90831d428d">FinalPath</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a10ce8cad8fee5d6a4c55270866aa05">create</a> (StringRef FilePath, size_t Size, unsigned Flags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory method to create an <a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> object which manages a read/write buffer of the specified size. <a href="#a3a10ce8cad8fee5d6a4c55270866aa05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a> - This interface provides simple way to create an in-memory buffer which will be written to a file.</p>


<p>During the lifetime of these objects, the content or existence of the specified file is undefined. That is, creating an <a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> for a file may immediately remove the file. If the <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a> is committed, the target file's content will become the buffer content at the time of the commit. If the <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a> is not committed, the file will be deleted in the <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a> destructor.</p>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#af1b284b267d7f4e6bac7b2e2f5916543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_executable<a id="af1b284b267d7f4e6bac7b2e2f5916543afe6cf01b015c486f72450c8dee965b43"></a></td>
<td class="doxyEnumItemDescription">Set the 'x' bit on the resulting file (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F_no_mmap<a id="af1b284b267d7f4e6bac7b2e2f5916543a689301246a0b57930b400d09c64c2efa"></a></td>
<td class="doxyEnumItemDescription">Don't use mmap and instead write an in-memory buffer to a file when this buffer is closed (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### FileOutputBuffer() {#a92df6484e65e47b575a10a4f2080ae1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FileOutputBuffer::FileOutputBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>


<p>Reference <a href="#afa260e26c967de39c8006b90831d428d">FinalPath</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-fileoutputbuffer-cpp-/inmemorybuffer/#ad881bb4ed438c5b0eed9e985410f3a94">anonymous{FileOutputBuffer.cpp}::InMemoryBuffer::InMemoryBuffer</a> and <a href="/web-llvm/docs/api/classes/anonymous-fileoutputbuffer-cpp-/ondiskbuffer/#acc7a7eb5cdc4c740bde5f4bd2b661a83">anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::OnDiskBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FileOutputBuffer() {#a4f000f4de53568b0618c9271ba71ce01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::FileOutputBuffer::~FileOutputBuffer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this object was previously committed, the destructor just deletes this object.</p>


<p>If this object was not committed, the destructor deallocates the buffer and the target file is never written.</p>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### commit() {#aafb077585b21cdc78ea9bdd1c0624228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::FileOutputBuffer::commit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flushes the content of the buffer to its file and deallocates the buffer.</p>


<p>If <a href="#aafb077585b21cdc78ea9bdd1c0624228">commit()</a> is not called before this object's destructor is called, the file is deleted in the destructor. The optional parameter is used if it turns out you want the file size to be smaller than initially requested.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>

</div>
</div>

### discard() {#acec36e58ffe661130abcaec115178ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::FileOutputBuffer::discard ()</td>
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

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>

</div>
</div>

### getBufferEnd() {#a9fa8358ab39c2f8ada5168ec36b5e446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint8_t * llvm::FileOutputBuffer::getBufferEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the end of the buffer.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>

</div>
</div>

### getBufferSize() {#abe56ca0702b9a1b01ea3152df952f813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual size_t llvm::FileOutputBuffer::getBufferSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of the buffer.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>

</div>
</div>

### getBufferStart() {#a10eafd7021bff750e7cc5da3f6c83516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint8_t * llvm::FileOutputBuffer::getBufferStart ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the start of the buffer.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>

</div>
</div>

### getPath() {#a8608f2b468c9ff9ff7a890c12dffd4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::FileOutputBuffer::getPath ()</td>
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

<p>Returns path where file will show up if buffer is committed.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>


<p>Reference <a href="#afa260e26c967de39c8006b90831d428d">FinalPath</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### FinalPath {#afa260e26c967de39c8006b90831d428d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::FileOutputBuffer::FinalPath</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-fileoutputbuffer-cpp-/inmemorybuffer/#aa633fcd4ff4b9eb332ba7f26d090c10a">anonymous{FileOutputBuffer.cpp}::InMemoryBuffer::commit</a>, <a href="/web-llvm/docs/api/classes/anonymous-fileoutputbuffer-cpp-/ondiskbuffer/#a138cd3bcdff42739b4b0111fa28c4b45">anonymous{FileOutputBuffer.cpp}::OnDiskBuffer::commit</a>, <a href="#a92df6484e65e47b575a10a4f2080ae1b">FileOutputBuffer</a> and <a href="#a8608f2b468c9ff9ff7a890c12dffd4f9">getPath</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a3a10ce8cad8fee5d6a4c55270866aa05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; FileOutputBuffer &gt; &gt; FileOutputBuffer::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FilePath, size_t Size, unsigned Flags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Factory method to create an <a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a> object which manages a read/write buffer of the specified size.</p>


<p>When committed, the buffer will be written to the file at the specified path.</p>


<p>When F_modify is specified and <span class="doxyComputerOutput">FilePath</span> refers to an existing on-disk file <span class="doxyComputerOutput">Size</span> may be set to -1, in which case the entire file is used. Otherwise, the file shrinks or grows as necessary based on the value of <span class="doxyComputerOutput">Size</span>. It is an error to specify F_modify and Size=-1 if <span class="doxyComputerOutput">FilePath</span> does not exist.</p>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82a5a587f3cbb44292644d2f34d72f40553">llvm::sys::fs::all_exe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82ab5e842a50787e803e6e66bc9cc73f634">llvm::sys::fs::all_read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82a1c2301837e9bfe7c9c8421b540d92822">llvm::sys::fs::all_write</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp/#ab567e593dcf755d782527311e9b300fa">createInMemoryBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp/#a31b5a8b8b08e1fc483335974755720ed">createOnDiskBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca1c3e56917e1b64d1874d5d88c085e0c9">llvm::sys::fs::directory_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#af1b284b267d7f4e6bac7b2e2f5916543afe6cf01b015c486f72450c8dee965b43">F_executable</a>, <a href="#af1b284b267d7f4e6bac7b2e2f5916543a689301246a0b57930b400d09c64c2efa">F_no_mmap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4cbd4f831bcb7891ccf9a70c3957cf49">llvm::sys::fs::file_not_found</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baf3c51d7ea75a76f26c0a2bdc00c4e006">llvm::is_a_directory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4676601564b208338edf7317182f473e">llvm::sys::fs::regular_file</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca39fe2d3c413eb8d3f1d2f3b199fd29de">llvm::sys::fs::status_error</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status/#ab01b92f53a9f931c5859498219da2613">llvm::sys::fs::basic_file_status::type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/msf/msfbuilder/#a6c98d361786661879be283e8abc78dbf">llvm::msf::MSFBuilder::commit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#abe70653ea636e6b63159edf52d38afc5">llvm::objcopy::deepWriteArchive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#a81e88ae7d3e872ba0cdc367330b2974d">llvm::objcopy::coff::dumpSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a101c2836638ffc1c34e2e502ad68d0da">llvm::ifs::writeELFBinaryToFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">FileOutputBuffer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
