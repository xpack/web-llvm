---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/lllazyjit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLLazyJIT` Class Reference

<p>An extended version of <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> that supports lazy function-at-a-time compilation of LLVM IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::LLLazyJIT { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">llvm/ExecutionEngine/Orc/LLJIT.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pre-fabricated ORC JIT stack that can serve as an alternative to <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename, typename, typename&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0e42999670094cbbd1ea6ce38df5280">LLJITBuilderSetters</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8113d9c3f1046cdebf307c012efb9d17">LLLazyJIT</a> (LLLazyJITBuilderState &amp;S, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a1a6619833ad50ce35cd7c05207af67">setPartitionFunction</a> (IRPartitionLayer::PartitionFunction Partition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the partition function. <a href="#a3a1a6619833ad50ce35cd7c05207af67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer">CompileOnDemandLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2df3c64cf5150e641758eb92a54bbc">getCompileOnDemandLayer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the on-demand layer. <a href="#a5b2df3c64cf5150e641758eb92a54bbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6fca2ea17d5c43653424337abc473a">addLazyIRModule</a> (JITDylib &amp;JD, ThreadSafeModule M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module to be lazily compiled to <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> JD. <a href="#afa6fca2ea17d5c43653424337abc473a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59892e6011cedcd35f68338b72cd5f31">addLazyIRModule</a> (ThreadSafeModule M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module to be lazily compiled to the main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a59892e6011cedcd35f68338b72cd5f31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a501a1842f621c0a938fccbbd6df4d564">LCTMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer">IRPartitionLayer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a15e90d3545c65c293b57b08f615244">IPLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer">CompileOnDemandLayer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a244340f2e9efaacc1122f7c1e2653851">CODLayer</a></td>
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

<p>An extended version of <a href="/web-llvm/docs/api/classes/llvm/orc/lljit">LLJIT</a> that supports lazy function-at-a-time compilation of LLVM IR.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LLJITBuilderSetters {#af0e42999670094cbbd1ea6ce38df5280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuildersetters">LLJITBuilderSetters</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>Reference <a href="#af0e42999670094cbbd1ea6ce38df5280">LLJITBuilderSetters</a>.</p>


<p>Referenced by <a href="#af0e42999670094cbbd1ea6ce38df5280">LLJITBuilderSetters</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LLLazyJIT() {#a8113d9c3f1046cdebf307c012efb9d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::LLLazyJIT::LLLazyJIT (<a href="/web-llvm/docs/api/classes/llvm/orc/lllazyjitbuilderstate">LLLazyJITBuilderState</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 1295 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLazyIRModule() {#afa6fca2ea17d5c43653424337abc473a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLLazyJIT::addLazyIRModule (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a module to be lazily compiled to <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> JD.</p>

<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>, definition at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule/#a5dc53e9bbda9066a1ade839494fe0cd9">llvm::orc::ThreadSafeModule::withModuleDo</a>.</p>


<p>Referenced by <a href="#a59892e6011cedcd35f68338b72cd5f31">addLazyIRModule</a>.</p>

</div>
</div>

### addLazyIRModule() {#a59892e6011cedcd35f68338b72cd5f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::LLLazyJIT::addLazyIRModule (<a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> M)</td>
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

<p>Add a module to be lazily compiled to the main <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>


<p>References <a href="#afa6fca2ea17d5c43653424337abc473a">addLazyIRModule</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a4403c6d0172443bd06841dc65467d6da">llvm::orc::LLJIT::Main</a>.</p>

</div>
</div>

### getCompileOnDemandLayer() {#a5b2df3c64cf5150e641758eb92a54bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileOnDemandLayer &amp; llvm::orc::LLLazyJIT::getCompileOnDemandLayer ()</td>
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

<p>Returns a reference to the on-demand layer.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

### setPartitionFunction() {#a3a1a6619833ad50ce35cd7c05207af67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::LLLazyJIT::setPartitionFunction (<a href="/web-llvm/docs/api/classes/llvm/orc/irpartitionlayer/#a14c5fdeb59c2b96e436bef5da73e87f9">IRPartitionLayer::PartitionFunction</a> Partition)</td>
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

<p>Sets the partition function.</p>

<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CODLayer {#a244340f2e9efaacc1122f7c1e2653851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CompileOnDemandLayer&gt; llvm::orc::LLLazyJIT::CODLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

### IPLayer {#a4a15e90d3545c65c293b57b08f615244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;IRPartitionLayer&gt; llvm::orc::LLLazyJIT::IPLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

### LCTMgr {#a501a1842f621c0a938fccbbd6df4d564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LazyCallThroughManager&gt; llvm::orc::LLLazyJIT::LCTMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/lljit-h">LLJIT.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lljit-cpp">LLJIT.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
