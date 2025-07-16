---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVInstrInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-h">RISCVInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">MCTargetDesc/RISCVBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmatint-h">MCTargetDesc/RISCVMatInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscv-h">RISCV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmachinefunctioninfo-h">RISCVMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">llvm/Analysis/MemoryLocation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">llvm/CodeGen/LiveVariables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinecombinerpattern-h">llvm/CodeGen/MachineCombinerPattern.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinetracemetrics-h">llvm/CodeGen/MachineTraceMetrics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">llvm/CodeGen/RegisterScavenging.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">llvm/CodeGen/StackMaps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">llvm/MC/MCInstBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "RISCVGenCompressInstEmitter.inc"
#include "RISCVGenInstrInfo.inc"
#include "RISCVGenSearchableTables.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscvvpseudostable">RISCVVPseudosTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/riscv">RISCV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-riscvinstrinfo-cpp-">anonymous{RISCVInstrInfo.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvinstrinfo-cpp-/riscvpipelinerloopinfo">RISCVPipelinerLoopInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MachineOutlinerConstructionID { <a href="#a7c495f3a5e5dcd30c62df2edeccd86ea">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a331ddeeab0407b2178ebc605b4c168de">forwardCopyWillClobberTuple</a> (unsigned DstReg, unsigned SrcReg, unsigned NumRegs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acec254d4fbb18621ee4d54f867af85f9">isConvertibleToVMV_V_V</a> (const RISCVSubtarget &amp;STI, const MachineBasicBlock &amp;MBB, MachineBasicBlock::const_iterator MBBI, MachineBasicBlock::const_iterator &amp;DefMBBI, RISCVII::VLMUL LMul)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976">RISCVCC::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219be5e26dd017e77e6bae08d2753325">getCondFromBranchOpc</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a> (MachineInstr &amp;LastInst, MachineBasicBlock *&amp;Target, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452b99803927d8ed4cce6d76c385f8ec">getPredicatedOpcode</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adecd02add3a8a4d49bc27c4a6910605c">canFoldAsPredicatedOp</a> (Register Reg, const MachineRegisterInfo &amp;MRI, const TargetInstrInfo *TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify instructions that can be folded into a CCMOV instruction, and return the defining instruction. <a href="#adecd02add3a8a4d49bc27c4a6910605c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ee85d1d74b35fcebf4a24fcd802578">isFADD</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a666d2e57a2f9d581d596d2cd0f48894a">isFSUB</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2e0dca1cb64c1183b4263cd6621c48">isFMUL</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a> (const MachineInstr &amp;Root, const MachineOperand &amp;MO, bool DoRegPressureReduce)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed6416f30361f53101db3f22c2743dbb">getFPFusedMultiplyPatterns</a> (MachineInstr &amp;Root, SmallVectorImpl&lt; unsigned &gt; &amp;Patterns, bool DoRegPressureReduce)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e777196afeae01008075acf289bc924">getFPPatterns</a> (MachineInstr &amp;Root, SmallVectorImpl&lt; unsigned &gt; &amp;Patterns, bool DoRegPressureReduce)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d64a5fd52ca16e16ee50f916ab845a">canCombine</a> (const MachineBasicBlock &amp;MBB, const MachineOperand &amp;MO, unsigned CombineOpc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility routine that checks if. <a href="#a41d64a5fd52ca16e16ee50f916ab845a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab7185336f5a266b994341f14bc8faac">canCombineShiftIntoShXAdd</a> (const MachineBasicBlock &amp;MBB, const MachineOperand &amp;MO, unsigned OuterShiftAmt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility routine that checks if. <a href="#aab7185336f5a266b994341f14bc8faac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d54b78c6b15c6fcf873f09acc64a2d">getSHXADDShiftAmount</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7cbe832617857afaa39866967339d87">getSHXADDPatterns</a> (const MachineInstr &amp;Root, SmallVectorImpl&lt; unsigned &gt; &amp;Patterns)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227fe86424429965cabaed188260c3c8">getFPFusedMultiplyOpcode</a> (unsigned RootOpc, unsigned Pattern)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3731ff9b89570138608efcda73d72cdb">getAddendOperandIdx</a> (unsigned Pattern)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a> (MachineInstr &amp;Root, MachineInstr &amp;Prev, unsigned Pattern, SmallVectorImpl&lt; MachineInstr * &gt; &amp;InsInstrs, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DelInstrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a> (MachineInstr &amp;Root, unsigned AddOpIdx, SmallVectorImpl&lt; MachineInstr * &gt; &amp;InsInstrs, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DelInstrs, DenseMap&lt; unsigned, unsigned &gt; &amp;InstrIdxForVirtReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951bbdda542205db9de80f6bf44f571c">memOpsHaveSameBasePtr</a> (const MachineInstr &amp;MI1, ArrayRef&lt; const MachineOperand * &gt; BaseOps1, const MachineInstr &amp;MI2, ArrayRef&lt; const MachineOperand * &gt; BaseOps2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0896eaa4dfa916b067de719a48d0060">isCandidatePatchable</a> (const MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c063f61ab51976b76b1b7faa696d31">isMIReadsReg</a> (const MachineInstr &amp;MI, const TargetRegisterInfo *TRI, unsigned RegNo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc7c182e30e29f733866253f399e5839">isMIModifiesReg</a> (const MachineInstr &amp;MI, const TargetRegisterInfo *TRI, unsigned RegNo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05c04a32ecd794f1e86cfb753ed1f5c2">cannotInsertTailCall</a> (const MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2256b109946ab87fcd6aa4f82d610e28">analyzeCandidate</a> (outliner::Candidate &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1feb44daab9c30a1f6303e436adad8">isRVVWholeLoadStore</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44769ad9ee8a26cd247145fa02883792">PreferWholeRegisterMove</a>("riscv-prefer-whole-register-move", cl::init(false), cl::Hidden, cl::desc("Prefer whole register move for vector registers."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a08fc515218c080e73909645fecb41ed0">MachineTraceStrategy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af03fd419ccbdaf310f135c41bc14e0d2">ForceMachineCombinerStrategy</a>("riscv-force-machine-combiner-strategy", cl::Hidden, cl::desc("Force machine combiner to use a specific strategy for machine " "trace metrics evaluation."), cl::init(MachineTraceStrategy::TS_NumStrategies), cl::values(clEnumValN(MachineTraceStrategy::TS_Local, "local", "Local strategy."), clEnumValN(MachineTraceStrategy::TS_MinInstrCount, "min-instr", "MinInstrCount strategy.")))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb9d1dde65c47f060f939f4a9dd39609">GEN_CHECK_COMPRESS_INSTR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d99008fb7e5cdc4774786d0743a2c4f">GET_INSTRINFO_CTOR_DTOR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f11ade4c7901484baa40cab9d0d011">GET_INSTRINFO_NAMED_OPS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614407ca17f81d23604b51b027435618">GET_RISCVVPseudosTable_IMPL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1328aafab0ba8132134ae839043e1ed8">GET_RISCVMaskedPseudosTable_IMPL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f457938cfffac21cf486461098ad369">OPCODE_LMUL_CASE</a>(OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629db2495dfa61b86c613f56c562972b">OPCODE_LMUL_MASK_CASE</a>(OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278585ad9c23c5879636f58577ca7e7a">RVV_OPC_LMUL_CASE</a>(OPC, INV)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc35a104603ecf73a4433722be892952">RVV_OPC_LMUL_MASK_CASE</a>(OPC, INV)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd4a20c7548cf908d37bee756be9caa">CASE_OPERAND_UIMM</a>(NUM)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c5acfdaa401f68a4074a8013a727d35">CASE_OPERAND_SIMM</a>(NUM)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(OP, LMUL)&nbsp;&nbsp;&nbsp;  RISCV::Pseudo##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(OP, LMUL)&nbsp;&nbsp;&nbsp;  RISCV::Pseudo##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##_MASK</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3beca399cd888bf9592a5fd0fddc0bf">CASE_RVV_OPCODE_LMUL</a>(OP, LMUL)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1358a36845d3b21256f2f7e762b2820">CASE_RVV_OPCODE_UNMASK_WIDEN</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39994273d02b34906532e21f1fddafe8">CASE_RVV_OPCODE_UNMASK</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afefd18224ae60f4544513bd1e867f814">CASE_RVV_OPCODE_MASK_WIDEN</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af517025a8083176b552fd7804176f797">CASE_RVV_OPCODE_MASK</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ff02149bce7a64d19414caad225042">CASE_RVV_OPCODE_WIDEN</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746d9af508f41326e8e11b551c077f84">CASE_RVV_OPCODE</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89de0245330e0e334ffef52e284b6eca">CASE_VMA_OPCODE_COMMON</a>(OP, TYPE, LMUL)&nbsp;&nbsp;&nbsp;  RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##TYPE##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409c4a64458a4ae95962f464c2d0516e">CASE_VMA_OPCODE_LMULS_M1</a>(OP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd6607728af31885b1fbf34a6397ae99">CASE_VMA_OPCODE_LMULS_MF2</a>(OP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482032ef5d24b84b04eca82b256df3b4">CASE_VMA_OPCODE_LMULS_MF4</a>(OP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892e48a5567b90825543dce3f5f37e1a">CASE_VMA_OPCODE_LMULS</a>(OP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1599d31dc429d75f29eace3beeafed3">CASE_VFMA_OPCODE_COMMON</a>(OP, TYPE, LMUL, SEW)&nbsp;&nbsp;&nbsp;  RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##TYPE##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##SEW</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed8f9a40c3a2a7c45398506849859213">CASE_VFMA_OPCODE_LMULS_M1</a>(OP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6b599bda45819a842c1a4edb4e534ac">CASE_VFMA_OPCODE_LMULS_MF2</a>(OP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5636e92569b83a89a50b180ac901996a">CASE_VFMA_OPCODE_LMULS_MF4</a>(OP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77d1856888824e043ea8e6b763a2c8aa">CASE_VFMA_OPCODE_VV</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b2d4dfc12230301f7677929ffec53a">CASE_VFMA_SPLATS</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5824858de42703a0299483c29bf161b7">CASE_VMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, LMUL)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1793c05b8be52be19f7430919af654">CASE_VMA_CHANGE_OPCODE_LMULS_M1</a>(OLDOP, NEWOP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df2de92c22c087fd5a727c7c9687f44">CASE_VMA_CHANGE_OPCODE_LMULS_MF2</a>(OLDOP, NEWOP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8251a6d2e2b0d706ec1f7e7a8225aeb0">CASE_VMA_CHANGE_OPCODE_LMULS_MF4</a>(OLDOP, NEWOP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a668194d0494b30d8646ffe79d4726437">CASE_VMA_CHANGE_OPCODE_LMULS</a>(OLDOP, NEWOP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294ebdf953116b3db1ee6aee6129d24b">CASE_VMA_CHANGE_OPCODE_SPLATS</a>(OLDOP, NEWOP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf93e0eb733b138ddd006cdb120ee6fd">CASE_VFMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, LMUL, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a159b216503ae4c9348006b6c512f2307">CASE_VFMA_CHANGE_OPCODE_LMULS_M1</a>(OLDOP, NEWOP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec762b32bc3dcc5bbdf139929036853">CASE_VFMA_CHANGE_OPCODE_LMULS_MF2</a>(OLDOP, NEWOP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f05e3b011c4c387d739d55a762d414a">CASE_VFMA_CHANGE_OPCODE_VV</a>(OLDOP, NEWOP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac8a37976795f09162c215a008b69c6">CASE_VFMA_CHANGE_OPCODE_LMULS_MF4</a>(OLDOP, NEWOP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49af16e9f86a311a2836e0f121beadb9">CASE_VFMA_CHANGE_OPCODE_LMULS</a>(OLDOP, NEWOP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a072580305a1e7bbe49a1f629ca91c427">CASE_VFMA_CHANGE_OPCODE_SPLATS</a>(OLDOP, NEWOP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2577efa6a6c2a15477626c22374a4510">CASE_WIDEOP_OPCODE_COMMON</a>(OP, LMUL)&nbsp;&nbsp;&nbsp;  RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##_TIED</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac327385c43cd9514e1850e681546e0b0">CASE_WIDEOP_OPCODE_LMULS_MF4</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d83929bf0f0af935172f616c005fa6e">CASE_WIDEOP_OPCODE_LMULS</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b17487f7b42c42c37424c89e76d1bdf">CASE_WIDEOP_CHANGE_OPCODE_COMMON</a>(OP, LMUL)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97dc0fb5833b11e53a22a3b9311020ed">CASE_WIDEOP_CHANGE_OPCODE_LMULS_MF4</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3b7286bf46bae02f25c23d55890dd6">CASE_WIDEOP_CHANGE_OPCODE_LMULS</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(OP, LMUL, SEW)&nbsp;&nbsp;&nbsp;  RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##SEW##_TIED</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc95a011dc235ec62ecf9557de79b0ff">CASE_FP_WIDEOP_OPCODE_LMULS_MF4</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(OP, LMUL, SEW)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcea0d3881ec219f668641849efbd6f3">CASE_FP_WIDEOP_CHANGE_OPCODE_LMULS_MF4</a>(OP)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d63ab73dd4a2a00d4366493da423e18">CASE_FP_WIDEOP_CHANGE_OPCODE_LMULS</a>(OP)&nbsp;&nbsp;&nbsp;  <a href="#afcea0d3881ec219f668641849efbd6f3">CASE_FP_WIDEOP_CHANGE_OPCODE_LMULS_MF4</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>)</td>
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

