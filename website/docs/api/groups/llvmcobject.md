---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcobject
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Object file reading and writing Reference



## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueSectionIterator * <a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueSymbolIterator * <a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueRelocationIterator * <a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueObjectFile * <a href="#gad613c47de6adf4cf4f2cabf0eb19d879">LLVMObjectFileRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> instead. <a href="#gad613c47de6adf4cf4f2cabf0eb19d879">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMBinaryType { <a href="#gab0e40434b3ad6ce456b7542c6e91c730">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabe1e0252c6f4bc1b0b1b8b06f9df3546">LLVMCreateBinary</a> (LLVMMemoryBufferRef MemBuf, LLVMContextRef Context, char **ErrorMessage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a binary file from the given memory buffer. <a href="#gabe1e0252c6f4bc1b0b1b8b06f9df3546">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab7fb7f71c828fd1db5c8d99064208738">LLVMDisposeBinary</a> (LLVMBinaryRef BR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a binary file. <a href="#gab7fb7f71c828fd1db5c8d99064208738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9867eaa7b17ba17405cdf2539bedb108">LLVMMemoryBufferRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaeff7af5e130db7b11a27ed233f57d5c6">LLVMBinaryCopyMemoryBuffer</a> (LLVMBinaryRef BR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves a copy of the memory buffer associated with this object file. <a href="#gaeff7af5e130db7b11a27ed233f57d5c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gab0e40434b3ad6ce456b7542c6e91c730">LLVMBinaryType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9325ccf978c315587e6dfe55e4c3758a">LLVMBinaryGetType</a> (LLVMBinaryRef BR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the specific type of a binary. <a href="#ga9325ccf978c315587e6dfe55e4c3758a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab0bd1b18bfb07fa6d075f69f6c6dd62f">LLVMMachOUniversalBinaryCopyObjectForArch</a> (LLVMBinaryRef BR, const char *Arch, size_t ArchLen, char **ErrorMessage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabb7cdf8752b1939d369936207f9b25c1">LLVMObjectFileCopySectionIterator</a> (LLVMBinaryRef BR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve a copy of the section iterator for this object file. <a href="#gabb7cdf8752b1939d369936207f9b25c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9e0dcd6b052fe254c667071981e24f9b">LLVMObjectFileIsSectionIteratorAtEnd</a> (LLVMBinaryRef BR, LLVMSectionIteratorRef SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether the given section iterator is at the end. <a href="#ga9e0dcd6b052fe254c667071981e24f9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1002f207402c729401bc0b6de7f842f1">LLVMObjectFileCopySymbolIterator</a> (LLVMBinaryRef BR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve a copy of the symbol iterator for this object file. <a href="#ga1002f207402c729401bc0b6de7f842f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacdfb98daac681a078c04d6e52e2b4c4d">LLVMObjectFileIsSymbolIteratorAtEnd</a> (LLVMBinaryRef BR, LLVMSymbolIteratorRef SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether the given symbol iterator is at the end. <a href="#gacdfb98daac681a078c04d6e52e2b4c4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3b49a38b2c1aeca5cc0a77351f0eb9c1">LLVMDisposeSectionIterator</a> (LLVMSectionIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf73579ac560edf40c64de997c53df39b">LLVMMoveToNextSection</a> (LLVMSectionIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab7faf1f46a7fb022e21e792e0250709d">LLVMMoveToContainingSection</a> (LLVMSectionIteratorRef Sect, LLVMSymbolIteratorRef Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6cf9239b08abd808022e29295a3b350c">LLVMDisposeSymbolIterator</a> (LLVMSymbolIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9f94927ab91849027797983322db6f6a">LLVMMoveToNextSymbol</a> (LLVMSymbolIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4a57d024c433cf88a0da658ea1627093">LLVMGetSectionName</a> (LLVMSectionIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga679b35911250463347612612da632ce4">LLVMGetSectionSize</a> (LLVMSectionIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga42594e75dfeee0ddefefe22a09104045">LLVMGetSectionContents</a> (LLVMSectionIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga908c337a23ed06ca706cdec62f16b240">LLVMGetSectionAddress</a> (LLVMSectionIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf85321df24e95812d9f34a9e3d8462eb">LLVMGetSectionContainsSymbol</a> (LLVMSectionIteratorRef SI, LLVMSymbolIteratorRef Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa3b04667cb205951b32d722fe34c3788">LLVMGetRelocations</a> (LLVMSectionIteratorRef Section)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabcaef819e8ce56e50ede373ef1853ce7">LLVMDisposeRelocationIterator</a> (LLVMRelocationIteratorRef RI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga173e89e17518a7d5386413396f1ecda7">LLVMIsRelocationIteratorAtEnd</a> (LLVMSectionIteratorRef Section, LLVMRelocationIteratorRef RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3a1b85a24686caf1e4d5d4046b71d269">LLVMMoveToNextRelocation</a> (LLVMRelocationIteratorRef RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gace82127e9d25bb0a018ea2d621fda00a">LLVMGetSymbolName</a> (LLVMSymbolIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf98e23b38443db6fa6876aababd108a5">LLVMGetSymbolAddress</a> (LLVMSymbolIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga59539953bd3af17cb3aa953f5a618ec5">LLVMGetSymbolSize</a> (LLVMSymbolIteratorRef SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4d8fb55f7cd53955a6dd1521b94c490a">LLVMGetRelocationOffset</a> (LLVMRelocationIteratorRef RI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabe5bc64da12be2f20a9b4a5e203b8287">LLVMGetRelocationSymbol</a> (LLVMRelocationIteratorRef RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga05562625bf2087695b10afc50de236d3">LLVMGetRelocationType</a> (LLVMRelocationIteratorRef RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga59e1c8aada118b78e806cf237418233e">LLVMGetRelocationTypeName</a> (LLVMRelocationIteratorRef RI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf9576a73bac3cb684b64ba61ca660370">LLVMGetRelocationValueString</a> (LLVMRelocationIteratorRef RI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gad613c47de6adf4cf4f2cabf0eb19d879">LLVMObjectFileRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0fd9f7bc65117c049c14c047fb7907dc">LLVMCreateObjectFile</a> (LLVMMemoryBufferRef MemBuf)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMCreateBinary instead. <a href="#ga0fd9f7bc65117c049c14c047fb7907dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac245dfda741cb142ee2a4ef8e32a4e00">LLVMDisposeObjectFile</a> (LLVMObjectFileRef ObjectFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMDisposeBinary instead. <a href="#gac245dfda741cb142ee2a4ef8e32a4e00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7f10d0096ae160af533590c654514821">LLVMGetSections</a> (LLVMObjectFileRef ObjectFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMObjectFileCopySectionIterator instead. <a href="#ga7f10d0096ae160af533590c654514821">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5de931b766e11065f638d77513ed599b">LLVMIsSectionIteratorAtEnd</a> (LLVMObjectFileRef ObjectFile, LLVMSectionIteratorRef SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMObjectFileIsSectionIteratorAtEnd instead. <a href="#ga5de931b766e11065f638d77513ed599b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6f125ef242d41de192d8145d9869cd53">LLVMGetSymbols</a> (LLVMObjectFileRef ObjectFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMObjectFileCopySymbolIterator instead. <a href="#ga6f125ef242d41de192d8145d9869cd53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga921deacfe5162787c8b3c40c837598c1">LLVMIsSymbolIteratorAtEnd</a> (LLVMObjectFileRef ObjectFile, LLVMSymbolIteratorRef SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated: Use LLVMObjectFileIsSymbolIteratorAtEnd instead. <a href="#ga921deacfe5162787c8b3c40c837598c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### LLVMObjectFileRef {#gad613c47de6adf4cf4f2cabf0eb19d879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueObjectFile* LLVMObjectFileRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> instead.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>.</p>

