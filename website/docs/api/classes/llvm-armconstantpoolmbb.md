---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armconstantpoolmbb
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMConstantPoolMBB` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb">ARMConstantPoolMBB</a> - ARM-specific constantpool value of a machine basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ARMConstantPoolMBB { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">Target/ARM/ARMConstantPoolValue.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> specific constantpool value. <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708100fb3b41314bf6724320e06ac0bd">ARMConstantPoolMBB</a> (LLVMContext &amp;C, const MachineBasicBlock *mbb, unsigned id, unsigned char PCAdj, ARMCP::ARMCPModifier Modifier, bool AddCurrentAddress)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dcf159948d2d08c9315225770796cae">getMBB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a473e733e2610bba6d595ae063587919d">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d19ca1e52af861e38e22e4800ad5652">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8307b3875610081435c5ab30500a29f8">hasSameValue</a> (ARMConstantPoolValue *ACPV) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasSameValue - Return true if this <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> constpool value can share the same constantpool entry as another <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> constpool value. <a href="#a8307b3875610081435c5ab30500a29f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8d429cc1ce71cd4456657f4e6463f3">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#a8b8d429cc1ce71cd4456657f4e6463f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf1ce7e52763a63d121be75302ada45">equals</a> (const ARMConstantPoolMBB *A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b00fa11343a9e3fc501f0b0738b13c">MBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb">ARMConstantPoolMBB</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c19796f37809c5c4b35674958d7dde8">Create</a> (LLVMContext &amp;C, const MachineBasicBlock *mbb, unsigned ID, unsigned char PCAdj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08577dd62b00230909575dcdefd45f6">classof</a> (const ARMConstantPoolValue *ACPV)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb">ARMConstantPoolMBB</a> - ARM-specific constantpool value of a machine basic block.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### ARMConstantPoolMBB() {#a708100fb3b41314bf6724320e06ac0bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolMBB::ARMConstantPoolMBB (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb, unsigned id, unsigned char PCAdj, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a> Modifier, bool AddCurrentAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#a4d19ca1e52af861e38e22e4800ad5652}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantPoolMBB::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#af658836bbc9432b5e44b40dfde9f1904">llvm::ARMConstantPoolValue::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### equals() {#a2bf1ce7e52763a63d121be75302ada45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolMBB::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb">ARMConstantPoolMBB</a> * A)</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ab926b42ec064c1dd870bb93670d1cf91">llvm::ARMConstantPoolValue::equals</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#a473e733e2610bba6d595ae063587919d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ARMConstantPoolMBB::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a984cea3549f15471d09a91ba2f60d41b">llvm::ARMConstantPoolValue::getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getMBB() {#a2dcf159948d2d08c9315225770796cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock * llvm::ARMConstantPoolMBB::getMBB ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

### hasSameValue() {#a8307b3875610081435c5ab30500a29f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantPoolMBB::hasSameValue (<a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> * ACPV)</td>
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

<p>hasSameValue - Return true if this <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> constpool value can share the same constantpool entry as another <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> constpool value.</p>

<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">llvm::ARMConstantPoolValue::ARMConstantPoolValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ae204089fb50ef2edd07a7d18c5c4b79f">llvm::ARMConstantPoolValue::hasSameValue</a>.</p>

</div>
</div>

### print() {#a8b8d429cc1ce71cd4456657f4e6463f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantPoolMBB::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>print - Implement operator&lt;&lt;</p>

<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a7b8d7ad0899bfee6d615c35f0dfd9841">llvm::ARMConstantPoolValue::print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MBB {#a57b00fa11343a9e3fc501f0b0738b13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::ARMConstantPoolMBB::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ac08577dd62b00230909575dcdefd45f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolMBB::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> * ACPV)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">llvm::ARMConstantPoolValue::ARMConstantPoolValue</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a8761e4a93682b13870657a5b83612ffc">llvm::ARMConstantPoolValue::isMachineBasicBlock</a>.</p>

</div>
</div>

### Create() {#a6c19796f37809c5c4b35674958d7dde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolMBB * ARMConstantPoolMBB::Create (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb, unsigned ID, unsigned char PCAdj)</td>
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



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85ae9103902078db9ff4f9a7f5477b04c76">llvm::ARMCP::no_modifier</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
