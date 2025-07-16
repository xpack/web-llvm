---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/basicirlayermaterializationunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BasicIRLayerMaterializationUnit` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> that materializes modules by calling the 'emit' method on the given <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::BasicIRLayerMaterializationUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">llvm/ExecutionEngine/Orc/Layer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit">IRMaterializationUnit</a> is a convenient base class for MaterializationUnits wrapping LLVM IR. <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ecb87f3ae601f79964b914bf0363e57">BasicIRLayerMaterializationUnit</a> (IRLayer &amp;L, const IRSymbolMapper::ManglingOptions &amp;MO, ThreadSafeModule TSM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c3de158d308a4944aa62c9467720e2">materialize</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded. <a href="#a37c3de158d308a4944aa62c9467720e2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f70c224f1c836e949a377837dac6bd">L</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> that materializes modules by calling the 'emit' method on the given <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a>.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BasicIRLayerMaterializationUnit() {#a6ecb87f3ae601f79964b914bf0363e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::BasicIRLayerMaterializationUnit::BasicIRLayerMaterializationUnit (<a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/irsymbolmapper/manglingoptions">IRSymbolMapper::ManglingOptions</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a8c041de2ccbd4ea7436a03c71c79b900">llvm::orc::IRMaterializationUnit::TSM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### materialize() {#a37c3de158d308a4944aa62c9467720e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::BasicIRLayerMaterializationUnit::materialize (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R)</td>
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

<p>Implementations of this method should materialize all symbols in the materialzation unit, except for those that have been previously discarded.</p>

<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/layer-cpp">Layer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### L {#ac0f70c224f1c836e949a377837dac6bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRLayer&amp; llvm::orc::BasicIRLayerMaterializationUnit::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/layer-h">Layer.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
