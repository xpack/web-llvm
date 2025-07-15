---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armconstantpoolconstant
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMConstantPoolConstant` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> - ARM-specific constant pool values for Constants, Functions, and BlockAddresses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ARMConstantPoolConstant { ... }
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1148f5f0eb1757c42944dc17d2db1a">promoted_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, 1 &gt;::iterator</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3cd33915cdd48466fc4aa4127789a69">ARMConstantPoolConstant</a> (const Constant *C, unsigned ID, ARMCP::ARMCPKind Kind, unsigned char PCAdj, ARMCP::ARMCPModifier Modifier, bool AddCurrentAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af922bc572568d887ddd3bc5f40e9c50c">ARMConstantPoolConstant</a> (Type *Ty, const Constant *C, unsigned ID, ARMCP::ARMCPKind Kind, unsigned char PCAdj, ARMCP::ARMCPModifier Modifier, bool AddCurrentAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a2080192b8a9a9d70dc411ff5ab9e5">ARMConstantPoolConstant</a> (const GlobalVariable *GV, const Constant *Init)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0697bf0ebcbc0b21342fe3aa05affab5">getGV</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf196f3d97c12d4b378ed13794853e0">getBlockAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aff1148f5f0eb1757c42944dc17d2db1a">promoted_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a694c1474bd0837cb49e6c3e2d97f86f5">promotedGlobals</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8caeb5a0c13ef5720d94d7cc2eca43d7">getPromotedGlobalInit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae74fbc76f1ec40713c56d087bb30adfd">getExistingMachineCPValue</a> (MachineConstantPool *CP, Align Alignment) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd8aa4e2dedff3b3e8d75eefdfe21b2">hasSameValue</a> (ARMConstantPoolValue *ACPV) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasSameValue - Return true if this <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> constpool value can share the same constantpool entry as another <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> constpool value. <a href="#a9bd8aa4e2dedff3b3e8d75eefdfe21b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c8e149d2d3fa94ac779398e008824e">addSelectionDAGCSEId</a> (FoldingSetNodeID &amp;ID) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6ab465d21408bde16e78213c1a8d59f">print</a> (raw_ostream &amp;O) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Implement operator&lt;&lt; <a href="#ab6ab465d21408bde16e78213c1a8d59f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167bcc49ac973a78d293c16441111948">equals</a> (const ARMConstantPoolConstant *A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1a49566ff764aef9574149378a79ac">CVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71fb42cbd03fc34cb7d8ad72f5c5c906">GVars</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ce6739c10696336d46591fec3e12ac">Create</a> (const Constant *C, unsigned ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f4af29cea0dae3f4a3cf633dbacaba">Create</a> (const GlobalValue *GV, ARMCP::ARMCPModifier Modifier)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28d0b6e00730bf8008a6540b342266cb">Create</a> (const GlobalVariable *GV, const Constant *Initializer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6516eb2992024bde5a8ed543d085f72d">Create</a> (const Constant *C, unsigned ID, ARMCP::ARMCPKind Kind, unsigned char PCAdj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e146fe44eb83d5dafb931583676eaf4">Create</a> (const Constant *C, unsigned ID, ARMCP::ARMCPKind Kind, unsigned char PCAdj, ARMCP::ARMCPModifier Modifier, bool AddCurrentAddress)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e0273e8266cb9e01441d8dbc21d69d">classof</a> (const ARMConstantPoolValue *APV)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> - ARM-specific constant pool values for Constants, Functions, and BlockAddresses.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### promoted\_iterator {#aff1148f5f0eb1757c42944dc17d2db1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ARMConstantPoolConstant::promoted_iterator =  SmallPtrSet&lt;const GlobalVariable *, 1&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ARMConstantPoolConstant() {#ae3cd33915cdd48466fc4aa4127789a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolConstant::ARMConstantPoolConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, unsigned ID, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaab">ARMCP::ARMCPKind</a> Kind, unsigned char PCAdj, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a> Modifier, bool AddCurrentAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>

</div>
</div>

### ARMConstantPoolConstant() {#af922bc572568d887ddd3bc5f40e9c50c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolConstant::ARMConstantPoolConstant (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, unsigned ID, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaab">ARMCP::ARMCPKind</a> Kind, unsigned char PCAdj, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a> Modifier, bool AddCurrentAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>

</div>
</div>

### ARMConstantPoolConstant() {#aa7a2080192b8a9a9d70dc411ff5ab9e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolConstant::ARMConstantPoolConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Init)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSelectionDAGCSEId() {#ae6c8e149d2d3fa94ac779398e008824e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantPoolConstant::addSelectionDAGCSEId (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#af658836bbc9432b5e44b40dfde9f1904">llvm::ARMConstantPoolValue::addSelectionDAGCSEId</a>.</p>

</div>
</div>

### equals() {#a167bcc49ac973a78d293c16441111948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolConstant::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant">ARMConstantPoolConstant</a> * A)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ab926b42ec064c1dd870bb93670d1cf91">llvm::ARMConstantPoolValue::equals</a>.</p>

</div>
</div>

### getBlockAddress() {#abbf196f3d97c12d4b378ed13794853e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockAddress * ARMConstantPoolConstant::getBlockAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>.</p>

</div>
</div>

### getExistingMachineCPValue() {#ae74fbc76f1ec40713c56d087bb30adfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ARMConstantPoolConstant::getExistingMachineCPValue (<a href="/web-llvm/docs/api/classes/llvm/machineconstantpool">MachineConstantPool</a> * CP, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">llvm::ARMConstantPoolValue::ARMConstantPoolValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a984cea3549f15471d09a91ba2f60d41b">llvm::ARMConstantPoolValue::getExistingMachineCPValueImpl</a>.</p>

</div>
</div>

### getGV() {#a0697bf0ebcbc0b21342fe3aa05affab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue * ARMConstantPoolConstant::getGV ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>.</p>

</div>
</div>

### getPromotedGlobalInit() {#a8caeb5a0c13ef5720d94d7cc2eca43d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant * llvm::ARMConstantPoolConstant::getPromotedGlobalInit ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

### hasSameValue() {#a9bd8aa4e2dedff3b3e8d75eefdfe21b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMConstantPoolConstant::hasSameValue (<a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> * ACPV)</td>
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

<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">llvm::ARMConstantPoolValue::ARMConstantPoolValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ae204089fb50ef2edd07a7d18c5c4b79f">llvm::ARMConstantPoolValue::hasSameValue</a>.</p>

</div>
</div>

### print() {#ab6ab465d21408bde16e78213c1a8d59f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMConstantPoolConstant::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a7b8d7ad0899bfee6d615c35f0dfd9841">llvm::ARMConstantPoolValue::print</a>.</p>

</div>
</div>

### promotedGlobals() {#a694c1474bd0837cb49e6c3e2d97f86f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; promoted_iterator &gt; llvm::ARMConstantPoolConstant::promotedGlobals ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9b5301a03dc90d7ac00440e2de4d9149">llvm::iterator_range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CVal {#aca1a49566ff764aef9574149378a79ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant* llvm::ARMConstantPoolConstant::CVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

### GVars {#a71fb42cbd03fc34cb7d8ad72f5c5c906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const GlobalVariable*, 1&gt; llvm::ARMConstantPoolConstant::GVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a32e0273e8266cb9e01441d8dbc21d69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMConstantPoolConstant::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue">ARMConstantPoolValue</a> * APV)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a6d52e73a2bb8e9ddb5c1a00cf45d88e0">llvm::ARMConstantPoolValue::ARMConstantPoolValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ae603ba203d2cb8f2d58d8ba8b296f468">llvm::ARMConstantPoolValue::isBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#aa6db6cf5d86094941ae641ceecf87318">llvm::ARMConstantPoolValue::isGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ae25500a7ac8ad50ba2773c8558e1deaa">llvm::ARMConstantPoolValue::isLSDA</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a01cff4206f16f8e50159853a71f95080">llvm::ARMConstantPoolValue::isPromotedGlobal</a>.</p>

</div>
</div>

### Create() {#a42ce6739c10696336d46591fec3e12ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolConstant * ARMConstantPoolConstant::Create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, unsigned ID)</td>
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



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabad4206f41cccb7d5c78d6d642b4b35e1f">llvm::ARMCP::CPValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85ae9103902078db9ff4f9a7f5477b04c76">llvm::ARMCP::no_modifier</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac6767d87d6d42330fa8e29e15bb105b1">promoteToConstantPool</a>.</p>

</div>
</div>

### Create() {#af5f4af29cea0dae3f4a3cf633dbacaba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolConstant * ARMConstantPoolConstant::Create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a> Modifier)</td>
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



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabad4206f41cccb7d5c78d6d642b4b35e1f">llvm::ARMCP::CPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>.</p>

</div>
</div>

### Create() {#a28d0b6e00730bf8008a6540b342266cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolConstant * ARMConstantPoolConstant::Create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Initializer)</td>
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



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>

</div>
</div>

### Create() {#a6516eb2992024bde5a8ed543d085f72d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolConstant * ARMConstantPoolConstant::Create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, unsigned ID, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaab">ARMCP::ARMCPKind</a> Kind, unsigned char PCAdj)</td>
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



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85ae9103902078db9ff4f9a7f5477b04c76">llvm::ARMCP::no_modifier</a>.</p>

</div>
</div>

### Create() {#a6e146fe44eb83d5dafb931583676eaf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMConstantPoolConstant * ARMConstantPoolConstant::Create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, unsigned ID, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaab">ARMCP::ARMCPKind</a> Kind, unsigned char PCAdj, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad792b254bbbd9b9f3e5ea93d54a54d85">ARMCP::ARMCPModifier</a> Modifier, bool AddCurrentAddress)</td>
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



<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-cpp">ARMConstantPoolValue.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

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
