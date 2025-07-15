---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinedomtreeupdater
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineDomTreeUpdater` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachineDomTreeUpdater { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">llvm/CodeGen/MachineDomTreeUpdater.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c27b709939802f420472199343ef43">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater">GenericDomTreeUpdater</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinedomtreeupdater">MachineDomTreeUpdater</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095af11c37370db5be9f638de4168238">~MachineDomTreeUpdater</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3baf55e2d6a16f5fd88b6492eefcb4eb">validateDeleteBB</a> (MachineBasicBlock *DelBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First remove all the instructions of DelBB and then make sure DelBB has a valid terminator instruction which is necessary to have when DelBB still has to be inside of its parent <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> while awaiting deletion under Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> to prevent other routines from asserting the state of the IR is inconsistent. <a href="#a3baf55e2d6a16f5fd88b6492eefcb4eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4acf646d484cfde2074b23ef6d6e1199">forceFlushDeletedBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if at least one <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> is deleted. <a href="#a4acf646d484cfde2074b23ef6d6e1199">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7d9ac53a9826eb235e14e1beb0f0ea">GenericDomTreeUpdater&lt; MachineDomTreeUpdater, MachineDominatorTree, MachinePostDominatorTree &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37347c3bcb72b1a6c2ab0b5dc28cb34b">deleteBB</a> (MachineBasicBlock *DelBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete DelBB. <a href="#a37347c3bcb72b1a6c2ab0b5dc28cb34b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">MachineDomTreeUpdater.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Base {#a34c27b709939802f420472199343ef43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineDomTreeUpdater::Base = 
      GenericDomTreeUpdater&lt;MachineDomTreeUpdater, MachineDominatorTree,
                            MachinePostDominatorTree&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">MachineDomTreeUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineDomTreeUpdater() {#a095af11c37370db5be9f638de4168238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineDomTreeUpdater::~MachineDomTreeUpdater ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">MachineDomTreeUpdater.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a43c80a160270d75d99cfeb080c165694">llvm::GenericDomTreeUpdater&lt; MachineDomTreeUpdater, MachineDominatorTree, MachinePostDominatorTree &gt;::flush</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### forceFlushDeletedBB() {#a4acf646d484cfde2074b23ef6d6e1199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineDomTreeUpdater::forceFlushDeletedBB ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if at least one <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> is deleted.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">MachineDomTreeUpdater.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinedomtreeupdater-cpp">MachineDomTreeUpdater.cpp</a>.</p>

</div>
</div>

### validateDeleteBB() {#a3baf55e2d6a16f5fd88b6492eefcb4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineDomTreeUpdater::validateDeleteBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DelBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>First remove all the instructions of DelBB and then make sure DelBB has a valid terminator instruction which is necessary to have when DelBB still has to be inside of its parent <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> while awaiting deletion under Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a> to prevent other routines from asserting the state of the IR is inconsistent.</p>


<p>Assert if DelBB is nullptr or has predecessors.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">MachineDomTreeUpdater.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinedomtreeupdater-cpp">MachineDomTreeUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GenericDomTreeUpdater&lt; MachineDomTreeUpdater, MachineDominatorTree, MachinePostDominatorTree &gt; {#a4e7d9ac53a9826eb235e14e1beb0f0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::MachineDomTreeUpdater::GenericDomTreeUpdater&lt; MachineDomTreeUpdater, MachineDominatorTree, MachinePostDominatorTree &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">MachineDomTreeUpdater.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Mutation APIs

### deleteBB {#a37347c3bcb72b1a6c2ab0b5dc28cb34b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineDomTreeUpdater::deleteBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DelBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete DelBB.</p>


<p>DelBB will be removed from its Parent and erased from available trees if it exists and finally get deleted. Under Eager <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>, DelBB will be processed immediately. Under Lazy <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a2655b89361decf2c1493792dc14e5a56">UpdateStrategy</a>, DelBB will be queued until a flush event and all available trees are up-to-date. Assert if any instruction of DelBB is modified while awaiting deletion. When both DT and PDT are nullptrs, DelBB will be queued until <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a43c80a160270d75d99cfeb080c165694">flush()</a> is called.</p>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">MachineDomTreeUpdater.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinedomtreeupdater-cpp">MachineDomTreeUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a03640c958debd0b9a525cff8fe5a11ed">llvm::GenericDomTreeUpdater&lt; MachineDomTreeUpdater, MachineDominatorTree, MachinePostDominatorTree &gt;::DeletedBBs</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a42eae544363676292b0d6a03d06ba9df">llvm::GenericDomTreeUpdater&lt; MachineDomTreeUpdater, MachineDominatorTree, MachinePostDominatorTree &gt;::eraseDelBBNode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ac421fe6513e43aedbba712e4a981744e">llvm::MachineBasicBlock::eraseFromParent</a> and <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a6c1229274a768152e5ed6af3872af602">llvm::GenericDomTreeUpdater&lt; MachineDomTreeUpdater, MachineDominatorTree, MachinePostDominatorTree &gt;::Strategy</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">MachineDomTreeUpdater.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinedomtreeupdater-cpp">MachineDomTreeUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