## Enumerations

### MachineOutlinerConstructionID {#a7c495f3a5e5dcd30c62df2edeccd86ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum MachineOutlinerConstructionID </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineOutlinerTailCall<a id="a7c495f3a5e5dcd30c62df2edeccd86eaa0f5f89e2a0973bd42b48aa3ab23bc4a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineOutlinerDefault<a id="a7c495f3a5e5dcd30c62df2edeccd86eaae6d079724e013e1fd057cf6fcb57675a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2963 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### analyzeCandidate() {#a2256b109946ab87fcd6aa4f82d610e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool analyzeCandidate (<a href="/web-llvm/docs/api/structs/llvm/outliner/candidate">outliner::Candidate</a> &amp; C)</td>
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



<p>Definition at line 3013 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a05c04a32ecd794f1e86cfb753ed1f5c2">cannotInsertTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a0c5b673184f4d81114afba8a699cdb7e">llvm::RISCVInstrInfo::getOutliningCandidateInfo</a>.</p>

</div>
</div>

### canCombine() {#a41d64a5fd52ca16e16ee50f916ab845a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * canCombine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, unsigned CombineOpc)</td>
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

<p>Utility routine that checks if.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MO</td>
<td class="doxyParamItemDescription"><p>is defined by an</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CombineOpc</td>
<td class="doxyParamItemDescription"><p>instruction in the basic block</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MBB</td>
<td class="doxyParamItemDescription"></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### canCombineFPFusedMultiply() {#ae77d286780a8c426db7adb6c10b9a643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canCombineFPFusedMultiply (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, bool DoRegPressureReduce)</td>
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



