---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUInsertDelayAlu` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu { ... }
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DelayType { <a href="#a61a5ea8046e1a487e39c75b2af78bef9">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f45c4900f218a1f1919890cb5a76ad0">AMDGPUInsertDelayAlu</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab544e1282d5f0b4a4f0bbad08d93446b">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#ab544e1282d5f0b4a4f0bbad08d93446b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cdd14f8272a87151d5bd4f1aeeeb4de">emitDelayAlu</a> (MachineInstr &amp;MI, DelayInfo Delay, MachineInstr *LastDelayAlu)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e91d805ee46e758435fafffa3126255">runOnMachineBasicBlock</a> (MachineBasicBlock &amp;MBB, bool Emit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af83b3ea8c8510197a9fc5b6d4f7cff0a">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#af83b3ea8c8510197a9fc5b6d4f7cff0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0721319bb42cb0a6160f10023729f9e">SII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971378552f443b0ff307b0311712eaee">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a638f38cda1483a3da2ba11fcf890a1a3">SchedModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delaystate">DelayState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa146a11433047272b550c4301b549fbe">BlockState</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd449b894bd3b36c645c143ca58240e4">instructionWaitsForVALU</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a61a5ea8046e1a487e39c75b2af78bef9">DelayType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1abf441c2b55d0f822f53998df6e75">getDelayType</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b467706eb7315fa410e27d59e702bf">ID</a> = 0</td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### DelayType {#a61a5ea8046e1a487e39c75b2af78bef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayType </td>
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
<td class="doxyEnumItemName">VALU<a id="a61a5ea8046e1a487e39c75b2af78bef9a2d1d8dfa7b8a93b7b3339cb9bd860a4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TRANS<a id="a61a5ea8046e1a487e39c75b2af78bef9ab27dc6b647ff6c0da4e42e6b08301929"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SALU<a id="a61a5ea8046e1a487e39c75b2af78bef9a2bc00b11763adfa20e728ff6c62b9486"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OTHER<a id="a61a5ea8046e1a487e39c75b2af78bef9a241ba3270d1998e2060a9e411f773006"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AMDGPUInsertDelayAlu() {#a7f45c4900f218a1f1919890cb5a76ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::AMDGPUInsertDelayAlu ()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="#aa9b467706eb7315fa410e27d59e702bf">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitDelayAlu() {#a7cdd14f8272a87151d5bd4f1aeeeb4de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo">DelayInfo</a> Delay, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * LastDelayAlu)</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo/#acf9f5d59a24be46cbac8a6d800992d50">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::SALU_CYCLES_MAX</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo/#a870fc34a3ab61ee4003b6aa1d7536c4f">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::SALUCycles</a>, <a href="#aa0721319bb42cb0a6160f10023729f9e">SII</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo/#a990d7b1dba90a47ef530024145a016b4">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::TRANS_MAX</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo/#a476491112db2775de6b2003ae62341c1">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::TRANSNum</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo/#a327a68baee6f61f592a78c93e9cdfbb6">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::TRANSNumVALU</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo/#a32bbbf7da4ad61a76cce07a336f8b9f7">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::VALU_MAX</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo/#ad2720f790c61cec3b607f094725e22a9">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::VALUNum</a>.</p>


<p>Referenced by <a href="#a4e91d805ee46e758435fafffa3126255">runOnMachineBasicBlock</a>.</p>

</div>
</div>

### getAnalysisUsage() {#ab544e1282d5f0b4a4f0bbad08d93446b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### runOnMachineBasicBlock() {#a4e91d805ee46e758435fafffa3126255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::runOnMachineBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, bool Emit)</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa146a11433047272b550c4301b549fbe">BlockState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a7cdd14f8272a87151d5bd4f1aeeeb4de">emitDelayAlu</a>, <a href="#aeb1abf441c2b55d0f822f53998df6e75">getDelayType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac1656e5749e564620d30b6c2bd704f11">llvm::SIInstrInfo::getNumWaitStates</a>, <a href="#acd449b894bd3b36c645c143ca58240e4">instructionWaitsForVALU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delayinfo/#ab2f970d3531548ca857ac0f9de4f251e">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayInfo::merge</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delaystate/#a091d1a0517b4c9c8e6f1586d32a3bc27">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayState::merge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a61a5ea8046e1a487e39c75b2af78bef9a241ba3270d1998e2060a9e411f773006">OTHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#a638f38cda1483a3da2ba11fcf890a1a3">SchedModel</a> and <a href="#a971378552f443b0ff307b0311712eaee">TRI</a>.</p>


<p>Referenced by <a href="#af83b3ea8c8510197a9fc5b6d4f7cff0a">runOnMachineFunction</a>.</p>

</div>
</div>

### runOnMachineFunction() {#af83b3ea8c8510197a9fc5b6d4f7cff0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af9880d625c506aacc716ee1c9a29ff8b">llvm::SetVector&lt; T, Vector, Set, N &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="#a4e91d805ee46e758435fafffa3126255">runOnMachineBasicBlock</a>, <a href="#a638f38cda1483a3da2ba11fcf890a1a3">SchedModel</a>, <a href="#aa0721319bb42cb0a6160f10023729f9e">SII</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a> and <a href="#a971378552f443b0ff307b0311712eaee">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BlockState {#aa146a11433047272b550c4301b549fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, DelayState&gt; anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::BlockState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a4e91d805ee46e758435fafffa3126255">runOnMachineBasicBlock</a>.</p>

</div>
</div>

### SchedModel {#a638f38cda1483a3da2ba11fcf890a1a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel* anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a4e91d805ee46e758435fafffa3126255">runOnMachineBasicBlock</a> and <a href="#af83b3ea8c8510197a9fc5b6d4f7cff0a">runOnMachineFunction</a>.</p>

</div>
</div>

### SII {#aa0721319bb42cb0a6160f10023729f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::SII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a7cdd14f8272a87151d5bd4f1aeeeb4de">emitDelayAlu</a> and <a href="#af83b3ea8c8510197a9fc5b6d4f7cff0a">runOnMachineFunction</a>.</p>

</div>
</div>

### TRI {#a971378552f443b0ff307b0311712eaee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delaystate/#aee94f03d721dddddb0e9136561f3b8b8">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayState::dump</a>, <a href="#a4e91d805ee46e758435fafffa3126255">runOnMachineBasicBlock</a> and <a href="#af83b3ea8c8510197a9fc5b6d4f7cff0a">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDelayType() {#aeb1abf441c2b55d0f822f53998df6e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DelayType anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::getDelayType (uint64_t TSFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="#a61a5ea8046e1a487e39c75b2af78bef9a241ba3270d1998e2060a9e411f773006">OTHER</a>, <a href="#a61a5ea8046e1a487e39c75b2af78bef9a2bc00b11763adfa20e728ff6c62b9486">SALU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab20a2dd15666d86af4e1fdeb88b1be7c">llvm::SIInstrFlags::SALU</a>, <a href="#a61a5ea8046e1a487e39c75b2af78bef9ab27dc6b647ff6c0da4e42e6b08301929">TRANS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca6edf620aaa09a9f39b50177b8fa809d4">llvm::SIInstrFlags::TRANS</a>, <a href="#a61a5ea8046e1a487e39c75b2af78bef9a2d1d8dfa7b8a93b7b3339cb9bd860a4d">VALU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca25bdad6e13bc9ed9f9ce690ae614db1c">llvm::SIInstrFlags::VALU</a>.</p>


<p>Referenced by <a href="#a4e91d805ee46e758435fafffa3126255">runOnMachineBasicBlock</a>.</p>

</div>
</div>

### instructionWaitsForVALU() {#acd449b894bd3b36c645c143ca58240e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::instructionWaitsForVALU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/depctr/#ad0af1d007a5a69d0408b1ad698ffae04">llvm::AMDGPU::DepCtr::decodeFieldVaVdst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca953a5ba3766c4aea8d9b8eeeba722679">llvm::SIInstrFlags::DS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca3f6b33151573e94a6ef7f14b809dbe70">llvm::SIInstrFlags::EXP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181ecab0e8527c8c81d2caa91d9b2bd1852574">llvm::SIInstrFlags::FLAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca0666b703f5fe8ee884171492fb6a685a">llvm::SIInstrFlags::MIMG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca4863f895381859543f89e4423126a73f">llvm::SIInstrFlags::MTBUF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/siinstrflags/#a63fe1ccb8fc5f327a64d2977fce181eca2fca87a5855f045ac7f07d8c2814e81f">llvm::SIInstrFlags::MUBUF</a>.</p>


<p>Referenced by <a href="#a4e91d805ee46e758435fafffa3126255">runOnMachineBasicBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#aa9b467706eb7315fa410e27d59e702bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AMDGPUInsertDelayAlu::ID = 0</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a>.</p>


<p>Referenced by <a href="#a7f45c4900f218a1f1919890cb5a76ad0">AMDGPUInsertDelayAlu</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinsertdelayalu-cpp">AMDGPUInsertDelayAlu.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
