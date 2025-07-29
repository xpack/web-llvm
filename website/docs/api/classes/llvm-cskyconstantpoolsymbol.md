---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cskyconstantpoolsymbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CSKYConstantPoolSymbol` Class

<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol">CSKYConstantPoolSymbol</a> - CSKY-specific constantpool values for external symbols. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CSKYConstantPoolSymbol { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24fd16acf7aa7a345d8be602fdd867df">CSKYConstantPoolSymbol</a> (Type *Ty, const char *S, unsigned PCAdjust, CSKYCP::CSKYCPModifier Modifier, bool AddCurrentAddress)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73838254673eb1374cbb7ac9825d8b7">getSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f98d82b762f0af010741aa1b5be64cb">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19606a0f9813fdc91945453fe64fd62e">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468a6dacebcd2edadfc9dd258f8291a8">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#a468a6dacebcd2edadfc9dd258f8291a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc425fe9928b5653e1271c14f91a6c4d">equals</a> (const CSKYConstantPoolSymbol *A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8dccbfb38307a8bcd01bc23448b7a00">S</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol">CSKYConstantPoolSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb33f1d0f22848874dd3b14e265d268">Create</a> (Type *Ty, const char *S, unsigned PCAdjust, CSKYCP::CSKYCPModifier Modifier)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60c4869c2ca05a212303d08bba08cba">classof</a> (const CSKYConstantPoolValue *ACPV)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol">CSKYConstantPoolSymbol</a> - CSKY-specific constantpool values for external symbols.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### CSKYConstantPoolSymbol() {#a24fd16acf7aa7a345d8be602fdd867df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYConstantPoolSymbol::CSKYConstantPoolSymbol (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * S, unsigned PCAdjust, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4">CSKYCP::CSKYCPModifier</a> Modifier, bool AddCurrentAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#a19606a0f9813fdc91945453fe64fd62e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantPoolSymbol::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#ac2dce8ece8c4b01f78f80f643036681c">llvm::CSKYConstantPoolValue::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### equals() {#abc425fe9928b5653e1271c14f91a6c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolSymbol::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol">CSKYConstantPoolSymbol</a> * A)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a3f2211770c225a59cad39f4621a24404">llvm::CSKYConstantPoolValue::equals</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#a9f98d82b762f0af010741aa1b5be64cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CSKYConstantPoolSymbol::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a7f59aeed19f66ec8099052e3aa47c9c9">llvm::CSKYConstantPoolValue::getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getSymbol() {#ad73838254673eb1374cbb7ac9825d8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::CSKYConstantPoolSymbol::getSymbol ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>

</div>
</div>

### print() {#a468a6dacebcd2edadfc9dd258f8291a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantPoolSymbol::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a310e47e5146eaa80264533a27084604d">llvm::CSKYConstantPoolValue::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### S {#ac8dccbfb38307a8bcd01bc23448b7a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::CSKYConstantPoolSymbol::S</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aa60c4869c2ca05a212303d08bba08cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolSymbol::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue">CSKYConstantPoolValue</a> * ACPV)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a348e1e38604c1fc005a62ced08c6f583">llvm::CSKYConstantPoolValue::CSKYConstantPoolValue</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#af3293b45579bcf5442aeaa327c72bdb0">llvm::CSKYConstantPoolValue::isExtSymbol</a>.</p>

</div>
</div>

### Create() {#adeb33f1d0f22848874dd3b14e265d268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYConstantPoolSymbol * CSKYConstantPoolSymbol::Create (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * S, unsigned PCAdjust, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4">CSKYCP::CSKYCPModifier</a> Modifier)</td>
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



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#ad365afc92ba12f354616fd0033708911">llvm::CSKYConstantPoolValue::Modifier</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue/#a211fb7d504116ba5fb89bb4bc22a9070">llvm::CSKYConstantPoolValue::PCAdjust</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9fa574f4bc0ad6d1cd8335fdf7aba857">llvm::CSKYInstrInfo::getGlobalBaseReg</a>.</p>

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
