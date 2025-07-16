---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/callgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CallGraph` Class Reference

<p>The basic data container for the call graph of a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a></span> of IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CallGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">llvm/Analysis/CallGraph.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adebb19fa17fb98f5d8b9c9165d4f9424">iterator</a> = FunctionMapTy::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab893e545dbdee17eef97fa346d456130">const_iterator</a> = FunctionMapTy::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33df16b263460a814d3c0f2922f2f905">FunctionMapTy</a> = std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea64fa4d98ef692a8295cafd6c909b39">CallGraph</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ea19ddab9e23e24bd9e5490c662d628">CallGraph</a> (CallGraph &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7714337a3d1ff0cf280e803484154243">~CallGraph</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1ff3ad4f2fac884451f93fd9c33a01">operator[]</a> (const Function *F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the call graph node for the provided function. <a href="#a3c1ff3ad4f2fac884451f93fd9c33a01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1f077862e30e2b8507736ec2a34cb3">operator[]</a> (const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the call graph node for the provided function. <a href="#aee1f077862e30e2b8507736ec2a34cb3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a066faade450399db380381c68e8b32">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d20c4438dad4a93f2720a8866bf10d5">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6148a4c6df56af41c63c0c3a798c447">getModule</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the module the call graph corresponds to. <a href="#ac6148a4c6df56af41c63c0c3a798c447">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd0f61134b8387fbc0eb555142ad377">invalidate</a> (Module &amp;, const PreservedAnalyses &amp;PA, ModuleAnalysisManager::Invalidator &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adebb19fa17fb98f5d8b9c9165d4f9424">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeef5828c39699b414d1c5bb2996eccd">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adebb19fa17fb98f5d8b9c9165d4f9424">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4255a1c63f75411c1b78245d65e746">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab893e545dbdee17eef97fa346d456130">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89427cd9bf1a11ae4028af71e7a65fb9">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab893e545dbdee17eef97fa346d456130">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc762c29f1ac1f7e14e2d6fce922df11">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae16e2f40048685872258d2a9d03d849a">getExternalCallingNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a></span> which is used to represent undetermined calls into the callgraph. <a href="#ae16e2f40048685872258d2a9d03d849a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd0599a7756561b720a3b6c336dca4e8">getCallsExternalNode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68ea42c57e2aa0ba52f29dd6a7da4f3">ReplaceExternalCallEdge</a> (CallGraphNode *Old, CallGraphNode *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Old node has been deleted, and New is to be used in its place, update the ExternalCallingNode. <a href="#af68ea42c57e2aa0ba52f29dd6a7da4f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ae28b08e292f846fb954e805e533ce">removeFunctionFromModule</a> (CallGraphNode *CGN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink the function from this module, returning it. <a href="#a10ae28b08e292f846fb954e805e533ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91eed9199c5b0e56a1fc1f3487431c9c">getOrInsertFunction</a> (const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to operator[], but this will insert a new <a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> for <span class="doxyComputerOutput">F</span> if one does not already exist. <a href="#a91eed9199c5b0e56a1fc1f3487431c9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bfb7a1d16a4e74c64e5fc59d18b06f5">populateCallGraphNode</a> (CallGraphNode *CGN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate <span class="doxyComputerOutput">CGN</span> based on the calls inside the associated function. <a href="#a6bfb7a1d16a4e74c64e5fc59d18b06f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c8c41cb23ce1fd4f890daea132235e">addToCallGraph</a> (Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a function to the call graph, and link the node to all of the functions that it calls. <a href="#a87c8c41cb23ce1fd4f890daea132235e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8875fe410d658349263f15495106af15">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FunctionMapTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceca108260ae919bc30f84b9b81acd19">FunctionMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map from <span class="doxyComputerOutput">Function*</span> to <span class="doxyComputerOutput">CallGraphNode*</span>. <a href="#aceca108260ae919bc30f84b9b81acd19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb169460132d8a63c8935d97119c06a6">ExternalCallingNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node has edges to all external functions and those internal functions that have their address taken. <a href="#abb169460132d8a63c8935d97119c06a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594d8992b3d0209d493ba6e8ba654cb4">CallsExternalNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node has edges to it from all functions making indirect calls or calling an external function. <a href="#a594d8992b3d0209d493ba6e8ba654cb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The basic data container for the call graph of a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a></span> of IR.</p>


<p>This class exposes both the interface to the call graph for a module of IR.</p>


<p>The core call graph itself can also be updated to reflect changes to the IR.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ab893e545dbdee17eef97fa346d456130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CallGraph::const_iterator =  FunctionMapTy::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

### iterator {#adebb19fa17fb98f5d8b9c9165d4f9424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CallGraph::iterator =  FunctionMapTy::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### FunctionMapTy {#a33df16b263460a814d3c0f2922f2f905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CallGraph::FunctionMapTy = 
      std::map&lt;const Function *, std::unique_ptr&lt;CallGraphNode&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CallGraph() {#aea64fa4d98ef692a8295cafd6c909b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraph::CallGraph (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>References <a href="#a87c8c41cb23ce1fd4f890daea132235e">addToCallGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a91eed9199c5b0e56a1fc1f3487431c9c">getOrInsertFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73d11a138c9386cfbf4cc6ae5368e001">llvm::isDbgInfoIntrinsic</a>.</p>


<p>Referenced by <a href="#a6ea19ddab9e23e24bd9e5490c662d628">CallGraph</a>.</p>

</div>
</div>

### CallGraph() {#a6ea19ddab9e23e24bd9e5490c662d628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraph::CallGraph (<a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp;&amp; Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>References <a href="#aea64fa4d98ef692a8295cafd6c909b39">CallGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CallGraph() {#a7714337a3d1ff0cf280e803484154243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraph::~CallGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a3c1ff3ad4f2fac884451f93fd9c33a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallGraphNode * llvm::CallGraph::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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

<p>Returns the call graph node for the provided function.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### operator\[\]() {#aee1f077862e30e2b8507736ec2a34cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraphNode * llvm::CallGraph::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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

<p>Returns the call graph node for the provided function.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addToCallGraph() {#a87c8c41cb23ce1fd4f890daea132235e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraph::addToCallGraph (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a function to the call graph, and link the node to all of the functions that it calls.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a91eed9199c5b0e56a1fc1f3487431c9c">getOrInsertFunction</a> and <a href="#a6bfb7a1d16a4e74c64e5fc59d18b06f5">populateCallGraphNode</a>.</p>


<p>Referenced by <a href="#aea64fa4d98ef692a8295cafd6c909b39">CallGraph</a>.</p>

</div>
</div>

### begin() {#aaeef5828c39699b414d1c5bb2996eccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::CallGraph::begin ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d29484a2fc9ce2965ec195a43e4532a6/#acdb4bb60fa1ca7434f0e05b0be685a8c">llvm::GraphTraits&lt; CallGraph * &gt;::nodes_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02fb7f36a5622815e386262c1f910406/#aa68d60ea21e7c35c8e87758eaa757621">llvm::GraphTraits&lt; CallGraphDOTInfo * &gt;::nodes_begin</a> and <a href="/web-llvm/docs/api/structs/llvm/graphtraits-621fe9cffc0d763fde38d15ddc38dc99/#a2f7a8f2eb54cd98e569e80ef72071dfa">llvm::GraphTraits&lt; const CallGraph * &gt;::nodes_begin</a>.</p>

</div>
</div>

### begin() {#a89427cd9bf1a11ae4028af71e7a65fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::CallGraph::begin ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

### dump() {#a3d20c4438dad4a93f2720a8866bf10d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void CallGraph::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a1a066faade450399db380381c68e8b32">print</a>.</p>

</div>
</div>

### end() {#a8d4255a1c63f75411c1b78245d65e746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::CallGraph::end ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d29484a2fc9ce2965ec195a43e4532a6/#ad7e791791af9e34189310eabe3cbe8cf">llvm::GraphTraits&lt; CallGraph * &gt;::nodes_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02fb7f36a5622815e386262c1f910406/#ad20ad894a9bf9470be9b0990240c7d88">llvm::GraphTraits&lt; CallGraphDOTInfo * &gt;::nodes_end</a> and <a href="/web-llvm/docs/api/structs/llvm/graphtraits-621fe9cffc0d763fde38d15ddc38dc99/#a6efe32afe64b88375ee3de7a4786194f">llvm::GraphTraits&lt; const CallGraph * &gt;::nodes_end</a>.</p>

</div>
</div>

### end() {#afc762c29f1ac1f7e14e2d6fce922df11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::CallGraph::end ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

### getCallsExternalNode() {#abd0599a7756561b720a3b6c336dca4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraphNode * llvm::CallGraph::getCallsExternalNode ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a> and <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#af124dac4967882b35a6e3afafc30da8a">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getNodeLabel</a>.</p>

</div>
</div>

### getExternalCallingNode() {#ae16e2f40048685872258d2a9d03d849a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraphNode * llvm::CallGraph::getExternalCallingNode ()</td>
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

<p>Returns the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a></span> which is used to represent undetermined calls into the callgraph.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d29484a2fc9ce2965ec195a43e4532a6/#af82b3bcb53806555dffa0e5fc6cba568">llvm::GraphTraits&lt; CallGraph * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-02fb7f36a5622815e386262c1f910406/#a07c7ffaa3df4635a451ea088ee1a5971">llvm::GraphTraits&lt; CallGraphDOTInfo * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-621fe9cffc0d763fde38d15ddc38dc99/#a1c8b4cbcdd33a9bcf3818f498e36bccc">llvm::GraphTraits&lt; const CallGraph * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#af124dac4967882b35a6e3afafc30da8a">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getNodeLabel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6b42b6fca05063155c689008d30a2751">llvm::AMDGPU::removeFnAttrFromReachable</a>.</p>

</div>
</div>

### getModule() {#ac6148a4c6df56af41c63c0c3a798c447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module &amp; llvm::CallGraph::getModule ()</td>
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

<p>Returns the module the call graph corresponds to.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#ae8841a51c6b06a2a29e8e51024e9bc19">anonymous{CallGraphSCCPass.cpp}::CGPassManager::doFinalization</a> and <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a2330998b675c05167dc0a94a9f197599">anonymous{CallGraphSCCPass.cpp}::CGPassManager::doInitialization</a>.</p>

</div>
</div>

### getOrInsertFunction() {#a91eed9199c5b0e56a1fc1f3487431c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraphNode * CallGraph::getOrInsertFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to operator[], but this will insert a new <a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> for <span class="doxyComputerOutput">F</span> if one does not already exist.</p>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a87c8c41cb23ce1fd4f890daea132235e">addToCallGraph</a>, <a href="#aea64fa4d98ef692a8295cafd6c909b39">CallGraph</a> and <a href="#a6bfb7a1d16a4e74c64e5fc59d18b06f5">populateCallGraphNode</a>.</p>

</div>
</div>

### invalidate() {#aafd0f61134b8387fbc0eb555142ad377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallGraph::invalidate (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, ModuleAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>

</div>
</div>

### populateCallGraphNode() {#a6bfb7a1d16a4e74c64e5fc59d18b06f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraph::populateCallGraphNode (<a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> * CGN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate <span class="doxyComputerOutput">CGN</span> based on the calls inside the associated function.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa273a7c3463d96e7f545c205ff3b50e3">llvm::forEachCallbackFunction</a>, <a href="#a91eed9199c5b0e56a1fc1f3487431c9c">getOrInsertFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73d11a138c9386cfbf4cc6ae5368e001">llvm::isDbgInfoIntrinsic</a>.</p>


<p>Referenced by <a href="#a87c8c41cb23ce1fd4f890daea132235e">addToCallGraph</a>.</p>

</div>
</div>

### print() {#a1a066faade450399db380381c68e8b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraph::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a3d20c4438dad4a93f2720a8866bf10d5">dump</a>.</p>

</div>
</div>

### removeFunctionFromModule() {#a10ae28b08e292f846fb954e805e533ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * CallGraph::removeFunctionFromModule (<a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> * CGN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink the function from this module, returning it.</p>


<p>Because this removes the function from the module, the call graph node is destroyed. This is only valid if the function does not call any other functions (ie, there are no edges in it's CGN). The easiest way to do this is to dropAllReferences before calling this.</p>


<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphnode/#a4ca2bd9b898b17df1ddaedb6b60323ef">llvm::CallGraphNode::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#add1b62fd0110c8c97673ed9a66603f05">llvm::Function::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/callgraphnode/#aab57958df49938baa45ec4fb890cebac">llvm::CallGraphNode::getFunction</a>.</p>

</div>
</div>

### ReplaceExternalCallEdge() {#af68ea42c57e2aa0ba52f29dd6a7da4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraph::ReplaceExternalCallEdge (<a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/callgraphnode">CallGraphNode</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Old node has been deleted, and New is to be used in its place, update the ExternalCallingNode.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallsExternalNode {#a594d8992b3d0209d493ba6e8ba654cb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CallGraphNode&gt; llvm::CallGraph::CallsExternalNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This node has edges to it from all functions making indirect calls or calling an external function.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

### ExternalCallingNode {#abb169460132d8a63c8935d97119c06a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallGraphNode* llvm::CallGraph::ExternalCallingNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This node has edges to all external functions and those internal functions that have their address taken.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

### FunctionMap {#aceca108260ae919bc30f84b9b81acd19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionMapTy llvm::CallGraph::FunctionMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map from <span class="doxyComputerOutput">Function*</span> to <span class="doxyComputerOutput">CallGraphNode*</span>.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

### M {#a8875fe410d658349263f15495106af15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; llvm::CallGraph::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">CallGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraph-cpp">CallGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