<p>Definition at line 2112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a9a1da4c7c2a2a2ed0d083327dd28277c">llvm::MachineInstr::FmContract</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a33365204be9cb132de322e3713253b57">llvm::MachineInstr::getFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a1cfc09d31eaed5d0ca0725d09e044b47">llvm::RISCV::hasEqualFRM</a>, <a href="#a8b2e0dca1cb64c1183b4263cd6621c48">isFMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#aed6416f30361f53101db3f22c2743dbb">getFPFusedMultiplyPatterns</a>.</p>

</div>
</div>

### canCombineShiftIntoShXAdd() {#aab7185336f5a266b994341f14bc8faac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canCombineShiftIntoShXAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, unsigned OuterShiftAmt)</td>
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

<p>Utility routine that checks if.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MO</td>
<td class="doxyParamItemDescription"><p>is defined by a SLLI in</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MBB</td>
<td class="doxyParamItemDescription"><p>that can be combined by splitting across 2 SHXADD instructions. The first SHXADD shift amount is given by</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OuterShiftAmt.</td>
<td class="doxyParamItemDescription"></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a8a77823ca1d474b22f9b923674749a14">canCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#ae7cbe832617857afaa39866967339d87">getSHXADDPatterns</a>.</p>

</div>
</div>

### canFoldAsPredicatedOp() {#adecd02add3a8a4d49bc27c4a6910605c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * canFoldAsPredicatedOp (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
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

<p>Identify instructions that can be folded into a CCMOV instruction, and return the defining instruction.</p>

<p>Definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="#a452b99803927d8ed4cce6d76c385f8ec">getPredicatedOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>.</p>

</div>
</div>

### cannotInsertTailCall() {#a05c04a32ecd794f1e86cfb753ed1f5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool cannotInsertTailCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Definition at line 2992 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ae0de300bc79ed06538e3c4ef611ae27d">llvm::RISCVII::getTailExpandUseRegNo</a>, <a href="#ab0896eaa4dfa916b067de719a48d0060">isCandidatePatchable</a>, <a href="#adc7c182e30e29f733866253f399e5839">isMIModifiesReg</a>, <a href="#ab0c063f61ab51976b76b1b7faa696d31">isMIReadsReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2256b109946ab87fcd6aa4f82d610e28">analyzeCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a80ada2af2a2f2c3f640c0ad4192f53cb">llvm::RISCVInstrInfo::getOutliningTypeImpl</a>.</p>

</div>
</div>

### combineFPFusedMultiply() {#a35be28e9754ada1081edc62f6efc0878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void combineFPFusedMultiply (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Prev, unsigned Pattern, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; InsInstrs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DelInstrs)</td>
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



<p>Definition at line 2308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#a3731ff9b89570138608efcda73d72cdb">getAddendOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad73e18478cd951f76d35a88c4d43ef5a">llvm::MachineInstr::getFlags</a>, <a href="#a227fe86424429965cabaed188260c3c8">getFPFusedMultiplyOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a78cc51c415c7e64b5efe2c8458fbd35a">llvm::DILocation::getMergedLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a4862e12e65a868264ab84a2252104dda">llvm::RISCVInstrInfo::genAlternativeCodeSequence</a>.</p>

</div>
</div>

### forwardCopyWillClobberTuple() {#a331ddeeab0407b2178ebc605b4c168de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool forwardCopyWillClobberTuple (unsigned DstReg, unsigned SrcReg, unsigned NumRegs)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### genShXAddAddShift() {#a488ce2dad0d4f44659a655e17e0ae184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void genShXAddAddShift (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, unsigned AddOpIdx, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; InsInstrs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DelInstrs, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt; &amp; InstrIdxForVirtReg)</td>
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



<p>Definition at line 2354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac57d4100e9a9d02522fbd724568397d">llvm::getKillRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#af1d54b78c6b15c6fcf873f09acc64a2d">getSHXADDShiftAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a4862e12e65a868264ab84a2252104dda">llvm::RISCVInstrInfo::genAlternativeCodeSequence</a>.</p>

</div>
</div>

### getAddendOperandIdx() {#a3731ff9b89570138608efcda73d72cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getAddendOperandIdx (unsigned Pattern)</td>
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



<p>Definition at line 2295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a61cd734252074c5d1764adb9d141b24d">llvm::FMADD_AX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a836a34efbd0aff8a21c38e608762c4ce">llvm::FMADD_XA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a3765a3e5b572f57e131a5eb88c0d4722">llvm::FMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a837b9b047b8d6dc7148a6a8882fb3e48">llvm::FNMSUB</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>.</p>

</div>
</div>

### getCondFromBranchOpc() {#a219be5e26dd017e77e6bae08d2753325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RISCVCC::CondCode getCondFromBranchOpc (unsigned Opc)</td>
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



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a57d7c413055b2060a90dc73ab8f1a512">llvm::RISCVCC::COND_EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a9e7c8526fc843e319e53e5c3174296cc">llvm::RISCVCC::COND_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a12fd715db7ef1428e9cf7b6af55997b8">llvm::RISCVCC::COND_GEU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976af2efde5f90024ff3961e07c0f5f950d9">llvm::RISCVCC::COND_INVALID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a442618536f16dd10730e054e0825b482">llvm::RISCVCC::COND_LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976aefa5b6a280d2aec8bf02b490b207a3cb">llvm::RISCVCC::COND_LTU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvcc/#a54a545c3f090650e4ae09e3174045976a11bb96a4ca4e914a149e9a63e6875ea6">llvm::RISCVCC::COND_NE</a>.</p>

</div>
</div>

### getFPFusedMultiplyOpcode() {#a227fe86424429965cabaed188260c3c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getFPFusedMultiplyOpcode (unsigned RootOpc, unsigned Pattern)</td>
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



<p>Definition at line 2273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a3765a3e5b572f57e131a5eb88c0d4722">llvm::FMSUB</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>.</p>

</div>
</div>

### getFPFusedMultiplyPatterns() {#aed6416f30361f53101db3f22c2743dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getFPFusedMultiplyPatterns (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Patterns, bool DoRegPressureReduce)</td>
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



<p>Definition at line 2139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a61cd734252074c5d1764adb9d141b24d">llvm::FMADD_AX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a836a34efbd0aff8a21c38e608762c4ce">llvm::FMADD_XA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a3765a3e5b572f57e131a5eb88c0d4722">llvm::FMSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a837b9b047b8d6dc7148a6a8882fb3e48">llvm::FNMSUB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#ab9ee85d1d74b35fcebf4a24fcd802578">isFADD</a>, <a href="#a666d2e57a2f9d581d596d2cd0f48894a">isFSUB</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a8e777196afeae01008075acf289bc924">getFPPatterns</a>.</p>

</div>
</div>

### getFPPatterns() {#a8e777196afeae01008075acf289bc924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getFPPatterns (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Patterns, bool DoRegPressureReduce)</td>
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



