---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/irlayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IRLayer` Class Reference

<p>Interface for layers that accept LLVM IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::IRLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">llvm/ExecutionEngine/Orc/Layer.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer">CompileOnDemandLayer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer">IRCompileLayer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer">IRPartitionLayer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A layer that breaks up IR modules into smaller submodules that only contains looked up symbols. <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer">IRSpeculationLayer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer">IRTransformLayer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A layer that applies a transform to emitted modules. <a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer">ReOptimizeLayer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1141609d9c7e4bdd205bc09698ff51b3">IRLayer</a> (ExecutionSession &amp;ES, const IRSymbolMapper::ManglingOptions *&amp;MO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e7356e785b11cc1798ed30cb43f87e">~IRLayer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88dfbca45a6353ce7c643414c0d945cf">getExecutionSession</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> for this layer. <a href="#a88dfbca45a6353ce7c643414c0d945cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions">IRSymbolMapper::ManglingOptions</a> *&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3cfe72cdaca15dbe4c360d8bcdb5207">getManglingOptions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the mangling options for this layer. <a href="#ae3cfe72cdaca15dbe4c360d8bcdb5207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c064a010c4aaeb1df5ed5d5f4ef6de8">setCloneToNewContextOnEmit</a> (bool CloneToNewContextOnEmit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the CloneToNewContextOnEmit flag (false by default). <a href="#a9c064a010c4aaeb1df5ed5d5f4ef6de8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee70ef9d8989f16d25260d172b7f2bd9">getCloneToNewContextOnEmit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the current value of the CloneToNewContextOnEmit flag. <a href="#aee70ef9d8989f16d25260d172b7f2bd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d40572359c36d1ee718fe3b5ccb89e">add</a> (ResourceTrackerSP RT, ThreadSafeModule TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a MaterializatinoUnit representing the given IR to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> targeted by the given tracker. <a href="#a55d40572359c36d1ee718fe3b5ccb89e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad7763ba39a875c20de25ee9f47eba17">add</a> (JITDylib &amp;JD, ThreadSafeModule TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> representing the given IR to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#aad7763ba39a875c20de25ee9f47eba17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3432ce8c435e826875e4476505a4c2fc">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, ThreadSafeModule TSM)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit should materialize the given IR. <a href="#a3432ce8c435e826875e4476505a4c2fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46395ac2cabd0dd70182f04b8c24065d">CloneToNewContextOnEmit</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3fe7f434a1e51749411c39f9f31388">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions">IRSymbolMapper::ManglingOptions</a> *&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77ce44eb4fbac0c6be0969a24285014d">MO</a></td>
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

<p>Interface for layers that accept LLVM IR.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IRLayer() {#a1141609d9c7e4bdd205bc09698ff51b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::IRLayer::IRLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions">IRSymbolMapper::ManglingOptions</a> *&amp; MO)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer/#a60b3749f91b86e4e27270e69d82fb330">llvm::orc::CompileOnDemandLayer::CompileOnDemandLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer/#a94115e2997e96ff56c60b2a468f792b0">llvm::orc::IRCompileLayer::IRCompileLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer/#abf7323697c8d97d33f9c96099e9e7426">llvm::orc::IRPartitionLayer::IRPartitionLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#a3c29e3ba0c6b387670e92692754a9f82">llvm::orc::IRSpeculationLayer::IRSpeculationLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer/#ad8fed5aecfe2723e59e80ecf65cbab2b">llvm::orc::IRTransformLayer::IRTransformLayer</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a0b568a5599904f23d7fab8e9e45663af">llvm::orc::ReOptimizeLayer::ReOptimizeLayer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~IRLayer() {#a73e7356e785b11cc1798ed30cb43f87e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::IRLayer::~IRLayer ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a55d40572359c36d1ee718fe3b5ccb89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::IRLayer::add (<a href="/web-llvm/docs/api/namespaces/llvm/orc/#a25b487d71ccd2a8f38131e2b21c5d612">ResourceTrackerSP</a> RT, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
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

<p>Add a MaterializatinoUnit representing the given IR to the <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> targeted by the given tracker.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae3cfe72cdaca15dbe4c360d8bcdb5207">getManglingOptions</a>.</p>


<p>Referenced by <a href="#aad7763ba39a875c20de25ee9f47eba17">add</a>.</p>

</div>
</div>

### add() {#aad7763ba39a875c20de25ee9f47eba17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::IRLayer::add (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
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

<p>Adds a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> representing the given IR to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>If RT is not specif</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<p>References <a href="#a55d40572359c36d1ee718fe3b5ccb89e">add</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae3cfc9a4e792646e7108ebae425804f0">llvm::orc::JITDylib::getDefaultResourceTracker</a>.</p>

</div>
</div>

### emit() {#a3432ce8c435e826875e4476505a4c2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::orc::IRLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit should materialize the given IR.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

### getCloneToNewContextOnEmit() {#aee70ef9d8989f16d25260d172b7f2bd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::IRLayer::getCloneToNewContextOnEmit ()</td>
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

<p>Returns the current value of the CloneToNewContextOnEmit flag.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

### getExecutionSession() {#a88dfbca45a6353ce7c643414c0d945cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::IRLayer::getExecutionSession ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> for this layer.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer/#a58cc5a656f5d4cc0a32d58494dcb860b">llvm::orc::CompileOnDemandLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ircompilelayer/#a176fd0ce1f0e28e675e04c05c7716a03">llvm::orc::IRCompileLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer/#a422aebce39fe92265115190c32de1312">llvm::orc::IRPartitionLayer::emit</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer/#a6f4ae51591df573638504e97f54a5321">llvm::orc::IRTransformLayer::emit</a>.</p>

</div>
</div>

### getManglingOptions() {#ae3cfe72cdaca15dbe4c360d8bcdb5207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRSymbolMapper::ManglingOptions *&amp; llvm::orc::IRLayer::getManglingOptions ()</td>
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

<p>Get the mangling options for this layer.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<p>Referenced by <a href="#a55d40572359c36d1ee718fe3b5ccb89e">add</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer/#a60b3749f91b86e4e27270e69d82fb330">llvm::orc::CompileOnDemandLayer::CompileOnDemandLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer/#a58cc5a656f5d4cc0a32d58494dcb860b">llvm::orc::CompileOnDemandLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer/#a422aebce39fe92265115190c32de1312">llvm::orc::IRPartitionLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer/#abf7323697c8d97d33f9c96099e9e7426">llvm::orc::IRPartitionLayer::IRPartitionLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#a3c29e3ba0c6b387670e92692754a9f82">llvm::orc::IRSpeculationLayer::IRSpeculationLayer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irtransformlayer/#ad8fed5aecfe2723e59e80ecf65cbab2b">llvm::orc::IRTransformLayer::IRTransformLayer</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a0b568a5599904f23d7fab8e9e45663af">llvm::orc::ReOptimizeLayer::ReOptimizeLayer</a>.</p>

</div>
</div>

### setCloneToNewContextOnEmit() {#a9c064a010c4aaeb1df5ed5d5f4ef6de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::IRLayer::setCloneToNewContextOnEmit (bool CloneToNewContextOnEmit)</td>
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

<p>Sets the CloneToNewContextOnEmit flag (false by default).</p>


<p>When set, IR modules added to this layer will be cloned on to a new context before emit is called. This can be used by clients who want to load all IR using one <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> (to save memory via type and constant uniquing), but want to move Modules to fresh contexts before compiling them to enable concurrent compilation. Single threaded clients, or clients who load every module on a new context, need not set this.</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CloneToNewContextOnEmit {#a46395ac2cabd0dd70182f04b8c24065d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::IRLayer::CloneToNewContextOnEmit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

### ES {#a4f3fe7f434a1e51749411c39f9f31388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::IRLayer::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

### MO {#a77ce44eb4fbac0c6be0969a24285014d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRSymbolMapper::ManglingOptions*&amp; llvm::orc::IRLayer::MO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
