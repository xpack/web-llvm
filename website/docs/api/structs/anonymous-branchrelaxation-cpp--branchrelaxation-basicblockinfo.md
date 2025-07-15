---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-branchrelaxation-cpp-/branchrelaxation/basicblockinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BasicBlockInfo` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/basicblockinfo">BasicBlockInfo</a> - Information about the offset and size of a single basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{BranchRelaxation.cpp}::BranchRelaxation::BasicBlockInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09948668a567bb5b670a751f0c3b41a7">BasicBlockInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8f611dfd05f80edc08142e57f94f65">postOffset</a> (const MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the offset immediately following this block. <a href="#aaf8f611dfd05f80edc08142e57f94f65">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d5047856c504cd549c40b0d2af35c15">Offset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset - Distance from the beginning of the function to the beginning of this basic block. <a href="#a8d5047856c504cd549c40b0d2af35c15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125228eb9562ad7be1d5b550ce0ba3c8">Size</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size - Size of the basic block in bytes. <a href="#a125228eb9562ad7be1d5b550ce0ba3c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/basicblockinfo">BasicBlockInfo</a> - Information about the offset and size of a single basic block.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchrelaxation-cpp">BranchRelaxation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BasicBlockInfo() {#a09948668a567bb5b670a751f0c3b41a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BranchRelaxation.cpp}::BranchRelaxation::BasicBlockInfo::BasicBlockInfo ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchrelaxation-cpp">BranchRelaxation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### postOffset() {#aaf8f611dfd05f80edc08142e57f94f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BranchRelaxation.cpp}::BranchRelaxation::BasicBlockInfo::postOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Compute the offset immediately following this block.</p>


<p><span class="doxyComputerOutput">MBB</span> is the next block.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchrelaxation-cpp">BranchRelaxation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Offset {#a8d5047856c504cd549c40b0d2af35c15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BranchRelaxation.cpp}::BranchRelaxation::BasicBlockInfo::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset - Distance from the beginning of the function to the beginning of this basic block.</p>


<p>The offset is always aligned as required by the basic block.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchrelaxation-cpp">BranchRelaxation.cpp</a>.</p>

</div>
</div>

### Size {#a125228eb9562ad7be1d5b550ce0ba3c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BranchRelaxation.cpp}::BranchRelaxation::BasicBlockInfo::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size - Size of the basic block in bytes.</p>


<p>If the block contains inline assembly, this is a worst case estimate.</p>


<p>The size does not include any alignment padding whether from the beginning of the block, or from an aligned jump table at the end.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchrelaxation-cpp">BranchRelaxation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/branchrelaxation-cpp">BranchRelaxation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