<p>Definition at line 2162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Reference <a href="#aed6416f30361f53101db3f22c2743dbb">getFPFusedMultiplyPatterns</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ae92946bff8cb4ef04b71f5f6360e832e">llvm::RISCVInstrInfo::getMachineCombinerPatterns</a>.</p>

</div>
</div>

### getPredicatedOpcode() {#a452b99803927d8ed4cce6d76c385f8ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPredicatedOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#adecd02add3a8a4d49bc27c4a6910605c">canFoldAsPredicatedOp</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>.</p>

</div>
</div>

### getSHXADDPatterns() {#ae7cbe832617857afaa39866967339d87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getSHXADDPatterns (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Root, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Patterns)</td>
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



<p>Definition at line 2222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a8a77823ca1d474b22f9b923674749a14">canCombine</a>, <a href="#aab7185336f5a266b994341f14bc8faac">canCombineShiftIntoShXAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="#af1d54b78c6b15c6fcf873f09acc64a2d">getSHXADDShiftAmount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02ac182d12532b8a651beef3002b83f0ce3">llvm::SHXADD_ADD_SLLI_OP1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a074efa948b2b878d89eed41dbc6b7d02a3454ed75f30d39397bfb7c264d9dbd24">llvm::SHXADD_ADD_SLLI_OP2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ae92946bff8cb4ef04b71f5f6360e832e">llvm::RISCVInstrInfo::getMachineCombinerPatterns</a>.</p>

</div>
</div>

### getSHXADDShiftAmount() {#af1d54b78c6b15c6fcf873f09acc64a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getSHXADDShiftAmount (unsigned Opc)</td>
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



<p>Definition at line 2207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a> and <a href="#ae7cbe832617857afaa39866967339d87">getSHXADDPatterns</a>.</p>

</div>
</div>

### isCandidatePatchable() {#ab0896eaa4dfa916b067de719a48d0060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCandidatePatchable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Definition at line 2973 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a05c04a32ecd794f1e86cfb753ed1f5c2">cannotInsertTailCall</a>.</p>

</div>
</div>

### isConvertibleToVMV\_V\_V() {#acec254d4fbb18621ee4d54f867af85f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConvertibleToVMV_V_V (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> &amp; DefMBBI, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ab335a6694bd42d4d2f807ec281af1e1c">RISCVII::VLMUL</a> LMul)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#ac548025beac55d0f686dab8fa015e968">llvm::RISCVSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#af5af8d664535a4bfbb71f0243ed9ae3a">llvm::RISCVVType::getSEW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a12465125c9315bf864c53298cccde08a">llvm::RISCVVType::getVLMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#afc858f8e35813be95df97504afd771ef">llvm::RISCVII::hasSEWOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a81c11c8178c6df7f55ef0557daa54765">llvm::RISCVII::hasVLOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#aec590acd5a105a4b898d9dd2be57b6a7">llvm::RISCVII::isRVVWideningReduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvvtype/#a08cfea4b8c9e0a6118dc031cafeb0773">llvm::RISCVVType::isTailAgnostic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#a44769ad9ee8a26cd247145fa02883792">PreferWholeRegisterMove</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a436965f98f9e4301e33096c32ed6dbd2">llvm::RISCVInstrInfo::copyPhysRegVector</a>.</p>

</div>
</div>

### isFADD() {#ab9ee85d1d74b35fcebf4a24fcd802578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFADD (unsigned Opc)</td>
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



<p>Definition at line 1714 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#aed6416f30361f53101db3f22c2743dbb">getFPFusedMultiplyPatterns</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ade726ab992f758b88dcc4d6691efd90d">llvm::RISCVInstrInfo::isAssociativeAndCommutative</a>.</p>

</div>
</div>

### isFMUL() {#a8b2e0dca1cb64c1183b4263cd6621c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFMUL (unsigned Opc)</td>
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



<p>Definition at line 1736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ade726ab992f758b88dcc4d6691efd90d">llvm::RISCVInstrInfo::isAssociativeAndCommutative</a>.</p>

</div>
</div>

### isFSUB() {#a666d2e57a2f9d581d596d2cd0f48894a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFSUB (unsigned Opc)</td>
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



<p>Definition at line 1725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#aed6416f30361f53101db3f22c2743dbb">getFPFusedMultiplyPatterns</a>.</p>

</div>
</div>

### isMIModifiesReg() {#adc7c182e30e29f733866253f399e5839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isMIModifiesReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, unsigned RegNo)</td>
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



<p>Definition at line 2986 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a05c04a32ecd794f1e86cfb753ed1f5c2">cannotInsertTailCall</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a80ada2af2a2f2c3f640c0ad4192f53cb">llvm::RISCVInstrInfo::getOutliningTypeImpl</a>.</p>

</div>
</div>

### isMIReadsReg() {#ab0c063f61ab51976b76b1b7faa696d31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isMIReadsReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, unsigned RegNo)</td>
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



<p>Definition at line 2980 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a05c04a32ecd794f1e86cfb753ed1f5c2">cannotInsertTailCall</a>.</p>

</div>
</div>

### isRVVWholeLoadStore() {#a1e1feb44daab9c30a1f6303e436adad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRVVWholeLoadStore (unsigned Opcode)</td>
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



<p>Definition at line 4006 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ad821f506ad146f3ed222dbdeb8c3ca06">llvm::RISCV::isRVVSpill</a>.</p>

</div>
</div>

### memOpsHaveSameBasePtr() {#a951bbdda542205db9de80f6bf44f571c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool memOpsHaveSameBasePtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; BaseOps1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI2, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt; BaseOps2)</td>
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



<p>Definition at line 2791 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999795324f5e7c578a97992d780080f1">llvm::MachineInstr::hasOneMemOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa5ff177bc1498508696aaf27235db3fc">llvm::MachineInstr::memoperands_begin</a>.</p>

</div>
</div>

### parseCondBranch() {#aeb1310110d7dbaccfa5d0973446dc718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseCondBranch (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; LastInst, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; Target, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond)</td>
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



<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-cpp/#a1019cb49e24ce2dc8727c8fe035a352a">getCondFromBranchOpc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#aea73c4d0a4275b356a0d33ed0c6ccc58">llvm::MCInstrDesc::isConditionalBranch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ForceMachineCombinerStrategy {#af03fd419ccbdaf310f135c41bc14e0d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; MachineTraceStrategy &gt; ForceMachineCombinerStrategy("riscv-force-machine-combiner-strategy", cl::Hidden, cl::desc("Force machine combiner to use a specific strategy for machine " "trace metrics evaluation."), cl::init(MachineTraceStrategy::TS_NumStrategies), cl::values(clEnumValN(MachineTraceStrategy::TS_Local, "local", "Local strategy."), clEnumValN(MachineTraceStrategy::TS_MinInstrCount, "min-instr", "MinInstrCount strategy.")))</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a81c45072c5b34b2cbc6bae4a61b5900d">llvm::RISCVInstrInfo::getMachineCombinerTraceStrategy</a>.</p>

</div>
</div>

### PreferWholeRegisterMove {#a44769ad9ee8a26cd247145fa02883792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PreferWholeRegisterMove("riscv-prefer-whole-register-move", cl::init(false), cl::Hidden, cl::desc("Prefer whole register move for vector registers."))</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#acec254d4fbb18621ee4d54f867af85f9">isConvertibleToVMV_V_V</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CASE\_FP\_WIDEOP\_CHANGE\_OPCODE\_COMMON {#ab0cd0e77a310d074b0c4a2534db35689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON(OP, LMUL, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##SEW##_TIED:                             \
    NewOpc = RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##SEW;                              \
    break;
