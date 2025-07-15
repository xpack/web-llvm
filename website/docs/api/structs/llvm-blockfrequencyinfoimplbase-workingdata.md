---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/blockfrequencyinfoimplbase/workingdata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `WorkingData` Struct Reference

<p>Index of loop information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BlockFrequencyInfoImplBase::WorkingData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e89c609e3f1a14353a2899a4d49a907">WorkingData</a> (const BlockNode &amp;Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9920ac737bd7393a090ee45bb2ca4bef">isLoopHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab147fa0abcd57b2d539d3287dea94999">isDoubleLoopHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">LoopData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac98dd1c5dace8f581b741b8ba806c3d0">getContainingLoop</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4cfe26f95b98d5ebfcc8279a0f494d2">getResolvedNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve a node to its representative. <a href="#af4cfe26f95b98d5ebfcc8279a0f494d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">LoopData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad592be4ee2727ca73727de4b720a5a8e">getPackagedLoop</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a6e6da6d64b5e1623157336544dd0e7a2">BlockMass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e82eb147b14cb2ce1f556852b83643">getMass</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the appropriate mass for a node. <a href="#a54e82eb147b14cb2ce1f556852b83643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a379080d91da3d02263cd75cc3d3c74">isPackaged</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has ContainingLoop been packaged up? <a href="#a0a379080d91da3d02263cd75cc3d3c74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e34c35e227b4207044c6f3e470495b3">isAPackage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> been packaged up? <a href="#a8e34c35e227b4207044c6f3e470495b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59992d1f4d494ae6d3c33f61df86d20">isADoublePackage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> been packaged up twice? <a href="#af59992d1f4d494ae6d3c33f61df86d20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1db82bbd908839aac659f7ef02ea0d7">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node. <a href="#ad1db82bbd908839aac659f7ef02ea0d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">LoopData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac12aaee5ed3068e385388a736b3238bb">Loop</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop this block is inside. <a href="#ac12aaee5ed3068e385388a736b3238bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a6e6da6d64b5e1623157336544dd0e7a2">BlockMass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3486139f8bad153d3890d929a628de1a">Mass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mass distribution from the entry block. <a href="#a3486139f8bad153d3890d929a628de1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Index of loop information.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WorkingData() {#a7e89c609e3f1a14353a2899a4d49a907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BlockFrequencyInfoImplBase::WorkingData::WorkingData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a> &amp; Node)</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="#ad1db82bbd908839aac659f7ef02ea0d7">Node</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getContainingLoop() {#ac98dd1c5dace8f581b741b8ba806c3d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopData * llvm::BlockFrequencyInfoImplBase::WorkingData::getContainingLoop ()</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#ab147fa0abcd57b2d539d3287dea94999">isDoubleLoopHeader</a>, <a href="#a9920ac737bd7393a090ee45bb2ca4bef">isLoopHeader</a> and <a href="#ac12aaee5ed3068e385388a736b3238bb">Loop</a>.</p>

</div>
</div>

### getMass() {#a54e82eb147b14cb2ce1f556852b83643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass &amp; llvm::BlockFrequencyInfoImplBase::WorkingData::getMass ()</td>
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

<p>Get the appropriate mass for a node.</p>


<p>Get appropriate mass for <a href="/web-llvm/docs/api/classes/node">Node</a>. If <a href="/web-llvm/docs/api/classes/node">Node</a> is a loop-header (whose loop has been packaged), returns the mass of its pseudo-node. If it's a node inside a packaged loop, it returns the loop's mass.</p>


<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#af59992d1f4d494ae6d3c33f61df86d20">isADoublePackage</a>, <a href="#a8e34c35e227b4207044c6f3e470495b3">isAPackage</a>, <a href="#ac12aaee5ed3068e385388a736b3238bb">Loop</a> and <a href="#a3486139f8bad153d3890d929a628de1a">Mass</a>.</p>

</div>
</div>

### getPackagedLoop() {#ad592be4ee2727ca73727de4b720a5a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopData * llvm::BlockFrequencyInfoImplBase::WorkingData::getPackagedLoop ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="#ac12aaee5ed3068e385388a736b3238bb">Loop</a>.</p>


<p>Referenced by <a href="#af4cfe26f95b98d5ebfcc8279a0f494d2">getResolvedNode</a>.</p>

</div>
</div>

### getResolvedNode() {#af4cfe26f95b98d5ebfcc8279a0f494d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockNode llvm::BlockFrequencyInfoImplBase::WorkingData::getResolvedNode ()</td>
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

<p>Resolve a node to its representative.</p>


<p>Get the node currently representing <a href="/web-llvm/docs/api/classes/node">Node</a>, which could be a containing loop.</p>


<p>This function should only be called when distributing mass. As long as there are no irreducible edges to <a href="/web-llvm/docs/api/classes/node">Node</a>, then it will have complexity O(1) in this context.</p>