</div>
</div>

### LLVMRelocationIteratorRef {#gacfc595713ed017d3c5aaab450536fd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueRelocationIterator* LLVMRelocationIteratorRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>.</p>

</div>
</div>

### LLVMSectionIteratorRef {#gaae688e21a05eafae72ca3a48af2e7b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueSectionIterator* LLVMSectionIteratorRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>.</p>

</div>
</div>

### LLVMSymbolIteratorRef {#ga387344c8d1fe17d3070d0299a21d4d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueSymbolIterator* LLVMSymbolIteratorRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LLVMBinaryType {#gab0e40434b3ad6ce456b7542c6e91c730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LLVMBinaryType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeArchive<a id="ggab0e40434b3ad6ce456b7542c6e91c730a4a75f65ca5b992a45acaf3525e70c0f9"></a></td>
<td class="doxyEnumItemDescription">Archive file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeMachOUniversalBinary<a id="ggab0e40434b3ad6ce456b7542c6e91c730a948b21a7e40fd054a39c0e2fd2fd93d3"></a></td>
<td class="doxyEnumItemDescription">Mach-O Universal Binary file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeCOFFImportFile<a id="ggab0e40434b3ad6ce456b7542c6e91c730aa3765b2c17f4ebc482caa8ad0c2d61e4"></a></td>
<td class="doxyEnumItemDescription">COFF Import file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeIR<a id="ggab0e40434b3ad6ce456b7542c6e91c730a02263c2cd23397bcb8287389fba88fac"></a></td>
<td class="doxyEnumItemDescription">LLVM IR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeWinRes<a id="ggab0e40434b3ad6ce456b7542c6e91c730a7bf9ebb81577e6e8ef21ffb9a25243ee"></a></td>
<td class="doxyEnumItemDescription">Windows resource (.res) file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeCOFF<a id="ggab0e40434b3ad6ce456b7542c6e91c730aa1a268afb88e122a781699d083df61a2"></a></td>
<td class="doxyEnumItemDescription">COFF Object file</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeELF32L<a id="ggab0e40434b3ad6ce456b7542c6e91c730ad323a6ba2ae067c931baf499ea71c1ac"></a></td>
<td class="doxyEnumItemDescription">ELF 32-bit, little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeELF32B<a id="ggab0e40434b3ad6ce456b7542c6e91c730ab0731f5bedf57b41939d969f648471c6"></a></td>
<td class="doxyEnumItemDescription">ELF 32-bit, big endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeELF64L<a id="ggab0e40434b3ad6ce456b7542c6e91c730a68d39a58f66234a31a87b4159cb760b0"></a></td>
<td class="doxyEnumItemDescription">ELF 64-bit, little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeELF64B<a id="ggab0e40434b3ad6ce456b7542c6e91c730a1988f29aa0deb2ce176301a04fe55694"></a></td>
<td class="doxyEnumItemDescription">ELF 64-bit, big endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeMachO32L<a id="ggab0e40434b3ad6ce456b7542c6e91c730ad92fe8cc7a905f641da21304c4064f24"></a></td>
<td class="doxyEnumItemDescription">MachO 32-bit, little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeMachO32B<a id="ggab0e40434b3ad6ce456b7542c6e91c730a56730f35d180ddeab7b9458a6b38af08"></a></td>
<td class="doxyEnumItemDescription">MachO 32-bit, big endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeMachO64L<a id="ggab0e40434b3ad6ce456b7542c6e91c730ae63044b2d81c168817c5cd32c7ef886f"></a></td>
<td class="doxyEnumItemDescription">MachO 64-bit, little endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeMachO64B<a id="ggab0e40434b3ad6ce456b7542c6e91c730a9f12b46d73c472f866820e85c6a7e9dc"></a></td>
<td class="doxyEnumItemDescription">MachO 64-bit, big endian</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeWasm<a id="ggab0e40434b3ad6ce456b7542c6e91c730a604cf1514d36b3cd0177bc7b32adce54"></a></td>
<td class="doxyEnumItemDescription">Web Assembly</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMBinaryTypeOffload<a id="ggab0e40434b3ad6ce456b7542c6e91c730ae6e9e28b8cae3c63836a5847807af1d9"></a></td>
<td class="doxyEnumItemDescription">Offloading fatbinary</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMBinaryCopyMemoryBuffer() {#gaeff7af5e130db7b11a27ed233f57d5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMemoryBufferRef LLVMBinaryCopyMemoryBuffer (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> BR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieves a copy of the memory buffer associated with this object file.</p>


<p>The returned buffer is merely a shallow copy and does not own the actual backing buffer of the binary. Nevertheless, it is the responsibility of the caller to free it with <span class="doxyComputerOutput">LLVMDisposeMemoryBuffer</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::object::getMemoryBufferRef</p></dd>
</dl>


<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMBinaryGetType() {#ga9325ccf978c315587e6dfe55e4c3758a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBinaryType LLVMBinaryGetType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> BR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve the specific type of a binary.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/object/binary/#a60b6c7df2a6f0927102c0e2a23dd0b2e">llvm::object::Binary::getType</a></p></dd>
</dl>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a4a75f65ca5b992a45acaf3525e70c0f9">LLVMBinaryTypeArchive</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730aa1a268afb88e122a781699d083df61a2">LLVMBinaryTypeCOFF</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730aa3765b2c17f4ebc482caa8ad0c2d61e4">LLVMBinaryTypeCOFFImportFile</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730ab0731f5bedf57b41939d969f648471c6">LLVMBinaryTypeELF32B</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730ad323a6ba2ae067c931baf499ea71c1ac">LLVMBinaryTypeELF32L</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a1988f29aa0deb2ce176301a04fe55694">LLVMBinaryTypeELF64B</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a68d39a58f66234a31a87b4159cb760b0">LLVMBinaryTypeELF64L</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a02263c2cd23397bcb8287389fba88fac">LLVMBinaryTypeIR</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a56730f35d180ddeab7b9458a6b38af08">LLVMBinaryTypeMachO32B</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730ad92fe8cc7a905f641da21304c4064f24">LLVMBinaryTypeMachO32L</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a9f12b46d73c472f866820e85c6a7e9dc">LLVMBinaryTypeMachO64B</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730ae63044b2d81c168817c5cd32c7ef886f">LLVMBinaryTypeMachO64L</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a948b21a7e40fd054a39c0e2fd2fd93d3">LLVMBinaryTypeMachOUniversalBinary</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730ae6e9e28b8cae3c63836a5847807af1d9">LLVMBinaryTypeOffload</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a604cf1514d36b3cd0177bc7b32adce54">LLVMBinaryTypeWasm</a>, <a href="#ggab0e40434b3ad6ce456b7542c6e91c730a7bf9ebb81577e6e8ef21ffb9a25243ee">LLVMBinaryTypeWinRes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMCreateBinary() {#gabe1e0252c6f4bc1b0b1b8b06f9df3546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBinaryRef LLVMCreateBinary (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9867eaa7b17ba17405cdf2539bedb108">LLVMMemoryBufferRef</a> MemBuf, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> Context, char ** ErrorMessage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a binary file from the given memory buffer.</p>


<p>The exact type of the binary file will be inferred automatically, and the appropriate implementation selected. The context may be NULL except if the resulting file is an LLVM IR file.</p>


<p>The memory buffer is not consumed by this function. It is the responsibilty of the caller to free it with <span class="doxyComputerOutput">LLVMDisposeMemoryBuffer</span>.</p>


<p>If NULL is returned, the <span class="doxyComputerOutput">ErrorMessage</span> parameter is populated with the error's description. It is then the caller's responsibility to free this message by calling <span class="doxyComputerOutput">LLVMDisposeMessage</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a></p></dd>
</dl>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateObjectFile() {#ga0fd9f7bc65117c049c14c047fb7907dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMObjectFileRef LLVMCreateObjectFile (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9867eaa7b17ba17405cdf2539bedb108">LLVMMemoryBufferRef</a> MemBuf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMCreateBinary instead.</p>

<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDisposeBinary() {#gab7fb7f71c828fd1db5c8d99064208738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeBinary (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> BR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispose of a binary file.</p>


<p>The binary file does not own its backing buffer. It is the responsibilty of the caller to free it with <span class="doxyComputerOutput">LLVMDisposeMemoryBuffer</span>.</p>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDisposeObjectFile() {#gac245dfda741cb142ee2a4ef8e32a4e00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeObjectFile (<a href="#gad613c47de6adf4cf4f2cabf0eb19d879">LLVMObjectFileRef</a> ObjectFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMDisposeBinary instead.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDisposeRelocationIterator() {#gabcaef819e8ce56e50ede373ef1853ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeRelocationIterator (<a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a> RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDisposeSectionIterator() {#ga3b49a38b2c1aeca5cc0a77351f0eb9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeSectionIterator (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDisposeSymbolIterator() {#ga6cf9239b08abd808022e29295a3b350c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeSymbolIterator (<a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetRelocationOffset() {#ga4d8fb55f7cd53955a6dd1521b94c490a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMGetRelocationOffset (<a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a> RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetRelocations() {#gaa3b04667cb205951b32d722fe34c3788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRelocationIteratorRef LLVMGetRelocations (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetRelocationSymbol() {#gabe5bc64da12be2f20a9b4a5e203b8287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMSymbolIteratorRef LLVMGetRelocationSymbol (<a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a> RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetRelocationType() {#ga05562625bf2087695b10afc50de236d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMGetRelocationType (<a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a> RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetRelocationTypeName() {#ga59e1c8aada118b78e806cf237418233e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetRelocationTypeName (<a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a> RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac1b702e99f1978f2dd36cac2f7400f">llvm::getTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bb931812d78f470d4ca775ac8b88e61">llvm::safe_malloc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetRelocationValueString() {#gaf9576a73bac3cb684b64ba61ca660370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetRelocationValueString (<a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a> RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>

</div>
</div>

### LLVMGetSectionAddress() {#ga908c337a23ed06ca706cdec62f16b240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMGetSectionAddress (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetSectionContainsSymbol() {#gaf85321df24e95812d9f34a9e3d8462eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMGetSectionContainsSymbol (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI, <a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetSectionContents() {#ga42594e75dfeee0ddefefe22a09104045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetSectionContents (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetSectionName() {#ga4a57d024c433cf88a0da658ea1627093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetSectionName (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetSections() {#ga7f10d0096ae160af533590c654514821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMSectionIteratorRef LLVMGetSections (<a href="#gad613c47de6adf4cf4f2cabf0eb19d879">LLVMObjectFileRef</a> ObjectFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMObjectFileCopySectionIterator instead.</p>

<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetSectionSize() {#ga679b35911250463347612612da632ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMGetSectionSize (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetSymbolAddress() {#gaf98e23b38443db6fa6876aababd108a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMGetSymbolAddress (<a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a4a30a3fae601106b8b33c0871aa3069d">getAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetSymbolName() {#gace82127e9d25bb0a018ea2d621fda00a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetSymbolName (<a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetSymbols() {#ga6f125ef242d41de192d8145d9869cd53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMSymbolIteratorRef LLVMGetSymbols (<a href="#gad613c47de6adf4cf4f2cabf0eb19d879">LLVMObjectFileRef</a> ObjectFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMObjectFileCopySymbolIterator instead.</p>

<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetSymbolSize() {#ga59539953bd3af17cb3aa953f5a618ec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMGetSymbolSize (<a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMIsRelocationIteratorAtEnd() {#ga173e89e17518a7d5386413396f1ecda7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMIsRelocationIteratorAtEnd (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> Section, <a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a> RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMIsSectionIteratorAtEnd() {#ga5de931b766e11065f638d77513ed599b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMIsSectionIteratorAtEnd (<a href="#gad613c47de6adf4cf4f2cabf0eb19d879">LLVMObjectFileRef</a> ObjectFile, <a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMObjectFileIsSectionIteratorAtEnd instead.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMIsSymbolIteratorAtEnd() {#ga921deacfe5162787c8b3c40c837598c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMIsSymbolIteratorAtEnd (<a href="#gad613c47de6adf4cf4f2cabf0eb19d879">LLVMObjectFileRef</a> ObjectFile, <a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated: Use LLVMObjectFileIsSymbolIteratorAtEnd instead.</p>

<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMMachOUniversalBinaryCopyObjectForArch() {#gab0bd1b18bfb07fa6d075f69f6c6dd62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBinaryRef LLVMMachOUniversalBinaryCopyObjectForArch (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> BR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Arch, size_t ArchLen, char ** ErrorMessage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMMoveToContainingSection() {#gab7faf1f46a7fb022e21e792e0250709d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMMoveToContainingSection (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> Sect, <a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#a0453b143247301a1c5bdb3e25a6e4d2a">llvm::object::getSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMMoveToNextRelocation() {#ga3a1b85a24686caf1e4d5d4046b71d269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMMoveToNextRelocation (<a href="#gacfc595713ed017d3c5aaab450536fd5c">LLVMRelocationIteratorRef</a> RI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMMoveToNextSection() {#gaf73579ac560edf40c64de997c53df39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMMoveToNextSection (<a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMMoveToNextSymbol() {#ga9f94927ab91849027797983322db6f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMMoveToNextSymbol (<a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMObjectFileCopySectionIterator() {#gabb7cdf8752b1939d369936207f9b25c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMSectionIteratorRef LLVMObjectFileCopySectionIterator (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> BR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve a copy of the section iterator for this object file.</p>


<p>If there are no sections, the result is NULL.</p>


<p>The returned iterator is merely a shallow copy. Nevertheless, it is the responsibility of the caller to free it with <span class="doxyComputerOutput">LLVMDisposeSectionIterator</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::object::sections()</p></dd>
</dl>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#ad9bfff4f6c093ce614da964288d832c9">sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMObjectFileCopySymbolIterator() {#ga1002f207402c729401bc0b6de7f842f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMSymbolIteratorRef LLVMObjectFileCopySymbolIterator (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> BR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve a copy of the symbol iterator for this object file.</p>


<p>If there are no symbols, the result is NULL.</p>


<p>The returned iterator is merely a shallow copy. Nevertheless, it is the responsibility of the caller to free it with <span class="doxyComputerOutput">LLVMDisposeSymbolIterator</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::object::symbols()</p></dd>
</dl>


<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMObjectFileIsSectionIteratorAtEnd() {#ga9e0dcd6b052fe254c667071981e24f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMObjectFileIsSectionIteratorAtEnd (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> BR, <a href="#gaae688e21a05eafae72ca3a48af2e7b4d">LLVMSectionIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether the given section iterator is at the end.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::object::section_end</p></dd>
</dl>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMObjectFileIsSymbolIteratorAtEnd() {#gacdfb98daac681a078c04d6e52e2b4c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMObjectFileIsSymbolIteratorAtEnd (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga7b146c3251529961e8eeda888adac209">LLVMBinaryRef</a> BR, <a href="#ga387344c8d1fe17d3070d0299a21d4d92">LLVMSymbolIteratorRef</a> SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether the given symbol iterator is at the end.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::object::symbol_end</p></dd>
</dl>


<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/object-h">Object.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/object/object-cpp">Object.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
