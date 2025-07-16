---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cskyconstantpoolvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CSKYConstantPoolValue` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue">CSKYConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/csky">CSKY</a> specific constantpool value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CSKYConstantPoolValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">Target/CSKY/CSKYConstantPoolValue.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant">CSKYConstantPoolConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CSKY-specific constant pool values for Constants, Functions, and BlockAddresses. <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt">CSKYConstantPoolJT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CSKY-specific constantpool value of a jump table. <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb">CSKYConstantPoolMBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb">CSKYConstantPoolMBB</a> - CSKY-specific constantpool value of a machine basic block. <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol">CSKYConstantPoolSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol">CSKYConstantPoolSymbol</a> - CSKY-specific constantpool values for external symbols. <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348e1e38604c1fc005a62ced08c6f583">CSKYConstantPoolValue</a> (Type *Ty, CSKYCP::CSKYCPKind Kind, unsigned PCAdjust, CSKYCP::CSKYCPModifier Modifier, bool AddCurrentAddress, unsigned ID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4fd0e484744e9d1c45a041913485d0b">getModifierText</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7839898462d8df92936bf15046938a2e">getPCAdjustment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808fffee806197862bff1754199e15ad">mustAddCurrentAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4">CSKYCP::CSKYCPModifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae788b24d3fa905bf2ad8e3ec0eb786d8">getModifier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3313e4bb821e24fdfa7cfa8036633a">getLabelID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20df957b6f27461dfaaa049051b54e25">isGlobalValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3293b45579bcf5442aeaa327c72bdb0">isExtSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c4a55953fe7d6e4a59cda261a2e500">isBlockAddress</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e80f3fe8022c9ac777591115ae2c637">isMachineBasicBlock</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b08a58608aba96ea9ae32a576d0879">isJT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88a221eca9e924088e27ce657d809778">isConstPool</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc480159ebebc2b1dafff702e3d0f44c">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2dce8ece8c4b01f78f80f643036681c">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310e47e5146eaa80264533a27084604d">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#a310e47e5146eaa80264533a27084604d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2211770c225a59cad39f4621a24404">equals</a> (const CSKYConstantPoolValue *A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f59aeed19f66ec8099052e3aa47c9c9">getExistingMachineCPValueImpl</a> (MachineConstantPool *CP, Align Alignment)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a52910a7599c196a2a21a5fef5da46994">CSKYCP::CSKYCPKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ed825694c1cf82be7fe8b7aa3bc979">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a211fb7d504116ba5fb89bb4bc22a9070">PCAdjust</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4">CSKYCP::CSKYCPModifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad365afc92ba12f354616fd0033708911">Modifier</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3479a63947179467405781072aff1f">AddCurrentAddress</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412a536ed94670c0525c04408ffd7d3c">LabelId</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue">CSKYConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/csky">CSKY</a> specific constantpool value.</p>


<p>This is used to represent PC-relative displacement between the address of the load instruction and the constant being loaded, i.e. (&amp;GV-(LPIC+8)).</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### CSKYConstantPoolValue() {#a348e1e38604c1fc005a62ced08c6f583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYConstantPoolValue::CSKYConstantPoolValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a52910a7599c196a2a21a5fef5da46994">CSKYCP::CSKYCPKind</a> Kind, unsigned PCAdjust, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4">CSKYCP::CSKYCPModifier</a> Modifier, bool AddCurrentAddress, unsigned ID=0)</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>References <a href="#afb3479a63947179467405781072aff1f">AddCurrentAddress</a>, <a href="#aa0ed825694c1cf82be7fe8b7aa3bc979">Kind</a>, <a href="#a412a536ed94670c0525c04408ffd7d3c">LabelId</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue/#ac688aad44da54c2262096a4b5c5891f4">llvm::MachineConstantPoolValue::MachineConstantPoolValue</a>, <a href="#ad365afc92ba12f354616fd0033708911">Modifier</a> and <a href="#a211fb7d504116ba5fb89bb4bc22a9070">PCAdjust</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#af5b96d067ac1e07bd24eaca25a0c5412">llvm::CSKYConstantPoolConstant::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt/#a8786b661ca92e48a819c02f07e7ebaa5">llvm::CSKYConstantPoolJT::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb/#a37c473a11f98fdd74cd2a05eac8c141b">llvm::CSKYConstantPoolMBB::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#aa60c4869c2ca05a212303d08bba08cba">llvm::CSKYConstantPoolSymbol::classof</a>, <a href="#a3f2211770c225a59cad39f4621a24404">equals</a> and <a href="#a7f59aeed19f66ec8099052e3aa47c9c9">getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#ac2dce8ece8c4b01f78f80f643036681c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantPoolValue::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>References <a href="#a412a536ed94670c0525c04408ffd7d3c">LabelId</a>, <a href="#ad365afc92ba12f354616fd0033708911">Modifier</a> and <a href="#a211fb7d504116ba5fb89bb4bc22a9070">PCAdjust</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#ab6eaf5d3c9dd6794d787dc1b4adcb590">llvm::CSKYConstantPoolConstant::addSelectionDAGCSEId</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt/#a8d9d023906ede89ca8aa115c561df662">llvm::CSKYConstantPoolJT::addSelectionDAGCSEId</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb/#a073a968de1d890ffa42595e9c09d1902">llvm::CSKYConstantPoolMBB::addSelectionDAGCSEId</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#a19606a0f9813fdc91945453fe64fd62e">llvm::CSKYConstantPoolSymbol::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### equals() {#a3f2211770c225a59cad39f4621a24404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolvalue">CSKYConstantPoolValue</a> * A)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a348e1e38604c1fc005a62ced08c6f583">CSKYConstantPoolValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#ad7dd001024d4ae5f21d08357e17c858c">llvm::CSKYConstantPoolConstant::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt/#a002138404efa4f3870ff84cd8f01d31c">llvm::CSKYConstantPoolJT::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb/#a538974a817f929fa65fa1cd5845f3bfd">llvm::CSKYConstantPoolMBB::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#abc425fe9928b5653e1271c14f91a6c4d">llvm::CSKYConstantPoolSymbol::equals</a> and <a href="#a7f59aeed19f66ec8099052e3aa47c9c9">getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#afc480159ebebc2b1dafff702e3d0f44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CSKYConstantPoolValue::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getExistingMachineCPValueImpl() {#a7f59aeed19f66ec8099052e3aa47c9c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::CSKYConstantPoolValue::getExistingMachineCPValueImpl (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a348e1e38604c1fc005a62ced08c6f583">CSKYConstantPoolValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a3f2211770c225a59cad39f4621a24404">equals</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a44361e635fd7461e3a8eeb7fc9ad4f04">llvm::getAlign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#a85cfa254656ea195455c3ec355dcc72d">llvm::CSKYConstantPoolConstant::getExistingMachineCPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt/#a0d6a9d64629fa2d0cee461d2fa1f0c06">llvm::CSKYConstantPoolJT::getExistingMachineCPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb/#a05461131c89151c1ba2c11b52f9e6cc3">llvm::CSKYConstantPoolMBB::getExistingMachineCPValue</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#a9f98d82b762f0af010741aa1b5be64cb">llvm::CSKYConstantPoolSymbol::getExistingMachineCPValue</a>.</p>

</div>
</div>

### getLabelID() {#a2f3313e4bb821e24fdfa7cfa8036633a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CSKYConstantPoolValue::getLabelID ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Reference <a href="#a412a536ed94670c0525c04408ffd7d3c">LabelId</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### getModifier() {#ae788b24d3fa905bf2ad8e3ec0eb786d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYCP::CSKYCPModifier llvm::CSKYConstantPoolValue::getModifier ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Reference <a href="#ad365afc92ba12f354616fd0033708911">Modifier</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### getModifierText() {#af4fd0e484744e9d1c45a041913485d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * CSKYConstantPoolValue::getModifierText ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a11f72aa51db1915ad266a52e760f28af">llvm::CSKYCP::ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4ae82a4118bf542c05ab38488e5b578ae1">llvm::CSKYCP::GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a972b1bf03372caa6601f0a1b4903ae76">llvm::CSKYCP::GOTOFF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ad365afc92ba12f354616fd0033708911">Modifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4ab42535f4f838187946d69d1113f7cd32">llvm::CSKYCP::NO_MOD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a4534acdb80b394f5943dcc36c9704c9b">llvm::CSKYCP::PLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a5c32b033a20299c57276476c5b7c73b9">llvm::CSKYCP::TLSGD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4a200b54fa8d3a6ca97d345190f01a4087">llvm::CSKYCP::TLSIE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a4adf83f12fd4b32c53af26ac279ae9e4ae32b3dc690462147ec73186713977244">llvm::CSKYCP::TLSLE</a>.</p>


<p>Referenced by <a href="#a310e47e5146eaa80264533a27084604d">print</a>.</p>

</div>
</div>

### getPCAdjustment() {#a7839898462d8df92936bf15046938a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CSKYConstantPoolValue::getPCAdjustment ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Reference <a href="#a211fb7d504116ba5fb89bb4bc22a9070">PCAdjust</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isBlockAddress() {#a85c4a55953fe7d6e4a59cda261a2e500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::isBlockAddress ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a52910a7599c196a2a21a5fef5da46994ab917d70fc1937db9603905f1ec1bb6ac">llvm::CSKYCP::CPBlockAddress</a> and <a href="#aa0ed825694c1cf82be7fe8b7aa3bc979">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#af5b96d067ac1e07bd24eaca25a0c5412">llvm::CSKYConstantPoolConstant::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isConstPool() {#a88a221eca9e924088e27ce657d809778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::isConstPool ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a52910a7599c196a2a21a5fef5da46994a80797351072fb5a6a5a57cd61a65d923">llvm::CSKYCP::CPConstPool</a> and <a href="#aa0ed825694c1cf82be7fe8b7aa3bc979">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#af5b96d067ac1e07bd24eaca25a0c5412">llvm::CSKYConstantPoolConstant::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isExtSymbol() {#af3293b45579bcf5442aeaa327c72bdb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::isExtSymbol ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a52910a7599c196a2a21a5fef5da46994aec7b7a9c0ff58f51f3a82373053536ee">llvm::CSKYCP::CPExtSymbol</a> and <a href="#aa0ed825694c1cf82be7fe8b7aa3bc979">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#aa60c4869c2ca05a212303d08bba08cba">llvm::CSKYConstantPoolSymbol::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isGlobalValue() {#a20df957b6f27461dfaaa049051b54e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::isGlobalValue ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a52910a7599c196a2a21a5fef5da46994a04789ab67a1cddbbb789b02153814d85">llvm::CSKYCP::CPValue</a> and <a href="#aa0ed825694c1cf82be7fe8b7aa3bc979">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#af5b96d067ac1e07bd24eaca25a0c5412">llvm::CSKYConstantPoolConstant::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isJT() {#ae9b08a58608aba96ea9ae32a576d0879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::isJT ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a52910a7599c196a2a21a5fef5da46994a0994bb09ea1f60a124c61bdcb2f2e7c7">llvm::CSKYCP::CPJT</a> and <a href="#aa0ed825694c1cf82be7fe8b7aa3bc979">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt/#a8786b661ca92e48a819c02f07e7ebaa5">llvm::CSKYConstantPoolJT::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isMachineBasicBlock() {#a1e80f3fe8022c9ac777591115ae2c637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::isMachineBasicBlock ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskycp/#a52910a7599c196a2a21a5fef5da46994add82e3573eab3f64229820416db40224">llvm::CSKYCP::CPMachineBasicBlock</a> and <a href="#aa0ed825694c1cf82be7fe8b7aa3bc979">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb/#a37c473a11f98fdd74cd2a05eac8c141b">llvm::CSKYConstantPoolMBB::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### mustAddCurrentAddress() {#a808fffee806197862bff1754199e15ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::mustAddCurrentAddress ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Reference <a href="#afb3479a63947179467405781072aff1f">AddCurrentAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a96970d69b7b91b65fe1dec76d42fcea0">llvm::CSKYAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### print() {#a310e47e5146eaa80264533a27084604d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CSKYConstantPoolValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-cpp">CSKYConstantPoolValue.cpp</a>.</p>


<p>References <a href="#af4fd0e484744e9d1c45a041913485d0b">getModifierText</a>, <a href="#ad365afc92ba12f354616fd0033708911">Modifier</a> and <a href="#a211fb7d504116ba5fb89bb4bc22a9070">PCAdjust</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#abe523270c6342367542f38ef98ee7700">llvm::CSKYConstantPoolConstant::print</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt/#a34480ba690d947fee9a97b8611cfe062">llvm::CSKYConstantPoolJT::print</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb/#ac036b42b4583627d58c0aeec5495474c">llvm::CSKYConstantPoolMBB::print</a> and <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#a468a6dacebcd2edadfc9dd258f8291a8">llvm::CSKYConstantPoolSymbol::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AddCurrentAddress {#afb3479a63947179467405781072aff1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CSKYConstantPoolValue::AddCurrentAddress</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#ad2e7328dbae8591003a3f42d049754b5">llvm::CSKYConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#a9be132fd6a70bb5bf4c3f8847034099b">llvm::CSKYConstantPoolConstant::Create</a>, <a href="#a348e1e38604c1fc005a62ced08c6f583">CSKYConstantPoolValue</a> and <a href="#a808fffee806197862bff1754199e15ad">mustAddCurrentAddress</a>.</p>

</div>
</div>

### Kind {#aa0ed825694c1cf82be7fe8b7aa3bc979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYCP::CSKYCPKind llvm::CSKYConstantPoolValue::Kind</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#ad2e7328dbae8591003a3f42d049754b5">llvm::CSKYConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#a9be132fd6a70bb5bf4c3f8847034099b">llvm::CSKYConstantPoolConstant::Create</a>, <a href="#a348e1e38604c1fc005a62ced08c6f583">CSKYConstantPoolValue</a>, <a href="#a85c4a55953fe7d6e4a59cda261a2e500">isBlockAddress</a>, <a href="#a88a221eca9e924088e27ce657d809778">isConstPool</a>, <a href="#af3293b45579bcf5442aeaa327c72bdb0">isExtSymbol</a>, <a href="#a20df957b6f27461dfaaa049051b54e25">isGlobalValue</a>, <a href="#ae9b08a58608aba96ea9ae32a576d0879">isJT</a> and <a href="#a1e80f3fe8022c9ac777591115ae2c637">isMachineBasicBlock</a>.</p>

</div>
</div>

### LabelId {#a412a536ed94670c0525c04408ffd7d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CSKYConstantPoolValue::LabelId = 0</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="#ac2dce8ece8c4b01f78f80f643036681c">addSelectionDAGCSEId</a>, <a href="#a348e1e38604c1fc005a62ced08c6f583">CSKYConstantPoolValue</a> and <a href="#a2f3313e4bb821e24fdfa7cfa8036633a">getLabelID</a>.</p>

</div>
</div>

### Modifier {#ad365afc92ba12f354616fd0033708911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSKYCP::CSKYCPModifier llvm::CSKYConstantPoolValue::Modifier</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="#ac2dce8ece8c4b01f78f80f643036681c">addSelectionDAGCSEId</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#ad2e7328dbae8591003a3f42d049754b5">llvm::CSKYConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#a9be132fd6a70bb5bf4c3f8847034099b">llvm::CSKYConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpooljt/#a1a421ac223131c5c44b978a7f644b63b">llvm::CSKYConstantPoolJT::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#adeb33f1d0f22848874dd3b14e265d268">llvm::CSKYConstantPoolSymbol::Create</a>, <a href="#a348e1e38604c1fc005a62ced08c6f583">CSKYConstantPoolValue</a>, <a href="#ae788b24d3fa905bf2ad8e3ec0eb786d8">getModifier</a>, <a href="#af4fd0e484744e9d1c45a041913485d0b">getModifierText</a> and <a href="#a310e47e5146eaa80264533a27084604d">print</a>.</p>

</div>
</div>

### PCAdjust {#a211fb7d504116ba5fb89bb4bc22a9070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CSKYConstantPoolValue::PCAdjust</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantpoolvalue-h">CSKYConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="#ac2dce8ece8c4b01f78f80f643036681c">addSelectionDAGCSEId</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#ad2e7328dbae8591003a3f42d049754b5">llvm::CSKYConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolconstant/#a9be132fd6a70bb5bf4c3f8847034099b">llvm::CSKYConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolmbb/#a355518ff0b8c0aa7c495bfa151dc6169">llvm::CSKYConstantPoolMBB::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpoolsymbol/#adeb33f1d0f22848874dd3b14e265d268">llvm::CSKYConstantPoolSymbol::Create</a>, <a href="#a348e1e38604c1fc005a62ced08c6f583">CSKYConstantPoolValue</a>, <a href="#a7839898462d8df92936bf15046938a2e">getPCAdjustment</a> and <a href="#a310e47e5146eaa80264533a27084604d">print</a>.</p>

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
