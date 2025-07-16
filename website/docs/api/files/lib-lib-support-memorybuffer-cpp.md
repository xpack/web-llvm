---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/memorybuffer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MemoryBuffer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">llvm/Support/Alignment.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/program-h">llvm/Support/Program.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">llvm/Support/SmallVectorMemoryBuffer.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstring&gt;
#include &lt;new&gt;
#include &lt;sys/types.h&gt;
#include &lt;system_error&gt;
#include &lt;unistd.h&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-memorybuffer-cpp-">anonymous{MemoryBuffer.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memorybuffer-cpp-/namedbufferalloc">NamedBufferAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem">MemoryBufferMem&lt;MB&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem">MemoryBufferMem</a> - Named <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> pointing to a block of memory. <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermem/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermmapfile">MemoryBufferMMapFile&lt;MB&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> maps a file descriptor using <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">sys::fs::mapped_file_region</a>. <a href="/web-llvm/docs/api/classes/anonymous-memorybuffer-cpp-/memorybuffermmapfile/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a44946d964a5e69dfa745bb1e9eabd">operator new</a> (size_t N, const NamedBufferAlloc &amp;Alloc)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9886e033885181e8d14e3fddce06af8c">CopyStringRef</a> (char *Memory, StringRef Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CopyStringRef - Copies contents of a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> into a block of memory and null-terminates it. <a href="#a9886e033885181e8d14e3fddce06af8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b1e92bf20cb54acca62efdbfdebad54">getFileAux</a> (const Twine &amp;Filename, uint64_t MapSize, uint64_t Offset, bool IsText, bool RequiresNullTerminator, bool IsVolatile, std::optional&lt; Align &gt; Alignment) -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/mb">MB</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8da8a8e7960a91583ad18b42ecbbadeb">getMemBufferCopyImpl</a> (StringRef InputData, const Twine &amp;BufferName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad17f4118ff721e4675c06f38373a7d1">getMemoryBufferForStream</a> (sys::fs::file_t FD, const Twine &amp;BufferName)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MB&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a> (sys::fs::file_t FD, const Twine &amp;Filename, uint64_t FileSize, uint64_t MapSize, int64_t Offset, bool RequiresNullTerminator, bool IsVolatile, std::optional&lt; Align &gt; Alignment) -&gt; <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/mb">MB</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d9351d1bd2c5f5169b0bbc856b1a52">shouldUseMmap</a> (sys::fs::file_t FD, size_t FileSize, size_t MapSize, off_t Offset, bool RequiresNullTerminator, int PageSize, bool IsVolatile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer">WriteThroughMemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ce38671d4f07799441a502041db0ff">getReadWriteFile</a> (const Twine &amp;Filename, uint64_t FileSize, uint64_t MapSize, uint64_t Offset)</td>
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


<div class="doxySectionDef">

## Operators

### operator new() {#a21a44946d964a5e69dfa745bb1e9eabd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * operator new (size_t N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NamedBufferAlloc &amp; Alloc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="#a9886e033885181e8d14e3fddce06af8c">CopyStringRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afcd76d92f6ad67759238ccef6ec883af">llvm::report_bad_alloc_error</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### CopyStringRef() {#a9886e033885181e8d14e3fddce06af8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CopyStringRef (char * Memory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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

<p>CopyStringRef - Copies contents of a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> into a block of memory and null-terminates it.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4cb6ea02c3dec9abe04c03e501c60f75">llvm::WritableMemoryBuffer::getNewUninitMemBuffer</a> and <a href="#a21a44946d964a5e69dfa745bb1e9eabd">operator new</a>.</p>

</div>
</div>

### getFileAux() {#a4b1e92bf20cb54acca62efdbfdebad54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MB &gt; &gt; getFileAux (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t MapSize, uint64_t Offset, bool IsText, bool RequiresNullTerminator, bool IsVolatile, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a43548658b3d92c080577422f81f38038">llvm::sys::fs::closeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed898e74c946513975b0d7aad4d65e40">llvm::errorToErrorCode</a>, <a href="#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ae025e411759250214ffc53ab8d8a5e1d">llvm::sys::fs::openNativeFileForRead</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a401009afe6f903790ffe143f90da5084">llvm::WritableMemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa519672f542c6c93e950a9a9a6b14817">llvm::MemoryBuffer::getFileSlice</a> and <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a6c9a4fd03fd65c900374b608a411ad3c">llvm::WritableMemoryBuffer::getFileSlice</a>.</p>

</div>
</div>

