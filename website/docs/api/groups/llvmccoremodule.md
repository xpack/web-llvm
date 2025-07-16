---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccoremodule
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Modules Reference

<p>Modules represent the top-level structure in an LLVM program. <a href="#details">More...</a></p>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8cf6711b9359fb55d081bfc5e664370c">LLVMModuleCreateWithName</a> (const char *ModuleID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new, empty module in the global context. <a href="#ga8cf6711b9359fb55d081bfc5e664370c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6bf4a0a387cf7fe04cbe0438cdb36a51">LLVMModuleCreateWithNameInContext</a> (const char *ModuleID, LLVMContextRef C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new, empty module in a specific context. <a href="#ga6bf4a0a387cf7fe04cbe0438cdb36a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabffdc747c14d77b3eb89500adf4f269b">LLVMCloneModule</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an exact copy of the specified module. <a href="#gabffdc747c14d77b3eb89500adf4f269b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4acadb366d5ff0405371508ca741a5bf">LLVMDisposeModule</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy a module instance. <a href="#ga4acadb366d5ff0405371508ca741a5bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Soon to be deprecated. <a href="#ga1adb5d14471960646da56e130c6a0f84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacf510322862cd8d09fb5c614ebe09ab3">LLVMSetIsNewDbgInfoFormat</a> (LLVMModuleRef M, LLVMBool UseNewFormat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Soon to be deprecated. <a href="#gacf510322862cd8d09fb5c614ebe09ab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga053573a690cdb1e6c84451b980fd4155">LLVMGetModuleIdentifier</a> (LLVMModuleRef M, size_t *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the identifier of a module. <a href="#ga053573a690cdb1e6c84451b980fd4155">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaefcadd23e3fa1bc03f5af51b4689a2cf">LLVMSetModuleIdentifier</a> (LLVMModuleRef M, const char *Ident, size_t Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the identifier of a module to a string Ident with length Len. <a href="#gaefcadd23e3fa1bc03f5af51b4689a2cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5ef5081177ddb952a4f0c1b5465b41f9">LLVMGetSourceFileName</a> (LLVMModuleRef M, size_t *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the module's original source file name. <a href="#ga5ef5081177ddb952a4f0c1b5465b41f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3144997c9342d7df8af0e7550f39a506">LLVMSetSourceFileName</a> (LLVMModuleRef M, const char *Name, size_t Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the original source file name of a module to a string Name with length Len. <a href="#ga3144997c9342d7df8af0e7550f39a506">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga79c76af8c81bc8e2de2da48f7135997a">LLVMGetDataLayoutStr</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the data layout for a module. <a href="#ga79c76af8c81bc8e2de2da48f7135997a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac013e4aeb6a0674f18702e8f76f889c7">LLVMGetDataLayout</a> (LLVMModuleRef M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga125b4ef3982a95cf99cf052866c3c4f5">LLVMSetDataLayout</a> (LLVMModuleRef M, const char *DataLayoutStr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the data layout for a module. <a href="#ga125b4ef3982a95cf99cf052866c3c4f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaab7f6420f76734cbb0a22c5ba435a464">LLVMGetTarget</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the target triple for a module. <a href="#gaab7f6420f76734cbb0a22c5ba435a464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga792209d857f53a72ac34fec1c599664a">LLVMSetTarget</a> (LLVMModuleRef M, const char *Triple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the target triple for a module. <a href="#ga792209d857f53a72ac34fec1c599664a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga2582ca8c28f123476fb606097b475ed6">LLVMModuleFlagEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8e9d8283d0b2d13fc9f119c00730c4e1">LLVMCopyModuleFlagsMetadata</a> (LLVMModuleRef M, size_t *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the module flags as an array of flag-key-value triples. <a href="#ga8e9d8283d0b2d13fc9f119c00730c4e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga958e46099b5025db3567fdd036198f36">LLVMDisposeModuleFlagsMetadata</a> (LLVMModuleFlagEntry *Entries)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroys module flags metadata entries. <a href="#ga958e46099b5025db3567fdd036198f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoretypes/#gaa61633f872a8b3cbcbab5f5a96d3ce0f">LLVMModuleFlagBehavior</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7ffb147f3127ad15810853e2c984efda">LLVMModuleFlagEntriesGetFlagBehavior</a> (LLVMModuleFlagEntry *Entries, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the flag behavior for a module flag entry at a specific index. <a href="#ga7ffb147f3127ad15810853e2c984efda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga78a873e9b162867e522b5f1b5e6f67a3">LLVMModuleFlagEntriesGetKey</a> (LLVMModuleFlagEntry *Entries, unsigned Index, size_t *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the key for a module flag entry at a specific index. <a href="#ga78a873e9b162867e522b5f1b5e6f67a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6fb875163266d4dba53b46b1c6e0c263">LLVMModuleFlagEntriesGetMetadata</a> (LLVMModuleFlagEntry *Entries, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the metadata for a module flag entry at a specific index. <a href="#ga6fb875163266d4dba53b46b1c6e0c263">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabac5acb60629380b378eb8d9033de04c">LLVMGetModuleFlag</a> (LLVMModuleRef M, const char *Key, size_t KeyLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module-level flag to the module-level flags metadata if it doesn't already exist. <a href="#gabac5acb60629380b378eb8d9033de04c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga91746975955737845b0f9a3b33c415f5">LLVMAddModuleFlag</a> (LLVMModuleRef M, LLVMModuleFlagBehavior Behavior, const char *Key, size_t KeyLen, LLVMMetadataRef Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module-level flag to the module-level flags metadata if it doesn't already exist. <a href="#ga91746975955737845b0f9a3b33c415f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga31c87315ba3f595d6786c47a50d9f8e7">LLVMDumpModule</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a representation of a module to stderr. <a href="#ga31c87315ba3f595d6786c47a50d9f8e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4879fe0f5852edd39ea4a1e14d413bb0">LLVMPrintModuleToFile</a> (LLVMModuleRef M, const char *Filename, char **ErrorMessage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a representation of a module to a file. <a href="#ga4879fe0f5852edd39ea4a1e14d413bb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae0d61246e5b4f768588aef14e124a96b">LLVMPrintModuleToString</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string representation of the module. <a href="#gae0d61246e5b4f768588aef14e124a96b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga51c7c33e8376848eeb431e89b4a17f0c">LLVMGetModuleInlineAsm</a> (LLVMModuleRef M, size_t *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get inline assembly for a module. <a href="#ga51c7c33e8376848eeb431e89b4a17f0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab2633096e900a099e4ba1bcb0e28e620">LLVMSetModuleInlineAsm2</a> (LLVMModuleRef M, const char *Asm, size_t Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set inline assembly for a module. <a href="#gab2633096e900a099e4ba1bcb0e28e620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga357390c6ae457d796f6ae08cff56926d">LLVMAppendModuleInlineAsm</a> (LLVMModuleRef M, const char *Asm, size_t Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append inline assembly to a module. <a href="#ga357390c6ae457d796f6ae08cff56926d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4efd515d9e18a2bc89017e53a44142c2">LLVMGetInlineAsm</a> (LLVMTypeRef Ty, const char *AsmString, size_t AsmStringSize, const char *Constraints, size_t ConstraintsSize, LLVMBool HasSideEffects, LLVMBool IsAlignStack, LLVMInlineAsmDialect Dialect, LLVMBool CanThrow)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the specified uniqued inline asm string. <a href="#ga4efd515d9e18a2bc89017e53a44142c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7cc10368c3bcc93aef4159d9b788aaad">LLVMGetInlineAsmAsmString</a> (LLVMValueRef InlineAsmVal, size_t *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the template string used for an inline assembly snippet. <a href="#ga7cc10368c3bcc93aef4159d9b788aaad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6aab40de7b0d5bc2b765151ed050df76">LLVMGetInlineAsmConstraintString</a> (LLVMValueRef InlineAsmVal, size_t *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the raw constraint string for an inline assembly snippet. <a href="#ga6aab40de7b0d5bc2b765151ed050df76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoretypes/#gafa932ff1a3dabfe8c6109edd2b25baaf">LLVMInlineAsmDialect</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga95e52974c4e5460f3341688464c3ed73">LLVMGetInlineAsmDialect</a> (LLVMValueRef InlineAsmVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the dialect used by the inline asm snippet. <a href="#ga95e52974c4e5460f3341688464c3ed73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaee5f092641dc2a86cd315ed718b7a345">LLVMGetInlineAsmFunctionType</a> (LLVMValueRef InlineAsmVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the function type of the inline assembly snippet. <a href="#gaee5f092641dc2a86cd315ed718b7a345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga92d29d949187ef2e53abc4999ba5d0da">LLVMGetInlineAsmHasSideEffects</a> (LLVMValueRef InlineAsmVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get if the inline asm snippet has side effects. <a href="#ga92d29d949187ef2e53abc4999ba5d0da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8bd4c578ee6391ce16b3936d04af8cf8">LLVMGetInlineAsmNeedsAlignedStack</a> (LLVMValueRef InlineAsmVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get if the inline asm snippet needs an aligned stack. <a href="#ga8bd4c578ee6391ce16b3936d04af8cf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab9e9f884e7bfa21ae7f86b0d551ad849">LLVMGetInlineAsmCanUnwind</a> (LLVMValueRef InlineAsmVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get if the inline asm snippet may unwind the stack. <a href="#gab9e9f884e7bfa21ae7f86b0d551ad849">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga66fd1dc1c47edded31b7e802066e2a2e">LLVMGetModuleContext</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the context to which this module is associated. <a href="#ga66fd1dc1c47edded31b7e802066e2a2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga29066e749e093fba6fedb5efa0962177">LLVMGetTypeByName</a> (LLVMModuleRef M, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMGetTypeByName2 instead. <a href="#ga29066e749e093fba6fedb5efa0962177">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf9a80c7e6b324262edc1ff545411ea26">LLVMGetFirstNamedMetadata</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain an iterator to the first NamedMDNode in a Module. <a href="#gaf9a80c7e6b324262edc1ff545411ea26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab529111f5d4432548e3913d2d910e77c">LLVMGetLastNamedMetadata</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain an iterator to the last NamedMDNode in a Module. <a href="#gab529111f5d4432548e3913d2d910e77c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaacd234d81c636cdd202dd64dad371e1c">LLVMGetNextNamedMetadata</a> (LLVMNamedMDNodeRef NamedMDNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance a NamedMDNode iterator to the next NamedMDNode. <a href="#gaacd234d81c636cdd202dd64dad371e1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga26be85891d4ed0c9b687b41d35b5c6e6">LLVMGetPreviousNamedMetadata</a> (LLVMNamedMDNodeRef NamedMDNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decrement a NamedMDNode iterator to the previous NamedMDNode. <a href="#ga26be85891d4ed0c9b687b41d35b5c6e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad7b8b519d3496fe42eddc0f4a5459b80">LLVMGetNamedMetadata</a> (LLVMModuleRef M, const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve a NamedMDNode with the given name, returning NULL if no such node exists. <a href="#gad7b8b519d3496fe42eddc0f4a5459b80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad9b3a5b994444921aa10d156f06c816e">LLVMGetOrInsertNamedMetadata</a> (LLVMModuleRef M, const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve a NamedMDNode with the given name, creating a new node if no such node exists. <a href="#gad9b3a5b994444921aa10d156f06c816e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga638cf10ec868576e2a3be5a17d0ae39b">LLVMGetNamedMetadataName</a> (LLVMNamedMDNodeRef NamedMD, size_t *NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the name of a NamedMDNode. <a href="#ga638cf10ec868576e2a3be5a17d0ae39b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9c5c38aced0f4851f11036f4fd358114">LLVMGetNamedMetadataNumOperands</a> (LLVMModuleRef M, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the number of operands for named metadata in a module. <a href="#ga9c5c38aced0f4851f11036f4fd358114">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae134c00653fcc70b850fb03af410be9c">LLVMGetNamedMetadataOperands</a> (LLVMModuleRef M, const char *Name, LLVMValueRef *Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the named metadata operands for a module. <a href="#gae134c00653fcc70b850fb03af410be9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf1ac13437ad369836a46ed7eca8a39bc">LLVMAddNamedMetadataOperand</a> (LLVMModuleRef M, const char *Name, LLVMValueRef Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an operand to named metadata. <a href="#gaf1ac13437ad369836a46ed7eca8a39bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga515bb8a9dede000b935e77958f35a4cf">LLVMGetDebugLocDirectory</a> (LLVMValueRef Val, unsigned *Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the directory of the debug location for this value, which must be an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">llvm::GlobalVariable</a>, or <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>. <a href="#ga515bb8a9dede000b935e77958f35a4cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga46f93df14e032eacb6cc772e0a9a03ed">LLVMGetDebugLocFilename</a> (LLVMValueRef Val, unsigned *Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the filename of the debug location for this value, which must be an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">llvm::GlobalVariable</a>, or <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>. <a href="#ga46f93df14e032eacb6cc772e0a9a03ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga886911b0d3c9399b014304c8fcb39ebb">LLVMGetDebugLocLine</a> (LLVMValueRef Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the line number of the debug location for this value, which must be an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">llvm::GlobalVariable</a>, or <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>. <a href="#ga886911b0d3c9399b014304c8fcb39ebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga866a526e575a528cd4debd9a83a500e3">LLVMGetDebugLocColumn</a> (LLVMValueRef Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the column number of the debug location for this value, which must be an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>. <a href="#ga866a526e575a528cd4debd9a83a500e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga12f35adec814eb1d3e9a2090b14f74f5">LLVMAddFunction</a> (LLVMModuleRef M, const char *Name, LLVMTypeRef FunctionTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a function to a module under a specified name. <a href="#ga12f35adec814eb1d3e9a2090b14f74f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac230af72a200c4fce34d0b53134569cd">LLVMGetNamedFunction</a> (LLVMModuleRef M, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a Function value from a Module by its name. <a href="#gac230af72a200c4fce34d0b53134569cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga27a089a0715eb516edcb266071fa4dc1">LLVMGetNamedFunctionWithLength</a> (LLVMModuleRef M, const char *Name, size_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain a Function value from a Module by its name. <a href="#ga27a089a0715eb516edcb266071fa4dc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga374a76b8284f82daa51c2ca3cb92ec26">LLVMGetFirstFunction</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain an iterator to the first Function in a Module. <a href="#ga374a76b8284f82daa51c2ca3cb92ec26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga78c26f83ae950f9b29cd108cf89557aa">LLVMGetLastFunction</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain an iterator to the last Function in a Module. <a href="#ga78c26f83ae950f9b29cd108cf89557aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaea000c66c75e06bdfa25df033c117408">LLVMGetNextFunction</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance a Function iterator to the next Function. <a href="#gaea000c66c75e06bdfa25df033c117408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gadea5d093b5ca9181504d155d24ef3810">LLVMGetPreviousFunction</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decrement a Function iterator to the previous Function. <a href="#gadea5d093b5ca9181504d155d24ef3810">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga92011f59112d84a8fae289ca1549bd9d">LLVMSetModuleInlineAsm</a> (LLVMModuleRef M, const char *Asm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMSetModuleInlineAsm2 instead. <a href="#ga92011f59112d84a8fae289ca1549bd9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Modules represent the top-level structure in an LLVM program.</p>


