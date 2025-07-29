---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpslottracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPSlotTracker` Class

<p>This class can be used to assign names to VPValues. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPSlotTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">Transforms/Vectorize/VPlanValue.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4976fefaf9696951a382fbfb6c40eeb">VPSlotTracker</a> (const VPlan *Plan=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a7e7a1fc5386a94fa15cc6e157d7b79">getOrCreateName</a> (const VPValue *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name assigned to <span class="doxyComputerOutput">V</span>, if there is one, otherwise try to construct one from the underlying value, if there's one; else return &lt;badref&gt;. <a href="#a5a7e7a1fc5386a94fa15cc6e157d7b79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21a62be17505b8e95f1ba9b65e491fd">assignName</a> (const VPValue *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3a0cb898b18b395490c0b21a6a58842">assignNames</a> (const VPlan &amp;Plan)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1da45fb3d74a71853bce0d2c1f16c5db">assignNames</a> (const VPBasicBlock *VPBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5085b9135c14df9133460f26eac4cba">VPValue2Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of versioned names assigned to VPValues with underlying IR values. <a href="#ac5085b9135c14df9133460f26eac4cba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7aeae75439b534f6e1fdcc4c4563475">BaseName2Version</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the next number to use to version the base name. <a href="#aa7aeae75439b534f6e1fdcc4c4563475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf0ee8d7965c4302c94076a80d48642">NextSlot</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number to assign to the next <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> without underlying value. <a href="#abdf0ee8d7965c4302c94076a80d48642">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class can be used to assign names to VPValues.</p>


<p>For VPValues without underlying value, assign consecutive numbers and use those as names (wrapped in vp&lt;&gt;). Otherwise, use the name from the underlying value (wrapped in ir&lt;&gt;), appending a .V version number if there are multiple uses of the same name. Allows querying names for VPValues for printing, similar to the <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> for IR values.</p>


<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VPSlotTracker() {#ac4976fefaf9696951a382fbfb6c40eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPSlotTracker::VPSlotTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> * Plan=nullptr)</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getOrCreateName() {#a5a7e7a1fc5386a94fa15cc6e157d7b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string VPSlotTracker::getOrCreateName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the name assigned to <span class="doxyComputerOutput">V</span>, if there is one, otherwise try to construct one from the underlying value, if there's one; else return &lt;badref&gt;.</p>

<p>Declaration at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1577 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#a6c88376daf23b16ad26b7ac6c224d21e">llvm::VPRecipeBase::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a8d57e2fe646928a51e97714005eefdc7">llvm::VPBlockBase::getPlan</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#a3fc47e93505e87044e0861e4142eca20">llvm::VPValue::printAsOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignName() {#af21a62be17505b8e95f1ba9b65e491fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPSlotTracker::assignName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1514 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>

</div>
</div>

### assignNames() {#aa3a0cb898b18b395490c0b21a6a58842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPSlotTracker::assignNames (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1553 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>

</div>
</div>

### assignNames() {#a1da45fb3d74a71853bce0d2c1f16c5db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPSlotTracker::assignNames (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1571 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseName2Version {#aa7aeae75439b534f6e1fdcc4c4563475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; llvm::VPSlotTracker::BaseName2Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the next number to use to version the base name.</p>

<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### NextSlot {#abdf0ee8d7965c4302c94076a80d48642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPSlotTracker::NextSlot = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number to assign to the next <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> without underlying value.</p>

<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### VPValue2Name {#ac5085b9135c14df9133460f26eac4cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const VPValue *, std::string&gt; llvm::VPSlotTracker::VPValue2Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of versioned names assigned to VPValues with underlying IR values.</p>

<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
