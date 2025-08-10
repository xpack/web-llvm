---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/regallocbasic-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `RegAllocBasic.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/allocationorder-h">AllocationOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbase-h">RegAllocBase.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/calcspillweights-h">llvm/CodeGen/CalcSpillWeights.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livedebugvariables-h">llvm/CodeGen/LiveDebugVariables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervals-h">llvm/CodeGen/LiveIntervals.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">llvm/CodeGen/LiveRangeEdit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveregmatrix-h">llvm/CodeGen/LiveRegMatrix.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livestacks-h">llvm/CodeGen/LiveStacks.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">llvm/CodeGen/RegAllocRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spiller-h">llvm/CodeGen/Spiller.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">llvm/CodeGen/VirtRegMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;queue&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-regallocbasic-cpp-">anonymous{RegAllocBasic.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-regallocbasic-cpp-/compspillweight">CompSpillWeight</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic">RABasic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic">RABasic</a> provides a minimal implementation of the basic register allocation algorithm. <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d002c2a57c5f40bc24a769615f7319">INITIALIZE_PASS_BEGIN</a> (RABasic, "regallocbasic", "Basic Register Allocator", false, false) INITIALIZE_PASS_END(RABasic</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/registerregalloc">RegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6bcbfd470f335c8a006b2142da21bdd">basicRegAlloc</a>("basic", "basic register allocator", createBasicRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4618c0ee4617c528f22034b9bfb601c4">regallocbasic</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Basic <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Basic <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fd87a32b3a158abc6c784f97b981819">false</a></td>
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

### INITIALIZE\_PASS\_BEGIN() {#a37d002c2a57c5f40bc24a769615f7319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (RABasic, "regallocbasic", "Basic <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Allocator", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp">RegAllocBasic.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Allocator {#ad5d00e1d77644d95847b9bf8da12b759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Basic Register Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp">RegAllocBasic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recycler/#a87901daa616a2345b788a8d65e5f298b">llvm::Recycler&lt; T, Size, Align &gt;::Allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/#a218a988783b4829bf810f68bd0645bb3">llvm::ArrayRecycler&lt; MachineOperand &gt;::Capacity&lt; MachineOperand &gt;::allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/aggregatevalueexpression/#ae7aaabf0b26f785082c96762c2829874">llvm::GVNExpression::AggregateValueExpression::allocateIntOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#a1baacd54f9aea5a21f08d869810335a8">llvm::GVNExpression::BasicExpression::allocateOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapentrybase/#ad02f1e31d20dcd30fca53cf59db4e00d">llvm::StringMapEntryBase::allocateWithKey</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a8b3b31f7a0613368205a3384ea61c85c">llvm::ARMFunctionInfo::ARMFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae7eb95d6c78b269fe03ed9c78cf2c33f">llvm::LiveRange::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#aa97f1b8aea425f7d0284ae828a286e59">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::BumpPtrAllocatorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/#ab9b0fb1cc4d9ce7997a79e3976f6e772">llvm::ArrayRecycler&lt; MachineOperand &gt;::Capacity&lt; MachineOperand &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/recycler/#a1703e705b5efd7e581a499c4cea00b22">llvm::Recycler&lt; T, Size, Align &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmachinefunctioninfo/#aafba9dcb90de37017f086a718e820f76">llvm::AVRMachineFunctionInfo::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymachinefunctioninfo/#a4e4c9f1b400c8093626e45555b9299cd">llvm::CSKYMachineFunctionInfo::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmachinefunctioninfo/#a80b082e93a58b99564ad18e88ac8a83a">llvm::LoongArchMachineFunctionInfo::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#a83e7607428ae730737085ad37ffd6365">llvm::MachineFunctionInfo::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxmachinefunctioninfo/#ae205e0e0ae07b83425271d046b65f15b">llvm::NVPTXMachineFunctionInfo::clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/msfbuilder-cpp/#a39370f41a63dc06ba5dc36059e555bc2">commitFpm</a>, <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a40ef749f57b30897cbc9ac66edeae908">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ac66731b70af2ad5aded1ce13a20acb29">llvm::StringRef::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/scopedhashtableval/#a6d22d2a91de38c04fe692f57ed5aba3e">llvm::ScopedHashTableVal&lt; K, V &gt;::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtableinfobyptr/#a3a4f4feeaa7367627785fa335b336c56">llvm::ConcurrentHashTableInfoByPtr&lt; KeyTy, KeyDataTy, AllocatorTy &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody/#ad5911f089676e212db39133a0bba14e8">llvm::dwarf_linker::parallel::TypeEntryBody::create</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentryinfo/#a366b675a6f464efba4fba1005dd2b2c5">llvm::dwarf_linker::parallel::TypeEntryInfo::create</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/stringpoolentryinfo/#a8874c3ab601219c01d4343c006aed07c">llvm::dwarf_linker::StringPoolEntryInfo::create</a>, <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#a06ad8b2e5a8e3c0f81f05c7870fb3b23">llvm::MachineFunctionInfo::create</a>, <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#ad546ae797a07bdd23b9480f71dabf26b">llvm::MachineFunctionInfo::create</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetmachine/#ab1f583a3705f9fc96d9849dd280ff910">llvm::AVRTargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33f0027ccb45dd6c9aab3966c13b02d3">llvm::TargetMachine::createMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#af6fb03322f7b38d6e815343732497798">llvm::LiveInterval::createSubRange</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a8104005914e3dfed73608d0d8961b822">llvm::LiveInterval::createSubRangeFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/scopedhashtableval/#afa142de6353eb00dc802a4fdaa752ac8">llvm::ScopedHashTableVal&lt; K, V &gt;::Destroy</a>, <a href="/web-llvm/docs/api/classes/llvm/dieinlinestring/#adeccd8def277aff79dd9272c0d421196">llvm::DIEInlineString::DIEInlineString</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a3d54b859f7cec2b9d7e0e6a06b2f81ad">llvm::LiveRange::LiveRange</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#a60bef7f4a836cd97f9704940f259a6ae">llvm::LiveRegMatrix::LiveRegMatrixAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/nativesession-cpp/#ae1d1df29b280e901fe36cd22e7072f95">loadPdbFile</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/allocator-h/#a4ce943383950027ce02406cf66bb9a12">operator new</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/recyclingallocator-h/#adb9ea5e525d426a0a46be17f04de48a5">operator new</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a4f0f0772d897594cda8b20cca33028b3">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange/#af45ba13fe28f95278e407bf423f3d3c7">llvm::LiveInterval::SubRange::SubRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a7cc86b574116e1475520ba834befd71d">toDebugS</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeentrybody/#a95c255d41a30a621f1339a9736b2b501">llvm::dwarf_linker::parallel::TypeEntryBody::TypeEntryBody</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a2f04cf9234fce5da584b1b69d9c74a56">llvm::X86MachineFunctionInfo::X86MachineFunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a1b9ef8f0598f58cb90b889887fa11bce">llvm::WebAssemblyFunctionInfo::~WebAssemblyFunctionInfo</a>.</p>

</div>
</div>

### basicRegAlloc {#af6bcbfd470f335c8a006b2142da21bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRegAlloc basicRegAlloc("basic", "basic register allocator", createBasicRegisterAllocator)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp">RegAllocBasic.cpp</a>.</p>

</div>
</div>

### false {#a4fd87a32b3a158abc6c784f97b981819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Basic Register false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp">RegAllocBasic.cpp</a>.</p>

</div>
</div>

### regallocbasic {#a4618c0ee4617c528f22034b9bfb601c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">regallocbasic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp">RegAllocBasic.cpp</a>.</p>

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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp">RegAllocBasic.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