</div>
</dd>
</dl>

<p>Definition at line 3737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_FP\_WIDEOP\_CHANGE\_OPCODE\_LMULS {#a2d63ab73dd4a2a00d4366493da423e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FP_WIDEOP_CHANGE_OPCODE_LMULS(OP)&nbsp;&nbsp;&nbsp;  <a href="#afcea0d3881ec219f668641849efbd6f3">CASE_FP_WIDEOP_CHANGE_OPCODE_LMULS_MF4</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_FP\_WIDEOP\_CHANGE\_OPCODE\_LMULS\_MF4 {#afcea0d3881ec219f668641849efbd6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FP_WIDEOP_CHANGE_OPCODE_LMULS_MF4(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF4, E16)                            \
  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF2, E16)                            \
  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF2, E32)                            \
  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M1, E16)                             \
  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M1, E32)                             \
  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M2, E16)                             \
  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M2, E32)                             \
  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M4, E16)                             \
  <a href="#ab0cd0e77a310d074b0c4a2534db35689">CASE_FP_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M4, E32)                             \
</div>
</dd>
</dl>

<p>Definition at line 3742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>.</p>

</div>
</div>

### CASE\_FP\_WIDEOP\_OPCODE\_COMMON {#a360d35c1eb938fe8fc706a83db4cb42a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FP_WIDEOP_OPCODE_COMMON(OP, LMUL, SEW)&nbsp;&nbsp;&nbsp;  RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##SEW##_TIED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_FP\_WIDEOP\_OPCODE\_LMULS\_MF4 {#acc95a011dc235ec62ecf9557de79b0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_FP_WIDEOP_OPCODE_LMULS_MF4(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF4, E16):                                  \
  case <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF2, E16):                             \
  case <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF2, E32):                             \
  case <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M1, E16):                              \
  case <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M1, E32):                              \
  case <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M2, E16):                              \
  case <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M2, E32):                              \
  case <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M4, E16):                              \
  case <a href="#a360d35c1eb938fe8fc706a83db4cb42a">CASE_FP_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M4, E32)                               \
</div>
</dd>
</dl>

<p>Definition at line 3726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>.</p>

</div>
</div>

### CASE\_OPERAND\_SIMM {#a1c5acfdaa401f68a4074a8013a727d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_OPERAND_SIMM(NUM)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCVOp::OPERAND_SIMM##NUM:                                             \
    Ok = isInt&lt;NUM&gt;(Imm);                                                      \
    break;
</div>
</dd>
</dl>

<p>Definition at line 2469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6643db423ad018f2a7375b8f46e439af">llvm::RISCVInstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### CASE\_OPERAND\_UIMM {#a9fd4a20c7548cf908d37bee756be9caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_OPERAND_UIMM(NUM)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCVOp::OPERAND_UIMM##NUM:                                             \
    Ok = isUInt&lt;NUM&gt;(Imm);                                                     \
    break;
</div>
</dd>
</dl>

<p>Definition at line 2465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6643db423ad018f2a7375b8f46e439af">llvm::RISCVInstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE {#a746d9af508f41326e8e11b551c077f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a39994273d02b34906532e21f1fddafe8">CASE_RVV_OPCODE_UNMASK</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>):                                                 \
  case <a href="#af517025a8083176b552fd7804176f797">CASE_RVV_OPCODE_MASK</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>)
</div>
</dd>
</dl>

<p>Definition at line 3273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac6b66ad3777d7d6fa3a96bfd7031c28d">llvm::RISCVInstrInfo::findCommutedOpIndices</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE\_LMUL {#ae3beca399cd888bf9592a5fd0fddc0bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE_LMUL(OP, LMUL)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, LMUL):                                      \
  case <a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, LMUL)
</div>
</dd>
</dl>

<p>Definition at line 3241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE\_MASK {#af517025a8083176b552fd7804176f797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE_MASK(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#afefd18224ae60f4544513bd1e867f814">CASE_RVV_OPCODE_MASK_WIDEN</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>):                                             \
  case <a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M8)
</div>
</dd>
</dl>

<p>Definition at line 3265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac6b66ad3777d7d6fa3a96bfd7031c28d">llvm::RISCVInstrInfo::findCommutedOpIndices</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE\_MASK\_LMUL {#aff0686a05e54e2736947743cab265c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE_MASK_LMUL(OP, LMUL)&nbsp;&nbsp;&nbsp;  RISCV::Pseudo##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##_MASK</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE\_MASK\_WIDEN {#afefd18224ae60f4544513bd1e867f814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE_MASK_WIDEN(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF8):                                         \
  case <a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF4):                                    \
  case <a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF2):                                    \
  case <a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M1):                                     \
  case <a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M2):                                     \
  case <a href="#aff0686a05e54e2736947743cab265c9b">CASE_RVV_OPCODE_MASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M4)
</div>
</dd>
</dl>

<p>Definition at line 3257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE\_UNMASK {#a39994273d02b34906532e21f1fddafe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE_UNMASK(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ac1358a36845d3b21256f2f7e762b2820">CASE_RVV_OPCODE_UNMASK_WIDEN</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>):                                           \
  case <a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M8)
</div>
</dd>
</dl>

<p>Definition at line 3253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac6b66ad3777d7d6fa3a96bfd7031c28d">llvm::RISCVInstrInfo::findCommutedOpIndices</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE\_UNMASK\_LMUL {#acaed1a1aeacb5d4d5a09976b67d1422c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE_UNMASK_LMUL(OP, LMUL)&nbsp;&nbsp;&nbsp;  RISCV::Pseudo##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE\_UNMASK\_WIDEN {#ac1358a36845d3b21256f2f7e762b2820}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE_UNMASK_WIDEN(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF8):                                       \
  case <a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF4):                                  \
  case <a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF2):                                  \
  case <a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M1):                                   \
  case <a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M2):                                   \
  case <a href="#acaed1a1aeacb5d4d5a09976b67d1422c">CASE_RVV_OPCODE_UNMASK_LMUL</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M4)
</div>
</dd>
</dl>

<p>Definition at line 3245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_RVV\_OPCODE\_WIDEN {#a81ff02149bce7a64d19414caad225042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_RVV_OPCODE_WIDEN(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ac1358a36845d3b21256f2f7e762b2820">CASE_RVV_OPCODE_UNMASK_WIDEN</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>):                                           \
  case <a href="#afefd18224ae60f4544513bd1e867f814">CASE_RVV_OPCODE_MASK_WIDEN</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>)
</div>
</dd>
</dl>

<p>Definition at line 3269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac6b66ad3777d7d6fa3a96bfd7031c28d">llvm::RISCVInstrInfo::findCommutedOpIndices</a>.</p>

</div>
</div>

### CASE\_VFMA\_CHANGE\_OPCODE\_COMMON {#abf93e0eb733b138ddd006cdb120ee6fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_CHANGE_OPCODE_COMMON(OLDOP, NEWOP, TYPE, LMUL, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::PseudoV##OLDOP##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##TYPE##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##SEW:                        \
    Opc = RISCV::PseudoV##NEWOP##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##TYPE##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##SEW;                     \
    break;
