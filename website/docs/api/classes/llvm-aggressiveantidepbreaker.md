---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aggressiveantidepbreaker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AggressiveAntiDepBreaker` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AggressiveAntiDepBreaker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">CodeGen/AggressiveAntiDepBreaker.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70aca550bb62a3398d0022573f9b0007">RenameOrderType</a> = std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *, unsigned &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of a position in the allocation order for each regclass. <a href="#a70aca550bb62a3398d0022573f9b0007">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84346919b2ab9829188ffa8e7e8d3c9">AggressiveAntiDepBreaker</a> (MachineFunction &amp;MFi, const RegisterClassInfo &amp;RCI, TargetSubtargetInfo::RegClassVector &amp;CriticalPathRCs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fb042780e3f9caed69dd8b3ab540bd">AggressiveAntiDepBreaker</a> (const AggressiveAntiDepBreaker &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85134236bd6e22ec302972f727a01691">~AggressiveAntiDepBreaker</a> () override</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker">AggressiveAntiDepBreaker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfa77da43e26d190b85d10404e0c132">operator=</a> (const AggressiveAntiDepBreaker &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd095bb58a0243946704d20d3559d420">StartBlock</a> (MachineBasicBlock *BB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize anti-dep breaking for a new basic block. <a href="#abd095bb58a0243946704d20d3559d420">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7263c22653c86a22ff72bc5385e8835">BreakAntiDependencies</a> (const std::vector&lt; SUnit &gt; &amp;SUnits, MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End, unsigned InsertPosIndex, DbgValueVector &amp;DbgValues) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifiy anti-dependencies along the critical path of the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> and break them by renaming registers. <a href="#ab7263c22653c86a22ff72bc5385e8835">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b8115cab493470f09c72c83b2b3ba5">Observe</a> (MachineInstr &amp;MI, unsigned Count, unsigned InsertPosIndex) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update liveness information to account for the current instruction, which will not be scheduled. <a href="#a19b8115cab493470f09c72c83b2b3ba5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e720e0600da94ee88fe18c94fa4269a">FinishBlock</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finish anti-dep breaking for a basic block. <a href="#a6e720e0600da94ee88fe18c94fa4269a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ec3854838c7fa67db303737d787173">IsImplicitDefUse</a> (MachineInstr &amp;MI, MachineOperand &amp;MO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MO represents a register that is both implicitly used and defined in MI. <a href="#ad2ec3854838c7fa67db303737d787173">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9d84fbf79eed1729f07fcf74bc6e94">GetPassthruRegs</a> (MachineInstr &amp;MI, std::set&lt; unsigned &gt; &amp;PassthruRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If MI implicitly def/uses a register, then return that register and all subregisters. <a href="#afd9d84fbf79eed1729f07fcf74bc6e94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ba07821bf4dc8537f56ea836944d78">HandleLastUse</a> (unsigned Reg, unsigned KillIdx, const char *tag, const char *header=nullptr, const char *footer=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31e69c9797b91c96437e9367c38e738">PrescanInstruction</a> (MachineInstr &amp;MI, unsigned Count, std::set&lt; unsigned &gt; &amp;PassthruRegs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a873afe436b05b6260027d429ce869a4e">ScanInstruction</a> (MachineInstr &amp;MI, unsigned Count)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e3df945617c42dcc0a66628cadc285">GetRenameRegisters</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1612eff70c87d14b9e12936876f404a">FindSuitableFreeRegisters</a> (unsigned SuperReg, unsigned AntiDepGroupIndex, RenameOrderType &amp;RenameOrder, std::map&lt; unsigned, unsigned &gt; &amp;RenameMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1f73c4f58173fda45a7c39383b2c3e8">MF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1d3b9b749c73e8cb4707c62f407156">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30592433e3d78c980bb001a511472ee0">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6e360fc3f85ae08313a708109521989">TRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9eea9708919d7ce202de27c5aa163bd">RegClassInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8711bd327b350599c5e9164b4ce162">CriticalPathSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of registers that should only be renamed if they are on the critical path. <a href="#a6c8711bd327b350599c5e9164b4ce162">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepstate">AggressiveAntiDepState</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f62ed11ac6a4c20086ee75b9b8dbde">State</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The state used to identify and rename anti-dependence registers. <a href="#a55f62ed11ac6a4c20086ee75b9b8dbde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### RenameOrderType {#a70aca550bb62a3398d0022573f9b0007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AggressiveAntiDepBreaker::RenameOrderType =  std::map&lt;const TargetRegisterClass *, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of a position in the allocation order for each regclass.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AggressiveAntiDepBreaker() {#ae84346919b2ab9829188ffa8e7e8d3c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AggressiveAntiDepBreaker::AggressiveAntiDepBreaker (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MFi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> &amp; RCI, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a24e0be4e8e0875ea7cf4dd3d20c11662">TargetSubtargetInfo::RegClassVector</a> &amp; CriticalPathRCs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>


<p>Referenced by <a href="#a57fb042780e3f9caed69dd8b3ab540bd">AggressiveAntiDepBreaker</a> and <a href="#a4cfa77da43e26d190b85d10404e0c132">operator=</a>.</p>

</div>
</div>

### AggressiveAntiDepBreaker() {#a57fb042780e3f9caed69dd8b3ab540bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AggressiveAntiDepBreaker::AggressiveAntiDepBreaker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker">AggressiveAntiDepBreaker</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>


<p>References <a href="#ae84346919b2ab9829188ffa8e7e8d3c9">AggressiveAntiDepBreaker</a>, <a href="#ab7263c22653c86a22ff72bc5385e8835">BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a6e720e0600da94ee88fe18c94fa4269a">FinishBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a19b8115cab493470f09c72c83b2b3ba5">Observe</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="#abd095bb58a0243946704d20d3559d420">StartBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AggressiveAntiDepBreaker() {#a85134236bd6e22ec302972f727a01691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AggressiveAntiDepBreaker::~AggressiveAntiDepBreaker ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a4cfa77da43e26d190b85d10404e0c132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AggressiveAntiDepBreaker &amp; llvm::AggressiveAntiDepBreaker::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker">AggressiveAntiDepBreaker</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>


<p>Reference <a href="#ae84346919b2ab9829188ffa8e7e8d3c9">AggressiveAntiDepBreaker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### BreakAntiDependencies() {#ab7263c22653c86a22ff72bc5385e8835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AggressiveAntiDepBreaker::BreakAntiDependencies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt; &amp; SUnits, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End, unsigned InsertPosIndex, <a href="/web-llvm/docs/api/classes/llvm/antidepbreaker/#ac4f0c67e90ba02856fa8b30a5ec81032">DbgValueVector</a> &amp; DbgValues)</td>
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


<p>BreakAntiDependencies - Identifiy anti-dependencies within the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> and break them by renaming registers.</p>


<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp/#a4a408b05eacd6ea605ddc856dcf57f11">AntiDepEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp/#a4bfac8dc3460d1e7628eba4c5d6e4a12">CriticalPathStep</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a72e0568b7bf0e9a97260c34264a549a0">llvm::SUnit::Latency</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">llvm::SDep::Output</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a> and <a href="/web-llvm/docs/api/classes/llvm/antidepbreaker/#a8263e37c92ac03b506311cf58745b8ce">llvm::AntiDepBreaker::UpdateDbgValues</a>.</p>


<p>Referenced by <a href="#a57fb042780e3f9caed69dd8b3ab540bd">AggressiveAntiDepBreaker</a>.</p>

</div>
</div>

### FinishBlock() {#a6e720e0600da94ee88fe18c94fa4269a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveAntiDepBreaker::FinishBlock ()</td>
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

<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>Referenced by <a href="#a57fb042780e3f9caed69dd8b3ab540bd">AggressiveAntiDepBreaker</a>.</p>

</div>
</div>

### Observe() {#a19b8115cab493470f09c72c83b2b3ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveAntiDepBreaker::Observe (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Count, unsigned InsertPosIndex)</td>
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

<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>


<p>Referenced by <a href="#a57fb042780e3f9caed69dd8b3ab540bd">AggressiveAntiDepBreaker</a>.</p>

</div>
</div>

### StartBlock() {#abd095bb58a0243946704d20d3559d420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveAntiDepBreaker::StartBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa42c3828ac3f788f2ef3ff6fa46e4926">llvm::MachineFrameInfo::getPristineRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a82f5d244972c88ff03ee56d6c090ac70">llvm::MachineBasicBlock::isReturnBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adbff55f335d303816547f35eb6edb948">llvm::MachineBasicBlock::size</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>


<p>Referenced by <a href="#a57fb042780e3f9caed69dd8b3ab540bd">AggressiveAntiDepBreaker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### FindSuitableFreeRegisters() {#ad1612eff70c87d14b9e12936876f404a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AggressiveAntiDepBreaker::FindSuitableFreeRegisters (unsigned SuperReg, unsigned AntiDepGroupIndex, RenameOrderType &amp; RenameOrder, std::map&lt; unsigned, unsigned &gt; &amp; RenameMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### GetPassthruRegs() {#afd9d84fbf79eed1729f07fcf74bc6e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveAntiDepBreaker::GetPassthruRegs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::set&lt; unsigned &gt; &amp; PassthruRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If MI implicitly def/uses a register, then return that register and all subregisters.</p>

<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### GetRenameRegisters() {#a44e3df945617c42dcc0a66628cadc285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector AggressiveAntiDepBreaker::GetRenameRegisters (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### HandleLastUse() {#a37ba07821bf4dc8537f56ea836944d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveAntiDepBreaker::HandleLastUse (unsigned Reg, unsigned KillIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * tag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * header=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * footer=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### IsImplicitDefUse() {#ad2ec3854838c7fa67db303737d787173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AggressiveAntiDepBreaker::IsImplicitDefUse (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MO represents a register that is both implicitly used and defined in MI.</p>

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### PrescanInstruction() {#ae31e69c9797b91c96437e9367c38e738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveAntiDepBreaker::PrescanInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Count, std::set&lt; unsigned &gt; &amp; PassthruRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

### ScanInstruction() {#a873afe436b05b6260027d429ce869a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AggressiveAntiDepBreaker::ScanInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CriticalPathSet {#a6c8711bd327b350599c5e9164b4ce162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::AggressiveAntiDepBreaker::CriticalPathSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of registers that should only be renamed if they are on the critical path.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### MF {#aa1f73c4f58173fda45a7c39383b2c3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::AggressiveAntiDepBreaker::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### MRI {#a6f1d3b9b749c73e8cb4707c62f407156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::AggressiveAntiDepBreaker::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### RegClassInfo {#ac9eea9708919d7ce202de27c5aa163bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterClassInfo&amp; llvm::AggressiveAntiDepBreaker::RegClassInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### State {#a55f62ed11ac6a4c20086ee75b9b8dbde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AggressiveAntiDepState* llvm::AggressiveAntiDepBreaker::State = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The state used to identify and rename anti-dependence registers.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### TII {#a30592433e3d78c980bb001a511472ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::AggressiveAntiDepBreaker::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

### TRI {#ab6e360fc3f85ae08313a708109521989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::AggressiveAntiDepBreaker::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-cpp">AggressiveAntiDepBreaker.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/aggressiveantidepbreaker-h">AggressiveAntiDepBreaker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
