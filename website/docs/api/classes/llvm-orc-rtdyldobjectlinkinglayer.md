---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/rtdyldobjectlinkinglayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RTDyldObjectLinkingLayer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::RTDyldObjectLinkingLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">llvm/ExecutionEngine/Orc/RTDyldObjectLinkingLayer.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rttiextends">RTTIExtends&lt;ThisT, ParentT, ParentTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inheritance utility for extensible RTTI. <a href="/web-llvm/docs/api/classes/llvm/rttiextends/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92f37749f33343857631cf5cf2eaf381">NotifyLoadedFunction</a> = std::function&lt; void( <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp;R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp;Obj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &amp;)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functor for receiving object-loaded notifications. <a href="#a92f37749f33343857631cf5cf2eaf381">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad748c83b5f6db0f5d30bd2d537b142fb">NotifyEmittedFunction</a> = std::function&lt; void( <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp;R, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functor for receiving finalization notifications. <a href="#ad748c83b5f6db0f5d30bd2d537b142fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12b46d32b79c457c6d1c254daae7fd5">GetMemoryManagerFunction</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &gt;()&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468e0ea5d0a4c8c4b3fb7b92a3df32f7">MemoryManagerUP</a> = std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265854b41dc442be1d29e1a5b7043cc4">RTDyldObjectLinkingLayer</a> (ExecutionSession &amp;ES, GetMemoryManagerFunction GetMemoryManager)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> with the given NotifyLoaded, and NotifyEmitted functors. <a href="#a265854b41dc442be1d29e1a5b7043cc4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a744114ff64c7fdccce17d2e0c0755f09">~RTDyldObjectLinkingLayer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640efdfe6f9a9949a292dc894222e8f5">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, std::unique_ptr&lt; MemoryBuffer &gt; O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the object. <a href="#a640efdfe6f9a9949a292dc894222e8f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01dc8d414e17519d1760908746b27692">setNotifyLoaded</a> (NotifyLoadedFunction NotifyLoaded)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the NotifyLoaded callback. <a href="#a01dc8d414e17519d1760908746b27692">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237b2f36c0eb917c38e7a31cc4d25b45">setNotifyEmitted</a> (NotifyEmittedFunction NotifyEmitted)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the NotifyEmitted callback. <a href="#a237b2f36c0eb917c38e7a31cc4d25b45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fa547646c5f32600aa7336df436ae5">setProcessAllSections</a> (bool ProcessAllSections)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the 'ProcessAllSections' flag. <a href="#ac3fa547646c5f32600aa7336df436ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f7c81b37c4f8db5f4579cb667cb31a">setOverrideObjectFlagsWithResponsibilityFlags</a> (bool OverrideObjectFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructs this RTDyldLinkingLayer2 instance to override the symbol flags returned by <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> for any given object file with the flags supplied by the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance. <a href="#ac4f7c81b37c4f8db5f4579cb667cb31a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5fd9509ea64f5d3780326dea9b50424">setAutoClaimResponsibilityForObjectSymbols</a> (bool AutoClaimObjectSymbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If set, this <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> instance will claim responsibility for any symbols provided by a given object file that were not already in the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance. <a href="#aa5fd9509ea64f5d3780326dea9b50424">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae241d975e5b085fc6762f8f50e5d9add">registerJITEventListener</a> (JITEventListener &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a>. <a href="#ae241d975e5b085fc6762f8f50e5d9add">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa44eb942afaa83011358c9d4eed3fbc5">unregisterJITEventListener</a> (JITEventListener &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unregister a <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a>. <a href="#aa44eb942afaa83011358c9d4eed3fbc5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecef07dfec6b78ec8f7a7dbd32a4c8dd">onObjLoad</a> (MaterializationResponsibility &amp;R, const object::ObjectFile &amp;Obj, RuntimeDyld::MemoryManager &amp;MemMgr, RuntimeDyld::LoadedObjectInfo &amp;LoadedObjInfo, std::map&lt; StringRef, JITEvaluatedSymbol &gt; Resolved, std::set&lt; StringRef &gt; &amp;InternalSymbols)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8005f40544f15b7cacf4899e8178f5b5">onObjEmit</a> (MaterializationResponsibility &amp;R, object::OwningBinary&lt; object::ObjectFile &gt; O, std::unique_ptr&lt; RuntimeDyld::MemoryManager &gt; MemMgr, std::unique_ptr&lt; RuntimeDyld::LoadedObjectInfo &gt; LoadedObjInfo, std::unique_ptr&lt; SymbolDependenceMap &gt; Deps, Error Err)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae48ab9648a5872417294b117f6ac6ae3">handleRemoveResources</a> (JITDylib &amp;JD, ResourceKey K) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will be called <em>outside</em> the session lock. <a href="#ae48ab9648a5872417294b117f6ac6ae3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab38672b58ae7dc835c1dbaa4a5b6a486">handleTransferResources</a> (JITDylib &amp;JD, ResourceKey DstKey, ResourceKey SrcKey) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will be called <em>inside</em> the session lock. <a href="#ab38672b58ae7dc835c1dbaa4a5b6a486">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a95e428db7816717401fa38ed739cf">RTDyldLayerMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab12b46d32b79c457c6d1c254daae7fd5">GetMemoryManagerFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ce2422e5c0282a656bf837e7b068d5">GetMemoryManager</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a92f37749f33343857631cf5cf2eaf381">NotifyLoadedFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c212e4816f1e8bd09474a8fdd43b07">NotifyLoaded</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad748c83b5f6db0f5d30bd2d537b142fb">NotifyEmittedFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae49ae6d8dc2934a053af5028be0e5d30">NotifyEmitted</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2611ebd6ad631de34f26a4c9ebe6189e">ProcessAllSections</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5433b17ffcef48c0249a16deb73bfd">OverrideObjectFlags</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167e296cc63dc60670b12eb588329b47">AutoClaimObjectSymbols</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a>, std::vector&lt; MemoryManagerUP &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e953be20be5121391c6d555405d288">MemMgrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c24c2b01e431b873fcf03a54c5c1398">EventListeners</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac222431fb6f6e42de5ef61a2d3d8b86e">ID</a></td>
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


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GetMemoryManagerFunction {#ab12b46d32b79c457c6d1c254daae7fd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::RTDyldObjectLinkingLayer::GetMemoryManagerFunction = 
      unique_function&lt;std::unique_ptr&lt;RuntimeDyld::MemoryManager&gt;()&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### NotifyEmittedFunction {#ad748c83b5f6db0f5d30bd2d537b142fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::RTDyldObjectLinkingLayer::NotifyEmittedFunction =  std::function&lt;void(
      MaterializationResponsibility &amp;R, std::unique_ptr&lt;MemoryBuffer&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Functor for receiving finalization notifications.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### NotifyLoadedFunction {#a92f37749f33343857631cf5cf2eaf381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::RTDyldObjectLinkingLayer::NotifyLoadedFunction =  std::function&lt;void(
      MaterializationResponsibility &amp;R, const object::ObjectFile &amp;Obj,
      const RuntimeDyld::LoadedObjectInfo &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Functor for receiving object-loaded notifications.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### MemoryManagerUP {#a468e0ea5d0a4c8c4b3fb7b92a3df32f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::RTDyldObjectLinkingLayer::MemoryManagerUP =  std::unique_ptr&lt;RuntimeDyld::MemoryManager&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RTDyldObjectLinkingLayer() {#a265854b41dc442be1d29e1a5b7043cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::RTDyldObjectLinkingLayer::RTDyldObjectLinkingLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="#ab12b46d32b79c457c6d1c254daae7fd5">GetMemoryManagerFunction</a> GetMemoryManager)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> with the given NotifyLoaded, and NotifyEmitted functors.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#aa00c8d49e29326e8271a16b3f782b8a4">llvm::orc::ExecutionSession::registerResourceManager</a>.</p>


<p>Referenced by <a href="#a01dc8d414e17519d1760908746b27692">setNotifyLoaded</a> and <a href="#ac3fa547646c5f32600aa7336df436ae5">setProcessAllSections</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RTDyldObjectLinkingLayer() {#a744114ff64c7fdccce17d2e0c0755f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::RTDyldObjectLinkingLayer::~RTDyldObjectLinkingLayer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a640efdfe6f9a9949a292dc894222e8f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::RTDyldObjectLinkingLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the object.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a6d8cec64deb620b732a8a6922c327cf7">llvm::JITSymbolFlags::fromObjectSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9260a191f038a1fc705963675e349441">llvm::jitLinkForORC</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a771f3523463fc179b4e89f60841a23b8">llvm::object::SymbolRef::ST_File</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### registerJITEventListener() {#ae241d975e5b085fc6762f8f50e5d9add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::RTDyldObjectLinkingLayer::registerJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a>.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### setAutoClaimResponsibilityForObjectSymbols() {#aa5fd9509ea64f5d3780326dea9b50424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTDyldObjectLinkingLayer &amp; llvm::orc::RTDyldObjectLinkingLayer::setAutoClaimResponsibilityForObjectSymbols (bool AutoClaimObjectSymbols)</td>
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

<p>If set, this <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> instance will claim responsibility for any symbols provided by a given object file that were not already in the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance.</p>


<p>Setting this flag allows higher-level program representations (e.g. LLVM IR) to be added based on only a subset of the symbols they provide, without having to write intervening layers to scan and add the additional symbols. This trades diagnostic quality for convenience however: If all symbols are enumerated up-front then clashes can be detected and reported early (and usually deterministically). If this option is set, clashes for the additional symbols may not be detected until late, and detection may depend on the flow of control through JIT'd code. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> with care.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### setNotifyEmitted() {#a237b2f36c0eb917c38e7a31cc4d25b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTDyldObjectLinkingLayer &amp; llvm::orc::RTDyldObjectLinkingLayer::setNotifyEmitted (<a href="#ad748c83b5f6db0f5d30bd2d537b142fb">NotifyEmittedFunction</a> NotifyEmitted)</td>
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

<p>Set the NotifyEmitted callback.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### setNotifyLoaded() {#a01dc8d414e17519d1760908746b27692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTDyldObjectLinkingLayer &amp; llvm::orc::RTDyldObjectLinkingLayer::setNotifyLoaded (<a href="#a92f37749f33343857631cf5cf2eaf381">NotifyLoadedFunction</a> NotifyLoaded)</td>
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

<p>Set the NotifyLoaded callback.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>


<p>Reference <a href="#a265854b41dc442be1d29e1a5b7043cc4">RTDyldObjectLinkingLayer</a>.</p>

</div>
</div>

### setOverrideObjectFlagsWithResponsibilityFlags() {#ac4f7c81b37c4f8db5f4579cb667cb31a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTDyldObjectLinkingLayer &amp; llvm::orc::RTDyldObjectLinkingLayer::setOverrideObjectFlagsWithResponsibilityFlags (bool OverrideObjectFlags)</td>
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

<p>Instructs this RTDyldLinkingLayer2 instance to override the symbol flags returned by <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a> for any given object file with the flags supplied by the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance.</p>


<p>This is a workaround to support symbol visibility in <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a>, which does not use the libObject's SF_Exported flag. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> only when generating / adding <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> object files.</p>


<p>FIXME: We should be able to remove this if/when <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> properly tracks exported symbols.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### setProcessAllSections() {#ac3fa547646c5f32600aa7336df436ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTDyldObjectLinkingLayer &amp; llvm::orc::RTDyldObjectLinkingLayer::setProcessAllSections (bool ProcessAllSections)</td>
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

<p>Set the 'ProcessAllSections' flag.</p>


<p>If set to true, all sections in each object file will be allocated using the memory manager, rather than just the sections required for execution.</p>


<p>This is kludgy, and may be removed in the future.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>


<p>Reference <a href="#a265854b41dc442be1d29e1a5b7043cc4">RTDyldObjectLinkingLayer</a>.</p>

</div>
</div>

### unregisterJITEventListener() {#aa44eb942afaa83011358c9d4eed3fbc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::RTDyldObjectLinkingLayer::unregisterJITEventListener (<a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unregister a <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener">JITEventListener</a>.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### handleRemoveResources() {#ae48ab9648a5872417294b117f6ac6ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::RTDyldObjectLinkingLayer::handleRemoveResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> K)</td>
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


<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>

</div>
</div>

### handleTransferResources() {#ab38672b58ae7dc835c1dbaa4a5b6a486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::RTDyldObjectLinkingLayer::handleTransferResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> DstK, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> SrcK)</td>
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


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>

</div>
</div>

### onObjEmit() {#a8005f40544f15b7cacf4899e8178f5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::RTDyldObjectLinkingLayer::onObjEmit (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; R, <a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &gt; O, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &gt; MemMgr, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &gt; LoadedObjInfo, std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad4c600dd1184757dace1280e114f5b15">SymbolDependenceMap</a> &gt; Deps, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>

</div>
</div>

### onObjLoad() {#aecef07dfec6b78ec8f7a7dbd32a4c8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::RTDyldObjectLinkingLayer::onObjLoad (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/memorymanager">RuntimeDyld::MemoryManager</a> &amp; MemMgr, <a href="/web-llvm/docs/api/classes/llvm/runtimedyld/loadedobjectinfo">RuntimeDyld::LoadedObjectInfo</a> &amp; LoadedObjInfo, std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/jitevaluatedsymbol">JITEvaluatedSymbol</a> &gt; Resolved, std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; InternalSymbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AutoClaimObjectSymbols {#a167e296cc63dc60670b12eb588329b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::RTDyldObjectLinkingLayer::AutoClaimObjectSymbols = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### EventListeners {#a3c24c2b01e431b873fcf03a54c5c1398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;JITEventListener *&gt; llvm::orc::RTDyldObjectLinkingLayer::EventListeners</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### GetMemoryManager {#a15ce2422e5c0282a656bf837e7b068d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetMemoryManagerFunction llvm::orc::RTDyldObjectLinkingLayer::GetMemoryManager</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### MemMgrs {#a43e953be20be5121391c6d555405d288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ResourceKey, std::vector&lt;MemoryManagerUP&gt; &gt; llvm::orc::RTDyldObjectLinkingLayer::MemMgrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### NotifyEmitted {#ae49ae6d8dc2934a053af5028be0e5d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NotifyEmittedFunction llvm::orc::RTDyldObjectLinkingLayer::NotifyEmitted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### NotifyLoaded {#ae0c212e4816f1e8bd09474a8fdd43b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NotifyLoadedFunction llvm::orc::RTDyldObjectLinkingLayer::NotifyLoaded</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### OverrideObjectFlags {#abc5433b17ffcef48c0249a16deb73bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::RTDyldObjectLinkingLayer::OverrideObjectFlags = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### ProcessAllSections {#a2611ebd6ad631de34f26a4c9ebe6189e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::RTDyldObjectLinkingLayer::ProcessAllSections = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

### RTDyldLayerMutex {#a50a95e428db7816717401fa38ed739cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::RTDyldObjectLinkingLayer::RTDyldLayerMutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ac222431fb6f6e42de5ef61a2d3d8b86e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::orc::RTDyldObjectLinkingLayer::ID</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/rtdyldobjectlinkinglayer-h">RTDyldObjectLinkingLayer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/rtdyldobjectlinkinglayer-cpp">RTDyldObjectLinkingLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
