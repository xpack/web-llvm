---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WaitcntBrackets` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346ebb0249f57a1f637b365cf0d250c0">WaitcntBrackets</a> (const GCNSubtarget *SubTarget, InstCounterType MaxCounter, HardwareLimits Limits, RegisterEncoding Encoding, const unsigned *WaitEventMaskForInst, InstCounterType SmemAccessCounter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f5bc3acdaa4142d05719b6f2e1f081">getWaitCountMax</a> (InstCounterType T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51971ae9582c2d884bc84eef8498e243">getScoreLB</a> (InstCounterType T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1782f9a649439a5509201c2b1a5d5374">getScoreUB</a> (InstCounterType T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be60a3df71875c3240619489d10ec4f">getScoreRange</a> (InstCounterType T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6cd92b8b96ec1c43da17757bb46b24c">getRegScore</a> (int GprNo, InstCounterType T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae20faa6f3466c999ae960d1748027d73">merge</a> (const WaitcntBrackets &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the pending events and associater score brackets of <span class="doxyComputerOutput">Other</span> into this brackets status. <a href="#ae20faa6f3466c999ae960d1748027d73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2a0d0a57d96de39f44474a411f386d85">RegInterval</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690f39ef8620b9d57557d0cc194b3098">getRegInterval</a> (const MachineInstr *MI, const MachineRegisterInfo *MRI, const SIRegisterInfo *TRI, const MachineOperand &amp;Op) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80c6d7dc16d141e2688dcbbda2aa84df">counterOutOfOrder</a> (InstCounterType T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812aeb1ae1957923c10677d13d53d98f">simplifyWaitcnt</a> (AMDGPU::Waitcnt &amp;Wait) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify the waitcnt, in the sense of removing redundant counts, and return whether a waitcnt instruction is needed at all. <a href="#a812aeb1ae1957923c10677d13d53d98f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e0e3bf4a61f503a544ed56ee4a87e24">simplifyWaitcnt</a> (InstCounterType T, unsigned &amp;Count) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285b6a653ad2b8ffe32d2ba0c4a66038">determineWait</a> (InstCounterType T, RegInterval Interval, AMDGPU::Waitcnt &amp;Wait) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3523e089c2538f750cc2494c9f06a5d0">determineWait</a> (InstCounterType T, int RegNo, AMDGPU::Waitcnt &amp;Wait) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e968fc970599ceab59ecb968132e6d0">applyWaitcnt</a> (const AMDGPU::Waitcnt &amp;Wait)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825716f19fa85f96f4a9d4775f97da96">applyWaitcnt</a> (InstCounterType T, unsigned Count)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed39bc406ed2e03670a0ed9abd45145c">updateByEvent</a> (const SIInstrInfo *TII, const SIRegisterInfo *TRI, const MachineRegisterInfo *MRI, WaitEventType E, MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6311a87d3c8326d8c02a970c975c29f">hasPendingEvent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0087f24c1d72011fa46413e766d33e7d">hasPendingEvent</a> (WaitEventType E) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a536e1f675a18d61306db72cb494046f2">hasPendingEvent</a> (InstCounterType T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53fe20c17ca369081fdbf823480311b9">hasMixedPendingEvents</a> (InstCounterType T) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59c03636c9f9e9a34318f2b412bd5bb6">hasPendingFlat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb50d291f99656392690a84ac477a694">setPendingFlat</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7fc2251e1f67873a5824fd2d8c7dec1">hasOtherPendingVmemTypes</a> (RegInterval Interval, VmemType V) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19573a17312548294a35f19a0f8dde6b">clearVgprVmemTypes</a> (RegInterval Interval)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9feba9865c5cd3ad4186dccfb4e44c6c">setStateOnFunctionEntryOrReturn</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc04e6195d6a932c4b0a17d42b04023d">getLDSDMAStores</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4156a3a70e54022e727de27e8ccb17b">print</a> (raw_ostream &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045ad30ab1419840103a28ce5c6d5eb2">dump</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef2fa76388beb3e270648149725935e">setScoreLB</a> (InstCounterType T, unsigned Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8907bd66adcd9a78b7c017f15b8e658f">setScoreUB</a> (InstCounterType T, unsigned Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965a0dba4a447243fe3ff789c57f2a44">setRegScore</a> (int GprNo, InstCounterType T, unsigned Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55eaa1b09ef5bc1508f824d020bb8ab">setScoreByInterval</a> (RegInterval Interval, InstCounterType CntTy, unsigned Score)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5a6ab55a47594875099457a0c56bf74">setScoreByOperand</a> (const MachineInstr *MI, const SIRegisterInfo *TRI, const MachineRegisterInfo *MRI, const MachineOperand &amp;Op, InstCounterType CntTy, unsigned Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1f4335da188f6689b691ee171be4e2">ST</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca9c2fc52fc9e4c133fb9cb1de1bec8f">MaxCounter</a> = <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bac084d4a4136b25a86b0d2ae3b17f94c9">NUM_EXTENDED_INST_CNTS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits">HardwareLimits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c710aa72612bbfde9d9830a6fe092a5">Limits</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/registerencoding">RegisterEncoding</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad112a4e40f6282bee930c3a8ce010f70">Encoding</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5861829b573b1484ba3b33e8bfe10885">WaitEventMaskForInst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1acd2895b553e201e40e5a1afe77c8f">SmemAccessCounter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaab0a88fbae2fa061b1740c2315a06f">ScoreLBs</a>[NUM_INST_CNTS] = {0}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0108488d0f3045e0d49d93e6adec0d">ScoreUBs</a>[NUM_INST_CNTS] = {0}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7537c0bac09eefd2e06483c8957e2a80">PendingEvents</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76fac31abb86b4665d6148ffc2d3e0b5">LastFlat</a>[NUM_INST_CNTS] = {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2260bbb65d20cca28a8f69dd3b9aef">VgprUB</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728e7f258209e2b547b0332e821a75bb">SgprUB</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614fbf5de5686a5fc2060fb29002114e">VgprScores</a>[NUM_INST_CNTS][NUM_ALL_VGPRS] = {{0}}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a8d6c4194b803a858ccda203c7f745">SgprScores</a>[SQ_MAX_PGM_SGPRS] = {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93fb9752e03ff9ee41ae60b4f9686e6a">VgprVmemTypes</a>[NUM_ALL_VGPRS] = {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa4fa3be5a7c2744fdeb5ec65683600936">NUM_EXTRA_VGPRS</a> - 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7787ee8903f2cfeb7566b1a933fb9fd">LDSDMAStores</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8626ffdfaf566deaa4f9bccd2dd7a51">mergeScore</a> (const MergeInfo &amp;M, unsigned &amp;Score, unsigned OtherScore)</td>
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


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WaitcntBrackets() {#a346ebb0249f57a1f637b365cf0d250c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::WaitcntBrackets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> * SubTarget, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> MaxCounter, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits">HardwareLimits</a> Limits, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/registerencoding">RegisterEncoding</a> Encoding, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned * WaitEventMaskForInst, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> SmemAccessCounter)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="#ae20faa6f3466c999ae960d1748027d73">merge</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyWaitcnt() {#a0e968fc970599ceab59ecb968132e6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::applyWaitcnt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> &amp; Wait)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="#a0e968fc970599ceab59ecb968132e6d0">applyWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bafe2ec1259d862907bc38ee5058f82dd0">anonymous{SIInsertWaitcnts.cpp}::KM_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba0c4deee3d74fa3bd8a894f25581de266">anonymous{SIInsertWaitcnts.cpp}::STORE_CNT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="#a0e968fc970599ceab59ecb968132e6d0">applyWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aba82e76518953661f6dcb009c73e1a1f">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcnt</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### applyWaitcnt() {#a825716f19fa85f96f4a9d4775f97da96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::applyWaitcnt (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T, unsigned Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a80c6d7dc16d141e2688dcbbda2aa84df">counterOutOfOrder</a>, <a href="#a51971ae9582c2d884bc84eef8498e243">getScoreLB</a> and <a href="#a1782f9a649439a5509201c2b1a5d5374">getScoreUB</a>.</p>

</div>
</div>

### clearVgprVmemTypes() {#a19573a17312548294a35f19a0f8dde6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::clearVgprVmemTypes (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2a0d0a57d96de39f44474a411f386d85">RegInterval</a> Interval)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa813511b813d8f33c55787021db83c67b">anonymous{SIInsertWaitcnts.cpp}::NUM_ALL_VGPRS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a8a42c531875f7db92f2c697b823654b5">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcntInstBefore</a>.</p>

</div>
</div>

### counterOutOfOrder() {#a80c6d7dc16d141e2688dcbbda2aa84df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WaitcntBrackets::counterOutOfOrder (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="#a53fe20c17ca369081fdbf823480311b9">hasMixedPendingEvents</a>, <a href="#ad6311a87d3c8326d8c02a970c975c29f">hasPendingEvent</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daaf3cac1cd357193995b108d6d73781a32">anonymous{SIInsertWaitcnts.cpp}::SMEM_ACCESS</a>.</p>


<p>Referenced by <a href="#a825716f19fa85f96f4a9d4775f97da96">applyWaitcnt</a> and <a href="#a285b6a653ad2b8ffe32d2ba0c4a66038">determineWait</a>.</p>

</div>
</div>

### determineWait() {#a285b6a653ad2b8ffe32d2ba0c4a66038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::determineWait (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2a0d0a57d96de39f44474a411f386d85">RegInterval</a> Interval, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> &amp; Wait)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a35d2a37cdf3978760d16a64e0b573236">anonymous{SIInsertWaitcnts.cpp}::addWait</a>, <a href="#a80c6d7dc16d141e2688dcbbda2aa84df">counterOutOfOrder</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="#ad6cd92b8b96ec1c43da17757bb46b24c">getRegScore</a>, <a href="#a51971ae9582c2d884bc84eef8498e243">getScoreLB</a>, <a href="#a1782f9a649439a5509201c2b1a5d5374">getScoreUB</a>, <a href="#aa2f5bc3acdaa4142d05719b6f2e1f081">getWaitCountMax</a>, <a href="#a59c03636c9f9e9a34318f2b412bd5bb6">hasPendingFlat</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>


<p>Referenced by <a href="#a3523e089c2538f750cc2494c9f06a5d0">determineWait</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a8a42c531875f7db92f2c697b823654b5">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcntInstBefore</a>.</p>

</div>
</div>

### determineWait() {#a3523e089c2538f750cc2494c9f06a5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::determineWait (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T, int RegNo, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> &amp; Wait)</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="#a285b6a653ad2b8ffe32d2ba0c4a66038">determineWait</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>

</div>
</div>

### dump() {#a045ad30ab1419840103a28ce5c6d5eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::dump ()</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>.</p>

</div>
</div>

### getLDSDMAStores() {#abc04e6195d6a932c4b0a17d42b04023d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const MachineInstr * &gt; anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getLDSDMAStores ()</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a8a42c531875f7db92f2c697b823654b5">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcntInstBefore</a>.</p>

</div>
</div>

### getRegInterval() {#a690f39ef8620b9d57557d0cc194b3098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegInterval WaitcntBrackets::getRegInterval (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa7abf62de8745888264bd875ee49238f0">anonymous{SIInsertWaitcnts.cpp}::AGPR_OFFSET</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a12457438c2b018b673e22e0253e466c4">llvm::AMDGPU::getMCReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa813511b813d8f33c55787021db83c67b">anonymous{SIInsertWaitcnts.cpp}::NUM_ALL_VGPRS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hwencoding/#a7591861bd58475c68c3d9c2d3578daaca965397959a0d6089e58be5b01f6cf095">llvm::AMDGPU::HWEncoding::REG_IDX_MASK</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fabca3e41fab3e1bfd004160c4c334587a">anonymous{SIInsertWaitcnts.cpp}::SQ_MAX_PGM_SGPRS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8faebce3f552a3d4135d06f8f6dcf356ff4">anonymous{SIInsertWaitcnts.cpp}::SQ_MAX_PGM_VGPRS</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a8a42c531875f7db92f2c697b823654b5">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcntInstBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a6b65813ca9867deebf9b395cae8a8c7e">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::shouldFlushVmCnt</a> and <a href="#aed39bc406ed2e03670a0ed9abd45145c">updateByEvent</a>.</p>

</div>
</div>

### getRegScore() {#ad6cd92b8b96ec1c43da17757bb46b24c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getRegScore (int GprNo, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa813511b813d8f33c55787021db83c67b">anonymous{SIInsertWaitcnts.cpp}::NUM_ALL_VGPRS</a>.</p>


<p>Referenced by <a href="#a285b6a653ad2b8ffe32d2ba0c4a66038">determineWait</a>, <a href="#aa4156a3a70e54022e727de27e8ccb17b">print</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a6b65813ca9867deebf9b395cae8a8c7e">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::shouldFlushVmCnt</a>.</p>

</div>
</div>

### getScoreLB() {#a51971ae9582c2d884bc84eef8498e243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getScoreLB (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7baba718cf45e306a2491c209604bd44763">anonymous{SIInsertWaitcnts.cpp}::NUM_INST_CNTS</a>.</p>


<p>Referenced by <a href="#a825716f19fa85f96f4a9d4775f97da96">applyWaitcnt</a>, <a href="#a285b6a653ad2b8ffe32d2ba0c4a66038">determineWait</a>, <a href="#a0be60a3df71875c3240619489d10ec4f">getScoreRange</a>, <a href="#aa4156a3a70e54022e727de27e8ccb17b">print</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a6b65813ca9867deebf9b395cae8a8c7e">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::shouldFlushVmCnt</a>.</p>

</div>
</div>

### getScoreRange() {#a0be60a3df71875c3240619489d10ec4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getScoreRange (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="#a51971ae9582c2d884bc84eef8498e243">getScoreLB</a> and <a href="#a1782f9a649439a5509201c2b1a5d5374">getScoreUB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a8a42c531875f7db92f2c697b823654b5">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcntInstBefore</a>, <a href="#a536e1f675a18d61306db72cb494046f2">hasPendingEvent</a>, <a href="#aa4156a3a70e54022e727de27e8ccb17b">print</a> and <a href="#a1e0e3bf4a61f503a544ed56ee4a87e24">simplifyWaitcnt</a>.</p>

</div>
</div>

### getScoreUB() {#a1782f9a649439a5509201c2b1a5d5374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getScoreUB (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7baba718cf45e306a2491c209604bd44763">anonymous{SIInsertWaitcnts.cpp}::NUM_INST_CNTS</a>.</p>


<p>Referenced by <a href="#a825716f19fa85f96f4a9d4775f97da96">applyWaitcnt</a>, <a href="#a285b6a653ad2b8ffe32d2ba0c4a66038">determineWait</a>, <a href="#a0be60a3df71875c3240619489d10ec4f">getScoreRange</a>, <a href="#a9feba9865c5cd3ad4186dccfb4e44c6c">setStateOnFunctionEntryOrReturn</a> and <a href="#aed39bc406ed2e03670a0ed9abd45145c">updateByEvent</a>.</p>

</div>
</div>

### getWaitCountMax() {#aa2f5bc3acdaa4142d05719b6f2e1f081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getWaitCountMax (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bafe2ec1259d862907bc38ee5058f82dd0">anonymous{SIInsertWaitcnts.cpp}::KM_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba0c4deee3d74fa3bd8a894f25581de266">anonymous{SIInsertWaitcnts.cpp}::STORE_CNT</a>.</p>


<p>Referenced by <a href="#a285b6a653ad2b8ffe32d2ba0c4a66038">determineWait</a> and <a href="#a9feba9865c5cd3ad4186dccfb4e44c6c">setStateOnFunctionEntryOrReturn</a>.</p>

</div>
</div>

### hasMixedPendingEvents() {#a53fe20c17ca369081fdbf823480311b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasMixedPendingEvents (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Reference <a href="#ad6311a87d3c8326d8c02a970c975c29f">hasPendingEvent</a>.</p>


<p>Referenced by <a href="#a80c6d7dc16d141e2688dcbbda2aa84df">counterOutOfOrder</a>.</p>

</div>
</div>

### hasOtherPendingVmemTypes() {#ae7fc2251e1f67873a5824fd2d8c7dec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasOtherPendingVmemTypes (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2a0d0a57d96de39f44474a411f386d85">RegInterval</a> Interval, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7e0c506d37a9a462f9eece012cefae7f">VmemType</a> V)</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa813511b813d8f33c55787021db83c67b">anonymous{SIInsertWaitcnts.cpp}::NUM_ALL_VGPRS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a8a42c531875f7db92f2c697b823654b5">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcntInstBefore</a>.</p>

</div>
</div>

### hasPendingEvent() {#ad6311a87d3c8326d8c02a970c975c29f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasPendingEvent ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="#a80c6d7dc16d141e2688dcbbda2aa84df">counterOutOfOrder</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a8a42c531875f7db92f2c697b823654b5">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcntInstBefore</a>, <a href="#a53fe20c17ca369081fdbf823480311b9">hasMixedPendingEvents</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>.</p>

</div>
</div>

### hasPendingEvent() {#a0087f24c1d72011fa46413e766d33e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasPendingEvent (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86da">WaitEventType</a> E)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### hasPendingEvent() {#a536e1f675a18d61306db72cb494046f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasPendingEvent (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T)</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0be60a3df71875c3240619489d10ec4f">getScoreRange</a>.</p>

</div>
</div>

### hasPendingFlat() {#a59c03636c9f9e9a34318f2b412bd5bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasPendingFlat ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>.</p>


<p>Referenced by <a href="#a285b6a653ad2b8ffe32d2ba0c4a66038">determineWait</a>.</p>

</div>
</div>

### merge() {#ae20faa6f3466c999ae960d1748027d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WaitcntBrackets::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge the pending events and associater score brackets of <span class="doxyComputerOutput">Other</span> into this brackets status.</p>


<p>Returns whether the merge resulted in a change that requires tighter waits (i.e. the merged brackets strictly dominate the original brackets).</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2ef1dff4a80e63ecb924b7b283bf1c34">anonymous{SIInsertWaitcnts.cpp}::inst_counter_types</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#a346ebb0249f57a1f637b365cf0d250c0">WaitcntBrackets</a>.</p>

</div>
</div>

### print() {#aa4156a3a70e54022e727de27e8ccb17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa082e837576678f09ce5d8bf2b19d5e58">anonymous{SIInsertWaitcnts.cpp}::EXTRA_VGPR_LDS</a>, <a href="#ad6cd92b8b96ec1c43da17757bb46b24c">getRegScore</a>, <a href="#a51971ae9582c2d884bc84eef8498e243">getScoreLB</a>, <a href="#a0be60a3df71875c3240619489d10ec4f">getScoreRange</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2ef1dff4a80e63ecb924b7b283bf1c34">anonymous{SIInsertWaitcnts.cpp}::inst_counter_types</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bafe2ec1259d862907bc38ee5058f82dd0">anonymous{SIInsertWaitcnts.cpp}::KM_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa813511b813d8f33c55787021db83c67b">anonymous{SIInsertWaitcnts.cpp}::NUM_ALL_VGPRS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8faebce3f552a3d4135d06f8f6dcf356ff4">anonymous{SIInsertWaitcnts.cpp}::SQ_MAX_PGM_VGPRS</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba0c4deee3d74fa3bd8a894f25581de266">anonymous{SIInsertWaitcnts.cpp}::STORE_CNT</a>.</p>

</div>
</div>

### setPendingFlat() {#abb50d291f99656392690a84ac477a694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::setPendingFlat ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### setStateOnFunctionEntryOrReturn() {#a9feba9865c5cd3ad4186dccfb4e44c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::setStateOnFunctionEntryOrReturn ()</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="#a1782f9a649439a5509201c2b1a5d5374">getScoreUB</a>, <a href="#aa2f5bc3acdaa4142d05719b6f2e1f081">getWaitCountMax</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba0c4deee3d74fa3bd8a894f25581de266">anonymous{SIInsertWaitcnts.cpp}::STORE_CNT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

### simplifyWaitcnt() {#a812aeb1ae1957923c10677d13d53d98f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::simplifyWaitcnt (<a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> &amp; Wait)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simplify the waitcnt, in the sense of removing redundant counts, and return whether a waitcnt instruction is needed at all.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bafe2ec1259d862907bc38ee5058f82dd0">anonymous{SIInsertWaitcnts.cpp}::KM_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a>, <a href="#a812aeb1ae1957923c10677d13d53d98f">simplifyWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba0c4deee3d74fa3bd8a894f25581de266">anonymous{SIInsertWaitcnts.cpp}::STORE_CNT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a8a42c531875f7db92f2c697b823654b5">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcntInstBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a> and <a href="#a812aeb1ae1957923c10677d13d53d98f">simplifyWaitcnt</a>.</p>

</div>
</div>

### simplifyWaitcnt() {#a1e0e3bf4a61f503a544ed56ee4a87e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::simplifyWaitcnt (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T, unsigned &amp; Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="#a0be60a3df71875c3240619489d10ec4f">getScoreRange</a>.</p>

</div>
</div>

### updateByEvent() {#aed39bc406ed2e03670a0ed9abd45145c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::updateByEvent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86da">WaitEventType</a> E, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ade4229c653b0cbcaca057e8af5002783">llvm::MachineInstr::all_defs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3daf8e155bf0aa3e65b5260bfe3698c5">llvm::MachineInstr::all_uses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa3b9fba7fd848bb37e43040b66f6c051">llvm::MachineInstr::defs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a98688c0228b9cce9fde061dfd0ad8ee5">anonymous{SIInsertWaitcnts.cpp}::eventCounter</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa082e837576678f09ce5d8bf2b19d5e58">anonymous{SIInsertWaitcnts.cpp}::EXTRA_VGPR_LDS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a690f39ef8620b9d57557d0cc194b3098">getRegInterval</a>, <a href="#a1782f9a649439a5509201c2b1a5d5374">getScoreUB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ae89cf351b4c02b5f35b361ad6ca79d14">anonymous{SIInsertWaitcnts.cpp}::getVmemType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6c4c2a9d09070e2709f9725a915575e4">llvm::SIInstrInfo::isAtomicRet</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a5d2be32319a4c9ca5a0a37d0e2a3a68b">llvm::SIInstrInfo::isGWS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a17f5d15a7320dec2cfefb6617f711ab7">llvm::MachineInstr::mayLoadOrStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab37075d621acbbfc96ef2662f2e29883">llvm::MachineInstr::memoperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa813511b813d8f33c55787021db83c67b">anonymous{SIInsertWaitcnts.cpp}::NUM_ALL_VGPRS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa4fa3be5a7c2744fdeb5ec65683600936">anonymous{SIInsertWaitcnts.cpp}::NUM_EXTRA_VGPRS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8faebce3f552a3d4135d06f8f6dcf356ff4">anonymous{SIInsertWaitcnts.cpp}::SQ_MAX_PGM_VGPRS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac39e1c7fea00a5f2395927d0891edfce">anonymous{SIInsertWaitcnts.cpp}::updateVMCntOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a3f5e55facd89c7c4e29803a545e13716">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::updateEventWaitcntAfter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setRegScore() {#a965a0dba4a447243fe3ff789c57f2a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::setRegScore (int GprNo, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T, unsigned Val)</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### setScoreByInterval() {#aa55eaa1b09ef5bc1508f824d020bb8ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::setScoreByInterval (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2a0d0a57d96de39f44474a411f386d85">RegInterval</a> Interval, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> CntTy, unsigned Score)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### setScoreByOperand() {#af5a6ab55a47594875099457a0c56bf74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WaitcntBrackets::setScoreByOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> CntTy, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### setScoreLB() {#a7ef2fa76388beb3e270648149725935e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::setScoreLB (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T, unsigned Val)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### setScoreUB() {#a8907bd66adcd9a78b7c017f15b8e658f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::setScoreUB (<a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7b">InstCounterType</a> T, unsigned Val)</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Encoding {#ad112a4e40f6282bee930c3a8ce010f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterEncoding anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::Encoding = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### LastFlat {#a76fac31abb86b4665d6148ffc2d3e0b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::LastFlat[NUM_INST_CNTS] = {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### LDSDMAStores {#ae7787ee8903f2cfeb7566b1a933fb9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const MachineInstr *, NUM_EXTRA_VGPRS - 1&gt; anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::LDSDMAStores</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### Limits {#a7c710aa72612bbfde9d9830a6fe092a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HardwareLimits anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::Limits = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### MaxCounter {#aca9c2fc52fc9e4c133fb9cb1de1bec8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstCounterType anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::MaxCounter = <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bac084d4a4136b25a86b0d2ae3b17f94c9">NUM_EXTENDED_INST_CNTS</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### PendingEvents {#a7537c0bac09eefd2e06483c8957e2a80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::PendingEvents = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### ScoreLBs {#afaab0a88fbae2fa061b1740c2315a06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::ScoreLBs[NUM_INST_CNTS] = {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### ScoreUBs {#a0c0108488d0f3045e0d49d93e6adec0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::ScoreUBs[NUM_INST_CNTS] = {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### SgprScores {#a05a8d6c4194b803a858ccda203c7f745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::SgprScores[SQ_MAX_PGM_SGPRS] = {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### SgprUB {#a728e7f258209e2b547b0332e821a75bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::SgprUB = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### SmemAccessCounter {#af1acd2895b553e201e40e5a1afe77c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstCounterType anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::SmemAccessCounter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### ST {#a2d1f4335da188f6689b691ee171be4e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::ST = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### VgprScores {#a614fbf5de5686a5fc2060fb29002114e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::VgprScores[NUM_INST_CNTS][NUM_ALL_VGPRS] = {{0}}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### VgprUB {#a1c2260bbb65d20cca28a8f69dd3b9aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::VgprUB = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### VgprVmemTypes {#a93fb9752e03ff9ee41ae60b4f9686e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::VgprVmemTypes[NUM_ALL_VGPRS] = {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### WaitEventMaskForInst {#a5861829b573b1484ba3b33e8bfe10885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned* anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::WaitEventMaskForInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### mergeScore() {#aa8626ffdfaf566deaa4f9bccd2dd7a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WaitcntBrackets::mergeScore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MergeInfo &amp; M, unsigned &amp; Score, unsigned OtherScore)</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
