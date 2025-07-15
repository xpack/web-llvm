---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/raw-socket-stream-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `raw_socket_stream.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">llvm/Support/raw_socket_stream.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include &lt;atomic&gt;
#include &lt;fcntl.h&gt;
#include &lt;functional&gt;
#include &lt;poll.h&gt;
#include &lt;sys/socket.h&gt;
#include &lt;sys/un.h&gt;
#include &lt;unistd.h&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a962923a59c6a9e8ab55ec73dc320f68f">getLastSocketErrorCode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static sockaddr_un</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93e3301780b206d83d8a7c768ce4992">setSocketAddr</a> (StringRef SocketPath)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d53f471176148059cb8cd09dffe690">getSocketFD</a> (StringRef SocketPath)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab48a833c4f2a5ebcee2b8abada3e0ac5">manageTimeout</a> (const std::chrono::milliseconds &amp;Timeout, const std::function&lt; int()&gt; &amp;getActiveFD, const std::optional&lt; int &gt; &amp;CancelFD=std::nullopt)</td>
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

### getLastSocketErrorCode() {#a962923a59c6a9e8ab55ec73dc320f68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code getLastSocketErrorCode ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae075c94db10b09d6d5876d32219eaf0d">llvm::errnoAsErrorCode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/listeningsocket/#ac080084a7f9f9a2d530621e41a309967">llvm::ListeningSocket::accept</a>, <a href="/web-llvm/docs/api/classes/llvm/listeningsocket/#a22cd57e089541409aa05153237a44729">llvm::ListeningSocket::createUnix</a>, <a href="#a01d53f471176148059cb8cd09dffe690">getSocketFD</a> and <a href="#ab48a833c4f2a5ebcee2b8abada3e0ac5">manageTimeout</a>.</p>

</div>
</div>

### getSocketFD() {#a01d53f471176148059cb8cd09dffe690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int &gt; getSocketFD (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SocketPath)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>References <a href="#a962923a59c6a9e8ab55ec73dc320f68f">getLastSocketErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="#ac93e3301780b206d83d8a7c768ce4992">setSocketAddr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream/#a15311330f8fe55f5a39073ea9eab65a3">llvm::raw_socket_stream::createConnectedUnix</a> and <a href="/web-llvm/docs/api/classes/llvm/listeningsocket/#a22cd57e089541409aa05153237a44729">llvm::ListeningSocket::createUnix</a>.</p>

</div>
</div>

### manageTimeout() {#ab48a833c4f2a5ebcee2b8abada3e0ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code manageTimeout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::chrono::milliseconds &amp; Timeout, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; int()&gt; &amp; getActiveFD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; int &gt; &amp; CancelFD=std::nullopt)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>Reference <a href="#a962923a59c6a9e8ab55ec73dc320f68f">getLastSocketErrorCode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/listeningsocket/#ac080084a7f9f9a2d530621e41a309967">llvm::ListeningSocket::accept</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream/#af22cc7ec55d3e7b68bf83856ed991f0e">llvm::raw_socket_stream::read</a>.</p>

</div>
</div>

### setSocketAddr() {#ac93e3301780b206d83d8a7c768ce4992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sockaddr_un setSocketAddr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SocketPath)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/listeningsocket/#a22cd57e089541409aa05153237a44729">llvm::ListeningSocket::createUnix</a> and <a href="#a01d53f471176148059cb8cd09dffe690">getSocketFD</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
