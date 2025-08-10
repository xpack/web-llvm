---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/dfapacketizer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DFAPacketizer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">llvm/CodeGen/DFAPacketizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">llvm/CodeGen/MachineInstrBundle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">llvm/CodeGen/ScheduleDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;iterator&gt;
#include &lt;memory&gt;
#include &lt;vector&gt;
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49346b1c8b35e7fcccd41b3356ae37e9">InstrLimit</a>("dfa-instr-limit", cl::Hidden, cl::init(0), cl::desc("If present, stops packetizing after N instructions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc16edf21eddec420cd4b27adb3111c6">InstrCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"packets"</td>
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

## Variables

### InstrCount {#acc16edf21eddec420cd4b27adb3111c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned InstrCount = 0</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a6396da6d0b65cef8693b0aedd06f31e3">llvm::SystemZTTIImpl::adjustInliningThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#ac20133598c564acc81e5abadc5a1d637">countMBBInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a0892015643ec782f2fce58af100fbd6e">llvm::MachineFunction::getInstructionCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/#acd5b92b97f3839e8483329915a2bd8a9">llvm::MachineTraceMetrics::getResources</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a579d453037e2211a02d8f50a736eff46">llvm::PMDataManager::initSizeRemarkInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#acfb2315913d694fb3f1144279ab75a85">llvm::VLIWPacketizerList::PacketizeMIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoter/#aba67c0c1aba6c8fcf674792830b73704">anonymous{InstrProfiling.cpp}::PGOCounterPromoter::run</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a0dec4e6b40dec12d8c6a17040ee73021">llvm::FPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a3255b0b3ab79ad0d1b93ce3da675f240">llvm::LPPassManager::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a15f0d5cca56f2c4cc4f59bc85803233a">anonymous{LegacyPassManager.cpp}::MPPassManager::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a4450410892c5617bf65b229c3ecc2132">llvm::SchedDFSResult::SchedDFSImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a> and <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#a19e83509e45ee65e4495de5a3ed3d44a">llvm::SchedDFSImpl::visitPostorderNode</a>.</p>

</div>
</div>

### InstrLimit {#a49346b1c8b35e7fcccd41b3356ae37e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; InstrLimit("dfa-instr-limit", cl::Hidden, cl::init(0), cl::desc("If present, stops packetizing after N instructions"))</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a989e26280ba069ba20dd83144c3bd31a">findSurvivorBackwards</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#acfb2315913d694fb3f1144279ab75a85">llvm::VLIWPacketizerList::PacketizeMIs</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"packets"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp">DFAPacketizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
