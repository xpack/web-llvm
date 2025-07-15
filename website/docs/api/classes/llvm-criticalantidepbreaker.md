---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/criticalantidepbreaker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CriticalAntiDepBreaker` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::CriticalAntiDepBreaker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CodeGen/CriticalAntiDepBreaker.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/antidepbreaker">AntiDepBreaker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class works in conjunction with the post-RA scheduler to rename registers to break register anti-dependencies (WAR hazards). <a href="/web-llvm/docs/api/classes/llvm/antidepbreaker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8739af5d71311787ad3036ee84c9182a">RegRefIter</a> = std::multimap&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc978d8ee6fe85244aa7c78486162dfa">CriticalAntiDepBreaker</a> (MachineFunction &amp;MFi, const RegisterClassInfo &amp;RCI)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e2e1740694eb1ea7ccbcc78e7643af">~CriticalAntiDepBreaker</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4573a84f25279673e3906914132a39">StartBlock</a> (MachineBasicBlock *BB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize anti-dep breaking for a new basic block. <a href="#adb4573a84f25279673e3906914132a39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a71ccecb00de06004fb421a568dd7b4">BreakAntiDependencies</a> (const std::vector&lt; SUnit &gt; &amp;SUnits, MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End, unsigned InsertPosIndex, DbgValueVector &amp;DbgValues) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifiy anti-dependencies along the critical path of the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> and break them by renaming registers. <a href="#a5a71ccecb00de06004fb421a568dd7b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca18e9d509308d7beff421164ce304e8">Observe</a> (MachineInstr &amp;MI, unsigned Count, unsigned InsertPosIndex) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update liveness information to account for the current instruction, which will not be scheduled. <a href="#aca18e9d509308d7beff421164ce304e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b902b674dccf813eded0d99d6b012e">FinishBlock</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finish anti-dep breaking for a basic block. <a href="#a75b902b674dccf813eded0d99d6b012e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ff1e386a0aad4c32cddbdccc995113">PrescanInstruction</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1700a56970c3eb8680c7093fe3bb1f7b">ScanInstruction</a> (MachineInstr &amp;MI, unsigned Count)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca3d01ac943d5f4c9656daa2e85e7af">isNewRegClobberedByRefs</a> (RegRefIter RegRefBegin, RegRefIter RegRefEnd, unsigned NewReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1186fdee023fbfd3dfb4a32fc861083">findSuitableFreeRegister</a> (RegRefIter RegRefBegin, RegRefIter RegRefEnd, unsigned AntiDepReg, unsigned LastNewReg, const TargetRegisterClass *RC, SmallVectorImpl&lt; unsigned &gt; &amp;Forbid)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af300586e4a32f8cbdf9600dfed01f780">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68cf37820182ae5f0eff8ab4b96229bd">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5a06151943caac14ddb93deda052304">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeb144714a20425e052ed80803854a90">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed897eb93781e8b0db1f8bb96414d97">RegClassInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a8e4861b9562802a01d77b7ba07d715">AllocatableSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of allocatable registers. <a href="#a1a8e4861b9562802a01d77b7ba07d715">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4975f1bfbc77e749259af59eb3391485">Classes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For live regs that are only used in one register class in a live range, the register class. <a href="#a4975f1bfbc77e749259af59eb3391485">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::multimap&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2409825956afdbfbf32c75040d3d0af">RegRefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map registers to all their references within a live range. <a href="#af2409825956afdbfbf32c75040d3d0af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33068acc76f1eb483ee81e51d71d6850">KillIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the most recent kill (proceeding bottom-up), or ~0u if the register is not live. <a href="#a33068acc76f1eb483ee81e51d71d6850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46bb547ac67babb3ec868b92484f016">DefIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the most recent complete def (proceeding bottom up), or ~0u if the register is live. <a href="#af46bb547ac67babb3ec868b92484f016">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b7f879ea9b7452a91e51822285a7b5">KeepRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of registers which are live and cannot be changed to break anti-dependencies. <a href="#a71b7f879ea9b7452a91e51822285a7b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### RegRefIter {#a8739af5d71311787ad3036ee84c9182a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CriticalAntiDepBreaker::RegRefIter = 
        std::multimap&lt;unsigned, MachineOperand *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CriticalAntiDepBreaker() {#afc978d8ee6fe85244aa7c78486162dfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalAntiDepBreaker::CriticalAntiDepBreaker (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MFi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> &amp; RCI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CriticalAntiDepBreaker() {#a23e2e1740694eb1ea7ccbcc78e7643af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CriticalAntiDepBreaker::~CriticalAntiDepBreaker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>


<p>References <a href="#a5a71ccecb00de06004fb421a568dd7b4">BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a75b902b674dccf813eded0d99d6b012e">FinishBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aca18e9d509308d7beff421164ce304e8">Observe</a> and <a href="#adb4573a84f25279673e3906914132a39">StartBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### BreakAntiDependencies() {#a5a71ccecb00de06004fb421a568dd7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CriticalAntiDepBreaker::BreakAntiDependencies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt; &amp; SUnits, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End, unsigned InsertPosIndex, <a href="/web-llvm/docs/api/classes/llvm/antidepbreaker/#ac4f0c67e90ba02856fa8b30a5ec81032">DbgValueVector</a> &amp; DbgValues)</td>
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

<p>Identifiy anti-dependencies along the critical path of the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> and break them by renaming registers.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp/#a4bfac8dc3460d1e7628eba4c5d6e4a12">CriticalPathStep</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/classes/llvm/antidepbreaker/#a8263e37c92ac03b506311cf58745b8ce">llvm::AntiDepBreaker::UpdateDbgValues</a>.</p>


<p>Referenced by <a href="#a23e2e1740694eb1ea7ccbcc78e7643af">~CriticalAntiDepBreaker</a>.</p>

</div>
</div>

### FinishBlock() {#a75b902b674dccf813eded0d99d6b012e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CriticalAntiDepBreaker::FinishBlock ()</td>
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

<p>Finish anti-dep breaking for a basic block.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a35bbc237e4a675c5332103ac6e7dcce1">llvm::BitVector::clear</a>.</p>


<p>Referenced by <a href="#a23e2e1740694eb1ea7ccbcc78e7643af">~CriticalAntiDepBreaker</a>.</p>

</div>
</div>

### Observe() {#aca18e9d509308d7beff421164ce304e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CriticalAntiDepBreaker::Observe (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Count, unsigned InsertPosIndex)</td>
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

<p>Update liveness information to account for the current instruction, which will not be scheduled.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a23e2e1740694eb1ea7ccbcc78e7643af">~CriticalAntiDepBreaker</a>.</p>

</div>
</div>

### StartBlock() {#adb4573a84f25279673e3906914132a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CriticalAntiDepBreaker::StartBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>Initialize anti-dep breaking for a new basic block.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa42c3828ac3f788f2ef3ff6fa46e4926">llvm::MachineFrameInfo::getPristineRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a82f5d244972c88ff03ee56d6c090ac70">llvm::MachineBasicBlock::isReturnBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adbff55f335d303816547f35eb6edb948">llvm::MachineBasicBlock::size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>


<p>Referenced by <a href="#a23e2e1740694eb1ea7ccbcc78e7643af">~CriticalAntiDepBreaker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findSuitableFreeRegister() {#ae1186fdee023fbfd3dfb4a32fc861083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CriticalAntiDepBreaker::findSuitableFreeRegister (RegRefIter RegRefBegin, RegRefIter RegRefEnd, unsigned AntiDepReg, unsigned LastNewReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Forbid)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### isNewRegClobberedByRefs() {#a5ca3d01ac943d5f4c9656daa2e85e7af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CriticalAntiDepBreaker::isNewRegClobberedByRefs (RegRefIter RegRefBegin, RegRefIter RegRefEnd, unsigned NewReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### PrescanInstruction() {#a97ff1e386a0aad4c32cddbdccc995113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CriticalAntiDepBreaker::PrescanInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### ScanInstruction() {#a1700a56970c3eb8680c7093fe3bb1f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CriticalAntiDepBreaker::ScanInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllocatableSet {#a1a8e4861b9562802a01d77b7ba07d715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector llvm::CriticalAntiDepBreaker::AllocatableSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of allocatable registers.</p>


<p>We'll be ignoring anti-dependencies on non-allocatable registers, because they may not be safe to break.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### Classes {#a4975f1bfbc77e749259af59eb3391485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;const TargetRegisterClass *&gt; llvm::CriticalAntiDepBreaker::Classes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For live regs that are only used in one register class in a live range, the register class.</p>


<p>If the register is not live, the corresponding value is null. If the register is live but used in multiple register classes, the corresponding value is -1 casted to a pointer.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### DefIndices {#af46bb547ac67babb3ec868b92484f016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::CriticalAntiDepBreaker::DefIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the most recent complete def (proceeding bottom up), or ~0u if the register is live.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### KeepRegs {#a71b7f879ea9b7452a91e51822285a7b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::CriticalAntiDepBreaker::KeepRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set of registers which are live and cannot be changed to break anti-dependencies.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### KillIndices {#a33068acc76f1eb483ee81e51d71d6850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::CriticalAntiDepBreaker::KillIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the most recent kill (proceeding bottom-up), or ~0u if the register is not live.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### MF {#af300586e4a32f8cbdf9600dfed01f780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::CriticalAntiDepBreaker::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### MRI {#a68cf37820182ae5f0eff8ab4b96229bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::CriticalAntiDepBreaker::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### RegClassInfo {#a5ed897eb93781e8b0db1f8bb96414d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterClassInfo&amp; llvm::CriticalAntiDepBreaker::RegClassInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### RegRefs {#af2409825956afdbfbf32c75040d3d0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::multimap&lt;unsigned, MachineOperand *&gt; llvm::CriticalAntiDepBreaker::RegRefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map registers to all their references within a live range.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### TII {#ac5a06151943caac14ddb93deda052304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::CriticalAntiDepBreaker::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

### TRI {#aeeb144714a20425e052ed80803854a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::CriticalAntiDepBreaker::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-cpp">CriticalAntiDepBreaker.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/criticalantidepbreaker-h">CriticalAntiDepBreaker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
