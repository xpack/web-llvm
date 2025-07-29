---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/liveregmatrix-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LiveRegMatrix.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">llvm/CodeGen/LiveRegMatrix.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-h">RegisterCoalescer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">llvm/CodeGen/LiveInterval.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">llvm/CodeGen/LiveIntervalUnion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">llvm/CodeGen/VirtRegMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/lanebitmask-h">llvm/MC/LaneBitmask.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4985ae8422e42b1cda64e15599815e10">STATISTIC</a> (NumAssigned, "Number of registers assigned")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7a0cad16b246de17fa3786423410d91">STATISTIC</a> (NumUnassigned, "Number of registers unassigned")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25c51998eaa90d23fa08def51f03096">INITIALIZE_PASS_BEGIN</a> (LiveRegMatrixWrapperLegacy, "liveregmatrix", "Live Register Matrix", false, false) INITIALIZE_PASS_END(LiveRegMatrixWrapperLegacy</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Callable&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab2ae433d483c154d92c727cf7282996">foreachUnit</a> (const TargetRegisterInfo *TRI, const LiveInterval &amp;VRegInterval, MCRegister PhysReg, Callable Func)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaead1a96b8d70f9d2bd1e465959760d">liveregmatrix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Live <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8989acb71bd355e02bcf3a930b5e54ea">Matrix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Live <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4574a80ae3e35a469bc92018cfbb3516">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"regalloc"</td>
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

### foreachUnit() {#aab2ae433d483c154d92c727cf7282996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Callable&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool foreachUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VRegInterval, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, Callable Func)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#aca181a8107cd511dad6c6627fe9f6fae">llvm::LiveRegMatrix::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ad064f1e4af82a7f4251434afde29b0b5">llvm::LiveRegMatrix::checkInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ad08d47c88b8af3c45df94d19ccc6e679">llvm::LiveRegMatrix::checkRegUnitInterference</a> and <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#a128d0b27fb99ba10fc96a8c526129157">llvm::LiveRegMatrix::unassign</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#ae25c51998eaa90d23fa08def51f03096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/liveregmatrixwrapperlegacy">LiveRegMatrixWrapperLegacy</a>, "liveregmatrix", "Live <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Matrix", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### STATISTIC() {#a4985ae8422e42b1cda64e15599815e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumAssigned, "Number of registers assigned")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ae7a0cad16b246de17fa3786423410d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumUnassigned, "Number of registers unassigned")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/liveregmatrixwrapperlegacy/#ae999ef561f0cf66cb5cec3095bf66b87">llvm::LiveRegMatrixWrapperLegacy::ID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#a4574a80ae3e35a469bc92018cfbb3516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Live Register false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>

</div>
</div>

### liveregmatrix {#adaead1a96b8d70f9d2bd1e465959760d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">liveregmatrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>

</div>
</div>

### Matrix {#a8989acb71bd355e02bcf3a930b5e54ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Live Register Matrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#a7d21d6d08fe746df3e5621b4703523ea">llvm::PBQP::applyR2</a>, <a href="/web-llvm/docs/api/classes/llvm/allocationorder/#a1d17986988f0819f29d78d1be8555c9e">llvm::AllocationOrder::create</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a69138108d0e5888e6cafcdd27d082fc8">llvm::MatrixBuilder::CreateColumnMajorStore</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#ab245615ce0c4feee775f0d793d9ec6ef">llvm::MatrixBuilder::CreateMatrixInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/matrixbuilder/#a5342cc18cecbb68eff164826df1476e0">llvm::MatrixBuilder::CreateMatrixTranspose</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7f5b1f0925dc2dbb62f05681772ca912">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::finalizeLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a69a2253decaa6ee31ae96ec6e0b3de13">llvm::AArch64RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a77b81cc14aafd09d0e380b123cd06d51">llvm::ARMBaseRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a09a1c19b999c807cb52c21541a2c7de4">llvm::PPCRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc99d2835eb4b8cde9e81db9abca597c">llvm::TargetRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a3e33f515d9d731525f0fec52122fcd8c">llvm::TargetRegisterInfo::getRegUnitPressureSets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2689b832f03d85c8c3f2a096b653f75">LowerBITREVERSE</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a4c72146be47366faa66bbe3fa93abf2a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerColumnMajorStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a6fb1dea3dcd9b6517ad7c8a6a7269366">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/sipreallocatewwmregspass/#ae0b2123e3a8afffcdfc0e364d088f39a">llvm::SIPreAllocateWWMRegsPass::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-sipreallocatewwmregs-cpp-/sipreallocatewwmregslegacy/#aab18d5ce221151f612364e18c2fdb47b">anonymous{SIPreAllocateWWMRegs.cpp}::SIPreAllocateWWMRegsLegacy::runOnMachineFunction</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"regalloc"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp">LiveRegMatrix.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
