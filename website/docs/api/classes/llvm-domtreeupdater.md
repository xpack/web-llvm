---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/domtreeupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DomTreeUpdater` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DomTreeUpdater { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">llvm/Analysis/DomTreeUpdater.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater">GenericDomTreeUpdater&lt;DerivedT, DomTreeT, PostDomTreeT&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a036ff8cccdbdcfa3263cc9d426f36ea7">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater">GenericDomTreeUpdater</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a>, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684501bae0019eba47728686bc16c478">~DomTreeUpdater</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b547854a7f9e418222c9823b2602314">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug method to help view the internal state of this class. <a href="#a5b547854a7f9e418222c9823b2602314">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a3ebc3ad4cebba81973a05ebc38833">validateDeleteBB</a> (BasicBlock *DelBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First remove all the instructions of DelBB and then make sure DelBB has a valid terminator instruction which is necessary to have when DelBB still has to be inside of its parent <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> while awaiting deletion under Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> to prevent other routines from asserting the state of the IR is inconsistent. <a href="#a17a3ebc3ad4cebba81973a05ebc38833">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b218e43061f94f9d4b65216b53f045">forceFlushDeletedBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if at least one <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> is deleted. <a href="#aa7b218e43061f94f9d4b65216b53f045">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c09ac5aa2c107a9c733bc133e9582e">GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; CallBackOnDeletion &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b70cc7e93d1f949c3a97ba026de23c1">Callbacks</a></td>
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

## Mutation APIs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcca375fa8086f6844e863abbf58f83b">deleteBB</a> (BasicBlock *DelBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete DelBB. <a href="#adcca375fa8086f6844e863abbf58f83b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22a66bf381f2b0a994b4e00cca5eac4">callbackDeleteBB</a> (BasicBlock *DelBB, std::function&lt; void(BasicBlock *)&gt; Callback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete DelBB. <a href="#aa22a66bf381f2b0a994b4e00cca5eac4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Base {#a036ff8cccdbdcfa3263cc9d426f36ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeUpdater::Base = 
      GenericDomTreeUpdater&lt;DomTreeUpdater, DominatorTree, PostDominatorTree&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DomTreeUpdater() {#a684501bae0019eba47728686bc16c478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DomTreeUpdater::~DomTreeUpdater ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a43c80a160270d75d99cfeb080c165694">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::flush</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a5b547854a7f9e418222c9823b2602314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::DomTreeUpdater::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug method to help view the internal state of this class.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domtreeupdater-cpp">DomTreeUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### forceFlushDeletedBB() {#aa7b218e43061f94f9d4b65216b53f045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeUpdater::forceFlushDeletedBB ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if at least one <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> is deleted.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domtreeupdater-cpp">DomTreeUpdater.cpp</a>.</p>

</div>
</div>

### validateDeleteBB() {#a17a3ebc3ad4cebba81973a05ebc38833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeUpdater::validateDeleteBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * DelBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>First remove all the instructions of DelBB and then make sure DelBB has a valid terminator instruction which is necessary to have when DelBB still has to be inside of its parent <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> while awaiting deletion under Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> to prevent other routines from asserting the state of the IR is inconsistent.</p>


<p>Assert if DelBB is nullptr or has predecessors.</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domtreeupdater-cpp">DomTreeUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Callbacks {#a2b70cc7e93d1f949c3a97ba026de23c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CallBackOnDeletion&gt; llvm::DomTreeUpdater::Callbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>.</p>

</div>
</div>

### GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt; {#a56c09ac5aa2c107a9c733bc133e9582e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::DomTreeUpdater::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Mutation APIs



<p>These methods provide APIs for submitting updates to the <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> and the <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a>.</p>


<p>Note: There are two strategies to update the <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> and the <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a>:</p>


<ol class="doxyList" type="1">
<li>Eager <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>: Updates are submitted and then flushed immediately.</li>
<li>Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>: Updates are submitted but only flushed when you explicitly call Flush APIs. It is recommended to use this update strategy when you submit a bunch of updates multiple times which can then add up to a large number of updates between two queries on the <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a>. The incremental updater can reschedule the updates or decide to recalculate the dominator tree in order to speedup the updating process depending on the number of updates.</li>
</ol>

<p>Although GenericDomTree provides several update primitives, it is not encouraged to use these APIs directly.</p>


### callbackDeleteBB {#aa22a66bf381f2b0a994b4e00cca5eac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeUpdater::callbackDeleteBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * DelBB, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *)&gt; Callback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete DelBB.</p>


<p>DelBB will be removed from its Parent and erased from available trees if it exists. Then the callback will be called. Finally, DelBB will be deleted. Under Eager <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>, DelBB will be processed immediately. Under Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>, DelBB will be queued until a flush event and all available trees are up-to-date. Assert if any instruction of DelBB is modified while awaiting deletion. Multiple callbacks can be queued for one DelBB under Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>.</p>


<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domtreeupdater-cpp">DomTreeUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a03640c958debd0b9a525cff8fe5a11ed">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::DeletedBBs</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a42eae544363676292b0d6a03d06ba9df">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::eraseDelBBNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a629adad5a5d84929eac0f0b00132af1b">llvm::BasicBlock::removeFromParent</a> and <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::Strategy</a>.</p>

</div>
</div>

### deleteBB {#adcca375fa8086f6844e863abbf58f83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeUpdater::deleteBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * DelBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete DelBB.</p>


<p>DelBB will be removed from its Parent and erased from available trees if it exists and finally get deleted. Under Eager <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>, DelBB will be processed immediately. Under Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>, DelBB will be queued until a flush event and all available trees are up-to-date. Assert if any instruction of DelBB is modified while awaiting deletion. When both DT and PDT are nullptrs, DelBB will be queued until <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a43c80a160270d75d99cfeb080c165694">flush()</a> is called.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domtreeupdater-cpp">DomTreeUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a03640c958debd0b9a525cff8fe5a11ed">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::DeletedBBs</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a42eae544363676292b0d6a03d06ba9df">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::eraseDelBBNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a8dd327a937563afdb08250abc43820b0">llvm::BasicBlock::eraseFromParent</a> and <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::Strategy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#addf42fea14164ec994d4d517eaa56688">llvm::DeleteDeadBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">DomTreeUpdater.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/domtreeupdater-cpp">DomTreeUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
