---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mirprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MIRPrinter` Class Reference

<p>This class prints out the machine functions using the MIR serialization format. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MIRPrinter { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19473494c346af51cbbbd06974b217bc">MIRPrinter</a> (raw_ostream &amp;OS, const MachineModuleInfo &amp;MMI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad72f291464c14665189a84050f38376">print</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bc43ffc97603d2acaf34479afbe0c8">convert</a> (yaml::MachineFunction &amp;YamlMF, const MachineFunction &amp;MF, const MachineRegisterInfo &amp;RegInfo, const TargetRegisterInfo *TRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154503cbc95ef98bff03d91938d64b07">convert</a> (ModuleSlotTracker &amp;MST, yaml::MachineFrameInfo &amp;YamlMFI, const MachineFrameInfo &amp;MFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef1b1a235ce94996013a71608e08f58">convert</a> (yaml::MachineFunction &amp;MF, const MachineConstantPool &amp;ConstantPool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a144cc64259d65d3f419f9d176fcf8078">convert</a> (ModuleSlotTracker &amp;MST, yaml::MachineJumpTable &amp;YamlJTI, const MachineJumpTableInfo &amp;JTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb28916bca65c0b9e9ee811613c51895">convertStackObjects</a> (yaml::MachineFunction &amp;YMF, const MachineFunction &amp;MF, ModuleSlotTracker &amp;MST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02f64dd0aa867287b5ad17200de097a">convertEntryValueObjects</a> (yaml::MachineFunction &amp;YMF, const MachineFunction &amp;MF, ModuleSlotTracker &amp;MST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa43a432a700f337af56c8f2d1db9fe0b">convertCallSiteObjects</a> (yaml::MachineFunction &amp;YMF, const MachineFunction &amp;MF, ModuleSlotTracker &amp;MST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7de4da09df7011d92c1f4abd46134a2">convertMachineMetadataNodes</a> (yaml::MachineFunction &amp;YMF, const MachineFunction &amp;MF, MachineModuleSlotTracker &amp;MST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5982dea08cc92ad6fd8776a506980a69">convertCalledGlobals</a> (yaml::MachineFunction &amp;YMF, const MachineFunction &amp;MF, MachineModuleSlotTracker &amp;MST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4cf74ec548be92345368213cddb699">initRegisterMaskIds</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4444b277de48f6ce1fff578c50a6c4b3">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa650480e2e3cd4b27145b95fb1a53977">MMI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2c5e6685f4c0796000c449817b3d5e">RegisterMaskIds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, FrameIndexOperand &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d89a6359fcc250f503a1f771901c14">StackObjectOperandMapping</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps from stack object indices to operand indices which will be used when printing frame index machine operands. <a href="#a15d89a6359fcc250f503a1f771901c14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class prints out the machine functions using the MIR serialization format.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MIRPrinter() {#a19473494c346af51cbbbd06974b217bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIRPrinter::MIRPrinter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convert() {#ae0bc43ffc97603d2acaf34479afbe0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convert (<a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YamlMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; RegInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a3303a0dc072a32f8f6c197a2712c40ab">llvm::yaml::MachineFunction::CalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/virtualregisterdefinition/#aa751025d58044405a8bbd19c79f0ea5f">llvm::yaml::VirtualRegisterDefinition::Class</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/virtualregisterdefinition/#aea3265d6f612cffd455013124abd49f5">llvm::yaml::VirtualRegisterDefinition::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ab51f61ae0bd39115370428967ca3d51b">llvm::yaml::MachineFunction::LiveIns</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/virtualregisterdefinition/#ae1aae2d3504d65630178803e3d7046b9">llvm::yaml::VirtualRegisterDefinition::PreferredRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84f1f18b0f13167b8e9c455b9524b58d">llvm::printRegClassOrBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#ae07cd49d1962f418e0e2f363b0217219">printRegFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a5861c278d9a814fd24723840f9d91cbf">printRegMIR</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctionlivein/#a633eac995395b35eff56dc51270fce24">llvm::yaml::MachineFunctionLiveIn::Register</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/virtualregisterdefinition/#ab7af3a53144a5b39fa1671a5e5bc6475">llvm::yaml::VirtualRegisterDefinition::RegisterFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a7a8c97438b408f27171481c989bf78d8">llvm::yaml::MachineFunction::TracksRegLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctionlivein/#a28afdf339179811343bd124d7a951b1c">llvm::yaml::MachineFunctionLiveIn::VirtualRegister</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ac2571f4b44b3f6a8beffcb959ca04f80">llvm::yaml::MachineFunction::VirtualRegisters</a>.</p>

</div>
</div>

### convert() {#a154503cbc95ef98bff03d91938d64b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convert (<a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo">yaml::MachineFrameInfo</a> &amp; YamlMFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp; MFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a5bf18fefab479cb029f0e9f108729c1d">llvm::yaml::MachineFrameInfo::AdjustsStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a19e260b3bbf8fad8480d151e11919836">llvm::MachineFrameInfo::adjustsStack</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#abe8303ed6b0f0d79541058d84e663622">llvm::yaml::MachineFrameInfo::CVBytesOfCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab64be7aad4478fdbd1c73f0ec4dabaf8">llvm::MachineFrameInfo::getCVBytesOfCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa306e1d00f65a9bb1030e66e9d195a69">llvm::MachineFrameInfo::getLocalFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a3836203fac855ac3c5718b701bd13ffd">llvm::MachineFrameInfo::getMaxAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a4f335273c28b17552a7cfd802f42be2a">llvm::MachineFrameInfo::getMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a60679e554cbf7092c8a0ae6c5db2661a">llvm::MachineFrameInfo::getOffsetAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5b92dc4f379813174c0942c8d1d8e241">llvm::MachineFrameInfo::getRestorePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af5ba92668c96fb23e8d5fa9add3daab6">llvm::MachineFrameInfo::getSavePoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a306aa6e7fca4dc92686608c643fcca8a">llvm::yaml::MachineFrameInfo::HasCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a2cc8bb867c8949943ca7d88f1db31fde">llvm::MachineFrameInfo::hasCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a9016735335a3c6435f7f16116825219c">llvm::yaml::MachineFrameInfo::HasMustTailInVarArgFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a7819a781e436c677ed1613c7739ee53e">llvm::MachineFrameInfo::hasMustTailInVarArgFunc</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#af0e50d4ef5d9bc86991571c9619de069">llvm::yaml::MachineFrameInfo::HasOpaqueSPAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a51773b6c05f392988bf6395ccd1788ce">llvm::MachineFrameInfo::hasOpaqueSPAdjustment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a51235e1a5d7863dc6e9933438de22e6d">llvm::yaml::MachineFrameInfo::HasPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a503a8cb169aa29ac907c218692087db3">llvm::MachineFrameInfo::hasPatchPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a0498221b210f6df4f02fd3add9725c29">llvm::yaml::MachineFrameInfo::HasStackMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa7d9e2f26e4c8b32f51c455b220ce13c">llvm::MachineFrameInfo::hasStackMap</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a5ed48d893132df78f141176402c448db">llvm::yaml::MachineFrameInfo::HasTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a763b7a1e7127b495f396b30f0d9c95f1">llvm::MachineFrameInfo::hasTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a4e92ff52f16ad6886618a56be6a9d055">llvm::yaml::MachineFrameInfo::HasVAStart</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab512cf99651d9d49323b0ac9a25c7f8d">llvm::MachineFrameInfo::hasVAStart</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a3b6b5df16492bd4c6f017af899a9a146">llvm::yaml::MachineFrameInfo::IsCalleeSavedInfoValid</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a81504f733d0491a446a16ef1ba0a5c2a">llvm::MachineFrameInfo::isCalleeSavedInfoValid</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#aa9b00eeb533d4001da1e812507e16959">llvm::yaml::MachineFrameInfo::IsFrameAddressTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a99cdf1b99c0f1b7e1bf2111aa7d2eaa3">llvm::MachineFrameInfo::isMaxCallFrameSizeComputed</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#afa74fd3cd131ed4389fde07f7e2b89f0">llvm::yaml::MachineFrameInfo::IsReturnAddressTaken</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a20fde7903c3d7ad21cc5825bb886e360">llvm::MachineFrameInfo::isReturnAddressTaken</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#ab55df3c6c13bf6d53d1488479ea7c0bc">llvm::yaml::MachineFrameInfo::LocalFrameSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a8d6fb6a5a29375a2921f6790102343da">llvm::yaml::MachineFrameInfo::MaxAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a44e7d9e28508a268f8b00da0eb02d792">llvm::yaml::MachineFrameInfo::MaxCallFrameSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#aca7b8fcc1a367fef683a9da2d099d8a4">llvm::yaml::MachineFrameInfo::OffsetAdjustment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a0a35e68f5c41b739bbe9c62797258568">llvm::yaml::MachineFrameInfo::RestorePoint</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#ad430069d4a06a264245119f22a382968">llvm::yaml::MachineFrameInfo::SavePoint</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a632ec82029fec352e6e4daed322f7e7a">llvm::yaml::MachineFrameInfo::StackSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a7b5941aef995e9272fb38c7b69fbb6e4">llvm::yaml::StringValue::Value</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### convert() {#afef1b1a235ce94996013a71608e08f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convert (<a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> &amp; ConstantPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/machineconstantpoolvalue/#a34eefb2436721ce2f60fbeb30e039401">llvm::yaml::MachineConstantPoolValue::Alignment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a8ebb130d06aa8c1b7de125c912bca5c0">llvm::yaml::MachineFunction::Constants</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineconstantpoolvalue/#abd06f2046059641752f80d93445b3bfe">llvm::yaml::MachineConstantPoolValue::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineconstantpoolvalue/#a1f67969e45dc74b6c3d53634a08bd524">llvm::yaml::MachineConstantPoolValue::IsTargetSpecific</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a62213d5211c9d944e5ede1f0059a6ae2">llvm::Value::printAsOperand</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machineconstantpoolvalue/#a04aee810d665c06eef94a092f82a69a8">llvm::yaml::MachineConstantPoolValue::Value</a>.</p>

</div>
</div>

### convert() {#a144cc64259d65d3f419f9d176fcf8078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convert (<a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable">yaml::MachineJumpTable</a> &amp; YamlJTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo">MachineJumpTableInfo</a> &amp; JTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable/#a6986f1a514dddef9e9217329a45b54cc">llvm::yaml::MachineJumpTable::Entries</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#ab63740cb84cbbb0300d8fd6cf987928d">llvm::MachineJumpTableInfo::getEntryKind</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#af9c60f4a0193375a5dd205fb945107a8">llvm::MachineJumpTableInfo::getJumpTables</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable/#ac8a93874ae04bba919a09c023a2170f0">llvm::yaml::MachineJumpTable::Kind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>

</div>
</div>

### convertCalledGlobals() {#a5982dea08cc92ad6fd8776a506980a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convertCalledGlobals (<a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleslottracker">MachineModuleSlotTracker</a> &amp; MST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a38c6e87eb849a07b79b7c06a19fdf659">llvm::yaml::MachineFunction::CalledGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ae492969b53e63471494e412f431e5028">llvm::MachineFunction::getCalledGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#aad72f291464c14665189a84050f38376">print</a>.</p>

</div>
</div>

### convertCallSiteObjects() {#aa43a432a700f337af56c8f2d1db9fe0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convertCallSiteObjects (<a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/callsiteinfo/#adccb12eeea27de5fcd53fd77fddd8292">llvm::yaml::CallSiteInfo::ArgForwardingRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/callsiteinfo/argregpair/#a5fd19bf2909e667812d01af7a72f1a54">llvm::yaml::CallSiteInfo::ArgRegPair::ArgNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineinstrloc/#aec118b50f06a567a4cd9c2672df78eca">llvm::yaml::MachineInstrLoc::BlockNum</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/callsiteinfo/#ae24004be60178b9a2e658d0a8c81d25f">llvm::yaml::CallSiteInfo::CallLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#aadfb30b1968ac77ae1d8adabab992c5f">llvm::yaml::MachineFunction::CallSitesInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6f7a9feaea337124196cf22723879cf4">llvm::MachineFunction::getCallSitesInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineinstrloc/#a2fa0de3b3a876eac2d341f1c52478242">llvm::yaml::MachineInstrLoc::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a5861c278d9a814fd24723840f9d91cbf">printRegMIR</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/callsiteinfo/argregpair/#adcf1f6506647532763d3169845f35491">llvm::yaml::CallSiteInfo::ArgRegPair::Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#aad72f291464c14665189a84050f38376">print</a>.</p>

</div>
</div>

### convertEntryValueObjects() {#aa02f64dd0aa867287b5ad17200de097a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convertEntryValueObjects (<a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a59151a92c7061811f3634c5bb91f066d">llvm::yaml::MachineFunction::EntryValueObjects</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/entryvalueobject/#aca029e519974ecc0a8450f0761b7c8e4">llvm::yaml::EntryValueObject::EntryValueRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a0976d700c47dfb0f9e54a225f9e2bb0b">llvm::MachineFunction::getEntryValueVariableDbgInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a5861c278d9a814fd24723840f9d91cbf">printRegMIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a86f57e7a60bb7ee3c2c7b44edd900081">printStackObjectDbgInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#aad72f291464c14665189a84050f38376">print</a>.</p>

</div>
</div>

### convertMachineMetadataNodes() {#ae7de4da09df7011d92c1f4abd46134a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convertMachineMetadataNodes (<a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleslottracker">MachineModuleSlotTracker</a> &amp; MST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinemoduleslottracker/#aac196d286114a87387bcd505f13c5d6b">llvm::MachineModuleSlotTracker::collectMachineMDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a2baf55b45f594519e22af6975eea84e2">llvm::yaml::MachineFunction::MachineMetadataNodes</a>.</p>


<p>Referenced by <a href="#aad72f291464c14665189a84050f38376">print</a>.</p>

</div>
</div>

### convertStackObjects() {#afb28916bca65c0b9e9ee811613c51895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::convertStackObjects (<a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction">yaml::MachineFunction</a> &amp; YMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#adcf8c43175fbd961f1ce764f66eebb65">llvm::yaml::FixedMachineStackObject::Alignment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a213ca3de1b6abfde311fe386e3170445">llvm::yaml::MachineStackObject::Alignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-mirprinter-cpp-/frameindexoperand/#ad1245948287d60a5384eb715fbcae6e8">anonymous{MIRPrinter.cpp}::FrameIndexOperand::create</a>, <a href="/web-llvm/docs/api/structs/anonymous-mirprinter-cpp-/frameindexoperand/#a0d7e359161b639dcfa5307afd85dfe96">anonymous{MIRPrinter.cpp}::FrameIndexOperand::createFixed</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#a8f6272acd5c26ffaf9ee9c2ac6b7c88ba1629b94f1b44d8bff2c9260b5108cbca">llvm::yaml::FixedMachineStackObject::DefaultType</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a00910689f93f2d2788fd111a0f5f3c98a06d15fb320646591d0dc76f381faa599">llvm::yaml::MachineStackObject::DefaultType</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ac62b09916d93504555ac2dfebad458f0">llvm::yaml::MachineFunction::FixedStackObjects</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#af74e9ad9493c6d667c9ffc71941e0468">llvm::yaml::MachineFunction::FrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#afb21232f3c7815e299a2ac4045079ce2">llvm::yaml::MachineFrameInfo::FunctionContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#afca388351fa4893f6e67476db9350983">llvm::MachineFrameInfo::getFunctionContextIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a896b32f96f723bbb50eab23758900f5e">llvm::MachineFunction::getInStackSlotVariableDbgInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a23eb9fb6560e43fa6164b4ef35654628">llvm::MachineFrameInfo::getLocalFrameObjectCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a4987e73cba3f5835d640322be09d98bd">llvm::MachineFrameInfo::getLocalFrameObjectMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad8ccc7c575c4513731612b1d73b4bac0">llvm::MachineFrameInfo::getNumFixedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a171600b1de399e1d60976508ffb38ea3">llvm::MachineFrameInfo::getObjectAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae70474766f2a88bab5b2b77bcb22212b">llvm::MachineFrameInfo::getObjectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac51e2d34abb79b72afef355fac525c76">llvm::MachineFrameInfo::getObjectIndexEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5ee88eb786413b2cf541122aa749392c">llvm::MachineFrameInfo::getStackProtectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae2c878d38ca7ead514ef744f46e05779">llvm::MachineFrameInfo::hasFunctionContextIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac7c993678733273ea9d16db7ff87b2c6">llvm::MachineFrameInfo::hasStackProtectorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#a34136ebd06934ffa15bdafe42bd586c4">llvm::yaml::FixedMachineStackObject::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a16288742cf6e0d65dbab675c04f95160">llvm::yaml::MachineStackObject::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#a7c5a3655e0cdf21eff37fc4ec2b590e8">llvm::yaml::FixedMachineStackObject::IsAliased</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#afe20684ee4170df6085d75ef85f0124a">llvm::MachineFrameInfo::isAliasedObjectIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#af5302d38d9a16eee93f13a1579c8773d">llvm::MachineFrameInfo::isDeadObjectIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#a6292cacd571b7bc4996f493fec15cd06">llvm::yaml::FixedMachineStackObject::IsImmutable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a5eab840dac82571e53cc5f1c05643e2a">llvm::MachineFrameInfo::isImmutableObjectIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a91b0115deec3489d7e082a4a13f022ff">llvm::MachineFrameInfo::isSpillSlotObjectIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab86af583f3ac779bb3f74071d36b5923">llvm::MachineFrameInfo::isVariableSizedObjectIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#aa69a1b0c3e488112647e118d9afd3b4e">llvm::yaml::MachineStackObject::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#af357a86e2819b338da3213d7eb54e4ce">llvm::yaml::FixedMachineStackObject::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#aca627bc37ee24e0d173ec884b75a2060">llvm::yaml::MachineStackObject::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a5861c278d9a814fd24723840f9d91cbf">printRegMIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a86f57e7a60bb7ee3c2c7b44edd900081">printStackObjectDbgInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#aa7c297367c0cce1855e484d15703b759">llvm::MIPrinter::printStackObjectReference</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#a4c4c3d07c200eee5b8b4a130f360f2c5">llvm::yaml::FixedMachineStackObject::Size</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a94c7713be0ecaa20523113f374579e7c">llvm::yaml::MachineStackObject::Size</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#a8f6272acd5c26ffaf9ee9c2ac6b7c88badcfc39ed7b8ef2094eefb99c5489ea33">llvm::yaml::FixedMachineStackObject::SpillSlot</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a00910689f93f2d2788fd111a0f5f3c98ae1857f4d9ec015e8ad5d2ee7e314a547">llvm::yaml::MachineStackObject::SpillSlot</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#aba57b09333f65959ae4d5a06a71f4d03">llvm::yaml::FixedMachineStackObject::StackID</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a7b164fea5d497b7269e1fc317069bd11">llvm::yaml::MachineStackObject::StackID</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a26ee805cbe23d49eeb1ec869ee64b831">llvm::yaml::MachineFunction::StackObjects</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a7b38bb0439934cfd108a4e94039817d3">llvm::yaml::MachineFrameInfo::StackProtector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject/#aa3435c2d7140dfa0f0c8372d34c1082c">llvm::yaml::FixedMachineStackObject::Type</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a39ab4471a9d7e007d019f04b5d991231">llvm::yaml::MachineStackObject::Type</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a7b5941aef995e9272fb38c7b69fbb6e4">llvm::yaml::StringValue::Value</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject/#a00910689f93f2d2788fd111a0f5f3c98a01e62a4d3114de10ceb202f080f4f84f">llvm::yaml::MachineStackObject::VariableSized</a>.</p>


<p>Referenced by <a href="#aad72f291464c14665189a84050f38376">print</a>.</p>

</div>
</div>

### print() {#aad72f291464c14665189a84050f38376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a3c7726b1a6b7f283b069bbb0b635475f">llvm::yaml::MachineFunction::Alignment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a10b0117a0460fe70fd0e4740a0a41241">llvm::yaml::MachineFunction::Body</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a2f5576db3c62625645adc327ee4f5052">llvm::yaml::MachineFunction::CallsEHReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a768ff6dfb15d23afedd7f07501afee9e">llvm::MachineFunction::callsEHReturn</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a31b15da483d0a8768ca941f4ca1fae7d">llvm::yaml::MachineFunction::CallsUnwindInit</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6799fb8536b173a2078ef97e1f0d16ec">llvm::MachineFunction::callsUnwindInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a8ede31e560f002894d3cafea50fc7a42">convert</a>, <a href="#a5982dea08cc92ad6fd8776a506980a69">convertCalledGlobals</a>, <a href="#aa43a432a700f337af56c8f2d1db9fe0b">convertCallSiteObjects</a>, <a href="#aa02f64dd0aa867287b5ad17200de097a">convertEntryValueObjects</a>, <a href="#ae7de4da09df7011d92c1f4abd46134a2">convertMachineMetadataNodes</a>, <a href="#afb28916bca65c0b9e9ee811613c51895">convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a27e242bef133e4b324f5b96791fc5c60">llvm::MachineFunction::DebugValueSubstitutions</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#add3bc1e663452cbc0efc2a9dba55b83f">llvm::yaml::MachineFunction::DebugValueSubstitutions</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#aeea0f7fcb710f25aae085b35964183ae">llvm::yaml::MachineFunction::ExposesReturnsTwice</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4b94e0ca517e149914aa0c34ee06c9fa">llvm::MachineFunction::exposesReturnsTwice</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a8014afd87e04236365d1796e38bc15f5">llvm::MachineFunctionProperties::FailedISel</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a27d7806fe25e0c00e75bdc3a94c03c62">llvm::yaml::MachineFunction::FailedISel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a006012900aff2102a22e6424f2994592">llvm::MachineFunctionProperties::FailsVerification</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a0e5937af98ee91491e15bcad511fbae7">llvm::yaml::MachineFunction::FailsVerification</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#af74e9ad9493c6d667c9ffc71941e0468">llvm::yaml::MachineFunction::FrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a896f484b6a40f21209ce74312562539a">llvm::MachineFunction::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad828deab7de3b5f4d03fac86e26adae9">llvm::MachineFunction::getJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ace3586455329b8de92d6857cc4e5a255">llvm::yaml::MachineFunction::HasEHCatchret</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a41bb88fc40dae7727e4074a000092415">llvm::MachineFunction::hasEHCatchret</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#accac34c441267d31490a426fa871c892">llvm::yaml::MachineFunction::HasEHFunclets</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a982bf1866296321d833c4c54011a9393">llvm::yaml::MachineFunction::HasEHScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aed8ca0e9ecd3747a452827f9a9a95e4d">llvm::MachineFunction::hasEHScopes</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a58d5289a2652958a400724277203ddcc">llvm::yaml::MachineFunction::HasFakeUses</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adc9da4e965260c3373d6b6371e49d0e5">llvm::MachineFunction::hasFakeUses</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aacef05f16d3e71703f08bb4677e1d7a2">llvm::MachineFunctionProperties::hasProperty</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ab3ffdf1d35d7990b7638d08bc6218a6b">llvm::yaml::MachineFunction::HasWinCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4a8d56726b9e91d336422a546d126a0f">llvm::MachineFunction::hasWinCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ae60e01471d2263c6c6ed653bd7d05a93">llvm::yaml::MachineFunction::IsOutlined</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa92182f8698ec3756a39b8c4276efa25">llvm::MachineFunction::isOutlined</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96">llvm::MachineFunctionProperties::IsSSA</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#acaae3808253574ed9ae1b6297534ef2d">llvm::yaml::MachineFunction::IsSSA</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ae6bdcb605d4ef43e0e7486b009ce49a0">llvm::yaml::MachineFunction::JumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1aefa6e814420e5fc1dfad353869159a37">llvm::MachineFunctionProperties::Legalized</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#add00963bb9e345967a5d15e26a94ea0c">llvm::yaml::MachineFunction::Legalized</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#ade5f2c6b21e9075909823e4f3383520b">llvm::yaml::MachineFunction::MachineFuncInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#aba2e8ec06abbe646d4bd35e6a6e3a97c">llvm::yaml::MachineFunction::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76eece0bfd57256980609b66faaef22c">llvm::MachineFunctionProperties::NoPHIs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a65c8e995cbc256c9fe661a05db91706c">llvm::yaml::MachineFunction::NoPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a925ca7323b68ce24d231f0045b01b8e2">llvm::yaml::MachineFunction::NoVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#a3217d1ff332f5c57cf87c02208afb5cc">llvm::MIPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a062927be2f9d18d9995e64b0779c3dcf">llvm::MachineFunctionProperties::RegBankSelected</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a5c415cc48ef81a0d2b31ab5bd9dcf281">llvm::yaml::MachineFunction::RegBankSelected</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a91b442d385b54e1418d81adc34871053">llvm::MachineFunctionProperties::Selected</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a4c9919ff2d03b35595aa261a510e1f0d">llvm::yaml::MachineFunction::Selected</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#af93638ce95bf9bc94971201e48165b3a">llvm::yaml::Output::setWriteDefaultValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#ac7ff44093d66da87e6bc5b91d257af04">SimplifyMIR</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76b22d924565975a49b2283fa838e5f2">llvm::MachineFunctionProperties::TracksDebugUserValues</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a8757f3219b5b658572cec694611f0b64">llvm::yaml::MachineFunction::TracksDebugUserValues</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunction/#a884b692c5c3ebbbfc7ac1d55b7d95ed4">llvm::yaml::MachineFunction::UseDebugInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2593b6762f74e112d695516c3b6fa9ce">llvm::MachineFunction::useDebugInstrRef</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/blockstringvalue/#a3e6ec08737f4978c37a681cfbd0c9f65">llvm::yaml::BlockStringValue::Value</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue/#a7b5941aef995e9272fb38c7b69fbb6e4">llvm::yaml::StringValue::Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### initRegisterMaskIds() {#aae4cf74ec548be92345368213cddb699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIRPrinter::initRegisterMaskIds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MMI {#aa650480e2e3cd4b27145b95fb1a53977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineModuleInfo&amp; llvm::MIRPrinter::MMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

### OS {#a4444b277de48f6ce1fff578c50a6c4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::MIRPrinter::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

### RegisterMaskIds {#a8e2c5e6685f4c0796000c449817b3d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const uint32_t *, unsigned&gt; llvm::MIRPrinter::RegisterMaskIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

### StackObjectOperandMapping {#a15d89a6359fcc250f503a1f771901c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;int, FrameIndexOperand&gt; llvm::MIRPrinter::StackObjectOperandMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps from stack object indices to operand indices which will be used when printing frame index machine operands.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
