---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcndownwardrptracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCNDownwardRPTracker` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GCNDownwardRPTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">Target/AMDGPU/GCNRegPressure.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcnrptracker">GCNRPTracker</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e281cc5ec2888ede3051a3f5688e13">GCNDownwardRPTracker</a> (const LiveIntervals &amp;LIS_)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4d51e36b5ad49b3a5cad9dd82f835e">getNext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194c6037c4a80778db65e013496a0f76">moveMaxPressure</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">return</span> MaxPressure and clear it. <a href="#a194c6037c4a80778db65e013496a0f76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95cb78cfa1044889fefc65225f611e33">reset</a> (const MachineInstr &amp;MI, const LiveRegSet *LiveRegs=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset tracker to the point before the <span class="doxyComputerOutput">MI</span> filling <span class="doxyComputerOutput">LiveRegs</span> upon this point using LIS. <a href="#a95cb78cfa1044889fefc65225f611e33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a222d514d23098e92ecbd53e36b3c5084">advanceBeforeNext</a> (MachineInstr *MI=nullptr, bool UseInternalIterator=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move to the state right before the next MI or after the end of MBB. <a href="#a222d514d23098e92ecbd53e36b3c5084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda01c47a26407d9bf35e27efc904136">advanceToNext</a> (MachineInstr *MI=nullptr, bool UseInternalIterator=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move to the state at the MI, advanceBeforeNext has to be called first. <a href="#adda01c47a26407d9bf35e27efc904136">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28cf8598083957e4dbe32030b75a179b">advance</a> (MachineInstr *MI=nullptr, bool UseInternalIterator=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move to the state at the next MI. <a href="#a28cf8598083957e4dbe32030b75a179b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1378b886a42c2f813e0624d4d34e742f">advance</a> (MachineBasicBlock::const_iterator End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance instructions until before <span class="doxyComputerOutput">End</span>. <a href="#a1378b886a42c2f813e0624d4d34e742f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acacc3378d6418035be1ad851c03f8c9c">advance</a> (MachineBasicBlock::const_iterator Begin, MachineBasicBlock::const_iterator End, const LiveRegSet *LiveRegsCopy=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset to <span class="doxyComputerOutput">Begin</span> and advance to <span class="doxyComputerOutput">End</span>. <a href="#acacc3378d6418035be1ad851c03f8c9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gcnregpressure">GCNRegPressure</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa250f99a782d2da223c54ecde4acd0">bumpDownwardPressure</a> (const MachineInstr *MI, const SIRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mostly copy/paste from <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">CodeGen/RegisterPressure.cpp</a> Calculate the impact <span class="doxyComputerOutput">MI</span> will have on CurPressure and. <a href="#a4fa250f99a782d2da223c54ecde4acd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5392b4136b981c481ff22a58958aced">reset</a> (const MachineInstr &amp;MI, const LiveRegSet *LiveRegsCopy, bool After)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0da90b9f153963f1b241afe67d4096">reset</a> (const MachineRegisterInfo &amp;MRI_, const LiveRegSet &amp;LiveRegs_)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee66483ad05cbda25ea4c28315adae72">NextMI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ae230ab6aa51661a4e0d1937c08339">MBBEnd</a></td>
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


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCNDownwardRPTracker() {#a87e281cc5ec2888ede3051a3f5688e13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCNDownwardRPTracker::GCNDownwardRPTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS_)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a9e68c28afd52433cfe5de2743a051ad2">llvm::GCNRPTracker::GCNRPTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### advance() {#a28cf8598083957e4dbe32030b75a179b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNDownwardRPTracker::advance (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI=nullptr, bool UseInternalIterator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move to the state at the next MI.</p>


<p><span class="doxyComputerOutput">returns</span> false if reached end of block. If <span class="doxyComputerOutput">UseInternalIterator</span> is true, then internal iterators are used and set to process in program order. If <span class="doxyComputerOutput">UseInternalIterator</span> is false, then it is assumed that the tracker is using an externally managed iterator, and advance* calls will not update the state of the iterator. In such cases, the tracker will move to the state right before the provided <span class="doxyComputerOutput">MI</span> and use LIS for RP calculations.</p>


<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="#a222d514d23098e92ecbd53e36b3c5084">advanceBeforeNext</a>, <a href="#adda01c47a26407d9bf35e27efc904136">advanceToNext</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#acacc3378d6418035be1ad851c03f8c9c">advance</a>, <a href="#a1378b886a42c2f813e0624d4d34e742f">advance</a> and <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### advance() {#a1378b886a42c2f813e0624d4d34e742f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNDownwardRPTracker::advance (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance instructions until before <span class="doxyComputerOutput">End</span>.</p>

<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>Reference <a href="#a28cf8598083957e4dbe32030b75a179b">advance</a>.</p>

</div>
</div>

### advance() {#acacc3378d6418035be1ad851c03f8c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNDownwardRPTracker::advance (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> End, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> * LiveRegsCopy=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset to <span class="doxyComputerOutput">Begin</span> and advance to <span class="doxyComputerOutput">End</span>.</p>

<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="#a28cf8598083957e4dbe32030b75a179b">advance</a> and <a href="#a95cb78cfa1044889fefc65225f611e33">reset</a>.</p>

</div>
</div>

### advanceBeforeNext() {#a222d514d23098e92ecbd53e36b3c5084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNDownwardRPTracker::advanceBeforeNext (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI=nullptr, bool UseInternalIterator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move to the state right before the next MI or after the end of MBB.</p>


<p><span class="doxyComputerOutput">returns</span> false if reached end of the block. If <span class="doxyComputerOutput">UseInternalIterator</span> is true, then internal iterators are used and set to process in program order. If <span class="doxyComputerOutput">UseInternalIterator</span> is false, then it is assumed that the tracker is using an externally managed iterator, and advance* calls will not update the state of the iterator. In such cases, the tracker will move to the state right before the provided <span class="doxyComputerOutput">MI</span> and use LIS for RP calculations.</p>


<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a41b82ba049ec10e292e11bc79bd56bfd">llvm::GCNRPTracker::CurPressure</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a17a9972194d5c04aaa9366c010e9dabe">llvm::GCNRPTracker::LastTrackedMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ada6b5ab2740ab258cfa190c2a5acf8f5">llvm::GCNRPTracker::LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a400c0b88110521ad1de258a7885d9038">llvm::LiveRange::liveAt</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a0a547786ee2b51d087a8d47077a0a7de">llvm::GCNRPTracker::LiveRegs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">llvm::max</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#aa76f3a5de6758b1c12c3bfaa80ee0879">llvm::GCNRPTracker::MaxPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ad98cf5d6dde476f24e8221f34a918deb">llvm::GCNRPTracker::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>.</p>


<p>Referenced by <a href="#a28cf8598083957e4dbe32030b75a179b">advance</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### advanceToNext() {#adda01c47a26407d9bf35e27efc904136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNDownwardRPTracker::advanceToNext (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI=nullptr, bool UseInternalIterator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move to the state at the MI, advanceBeforeNext has to be called first.</p>


<p>If <span class="doxyComputerOutput">UseInternalIterator</span> is true, then internal iterators are used and set to process in program order. If <span class="doxyComputerOutput">UseInternalIterator</span> is false, then it is assumed that the tracker is using an externally managed iterator, and advance* calls will not update the state of the iterator. In such cases, the tracker will move to the state at the provided <span class="doxyComputerOutput">MI</span> .</p>


<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ade4229c653b0cbcaca057e8af5002783">llvm::MachineInstr::all_defs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a41b82ba049ec10e292e11bc79bd56bfd">llvm::GCNRPTracker::CurPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a827d52327fbe1bd7bf22242e7c18847d">getDefRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a17a9972194d5c04aaa9366c010e9dabe">llvm::GCNRPTracker::LastTrackedMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a0a547786ee2b51d087a8d47077a0a7de">llvm::GCNRPTracker::LiveRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">llvm::max</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#aa76f3a5de6758b1c12c3bfaa80ee0879">llvm::GCNRPTracker::MaxPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ad98cf5d6dde476f24e8221f34a918deb">llvm::GCNRPTracker::MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>.</p>


<p>Referenced by <a href="#a28cf8598083957e4dbe32030b75a179b">advance</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### bumpDownwardPressure() {#a4fa250f99a782d2da223c54ecde4acd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure GCNDownwardRPTracker::bumpDownwardPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mostly copy/paste from <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">CodeGen/RegisterPressure.cpp</a> Calculate the impact <span class="doxyComputerOutput">MI</span> will have on CurPressure and.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the speculated pressure. In order to support RP Speculation, this does not rely on the implicit program ordering in the <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>.</p></dd>
</dl>


<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a41b82ba049ec10e292e11bc79bd56bfd">llvm::GCNRPTracker::CurPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a2b640124aa4a430ee67d5409120e4deb">llvm::RegisterOperands::Defs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#abbe36a4a2c040ff3e4a6040a900b0997">llvm::GCNRPTracker::getLastUsedLanes</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#a8a4c16c737c90f7de638e1ee724d4785">llvm::GCNRegPressure::inc</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a17a9972194d5c04aaa9366c010e9dabe">llvm::GCNRPTracker::LastTrackedMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ada6b5ab2740ab258cfa190c2a5acf8f5">llvm::GCNRPTracker::LIS</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a0a547786ee2b51d087a8d47077a0a7de">llvm::GCNRPTracker::LiveRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ad98cf5d6dde476f24e8221f34a918deb">llvm::GCNRPTracker::MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acf9cb57c0c3b81e758a2af8aca736842">llvm::RegisterOperands::Uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a>.</p>

</div>
</div>

### getNext() {#a7b4d51e36b5ad49b3a5cad9dd82f835e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::const_iterator llvm::GCNDownwardRPTracker::getNext ()</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### moveMaxPressure() {#a194c6037c4a80778db65e013496a0f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNRegPressure llvm::GCNDownwardRPTracker::moveMaxPressure ()</td>
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

<p><span class="doxyComputerOutput">return</span> MaxPressure and clear it.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#aa76f3a5de6758b1c12c3bfaa80ee0879">llvm::GCNRPTracker::MaxPressure</a>.</p>

</div>
</div>

### reset() {#a95cb78cfa1044889fefc65225f611e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNDownwardRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> * LiveRegs=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset tracker to the point before the <span class="doxyComputerOutput">MI</span> filling <span class="doxyComputerOutput">LiveRegs</span> upon this point using LIS.</p>


<p><span class="doxyComputerOutput">returns</span> false if block is empty except debug values.</p>


<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a17a9972194d5c04aaa9366c010e9dabe">llvm::GCNRPTracker::LastTrackedMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ad98cf5d6dde476f24e8221f34a918deb">llvm::GCNRPTracker::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#ab5392b4136b981c481ff22a58958aced">llvm::GCNRPTracker::reset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>.</p>


<p>Referenced by <a href="#acacc3378d6418035be1ad851c03f8c9c">advance</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### reset() {#ab5392b4136b981c481ff22a58958aced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> * LiveRegsCopy, bool After)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>

</div>
</div>

### reset() {#a4a0da90b9f153963f1b241afe67d4096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNRPTracker::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a48c9e1114fb048675cd2d7174dfcc999">LiveRegSet</a> &amp; LiveRegs_)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MBBEnd {#a74ae230ab6aa51661a4e0d1937c08339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::const_iterator llvm::GCNDownwardRPTracker::MBBEnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>

</div>
</div>

### NextMI {#aee66483ad05cbda25ea4c28315adae72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::const_iterator llvm::GCNDownwardRPTracker::NextMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
