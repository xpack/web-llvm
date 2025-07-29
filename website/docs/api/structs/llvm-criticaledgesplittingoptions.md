---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/criticaledgesplittingoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CriticalEdgeSplittingOptions` Struct

<p>Option class for critical edge splitting. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::CriticalEdgeSplittingOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a> (DominatorTree *DT=nullptr, LoopInfo *LI=nullptr, MemorySSAUpdater *MSSAU=nullptr, PostDominatorTree *PDT=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/criticaledgesplittingoptions">CriticalEdgeSplittingOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae6c4689317427fe606a12a0ef0442d">setMergeIdenticalEdges</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/criticaledgesplittingoptions">CriticalEdgeSplittingOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8504b5a6c0c25fb11a79b8b317947152">setKeepOneInputPHIs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/criticaledgesplittingoptions">CriticalEdgeSplittingOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae355dd9e9ab1c9b6928bbf8d962403bf">setPreserveLCSSA</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/criticaledgesplittingoptions">CriticalEdgeSplittingOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec3f539d8bd56423f6882374ed11930">setIgnoreUnreachableDests</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/criticaledgesplittingoptions">CriticalEdgeSplittingOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65e4aaf0bb75bb474b5812a6dc72962">unsetPreserveLoopSimplify</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f19b8eb788ba80950c6835ca4ba457">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d1d47faf5cae8a86f8b9d1409f4b9c">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab190984f131aea41a3d3224eb29a8ad9">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1e09a5a5d2f91b5bc8c05496406131">MSSAU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87beba41c5d885a2fe9afb593fc2e4a4">MergeIdenticalEdges</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3286b223c2d8453ef3fc834068a0de">KeepOneInputPHIs</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07576136ce65067b61f10ea0cb1a0a52">PreserveLCSSA</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f6020a9ff97c0db6b311eb164656d68">IgnoreUnreachableDests</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49c1cc9b14d9bb63aff235f1c0830f8">PreserveLoopSimplify</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SplitCriticalEdge is guaranteed to preserve loop-simplify form if LI is provided. <a href="#aa49c1cc9b14d9bb63aff235f1c0830f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Option class for critical edge splitting.</p>


<p>This provides a builder interface for overriding the default options used during critical edge splitting.</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CriticalEdgeSplittingOptions() {#a1b605eeb005e925cf79734b808296c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CriticalEdgeSplittingOptions::CriticalEdgeSplittingOptions (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU=nullptr, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT=nullptr)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>References <a href="#a36f19b8eb788ba80950c6835ca4ba457">DT</a>, <a href="#ab190984f131aea41a3d3224eb29a8ad9">LI</a>, <a href="#afc1e09a5a5d2f91b5bc8c05496406131">MSSAU</a> and <a href="#ac1d1d47faf5cae8a86f8b9d1409f4b9c">PDT</a>.</p>


<p>Referenced by <a href="#aeec3f539d8bd56423f6882374ed11930">setIgnoreUnreachableDests</a>, <a href="#a8504b5a6c0c25fb11a79b8b317947152">setKeepOneInputPHIs</a>, <a href="#a2ae6c4689317427fe606a12a0ef0442d">setMergeIdenticalEdges</a>, <a href="#ae355dd9e9ab1c9b6928bbf8d962403bf">setPreserveLCSSA</a> and <a href="#aa65e4aaf0bb75bb474b5812a6dc72962">unsetPreserveLoopSimplify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setIgnoreUnreachableDests() {#aeec3f539d8bd56423f6882374ed11930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalEdgeSplittingOptions &amp; llvm::CriticalEdgeSplittingOptions::setIgnoreUnreachableDests ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>References <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a> and <a href="#a4f6020a9ff97c0db6b311eb164656d68">IgnoreUnreachableDests</a>.</p>

</div>
</div>

### setKeepOneInputPHIs() {#a8504b5a6c0c25fb11a79b8b317947152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalEdgeSplittingOptions &amp; llvm::CriticalEdgeSplittingOptions::setKeepOneInputPHIs ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>References <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a> and <a href="#a7f3286b223c2d8453ef3fc834068a0de">KeepOneInputPHIs</a>.</p>

</div>
</div>

### setMergeIdenticalEdges() {#a2ae6c4689317427fe606a12a0ef0442d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalEdgeSplittingOptions &amp; llvm::CriticalEdgeSplittingOptions::setMergeIdenticalEdges ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>References <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a> and <a href="#a87beba41c5d885a2fe9afb593fc2e4a4">MergeIdenticalEdges</a>.</p>

</div>
</div>

### setPreserveLCSSA() {#ae355dd9e9ab1c9b6928bbf8d962403bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalEdgeSplittingOptions &amp; llvm::CriticalEdgeSplittingOptions::setPreserveLCSSA ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>References <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a> and <a href="#a07576136ce65067b61f10ea0cb1a0a52">PreserveLCSSA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>.</p>

</div>
</div>

### unsetPreserveLoopSimplify() {#aa65e4aaf0bb75bb474b5812a6dc72962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalEdgeSplittingOptions &amp; llvm::CriticalEdgeSplittingOptions::unsetPreserveLoopSimplify ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>References <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a> and <a href="#aa49c1cc9b14d9bb63aff235f1c0830f8">PreserveLoopSimplify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DT {#a36f19b8eb788ba80950c6835ca4ba457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::CriticalEdgeSplittingOptions::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a>.</p>

</div>
</div>

### IgnoreUnreachableDests {#a4f6020a9ff97c0db6b311eb164656d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CriticalEdgeSplittingOptions::IgnoreUnreachableDests = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#aeec3f539d8bd56423f6882374ed11930">setIgnoreUnreachableDests</a>.</p>

</div>
</div>

### KeepOneInputPHIs {#a7f3286b223c2d8453ef3fc834068a0de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CriticalEdgeSplittingOptions::KeepOneInputPHIs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#a8504b5a6c0c25fb11a79b8b317947152">setKeepOneInputPHIs</a>.</p>

</div>
</div>

### LI {#ab190984f131aea41a3d3224eb29a8ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::CriticalEdgeSplittingOptions::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a>.</p>

</div>
</div>

### MergeIdenticalEdges {#a87beba41c5d885a2fe9afb593fc2e4a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CriticalEdgeSplittingOptions::MergeIdenticalEdges = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#a2ae6c4689317427fe606a12a0ef0442d">setMergeIdenticalEdges</a>.</p>

</div>
</div>

### MSSAU {#afc1e09a5a5d2f91b5bc8c05496406131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAUpdater* llvm::CriticalEdgeSplittingOptions::MSSAU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a>.</p>

</div>
</div>

### PDT {#ac1d1d47faf5cae8a86f8b9d1409f4b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDominatorTree* llvm::CriticalEdgeSplittingOptions::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#a1b605eeb005e925cf79734b808296c9b">CriticalEdgeSplittingOptions</a>.</p>

</div>
</div>

### PreserveLCSSA {#a07576136ce65067b61f10ea0cb1a0a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CriticalEdgeSplittingOptions::PreserveLCSSA = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#ae355dd9e9ab1c9b6928bbf8d962403bf">setPreserveLCSSA</a>.</p>

</div>
</div>

### PreserveLoopSimplify {#aa49c1cc9b14d9bb63aff235f1c0830f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CriticalEdgeSplittingOptions::PreserveLoopSimplify = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SplitCriticalEdge is guaranteed to preserve loop-simplify form if LI is provided.</p>


<p>If it cannot be preserved, no splitting will take place. If it is not set, preserve loop-simplify form if possible.</p>


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a>.</p>


<p>Referenced by <a href="#aa65e4aaf0bb75bb474b5812a6dc72962">unsetPreserveLoopSimplify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">BasicBlockUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
