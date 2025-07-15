---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/outliner/globaloutlinedfunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GlobalOutlinedFunction` Struct Reference

<p>The information necessary to create an outlined function that is matched globally. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::outliner::GlobalOutlinedFunction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">llvm/CodeGen/MachineOutliner.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The information necessary to create an outlined function for some class of candidate. <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a463e885d11330185cf612f79fce97b71">GlobalOutlinedFunction</a> (std::unique_ptr&lt; OutlinedFunction &gt; OF, unsigned GlobalOccurrenceCount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab67942f75a3949c6dfe0fc14abdbb1f">GlobalOutlinedFunction</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f86dc4812d7c024fd4a0943a4f26f3">~GlobalOutlinedFunction</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e17727ea30aa97903c1a0c5785ea444">getOccurrenceCount</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of times that appear globally. <a href="#a8e17727ea30aa97903c1a0c5785ea444">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa2c81688be51a0d2f4836630470b7f6">getOutliningCost</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the outlining cost using the global occurrence count with the same cost as the first (unique) candidate. <a href="#aaa2c81688be51a0d2f4836630470b7f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d53a787cdd3b637308c654767487bc1">GlobalOccurrenceCount</a></td>
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

<p>The information necessary to create an outlined function that is matched globally.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GlobalOutlinedFunction() {#a463e885d11330185cf612f79fce97b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::outliner::GlobalOutlinedFunction::GlobalOutlinedFunction (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction">OutlinedFunction</a> &gt; OF, unsigned GlobalOccurrenceCount)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>References <a href="#a2d53a787cdd3b637308c654767487bc1">GlobalOccurrenceCount</a> and <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#ac2f1c35acd04b812afdb550964c2eab2">llvm::outliner::OutlinedFunction::OutlinedFunction</a>.</p>

</div>
</div>

### GlobalOutlinedFunction() {#aab67942f75a3949c6dfe0fc14abdbb1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::outliner::GlobalOutlinedFunction::GlobalOutlinedFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GlobalOutlinedFunction() {#ac8f86dc4812d7c024fd4a0943a4f26f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::outliner::GlobalOutlinedFunction::~GlobalOutlinedFunction ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getOccurrenceCount() {#a8e17727ea30aa97903c1a0c5785ea444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::GlobalOutlinedFunction::getOccurrenceCount ()</td>
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

<p>Return the number of times that appear globally.</p>


<p>Global outlining candidate is uniquely created per each match, but this might be erased out when it's overlapped with the previous outlining instance.</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#afaa7ed984d2671729752893984eb85a3">llvm::outliner::OutlinedFunction::Candidates</a> and <a href="#a2d53a787cdd3b637308c654767487bc1">GlobalOccurrenceCount</a>.</p>


<p>Referenced by <a href="#aaa2c81688be51a0d2f4836630470b7f6">getOutliningCost</a>.</p>

</div>
</div>

### getOutliningCost() {#aaa2c81688be51a0d2f4836630470b7f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::GlobalOutlinedFunction::getOutliningCost ()</td>
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

<p>Return the outlining cost using the global occurrence count with the same cost as the first (unique) candidate.</p>

<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#afaa7ed984d2671729752893984eb85a3">llvm::outliner::OutlinedFunction::Candidates</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#ac55fb9b4653cc5d1f1247eb015db5ed5">llvm::outliner::OutlinedFunction::FrameOverhead</a>, <a href="#a8e17727ea30aa97903c1a0c5785ea444">getOccurrenceCount</a> and <a href="/web-llvm/docs/api/structs/llvm/outliner/outlinedfunction/#ad73db622d8cc649f5d3f7f3dbba5398d">llvm::outliner::OutlinedFunction::SequenceSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### GlobalOccurrenceCount {#a2d53a787cdd3b637308c654767487bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::outliner::GlobalOutlinedFunction::GlobalOccurrenceCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a>.</p>


<p>Referenced by <a href="#a8e17727ea30aa97903c1a0c5785ea444">getOccurrenceCount</a> and <a href="#a463e885d11330185cf612f79fce97b71">GlobalOutlinedFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoutliner-h">MachineOutliner.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
