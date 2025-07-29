---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/debuginfo-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DebugInfo.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h">llvm-c/ExternC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf09a2cd6396ded40b1260ca98a72e434">LLVMMetadataKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad62412f52ebf888987a3d47bb92957c8">LLVMDWARFTypeEncoding</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An LLVM DWARF type encoding. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad62412f52ebf888987a3d47bb92957c8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMDIFlags { <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga63e7a3126853c894baa1de14336a95dd">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug info flags. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga63e7a3126853c894baa1de14336a95dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMDWARFSourceLanguage { <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4436852644d626940ee2edc2ffb65880">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source languages known by DWARF. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4436852644d626940ee2edc2ffb65880">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMDWARFEmissionKind { <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaa41a1dcb1b6bd5caafaf78826c34ba05">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount of debug information to emit. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaa41a1dcb1b6bd5caafaf78826c34ba05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0381ae5461ce8b139d33b6b4f4285bb7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of metadata nodes. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0381ae5461ce8b139d33b6b4f4285bb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMDWARFMacinfoRecordType { <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga14993987c05399db82db9a73c7cb557c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describes the kind of macro declaration used for LLVMDIBuilderCreateMacro. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga14993987c05399db82db9a73c7cb557c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga731cad87060764d2639a9b661b88f3d4">LLVMDebugMetadataVersion</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current debug metadata version number. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga731cad87060764d2639a9b661b88f3d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga75216df9fb21497235b8dc0da3f77cd2">LLVMGetModuleDebugMetadataVersion</a> (LLVMModuleRef Module)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The version of debug metadata that's present in the provided <span class="doxyComputerOutput">Module</span>. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga75216df9fb21497235b8dc0da3f77cd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac86aed2f5553740f151cb1905d4718ee">LLVMStripModuleDebugInfo</a> (LLVMModuleRef Module)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip debug info in the module if it exists. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac86aed2f5553740f151cb1905d4718ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3e4ab5c187c85469fa148ba496ad785c">LLVMCreateDIBuilderDisallowUnresolved</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a builder for a module, and do not allow for unresolved nodes attached to the module. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3e4ab5c187c85469fa148ba496ad785c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga47bd8cf5e928bfd6e2dbbc41bef906e8">LLVMCreateDIBuilder</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a builder for a module and collect unresolved nodes attached to the module in order to resolve cycles during a call to <span class="doxyComputerOutput">LLVMDIBuilderFinalize</span>. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga47bd8cf5e928bfd6e2dbbc41bef906e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf36ccab6f24f7aa2fab88270756bf952">LLVMDisposeDIBuilder</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocates the <span class="doxyComputerOutput">DIBuilder</span> and everything it owns. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf36ccab6f24f7aa2fab88270756bf952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2137b1dffc60225e2d26756f299a2223">LLVMDIBuilderFinalize</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct any deferred debug info descriptors. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2137b1dffc60225e2d26756f299a2223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabc75effdb1e1cc44b4393c7716e7f5d2">LLVMDIBuilderFinalizeSubprogram</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Subprogram)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize a specific subprogram. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabc75effdb1e1cc44b4393c7716e7f5d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac80c97dafb7ed1815c40df3e29ac574d">LLVMDIBuilderCreateCompileUnit</a> (LLVMDIBuilderRef Builder, LLVMDWARFSourceLanguage Lang, LLVMMetadataRef FileRef, const char *Producer, size_t ProducerLen, LLVMBool isOptimized, const char *Flags, size_t FlagsLen, unsigned RuntimeVer, const char *SplitName, size_t SplitNameLen, LLVMDWARFEmissionKind Kind, unsigned DWOId, LLVMBool SplitDebugInlining, LLVMBool DebugInfoForProfiling, const char *SysRoot, size_t SysRootLen, const char *SDK, size_t SDKLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CompileUnit provides an anchor for all debugging information generated during this instance of compilation. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac80c97dafb7ed1815c40df3e29ac574d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaee236259f740de70edbb17b7a274aa3f">LLVMDIBuilderCreateFile</a> (LLVMDIBuilderRef Builder, const char *Filename, size_t FilenameLen, const char *Directory, size_t DirectoryLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a file descriptor to hold debugging information for a file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaee236259f740de70edbb17b7a274aa3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a47cdee54f0b80f9ba952d766582f97">LLVMDIBuilderCreateModule</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentScope, const char *Name, size_t NameLen, const char *ConfigMacros, size_t ConfigMacrosLen, const char *IncludePath, size_t IncludePathLen, const char *APINotesFile, size_t APINotesFileLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new descriptor for a module with the specified parent scope. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a47cdee54f0b80f9ba952d766582f97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga28cb215b1180c262f2a29d811fef274f">LLVMDIBuilderCreateNameSpace</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentScope, const char *Name, size_t NameLen, LLVMBool ExportSymbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new descriptor for a namespace with the specified parent scope. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga28cb215b1180c262f2a29d811fef274f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga16e177b130697369b80b40e2a6e4b4bd">LLVMDIBuilderCreateFunction</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *LinkageName, size_t LinkageNameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool IsLocalToUnit, LLVMBool IsDefinition, unsigned ScopeLine, LLVMDIFlags Flags, LLVMBool IsOptimized)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified subprogram. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga16e177b130697369b80b40e2a6e4b4bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad66fcc89d7abf993d470cc20459ac6c3">LLVMDIBuilderCreateLexicalBlock</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned Column)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a lexical block with the specified parent context. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad66fcc89d7abf993d470cc20459ac6c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233939d145977e24bad18c7a27718fba">LLVMDIBuilderCreateLexicalBlockFile</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Discriminator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a lexical block with a new file attached. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233939d145977e24bad18c7a27718fba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4bd7b93a5adab9a1c2e0115d6fd27aaa">LLVMDIBuilderCreateImportedModuleFromNamespace</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef NS, LLVMMetadataRef File, unsigned Line)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported namespace. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4bd7b93a5adab9a1c2e0115d6fd27aaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga79b2014998173c73f1643a12d125f57d">LLVMDIBuilderCreateImportedModuleFromAlias</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef ImportedEntity, LLVMMetadataRef File, unsigned Line, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module that aliases another imported entity descriptor. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga79b2014998173c73f1643a12d125f57d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0fb25118742415266bc77ba402c0be3e">LLVMDIBuilderCreateImportedModuleFromModule</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef M, LLVMMetadataRef File, unsigned Line, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0fb25118742415266bc77ba402c0be3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaecac3bea8780aabc755043bf56ccde16">LLVMDIBuilderCreateImportedDeclaration</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef Decl, LLVMMetadataRef File, unsigned Line, const char *Name, size_t NameLen, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported function, type, or variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaecac3bea8780aabc755043bf56ccde16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga297455fb958aa499228de05966751977">LLVMDIBuilderCreateDebugLocation</a> (LLVMContextRef Ctx, unsigned Line, unsigned Column, LLVMMetadataRef Scope, LLVMMetadataRef InlinedAt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new DebugLocation that describes a source location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga297455fb958aa499228de05966751977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac367fff632214b9cb6a7c72a560c6375">LLVMDILocationGetLine</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the line number of this debug location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac367fff632214b9cb6a7c72a560c6375">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5d3f8954443857acd2f3e63e924af5bb">LLVMDILocationGetColumn</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the column number of this debug location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5d3f8954443857acd2f3e63e924af5bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4b79e6d86d287cbd5a2bad9d890d0cf6">LLVMDILocationGetScope</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the local scope associated with this debug location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4b79e6d86d287cbd5a2bad9d890d0cf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga02154723977a1df274e6dd6cab1b3c12">LLVMDILocationGetInlinedAt</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the "inline at" location associated with this debug location. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga02154723977a1df274e6dd6cab1b3c12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabb1ada7b7f03079b1a3fc26d45a872c8">LLVMDIScopeGetFile</a> (LLVMMetadataRef Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the file associated with a given scope. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabb1ada7b7f03079b1a3fc26d45a872c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6d217da95423a5058437b10d48eb299c">LLVMDIFileGetDirectory</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the directory of a given file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6d217da95423a5058437b10d48eb299c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7080e9914e8708451283d10b69cc8edc">LLVMDIFileGetFilename</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of a given file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7080e9914e8708451283d10b69cc8edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae0a790e33f02c87d24b428da4d2b34ce">LLVMDIFileGetSource</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source of a given file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae0a790e33f02c87d24b428da4d2b34ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadbd363bcd72a98cc8225b11a0ea0f6fa">LLVMDIBuilderGetOrCreateTypeArray</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a type array. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadbd363bcd72a98cc8225b11a0ea0f6fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga96266a67a61ce67e77498296bbae2551">LLVMDIBuilderCreateSubroutineType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef File, LLVMMetadataRef *ParameterTypes, unsigned NumParameterTypes, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create subroutine type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga96266a67a61ce67e77498296bbae2551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9ea606817ce85b9915297eb2de2a653d">LLVMDIBuilderCreateMacro</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentMacroFile, unsigned Line, LLVMDWARFMacinfoRecordType RecordType, const char *Name, size_t NameLen, const char *Value, size_t ValueLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a macro. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9ea606817ce85b9915297eb2de2a653d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4f1086f983fe945bf4377c392ed87f4a">LLVMDIBuilderCreateTempMacroFile</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentMacroFile, unsigned Line, LLVMMetadataRef File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information temporary entry for a macro file. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga4f1086f983fe945bf4377c392ed87f4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga52949afcc1bb31880de9208e6a488329">LLVMDIBuilderCreateEnumerator</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, int64_t Value, LLVMBool IsUnsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an enumerator. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga52949afcc1bb31880de9208e6a488329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0f63a87fe95c032988248173c40836e4">LLVMDIBuilderCreateEnumerationType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMMetadataRef *Elements, unsigned NumElements, LLVMMetadataRef ClassTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an enumeration. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga0f63a87fe95c032988248173c40836e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga90500ff94794b86be3dd73f6d6f3a8a5">LLVMDIBuilderCreateUnionType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, LLVMMetadataRef *Elements, unsigned NumElements, unsigned RunTimeLang, const char *UniqueId, size_t UniqueIdLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a union. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga90500ff94794b86be3dd73f6d6f3a8a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab3c5243ec4c41efdde6efd665f31c2a9">LLVMDIBuilderCreateArrayType</a> (LLVMDIBuilderRef Builder, uint64_t Size, uint32_t AlignInBits, LLVMMetadataRef Ty, LLVMMetadataRef *Subscripts, unsigned NumSubscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an array. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab3c5243ec4c41efdde6efd665f31c2a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5a3fc221b7877d1efe4e10fe6d586a37">LLVMDIBuilderCreateVectorType</a> (LLVMDIBuilderRef Builder, uint64_t Size, uint32_t AlignInBits, LLVMMetadataRef Ty, LLVMMetadataRef *Subscripts, unsigned NumSubscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a vector type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5a3fc221b7877d1efe4e10fe6d586a37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga280cc8b0ba12ddba27a70640961d5aae">LLVMDIBuilderCreateUnspecifiedType</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DWARF unspecified type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga280cc8b0ba12ddba27a70640961d5aae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacec115e56690a95e2bbf90143b39b3a7">LLVMDIBuilderCreateBasicType</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, uint64_t SizeInBits, LLVMDWARFTypeEncoding Encoding, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a basic type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacec115e56690a95e2bbf90143b39b3a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafa96c20ff0708be1cabd2c06c9ce03ca">LLVMDIBuilderCreatePointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef PointeeTy, uint64_t SizeInBits, uint32_t AlignInBits, unsigned AddressSpace, const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a pointer. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafa96c20ff0708be1cabd2c06c9ce03ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf293a26d4fd886befce34f6ce2a3bdf1">LLVMDIBuilderCreateStructType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, LLVMMetadataRef DerivedFrom, LLVMMetadataRef *Elements, unsigned NumElements, unsigned RunTimeLang, LLVMMetadataRef VTableHolder, const char *UniqueId, size_t UniqueIdLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a struct. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf293a26d4fd886befce34f6ce2a3bdf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabe5507b0346c326bcbd875dec7dfca91">LLVMDIBuilderCreateMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a member. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabe5507b0346c326bcbd875dec7dfca91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7c8d150bba12a1d9874e3d692fd804f6">LLVMDIBuilderCreateStaticMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, LLVMMetadataRef Type, LLVMDIFlags Flags, LLVMValueRef ConstantVal, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a C++ static data member. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7c8d150bba12a1d9874e3d692fd804f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5abafa3c43023b3169fae1f22c678049">LLVMDIBuilderCreateMemberPointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef PointeeType, LLVMMetadataRef ClassType, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a pointer to member. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5abafa3c43023b3169fae1f22c678049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga00f6a1630b3771db5c911f99a4f8dca6">LLVMDIBuilderCreateObjCIVar</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Ty, LLVMMetadataRef PropertyNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Objective-C instance variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga00f6a1630b3771db5c911f99a4f8dca6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9cbf85a105f1c34719076b29b0830a83">LLVMDIBuilderCreateObjCProperty</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, const char *GetterName, size_t GetterNameLen, const char *SetterName, size_t SetterNameLen, unsigned PropertyAttributes, LLVMMetadataRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Objective-C property. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9cbf85a105f1c34719076b29b0830a83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga20ed80a8dd7b49ba6fcdd9d3d2ac20e5">LLVMDIBuilderCreateObjectPointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type, LLVMBool Implicit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a uniqued DIType* clone with FlagObjectPointer. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga20ed80a8dd7b49ba6fcdd9d3d2ac20e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8780f2c20339b37b01f8878401f27d00">LLVMDIBuilderCreateQualifiedType</a> (LLVMDIBuilderRef Builder, unsigned Tag, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a qualified type, e.g. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8780f2c20339b37b01f8878401f27d00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a2899f83e586e884e2c75811d911742">LLVMDIBuilderCreateReferenceType</a> (LLVMDIBuilderRef Builder, unsigned Tag, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a c++ style reference or rvalue reference type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3a2899f83e586e884e2c75811d911742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac54583c434a27a5a1cc2f1a64f1abd6e">LLVMDIBuilderCreateNullPtrType</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create C++11 nullptr type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac54583c434a27a5a1cc2f1a64f1abd6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf237e3bbfe69ee176ae2bf8db9079346">LLVMDIBuilderCreateTypedef</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Scope, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a typedef. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf237e3bbfe69ee176ae2bf8db9079346">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac57bc2d6025d4be99b2e1b11c91a8904">LLVMDIBuilderCreateInheritance</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Ty, LLVMMetadataRef BaseTy, uint64_t BaseOffset, uint32_t VBPtrOffset, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry to establish inheritance relationship between two types. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gac57bc2d6025d4be99b2e1b11c91a8904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga93103e684ef975e27c124279b530f4a4">LLVMDIBuilderCreateForwardDecl</a> (LLVMDIBuilderRef Builder, unsigned Tag, const char *Name, size_t NameLen, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a permanent forward-declared type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga93103e684ef975e27c124279b530f4a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadcfce4b4d1ca9e120e479b56f24378d2">LLVMDIBuilderCreateReplaceableCompositeType</a> (LLVMDIBuilderRef Builder, unsigned Tag, const char *Name, size_t NameLen, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a temporary forward-declared type. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gadcfce4b4d1ca9e120e479b56f24378d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b2ece29856cc374fa69d6945066f332">LLVMDIBuilderCreateBitFieldMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint64_t OffsetInBits, uint64_t StorageOffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a bit field member. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b2ece29856cc374fa69d6945066f332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabdc3694c6c196a2d7181860b40fb9ac3">LLVMDIBuilderCreateClassType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef DerivedFrom, LLVMMetadataRef *Elements, unsigned NumElements, LLVMMetadataRef VTableHolder, LLVMMetadataRef TemplateParamsNode, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a class. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabdc3694c6c196a2d7181860b40fb9ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga208f89cfe45c5cfe3fa2c77c9227964f">LLVMDIBuilderCreateArtificialType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a uniqued DIType* clone with FlagArtificial set. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga208f89cfe45c5cfe3fa2c77c9227964f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaef39844bc3df500ee733588158eae292">LLVMDITypeGetName</a> (LLVMMetadataRef DType, size_t *Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of this DIType. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaef39844bc3df500ee733588158eae292">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga12af60f959285ba5ff8d568d27dda9a9">LLVMDITypeGetSizeInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of this DIType in bits. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga12af60f959285ba5ff8d568d27dda9a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae9747065099a9912fec575bd7edb7857">LLVMDITypeGetOffsetInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the offset of this DIType in bits. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gae9747065099a9912fec575bd7edb7857">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2c1ae3a9365c49a64025df8a64086c2c">LLVMDITypeGetAlignInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alignment of this DIType in bits. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2c1ae3a9365c49a64025df8a64086c2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga780f4dfcebe39a69b115ae4f0d2b300f">LLVMDITypeGetLine</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source line where this DIType is declared. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga780f4dfcebe39a69b115ae4f0d2b300f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6bcea905cd35ad99a0d535721d8fe4ff">LLVMDITypeGetFlags</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the flags associated with this DIType. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6bcea905cd35ad99a0d535721d8fe4ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga45454a88af46c21af848f5f95db5795c">LLVMDIBuilderGetOrCreateSubrange</a> (LLVMDIBuilderRef Builder, int64_t LowerBound, int64_t Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a value range. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga45454a88af46c21af848f5f95db5795c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga07712e5d4d664c623674c09e03c9c011">LLVMDIBuilderGetOrCreateArray</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an array of DI Nodes. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga07712e5d4d664c623674c09e03c9c011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5821133c41a6cdaea77af97a71ce2ab1">LLVMDIBuilderCreateExpression</a> (LLVMDIBuilderRef Builder, uint64_t *Addr, size_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable which has a complex address expression for its address. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga5821133c41a6cdaea77af97a71ce2ab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabd9e7761d1632466c41620b609381644">LLVMDIBuilderCreateConstantValueExpression</a> (LLVMDIBuilderRef Builder, uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable that does not have an address, but does have a constant value. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gabd9e7761d1632466c41620b609381644">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga83af94c8ebc30248947274cd3c6b2b18">LLVMDIBuilderCreateGlobalVariableExpression</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *Linkage, size_t LinkLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool LocalToUnit, LLVMMetadataRef Expr, LLVMMetadataRef Decl, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga83af94c8ebc30248947274cd3c6b2b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga829c0e0a5fec733d28b736c072bec4eb">LLVMGetDINodeTag</a> (LLVMMetadataRef MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the dwarf::Tag of a DINode. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga829c0e0a5fec733d28b736c072bec4eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b9b6964e6643fc8cd61ea5b7a447ac3">LLVMDIGlobalVariableExpressionGetVariable</a> (LLVMMetadataRef GVE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the <span class="doxyComputerOutput">DIVariable</span> associated with this global variable expression. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga1b9b6964e6643fc8cd61ea5b7a447ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2d889441ac9541119cc05b65b178bcfe">LLVMDIGlobalVariableExpressionGetExpression</a> (LLVMMetadataRef GVE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the <span class="doxyComputerOutput">DIExpression</span> associated with this global variable expression. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2d889441ac9541119cc05b65b178bcfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7929e8886d3a6c8c121f17dcb2af1dd6">LLVMDIVariableGetFile</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the file associated with a given variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga7929e8886d3a6c8c121f17dcb2af1dd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2ed3e2ec3f48e55ed167177139d5b14b">LLVMDIVariableGetScope</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the scope associated with a given variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2ed3e2ec3f48e55ed167177139d5b14b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad19c6732705efa0c40e2bc0010632303">LLVMDIVariableGetLine</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source line where this <span class="doxyComputerOutput">DIVariable</span> is declared. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad19c6732705efa0c40e2bc0010632303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga68d0a34a31a878cc0452697bebf63e1f">LLVMTemporaryMDNode</a> (LLVMContextRef Ctx, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new temporary <span class="doxyComputerOutput">MDNode</span>. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga68d0a34a31a878cc0452697bebf63e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga488dddd6a44fa6154d5520c2a76cab41">LLVMDisposeTemporaryMDNode</a> (LLVMMetadataRef TempNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate a temporary node. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga488dddd6a44fa6154d5520c2a76cab41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga704c67d1afa02bfe39cd02b4830c8f3f">LLVMMetadataReplaceAllUsesWith</a> (LLVMMetadataRef TempTargetMetadata, LLVMMetadataRef Replacement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all uses of temporary metadata. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga704c67d1afa02bfe39cd02b4830c8f3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga862c55fb3e10df7538c7883a948df025">LLVMDIBuilderCreateTempGlobalVariableFwdDecl</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *Linkage, size_t LnkLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool LocalToUnit, LLVMMetadataRef Decl, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified global variable that is temporary and meant to be RAUWed. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga862c55fb3e10df7538c7883a948df025">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacac753a410ba2c99ab8de5a5bb6275aa">LLVMDIBuilderInsertDeclareRecordBefore</a> (LLVMDIBuilderRef Builder, LLVMValueRef Storage, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMValueRef Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gacac753a410ba2c99ab8de5a5bb6275aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga17213bad234b832c6447b97ce0a1cdfa">LLVMDIBuilderInsertDeclareRecordAtEnd</a> (LLVMDIBuilderRef Builder, LLVMValueRef Storage, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMBasicBlockRef Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga17213bad234b832c6447b97ce0a1cdfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad502913d5fbb1891c256136560488409">LLVMDIBuilderInsertDbgValueRecordBefore</a> (LLVMDIBuilderRef Builder, LLVMValueRef Val, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMValueRef Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gad502913d5fbb1891c256136560488409">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab976691ac79d65d9ff429b3c5a8f587a">LLVMDIBuilderInsertDbgValueRecordAtEnd</a> (LLVMDIBuilderRef Builder, LLVMValueRef Val, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMBasicBlockRef Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab976691ac79d65d9ff429b3c5a8f587a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga677811d786d2d985b961135a8b0a555b">LLVMDIBuilderCreateAutoVariable</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool AlwaysPreserve, LLVMDIFlags Flags, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a local auto variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga677811d786d2d985b961135a8b0a555b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9390bbfb5a8ea9b429b6086a6fcf957a">LLVMDIBuilderCreateParameterVariable</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, unsigned ArgNo, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool AlwaysPreserve, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a function parameter variable. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga9390bbfb5a8ea9b429b6086a6fcf957a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafddfbdaa9a85beba597ca456f2085251">LLVMGetSubprogram</a> (LLVMValueRef Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the subprogram attached to a function. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gafddfbdaa9a85beba597ca456f2085251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3fb4cb7331aa97b2bdd91044b5c33fad">LLVMSetSubprogram</a> (LLVMValueRef Func, LLVMMetadataRef SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the subprogram attached to a function. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga3fb4cb7331aa97b2bdd91044b5c33fad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233c8c86bdfa0ceaad5ddbbb5d50fa1d">LLVMDISubprogramGetLine</a> (LLVMMetadataRef Subprogram)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the line associated with a given subprogram. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga233c8c86bdfa0ceaad5ddbbb5d50fa1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2f2db17683a598ccfcfe8b0ad33f3040">LLVMInstructionGetDebugLoc</a> (LLVMValueRef Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the debug location for the given instruction. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga2f2db17683a598ccfcfe8b0ad33f3040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga50b4ca3bd1b86721e92ac6b411af63c8">LLVMInstructionSetDebugLoc</a> (LLVMValueRef Inst, LLVMMetadataRef Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the debug location for the given instruction. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga50b4ca3bd1b86721e92ac6b411af63c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga71d2155ac54703ed0f1e3e230ef36065">LLVMDIBuilderCreateLabel</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Context, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMBool AlwaysPreserve)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a label. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga71d2155ac54703ed0f1e3e230ef36065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gace19cbd43c471a934793ba8f66ec16ce">LLVMDIBuilderInsertLabelBefore</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef LabelInfo, LLVMMetadataRef Location, LLVMValueRef InsertBefore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.label intrinsic call. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gace19cbd43c471a934793ba8f66ec16ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab176ba6b04ac20f7363e3f2315dd7545">LLVMDIBuilderInsertLabelAtEnd</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef LabelInfo, LLVMMetadataRef Location, LLVMBasicBlockRef InsertAtEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.label intrinsic call. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gab176ba6b04ac20f7363e3f2315dd7545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#gaf09a2cd6396ded40b1260ca98a72e434">LLVMMetadataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8794c88979fc63df9256714ddad96268">LLVMGetMetadataKind</a> (LLVMMetadataRef Metadata)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the enumerated type of a Metadata instance. <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga8794c88979fc63df9256714ddad96268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
