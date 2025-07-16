---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/fileoutputbuffer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `FileOutputBuffer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileoutputbuffer-h">llvm/Support/FileOutputBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memory-h">llvm/Support/Memory.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timeprofiler-h">llvm/Support/TimeProfiler.h</a>"
#include &lt;system_error&gt;
#include &lt;unistd.h&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-fileoutputbuffer-cpp-">anonymous{FileOutputBuffer.cpp}</a></td>
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

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; InMemoryBuffer &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab567e593dcf755d782527311e9b300fa">createInMemoryBuffer</a> (StringRef Path, size_t Size, unsigned Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer">FileOutputBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b5a8b8b08e1fc483335974755720ed">createOnDiskBuffer</a> (StringRef Path, size_t Size, unsigned Mode)</td>
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

## Functions

### createInMemoryBuffer() {#ab567e593dcf755d782527311e9b300fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; InMemoryBuffer &gt; &gt; createInMemoryBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, size_t Size, unsigned Mode)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a1326dd13b23711e68ade413fbc57b9f6">llvm::sys::Memory::allocateMappedMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a548f317b89dc0bba738b89e5ce791395a02cae455b05abf1bfb1de69095e66417">llvm::sys::Memory::MF_READ</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/memory/#a548f317b89dc0bba738b89e5ce791395a83e34a8267f7acd88563e9d5a3ee7c25">llvm::sys::Memory::MF_WRITE</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a3a10ce8cad8fee5d6a4c55270866aa05">llvm::FileOutputBuffer::create</a> and <a href="#a31b5a8b8b08e1fc483335974755720ed">createOnDiskBuffer</a>.</p>

</div>
</div>

### createOnDiskBuffer() {#a31b5a8b8b08e1fc483335974755720ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; FileOutputBuffer &gt; &gt; createOnDiskBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, size_t Size, unsigned Mode)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp">FileOutputBuffer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac90e775833cd4fd0da26c96bfa8f2f06">llvm::sys::fs::convertFDToNativeFile</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/tempfile/#ad1d2e9ae2eb5ea7e7b60f8bcb715b2e9">llvm::sys::fs::TempFile::create</a>, <a href="#ab567e593dcf755d782527311e9b300fa">createInMemoryBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region/#a7d087bce12e64c2578f57ca0e1884919afbac192dfef7b435728686ff9f82dad5">llvm::sys::fs::mapped_file_region::readwrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a432aad8e94857a0e03a0b8dfb9447fe0">llvm::sys::fs::resize_file_before_mapping_readwrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a3a10ce8cad8fee5d6a4c55270866aa05">llvm::FileOutputBuffer::create</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
