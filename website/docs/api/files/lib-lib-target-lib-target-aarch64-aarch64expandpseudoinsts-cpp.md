---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AArch64ExpandPseudoInsts.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-h">AArch64ExpandImm.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-h">AArch64InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">MCTargetDesc/AArch64AddressingModes.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64baseinfo-h">Utils/AArch64BaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">llvm/CodeGen/LivePhysRegs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64expandpseudoinsts-cpp-">anonymous{AArch64ExpandPseudoInsts.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64expandpseudoinsts-cpp-/aarch64expandpseudo">AArch64ExpandPseudo</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774f76f62f3dec65d8333ecc39a64453">INITIALIZE_PASS</a> (AArch64ExpandPseudo, "aarch64-expand-pseudo", AARCH64_EXPAND_PSEUDO_NAME, false, false) static void transferImpOps(MachineInstr &amp;OldMI</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer implicit operands on the pseudo instruction to the instructions created from the expansion. <a href="#a774f76f62f3dec65d8333ecc39a64453">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfc8b177e8521a4b496ae2edff6244f">for</a> (const MachineOperand &amp;MO :llvm::drop_begin(OldMI.operands(), Desc.getNumOperands()))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe83de329645327b1d40bee0d304aff8">createCallWithOps</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const AArch64InstrInfo *TII, unsigned Opcode, ArrayRef&lt; MachineOperand &gt; ExplicitOps, unsigned RegMaskStartIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ac915411e77e361580ea305fb31325">createCall</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, const AArch64InstrInfo *TII, MachineOperand &amp;CallTarget, unsigned RegMaskStartIdx)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ece0ac2421637044624c9b01c42466">DefMI</a> = ...</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0180122814bf3f43132da7005578822e">AARCH64_EXPAND_PSEUDO_NAME</a>&nbsp;&nbsp;&nbsp;"AArch64 <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> instruction expansion pass"</td>
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


<div class="doxySectionDef">

## Functions

### createCall() {#ad3ac915411e77e361580ea305fb31325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * createCall (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo">AArch64InstrInfo</a> * TII, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; CallTarget, unsigned RegMaskStartIdx)</td>
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



<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp">AArch64ExpandPseudoInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abe83de329645327b1d40bee0d304aff8">createCallWithOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### createCallWithOps() {#abe83de329645327b1d40bee0d304aff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * createCallWithOps (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo">AArch64InstrInfo</a> * TII, unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; ExplicitOps, unsigned RegMaskStartIdx)</td>
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



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp">AArch64ExpandPseudoInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af066b2b6a1013299bfca84fe8b798a0b">llvm::MachineInstrBuilder::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#ad3ac915411e77e361580ea305fb31325">createCall</a>.</p>

</div>
</div>

### for() {#a4cfc8b177e8521a4b496ae2edff6244f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">for (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;MO  :llvm::drop_begin=OldMI.operands(), Desc.getNumOperands())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp">AArch64ExpandPseudoInsts.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout/#af3fa75b45aafa6c528042df53446d8e1">llvm::jitlink::BasicLayout::BasicLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a8d3e918d874e8e80cf9a403e8ea59e32">canBeFeederToNewValueJump</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a435084f5e140c85f72921239385f9edb">canRenameUntilSecondLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#ab299749106299a5f9b4420486988f11a">anonymous{CoroElide.cpp}::CoroIdElider::CoroIdElider</a>, <a href="/web-llvm/docs/api/classes/anonymous-coveragemappingwriter-cpp-/counterexpressionsminimizer/#ad4aaec8d4c374c7ebb4b4091b764485f">anonymous{CoverageMappingWriter.cpp}::CounterExpressionsMinimizer::CounterExpressionsMinimizer</a>, <a href="/web-llvm/docs/api/classes/anonymous-acceltable-cpp-/dwarf5acceltablewriter/#ac9fcce12a4cf8ec49ed9cb6aaf1abb62">anonymous{AccelTable.cpp}::Dwarf5AccelTableWriter::Dwarf5AccelTableWriter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ae25b1e577bcd72ebc8b84b83aca02662">for</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate/#a0a8bbbf9ec7c7e88b08172862188e530">anonymous{LoopFuse.cpp}::FusionCandidate::FusionCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker/#a9910e63c423b9ed6890d2b551142ef92">anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::GCPtrTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/genericopttable/#ac3179665bf593185b092d08113399ae8">llvm::opt::GenericOptTable::GenericOptTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/guidtofuncnamemapper/#a0443cc3fdee8b10994d348458d6d9949">anonymous{SampleProfile.cpp}::GUIDToFuncNameMapper::GUIDToFuncNameMapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsplitconst32andconst64-cpp/#a79661f41f9eef555922452344ae54280">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxproxyregerasure-cpp/#a9d0f767158270855806d4e9899311db5">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#aed0d70e55a261450cb76cb7f615977dc">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callframeoptimization-cpp/#a91d092e016c6260bf8a84260975ae781">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#acd2031b426c61bce2c9afd0f1463d109">llvm::IntrinsicCostAttributes::IntrinsicCostAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aca012302770ad32503de5e2c62344290">isProfitableChain</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsrinstance/#a9bcf42be7435217d79cd175d4e6993d7">anonymous{LoopStrengthReduce.cpp}::LSRInstance::LSRInstance</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a11dfc334374b4579c63c4269e3e1d34b">llvm::rdf::PhysicalRegisterInfo::PhysicalRegisterInfo</a>, <a href="/web-llvm/docs/api/structs/prefixmatcher/#ac9d4f7a82f0d45796979a17a39fe7cfc">PrefixMatcher::PrefixMatcher</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#a547e6acb76d014207c771774f809696a">reconnectChildLoops</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64postcoalescerpass-cpp-/aarch64postcoalescer/#af7c68f72faddb47f4a574fbd77f55806">anonymous{AArch64PostCoalescerPass.cpp}::AArch64PostCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats/#a8305613a915321631b70e8f26e2d55d6">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacementStats::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner/#a292abfa5a62a1fd7b53592085a48e651">llvm::MachinePipeliner::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#a207cce78de7e84e6885684960f5c4f50">RemoveLoadsIntoFakeUses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowertypetests-cpp-/scopedsavealiaseesandused/#aa02d191d0f55ac0d1a4921d778d0fe63">anonymous{LowerTypeTests.cpp}::ScopedSaveAliaseesAndUsed::ScopedSaveAliaseesAndUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkandhoistlicmflags/#a30d4121b007bf8064374e069fd2de689">llvm::SinkAndHoistLICMFlags::SinkAndHoistLICMFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduleblockscheduler/#a3f8aa4817345abf1b92fbb1b32c6de80">llvm::SIScheduleBlockScheduler::SIScheduleBlockScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a52cd535b24f497c8e260a5dee1ff01dc">llvm::StringMap&lt; std::nullopt_t, AllocatorTy &gt;::StringMap</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a2ca404ac00efb240e891d7f7d86aec02">llvm::TimerGroup::TimerGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a943584f0c65b24cfb9cbbca6d86fa75a">llvm::ValueEnumerator::ValueEnumerator</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblydebugvaluemanager/#a2babcc960233b1e1c8c61a91283b955a">llvm::WebAssemblyDebugValueManager::WebAssemblyDebugValueManager</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a774f76f62f3dec65d8333ecc39a64453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (AArch64ExpandPseudo, "aarch64-<a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a>-pseudo", <a href="#a0180122814bf3f43132da7005578822e">AARCH64_EXPAND_PSEUDO_NAME</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer implicit operands on the pseudo instruction to the instructions created from the expansion.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp">AArch64ExpandPseudoInsts.cpp</a>.</p>


<p>Reference <a href="#a0180122814bf3f43132da7005578822e">AARCH64_EXPAND_PSEUDO_NAME</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DefMI {#ad3ece0ac2421637044624c9b01c42466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MachineInstrBuilder&amp; DefMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#a4de98a9acffcef5bb4b31862cb8c72ac">Desc</a> = OldMI.getDesc()
</div>
</dd>
</dl>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp">AArch64ExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a9027a59d16b066e9f8549b9a9c50b60b">llvm::AArch64Subtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizehelper/#af375ca05eecaafa17b7a92ec352537d4">llvm::AMDGPU::RegBankLegalizeHelper::applyMappingPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aef21a685c4183683271cbaa741991f12">canFoldIntoCSel</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#aeaf1429d245f871e41187accdce34e06">llvm::LiveRangeEdit::checkRematerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#abe764852febe90b22412f1acf299fb9e">llvm::TargetSchedModel::computeOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a5a00ff1e3eb19fe4001d742d93f8fade">llvm::TargetSchedModel::computeOutputLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#aaea2f970a2bbb337f3098d43c1fdfb8c">llvm::GCNSchedStage::computeSUnitReadyCycle</a>, <a href="/web-llvm/docs/api/classes/regbankselecthelper/#ae56b2250d41c0820f12319e553d76084">RegBankSelectHelper::constrainRegBankUse</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ab8b249a6f01a1f333bc2bfbc6463251c">llvm::PPCInstrInfo::convertToImmediateForm</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5424d7c9e608bd5b2087f1021908a08">llvm::TargetInstrInfo::defaultDefLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad99c8ee849f72738dd718fec8d3a1d42">llvm::CombinerHelper::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd734184546746d0ab64985a91368a14">llvm::execMayBeModifiedBeforeAnyUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a20c762703f9faa4263464684aae1ad">llvm::execMayBeModifiedBeforeUse</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a5bce8dbd0e078a0ea0821917ab1f4873">llvm::MachineFunction::finalizeDebugInstrRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/initundef-cpp/#aaa5adc9fa31e5b621e14ae1b2560534e">findImplictDefMIFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a6998a9da8b2724f73f31a95ae76c8ce3">llvm::PPCInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#acced35ebfd644d56dc0bcc060bb1bd8d">llvm::SystemZInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa41c45a69f227ee71e5ced4e6e3fde18">llvm::TargetInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a016eece9dce70ed04e3636537f22a697">llvm::VEInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aee61c5ff08966f039eec33e3c213bff5">llvm::X86InstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a727184c28151d2b605686087351b8d7b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldInstOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedca54ee65b84a32a3bf0c9a595e2fd9">llvm::PPCInstrInfo::getConstantFromConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96b61989528fd1061ce48169e066cd14">llvm::getConstFromIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#accc8c4eb3eb2c7b4ceff04fc9a63c9da">llvm::getDefSrcRegIgnoringCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a23c3c91648996442b88f0c53cf1415d8">getFoldableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7326d1a0ae53d6dece409404840c5e6f">getFoldableImm</a>, <a href="/web-llvm/docs/api/classes/llvm/armhazardrecognizerfpmlx/#af1064d4637b93e114f1d15631abdc03f">llvm::ARMHazardRecognizerFPMLx::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo/#a9a34245bb11e89a64a45063a8fc9e201">llvm::RISCVRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#ab84d39303f3dab27a9cf03cd488b23c6">llvm::X86RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a629d41f7f65cdba7304662a7c7132345">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4cbbdd3795a958b1e24bd85cf48a0519">llvm::HexagonInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a836e5efd0e3634abca5e8a1c02ef6232">llvm::PPCInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a9b1e693dee703f46fd28221e99d4acff">llvm::TargetInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a4993bfe73a55f4fcc5d02d09c410ddaf">llvm::TargetInstrInfo::hasHighOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ae6d780628c548ae14b087f4cc6b816be">llvm::X86InstrInfo::hasHighOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abb81aa2a9fed25ed7a1762421866fcc3">llvm::PPCInstrInfo::hasLowDefLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0aa73253579dd1c4acde85953454e838">llvm::TargetInstrInfo::hasLowDefLatency</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a9b9c5d8f1e5e26cc1a93b263a223cbe5">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::hasNonZeroAVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-cpp/#af4b92b87cdc1663f71632274fefb42c3">hasRAWHazard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp/#aeab9aaa0283d5249c25d93393677af94">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-combinerhelper-cpp-/#abe36a8462243713bdada68a3fc16ee47">anonymous{CombinerHelper.cpp}::InsertInsnsWithoutSideEffectsBeforeUse</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#a5c87181311e69141665082e3fc53d801">llvm::MachineTraceMetrics::Trace::isDepInTrace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff9fc12d1e70e76349dfad9462ee5c21">llvm::isKnownNeverNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb26c86c4abcccbe5376b3f7e5e8af69">llvm::isNZCVTouchedInInstructionRange</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3a9969db0d864227c6955d383a7bbe45">llvm::CombinerHelper::isPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5fd133d3cc0d8e1b33fe7ae34657d45c">llvm::CombinerHelper::matchExtendThroughPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a16eb84143cfa149db94e8b4b4b2a8629">llvm::PPCInstrInfo::onlyFoldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a6213ea1bf5dbbaaf18c24ef42a95a019">llvm::SystemZInstrInfo::optimizeLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a01961400ab1186ac9f849cf0e738447f">llvm::TargetInstrInfo::optimizeLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#afbc1088fd64459bec1157940aa59eb69">llvm::X86InstrInfo::optimizeLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#aadcf47d2bfa2abd153d66b001715198c">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::processPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a9e0695dc8fb597f66ca702309da941f7">llvm::LiveVariables::recomputeForSingleDefVirtReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#afb605ebf6dc090e58e5d3dd1a9125d33">regIsPICBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a18f4a66d99dba4cf2a2c1054d796cf9c">removeCopies</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-phielimination-cpp-/phieliminationimpl/#aab3db5c9e390ca00331b7d432c735dcd">anonymous{PHIElimination.cpp}::PHIEliminationImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64condbrtuning-cpp-/aarch64condbrtuning/#a3f2d376e9233d0fcb1dc2c5543fb3065">anonymous{AArch64CondBrTuning.cpp}::AArch64CondBrTuning::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvvloptimizer-cpp-/riscvvloptimizer/#aef0982e6aa98fe02059f7f1a24d0de65">anonymous{RISCVVLOptimizer.cpp}::RISCVVLOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a176bfede6f24b05b428c0f42f9d95390">scavengeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a068e9d1fd54621ae340f26c41d170a1a">llvm::X86FrameLowering::spillFPBP</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a9a7aa541dbcfdac34b25b49217ec39d7">llvm::MachineTraceMetrics::Ensemble::Trace</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3140a2195ea3bf00ed638bd5a2a13b35">llvm::LegalizationArtifactCombiner::tryFoldImplicitDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a7c842ead18aca7681bd1cd596a3c8ba3">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::tryMoveVGPRConstToSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#ac47046162deb21d43512581afc16fa7c">updatePHIs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a344a4fa1e7c1a3a6f6ede4213058ad12">valueIsKnownNeverF32Denorm</a>.</p>

</div>
</div>

### UseMI {#a6cf2f8996b1e9aaf2d7a435aaa62382f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder&amp; UseMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp">AArch64ExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl/#afe3f48a41bbbfc79a0c7160865d61ea9">llvm::Combiner::WorkListMaintainerImpl&lt; Lvl &gt;::addUsersToWorkList</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a9027a59d16b066e9f8549b9a9c50b60b">llvm::AArch64Subtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/combiner/worklistmaintainerimpl/#a2a0be1f113eb61c3bbfc1ea4ef8e9832">llvm::Combiner::WorkListMaintainerImpl&lt; Lvl &gt;::appliedCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a00301689820a26a9f3b438f6dece6ef0">llvm::CombinerHelper::applyCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#a99fb6c2c4ea3a52f8977eeb8d2c2f425">anonymous{SPIRVPreLegalizerCombiner.cpp}::applySPIRVDistance</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a5290bdffbf68a26e47345d1bb2abb246">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectCandidateRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#abe764852febe90b22412f1acf299fb9e">llvm::TargetSchedModel::computeOperandLatency</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#ae5e50a6a8cb928fb34cd4fde19384381">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::createCRLogicalOpInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad99c8ee849f72738dd718fec8d3a1d42">llvm::CombinerHelper::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a20c762703f9faa4263464684aae1ad">llvm::execMayBeModifiedBeforeUse</a>, <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpander/#a772c336d26015c2e6fb5efc62cf166be">llvm::ModuloScheduleExpander::expand</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ad8d9864fc2d6dd085102d0999ce27aa1">llvm::PeelingModuloScheduleExpander::filterInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a7636a283116b131c3d7722fbb31bf9db">findAssignTypeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ab88eabb9aada899a03069797171cd2d5">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::findNonPHIUsesInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a6998a9da8b2724f73f31a95ae76c8ce3">llvm::PPCInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#acced35ebfd644d56dc0bcc060bb1bd8d">llvm::SystemZInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa41c45a69f227ee71e5ced4e6e3fde18">llvm::TargetInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a016eece9dce70ed04e3636537f22a697">llvm::VEInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aee61c5ff08966f039eec33e3c213bff5">llvm::X86InstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a727184c28151d2b605686087351b8d7b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldInstOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a66eb61143b269793cb50e67646375778">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::frameIndexMayFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a59b9890650c2857c6688596e74fefef1">getDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo/#a9a34245bb11e89a64a45063a8fc9e201">llvm::RISCVRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#ab84d39303f3dab27a9cf03cd488b23c6">llvm::X86RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4cbbdd3795a958b1e24bd85cf48a0519">llvm::HexagonInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a836e5efd0e3634abca5e8a1c02ef6232">llvm::PPCInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a9b1e693dee703f46fd28221e99d4acff">llvm::TargetInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a165430a83d0399a48d8983764c9e60b3">getPHIDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a4993bfe73a55f4fcc5d02d09c410ddaf">llvm::TargetInstrInfo::hasHighOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ae6d780628c548ae14b087f4cc6b816be">llvm::X86InstrInfo::hasHighOperandLatency</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-combinerhelper-cpp-/#abe36a8462243713bdada68a3fc16ee47">anonymous{CombinerHelper.cpp}::InsertInsnsWithoutSideEffectsBeforeUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#acfdb7e9be44e0d08b3b97b9177b8239e">isCopyFeedingInvariantStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#af85a5fe23faddaea6601422ca2854b05">isDefLiveOut</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#a5c87181311e69141665082e3fc53d801">llvm::MachineTraceMetrics::Trace::isDepInTrace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb26c86c4abcccbe5376b3f7e5e8af69">llvm::isNZCVTouchedInInstructionRange</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3a9969db0d864227c6955d383a7bbe45">llvm::CombinerHelper::isPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a213df9204c030effa8d56a05564997a7">llvm::MachineRegisterInfo::markUsesInDebugValueAsUndef</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a6a0e1a9e7ae975ebc159132831f812e5">anonymous{AArch64PostLegalizerCombiner.cpp}::matchAArch64MulConstCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a2ea6814df78ae99e8a540fb4e8fc4ed1">llvm::CombinerHelper::matchCombineDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab5ece2e19fefdc8f1112b05d6274e649">llvm::CombinerHelper::matchCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3acff99aeccfa086e7fbef44df8c0ce1">llvm::CombinerHelper::matchPtrAddImmedChain</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16registerinfo/#a1d5cf121906fd0c39ea512dc759e9392">llvm::Mips16RegisterInfo::Mips16RegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a16eb84143cfa149db94e8b4b4b2a8629">llvm::PPCInstrInfo::onlyFoldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a86f2353949000eecd69fbbe3c669efc4">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeLiveRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#aa35ddcfd60c7c4587ea25cb27e25968e">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeWaterfallLiveRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwasrcoperand/#a7f2319e3588e98e73879945fdc62b25b">anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::potentialToConvert</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#aadcf47d2bfa2abd153d66b001715198c">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::processPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a0440a06c400cd0c68710d37b74cb8c67">pushDepHeight</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac5b6ac3924041b35531d4e9bf66c3df4">llvm::SIInstrInfo::readlaneVGPRToSGPR</a>, <a href="/web-llvm/docs/api/classes/regbankselecthelper/#a9c19f0d81ecc0282828c546f12bc5b36">RegBankSelectHelper::reAssignRegBankOnDef</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a9e0695dc8fb597f66ca702309da941f7">llvm::LiveVariables::recomputeForSingleDefVirtReg</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a99f0584edf9a13120df821e7f77d9731">llvm::LegalizationArtifactCombiner::replaceRegOrBuildCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a71a08885f7838dc5a544816a357e2ec7">llvm::MachineSSAUpdater::RewriteUse</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#a62ce7ffa7758a2203d98c3f40caa5f89">llvm::PeelingModuloScheduleExpander::rewriteUsesOf</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16registerinfo/#a91cb07cc7a2519edf81f75395810f547">llvm::Mips16RegisterInfo::saveScavengerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a9b83fea6470c12edb28e6b263d9a35c2">llvm::TargetRegisterInfo::saveScavengerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a62d08c8303092539ecb1fde389108e7a">llvm::RegScavenger::scavengeRegisterBackwards</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a7c8714527422f164b52d6daaa65850e8">tryChangeVGPRtoSGPRinCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a553d8629e18f8acb82dbadd0a160b877">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldRegSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acd13e2195957a8e92e36d055dde1ffb8">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryToFoldACImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a804ccee98d777a9a0e3b342bd850688d">llvm::MachineTraceMetrics::Ensemble::updateDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a3118fc82938c92f70453a0ccf9e7fc70">llvm::MachineTraceMetrics::Ensemble::updateDepth</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a05ac0dbbd44f86b9fe34282e8109c1ee">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::updateLiveRangeInThenRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6eb3ac91456a9880aecf25dc8e3cbaa5">updatePhysDepsDownwards</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a87e58e9d24983c7890c502fbe731f950">verifyCFIntrinsic</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AARCH64\_EXPAND\_PSEUDO\_NAME {#a0180122814bf3f43132da7005578822e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AARCH64_EXPAND_PSEUDO_NAME&nbsp;&nbsp;&nbsp;"AArch64 <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> instruction expansion pass"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp">AArch64ExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64expandpseudoinsts-cpp-/aarch64expandpseudo/#ae5fef1006467524a2a3e80a073099d94">anonymous{AArch64ExpandPseudoInsts.cpp}::AArch64ExpandPseudo::getPassName</a> and <a href="#a774f76f62f3dec65d8333ecc39a64453">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
