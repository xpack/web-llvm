---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/epcgenericjitlinkmemorymanager/inflightalloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InFlightAlloc` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc">InFlightAlloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an allocation which has not been finalized yet. <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4eedec461fdf091ffa68dd803bf6cc3">SegInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/allocgroupsmallmap">AllocGroupSmallMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/epcgenericjitlinkmemorymanager/inflightalloc/seginfo">SegInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f99cffd10c253ae6ce5da12de53383a">InFlightAlloc</a> (EPCGenericJITLinkMemoryManager &amp;Parent, LinkGraph &amp;G, ExecutorAddr AllocAddr, SegInfoMap Segs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e3aa5ba4f76b3dc2a0c9bd4077ab11">finalize</a> (OnFinalizedFunction OnFinalize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called to transfer working memory to the target and apply finalization. <a href="#a00e3aa5ba4f76b3dc2a0c9bd4077ab11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be2c182f59edfb11705bcb46a6cc1da">abandon</a> (OnAbandonedFunction OnAbandoned) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called prior to finalization if the allocation should be abandoned. <a href="#a6be2c182f59edfb11705bcb46a6cc1da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager">EPCGenericJITLinkMemoryManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2bfbfb1b7722ca3870d052b714ff92">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdac237433dea19dfa9dc48b93f0abad">G</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace41623d25a9cdbfcb470190b312dc77">AllocAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad4eedec461fdf091ffa68dd803bf6cc3">SegInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520c81f8c46f55a4f411e32f914a0e83">Segs</a></td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SegInfoMap {#ad4eedec461fdf091ffa68dd803bf6cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::SegInfoMap =  AllocGroupSmallMap&lt;SegInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InFlightAlloc() {#a6f99cffd10c253ae6ce5da12de53383a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::InFlightAlloc (<a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager">EPCGenericJITLinkMemoryManager</a> &amp; Parent, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> AllocAddr, <a href="#ad4eedec461fdf091ffa68dd803bf6cc3">SegInfoMap</a> Segs)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager/#a802082bc67d1af66487f8e6feae2334f">llvm::orc::EPCGenericJITLinkMemoryManager::EPCGenericJITLinkMemoryManager</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### abandon() {#a6be2c182f59edfb11705bcb46a6cc1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::abandon (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc/#a4f3c1cf1871e9e99843174f7b8992849">OnAbandonedFunction</a> OnAbandoned)</td>
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

<p>Called prior to finalization if the allocation should be abandoned.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>.</p>

</div>
</div>

### finalize() {#a00e3aa5ba4f76b3dc2a0c9bd4077ab11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::finalize (<a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/inflightalloc/#a9f4c74c3c51697683582571ffc39d987">OnFinalizedFunction</a> OnFinalized)</td>
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

<p>Called to transfer working memory to the target and apply finalization.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/finalizerequest/#aa85c28825544c150ba63349d9c0cb7ce">llvm::orc::tpctypes::FinalizeRequest::Actions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/finalizerequest/#aa7cb8653a6dc958e3aaf84d92fc08b69">llvm::orc::tpctypes::FinalizeRequest::Segments</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllocAddr {#ace41623d25a9cdbfcb470190b312dc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::AllocAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

### G {#abdac237433dea19dfa9dc48b93f0abad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraph&amp; llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::G</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

### Parent {#a5d2bfbfb1b7722ca3870d052b714ff92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EPCGenericJITLinkMemoryManager&amp; llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

### Segs {#a520c81f8c46f55a4f411e32f914a0e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SegInfoMap llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::Segs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericjitlinkmemorymanager-cpp">EPCGenericJITLinkMemoryManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
