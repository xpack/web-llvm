---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vliwpacketizerlist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VLIWPacketizerList` Class



## Declaration

<div class="doxyDeclaration">
class llvm::VLIWPacketizerList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">llvm/CodeGen/DFAPacketizer.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist">R600PacketizerList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist">HexagonPacketizerList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1535a24a0c1b6049bba8cce276f8033f">VLIWPacketizerList</a> (MachineFunction &amp;MF, MachineLoopInfo &amp;MLI, AAResults *AA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2e38904990cccef709c985b323566e">VLIWPacketizerList</a> (const VLIWPacketizerList &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99817b33ea35dd4c95d91d34d1f94a43">~VLIWPacketizerList</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist">VLIWPacketizerList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878fc0ab7f6b62fea34c7d6fc52928c3">operator=</a> (const VLIWPacketizerList &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator BeginItr, MachineBasicBlock::iterator EndItr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dfapacketizer">DFAPacketizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acacf6d4690a265959ef93817d8230118">getResourceTracker</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae687f7292a0b3db97788f744d37d85d4">addToPacket</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05188b9f403d9279681683e2a7b3d3e">endPacket</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3369d49af4b9e73ea4946d83113cda5">initPacketizerState</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e01bf4eca10a5d5f07920f8cf84fab">ignorePseudoInstruction</a> (const MachineInstr &amp;I, const MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19245ba7597bdc448d2d9f21865e2b64">isSoloInstruction</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8cb79fea0e885619bcdb347e2bc22c">shouldAddToPacket</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed4f250d154c460d2acd08c81aae5b3">isLegalToPacketizeTogether</a> (SUnit *SUI, SUnit *SUJ)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cec2dc6fdf9c6662c833a91db3b7db3">isLegalToPruneDependencies</a> (SUnit *SUI, SUnit *SUJ)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4649b5bf16bf1dd02a1edd3a6b44be">addMutation</a> (std::unique_ptr&lt; ScheduleDAGMutation &gt; Mutation)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a49db9f3f84ee0258f9db321f1c7f9f">alias</a> (const MachineInstr &amp;MI1, const MachineInstr &amp;MI2, bool UseTBAA=true) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6002b152456ae7e8b84cbb5678a41640">alias</a> (const MachineMemOperand &amp;Op1, const MachineMemOperand &amp;Op2, bool UseTBAA=true) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b3d85290b815a7b870ea1b841d4288">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f50fd2b4dcd0bfcb409df2903776f45">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cd7219145832625cfe1d7b5b873c7d">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/defaultvliwscheduler">DefaultVLIWScheduler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc4ef70bbaad0768409bc9bc56865ea">VLIWScheduler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce4208a9adff0d4c41486339da72880">CurrentPacketMIs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dfapacketizer">DFAPacketizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa563675151ea61dfc14e8dd078327bc9">ResourceTracker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73fbb834524be9f7106e907bff83cf06">MIToSUnit</a></td>
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


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VLIWPacketizerList() {#a1535a24a0c1b6049bba8cce276f8033f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWPacketizerList::VLIWPacketizerList (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; MLI, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>


<p>References <a href="#a34cd7219145832625cfe1d7b5b873c7d">AA</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a>, <a href="#a12b3d85290b815a7b870ea1b841d4288">MF</a>, <a href="#aa563675151ea61dfc14e8dd078327bc9">ResourceTracker</a>, <a href="#a4f50fd2b4dcd0bfcb409df2903776f45">TII</a> and <a href="#a8bc4ef70bbaad0768409bc9bc56865ea">VLIWScheduler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0bd4071843f49d48f53401da3603c0e9">llvm::HexagonPacketizerList::HexagonPacketizerList</a>, <a href="#a878fc0ab7f6b62fea34c7d6fc52928c3">operator=</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#a77ab021a2a74c107e096dbca4fafecf5">anonymous{R600Packetizer.cpp}::R600PacketizerList::R600PacketizerList</a> and <a href="#a2e2e38904990cccef709c985b323566e">VLIWPacketizerList</a>.</p>

</div>
</div>

### VLIWPacketizerList() {#a2e2e38904990cccef709c985b323566e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VLIWPacketizerList::VLIWPacketizerList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist">VLIWPacketizerList</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a1535a24a0c1b6049bba8cce276f8033f">VLIWPacketizerList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VLIWPacketizerList() {#a99817b33ea35dd4c95d91d34d1f94a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWPacketizerList::~VLIWPacketizerList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>


<p>References <a href="#aa563675151ea61dfc14e8dd078327bc9">ResourceTracker</a> and <a href="#a8bc4ef70bbaad0768409bc9bc56865ea">VLIWScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a878fc0ab7f6b62fea34c7d6fc52928c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWPacketizerList &amp; llvm::VLIWPacketizerList::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist">VLIWPacketizerList</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Reference <a href="#a1535a24a0c1b6049bba8cce276f8033f">VLIWPacketizerList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addMutation() {#a1a4649b5bf16bf1dd02a1edd3a6b44be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VLIWPacketizerList::addMutation (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> &gt; Mutation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a> and <a href="#a8bc4ef70bbaad0768409bc9bc56865ea">VLIWScheduler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0bd4071843f49d48f53401da3603c0e9">llvm::HexagonPacketizerList::HexagonPacketizerList</a>.</p>

</div>
</div>

### addToPacket() {#ae687f7292a0b3db97788f744d37d85d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MachineBasicBlock::iterator llvm::VLIWPacketizerList::addToPacket (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>References <a href="#a6ce4208a9adff0d4c41486339da72880">CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aa563675151ea61dfc14e8dd078327bc9">ResourceTracker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#abfcc0b59be9882aca9a246d1ee6a1eb0">anonymous{R600Packetizer.cpp}::R600PacketizerList::addToPacket</a> and <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>.</p>

</div>
</div>

### alias() {#a5a49db9f3f84ee0258f9db321f1c7f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VLIWPacketizerList::alias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI2, bool UseTBAA=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>


<p>References <a href="#a5a49db9f3f84ee0258f9db321f1c7f9f">alias</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab37075d621acbbfc96ef2662f2e29883">llvm::MachineInstr::memoperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a4cd2e2c219c477019aa343c92dcf56cb">llvm::MachineInstr::memoperands_empty</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a85e6100733f4ae2c0946eeab33a9086c">UseTBAA</a>.</p>


<p>Referenced by <a href="#a5a49db9f3f84ee0258f9db321f1c7f9f">alias</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### endPacket() {#ac05188b9f403d9279681683e2a7b3d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VLIWPacketizerList::endPacket (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>


<p>References <a href="#a6ce4208a9adff0d4c41486339da72880">CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aa563675151ea61dfc14e8dd078327bc9">ResourceTracker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#abfcc0b59be9882aca9a246d1ee6a1eb0">anonymous{R600Packetizer.cpp}::R600PacketizerList::addToPacket</a> and <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>.</p>

</div>
</div>

### getResourceTracker() {#acacf6d4690a265959ef93817d8230118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DFAPacketizer * llvm::VLIWPacketizerList::getResourceTracker ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Reference <a href="#aa563675151ea61dfc14e8dd078327bc9">ResourceTracker</a>.</p>

</div>
</div>

### ignorePseudoInstruction() {#ac0e01bf4eca10a5d5f07920f8cf84fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::VLIWPacketizerList::ignorePseudoInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>.</p>

</div>
</div>

### initPacketizerState() {#ab3369d49af4b9e73ea4946d83113cda5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::VLIWPacketizerList::initPacketizerState ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>.</p>

</div>
</div>

### isLegalToPacketizeTogether() {#a2ed4f250d154c460d2acd08c81aae5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::VLIWPacketizerList::isLegalToPacketizeTogether (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUI, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUJ)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>.</p>

</div>
</div>

### isLegalToPruneDependencies() {#a9cec2dc6fdf9c6662c833a91db3b7db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::VLIWPacketizerList::isLegalToPruneDependencies (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUI, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUJ)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>.</p>

</div>
</div>

### isSoloInstruction() {#a19245ba7597bdc448d2d9f21865e2b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::VLIWPacketizerList::isSoloInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>.</p>

</div>
</div>

### PacketizeMIs() {#acfb2315913d694fb3f1144279ab75a85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VLIWPacketizerList::PacketizeMIs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> BeginItr, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> EndItr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>


<p>References <a href="#ae687f7292a0b3db97788f744d37d85d4">addToPacket</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6ce4208a9adff0d4c41486339da72880">CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac05188b9f403d9279681683e2a7b3d3e">endPacket</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#ac0e01bf4eca10a5d5f07920f8cf84fab">ignorePseudoInstruction</a>, <a href="#ab3369d49af4b9e73ea4946d83113cda5">initPacketizerState</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp/#acc16edf21eddec420cd4b27adb3111c6">InstrCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp/#a49346b1c8b35e7fcccd41b3356ae37e9">InstrLimit</a>, <a href="#a2ed4f250d154c460d2acd08c81aae5b3">isLegalToPacketizeTogether</a>, <a href="#a9cec2dc6fdf9c6662c833a91db3b7db3">isLegalToPruneDependencies</a>, <a href="#a19245ba7597bdc448d2d9f21865e2b64">isSoloInstruction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a73fbb834524be9f7106e907bff83cf06">MIToSUnit</a>, <a href="#aa563675151ea61dfc14e8dd078327bc9">ResourceTracker</a>, <a href="#afa8cb79fea0e885619bcdb347e2bc22c">shouldAddToPacket</a> and <a href="#a8bc4ef70bbaad0768409bc9bc56865ea">VLIWScheduler</a>.</p>

</div>
</div>

### shouldAddToPacket() {#afa8cb79fea0e885619bcdb347e2bc22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::VLIWPacketizerList::shouldAddToPacket (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### alias() {#a6002b152456ae7e8b84cbb5678a41640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VLIWPacketizerList::alias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; Op2, bool UseTBAA=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AA {#a34cd7219145832625cfe1d7b5b873c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::VLIWPacketizerList::AA</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0bd4071843f49d48f53401da3603c0e9">llvm::HexagonPacketizerList::HexagonPacketizerList</a> and <a href="#a1535a24a0c1b6049bba8cce276f8033f">VLIWPacketizerList</a>.</p>

</div>
</div>

### CurrentPacketMIs {#a6ce4208a9adff0d4c41486339da72880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineInstr*&gt; llvm::VLIWPacketizerList::CurrentPacketMIs</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#abfcc0b59be9882aca9a246d1ee6a1eb0">anonymous{R600Packetizer.cpp}::R600PacketizerList::addToPacket</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#aec7e812b238864a5d4ddc2c6b2548c74">llvm::HexagonPacketizerList::addToPacket</a>, <a href="#ae687f7292a0b3db97788f744d37d85d4">addToPacket</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0256920aada1bf35dc3c90cbfba10e5d">llvm::HexagonPacketizerList::arePredicatesComplements</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a82b468a911dfb66ebd0e9dfafd6ec6a1">llvm::HexagonPacketizerList::calcStall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a284b9287f16ce98d3063620d92f54700">llvm::HexagonPacketizerList::canPromoteToDotCur</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a8185efd733082b43be2ca1a1b5d977ad">llvm::HexagonPacketizerList::cleanUpDotCur</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0917b287f84d46e070dbddb483e4ce94">llvm::HexagonPacketizerList::endPacket</a>, <a href="#ac05188b9f403d9279681683e2a7b3d3e">endPacket</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a868b649a2ce162e4c94bbc9fcfd5d3ab">llvm::HexagonPacketizerList::foundLSInPacket</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ad2f5472a8ef3d4a8979234c5bc76b2dc">anonymous{R600Packetizer.cpp}::R600PacketizerList::isBundlableWithCurrentPMI</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a642903485b484d638fafe7da8142cdd8">llvm::HexagonPacketizerList::restrictingDepExistInPacket</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ab2691fcbf8c425f40f56f085b5233783">llvm::HexagonPacketizerList::shouldAddToPacket</a>.</p>

</div>
</div>

### MF {#a12b3d85290b815a7b870ea1b841d4288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::VLIWPacketizerList::MF</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a284b9287f16ce98d3063620d92f54700">llvm::HexagonPacketizerList::canPromoteToDotCur</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a87edaaaaa788f8bc30dfad90aecdb343">llvm::HexagonPacketizerList::canPromoteToDotNew</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0bd4071843f49d48f53401da3603c0e9">llvm::HexagonPacketizerList::HexagonPacketizerList</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#a77ab021a2a74c107e096dbca4fafecf5">anonymous{R600Packetizer.cpp}::R600PacketizerList::R600PacketizerList</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ad36ca022c185189ffab3e5b69c97e12b">llvm::HexagonPacketizerList::tryAllocateResourcesForConstExt</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#aa591493a333d880df171a5036eb16449">llvm::HexagonPacketizerList::unpacketizeSoloInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2c4c903d0a03629b92e4bcc894bbd793">llvm::HexagonPacketizerList::useCalleesSP</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#abf8fdc79c6fcc0fb997214d040de1063">llvm::HexagonPacketizerList::useCallersSP</a> and <a href="#a1535a24a0c1b6049bba8cce276f8033f">VLIWPacketizerList</a>.</p>

</div>
</div>

### MIToSUnit {#a73fbb834524be9f7106e907bff83cf06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;MachineInstr*, SUnit*&gt; llvm::VLIWPacketizerList::MIToSUnit</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0256920aada1bf35dc3c90cbfba10e5d">llvm::HexagonPacketizerList::arePredicatesComplements</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a82b468a911dfb66ebd0e9dfafd6ec6a1">llvm::HexagonPacketizerList::calcStall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a642903485b484d638fafe7da8142cdd8">llvm::HexagonPacketizerList::restrictingDepExistInPacket</a>.</p>

</div>
</div>

### ResourceTracker {#aa563675151ea61dfc14e8dd078327bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DFAPacketizer* llvm::VLIWPacketizerList::ResourceTracker</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#aec7e812b238864a5d4ddc2c6b2548c74">llvm::HexagonPacketizerList::addToPacket</a>, <a href="#ae687f7292a0b3db97788f744d37d85d4">addToPacket</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a87edaaaaa788f8bc30dfad90aecdb343">llvm::HexagonPacketizerList::canPromoteToDotNew</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a0917b287f84d46e070dbddb483e4ce94">llvm::HexagonPacketizerList::endPacket</a>, <a href="#ac05188b9f403d9279681683e2a7b3d3e">endPacket</a>, <a href="#acacf6d4690a265959ef93817d8230118">getResourceTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#aa3867c828f38e2bf9dd517c69c682cc9">llvm::HexagonPacketizerList::ignorePseudoInstruction</a>, <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ab2691fcbf8c425f40f56f085b5233783">llvm::HexagonPacketizerList::shouldAddToPacket</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ad36ca022c185189ffab3e5b69c97e12b">llvm::HexagonPacketizerList::tryAllocateResourcesForConstExt</a>, <a href="#a1535a24a0c1b6049bba8cce276f8033f">VLIWPacketizerList</a> and <a href="#a99817b33ea35dd4c95d91d34d1f94a43">~VLIWPacketizerList</a>.</p>

</div>
</div>

### TII {#a4f50fd2b4dcd0bfcb409df2903776f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::VLIWPacketizerList::TII</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="#a1535a24a0c1b6049bba8cce276f8033f">VLIWPacketizerList</a>.</p>

</div>
</div>

### VLIWScheduler {#a8bc4ef70bbaad0768409bc9bc56865ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefaultVLIWScheduler* llvm::VLIWPacketizerList::VLIWScheduler</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a>.</p>


<p>Referenced by <a href="#a1a4649b5bf16bf1dd02a1edd3a6b44be">addMutation</a>, <a href="#acfb2315913d694fb3f1144279ab75a85">PacketizeMIs</a>, <a href="#a1535a24a0c1b6049bba8cce276f8033f">VLIWPacketizerList</a> and <a href="#a99817b33ea35dd4c95d91d34d1f94a43">~VLIWPacketizerList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">DFAPacketizer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
