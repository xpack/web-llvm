---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xtensaconstantpoolsymbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XtensaConstantPoolSymbol` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol">XtensaConstantPoolSymbol</a> - Xtensa-specific constantpool values for external symbols. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::XtensaConstantPoolSymbol { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fab8cab84a17be97cedf58e39eb1f00">XtensaConstantPoolSymbol</a> (LLVMContext &amp;C, const char *S, unsigned Id, bool PrivLinkage, XtensaCP::XtensaCPModifier Modifier=XtensaCP::no_modifier)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a70fc55b97db86abad56d9f3985eaf">getSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc9f5dc083392e165c86e73ab9630dd2">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbdcbb70749af1d429853ea9ed3a857">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8efbf1c50c4090ac62d919f2473d02d">hasSameValue</a> (XtensaConstantPoolValue *ACPV) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasSameValue - Return true if this <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> constpool value can share the same constantpool entry as another <a href="/web-llvm/docs/api/namespaces/llvm/xtensa">Xtensa</a> constpool value. <a href="#ad8efbf1c50c4090ac62d919f2473d02d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae646f3b2badcba4a679fec3dfed5d872">isPrivateLinkage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba4298ae23c345473e154565f9e8358">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#a7ba4298ae23c345473e154565f9e8358">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78fcfb95e981f3eeb99b9404f19622bc">equals</a> (const XtensaConstantPoolSymbol *A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2fe37501c869b451ecd1cfd4ad3d0f">S</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f02ee531ff50ddb02795245218e5b3">PrivateLinkage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol">XtensaConstantPoolSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a487b19cfd3f5516da934304d395dd">Create</a> (LLVMContext &amp;C, const char *S, unsigned ID, bool PrivLinkage, XtensaCP::XtensaCPModifier Modifier=XtensaCP::no_modifier)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7951ef0c320d3169e91a216bf9414b40">classof</a> (const XtensaConstantPoolValue *ACPV)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol">XtensaConstantPoolSymbol</a> - Xtensa-specific constantpool values for external symbols.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### XtensaConstantPoolSymbol() {#a3fab8cab84a17be97cedf58e39eb1f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaConstantPoolSymbol::XtensaConstantPoolSymbol (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * S, unsigned Id, bool PrivLinkage, <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ce">XtensaCP::XtensaCPModifier</a> Modifier=<a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ceab799a87d12a8af0b475611ee234205c1">XtensaCP::no_modifier</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#a3cbdcbb70749af1d429853ea9ed3a857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XtensaConstantPoolSymbol::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#ae3d6cad9352423bf26af9b5a0bb3b2ab">llvm::XtensaConstantPoolValue::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### equals() {#a78fcfb95e981f3eeb99b9404f19622bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolSymbol::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolsymbol">XtensaConstantPoolSymbol</a> * A)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a617163adacda2b48ac39403c1821fcfa">llvm::XtensaConstantPoolValue::equals</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#abc9f5dc083392e165c86e73ab9630dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int XtensaConstantPoolSymbol::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a3c10be993d9d234692503295df2b2f58">llvm::XtensaConstantPoolValue::getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getSymbol() {#ae0a70fc55b97db86abad56d9f3985eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::XtensaConstantPoolSymbol::getSymbol ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### hasSameValue() {#ad8efbf1c50c4090ac62d919f2473d02d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XtensaConstantPoolSymbol::hasSameValue (<a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> * ACPV)</td>
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

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a05980aae61642ceb04476b05b56766af">llvm::XtensaConstantPoolValue::hasSameValue</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a765edbf8d35f03adf16199d204125b08">llvm::XtensaConstantPoolValue::XtensaConstantPoolValue</a>.</p>

</div>
</div>

### isPrivateLinkage() {#ae646f3b2badcba4a679fec3dfed5d872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolSymbol::isPrivateLinkage ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ac8d6e594b7d8069d02f1feb6d6781ea8">llvm::XtensaAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### print() {#a7ba4298ae23c345473e154565f9e8358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XtensaConstantPoolSymbol::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a5d767be0fbed9e21c5dbd08ca46b932b">llvm::XtensaConstantPoolValue::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PrivateLinkage {#ad5f02ee531ff50ddb02795245218e5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolSymbol::PrivateLinkage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>

</div>
</div>

### S {#a5e2fe37501c869b451ecd1cfd4ad3d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::XtensaConstantPoolSymbol::S</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a7951ef0c320d3169e91a216bf9414b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XtensaConstantPoolSymbol::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue">XtensaConstantPoolValue</a> * ACPV)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a1ea124d71c6604a6ac7787d60ee8edad">llvm::XtensaConstantPoolValue::isExtSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensaconstantpoolvalue/#a765edbf8d35f03adf16199d204125b08">llvm::XtensaConstantPoolValue::XtensaConstantPoolValue</a>.</p>

</div>
</div>

### Create() {#ab0a487b19cfd3f5516da934304d395dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XtensaConstantPoolSymbol * XtensaConstantPoolSymbol::Create (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * S, unsigned ID, bool PrivLinkage, <a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ce">XtensaCP::XtensaCPModifier</a> Modifier=<a href="/web-llvm/docs/api/namespaces/llvm/xtensacp/#ab65f273c30eeb4ef6d0a162bd53b40ceab799a87d12a8af0b475611ee234205c1">XtensaCP::no_modifier</a>)</td>
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



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-h">XtensaConstantPoolValue.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaconstantpoolvalue-cpp">XtensaConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
