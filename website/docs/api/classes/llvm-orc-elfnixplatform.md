---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/elfnixplatform
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ELFNixPlatform` Class Reference

<p>Mediates between ELFNix initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ELFNixPlatform { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">llvm/ExecutionEngine/Orc/ELFNixPlatform.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Platforms set up standard symbols and mediate interactions between dynamic initializers (e.g. <a href="/web-llvm/docs/api/classes/llvm/orc/platform/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac47d5a5d1a82cdf25d36c7f2b9e877e3">PushInitializersSendResultFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1ec64f60878483dc018f84901b95c3ba">ELFNixJITDylibDepInfoMap</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5e295e385206d45ad078885b87d4271">SendSymbolAddressFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac922abab67b7b76c4ae28cde369cd4da">ELFNixPlatform</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, std::unique_ptr&lt; DefinitionGenerator &gt; OrcRuntimeGenerator, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7523fe80220e295e2b16bd82472481ee">getExecutionSession</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280360aba7063ebc472bc8a4e6926a7a">getObjectLinkingLayer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7127d538ced6f1908ebede62dfb6ae">setupJITDylib</a> (JITDylib &amp;JD) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is created (unless it is created with EmptyJITDylib set) to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to install any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> specific standard symbols (e.g __dso_handle). <a href="#a6c7127d538ced6f1908ebede62dfb6ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8004825924463615a0f9e6f1ebc78d">teardownJITDylib</a> (JITDylib &amp;JD) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is removed to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to remove any JITDylib-specific data. <a href="#ade8004825924463615a0f9e6f1ebc78d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454ad1d1eb28a3dfc9ed6383417df7bb">notifyAdding</a> (ResourceTracker &amp;RT, const MaterializationUnit &amp;MU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> is added to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a454ad1d1eb28a3dfc9ed6383417df7bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b7f7091f6dcf7cdfb412caaa9975134">notifyRemoving</a> (ResourceTracker &amp;RT) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock when a <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> is removed. <a href="#a6b7f7091f6dcf7cdfb412caaa9975134">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2876c69706f5ccd4d76a0363b7ac9dd9">associateRuntimeSupportFunctions</a> (JITDylib &amp;PlatformJD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83901f466225f4916251f1e7316a8ff1">pushInitializersLoop</a> (PushInitializersSendResultFn SendResult, JITDylibSP JD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ffc7287a7118617bd1d9782671d8e2">rt_recordInitializers</a> (PushInitializersSendResultFn SendResult, ExecutorAddr JDHeader)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263c8af673bd80696cbb10ab5e304829">rt_lookupSymbol</a> (SendSymbolAddressFn SendResult, ExecutorAddr Handle, StringRef SymbolName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56dbaf569926fd35c7b3b8514c5df34">registerPerObjectSections</a> (jitlink::LinkGraph &amp;G, const ELFPerObjectSectionsToRegister &amp;POSR, bool IsBootstrapping)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab978c94074ab80e17e2d10a080766423">createPThreadKey</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a109d1cce925e815c2e717695eb53ef70">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad676f8e9f0b16f59d8029de445e4db24">PlatformJD</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df56e6e5a9a7c12eb47abd168e5a162">ObjLinkingLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3345cbfa52504547831019066047ad7d">DSOHandleSymbol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b48c27e1193827bfc93cd741e7031a9">PlatformBootstrap</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc9ff3f2de63b5f55b03a0ed09be16e">PlatformShutdown</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2509deb6f57a5b06299978f99c4af1e">RegisterJITDylib</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d7619bb1fe0695604b5ffcb282a7fe">DeregisterJITDylib</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a836d47e8a276984d97602bfef0f44159">RegisterObjectSections</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf912f1463ca08bac00852c54e7ec7b8">DeregisterObjectSections</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a474e6d2017825962df82877771005b">RegisterInitSections</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4395e11d084c1ce9f97873f4c6f63003">DeregisterInitSections</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/runtimefunction">RuntimeFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ffaf14a67975db77539bd57e2d5ff0b">CreatePThreadKey</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c6b247c6238d91a23aadc151cef190">RegisteredInitSymbols</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08510793d0102b70cf94c323f12aef4d">PlatformMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister">ELFPerObjectSectionsToRegister</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab719374298dba7c4a4aafc6c76a17e0b">BootstrapPOSRs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc21854e54ac590eeb370eb036fa583">HandleAddrToJITDylib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b43413007edcb38371870990fd7ea5">JITDylibToHandleAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439a3777e5c4ae72f7e70a6d07cd5873">JITDylibToPThreadKey</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; BootstrapInfo * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5767a9e9189c25151ef9f4739f7b622">Bootstrap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a419d5abbdb82bc571c3867365716d">Create</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, std::unique_ptr&lt; DefinitionGenerator &gt; OrcRuntime, std::optional&lt; SymbolAliasMap &gt; RuntimeAliases=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to create a <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> instance, adding the ORC runtime to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#aa9a419d5abbdb82bc571c3867365716d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a176a05717f48de0630c7881365edd895">Create</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, const char *OrcRuntimePath, std::optional&lt; SymbolAliasMap &gt; RuntimeAliases=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct using a path to the ORC runtime. <a href="#a176a05717f48de0630c7881365edd895">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e9150a53b2c3f3e182626bfbdf651e">standardPlatformAliases</a> (ExecutionSession &amp;ES, JITDylib &amp;PlatformJD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an AliasMap containing the default aliases for the <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a>. <a href="#a40e9150a53b2c3f3e182626bfbdf651e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc2b22228c720045d3363d9cebe29b64">requiredCXXAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the array of required CXX aliases. <a href="#adc2b22228c720045d3363d9cebe29b64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a843db0c534aa68d1fea644f1d94db83d">standardRuntimeUtilityAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the array of standard runtime utility aliases for <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a>. <a href="#a843db0c534aa68d1fea644f1d94db83d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc9ba4caaf5e4f5903f5292c8e3f8317">standardLazyCompilationAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a list of aliases required to enable lazy compilation via the ORC runtime. <a href="#abc9ba4caaf5e4f5903f5292c8e3f8317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f66e01da8b92ebcb8f236a76952980b">supportedTarget</a> (const Triple &amp;TT)</td>
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

<p>Mediates between ELFNix initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### PushInitializersSendResultFn {#ac47d5a5d1a82cdf25d36c7f2b9e877e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ELFNixPlatform::PushInitializersSendResultFn = 
      unique_function&lt;void(Expected&lt;ELFNixJITDylibDepInfoMap&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### SendSymbolAddressFn {#af5e295e385206d45ad078885b87d4271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ELFNixPlatform::SendSymbolAddressFn =  unique_function&lt;void(Expected&lt;ExecutorAddr&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ELFNixPlatform() {#ac922abab67b7b76c4ae28cde369cd4da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ELFNixPlatform::ELFNixPlatform (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a> &gt; OrcRuntimeGenerator, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExecutionSession() {#a7523fe80220e295e2b16bd82472481ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::ELFNixPlatform::getExecutionSession ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-elfnixplatform-cpp-/#a4edaac18b04b42252a7c922e21fcc222">anonymous{ELFNixPlatform.cpp}::createPlatformGraph</a>.</p>

</div>
</div>

### getObjectLinkingLayer() {#a280360aba7063ebc472bc8a4e6926a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLinkingLayer &amp; llvm::orc::ELFNixPlatform::getObjectLinkingLayer ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### notifyAdding() {#a454ad1d1eb28a3dfc9ed6383417df7bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::notifyAdding (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &amp; MU)</td>
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

<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> is added to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a99d1933cb59ec5527b4c025ae7027216">llvm::orc::MaterializationUnit::getInitializerSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#a19b2c478815e45a7c78615959f5450a2">llvm::orc::ResourceTracker::getJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a1c2e2986d77d9e3cc3d1c64e6e8f35ad">llvm::orc::MaterializationUnit::getName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>

</div>
</div>

### notifyRemoving() {#a6b7f7091f6dcf7cdfb412caaa9975134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::notifyRemoving (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT)</td>
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

<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock when a <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> is removed.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### setupJITDylib() {#a6c7127d538ced6f1908ebede62dfb6ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::setupJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is created (unless it is created with EmptyJITDylib set) to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to install any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> specific standard symbols (e.g __dso_handle).</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a5ec8631eb0c37168d6f85c4ecad77747">llvm::orc::JITDylib::define</a>.</p>

</div>
</div>

### teardownJITDylib() {#ade8004825924463615a0f9e6f1ebc78d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::teardownJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is removed to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to remove any JITDylib-specific data.</p>

<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### associateRuntimeSupportFunctions() {#a2876c69706f5ccd4d76a0363b7ac9dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::associateRuntimeSupportFunctions (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### createPThreadKey() {#ab978c94074ab80e17e2d10a080766423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::orc::ELFNixPlatform::createPThreadKey ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### pushInitializersLoop() {#a83901f466225f4916251f1e7316a8ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ELFNixPlatform::pushInitializersLoop (<a href="/web-llvm/docs/api/classes/llvm/unique-function">PushInitializersSendResultFn</a> SendResult, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> JD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### registerPerObjectSections() {#ab56dbaf569926fd35c7b3b8514c5df34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::registerPerObjectSections (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/elfperobjectsectionstoregister">ELFPerObjectSectionsToRegister</a> &amp; POSR, bool IsBootstrapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### rt\_lookupSymbol() {#a263c8af673bd80696cbb10ab5e304829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ELFNixPlatform::rt_lookupSymbol (<a href="/web-llvm/docs/api/classes/llvm/unique-function">SendSymbolAddressFn</a> SendResult, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> Handle, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### rt\_recordInitializers() {#a22ffc7287a7118617bd1d9782671d8e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ELFNixPlatform::rt_recordInitializers (<a href="/web-llvm/docs/api/classes/llvm/unique-function">PushInitializersSendResultFn</a> SendResult, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> JDHeader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bootstrap {#aa5767a9e9189c25151ef9f4739f7b622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;BootstrapInfo *&gt; llvm::orc::ELFNixPlatform::Bootstrap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### BootstrapPOSRs {#ab719374298dba7c4a4aafc6c76a17e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ELFPerObjectSectionsToRegister&gt; llvm::orc::ELFNixPlatform::BootstrapPOSRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### CreatePThreadKey {#a9ffaf14a67975db77539bd57e2d5ff0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::CreatePThreadKey</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_create_pthread_key")}
</div>
</dd>
</dl>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### DeregisterInitSections {#a4395e11d084c1ce9f97873f4c6f63003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::DeregisterInitSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_deregister_init_sections")}
</div>
</dd>
</dl>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### DeregisterJITDylib {#a37d7619bb1fe0695604b5ffcb282a7fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::DeregisterJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_deregister_jitdylib")}
</div>
</dd>
</dl>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### DeregisterObjectSections {#acf912f1463ca08bac00852c54e7ec7b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::DeregisterObjectSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_deregister_object_sections")}
</div>
</dd>
</dl>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### DSOHandleSymbol {#a3345cbfa52504547831019066047ad7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::ELFNixPlatform::DSOHandleSymbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### ES {#a109d1cce925e815c2e717695eb53ef70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::ELFNixPlatform::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### HandleAddrToJITDylib {#accc21854e54ac590eeb370eb036fa583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ExecutorAddr, JITDylib *&gt; llvm::orc::ELFNixPlatform::HandleAddrToJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### JITDylibToHandleAddr {#a03b43413007edcb38371870990fd7ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;JITDylib *, ExecutorAddr&gt; llvm::orc::ELFNixPlatform::JITDylibToHandleAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### JITDylibToPThreadKey {#a439a3777e5c4ae72f7e70a6d07cd5873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;JITDylib *, uint64_t&gt; llvm::orc::ELFNixPlatform::JITDylibToPThreadKey</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### ObjLinkingLayer {#a6df56e6e5a9a7c12eb47abd168e5a162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLinkingLayer&amp; llvm::orc::ELFNixPlatform::ObjLinkingLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### PlatformBootstrap {#a7b48c27e1193827bfc93cd741e7031a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::PlatformBootstrap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_platform_bootstrap")}
</div>
</dd>
</dl>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### PlatformJD {#ad676f8e9f0b16f59d8029de445e4db24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib&amp; llvm::orc::ELFNixPlatform::PlatformJD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### PlatformMutex {#a08510793d0102b70cf94c323f12aef4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::ELFNixPlatform::PlatformMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### PlatformShutdown {#a9dc9ff3f2de63b5f55b03a0ed09be16e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::PlatformShutdown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_platform_shutdown")}
</div>
</dd>
</dl>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### RegisteredInitSymbols {#a84c6b247c6238d91a23aadc151cef190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;JITDylib *, SymbolLookupSet&gt; llvm::orc::ELFNixPlatform::RegisteredInitSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### RegisterInitSections {#a9a474e6d2017825962df82877771005b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::RegisterInitSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_register_init_sections")}
</div>
</dd>
</dl>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### RegisterJITDylib {#ad2509deb6f57a5b06299978f99c4af1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::RegisterJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_register_jitdylib")}
</div>
</dd>
</dl>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### RegisterObjectSections {#a836d47e8a276984d97602bfef0f44159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::ELFNixPlatform::RegisterObjectSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("__orc_rt_elfnix_register_object_sections")}
</div>
</dd>
</dl>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#aa9a419d5abbdb82bc571c3867365716d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ELFNixPlatform &gt; &gt; llvm::orc::ELFNixPlatform::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a> &gt; OrcRuntime, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> &gt; RuntimeAliases=std::nullopt)</td>
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

<p>Try to create a <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> instance, adding the ORC runtime to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>The ORC runtime requires access to a number of symbols in libc++. It is up to the caller to ensure that the required symbols can be referenced by code added to PlatformJD. The standard way to achieve this is to first attach dynamic library search generators for either the given process, or for the specific required libraries, to PlatformJD, then to create the platform instance:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;PlatformJD = ES.createBareJITDylib(</span><span class="doxyHighlightStringLiteral">"stdlib"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">PlatformJD.addGenerator(</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ExitOnErr(EPCDynamicLibrarySearchGenerator</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">              ::GetForTargetProcess(EPC)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">ES.setPlatform(</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ExitOnErr(<a href="#aa9a419d5abbdb82bc571c3867365716d">ELFNixPlatform::Create</a>(ES, ObjLayer, EPC, PlatformJD,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                  </span><span class="doxyHighlightStringLiteral">"/path/to/orc/runtime"</span><span class="doxyHighlight">)));</span></span></div>

</div>


<p>Alternatively, these symbols could be added to another <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> that PlatformJD links against.</p>


<p>Clients are also responsible for ensuring that any JIT'd code that depends on runtime functions (including any code using TLV or static destructors) can reference the runtime symbols. This is usually achieved by linking any JITDylibs containing regular code against PlatformJD.</p>


<p>By default, <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> will add the set of aliases returned by the standardPlatformAliases function. This includes both required aliases (e.g. __cxa_atexit -&gt; __orc_rt_elf_cxa_atexit for static destructor support), and optional aliases that provide JIT versions of common functions (e.g. dlopen -&gt; __orc_rt_elf_jit_dlopen). Clients can override these defaults by passing a non-None value for the RuntimeAliases function, in which case the client is responsible for setting up all aliases (including the required ones).</p>


<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3a6ca0ed8ac3267e0579452013a2e82d">llvm::orc::absoluteSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a40e9150a53b2c3f3e182626bfbdf651e">standardPlatformAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2c212cdbe134087fcaa385aad1bc8a9e">llvm::orc::symbolAliases</a>.</p>


<p>Referenced by <a href="#a176a05717f48de0630c7881365edd895">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>.</p>

</div>
</div>

### Create() {#a176a05717f48de0630c7881365edd895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ELFNixPlatform &gt; &gt; llvm::orc::ELFNixPlatform::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OrcRuntimePath, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> &gt; RuntimeAliases=std::nullopt)</td>
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

<p>Construct using a path to the ORC runtime.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="#aa9a419d5abbdb82bc571c3867365716d">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a703cd8845907b2859b4ebdd00c206bc1">llvm::orc::StaticLibraryDefinitionGenerator::Load</a>.</p>

</div>
</div>

### requiredCXXAliases() {#adc2b22228c720045d3363d9cebe29b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const char *, const char * &gt; &gt; llvm::orc::ELFNixPlatform::requiredCXXAliases ()</td>
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

<p>Returns the array of required CXX aliases.</p>

<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a40e9150a53b2c3f3e182626bfbdf651e">standardPlatformAliases</a>.</p>

</div>
</div>

### standardLazyCompilationAliases() {#abc9ba4caaf5e4f5903f5292c8e3f8317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const char *, const char * &gt; &gt; llvm::orc::ELFNixPlatform::standardLazyCompilationAliases ()</td>
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

<p>Returns a list of aliases required to enable lazy compilation via the ORC runtime.</p>

<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a40e9150a53b2c3f3e182626bfbdf651e">standardPlatformAliases</a>.</p>

</div>
</div>

### standardPlatformAliases() {#a40e9150a53b2c3f3e182626bfbdf651e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolAliasMap &gt; llvm::orc::ELFNixPlatform::standardPlatformAliases (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD)</td>
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

<p>Returns an AliasMap containing the default aliases for the <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a>.</p>


<p>This can be modified by clients when constructing the platform to add or remove aliases.</p>


<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a82f74a53afe9225468960223f8d96c46">llvm::orc::addAliases</a>, <a href="#adc2b22228c720045d3363d9cebe29b64">requiredCXXAliases</a>, <a href="#abc9ba4caaf5e4f5903f5292c8e3f8317">standardLazyCompilationAliases</a> and <a href="#a843db0c534aa68d1fea644f1d94db83d">standardRuntimeUtilityAliases</a>.</p>


<p>Referenced by <a href="#aa9a419d5abbdb82bc571c3867365716d">Create</a>.</p>

</div>
</div>

### standardRuntimeUtilityAliases() {#a843db0c534aa68d1fea644f1d94db83d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const char *, const char * &gt; &gt; llvm::orc::ELFNixPlatform::standardRuntimeUtilityAliases ()</td>
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

<p>Returns the array of standard runtime utility aliases for <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a>.</p>

<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a40e9150a53b2c3f3e182626bfbdf651e">standardPlatformAliases</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### supportedTarget() {#a7f66e01da8b92ebcb8f236a76952980b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::ELFNixPlatform::supportedTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