</div>
</dd>
</dl>

<p>Definition at line 3521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_CHANGE\_OPCODE\_LMULS {#a49af16e9f86a311a2836e0f121beadb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_CHANGE_OPCODE_LMULS(OLDOP, NEWOP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#abf93e0eb733b138ddd006cdb120ee6fd">CASE_VFMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, MF8, SEW)                 \
  <a href="#a4ac8a37976795f09162c215a008b69c6">CASE_VFMA_CHANGE_OPCODE_LMULS_MF4</a>(OLDOP, NEWOP, TYPE, SEW)
</div>
</dd>
</dl>

<p>Definition at line 3545 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_CHANGE\_OPCODE\_LMULS\_M1 {#a159b216503ae4c9348006b6c512f2307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_CHANGE_OPCODE_LMULS_M1(OLDOP, NEWOP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#abf93e0eb733b138ddd006cdb120ee6fd">CASE_VFMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, M1, SEW)                  \
  <a href="#abf93e0eb733b138ddd006cdb120ee6fd">CASE_VFMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, M2, SEW)                  \
  <a href="#abf93e0eb733b138ddd006cdb120ee6fd">CASE_VFMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, M4, SEW)                  \
  <a href="#abf93e0eb733b138ddd006cdb120ee6fd">CASE_VFMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, M8, SEW)
</div>
</dd>
</dl>

<p>Definition at line 3526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_CHANGE\_OPCODE\_LMULS\_MF2 {#aeec762b32bc3dcc5bbdf139929036853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_CHANGE_OPCODE_LMULS_MF2(OLDOP, NEWOP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#abf93e0eb733b138ddd006cdb120ee6fd">CASE_VFMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, MF2, SEW)                 \
  <a href="#a159b216503ae4c9348006b6c512f2307">CASE_VFMA_CHANGE_OPCODE_LMULS_M1</a>(OLDOP, NEWOP, TYPE, SEW)
</div>
</dd>
</dl>

<p>Definition at line 3532 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_CHANGE\_OPCODE\_LMULS\_MF4 {#a4ac8a37976795f09162c215a008b69c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_CHANGE_OPCODE_LMULS_MF4(OLDOP, NEWOP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#abf93e0eb733b138ddd006cdb120ee6fd">CASE_VFMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, MF4, SEW)                 \
  <a href="#aeec762b32bc3dcc5bbdf139929036853">CASE_VFMA_CHANGE_OPCODE_LMULS_MF2</a>(OLDOP, NEWOP, TYPE, SEW)
</div>
</dd>
</dl>

<p>Definition at line 3541 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_CHANGE\_OPCODE\_SPLATS {#a072580305a1e7bbe49a1f629ca91c427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_CHANGE_OPCODE_SPLATS(OLDOP, NEWOP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a4ac8a37976795f09162c215a008b69c6">CASE_VFMA_CHANGE_OPCODE_LMULS_MF4</a>(OLDOP, NEWOP, VFPR16, E16)                 \
  <a href="#aeec762b32bc3dcc5bbdf139929036853">CASE_VFMA_CHANGE_OPCODE_LMULS_MF2</a>(OLDOP, NEWOP, VFPR32, E32)                 \
  <a href="#a159b216503ae4c9348006b6c512f2307">CASE_VFMA_CHANGE_OPCODE_LMULS_M1</a>(OLDOP, NEWOP, VFPR64, E64)
</div>
</dd>
</dl>

<p>Definition at line 3549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aabdf5cb19126a5e4243ff0818a908ccb">llvm::RISCVInstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### CASE\_VFMA\_CHANGE\_OPCODE\_VV {#a1f05e3b011c4c387d739d55a762d414a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_CHANGE_OPCODE_VV(OLDOP, NEWOP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a4ac8a37976795f09162c215a008b69c6">CASE_VFMA_CHANGE_OPCODE_LMULS_MF4</a>(OLDOP, NEWOP, VV, E16)                     \
  <a href="#aeec762b32bc3dcc5bbdf139929036853">CASE_VFMA_CHANGE_OPCODE_LMULS_MF2</a>(OLDOP, NEWOP, VV, E32)                     \
  <a href="#a159b216503ae4c9348006b6c512f2307">CASE_VFMA_CHANGE_OPCODE_LMULS_M1</a>(OLDOP, NEWOP, VV, E64)
</div>
</dd>
</dl>

<p>Definition at line 3536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aabdf5cb19126a5e4243ff0818a908ccb">llvm::RISCVInstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### CASE\_VFMA\_OPCODE\_COMMON {#ae1599d31dc429d75f29eace3beeafed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_OPCODE_COMMON(OP, TYPE, LMUL, SEW)&nbsp;&nbsp;&nbsp;  RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##TYPE##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##SEW</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_OPCODE\_LMULS\_M1 {#aed8f9a40c3a2a7c45398506849859213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_OPCODE_LMULS_M1(OP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ae1599d31dc429d75f29eace3beeafed3">CASE_VFMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, M1, SEW):                                  \
  case <a href="#ae1599d31dc429d75f29eace3beeafed3">CASE_VFMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, M2, SEW):                             \
  case <a href="#ae1599d31dc429d75f29eace3beeafed3">CASE_VFMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, M4, SEW):                             \
  case <a href="#ae1599d31dc429d75f29eace3beeafed3">CASE_VFMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, M8, SEW)
</div>
</dd>
</dl>

<p>Definition at line 3304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_OPCODE\_LMULS\_MF2 {#af6b599bda45819a842c1a4edb4e534ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_OPCODE_LMULS_MF2(OP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ae1599d31dc429d75f29eace3beeafed3">CASE_VFMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, MF2, SEW):                                 \
  case <a href="#aed8f9a40c3a2a7c45398506849859213">CASE_VFMA_OPCODE_LMULS_M1</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, SEW)
</div>
</dd>
</dl>

<p>Definition at line 3310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_OPCODE\_LMULS\_MF4 {#a5636e92569b83a89a50b180ac901996a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_OPCODE_LMULS_MF4(OP, TYPE, SEW)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ae1599d31dc429d75f29eace3beeafed3">CASE_VFMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, MF4, SEW):                                 \
  case <a href="#af6b599bda45819a842c1a4edb4e534ac">CASE_VFMA_OPCODE_LMULS_MF2</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, SEW)
</div>
</dd>
</dl>

<p>Definition at line 3314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VFMA\_OPCODE\_VV {#a77d1856888824e043ea8e6b763a2c8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_OPCODE_VV(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a5636e92569b83a89a50b180ac901996a">CASE_VFMA_OPCODE_LMULS_MF4</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, VV, E16):                                     \
  case <a href="#af6b599bda45819a842c1a4edb4e534ac">CASE_VFMA_OPCODE_LMULS_MF2</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, VV, E32):                                \
  case <a href="#aed8f9a40c3a2a7c45398506849859213">CASE_VFMA_OPCODE_LMULS_M1</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, VV, E64)
</div>
</dd>
</dl>

<p>Definition at line 3318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aabdf5cb19126a5e4243ff0818a908ccb">llvm::RISCVInstrInfo::commuteInstructionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac6b66ad3777d7d6fa3a96bfd7031c28d">llvm::RISCVInstrInfo::findCommutedOpIndices</a>.</p>

</div>
</div>

