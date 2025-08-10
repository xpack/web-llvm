---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/objectlinkinglayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ObjectLinkingLayer` Class

<p>An <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> implementation built on JITLink. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::ObjectLinkingLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">llvm/ExecutionEngine/Orc/ObjectLinkingLayer.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> links LinkGraphs into the Executor using JITLink. <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286b2439c25722cee3d598c060a59e7d">ReturnObjectBufferFunction</a> = std::function&lt; void(std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb46f5a4d020b1f32c56f23c0ce74f6d">BaseObjectLayer</a> = <a href="/web-llvm/docs/api/classes/llvm/rttiextends">RTTIExtends</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a569f84e25f4009b5c39a445b5311bf38">ObjectLinkingLayer</a> (ExecutionSession &amp;ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> using the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> instance's memory manager. <a href="#a569f84e25f4009b5c39a445b5311bf38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e729ee8c040da41f4b7db4ceb010e5">ObjectLinkingLayer</a> (ExecutionSession &amp;ES, jitlink::JITLinkMemoryManager &amp;MemMgr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> using a custom memory manager. <a href="#aa3e729ee8c040da41f4b7db4ceb010e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c0b7ebcf08cd50930dd0a4040a2129">ObjectLinkingLayer</a> (ExecutionSession &amp;ES, std::unique_ptr&lt; jitlink::JITLinkMemoryManager &gt; MemMgr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a>. <a href="#ae0c0b7ebcf08cd50930dd0a4040a2129">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4969d2212f78f895fc8184d5a9613387">setReturnObjectBuffer</a> (ReturnObjectBufferFunction ReturnObjectBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set an object buffer return function. <a href="#a4969d2212f78f895fc8184d5a9613387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a964526f0df9bb7f08d8965630e63280f">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, std::unique_ptr&lt; MemoryBuffer &gt; O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an object file. <a href="#a964526f0df9bb7f08d8965630e63280f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4da9675d079c8aff4abac6c5ca2bc4c2">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, std::unique_ptr&lt; jitlink::LinkGraph &gt; G) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a LinkGraph. <a href="#a4da9675d079c8aff4abac6c5ca2bc4c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91b551e0adb2c3097bff3a776bf2722">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, std::unique_ptr&lt; jitlink::LinkGraph &gt; G, std::unique_ptr&lt; MemoryBuffer &gt; ObjBuf)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a LinkGraph with the given backing buffer. <a href="#aa91b551e0adb2c3097bff3a776bf2722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a14765d70bbf88934f2246fa3bf951">add</a> (ResourceTrackerSP RT, std::unique_ptr&lt; MemoryBuffer &gt; O, MaterializationUnit::Interface I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for the object file in the given memory buffer to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> for the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>. <a href="#af3a14765d70bbf88934f2246fa3bf951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972e1603fbdf3e039431a4bf34df6e03">add</a> (ResourceTrackerSP RT, std::unique_ptr&lt; MemoryBuffer &gt; O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for the object file in the given memory buffer to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> for the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>. <a href="#a972e1603fbdf3e039431a4bf34df6e03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446313e5f05f661d0d6462ceed1541ca">add</a> (JITDylib &amp;JD, std::unique_ptr&lt; MemoryBuffer &gt; O, MaterializationUnit::Interface I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for the object file in the given memory buffer to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a446313e5f05f661d0d6462ceed1541ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8710db633e1c0759d35acca81ad4a9b6">add</a> (JITDylib &amp;JD, std::unique_ptr&lt; MemoryBuffer &gt; O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for the object file in the given memory buffer to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a8710db633e1c0759d35acca81ad4a9b6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eae41d35e227d19a188c6b0287b9694">ID</a></td>
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

<p>An <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> implementation built on JITLink.</p>


<p>Clients can use this class to add relocatable object files to an <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>, and it typically serves as the base layer (underneath a compiling layer like <a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer">IRCompileLayer</a>) for the rest of the JIT.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ReturnObjectBufferFunction {#a286b2439c25722cee3d598c060a59e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ObjectLinkingLayer::ReturnObjectBufferFunction = 
      std::function&lt;void(std::unique_ptr&lt;MemoryBuffer&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### BaseObjectLayer {#aeb46f5a4d020b1f32c56f23c0ce74f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::ObjectLinkingLayer::BaseObjectLayer =  RTTIExtends&lt;ObjectLinkingLayer, ObjectLayer&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ObjectLinkingLayer() {#a569f84e25f4009b5c39a445b5311bf38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ObjectLinkingLayer::ObjectLinkingLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> using the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> instance's memory manager.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#ad724ca2d7c9b366f039bd13c3d04dcd3">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer</a>.</p>

</div>
</div>

### ObjectLinkingLayer() {#aa3e729ee8c040da41f4b7db4ceb010e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ObjectLinkingLayer::ObjectLinkingLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &amp; MemMgr)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> using a custom memory manager.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#ad724ca2d7c9b366f039bd13c3d04dcd3">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer</a>.</p>

</div>
</div>

### ObjectLinkingLayer() {#ae0c0b7ebcf08cd50930dd0a4040a2129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ObjectLinkingLayer::ObjectLinkingLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt; MemMgr)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a>.</p>


<p>Takes ownership of the given JITLinkMemoryManager. This method is a temporary hack to simplify co-existence with <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> (which also owns its allocators).</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#ad724ca2d7c9b366f039bd13c3d04dcd3">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#af3a14765d70bbf88934f2246fa3bf951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ObjectLayer::add (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; O, <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">MaterializationUnit::Interface</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for the object file in the given memory buffer to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> for the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>

</div>
</div>

### add() {#a972e1603fbdf3e039431a4bf34df6e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ObjectLayer::add (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for the object file in the given memory buffer to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> for the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>.</p>


<p>The interface for the object will be built using the default object interface builder.</p>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### add() {#a446313e5f05f661d0d6462ceed1541ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ObjectLayer::add (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; O, <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">MaterializationUnit::Interface</a> I)</td>
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

<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for the object file in the given memory buffer to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

### add() {#a8710db633e1c0759d35acca81ad4a9b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ObjectLayer::add (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> for the object file in the given memory buffer to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>The interface for the object will be built using the default object interface builder.</p>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer/#a95c5001be77bb9f4a63ae76d5e85bb2b">llvm::orc::ObjectLayer::ID</a>.</p>

</div>
</div>

### emit() {#a964526f0df9bb7f08d8965630e63280f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ObjectLinkingLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit an object file.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/objectlinkinglayer-cpp">ObjectLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aad60b2c2a2e09a361eac9a21327a8eaf">llvm::jitlink::createLinkGraphFromObject</a>, <a href="#a964526f0df9bb7f08d8965630e63280f">emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a5cb70ce82cd664c0945a09a5477f4157">llvm::orc::LinkGraphLayer::getExecutionSession</a>.</p>


<p>Referenced by <a href="#a964526f0df9bb7f08d8965630e63280f">emit</a>.</p>

</div>
</div>

### emit() {#a4da9675d079c8aff4abac6c5ca2bc4c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &gt; G)</td>
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

<p>Emit a LinkGraph.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>

</div>
</div>

### emit() {#aa91b551e0adb2c3097bff3a776bf2722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &gt; G, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; ObjBuf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a LinkGraph with the given backing buffer.</p>


<p>This overload is intended for use by <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a>.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>

</div>
</div>

### setReturnObjectBuffer() {#a4969d2212f78f895fc8184d5a9613387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ObjectLinkingLayer::setReturnObjectBuffer (<a href="#a286b2439c25722cee3d598c060a59e7d">ReturnObjectBufferFunction</a> ReturnObjectBuffer)</td>
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

<p>Set an object buffer return function.</p>


<p>By default object buffers are deleted once the JIT has linked them. If a return function is set then it will be called to transfer ownership of the buffer instead.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#a7ee84ff8561dcc47616711f6fb0847e4">llvm::orc::LinkGraphLinkingLayer::ReturnObjectBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a9eae41d35e227d19a188c6b0287b9694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::orc::ObjectLinkingLayer::ID</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/objectlinkinglayer-h">ObjectLinkingLayer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/objectlinkinglayer-cpp">ObjectLinkingLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
