---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcregaliasiterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCRegAliasIterator` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator">MCRegAliasIterator</a> enumerates all registers aliasing Reg. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCRegAliasIterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eadaf6feef51fbb1fe642412ce54ae9">MCRegAliasIterator</a> (MCRegister Reg, const MCRegisterInfo *MCRI, bool IncludeSelf)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657e4584ea0df15863e1a9268e21c180">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator">MCRegAliasIterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7027113b94deef0ada2c129633af705">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac336c049c12ead7be5b86e6d046f8ab0">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23d6170c55387488544c50d72057dc20">It</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd142d10299d8fa7a41f38f6a000b305">End</a> = nullptr</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator">MCRegAliasIterator</a> enumerates all registers aliasing Reg.</p>

<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCRegAliasIterator() {#a2eadaf6feef51fbb1fe642412ce54ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCRegAliasIterator::MCRegAliasIterator (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * MCRI, bool IncludeSelf)</td>
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



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#af7027113b94deef0ada2c129633af705">operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#a657e4584ea0df15863e1a9268e21c180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::MCRegAliasIterator::operator* ()</td>
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



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### operator++() {#af7027113b94deef0ada2c129633af705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegAliasIterator &amp; llvm::MCRegAliasIterator::operator++ ()</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac336c049c12ead7be5b86e6d046f8ab0">isValid</a> and <a href="#a2eadaf6feef51fbb1fe642412ce54ae9">MCRegAliasIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isValid() {#ac336c049c12ead7be5b86e6d046f8ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegAliasIterator::isValid ()</td>
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



<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a6afe81a8562ad740b6edd4c536974067">addRegAndItsAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a65d34a1acd6c2473aab0fabe963fccfb">AnyAliasLiveIn</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/callmutation/#a6cd9122ce8216f80dd0921f844f7b7e1">llvm::HexagonSubtarget::CallMutation::apply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#abbaf6b527fda317964759a8917f436cd">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a37a1b9361cb4ed78aa4af0973696f7fb">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp/#aef8f01c925c0c7beb94976a8f86a9af1">collectRegDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aa3dfee03e12575026fa0a0461348a756">llvm::MachineRegisterInfo::disableCalleeSavedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#ae82cb5b8bd04147ce1ebe063f447c718">findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a48595fc4feb49d51ed2eecbf73dadc24">llvm::X86RegisterInfo::findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a85c1ec2b6a80a274d6f070a19045d392">llvm::rdf::PhysicalRegisterInfo::getAliasSet</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aed31f9e731d0e88307aa322db45a11d8">llvm::PPCRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/sparcregisterinfo/#aa433f99693e51b79b0ed2d9209427aab">llvm::SparcRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a2928124814b8fb3a7ca66289f7c20dee">llvm::SystemZRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/veregisterinfo/#a36ef2502150597fe6fd54aadbc0d429c">llvm::VERegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a339d32ea1f7597a13e849615446a7d26">llvm::X86RegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#ac546420f6cd906a9b17e41c43e720e98">TransferTracker::isCalleeSaved</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/instrrefbasedldv/#ad778dafd8a5d853569fe78079b6960b7">LiveDebugValues::InstrRefBasedLDV::isCalleeSavedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#abe36a37a2974f73af12228bccbaef0b4">llvm::MachineRegisterInfo::isConstantPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af2a209ffefa8ca1df76b99fe3c2e2cc4">llvm::MachineRegisterInfo::isPhysRegModified</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#afd23983bb9fb4af65e27b56cc506edbc">llvm::MachineRegisterInfo::isPhysRegUsed</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a69c882828373f9113a87c3bb0823695d">anonymous{DelaySlotFiller.cpp}::Filler::IsRegInSet</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaidelayslotfiller-cpp-/filler/#a72a4812c58fcd7d9724a62d3b313871d">anonymous{LanaiDelaySlotFiller.cpp}::Filler::isRegInSet</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#ae118b50388837cac4d807896b91f111e">LiveDebugValues::MLocTracker::MLocTracker</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#a6f94ed74de2043a25224558de11aea10">needToReserveScavengingSpillSlots</a>, <a href="#af7027113b94deef0ada2c129633af705">operator++</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa4d444250018e8e065ca05a73bdf3d35">llvm::rdf::Liveness::resetKills</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#a20589df6cd2c2e12e77a1741a0e4223e">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::run</a>, <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix/#aa90dd7f08ca467a5d6dc3215fb98ee51">llvm::ExecutionDomainFix::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo/#ac892fad5c3d0080c8cca7557659668d5">llvm::RegisterClassInfo::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseframelowering-cpp/#a8058af7f16d3ab91b5a51f5102843b96">setAliasRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#aea759a40aec24ad7cbc5c1761cdf2dbd">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::setCallerSaved</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#adb26143a53c2c642b1ee05805ba3d3cb">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::setUnallocatableRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#abd095bb58a0243946704d20d3559d420">llvm::AggressiveAntiDepBreaker::StartBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#adb4573a84f25279673e3906914132a39">llvm::CriticalAntiDepBreaker::StartBlock</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#ad19536429e02ee5405f51a51bbb256cd">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineFunctionAfter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### End {#acd142d10299d8fa7a41f38f6a000b305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg* llvm::MCRegAliasIterator::End = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### It {#a23d6170c55387488544c50d72057dc20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg* llvm::MCRegAliasIterator::It = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
