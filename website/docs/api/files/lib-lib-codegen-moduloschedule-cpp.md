---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/moduloschedule-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ModuloSchedule.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">llvm/CodeGen/ModuloSchedule.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">llvm/Analysis/MemoryLocation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-moduloschedule-cpp-">anonymous{ModuloSchedule.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter">KernelRewriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrites the kernel block in-place to adhere to the given schedule. <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kerneloperandinfo">KernelOperandInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describes an operand in the kernel of a pipelined loop. <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kerneloperandinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest">ModuloScheduleTest</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4cf8c8e4e2cc5bf94656e979ed629b4">getPhiRegs</a> (MachineInstr &amp;Phi, MachineBasicBlock *Loop, unsigned &amp;InitVal, unsigned &amp;LoopVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register values for the operands of a Phi instruction. <a href="#ad4cf8c8e4e2cc5bf94656e979ed629b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9dc42645b503479257f220db42a4c00">getInitPhiReg</a> (MachineInstr &amp;Phi, MachineBasicBlock *LoopBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the Phi register value that comes from the incoming block. <a href="#ac9dc42645b503479257f220db42a4c00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3338cf03496688897abc2cc959bf9f17">getLoopPhiReg</a> (MachineInstr &amp;Phi, MachineBasicBlock *LoopBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the Phi register value that comes the loop block. <a href="#a3338cf03496688897abc2cc959bf9f17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae6899676da32051a20f083232f1020">replaceRegUsesAfterLoop</a> (unsigned FromReg, unsigned ToReg, MachineBasicBlock *MBB, MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all uses of FromReg that appear outside the specified basic block with ToReg. <a href="#adae6899676da32051a20f083232f1020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac798656b15d5b309da9e0cf04880d2d6">hasUseAfterLoop</a> (unsigned Reg, MachineBasicBlock *BB, MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the register has a use that occurs outside the specified loop. <a href="#ac798656b15d5b309da9e0cf04880d2d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e01d665bfe75348712ab437ccd8947">removePhis</a> (MachineBasicBlock *BB, MachineBasicBlock *Incoming)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the incoming block from the Phis in a basic block. <a href="#a17e01d665bfe75348712ab437ccd8947">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a087b8382e9e76fa52c0c473b14f7d37d">createDedicatedExit</a> (MachineBasicBlock *Loop, MachineBasicBlock *Exit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a dedicated exit for <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>. <a href="#a087b8382e9e76fa52c0c473b14f7d37d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705be3f7ea0c2050a03f93ea0d51b3fb">getLoopPhiUser</a> (Register Reg, MachineBasicBlock *Loop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a phi if Reg is referenced by the phi. <a href="#a705be3f7ea0c2050a03f93ea0d51b3fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a15cbd1c12c2a4320cc6e9d04d9a8a">replacePhiSrc</a> (MachineInstr &amp;Phi, Register OrigReg, Register NewReg, MachineBasicBlock *NewMBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1ec89e71fd305c8a25e468cf1ab2392">INITIALIZE_PASS_BEGIN</a> (ModuloScheduleTest, "modulo-schedule-test", "Modulo Schedule test pass", false, false) INITIALIZE_PASS_END(ModuloScheduleTest</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94d423b2ab5badfb6f0e24e15ab94d04">parseSymbolString</a> (StringRef S, int &amp;Cycle, int &amp;Stage)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0f28ca2890f02709bba618628463af">SwapBranchTargetsMVE</a>("pipeliner-swap-branch-targets-mve", cl::Hidden, cl::init(false), cl::desc("Swap target blocks of a conditional branch for MVE expander"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">modulo schedule</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a106e32122c569cdb42ddf61ecbb0aad1">test</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">modulo schedule Modulo Schedule <a href="#a106e32122c569cdb42ddf61ecbb0aad1">test</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27488fd62a85fc5ec4fd4247f8ec22aa">pass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">modulo schedule Modulo Schedule <a href="#a106e32122c569cdb42ddf61ecbb0aad1">test</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f2eda570dda605b1ffb253c8ea9a98">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"pipeliner"</td>
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

### createDedicatedExit() {#a087b8382e9e76fa52c0c473b14f7d37d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * createDedicatedExit (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Loop, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Exit)</td>
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

<p>Create a dedicated exit for <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>.</p>


<p>Exit is the original exit for <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>. If it is already dedicated exit, return it. Otherwise, insert a new block between them and return the new block.</p>


