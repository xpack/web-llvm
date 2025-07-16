---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/reoptimizelayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ReOptimizeLayer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::ReOptimizeLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">llvm/ExecutionEngine/Orc/ReOptimizeLayer.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface for layers that accept LLVM IR. <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> = uint64_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433182a5de2e7e5d1ad1534249ab37ba">AddProfilerFunc</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>( <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a> &amp;Parent, <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> MUID, unsigned CurVersion, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp;TSM)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a433182a5de2e7e5d1ad1534249ab37ba">AddProfilerFunc</a> will be called when <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a> emits the first version of a materialization unit in order to inject profiling code and reoptimization request code. <a href="#a433182a5de2e7e5d1ad1534249ab37ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ef2e9b5a8868d2c58079b69529089b">ReOptimizeFunc</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>( <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a> &amp;Parent, <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> MUID, unsigned CurVersion, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> OldRT, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp;TSM)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a01ef2e9b5a8868d2c58079b69529089b">ReOptimizeFunc</a> will be called when <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a> reoptimization of a materialization unit was requested in order to reoptimize the IR module based on profile data. <a href="#a01ef2e9b5a8868d2c58079b69529089b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5e55463a6c53b139e13da771a2d9ed0">SPSReoptimizeArgList</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsarglist">shared::SPSArgList</a>&lt; <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a>, uint32_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b37cd74c5cbfccd6810eab6cd02058f">SendErrorFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b568a5599904f23d7fab8e9e45663af">ReOptimizeLayer</a> (ExecutionSession &amp;ES, DataLayout &amp;DL, IRLayer &amp;BaseLayer, RedirectableSymbolManager &amp;RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5875dd2423151ba677f05e35443652">setReoptimizeFunc</a> (ReOptimizeFunc ReOptFunc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb47e83bf9abcaaf27ec0b4c265afd3">setAddProfilerFunc</a> (AddProfilerFunc ProfilerFunc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a0b692655f9afeb0e25125cbf3b8cd">reigsterRuntimeFunctions</a> (JITDylib &amp;PlatformJD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers reoptimize runtime dispatch handlers to given PlatformJD. <a href="#a17a0b692655f9afeb0e25125cbf3b8cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c88678c1ec65beaba8e75c3d2153d85">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, ThreadSafeModule TSM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the given module. <a href="#a0c88678c1ec65beaba8e75c3d2153d85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd0d657410c7bb991aeca1736fe82b3">handleRemoveResources</a> (JITDylib &amp;JD, ResourceKey K) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will be called <em>outside</em> the session lock. <a href="#aacd0d657410c7bb991aeca1736fe82b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3455627cec2934fa2de73ac79470b5">handleTransferResources</a> (JITDylib &amp;JD, ResourceKey DstK, ResourceKey SrcK) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will be called <em>inside</em> the session lock. <a href="#a8a3455627cec2934fa2de73ac79470b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a8ab9a099de556e888c5f92a4fe49d2fa">SymbolMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af453d5f7632ec8a10d71a59c77416774">emitMUImplSymbols</a> (ReOptMaterializationUnitState &amp;MUState, uint32_t Version, JITDylib &amp;JD, ThreadSafeModule TSM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aed65d2b592be0f940680d54ba149e7">rt_reoptimize</a> (SendErrorFn SendResult, ReOptMaterializationUnitID MUID, uint32_t CurVersion)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ReOptMaterializationUnitState &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880da947c2de3f8e421a0306a30ae402">createMaterializationUnitState</a> (const ThreadSafeModule &amp;TSM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac0ddb3025d0d021197541ed586fc8e8">registerMaterializationUnitResource</a> (ResourceKey Key, ReOptMaterializationUnitState &amp;State)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ReOptMaterializationUnitState &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3e0a245e03b01d4cae10f048b041c6">getMaterializationUnitState</a> (ReOptMaterializationUnitID MUID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac96162cebeb7ab8ee8e5c7a69b3060a">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/mangleandinterner">MangleAndInterner</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7bff0c8a93e4ae71e317df5f5fa446">Mangle</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8ff47c58e7dcde673c12787dd3ea887">BaseLayer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d4f9464229271198ef694548fba10f">RSManager</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a01ef2e9b5a8868d2c58079b69529089b">ReOptimizeFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc782277703682c559a8a8a92ffafdca">ReOptFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a433182a5de2e7e5d1ad1534249ab37ba">AddProfilerFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bda796d90d1bb81e2cac10f5d980514">ProfilerFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a307e27a00176312ce1bb49682cab7">Mutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a>, ReOptMaterializationUnitState &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c77635530b1007d01fe24aaddb7178">MUStates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a>, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241a5d067aa6878653b2d6eecdfdc873">MUResources</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dd6137880b68610ce0bdd6be521df5e">NextID</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d94843d12c81b1eda3d646bb2ab38e">reoptimizeIfCallFrequent</a> (ReOptimizeLayer &amp;Parent, ReOptMaterializationUnitID MUID, unsigned CurVersion, ThreadSafeModule &amp;TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic <a href="#a433182a5de2e7e5d1ad1534249ab37ba">AddProfilerFunc</a> that reoptimizes the function when the call count exceeds CallCountThreshold. <a href="#aa1d94843d12c81b1eda3d646bb2ab38e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca0a9a464229ad1ddfc9bae02574c6b">identity</a> (ReOptimizeLayer &amp;Parent, ReOptMaterializationUnitID MUID, unsigned CurVersion, ResourceTrackerSP OldRT, ThreadSafeModule &amp;TSM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9e3a3c2e449cbc1dfebc37503af252">createReoptimizeCall</a> (Module &amp;M, Instruction &amp;IP, GlobalVariable *ArgBuffer)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71e72c141ac7260165039799a5cee215">createReoptimizeArgBuffer</a> (Module &amp;M, ReOptMaterializationUnitID MUID, uint32_t CurVersion)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2c501476e240de056fff1f511859f5">CallCountThreshold</a> = 10</td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AddProfilerFunc {#a433182a5de2e7e5d1ad1534249ab37ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ReOptimizeLayer::AddProfilerFunc =  unique_function&lt;Error(
      ReOptimizeLayer &amp;Parent, ReOptMaterializationUnitID MUID,
      unsigned CurVersion, ThreadSafeModule &amp;TSM)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a433182a5de2e7e5d1ad1534249ab37ba">AddProfilerFunc</a> will be called when <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a> emits the first version of a materialization unit in order to inject profiling code and reoptimization request code.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### ReOptimizeFunc {#a01ef2e9b5a8868d2c58079b69529089b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ReOptimizeLayer::ReOptimizeFunc =  unique_function&lt;Error(
      ReOptimizeLayer &amp;Parent, ReOptMaterializationUnitID MUID,
      unsigned CurVersion, ResourceTrackerSP OldRT, ThreadSafeModule &amp;TSM)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a01ef2e9b5a8868d2c58079b69529089b">ReOptimizeFunc</a> will be called when <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a> reoptimization of a materialization unit was requested in order to reoptimize the IR module based on profile data.</p>


