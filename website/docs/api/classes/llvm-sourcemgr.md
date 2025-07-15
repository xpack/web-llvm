---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sourcemgr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SourceMgr` Class Reference

<p>This owns the files read by a parser, handles include stacks, and handles diagnostic wrangling. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SourceMgr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf78be89ec851a45f37a776a5a58bfe8">DiagHandlerTy</a> = void(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp;, void *Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clients that want to handle their own diagnostics in a custom way can register a function pointer+context as a diagnostic handler. <a href="#acf78be89ec851a45f37a776a5a58bfe8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DiagKind { <a href="#a346262ff27e71aff626fe6548ef8a777">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832a884d4405c7a6640c36e2f6497708">SourceMgr</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee27450833a4616b24ed4646141073f">SourceMgr</a> (const SourceMgr &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c44b700923a396138319d1b298d53a6">SourceMgr</a> (SourceMgr &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8954d61a9cd561f541c84c150f5fc5b6">~SourceMgr</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389537f7afe774704e6ffa69d122f274">operator=</a> (const SourceMgr &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10196833265cc9d121e23cb1a3b3b0b8">operator=</a> (SourceMgr &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d00e16a69c913f50f7e6b1f4a23d056">getIncludeDirs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the include directories of this source manager. <a href="#a1d00e16a69c913f50f7e6b1f4a23d056">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4623f407b4e8c9d13883dc50bf6cd9ae">setIncludeDirs</a> (const std::vector&lt; std::string &gt; &amp;Dirs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad324bef18696e3fcd110ffb2d33a2b58">setDiagHandler</a> (DiagHandlerTy DH, void *Ctx=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify a diagnostic handler to be invoked every time PrintMessage is called. <a href="#ad324bef18696e3fcd110ffb2d33a2b58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acf78be89ec851a45f37a776a5a58bfe8">DiagHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25349c8e3db02cc6c6984dd1b2f56978">getDiagHandler</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a459669ba9af7d72ba179fbd8e6a240">getDiagContext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SrcBuffer &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff646a871ca58ccd8d16633b7b88eaaf">getBufferInfo</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56740d2dab215f8642e6acf4ff49c62d">getMemoryBuffer</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d21b555e4cfc2a1be47148889ef48b8">getNumBuffers</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a208a36067279ac9669eb29f34ae9daed">getMainFileID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63fc7559491478903a3d4d365de5da36">getParentIncludeLoc</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe70aa1105a855036bdeb6426cac27db">AddNewSourceBuffer</a> (std::unique_ptr&lt; MemoryBuffer &gt; F, SMLoc IncludeLoc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new source buffer to this source manager. <a href="#afe70aa1105a855036bdeb6426cac27db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c533e5b4fb98dcc0fbf4df792aaf96">takeSourceBuffersFrom</a> (SourceMgr &amp;SrcMgr, SMLoc MainBufferIncludeLoc=SMLoc())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Takes the source buffers from the given source manager and append them to the current manager. <a href="#af9c533e5b4fb98dcc0fbf4df792aaf96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade78f93269ac7fa03b8ed1806262443d">AddIncludeFile</a> (const std::string &amp;Filename, SMLoc IncludeLoc, std::string &amp;IncludedFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for a file with the specified name in the current directory or in one of the IncludeDirs. <a href="#ade78f93269ac7fa03b8ed1806262443d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8517e1b412dcd4f30cdce1c9541cc9">OpenIncludeFile</a> (const std::string &amp;Filename, std::string &amp;IncludedFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for a file with the specified name in the current directory or in one of the IncludeDirs, and try to open it <b>without</b> adding to the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a>. <a href="#a0c8517e1b412dcd4f30cdce1c9541cc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757ccf4ae54f435c3828c704ca65798e">FindBufferContainingLoc</a> (SMLoc Loc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the buffer containing the specified location. <a href="#a757ccf4ae54f435c3828c704ca65798e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84919a22333087fc39465b1826a8208">FindLineNumber</a> (SMLoc Loc, unsigned BufferID=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the line number for the specified location in the specified file. <a href="#af84919a22333087fc39465b1826a8208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494d75fe0bc43f9c6b8821f983205649">getLineAndColumn</a> (SMLoc Loc, unsigned BufferID=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the line and column number for the specified location in the specified file. <a href="#a494d75fe0bc43f9c6b8821f983205649">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8ebf8281d0ee499c10e259b917e4b1a">getFormattedLocationNoOffset</a> (SMLoc Loc, bool IncludePath=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a string with the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></span> filename and line number formatted in the standard style. <a href="#af8ebf8281d0ee499c10e259b917e4b1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3380c7e96d28b108876d8e7b66e341">FindLocForLineAndColumn</a> (unsigned BufferID, unsigned LineNo, unsigned ColNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a line and column number in a mapped buffer, turn it into an <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>. <a href="#aff3380c7e96d28b108876d8e7b66e341">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb499d84f3af1286e8d508a760aa396">PrintMessage</a> (raw_ostream &amp;OS, SMLoc Loc, DiagKind Kind, const Twine &amp;Msg, ArrayRef&lt; SMRange &gt; Ranges={}, ArrayRef&lt; SMFixIt &gt; FixIts={}, bool ShowColors=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a message about the specified location with the specified string. <a href="#a5fb499d84f3af1286e8d508a760aa396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd60e3f6be5b0af5c3b08eb81c9a7aed">PrintMessage</a> (SMLoc Loc, DiagKind Kind, const Twine &amp;Msg, ArrayRef&lt; SMRange &gt; Ranges={}, ArrayRef&lt; SMFixIt &gt; FixIts={}, bool ShowColors=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a diagnostic to <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs()</a>. <a href="#abd60e3f6be5b0af5c3b08eb81c9a7aed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a042b7e85ad239f80f6a079283a9faee6">PrintMessage</a> (raw_ostream &amp;OS, const SMDiagnostic &amp;Diagnostic, bool ShowColors=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits a manually-constructed diagnostic to the given output stream. <a href="#a042b7e85ad239f80f6a079283a9faee6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf08ebc749ce91001ea768a16da0605">GetMessage</a> (SMLoc Loc, DiagKind Kind, const Twine &amp;Msg, ArrayRef&lt; SMRange &gt; Ranges={}, ArrayRef&lt; SMFixIt &gt; FixIts={}) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> at the specified location with the specified string. <a href="#acdf08ebc749ce91001ea768a16da0605">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700008f59fc3d0ac675878b0432b59e4">PrintIncludeStack</a> (SMLoc IncludeLoc, raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints the names of included files and the line of the file they were included from. <a href="#a700008f59fc3d0ac675878b0432b59e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201d6394a54bc3a9b7f9d6c0f0bb3757">isValidBufferID</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; SrcBuffer &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953b5aaaa8ba761726dda1530996d7fc">Buffers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is all of the buffers that we are reading from. <a href="#a953b5aaaa8ba761726dda1530996d7fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327607e571184c8cc980373deba24baf">IncludeDirectories</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acf78be89ec851a45f37a776a5a58bfe8">DiagHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9292998b7687dd2cbef425121708f056">DiagHandler</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac12c71999dbc4fe3a959eda864316782">DiagContext</a> = nullptr</td>
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

<p>This owns the files read by a parser, handles include stacks, and handles diagnostic wrangling.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DiagHandlerTy {#acf78be89ec851a45f37a776a5a58bfe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SourceMgr::DiagHandlerTy =  void (*)(const SMDiagnostic &amp;, void *Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clients that want to handle their own diagnostics in a custom way can register a function pointer+context as a diagnostic handler.</p>


<p>It gets called each time PrintMessage is invoked.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DiagKind {#a346262ff27e71aff626fe6548ef8a777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SourceMgr::DiagKind </td>
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
<td class="doxyEnumItemName">DK_Error<a id="a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_Warning<a id="a346262ff27e71aff626fe6548ef8a777a6bcc8ac9374461ed0599334db63365d0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_Remark<a id="a346262ff27e71aff626fe6548ef8a777ae5a15719ab746bdc7713c4784fc1c6ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DK_Note<a id="a346262ff27e71aff626fe6548ef8a777ad5935d1ea3df60ee7ba90b8e23fa6b42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SourceMgr() {#a832a884d4405c7a6640c36e2f6497708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SourceMgr::SourceMgr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="#a389537f7afe774704e6ffa69d122f274">operator=</a>, <a href="#a10196833265cc9d121e23cb1a3b3b0b8">operator=</a>, <a href="#aeee27450833a4616b24ed4646141073f">SourceMgr</a>, <a href="#a1c44b700923a396138319d1b298d53a6">SourceMgr</a> and <a href="#af9c533e5b4fb98dcc0fbf4df792aaf96">takeSourceBuffersFrom</a>.</p>

</div>
</div>

### SourceMgr() {#aeee27450833a4616b24ed4646141073f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SourceMgr::SourceMgr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="#a832a884d4405c7a6640c36e2f6497708">SourceMgr</a>.</p>

</div>
</div>

### SourceMgr() {#a1c44b700923a396138319d1b298d53a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SourceMgr::SourceMgr (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="#a832a884d4405c7a6640c36e2f6497708">SourceMgr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SourceMgr() {#a8954d61a9cd561f541c84c150f5fc5b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SourceMgr::~SourceMgr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a389537f7afe774704e6ffa69d122f274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr &amp; llvm::SourceMgr::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="#a832a884d4405c7a6640c36e2f6497708">SourceMgr</a>.</p>

</div>
</div>

### operator=() {#a10196833265cc9d121e23cb1a3b3b0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr &amp; llvm::SourceMgr::operator= (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="#a832a884d4405c7a6640c36e2f6497708">SourceMgr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddIncludeFile() {#ade78f93269ac7fa03b8ed1806262443d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SourceMgr::AddIncludeFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Filename, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IncludeLoc, std::string &amp; IncludedFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for a file with the specified name in the current directory or in one of the IncludeDirs.</p>


<p>If no file is found, this returns 0, otherwise it returns the buffer <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the stacked file. The full path to the included file can be found in <span class="doxyComputerOutput">IncludedFile</span>.</p>


<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="#afe70aa1105a855036bdeb6426cac27db">AddNewSourceBuffer</a> and <a href="#a0c8517e1b412dcd4f30cdce1c9541cc9">OpenIncludeFile</a>.</p>

</div>
</div>

### AddNewSourceBuffer() {#afe70aa1105a855036bdeb6426cac27db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SourceMgr::AddNewSourceBuffer (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; F, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IncludeLoc)</td>
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

<p>Add a new source buffer to this source manager.</p>


<p>This takes ownership of the memory buffer.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#ade78f93269ac7fa03b8ed1806262443d">AddIncludeFile</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#a982f596dc670886cba9172ea00cb7a48">parseAssemblyInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf2c472d771169c6100c6302079309da">llvm::parseConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a693d5398216b0ca25097c2bde8fe6284">llvm::parseDIExpressionBodyAtBeginning</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp/#a3f2868a82e652c99a57c4dd99683af87">parseSummaryIndexAssemblyInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add17c7296500b889d12eb44d547a59ba">llvm::parseType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35d32e57764638fe887f59392490e49c">llvm::parseTypeAtBeginning</a> and <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>.</p>

</div>
</div>

### FindBufferContainingLoc() {#a757ccf4ae54f435c3828c704ca65798e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SourceMgr::FindBufferContainingLoc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the buffer containing the specified location.</p>


<p>0 is returned if the buffer is not found.</p>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>Referenced by <a href="#af8ebf8281d0ee499c10e259b917e4b1a">getFormattedLocationNoOffset</a>, <a href="#a494d75fe0bc43f9c6b8821f983205649">getLineAndColumn</a>, <a href="#acdf08ebc749ce91001ea768a16da0605">GetMessage</a>, <a href="#a700008f59fc3d0ac675878b0432b59e4">PrintIncludeStack</a> and <a href="#a042b7e85ad239f80f6a079283a9faee6">PrintMessage</a>.</p>

</div>
</div>

### FindLineNumber() {#af84919a22333087fc39465b1826a8208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SourceMgr::FindLineNumber (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned BufferID=0)</td>
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

<p>Find the line number for the specified location in the specified file.</p>


<p>This is not a fast method.</p>


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="#a494d75fe0bc43f9c6b8821f983205649">getLineAndColumn</a>.</p>


<p>Referenced by <a href="#af8ebf8281d0ee499c10e259b917e4b1a">getFormattedLocationNoOffset</a> and <a href="#a700008f59fc3d0ac675878b0432b59e4">PrintIncludeStack</a>.</p>

</div>
</div>

### FindLocForLineAndColumn() {#aff3380c7e96d28b108876d8e7b66e341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc SourceMgr::FindLocForLineAndColumn (unsigned BufferID, unsigned LineNo, unsigned ColNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a line and column number in a mapped buffer, turn it into an <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>.</p>


<p>This will return a null <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> if the line/column location is invalid.</p>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="#aff646a871ca58ccd8d16633b7b88eaaf">getBufferInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getBufferInfo() {#aff646a871ca58ccd8d16633b7b88eaaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SrcBuffer &amp; llvm::SourceMgr::getBufferInfo (unsigned i)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#aff3380c7e96d28b108876d8e7b66e341">FindLocForLineAndColumn</a>, <a href="#af8ebf8281d0ee499c10e259b917e4b1a">getFormattedLocationNoOffset</a>, <a href="#a494d75fe0bc43f9c6b8821f983205649">getLineAndColumn</a>, <a href="#a700008f59fc3d0ac675878b0432b59e4">PrintIncludeStack</a> and <a href="#a042b7e85ad239f80f6a079283a9faee6">PrintMessage</a>.</p>

</div>
</div>

### getDiagContext() {#a1a459669ba9af7d72ba179fbd8e6a240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::SourceMgr::getDiagContext ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af5bd59cf74666a7da28269e983745b04">llvm::TableGenParseFile</a> and <a href="/web-llvm/docs/api/classes/llvm/remarks/yamlparseerror/#aee75e19211cebf7bf53859a98bd5ac61">llvm::remarks::YAMLParseError::YAMLParseError</a>.</p>

</div>
</div>

### getDiagHandler() {#a25349c8e3db02cc6c6984dd1b2f56978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagHandlerTy llvm::SourceMgr::getDiagHandler ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af5bd59cf74666a7da28269e983745b04">llvm::TableGenParseFile</a> and <a href="/web-llvm/docs/api/classes/llvm/remarks/yamlparseerror/#aee75e19211cebf7bf53859a98bd5ac61">llvm::remarks::YAMLParseError::YAMLParseError</a>.</p>

</div>
</div>

### getFormattedLocationNoOffset() {#af8ebf8281d0ee499c10e259b917e4b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string SourceMgr::getFormattedLocationNoOffset (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, bool IncludePath=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a string with the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></span> filename and line number formatted in the standard style.</p>


<p>Get a string with the source location formatted in the standard style, but without the line offset.</p>


<p>If <span class="doxyComputerOutput">IncludePath</span> is true, the path is included. If false, only the file name and extension are included.</p>


<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a757ccf4ae54f435c3828c704ca65798e">FindBufferContainingLoc</a>, <a href="#af84919a22333087fc39465b1826a8208">FindLineNumber</a>, <a href="#aff646a871ca58ccd8d16633b7b88eaaf">getBufferInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getIncludeDirs() {#a1d00e16a69c913f50f7e6b1f4a23d056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::string &gt; llvm::SourceMgr::getIncludeDirs ()</td>
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

<p>Return the include directories of this source manager.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af5bd59cf74666a7da28269e983745b04">llvm::TableGenParseFile</a>.</p>

</div>
</div>

### getLineAndColumn() {#a494d75fe0bc43f9c6b8821f983205649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; SourceMgr::getLineAndColumn (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, unsigned BufferID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the line and column number for the specified location in the specified file.</p>


<p>This is not a fast method.</p>


<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7a7c222449f3208a532168c90bfb654d">llvm::StringRef::find_last_of</a>, <a href="#a757ccf4ae54f435c3828c704ca65798e">FindBufferContainingLoc</a>, <a href="#aff646a871ca58ccd8d16633b7b88eaaf">getBufferInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/filecheckdiag/#a61b7d723c27bc645be803cb48a7f103f">llvm::FileCheckDiag::FileCheckDiag</a>, <a href="#af84919a22333087fc39465b1826a8208">FindLineNumber</a> and <a href="#acdf08ebc749ce91001ea768a16da0605">GetMessage</a>.</p>

</div>
</div>

### getMainFileID() {#a208a36067279ac9669eb29f34ae9daed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SourceMgr::getMainFileID ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5d21b555e4cfc2a1be47148889ef48b8">getNumBuffers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d46d39efe0be42a72faf3e6db59de3f">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### getMemoryBuffer() {#a56740d2dab215f8642e6acf4ff49c62d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemoryBuffer * llvm::SourceMgr::getMemoryBuffer (unsigned i)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d46d39efe0be42a72faf3e6db59de3f">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="#acdf08ebc749ce91001ea768a16da0605">GetMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

### GetMessage() {#acdf08ebc749ce91001ea768a16da0605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMDiagnostic SourceMgr::GetMessage (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="#a346262ff27e71aff626fe6548ef8a777">DiagKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &gt; Ranges={}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smfixit">SMFixIt</a> &gt; FixIts={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> at the specified location with the specified string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Msg</td>
<td class="doxyParamItemDescription"><p>If non-null, the kind of message (e.g., "error") which is prefixed to the message.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a757ccf4ae54f435c3828c704ca65798e">FindBufferContainingLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#ae4604d3bedbb15e6c516f9357d3b773e">llvm::MemoryBuffer::getBufferEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a2037f11968aa30bfda0b4de9f335624d">llvm::MemoryBuffer::getBufferIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#af1972b9a0324e0311ad641eac2de2b7f">llvm::MemoryBuffer::getBufferStart</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="#a494d75fe0bc43f9c6b8821f983205649">getLineAndColumn</a>, <a href="#a56740d2dab215f8642e6acf4ff49c62d">getMemoryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d46d39efe0be42a72faf3e6db59de3f">anonymous{MIParser.cpp}::MIParser::error</a>, <a href="/web-llvm/docs/api/classes/llvm/errordiagnostic/#afd2d10db0e8822de9860636d612a13af">llvm::ErrorDiagnostic::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add17c7296500b889d12eb44d547a59ba">llvm::parseType</a>, <a href="#a5fb499d84f3af1286e8d508a760aa396">PrintMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aac3107671801e6bb16ef896f382759cd">llvm::MCContext::reportError</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a99057f5cbc5ee5f973d463d4c30abe7d">llvm::MCContext::reportWarning</a>.</p>

</div>
</div>

### getNumBuffers() {#a5d21b555e4cfc2a1be47148889ef48b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SourceMgr::getNumBuffers ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="#a208a36067279ac9669eb29f34ae9daed">getMainFileID</a> and <a href="#af9c533e5b4fb98dcc0fbf4df792aaf96">takeSourceBuffersFrom</a>.</p>

</div>
</div>

### getParentIncludeLoc() {#a63fc7559491478903a3d4d365de5da36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::SourceMgr::getParentIncludeLoc (unsigned i)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### OpenIncludeFile() {#a0c8517e1b412dcd4f30cdce1c9541cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; SourceMgr::OpenIncludeFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Filename, std::string &amp; IncludedFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for a file with the specified name in the current directory or in one of the IncludeDirs, and try to open it <b>without</b> adding to the <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a>.</p>


<p>If the opened file is intended to be added to the source manager, prefer <span class="doxyComputerOutput">AddIncludeFile</span> instead.</p>


<p>If no file is found, this returns an <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>, otherwise it returns the buffer of the stacked file. The full path to the included file can be found in <span class="doxyComputerOutput">IncludedFile</span>.</p>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>.</p>


<p>Referenced by <a href="#ade78f93269ac7fa03b8ed1806262443d">AddIncludeFile</a>.</p>

</div>
</div>

### PrintIncludeStack() {#a700008f59fc3d0ac675878b0432b59e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SourceMgr::PrintIncludeStack (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IncludeLoc, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prints the names of included files and the line of the file they were included from.</p>


<p>A diagnostic handler can use this before printing its custom formatted message.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IncludeLoc</td>
<td class="doxyParamItemDescription"><p>The location of the include.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>the <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> to print on.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a757ccf4ae54f435c3828c704ca65798e">FindBufferContainingLoc</a>, <a href="#af84919a22333087fc39465b1826a8208">FindLineNumber</a>, <a href="#aff646a871ca58ccd8d16633b7b88eaaf">getBufferInfo</a> and <a href="#a700008f59fc3d0ac675878b0432b59e4">PrintIncludeStack</a>.</p>


<p>Referenced by <a href="#a700008f59fc3d0ac675878b0432b59e4">PrintIncludeStack</a> and <a href="#a042b7e85ad239f80f6a079283a9faee6">PrintMessage</a>.</p>

</div>
</div>

### PrintMessage() {#a5fb499d84f3af1286e8d508a760aa396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SourceMgr::PrintMessage (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="#a346262ff27e71aff626fe6548ef8a777">DiagKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &gt; Ranges={}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smfixit">SMFixIt</a> &gt; FixIts={}, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a message about the specified location with the specified string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ShowColors</td>
<td class="doxyParamItemDescription"><p>Display colored messages if output is a terminal and the default error handler is used.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="#acdf08ebc749ce91001ea768a16da0605">GetMessage</a> and <a href="#a5fb499d84f3af1286e8d508a760aa396">PrintMessage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#ac71c43fb658be4df9989f55be8447e1d">llvm::FileCheckString::CheckDag</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a36305f86aafd6d41b0c449eac6476efd">llvm::FileCheckString::CheckNext</a>, <a href="/web-llvm/docs/api/structs/llvm/filecheckstring/#a82944774d532e6adc41c92e29a00e2e9">llvm::FileCheckString::CheckSame</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9f274211d8e2baf7f13ec1e030e09de6">llvm::vfs::RedirectingFileSystem::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa660e7b419602632507f83ec8a1520aa">llvm::MCObjectStreamer::emitFill</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#ae173fad50624dec05877e86be7b7e429">llvm::Pattern::parsePattern</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3331028c9eef66f4022ac3efa310af7d">llvm::Pattern::printFuzzyMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#adadd7e41a96b9e407d8e07cb45a0d6e2">printMatch</a>, <a href="#a5fb499d84f3af1286e8d508a760aa396">PrintMessage</a>, <a href="#abd60e3f6be5b0af5c3b08eb81c9a7aed">PrintMessage</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5d394830d4143542278afee43f527b48">printNoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3a4e8a88439506522a2a0f3850802d3f">llvm::Pattern::printSubstitutions</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a91f729b936911342abb6b606e0606cdc">llvm::Pattern::printVariableDefs</a> and <a href="/web-llvm/docs/api/classes/llvm/filecheck/#a20fa01b6cdae5b207cf5dcdda4fced04">llvm::FileCheck::readCheckFile</a>.</p>

</div>
</div>

### PrintMessage() {#abd60e3f6be5b0af5c3b08eb81c9a7aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SourceMgr::PrintMessage (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, <a href="#a346262ff27e71aff626fe6548ef8a777">DiagKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &gt; Ranges={}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smfixit">SMFixIt</a> &gt; FixIts={}, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits a diagnostic to <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs()</a>.</p>

<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="#a5fb499d84f3af1286e8d508a760aa396">PrintMessage</a>.</p>

</div>
</div>

### PrintMessage() {#a042b7e85ad239f80f6a079283a9faee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SourceMgr::PrintMessage (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Diagnostic, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits a manually-constructed diagnostic to the given output stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ShowColors</td>
<td class="doxyParamItemDescription"><p>Display colored messages if output is a terminal and the default error handler is used.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a757ccf4ae54f435c3828c704ca65798e">FindBufferContainingLoc</a>, <a href="#aff646a871ca58ccd8d16633b7b88eaaf">getBufferInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a7f7639f70813f4388a60639d770ae0de">llvm::SMDiagnostic::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#abb1e94b8fff61f549bcbd5a2780f6796">llvm::SMLoc::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a> and <a href="#a700008f59fc3d0ac675878b0432b59e4">PrintIncludeStack</a>.</p>

</div>
</div>

### setDiagHandler() {#ad324bef18696e3fcd110ffb2d33a2b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SourceMgr::setDiagHandler (<a href="#acf78be89ec851a45f37a776a5a58bfe8">DiagHandlerTy</a> DH, void * Ctx=nullptr)</td>
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

<p>Specify a diagnostic handler to be invoked every time PrintMessage is called.</p>


<p><span class="doxyComputerOutput">Ctx</span> is passed into the handler when it is invoked.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9f274211d8e2baf7f13ec1e030e09de6">llvm::vfs::RedirectingFileSystem::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#a08be5fbbd5b0a3cc5ddc2a582fbd200d">setupSM</a> and <a href="/web-llvm/docs/api/classes/llvm/remarks/yamlparseerror/#aee75e19211cebf7bf53859a98bd5ac61">llvm::remarks::YAMLParseError::YAMLParseError</a>.</p>

</div>
</div>

### setIncludeDirs() {#a4623f407b4e8c9d13883dc50bf6cd9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SourceMgr::setIncludeDirs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; Dirs)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### takeSourceBuffersFrom() {#af9c533e5b4fb98dcc0fbf4df792aaf96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SourceMgr::takeSourceBuffersFrom (<a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SrcMgr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> MainBufferIncludeLoc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Takes the source buffers from the given source manager and append them to the current manager.</p>


<p><span class="doxyComputerOutput">MainBufferIncludeLoc</span> is an optional include location to attach to the main buffer of <span class="doxyComputerOutput">SrcMgr</span> after it gets moved to the current manager.</p>


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>


<p>References <a href="#a5d21b555e4cfc2a1be47148889ef48b8">getNumBuffers</a>, <a href="#a832a884d4405c7a6640c36e2f6497708">SourceMgr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5f3f23062c5d5636bee27c54f4a407f0">llvm::SrcMgr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af5bd59cf74666a7da28269e983745b04">llvm::TableGenParseFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isValidBufferID() {#a201d6394a54bc3a9b7f9d6c0f0bb3757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SourceMgr::isValidBufferID (unsigned i)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffers {#a953b5aaaa8ba761726dda1530996d7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SrcBuffer&gt; llvm::SourceMgr::Buffers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is all of the buffers that we are reading from.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### DiagContext {#ac12c71999dbc4fe3a959eda864316782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::SourceMgr::DiagContext = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### DiagHandler {#a9292998b7687dd2cbef425121708f056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagHandlerTy llvm::SourceMgr::DiagHandler = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

### IncludeDirectories {#a327607e571184c8cc980373deba24baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::SourceMgr::IncludeDirectories</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">SourceMgr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp">SourceMgr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
