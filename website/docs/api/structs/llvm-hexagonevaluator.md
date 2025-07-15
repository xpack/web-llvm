---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/hexagonevaluator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `HexagonEvaluator` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::HexagonEvaluator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">Target/Hexagon/HexagonBitTracker.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator">MachineEvaluator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8f60ca7a06508167e5bc0f00c1c75cd">CellMapType</a> = <a href="/web-llvm/docs/api/structs/llvm/bittracker/#ac0eea221b9e05301dfd8cb9ac47bc7d8">BitTracker::CellMapType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae95d2e2e4cfa9d21f07249ee597c942d">RegisterRef</a> = <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de8d99df6351fca1f48df07dd2b5eb0">RegisterCell</a> = <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a495e6e7b2e94dda7aaea1eaeacc25570">BranchTargetList</a> = <a href="/web-llvm/docs/api/structs/llvm/bittracker/#a47ead69576339dc99f21824830f15fcc">BitTracker::BranchTargetList</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7171d1c3b684a74eae67782c6e96eea">RegExtMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, ExtType &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2b22f49f8bb9c6c2d5c4ff5211d9e9">HexagonEvaluator</a> (const HexagonRegisterInfo &amp;tri, MachineRegisterInfo &amp;mri, const HexagonInstrInfo &amp;tii, MachineFunction &amp;mf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49b4d08c8b0024b97c7e090a0b3e50f6">evaluate</a> (const MachineInstr &amp;MI, const CellMapType &amp;Inputs, CellMapType &amp;Outputs) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8a4f85c8a56769ce682ff88d5b60f1">evaluate</a> (const MachineInstr &amp;BI, const CellMapType &amp;Inputs, BranchTargetList &amp;Targets, bool &amp;FallsThru) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/bitmask">BitTracker::BitMask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26c72fb657ffaea1a961279c6d3a80fb">mask</a> (Register Reg, unsigned Sub) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cd40aa7d878b134c54cf218b4fb5a6">getPhysRegBitWidth</a> (MCRegister Reg) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ef22a357f6b3f17e77b598df0ca45f">composeWithSubRegIndex</a> (const TargetRegisterClass &amp;RC, unsigned Idx) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05093380bce7d4370d6af9523ac10e0">getUniqueDefVReg</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77ba811c5df757eae792c111b8b825fc">evaluateLoad</a> (const MachineInstr &amp;MI, const CellMapType &amp;Inputs, CellMapType &amp;Outputs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adadfda429dbbfa7d188d6039eb702959">evaluateFormalCopy</a> (const MachineInstr &amp;MI, const CellMapType &amp;Inputs, CellMapType &amp;Outputs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633bbd0e138eb33135d905190a539e23">getNextPhysReg</a> (unsigned PReg, unsigned Width) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01b1854161bf46327d74e3430e56b71">getVirtRegFor</a> (unsigned PReg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ebd1745b8aea9e691aec9837465131e">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd44a21a5a54d02b58db73756788c04">MFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d419678a35ca8a83f34a302d9c62e23">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">RegExtMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d11e25c024cdb9ff43d3dfb5d70439b">VRX</a></td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BranchTargetList {#a495e6e7b2e94dda7aaea1eaeacc25570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonEvaluator::BranchTargetList =  BitTracker::BranchTargetList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>

</div>
</div>

### CellMapType {#ab8f60ca7a06508167e5bc0f00c1c75cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonEvaluator::CellMapType =  BitTracker::CellMapType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>

</div>
</div>

### RegisterCell {#a6de8d99df6351fca1f48df07dd2b5eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonEvaluator::RegisterCell =  BitTracker::RegisterCell</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>

</div>
</div>

