---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/prefetch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Prefetch` Struct

<p>A record for a potential prefetch made during the initial scan of the loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct Prefetch { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4ee98e266564177ed0ddb2d1d13ee7">Prefetch</a> (const SCEVAddRecExpr *L, Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor to create a new <a href="/web-llvm/docs/api/structs/prefetch">Prefetch</a> for <span class="doxyComputerOutput">I</span>. <a href="#ada4ee98e266564177ed0ddb2d1d13ee7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63798d891eed0f2ca719b80993bfd24d">addInstruction</a> (Instruction *I, DominatorTree *DT=nullptr, int64_t PtrDiff=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the instruction. <a href="#a63798d891eed0f2ca719b80993bfd24d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe7627ac85b04e66883d05bf27f2e2cf">LSCEVAddRec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The address formula for this prefetch as returned by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>. <a href="#abe7627ac85b04e66883d05bf27f2e2cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5374d9e6077e58aa5b386cff17137285">InsertPt</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The point of insertion for the prefetch instruction. <a href="#a5374d9e6077e58aa5b386cff17137285">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5b950dd3f8fe25c3eb7d28cf3f6860">Writes</a> = <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp/#af8f2b0659e6aa4c7f72b51863942ed2c">false</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if targeting a write memory access. <a href="#a8b5b950dd3f8fe25c3eb7d28cf3f6860">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7517b1239c25d05bda1d84e39b2aee2">MemI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The (first seen) prefetched instruction. <a href="#ab7517b1239c25d05bda1d84e39b2aee2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A record for a potential prefetch made during the initial scan of the loop.</p>


<p>This is used to let a single prefetch target multiple memory accesses.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp">LoopDataPrefetch.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Prefetch() {#ada4ee98e266564177ed0ddb2d1d13ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Prefetch::Prefetch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * L, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Constructor to create a new <a href="/web-llvm/docs/api/structs/prefetch">Prefetch</a> for <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp">LoopDataPrefetch.cpp</a>.</p>


<p>References <a href="#a63798d891eed0f2ca719b80993bfd24d">addInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#abe7627ac85b04e66883d05bf27f2e2cf">LSCEVAddRec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addInstruction() {#a63798d891eed0f2ca719b80993bfd24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Prefetch::addInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr, int64_t PtrDiff=0)</td>
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

<p>Add the instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>to this prefetch. If it's not the first one, 'InsertPt' and 'Writes' will be updated as required.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PtrDiff</td>
<td class="doxyParamItemDescription"><p>the known constant address difference to the first added instruction.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp">LoopDataPrefetch.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a5374d9e6077e58aa5b386cff17137285">InsertPt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ab7517b1239c25d05bda1d84e39b2aee2">MemI</a> and <a href="#a8b5b950dd3f8fe25c3eb7d28cf3f6860">Writes</a>.</p>


<p>Referenced by <a href="#ada4ee98e266564177ed0ddb2d1d13ee7">Prefetch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### InsertPt {#a5374d9e6077e58aa5b386cff17137285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* Prefetch::InsertPt = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The point of insertion for the prefetch instruction.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp">LoopDataPrefetch.cpp</a>.</p>


<p>Referenced by <a href="#a63798d891eed0f2ca719b80993bfd24d">addInstruction</a>.</p>

</div>
</div>

### LSCEVAddRec {#abe7627ac85b04e66883d05bf27f2e2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVAddRecExpr* Prefetch::LSCEVAddRec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The address formula for this prefetch as returned by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp">LoopDataPrefetch.cpp</a>.</p>


<p>Referenced by <a href="#ada4ee98e266564177ed0ddb2d1d13ee7">Prefetch</a>.</p>

</div>
</div>

### MemI {#ab7517b1239c25d05bda1d84e39b2aee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* Prefetch::MemI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The (first seen) prefetched instruction.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp">LoopDataPrefetch.cpp</a>.</p>


<p>Referenced by <a href="#a63798d891eed0f2ca719b80993bfd24d">addInstruction</a>.</p>

</div>
</div>

### Writes {#a8b5b950dd3f8fe25c3eb7d28cf3f6860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Prefetch::Writes = <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp/#af8f2b0659e6aa4c7f72b51863942ed2c">false</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if targeting a write memory access.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp">LoopDataPrefetch.cpp</a>.</p>


<p>Referenced by <a href="#a63798d891eed0f2ca719b80993bfd24d">addInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdataprefetch-cpp">LoopDataPrefetch.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
