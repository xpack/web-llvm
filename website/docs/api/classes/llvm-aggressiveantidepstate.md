---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aggressiveantidepstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AggressiveAntiDepState` Class

<p>Contains all the state necessary for anti-dep breaking. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AggressiveAntiDepState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">CodeGen/AggressiveAntiDepBreaker.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8e899a88a4162aeeaca5461012bb78">AggressiveAntiDepState</a> (const unsigned TargetRegs, MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc262ecf92c28647ff8a46216e82c0c1">GetKillIndices</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the kill indices. <a href="#acc262ecf92c28647ff8a46216e82c0c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6258f0ca25623f12e1c543467ad51f68">GetDefIndices</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the define indices. <a href="#a6258f0ca25623f12e1c543467ad51f68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::multimap&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/aggressiveantidepstate/registerreference">RegisterReference</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1f0778f56b17cb4ae959934b0a95b2">GetRegRefs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the RegRefs map. <a href="#a8c1f0778f56b17cb4ae959934b0a95b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8875a9b7c0c6feb3448437e75b9356f5">GetGroup</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560eaba05729f660add3032185f9fbfb">GetGroupRegs</a> (unsigned Group, std::vector&lt; unsigned &gt; &amp;Regs, std::multimap&lt; unsigned, AggressiveAntiDepState::RegisterReference &gt; *RegRefs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2acf6127130067c40e3b47fd632d127">UnionGroups</a> (unsigned Reg1, unsigned Reg2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a744b242deb550943b03c470134020f52">LeaveGroup</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6eff8804ae39a7820d75f2c87fa5598">IsLive</a> (unsigned Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if Reg is live. <a href="#aa6eff8804ae39a7820d75f2c87fa5598">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5db545f6beb24a07508ca78e298ac8e">NumTargetRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of non-virtual target registers (i.e. TRI-&gt;getNumRegs()). <a href="#ae5db545f6beb24a07508ca78e298ac8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaba3c4975e36e28e0690523f941a99b">GroupNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements a disjoint-union data structure to form register groups. <a href="#afaba3c4975e36e28e0690523f941a99b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e6548530387ebf4d1da726cedcd6e7">GroupNodeIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each register, the index of the GroupNode currently representing the group that the register belongs to. <a href="#a99e6548530387ebf4d1da726cedcd6e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::multimap&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/aggressiveantidepstate/registerreference">RegisterReference</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86dcd1edf8abe41a93ae427c565f8cb0">RegRefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map registers to all their references within a live range. <a href="#a86dcd1edf8abe41a93ae427c565f8cb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a780e217952c6283bde75d4aed214af89">KillIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the most recent kill (proceeding bottom-up), or ~0u if the register is not live. <a href="#a780e217952c6283bde75d4aed214af89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b5b44878a3c8bd51838458ec5f6ed35">DefIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the most recent complete def (proceeding bottom up), or ~0u if the register is live. <a href="#a7b5b44878a3c8bd51838458ec5f6ed35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Contains all the state necessary for anti-dep breaking.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AggressiveAntiDepState() {#a0c8e899a88a4162aeeaca5461012bb78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AggressiveAntiDepState::AggressiveAntiDepState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned TargetRegs, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adbff55f335d303816547f35eb6edb948">llvm::MachineBasicBlock::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### GetDefIndices() {#a6258f0ca25623f12e1c543467ad51f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; unsigned &gt; &amp; llvm::AggressiveAntiDepState::GetDefIndices ()</td>
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

<p>Return the define indices.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### GetGroup() {#a8875a9b7c0c6feb3448437e75b9356f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AggressiveAntiDepState::GetGroup (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>Referenced by <a href="#a560eaba05729f660add3032185f9fbfb">GetGroupRegs</a> and <a href="#ac2acf6127130067c40e3b47fd632d127">UnionGroups</a>.</p>

</div>
</div>

### GetGroupRegs() {#a560eaba05729f660add3032185f9fbfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveAntiDepState::GetGroupRegs (unsigned Group, std::vector&lt; unsigned &gt; &amp; Regs, std::multimap&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/aggressiveantidepstate/registerreference">AggressiveAntiDepState::RegisterReference</a> &gt; * RegRefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>Reference <a href="#a8875a9b7c0c6feb3448437e75b9356f5">GetGroup</a>.</p>

</div>
</div>

### GetKillIndices() {#acc262ecf92c28647ff8a46216e82c0c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; unsigned &gt; &amp; llvm::AggressiveAntiDepState::GetKillIndices ()</td>
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

<p>Return the kill indices.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### GetRegRefs() {#a8c1f0778f56b17cb4ae959934b0a95b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::multimap&lt; unsigned, RegisterReference &gt; &amp; llvm::AggressiveAntiDepState::GetRegRefs ()</td>
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

<p>Return the RegRefs map.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### IsLive() {#aa6eff8804ae39a7820d75f2c87fa5598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AggressiveAntiDepState::IsLive (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if Reg is live.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### LeaveGroup() {#a744b242deb550943b03c470134020f52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AggressiveAntiDepState::LeaveGroup (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### UnionGroups() {#ac2acf6127130067c40e3b47fd632d127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AggressiveAntiDepState::UnionGroups (unsigned Reg1, unsigned Reg2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8875a9b7c0c6feb3448437e75b9356f5">GetGroup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DefIndices {#a7b5b44878a3c8bd51838458ec5f6ed35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::AggressiveAntiDepState::DefIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the most recent complete def (proceeding bottom up), or ~0u if the register is live.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### GroupNodeIndices {#a99e6548530387ebf4d1da726cedcd6e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::AggressiveAntiDepState::GroupNodeIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For each register, the index of the GroupNode currently representing the group that the register belongs to.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> 0 is always represented by the 0 group, a group composed of registers that are not eligible for anti-aliasing.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### GroupNodes {#afaba3c4975e36e28e0690523f941a99b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::AggressiveAntiDepState::GroupNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements a disjoint-union data structure to form register groups.</p>


<p>A node is represented by an index into the vector. A node can "point to" itself to indicate that it is the parent of a group, or point to another node to indicate that it is a member of the same group as that node.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### KillIndices {#a780e217952c6283bde75d4aed214af89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::AggressiveAntiDepState::KillIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the most recent kill (proceeding bottom-up), or ~0u if the register is not live.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### NumTargetRegs {#ae5db545f6beb24a07508ca78e298ac8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::AggressiveAntiDepState::NumTargetRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of non-virtual target registers (i.e. TRI-&gt;getNumRegs()).</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### RegRefs {#a86dcd1edf8abe41a93ae427c565f8cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::multimap&lt;unsigned, RegisterReference&gt; llvm::AggressiveAntiDepState::RegRefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map registers to all their references within a live range.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
