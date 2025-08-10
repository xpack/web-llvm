---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/wholeprogramdevirt/virtualcalltarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VirtualCallTarget` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::wholeprogramdevirt::VirtualCallTarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">llvm/Transforms/IPO/WholeProgramDevirt.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b16d241bb6365303178c509cd4227b">VirtualCallTarget</a> (GlobalValue *Fn, const TypeMemberInfo *TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3956bd4bc329224815e72bfac06ee445">VirtualCallTarget</a> (const TypeMemberInfo *TM, bool IsBigEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a85548479dea353a60994ffe26e6d7">minBeforeBytes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acccef23746c3dcaf68b96046a8bc2fce">minAfterBytes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a2104a416aedf3c97462513ce13c1a">allocatedBeforeBytes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133904aa81277a5846c62fabd87b8cb4">allocatedAfterBytes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c0cf8b5d019262416e5f6afb44617f9">setBeforeBit</a> (uint64_t Pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf23a077ec5e50be8c959fbaa58764f1">setAfterBit</a> (uint64_t Pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882eba3c69318bd6bce348d05a1eee7e">setBeforeBytes</a> (uint64_t Pos, uint8_t Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac519a5aee06c9c3c48dc6fb9d4ab119a">setAfterBytes</a> (uint64_t Pos, uint8_t Size)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce909bc914445f4c5bab5fc525193c9">Fn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/typememberinfo">TypeMemberInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf3b9cd84b1fbc9cb8283e89ad5d1f6f">RetVal</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aeff409eb1e18f197498602d01aee94">IsBigEndian</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e93ca0e36159d9dbd5fa623689a2f3">WasDevirt</a></td>
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


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VirtualCallTarget() {#a55b16d241bb6365303178c509cd4227b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtualCallTarget::VirtualCallTarget (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/typememberinfo">TypeMemberInfo</a> * TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a7ce909bc914445f4c5bab5fc525193c9">Fn</a>, <a href="#a6aeff409eb1e18f197498602d01aee94">IsBigEndian</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#aad6842fbf58844d974611a4915a00aae">isBigEndian</a>, <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a> and <a href="#ae9e93ca0e36159d9dbd5fa623689a2f3">WasDevirt</a>.</p>

</div>
</div>

### VirtualCallTarget() {#a3956bd4bc329224815e72bfac06ee445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::wholeprogramdevirt::VirtualCallTarget::VirtualCallTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/typememberinfo">TypeMemberInfo</a> * TM, bool IsBigEndian)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>References <a href="#a7ce909bc914445f4c5bab5fc525193c9">Fn</a>, <a href="#a6aeff409eb1e18f197498602d01aee94">IsBigEndian</a>, <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a> and <a href="#ae9e93ca0e36159d9dbd5fa623689a2f3">WasDevirt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocatedAfterBytes() {#a133904aa81277a5846c62fabd87b8cb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::wholeprogramdevirt::VirtualCallTarget::allocatedAfterBytes ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>References <a href="#acccef23746c3dcaf68b96046a8bc2fce">minAfterBytes</a> and <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a>.</p>

</div>
</div>

### allocatedBeforeBytes() {#ac1a2104a416aedf3c97462513ce13c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::wholeprogramdevirt::VirtualCallTarget::allocatedBeforeBytes ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>References <a href="#ac3a85548479dea353a60994ffe26e6d7">minBeforeBytes</a> and <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a>.</p>

</div>
</div>

### minAfterBytes() {#acccef23746c3dcaf68b96046a8bc2fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::wholeprogramdevirt::VirtualCallTarget::minAfterBytes ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>Reference <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a>.</p>


<p>Referenced by <a href="#a133904aa81277a5846c62fabd87b8cb4">allocatedAfterBytes</a>, <a href="#abf23a077ec5e50be8c959fbaa58764f1">setAfterBit</a> and <a href="#ac519a5aee06c9c3c48dc6fb9d4ab119a">setAfterBytes</a>.</p>

</div>
</div>

### minBeforeBytes() {#ac3a85548479dea353a60994ffe26e6d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::wholeprogramdevirt::VirtualCallTarget::minBeforeBytes ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>Reference <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a>.</p>


<p>Referenced by <a href="#ac1a2104a416aedf3c97462513ce13c1a">allocatedBeforeBytes</a>, <a href="#a7c0cf8b5d019262416e5f6afb44617f9">setBeforeBit</a> and <a href="#a882eba3c69318bd6bce348d05a1eee7e">setBeforeBytes</a>.</p>

</div>
</div>

### setAfterBit() {#abf23a077ec5e50be8c959fbaa58764f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::wholeprogramdevirt::VirtualCallTarget::setAfterBit (uint64_t Pos)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acccef23746c3dcaf68b96046a8bc2fce">minAfterBytes</a>, <a href="#adf3b9cd84b1fbc9cb8283e89ad5d1f6f">RetVal</a> and <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a>.</p>

</div>
</div>

### setAfterBytes() {#ac519a5aee06c9c3c48dc6fb9d4ab119a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::wholeprogramdevirt::VirtualCallTarget::setAfterBytes (uint64_t Pos, uint8_t Size)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6aeff409eb1e18f197498602d01aee94">IsBigEndian</a>, <a href="#acccef23746c3dcaf68b96046a8bc2fce">minAfterBytes</a>, <a href="#adf3b9cd84b1fbc9cb8283e89ad5d1f6f">RetVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a>.</p>

</div>
</div>

### setBeforeBit() {#a7c0cf8b5d019262416e5f6afb44617f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::wholeprogramdevirt::VirtualCallTarget::setBeforeBit (uint64_t Pos)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac3a85548479dea353a60994ffe26e6d7">minBeforeBytes</a>, <a href="#adf3b9cd84b1fbc9cb8283e89ad5d1f6f">RetVal</a> and <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a>.</p>

</div>
</div>

### setBeforeBytes() {#a882eba3c69318bd6bce348d05a1eee7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::wholeprogramdevirt::VirtualCallTarget::setBeforeBytes (uint64_t Pos, uint8_t Size)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6aeff409eb1e18f197498602d01aee94">IsBigEndian</a>, <a href="#ac3a85548479dea353a60994ffe26e6d7">minBeforeBytes</a>, <a href="#adf3b9cd84b1fbc9cb8283e89ad5d1f6f">RetVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#ae355164b95e2e82d5466dccd12b7f3fc">TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Fn {#a7ce909bc914445f4c5bab5fc525193c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue* llvm::wholeprogramdevirt::VirtualCallTarget::Fn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>Referenced by <a href="#a3956bd4bc329224815e72bfac06ee445">VirtualCallTarget</a> and <a href="#a55b16d241bb6365303178c509cd4227b">VirtualCallTarget</a>.</p>

</div>
</div>

### IsBigEndian {#a6aeff409eb1e18f197498602d01aee94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::wholeprogramdevirt::VirtualCallTarget::IsBigEndian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>Referenced by <a href="#ac519a5aee06c9c3c48dc6fb9d4ab119a">setAfterBytes</a>, <a href="#a882eba3c69318bd6bce348d05a1eee7e">setBeforeBytes</a>, <a href="#a3956bd4bc329224815e72bfac06ee445">VirtualCallTarget</a> and <a href="#a55b16d241bb6365303178c509cd4227b">VirtualCallTarget</a>.</p>

</div>
</div>

### RetVal {#adf3b9cd84b1fbc9cb8283e89ad5d1f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::wholeprogramdevirt::VirtualCallTarget::RetVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>Referenced by <a href="#abf23a077ec5e50be8c959fbaa58764f1">setAfterBit</a>, <a href="#ac519a5aee06c9c3c48dc6fb9d4ab119a">setAfterBytes</a>, <a href="#a7c0cf8b5d019262416e5f6afb44617f9">setBeforeBit</a> and <a href="#a882eba3c69318bd6bce348d05a1eee7e">setBeforeBytes</a>.</p>

</div>
</div>

### TM {#ae355164b95e2e82d5466dccd12b7f3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TypeMemberInfo* llvm::wholeprogramdevirt::VirtualCallTarget::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>Referenced by <a href="#a133904aa81277a5846c62fabd87b8cb4">allocatedAfterBytes</a>, <a href="#ac1a2104a416aedf3c97462513ce13c1a">allocatedBeforeBytes</a>, <a href="#acccef23746c3dcaf68b96046a8bc2fce">minAfterBytes</a>, <a href="#ac3a85548479dea353a60994ffe26e6d7">minBeforeBytes</a>, <a href="#abf23a077ec5e50be8c959fbaa58764f1">setAfterBit</a>, <a href="#ac519a5aee06c9c3c48dc6fb9d4ab119a">setAfterBytes</a>, <a href="#a7c0cf8b5d019262416e5f6afb44617f9">setBeforeBit</a>, <a href="#a882eba3c69318bd6bce348d05a1eee7e">setBeforeBytes</a>, <a href="#a3956bd4bc329224815e72bfac06ee445">VirtualCallTarget</a> and <a href="#a55b16d241bb6365303178c509cd4227b">VirtualCallTarget</a>.</p>

</div>
</div>

### WasDevirt {#ae9e93ca0e36159d9dbd5fa623689a2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::wholeprogramdevirt::VirtualCallTarget::WasDevirt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a>.</p>


<p>Referenced by <a href="#a3956bd4bc329224815e72bfac06ee445">VirtualCallTarget</a> and <a href="#a55b16d241bb6365303178c509cd4227b">VirtualCallTarget</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">WholeProgramDevirt.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
