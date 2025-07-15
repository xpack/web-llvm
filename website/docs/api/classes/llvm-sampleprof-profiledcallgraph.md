---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/profiledcallgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ProfiledCallGraph` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::ProfiledCallGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">llvm/Transforms/IPO/ProfiledCallGraph.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bcc7eefa431e84d1636faf7d86fe225">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode/#a1ba04bfbe655da7d83d348727cca718c">ProfiledCallGraphNode::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5daf6edacb298caa44c8305b0b591a4">ProfiledCallGraph</a> (SampleProfileMap &amp;ProfileMap, uint64_t IgnoreColdCallThreshold=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae2ab44bcb9d9add7c351061ac8e6f6">ProfiledCallGraph</a> (SampleContextTracker &amp;ContextTracker, uint64_t IgnoreColdCallThreshold=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9bcc7eefa431e84d1636faf7d86fe225">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ddc9bdb077cf643f29ddd1320bafb4">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9bcc7eefa431e84d1636faf7d86fe225">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add34fd6645cc6eb20b5210117cd4f767">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode">ProfiledCallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4afbf3b4aab03e1777b67fd657d03cb5">getEntryNode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2f80085f5ee5fd2f1c262f067f8be2">addProfiledFunction</a> (FunctionId Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f267a62c56114a20d6a1da0121f625">addProfiledCall</a> (FunctionId CallerName, FunctionId CalleeName, uint64_t Weight=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77ad68d664184eb8673b0e7c0758930">addProfiledCalls</a> (const FunctionSamples &amp;Samples)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ff0def37742abb5b767e8800e6ac6c">trimColdEges</a> (uint64_t Threshold=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode">ProfiledCallGraphNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443e6d448c86565e10058ef49b657d8c">Root</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::list&lt; <a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode">ProfiledCallGraphNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3a1161d808a01548bc8e7eeee792154">ProfiledCallGraphNodeList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode">ProfiledCallGraphNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab885a59b94c9435d35b9a656cdbf141c">ProfiledFunctions</a></td>
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


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a9bcc7eefa431e84d1636faf7d86fe225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprof::ProfiledCallGraph::iterator =  ProfiledCallGraphNode::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ProfiledCallGraph() {#ae5daf6edacb298caa44c8305b0b591a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraph (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; ProfileMap, uint64_t IgnoreColdCallThreshold=0)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>.</p>

</div>
</div>

### ProfiledCallGraph() {#acae2ab44bcb9d9add7c351061ac8e6f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraph (<a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker">SampleContextTracker</a> &amp; ContextTracker, uint64_t IgnoreColdCallThreshold=0)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>References <a href="#abb2f80085f5ee5fd2f1c262f067f8be2">addProfiledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#acbd03b8899e421aa9cab2850607a1b13">llvm::sampleprof::FunctionSamples::findCallTargetMapAt</a>, <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#a0f957c3b9a4c1c915ff992784abea057">llvm::ContextTrieNode::getAllChildContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a7ff8c2d016ae9169f35cdd1d1aaa1564">llvm::sampleprof::FunctionSamples::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#af757985efc97179779ea3fc9e84f4735">llvm::sampleprof::FunctionSamples::getHeadSamplesEstimate</a> and <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a42ff5d19f024e956412b151ae3a095ec">llvm::SampleContextTracker::getRootContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addProfiledFunction() {#abb2f80085f5ee5fd2f1c262f067f8be2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::ProfiledCallGraph::addProfiledFunction (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> Name)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Referenced by <a href="#acae2ab44bcb9d9add7c351061ac8e6f6">ProfiledCallGraph</a>.</p>

</div>
</div>

### begin() {#ae0ddc9bdb077cf643f29ddd1320bafb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sampleprof::ProfiledCallGraph::begin ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f1a5a865e618ee33971da5868fe61069/#adc2cb75bfde47d5fa2eb96ccfb96292f">llvm::GraphTraits&lt; ProfiledCallGraph * &gt;::nodes_begin</a>.</p>

</div>
</div>

### end() {#add34fd6645cc6eb20b5210117cd4f767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sampleprof::ProfiledCallGraph::end ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f1a5a865e618ee33971da5868fe61069/#aba229770fe3c5e039e0fe34fa3a541f8">llvm::GraphTraits&lt; ProfiledCallGraph * &gt;::nodes_end</a>.</p>

</div>
</div>

### getEntryNode() {#a4afbf3b4aab03e1777b67fd657d03cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfiledCallGraphNode * llvm::sampleprof::ProfiledCallGraph::getEntryNode ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f1a5a865e618ee33971da5868fe61069/#aa34b0507daeb588235560612f44a4062">llvm::GraphTraits&lt; ProfiledCallGraph * &gt;::getEntryNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addProfiledCall() {#a53f267a62c56114a20d6a1da0121f625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::ProfiledCallGraph::addProfiledCall (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> CallerName, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> CalleeName, uint64_t Weight=0)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>

</div>
</div>

### addProfiledCalls() {#ae77ad68d664184eb8673b0e7c0758930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::ProfiledCallGraph::addProfiledCalls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> &amp; Samples)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>

</div>
</div>

### trimColdEges() {#a39ff0def37742abb5b767e8800e6ac6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::ProfiledCallGraph::trimColdEges (uint64_t Threshold=0)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ProfiledCallGraphNodeList {#aa3a1161d808a01548bc8e7eeee792154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::list&lt;ProfiledCallGraphNode&gt; llvm::sampleprof::ProfiledCallGraph::ProfiledCallGraphNodeList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>

</div>
</div>

### ProfiledFunctions {#ab885a59b94c9435d35b9a656cdbf141c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashKeyMap&lt;llvm::DenseMap, FunctionId, ProfiledCallGraphNode*&gt; llvm::sampleprof::ProfiledCallGraph::ProfiledFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>

</div>
</div>

### Root {#a443e6d448c86565e10058ef49b657d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfiledCallGraphNode llvm::sampleprof::ProfiledCallGraph::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