### getMemBufferCopyImpl() {#a8da8a8e7960a91583ad18b42ecbbadeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; WritableMemoryBuffer &gt; &gt; getMemBufferCopyImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BufferName)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4cb6ea02c3dec9abe04c03e501c60f75">llvm::WritableMemoryBuffer::getNewUninitMemBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baafdb5594dc3e484fc1bfd7c564d550c1">llvm::not_enough_memory</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a> and <a href="#aad17f4118ff721e4675c06f38373a7d1">getMemoryBufferForStream</a>.</p>

</div>
</div>

### getMemoryBufferForStream() {#aad17f4118ff721e4675c06f38373a7d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; WritableMemoryBuffer &gt; &gt; getMemoryBufferForStream (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> FD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BufferName)</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed898e74c946513975b0d7aad4d65e40">llvm::errorToErrorCode</a>, <a href="#a8da8a8e7960a91583ad18b42ecbbadeb">getMemBufferCopyImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a25241903dcf363fdf53dc9e8f1037e7a">llvm::sys::fs::readNativeFileToEOF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a76b193577aa67b1fac72cdbb5343241a">llvm::MemoryBuffer::getFileAsStream</a>, <a href="#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#ae56e946cf4266646c30b0898033b88bc">llvm::MemoryBuffer::getSTDIN</a>.</p>

</div>
</div>

### getOpenFileImpl() {#a7a23441815c1bba5006a34529e58aa86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MB&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MB &gt; &gt; getOpenFileImpl (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> FD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t FileSize, uint64_t MapSize, int64_t Offset, bool RequiresNullTerminator, bool IsVolatile, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &gt; Alignment)</td>
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



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca782f4defa0d88eb594062eda6a2fbdd1">llvm::sys::fs::block_file</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a0bf5f8e45bfccb0805b5e12d44622271">llvm::MutableArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a23489fd833f61022bf08dbe3ba9f1973">llvm::MutableArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed898e74c946513975b0d7aad4d65e40">llvm::errorToErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="#aad17f4118ff721e4675c06f38373a7d1">getMemoryBufferForStream</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4cb6ea02c3dec9abe04c03e501c60f75">llvm::WritableMemoryBuffer::getNewUninitMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a774becf3d10728695b270703bca011ec">llvm::sys::Process::getPageSizeEstimate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baafdb5594dc3e484fc1bfd7c564d550c1">llvm::not_enough_memory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5660354df7a84cb04d5ad682ca195bba">llvm::sys::fs::readNativeFileSlice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4676601564b208338edf7317182f473e">llvm::sys::fs::regular_file</a>, <a href="#a24d9351d1bd2c5f5169b0bbc856b1a52">shouldUseMmap</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a4b1e92bf20cb54acca62efdbfdebad54">getFileAux</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0163ef693f4fd640ec72a5fe74e5852c">llvm::MemoryBuffer::getOpenFile</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a4432e24dbd29bafd528e623c04c62395">llvm::MemoryBuffer::getOpenFileSlice</a>.</p>

</div>
</div>

### getReadWriteFile() {#a61ce38671d4f07799441a502041db0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; WriteThroughMemoryBuffer &gt; &gt; getReadWriteFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Filename, uint64_t FileSize, uint64_t MapSize, uint64_t Offset)</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca782f4defa0d88eb594062eda6a2fbdd1">llvm::sys::fs::block_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a93918b3a9b70253cd229fc5864884f58a028d2e48ae4e6c34d4a5bbb70438a936">llvm::sys::fs::CD_OpenExisting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed898e74c946513975b0d7aad4d65e40">llvm::errorToErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a9c6a326cce84918de3996872b97f59c6">llvm::sys::fs::openNativeFileForReadWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4676601564b208338edf7317182f473e">llvm::sys::fs::regular_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer/#a7db8b1f439ade71b1df3ce7c78a20d96">llvm::WriteThroughMemoryBuffer::getFile</a> and <a href="/web-llvm/docs/api/classes/llvm/writethroughmemorybuffer/#af123154a1169a76f1006090f357e0f83">llvm::WriteThroughMemoryBuffer::getFileSlice</a>.</p>

</div>
</div>

### shouldUseMmap() {#a24d9351d1bd2c5f5169b0bbc856b1a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldUseMmap (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> FD, size_t FileSize, size_t MapSize, off_t Offset, bool RequiresNullTerminator, int PageSize, bool IsVolatile)</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp">MemoryBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a>.</p>


<p>Referenced by <a href="#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