<p>OldRT is the <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> that tracks the old function definitions. The OldRT must be kept alive until it can be guaranteed that every invocation of the old function definitions has been terminated.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### ReOptMaterializationUnitID {#a81245c84a2a98f7c3b05d801696a2598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ReOptimizeLayer::ReOptMaterializationUnitID =  uint64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### SendErrorFn {#a0b37cd74c5cbfccd6810eab6cd02058f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ReOptimizeLayer::SendErrorFn =  unique_function&lt;void(Error)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### SPSReoptimizeArgList {#af5e55463a6c53b139e13da771a2d9ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ReOptimizeLayer::SPSReoptimizeArgList = 
      shared::SPSArgList&lt;ReOptMaterializationUnitID, uint32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ReOptimizeLayer() {#a0b568a5599904f23d7fab8e9e45663af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ReOptimizeLayer::ReOptimizeLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp; BaseLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/redirectablesymbolmanager">RedirectableSymbolManager</a> &amp; RM)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#ae3cfe72cdaca15dbe4c360d8bcdb5207">llvm::orc::IRLayer::getManglingOptions</a>, <a href="#a1ca0a9a464229ad1ddfc9bae02574c6b">identity</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#a1141609d9c7e4bdd205bc09698ff51b3">llvm::orc::IRLayer::IRLayer</a> and <a href="#aa1d94843d12c81b1eda3d646bb2ab38e">reoptimizeIfCallFrequent</a>.</p>


<p>Referenced by <a href="#a1ca0a9a464229ad1ddfc9bae02574c6b">identity</a> and <a href="#aa1d94843d12c81b1eda3d646bb2ab38e">reoptimizeIfCallFrequent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a0c88678c1ec65beaba8e75c3d2153d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReOptimizeLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
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

<p>Emits the given module.</p>


<p>This should not be called by clients: it will be called by the JIT when a definition added via the add method is requested.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### handleRemoveResources() {#aacd0d657410c7bb991aeca1736fe82b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ReOptimizeLayer::handleRemoveResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> K)</td>
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


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### handleTransferResources() {#a8a3455627cec2934fa2de73ac79470b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReOptimizeLayer::handleTransferResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> DstK, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> SrcK)</td>
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


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>

</div>
</div>

### reigsterRuntimeFunctions() {#a17a0b692655f9afeb0e25125cbf3b8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ReOptimizeLayer::reigsterRuntimeFunctions (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers reoptimize runtime dispatch handlers to given PlatformJD.</p>


<p>The reoptimization request will not be handled if dispatch handler is not registered by using this function.</p>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>

</div>
</div>

### setAddProfilerFunc() {#a7cb47e83bf9abcaaf27ec0b4c265afd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ReOptimizeLayer::setAddProfilerFunc (<a href="#a433182a5de2e7e5d1ad1534249ab37ba">AddProfilerFunc</a> ProfilerFunc)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### setReoptimizeFunc() {#a0f5875dd2423151ba677f05e35443652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ReOptimizeLayer::setReoptimizeFunc (<a href="#a01ef2e9b5a8868d2c58079b69529089b">ReOptimizeFunc</a> ReOptFunc)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createMaterializationUnitState() {#a880da947c2de3f8e421a0306a30ae402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReOptimizeLayer::ReOptMaterializationUnitState &amp; ReOptimizeLayer::createMaterializationUnitState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp; TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>

</div>
</div>

### emitMUImplSymbols() {#af453d5f7632ec8a10d71a59c77416774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolMap &gt; ReOptimizeLayer::emitMUImplSymbols (ReOptMaterializationUnitState &amp; MUState, uint32_t Version, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>

</div>
</div>

### getMaterializationUnitState() {#a8d3e0a245e03b01d4cae10f048b041c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReOptimizeLayer::ReOptMaterializationUnitState &amp; ReOptimizeLayer::getMaterializationUnitState (<a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> MUID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>

</div>
</div>

### registerMaterializationUnitResource() {#aac0ddb3025d0d021197541ed586fc8e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReOptimizeLayer::registerMaterializationUnitResource (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> Key, ReOptMaterializationUnitState &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>

</div>
</div>

### rt\_reoptimize() {#a3aed65d2b592be0f940680d54ba149e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReOptimizeLayer::rt_reoptimize (<a href="/web-llvm/docs/api/classes/llvm/unique-function">SendErrorFn</a> SendResult, <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> MUID, uint32_t CurVersion)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseLayer {#ae8ff47c58e7dcde673c12787dd3ea887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRLayer&amp; llvm::orc::ReOptimizeLayer::BaseLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### ES {#aac96162cebeb7ab8ee8e5c7a69b3060a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::ReOptimizeLayer::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### Mangle {#aac7bff0c8a93e4ae71e317df5f5fa446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MangleAndInterner llvm::orc::ReOptimizeLayer::Mangle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### MUResources {#a241a5d067aa6878653b2d6eecdfdc873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ResourceKey, DenseSet&lt;ReOptMaterializationUnitID&gt; &gt; llvm::orc::ReOptimizeLayer::MUResources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### MUStates {#aa1c77635530b1007d01fe24aaddb7178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ReOptMaterializationUnitID, ReOptMaterializationUnitState&gt; llvm::orc::ReOptimizeLayer::MUStates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### Mutex {#a74a307e27a00176312ce1bb49682cab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::ReOptimizeLayer::Mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### NextID {#a8dd6137880b68610ce0bdd6be521df5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReOptMaterializationUnitID llvm::orc::ReOptimizeLayer::NextID = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### ProfilerFunc {#a8bda796d90d1bb81e2cac10f5d980514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddProfilerFunc llvm::orc::ReOptimizeLayer::ProfilerFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### ReOptFunc {#adc782277703682c559a8a8a92ffafdca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReOptimizeFunc llvm::orc::ReOptimizeLayer::ReOptFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

### RSManager {#a27d4f9464229271198ef694548fba10f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RedirectableSymbolManager&amp; llvm::orc::ReOptimizeLayer::RSManager</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createReoptimizeCall() {#a7c9e3a3c2e449cbc1dfebc37503af252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReOptimizeLayer::createReoptimizeCall (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; IP, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * ArgBuffer)</td>
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



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>.</p>


<p>Referenced by <a href="#aa1d94843d12c81b1eda3d646bb2ab38e">reoptimizeIfCallFrequent</a>.</p>

</div>
</div>

### identity() {#a1ca0a9a464229ad1ddfc9bae02574c6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ReOptimizeLayer::identity (<a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a> &amp; Parent, <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> MUID, unsigned CurVersion, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> OldRT, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp; TSM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>


<p>References <a href="#a0b568a5599904f23d7fab8e9e45663af">ReOptimizeLayer</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a0b568a5599904f23d7fab8e9e45663af">ReOptimizeLayer</a>.</p>

</div>
</div>

### reoptimizeIfCallFrequent() {#aa1d94843d12c81b1eda3d646bb2ab38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ReOptimizeLayer::reoptimizeIfCallFrequent (<a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a> &amp; Parent, <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> MUID, unsigned CurVersion, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> &amp; TSM)</td>
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

<p>Basic <a href="#a433182a5de2e7e5d1ad1534249ab37ba">AddProfilerFunc</a> that reoptimizes the function when the call count exceeds CallCountThreshold.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>


<p>References <a href="#adb2c501476e240de056fff1f511859f5">CallCountThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="#a7c9e3a3c2e449cbc1dfebc37503af252">createReoptimizeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="#a0b568a5599904f23d7fab8e9e45663af">ReOptimizeLayer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule/#a5dc53e9bbda9066a1ade839494fe0cd9">llvm::orc::ThreadSafeModule::withModuleDo</a>.</p>


<p>Referenced by <a href="#a0b568a5599904f23d7fab8e9e45663af">ReOptimizeLayer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### createReoptimizeArgBuffer() {#a71e72c141ac7260165039799a5cee215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Constant * &gt; ReOptimizeLayer::createReoptimizeArgBuffer (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="#a81245c84a2a98f7c3b05d801696a2598">ReOptMaterializationUnitID</a> MUID, uint32_t CurVersion)</td>
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



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### CallCountThreshold {#adb2c501476e240de056fff1f511859f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::orc::ReOptimizeLayer::CallCountThreshold = 10</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a>.</p>


<p>Referenced by <a href="#aa1d94843d12c81b1eda3d646bb2ab38e">reoptimizeIfCallFrequent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/reoptimizelayer-h">ReOptimizeLayer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/reoptimizelayer-cpp">ReOptimizeLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
