---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineloop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineLoop` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachineLoop { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopbase">LoopBase&lt;BlockT, LoopT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instances of this class are used to represent loops that are detected in the flow graph. <a href="/web-llvm/docs/api/classes/llvm/loopbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b25b2f840c82a24dfd0fe80b5cfefc9">LoopInfoBase&lt; MachineBasicBlock, MachineLoop &gt;</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67f66885ba37646c0069ee7ad57686f">MachineLoop</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3637288a6f4af3b6d1143e96a99baa4d">MachineLoop</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb3765b2827835823c1c55d12b33957">getTopBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the "top" block in the loop, which is the first block in the linear layout, ignoring any parts of the loop not contiguous with the part that contains the header. <a href="#adfb3765b2827835823c1c55d12b33957">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d6d2568abd0f3161ac255b4c6e1f4c">getBottomBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the "bottom" block in the loop, which is the last block in the linear layout, ignoring any parts of the loop not contiguous with the part that contains the header. <a href="#aa5d6d2568abd0f3161ac255b4c6e1f4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c5ce341ebbe98e0a15ea6914661f0b">findLoopControlBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the block that contains the loop control variable and the loop test. <a href="#a21c5ce341ebbe98e0a15ea6914661f0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8272f9a740bb9f21c0a1025873ae697a">getStartLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the debug location of the start of this loop. <a href="#a8272f9a740bb9f21c0a1025873ae697a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670b0c3e3a586e3263765d61f840cf22">getLoopID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the llvm.loop metadata for this loop. <a href="#a670b0c3e3a586e3263765d61f840cf22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ba70811fe6842e3354120afc36c8d5">isLoopInvariant</a> (MachineInstr &amp;I, const Register ExcludeReg=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction is loop invariant. <a href="#ac3ba70811fe6842e3354120afc36c8d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8540c69f528369eb693bb2fafc1d7030">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6943de33e6f8e1d4c00e535578950acc">isLoopInvariantImplicitPhysReg</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given physreg has no defs inside the loop. <a href="#a6943de33e6f8e1d4c00e535578950acc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LoopInfoBase&lt; MachineBasicBlock, MachineLoop &gt; {#a7b25b2f840c82a24dfd0fe80b5cfefc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/loopinfobase">LoopInfoBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MachineLoop() {#af67f66885ba37646c0069ee7ad57686f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineLoop::MachineLoop (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>.</p>

</div>
</div>

### MachineLoop() {#a3637288a6f4af3b6d1143e96a99baa4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineLoop::MachineLoop ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a8540c69f528369eb693bb2fafc1d7030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineLoop::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::print</a>.</p>

</div>
</div>

### findLoopControlBlock() {#a21c5ce341ebbe98e0a15ea6914661f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineLoop::findLoopControlBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the block that contains the loop control variable and the loop test.</p>


<p>This will return the latch block if it's one of the exiting blocks. Otherwise, return the exiting block. Return 'null' when multiple exiting blocks are present.</p>


<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#adf6f53d7652b471c995b7d10f3dd2729">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::getExitingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::getLoopLatch</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#af691775d5a45e28afbdb3e97cab22eee">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::isLoopExiting</a>.</p>


<p>Referenced by <a href="#a670b0c3e3a586e3263765d61f840cf22">getLoopID</a>.</p>

</div>
</div>

### getBottomBlock() {#aa5d6d2568abd0f3161ac255b4c6e1f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineLoop::getBottomBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the "bottom" block in the loop, which is the last block in the linear layout, ignoring any parts of the loop not contiguous with the part that contains the header.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>.</p>

</div>
</div>

### getLoopID() {#a670b0c3e3a586e3263765d61f840cf22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MachineLoop::getLoopID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the llvm.loop metadata for this loop.</p>


<p>If each branch to the header of this loop contains the same llvm.loop metadata, then this metadata node is returned. Otherwise, if any latch instruction does not contain the llvm.loop metadata or multiple latch instructions contain different llvm.loop metadata nodes, then null is returned.</p>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::blocks</a>, <a href="#a21c5ce341ebbe98e0a15ea6914661f0b">findLoopControlBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>

</div>
</div>

### getStartLoc() {#a8272f9a740bb9f21c0a1025873ae697a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc MachineLoop::getStartLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the debug location of the start of this loop.</p>


<p>This looks for a BB terminating instruction with a known debug location by looking at the preheader and header blocks. If it cannot find a terminating instruction with location information, it returns an unknown location.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::getHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::getLoopPreheader</a>.</p>

</div>
</div>

### getTopBlock() {#adfb3765b2827835823c1c55d12b33957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineLoop::getTopBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the "top" block in the loop, which is the first block in the linear layout, ignoring any parts of the loop not contiguous with the part that contains the header.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>.</p>

</div>
</div>

### isLoopInvariant() {#ac3ba70811fe6842e3354120afc36c8d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLoop::isLoopInvariant (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ExcludeReg=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the instruction is loop invariant.</p>


<p>I.e., all virtual register operands are defined outside of the loop, physical registers aren't accessed explicitly, and there are no side effects that aren't captured by the operands or other flags. ExcludeReg can be used to exclude the given register from the check i.e. when we're considering hoisting it's definition but not hoisted it yet</p>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; MachineBasicBlock, MachineLoop &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isLoopInvariantImplicitPhysReg() {#a6943de33e6f8e1d4c00e535578950acc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineLoop::isLoopInvariantImplicitPhysReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the given physreg has no defs inside the loop.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">MachineLoopInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineloopinfo-cpp">MachineLoopInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
