---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-7dec749f93c51446f39c26c3bd42b2d1
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SPSSerializationTraits` Class Template Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::SPSSerializationTraits&lt;SPSAllocActionCallPair, AllocActionCallPair&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">llvm/ExecutionEngine/Orc/Shared/AllocationActions.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347866b04bcb42fcb0fec4ab651e1f3a">AL</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple/#a4ac958780d60988306a818239d07657c">SPSAllocActionCallPair::AsArgList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a123b37ad930479ef8d8b820e345b2b">size</a> (const AllocActionCallPair &amp;AAP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633668f79490e4395f8586ad80471ead">serialize</a> (SPSOutputBuffer &amp;OB, const AllocActionCallPair &amp;AAP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ffae4808351f6d6a7c57c39b381b3f7">deserialize</a> (SPSInputBuffer &amp;IB, AllocActionCallPair &amp;AAP)</td>
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


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AL {#a347866b04bcb42fcb0fec4ab651e1f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::AL =  SPSAllocActionCallPair::AsArgList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a4ffae4808351f6d6a7c57c39b381b3f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair">AllocActionCallPair</a> &amp; AAP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair/#a733e0c5d6f3653dc2e39b95ebee54fb9">llvm::orc::shared::AllocActionCallPair::Dealloc</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair/#aa71439aac13433d1b23c0a3e636721d7">llvm::orc::shared::AllocActionCallPair::Finalize</a>.</p>

</div>
</div>

### serialize() {#a633668f79490e4395f8586ad80471ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair">AllocActionCallPair</a> &amp; AAP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair/#a733e0c5d6f3653dc2e39b95ebee54fb9">llvm::orc::shared::AllocActionCallPair::Dealloc</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair/#aa71439aac13433d1b23c0a3e636721d7">llvm::orc::shared::AllocActionCallPair::Finalize</a>.</p>

</div>
</div>

### size() {#a7a123b37ad930479ef8d8b820e345b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSAllocActionCallPair, AllocActionCallPair &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair">AllocActionCallPair</a> &amp; AAP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair/#a733e0c5d6f3653dc2e39b95ebee54fb9">llvm::orc::shared::AllocActionCallPair::Dealloc</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair/#aa71439aac13433d1b23c0a3e636721d7">llvm::orc::shared::AllocActionCallPair::Finalize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
