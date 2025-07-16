---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-valuemapper-cpp-/delayedbasicblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DelayedBasicBlock` Struct Reference

<p>A basic block used in a <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> whose function body is not yet materialized. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ValueMapper.cpp}::DelayedBasicBlock { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cf1595c8e519c7a89faf8cccd313584">DelayedBasicBlock</a> (const BlockAddress &amp;Old)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac083c30a7c3a41b4c653d7c7ab86801c">OldBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f2f65273a8bc92c15375d52b8f8d706">TempBB</a></td>
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

<p>A basic block used in a <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> whose function body is not yet materialized.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DelayedBasicBlock() {#a9cf1595c8e519c7a89faf8cccd313584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ValueMapper.cpp}::DelayedBasicBlock::DelayedBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> &amp; Old)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>References <a href="#ac083c30a7c3a41b4c653d7c7ab86801c">OldBB</a> and <a href="#a9f2f65273a8bc92c15375d52b8f8d706">TempBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OldBB {#ac083c30a7c3a41b4c653d7c7ab86801c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{ValueMapper.cpp}::DelayedBasicBlock::OldBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Referenced by <a href="#a9cf1595c8e519c7a89faf8cccd313584">DelayedBasicBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a70a9be463da66de9360f96b0df3be34a">anonymous{ValueMapper.cpp}::Mapper::flush</a>.</p>

</div>
</div>

### TempBB {#a9f2f65273a8bc92c15375d52b8f8d706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BasicBlock&gt; anonymous{ValueMapper.cpp}::DelayedBasicBlock::TempBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Referenced by <a href="#a9cf1595c8e519c7a89faf8cccd313584">DelayedBasicBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a70a9be463da66de9360f96b0df3be34a">anonymous{ValueMapper.cpp}::Mapper::flush</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
