---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `JITLinkCtx` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::LinkGraphLinkingLayer::JITLinkCtx { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds context for a single jitLink invocation. <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a073ebe5b6a1a0f6f62be31c4f24f73d5">JITLinkCtx</a> (LinkGraphLinkingLayer &amp;Layer, std::unique_ptr&lt; MaterializationResponsibility &gt; MR, std::unique_ptr&lt; MemoryBuffer &gt; ObjBuffer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1136a7a0cde1fec195224f3a3bb82c32">~JITLinkCtx</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">JITLinkMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ffd3f0263ce6b144d012d0e21738c85">getMemoryManager</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the MemoryManager to be used for this link. <a href="#a2ffd3f0263ce6b144d012d0e21738c85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76c45898b19a292e45ded83446e358e">notifyMaterializing</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10264344ebbce5afada547a68412ead8">notifyFailed</a> (Error Err) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify this context that linking failed. <a href="#a10264344ebbce5afada547a68412ead8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e2d6772947f738a66a42d8c8e9a67f">lookup</a> (const LookupMap &amp;Symbols, std::unique_ptr&lt; JITLinkAsyncLookupContinuation &gt; LC) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink to resolve external symbols. <a href="#a61e2d6772947f738a66a42d8c8e9a67f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569ab99e0391c055c321e1088a303335">notifyResolved</a> (LinkGraph &amp;G) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink once all defined symbols in the graph have been assigned their final memory locations in the target process. <a href="#a569ab99e0391c055c321e1088a303335">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a212b5938554719410ce827320a6adf76">notifyFinalized</a> (JITLinkMemoryManager::FinalizedAlloc A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink to notify the context that the object has been finalized (i.e. <a href="#a212b5938554719410ce827320a6adf76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a00c066d790481f29c26588193ee3a35e">LinkGraphPassFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90013f109379fa5e80ef60f26fe09ef6">getMarkLivePass</a> (const Triple &amp;TT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the mark-live pass to be used for this link. <a href="#a90013f109379fa5e80ef60f26fe09ef6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9244565368ee4c5e1c2666b63b6af76d">modifyPassConfig</a> (LinkGraph &amp;LG, PassConfiguration &amp;Config) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by JITLink to modify the pass pipeline prior to linking. <a href="#a9244565368ee4c5e1c2666b63b6af76d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8e73a73071047876dcd6fda9a6a483">notifyLoaded</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd274aecaf8f78e9040be59dfe07874d">notifyEmitted</a> (jitlink::JITLinkMemoryManager::FinalizedAlloc FA)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a191a9660d6dffaf2c124de178660ba4a">claimOrExternalizeWeakAndCommonSymbols</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80dc4337c3f996512b05bbeaf5aaa32e">markResponsibilitySymbolsLive</a> (LinkGraph &amp;G) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243e826b64aece11a7801e5368106942">registerDependencies</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af181e5e6451eed0262604549515925df">Layer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/plugin">LinkGraphLinkingLayer::Plugin</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dcee3c53036ce9dc95f6d1df97856d9">Plugins</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2caf50f39c0fa119d3be30c0579da927">MR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a46a3b93c5f52efaa00199c6b30948d">ObjBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/nonowningsymbolstringptr">NonOwningSymbolStringPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f5f0c96f76144b3939bf8dcf3e829e">SymbolSourceJDs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/symboldependencegroup">SymbolDependenceGroup</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d4bc93d3ebcdd40094fe0dd6ced825e">SymbolDepGroups</a></td>
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


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### JITLinkCtx() {#a073ebe5b6a1a0f6f62be31c4f24f73d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::JITLinkCtx (<a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> &amp; Layer, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; MR, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; ObjBuffer)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext/#a24398345edc8a687abe8c81f1fcdaa2b">llvm::jitlink::JITLinkContext::JITLinkContext</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#ad724ca2d7c9b366f039bd13c3d04dcd3">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~JITLinkCtx() {#a1136a7a0cde1fec195224f3a3bb82c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::~JITLinkCtx ()</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMarkLivePass() {#a90013f109379fa5e80ef60f26fe09ef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphPassFunction llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::getMarkLivePass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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

<p>Returns the mark-live pass to be used for this link.</p>


<p>If no pass is returned (the default) then the target-specific linker implementation will choose a conservative default (usually marking all symbols live). This function is only called if shouldAddDefaultTargetPasses returns true, otherwise the JITContext is responsible for adding a mark-live pass in modifyPassConfig.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### getMemoryManager() {#a2ffd3f0263ce6b144d012d0e21738c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITLinkMemoryManager &amp; llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::getMemoryManager ()</td>
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

<p>Return the MemoryManager to be used for this link.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### lookup() {#a61e2d6772947f738a66a42d8c8e9a67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext/#a58d8c813630c45ed687b828d320c3642">LookupMap</a> &amp; Symbols, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkasynclookupcontinuation">JITLinkAsyncLookupContinuation</a> &gt; LC)</td>
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

<p>Called by JITLink to resolve external symbols.</p>


<p>This method is passed a lookup continutation which it must call with a result to continue the linking process.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset/#a6542a1b1d7b2b32faca7cc49c8d167e0">llvm::orc::SymbolLookupSet::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a278b50a28b5c8c2c7338d41b70f28798aa1734373fb555ce75d3e33411f9ea827">llvm::jitlink::RequiredSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9abaa1734373fb555ce75d3e33411f9ea827">llvm::orc::RequiredSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adac25fca9fb14b1defe43d18a81c16e8af691f042a559b1c1a4f89826c6f75760">llvm::orc::Resolved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ac17672ae6b70c781cc77713e88d698eba84a8921b25f505d0d2077aeb5db4bc16">llvm::orc::Static</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a278b50a28b5c8c2c7338d41b70f28798a26a03cdefe35519715a4b6d564c9c9c7">llvm::jitlink::WeaklyReferencedSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>

</div>
</div>

### modifyPassConfig() {#a9244565368ee4c5e1c2666b63b6af76d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::modifyPassConfig (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">PassConfiguration</a> &amp; Config)</td>
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

<p>Called by JITLink to modify the pass pipeline prior to linking.</p>


<p>The default version performs no modification.</p>


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration/#a37decb1a4d14127fabb251c498274d0b">llvm::jitlink::PassConfiguration::PreFixupPasses</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration/#ad40c7648b8ad38b6d942e7194a4faa34">llvm::jitlink::PassConfiguration::PrePrunePasses</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### notifyEmitted() {#afd274aecaf8f78e9040be59dfe07874d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyEmitted (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">jitlink::JITLinkMemoryManager::FinalizedAlloc</a> FA)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a212b5938554719410ce827320a6adf76">notifyFinalized</a>.</p>

</div>
</div>

### notifyFailed() {#a10264344ebbce5afada547a68412ead8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyFailed (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
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

<p>Notify this context that linking failed.</p>


<p>Called by JITLink if linking cannot be completed.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### notifyFinalized() {#a212b5938554719410ce827320a6adf76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyFinalized (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">JITLinkMemoryManager::FinalizedAlloc</a> Alloc)</td>
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

<p>Called by JITLink to notify the context that the object has been finalized (i.e.</p>


<p>emitted to memory and memory permissions set). If all of this objects dependencies have also been finalized then the code is ready to run.</p>


<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#afd274aecaf8f78e9040be59dfe07874d">notifyEmitted</a>.</p>

</div>
</div>

### notifyLoaded() {#a4e8e73a73071047876dcd6fda9a6a483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyLoaded ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a569ab99e0391c055c321e1088a303335">notifyResolved</a>.</p>

</div>
</div>

### notifyMaterializing() {#ad76c45898b19a292e45ded83446e358e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyMaterializing (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### notifyResolved() {#a569ab99e0391c055c321e1088a303335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyResolved (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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

<p>Called by JITLink once all defined symbols in the graph have been assigned their final memory locations in the target process.</p>


<p>At this point the LinkGraph can be inspected to build a symbol table, however the block content will not generally have been copied to the target location yet.</p>


<p>If the client detects an error in the LinkGraph state (e.g. unexpected or missing symbols) they may return an error here. The error will be propagated to notifyFailed and the linker will bail out.</p>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a99fe4a708e2a83ed2e9aaf8c3d909a1b">llvm::orc::LinkGraphLayer::getJITSymbolFlagsForSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a4e8e73a73071047876dcd6fda9a6a483">notifyLoaded</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda1fee46ed8695ca5c28a7c177dae57a8a">llvm::jitlink::SideEffectsOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### claimOrExternalizeWeakAndCommonSymbols() {#a191a9660d6dffaf2c124de178660ba4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::claimOrExternalizeWeakAndCommonSymbols (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### markResponsibilitySymbolsLive() {#a80dc4337c3f996512b05bbeaf5aaa32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::markResponsibilitySymbolsLive (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### registerDependencies() {#a243e826b64aece11a7801e5368106942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::registerDependencies (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Layer {#af181e5e6451eed0262604549515925df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphLinkingLayer&amp; llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::Layer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### MR {#a2caf50f39c0fa119d3be30c0579da927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MaterializationResponsibility&gt; llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::MR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### ObjBuffer {#a8a46a3b93c5f52efaa00199c6b30948d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::ObjBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### Plugins {#a0dcee3c53036ce9dc95f6d1df97856d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;LinkGraphLinkingLayer::Plugin&gt; &gt; llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::Plugins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### SymbolDepGroups {#a7d4bc93d3ebcdd40094fe0dd6ced825e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SymbolDependenceGroup&gt; llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::SymbolDepGroups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### SymbolSourceJDs {#a61f5f0c96f76144b3939bf8dcf3e829e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;NonOwningSymbolStringPtr, JITDylib *&gt; llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::SymbolSourceJDs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