<p>In general, the complexity is O(L), where L is the number of loop headers <a href="/web-llvm/docs/api/classes/node">Node</a> has been packaged into. Since this method is called in the context of distributing mass, L will be the number of loop headers an early exit edge jumps out of.</p>


<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#ad592be4ee2727ca73727de4b720a5a8e">getPackagedLoop</a> and <a href="#ad1db82bbd908839aac659f7ef02ea0d7">Node</a>.</p>


<p>Referenced by <a href="#a0a379080d91da3d02263cd75cc3d3c74">isPackaged</a>.</p>

</div>
</div>

### isADoublePackage() {#af59992d1f4d494ae6d3c33f61df86d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::WorkingData::isADoublePackage ()</td>
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

<p>Has <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> been packaged up twice?</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#ab147fa0abcd57b2d539d3287dea94999">isDoubleLoopHeader</a> and <a href="#ac12aaee5ed3068e385388a736b3238bb">Loop</a>.</p>


<p>Referenced by <a href="#a54e82eb147b14cb2ce1f556852b83643">getMass</a>.</p>

</div>
</div>

### isAPackage() {#a8e34c35e227b4207044c6f3e470495b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::WorkingData::isAPackage ()</td>
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

<p>Has <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> been packaged up?</p>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#a9920ac737bd7393a090ee45bb2ca4bef">isLoopHeader</a> and <a href="#ac12aaee5ed3068e385388a736b3238bb">Loop</a>.</p>


<p>Referenced by <a href="#a54e82eb147b14cb2ce1f556852b83643">getMass</a>.</p>

</div>
</div>

### isDoubleLoopHeader() {#ab147fa0abcd57b2d539d3287dea94999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::WorkingData::isDoubleLoopHeader ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#a9920ac737bd7393a090ee45bb2ca4bef">isLoopHeader</a>, <a href="#ac12aaee5ed3068e385388a736b3238bb">Loop</a> and <a href="#ad1db82bbd908839aac659f7ef02ea0d7">Node</a>.</p>


<p>Referenced by <a href="#ac98dd1c5dace8f581b741b8ba806c3d0">getContainingLoop</a> and <a href="#af59992d1f4d494ae6d3c33f61df86d20">isADoublePackage</a>.</p>

</div>
</div>

### isLoopHeader() {#a9920ac737bd7393a090ee45bb2ca4bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::WorkingData::isLoopHeader ()</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#ac12aaee5ed3068e385388a736b3238bb">Loop</a> and <a href="#ad1db82bbd908839aac659f7ef02ea0d7">Node</a>.</p>


<p>Referenced by <a href="#ac98dd1c5dace8f581b741b8ba806c3d0">getContainingLoop</a>, <a href="#a8e34c35e227b4207044c6f3e470495b3">isAPackage</a> and <a href="#ab147fa0abcd57b2d539d3287dea94999">isDoubleLoopHeader</a>.</p>

</div>
</div>

### isPackaged() {#a0a379080d91da3d02263cd75cc3d3c74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::WorkingData::isPackaged ()</td>
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

<p>Has ContainingLoop been packaged up?</p>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#af4cfe26f95b98d5ebfcc8279a0f494d2">getResolvedNode</a> and <a href="#ad1db82bbd908839aac659f7ef02ea0d7">Node</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Loop {#ac12aaee5ed3068e385388a736b3238bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopData* llvm::BlockFrequencyInfoImplBase::WorkingData::Loop = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop this block is inside.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#ac98dd1c5dace8f581b741b8ba806c3d0">getContainingLoop</a>, <a href="#a54e82eb147b14cb2ce1f556852b83643">getMass</a>, <a href="#ad592be4ee2727ca73727de4b720a5a8e">getPackagedLoop</a>, <a href="#af59992d1f4d494ae6d3c33f61df86d20">isADoublePackage</a>, <a href="#a8e34c35e227b4207044c6f3e470495b3">isAPackage</a>, <a href="#ab147fa0abcd57b2d539d3287dea94999">isDoubleLoopHeader</a> and <a href="#a9920ac737bd7393a090ee45bb2ca4bef">isLoopHeader</a>.</p>

</div>
</div>

### Mass {#a3486139f8bad153d3890d929a628de1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass llvm::BlockFrequencyInfoImplBase::WorkingData::Mass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mass distribution from the entry block.</p>

<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#a54e82eb147b14cb2ce1f556852b83643">getMass</a>.</p>

</div>
</div>

### Node {#ad1db82bbd908839aac659f7ef02ea0d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockNode llvm::BlockFrequencyInfoImplBase::WorkingData::Node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This node.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#af4cfe26f95b98d5ebfcc8279a0f494d2">getResolvedNode</a>, <a href="#ab147fa0abcd57b2d539d3287dea94999">isDoubleLoopHeader</a>, <a href="#a9920ac737bd7393a090ee45bb2ca4bef">isLoopHeader</a>, <a href="#a0a379080d91da3d02263cd75cc3d3c74">isPackaged</a> and <a href="#a7e89c609e3f1a14353a2899a4d49a907">WorkingData</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
