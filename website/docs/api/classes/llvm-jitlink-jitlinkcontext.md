---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/jitlinkcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `JITLinkContext` Class

<p>Holds context for a single jitLink invocation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::JITLinkContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">llvm/ExecutionEngine/JITLink/JITLink.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx">JITLinkCtx</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d8c813630c45ed687b828d320c3642">LookupMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">orc::SymbolStringPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a278b50a28b5c8c2c7338d41b70f28798">SymbolLookupFlags</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24398345edc8a687abe8c81f1fcdaa2b">JITLinkContext</a> (const JITLinkDylib *JD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a>. <a href="#a24398345edc8a687abe8c81f1fcdaa2b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb97cfb71b150c481decd911596ec21">~JITLinkContext</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy a <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a>. <a href="#a2cb97cfb71b150c481decd911596ec21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483b26069e394ab229e8052a331bcf71">getJITLinkDylib</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> that this link is targeting, if any. <a href="#a483b26069e394ab229e8052a331bcf71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c70dd71e68be2fa3fa611aa98e6672">getMemoryManager</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the MemoryManager to be used for this link. <a href="#a62c70dd71e68be2fa3fa611aa98e6672">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b3ad467f00576bfe7596cb9b8b8504">notifyFailed</a> (Error Err)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify this context that linking failed. <a href="#a50b3ad467f00576bfe7596cb9b8b8504">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703b91afadf06911dfe35492bd290533">lookup</a> (const LookupMap &amp;Symbols, std::unique_ptr&lt; JITLinkAsyncLookupContinuation &gt; LC)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink to resolve external symbols. <a href="#a703b91afadf06911dfe35492bd290533">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82007a5d103f02d7e19f1399819da3cb">notifyResolved</a> (LinkGraph &amp;G)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink once all defined symbols in the graph have been assigned their final memory locations in the target process. <a href="#a82007a5d103f02d7e19f1399819da3cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05439ba03a03714938a2933b7e1e4f4e">notifyFinalized</a> (JITLinkMemoryManager::FinalizedAlloc Alloc)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink to notify the context that the object has been finalized (i.e. <a href="#a05439ba03a03714938a2933b7e1e4f4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8804cf05047727379e11aedb8616773">shouldAddDefaultTargetPasses</a> (const Triple &amp;TT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink prior to linking to determine whether default passes for the target should be added. <a href="#ac8804cf05047727379e11aedb8616773">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a00c066d790481f29c26588193ee3a35e">LinkGraphPassFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13584b1dc0cca51793183fa537c99ec">getMarkLivePass</a> (const Triple &amp;TT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the mark-live pass to be used for this link. <a href="#af13584b1dc0cca51793183fa537c99ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311bd3a401f79170b604b35e9b7b1613">modifyPassConfig</a> (LinkGraph &amp;G, PassConfiguration &amp;Config)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink to modify the pass pipeline prior to linking. <a href="#a311bd3a401f79170b604b35e9b7b1613">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84323b02da314eb38b7c74a4b493155d">JD</a> = nullptr</td>
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

<p>Holds context for a single jitLink invocation.</p>

<p>Definition at line 1932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LookupMap {#a58d8c813630c45ed687b828d320c3642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::JITLinkContext::LookupMap =  DenseMap&lt;orc::SymbolStringPtr, SymbolLookupFlags&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### JITLinkContext() {#a24398345edc8a687abe8c81f1fcdaa2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::JITLinkContext::JITLinkContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> * JD)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a>.</p>

<p>Definition at line 1937 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx/#a073ebe5b6a1a0f6f62be31c4f24f73d5">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::JITLinkCtx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~JITLinkContext() {#a2cb97cfb71b150c481decd911596ec21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::JITLinkContext::~JITLinkContext ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy a <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a>.</p>

<p>Definition at line 1940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getJITLinkDylib() {#a483b26069e394ab229e8052a331bcf71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const JITLinkDylib * llvm::jitlink::JITLinkContext::getJITLinkDylib ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkdylib">JITLinkDylib</a> that this link is targeting, if any.</p>

<p>Definition at line 1943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### getMarkLivePass() {#af13584b1dc0cca51793183fa537c99ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphPassFunction llvm::jitlink::JITLinkContext::getMarkLivePass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the mark-live pass to be used for this link.</p>


<p>If no pass is returned (the default) then the target-specific linker implementation will choose a conservative default (usually marking all symbols live). This function is only called if shouldAddDefaultTargetPasses returns true, otherwise the JITContext is responsible for adding a mark-live pass in modifyPassConfig.</p>


<p>Declaration at line 1986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlink-cpp">JITLink.cpp</a>.</p>


<p>Reference <a href="#af13584b1dc0cca51793183fa537c99ec">getMarkLivePass</a>.</p>


<p>Referenced by <a href="#af13584b1dc0cca51793183fa537c99ec">getMarkLivePass</a>.</p>

</div>
</div>

### getMemoryManager() {#a62c70dd71e68be2fa3fa611aa98e6672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual JITLinkMemoryManager &amp; llvm::jitlink::JITLinkContext::getMemoryManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the MemoryManager to be used for this link.</p>

<p>Definition at line 1946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### lookup() {#a703b91afadf06911dfe35492bd290533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::jitlink::JITLinkContext::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a58d8c813630c45ed687b828d320c3642">LookupMap</a> &amp; Symbols, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkasynclookupcontinuation">JITLinkAsyncLookupContinuation</a> &gt; LC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by JITLink to resolve external symbols.</p>


<p>This method is passed a lookup continutation which it must call with a result to continue the linking process.</p>


<p>Definition at line 1955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### modifyPassConfig() {#a311bd3a401f79170b604b35e9b7b1613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::JITLinkContext::modifyPassConfig (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">PassConfiguration</a> &amp; Config)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by JITLink to modify the pass pipeline prior to linking.</p>


<p>The default version performs no modification.</p>


<p>Declaration at line 1990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlink-cpp">JITLink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a311bd3a401f79170b604b35e9b7b1613">modifyPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a311bd3a401f79170b604b35e9b7b1613">modifyPassConfig</a>.</p>

</div>
</div>

### notifyFailed() {#a50b3ad467f00576bfe7596cb9b8b8504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::jitlink::JITLinkContext::notifyFailed (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notify this context that linking failed.</p>


<p>Called by JITLink if linking cannot be completed.</p>


<p>Definition at line 1950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

### notifyFinalized() {#a05439ba03a03714938a2933b7e1e4f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::jitlink::JITLinkContext::notifyFinalized (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">JITLinkMemoryManager::FinalizedAlloc</a> Alloc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by JITLink to notify the context that the object has been finalized (i.e.</p>


<p>emitted to memory and memory permissions set). If all of this objects dependencies have also been finalized then the code is ready to run.</p>


<p>Definition at line 1972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### notifyResolved() {#a82007a5d103f02d7e19f1399819da3cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::jitlink::JITLinkContext::notifyResolved (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by JITLink once all defined symbols in the graph have been assigned their final memory locations in the target process.</p>


<p>At this point the <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> can be inspected to build a symbol table, however the block content will not generally have been copied to the target location yet.</p>


<p>If the client detects an error in the <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> state (e.g. unexpected or missing symbols) they may return an error here. The error will be propagated to notifyFailed and the linker will bail out.</p>


<p>Definition at line 1966 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### shouldAddDefaultTargetPasses() {#ac8804cf05047727379e11aedb8616773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::JITLinkContext::shouldAddDefaultTargetPasses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by JITLink prior to linking to determine whether default passes for the target should be added.</p>


<p>The default implementation returns true. If subclasses override this method to return false for any target then they are required to fully configure the pass pipeline for that target.</p>


<p>Declaration at line 1978 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlink-cpp">JITLink.cpp</a>.</p>


<p>Reference <a href="#ac8804cf05047727379e11aedb8616773">shouldAddDefaultTargetPasses</a>.</p>


<p>Referenced by <a href="#ac8804cf05047727379e11aedb8616773">shouldAddDefaultTargetPasses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### JD {#a84323b02da314eb38b7c74a4b493155d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const JITLinkDylib* llvm::jitlink::JITLinkContext::JD = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1993 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/jitlink-cpp">JITLink.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
