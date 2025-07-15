---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/listeningsocket
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ListeningSocket` Class Reference

<p>Manages a passive (i.e., listening) UNIX domain socket. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ListeningSocket { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">llvm/Support/raw_socket_stream.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e7ab1ab38cc68f656ce8a425d536bf">ListeningSocket</a> (ListeningSocket &amp;&amp;LS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e74f90491fae9cdd0088d3f9718c561">ListeningSocket</a> (const ListeningSocket &amp;LS)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa35ac319fb45c790661ac10d5d1ca7">ListeningSocket</a> (int SocketFD, StringRef SocketPath, int PipeFD[2])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6af2845a3e2eacf99fe9a593660142">~ListeningSocket</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7b840e64fa22c48b1be27826bfe843">operator=</a> (const ListeningSocket &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682299af2a92a43ba340ce4a0ce736ba">shutdown</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Closes the FD, unlinks the socket file, and writes to PipeFD. <a href="#a682299af2a92a43ba340ce4a0ce736ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream">raw_socket_stream</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac080084a7f9f9a2d530621e41a309967">accept</a> (const std::chrono::milliseconds &amp;Timeout=std::chrono::milliseconds(-1))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accepts an incoming connection on the listening socket. <a href="#ac080084a7f9f9a2d530621e41a309967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558f10cb44ab6fee366ae1c7daa44e9f">FD</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe93f0a026bd14fb4a68e8dc0cf04b3d">SocketPath</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a6a79b58c1c9217b7d5f049ec67e478">PipeFD</a>[2]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a separate thread calls <a href="#a682299af2a92a43ba340ce4a0ce736ba">ListeningSocket::shutdown</a>, the <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> file descriptor (FD) could be closed while ::poll is waiting for it to be ready to perform a I/O operations. <a href="#a0a6a79b58c1c9217b7d5f049ec67e478">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22cd57e089541409aa05153237a44729">createUnix</a> (StringRef SocketPath, int MaxBacklog=llvm::hardware_concurrency().compute_thread_count())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a listening socket bound to the specified file system path. <a href="#a22cd57e089541409aa05153237a44729">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Manages a passive (i.e., listening) UNIX domain socket.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> class encapsulates a UNIX domain socket that can listen and accept incoming connections. <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> is portable and supports Windows builds begining with Insider Build 17063. <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> is designed for server-side operations, working alongside <span class="doxyComputerOutput">raw_socket_streams</span> that function as client connections.</p>


<p>Usage example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac10322dc19a928c2dbb83ec9689dc23caac70412e939d72a9234cdebb1af5867b">Path</a> = </span><span class="doxyHighlightStringLiteral">"/path/to/socket"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Expected&lt;ListeningSocket&gt; S = <a href="#a22cd57e089541409aa05153237a44729">ListeningSocket::createUnix</a>(Path);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (S) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  Expected&lt;std::unique_ptr&lt;raw_socket_stream&gt;&gt; connection = S-&gt;accept();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (connection) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Use the accepted raw_socket_stream for communication.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ListeningSocket() {#a00e7ab1ab38cc68f656ce8a425d536bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ListeningSocket::ListeningSocket (<a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> &amp;&amp; LS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load</a>.</p>

</div>
</div>

### ListeningSocket() {#a3e74f90491fae9cdd0088d3f9718c561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ListeningSocket::ListeningSocket (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> &amp; LS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ListeningSocket() {#a6aa35ac319fb45c790661ac10d5d1ca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ListeningSocket::ListeningSocket (int SocketFD, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SocketPath, int PipeFD=[2])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ListeningSocket() {#aab6af2845a3e2eacf99fe9a593660142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ListeningSocket::~ListeningSocket ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>Reference <a href="#a682299af2a92a43ba340ce4a0ce736ba">shutdown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a5e7b840e64fa22c48b1be27826bfe843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ListeningSocket &amp; llvm::ListeningSocket::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a00440f10281348fd9f7be52e23c7c874">llvm::hardware_concurrency</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accept() {#ac080084a7f9f9a2d530621e41a309967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; raw_socket_stream &gt; &gt; ListeningSocket::accept (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::chrono::milliseconds &amp; Timeout=std::chrono::milliseconds(-1))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accepts an incoming connection on the listening socket.</p>


<p>This method can optionally either block until a connection is available or timeout after a specified amount of time has passed. By default the method will block until the socket has recieved a connection. If the accept timesout this method will return std::errc:timed_out</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Timeout</td>
<td class="doxyParamItemDescription"><p>An optional timeout duration in milliseconds. Setting Timeout to a negative number causes <a href="#ac080084a7f9f9a2d530621e41a309967">accept</a> to block indefinitely</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>References <a href="#ac080084a7f9f9a2d530621e41a309967">accept</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp/#a962923a59c6a9e8ab55ec73dc320f68f">getLastSocketErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp/#ab48a833c4f2a5ebcee2b8abada3e0ac5">manageTimeout</a>.</p>


<p>Referenced by <a href="#ac080084a7f9f9a2d530621e41a309967">accept</a>.</p>

</div>
</div>

### shutdown() {#a682299af2a92a43ba340ce4a0ce736ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ListeningSocket::shutdown ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Closes the FD, unlinks the socket file, and writes to PipeFD.</p>


<p>After the construction of the <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a>, shutdown is signal safe if it is called during the lifetime of the object. shutdown can be called concurrently with <a href="#ac080084a7f9f9a2d530621e41a309967">ListeningSocket::accept</a> as writing to PipeFD will cause a blocking call to ::poll to return.</p>


<p>Once shutdown is called there is no way to reinitialize <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a>.</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>.</p>


<p>Referenced by <a href="#aab6af2845a3e2eacf99fe9a593660142">~ListeningSocket</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FD {#a558f10cb44ab6fee366ae1c7daa44e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;int&gt; llvm::ListeningSocket::FD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>.</p>

</div>
</div>

### PipeFD {#a0a6a79b58c1c9217b7d5f049ec67e478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ListeningSocket::PipeFD[2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a separate thread calls <a href="#a682299af2a92a43ba340ce4a0ce736ba">ListeningSocket::shutdown</a>, the <a href="/web-llvm/docs/api/classes/llvm/listeningsocket">ListeningSocket</a> file descriptor (FD) could be closed while ::poll is waiting for it to be ready to perform a I/O operations.</p>


<p>::poll will continue to block even after FD is closed so use a self-pipe mechanism to get ::poll to return</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>.</p>

</div>
</div>

### SocketPath {#afe93f0a026bd14fb4a68e8dc0cf04b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ListeningSocket::SocketPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createUnix() {#a22cd57e089541409aa05153237a44729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ListeningSocket &gt; ListeningSocket::createUnix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SocketPath, int MaxBacklog=<a href="/web-llvm/docs/api/namespaces/llvm/#a00440f10281348fd9f7be52e23c7c874">llvm::hardware_concurrency</a>().compute_thread_count())</td>
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

<p>Creates a listening socket bound to the specified file system path.</p>


<p>Handles the socket creation, binding, and immediately starts listening for incoming connections.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SocketPath</td>
<td class="doxyParamItemDescription"><p>The file system path where the socket will be created</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxBacklog</td>
<td class="doxyParamItemDescription"><p>The max number of connections in a socket's backlog</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-socket-stream-h">raw_socket_stream.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp">raw_socket_stream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a645a607ffcccb12f16a5736db991e7d9">llvm::sys::fs::exists</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp/#a962923a59c6a9e8ab55ec73dc320f68f">getLastSocketErrorCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp/#a01d53f471176148059cb8cd09dffe690">getSocketFD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-socket-stream-cpp/#ac93e3301780b206d83d8a7c768ce4992">setSocketAddr</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