### RegisterRef {#ae95d2e2e4cfa9d21f07249ee597c942d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonEvaluator::RegisterRef =  BitTracker::RegisterRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### RegExtMap {#ab7171d1c3b684a74eae67782c6e96eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HexagonEvaluator::RegExtMap =  DenseMap&lt;unsigned, ExtType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HexagonEvaluator() {#a5c2b22f49f8bb9c6c2d5c4ff5211d9e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonEvaluator::HexagonEvaluator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> &amp; tri, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; mri, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> &amp; tii, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4301e1f2a5607d796c5505a5a5919501">llvm::BitTracker::MachineEvaluator::MachineEvaluator</a>, <a href="#a7ebd1745b8aea9e691aec9837465131e">MF</a>, <a href="#a6bd44a21a5a54d02b58db73756788c04">MFI</a> and <a href="#a7d419678a35ca8a83f34a302d9c62e23">TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### composeWithSubRegIndex() {#a82ef22a357f6b3f17e77b598df0ca45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass &amp; HexagonEvaluator::composeWithSubRegIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC, unsigned Idx)</td>
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



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#acf8436e28b183b48eecf6b8564536c7aa7e62627fded515ebb9ff5d0ec9571d95">llvm::Hexagon::ps_sub_hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#acf8436e28b183b48eecf6b8564536c7aa4c96233dec1eedf779c37f230f6d8c10">llvm::Hexagon::ps_sub_lo</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a440983b5e0f6fc9cd9771b51f1f998dd">llvm::BitTracker::MachineEvaluator::TRI</a>.</p>

</div>
</div>

### evaluate() {#a49b4d08c8b0024b97c7e090a0b3e50f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8f60ca7a06508167e5bc0f00c1c75cd">CellMapType</a> &amp; Inputs, <a href="#ab8f60ca7a06508167e5bc0f00c1c75cd">CellMapType</a> &amp; Outputs)</td>
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



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a1385460950e6fe590c5913ba8c9dbe90">llvm::BitTracker::RegisterCell::cat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#adbf082422e6f7a82cea21dfa3273811d">llvm::BitTracker::MachineEvaluator::eADD</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ab4b48cf5ad86cd432b03b6f5b254f227">llvm::BitTracker::MachineEvaluator::eAND</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a86f3525b5df439dd04caea2c1d4f567d">llvm::BitTracker::MachineEvaluator::eASL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a83c32395e0a0c8e1d12e4dbdc5483928">llvm::BitTracker::MachineEvaluator::eASR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6a2e09403daa9d3a9d40a68895e90aa9">llvm::BitTracker::MachineEvaluator::eCLB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8fa571f010447594afbfb0dd92cdb917">llvm::BitTracker::MachineEvaluator::eCTB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4ba2ddc1335f8aec90d6af171f4d5a3e">llvm::BitTracker::MachineEvaluator::eIMM</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aceb7efc236b586c36f36b047db000db9">llvm::BitTracker::MachineEvaluator::eINS</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4d418e3defa1322e8e55b020eef30475">llvm::BitTracker::MachineEvaluator::eLSR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6032f746ffa25df648aa38680d1e891e">llvm::BitTracker::MachineEvaluator::eMLS</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a518631233431d2324f15075cf91ffab2">llvm::BitTracker::MachineEvaluator::eMLU</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a4aa1e4c6871a0b6056bba979f7c546bb">llvm::BitTracker::MachineEvaluator::eNOT</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#abe57eebc5c101a825f3c31712fdd617b">llvm::BitTracker::MachineEvaluator::eORL</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#add47c55cf111a92da1ded367147668eb">llvm::BitTracker::MachineEvaluator::eSUB</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#ac2da26c1aaa137602b14f3b3da367f61">llvm::BitTracker::MachineEvaluator::eSXT</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a2c519d1784e4a4beee0fd668ed8d3900">llvm::BitTracker::MachineEvaluator::eXOR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#aefa1e921dff52ae9ac378bf26a32b4d2">llvm::BitTracker::MachineEvaluator::eXTR</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a57424565b80f4f8fef7b5a8e11735f34">llvm::BitTracker::MachineEvaluator::eZXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a64ee9ca87205e764e0382240030f87ee">llvm::BitTracker::MachineEvaluator::getRegBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a2239343bf72ef6a991165363ac0386c3">im</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ab436b1402523817d32ee31d1d7eb7a0c">llvm::BitTracker::RegisterCell::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#abdda211d574b7a9074aa1cdb1b0b204b">llvm::BitTracker::BitValue::is</a>, <a href="#a6bd44a21a5a54d02b58db73756788c04">MFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6d5cfd7739a2939cd9418586c8aa1a3c">llvm::BitTracker::MachineEvaluator::MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8944fc547212f985ad3f9706eb5b8725">llvm::BitTracker::MachineEvaluator::putCell</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a2e1b5bd9424a1d1082d4bd670b1a0be6">rc</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4b372ece8559169470a7fcfb471c2302">llvm::BitTracker::RegisterCell::self</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a457abdc792a2b697c1031f09edb8492f">llvm::shuffle</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>

