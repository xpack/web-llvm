---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/raw-fd-stream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `raw_fd_stream` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> of a file for reading/writing/seeking. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::raw_fd_stream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to a file descriptor. <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream">raw_socket_stream</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a76e6fdfee784d51393f12ce7c5256">raw_fd_stream</a> (StringRef Filename, std::error_code &amp;EC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified file for reading/writing/seeking. <a href="#ac9a76e6fdfee784d51393f12ce7c5256">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f27b402c83b3bd64d4b0c6ba2e798c">raw_fd_stream</a> (int fd, bool shouldClose)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ssize_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64d05ca7d5c140c9a967027408c93a8">read</a> (char *Ptr, size_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This reads the <span class="doxyComputerOutput">Size</span> bytes into a buffer pointed by <span class="doxyComputerOutput">Ptr</span>. <a href="#af64d05ca7d5c140c9a967027408c93a8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac10c45dc61a1a5df36766b16d1f8e9b9">classof</a> (const raw_ostream *OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">OS</span> is a pointer of type raw_fd_stream*. <a href="#ac10c45dc61a1a5df36766b16d1f8e9b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> of a file for reading/writing/seeking.</p>

<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### raw\_fd\_stream() {#ac9a76e6fdfee784d51393f12ce7c5256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_stream::raw_fd_stream (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::error_code &amp; EC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Open the specified file for reading/writing/seeking.</p>


<p>If an error occurs, information about the error is put into EC, and the stream should be immediately destroyed.</p>


<p>Declaration at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp/#a2ef27606df20d46db5a3b4f58604ccba">getFD</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a98031dbf79580cd3975105f7397b9712">llvm::raw_fd_ostream::isRegularFile</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43a8dfae711fb29865c49b78c8ea1a6f782">llvm::raw_ostream::OK_FDStream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#af5462bc0fe5a61eccc662708da280e64">llvm::raw_fd_ostream::raw_fd_ostream</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream/#a86d8427648f496899f5aeb5e92ea6e81">llvm::raw_socket_stream::raw_socket_stream</a>.</p>

</div>
</div>

### raw\_fd\_stream() {#a26f27b402c83b3bd64d4b0c6ba2e798c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_stream::raw_fd_stream (int fd, bool shouldClose)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43a8dfae711fb29865c49b78c8ea1a6f782">llvm::raw_ostream::OK_FDStream</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#af5462bc0fe5a61eccc662708da280e64">llvm::raw_fd_ostream::raw_fd_ostream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### read() {#af64d05ca7d5c140c9a967027408c93a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ssize_t raw_fd_stream::read (char * Ptr, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This reads the <span class="doxyComputerOutput">Size</span> bytes into a buffer pointed by <span class="doxyComputerOutput">Ptr</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ptr</td>
<td class="doxyParamItemDescription"><p>The start of the buffer to hold data to be read.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>The number of bytes to be read.</p></td>
</tr>
</table>
</dd>
</dl>

<p>On success, the number of bytes read is returned, and the file position is advanced by this number. On error, -1 is returned, use <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error()</a> to get the error code.</p>


<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae075c94db10b09d6d5876d32219eaf0d">llvm::errnoAsErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#af96ea3efa5212f54e22e5d5d01cf029c">llvm::raw_fd_ostream::error_detected</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#ad429e128376a6912c6074e6c59dab97e">llvm::raw_fd_ostream::get_fd</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a45c7da9b34cb308a76ace46770cf9a82">llvm::raw_fd_ostream::inc_pos</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#af64d05ca7d5c140c9a967027408c93a8">read</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#af64d05ca7d5c140c9a967027408c93a8">read</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream/#af22cc7ec55d3e7b68bf83856ed991f0e">llvm::raw_socket_stream::read</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ac10c45dc61a1a5df36766b16d1f8e9b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool raw_fd_stream::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * OS)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">OS</span> is a pointer of type raw_fd_stream*.</p>

<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#af3aec1d6c89f3eed88579d13ade51ea0">llvm::raw_ostream::get_kind</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43a8dfae711fb29865c49b78c8ea1a6f782">llvm::raw_ostream::OK_FDStream</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
