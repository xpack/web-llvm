---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/orc/rt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `rt` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::orc::rt { ... }
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59cbb375727166fc83c1ed4a1e00010b">SPSSimpleExecutorDylibManagerOpenSignature</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">shared::SPSExpected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a> &gt;(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a3b101487ee72cf9033225840204e68bb">shared::SPSString</a>, uint64_t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a074336153a117ca2ccd97221e728a5c3">SPSSimpleExecutorDylibManagerLookupSignature</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">shared::SPSExpected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">shared::SPSSequence</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a2e25123fcbb940292ea9a1f907924952">shared::SPSExecutorSymbolDef</a> &gt; &gt;( <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#aa4683bc096f3b0cd8be3e2bcfa5924fa">shared::SPSRemoteSymbolLookupSet</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a050da764894bd3ab4db31952c8982c39">SPSSimpleExecutorMemoryManagerReserveSignature</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">shared::SPSExpected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a> &gt;(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, uint64_t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a748877e70deb4d5cfba84c82ae219701">SPSSimpleExecutorMemoryManagerFinalizeSignature</a> = shared::SPSError(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a35b277daedca31091f550803ef8834c0">shared::SPSFinalizeRequest</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbeca9ac4a6c6710667297da29cc62c4">SPSSimpleExecutorMemoryManagerDeallocateSignature</a> = shared::SPSError( <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">shared::SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a> &gt;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557165be8fb59bae42025bd5c59541bb">SPSExecutorSharedMemoryMapperServiceReserveSignature</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">shared::SPSExpected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">shared::SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a3b101487ee72cf9033225840204e68bb">shared::SPSString</a> &gt; &gt;( <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, uint64_t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde1ae43605670d8b04367538b53ae4c">SPSExecutorSharedMemoryMapperServiceInitializeSignature</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">shared::SPSExpected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a> &gt;( <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#aa747eff51a403ae9b4d7a429b63cbfc7">shared::SPSSharedMemoryFinalizeRequest</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae643ba16206c473d4fa46b2e6891b495">SPSExecutorSharedMemoryMapperServiceDeinitializeSignature</a> = shared::SPSError(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">shared::SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a> &gt;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7edf987a15b9ab28b0bd14558106a01">SPSExecutorSharedMemoryMapperServiceReleaseSignature</a> = shared::SPSError( <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">shared::SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a> &gt;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089acd594927cea1e4a54d2081357adf">SPSRunAsMainSignature</a> = int64_t(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">shared::SPSSequence</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a3b101487ee72cf9033225840204e68bb">shared::SPSString</a> &gt;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3991d73f7bf5524bc58acb9ad0277ab2">SPSRunAsVoidFunctionSignature</a> = int32_t(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa897fd436b75aeb029811e35f1683c07">SPSRunAsIntFunctionSignature</a> = int32_t(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">shared::SPSExecutorAddr</a>, int32_t)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5000e68c40d7a033515b57676e2b59c">SimpleExecutorDylibManagerInstanceName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bb4954899f7b8d42b5c1efed3aff24">SimpleExecutorDylibManagerOpenWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc7ccbe616e10eaa1e40ab3ef4e1cd0">SimpleExecutorDylibManagerLookupWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefed2faa1885d142243754bc19726f68">SimpleExecutorMemoryManagerInstanceName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e31b039e3f8f9d74a5ecc9fc4445e9">SimpleExecutorMemoryManagerReserveWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1386745ca3127ba6afbb98a00984da28">SimpleExecutorMemoryManagerFinalizeWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66900c0d1cb7093763fdf126c66fb770">SimpleExecutorMemoryManagerDeallocateWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37bd244700f67073b1a7fd36d4b0c6df">ExecutorSharedMemoryMapperServiceInstanceName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7496ff8990f2e5591c5b891e8f674e9e">ExecutorSharedMemoryMapperServiceReserveWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79a01251b80e17a178dd67316d2c3f0">ExecutorSharedMemoryMapperServiceInitializeWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98730faf23f94a2a4e52ea58da0af591">ExecutorSharedMemoryMapperServiceDeinitializeWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e9a0ddd7ddd135851d649fb8234373b">ExecutorSharedMemoryMapperServiceReleaseWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7198652f85526109e77300b9b67f559">MemoryWriteUInt8sWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a7b80a8e73315cd597145aa582492f">MemoryWriteUInt16sWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a53cab0630ca7f22bc6c2074fc5be8">MemoryWriteUInt32sWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48f07bac1a7bc98ef719170b0ebb6b9">MemoryWriteUInt64sWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca94690d0b8e760f473aab2fa27d5c23">MemoryWriteBuffersWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89935ea06c8efbd5b88cc51afd4d38f">MemoryWritePointersWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a708d9b5b8008550fc5bcbda4264b33fe">RegisterEHFrameSectionWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f498b849914201972f86b5bbcb41a9">DeregisterEHFrameSectionWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d022df65cef8fec8bc53d39f9d918a">RunAsMainWrapperName</a> = "__llvm_orc_bootstrap_run_as_main_wrapper"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46df3c9953b16c7deb29b22d05bd6db">RunAsVoidFunctionWrapperName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f1789497f8bff6fa2ff287fc252d0a">RunAsIntFunctionWrapperName</a> = ...</td>
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


<div class="doxySectionDef">

## Typedefs

### SPSExecutorSharedMemoryMapperServiceDeinitializeSignature {#ae643ba16206c473d4fa46b2e6891b495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSExecutorSharedMemoryMapperServiceDeinitializeSignature = 
    shared::SPSError(shared::SPSExecutorAddr,
                     shared::SPSSequence&lt;shared::SPSExecutorAddr&gt;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSExecutorSharedMemoryMapperServiceInitializeSignature {#acde1ae43605670d8b04367538b53ae4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSExecutorSharedMemoryMapperServiceInitializeSignature = 
    shared::SPSExpected&lt;shared::SPSExecutorAddr&gt;(
        shared::SPSExecutorAddr, shared::SPSExecutorAddr,
        shared::SPSSharedMemoryFinalizeRequest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSExecutorSharedMemoryMapperServiceReleaseSignature {#af7edf987a15b9ab28b0bd14558106a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSExecutorSharedMemoryMapperServiceReleaseSignature =  shared::SPSError(
    shared::SPSExecutorAddr, shared::SPSSequence&lt;shared::SPSExecutorAddr&gt;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSExecutorSharedMemoryMapperServiceReserveSignature {#a557165be8fb59bae42025bd5c59541bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSExecutorSharedMemoryMapperServiceReserveSignature = 
    shared::SPSExpected&lt;
        shared::SPSTuple&lt;shared::SPSExecutorAddr, shared::SPSString&gt;&gt;(
        shared::SPSExecutorAddr, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSRunAsIntFunctionSignature {#aa897fd436b75aeb029811e35f1683c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSRunAsIntFunctionSignature =  int32_t(shared::SPSExecutorAddr, int32_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSRunAsMainSignature {#a089acd594927cea1e4a54d2081357adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSRunAsMainSignature =  int64_t(shared::SPSExecutorAddr,
                                      shared::SPSSequence&lt;shared::SPSString&gt;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSRunAsVoidFunctionSignature {#a3991d73f7bf5524bc58acb9ad0277ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSRunAsVoidFunctionSignature =  int32_t(shared::SPSExecutorAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSSimpleExecutorDylibManagerLookupSignature {#a074336153a117ca2ccd97221e728a5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSSimpleExecutorDylibManagerLookupSignature = 
    shared::SPSExpected&lt;shared::SPSSequence&lt;shared::SPSExecutorSymbolDef&gt;&gt;(
        shared::SPSExecutorAddr, shared::SPSExecutorAddr,
        shared::SPSRemoteSymbolLookupSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSSimpleExecutorDylibManagerOpenSignature {#a59cbb375727166fc83c1ed4a1e00010b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSSimpleExecutorDylibManagerOpenSignature = 
    shared::SPSExpected&lt;shared::SPSExecutorAddr&gt;(shared::SPSExecutorAddr,
                                                 shared::SPSString, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSSimpleExecutorMemoryManagerDeallocateSignature {#afbeca9ac4a6c6710667297da29cc62c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSSimpleExecutorMemoryManagerDeallocateSignature =  shared::SPSError(
    shared::SPSExecutorAddr, shared::SPSSequence&lt;shared::SPSExecutorAddr&gt;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSSimpleExecutorMemoryManagerFinalizeSignature {#a748877e70deb4d5cfba84c82ae219701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSSimpleExecutorMemoryManagerFinalizeSignature = 
    shared::SPSError(shared::SPSExecutorAddr, shared::SPSFinalizeRequest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

### SPSSimpleExecutorMemoryManagerReserveSignature {#a050da764894bd3ab4db31952c8982c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::rt::SPSSimpleExecutorMemoryManagerReserveSignature = 
    shared::SPSExpected&lt;shared::SPSExecutorAddr&gt;(shared::SPSExecutorAddr,
                                                 uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DeregisterEHFrameSectionWrapperName {#a68f498b849914201972f86b5bbcb41a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::DeregisterEHFrameSectionWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm_orc_deregisterEHFrameSectionWrapper"
</div>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2eb4c57e962ea964e0917f7dee774c93">llvm::orc::addDefaultBootstrapValuesForHostProcess</a>.</p>

</div>
</div>

### ExecutorSharedMemoryMapperServiceDeinitializeWrapperName {#a98730faf23f94a2a4e52ea58da0af591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::ExecutorSharedMemoryMapperServiceDeinitializeWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_ExecutorSharedMemoryMapperService_Deinitialize"
</div>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a30b2bf2d887d64fbcbd360accb5ed8a1">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::addBootstrapSymbols</a>.</p>

</div>
</div>

### ExecutorSharedMemoryMapperServiceInitializeWrapperName {#af79a01251b80e17a178dd67316d2c3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::ExecutorSharedMemoryMapperServiceInitializeWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_ExecutorSharedMemoryMapperService_Initialize"
</div>
</dd>
</dl>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a30b2bf2d887d64fbcbd360accb5ed8a1">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::addBootstrapSymbols</a>.</p>

</div>
</div>

### ExecutorSharedMemoryMapperServiceInstanceName {#a37bd244700f67073b1a7fd36d4b0c6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::ExecutorSharedMemoryMapperServiceInstanceName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_ExecutorSharedMemoryMapperService_Instance"
</div>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a30b2bf2d887d64fbcbd360accb5ed8a1">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::addBootstrapSymbols</a>.</p>

</div>
</div>

### ExecutorSharedMemoryMapperServiceReleaseWrapperName {#a9e9a0ddd7ddd135851d649fb8234373b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::ExecutorSharedMemoryMapperServiceReleaseWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_ExecutorSharedMemoryMapperService_Release"
</div>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a30b2bf2d887d64fbcbd360accb5ed8a1">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::addBootstrapSymbols</a>.</p>

</div>
</div>

### ExecutorSharedMemoryMapperServiceReserveWrapperName {#a7496ff8990f2e5591c5b891e8f674e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::ExecutorSharedMemoryMapperServiceReserveWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_ExecutorSharedMemoryMapperService_Reserve"
</div>
</dd>
</dl>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a30b2bf2d887d64fbcbd360accb5ed8a1">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::addBootstrapSymbols</a>.</p>

</div>
</div>

### MemoryWriteBuffersWrapperName {#aca94690d0b8e760f473aab2fa27d5c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::MemoryWriteBuffersWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_bootstrap_mem_write_buffers_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### MemoryWritePointersWrapperName {#aa89935ea06c8efbd5b88cc51afd4d38f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::MemoryWritePointersWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_bootstrap_mem_write_pointers_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### MemoryWriteUInt16sWrapperName {#a16a7b80a8e73315cd597145aa582492f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::MemoryWriteUInt16sWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_bootstrap_mem_write_uint16s_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### MemoryWriteUInt32sWrapperName {#ab1a53cab0630ca7f22bc6c2074fc5be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::MemoryWriteUInt32sWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_bootstrap_mem_write_uint32s_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### MemoryWriteUInt64sWrapperName {#aa48f07bac1a7bc98ef719170b0ebb6b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::MemoryWriteUInt64sWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_bootstrap_mem_write_uint64s_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### MemoryWriteUInt8sWrapperName {#aa7198652f85526109e77300b9b67f559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::MemoryWriteUInt8sWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_bootstrap_mem_write_uint8s_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### RegisterEHFrameSectionWrapperName {#a708d9b5b8008550fc5bcbda4264b33fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::RegisterEHFrameSectionWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm_orc_registerEHFrameSectionWrapper"
</div>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2eb4c57e962ea964e0917f7dee774c93">llvm::orc::addDefaultBootstrapValuesForHostProcess</a>.</p>

</div>
</div>

### RunAsIntFunctionWrapperName {#a29f1789497f8bff6fa2ff287fc252d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::RunAsIntFunctionWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_bootstrap_run_as_int_function_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### RunAsMainWrapperName {#ae0d022df65cef8fec8bc53d39f9d918a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::RunAsMainWrapperName = "__llvm_orc_bootstrap_run_as_main_wrapper"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### RunAsVoidFunctionWrapperName {#ac46df3c9953b16c7deb29b22d05bd6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::RunAsVoidFunctionWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_bootstrap_run_as_void_function_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt-bootstrap/#a80380ad8a5c79d75366b0c1d968a4b7c">llvm::orc::rt_bootstrap::addTo</a>.</p>

</div>
</div>

### SimpleExecutorDylibManagerInstanceName {#ae5000e68c40d7a033515b57676e2b59c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::SimpleExecutorDylibManagerInstanceName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_SimpleExecutorDylibManager_Instance"
</div>
</dd>
</dl>

<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#adecf4516866175cd6afadcb25ba6e888">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::addBootstrapSymbols</a>.</p>

</div>
</div>

### SimpleExecutorDylibManagerLookupWrapperName {#a9dc7ccbe616e10eaa1e40ab3ef4e1cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::SimpleExecutorDylibManagerLookupWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_SimpleExecutorDylibManager_lookup_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#adecf4516866175cd6afadcb25ba6e888">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::addBootstrapSymbols</a>.</p>

</div>
</div>

### SimpleExecutorDylibManagerOpenWrapperName {#a86bb4954899f7b8d42b5c1efed3aff24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::SimpleExecutorDylibManagerOpenWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_SimpleExecutorDylibManager_open_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#adecf4516866175cd6afadcb25ba6e888">llvm::orc::rt_bootstrap::SimpleExecutorDylibManager::addBootstrapSymbols</a>.</p>

</div>
</div>

### SimpleExecutorMemoryManagerDeallocateWrapperName {#a66900c0d1cb7093763fdf126c66fb770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::SimpleExecutorMemoryManagerDeallocateWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_SimpleExecutorMemoryManager_deallocate_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#ae8c4ce91d8e4f8891a7b0b4aa07dc301">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::addBootstrapSymbols</a>.</p>

</div>
</div>

### SimpleExecutorMemoryManagerFinalizeWrapperName {#a1386745ca3127ba6afbb98a00984da28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::SimpleExecutorMemoryManagerFinalizeWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_SimpleExecutorMemoryManager_finalize_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#ae8c4ce91d8e4f8891a7b0b4aa07dc301">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::addBootstrapSymbols</a>.</p>

</div>
</div>

### SimpleExecutorMemoryManagerInstanceName {#aefed2faa1885d142243754bc19726f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::SimpleExecutorMemoryManagerInstanceName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_SimpleExecutorMemoryManager_Instance"
</div>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#ae8c4ce91d8e4f8891a7b0b4aa07dc301">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::addBootstrapSymbols</a>.</p>

</div>
</div>

### SimpleExecutorMemoryManagerReserveWrapperName {#a75e31b039e3f8f9d74a5ecc9fc4445e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::orc::rt::SimpleExecutorMemoryManagerReserveWrapperName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "__llvm_orc_SimpleExecutorMemoryManager_reserve_wrapper"
</div>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#ae8c4ce91d8e4f8891a7b0b4aa07dc301">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::addBootstrapSymbols</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/orcrtbridge-h">OrcRTBridge.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcrtbridge-cpp">OrcRTBridge.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
