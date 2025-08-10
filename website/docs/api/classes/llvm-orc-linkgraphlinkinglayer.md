---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/linkgraphlinkinglayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LinkGraphLinkingLayer` Class

<p><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> links LinkGraphs into the Executor using JITLink. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::LinkGraphLinkingLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">llvm/ExecutionEngine/Orc/LinkGraphLinkingLayer.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer">LinkGraphLayer</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/orc/objectlayer">ObjectLayer</a> implementation built on JITLink. <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d894b917ccd0671ad199bdc9f5ac175">FinalizedAlloc</a> = <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">jitlink::JITLinkMemoryManager::FinalizedAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad724ca2d7c9b366f039bd13c3d04dcd3">LinkGraphLinkingLayer</a> (ExecutionSession &amp;ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> using the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> instance's memory manager. <a href="#ad724ca2d7c9b366f039bd13c3d04dcd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c44b72f1eb7d86fc84b38a3f5e90db9">LinkGraphLinkingLayer</a> (ExecutionSession &amp;ES, jitlink::JITLinkMemoryManager &amp;MemMgr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> using a custom memory manager. <a href="#a5c44b72f1eb7d86fc84b38a3f5e90db9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0960a18b5222ff8dfaa402b42dbb1011">LinkGraphLinkingLayer</a> (ExecutionSession &amp;ES, std::unique_ptr&lt; jitlink::JITLinkMemoryManager &gt; MemMgr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a>. <a href="#a0960a18b5222ff8dfaa402b42dbb1011">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0523d9701683387ed51c9121d81bb14">~LinkGraphLinkingLayer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy the <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a>. <a href="#ac0523d9701683387ed51c9121d81bb14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ffb6063ef6e0886ce5edc8769b2617">addPlugin</a> (std::shared_ptr&lt; Plugin &gt; P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a plugin. <a href="#af2ffb6063ef6e0886ce5edc8769b2617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc37c4c8cfaf6346924ed90e7df38c4">removePlugin</a> (Plugin &amp;P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a plugin. <a href="#a4bc37c4c8cfaf6346924ed90e7df38c4">More...</a></p>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a749aed4686716faf9e149640e2e4071d">setOverrideObjectFlagsWithResponsibilityFlags</a> (bool OverrideObjectFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructs this LinkgraphLinkingLayer instance to override the symbol flags found in the LinkGraph with the flags supplied by the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance. <a href="#a749aed4686716faf9e149640e2e4071d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ee09093baf2b4dbb6fcabd6e869442">setAutoClaimResponsibilityForObjectSymbols</a> (bool AutoClaimObjectSymbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If set, this <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> instance will claim responsibility for any symbols provided by a given object file that were not already in the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance. <a href="#a42ee09093baf2b4dbb6fcabd6e869442">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

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

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c124f63002f22b0dfbc655baf85ff7f">recordFinalizedAlloc</a> (MaterializationResponsibility &amp;MR, FinalizedAlloc FA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae784d79fd84d7a0bd7c7f6a6c7e4415a">handleRemoveResources</a> (JITDylib &amp;JD, ResourceKey K) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will be called <em>outside</em> the session lock. <a href="#ae784d79fd84d7a0bd7c7f6a6c7e4415a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1af7eb172233957b31e31f86f8fcef">handleTransferResources</a> (JITDylib &amp;JD, ResourceKey DstKey, ResourceKey SrcKey) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will be called <em>inside</em> the session lock. <a href="#aea1af7eb172233957b31e31f86f8fcef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee84ff8561dcc47616711f6fb0847e4">ReturnObjectBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1260f11443fda95faa088eda685974">LayerMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaadbb2669f090fc00aed34afd76391f1">MemMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a147ed9c2e2a2a77dba52134534d115b7">MemMgrOwnership</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7657f9d64a5b58d61196fb50ccc78ff3">OverrideObjectFlags</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea1b7d70b061c7eb8a28fa860ce1cca">AutoClaimObjectSymbols</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a>, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6465b7133885a38313965e50f027d393">Allocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/plugin">Plugin</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadffe8bbacab4e75421b46f90332c111">Plugins</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> links LinkGraphs into the Executor using JITLink.</p>


<p>Clients can use this class to add LinkGraphs to an <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a>, and it serves as a base for the <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> that can link object files.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FinalizedAlloc {#a1d894b917ccd0671ad199bdc9f5ac175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::LinkGraphLinkingLayer::FinalizedAlloc =  jitlink::JITLinkMemoryManager::FinalizedAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LinkGraphLinkingLayer() {#ad724ca2d7c9b366f039bd13c3d04dcd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> using the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> instance's memory manager.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a203d1d7d9d7c584c8185c1c0147020c1">llvm::orc::LinkGraphLayer::LinkGraphLayer</a>.</p>


<p>Referenced by <a href="#af2ffb6063ef6e0886ce5edc8769b2617">addPlugin</a>, <a href="#a4da9675d079c8aff4abac6c5ca2bc4c2">emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx/#a073ebe5b6a1a0f6f62be31c4f24f73d5">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::JITLinkCtx</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer/#a569f84e25f4009b5c39a445b5311bf38">llvm::orc::ObjectLinkingLayer::ObjectLinkingLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer/#aa3e729ee8c040da41f4b7db4ceb010e5">llvm::orc::ObjectLinkingLayer::ObjectLinkingLayer</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer/#ae0c0b7ebcf08cd50930dd0a4040a2129">llvm::orc::ObjectLinkingLayer::ObjectLinkingLayer</a>.</p>

</div>
</div>

### LinkGraphLinkingLayer() {#a5c44b72f1eb7d86fc84b38a3f5e90db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &amp; MemMgr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> using a custom memory manager.</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a203d1d7d9d7c584c8185c1c0147020c1">llvm::orc::LinkGraphLayer::LinkGraphLayer</a>.</p>

</div>
</div>

### LinkGraphLinkingLayer() {#a0960a18b5222ff8dfaa402b42dbb1011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager">jitlink::JITLinkMemoryManager</a> &gt; MemMgr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a>.</p>


<p>Takes ownership of the given JITLinkMemoryManager. This method is a temporary hack to simplify co-existence with <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer">RTDyldObjectLinkingLayer</a> (which also owns its allocators).</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LinkGraphLinkingLayer() {#ac0523d9701683387ed51c9121d81bb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LinkGraphLinkingLayer::~LinkGraphLinkingLayer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy the <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a>.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#ab58270d4adca4a62c6721739e0f4c725">llvm::orc::ExecutionSession::deregisterResourceManager</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlayer/#a5cb70ce82cd664c0945a09a5477f4157">llvm::orc::LinkGraphLayer::getExecutionSession</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPlugin() {#af2ffb6063ef6e0886ce5edc8769b2617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphLinkingLayer &amp; llvm::orc::LinkGraphLinkingLayer::addPlugin (std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/plugin">Plugin</a> &gt; P)</td>
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

<p>Add a plugin.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>


<p>References <a href="#ad724ca2d7c9b366f039bd13c3d04dcd3">LinkGraphLinkingLayer</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

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

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#ad724ca2d7c9b366f039bd13c3d04dcd3">LinkGraphLinkingLayer</a>.</p>

</div>
</div>

### removePlugin() {#a4bc37c4c8cfaf6346924ed90e7df38c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::removePlugin (<a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/plugin">Plugin</a> &amp; P)</td>
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

<p>Remove a plugin.</p>


<p>This remove applies only to subsequent links (links already underway will continue to use the plugin), and does not of itself destroy the plugin – destruction will happen once all shared pointers (including those held by in-progress links) are destroyed.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### setAutoClaimResponsibilityForObjectSymbols() {#a42ee09093baf2b4dbb6fcabd6e869442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphLinkingLayer &amp; llvm::orc::LinkGraphLinkingLayer::setAutoClaimResponsibilityForObjectSymbols (bool AutoClaimObjectSymbols)</td>
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

<p>If set, this <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer">LinkGraphLinkingLayer</a> instance will claim responsibility for any symbols provided by a given object file that were not already in the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance.</p>


<p>Setting this flag allows higher-level program representations (e.g. LLVM IR) to be added based on only a subset of the symbols they provide, without having to write intervening layers to scan and add the additional symbols. This trades diagnostic quality for convenience however: If all symbols are enumerated up-front then clashes can be detected and reported early (and usually deterministically). If this option is set, clashes for the additional symbols may not be detected until late, and detection may depend on the flow of control through JIT'd code. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> with care.</p>


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

### setOverrideObjectFlagsWithResponsibilityFlags() {#a749aed4686716faf9e149640e2e4071d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphLinkingLayer &amp; llvm::orc::LinkGraphLinkingLayer::setOverrideObjectFlagsWithResponsibilityFlags (bool OverrideObjectFlags)</td>
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

<p>Instructs this LinkgraphLinkingLayer instance to override the symbol flags found in the LinkGraph with the flags supplied by the <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> instance.</p>


<p>This is a workaround to support symbol visibility in <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a>, which does not use the libObject's SF_Exported flag. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> only when generating / adding <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> object files.</p>


<p>FIXME: We should be able to remove this if/when <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> properly tracks exported symbols.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

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
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a LinkGraph with the given backing buffer.</p>


<p>This overload is intended for use by <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a>.</p>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### handleRemoveResources() {#ae784d79fd84d7a0bd7c7f6a6c7e4415a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLinkingLayer::handleRemoveResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> K)</td>
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


<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>, definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### handleTransferResources() {#aea1af7eb172233957b31e31f86f8fcef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LinkGraphLinkingLayer::handleTransferResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> DstK, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> SrcK)</td>
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


<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

### recordFinalizedAlloc() {#a6c124f63002f22b0dfbc655baf85ff7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLinkingLayer::recordFinalizedAlloc (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> FA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>, definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ReturnObjectBuffer {#a7ee84ff8561dcc47616711f6fb0847e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(std::unique_ptr&lt;MemoryBuffer&gt;)&gt; llvm::orc::LinkGraphLinkingLayer::ReturnObjectBuffer</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer/#a4969d2212f78f895fc8184d5a9613387">llvm::orc::ObjectLinkingLayer::setReturnObjectBuffer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocs {#a6465b7133885a38313965e50f027d393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ResourceKey, std::vector&lt;FinalizedAlloc&gt; &gt; llvm::orc::LinkGraphLinkingLayer::Allocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

### AutoClaimObjectSymbols {#a4ea1b7d70b061c7eb8a28fa860ce1cca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::LinkGraphLinkingLayer::AutoClaimObjectSymbols = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

### LayerMutex {#a3c1260f11443fda95faa088eda685974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::LinkGraphLinkingLayer::LayerMutex</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

### MemMgr {#aaadbb2669f090fc00aed34afd76391f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">jitlink::JITLinkMemoryManager&amp; llvm::orc::LinkGraphLinkingLayer::MemMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

### MemMgrOwnership {#a147ed9c2e2a2a77dba52134534d115b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;jitlink::JITLinkMemoryManager&gt; llvm::orc::LinkGraphLinkingLayer::MemMgrOwnership</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

### OverrideObjectFlags {#a7657f9d64a5b58d61196fb50ccc78ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::LinkGraphLinkingLayer::OverrideObjectFlags = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

### Plugins {#aadffe8bbacab4e75421b46f90332c111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;Plugin&gt; &gt; llvm::orc::LinkGraphLinkingLayer::Plugins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlinkinglayer-h">LinkGraphLinkingLayer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlinkinglayer-cpp">LinkGraphLinkingLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
