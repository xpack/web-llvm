---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-webassemblycfgsort-cpp-/entry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Entry` Struct Reference

<p>Bookkeeping for a region to help ensure that we don't mix blocks not dominated by the its header among its blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{WebAssemblyCFGSort.cpp}::Entry { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4167dec092b2252b9120d82ade98b7a0">Entry</a> (const SortRegion *R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SortRegion *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a936904f3e0193dbcf41cc18b26630ecd">TheRegion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff31d79a6e5ef070ffc0a7bb7ce371c">NumBlocksLeft</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa579205323c766f238fb482355db54f2">Deferred</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of blocks not dominated by <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>'s header that are deferred until after all of <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>'s blocks have been seen. <a href="#aa579205323c766f238fb482355db54f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Bookkeeping for a region to help ensure that we don't mix blocks not dominated by the its header among its blocks.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp">WebAssemblyCFGSort.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Entry() {#a4167dec092b2252b9120d82ade98b7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WebAssemblyCFGSort.cpp}::Entry::Entry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SortRegion * R)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp">WebAssemblyCFGSort.cpp</a>.</p>


<p>References <a href="#afff31d79a6e5ef070ffc0a7bb7ce371c">NumBlocksLeft</a> and <a href="#a936904f3e0193dbcf41cc18b26630ecd">TheRegion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp/#ab52c873c8169af2a8b1256ace3fe7a7c">sortBlocks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Deferred {#aa579205323c766f238fb482355db54f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineBasicBlock *&gt; anonymous{WebAssemblyCFGSort.cpp}::Entry::Deferred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of blocks not dominated by <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>'s header that are deferred until after all of <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>'s blocks have been seen.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp">WebAssemblyCFGSort.cpp</a>.</p>

</div>
</div>

### NumBlocksLeft {#afff31d79a6e5ef070ffc0a7bb7ce371c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{WebAssemblyCFGSort.cpp}::Entry::NumBlocksLeft</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp">WebAssemblyCFGSort.cpp</a>.</p>


<p>Referenced by <a href="#a4167dec092b2252b9120d82ade98b7a0">Entry</a>.</p>

</div>
</div>

### TheRegion {#a936904f3e0193dbcf41cc18b26630ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SortRegion* anonymous{WebAssemblyCFGSort.cpp}::Entry::TheRegion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp">WebAssemblyCFGSort.cpp</a>.</p>


<p>Referenced by <a href="#a4167dec092b2252b9120d82ade98b7a0">Entry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp">WebAssemblyCFGSort.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
