---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/machineoperand-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MachineOperand.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stablehashing-h">llvm/ADT/StableHashing.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loads-h">llvm/Analysis/Loads.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/mirformatter-h">llvm/CodeGen/MIRFormatter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">llvm/CodeGen/MachineJumpTableInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/pseudosourcevaluemanager-h">llvm/CodeGen/PseudoSourceValueManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irprintingpasses-h">llvm/IR/IRPrintingPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">llvm/IR/ModuleSlotTracker.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetintrinsicinfo-h">llvm/Target/TargetIntrinsicInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215563f9d37c9c9cab3f9e52f0507209">getMFIfAvailable</a> (const MachineOperand &amp;MO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d379b8b0ed1a7958e04dd5df4e473d1">getMFIfAvailable</a> (MachineOperand &amp;MO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27abdb8883d8ef8d984acaea1846fd2">tryToGetTargetInfo</a> (const MachineOperand &amp;MO, const TargetRegisterInfo *&amp;TRI, const TargetIntrinsicInfo *&amp;IntrinsicInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23060980870dd18a2719ac5468af3faf">getTargetIndexName</a> (const MachineFunction &amp;MF, int Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a451e8cfa89994a66fbc9d47ce9c3bca8">getTargetFlagName</a> (const TargetInstrInfo *TII, unsigned TF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67bc6e371d9dfd804cecd64d83fd073c">printCFIRegister</a> (unsigned DwarfReg, raw_ostream &amp;OS, const TargetRegisterInfo *TRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a> (raw_ostream &amp;OS, const BasicBlock &amp;BB, ModuleSlotTracker &amp;MST)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b99b3e536e8f7ddb0167814d1c0d50">printSyncScope</a> (raw_ostream &amp;OS, const LLVMContext &amp;Context, SyncScope::ID SSID, SmallVectorImpl&lt; StringRef &gt; &amp;SSNs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8958e62bf7c2eb551a7004ae14def896">getTargetMMOFlagName</a> (const TargetInstrInfo &amp;TII, unsigned TMMOFlag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294946bd7b49d5ef31f4f42120f75b92">printFrameIndex</a> (raw_ostream &amp;OS, int FrameIndex, bool IsFixed, const MachineFrameInfo *MFI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a> (raw_ostream &amp;OS, const MCCFIInstruction &amp;CFI, const TargetRegisterInfo *TRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a390a2d47af94ecd445ec74a3fdadca5a">PrintRegMaskNumRegs</a>("print-regmask-num-regs", cl::desc("Number of registers to limit to when " "printing regmask operands in IR dumps. " "unlimited = -1"), cl::init(32), cl::Hidden)</td>
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

### getMFIfAvailable() {#a215563f9d37c9c9cab3f9e52f0507209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction * getMFIfAvailable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2d379b8b0ed1a7958e04dd5df4e473d1">getMFIfAvailable</a>.</p>

</div>
</div>

### getMFIfAvailable() {#a2d379b8b0ed1a7958e04dd5df4e473d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction * getMFIfAvailable (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>Reference <a href="#a215563f9d37c9c9cab3f9e52f0507209">getMFIfAvailable</a>.</p>

</div>
</div>

### getTargetFlagName() {#a451e8cfa89994a66fbc9d47ce9c3bca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getTargetFlagName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, unsigned TF)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bdc6bcbf7eec4329ba1b6c91ff776d8">llvm::MachineOperand::printTargetFlags</a>.</p>

</div>
</div>

### getTargetIndexName() {#a23060980870dd18a2719ac5468af3faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getTargetIndexName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, int Index)</td>
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



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getTargetMMOFlagName() {#a8958e62bf7c2eb551a7004ae14def896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getTargetMMOFlagName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, unsigned TMMOFlag)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a4706e639e364501f6000985df1222c58">llvm::MachineMemOperand::print</a>.</p>

</div>
</div>

### printCFI() {#aba7721fa19b2ff3f14b96aaf2ba413c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printCFI (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a> &amp; CFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a31a07e509ef445f6d35b9e7cfd3bed74">llvm::MCCFIInstruction::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a0607bec0f8845b94270b8039f0d975ce">llvm::MCCFIInstruction::getLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aef30e8b2caf06dd1513a1c9aacf45097">llvm::MCCFIInstruction::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a9d7ee9c6eaabde95dd9695326a77f253">llvm::MCCFIInstruction::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a57846002cda511da6585cb417cf9d392">llvm::MCCFIInstruction::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a49509b83b020570fb6efb6c2b10b7b6f">llvm::MCCFIInstruction::getRegister2</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#abb6341197e146d69c1fa9cbde53f22d4">llvm::MCCFIInstruction::getValues</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecaea7047186e58e6304947fbe2b12963ca">llvm::MCCFIInstruction::OpAdjustCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecacbbd41f459c6cea155b66a7ba10f1058">llvm::MCCFIInstruction::OpDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca5822faf65b27795cd48bd44712d48927">llvm::MCCFIInstruction::OpDefCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca238c64d5f2c2fea57085c0238948b04f">llvm::MCCFIInstruction::OpDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecaf15acea66ebc677cba2af933cc86c953">llvm::MCCFIInstruction::OpEscape</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca41d79805b057315fb8e3593987b4fe6d">llvm::MCCFIInstruction::OpLLVMDefAspaceCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecaa66d4b16f63e1a1f48ab0a412e105d84">llvm::MCCFIInstruction::OpNegateRAState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca66624166e3d049539c5275c2a92993bc">llvm::MCCFIInstruction::OpNegateRAStateWithPC</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca74ec33979cec7221719caa137b50da3f">llvm::MCCFIInstruction::OpOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca47154c1d7af6be5e653ad8d1647efef1">llvm::MCCFIInstruction::OpRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca829be22c6230d5b270c57913ab767d66">llvm::MCCFIInstruction::OpRelOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca9725887cea764021d6f8d670f28f1ae5">llvm::MCCFIInstruction::OpRememberState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecab1624e2be4e6b5b590bcc4743241c0a8">llvm::MCCFIInstruction::OpRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca52e7e859e3f36138023caadf8991d04b">llvm::MCCFIInstruction::OpRestoreState</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecab85cb8f2dc33b315db03abc258d2d7d0">llvm::MCCFIInstruction::OpSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca3d6a7342ab1bccb9ac138911f12e2eb4">llvm::MCCFIInstruction::OpUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca3316e063e766219c3a12d004d2d10afd">llvm::MCCFIInstruction::OpWindowSave</a>, <a href="#a67bc6e371d9dfd804cecd64d83fd073c">printCFIRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af04079051720988fb6801f962d034e03">llvm::MachineOperand::printSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>.</p>

</div>
</div>

### printCFIRegister() {#a67bc6e371d9dfd804cecd64d83fd073c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printCFIRegister (unsigned DwarfReg, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

### printFrameIndex() {#a294946bd7b49d5ef31f4f42120f75b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int FrameIndex, bool IsFixed, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> * MFI)</td>
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



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a171600b1de399e1d60976508ffb38ea3">llvm::MachineFrameInfo::getObjectAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae70474766f2a88bab5b2b77bcb22212b">llvm::MachineFrameInfo::getObjectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ae6e7e975f7a4e5d535be32068a7c67df">llvm::MachineFrameInfo::isFixedObjectIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2c42d0e762a9efb66e50b7f349ee4207">llvm::MachineOperand::printStackObjectReference</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a4706e639e364501f6000985df1222c58">llvm::MachineMemOperand::print</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>.</p>

</div>
</div>

### printIRBlockReference() {#a39e0c396e9ae881eddc29a02ebc40956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printIRBlockReference (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST)</td>
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



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a8d3ee14bd6234e0fa0b97c19df3882ce">llvm::ModuleSlotTracker::getCurrentFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a6d82623735b3bd2208170d379913f2e1">llvm::ModuleSlotTracker::getLocalSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaf41c1517148f1b067536a43623d6a6b">llvm::MachineOperand::printIRSlotNumber</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aef01c7734472703b7f3d76c5af23e1d3">llvm::printLLVMNameWithoutPrefix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>.</p>

</div>
</div>

### printSyncScope() {#a12b99b3e536e8f7ddb0167814d1c0d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printSyncScope (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; SSNs)</td>
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



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">llvm::SyncScope::System</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a4706e639e364501f6000985df1222c58">llvm::MachineMemOperand::print</a>.</p>

</div>
</div>

### tryToGetTargetInfo() {#ac27abdb8883d8ef8d984acaea1846fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void tryToGetTargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *&amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> *&amp; IntrinsicInfo)</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### PrintRegMaskNumRegs {#a390a2d47af94ecd445ec74a3fdadca5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; PrintRegMaskNumRegs("print-regmask-num-regs", cl::desc("Number of registers to limit to when " "printing regmask operands in IR dumps. " "unlimited = -1"), cl::init(32), cl::Hidden)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
