---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cskyconstantpoolmbb
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CSKYConstantPoolMBB` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb">CSKYConstantPoolMBB</a> - CSKY-specific constantpool value of a machine basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CSKYConstantPoolMBB { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">Target/CSKY/CSKYConstantPoolValue.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue">CSKYConstantPoolValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue">CSKYConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/csky">CSKY</a> specific constantpool value. <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687cbece100be5502de8ccdb043dd803">CSKYConstantPoolMBB</a> (Type *Ty, const MachineBasicBlock *Mbb, unsigned PCAdjust, CSKYCP::CSKYCPModifier Modifier, bool AddCurrentAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd57b5434de79ef4498ab86fad228004">getMBB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05461131c89151c1ba2c11b52f9e6cc3">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a073a968de1d890ffa42595e9c09d1902">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac036b42b4583627d58c0aeec5495474c">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#ac036b42b4583627d58c0aeec5495474c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538974a817f929fa65fa1cd5845f3bfd">equals</a> (const CSKYConstantPoolMBB *A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe5ccc036d30ffbbadb8768cfa9b475">MBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb">CSKYConstantPoolMBB</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355518ff0b8c0aa7c495bfa151dc6169">Create</a> (Type *Ty, const MachineBasicBlock *Mbb, unsigned PCAdjust)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c473a11f98fdd74cd2a05eac8c141b">classof</a> (const CSKYConstantPoolValue *ACPV)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb">CSKYConstantPoolMBB</a> - CSKY-specific constantpool value of a machine basic block.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### CSKYConstantPoolMBB() {#a687cbece100be5502de8ccdb043dd803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYConstantPoolMBB::CSKYConstantPoolMBB (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Mbb, unsigned PCAdjust, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4">CSKYCP::CSKYCPModifier</a> Modifier, bool AddCurrentAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#a073a968de1d890ffa42595e9c09d1902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantPoolMBB::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#ac2dce8ece8c4b01f78f80f643036681c">llvm::CSKYConstantPoolValue::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### equals() {#a538974a817f929fa65fa1cd5845f3bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolMBB::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb">CSKYConstantPoolMBB</a> * A)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a3f2211770c225a59cad39f4621a24404">llvm::CSKYConstantPoolValue::equals</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#a05461131c89151c1ba2c11b52f9e6cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CSKYConstantPoolMBB::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a7f59aeed19f66ec8099052e3aa47c9c9">llvm::CSKYConstantPoolValue::getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getMBB() {#acd57b5434de79ef4498ab86fad228004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock * llvm::CSKYConstantPoolMBB::getMBB ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>

</div>
</div>

### print() {#ac036b42b4583627d58c0aeec5495474c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantPoolMBB::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a310e47e5146eaa80264533a27084604d">llvm::CSKYConstantPoolValue::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MBB {#a7fe5ccc036d30ffbbadb8768cfa9b475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::CSKYConstantPoolMBB::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a37c473a11f98fdd74cd2a05eac8c141b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolMBB::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue">CSKYConstantPoolValue</a> * ACPV)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a348e1e38604c1fc005a62ced08c6f583">llvm::CSKYConstantPoolValue::CSKYConstantPoolValue</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a1e80f3fe8022c9ac777591115ae2c637">llvm::CSKYConstantPoolValue::isMachineBasicBlock</a>.</p>

</div>
</div>

### Create() {#a355518ff0b8c0aa7c495bfa151dc6169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYConstantPoolMBB * CSKYConstantPoolMBB::Create (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Mbb, unsigned PCAdjust)</td>
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



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a11f72aa51db1915ad266a52e760f28af">llvm::CSKYCP::ADDR</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a211fb7d504116ba5fb89bb4bc22a9070">llvm::CSKYConstantPoolValue::PCAdjust</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