### CASE\_VFMA\_SPLATS {#a44b2d4dfc12230301f7677929ffec53a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VFMA_SPLATS(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a5636e92569b83a89a50b180ac901996a">CASE_VFMA_OPCODE_LMULS_MF4</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, VFPR16, E16):                                 \
  case <a href="#af6b599bda45819a842c1a4edb4e534ac">CASE_VFMA_OPCODE_LMULS_MF2</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, VFPR32, E32):                            \
  case <a href="#aed8f9a40c3a2a7c45398506849859213">CASE_VFMA_OPCODE_LMULS_M1</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, VFPR64, E64)
</div>
</dd>
</dl>

<p>Definition at line 3323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aabdf5cb19126a5e4243ff0818a908ccb">llvm::RISCVInstrInfo::commuteInstructionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac6b66ad3777d7d6fa3a96bfd7031c28d">llvm::RISCVInstrInfo::findCommutedOpIndices</a>.</p>

</div>
</div>

### CASE\_VMA\_CHANGE\_OPCODE\_COMMON {#a5824858de42703a0299483c29bf161b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_CHANGE_OPCODE_COMMON(OLDOP, NEWOP, TYPE, LMUL)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::PseudoV##OLDOP##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##TYPE##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL:                                \
    Opc = RISCV::PseudoV##NEWOP##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##TYPE##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL;                             \
    break;
</div>
</dd>
</dl>

<p>Definition at line 3492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VMA\_CHANGE\_OPCODE\_LMULS {#a668194d0494b30d8646ffe79d4726437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_CHANGE_OPCODE_LMULS(OLDOP, NEWOP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a5824858de42703a0299483c29bf161b7">CASE_VMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, MF8)                       \
  <a href="#a8251a6d2e2b0d706ec1f7e7a8225aeb0">CASE_VMA_CHANGE_OPCODE_LMULS_MF4</a>(OLDOP, NEWOP, TYPE)
</div>
</dd>
</dl>

<p>Definition at line 3511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aabdf5cb19126a5e4243ff0818a908ccb">llvm::RISCVInstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### CASE\_VMA\_CHANGE\_OPCODE\_LMULS\_M1 {#aee1793c05b8be52be19f7430919af654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_CHANGE_OPCODE_LMULS_M1(OLDOP, NEWOP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a5824858de42703a0299483c29bf161b7">CASE_VMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, M1)                        \
  <a href="#a5824858de42703a0299483c29bf161b7">CASE_VMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, M2)                        \
  <a href="#a5824858de42703a0299483c29bf161b7">CASE_VMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, M4)                        \
  <a href="#a5824858de42703a0299483c29bf161b7">CASE_VMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, M8)
</div>
</dd>
</dl>

<p>Definition at line 3497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VMA\_CHANGE\_OPCODE\_LMULS\_MF2 {#a0df2de92c22c087fd5a727c7c9687f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_CHANGE_OPCODE_LMULS_MF2(OLDOP, NEWOP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a5824858de42703a0299483c29bf161b7">CASE_VMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, MF2)                       \
  <a href="#aee1793c05b8be52be19f7430919af654">CASE_VMA_CHANGE_OPCODE_LMULS_M1</a>(OLDOP, NEWOP, TYPE)
</div>
</dd>
</dl>

<p>Definition at line 3503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VMA\_CHANGE\_OPCODE\_LMULS\_MF4 {#a8251a6d2e2b0d706ec1f7e7a8225aeb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_CHANGE_OPCODE_LMULS_MF4(OLDOP, NEWOP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a5824858de42703a0299483c29bf161b7">CASE_VMA_CHANGE_OPCODE_COMMON</a>(OLDOP, NEWOP, TYPE, MF4)                       \
  <a href="#a0df2de92c22c087fd5a727c7c9687f44">CASE_VMA_CHANGE_OPCODE_LMULS_MF2</a>(OLDOP, NEWOP, TYPE)
</div>
</dd>
</dl>

<p>Definition at line 3507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VMA\_CHANGE\_OPCODE\_SPLATS {#a294ebdf953116b3db1ee6aee6129d24b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_CHANGE_OPCODE_SPLATS(OLDOP, NEWOP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a8251a6d2e2b0d706ec1f7e7a8225aeb0">CASE_VMA_CHANGE_OPCODE_LMULS_MF4</a>(OLDOP, NEWOP, VFPR16)                       \
  <a href="#a0df2de92c22c087fd5a727c7c9687f44">CASE_VMA_CHANGE_OPCODE_LMULS_MF2</a>(OLDOP, NEWOP, VFPR32)                       \
  <a href="#aee1793c05b8be52be19f7430919af654">CASE_VMA_CHANGE_OPCODE_LMULS_M1</a>(OLDOP, NEWOP, VFPR64)
</div>
</dd>
</dl>

<p>Definition at line 3515 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VMA\_OPCODE\_COMMON {#a89de0245330e0e334ffef52e284b6eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_OPCODE_COMMON(OP, TYPE, LMUL)&nbsp;&nbsp;&nbsp;  RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##TYPE##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VMA\_OPCODE\_LMULS {#a892e48a5567b90825543dce3f5f37e1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_OPCODE_LMULS(OP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a89de0245330e0e334ffef52e284b6eca">CASE_VMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, MF8):                                       \
  case <a href="#a482032ef5d24b84b04eca82b256df3b4">CASE_VMA_OPCODE_LMULS_MF4</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE)
</div>
</dd>
</dl>

<p>Definition at line 3296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aabdf5cb19126a5e4243ff0818a908ccb">llvm::RISCVInstrInfo::commuteInstructionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ac6b66ad3777d7d6fa3a96bfd7031c28d">llvm::RISCVInstrInfo::findCommutedOpIndices</a>.</p>

</div>
</div>

### CASE\_VMA\_OPCODE\_LMULS\_M1 {#a409c4a64458a4ae95962f464c2d0516e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_OPCODE_LMULS_M1(OP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a89de0245330e0e334ffef52e284b6eca">CASE_VMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, M1):                                        \
  case <a href="#a89de0245330e0e334ffef52e284b6eca">CASE_VMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, M2):                                   \
  case <a href="#a89de0245330e0e334ffef52e284b6eca">CASE_VMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, M4):                                   \
  case <a href="#a89de0245330e0e334ffef52e284b6eca">CASE_VMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, M8)
</div>
</dd>
</dl>

<p>Definition at line 3282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VMA\_OPCODE\_LMULS\_MF2 {#acd6607728af31885b1fbf34a6397ae99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_OPCODE_LMULS_MF2(OP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a89de0245330e0e334ffef52e284b6eca">CASE_VMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, MF2):                                       \
  case <a href="#a409c4a64458a4ae95962f464c2d0516e">CASE_VMA_OPCODE_LMULS_M1</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE)
</div>
</dd>
</dl>

<p>Definition at line 3288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_VMA\_OPCODE\_LMULS\_MF4 {#a482032ef5d24b84b04eca82b256df3b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMA_OPCODE_LMULS_MF4(OP, TYPE)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a89de0245330e0e334ffef52e284b6eca">CASE_VMA_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE, MF4):                                       \
  case <a href="#acd6607728af31885b1fbf34a6397ae99">CASE_VMA_OPCODE_LMULS_MF2</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, TYPE)
</div>
</dd>
</dl>

