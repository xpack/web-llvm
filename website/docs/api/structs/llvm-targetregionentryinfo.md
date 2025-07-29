---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetregionentryinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TargetRegionEntryInfo` Struct

<p>Data structure to contain the information needed to uniquely identify a target entry. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetRegionEntryInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8055c1edf9d161a65a820399e803add">TargetRegionEntryInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eac93a2c21595cafb4c8e4a816acf7b">TargetRegionEntryInfo</a> (StringRef ParentName, unsigned DeviceID, unsigned FileID, unsigned Line, unsigned Count=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c21df54ad219fb4f87a3532f89b090e">operator&lt;</a> (const TargetRegionEntryInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89525afb0a8095beeb2dc7b083491942">ParentName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a8eeba86c83f02b7e129b7880ec654">DeviceID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80293a526ecd17ee44ce5b982dff1ca1">FileID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f195e58ff3b0960a5c0884449d092a">Line</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc8999b43ab73c1f7f8618f7735f3cd">Count</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a267f191642077971aa8eeba25ea6f5">getTargetRegionEntryFnName</a> (SmallVectorImpl&lt; char &gt; &amp;Name, StringRef ParentName, unsigned DeviceID, unsigned FileID, unsigned Line, unsigned Count)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e78748236396089e6a27766e44407f9">KernelNamePrefix</a> = "__omp_offloading_"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The prefix used for kernel names. <a href="#a3e78748236396089e6a27766e44407f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Data structure to contain the information needed to uniquely identify a target entry.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetRegionEntryInfo() {#af8055c1edf9d161a65a820399e803add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetRegionEntryInfo::TargetRegionEntryInfo ()</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#a8cc8999b43ab73c1f7f8618f7735f3cd">Count</a>, <a href="#a50a8eeba86c83f02b7e129b7880ec654">DeviceID</a>, <a href="#a80293a526ecd17ee44ce5b982dff1ca1">FileID</a> and <a href="#a70f195e58ff3b0960a5c0884449d092a">Line</a>.</p>


<p>Referenced by <a href="#a6c21df54ad219fb4f87a3532f89b090e">operator&lt;</a>.</p>

</div>
</div>

### TargetRegionEntryInfo() {#a7eac93a2c21595cafb4c8e4a816acf7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetRegionEntryInfo::TargetRegionEntryInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ParentName, unsigned DeviceID, unsigned FileID, unsigned Line, unsigned Count=0)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#a8cc8999b43ab73c1f7f8618f7735f3cd">Count</a>, <a href="#a50a8eeba86c83f02b7e129b7880ec654">DeviceID</a>, <a href="#a80293a526ecd17ee44ce5b982dff1ca1">FileID</a>, <a href="#a70f195e58ff3b0960a5c0884449d092a">Line</a> and <a href="#a89525afb0a8095beeb2dc7b083491942">ParentName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a6c21df54ad219fb4f87a3532f89b090e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegionEntryInfo::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp; RHS)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="#a8cc8999b43ab73c1f7f8618f7735f3cd">Count</a>, <a href="#a50a8eeba86c83f02b7e129b7880ec654">DeviceID</a>, <a href="#a80293a526ecd17ee44ce5b982dff1ca1">FileID</a>, <a href="#a70f195e58ff3b0960a5c0884449d092a">Line</a>, <a href="#a89525afb0a8095beeb2dc7b083491942">ParentName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#af8055c1edf9d161a65a820399e803add">TargetRegionEntryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Count {#a8cc8999b43ab73c1f7f8618f7735f3cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetRegionEntryInfo::Count</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a0a267f191642077971aa8eeba25ea6f5">getTargetRegionEntryFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a8a88ec295fa5c83572df98cfaff271ed">llvm::OffloadEntriesInfoManager::hasTargetRegionEntryInfo</a>, <a href="#a6c21df54ad219fb4f87a3532f89b090e">operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a9736eb60d11b4a8d644d3e32346e7f56">llvm::OffloadEntriesInfoManager::registerTargetRegionEntryInfo</a>, <a href="#af8055c1edf9d161a65a820399e803add">TargetRegionEntryInfo</a> and <a href="#a7eac93a2c21595cafb4c8e4a816acf7b">TargetRegionEntryInfo</a>.</p>

</div>
</div>

### DeviceID {#a50a8eeba86c83f02b7e129b7880ec654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetRegionEntryInfo::DeviceID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a6827980ed8b61f42e680949ff4511b03">llvm::OffloadEntriesInfoManager::getTargetRegionEntryFnName</a>, <a href="#a0a267f191642077971aa8eeba25ea6f5">getTargetRegionEntryFnName</a>, <a href="#a6c21df54ad219fb4f87a3532f89b090e">operator&lt;</a>, <a href="#af8055c1edf9d161a65a820399e803add">TargetRegionEntryInfo</a> and <a href="#a7eac93a2c21595cafb4c8e4a816acf7b">TargetRegionEntryInfo</a>.</p>

</div>
</div>

### FileID {#a80293a526ecd17ee44ce5b982dff1ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetRegionEntryInfo::FileID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#afdc1b8675a946ce055c64607ba75af3a">llvm::OpenMPIRBuilder::getAddrOfDeclareTargetVar</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a6827980ed8b61f42e680949ff4511b03">llvm::OffloadEntriesInfoManager::getTargetRegionEntryFnName</a>, <a href="#a0a267f191642077971aa8eeba25ea6f5">getTargetRegionEntryFnName</a>, <a href="#a6c21df54ad219fb4f87a3532f89b090e">operator&lt;</a>, <a href="#af8055c1edf9d161a65a820399e803add">TargetRegionEntryInfo</a> and <a href="#a7eac93a2c21595cafb4c8e4a816acf7b">TargetRegionEntryInfo</a>.</p>

</div>
</div>

### Line {#a70f195e58ff3b0960a5c0884449d092a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetRegionEntryInfo::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a6827980ed8b61f42e680949ff4511b03">llvm::OffloadEntriesInfoManager::getTargetRegionEntryFnName</a>, <a href="#a0a267f191642077971aa8eeba25ea6f5">getTargetRegionEntryFnName</a>, <a href="#a6c21df54ad219fb4f87a3532f89b090e">operator&lt;</a>, <a href="#af8055c1edf9d161a65a820399e803add">TargetRegionEntryInfo</a> and <a href="#a7eac93a2c21595cafb4c8e4a816acf7b">TargetRegionEntryInfo</a>.</p>

</div>
</div>

### ParentName {#a89525afb0a8095beeb2dc7b083491942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::TargetRegionEntryInfo::ParentName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acc290ce16055813d4ee68af4c8023a09">llvm::OpenMPIRBuilder::createOffloadEntriesAndInfoMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a6827980ed8b61f42e680949ff4511b03">llvm::OffloadEntriesInfoManager::getTargetRegionEntryFnName</a>, <a href="#a0a267f191642077971aa8eeba25ea6f5">getTargetRegionEntryFnName</a>, <a href="#a6c21df54ad219fb4f87a3532f89b090e">operator&lt;</a> and <a href="#a7eac93a2c21595cafb4c8e4a816acf7b">TargetRegionEntryInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getTargetRegionEntryFnName() {#a0a267f191642077971aa8eeba25ea6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetRegionEntryInfo::getTargetRegionEntryFnName (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ParentName, unsigned DeviceID, unsigned FileID, unsigned Line, unsigned Count)</td>
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



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9405 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a8cc8999b43ab73c1f7f8618f7735f3cd">Count</a>, <a href="#a50a8eeba86c83f02b7e129b7880ec654">DeviceID</a>, <a href="#a80293a526ecd17ee44ce5b982dff1ca1">FileID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a3e78748236396089e6a27766e44407f9">KernelNamePrefix</a>, <a href="#a70f195e58ff3b0960a5c0884449d092a">Line</a> and <a href="#a89525afb0a8095beeb2dc7b083491942">ParentName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a6827980ed8b61f42e680949ff4511b03">llvm::OffloadEntriesInfoManager::getTargetRegionEntryFnName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### KernelNamePrefix {#a3e78748236396089e6a27766e44407f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::TargetRegionEntryInfo::KernelNamePrefix = "__omp_offloading_"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The prefix used for kernel names.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a36c152217dc69b5295561b2f99c52c17">llvm::omp::deconstructOpenMPKernelName</a> and <a href="#a0a267f191642077971aa8eeba25ea6f5">getTargetRegionEntryFnName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
