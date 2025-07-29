---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/offloadentriesinfomanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OffloadEntriesInfoManager` Class

<p>Class that manages information about offload code regions and data. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OffloadEntriesInfoManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp;EntryInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/offloadentryinfotargetregion">OffloadEntryInfoTargetRegion</a> &amp;)&gt; <a href="#ac115d36d95b2d0b214799c15f2df8cbf">OffloadTargetRegionEntryInfoActTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>brief Applies action <em>Action</em> on all registered entries. <a href="#ac115d36d95b2d0b214799c15f2df8cbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/offloadentryinfodeviceglobalvar">OffloadEntryInfoDeviceGlobalVar</a> &amp;)&gt; <a href="#a0035f4c66082f93a65972a35db34f497">OffloadDeviceGlobalVarEntryInfoActTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Applies action <em>Action</em> on all registered entries. <a href="#a0035f4c66082f93a65972a35db34f497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/offloadentryinfotargetregion">OffloadEntryInfoTargetRegion</a> &gt; <a href="#a399621ac2607a5de4f9060d3be66636c">OffloadEntriesTargetRegionTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/offloadentryinfodeviceglobalvar">OffloadEntryInfoDeviceGlobalVar</a> &gt; <a href="#a35b832225ed703f5a29342948be87f7f">OffloadEntriesDeviceGlobalVarTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage for device global variable entries kind. <a href="#a35b832225ed703f5a29342948be87f7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OMPTargetRegionEntryKind : uint32_t { <a href="#a4e85049eada7d6cc3bedde1433ce4a7b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kind of the target registry entry. <a href="#a4e85049eada7d6cc3bedde1433ce4a7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OMPTargetGlobalVarEntryKind : uint32_t { <a href="#ab9575c71365de4083a7be6ef6572d534">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kind of the global variable entry.. <a href="#ab9575c71365de4083a7be6ef6572d534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OMPTargetDeviceClauseKind : uint32_t { <a href="#a2dc9d099b77ee3b8db3b00ad9273823d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kind of device clause for declare target variables and functions NOTE: Currently not used as a part of a variable entry used for Flang and Clang to interface with the variable related registration functions. <a href="#a2dc9d099b77ee3b8db3b00ad9273823d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65fdcb97db8aec52c40aaa410875e5d9">OffloadEntriesInfoManager</a> (OpenMPIRBuilder *builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1c69166900a3ea831da7b0bda28554e">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a there are no entries defined. <a href="#af1c69166900a3ea831da7b0bda28554e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf155f94f5d49e4dd6dc17a3ae2fe4fa">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return number of entries defined so far. <a href="#aaf155f94f5d49e4dd6dc17a3ae2fe4fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05d360f14a80b1fc10d1632aa0f1433">initializeTargetRegionEntryInfo</a> (const TargetRegionEntryInfo &amp;EntryInfo, unsigned Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize target region entry. <a href="#ab05d360f14a80b1fc10d1632aa0f1433">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9736eb60d11b4a8d644d3e32346e7f56">registerTargetRegionEntryInfo</a> (TargetRegionEntryInfo EntryInfo, Constant *Addr, Constant *ID, OMPTargetRegionEntryKind Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> target region entry. <a href="#a9736eb60d11b4a8d644d3e32346e7f56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a88ec295fa5c83572df98cfaff271ed">hasTargetRegionEntryInfo</a> (TargetRegionEntryInfo EntryInfo, bool IgnoreAddressId=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a target region entry with the provided information exists. <a href="#a8a88ec295fa5c83572df98cfaff271ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6827980ed8b61f42e680949ff4511b03">getTargetRegionEntryFnName</a> (SmallVectorImpl&lt; char &gt; &amp;Name, const TargetRegionEntryInfo &amp;EntryInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87d491241b8ff7bdec84f22843c6ab5">actOnTargetRegionEntriesInfo</a> (const OffloadTargetRegionEntryInfoActTy &amp;Action)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4503192ffc49753d6b8ec734f2927742">initializeDeviceGlobalVarEntryInfo</a> (StringRef Name, OMPTargetGlobalVarEntryKind Flags, unsigned Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize device global variable entry. <a href="#a4503192ffc49753d6b8ec734f2927742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4229a8d4526cc8fc7d5e043727b07128">registerDeviceGlobalVarEntryInfo</a> (StringRef VarName, Constant *Addr, int64_t VarSize, OMPTargetGlobalVarEntryKind Flags, GlobalValue::LinkageTypes Linkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> device global variable entry. <a href="#a4229a8d4526cc8fc7d5e043727b07128">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca32e410f9038aada8d559cee9754d95">hasDeviceGlobalVarEntryInfo</a> (StringRef VarName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the variable with the given name has been registered already. <a href="#aca32e410f9038aada8d559cee9754d95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453a107a33d0d865ed6e021fc6cdcc20">actOnDeviceGlobalVarEntriesInfo</a> (const OffloadDeviceGlobalVarEntryInfoActTy &amp;Action)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96b74c176d5d60f1a260b97ca1ae7db">getTargetRegionEntryInfoCount</a> (const TargetRegionEntryInfo &amp;EntryInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the count of entries at a particular source location. <a href="#af96b74c176d5d60f1a260b97ca1ae7db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7206a799a071ced3be27833d03659342">incrementTargetRegionEntryInfoCount</a> (const TargetRegionEntryInfo &amp;EntryInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the count of entries at a particular source location. <a href="#a7206a799a071ced3be27833d03659342">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b9fccdd89a395523ce9bf866ea444d6">OMPBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of entries registered so far. <a href="#a8b9fccdd89a395523ce9bf866ea444d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a921193c2e2d5a6499b14834f6acd5e">OffloadingEntriesNum</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7afcc67060216ff841fccef7b091607">OffloadEntriesTargetRegionCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">OffloadEntriesTargetRegionTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc82ccba01900ab3ad0d002589f0fa4">OffloadEntriesTargetRegion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">OffloadEntriesDeviceGlobalVarTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49c225018cdcdaadd602cc74d738893b">OffloadEntriesDeviceGlobalVar</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a20827acbe600f63281115d6198a41">getTargetRegionEntryCountKey</a> (const TargetRegionEntryInfo &amp;EntryInfo)</td>
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

<p>Class that manages information about offload code regions and data.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### OffloadDeviceGlobalVarEntryInfoActTy {#a0035f4c66082f93a65972a35db34f497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef function_ref&lt;void(StringRef, const OffloadEntryInfoDeviceGlobalVar &amp;)&gt; llvm::OffloadEntriesInfoManager::OffloadDeviceGlobalVarEntryInfoActTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Applies action <em>Action</em> on all registered entries.</p>

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### OffloadTargetRegionEntryInfoActTy {#ac115d36d95b2d0b214799c15f2df8cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef function_ref&lt;void(const TargetRegionEntryInfo &amp;EntryInfo, const OffloadEntryInfoTargetRegion &amp;)&gt; llvm::OffloadEntriesInfoManager::OffloadTargetRegionEntryInfoActTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>brief Applies action <em>Action</em> on all registered entries.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### OffloadEntriesDeviceGlobalVarTy {#a35b832225ed703f5a29342948be87f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef StringMap&lt;OffloadEntryInfoDeviceGlobalVar&gt; llvm::OffloadEntriesInfoManager::OffloadEntriesDeviceGlobalVarTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Storage for device global variable entries kind.</p>


<p>The storage is to be indexed by mangled name.</p>


<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### OffloadEntriesTargetRegionTy {#a399621ac2607a5de4f9060d3be66636c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::map&lt;TargetRegionEntryInfo, OffloadEntryInfoTargetRegion&gt; llvm::OffloadEntriesInfoManager::OffloadEntriesTargetRegionTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### OMPTargetDeviceClauseKind {#a2dc9d099b77ee3b8db3b00ad9273823d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::OffloadEntriesInfoManager::OMPTargetDeviceClauseKind : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kind of device clause for declare target variables and functions NOTE: Currently not used as a part of a variable entry used for Flang and Clang to interface with the variable related registration functions.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetDeviceClauseAny<a id="a2dc9d099b77ee3b8db3b00ad9273823da168f6569c38da7979aa5e36d0a21b871"></a></td>
<td class="doxyEnumItemDescription">The target is marked for all devices (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetDeviceClauseNoHost<a id="a2dc9d099b77ee3b8db3b00ad9273823da0b01e5482bdaaeddc6a90686b1e99463"></a></td>
<td class="doxyEnumItemDescription">The target is marked for non-host devices (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetDeviceClauseHost<a id="a2dc9d099b77ee3b8db3b00ad9273823daf7d5c1f2266295444968655f5f3bd339"></a></td>
<td class="doxyEnumItemDescription">The target is marked for host devices (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetDeviceClauseNone<a id="a2dc9d099b77ee3b8db3b00ad9273823da830796e694a1ff7b17eff2d951c8f433"></a></td>
<td class="doxyEnumItemDescription">The target is marked as having no clause (= 0x3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### OMPTargetGlobalVarEntryKind {#ab9575c71365de4083a7be6ef6572d534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kind of the global variable entry..</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetGlobalVarEntryTo<a id="ab9575c71365de4083a7be6ef6572d534acf96797e65a60ff4302eb2bbdbbd8880"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a to declare target (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetGlobalVarEntryLink<a id="ab9575c71365de4083a7be6ef6572d534abe3a7916fb5f7a79d6aea6c0356e71a6"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a to declare target link (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetGlobalVarEntryEnter<a id="ab9575c71365de4083a7be6ef6572d534a1b9b415348a31bfeaa94e778e0421ddf"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a declare target enter (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetGlobalVarEntryNone<a id="ab9575c71365de4083a7be6ef6572d534a40aa302252a84ae8b11083d9f45f7577"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as having no declare target entry kind (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetGlobalVarEntryIndirect<a id="ab9575c71365de4083a7be6ef6572d534aba847264872ebbdaf660316167b89e15"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a declare target indirect global (= 0x8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetGlobalRegisterRequires<a id="ab9575c71365de4083a7be6ef6572d534ab16880c5ddd7886e422bf6dc1e670cca"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as a register requires global (= 0x10)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### OMPTargetRegionEntryKind {#a4e85049eada7d6cc3bedde1433ce4a7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::OffloadEntriesInfoManager::OMPTargetRegionEntryKind : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kind of the target registry entry.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OMPTargetRegionEntryTargetRegion<a id="a4e85049eada7d6cc3bedde1433ce4a7ba1e2537a111117d2cebad779b6de1856b"></a></td>
<td class="doxyEnumItemDescription">Mark the entry as target region (= 0x0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OffloadEntriesInfoManager() {#a65fdcb97db8aec52c40aaa410875e5d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OffloadEntriesInfoManager::OffloadEntriesInfoManager (<a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> * builder)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### actOnDeviceGlobalVarEntriesInfo() {#a453a107a33d0d865ed6e021fc6cdcc20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OffloadEntriesInfoManager::actOnDeviceGlobalVarEntriesInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0035f4c66082f93a65972a35db34f497">OffloadDeviceGlobalVarEntryInfoActTy</a> &amp; Action)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9817 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### actOnTargetRegionEntriesInfo() {#aa87d491241b8ff7bdec84f22843c6ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OffloadEntriesInfoManager::actOnTargetRegionEntriesInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ac115d36d95b2d0b214799c15f2df8cbf">OffloadTargetRegionEntryInfoActTy</a> &amp; Action)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9763 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### empty() {#af1c69166900a3ea831da7b0bda28554e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OffloadEntriesInfoManager::empty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a there are no entries defined.</p>

<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9686 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### getTargetRegionEntryFnName() {#a6827980ed8b61f42e680949ff4511b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OffloadEntriesInfoManager::getTargetRegionEntryFnName (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; EntryInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9415 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a50a8eeba86c83f02b7e129b7880ec654">llvm::TargetRegionEntryInfo::DeviceID</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a80293a526ecd17ee44ce5b982dff1ca1">llvm::TargetRegionEntryInfo::FileID</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a0a267f191642077971aa8eeba25ea6f5">llvm::TargetRegionEntryInfo::getTargetRegionEntryFnName</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a70f195e58ff3b0960a5c0884449d092a">llvm::TargetRegionEntryInfo::Line</a> and <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a89525afb0a8095beeb2dc7b083491942">llvm::TargetRegionEntryInfo::ParentName</a>.</p>

</div>
</div>

### hasDeviceGlobalVarEntryInfo() {#aca32e410f9038aada8d559cee9754d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OffloadEntriesInfoManager::hasDeviceGlobalVarEntryInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VarName)</td>
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

<p>Checks if the variable with the given name has been registered already.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a4229a8d4526cc8fc7d5e043727b07128">registerDeviceGlobalVarEntryInfo</a>.</p>

</div>
</div>

### hasTargetRegionEntryInfo() {#a8a88ec295fa5c83572df98cfaff271ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OffloadEntriesInfoManager::hasTargetRegionEntryInfo (<a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> EntryInfo, bool IgnoreAddressId=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a target region entry with the provided information exists.</p>

<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9747 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a8cc8999b43ab73c1f7f8618f7735f3cd">llvm::TargetRegionEntryInfo::Count</a>.</p>


<p>Referenced by <a href="#a9736eb60d11b4a8d644d3e32346e7f56">registerTargetRegionEntryInfo</a>.</p>

</div>
</div>

### initializeDeviceGlobalVarEntryInfo() {#a4503192ffc49753d6b8ec734f2927742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OffloadEntriesInfoManager::initializeDeviceGlobalVarEntryInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="#ab9575c71365de4083a7be6ef6572d534">OMPTargetGlobalVarEntryKind</a> Flags, unsigned Order)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize device global variable entry.</p>


<p>This is ONLY used for DEVICE compilation.</p>


<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9771 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### initializeTargetRegionEntryInfo() {#ab05d360f14a80b1fc10d1632aa0f1433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OffloadEntriesInfoManager::initializeTargetRegionEntryInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; EntryInfo, unsigned Order)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize target region entry.</p>


<p>This is ONLY needed for DEVICE compilation.</p>


<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9707 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="#a4e85049eada7d6cc3bedde1433ce4a7ba1e2537a111117d2cebad779b6de1856b">OMPTargetRegionEntryTargetRegion</a>.</p>

</div>
</div>

### registerDeviceGlobalVarEntryInfo() {#a4229a8d4526cc8fc7d5e043727b07128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OffloadEntriesInfoManager::registerDeviceGlobalVarEntryInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VarName, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Addr, int64_t VarSize, <a href="#ab9575c71365de4083a7be6ef6572d534">OMPTargetGlobalVarEntryKind</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> device global variable entry.</p>

<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9777 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aca32e410f9038aada8d559cee9754d95">hasDeviceGlobalVarEntryInfo</a> and <a href="#ab9575c71365de4083a7be6ef6572d534aba847264872ebbdaf660316167b89e15">OMPTargetGlobalVarEntryIndirect</a>.</p>

</div>
</div>

### registerTargetRegionEntryInfo() {#a9736eb60d11b4a8d644d3e32346e7f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OffloadEntriesInfoManager::registerTargetRegionEntryInfo (<a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> EntryInfo, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * ID, <a href="#a4e85049eada7d6cc3bedde1433ce4a7b">OMPTargetRegionEntryKind</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> target region entry.</p>

<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9715 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a8cc8999b43ab73c1f7f8618f7735f3cd">llvm::TargetRegionEntryInfo::Count</a>, <a href="#a8a88ec295fa5c83572df98cfaff271ed">hasTargetRegionEntryInfo</a> and <a href="#a4e85049eada7d6cc3bedde1433ce4a7ba1e2537a111117d2cebad779b6de1856b">OMPTargetRegionEntryTargetRegion</a>.</p>

</div>
</div>

### size() {#aaf155f94f5d49e4dd6dc17a3ae2fe4fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OffloadEntriesInfoManager::size ()</td>
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

<p>Return number of entries defined so far.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getTargetRegionEntryInfoCount() {#af96b74c176d5d60f1a260b97ca1ae7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned OffloadEntriesInfoManager::getTargetRegionEntryInfoCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; EntryInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the count of entries at a particular source location.</p>

<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9691 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### incrementTargetRegionEntryInfoCount() {#a7206a799a071ced3be27833d03659342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OffloadEntriesInfoManager::incrementTargetRegionEntryInfoCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; EntryInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the count of entries at a particular source location.</p>

<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9700 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OffloadEntriesDeviceGlobalVar {#a49c225018cdcdaadd602cc74d738893b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffloadEntriesDeviceGlobalVarTy llvm::OffloadEntriesInfoManager::OffloadEntriesDeviceGlobalVar</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### OffloadEntriesTargetRegion {#a2cc82ccba01900ab3ad0d002589f0fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OffloadEntriesTargetRegionTy llvm::OffloadEntriesInfoManager::OffloadEntriesTargetRegion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### OffloadEntriesTargetRegionCount {#ad7afcc67060216ff841fccef7b091607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;TargetRegionEntryInfo, unsigned&gt; llvm::OffloadEntriesInfoManager::OffloadEntriesTargetRegionCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### OffloadingEntriesNum {#a4a921193c2e2d5a6499b14834f6acd5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OffloadEntriesInfoManager::OffloadingEntriesNum = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### OMPBuilder {#a8b9fccdd89a395523ce9bf866ea444d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder* llvm::OffloadEntriesInfoManager::OMPBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of entries registered so far.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getTargetRegionEntryCountKey() {#a30a20827acbe600f63281115d6198a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetRegionEntryInfo llvm::OffloadEntriesInfoManager::getTargetRegionEntryCountKey (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; EntryInfo)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
