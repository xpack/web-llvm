---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-webassemblyregstackify-cpp-/commutingstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CommutingState` Class

<p>State to keep track of whether commuting is in flight or whether it's been tried for the current instruction and didn't work. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{WebAssemblyRegStackify.cpp}::CommutingState { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea15ac34bc701369f48c52d1c9a3adf">maybeCommute</a> (MachineInstr *Insert, TreeWalkerState &amp;TreeWalker, const WebAssemblyInstrInfo *TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stackification for an operand was not successful due to ordering constraints. <a href="#a4ea15ac34bc701369f48c52d1c9a3adf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2666f16ab9ff0288fdea2fd022f0bacf">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stackification for some operand was successful. <a href="#a2666f16ab9ff0288fdea2fd022f0bacf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be2d27825f4630f7a2dd2db9ae236fd">TentativelyCommuting</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>There are effectively three states: the initial state where we haven't started commuting anything and we don't know anything yet, the tentative state where we've commuted the operands of the current instruction and are revisiting it, and the declined state where we've reverted the operands back to their original order and will no longer commute it further. <a href="#a6be2d27825f4630f7a2dd2db9ae236fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706dfd0c30cda3b2734b465d4fa50326">Declined</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea1ebe4ca7a599ef2eb9dfb7aee4b78">Operand0</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>During the tentative state, these hold the operand indices of the commuted operands. <a href="#a5ea1ebe4ca7a599ef2eb9dfb7aee4b78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef4fca0127c216376df12f717fbf423">Operand1</a></td>
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

<p>State to keep track of whether commuting is in flight or whether it's been tried for the current instruction and didn't work.</p>

<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### maybeCommute() {#a4ea15ac34bc701369f48c52d1c9a3adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyRegStackify.cpp}::CommutingState::maybeCommute (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Insert, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregstackify-cpp-/treewalkerstate">TreeWalkerState</a> &amp; TreeWalker, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo">WebAssemblyInstrInfo</a> * TII)</td>
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

<p>Stackification for an operand was not successful due to ordering constraints.</p>


<p>If possible, and if we haven't already tried it and declined it, commute Insert's operands and prepare to revisit it.</p>


<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae73e2be2b66dc9e4f2f90d56076d7ea9">llvm::TargetInstrInfo::CommuteAnyOperandIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregstackify-cpp-/treewalkerstate/#aa5edebfea044309a470310fb2b20128e">anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::hasRemainingOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregstackify-cpp-/treewalkerstate/#a356eb98932f2179db61f9027ab50cce6">anonymous{WebAssemblyRegStackify.cpp}::TreeWalkerState::resetTopOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### reset() {#a2666f16ab9ff0288fdea2fd022f0bacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{WebAssemblyRegStackify.cpp}::CommutingState::reset ()</td>
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

<p>Stackification for some operand was successful.</p>


<p>Reset to the default state.</p>


<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Declined {#a706dfd0c30cda3b2734b465d4fa50326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyRegStackify.cpp}::CommutingState::Declined = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

### Operand0 {#a5ea1ebe4ca7a599ef2eb9dfb7aee4b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{WebAssemblyRegStackify.cpp}::CommutingState::Operand0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>During the tentative state, these hold the operand indices of the commuted operands.</p>

<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

### Operand1 {#a0ef4fca0127c216376df12f717fbf423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{WebAssemblyRegStackify.cpp}::CommutingState::Operand1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

### TentativelyCommuting {#a6be2d27825f4630f7a2dd2db9ae236fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WebAssemblyRegStackify.cpp}::CommutingState::TentativelyCommuting = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>There are effectively three states: the initial state where we haven't started commuting anything and we don't know anything yet, the tentative state where we've commuted the operands of the current instruction and are revisiting it, and the declined state where we've reverted the operands back to their original order and will no longer commute it further.</p>

<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp">WebAssemblyRegStackify.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
