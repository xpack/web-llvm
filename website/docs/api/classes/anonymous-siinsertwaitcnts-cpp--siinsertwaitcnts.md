---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SIInsertWaitcnts` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86722649a06b625840046a1701025785">SIInsertWaitcnts</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b65813ca9867deebf9b395cae8a8c7e">shouldFlushVmCnt</a> (MachineLoop *ML, WaitcntBrackets &amp;Brackets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b2fd564c6db478ebdc025a9781c7d0">isPreheaderToFlush</a> (MachineBasicBlock &amp;MBB, WaitcntBrackets &amp;ScoreBrackets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b41f307768619a97e70860c9ff562cd">isVMEMOrFlatVMEM</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6a5b3788b7384e1928f2ccd79f26b7">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#aab6a5b3788b7384e1928f2ccd79f26b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab60e5bcbfea5d6f10842af4faa4b92">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a1ab60e5bcbfea5d6f10842af4faa4b92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51964e59ed1cde09d8e6d578e9c46d83">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a51964e59ed1cde09d8e6d578e9c46d83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d57ca6f657dca3fad46758dcd455db0">isForceEmitWaitcnt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a2b453bf3ce25f979403d9d95c7070">setForceEmitWaitcnt</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86da">WaitEventType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d5807670c4c32383f66d0e1df8936e0">getVmemWaitEventType</a> (const MachineInstr &amp;Inst) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1de9db6b5ec43a3d021397cf12dc467">mayAccessVMEMThroughFlat</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d11a157ed918f93d2cf2900bc35472">mayAccessLDSThroughFlat</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16768e1f726fb953877c159ef9a31ea">mayAccessScratchThroughFlat</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a42c531875f7db92f2c697b823654b5">generateWaitcntInstBefore</a> (MachineInstr &amp;MI, WaitcntBrackets &amp;ScoreBrackets, MachineInstr *OldWaitcntInstr, bool FlushVmCnt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate s_waitcnt instruction to be placed before cur_Inst. <a href="#a8a42c531875f7db92f2c697b823654b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba82e76518953661f6dcb009c73e1a1f">generateWaitcnt</a> (AMDGPU::Waitcnt Wait, MachineBasicBlock::instr_iterator It, MachineBasicBlock &amp;Block, WaitcntBrackets &amp;ScoreBrackets, MachineInstr *OldWaitcntInstr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f5e55facd89c7c4e29803a545e13716">updateEventWaitcntAfter</a> (MachineInstr &amp;Inst, WaitcntBrackets *ScoreBrackets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350c647ea2f30d644a78ec7ab9dc9684">insertWaitcntInBlock</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;Block, WaitcntBrackets &amp;ScoreBrackets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6ef52d3b624162a1875ff0835b42b28">ST</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bdb162aed6c88777b4b56bdd6772d47">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e86e4114d24eb946824ba54e75a5a7">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd55c39c70ba15b6114d6c76075acceb">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e1cd2293b83bae8ffa05ea72762809">SLoadAddresses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6a965a7611410b0682c0b328b2968d2">PreheadersToFlush</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d857de994d986f1a74951928484e6b">MLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f900acab8b5bca42efef52754071aca">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a676e53bf212d33c16881aef0a6bb192e">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954a47dac428f85d74827e4c4867321c">SmemAccessCounter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, BlockInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e1da77f91e596472f07d1a1a715ad5">BlockInfos</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8351444c5f8c324d419219230a117231">ForceEmitWaitcnt</a>[NUM_INST_CNTS]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12">WaitcntGeneratorPreGFX12</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b8d61cd3f55701f35a1cd67bfdd7555">WCGPreGFX12</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus">WaitcntGeneratorGFX12Plus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3e6648d84be5dc0588662dc0d662066">WCGGFX12Plus</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgenerator">WaitcntGenerator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ebc17ff484902a9da533e43321b0c5">WCG</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b4bdbc9cee6e008d4ec28aa1d096a4a">ReleaseVGPRInsts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87a901c050f1e940049b116ff7ceba4">MaxCounter</a> = <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba6bce6243a580981ed0a55d0ac3fb5f2c">NUM_NORMAL_INST_CNTS</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4003ab1ea1a7dd8d318409cfb820f3c">ID</a> = 0</td>
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


<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIInsertWaitcnts() {#a86722649a06b625840046a1701025785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::SIInsertWaitcnts ()</td>
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



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="#ab4003ab1ea1a7dd8d318409cfb820f3c">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae1f1b566607514b37834c2667e016954">llvm::createSIInsertWaitcntsPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### generateWaitcnt() {#aba82e76518953661f6dcb009c73e1a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::generateWaitcnt (<a href="/web-llvm/docs/api/structs/llvm/amdgpu/waitcnt">AMDGPU::Waitcnt</a> Wait, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> It, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Block, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> &amp; ScoreBrackets, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OldWaitcntInstr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a0e968fc970599ceab59ecb968132e6d0">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::applyWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a85e762ca75d1db9247a7d659fbf77d2a">llvm::SIInstrInfo::isVINTERP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>


<p>Referenced by <a href="#a8a42c531875f7db92f2c697b823654b5">generateWaitcntInstBefore</a> and <a href="#a350c647ea2f30d644a78ec7ab9dc9684">insertWaitcntInBlock</a>.</p>

</div>
</div>

### generateWaitcntInstBefore() {#a8a42c531875f7db92f2c697b823654b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::generateWaitcntInstBefore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> &amp; ScoreBrackets, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OldWaitcntInstr, bool FlushVmCnt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate s_waitcnt instruction to be placed before cur_Inst.</p>


<p>Instructions of a given type are returned in order, but instructions of different types can complete out of order. We rely on this in-order completion and simply assign a score to the memory access instructions. We keep track of the active "score bracket" to determine if an access of a memory read requires an s_waitcnt and if so what the value of each counter is. The "score bracket" is bound by the lower bound and upper bound scores (*_score_LB and *_score_ub respectively). If FlushVmCnt is true, that means that we want to generate a s_waitcnt to flush the vmcnt counter here.</p>


<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a35d2a37cdf3978760d16a64e0b573236">anonymous{SIInsertWaitcnts.cpp}::addWait</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a5afc28dc25e85e7b88c083ef9fc1e9d3">callWaitsOnFunctionEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a19573a17312548294a35f19a0f8dde6b">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::clearVgprVmemTypes</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a285b6a653ad2b8ffe32d2ba0c4a66038">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::determineWait</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa3d3a2918b4a8d46587a46104973a0fbb">anonymous{SIInsertWaitcnts.cpp}::EXP_GPR_LOCK</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa29adb0a7716bd8776a15d8e48236b226">anonymous{SIInsertWaitcnts.cpp}::EXP_LDS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daac5112e1f3b27e352669978def9632a96">anonymous{SIInsertWaitcnts.cpp}::EXP_PARAM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daad6945119665d190abd3262800abbf1b8">anonymous{SIInsertWaitcnts.cpp}::EXP_POS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fa082e837576678f09ce5d8bf2b19d5e58">anonymous{SIInsertWaitcnts.cpp}::EXTRA_VGPR_LDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#aab5a1fbc9805148012c6021e0370acfe">ForceEmitZeroFlag</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa7cabdbd2bae66ba4d0a4af5e95148024">anonymous{SIInsertWaitcnts.cpp}::GDS_GPR_LOCK</a>, <a href="#aba82e76518953661f6dcb009c73e1a1f">generateWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#abc04e6195d6a932c4b0a17d42b04023d">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getLDSDMAStores</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a690f39ef8620b9d57557d0cc194b3098">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getRegInterval</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a0be60a3df71875c3240619489d10ec4f">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getScoreRange</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ae89cf351b4c02b5f35b361ad6ca79d14">anonymous{SIInsertWaitcnts.cpp}::getVmemType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2afee0105d2e947dda0884cc47a33c93b7">llvm::AMDGPUSubtarget::GFX11</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#ae7fc2251e1f67873a5824fd2d8c7dec1">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasOtherPendingVmemTypes</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#ad6311a87d3c8326d8c02a970c975c29f">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasPendingEvent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#a3a326b706ed4c9caaca05063b47c98dbac1f00b8c9ee08df6cb5378168b3e3353">llvm::AMDGPU::SendMsg::ID_GS_DONE_PreGFX11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#a3a326b706ed4c9caaca05063b47c98dba2725a8fe1793af838f1f598cf482dd94">llvm::AMDGPU::SendMsg::ID_MASK_PreGFX11_</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bafe2ec1259d862907bc38ee5058f82dd0">anonymous{SIInsertWaitcnts.cpp}::KM_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a94ceb20d45e28266a8e3c88177cd5433">readsVCCZ</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daadee683fb94c4b2131a4d3b2cc23c4ea3">anonymous{SIInsertWaitcnts.cpp}::SCRATCH_WRITE_ACCESS</a>, <a href="#a90a2b453bf3ce25f979403d9d95c7070">setForceEmitWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a812aeb1ae1957923c10677d13d53d98f">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::simplifyWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daaf3cac1cd357193995b108d6d73781a32">anonymous{SIInsertWaitcnts.cpp}::SMEM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8faebce3f552a3d4135d06f8f6dcf356ff4">anonymous{SIInsertWaitcnts.cpp}::SQ_MAX_PGM_VGPRS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba0c4deee3d74fa3bd8a894f25581de266">anonymous{SIInsertWaitcnts.cpp}::STORE_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac39e1c7fea00a5f2395927d0891edfce">anonymous{SIInsertWaitcnts.cpp}::updateVMCntOnly</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>


<p>Referenced by <a href="#a350c647ea2f30d644a78ec7ab9dc9684">insertWaitcntInBlock</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a51964e59ed1cde09d8e6d578e9c46d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#aaeddaf79040291b6f3e0db57943aac39">llvm::AnalysisUsage::addUsedIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### getPassName() {#a1ab60e5bcbfea5d6f10842af4faa4b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getPassName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### getVmemWaitEventType() {#a4d5807670c4c32383f66d0e1df8936e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WaitEventType anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::getVmemWaitEventType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst)</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ae89cf351b4c02b5f35b361ad6ca79d14">anonymous{SIInsertWaitcnts.cpp}::getVmemType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#afbb07a5c117ab74c3cd893b82560bb82">llvm::SIInstrInfo::isAtomicNoRet</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adc3333d2d5974f4068df84f8706fc7d2">llvm::SIInstrInfo::isFLAT</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a08b830059090a1bb27b14e1e524fdb46">llvm::SIInstrInfo::isVMEM</a>, <a href="#aa16768e1f726fb953877c159ef9a31ea">mayAccessScratchThroughFlat</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a682028ac4a06c9e3550fa8e6e1909fa9">llvm::MachineInstr::mayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a35927952ceaf2f903e7d3aa920588daf">llvm::SIInstrInfo::mayWriteLDSThroughDMA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7e0c506d37a9a462f9eece012cefae7fad9c26c725e7882a4a53f8490013c2a66">anonymous{SIInsertWaitcnts.cpp}::NUM_VMEM_TYPES</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daadee683fb94c4b2131a4d3b2cc23c4ea3">anonymous{SIInsertWaitcnts.cpp}::SCRATCH_WRITE_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa21de8177a6f3abd11c6c077c5d7ea476">anonymous{SIInsertWaitcnts.cpp}::VMEM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa7d81d39ce1e8450d43d9559acbe42dd1">anonymous{SIInsertWaitcnts.cpp}::VMEM_BVH_READ_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa1d154e87495ad512bb7d4358ae701f5d">anonymous{SIInsertWaitcnts.cpp}::VMEM_READ_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa67397bffb67b25a842216f7d121c4da8">anonymous{SIInsertWaitcnts.cpp}::VMEM_SAMPLER_READ_ACCESS</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa178c35ca811b8695e008c8a293276134">anonymous{SIInsertWaitcnts.cpp}::VMEM_WRITE_ACCESS</a>.</p>


<p>Referenced by <a href="#a3f5e55facd89c7c4e29803a545e13716">updateEventWaitcntAfter</a>.</p>

</div>
</div>

### insertWaitcntInBlock() {#a350c647ea2f30d644a78ec7ab9dc9684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::insertWaitcntInBlock (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; Block, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> &amp; ScoreBrackets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9024bfb74506b66f45d153234a802000">llvm::MachineInstr::definesRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a045ad30ab1419840103a28ce5c6d5eb2">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::dump</a>, <a href="#aba82e76518953661f6dcb009c73e1a1f">generateWaitcnt</a>, <a href="#a8a42c531875f7db92f2c697b823654b5">generateWaitcntInstBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb10ef030fba4ea901518a0c8dbef3e2">llvm::MachineInstr::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#ad6311a87d3c8326d8c02a970c975c29f">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::hasPendingEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6c4c2a9d09070e2709f9725a915575e4">llvm::SIInstrInfo::isAtomicRet</a>, <a href="#a51b2fd564c6db478ebdc025a9781c7d0">isPreheaderToFlush</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a80ca145710cb63f6d1484dacf37a8620">isWaitInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a17f5d15a7320dec2cfefb6617f711ab7">llvm::MachineInstr::mayLoadOrStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab37075d621acbbfc96ef2662f2e29883">llvm::MachineInstr::memoperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab419785650ef9728b5305d220179017c">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a94ceb20d45e28266a8e3c88177cd5433">readsVCCZ</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a812aeb1ae1957923c10677d13d53d98f">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::simplifyWaitcnt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daaf3cac1cd357193995b108d6d73781a32">anonymous{SIInsertWaitcnts.cpp}::SMEM_ACCESS</a>, <a href="#a3f5e55facd89c7c4e29803a545e13716">updateEventWaitcntAfter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa49bfe5e1e40e44e387a5e03c6ca759c5">llvm::Wait</a>.</p>


<p>Referenced by <a href="#aab6a5b3788b7384e1928f2ccd79f26b7">runOnMachineFunction</a>.</p>

</div>
</div>

### isForceEmitWaitcnt() {#a5d57ca6f657dca3fad46758dcd455db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::isForceEmitWaitcnt ()</td>
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



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2ef1dff4a80e63ecb924b7b283bf1c34">anonymous{SIInsertWaitcnts.cpp}::inst_counter_types</a>.</p>

</div>
</div>

### isPreheaderToFlush() {#a51b2fd564c6db478ebdc025a9781c7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::isPreheaderToFlush (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> &amp; ScoreBrackets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a6b65813ca9867deebf9b395cae8a8c7e">shouldFlushVmCnt</a>.</p>


<p>Referenced by <a href="#a350c647ea2f30d644a78ec7ab9dc9684">insertWaitcntInBlock</a>.</p>

</div>
</div>

### isVMEMOrFlatVMEM() {#a3b41f307768619a97e70860c9ff562cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::isVMEMOrFlatVMEM (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adc3333d2d5974f4068df84f8706fc7d2">llvm::SIInstrInfo::isFLAT</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a08b830059090a1bb27b14e1e524fdb46">llvm::SIInstrInfo::isVMEM</a>, <a href="#ac1de9db6b5ec43a3d021397cf12dc467">mayAccessVMEMThroughFlat</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a6b65813ca9867deebf9b395cae8a8c7e">shouldFlushVmCnt</a>.</p>

</div>
</div>

### mayAccessLDSThroughFlat() {#ac5d11a157ed918f93d2cf2900bc35472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::mayAccessLDSThroughFlat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aaa1e27e4fc68e5706a4b7bbaed447c14">llvm::AMDGPUAS::FLAT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a3f5e55facd89c7c4e29803a545e13716">updateEventWaitcntAfter</a>.</p>

</div>
</div>

### mayAccessScratchThroughFlat() {#aa16768e1f726fb953877c159ef9a31ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::mayAccessScratchThroughFlat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a4d5807670c4c32383f66d0e1df8936e0">getVmemWaitEventType</a>.</p>

</div>
</div>

### mayAccessVMEMThroughFlat() {#ac1de9db6b5ec43a3d021397cf12dc467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::mayAccessVMEMThroughFlat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a5b71ba6fa435ec288aba849e113721a7">llvm::AMDGPUAS::REGION_ADDRESS</a>.</p>


<p>Referenced by <a href="#a3b41f307768619a97e70860c9ff562cd">isVMEMOrFlatVMEM</a> and <a href="#a3f5e55facd89c7c4e29803a545e13716">updateEventWaitcntAfter</a>.</p>

</div>
</div>

### runOnMachineFunction() {#aab6a5b3788b7384e1928f2ccd79f26b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits/#ab323633a26ac6647e56edc46d8310e3d">anonymous{SIInsertWaitcnts.cpp}::HardwareLimits::BvhcntMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits/#abd44c347381ea69327ff8cd8f056c769">anonymous{SIInsertWaitcnts.cpp}::HardwareLimits::DscntMax</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a98688c0228b9cce9fde061dfd0ad8ee5">anonymous{SIInsertWaitcnts.cpp}::eventCounter</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits/#aeb499d28e32df55726060e9f373fd92b">anonymous{SIInsertWaitcnts.cpp}::HardwareLimits::ExpcntMax</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#af94c014e968489e96c7d4353a84ad7f5">llvm::Pass::getAnalysisIfAvailable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a942bb5a7eec99886589ccbcec455fe70">llvm::AMDGPU::getBvhcntBitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#afe3ac3f0070302c876643fd5874036fb">llvm::AMDGPU::getDscntBitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa214c98bde27112b9cec6bc4e1dba715">llvm::AMDGPU::getExpcntBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a32384420526a080b93cc98ab5a023001">llvm::GCNSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4c450943f424116a9b6b9a3db451af6c">llvm::AMDGPU::getIsaVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a81bde5d0794bf37b6e8850dca91b8683">llvm::AMDGPU::getKmcntBitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a906595c44094cbae6a0cca1b1a8b1304">llvm::AMDGPU::getLgkmcntBitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af0408612031ad2749dd5aea581b7daec">llvm::AMDGPU::getLoadcntBitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a41a62eaa48728ca1d52dda5d0a9b08c1">llvm::AMDGPU::IsaInfo::getMaxWavesPerEU</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#addd7333a1ddd4f2210a9870f8e2b20b0">llvm::SIInstrInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a69a0855213041f468cf764a613d25d7d">llvm::AMDGPU::getSamplecntBitMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a393b0ad5ab188fc0a3af89ce8daa16e6">llvm::AMDGPU::getStorecntBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a84f97b2884502eab6b0196da9e29e178">llvm::AMDGPU::getVmcntBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/sendmsg/#a3a326b706ed4c9caaca05063b47c98dbaa6cd8fa6c5997ec2807bb22563d7d179">llvm::AMDGPU::SendMsg::ID_DEALLOC_VGPRS_GFX11Plus</a>, <a href="#a350c647ea2f30d644a78ec7ab9dc9684">insertWaitcntInBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a2ef1dff4a80e63ecb924b7b283bf1c34">anonymous{SIInsertWaitcnts.cpp}::inst_counter_types</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a0aac99f8424594e610c451a87044a760">anonymous{SIInsertWaitcnts.cpp}::instrsForExtendedCounterTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#ab37f1839fd82f8b84b7a2ca87b289c46">llvm::AMDGPUMachineFunction::isEntryFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits/#a3b541b77a8c94ac62610873c0080385c">anonymous{SIInsertWaitcnts.cpp}::HardwareLimits::KmcntMax</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits/#a194d12e7a4487e828a4a298fb428a7b1">anonymous{SIInsertWaitcnts.cpp}::HardwareLimits::LoadcntMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bac084d4a4136b25a86b0d2ae3b17f94c9">anonymous{SIInsertWaitcnts.cpp}::NUM_EXTENDED_INST_CNTS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba6bce6243a580981ed0a55d0ac3fb5f2c">anonymous{SIInsertWaitcnts.cpp}::NUM_NORMAL_INST_CNTS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/hwencoding/#a7591861bd58475c68c3d9c2d3578daaca965397959a0d6089e58be5b01f6cf095">llvm::AMDGPU::HWEncoding::REG_IDX_MASK</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits/#ad6eeaa887e352dff65aedfc7c97ddbf0">anonymous{SIInsertWaitcnts.cpp}::HardwareLimits::SamplecntMax</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/registerencoding/#a0c0b3be0e8e8f141c962bcb37438b39a">anonymous{SIInsertWaitcnts.cpp}::RegisterEncoding::SGPR0</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/registerencoding/#ac2e6823524a16bde9f4c951a1f7d6fb9">anonymous{SIInsertWaitcnts.cpp}::RegisterEncoding::SGPRL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daaf3cac1cd357193995b108d6d73781a32">anonymous{SIInsertWaitcnts.cpp}::SMEM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8fabca3e41fab3e1bfd004160c4c334587a">anonymous{SIInsertWaitcnts.cpp}::SQ_MAX_PGM_SGPRS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#ac72c82b6709bc2504686d809d61b5e8faebce3f552a3d4135d06f8f6dcf356ff4">anonymous{SIInsertWaitcnts.cpp}::SQ_MAX_PGM_VGPRS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba0c4deee3d74fa3bd8a894f25581de266">anonymous{SIInsertWaitcnts.cpp}::STORE_CNT</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/hardwarelimits/#a13f04d8a9d9a2a9b79d9f6d6f4afa632">anonymous{SIInsertWaitcnts.cpp}::HardwareLimits::StorecntMax</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/registerencoding/#adf6f8c696eca1ca3f46aa76e37a293c9">anonymous{SIInsertWaitcnts.cpp}::RegisterEncoding::VGPR0</a>, <a href="/web-llvm/docs/api/structs/anonymous-siinsertwaitcnts-cpp-/registerencoding/#a3f63bf537289ffe2bd571c6a9a3f1120">anonymous{SIInsertWaitcnts.cpp}::RegisterEncoding::VGPRL</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a346ebb0249f57a1f637b365cf0d250c0">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::WaitcntBrackets</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#ac90dcf906933ef797a10ccbe27b91ec5">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::WaitcntGeneratorGFX12Plus</a> and <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#afb495e3090f7a7adbb6d855117b3b433">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::WaitcntGeneratorPreGFX12</a>.</p>

</div>
</div>

### setForceEmitWaitcnt() {#a90a2b453bf3ce25f979403d9d95c7070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::setForceEmitWaitcnt ()</td>
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



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bad2dc0db90fa9cebb27684f1f2e9416a4">anonymous{SIInsertWaitcnts.cpp}::DS_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a50989c336e006eb7f8c168f04dbb32a4">llvm::DebugCounter::isCounterSet</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bafe2ec1259d862907bc38ee5058f82dd0">anonymous{SIInsertWaitcnts.cpp}::KM_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a> and <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a5aace8653ce3726ef07194dcf6bce2bf">llvm::DebugCounter::shouldExecute</a>.</p>


<p>Referenced by <a href="#a8a42c531875f7db92f2c697b823654b5">generateWaitcntInstBefore</a>.</p>

</div>
</div>

### shouldFlushVmCnt() {#a6b65813ca9867deebf9b395cae8a8c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIInsertWaitcnts::shouldFlushVmCnt (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * ML, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> &amp; Brackets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba5a4952f35190975e3b6c84922d8b4ff8">anonymous{SIInsertWaitcnts.cpp}::BVH_CNT</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a690f39ef8620b9d57557d0cc194b3098">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getRegInterval</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#ad6cd92b8b96ec1c43da17757bb46b24c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getRegScore</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a51971ae9582c2d884bc84eef8498e243">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getScoreLB</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="#a3b41f307768619a97e70860c9ff562cd">isVMEMOrFlatVMEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba70f203972ebeec43ef1971db7a1ed063">anonymous{SIInsertWaitcnts.cpp}::LOAD_CNT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3ad01fd9b01e9dde8bd3dc247afbfb7218">ML</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba30a06f8031e397d17b375dce3d7399fd">anonymous{SIInsertWaitcnts.cpp}::SAMPLE_CNT</a>.</p>


<p>Referenced by <a href="#a51b2fd564c6db478ebdc025a9781c7d0">isPreheaderToFlush</a>.</p>

</div>
</div>

### updateEventWaitcntAfter() {#a3f5e55facd89c7c4e29803a545e13716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIInsertWaitcnts::updateEventWaitcntAfter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets">WaitcntBrackets</a> * ScoreBrackets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a0e968fc970599ceab59ecb968132e6d0">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::applyWaitcnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a12875f783295ef0f67d11ae574bdcfdd">callWaitsOnFunctionReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#af7592dc94276d1958420bcfb414b6998afe9e14fadada855231c900eecbea27f2">llvm::AMDGPU::Exp::ET_PARAM0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#af7592dc94276d1958420bcfb414b6998a6a774a598f798bc6a057d9a88a1427c0">llvm::AMDGPU::Exp::ET_PARAM31</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#af7592dc94276d1958420bcfb414b6998a819e373068289857bb1cef7f5b320c11">llvm::AMDGPU::Exp::ET_POS0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/exp/#af7592dc94276d1958420bcfb414b6998ac84234e8abdfe7d1a85fef7297734e49">llvm::AMDGPU::Exp::ET_POS_LAST</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7bae9718b54520e280d35e9e0268e726ca6">anonymous{SIInsertWaitcnts.cpp}::EXP_CNT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa3d3a2918b4a8d46587a46104973a0fbb">anonymous{SIInsertWaitcnts.cpp}::EXP_GPR_LOCK</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa29adb0a7716bd8776a15d8e48236b226">anonymous{SIInsertWaitcnts.cpp}::EXP_LDS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daac5112e1f3b27e352669978def9632a96">anonymous{SIInsertWaitcnts.cpp}::EXP_PARAM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daad6945119665d190abd3262800abbf1b8">anonymous{SIInsertWaitcnts.cpp}::EXP_POS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa495d00b9909551a28dd47651ca5abd6b">anonymous{SIInsertWaitcnts.cpp}::GDS_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa7cabdbd2bae66ba4d0a4af5e95148024">anonymous{SIInsertWaitcnts.cpp}::GDS_GPR_LOCK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad6c6b1894340016cee9e4b730ade8af6">llvm::AMDGPU::getMUBUFIsBufferInv</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#a4d5807670c4c32383f66d0e1df8936e0">getVmemWaitEventType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6c4c2a9d09070e2709f9725a915575e4">llvm::SIInstrInfo::isAtomicRet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a1bcf009f708fdf8a9c5cf20646d86007">isCacheInvOrWBInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a2d40ab246e329190bbf36cd93fd88e83">llvm::SIInstrInfo::isEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a5b2aaf80981b29494436f2b18a604e1c">llvm::SIInstrInfo::isLDSDIR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a08b830059090a1bb27b14e1e524fdb46">llvm::SIInstrInfo::isVMEM</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daaa8971543f4c4ff4e747224697d45f0f6">anonymous{SIInsertWaitcnts.cpp}::LDS_ACCESS</a>, <a href="#ac5d11a157ed918f93d2cf2900bc35472">mayAccessLDSThroughFlat</a>, <a href="#ac1de9db6b5ec43a3d021397cf12dc467">mayAccessVMEMThroughFlat</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a17f5d15a7320dec2cfefb6617f711ab7">llvm::MachineInstr::mayLoadOrStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#abb50d291f99656392690a84ac477a694">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::setPendingFlat</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a9feba9865c5cd3ad4186dccfb4e44c6c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::setStateOnFunctionEntryOrReturn</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daaf3cac1cd357193995b108d6d73781a32">anonymous{SIInsertWaitcnts.cpp}::SMEM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa33b8619729a53d2b671fae55f77a626a">anonymous{SIInsertWaitcnts.cpp}::SQ_MESSAGE</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a7fa7c35bfc5ff0d3fd25401b3b2e86daa66da40a072eb0d08160551b7cfd8846e">anonymous{SIInsertWaitcnts.cpp}::VMW_GPR_LOCK</a>.</p>


<p>Referenced by <a href="#a350c647ea2f30d644a78ec7ab9dc9684">insertWaitcntInBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a676e53bf212d33c16881aef0a6bb192e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### BlockInfos {#a22e1da77f91e596472f07d1a1a715ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;MachineBasicBlock *, BlockInfo&gt; anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::BlockInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### ForceEmitWaitcnt {#a8351444c5f8c324d419219230a117231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::ForceEmitWaitcnt[NUM_INST_CNTS]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### MaxCounter {#ae87a901c050f1e940049b116ff7ceba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstCounterType anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::MaxCounter = <a href="/web-llvm/docs/api/namespaces/anonymous-siinsertwaitcnts-cpp-/#a871adff9f76dede83762790959bc8e7ba6bce6243a580981ed0a55d0ac3fb5f2c">NUM_NORMAL_INST_CNTS</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### MLI {#a30d857de994d986f1a74951928484e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo* anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::MLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### MRI {#acd55c39c70ba15b6114d6c76075acceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### PDT {#a1f900acab8b5bca42efef52754071aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePostDominatorTree* anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### PreheadersToFlush {#ab6a965a7611410b0682c0b328b2968d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, bool&gt; anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::PreheadersToFlush</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### ReleaseVGPRInsts {#a3b4bdbc9cee6e008d4ec28aa1d096a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;MachineInstr *&gt; anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::ReleaseVGPRInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### SLoadAddresses {#a73e1cd2293b83bae8ffa05ea72762809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, MachineBasicBlock *&gt; anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::SLoadAddresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### SmemAccessCounter {#a954a47dac428f85d74827e4c4867321c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstCounterType anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::SmemAccessCounter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### ST {#ab6ef52d3b624162a1875ff0835b42b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::ST = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### TII {#a1bdb162aed6c88777b4b56bdd6772d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### TRI {#ae7e86e4114d24eb946824ba54e75a5a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo* anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### WCG {#a73ebc17ff484902a9da533e43321b0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WaitcntGenerator* anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::WCG = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### WCGGFX12Plus {#ad3e6648d84be5dc0588662dc0d662066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WaitcntGeneratorGFX12Plus anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::WCGGFX12Plus</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

### WCGPreGFX12 {#a5b8d61cd3f55701f35a1cd67bfdd7555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WaitcntGeneratorPreGFX12 anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::WCGPreGFX12</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ab4003ab1ea1a7dd8d318409cfb820f3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SI Insert false char SIInsertWaitcnts::ID = 0</td>
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



<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp">SIInsertWaitcnts.cpp</a>.</p>


<p>Referenced by <a href="#a86722649a06b625840046a1701025785">SIInsertWaitcnts</a>.</p>

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
