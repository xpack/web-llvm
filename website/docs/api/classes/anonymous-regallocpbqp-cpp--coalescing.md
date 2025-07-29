---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-regallocpbqp-cpp-/coalescing
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Coalescing` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{RegAllocPBQP.cpp}::Coalescing { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqpraconstraint">PBQPRAConstraint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract base for classes implementing <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> register allocation constraints (e.g. <a href="/web-llvm/docs/api/classes/llvm/pbqpraconstraint/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a07c5954404c20c6abe9a6791f19c2">apply</a> (PBQPRAGraph &amp;G) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac623e3c42d77783cdda64d3ad61974c5">addVirtRegCoalesce</a> (PBQPRAGraph::RawMatrix &amp;CostMat, const PBQPRAGraph::NodeMetadata::AllowedRegVector &amp;Allowed1, const PBQPRAGraph::NodeMetadata::AllowedRegVector &amp;Allowed2, PBQP::PBQPNum Benefit)</td>
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


<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### apply() {#a68a07c5954404c20c6abe9a6791f19c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegAllocPBQP.cpp}::Coalescing::apply (<a href="/web-llvm/docs/api/namespaces/llvm/#a3e50e01d41081a45d6a7f23af6b52df2">PBQPRAGraph</a> &amp; G)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#a9be2cffeaf9bda65c4c49eeebaa5458f">llvm::MachineBlockFrequencyInfo::getBlockFreqRelativeToEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a7f39116ef8979cff64ea1c666228e7d9">llvm::MachineRegisterInfo::isAllocatable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addVirtRegCoalesce() {#ac623e3c42d77783cdda64d3ad61974c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegAllocPBQP.cpp}::Coalescing::addVirtRegCoalesce (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a9833a63eae70b8c2beb33f0627ea0032">PBQPRAGraph::RawMatrix</a> &amp; CostMat, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PBQPRAGraph::NodeMetadata::AllowedRegVector &amp; Allowed1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PBQPRAGraph::NodeMetadata::AllowedRegVector &amp; Allowed2, <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#a7bb13d1dd9c69a2a9350ca5ba163a715">PBQP::PBQPNum</a> Benefit)</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
