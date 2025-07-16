---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-stackcoloring-cpp-/stackcoloring/blocklifetimeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BlockLifetimeInfo` Struct Reference

<p>A class representing liveness information for a single basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{StackColoring.cpp}::StackColoring::BlockLifetimeInfo { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7946e33bd402ca9eafd8a71cb00bb7">Begin</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which slots BEGINs in each basic block. <a href="#a1c7946e33bd402ca9eafd8a71cb00bb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2faa085cd36299444e27272676980d1a">End</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which slots ENDs in each basic block. <a href="#a2faa085cd36299444e27272676980d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0be771fca0e714cb74082416ee39ee5">LiveIn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which slots are marked as LIVE_IN, coming into each basic block. <a href="#ac0be771fca0e714cb74082416ee39ee5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08163b14f5fa4450d4846ac2bce5243d">LiveOut</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Which slots are marked as LIVE_OUT, coming out of each basic block. <a href="#a08163b14f5fa4450d4846ac2bce5243d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class representing liveness information for a single basic block.</p>


<p>Each bit in the <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> represents the liveness property for a different stack slot.</p>


<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Begin {#a1c7946e33bd402ca9eafd8a71cb00bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{StackColoring.cpp}::StackColoring::BlockLifetimeInfo::Begin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Which slots BEGINs in each basic block.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### End {#a2faa085cd36299444e27272676980d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{StackColoring.cpp}::StackColoring::BlockLifetimeInfo::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Which slots ENDs in each basic block.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### LiveIn {#ac0be771fca0e714cb74082416ee39ee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{StackColoring.cpp}::StackColoring::BlockLifetimeInfo::LiveIn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Which slots are marked as LIVE_IN, coming into each basic block.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### LiveOut {#a08163b14f5fa4450d4846ac2bce5243d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{StackColoring.cpp}::StackColoring::BlockLifetimeInfo::LiveOut</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Which slots are marked as LIVE_OUT, coming out of each basic block.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
