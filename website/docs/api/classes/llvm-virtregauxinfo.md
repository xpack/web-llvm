---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/virtregauxinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VirtRegAuxInfo` Class

<p>Calculate auxiliary information for a virtual register such as its spill weight and allocation hint. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VirtRegAuxInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">llvm/CodeGen/CalcSpillWeights.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/pbqpvirtregauxinfo">PBQPVirtRegAuxInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PBQP-specific implementation of weight normalization. <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/pbqpvirtregauxinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67acd36a8a51bb0a789af4c19ff4bb4d">VirtRegAuxInfo</a> (MachineFunction &amp;MF, LiveIntervals &amp;LIS, const VirtRegMap &amp;VRM, const MachineLoopInfo &amp;Loops, const MachineBlockFrequencyInfo &amp;MBFI, ProfileSummaryInfo *PSI=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fbb56f62d9686fea21da81ee193de5">~VirtRegAuxInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab388ef162b7c6b9061678583f9fd0f16">calculateSpillWeightAndHint</a> (LiveInterval &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>(re)compute li's spill weight and allocation hint. <a href="#ab388ef162b7c6b9061678583f9fd0f16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a394261440649abcae4183f645af90a6d">calculateSpillWeightsAndHints</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute spill weights and allocation hints for all virtual register live intervals. <a href="#a394261440649abcae4183f645af90a6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137403167e291d2e011441ce02d51898">weightCalcHelper</a> (LiveInterval &amp;LI, SlotIndex *Start=nullptr, SlotIndex *End=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for weight calculations. <a href="#a137403167e291d2e011441ce02d51898">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dde429a6e275bf6f6618f659c5be4b7">normalize</a> (float UseDefFreq, unsigned Size, unsigned NumInstr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Weight normalization function. <a href="#a8dde429a6e275bf6f6618f659c5be4b7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf9e63f694ed5f493df5b5143ccb45b">isLiveAtStatepointVarArg</a> (LiveInterval &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Reg of live interval LI is used in instruction with many operands like STATEPOINT. <a href="#a5bf9e63f694ed5f493df5b5143ccb45b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a50978552b9c0a2b17e602a4f87edb">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01725f8c33cc3e524f1951914e93ac6e">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ed76e7a0029079f423d29ea321ffce0">VRM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf0fc0798655e5eecec00b24ac3dcb0e">Loops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab007e477235023dc61f1e16064aba2a9">PSI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1faa8c4f1a5ee8f0220b2b35fba8d1c7">MBFI</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01fce66601f12ad1b3bd219ff02c3426">copyHint</a> (const MachineInstr *MI, unsigned Reg, const TargetRegisterInfo &amp;TRI, const MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the preferred allocation register for reg, given a COPY instruction. <a href="#a01fce66601f12ad1b3bd219ff02c3426">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4d1b2ff6c306576d8ffa9922fa8ba3">isRematerializable</a> (const LiveInterval &amp;LI, const LiveIntervals &amp;LIS, const VirtRegMap &amp;VRM, const TargetInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if all values in LI are rematerializable. <a href="#a9e4d1b2ff6c306576d8ffa9922fa8ba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Calculate auxiliary information for a virtual register such as its spill weight and allocation hint.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VirtRegAuxInfo() {#a67acd36a8a51bb0a789af4c19ff4bb4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VirtRegAuxInfo::VirtRegAuxInfo (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; VRM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; Loops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> &amp; MBFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI=nullptr)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/pbqpvirtregauxinfo/#ab9d9c72d356da8d926532afd352ced3c">anonymous{RegAllocPBQP.cpp}::PBQPVirtRegAuxInfo::PBQPVirtRegAuxInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VirtRegAuxInfo() {#a19fbb56f62d9686fea21da81ee193de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::VirtRegAuxInfo::~VirtRegAuxInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculateSpillWeightAndHint() {#ab388ef162b7c6b9061678583f9fd0f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VirtRegAuxInfo::calculateSpillWeightAndHint (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>(re)compute li's spill weight and allocation hint.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp">CalcSpillWeights.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#af9c21366c83a0e52bd68da820745651d">llvm::LiveInterval::setWeight</a> and <a href="#a137403167e291d2e011441ce02d51898">weightCalcHelper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#a6c15e4226ea85c6c5ffdb7b907023b85">llvm::LiveRangeEdit::calculateRegClassAndHint</a> and <a href="#a394261440649abcae4183f645af90a6d">calculateSpillWeightsAndHints</a>.</p>

</div>
</div>

### calculateSpillWeightsAndHints() {#a394261440649abcae4183f645af90a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VirtRegAuxInfo::calculateSpillWeightsAndHints ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute spill weights and allocation hints for all virtual register live intervals.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp">CalcSpillWeights.cpp</a>.</p>


<p>References <a href="#ab388ef162b7c6b9061678583f9fd0f16">calculateSpillWeightAndHint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a94391e15de6cfad5cf6522641d8b7f95">anonymous{RegAllocBasic.cpp}::RABasic::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a82bfae004546453f47c217784928e0a5">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### normalize() {#a8dde429a6e275bf6f6618f659c5be4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual float llvm::VirtRegAuxInfo::normalize (float UseDefFreq, unsigned Size, unsigned NumInstr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Weight normalization function.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aea0a52847ac687ee3f8d144b248ebae0">llvm::normalizeSpillWeight</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a137403167e291d2e011441ce02d51898">weightCalcHelper</a>.</p>

</div>
</div>

### weightCalcHelper() {#a137403167e291d2e011441ce02d51898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float VirtRegAuxInfo::weightCalcHelper (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> * Start=nullptr, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> * End=nullptr)</td>
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

<p>Helper function for weight calculations.</p>


<p>(Re)compute LI's spill weight and allocation hint, or, for non null start and end - compute future expected spill weight of a split artifact of LI that will span between start and end slot indexes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LI</td>
<td class="doxyParamItemDescription"><p>The live interval for which to compute the weight.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Start</td>
<td class="doxyParamItemDescription"><p>The expected beginning of the split artifact. Instructions before start will not affect the weight. Relevant for weight calculation of future split artifact.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">End</td>
<td class="doxyParamItemDescription"><p>The expected end of the split artifact. Instructions after end will not affect the weight. Relevant for weight calculation of future split artifact.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The spill weight. Returns negative weight for unspillable LI.</p></dd>
</dl>


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp">CalcSpillWeights.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp/#a413851d287074f68f5d568f75155c283">canMemFoldInlineAsm</a>, <a href="#a01fce66601f12ad1b3bd219ff02c3426">copyHint</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a5d81038ff196d7a9495ff9f7266d667c">llvm::LiveInterval::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a7645b48e30da2e9ae644b6ade5663dbb">llvm::LiveIntervals::getSpillWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a4e12c0cb71a44b8822c5a35cbbe5c731">llvm::LiveRange::isLiveAtIndexes</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#af691775d5a45e28afbdb3e97cab22eee">llvm::LoopBase&lt; BlockT, LoopT &gt;::isLoopExiting</a>, <a href="#a9e4d1b2ff6c306576d8ffa9922fa8ba3">isRematerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1a07a284547e2997c90a6a1be428cd47">llvm::LiveInterval::isSpillable</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a61f530037a29a00a48799b14104a68d1">llvm::LiveRange::isZeroLength</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0f0455af60f6cc894c2f580b82042b0b">llvm::LiveInterval::markNotSpillable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a8dde429a6e275bf6f6618f659c5be4b7">normalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a061b224a1a3c3486fd854e5009a858c9">llvm::operator&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#ab388ef162b7c6b9061678583f9fd0f16">calculateSpillWeightAndHint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isLiveAtStatepointVarArg() {#a5bf9e63f694ed5f493df5b5143ccb45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VirtRegAuxInfo::isLiveAtStatepointVarArg (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if Reg of live interval LI is used in instruction with many operands like STATEPOINT.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp">CalcSpillWeights.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LIS {#a01725f8c33cc3e524f1951914e93ac6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; llvm::VirtRegAuxInfo::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>

</div>
</div>

### Loops {#adf0fc0798655e5eecec00b24ac3dcb0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineLoopInfo&amp; llvm::VirtRegAuxInfo::Loops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>

</div>
</div>

### MBFI {#a1faa8c4f1a5ee8f0220b2b35fba8d1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBlockFrequencyInfo&amp; llvm::VirtRegAuxInfo::MBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>

</div>
</div>

### MF {#a54a50978552b9c0a2b17e602a4f87edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::VirtRegAuxInfo::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>

</div>
</div>

### PSI {#ab007e477235023dc61f1e16064aba2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::VirtRegAuxInfo::PSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>

</div>
</div>

### VRM {#a6ed76e7a0029079f423d29ea321ffce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VirtRegMap&amp; llvm::VirtRegAuxInfo::VRM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### copyHint() {#a01fce66601f12ad1b3bd219ff02c3426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register VirtRegAuxInfo::copyHint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the preferred allocation register for reg, given a COPY instruction.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp">CalcSpillWeights.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/register/#a49effcc0d9e7a321043ade70145d11f6">llvm::Register::asMCReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a137403167e291d2e011441ce02d51898">weightCalcHelper</a>.</p>

</div>
</div>

### isRematerializable() {#a9e4d1b2ff6c306576d8ffa9922fa8ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VirtRegAuxInfo::isRematerializable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; VRM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if all values in LI are rematerializable.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp">CalcSpillWeights.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a5fb099e2afb74f4c922f32894b30b279">llvm::LiveRange::vni_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#aca7b7d6f329690e6bd5b5e1c83db7c1e">llvm::LiveRange::vni_end</a>.</p>


<p>Referenced by <a href="#a137403167e291d2e011441ce02d51898">weightCalcHelper</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">CalcSpillWeights.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp">CalcSpillWeights.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
