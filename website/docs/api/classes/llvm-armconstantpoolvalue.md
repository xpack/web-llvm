---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armconstantpoolvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMConstantPoolValue` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> specific constantpool value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ARMConstantPoolValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">Target/ARM/ARMConstantPoolValue.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> - ARM-specific constant pool values for Constants, Functions, and BlockAddresses. <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb">ARMConstantPoolMBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb">ARMConstantPoolMBB</a> - ARM-specific constantpool value of a machine basic block. <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol">ARMConstantPoolSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol">ARMConstantPoolSymbol</a> - ARM-specific constantpool values for external symbols. <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">ARMConstantPoolValue</a> (Type *Ty, unsigned id, ARMCP::ARMCPKind Kind, unsigned char PCAdj, ARMCP::ARMCPModifier Modifier, bool AddCurrentAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3396883abbd2b3c2e61cd4f87943702c">ARMConstantPoolValue</a> (LLVMContext &amp;C, unsigned id, ARMCP::ARMCPKind Kind, unsigned char PCAdj, ARMCP::ARMCPModifier Modifier, bool AddCurrentAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75709b46bf0d746eb031e606ebc8c818">~ARMConstantPoolValue</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4a46d23b1ab79b5dc190ac58f22eae">getModifier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada078240593f51d95cc878aea5ca981b">getModifierText</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8601d311397874b25c22f9e3066d2a">hasModifier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accec0ab52fef914619e937abd7f85c8b">mustAddCurrentAddress</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b32249540bb5161b162e30f0fd1769">getLabelId</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123d1ad2f85db8bfe2749294e5751c70">getPCAdjustment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6db6cf5d86094941ae641ceecf87318">isGlobalValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8d346c78a82437ac734e4ce1cb0553">isExtSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae603ba203d2cb8f2d58d8ba8b296f468">isBlockAddress</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25500a7ac8ad50ba2773c8558e1deaa">isLSDA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8761e4a93682b13870657a5b83612ffc">isMachineBasicBlock</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01cff4206f16f8e50159853a71f95080">isPromotedGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4cba7ac19e830bf30907621cf250e5">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af658836bbc9432b5e44b40dfde9f1904">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae204089fb50ef2edd07a7d18c5c4b79f">hasSameValue</a> (ARMConstantPoolValue *ACPV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasSameValue - Return true if this <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> constpool value can share the same constantpool entry as another <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> constpool value. <a href="#ae204089fb50ef2edd07a7d18c5c4b79f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab926b42ec064c1dd870bb93670d1cf91">equals</a> (const ARMConstantPoolValue *A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b8d7ad0899bfee6d615c35f0dfd9841">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#a7b8d7ad0899bfee6d615c35f0dfd9841">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2939cb3fb23575c829b38126355af2a9">print</a> (raw_ostream *O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e996e33d02377f36d099211fedf9bc">dump</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a984cea3549f15471d09a91ba2f60d41b">getExistingMachineCPValueImpl</a> (MachineConstantPool *CP, Align Alignment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ae438412f0c748a8c8ee3c2064342b3">LabelId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaab">ARMCP::ARMCPKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abce60d528d11b067108ff2b0a78c133a">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66416b8f3e3973a08fd3cc82f611901">PCAdjust</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6830e881efa2cfa97a891d0e59f349a4">Modifier</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae29cd88288df12a3e26fdb6e02a43886">AddCurrentAddress</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> - <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> specific constantpool value.</p>


<p>This is used to represent PC-relative displacement between the address of the load instruction and the constant being loaded, i.e. (&amp;GV-(LPIC+8)).</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ARMConstantPoolValue() {#a6d52e73a2bb8e9ddb5c1a00cf45d88e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolValue::ARMConstantPoolValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned id, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaab">ARMCP::ARMCPKind</a> Kind, unsigned char PCAdj, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a> Modifier, bool AddCurrentAddress)</td>
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



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue/#ac688aad44da54c2262096a4b5c5891f4">llvm::MachineConstantPoolValue::MachineConstantPoolValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a32e0273e8266cb9e01441d8dbc21d69d">llvm::ARMConstantPoolConstant::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#ac08577dd62b00230909575dcdefd45f6">llvm::ARMConstantPoolMBB::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#acbe84c5b76bebe7b2657a9028d019850">llvm::ARMConstantPoolSymbol::classof</a>, <a href="#ab926b42ec064c1dd870bb93670d1cf91">equals</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#ae74fbc76f1ec40713c56d087bb30adfd">llvm::ARMConstantPoolConstant::getExistingMachineCPValue</a>, <a href="#a984cea3549f15471d09a91ba2f60d41b">getExistingMachineCPValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a9bd8aa4e2dedff3b3e8d75eefdfe21b2">llvm::ARMConstantPoolConstant::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#a8307b3875610081435c5ab30500a29f8">llvm::ARMConstantPoolMBB::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#a5b56d239ebf470d31f2d569f8ba8a5d5">llvm::ARMConstantPoolSymbol::hasSameValue</a> and <a href="#ae204089fb50ef2edd07a7d18c5c4b79f">hasSameValue</a>.</p>

</div>
</div>

### ARMConstantPoolValue() {#a3396883abbd2b3c2e61cd4f87943702c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolValue::ARMConstantPoolValue (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned id, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaab">ARMCP::ARMCPKind</a> Kind, unsigned char PCAdj, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a> Modifier, bool AddCurrentAddress)</td>
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



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolvalue/#ac688aad44da54c2262096a4b5c5891f4">llvm::MachineConstantPoolValue::MachineConstantPoolValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ARMConstantPoolValue() {#a75709b46bf0d746eb031e606ebc8c818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolValue::~ARMConstantPoolValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#af658836bbc9432b5e44b40dfde9f1904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantPoolValue::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#ae6c8e149d2d3fa94ac779398e008824e">llvm::ARMConstantPoolConstant::addSelectionDAGCSEId</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#a4d19ca1e52af861e38e22e4800ad5652">llvm::ARMConstantPoolMBB::addSelectionDAGCSEId</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#a54020803303eb37503a96938c9b5c1a6">llvm::ARMConstantPoolSymbol::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### dump() {#a72e996e33d02377f36d099211fedf9bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ARMConstantPoolValue::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### equals() {#ab926b42ec064c1dd870bb93670d1cf91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> * A)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">ARMConstantPoolValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a167bcc49ac973a78d293c16441111948">llvm::ARMConstantPoolConstant::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#a2bf1ce7e52763a63d121be75302ada45">llvm::ARMConstantPoolMBB::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#ade14b4bb44c4d8455b98609ca473c663">llvm::ARMConstantPoolSymbol::equals</a> and <a href="#a984cea3549f15471d09a91ba2f60d41b">getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#a1d4cba7ac19e830bf30907621cf250e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ARMConstantPoolValue::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getLabelId() {#ae1b32249540bb5161b162e30f0fd1769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMConstantPoolValue::getLabelId ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### getModifier() {#abe4a46d23b1ab79b5dc190ac58f22eae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMCP::ARMCPModifier llvm::ARMConstantPoolValue::getModifier ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### getModifierText() {#ada078240593f51d95cc878aea5ca981b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ARMConstantPoolValue::getModifierText ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85a3d74db86256dfd469bc89a14b1d76fab">llvm::ARMCP::GOT_PREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85acddd18dc22e67498fcf0a79b16155fcf">llvm::ARMCP::GOTTPOFF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85ae9103902078db9ff4f9a7f5477b04c76">llvm::ARMCP::no_modifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85a44297a25f1c31b29e03e9631855cfef9">llvm::ARMCP::SBREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85a007149d5920d57032dba20c97c18e7e6">llvm::ARMCP::SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85a62fc1799424549066b0c6b91919152d7">llvm::ARMCP::TLSGD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85ae08d827e55e1fbc94f0156f25aea52e2">llvm::ARMCP::TPOFF</a>.</p>


<p>Referenced by <a href="#a7b8d7ad0899bfee6d615c35f0dfd9841">print</a>.</p>

</div>
</div>

### getPCAdjustment() {#a123d1ad2f85db8bfe2749294e5751c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::ARMConstantPoolValue::getPCAdjustment ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### hasModifier() {#adc8601d311397874b25c22f9e3066d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::hasModifier ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85ae9103902078db9ff4f9a7f5477b04c76">llvm::ARMCP::no_modifier</a>.</p>

</div>
</div>

### hasSameValue() {#ae204089fb50ef2edd07a7d18c5c4b79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantPoolValue::hasSameValue (<a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> * ACPV)</td>
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

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">ARMConstantPoolValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabab8ec2c2ae69c4040c312cf22f10c6819">llvm::ARMCP::CPExtSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabad4206f41cccb7d5c78d6d642b4b35e1f">llvm::ARMCP::CPValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a9bd8aa4e2dedff3b3e8d75eefdfe21b2">llvm::ARMConstantPoolConstant::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#a8307b3875610081435c5ab30500a29f8">llvm::ARMConstantPoolMBB::hasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#a5b56d239ebf470d31f2d569f8ba8a5d5">llvm::ARMConstantPoolSymbol::hasSameValue</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>.</p>

</div>
</div>

### isBlockAddress() {#ae603ba203d2cb8f2d58d8ba8b296f468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::isBlockAddress ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabac6721b50294fd164c5861cb82e938e10">llvm::ARMCP::CPBlockAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a32e0273e8266cb9e01441d8dbc21d69d">llvm::ARMConstantPoolConstant::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isExtSymbol() {#a8b8d346c78a82437ac734e4ce1cb0553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::isExtSymbol ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabab8ec2c2ae69c4040c312cf22f10c6819">llvm::ARMCP::CPExtSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#acbe84c5b76bebe7b2657a9028d019850">llvm::ARMConstantPoolSymbol::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isGlobalValue() {#aa6db6cf5d86094941ae641ceecf87318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::isGlobalValue ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabad4206f41cccb7d5c78d6d642b4b35e1f">llvm::ARMCP::CPValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a32e0273e8266cb9e01441d8dbc21d69d">llvm::ARMConstantPoolConstant::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isLSDA() {#ae25500a7ac8ad50ba2773c8558e1deaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::isLSDA ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaaba7266a79b029f9dc90109a374fe43c64f">llvm::ARMCP::CPLSDA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a32e0273e8266cb9e01441d8dbc21d69d">llvm::ARMConstantPoolConstant::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isMachineBasicBlock() {#a8761e4a93682b13870657a5b83612ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::isMachineBasicBlock ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaaba69027420555aea47cb71a920edb9efcc">llvm::ARMCP::CPMachineBasicBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#ac08577dd62b00230909575dcdefd45f6">llvm::ARMConstantPoolMBB::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### isPromotedGlobal() {#a01cff4206f16f8e50159853a71f95080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::isPromotedGlobal ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaaba842db4432c41709c02038126b8d57e27">llvm::ARMCP::CPPromotedGlobal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a32e0273e8266cb9e01441d8dbc21d69d">llvm::ARMConstantPoolConstant::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### mustAddCurrentAddress() {#accec0ab52fef914619e937abd7f85c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::mustAddCurrentAddress ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a64d5e2e905476441f2485f563970f7fe">llvm::ARMAsmPrinter::emitMachineConstantPoolValue</a>.</p>

</div>
</div>

### print() {#a7b8d7ad0899bfee6d615c35f0dfd9841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantPoolValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="#ada078240593f51d95cc878aea5ca981b">getModifierText</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#ab6ab465d21408bde16e78213c1a8d59f">llvm::ARMConstantPoolConstant::print</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#a8b8d429cc1ce71cd4456657f4e6463f3">llvm::ARMConstantPoolMBB::print</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#a87cc1c8dfc064bce322ee7c2641eaff3">llvm::ARMConstantPoolSymbol::print</a>.</p>

</div>
</div>

### print() {#a2939cb3fb23575c829b38126355af2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ARMConstantPoolValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * O)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="#a2939cb3fb23575c829b38126355af2a9">print</a>.</p>


<p>Referenced by <a href="#a2939cb3fb23575c829b38126355af2a9">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getExistingMachineCPValueImpl() {#a984cea3549f15471d09a91ba2f60d41b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ARMConstantPoolValue::getExistingMachineCPValueImpl (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>References <a href="#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">ARMConstantPoolValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab926b42ec064c1dd870bb93670d1cf91">equals</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a44361e635fd7461e3a8eeb7fc9ad4f04">llvm::getAlign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#ae74fbc76f1ec40713c56d087bb30adfd">llvm::ARMConstantPoolConstant::getExistingMachineCPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#a473e733e2610bba6d595ae063587919d">llvm::ARMConstantPoolMBB::getExistingMachineCPValue</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#a6abd560b29eb37e576ec58d86d17099f">llvm::ARMConstantPoolSymbol::getExistingMachineCPValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddCurrentAddress {#ae29cd88288df12a3e26fdb6e02a43886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolValue::AddCurrentAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

### Kind {#abce60d528d11b067108ff2b0a78c133a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMCP::ARMCPKind llvm::ARMConstantPoolValue::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

### LabelId {#a4ae438412f0c748a8c8ee3c2064342b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMConstantPoolValue::LabelId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

### Modifier {#a6830e881efa2cfa97a891d0e59f349a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMCP::ARMCPModifier llvm::ARMConstantPoolValue::Modifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

### PCAdjust {#ab66416b8f3e3973a08fd3cc82f611901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::ARMConstantPoolValue::PCAdjust</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
