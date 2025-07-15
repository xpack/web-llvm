---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/linkgraphlayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LinkGraphLayer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::LinkGraphLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">llvm/ExecutionEngine/Orc/LinkGraphLayer.h</a>"
</div>

## Derived Classes

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203d1d7d9d7c584c8185c1c0147020c1">LinkGraphLayer</a> (ExecutionSession &amp;ES)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef83ab741aeb76edb5071b46e6c06677">~LinkGraphLayer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb70ce82cd664c0945a09a5477f4157">getExecutionSession</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67fe8582f6ab5381bac8a8f11435f831">add</a> (ResourceTrackerSP RT, std::unique_ptr&lt; jitlink::LinkGraph &gt; G, MaterializationUnit::Interface I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a LinkGraph to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> for the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>. <a href="#a67fe8582f6ab5381bac8a8f11435f831">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8660df7a4a67faec7f008ad622b50104">add</a> (ResourceTrackerSP RT, std::unique_ptr&lt; jitlink::LinkGraph &gt; G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a LinkGraph to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> for the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>. <a href="#a8660df7a4a67faec7f008ad622b50104">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645e7dc16b19043db73e13534780b159">add</a> (JITDylib &amp;JD, std::unique_ptr&lt; jitlink::LinkGraph &gt; G, MaterializationUnit::Interface I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a LinkGraph to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a645e7dc16b19043db73e13534780b159">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b8c181245131d2ad620fe11fdb47ad">add</a> (JITDylib &amp;JD, std::unique_ptr&lt; jitlink::LinkGraph &gt; G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a LinkGraph to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#aa8b8c181245131d2ad620fe11fdb47ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85bd7e0e09310eb6f4265ff278b1e5f0">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, std::unique_ptr&lt; jitlink::LinkGraph &gt; G)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit should materialize the given IR. <a href="#a85bd7e0e09310eb6f4265ff278b1e5f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">MaterializationUnit::Interface</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c62bffede0829515a1dc63f3aeb9982">getInterface</a> (jitlink::LinkGraph &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the interface for the given LinkGraph. <a href="#a8c62bffede0829515a1dc63f3aeb9982">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a2d42216a8db693b1c8b2fc1713064">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887d81ead3575bdc3e37196b020c177e">Counter</a> {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fe4a708e2a83ed2e9aaf8c3d909a1b">getJITSymbolFlagsForSymbol</a> (jitlink::Symbol &amp;Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> for the given symbol. <a href="#a99fe4a708e2a83ed2e9aaf8c3d909a1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LinkGraphLayer() {#a203d1d7d9d7c584c8185c1c0147020c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LinkGraphLayer::LinkGraphLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#ad724ca2d7c9b366f039bd13c3d04dcd3">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#a5c44b72f1eb7d86fc84b38a3f5e90db9">llvm::orc::LinkGraphLinkingLayer::LinkGraphLinkingLayer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LinkGraphLayer() {#aef83ab741aeb76edb5071b46e6c06677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LinkGraphLayer::~LinkGraphLayer ()</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a67fe8582f6ab5381bac8a8f11435f831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLayer::add (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &gt; G, <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">MaterializationUnit::Interface</a> I)</td>
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

<p>Adds a LinkGraph to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> for the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aa8b8c181245131d2ad620fe11fdb47ad">add</a>, <a href="#a645e7dc16b19043db73e13534780b159">add</a> and <a href="#a8660df7a4a67faec7f008ad622b50104">add</a>.</p>

</div>
</div>

### add() {#a8660df7a4a67faec7f008ad622b50104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLayer::add (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &gt; G)</td>
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

<p>Adds a LinkGraph to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> for the given <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a>.</p>


<p>The interface for the graph will be built using getLinkGraphInterface.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>


<p>References <a href="#a67fe8582f6ab5381bac8a8f11435f831">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a8c62bffede0829515a1dc63f3aeb9982">getInterface</a>.</p>

</div>
</div>

### add() {#a645e7dc16b19043db73e13534780b159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLayer::add (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &gt; G, <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface">MaterializationUnit::Interface</a> I)</td>
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

<p>Adds a LinkGraph to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>


<p>References <a href="#a67fe8582f6ab5381bac8a8f11435f831">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae3cfc9a4e792646e7108ebae425804f0">llvm::orc::JITDylib::getDefaultResourceTracker</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### add() {#aa8b8c181245131d2ad620fe11fdb47ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LinkGraphLayer::add (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &gt; G)</td>
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

<p>Adds a LinkGraph to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>The interface for the object will be built using getLinkGraphInterface.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>


<p>References <a href="#a67fe8582f6ab5381bac8a8f11435f831">add</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae3cfc9a4e792646e7108ebae425804f0">llvm::orc::JITDylib::getDefaultResourceTracker</a>.</p>

</div>
</div>

### emit() {#a85bd7e0e09310eb6f4265ff278b1e5f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::LinkGraphLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &gt; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit should materialize the given IR.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### getExecutionSession() {#a5cb70ce82cd664c0945a09a5477f4157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::LinkGraphLayer::getExecutionSession ()</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer/#a964526f0df9bb7f08d8965630e63280f">llvm::orc::ObjectLinkingLayer::emit</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/#ac0523d9701683387ed51c9121d81bb14">llvm::orc::LinkGraphLinkingLayer::~LinkGraphLinkingLayer</a>.</p>

</div>
</div>

### getInterface() {#a8c62bffede0829515a1dc63f3aeb9982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaterializationUnit::Interface llvm::orc::LinkGraphLayer::getInterface (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the interface for the given LinkGraph.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlayer-cpp">LinkGraphLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a99fe4a708e2a83ed2e9aaf8c3d909a1b">getJITSymbolFlagsForSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface/#ae84ce7aa9f7158e55dde1e5c71e9451b">llvm::orc::MaterializationUnit::Interface::InitSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda509820290d57f333403f490dde7316f4">llvm::jitlink::Local</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/materializationunit/interface/#a01cc8573508b1f5e29fdb4ea78cf2bae">llvm::orc::MaterializationUnit::Interface::SymbolFlags</a>.</p>


<p>Referenced by <a href="#a8660df7a4a67faec7f008ad622b50104">add</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Counter {#a887d81ead3575bdc3e37196b020c177e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;uint64_t&gt; llvm::orc::LinkGraphLayer::Counter {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>

</div>
</div>

### ES {#a05a2d42216a8db693b1c8b2fc1713064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::LinkGraphLayer::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getJITSymbolFlagsForSymbol() {#a99fe4a708e2a83ed2e9aaf8c3d909a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags llvm::orc::LinkGraphLayer::getJITSymbolFlagsForSymbol (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">jitlink::Symbol</a> &amp; Sym)</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> for the given symbol.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlayer-cpp">LinkGraphLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5">llvm::JITSymbolFlags::Callable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda7a1920d61156abc05a60135aefe8bc67">llvm::jitlink::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a76430b8581e0d1748b8615cf8130c283">llvm::jitlink::Symbol::getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a51c33c919f5a66e0d0b9814b6b049363">llvm::jitlink::Symbol::getScope</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a15d4df0ad60a70e4074ccf11dfdc0164">llvm::jitlink::Symbol::isCallable</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbab78b49be60a6b5faf277860a45753ea5">llvm::JITSymbolFlags::MaterializationSideEffectsOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#adb322dc6826cf005531ccfdf666260fda1fee46ed8695ca5c28a7c177dae57a8a">llvm::jitlink::SideEffectsOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55fa7324e3727807d95037eb19d304fd91ec">llvm::jitlink::Weak</a> and <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397">llvm::JITSymbolFlags::Weak</a>.</p>


<p>Referenced by <a href="#a8c62bffede0829515a1dc63f3aeb9982">getInterface</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx/#a569ab99e0391c055c321e1088a303335">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::notifyResolved</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/linkgraphlayer-h">LinkGraphLayer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/linkgraphlayer-cpp">LinkGraphLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