<p>Definition at line 2136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getInitPhiReg() {#ac9dc42645b503479257f220db42a4c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getInitPhiReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Phi, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LoopBB)</td>
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

<p>Return the Phi register value that comes from the incoming block.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kerneloperandinfo/#a0780dfcb3a517ab51f5f973dae9e1edb">anonymous{ModuloSchedule.cpp}::KernelOperandInfo::KernelOperandInfo</a>.</p>

</div>
</div>

### getLoopPhiReg() {#a3338cf03496688897abc2cc959bf9f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getLoopPhiReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Phi, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * LoopBB)</td>
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

<p>Return the Phi register value that comes the loop block.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### getLoopPhiUser() {#a705be3f7ea0c2050a03f93ea0d51b3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * getLoopPhiUser (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Loop)</td>
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

<p>Return a phi if Reg is referenced by the phi.</p>


<p>canApply() guarantees that at most only one such phi exists.</p>


<p>Definition at line 2381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#ad4cf8c8e4e2cc5bf94656e979ed629b4">getPhiRegs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getPhiRegs() {#ad4cf8c8e4e2cc5bf94656e979ed629b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getPhiRegs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Phi, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Loop, unsigned &amp; InitVal, unsigned &amp; LoopVal)</td>
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

<p>Return the register values for the operands of a Phi instruction.</p>


<p>This function assume the instruction is a Phi.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### hasUseAfterLoop() {#ac798656b15d5b309da9e0cf04880d2d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasUseAfterLoop (unsigned Reg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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

<p>Return true if the register has a use that occurs outside the specified loop.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#ae1ec89e71fd305c8a25e468cf1ab2392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (ModuloScheduleTest, "modulo-schedule-test", "Modulo Schedule <a href="#a106e32122c569cdb42ddf61ecbb0aad1">test</a> pass", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2793 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### parseSymbolString() {#a94d423b2ab5badfb6f0e24e15ab94d04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseSymbolString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, int &amp; Cycle, int &amp; Stage)</td>
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



<p>Definition at line 2811 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest/#aff71500f971dc1f796d293a1450dc6b0">anonymous{ModuloSchedule.cpp}::ModuloScheduleTest::runOnLoop</a>.</p>

</div>
</div>

### removePhis() {#a17e01d665bfe75348712ab437ccd8947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void removePhis (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Incoming)</td>
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

<p>Remove the incoming block from the Phis in a basic block.</p>

<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### replacePhiSrc() {#a54a15cbd1c12c2a4320cc6e9d04d9a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replacePhiSrc (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Phi, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OrigReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewMBB)</td>
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



<p>Definition at line 2467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### replaceRegUsesAfterLoop() {#adae6899676da32051a20f083232f1020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceRegUsesAfterLoop (unsigned FromReg, unsigned ToReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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

<p>Replace all uses of FromReg that appear outside the specified basic block with ToReg.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#a34f2eda570dda605b1ffb253c8ea9a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">modulo schedule Modulo Schedule test false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2798 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### pass {#a27488fd62a85fc5ec4fd4247f8ec22aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">modulo schedule Modulo Schedule test pass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2798 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### SwapBranchTargetsMVE {#abc0f28ca2890f02709bba618628463af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SwapBranchTargetsMVE("pipeliner-swap-branch-targets-mve", cl::Hidden, cl::init(false), cl::desc("Swap target blocks of a conditional branch for MVE expander"))</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### test {#a106e32122c569cdb42ddf61ecbb0aad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">modulo schedule test</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2797 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#ae4e093eb8f2823c4ec033c43d0d1e316">llvm::SmallBitVector::anyCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a716b165edca27031ffb7a20ea48e41e3">llvm::GCNSubtarget::initializeSubtargetDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a6fdba831dfffefd06bd242697b32ff72">llvm::PPCRegisterInfo::isCallerPreservedPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcinstprinter-cpp/#aad70fb95e1855cf69dfefcf98e2d5e8b">matchAliasCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a626851f9ade8d8e3c2f7cde2ab1c67c8">llvm::SmallBitVector::operator&amp;=</a>, <a href="/web-llvm/docs/api/classes/llvm/bitset/#a3b6d2aeb1ac8efb7625ffdd785d4c5be">llvm::Bitset&lt; AEK_NUM_EXTENSIONS &gt;::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#ab060954a64e3cc74a090baf475007883">llvm::FeatureBitset::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/zip-longest-iterator/#aa127698d88fb1ebfcdfd89bdbefbfd74">llvm::detail::zip_longest_iterator&lt; decltype(adl_begin(std::declval&lt; Args &gt;()))... &gt;::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#af69725ffe3f92d550e8b98f8712f3afc">llvm::SmallBitVector::operator^=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#adf37f317affdd5c72ad07e1ca26e88b0">llvm::SmallBitVector::operator|=</a>, <a href="/web-llvm/docs/api/classes/llvm/coalescingbitvector/#a01f3632c0200ff6d2cd9e1c41fb28884">llvm::CoalescingBitVector&lt; uint64_t &gt;::set</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a22744e70f0f3faf295475ef8cfe92581">llvm::SmallBitVector::test</a>, <a href="/web-llvm/docs/api/classes/llvm/coalescingbitvector/#af020db0e9eae4b30ee1280fc8252c36b">llvm::CoalescingBitVector&lt; uint64_t &gt;::test_and_set</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#a759ce34463b442a0bf75fc75287582bc">llvm::SparseBitVector&lt; 128 &gt;::test_and_set</a> and <a href="/web-llvm/docs/api/structs/llvm/sparsebitvectorelement/#a928996e4af50f5b8cc419e17a94346ce">llvm::SparseBitVectorElement&lt; ElementSize &gt;::test_and_set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"pipeliner"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
