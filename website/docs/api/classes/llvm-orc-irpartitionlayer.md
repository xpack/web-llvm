---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/irpartitionlayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IRPartitionLayer` Class

<p>A layer that breaks up IR modules into smaller submodules that only contains looked up symbols. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::IRPartitionLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">llvm/ExecutionEngine/Orc/IRPartitionLayer.h</a>"
</div>

## Base class

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

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711d070e416c2146b2387262fc703591">GlobalValueSet</a> = std::set&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c5fdeb59c2b96e436bef5da73e87f9">PartitionFunction</a> = std::function&lt; std::optional&lt; <a href="#a711d070e416c2146b2387262fc703591">GlobalValueSet</a> &gt;(<a href="#a711d070e416c2146b2387262fc703591">GlobalValueSet</a> Requested)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Partitioning function. <a href="#a14c5fdeb59c2b96e436bef5da73e87f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af268832e921ee9d8bb7cd4f828d6be16">PartitioningIRMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf7323697c8d97d33f9c96099e9e7426">IRPartitionLayer</a> (ExecutionSession &amp;ES, IRLayer &amp;BaseLayer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer">IRPartitionLayer</a>. <a href="#abf7323697c8d97d33f9c96099e9e7426">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0da72f54d279e477b8c4e345ee7e19a">setPartitionFunction</a> (PartitionFunction Partition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the partition function. <a href="#af0da72f54d279e477b8c4e345ee7e19a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422aebce39fe92265115190c32de1312">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, ThreadSafeModule TSM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the given module. <a href="#a422aebce39fe92265115190c32de1312">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605d986e9b892770dfca2d84373732c6">cleanUpModule</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00efb1d475a4576bd7960e2bd9c2daef">expandPartition</a> (GlobalValueSet &amp;Partition)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b31a377cbb66ad7146eed2848f8d661">emitPartition</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, ThreadSafeModule TSM, IRMaterializationUnit::SymbolNameToDefinitionMap Defs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba3a29548081c810b0e1d476444372c">BaseLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a14c5fdeb59c2b96e436bef5da73e87f9">PartitionFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd1875b8397e998f887f2248fbea046">Partition</a> = <a href="#af4b6e5166c469c1a35960a5c838d381f">compileRequested</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbollinkagepromoter">SymbolLinkagePromoter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee65605af0a21a76a860d9790b8f81a2">PromoteSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="#a711d070e416c2146b2387262fc703591">GlobalValueSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b6e5166c469c1a35960a5c838d381f">compileRequested</a> (GlobalValueSet Requested)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Off-the-shelf partitioning which compiles all requested symbols (usually a single function at a time). <a href="#af4b6e5166c469c1a35960a5c838d381f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="#a711d070e416c2146b2387262fc703591">GlobalValueSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c9261ce51dd65ab4d3d3c8d2d29792">compileWholeModule</a> (GlobalValueSet Requested)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Off-the-shelf partitioning which compiles whole modules whenever any symbol in them is requested. <a href="#a50c9261ce51dd65ab4d3d3c8d2d29792">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A layer that breaks up IR modules into smaller submodules that only contains looked up symbols.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GlobalValueSet {#a711d070e416c2146b2387262fc703591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::IRPartitionLayer::GlobalValueSet =  std::set&lt;const GlobalValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>.</p>

</div>
</div>

### PartitionFunction {#a14c5fdeb59c2b96e436bef5da73e87f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::IRPartitionLayer::PartitionFunction = 
      std::function&lt;std::optional&lt;GlobalValueSet&gt;(GlobalValueSet Requested)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Partitioning function.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### PartitioningIRMaterializationUnit {#af268832e921ee9d8bb7cd4f828d6be16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/partitioningirmaterializationunit">PartitioningIRMaterializationUnit</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>.</p>


<p>Reference <a href="#af268832e921ee9d8bb7cd4f828d6be16">PartitioningIRMaterializationUnit</a>.</p>


<p>Referenced by <a href="#af268832e921ee9d8bb7cd4f828d6be16">PartitioningIRMaterializationUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IRPartitionLayer() {#abf7323697c8d97d33f9c96099e9e7426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRPartitionLayer::IRPartitionLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp; BaseLayer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer">IRPartitionLayer</a>.</p>

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#ae3cfe72cdaca15dbe4c360d8bcdb5207">llvm::orc::IRLayer::getManglingOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#a1141609d9c7e4bdd205bc09698ff51b3">llvm::orc::IRLayer::IRLayer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a422aebce39fe92265115190c32de1312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRPartitionLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
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


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#a88dfbca45a6353ce7c643414c0d945cf">llvm::orc::IRLayer::getExecutionSession</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#ae3cfe72cdaca15dbe4c360d8bcdb5207">llvm::orc::IRLayer::getManglingOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule/#a5dc53e9bbda9066a1ade839494fe0cd9">llvm::orc::ThreadSafeModule::withModuleDo</a>.</p>

</div>
</div>

### setPartitionFunction() {#af0da72f54d279e477b8c4e345ee7e19a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRPartitionLayer::setPartitionFunction (<a href="#a14c5fdeb59c2b96e436bef5da73e87f9">PartitionFunction</a> Partition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the partition function.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cleanUpModule() {#a605d986e9b892770dfca2d84373732c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRPartitionLayer::cleanUpModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

### emitPartition() {#a1b31a377cbb66ad7146eed2848f8d661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRPartitionLayer::emitPartition (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#acda17e0078ab60791c6e794f403b71ff">IRMaterializationUnit::SymbolNameToDefinitionMap</a> Defs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

### expandPartition() {#a00efb1d475a4576bd7960e2bd9c2daef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRPartitionLayer::expandPartition (<a href="#a711d070e416c2146b2387262fc703591">GlobalValueSet</a> &amp; Partition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseLayer {#a1ba3a29548081c810b0e1d476444372c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRLayer&amp; llvm::orc::IRPartitionLayer::BaseLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>.</p>

</div>
</div>

### Partition {#a9bd1875b8397e998f887f2248fbea046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PartitionFunction llvm::orc::IRPartitionLayer::Partition = <a href="#af4b6e5166c469c1a35960a5c838d381f">compileRequested</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>.</p>

</div>
</div>

### PromoteSymbols {#aee65605af0a21a76a860d9790b8f81a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolLinkagePromoter llvm::orc::IRPartitionLayer::PromoteSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### compileRequested() {#af4b6e5166c469c1a35960a5c838d381f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; IRPartitionLayer::GlobalValueSet &gt; IRPartitionLayer::compileRequested (<a href="#a711d070e416c2146b2387262fc703591">GlobalValueSet</a> Requested)</td>
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

<p>Off-the-shelf partitioning which compiles all requested symbols (usually a single function at a time).</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

### compileWholeModule() {#a50c9261ce51dd65ab4d3d3c8d2d29792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; IRPartitionLayer::GlobalValueSet &gt; IRPartitionLayer::compileWholeModule (<a href="#a711d070e416c2146b2387262fc703591">GlobalValueSet</a> Requested)</td>
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

<p>Off-the-shelf partitioning which compiles whole modules whenever any symbol in them is requested.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/irpartitionlayer-h">IRPartitionLayer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/irpartitionlayer-cpp">IRPartitionLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
