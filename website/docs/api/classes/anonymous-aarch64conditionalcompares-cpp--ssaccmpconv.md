---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SSACCmpConv` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae545377195b4613619abe889fb53b92c">runOnMachineFunction</a> (MachineFunction &amp;MF, const MachineBranchProbabilityInfo *MBPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - Initialize per-function data structures. <a href="#ae545377195b4613619abe889fb53b92c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545b0c16154dffb0ddba86968d798e2f">canConvert</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the sub-CFG headed by MBB can be cmp-converted, initialize the internal state, and return true. <a href="#a545b0c16154dffb0ddba86968d798e2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c2c7a46bf3359100068e45134218920">convert</a> (SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;RemovedBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cmo-convert the last block passed to canConvertCmp(), assuming it is possible. <a href="#a8c2c7a46bf3359100068e45134218920">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa016d989e7b958f8f9223589db614807">expectedCodeSizeDelta</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the expected code size delta if the conversion into a conditional compare is performed. <a href="#aa016d989e7b958f8f9223589db614807">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5b677de8a8d22c6eecbc1b5fcd15743">trivialTailPHIs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the Tail PHIs are trivially convertible. <a href="#aa5b677de8a8d22c6eecbc1b5fcd15743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4839b3cc6b505aa639d0da2e7813f1f9">updateTailPHIs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove CmpBB from the Tail PHIs. <a href="#a4839b3cc6b505aa639d0da2e7813f1f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bfd9624657da83223650f9dc4ebb04e">isDeadDef</a> (unsigned DstReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if an operand defining DstReg is dead. <a href="#a3bfd9624657da83223650f9dc4ebb04e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935725a9425f5353cff1ba9a258dbd38">findConvertibleCompare</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the compare instruction in MBB that controls the conditional branch. <a href="#a935725a9425f5353cff1ba9a258dbd38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a47107452dc6c8a037729ee1e95e02">canSpeculateInstrs</a> (MachineBasicBlock *MBB, const MachineInstr *CmpMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all non-terminator instructions in MBB can be safely speculated. <a href="#ab2a47107452dc6c8a037729ee1e95e02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd72a8ce84f1d0337ebfe7f03beccac0">Head</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The first block containing a conditional branch, dominating everything else. <a href="#abd72a8ce84f1d0337ebfe7f03beccac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49e72cb5fa7f420d3ddc70238afb589">CmpBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The block containing cmp+br.cond with a successor shared with Head. <a href="#af49e72cb5fa7f420d3ddc70238afb589">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1de41412b7998919eb603347b5091ca">Tail</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The common successor for Head and CmpBB. <a href="#ac1de41412b7998919eb603347b5091ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504801b55be6d80f05f6159184b8e4af">CmpMI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The compare instruction in CmpBB that can be converted to a ccmp. <a href="#a504801b55be6d80f05f6159184b8e4af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7844eba329f544cc3800777781548477">MF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ee01d18dc58c8c1b7a64c8c7ade837">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a990a81e8bbb16bee32b89d44ee650d62">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45f22acda856418a9026f04c9c234df">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd46bb1a9a74834ff8cae8c3e7b4d26">MBPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4111fa484121ed8c5d258e2c9b680d8b">HeadCond</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The branch condition in Head as determined by analyzeBranch. <a href="#a4111fa484121ed8c5d258e2c9b680d8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c99ba09a373b59d72b9cd5a261a6ae">HeadCmpBBCC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The condition code that makes Head branch to CmpBB. <a href="#af0c99ba09a373b59d72b9cd5a261a6ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed9d57525af5902ba7bbd20db931b54e">CmpBBCond</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The branch condition in CmpBB. <a href="#aed9d57525af5902ba7bbd20db931b54e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28">AArch64CC::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0988b108adaec18ca0d8d0cdd9f89168">CmpBBTailCC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The condition code that makes CmpBB branch to Tail. <a href="#a0988b108adaec18ca0d8d0cdd9f89168">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### canConvert() {#a545b0c16154dffb0ddba86968d798e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSACCmpConv::canConvert (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the sub-CFG headed by MBB can be cmp-converted, initialize the internal state, and return true.</p>


<p>Analyze the sub-cfg rooted in MBB, and return true if it is a potential candidate for cmp-conversion.</p>


<p>Fill out the internal state.</p>


<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af49e72cb5fa7f420d3ddc70238afb589">CmpBB</a>, <a href="#a504801b55be6d80f05f6159184b8e4af">CmpMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#af2ca6ef2f5cc21570610580d628314c5">llvm::AArch64CC::getCondCodeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#afc2ebeb83373be407903e43096e4f7b9">llvm::AArch64CC::getInvertedCondCode</a>, <a href="#abd72a8ce84f1d0337ebfe7f03beccac0">Head</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp/#a9ffc0d089afbddfa36b41b4d1c345d47">parseCond</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#ac1de41412b7998919eb603347b5091ca">Tail</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### convert() {#a8c2c7a46bf3359100068e45134218920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSACCmpConv::convert (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; RemovedBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cmo-convert the last block passed to canConvertCmp(), assuming it is possible.</p>


<p>Add any erased blocks to RemovedBlocks.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#af49e72cb5fa7f420d3ddc70238afb589">CmpBB</a>, <a href="#a504801b55be6d80f05f6159184b8e4af">CmpMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013">llvm::RegState::Dead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a756347c46f7abfa1e1fefcc39502c680">llvm::AArch64CC::EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#affed553a12fdb2f42041ea371820e01f">llvm::AArch64CC::getNZCVToSatisfyCondCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="#abd72a8ce84f1d0337ebfe7f03beccac0">Head</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#abfa1f7dce576430da99eed57807c7f28a191e89dbc4939ebd0b572cae44aac05f">llvm::AArch64CC::NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#ac1de41412b7998919eb603347b5091ca">Tail</a>.</p>

</div>
</div>

### expectedCodeSizeDelta() {#aa016d989e7b958f8f9223589db614807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SSACCmpConv::expectedCodeSizeDelta ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the expected code size delta if the conversion into a conditional compare is performed.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>References <a href="#a504801b55be6d80f05f6159184b8e4af">CmpMI</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### runOnMachineFunction() {#ae545377195b4613619abe889fb53b92c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> * MBPI)</td>
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

<p>runOnMachineFunction - Initialize per-function data structures.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canSpeculateInstrs() {#ab2a47107452dc6c8a037729ee1e95e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSACCmpConv::canSpeculateInstrs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CmpMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all non-terminator instructions in MBB can be safely speculated.</p>


<p>Determine if all the instructions in MBB can safely be speculated.</p>


<p>The terminators are not considered.</p>


<p>Only CmpMI is allowed to clobber the flags.</p>


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### findConvertibleCompare() {#a935725a9425f5353cff1ba9a258dbd38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SSACCmpConv::findConvertibleCompare (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the compare instruction in MBB that controls the conditional branch.</p>


<p>Return NULL if a convertible instruction can't be found.</p>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### isDeadDef() {#a3bfd9624657da83223650f9dc4ebb04e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSACCmpConv::isDeadDef (unsigned DstReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if an operand defining DstReg is dead.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### trivialTailPHIs() {#aa5b677de8a8d22c6eecbc1b5fcd15743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSACCmpConv::trivialTailPHIs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the Tail PHIs are trivially convertible.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### updateTailPHIs() {#a4839b3cc6b505aa639d0da2e7813f1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSACCmpConv::updateTailPHIs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove CmpBB from the Tail PHIs.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CmpBB {#af49e72cb5fa7f420d3ddc70238afb589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::CmpBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The block containing cmp+br.cond with a successor shared with Head.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>Referenced by <a href="#a545b0c16154dffb0ddba86968d798e2f">canConvert</a> and <a href="#a8c2c7a46bf3359100068e45134218920">convert</a>.</p>

</div>
</div>

### CmpMI {#a504801b55be6d80f05f6159184b8e4af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::CmpMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The compare instruction in CmpBB that can be converted to a ccmp.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>Referenced by <a href="#a545b0c16154dffb0ddba86968d798e2f">canConvert</a>, <a href="#a8c2c7a46bf3359100068e45134218920">convert</a> and <a href="#aa016d989e7b958f8f9223589db614807">expectedCodeSizeDelta</a>.</p>

</div>
</div>

### Head {#abd72a8ce84f1d0337ebfe7f03beccac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::Head</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The first block containing a conditional branch, dominating everything else.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>Referenced by <a href="#a545b0c16154dffb0ddba86968d798e2f">canConvert</a> and <a href="#a8c2c7a46bf3359100068e45134218920">convert</a>.</p>

</div>
</div>

### Tail {#ac1de41412b7998919eb603347b5091ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::Tail</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The common successor for Head and CmpBB.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>Referenced by <a href="#a545b0c16154dffb0ddba86968d798e2f">canConvert</a> and <a href="#a8c2c7a46bf3359100068e45134218920">convert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CmpBBCond {#aed9d57525af5902ba7bbd20db931b54e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineOperand, 4&gt; anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::CmpBBCond</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The branch condition in CmpBB.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### CmpBBTailCC {#a0988b108adaec18ca0d8d0cdd9f89168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64CC::CondCode anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::CmpBBTailCC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The condition code that makes CmpBB branch to Tail.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### HeadCmpBBCC {#af0c99ba09a373b59d72b9cd5a261a6ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64CC::CondCode anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::HeadCmpBBCC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The condition code that makes Head branch to CmpBB.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### HeadCond {#a4111fa484121ed8c5d258e2c9b680d8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineOperand, 4&gt; anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::HeadCond</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The branch condition in Head as determined by analyzeBranch.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### MBPI {#a3fd46bb1a9a74834ff8cae8c3e7b4d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::MBPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### MF {#a7844eba329f544cc3800777781548477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### MRI {#ab45f22acda856418a9026f04c9c234df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### TII {#a82ee01d18dc58c8c1b7a64c8c7ade837}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### TRI {#a990a81e8bbb16bee32b89d44ee650d62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
