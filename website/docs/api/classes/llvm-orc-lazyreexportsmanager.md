---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/lazyreexportsmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LazyReexportsManager` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::LazyReexportsManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">llvm/ExecutionEngine/Orc/LazyReexports.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager">ResourceManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Listens for <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> operations. <a href="/web-llvm/docs/api/classes/llvm/orc/resourcemanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d3ba3b3dc709e7d752555101ae2fe6">OnTrampolinesReadyFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void( <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt; &gt; EntryAddrs)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf414262a7add3f75deb5679c717d9ae">EmitTrampolinesFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, size_t NumTrampolines, <a href="#a70d3ba3b3dc709e7d752555101ae2fe6">OnTrampolinesReadyFn</a> OnTrampolinesReady)&gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75dce816afff1a660e9b5c76a60533c">ResolveSendResultFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt;)&gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8395f3c722c15e6c66c83cf2beb305d7">lazyReexports</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Define lazy-reexports based on the given <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a>. <a href="#a8395f3c722c15e6c66c83cf2beb305d7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2de7bf617ae3d5268d12a93af0fe457">LazyReexportsManager</a> (LazyReexportsManager &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd57073726bf01acac471d4252d5cc76">LazyReexportsManager</a> (EmitTrampolinesFn EmitTrampolines, RedirectableSymbolManager &amp;RSMgr, JITDylib &amp;PlatformJD, Listener *L, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager">LazyReexportsManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab504bbdf2ea4f0849ea733c603b08215">operator=</a> (LazyReexportsManager &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e035d19beaac11de143eeeec21f646b">handleRemoveResources</a> (JITDylib &amp;JD, ResourceKey K) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will be called <em>outside</em> the session lock. <a href="#a8e035d19beaac11de143eeeec21f646b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3298447752d621a6c372559f6892c844">handleTransferResources</a> (JITDylib &amp;JD, ResourceKey DstK, ResourceKey SrcK) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will be called <em>inside</em> the session lock. <a href="#a3298447752d621a6c372559f6892c844">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e10c0dcd7789e353545341770891e3a">createLazyReexports</a> (SymbolAliasMap Reexports)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38634af3fdc553a7eacb20fad2600e01">emitReentryTrampolines</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; MR, SymbolAliasMap Reexports)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6486a3a29c59402b6d71a506d7b9d40c">emitRedirectableSymbols</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; MR, SymbolAliasMap Reexports, Expected&lt; std::vector&lt; ExecutorSymbolDef &gt; &gt; ReentryPoints)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b913ed33b7765935a47e183e52d6bb8">resolve</a> (ResolveSendResultFn SendResult, ExecutorAddr ReentryStubAddr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6646c216c82d554dce84617d07502223">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaf414262a7add3f75deb5679c717d9ae">EmitTrampolinesFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe45b67bcc37191e51790c686b122c9b">EmitTrampolines</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/redirectablesymbolmanager">RedirectableSymbolManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef2e49ebd14a77d98093a4d654b71d2a">RSMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/listener">Listener</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b02dd040db7583ed5321c7490166c07">L</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a>, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180d1f67d58528970651661e5764dc2c">KeyToReentryAddrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/lazyreexportsmanager/callthroughinfo">CallThroughInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a9d5fbb3636ecf337ffe22715807561">CallThroughs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager">LazyReexportsManager</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7356741dd0185ed365b0cdfc7d96a14">Create</a> (EmitTrampolinesFn EmitTrampolines, RedirectableSymbolManager &amp;RSMgr, JITDylib &amp;PlatformJD, Listener *L=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager">LazyReexportsManager</a> that uses the ORC runtime for reentry. <a href="#af7356741dd0185ed365b0cdfc7d96a14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### EmitTrampolinesFn {#aaf414262a7add3f75deb5679c717d9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::LazyReexportsManager::EmitTrampolinesFn = 
      unique_function&lt;void(ResourceTrackerSP RT, size_t NumTrampolines,
                           OnTrampolinesReadyFn OnTrampolinesReady)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

### OnTrampolinesReadyFn {#a70d3ba3b3dc709e7d752555101ae2fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::LazyReexportsManager::OnTrampolinesReadyFn =  unique_function&lt;void(
      Expected&lt;std::vector&lt;ExecutorSymbolDef&gt;&gt; EntryAddrs)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### ResolveSendResultFn {#ad75dce816afff1a660e9b5c76a60533c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::LazyReexportsManager::ResolveSendResultFn = 
      unique_function&lt;void(Expected&lt;ExecutorSymbolDef&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### lazyReexports {#a8395f3c722c15e6c66c83cf2beb305d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt; <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager">LazyReexportsManager</a> &amp; LRM, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> Reexports</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Define lazy-reexports based on the given <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a>.</p>


<p>Each lazy re-export is a callable symbol that will look up and dispatch to the given aliasee on first call. All subsequent calls will go directly to the aliasee.</p>


<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>


<p>Reference <a href="#ae2de7bf617ae3d5268d12a93af0fe457">LazyReexportsManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LazyReexportsManager() {#ae2de7bf617ae3d5268d12a93af0fe457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LazyReexportsManager::LazyReexportsManager (<a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager">LazyReexportsManager</a> &amp;&amp;)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>


<p>Reference <a href="#ae2de7bf617ae3d5268d12a93af0fe457">LazyReexportsManager</a>.</p>


<p>Referenced by <a href="#af7356741dd0185ed365b0cdfc7d96a14">Create</a>, <a href="#a8395f3c722c15e6c66c83cf2beb305d7">lazyReexports</a>, <a href="#ae2de7bf617ae3d5268d12a93af0fe457">LazyReexportsManager</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/mu/#a8d109ba81511e8f29201fa169b6529b7">llvm::orc::LazyReexportsManager::MU::MU</a> and <a href="#ab504bbdf2ea4f0849ea733c603b08215">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LazyReexportsManager() {#afd57073726bf01acac471d4252d5cc76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LazyReexportsManager::LazyReexportsManager (<a href="#aaf414262a7add3f75deb5679c717d9ae">EmitTrampolinesFn</a> EmitTrampolines, <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablesymbolmanager">RedirectableSymbolManager</a> &amp; RSMgr, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/listener">Listener</a> * L, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ab504bbdf2ea4f0849ea733c603b08215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyReexportsManager &amp; llvm::orc::LazyReexportsManager::operator= (<a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager">LazyReexportsManager</a> &amp;&amp;)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>


<p>Reference <a href="#ae2de7bf617ae3d5268d12a93af0fe457">LazyReexportsManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### handleRemoveResources() {#a8e035d19beaac11de143eeeec21f646b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LazyReexportsManager::handleRemoveResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> K)</td>
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

<p>This function will be called <em>outside</em> the session lock.</p>


<p>ResourceManagers should perform book-keeping under the session lock, and any expensive cleanup outside the session lock.</p>


<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a67fc014ddc6f09ff528b686fd7b1de20">llvm::orc::JITDylib::getExecutionSession</a>, <a href="#a8e035d19beaac11de143eeeec21f646b">handleRemoveResources</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#ab9ce518e73ce35d17cd88e873776d51e">llvm::orc::ExecutionSession::runSessionLocked</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a8e035d19beaac11de143eeeec21f646b">handleRemoveResources</a>.</p>

</div>
</div>

### handleTransferResources() {#a3298447752d621a6c372559f6892c844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LazyReexportsManager::handleTransferResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> DstK, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> SrcK)</td>
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

<p>This function will be called <em>inside</em> the session lock.</p>


<p>ResourceManagers DO NOT need to re-lock the session.</p>


<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a>.</p>


<p>References <a href="#a3298447752d621a6c372559f6892c844">handleTransferResources</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a3298447752d621a6c372559f6892c844">handleTransferResources</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createLazyReexports() {#a6e10c0dcd7789e353545341770891e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MaterializationUnit &gt; llvm::orc::LazyReexportsManager::createLazyReexports (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> Reexports)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>, definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a>.</p>

</div>
</div>

### emitRedirectableSymbols() {#a6486a3a29c59402b6d71a506d7b9d40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LazyReexportsManager::emitRedirectableSymbols (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; MR, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> Reexports, <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a> &gt; &gt; ReentryPoints)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>, definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a>.</p>

</div>
</div>

### emitReentryTrampolines() {#a38634af3fdc553a7eacb20fad2600e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LazyReexportsManager::emitReentryTrampolines (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; MR, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> Reexports)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>, definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a>.</p>

</div>
</div>

### resolve() {#a4b913ed33b7765935a47e183e52d6bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LazyReexportsManager::resolve (<a href="/web-llvm/docs/api/classes/llvm/unique-function">ResolveSendResultFn</a> SendResult, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ReentryStubAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallThroughs {#a6a9d5fbb3636ecf337ffe22715807561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ExecutorAddr, CallThroughInfo&gt; llvm::orc::LazyReexportsManager::CallThroughs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

### EmitTrampolines {#abe45b67bcc37191e51790c686b122c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmitTrampolinesFn llvm::orc::LazyReexportsManager::EmitTrampolines</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

### ES {#a6646c216c82d554dce84617d07502223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::LazyReexportsManager::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

### KeyToReentryAddrs {#a180d1f67d58528970651661e5764dc2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ResourceKey, std::vector&lt;ExecutorAddr&gt; &gt; llvm::orc::LazyReexportsManager::KeyToReentryAddrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

### L {#a1b02dd040db7583ed5321c7490166c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Listener* llvm::orc::LazyReexportsManager::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

### RSMgr {#aef2e49ebd14a77d98093a4d654b71d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RedirectableSymbolManager&amp; llvm::orc::LazyReexportsManager::RSMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#af7356741dd0185ed365b0cdfc7d96a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; LazyReexportsManager &gt; &gt; llvm::orc::LazyReexportsManager::Create (<a href="#aaf414262a7add3f75deb5679c717d9ae">EmitTrampolinesFn</a> EmitTrampolines, <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablesymbolmanager">RedirectableSymbolManager</a> &amp; RSMgr, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager/listener">Listener</a> * L=nullptr)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/lazyreexportsmanager">LazyReexportsManager</a> that uses the ORC runtime for reentry.</p>


<p>This will work both in-process and out-of-process.</p>


<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a>.</p>


<p>References <a href="#af7356741dd0185ed365b0cdfc7d96a14">Create</a>, <a href="#ae2de7bf617ae3d5268d12a93af0fe457">LazyReexportsManager</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#af7356741dd0185ed365b0cdfc7d96a14">Create</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a6a7f84934d8f3975d6d33c72bdea69c7">llvm::orc::createJITLinkLazyReexportsManager</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lazyreexports-h">LazyReexports.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lazyreexports-cpp">LazyReexports.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
