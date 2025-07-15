---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/writablememorybuffer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WritableMemoryBuffer` Class Reference

<p>This class is an extension of <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, which allows copy-on-write access to the underlying contents. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::WritableMemoryBuffer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This interface provides simple read-only access to a block of memory, and provides simple methods for reading files and standard input into a memory buffer. <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4571f3c6ad2b03f15e98bd2ba964888e">WritableMemoryBuffer</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7def6ecf63f529b0f7b9009a8140211">getBufferStart</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1220c05a9c901648d43e36ee6df59f6">getBufferEnd</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26c7adb475a83fc408039305e3e130a1">getBuffer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d9843621ff4677c0b9087277dc4bd0">getBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4604d3bedbb15e6c516f9357d3b773e">getBufferEnd</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1972b9a0324e0311ad641eac2de2b7f">getBufferStart</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401009afe6f903790ffe143f90da5084">getFile</a> (const Twine &amp;Filename, bool IsVolatile=false, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9a4fd03fd65c900374b608a411ad3c">getFileSlice</a> (const Twine &amp;Filename, uint64_t MapSize, uint64_t Offset, bool IsVolatile=false, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a subrange of the specified file as a <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a>. <a href="#a6c9a4fd03fd65c900374b608a411ad3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb6ea02c3dec9abe04c03e501c60f75">getNewUninitMemBuffer</a> (size_t Size, const Twine &amp;BufferName="", std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a new <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> of the specified size that is not initialized. <a href="#a4cb6ea02c3dec9abe04c03e501c60f75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba0db4e545291ac0dbf07804f13d351">getNewMemBuffer</a> (size_t Size, const Twine &amp;BufferName="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a new zero-initialized <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> of the specified size. <a href="#a3ba0db4e545291ac0dbf07804f13d351">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b193577aa67b1fac72cdbb5343241a">getFileAsStream</a> (const Twine &amp;Filename)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read all of the specified file into a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> as a stream (i.e. <a href="#a76b193577aa67b1fac72cdbb5343241a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c54e2428ad0163441789c281ca42ee4">getFileOrSTDIN</a> (const Twine &amp;Filename, bool IsText=false, bool RequiresNullTerminator=true, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified file as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, or open stdin if the Filename is "-". <a href="#a9c54e2428ad0163441789c281ca42ee4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f68098734d6d3b451aacf5b38a67131">getMemBuffer</a> (StringRef InputData, StringRef BufferName="", bool RequiresNullTerminator=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified memory range as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a0f68098734d6d3b451aacf5b38a67131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1821192144d28e409d3eb945b5f19bb0">getMemBuffer</a> (MemoryBufferRef Ref, bool RequiresNullTerminator=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32d2c9ba9019e6e41605c60acd06bd09">getMemBufferCopy</a> (StringRef InputData, const Twine &amp;BufferName="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified memory range as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, copying the contents and taking ownership of it. <a href="#a32d2c9ba9019e6e41605c60acd06bd09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0163ef693f4fd640ec72a5fe74e5852c">getOpenFile</a> (sys::fs::file_t FD, const Twine &amp;Filename, uint64_t FileSize, bool RequiresNullTerminator=true, bool IsVolatile=false, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an already-open file descriptor, read the file and return a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a0163ef693f4fd640ec72a5fe74e5852c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4432e24dbd29bafd528e623c04c62395">getOpenFileSlice</a> (sys::fs::file_t FD, const Twine &amp;Filename, uint64_t MapSize, int64_t Offset, bool IsVolatile=false, std::optional&lt; Align &gt; Alignment=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an already-open file descriptor, map some slice of it into a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>. <a href="#a4432e24dbd29bafd528e623c04c62395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56e946cf4266646c30b0898033b88bc">getSTDIN</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read all of stdin into a file buffer, and return it. <a href="#ae56e946cf4266646c30b0898033b88bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class is an extension of <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, which allows copy-on-write access to the underlying contents.</p>


<p>It only supports creation methods that are guaranteed to produce a writable buffer. For example, mapping a file read-only is not supported.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### WritableMemoryBuffer() {#a4571f3c6ad2b03f15e98bd2ba964888e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WritableMemoryBuffer::WritableMemoryBuffer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a69d9843621ff4677c0b9087277dc4bd0">llvm::MemoryBuffer::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#ae4604d3bedbb15e6c516f9357d3b773e">llvm::MemoryBuffer::getBufferEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#af1972b9a0324e0311ad641eac2de2b7f">llvm::MemoryBuffer::getBufferStart</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBuffer() {#a26c7adb475a83fc408039305e3e130a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; char &gt; llvm::WritableMemoryBuffer::getBuffer ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>References <a href="#ae1220c05a9c901648d43e36ee6df59f6">getBufferEnd</a> and <a href="#aa7def6ecf63f529b0f7b9009a8140211">getBufferStart</a>.</p>

</div>
</div>

### getBuffer() {#a69d9843621ff4677c0b9087277dc4bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MemoryBuffer::getBuffer ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

### getBufferEnd() {#ae1220c05a9c901648d43e36ee6df59f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::WritableMemoryBuffer::getBufferEnd ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#ae4604d3bedbb15e6c516f9357d3b773e">llvm::MemoryBuffer::getBufferEnd</a>.</p>


<p>Referenced by <a href="#a26c7adb475a83fc408039305e3e130a1">getBuffer</a>.</p>

</div>
</div>

### getBufferEnd() {#ae4604d3bedbb15e6c516f9357d3b773e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MemoryBuffer::getBufferEnd ()</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

### getBufferStart() {#aa7def6ecf63f529b0f7b9009a8140211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::WritableMemoryBuffer::getBufferStart ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#af1972b9a0324e0311ad641eac2de2b7f">llvm::MemoryBuffer::getBufferStart</a>.</p>


<p>Referenced by <a href="#a26c7adb475a83fc408039305e3e130a1">getBuffer</a>.</p>

</div>
</div>

### getBufferStart() {#af1972b9a0324e0311ad641eac2de2b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MemoryBuffer::getBufferStart ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFile() {#a401009afe6f903790ffe143f90da5084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; WritableMemoryBuffer &gt; &gt; WritableMemoryBuffer::getFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, bool IsVolatile=false, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a4b1e92bf20cb54acca62efdbfdebad54">getFileAux</a>.</p>

</div>
</div>

### getFileSlice() {#a6c9a4fd03fd65c900374b608a411ad3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; WritableMemoryBuffer &gt; &gt; WritableMemoryBuffer::getFileSlice (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t MapSize, uint64_t Offset, bool IsVolatile=false, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Map a subrange of the specified file as a <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer">WritableMemoryBuffer</a>.</p>

<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a4b1e92bf20cb54acca62efdbfdebad54">getFileAux</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getNewMemBuffer() {#a3ba0db4e545291ac0dbf07804f13d351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; WritableMemoryBuffer &gt; WritableMemoryBuffer::getNewMemBuffer (size_t Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BufferName="")</td>
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

<p>Allocate a new zero-initialized <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> of the specified size.</p>


<p>Note that the caller need not initialize the memory allocated by this method. The memory is owned by the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> object.</p>


<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="#a4cb6ea02c3dec9abe04c03e501c60f75">getNewUninitMemBuffer</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/asciihexwriter/#a6c8bb3c922ce45c595377546d41f1222">llvm::objcopy::elf::ASCIIHexWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5b9da0f3636f00c8eb9dca28bf21e606">llvm::objcopy::elf::BinaryWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfwriter/#a96ec94d70c19707787f756fa97cc3467">llvm::objcopy::elf::ELFWriter&lt; ELFT &gt;::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/windowsresourcecoffwriter/#a73516b68a8b7fc352af8c8702a6f850a">llvm::object::WindowsResourceCOFFWriter::WindowsResourceCOFFWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#a664a6fc223b56ef4fec7642360062ae0">llvm::objcopy::macho::MachOWriter::write</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/xcoff/xcoffwriter/#af3adedc8850f537a3ba8e71bba9d9934">llvm::objcopy::xcoff::XCOFFWriter::write</a>.</p>

</div>
</div>

### getNewUninitMemBuffer() {#a4cb6ea02c3dec9abe04c03e501c60f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; WritableMemoryBuffer &gt; WritableMemoryBuffer::getNewUninitMemBuffer (size_t Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BufferName="", std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Allocate a new <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> of the specified size that is not initialized.</p>


<p>Note that the caller should initialize the memory allocated by this method. The memory is owned by the <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> object.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>Set to indicate that the buffer should be aligned to at least the specified alignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afff5074588f0423a669618a7134e13ec">llvm::alignAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a9886e033885181e8d14e3fddce06af8c">CopyStringRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#ac521760e9a45f304a4cbe46ed4fff845">llvm::Twine::toStringRef</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#a138ae135dded82599e2cd8a1a80cdab4">llvm::object::COFFObjectFile::getHybridObjectView</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a8da8a8e7960a91583ad18b42ecbbadeb">getMemBufferCopyImpl</a>, <a href="#a3ba0db4e545291ac0dbf07804f13d351">getNewMemBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a71a8c6078191280b00feef9864b58338">loadBinaryFormat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getFileAsStream() {#a76b193577aa67b1fac72cdbb5343241a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getFileAsStream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename)</td>
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

<p>Read all of the specified file into a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> as a stream (i.e.</p>


<p>until EOF reached). This is useful for special files that look like a regular file but have 0 size (e.g. /proc/cpuinfo on Linux).</p>


<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### getFileOrSTDIN() {#a9c54e2428ad0163441789c281ca42ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getFileOrSTDIN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, bool IsText=false, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Open the specified file as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, or open stdin if the Filename is "-".</p>

<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### getMemBuffer() {#a0f68098734d6d3b451aacf5b38a67131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; MemoryBuffer::getMemBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputData, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BufferName="", bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Open the specified memory range as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>


<p>Note that InputData must be null terminated if RequiresNullTerminator is true.</p>


<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### getMemBuffer() {#a1821192144d28e409d3eb945b5f19bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; MemoryBuffer::getMemBuffer (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Ref, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### getMemBufferCopy() {#a32d2c9ba9019e6e41605c60acd06bd09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; MemoryBuffer::getMemBufferCopy (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BufferName="")</td>
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

<p>Open the specified memory range as a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>, copying the contents and taking ownership of it.</p>


<p>InputData does not have to be null terminated.</p>


<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### getOpenFile() {#a0163ef693f4fd640ec72a5fe74e5852c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getOpenFile (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> FD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t FileSize, bool RequiresNullTerminator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool IsVolatile=false, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Given an already-open file descriptor, read the file and return a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsVolatile</td>
<td class="doxyParamItemDescription"><p>Set to true to indicate that the contents of the file can change outside the user's control, e.g. when libclang tries to parse while the user is editing/updating the file or if the file is on an NFS.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Alignment</td>
<td class="doxyParamItemDescription"><p>Set to indicate that the buffer should be aligned to at least the specified alignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### getOpenFileSlice() {#a4432e24dbd29bafd528e623c04c62395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getOpenFileSlice (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> FD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t MapSize, int64_t Offset, bool IsVolatile=false, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment=std::nullopt)</td>
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

<p>Given an already-open file descriptor, map some slice of it into a <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>.</p>


<p>The slice is specified by an <span class="doxyComputerOutput">Offset</span> and <span class="doxyComputerOutput">MapSize</span>. Since this is in the middle of a file, the buffer is not null terminated.</p>


<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

### getSTDIN() {#ae56e946cf4266646c30b0898033b88bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; MemoryBuffer::getSTDIN ()</td>
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

<p>Read all of stdin into a file buffer, and return it.</p>

<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">MemoryBuffer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