</div>
</div>

### evaluate() {#a6e8a4f85c8a56769ce682ff88d5b60f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; BI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8f60ca7a06508167e5bc0f00c1c75cd">CellMapType</a> &amp; Inputs, <a href="#a495e6e7b2e94dda7aaea1eaeacc25570">BranchTargetList</a> &amp; Targets, bool &amp; FallsThru)</td>
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



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a9a70d4969d8d43a9c9b324f692bc8ecd">llvm::BitTracker::MachineEvaluator::getCell</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aec7c967a5416fa6e154433965357a50ea0cbc6611f5540bd0809a388dc95a615b">llvm::Test</a>.</p>

</div>
</div>

### getPhysRegBitWidth() {#a34cd40aa7d878b134c54cf218b4fb5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t HexagonEvaluator::getPhysRegBitWidth (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a7ebd1745b8aea9e691aec9837465131e">MF</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a440983b5e0f6fc9cd9771b51f1f998dd">llvm::BitTracker::MachineEvaluator::TRI</a>.</p>

</div>
</div>

### mask() {#a26c72fb657ffaea1a961279c6d3a80fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::BitMask HexagonEvaluator::mask (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned Sub)</td>
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



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a64ee9ca87205e764e0382240030f87ee">llvm::BitTracker::MachineEvaluator::getRegBitWidth</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a6d5cfd7739a2939cd9418586c8aa1a3c">llvm::BitTracker::MachineEvaluator::MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#acf8436e28b183b48eecf6b8564536c7aa4c96233dec1eedf779c37f230f6d8c10">llvm::Hexagon::ps_sub_lo</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a440983b5e0f6fc9cd9771b51f1f998dd">llvm::BitTracker::MachineEvaluator::TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateFormalCopy() {#adadfda429dbbfa7d188d6039eb702959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonEvaluator::evaluateFormalCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8f60ca7a06508167e5bc0f00c1c75cd">CellMapType</a> &amp; Inputs, <a href="#ab8f60ca7a06508167e5bc0f00c1c75cd">CellMapType</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 1216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>

</div>
</div>

### evaluateLoad() {#a77ba811c5df757eae792c111b8b825fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonEvaluator::evaluateLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ab8f60ca7a06508167e5bc0f00c1c75cd">CellMapType</a> &amp; Inputs, <a href="#ab8f60ca7a06508167e5bc0f00c1c75cd">CellMapType</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>

</div>
</div>

### getNextPhysReg() {#a633bbd0e138eb33135d905190a539e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HexagonEvaluator::getNextPhysReg (unsigned PReg, unsigned Width)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 1250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>

</div>
</div>

### getUniqueDefVReg() {#ab05093380bce7d4370d6af9523ac10e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HexagonEvaluator::getUniqueDefVReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 1043 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>

</div>
</div>

### getVirtRegFor() {#ae01b1854161bf46327d74e3430e56b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HexagonEvaluator::getVirtRegFor (unsigned PReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>, definition at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MF {#a7ebd1745b8aea9e691aec9837465131e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::HexagonEvaluator::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>


<p>Referenced by <a href="#a34cd40aa7d878b134c54cf218b4fb5a6">getPhysRegBitWidth</a> and <a href="#a5c2b22f49f8bb9c6c2d5c4ff5211d9e9">HexagonEvaluator</a>.</p>

</div>
</div>

### MFI {#a6bd44a21a5a54d02b58db73756788c04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFrameInfo&amp; llvm::HexagonEvaluator::MFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>


<p>Referenced by <a href="#a49b4d08c8b0024b97c7e090a0b3e50f6">evaluate</a> and <a href="#a5c2b22f49f8bb9c6c2d5c4ff5211d9e9">HexagonEvaluator</a>.</p>

</div>
</div>

### TII {#a7d419678a35ca8a83f34a302d9c62e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonInstrInfo&amp; llvm::HexagonEvaluator::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>


<p>Referenced by <a href="#a5c2b22f49f8bb9c6c2d5c4ff5211d9e9">HexagonEvaluator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### VRX {#a3d11e25c024cdb9ff43d3dfb5d70439b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegExtMap llvm::HexagonEvaluator::VRX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