<p>An LLVM module is effectively a translation unit or a collection of translation units merged together.</p>


<div class="doxySectionDef">

## Functions

### LLVMAddFunction() {#ga12f35adec814eb1d3e9a2090b14f74f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMAddFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> FunctionTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a function to a module under a specified name.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create()</a></p></dd>
</dl>


<p>Declaration at line 1178 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2391 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMAddModuleFlag() {#ga91746975955737845b0f9a3b33c415f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMAddModuleFlag (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gaa61633f872a8b3cbcbab5f5a96d3ce0f">LLVMModuleFlagBehavior</a> Behavior, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, size_t KeyLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a module-level flag to the module-level flags metadata if it doesn't already exist.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::addModuleFlag()</p></dd>
</dl>


<p>Declaration at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a10b56b76b9e70846d3b1268ab3df0791">map_to_llvmModFlagBehavior</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMAddNamedMetadataOperand() {#gaf1ac13437ad369836a46ed7eca8a39bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMAddNamedMetadataOperand (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an operand to named metadata.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#a06bb57eb1830a137e7b8f8b25908ed24">llvm::Module::getNamedMetadata()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::MDNode::addOperand()</p></dd>
</dl>


<p>Declaration at line 1132 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1449 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a39c9d039f5cbab6c4155e907c466ab25">extractMDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMAppendModuleInlineAsm() {#ga357390c6ae457d796f6ae08cff56926d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMAppendModuleInlineAsm (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Asm, size_t Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append inline assembly to a module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::appendModuleInlineAsm()</p></dd>
</dl>


<p>Declaration at line 979 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMCloneModule() {#gabffdc747c14d77b3eb89500adf4f269b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMModuleRef LLVMCloneModule (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an exact copy of the specified module.</p>

<p>Declaration at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonemodule-cpp">CloneModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae13b67a51d9f8061d598e82272b79b80">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCopyModuleFlagsMetadata() {#ga8e9d8283d0b2d13fc9f119c00730c4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMModuleFlagEntry * LLVMCopyModuleFlagsMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, size_t * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the module flags as an array of flag-key-value triples.</p>


<p>The caller is responsible for freeing this array by calling <span class="doxyComputerOutput">LLVMDisposeModuleFlagsMetadata</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::getModuleFlagsMetadata()</p></dd>
</dl>


<p>Declaration at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a8505d29a37855d89492cb0d5c19bc125">map_from_llvmModFlagBehavior</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bb931812d78f470d4ca775ac8b88e61">llvm::safe_malloc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDisposeModule() {#ga4acadb366d5ff0405371508ca741a5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeModule (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy a module instance.</p>


<p>This must be called for every created module or memory will be leaked.</p>


<p>Declaration at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDisposeModuleFlagsMetadata() {#ga958e46099b5025db3567fdd036198f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeModuleFlagsMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga2582ca8c28f123476fb606097b475ed6">LLVMModuleFlagEntry</a> * Entries)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroys module flags metadata entries.</p>

<p>Declaration at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>

</div>
</div>

### LLVMDumpModule() {#ga31c87315ba3f595d6786c47a50d9f8e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDumpModule (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a representation of a module to stderr.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::dump()</p></dd>
</dl>


<p>Declaration at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetDataLayout() {#gac013e4aeb6a0674f18702e8f76f889c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetDataLayout (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="#ga79c76af8c81bc8e2de2da48f7135997a">LLVMGetDataLayoutStr</a>.</p>

</div>
</div>

### LLVMGetDataLayoutStr() {#ga79c76af8c81bc8e2de2da48f7135997a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetDataLayoutStr (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the data layout for a module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::getDataLayoutStr()</p></dd>
</dl>


<p>LLVMGetDataLayout is DEPRECATED, as the name is not only incorrect, but match the name of another method on the module. Prefer the use of LLVMGetDataLayoutStr, which is not ambiguous.</p>


<p>Declaration at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>


<p>Referenced by <a href="#gac013e4aeb6a0674f18702e8f76f889c7">LLVMGetDataLayout</a>.</p>

</div>
</div>

### LLVMGetDebugLocColumn() {#ga866a526e575a528cd4debd9a83a500e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGetDebugLocColumn (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the column number of the debug location for this value, which must be an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc()</a></p></dd>
</dl>


<p>Declaration at line 1171 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1529 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetDebugLocDirectory() {#ga515bb8a9dede000b935e77958f35a4cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetDebugLocDirectory (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val, unsigned * Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the directory of the debug location for this value, which must be an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">llvm::GlobalVariable</a>, or <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a7bd3c333fa06c8fae17d52a78db3fde2">llvm::GlobalVariable::getDebugInfo()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram()</a></p></dd>
</dl>


<p>Declaration at line 1143 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1459 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetDebugLocFilename() {#ga46f93df14e032eacb6cc772e0a9a03ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetDebugLocFilename (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val, unsigned * Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the filename of the debug location for this value, which must be an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">llvm::GlobalVariable</a>, or <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a7bd3c333fa06c8fae17d52a78db3fde2">llvm::GlobalVariable::getDebugInfo()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram()</a></p></dd>
</dl>


<p>Declaration at line 1153 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1483 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetDebugLocLine() {#ga886911b0d3c9399b014304c8fcb39ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGetDebugLocLine (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the line number of the debug location for this value, which must be an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">llvm::GlobalVariable</a>, or <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a7bd3c333fa06c8fae17d52a78db3fde2">llvm::GlobalVariable::getDebugInfo()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram()</a></p></dd>
</dl>


<p>Declaration at line 1163 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetFirstFunction() {#ga374a76b8284f82daa51c2ca3cb92ec26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetFirstFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain an iterator to the first Function in a Module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#a279174d137c1ef32aa5b627f5e06620f">llvm::Module::begin()</a></p></dd>
</dl>


<p>Declaration at line 1205 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2406 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetFirstNamedMetadata() {#gaf9a80c7e6b324262edc1ff545411ea26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMNamedMDNodeRef LLVMGetFirstNamedMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain an iterator to the first NamedMDNode in a Module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#a5d052342d8cb7a6952a4c123b5385f90">llvm::Module::named_metadata_begin()</a></p></dd>
</dl>


<p>Declaration at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1364 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetInlineAsm() {#ga4efd515d9e18a2bc89017e53a44142c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetInlineAsm (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab81b4df33167d47174f9b86a75e3be88">LLVMTypeRef</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * AsmString, size_t AsmStringSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Constraints, size_t ConstraintsSize, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> HasSideEffects, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> IsAlignStack, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gafa932ff1a3dabfe8c6109edd2b25baaf">LLVMInlineAsmDialect</a> Dialect, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> CanThrow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the specified uniqued inline asm string.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>InlineAsm::get()</p></dd>
</dl>


<p>Declaration at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8ae46075a65afe271f3d7f91e1243aacca">llvm::InlineAsm::AD_ATT</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8ac2322cfab42cb6c46aa198861244231e">llvm::InlineAsm::AD_Intel</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a44dec91bb943f56f8bba3e9171a76947">llvm::InlineAsm::get</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ggafa932ff1a3dabfe8c6109edd2b25baafa3ce423c6d3f009cd87aa4f1072e5b3a3">LLVMInlineAsmDialectATT</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ggafa932ff1a3dabfe8c6109edd2b25baafad050e4ce2cfb6e28b5062a52e6b2063a">LLVMInlineAsmDialectIntel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetInlineAsmAsmString() {#ga7cc10368c3bcc93aef4159d9b788aaad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetInlineAsmAsmString (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> InlineAsmVal, size_t * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the template string used for an inline assembly snippet.</p>

<p>Declaration at line 996 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetInlineAsmCanUnwind() {#gab9e9f884e7bfa21ae7f86b0d551ad849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMGetInlineAsmCanUnwind (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> InlineAsmVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get if the inline asm snippet may unwind the stack.</p>

<p>Declaration at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetInlineAsmConstraintString() {#ga6aab40de7b0d5bc2b765151ed050df76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetInlineAsmConstraintString (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> InlineAsmVal, size_t * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the raw constraint string for an inline assembly snippet.</p>

<p>Declaration at line 1002 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetInlineAsmDialect() {#ga95e52974c4e5460f3341688464c3ed73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMInlineAsmDialect LLVMGetInlineAsmDialect (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> InlineAsmVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the dialect used by the inline asm snippet.</p>

<p>Declaration at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8ae46075a65afe271f3d7f91e1243aacca">llvm::InlineAsm::AD_ATT</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8ac2322cfab42cb6c46aa198861244231e">llvm::InlineAsm::AD_Intel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ggafa932ff1a3dabfe8c6109edd2b25baafa3ce423c6d3f009cd87aa4f1072e5b3a3">LLVMInlineAsmDialectATT</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#ggafa932ff1a3dabfe8c6109edd2b25baafad050e4ce2cfb6e28b5062a52e6b2063a">LLVMInlineAsmDialectIntel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetInlineAsmFunctionType() {#gaee5f092641dc2a86cd315ed718b7a345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTypeRef LLVMGetInlineAsmFunctionType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> InlineAsmVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the function type of the inline assembly snippet.</p>


<p>The same type that was passed into LLVMGetInlineAsm originally</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#ga4efd515d9e18a2bc89017e53a44142c2">LLVMGetInlineAsm</a></p></dd>
</dl>


<p>Declaration at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetInlineAsmHasSideEffects() {#ga92d29d949187ef2e53abc4999ba5d0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMGetInlineAsmHasSideEffects (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> InlineAsmVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get if the inline asm snippet has side effects.</p>

<p>Declaration at line 1024 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetInlineAsmNeedsAlignedStack() {#ga8bd4c578ee6391ce16b3936d04af8cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMGetInlineAsmNeedsAlignedStack (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> InlineAsmVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get if the inline asm snippet needs an aligned stack.</p>

<p>Declaration at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetLastFunction() {#ga78c26f83ae950f9b29cd108cf89557aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetLastFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain an iterator to the last Function in a Module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#aa608a2d900dd6c15c18f4236b6548496">llvm::Module::end()</a></p></dd>
</dl>


<p>Declaration at line 1212 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2414 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetLastNamedMetadata() {#gab529111f5d4432548e3913d2d910e77c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMNamedMDNodeRef LLVMGetLastNamedMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain an iterator to the last NamedMDNode in a Module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#ab52eefaf4892829072b70e0e2e3d88bf">llvm::Module::named_metadata_end()</a></p></dd>
</dl>


<p>Declaration at line 1060 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1372 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetModuleContext() {#ga66fd1dc1c47edded31b7e802066e2a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContextRef LLVMGetModuleContext (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the context to which this module is associated.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::getContext()</p></dd>
</dl>


<p>Declaration at line 1043 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetModuleFlag() {#gabac5acb60629380b378eb8d9033de04c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMGetModuleFlag (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, size_t KeyLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a module-level flag to the module-level flags metadata if it doesn't already exist.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::getModuleFlag()</p></dd>
</dl>


<p>Declaration at line 923 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetModuleIdentifier() {#ga053573a690cdb1e6c84451b980fd4155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetModuleIdentifier (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, size_t * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the identifier of a module.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>Module to obtain identifier of</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>Out parameter which holds the length of the returned string.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The identifier of M.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::getModuleIdentifier()</p></dd>
</dl>


<p>Declaration at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetModuleInlineAsm() {#ga51c7c33e8376848eeb431e89b4a17f0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetModuleInlineAsm (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, size_t * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get inline assembly for a module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::getModuleInlineAsm()</p></dd>
</dl>


<p>Declaration at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetNamedFunction() {#gac230af72a200c4fce34d0b53134569cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetNamedFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a Function value from a Module by its name.</p>


<p>The returned value corresponds to a <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> value.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#a209a615a3a32241323420cca24b5520a">llvm::Module::getFunction()</a></p></dd>
</dl>


<p>Declaration at line 1188 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2397 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetNamedFunctionWithLength() {#ga27a089a0715eb516edcb266071fa4dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetNamedFunctionWithLength (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain a Function value from a Module by its name.</p>


<p>The returned value corresponds to a <a href="/web-llvm/docs/api/classes/llvm/function">llvm::Function</a> value.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#a209a615a3a32241323420cca24b5520a">llvm::Module::getFunction()</a></p></dd>
</dl>


<p>Declaration at line 1197 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2401 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetNamedMetadata() {#gad7b8b519d3496fe42eddc0f4a5459b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMNamedMDNodeRef LLVMGetNamedMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve a NamedMDNode with the given name, returning NULL if no such node exists.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#a06bb57eb1830a137e7b8f8b25908ed24">llvm::Module::getNamedMetadata()</a></p></dd>
</dl>


<p>Declaration at line 1084 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1396 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetNamedMetadataName() {#ga638cf10ec868576e2a3be5a17d0ae39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetNamedMetadataName (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a> NamedMD, size_t * NameLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the name of a NamedMDNode.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#a5e90645e97cbfe08194f0db4d0bdec88">llvm::NamedMDNode::getName()</a></p></dd>
</dl>


<p>Declaration at line 1102 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1406 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#a5e90645e97cbfe08194f0db4d0bdec88">llvm::NamedMDNode::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetNamedMetadataNumOperands() {#ga9c5c38aced0f4851f11036f4fd358114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGetNamedMetadataNumOperands (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the number of operands for named metadata in a module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#a06bb57eb1830a137e7b8f8b25908ed24">llvm::Module::getNamedMetadata()</a></p></dd>
</dl>


<p>Declaration at line 1110 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1432 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetNamedMetadataOperands() {#gae134c00653fcc70b850fb03af410be9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMGetNamedMetadataOperands (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> * Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the named metadata operands for a module.</p>


<p>The passed <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> pointer should refer to an array of <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> at least LLVMGetNamedMetadataNumOperands long. This array will be populated with the <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> instances. Each instance corresponds to a <a href="/web-llvm/docs/api/classes/llvm/mdnode">llvm::MDNode</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#a06bb57eb1830a137e7b8f8b25908ed24">llvm::Module::getNamedMetadata()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand()</a></p></dd>
</dl>


<p>Declaration at line 1123 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1439 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetNextFunction() {#gaea000c66c75e06bdfa25df033c117408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetNextFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance a Function iterator to the next Function.</p>


<p>Returns NULL if the iterator was already at the end and there are no more functions.</p>


<p>Declaration at line 1220 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2422 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetNextNamedMetadata() {#gaacd234d81c636cdd202dd64dad371e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMNamedMDNodeRef LLVMGetNextNamedMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a> NamedMDNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance a NamedMDNode iterator to the next NamedMDNode.</p>


<p>Returns NULL if the iterator was already at the end and there are no more named metadata nodes.</p>


<p>Declaration at line 1068 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1380 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae8578a0e0ed99d2daba95da926662a8d">llvm::NamedMDNode::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#ab52eefaf4892829072b70e0e2e3d88bf">llvm::Module::named_metadata_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetOrInsertNamedMetadata() {#gad9b3a5b994444921aa10d156f06c816e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMNamedMDNodeRef LLVMGetOrInsertNamedMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve a NamedMDNode with the given name, creating a new node if no such node exists.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/module/#ab33e5587b25f9c80f6ea5000124d1a2b">llvm::Module::getOrInsertNamedMetadata()</a></p></dd>
</dl>


<p>Declaration at line 1093 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1401 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetPreviousFunction() {#gadea5d093b5ca9181504d155d24ef3810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetPreviousFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decrement a Function iterator to the previous Function.</p>


<p>Returns NULL if the iterator was already at the beginning and there are no previous functions.</p>


<p>Declaration at line 1228 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2430 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetPreviousNamedMetadata() {#ga26be85891d4ed0c9b687b41d35b5c6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMNamedMDNodeRef LLVMGetPreviousNamedMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga348dc6ce48243a524ee3937ef2d8ca29">LLVMNamedMDNodeRef</a> NamedMDNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decrement a NamedMDNode iterator to the previous NamedMDNode.</p>


<p>Returns NULL if the iterator was already at the beginning and there are no previous named metadata nodes.</p>


<p>Declaration at line 1076 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 1388 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#ae8578a0e0ed99d2daba95da926662a8d">llvm::NamedMDNode::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a5d052342d8cb7a6952a4c123b5385f90">llvm::Module::named_metadata_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetSourceFileName() {#ga5ef5081177ddb952a4f0c1b5465b41f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetSourceFileName (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, size_t * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the module's original source file name.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>Module to obtain the name of</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>Out parameter which holds the length of the returned string</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The original source file name of M</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::getSourceFileName()</p></dd>
</dl>


<p>Declaration at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetTarget() {#gaab7f6420f76734cbb0a22c5ba435a464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetTarget (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the target triple for a module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::getTargetTriple()</p></dd>
</dl>


<p>Declaration at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetTypeByName() {#ga29066e749e093fba6fedb5efa0962177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTypeRef LLVMGetTypeByName (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMGetTypeByName2 instead.</p>

<p>Declaration at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 849 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/structtype/#a75a89f1513d9f9bdcf0366a436ca43b5">llvm::StructType::getTypeByName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMIsNewDbgInfoFormat() {#ga1adb5d14471960646da56e130c6a0f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMIsNewDbgInfoFormat (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Soon to be deprecated.</p>


<p>See <a href="https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes">https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes</a></p>


<p>Returns true if the module is in the new debug info mode which uses non-instruction debug records instead of debug intrinsics for variable location tracking.</p>


<p>Declaration at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMModuleCreateWithName() {#ga8cf6711b9359fb55d081bfc5e664370c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMModuleRef LLVMModuleCreateWithName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ModuleID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new, empty module in the global context.</p>


<p>This is equivalent to calling LLVMModuleCreateWithNameInContext with <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga0055cde9a9b2497b332d639d8844a810">LLVMGetGlobalContext()</a> as the context parameter.</p>


<p>Every invocation should be paired with <a href="#ga4acadb366d5ff0405371508ca741a5bf">LLVMDisposeModule()</a> or memory will be leaked.</p>


<p>Declaration at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#ae804664ac6f43af40da2e4dd0ed3d6d0">getGlobalContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMModuleCreateWithNameInContext() {#ga6bf4a0a387cf7fe04cbe0438cdb36a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMModuleRef LLVMModuleCreateWithNameInContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ModuleID, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new, empty module in a specific context.</p>


<p>Every invocation should be paired with <a href="#ga4acadb366d5ff0405371508ca741a5bf">LLVMDisposeModule()</a> or memory will be leaked.</p>


<p>Declaration at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMModuleFlagEntriesGetFlagBehavior() {#ga7ffb147f3127ad15810853e2c984efda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMModuleFlagBehavior LLVMModuleFlagEntriesGetFlagBehavior (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga2582ca8c28f123476fb606097b475ed6">LLVMModuleFlagEntry</a> * Entries, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the flag behavior for a module flag entry at a specific index.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::ModuleFlagEntry::Behavior</p></dd>
</dl>


<p>Declaration at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvmopaquemoduleflagentry/#a0bf60fa9ba17bb4342038d6292a39c64">LLVMOpaqueModuleFlagEntry::Behavior</a>.</p>

</div>
</div>

### LLVMModuleFlagEntriesGetKey() {#ga78a873e9b162867e522b5f1b5e6f67a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMModuleFlagEntriesGetKey (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga2582ca8c28f123476fb606097b475ed6">LLVMModuleFlagEntry</a> * Entries, unsigned Index, size_t * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the key for a module flag entry at a specific index.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::ModuleFlagEntry::Key</p></dd>
</dl>


<p>Declaration at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvmopaquemoduleflagentry/#a7f71ecbb1671eeb54f0bf2f9190cb454">LLVMOpaqueModuleFlagEntry::Key</a> and <a href="/web-llvm/docs/api/structs/llvmopaquemoduleflagentry/#ac7252bc54c53d0bac8075bc7820ae5ef">LLVMOpaqueModuleFlagEntry::KeyLen</a>.</p>

</div>
</div>

### LLVMModuleFlagEntriesGetMetadata() {#ga6fb875163266d4dba53b46b1c6e0c263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMModuleFlagEntriesGetMetadata (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga2582ca8c28f123476fb606097b475ed6">LLVMModuleFlagEntry</a> * Entries, unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the metadata for a module flag entry at a specific index.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::ModuleFlagEntry::Val</p></dd>
</dl>


<p>Declaration at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvmopaquemoduleflagentry/#a9254736f6624197054940df2ead5fa71">LLVMOpaqueModuleFlagEntry::Metadata</a>.</p>

</div>
</div>

### LLVMPrintModuleToFile() {#ga4879fe0f5852edd39ea4a1e14d413bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMPrintModuleToFile (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Filename, char ** ErrorMessage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print a representation of a module to a file.</p>


<p>The ErrorMessage needs to be disposed with LLVMDisposeMessage. Returns 0 on success, 1 otherwise.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::print()</p></dd>
</dl>


<p>Declaration at line 949 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a293545f9b5864a8e1b33e57becbc5b3a">llvm::raw_fd_ostream::close</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a215c95ed69aa5b5756dd9c0f1b1de410">llvm::raw_fd_ostream::error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a0d5a564fb5459ab9ce6e56401786542b">llvm::raw_fd_ostream::has_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMPrintModuleToString() {#gae0d61246e5b4f768588aef14e124a96b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * LLVMPrintModuleToString (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a string representation of the module.</p>


<p>Use LLVMDisposeMessage to free the string.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::print()</p></dd>
</dl>


<p>Declaration at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetDataLayout() {#ga125b4ef3982a95cf99cf052866c3c4f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetDataLayout (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * DataLayoutStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the data layout for a module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::setDataLayout()</p></dd>
</dl>


<p>Declaration at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetIsNewDbgInfoFormat() {#gacf510322862cd8d09fb5c614ebe09ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetIsNewDbgInfoFormat (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> UseNewFormat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Soon to be deprecated.</p>


<p>See <a href="https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes">https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes</a></p>


<p>Convert module into desired debug info format.</p>


<p>Declaration at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetModuleIdentifier() {#gaefcadd23e3fa1bc03f5af51b4689a2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetModuleIdentifier (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ident, size_t Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the identifier of a module to a string Ident with length Len.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>The module to set identifier</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ident</td>
<td class="doxyParamItemDescription"><p>The string to set M's identifier to</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>Length of Ident</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::setModuleIdentifier()</p></dd>
</dl>


<p>Declaration at line 822 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetModuleInlineAsm() {#ga92011f59112d84a8fae289ca1549bd9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetModuleInlineAsm (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMSetModuleInlineAsm2 instead.</p>

<p>Declaration at line 1231 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetModuleInlineAsm2() {#gab2633096e900a099e4ba1bcb0e28e620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetModuleInlineAsm2 (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Asm, size_t Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set inline assembly for a module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::setModuleInlineAsm()</p></dd>
</dl>


<p>Declaration at line 972 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetSourceFileName() {#ga3144997c9342d7df8af0e7550f39a506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetSourceFileName (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the original source file name of a module to a string Name with length Len.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>The module to set the source file name of</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The string to set M's source file name to</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>Length of Name</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::setSourceFileName()</p></dd>
</dl>


<p>Declaration at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMSetTarget() {#ga792209d857f53a72ac34fec1c599664a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetTarget (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Triple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the target triple for a module.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>Module::setTargetTriple()</p></dd>
</dl>


<p>Declaration at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
