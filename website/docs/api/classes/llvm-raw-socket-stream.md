---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/raw-socket-stream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `raw_socket_stream` Class



## Declaration

<div class="doxyDeclaration">
class llvm::raw_socket_stream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">llvm/Support/raw_socket_stream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> of a file for reading/writing/seeking. <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d8427648f496899f5aeb5e92ea6e81">raw_socket_stream</a> (int SocketFD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe1405099d634d6a8fa75d0ad84fe9f1">~raw_socket_stream</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22cc7ec55d3e7b68bf83856ed991f0e">read</a> (char *Ptr, size_t Size, const std::chrono::milliseconds &amp;Timeout=std::chrono::milliseconds(-1))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to read from the <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream">raw_socket_stream</a>'s file descriptor. <a href="#af22cc7ec55d3e7b68bf83856ed991f0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a775e18db984168cf5083d77d4e484c27">current_pos</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current position within the stream, not counting the bytes currently in the buffer. <a href="#a775e18db984168cf5083d77d4e484c27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream">raw_socket_stream</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15311330f8fe55f5a39073ea9eab65a3">createConnectedUnix</a> (StringRef SocketPath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream">raw_socket_stream</a></span> connected to the UNIX domain socket at <span class="doxyComputerOutput">SocketPath</span>. <a href="#a15311330f8fe55f5a39073ea9eab65a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### raw\_socket\_stream() {#a86d8427648f496899f5aeb5e92ea6e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_socket_stream::raw_socket_stream (int SocketFD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#ac9a76e6fdfee784d51393f12ce7c5256">llvm::raw_fd_stream::raw_fd_stream</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~raw\_socket\_stream() {#abe1405099d634d6a8fa75d0ad84fe9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_socket_stream::~raw_socket_stream ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### read() {#af22cc7ec55d3e7b68bf83856ed991f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ssize_t raw_socket_stream::read (char * Ptr, size_t Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::chrono::milliseconds &amp; Timeout=std::chrono::milliseconds(-1))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to read from the <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream">raw_socket_stream</a>'s file descriptor.</p>


<p>This method can optionally either block until data is read or an error has occurred or timeout after a specified amount of time has passed. By default the method will block until the socket has read data or encountered an error. If the read times out this method will return std::errc:timed_out</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ptr</td>
<td class="doxyParamItemDescription"><p>The start of the buffer that will hold any read data</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>The number of bytes to be read</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Timeout</td>
<td class="doxyParamItemDescription"><p>An optional timeout duration in milliseconds</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#af96ea3efa5212f54e22e5d5d01cf029c">llvm::raw_fd_ostream::error_detected</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#ad429e128376a6912c6074e6c59dab97e">llvm::raw_fd_ostream::get_fd</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp/#ab48a833c4f2a5ebcee2b8abada3e0ac5">manageTimeout</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#af64d05ca7d5c140c9a967027408c93a8">llvm::raw_fd_stream::read</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### current\_pos() {#a775e18db984168cf5083d77d4e484c27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::raw_socket_stream::current_pos ()</td>
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

<p>Return the current position within the stream, not counting the bytes currently in the buffer.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createConnectedUnix() {#a15311330f8fe55f5a39073ea9eab65a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; raw_socket_stream &gt; &gt; raw_socket_stream::createConnectedUnix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SocketPath)</td>
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

<p>Create a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream">raw_socket_stream</a></span> connected to the UNIX domain socket at <span class="doxyComputerOutput">SocketPath</span>.</p>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp/#a01d53f471176148059cb8cd09dffe690">getSocketFD</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
