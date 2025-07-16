---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/debugobjectmanagerplugin
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DebugObjectManagerPlugin` Class Reference

<p>Creates and manages DebugObjects for JITLink artifacts. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::DebugObjectManagerPlugin { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">llvm/ExecutionEngine/Orc/DebugObjectManagerPlugin.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ObjectLinkingLayer::Plugin</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f6d746bd15817d2bd53a218c9b75535">OwnedDebugObject</a> = std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject">DebugObject</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6859199292075b7a74f94aef8bd0a1c">DebugObjectManagerPlugin</a> (ExecutionSession &amp;ES, std::unique_ptr&lt; DebugObjectRegistrar &gt; Target)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425692d9da5a7144a11bbd4a12d3befd">DebugObjectManagerPlugin</a> (ExecutionSession &amp;ES, std::unique_ptr&lt; DebugObjectRegistrar &gt; Target, bool RequireDebugSections, bool AutoRegisterCode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the plugin to submit DebugObjects for JITLink artifacts. <a href="#a425692d9da5a7144a11bbd4a12d3befd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d08d65e4a9851911bda6f48091b7042">~DebugObjectManagerPlugin</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3d04daa67fdb97d7c6adb095fd9b85">notifyMaterializing</a> (MaterializationResponsibility &amp;MR, jitlink::LinkGraph &amp;G, jitlink::JITLinkContext &amp;Ctx, MemoryBufferRef InputObject) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778eb8f8c5516bfed164b60b1594d632">notifyEmitted</a> (MaterializationResponsibility &amp;MR) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a24c1efd3e1604d378e7a1482bb6de3">notifyFailed</a> (MaterializationResponsibility &amp;MR) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08990f110a9a374bbac36366d6d8e320">notifyRemovingResources</a> (JITDylib &amp;JD, ResourceKey K) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a184ef71d4418c2a54aad454f621c39dd">notifyTransferringResources</a> (JITDylib &amp;JD, ResourceKey DstKey, ResourceKey SrcKey) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf15a05cfd44aa92db5db5251a6f3631">modifyPassConfig</a> (MaterializationResponsibility &amp;MR, jitlink::LinkGraph &amp;LG, jitlink::PassConfiguration &amp;PassConfig) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f9559ec86a080939659a9f589dc5cf5">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> *, OwnedDebugObject &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177000d4f4ba8bd6113001cf8dda98fa">PendingObjs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a>, std::vector&lt; OwnedDebugObject &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4e7b76bf821b082fa0a3d83112eca48">RegisteredObjs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285bfe99869ecdf120b82f2ebc698806">PendingObjsLock</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633ab20f8b8b58271edf6f1b442669d5">RegisteredObjsLock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectregistrar">DebugObjectRegistrar</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b897e7d234d5b7a2d6b7b75c1c042f2">Target</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481745162076395dbac6c81ea28fe02f">RequireDebugSections</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e6b1d22913981147f36b593f324d96">AutoRegisterCode</a></td>
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

<p>Creates and manages DebugObjects for JITLink artifacts.</p>


<p>DebugObjects are created when linking for a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> starts. They are pending as long as materialization is in progress.</p>


<p>There can only be one pending <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject">DebugObject</a> per <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a>. If materialization fails, pending DebugObjects are discarded.</p>


<p>Once executable code for the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> is emitted, the corresponding <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject">DebugObject</a> is finalized to target memory and the provided <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectregistrar">DebugObjectRegistrar</a> is notified. Ownership of DebugObjects remains with the plugin.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### OwnedDebugObject {#a3f6d746bd15817d2bd53a218c9b75535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::DebugObjectManagerPlugin::OwnedDebugObject =  std::unique_ptr&lt;DebugObject&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DebugObjectManagerPlugin() {#ac6859199292075b7a74f94aef8bd0a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::DebugObjectManagerPlugin::DebugObjectManagerPlugin (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectregistrar">DebugObjectRegistrar</a> &gt; Target)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="#ac6859199292075b7a74f94aef8bd0a1c">DebugObjectManagerPlugin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#ac6859199292075b7a74f94aef8bd0a1c">DebugObjectManagerPlugin</a> and <a href="#a425692d9da5a7144a11bbd4a12d3befd">DebugObjectManagerPlugin</a>.</p>

</div>
</div>

### DebugObjectManagerPlugin() {#a425692d9da5a7144a11bbd4a12d3befd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::DebugObjectManagerPlugin::DebugObjectManagerPlugin (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectregistrar">DebugObjectRegistrar</a> &gt; Target, bool RequireDebugSections, bool AutoRegisterCode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the plugin to submit DebugObjects for JITLink artifacts.</p>


<p>For all options the recommended setting is true.</p>


<p>RequireDebugSections: Submit debug objects to the executor only if they contain actual debug info. Turning this off may allow minimal debugging based on raw symbol names. Note that this may cause significant memory and transport overhead for objects built with a release configuration.</p>


<p>AutoRegisterCode: Notify the debugger for each new debug object. This is a good default mode, but it may cause significant overhead when adding many modules in sequence. When turning this off, the user has to issue the call to <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp/#acfc836ae108641ea6231b8d9def3a15a">__jit_debug_register_code()</a> on the executor side manually.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="#ac6859199292075b7a74f94aef8bd0a1c">DebugObjectManagerPlugin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DebugObjectManagerPlugin() {#a7d08d65e4a9851911bda6f48091b7042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::DebugObjectManagerPlugin::~DebugObjectManagerPlugin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### modifyPassConfig() {#abf15a05cfd44aa92db5db5251a6f3631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::DebugObjectManagerPlugin::modifyPassConfig (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; LG, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">jitlink::PassConfiguration</a> &amp; PassConfig)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject/#a34e2dc18068261d4f692c2b66648040a">llvm::orc::DebugObject::hasFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration/#a084adb14a6ed485ceafa7aeb5ddcdba9">llvm::jitlink::PassConfiguration::PostAllocationPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a559001955d0887af6200e615e38992e2a84493ea663f7fbef7ae24b6074dbe9af">llvm::orc::ReportFinalSectionLoadAddresses</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debugobject/#acf578478148b09a5ce32995f4f72e7b3">llvm::orc::DebugObject::reportSectionTargetMemoryRange</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ac48009c99a3fdb9c6c3ebd54abd1ff79">llvm::jitlink::LinkGraph::sections</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### notifyEmitted() {#a778eb8f8c5516bfed164b60b1594d632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::DebugObjectManagerPlugin::notifyEmitted (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>, definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility/#a5212856dfb6ccde003f082318cfb4e65">llvm::orc::MaterializationResponsibility::withResourceKeyDo</a>.</p>

</div>
</div>

### notifyFailed() {#a5a24c1efd3e1604d378e7a1482bb6de3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::DebugObjectManagerPlugin::notifyFailed (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### notifyMaterializing() {#a8a3d04daa67fdb97d7c6adb095fd9b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::DebugObjectManagerPlugin::notifyMaterializing (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">jitlink::JITLinkContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> InputObject)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>, definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a415d8bb3bcda2c9129502a0852bb308a">llvm::orc::createDebugObjectFromBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a559001955d0887af6200e615e38992e2ae9d9ad54f546973ac0fc1f010dcefc98">llvm::orc::HasDebugSections</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### notifyRemovingResources() {#a08990f110a9a374bbac36366d6d8e320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::DebugObjectManagerPlugin::notifyRemovingResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>, definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### notifyTransferringResources() {#a184ef71d4418c2a54aad454f621c39dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::DebugObjectManagerPlugin::notifyTransferringResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> DstKey, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> SrcKey)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AutoRegisterCode {#a12e6b1d22913981147f36b593f324d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::DebugObjectManagerPlugin::AutoRegisterCode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

### ES {#a5f9559ec86a080939659a9f589dc5cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::DebugObjectManagerPlugin::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

### PendingObjs {#a177000d4f4ba8bd6113001cf8dda98fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;MaterializationResponsibility *, OwnedDebugObject&gt; llvm::orc::DebugObjectManagerPlugin::PendingObjs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

### PendingObjsLock {#a285bfe99869ecdf120b82f2ebc698806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::DebugObjectManagerPlugin::PendingObjsLock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

### RegisteredObjs {#ad4e7b76bf821b082fa0a3d83112eca48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;ResourceKey, std::vector&lt;OwnedDebugObject&gt; &gt; llvm::orc::DebugObjectManagerPlugin::RegisteredObjs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

### RegisteredObjsLock {#a633ab20f8b8b58271edf6f1b442669d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::DebugObjectManagerPlugin::RegisteredObjsLock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

### RequireDebugSections {#a481745162076395dbac6c81ea28fe02f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::DebugObjectManagerPlugin::RequireDebugSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

### Target {#a0b897e7d234d5b7a2d6b7b75c1c042f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DebugObjectRegistrar&gt; llvm::orc::DebugObjectManagerPlugin::Target</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugobjectmanagerplugin-h">DebugObjectManagerPlugin.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugobjectmanagerplugin-cpp">DebugObjectManagerPlugin.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
