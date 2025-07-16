---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xtensaconstantpoolvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XtensaConstantPoolValue` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> specific constantpool value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::XtensaConstantPoolValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">Target/Xtensa/XtensaConstantPoolValue.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue">MachineConstantPoolValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract base class for all machine specific constantpool value subclasses. <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant">XtensaConstantPoolConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant">XtensaConstantPoolConstant</a> - Xtensa-specific constant pool values for Constants (for example BlockAddresses). <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable">XtensaConstantPoolJumpTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable">XtensaConstantPoolJumpTable</a> - Xtensa-specific constantpool values for Jump Table symbols. <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb">XtensaConstantPoolMBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb">XtensaConstantPoolMBB</a> - Xtensa-specific constantpool value of a machine basic block. <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol">XtensaConstantPoolSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol">XtensaConstantPoolSymbol</a> - Xtensa-specific constantpool values for external symbols. <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765edbf8d35f03adf16199d204125b08">XtensaConstantPoolValue</a> (Type *Ty, unsigned ID, XtensaCP::XtensaCPKind Kind, XtensaCP::XtensaCPModifier Modifier=XtensaCP::no_modifier)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797e199f4f499602064f34a1f86be6e9">XtensaConstantPoolValue</a> (LLVMContext &amp;C, unsigned id, XtensaCP::XtensaCPKind Kind, XtensaCP::XtensaCPModifier Modifier=XtensaCP::no_modifier)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa527858f937e6b1b916864deea1ec6">~XtensaConstantPoolValue</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ce">XtensaCP::XtensaCPModifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b0027fb18fbf6ecb8cb10f71076f0e">getModifier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a6405e3e42df80328e697c8c1ea74c">hasModifier</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7525c2727828dfd392f8cf7ae8da79">getModifierText</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e08c2e4058c066a25c523f8f88e907">getLabelId</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac58719da1a60cfe271915c58ffbb5b3">setLabelId</a> (unsigned ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea124d71c6604a6ac7787d60ee8edad">isExtSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f68a3fb954986275c88d551990490a2">isBlockAddress</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c09412793e433f00e66dfc4f11bc95">isMachineBasicBlock</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c4946a160a9c92c1f8b866001b0ab15">isJumpTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a87ed8435d700a73e7eb9acaa58bc79">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d6cad9352423bf26af9b5a0bb3b2ab">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05980aae61642ceb04476b05b56766af">hasSameValue</a> (XtensaConstantPoolValue *ACPV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasSameValue - Return true if this <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> constpool value can share the same constantpool entry as another <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> constpool value. <a href="#a05980aae61642ceb04476b05b56766af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617163adacda2b48ac39403c1821fcfa">equals</a> (const XtensaConstantPoolValue *A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d767be0fbed9e21c5dbd08ca46b932b">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#a5d767be0fbed9e21c5dbd08ca46b932b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e48199b24d57a81f0edd142c16068c">dump</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c10be993d9d234692503295df2b2f58">getExistingMachineCPValueImpl</a> (MachineConstantPool *CP, Align Alignment)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a7b181da81f851cf9f99cae00bce06e">LabelId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#a3a525a99a5b55d48a46d23eab21558ed">XtensaCP::XtensaCPKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b1fa3c64187136e83bb4df00afed934">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ce">XtensaCP::XtensaCPModifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547e7508d7d8021cbb12f4a3eec9b102">Modifier</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> specific constantpool value.</p>


<p>This is used to represent PC-relative displacement between the address of the load instruction and the constant being loaded.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### XtensaConstantPoolValue() {#a765edbf8d35f03adf16199d204125b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaConstantPoolValue::XtensaConstantPoolValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned ID, <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#a3a525a99a5b55d48a46d23eab21558ed">XtensaCP::XtensaCPKind</a> Kind, <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ce">XtensaCP::XtensaCPModifier</a> Modifier=<a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ceab799a87d12a8af0b475611ee234205c1">XtensaCP::no_modifier</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue/#ac688aad44da54c2262096a4b5c5891f4">llvm::MachineConstantPoolValue::MachineConstantPoolValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#a4b0ae82eb679d739968c6a02509144a3">llvm::XtensaConstantPoolConstant::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable/#a9506dc9a11529716f95756e1ac8cc60b">llvm::XtensaConstantPoolJumpTable::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#a0005008ddddbc0cf31613e6b9ac479dc">llvm::XtensaConstantPoolMBB::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#a7951ef0c320d3169e91a216bf9414b40">llvm::XtensaConstantPoolSymbol::classof</a>, <a href="#a617163adacda2b48ac39403c1821fcfa">equals</a>, <a href="#a3c10be993d9d234692503295df2b2f58">getExistingMachineCPValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#a419c3ceee02083f62a1c33bf68db4f5b">llvm::XtensaConstantPoolConstant::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable/#adb52e73abdf2cd58f1171dfc9f96f30b">llvm::XtensaConstantPoolJumpTable::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#a5e02d34d43f522bf9e426d914d2533e3">llvm::XtensaConstantPoolMBB::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#ad8efbf1c50c4090ac62d919f2473d02d">llvm::XtensaConstantPoolSymbol::hasSameValue</a> and <a href="#a05980aae61642ceb04476b05b56766af">hasSameValue</a>.</p>

</div>
</div>

### XtensaConstantPoolValue() {#a797e199f4f499602064f34a1f86be6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaConstantPoolValue::XtensaConstantPoolValue (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned id, <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#a3a525a99a5b55d48a46d23eab21558ed">XtensaCP::XtensaCPKind</a> Kind, <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ce">XtensaCP::XtensaCPModifier</a> Modifier=<a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ceab799a87d12a8af0b475611ee234205c1">XtensaCP::no_modifier</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue/#ac688aad44da54c2262096a4b5c5891f4">llvm::MachineConstantPoolValue::MachineConstantPoolValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~XtensaConstantPoolValue() {#a2fa527858f937e6b1b916864deea1ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaConstantPoolValue::~XtensaConstantPoolValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#ae3d6cad9352423bf26af9b5a0bb3b2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XtensaConstantPoolValue::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#afd5f1d727eb4919552cdd16b7311a772">llvm::XtensaConstantPoolConstant::addSelectionDAGCSEId</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#aca7ad25a839945b406cfd0a799068ced">llvm::XtensaConstantPoolMBB::addSelectionDAGCSEId</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#a3cbdcbb70749af1d429853ea9ed3a857">llvm::XtensaConstantPoolSymbol::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### dump() {#aa6e48199b24d57a81f0edd142c16068c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XtensaConstantPoolValue::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>.</p>

</div>
</div>

### equals() {#a617163adacda2b48ac39403c1821fcfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolValue::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> * A)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a765edbf8d35f03adf16199d204125b08">XtensaConstantPoolValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#ac9c973431447b5f84e2fc0af4b22de6d">llvm::XtensaConstantPoolConstant::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable/#a87e5bbdd39e8bd4540b5e35b83040998">llvm::XtensaConstantPoolJumpTable::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#a2356862d5a04b931aee051f7c6173356">llvm::XtensaConstantPoolMBB::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#a78fcfb95e981f3eeb99b9404f19622bc">llvm::XtensaConstantPoolSymbol::equals</a> and <a href="#a3c10be993d9d234692503295df2b2f58">getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#a3a87ed8435d700a73e7eb9acaa58bc79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int XtensaConstantPoolValue::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getLabelId() {#a75e08c2e4058c066a25c523f8f88e907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::XtensaConstantPoolValue::getLabelId ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### getModifier() {#ae5b0027fb18fbf6ecb8cb10f71076f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaCP::XtensaCPModifier llvm::XtensaConstantPoolValue::getModifier ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### getModifierText() {#a7e7525c2727828dfd392f8cf7ae8da79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef XtensaConstantPoolValue::getModifierText ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ceab799a87d12a8af0b475611ee234205c1">llvm::XtensaCP::no_modifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ceaa8d6600b70f45981fc58530ea371d67d">llvm::XtensaCP::TPOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### hasModifier() {#a74a6405e3e42df80328e697c8c1ea74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolValue::hasModifier ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ceab799a87d12a8af0b475611ee234205c1">llvm::XtensaCP::no_modifier</a>.</p>

</div>
</div>

### hasSameValue() {#a05980aae61642ceb04476b05b56766af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XtensaConstantPoolValue::hasSameValue (<a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> * ACPV)</td>
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

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="#a765edbf8d35f03adf16199d204125b08">XtensaConstantPoolValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#a419c3ceee02083f62a1c33bf68db4f5b">llvm::XtensaConstantPoolConstant::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable/#adb52e73abdf2cd58f1171dfc9f96f30b">llvm::XtensaConstantPoolJumpTable::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#a5e02d34d43f522bf9e426d914d2533e3">llvm::XtensaConstantPoolMBB::hasSameValue</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#ad8efbf1c50c4090ac62d919f2473d02d">llvm::XtensaConstantPoolSymbol::hasSameValue</a>.</p>

</div>
</div>

### isBlockAddress() {#a9f68a3fb954986275c88d551990490a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolValue::isBlockAddress ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#a3a525a99a5b55d48a46d23eab21558eda50de8cf161cd71df130c5a4054aefd52">llvm::XtensaCP::CPBlockAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#a4b0ae82eb679d739968c6a02509144a3">llvm::XtensaConstantPoolConstant::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isExtSymbol() {#a1ea124d71c6604a6ac7787d60ee8edad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolValue::isExtSymbol ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#a3a525a99a5b55d48a46d23eab21558eda6a765aeaa4121b82d4cf318652738ce1">llvm::XtensaCP::CPExtSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#a7951ef0c320d3169e91a216bf9414b40">llvm::XtensaConstantPoolSymbol::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isJumpTable() {#a1c4946a160a9c92c1f8b866001b0ab15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolValue::isJumpTable ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#a3a525a99a5b55d48a46d23eab21558edae2ee75b083eaaa4cd4bba1d3bbe26b5c">llvm::XtensaCP::CPJumpTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable/#a9506dc9a11529716f95756e1ac8cc60b">llvm::XtensaConstantPoolJumpTable::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isMachineBasicBlock() {#a90c09412793e433f00e66dfc4f11bc95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolValue::isMachineBasicBlock ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#a3a525a99a5b55d48a46d23eab21558eda5bb965b11321e5582cb07b5314be058e">llvm::XtensaCP::CPMachineBasicBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#a0005008ddddbc0cf31613e6b9ac479dc">llvm::XtensaConstantPoolMBB::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### print() {#a5d767be0fbed9e21c5dbd08ca46b932b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XtensaConstantPoolValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#ae0b86cc075676b2312b2001a8bfeab33">llvm::XtensaConstantPoolConstant::print</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable/#aa9c6d4d95a64c0c28bfb0f8907d27a8d">llvm::XtensaConstantPoolJumpTable::print</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#a4e74d1b0ffe84330d4664f6b8ed46437">llvm::XtensaConstantPoolMBB::print</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#a7ba4298ae23c345473e154565f9e8358">llvm::XtensaConstantPoolSymbol::print</a>.</p>

</div>
</div>

### setLabelId() {#aac58719da1a60cfe271915c58ffbb5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::XtensaConstantPoolValue::setLabelId (unsigned ID)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a2aca46ca706a8a857dc668e015740e53">llvm::XtensaAsmPrinter::emitMachineConstantPoolEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getExistingMachineCPValueImpl() {#a3c10be993d9d234692503295df2b2f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::XtensaConstantPoolValue::getExistingMachineCPValueImpl (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a617163adacda2b48ac39403c1821fcfa">equals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a44361e635fd7461e3a8eeb7fc9ad4f04">llvm::getAlign</a> and <a href="#a765edbf8d35f03adf16199d204125b08">XtensaConstantPoolValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolconstant/#a1ad5f5628b9d3618c3cd4cc459b7c6ba">llvm::XtensaConstantPoolConstant::getExistingMachineCPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpooljumptable/#ac4d7a0a245173b435a87f1f9ce8141d8">llvm::XtensaConstantPoolJumpTable::getExistingMachineCPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolmbb/#ae198a336f23286160403a87d921ba1a0">llvm::XtensaConstantPoolMBB::getExistingMachineCPValue</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol/#abc9f5dc083392e165c86e73ab9630dd2">llvm::XtensaConstantPoolSymbol::getExistingMachineCPValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a8b1fa3c64187136e83bb4df00afed934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaCP::XtensaCPKind llvm::XtensaConstantPoolValue::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>

</div>
</div>

### LabelId {#a3a7b181da81f851cf9f99cae00bce06e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::XtensaConstantPoolValue::LabelId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>

</div>
</div>

### Modifier {#a547e7508d7d8021cbb12f4a3eec9b102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaCP::XtensaCPModifier llvm::XtensaConstantPoolValue::Modifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>

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
