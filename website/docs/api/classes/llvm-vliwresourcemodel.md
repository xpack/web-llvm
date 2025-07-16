---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vliwresourcemodel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VLIWResourceModel` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::VLIWResourceModel { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">llvm/CodeGen/VLIWMachineScheduler.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagonvliwresourcemodel">HexagonVLIWResourceModel</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5142ae192809cf76ca4335049586561">VLIWResourceModel</a> (const TargetSubtargetInfo &amp;STI, const TargetSchedModel *SM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae38b56ead513cc53707d64b579c8fb1a">VLIWResourceModel</a> (const VLIWResourceModel &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321e4171b0c64d6ce799d8967353e01f">~VLIWResourceModel</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel">VLIWResourceModel</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a377f58bae12983d68a7726434837a">operator=</a> (const VLIWResourceModel &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af83154580059859d63f3daa3db32bdc8">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36231f2afc68d76cf54a3d4a8f87a70a">hasDependence</a> (const SUnit *SUd, const SUnit *SUu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is a dependence between SUd and SUu. <a href="#a36231f2afc68d76cf54a3d4a8f87a70a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa113683bb9cebc99c2711ac4a4c36dd">isResourceAvailable</a> (SUnit *SU, bool IsTop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if scheduling of this SU is possible in the current packet. <a href="#afa113683bb9cebc99c2711ac4a4c36dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6641c29e6f96fdf149d7f9f5dddec48f">reserveResources</a> (SUnit *SU, bool IsTop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of available resources. <a href="#a6641c29e6f96fdf149d7f9f5dddec48f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74e76c4c350e1d1675ae4ae9167c2a9">getTotalPackets</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25bdd2973e6aa462d954fd25ba81d87f">getPacketInstCount</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a788886ebcf4427cbaef1b29089eb0ff3">isInPacket</a> (SUnit *SU) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dfapacketizer">DFAPacketizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d0e9315e9e0aba0008b5028a6c2044">createPacketizer</a> (const TargetSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0ea915c66a119ea471d7a6a76d274d">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dfapacketizer">DFAPacketizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93aaa6653570715ab620a108c4a8dc1a">ResourcesModel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ResourcesModel - Represents VLIW state. <a href="#a93aaa6653570715ab620a108c4a8dc1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9cf1272e3d9e06f924b20c531686ce">SchedModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2eeb18e9cfc30d257ccfccc5891c435">Packet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Local packet/bundle model. <a href="#aa2eeb18e9cfc30d257ccfccc5891c435">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f06d239ea8fb5c027d2e4fb9518b0a">TotalPackets</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total packets created. <a href="#a17f06d239ea8fb5c027d2e4fb9518b0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VLIWResourceModel() {#af5142ae192809cf76ca4335049586561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWResourceModel::VLIWResourceModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a63d0e9315e9e0aba0008b5028a6c2044">createPacketizer</a>, <a href="#aa2eeb18e9cfc30d257ccfccc5891c435">Packet</a>, <a href="#a93aaa6653570715ab620a108c4a8dc1a">ResourcesModel</a>, <a href="#ade9cf1272e3d9e06f924b20c531686ce">SchedModel</a> and <a href="#afe0ea915c66a119ea471d7a6a76d274d">TII</a>.</p>


<p>Referenced by <a href="#a70a377f58bae12983d68a7726434837a">operator=</a> and <a href="#ae38b56ead513cc53707d64b579c8fb1a">VLIWResourceModel</a>.</p>

</div>
</div>

### VLIWResourceModel() {#ae38b56ead513cc53707d64b579c8fb1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VLIWResourceModel::VLIWResourceModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel">VLIWResourceModel</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Reference <a href="#af5142ae192809cf76ca4335049586561">VLIWResourceModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VLIWResourceModel() {#a321e4171b0c64d6ce799d8967353e01f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWResourceModel::~VLIWResourceModel ()</td>
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



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>Reference <a href="#a93aaa6653570715ab620a108c4a8dc1a">ResourcesModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a70a377f58bae12983d68a7726434837a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLIWResourceModel &amp; llvm::VLIWResourceModel::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel">VLIWResourceModel</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Reference <a href="#af5142ae192809cf76ca4335049586561">VLIWResourceModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPacketInstCount() {#a25bdd2973e6aa462d954fd25ba81d87f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::VLIWResourceModel::getPacketInstCount ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Reference <a href="#aa2eeb18e9cfc30d257ccfccc5891c435">Packet</a>.</p>

</div>
</div>

### getTotalPackets() {#af74e76c4c350e1d1675ae4ae9167c2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VLIWResourceModel::getTotalPackets ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Reference <a href="#a17f06d239ea8fb5c027d2e4fb9518b0a">TotalPackets</a>.</p>

</div>
</div>

### hasDependence() {#a36231f2afc68d76cf54a3d4a8f87a70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VLIWResourceModel::hasDependence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUd, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUu)</td>
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

<p>Return true if there is a dependence between SUd and SUu.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonvliwresourcemodel/#aa66dd2a7692adf3c952cd70ea8a43641">llvm::HexagonVLIWResourceModel::hasDependence</a> and <a href="#afa113683bb9cebc99c2711ac4a4c36dd">isResourceAvailable</a>.</p>

</div>
</div>

### isInPacket() {#a788886ebcf4427cbaef1b29089eb0ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VLIWResourceModel::isInPacket (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="#aa2eeb18e9cfc30d257ccfccc5891c435">Packet</a>.</p>

</div>
</div>

### isResourceAvailable() {#afa113683bb9cebc99c2711ac4a4c36dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VLIWResourceModel::isResourceAvailable (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTop)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if scheduling of this SU is possible in the current packet.</p>


<p>It is <em>not</em> precise (statefull), it is more like another heuristic. Many corner cases are figured empirically.</p>


<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#a36231f2afc68d76cf54a3d4a8f87a70a">hasDependence</a>, <a href="#aa2eeb18e9cfc30d257ccfccc5891c435">Packet</a> and <a href="#a93aaa6653570715ab620a108c4a8dc1a">ResourcesModel</a>.</p>


<p>Referenced by <a href="#a6641c29e6f96fdf149d7f9f5dddec48f">reserveResources</a>.</p>

</div>
</div>

### reserveResources() {#a6641c29e6f96fdf149d7f9f5dddec48f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VLIWResourceModel::reserveResources (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, bool IsTop)</td>
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

<p>Keep track of available resources.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#afa113683bb9cebc99c2711ac4a4c36dd">isResourceAvailable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa2eeb18e9cfc30d257ccfccc5891c435">Packet</a>, <a href="#af83154580059859d63f3daa3db32bdc8">reset</a>, <a href="#a93aaa6653570715ab620a108c4a8dc1a">ResourcesModel</a>, <a href="#ade9cf1272e3d9e06f924b20c531686ce">SchedModel</a> and <a href="#a17f06d239ea8fb5c027d2e4fb9518b0a">TotalPackets</a>.</p>

</div>
</div>

### reset() {#af83154580059859d63f3daa3db32bdc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VLIWResourceModel::reset ()</td>
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



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="#aa2eeb18e9cfc30d257ccfccc5891c435">Packet</a> and <a href="#a93aaa6653570715ab620a108c4a8dc1a">ResourcesModel</a>.</p>


<p>Referenced by <a href="#a6641c29e6f96fdf149d7f9f5dddec48f">reserveResources</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createPacketizer() {#a63d0e9315e9e0aba0008b5028a6c2044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DFAPacketizer * VLIWResourceModel::createPacketizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a186f383639b8c8fe141b55411d1121a9">llvm::TargetInstrInfo::CreateTargetScheduleState</a> and <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>.</p>


<p>Referenced by <a href="#af5142ae192809cf76ca4335049586561">VLIWResourceModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Packet {#aa2eeb18e9cfc30d257ccfccc5891c435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SUnit *&gt; llvm::VLIWResourceModel::Packet</td>
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

<p>Local packet/bundle model.</p>


<p>Purely internal to the MI scheduler at the time.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a25bdd2973e6aa462d954fd25ba81d87f">getPacketInstCount</a>, <a href="#a788886ebcf4427cbaef1b29089eb0ff3">isInPacket</a>, <a href="#afa113683bb9cebc99c2711ac4a4c36dd">isResourceAvailable</a>, <a href="#a6641c29e6f96fdf149d7f9f5dddec48f">reserveResources</a>, <a href="#af83154580059859d63f3daa3db32bdc8">reset</a> and <a href="#af5142ae192809cf76ca4335049586561">VLIWResourceModel</a>.</p>

</div>
</div>

### ResourcesModel {#a93aaa6653570715ab620a108c4a8dc1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DFAPacketizer* llvm::VLIWResourceModel::ResourcesModel</td>
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

<p>ResourcesModel - Represents VLIW state.</p>


<p>Not limited to VLIW targets per se, but assumes definition of resource model by a target.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#afa113683bb9cebc99c2711ac4a4c36dd">isResourceAvailable</a>, <a href="#a6641c29e6f96fdf149d7f9f5dddec48f">reserveResources</a>, <a href="#af83154580059859d63f3daa3db32bdc8">reset</a>, <a href="#af5142ae192809cf76ca4335049586561">VLIWResourceModel</a> and <a href="#a321e4171b0c64d6ce799d8967353e01f">~VLIWResourceModel</a>.</p>

</div>
</div>

### SchedModel {#ade9cf1272e3d9e06f924b20c531686ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel* llvm::VLIWResourceModel::SchedModel</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#a6641c29e6f96fdf149d7f9f5dddec48f">reserveResources</a> and <a href="#af5142ae192809cf76ca4335049586561">VLIWResourceModel</a>.</p>

</div>
</div>

### TII {#afe0ea915c66a119ea471d7a6a76d274d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::VLIWResourceModel::TII</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonvliwresourcemodel/#aa66dd2a7692adf3c952cd70ea8a43641">llvm::HexagonVLIWResourceModel::hasDependence</a> and <a href="#af5142ae192809cf76ca4335049586561">VLIWResourceModel</a>.</p>

</div>
</div>

### TotalPackets {#a17f06d239ea8fb5c027d2e4fb9518b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VLIWResourceModel::TotalPackets = 0</td>
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

<p>Total packets created.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a>.</p>


<p>Referenced by <a href="#af74e76c4c350e1d1675ae4ae9167c2a9">getTotalPackets</a> and <a href="#a6641c29e6f96fdf149d7f9f5dddec48f">reserveResources</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">VLIWMachineScheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/vliwmachinescheduler-cpp">VLIWMachineScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
