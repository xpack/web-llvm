---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/shared/allocactioncallpair
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AllocActionCallPair` Struct Reference

<p>A pair of WrapperFunctionCalls, one to be run at finalization time, one to be run at deallocation time. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::orc::shared::AllocActionCallPair { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">llvm/ExecutionEngine/Orc/Shared/AllocationActions.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa71439aac13433d1b23c0a3e636721d7">Finalize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a733e0c5d6f3653dc2e39b95ebee54fb9">Dealloc</a></td>
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

<p>A pair of WrapperFunctionCalls, one to be run at finalization time, one to be run at deallocation time.</p>


<p>AllocActionCallPairs should be constructed for paired operations (e.g. __register_ehframe and __deregister_ehframe for eh-frame registration). See comments for <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a6da0b5cb8e68a6cc791a183d9d38aae0">AllocActions</a> for execution ordering.</p>


<p>For unpaired operations one or the other member can be left unused, as AllocationActionCalls with an FnAddr of zero will be skipped.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Dealloc {#a733e0c5d6f3653dc2e39b95ebee54fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WrapperFunctionCall llvm::orc::shared::AllocActionCallPair::Dealloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7dec749f93c51446f39c26c3bd42b2d1/#a4ffae4808351f6d6a7c57c39b381b3f7">llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7dec749f93c51446f39c26c3bd42b2d1/#a633668f79490e4395f8586ad80471ead">llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7dec749f93c51446f39c26c3bd42b2d1/#a7a123b37ad930479ef8d8b820e345b2b">llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::size</a>.</p>

</div>
</div>

### Finalize {#aa71439aac13433d1b23c0a3e636721d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WrapperFunctionCall llvm::orc::shared::AllocActionCallPair::Finalize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7dec749f93c51446f39c26c3bd42b2d1/#a4ffae4808351f6d6a7c57c39b381b3f7">llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7dec749f93c51446f39c26c3bd42b2d1/#a633668f79490e4395f8586ad80471ead">llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7dec749f93c51446f39c26c3bd42b2d1/#a7a123b37ad930479ef8d8b820e345b2b">llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
