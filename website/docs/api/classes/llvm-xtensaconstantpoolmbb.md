---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xtensaconstantpoolmbb
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `XtensaConstantPoolMBB` Class

<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb">XtensaConstantPoolMBB</a> - Xtensa-specific constantpool value of a machine basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::XtensaConstantPoolMBB { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">Target/Xtensa/XtensaConstantPoolValue.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> specific constantpool value. <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b38e5425bf9426c0bced14d27f6fe5">XtensaConstantPoolMBB</a> (LLVMContext &amp;C, const MachineBasicBlock *M, unsigned ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe6729bdeb44fc622f6416500712f73">getMBB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae198a336f23286160403a87d921ba1a0">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7ad25a839945b406cfd0a799068ced">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e02d34d43f522bf9e426d914d2533e3">hasSameValue</a> (XtensaConstantPoolValue *ACPV) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasSameValue - Return true if this <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> constpool value can share the same constantpool entry as another <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> constpool value. <a href="#a5e02d34d43f522bf9e426d914d2533e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e74d1b0ffe84330d4664f6b8ed46437">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#a4e74d1b0ffe84330d4664f6b8ed46437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2356862d5a04b931aee051f7c6173356">equals</a> (const XtensaConstantPoolMBB *A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477061af5b998ab3658de7b15c7e605c">MBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb">XtensaConstantPoolMBB</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2728a556477ef41f7193f92a06a8a43c">Create</a> (LLVMContext &amp;C, const MachineBasicBlock *M, unsigned ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0005008ddddbc0cf31613e6b9ac479dc">classof</a> (const XtensaConstantPoolValue *ACPV)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb">XtensaConstantPoolMBB</a> - Xtensa-specific constantpool value of a machine basic block.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### XtensaConstantPoolMBB() {#a50b38e5425bf9426c0bced14d27f6fe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaConstantPoolMBB::XtensaConstantPoolMBB (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * M, unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#aca7ad25a839945b406cfd0a799068ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XtensaConstantPoolMBB::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#ae3d6cad9352423bf26af9b5a0bb3b2ab">llvm::XtensaConstantPoolValue::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### equals() {#a2356862d5a04b931aee051f7c6173356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolMBB::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb">XtensaConstantPoolMBB</a> * A)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a617163adacda2b48ac39403c1821fcfa">llvm::XtensaConstantPoolValue::equals</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#ae198a336f23286160403a87d921ba1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int XtensaConstantPoolMBB::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a3c10be993d9d234692503295df2b2f58">llvm::XtensaConstantPoolValue::getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getMBB() {#afbe6729bdeb44fc622f6416500712f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock * llvm::XtensaConstantPoolMBB::getMBB ()</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>

</div>
</div>

### hasSameValue() {#a5e02d34d43f522bf9e426d914d2533e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XtensaConstantPoolMBB::hasSameValue (<a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> * ACPV)</td>
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

<p>hasSameValue - Return true if this <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> constpool value can share the same constantpool entry as another <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> constpool value.</p>

<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a05980aae61642ceb04476b05b56766af">llvm::XtensaConstantPoolValue::hasSameValue</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a765edbf8d35f03adf16199d204125b08">llvm::XtensaConstantPoolValue::XtensaConstantPoolValue</a>.</p>

</div>
</div>

### print() {#a4e74d1b0ffe84330d4664f6b8ed46437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XtensaConstantPoolMBB::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a5d767be0fbed9e21c5dbd08ca46b932b">llvm::XtensaConstantPoolValue::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MBB {#a477061af5b998ab3658de7b15c7e605c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::XtensaConstantPoolMBB::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a0005008ddddbc0cf31613e6b9ac479dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolMBB::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> * ACPV)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a90c09412793e433f00e66dfc4f11bc95">llvm::XtensaConstantPoolValue::isMachineBasicBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a765edbf8d35f03adf16199d204125b08">llvm::XtensaConstantPoolValue::XtensaConstantPoolValue</a>.</p>

</div>
</div>

### Create() {#a2728a556477ef41f7193f92a06a8a43c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaConstantPoolMBB * XtensaConstantPoolMBB::Create (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * M, unsigned ID)</td>
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



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