<p>Definition at line 3292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_WIDEOP\_CHANGE\_OPCODE\_COMMON {#a8b17487f7b42c42c37424c89e76d1bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_WIDEOP_CHANGE_OPCODE_COMMON(OP, LMUL)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##_TIED:                                     \
    NewOpc = RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL;                                      \
    break;
</div>
</dd>
</dl>

<p>Definition at line 3706 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_WIDEOP\_CHANGE\_OPCODE\_LMULS {#a3b3b7286bf46bae02f25c23d55890dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_WIDEOP_CHANGE_OPCODE_LMULS(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a8b17487f7b42c42c37424c89e76d1bdf">CASE_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF8)                                    \
  <a href="#a97dc0fb5833b11e53a22a3b9311020ed">CASE_WIDEOP_CHANGE_OPCODE_LMULS_MF4</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>)
</div>
</dd>
</dl>

<p>Definition at line 3718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>.</p>

</div>
</div>

### CASE\_WIDEOP\_CHANGE\_OPCODE\_LMULS\_MF4 {#a97dc0fb5833b11e53a22a3b9311020ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_WIDEOP_CHANGE_OPCODE_LMULS_MF4(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a8b17487f7b42c42c37424c89e76d1bdf">CASE_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF4)                                    \
  <a href="#a8b17487f7b42c42c37424c89e76d1bdf">CASE_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF2)                                    \
  <a href="#a8b17487f7b42c42c37424c89e76d1bdf">CASE_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M1)                                     \
  <a href="#a8b17487f7b42c42c37424c89e76d1bdf">CASE_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M2)                                     \
  <a href="#a8b17487f7b42c42c37424c89e76d1bdf">CASE_WIDEOP_CHANGE_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M4)
</div>
</dd>
</dl>

<p>Definition at line 3711 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_WIDEOP\_OPCODE\_COMMON {#a2577efa6a6c2a15477626c22374a4510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_WIDEOP_OPCODE_COMMON(OP, LMUL)&nbsp;&nbsp;&nbsp;  RISCV::PseudoV##<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>##<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>##LMUL##_TIED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3692 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### CASE\_WIDEOP\_OPCODE\_LMULS {#a5d83929bf0f0af935172f616c005fa6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_WIDEOP_OPCODE_LMULS(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a2577efa6a6c2a15477626c22374a4510">CASE_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF8):                                          \
  case <a href="#ac327385c43cd9514e1850e681546e0b0">CASE_WIDEOP_OPCODE_LMULS_MF4</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>)
</div>
</dd>
</dl>

<p>Definition at line 3702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>.</p>

</div>
</div>

### CASE\_WIDEOP\_OPCODE\_LMULS\_MF4 {#ac327385c43cd9514e1850e681546e0b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_WIDEOP_OPCODE_LMULS_MF4(OP)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a2577efa6a6c2a15477626c22374a4510">CASE_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF4):                                          \
  case <a href="#a2577efa6a6c2a15477626c22374a4510">CASE_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, MF2):                                     \
  case <a href="#a2577efa6a6c2a15477626c22374a4510">CASE_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M1):                                      \
  case <a href="#a2577efa6a6c2a15477626c22374a4510">CASE_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M2):                                      \
  case <a href="#a2577efa6a6c2a15477626c22374a4510">CASE_WIDEOP_OPCODE_COMMON</a>(<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, M4)
</div>
</dd>
</dl>

<p>Definition at line 3695 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### GEN\_CHECK\_COMPRESS\_INSTR {#afb9d1dde65c47f060f939f4a9dd39609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GEN_CHECK_COMPRESS_INSTR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_CTOR\_DTOR {#a5d99008fb7e5cdc4774786d0743a2c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_CTOR_DTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_NAMED\_OPS {#a16f11ade4c7901484baa40cab9d0d011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_NAMED_OPS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_RISCVMaskedPseudosTable\_IMPL {#a1328aafab0ba8132134ae839043e1ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVMaskedPseudosTable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_RISCVVPseudosTable\_IMPL {#a614407ca17f81d23604b51b027435618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_RISCVVPseudosTable_IMPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### OPCODE\_LMUL\_CASE {#a9f457938cfffac21cf486461098ad369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPCODE_LMUL_CASE(OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::OPC##_M1:                                                        \
  case RISCV::OPC##_M2:                                                        \
  case RISCV::OPC##_M4:                                                        \
  case RISCV::OPC##_M8:                                                        \
  case RISCV::OPC##_MF2:                                                       \
  case RISCV::OPC##_MF4:                                                       \
  case RISCV::OPC##_MF8
</div>
</dd>
</dl>

<p>Definition at line 1749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### OPCODE\_LMUL\_MASK\_CASE {#a629db2495dfa61b86c613f56c562972b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define OPCODE_LMUL_MASK_CASE(OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::OPC##_M1_MASK:                                                   \
  case RISCV::OPC##_M2_MASK:                                                   \
  case RISCV::OPC##_M4_MASK:                                                   \
  case RISCV::OPC##_M8_MASK:                                                   \
  case RISCV::OPC##_MF2_MASK:                                                  \
  case RISCV::OPC##_MF4_MASK:                                                  \
  case RISCV::OPC##_MF8_MASK
</div>
</dd>
</dl>

<p>Definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>

</div>
</div>

### RVV\_OPC\_LMUL\_CASE {#a278585ad9c23c5879636f58577ca7e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RVV_OPC_LMUL_CASE(OPC, INV)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::OPC##_M1:                                                        \
    return RISCV::INV##_M1;                                                    \
  case RISCV::OPC##_M2:                                                        \
    return RISCV::INV##_M2;                                                    \
  case RISCV::OPC##_M4:                                                        \
    return RISCV::INV##_M4;                                                    \
  case RISCV::OPC##_M8:                                                        \
    return RISCV::INV##_M8;                                                    \
  case RISCV::OPC##_MF2:                                                       \
    return RISCV::INV##_MF2;                                                   \
  case RISCV::OPC##_MF4:                                                       \
    return RISCV::INV##_MF4;                                                   \
  case RISCV::OPC##_MF8:                                                       \
    return RISCV::INV##_MF8
</div>
</dd>
</dl>

<p>Definition at line 2045 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a79a9b4d0a95a7b0b741f2aaae4b3427d">llvm::RISCVInstrInfo::getInverseOpcode</a>.</p>

</div>
</div>

### RVV\_OPC\_LMUL\_MASK\_CASE {#afc35a104603ecf73a4433722be892952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RVV_OPC_LMUL_MASK_CASE(OPC, INV)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::OPC##_M1_MASK:                                                   \
    return RISCV::INV##_M1_MASK;                                               \
  case RISCV::OPC##_M2_MASK:                                                   \
    return RISCV::INV##_M2_MASK;                                               \
  case RISCV::OPC##_M4_MASK:                                                   \
    return RISCV::INV##_M4_MASK;                                               \
  case RISCV::OPC##_M8_MASK:                                                   \
    return RISCV::INV##_M8_MASK;                                               \
  case RISCV::OPC##_MF2_MASK:                                                  \
    return RISCV::INV##_MF2_MASK;                                              \
  case RISCV::OPC##_MF4_MASK:                                                  \
    return RISCV::INV##_MF4_MASK;                                              \
  case RISCV::OPC##_MF8_MASK:                                                  \
    return RISCV::INV##_MF8_MASK
</div>
</dd>
</dl>

<p>Definition at line 2061 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp">RISCVInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a79a9b4d0a95a7b0b741f2aaae4b3427d">llvm::RISCVInstrInfo::getInverseOpcode</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
