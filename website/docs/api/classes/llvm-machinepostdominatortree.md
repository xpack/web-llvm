---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinepostdominatortree
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachinePostDominatorTree` Class

<p><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> - an analysis pass wrapper for <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> used to compute the post-dominator tree for MachineFunctions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachinePostDominatorTree { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">llvm/CodeGen/MachinePostDominators.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase&lt;NodeT, IsPostDom&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Core dominator tree base class. <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8777602c71284db04e9a2898f85d6dea">Base</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a42a6aebb3458a7c7e43d89338c1a6816">PostDomTreeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f3d17a1ba40b49d2940798f2067783">MachinePostDominatorTree</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5890d0e4bf27bee6a8234f356febd92f">MachinePostDominatorTree</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1deaedd3d73b764265d064639c1d36c0">invalidate</a> (MachineFunction &amp;, const PreservedAnalyses &amp;PA, MachineFunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation explicitly. <a href="#a1deaedd3d73b764265d064639c1d36c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d9f37d3681f5f14f5cf21fdf060703f">findNearestCommonDominator</a> (ArrayRef&lt; MachineBasicBlock * &gt; Blocks) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the nearest common dominator of the given blocks. <a href="#a5d9f37d3681f5f14f5cf21fdf060703f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69db559752d15bd1cea83c400c619f16">findNearestCommonDominator</a> (T *A, T *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make findNearestCommonDominator(const NodeT *A, const NodeT *B) available. <a href="#a69db559752d15bd1cea83c400c619f16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb6fe22898eb44734c7c81d4270142f">findNearestCommonDominator</a> (const T *A, const T *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make findNearestCommonDominator(const NodeT *A, const NodeT *B) available. <a href="#a8bb6fe22898eb44734c7c81d4270142f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4e706b8da30a388b3c9310aa423b1b">findNearestCommonDominator</a> (iterator_range&lt; IteratorTy &gt; Nodes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make findNearestCommonDominator(const NodeT *A, const NodeT *B) available. <a href="#a3f4e706b8da30a388b3c9310aa423b1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> - an analysis pass wrapper for <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> used to compute the post-dominator tree for MachineFunctions.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#a8777602c71284db04e9a2898f85d6dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachinePostDominatorTree::Base =  PostDomTreeBase&lt;MachineBasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachinePostDominatorTree() {#aa5f3d17a1ba40b49d2940798f2067783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachinePostDominatorTree::MachinePostDominatorTree ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>

</div>
</div>

### MachinePostDominatorTree() {#a5890d0e4bf27bee6a8234f356febd92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachinePostDominatorTree::MachinePostDominatorTree (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; T, true &gt;::recalculate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findNearestCommonDominator() {#a5d9f37d3681f5f14f5cf21fdf060703f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachinePostDominatorTree::findNearestCommonDominator (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; Blocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the nearest common dominator of the given blocks.</p>


<p>If that tree node is a virtual root, a nullptr will be returned.</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepostdominators-cpp">MachinePostDominators.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a26cf1d2b810e0413369fda9759618123">llvm::DominatorTreeBase&lt; T, true &gt;::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; T, true &gt;::getNode</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ae01eee1948b6c351f27a31bbe17fe1b2">llvm::DominatorTreeBase&lt; T, true &gt;::isVirtualRoot</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a69db559752d15bd1cea83c400c619f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::DominatorTreeBase&lt; T, IsPostDom &gt;::findNearestCommonDominator (T * A, T * B)</td>
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

<p>Make findNearestCommonDominator(const NodeT *A, const NodeT *B) available.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a8bb6fe22898eb44734c7c81d4270142f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * llvm::DominatorTreeBase&lt; T, IsPostDom &gt;::findNearestCommonDominator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * B)</td>
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

<p>Make findNearestCommonDominator(const NodeT *A, const NodeT *B) available.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a3f4e706b8da30a388b3c9310aa423b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::DominatorTreeBase&lt; T, IsPostDom &gt;::findNearestCommonDominator (<a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; IteratorTy &gt; Nodes)</td>
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

<p>Make findNearestCommonDominator(const NodeT *A, const NodeT *B) available.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### invalidate() {#a1deaedd3d73b764265d064639c1d36c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachinePostDominatorTree::invalidate (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, MachineFunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle invalidation explicitly.</p>

<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepostdominators-cpp">MachinePostDominators.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepostdominators-cpp">MachinePostDominators.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
