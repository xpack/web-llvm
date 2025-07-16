---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/divergencepropagator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DivergencePropagator` Class Template Reference

<p>Compute divergence starting with a divergent branch. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename ContextT&gt;
class llvm::DivergencePropagator&lt;ContextT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">llvm/ADT/GenericUniformityImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> = typename ContextT::BlockT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b68822e3cb504bb1308d3c49d324451">DominatorTreeT</a> = typename ContextT::DominatorTreeT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4cbe6976f132b9a1039b49ffb2f3346c">FunctionT</a> = typename ContextT::FunctionT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2c498bed5b911ac568ac12ef3e880bc">ValueRefT</a> = typename ContextT::ValueRefT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a582bf57e481e9df41fc6a96af7eb972e">CycleInfoT</a> = <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfo">GenericCycleInfo</a>&lt; ContextT &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae1a44d6de22b0cd39412dcb2b3992a51">CycleT</a> = typename CycleInfoT::CycleT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a866e9bb2588b808f927062b16a23e06c">ModifiedPO</a> = <a href="/web-llvm/docs/api/classes/llvm/modifiedpostorder">ModifiedPostOrder</a>&lt; ContextT &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11cbba4d2f2a8364bf42215db3b325ef">SyncDependenceAnalysisT</a> = <a href="/web-llvm/docs/api/classes/llvm/genericsyncdependenceanalysis">GenericSyncDependenceAnalysis</a>&lt; ContextT &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af1a21e935b457b387f4f54517b1fb662">DivergenceDescriptorT</a> = typename SyncDependenceAnalysisT::DivergenceDescriptor</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a01930caab49dcf984bb93ccb8f932e50">BlockLabelMapT</a> = typename SyncDependenceAnalysisT::BlockLabelMap</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aefcd4588c26dc8f0236290c1e2af58d9">DivergencePropagator</a> (const ModifiedPO &amp;CyclePOT, const DominatorTreeT &amp;DT, const CycleInfoT &amp;CI, const BlockT &amp;DivTermBlock)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4c72630ffc031d0c72c3e0a3af2bcbda">printDefs</a> (raw_ostream &amp;Out)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26ba4f21aacd60c82d606f8d6830cb1a">computeJoin</a> (const BlockT &amp;SuccBlock, const BlockT &amp;PushedLabel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac9b09a5db2a5ebed6739fad98a47b232">visitCycleExitEdge</a> (const BlockT &amp;ExitBlock, const BlockT &amp;Label)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af14ecd129e3da10ff3276dca2149a1c8">visitEdge</a> (const BlockT &amp;SuccBlock, const BlockT &amp;Label)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8395f502f0ee748b8c9708747d72a6c">computeJoinPoints</a> () -&gt; std::unique_ptr&lt; <a href="#af1a21e935b457b387f4f54517b1fb662">DivergenceDescriptorT</a> &gt;</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a866e9bb2588b808f927062b16a23e06c">ModifiedPO</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a058ad83af142fe89600382d7ebd6d043">CyclePOT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a1b68822e3cb504bb1308d3c49d324451">DominatorTreeT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82f5d9a55d60641dce49b2c606949759">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a582bf57e481e9df41fc6a96af7eb972e">CycleInfoT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79d4b0e0dde4d0ce765038ab1b0b3eeb">CI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ab9f4c02e1305316eef4eb1ec559f90">DivTermBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ContextT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba32182b54dcb9bc0b1dffadfe4cc7f5">Context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparsebitvector">SparseBitVector</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac80d6ceb5ca63123bccddc966f43696f">FreshLabels</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::unique_ptr&lt; <a href="#af1a21e935b457b387f4f54517b1fb662">DivergenceDescriptorT</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ce1c6241dbd4a80b91672bb4aa5e514">DivDesc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ContextT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a01930caab49dcf984bb93ccb8f932e50">BlockLabelMapT</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd0cfe9eadc0468f0b6be367ed4f59da">BlockLabels</a></td>
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

<p>Compute divergence starting with a divergent branch.</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockLabelMapT {#a01930caab49dcf984bb93ccb8f932e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::BlockLabelMapT =  typename SyncDependenceAnalysisT::BlockLabelMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### BlockT {#ae07136789e9c05c9e4c4e926edc670a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::BlockT =  typename ContextT::BlockT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### CycleInfoT {#a582bf57e481e9df41fc6a96af7eb972e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::CycleInfoT =  GenericCycleInfo&lt;ContextT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### CycleT {#ae1a44d6de22b0cd39412dcb2b3992a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::CycleT =  typename CycleInfoT::CycleT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### DivergenceDescriptorT {#af1a21e935b457b387f4f54517b1fb662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::DivergenceDescriptorT = 
      typename SyncDependenceAnalysisT::DivergenceDescriptor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### DominatorTreeT {#a1b68822e3cb504bb1308d3c49d324451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::DominatorTreeT =  typename ContextT::DominatorTreeT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### FunctionT {#a4cbe6976f132b9a1039b49ffb2f3346c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::FunctionT =  typename ContextT::FunctionT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### ModifiedPO {#a866e9bb2588b808f927062b16a23e06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::ModifiedPO =  ModifiedPostOrder&lt;ContextT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### SyncDependenceAnalysisT {#a11cbba4d2f2a8364bf42215db3b325ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::SyncDependenceAnalysisT =  GenericSyncDependenceAnalysis&lt;ContextT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

### ValueRefT {#ad2c498bed5b911ac568ac12ef3e880bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DivergencePropagator&lt; ContextT &gt;::ValueRefT =  typename ContextT::ValueRefT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DivergencePropagator() {#aefcd4588c26dc8f0236290c1e2af58d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DivergencePropagator&lt; ContextT &gt;::DivergencePropagator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a866e9bb2588b808f927062b16a23e06c">ModifiedPO</a> &amp; CyclePOT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a1b68822e3cb504bb1308d3c49d324451">DominatorTreeT</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a582bf57e481e9df41fc6a96af7eb972e">CycleInfoT</a> &amp; CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> &amp; DivTermBlock)</td>
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



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#abd0cfe9eadc0468f0b6be367ed4f59da">llvm::DivergencePropagator&lt; ContextT &gt;::BlockLabels</a>, <a href="#a79d4b0e0dde4d0ce765038ab1b0b3eeb">llvm::DivergencePropagator&lt; ContextT &gt;::CI</a>, <a href="#aba32182b54dcb9bc0b1dffadfe4cc7f5">llvm::DivergencePropagator&lt; ContextT &gt;::Context</a>, <a href="#a058ad83af142fe89600382d7ebd6d043">llvm::DivergencePropagator&lt; ContextT &gt;::CyclePOT</a>, <a href="#a3ce1c6241dbd4a80b91672bb4aa5e514">llvm::DivergencePropagator&lt; ContextT &gt;::DivDesc</a>, <a href="#a3ab9f4c02e1305316eef4eb1ec559f90">llvm::DivergencePropagator&lt; ContextT &gt;::DivTermBlock</a> and <a href="#a82f5d9a55d60641dce49b2c606949759">llvm::DivergencePropagator&lt; ContextT &gt;::DT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeJoin() {#a26ba4f21aacd60c82d606f8d6830cb1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DivergencePropagator&lt; ContextT &gt;::computeJoin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> &amp; SuccBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> &amp; PushedLabel)</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#abd0cfe9eadc0468f0b6be367ed4f59da">llvm::DivergencePropagator&lt; ContextT &gt;::BlockLabels</a>, <a href="#aba32182b54dcb9bc0b1dffadfe4cc7f5">llvm::DivergencePropagator&lt; ContextT &gt;::Context</a>, <a href="#a058ad83af142fe89600382d7ebd6d043">llvm::DivergencePropagator&lt; ContextT &gt;::CyclePOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac80d6ceb5ca63123bccddc966f43696f">llvm::DivergencePropagator&lt; ContextT &gt;::FreshLabels</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#ac9b09a5db2a5ebed6739fad98a47b232">llvm::DivergencePropagator&lt; ContextT &gt;::visitCycleExitEdge</a> and <a href="#af14ecd129e3da10ff3276dca2149a1c8">llvm::DivergencePropagator&lt; ContextT &gt;::visitEdge</a>.</p>

</div>
</div>

### computeJoinPoints() {#aa8395f502f0ee748b8c9708747d72a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; DivergenceDescriptorT &gt; llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints ()</td>
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



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#abd0cfe9eadc0468f0b6be367ed4f59da">llvm::DivergencePropagator&lt; ContextT &gt;::BlockLabels</a>, <a href="#a79d4b0e0dde4d0ce765038ab1b0b3eeb">llvm::DivergencePropagator&lt; ContextT &gt;::CI</a>, <a href="#aba32182b54dcb9bc0b1dffadfe4cc7f5">llvm::DivergencePropagator&lt; ContextT &gt;::Context</a>, <a href="#a058ad83af142fe89600382d7ebd6d043">llvm::DivergencePropagator&lt; ContextT &gt;::CyclePOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3ce1c6241dbd4a80b91672bb4aa5e514">llvm::DivergencePropagator&lt; ContextT &gt;::DivDesc</a>, <a href="#a3ab9f4c02e1305316eef4eb1ec559f90">llvm::DivergencePropagator&lt; ContextT &gt;::DivTermBlock</a>, <a href="#ac80d6ceb5ca63123bccddc966f43696f">llvm::DivergencePropagator&lt; ContextT &gt;::FreshLabels</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a4c72630ffc031d0c72c3e0a3af2bcbda">llvm::DivergencePropagator&lt; ContextT &gt;::printDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>, <a href="#ac9b09a5db2a5ebed6739fad98a47b232">llvm::DivergencePropagator&lt; ContextT &gt;::visitCycleExitEdge</a> and <a href="#af14ecd129e3da10ff3276dca2149a1c8">llvm::DivergencePropagator&lt; ContextT &gt;::visitEdge</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericsyncdependenceanalysis/#ab8d94c28ff25155aabaffd9dfa97ba76">llvm::GenericSyncDependenceAnalysis&lt; ContextT &gt;::getJoinBlocks</a>.</p>

</div>
</div>

### printDefs() {#a4c72630ffc031d0c72c3e0a3af2bcbda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DivergencePropagator&lt; ContextT &gt;::printDefs (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#abd0cfe9eadc0468f0b6be367ed4f59da">llvm::DivergencePropagator&lt; ContextT &gt;::BlockLabels</a>, <a href="#aba32182b54dcb9bc0b1dffadfe4cc7f5">llvm::DivergencePropagator&lt; ContextT &gt;::Context</a> and <a href="#a058ad83af142fe89600382d7ebd6d043">llvm::DivergencePropagator&lt; ContextT &gt;::CyclePOT</a>.</p>


<p>Referenced by <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a>.</p>

</div>
</div>

### visitCycleExitEdge() {#ac9b09a5db2a5ebed6739fad98a47b232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DivergencePropagator&lt; ContextT &gt;::visitCycleExitEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> &amp; ExitBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> &amp; Label)</td>
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



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#a26ba4f21aacd60c82d606f8d6830cb1a">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoin</a>, <a href="#aba32182b54dcb9bc0b1dffadfe4cc7f5">llvm::DivergencePropagator&lt; ContextT &gt;::Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3ce1c6241dbd4a80b91672bb4aa5e514">llvm::DivergencePropagator&lt; ContextT &gt;::DivDesc</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a>.</p>

</div>
</div>

### visitEdge() {#af14ecd129e3da10ff3276dca2149a1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DivergencePropagator&lt; ContextT &gt;::visitEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> &amp; SuccBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae07136789e9c05c9e4c4e926edc670a6">BlockT</a> &amp; Label)</td>
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



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>References <a href="#a26ba4f21aacd60c82d606f8d6830cb1a">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoin</a>, <a href="#aba32182b54dcb9bc0b1dffadfe4cc7f5">llvm::DivergencePropagator&lt; ContextT &gt;::Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3ce1c6241dbd4a80b91672bb4aa5e514">llvm::DivergencePropagator&lt; ContextT &gt;::DivDesc</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockLabels {#abd0cfe9eadc0468f0b6be367ed4f59da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockLabelMapT&amp; llvm::DivergencePropagator&lt; ContextT &gt;::BlockLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a26ba4f21aacd60c82d606f8d6830cb1a">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoin</a>, <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a>, <a href="#aefcd4588c26dc8f0236290c1e2af58d9">llvm::DivergencePropagator&lt; ContextT &gt;::DivergencePropagator</a> and <a href="#a4c72630ffc031d0c72c3e0a3af2bcbda">llvm::DivergencePropagator&lt; ContextT &gt;::printDefs</a>.</p>

</div>
</div>

### CI {#a79d4b0e0dde4d0ce765038ab1b0b3eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CycleInfoT&amp; llvm::DivergencePropagator&lt; ContextT &gt;::CI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a> and <a href="#aefcd4588c26dc8f0236290c1e2af58d9">llvm::DivergencePropagator&lt; ContextT &gt;::DivergencePropagator</a>.</p>

</div>
</div>

### Context {#aba32182b54dcb9bc0b1dffadfe4cc7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ContextT&amp; llvm::DivergencePropagator&lt; ContextT &gt;::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a26ba4f21aacd60c82d606f8d6830cb1a">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoin</a>, <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a>, <a href="#aefcd4588c26dc8f0236290c1e2af58d9">llvm::DivergencePropagator&lt; ContextT &gt;::DivergencePropagator</a>, <a href="#a4c72630ffc031d0c72c3e0a3af2bcbda">llvm::DivergencePropagator&lt; ContextT &gt;::printDefs</a>, <a href="#ac9b09a5db2a5ebed6739fad98a47b232">llvm::DivergencePropagator&lt; ContextT &gt;::visitCycleExitEdge</a> and <a href="#af14ecd129e3da10ff3276dca2149a1c8">llvm::DivergencePropagator&lt; ContextT &gt;::visitEdge</a>.</p>

</div>
</div>

### CyclePOT {#a058ad83af142fe89600382d7ebd6d043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModifiedPO&amp; llvm::DivergencePropagator&lt; ContextT &gt;::CyclePOT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a26ba4f21aacd60c82d606f8d6830cb1a">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoin</a>, <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a>, <a href="#aefcd4588c26dc8f0236290c1e2af58d9">llvm::DivergencePropagator&lt; ContextT &gt;::DivergencePropagator</a> and <a href="#a4c72630ffc031d0c72c3e0a3af2bcbda">llvm::DivergencePropagator&lt; ContextT &gt;::printDefs</a>.</p>

</div>
</div>

### DivDesc {#a3ce1c6241dbd4a80b91672bb4aa5e514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DivergenceDescriptorT&gt; llvm::DivergencePropagator&lt; ContextT &gt;::DivDesc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a>, <a href="#aefcd4588c26dc8f0236290c1e2af58d9">llvm::DivergencePropagator&lt; ContextT &gt;::DivergencePropagator</a>, <a href="#ac9b09a5db2a5ebed6739fad98a47b232">llvm::DivergencePropagator&lt; ContextT &gt;::visitCycleExitEdge</a> and <a href="#af14ecd129e3da10ff3276dca2149a1c8">llvm::DivergencePropagator&lt; ContextT &gt;::visitEdge</a>.</p>

</div>
</div>

### DivTermBlock {#a3ab9f4c02e1305316eef4eb1ec559f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockT&amp; llvm::DivergencePropagator&lt; ContextT &gt;::DivTermBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a> and <a href="#aefcd4588c26dc8f0236290c1e2af58d9">llvm::DivergencePropagator&lt; ContextT &gt;::DivergencePropagator</a>.</p>

</div>
</div>

### DT {#a82f5d9a55d60641dce49b2c606949759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DominatorTreeT&amp; llvm::DivergencePropagator&lt; ContextT &gt;::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#aefcd4588c26dc8f0236290c1e2af58d9">llvm::DivergencePropagator&lt; ContextT &gt;::DivergencePropagator</a>.</p>

</div>
</div>

### FreshLabels {#ac80d6ceb5ca63123bccddc966f43696f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ContextT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseBitVector llvm::DivergencePropagator&lt; ContextT &gt;::FreshLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a>.</p>


<p>Referenced by <a href="#a26ba4f21aacd60c82d606f8d6830cb1a">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoin</a> and <a href="#aa8395f502f0ee748b8c9708747d72a6c">llvm::DivergencePropagator&lt; ContextT &gt;::computeJoinPoints</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericuniformityimpl-h">GenericUniformityImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
