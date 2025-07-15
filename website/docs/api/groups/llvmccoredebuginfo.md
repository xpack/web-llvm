---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccoredebuginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Debug Information Reference

<p>This file declares the C API endpoints for generating DWARF Debug Info. <a href="#details">More...</a></p>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned <a href="#gaf09a2cd6396ded40b1260ca98a72e434">LLVMMetadataKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned <a href="#gad62412f52ebf888987a3d47bb92957c8">LLVMDWARFTypeEncoding</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An LLVM DWARF type encoding. <a href="#gad62412f52ebf888987a3d47bb92957c8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMDIFlags { <a href="#ga63e7a3126853c894baa1de14336a95dd">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug info flags. <a href="#ga63e7a3126853c894baa1de14336a95dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMDWARFSourceLanguage { <a href="#ga4436852644d626940ee2edc2ffb65880">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source languages known by DWARF. <a href="#ga4436852644d626940ee2edc2ffb65880">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMDWARFEmissionKind { <a href="#gaa41a1dcb1b6bd5caafaf78826c34ba05">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The amount of debug information to emit. <a href="#gaa41a1dcb1b6bd5caafaf78826c34ba05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#ga0381ae5461ce8b139d33b6b4f4285bb7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of metadata nodes. <a href="#ga0381ae5461ce8b139d33b6b4f4285bb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMDWARFMacinfoRecordType { <a href="#ga14993987c05399db82db9a73c7cb557c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describes the kind of macro declaration used for LLVMDIBuilderCreateMacro. <a href="#ga14993987c05399db82db9a73c7cb557c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga731cad87060764d2639a9b661b88f3d4">LLVMDebugMetadataVersion</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current debug metadata version number. <a href="#ga731cad87060764d2639a9b661b88f3d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga75216df9fb21497235b8dc0da3f77cd2">LLVMGetModuleDebugMetadataVersion</a> (LLVMModuleRef Module)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The version of debug metadata that's present in the provided <span class="doxyComputerOutput">Module</span>. <a href="#ga75216df9fb21497235b8dc0da3f77cd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac86aed2f5553740f151cb1905d4718ee">LLVMStripModuleDebugInfo</a> (LLVMModuleRef Module)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Strip debug info in the module if it exists. <a href="#gac86aed2f5553740f151cb1905d4718ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3e4ab5c187c85469fa148ba496ad785c">LLVMCreateDIBuilderDisallowUnresolved</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a builder for a module, and do not allow for unresolved nodes attached to the module. <a href="#ga3e4ab5c187c85469fa148ba496ad785c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga47bd8cf5e928bfd6e2dbbc41bef906e8">LLVMCreateDIBuilder</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a builder for a module and collect unresolved nodes attached to the module in order to resolve cycles during a call to <span class="doxyComputerOutput">LLVMDIBuilderFinalize</span>. <a href="#ga47bd8cf5e928bfd6e2dbbc41bef906e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf36ccab6f24f7aa2fab88270756bf952">LLVMDisposeDIBuilder</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocates the <span class="doxyComputerOutput">DIBuilder</span> and everything it owns. <a href="#gaf36ccab6f24f7aa2fab88270756bf952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2137b1dffc60225e2d26756f299a2223">LLVMDIBuilderFinalize</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct any deferred debug info descriptors. <a href="#ga2137b1dffc60225e2d26756f299a2223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabc75effdb1e1cc44b4393c7716e7f5d2">LLVMDIBuilderFinalizeSubprogram</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Subprogram)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize a specific subprogram. <a href="#gabc75effdb1e1cc44b4393c7716e7f5d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac80c97dafb7ed1815c40df3e29ac574d">LLVMDIBuilderCreateCompileUnit</a> (LLVMDIBuilderRef Builder, LLVMDWARFSourceLanguage Lang, LLVMMetadataRef FileRef, const char *Producer, size_t ProducerLen, LLVMBool isOptimized, const char *Flags, size_t FlagsLen, unsigned RuntimeVer, const char *SplitName, size_t SplitNameLen, LLVMDWARFEmissionKind Kind, unsigned DWOId, LLVMBool SplitDebugInlining, LLVMBool DebugInfoForProfiling, const char *SysRoot, size_t SysRootLen, const char *SDK, size_t SDKLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CompileUnit provides an anchor for all debugging information generated during this instance of compilation. <a href="#gac80c97dafb7ed1815c40df3e29ac574d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaee236259f740de70edbb17b7a274aa3f">LLVMDIBuilderCreateFile</a> (LLVMDIBuilderRef Builder, const char *Filename, size_t FilenameLen, const char *Directory, size_t DirectoryLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a file descriptor to hold debugging information for a file. <a href="#gaee236259f740de70edbb17b7a274aa3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3a47cdee54f0b80f9ba952d766582f97">LLVMDIBuilderCreateModule</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentScope, const char *Name, size_t NameLen, const char *ConfigMacros, size_t ConfigMacrosLen, const char *IncludePath, size_t IncludePathLen, const char *APINotesFile, size_t APINotesFileLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new descriptor for a module with the specified parent scope. <a href="#ga3a47cdee54f0b80f9ba952d766582f97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga28cb215b1180c262f2a29d811fef274f">LLVMDIBuilderCreateNameSpace</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentScope, const char *Name, size_t NameLen, LLVMBool ExportSymbols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new descriptor for a namespace with the specified parent scope. <a href="#ga28cb215b1180c262f2a29d811fef274f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga16e177b130697369b80b40e2a6e4b4bd">LLVMDIBuilderCreateFunction</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *LinkageName, size_t LinkageNameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool IsLocalToUnit, LLVMBool IsDefinition, unsigned ScopeLine, LLVMDIFlags Flags, LLVMBool IsOptimized)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified subprogram. <a href="#ga16e177b130697369b80b40e2a6e4b4bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad66fcc89d7abf993d470cc20459ac6c3">LLVMDIBuilderCreateLexicalBlock</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned Column)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a lexical block with the specified parent context. <a href="#gad66fcc89d7abf993d470cc20459ac6c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga233939d145977e24bad18c7a27718fba">LLVMDIBuilderCreateLexicalBlockFile</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Discriminator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a lexical block with a new file attached. <a href="#ga233939d145977e24bad18c7a27718fba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4bd7b93a5adab9a1c2e0115d6fd27aaa">LLVMDIBuilderCreateImportedModuleFromNamespace</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef NS, LLVMMetadataRef File, unsigned Line)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported namespace. <a href="#ga4bd7b93a5adab9a1c2e0115d6fd27aaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga79b2014998173c73f1643a12d125f57d">LLVMDIBuilderCreateImportedModuleFromAlias</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef ImportedEntity, LLVMMetadataRef File, unsigned Line, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module that aliases another imported entity descriptor. <a href="#ga79b2014998173c73f1643a12d125f57d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0fb25118742415266bc77ba402c0be3e">LLVMDIBuilderCreateImportedModuleFromModule</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef M, LLVMMetadataRef File, unsigned Line, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported module. <a href="#ga0fb25118742415266bc77ba402c0be3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaecac3bea8780aabc755043bf56ccde16">LLVMDIBuilderCreateImportedDeclaration</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, LLVMMetadataRef Decl, LLVMMetadataRef File, unsigned Line, const char *Name, size_t NameLen, LLVMMetadataRef *Elements, unsigned NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for an imported function, type, or variable. <a href="#gaecac3bea8780aabc755043bf56ccde16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga297455fb958aa499228de05966751977">LLVMDIBuilderCreateDebugLocation</a> (LLVMContextRef Ctx, unsigned Line, unsigned Column, LLVMMetadataRef Scope, LLVMMetadataRef InlinedAt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new DebugLocation that describes a source location. <a href="#ga297455fb958aa499228de05966751977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac367fff632214b9cb6a7c72a560c6375">LLVMDILocationGetLine</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the line number of this debug location. <a href="#gac367fff632214b9cb6a7c72a560c6375">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5d3f8954443857acd2f3e63e924af5bb">LLVMDILocationGetColumn</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the column number of this debug location. <a href="#ga5d3f8954443857acd2f3e63e924af5bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4b79e6d86d287cbd5a2bad9d890d0cf6">LLVMDILocationGetScope</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the local scope associated with this debug location. <a href="#ga4b79e6d86d287cbd5a2bad9d890d0cf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga02154723977a1df274e6dd6cab1b3c12">LLVMDILocationGetInlinedAt</a> (LLVMMetadataRef Location)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the "inline at" location associated with this debug location. <a href="#ga02154723977a1df274e6dd6cab1b3c12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabb1ada7b7f03079b1a3fc26d45a872c8">LLVMDIScopeGetFile</a> (LLVMMetadataRef Scope)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the file associated with a given scope. <a href="#gabb1ada7b7f03079b1a3fc26d45a872c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6d217da95423a5058437b10d48eb299c">LLVMDIFileGetDirectory</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the directory of a given file. <a href="#ga6d217da95423a5058437b10d48eb299c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7080e9914e8708451283d10b69cc8edc">LLVMDIFileGetFilename</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of a given file. <a href="#ga7080e9914e8708451283d10b69cc8edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae0a790e33f02c87d24b428da4d2b34ce">LLVMDIFileGetSource</a> (LLVMMetadataRef File, unsigned *Len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source of a given file. <a href="#gae0a790e33f02c87d24b428da4d2b34ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gadbd363bcd72a98cc8225b11a0ea0f6fa">LLVMDIBuilderGetOrCreateTypeArray</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a type array. <a href="#gadbd363bcd72a98cc8225b11a0ea0f6fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga96266a67a61ce67e77498296bbae2551">LLVMDIBuilderCreateSubroutineType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef File, LLVMMetadataRef *ParameterTypes, unsigned NumParameterTypes, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create subroutine type. <a href="#ga96266a67a61ce67e77498296bbae2551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9ea606817ce85b9915297eb2de2a653d">LLVMDIBuilderCreateMacro</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentMacroFile, unsigned Line, LLVMDWARFMacinfoRecordType RecordType, const char *Name, size_t NameLen, const char *Value, size_t ValueLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a macro. <a href="#ga9ea606817ce85b9915297eb2de2a653d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4f1086f983fe945bf4377c392ed87f4a">LLVMDIBuilderCreateTempMacroFile</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef ParentMacroFile, unsigned Line, LLVMMetadataRef File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information temporary entry for a macro file. <a href="#ga4f1086f983fe945bf4377c392ed87f4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga52949afcc1bb31880de9208e6a488329">LLVMDIBuilderCreateEnumerator</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, int64_t Value, LLVMBool IsUnsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an enumerator. <a href="#ga52949afcc1bb31880de9208e6a488329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0f63a87fe95c032988248173c40836e4">LLVMDIBuilderCreateEnumerationType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMMetadataRef *Elements, unsigned NumElements, LLVMMetadataRef ClassTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an enumeration. <a href="#ga0f63a87fe95c032988248173c40836e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga90500ff94794b86be3dd73f6d6f3a8a5">LLVMDIBuilderCreateUnionType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, LLVMMetadataRef *Elements, unsigned NumElements, unsigned RunTimeLang, const char *UniqueId, size_t UniqueIdLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a union. <a href="#ga90500ff94794b86be3dd73f6d6f3a8a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab3c5243ec4c41efdde6efd665f31c2a9">LLVMDIBuilderCreateArrayType</a> (LLVMDIBuilderRef Builder, uint64_t Size, uint32_t AlignInBits, LLVMMetadataRef Ty, LLVMMetadataRef *Subscripts, unsigned NumSubscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for an array. <a href="#gab3c5243ec4c41efdde6efd665f31c2a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5a3fc221b7877d1efe4e10fe6d586a37">LLVMDIBuilderCreateVectorType</a> (LLVMDIBuilderRef Builder, uint64_t Size, uint32_t AlignInBits, LLVMMetadataRef Ty, LLVMMetadataRef *Subscripts, unsigned NumSubscripts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a vector type. <a href="#ga5a3fc221b7877d1efe4e10fe6d586a37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga280cc8b0ba12ddba27a70640961d5aae">LLVMDIBuilderCreateUnspecifiedType</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DWARF unspecified type. <a href="#ga280cc8b0ba12ddba27a70640961d5aae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacec115e56690a95e2bbf90143b39b3a7">LLVMDIBuilderCreateBasicType</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, uint64_t SizeInBits, LLVMDWARFTypeEncoding Encoding, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a basic type. <a href="#gacec115e56690a95e2bbf90143b39b3a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafa96c20ff0708be1cabd2c06c9ce03ca">LLVMDIBuilderCreatePointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef PointeeTy, uint64_t SizeInBits, uint32_t AlignInBits, unsigned AddressSpace, const char *Name, size_t NameLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a pointer. <a href="#gafa96c20ff0708be1cabd2c06c9ce03ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf293a26d4fd886befce34f6ce2a3bdf1">LLVMDIBuilderCreateStructType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, LLVMMetadataRef DerivedFrom, LLVMMetadataRef *Elements, unsigned NumElements, unsigned RunTimeLang, LLVMMetadataRef VTableHolder, const char *UniqueId, size_t UniqueIdLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a struct. <a href="#gaf293a26d4fd886befce34f6ce2a3bdf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabe5507b0346c326bcbd875dec7dfca91">LLVMDIBuilderCreateMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a member. <a href="#gabe5507b0346c326bcbd875dec7dfca91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7c8d150bba12a1d9874e3d692fd804f6">LLVMDIBuilderCreateStaticMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, LLVMMetadataRef Type, LLVMDIFlags Flags, LLVMValueRef ConstantVal, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a C++ static data member. <a href="#ga7c8d150bba12a1d9874e3d692fd804f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5abafa3c43023b3169fae1f22c678049">LLVMDIBuilderCreateMemberPointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef PointeeType, LLVMMetadataRef ClassType, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a pointer to member. <a href="#ga5abafa3c43023b3169fae1f22c678049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga00f6a1630b3771db5c911f99a4f8dca6">LLVMDIBuilderCreateObjCIVar</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Ty, LLVMMetadataRef PropertyNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Objective-C instance variable. <a href="#ga00f6a1630b3771db5c911f99a4f8dca6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9cbf85a105f1c34719076b29b0830a83">LLVMDIBuilderCreateObjCProperty</a> (LLVMDIBuilderRef Builder, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, const char *GetterName, size_t GetterNameLen, const char *SetterName, size_t SetterNameLen, unsigned PropertyAttributes, LLVMMetadataRef Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for Objective-C property. <a href="#ga9cbf85a105f1c34719076b29b0830a83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga20ed80a8dd7b49ba6fcdd9d3d2ac20e5">LLVMDIBuilderCreateObjectPointerType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type, LLVMBool Implicit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a uniqued DIType* clone with FlagObjectPointer. <a href="#ga20ed80a8dd7b49ba6fcdd9d3d2ac20e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8780f2c20339b37b01f8878401f27d00">LLVMDIBuilderCreateQualifiedType</a> (LLVMDIBuilderRef Builder, unsigned Tag, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a qualified type, e.g. <a href="#ga8780f2c20339b37b01f8878401f27d00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3a2899f83e586e884e2c75811d911742">LLVMDIBuilderCreateReferenceType</a> (LLVMDIBuilderRef Builder, unsigned Tag, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a c++ style reference or rvalue reference type. <a href="#ga3a2899f83e586e884e2c75811d911742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac54583c434a27a5a1cc2f1a64f1abd6e">LLVMDIBuilderCreateNullPtrType</a> (LLVMDIBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create C++11 nullptr type. <a href="#gac54583c434a27a5a1cc2f1a64f1abd6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf237e3bbfe69ee176ae2bf8db9079346">LLVMDIBuilderCreateTypedef</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Scope, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a typedef. <a href="#gaf237e3bbfe69ee176ae2bf8db9079346">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac57bc2d6025d4be99b2e1b11c91a8904">LLVMDIBuilderCreateInheritance</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Ty, LLVMMetadataRef BaseTy, uint64_t BaseOffset, uint32_t VBPtrOffset, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry to establish inheritance relationship between two types. <a href="#gac57bc2d6025d4be99b2e1b11c91a8904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga93103e684ef975e27c124279b530f4a4">LLVMDIBuilderCreateForwardDecl</a> (LLVMDIBuilderRef Builder, unsigned Tag, const char *Name, size_t NameLen, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a permanent forward-declared type. <a href="#ga93103e684ef975e27c124279b530f4a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gadcfce4b4d1ca9e120e479b56f24378d2">LLVMDIBuilderCreateReplaceableCompositeType</a> (LLVMDIBuilderRef Builder, unsigned Tag, const char *Name, size_t NameLen, LLVMMetadataRef Scope, LLVMMetadataRef File, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, LLVMDIFlags Flags, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a temporary forward-declared type. <a href="#gadcfce4b4d1ca9e120e479b56f24378d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1b2ece29856cc374fa69d6945066f332">LLVMDIBuilderCreateBitFieldMemberType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint64_t OffsetInBits, uint64_t StorageOffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a bit field member. <a href="#ga1b2ece29856cc374fa69d6945066f332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabdc3694c6c196a2d7181860b40fb9ac3">LLVMDIBuilderCreateClassType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, LLVMDIFlags Flags, LLVMMetadataRef DerivedFrom, LLVMMetadataRef *Elements, unsigned NumElements, LLVMMetadataRef VTableHolder, LLVMMetadataRef TemplateParamsNode, const char *UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create debugging information entry for a class. <a href="#gabdc3694c6c196a2d7181860b40fb9ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga208f89cfe45c5cfe3fa2c77c9227964f">LLVMDIBuilderCreateArtificialType</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a uniqued DIType* clone with FlagArtificial set. <a href="#ga208f89cfe45c5cfe3fa2c77c9227964f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaef39844bc3df500ee733588158eae292">LLVMDITypeGetName</a> (LLVMMetadataRef DType, size_t *Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of this DIType. <a href="#gaef39844bc3df500ee733588158eae292">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga12af60f959285ba5ff8d568d27dda9a9">LLVMDITypeGetSizeInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of this DIType in bits. <a href="#ga12af60f959285ba5ff8d568d27dda9a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae9747065099a9912fec575bd7edb7857">LLVMDITypeGetOffsetInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the offset of this DIType in bits. <a href="#gae9747065099a9912fec575bd7edb7857">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2c1ae3a9365c49a64025df8a64086c2c">LLVMDITypeGetAlignInBits</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alignment of this DIType in bits. <a href="#ga2c1ae3a9365c49a64025df8a64086c2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga780f4dfcebe39a69b115ae4f0d2b300f">LLVMDITypeGetLine</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source line where this DIType is declared. <a href="#ga780f4dfcebe39a69b115ae4f0d2b300f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6bcea905cd35ad99a0d535721d8fe4ff">LLVMDITypeGetFlags</a> (LLVMMetadataRef DType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the flags associated with this DIType. <a href="#ga6bcea905cd35ad99a0d535721d8fe4ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga45454a88af46c21af848f5f95db5795c">LLVMDIBuilderGetOrCreateSubrange</a> (LLVMDIBuilderRef Builder, int64_t LowerBound, int64_t Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a descriptor for a value range. <a href="#ga45454a88af46c21af848f5f95db5795c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga07712e5d4d664c623674c09e03c9c011">LLVMDIBuilderGetOrCreateArray</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an array of DI Nodes. <a href="#ga07712e5d4d664c623674c09e03c9c011">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5821133c41a6cdaea77af97a71ce2ab1">LLVMDIBuilderCreateExpression</a> (LLVMDIBuilderRef Builder, uint64_t *Addr, size_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable which has a complex address expression for its address. <a href="#ga5821133c41a6cdaea77af97a71ce2ab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gabd9e7761d1632466c41620b609381644">LLVMDIBuilderCreateConstantValueExpression</a> (LLVMDIBuilderRef Builder, uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable that does not have an address, but does have a constant value. <a href="#gabd9e7761d1632466c41620b609381644">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga83af94c8ebc30248947274cd3c6b2b18">LLVMDIBuilderCreateGlobalVariableExpression</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *Linkage, size_t LinkLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool LocalToUnit, LLVMMetadataRef Expr, LLVMMetadataRef Decl, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified variable. <a href="#ga83af94c8ebc30248947274cd3c6b2b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga829c0e0a5fec733d28b736c072bec4eb">LLVMGetDINodeTag</a> (LLVMMetadataRef MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the dwarf::Tag of a DINode. <a href="#ga829c0e0a5fec733d28b736c072bec4eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1b9b6964e6643fc8cd61ea5b7a447ac3">LLVMDIGlobalVariableExpressionGetVariable</a> (LLVMMetadataRef GVE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the <span class="doxyComputerOutput">DIVariable</span> associated with this global variable expression. <a href="#ga1b9b6964e6643fc8cd61ea5b7a447ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2d889441ac9541119cc05b65b178bcfe">LLVMDIGlobalVariableExpressionGetExpression</a> (LLVMMetadataRef GVE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the <span class="doxyComputerOutput">DIExpression</span> associated with this global variable expression. <a href="#ga2d889441ac9541119cc05b65b178bcfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7929e8886d3a6c8c121f17dcb2af1dd6">LLVMDIVariableGetFile</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the file associated with a given variable. <a href="#ga7929e8886d3a6c8c121f17dcb2af1dd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2ed3e2ec3f48e55ed167177139d5b14b">LLVMDIVariableGetScope</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the scope associated with a given variable. <a href="#ga2ed3e2ec3f48e55ed167177139d5b14b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad19c6732705efa0c40e2bc0010632303">LLVMDIVariableGetLine</a> (LLVMMetadataRef Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the source line where this <span class="doxyComputerOutput">DIVariable</span> is declared. <a href="#gad19c6732705efa0c40e2bc0010632303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga68d0a34a31a878cc0452697bebf63e1f">LLVMTemporaryMDNode</a> (LLVMContextRef Ctx, LLVMMetadataRef *Data, size_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new temporary <span class="doxyComputerOutput">MDNode</span>. <a href="#ga68d0a34a31a878cc0452697bebf63e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga488dddd6a44fa6154d5520c2a76cab41">LLVMDisposeTemporaryMDNode</a> (LLVMMetadataRef TempNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate a temporary node. <a href="#ga488dddd6a44fa6154d5520c2a76cab41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga704c67d1afa02bfe39cd02b4830c8f3f">LLVMMetadataReplaceAllUsesWith</a> (LLVMMetadataRef TempTargetMetadata, LLVMMetadataRef Replacement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all uses of temporary metadata. <a href="#ga704c67d1afa02bfe39cd02b4830c8f3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga862c55fb3e10df7538c7883a948df025">LLVMDIBuilderCreateTempGlobalVariableFwdDecl</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, const char *Linkage, size_t LnkLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool LocalToUnit, LLVMMetadataRef Decl, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for the specified global variable that is temporary and meant to be RAUWed. <a href="#ga862c55fb3e10df7538c7883a948df025">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacac753a410ba2c99ab8de5a5bb6275aa">LLVMDIBuilderInsertDeclareRecordBefore</a> (LLVMDIBuilderRef Builder, LLVMValueRef Storage, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMValueRef Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="#gacac753a410ba2c99ab8de5a5bb6275aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga17213bad234b832c6447b97ce0a1cdfa">LLVMDIBuilderInsertDeclareRecordAtEnd</a> (LLVMDIBuilderRef Builder, LLVMValueRef Storage, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMBasicBlockRef Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="#ga17213bad234b832c6447b97ce0a1cdfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad502913d5fbb1891c256136560488409">LLVMDIBuilderInsertDbgValueRecordBefore</a> (LLVMDIBuilderRef Builder, LLVMValueRef Val, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMValueRef Instr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="#gad502913d5fbb1891c256136560488409">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab976691ac79d65d9ff429b3c5a8f587a">LLVMDIBuilderInsertDbgValueRecordAtEnd</a> (LLVMDIBuilderRef Builder, LLVMValueRef Val, LLVMMetadataRef VarInfo, LLVMMetadataRef Expr, LLVMMetadataRef DebugLoc, LLVMBasicBlockRef Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true). <a href="#gab976691ac79d65d9ff429b3c5a8f587a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga677811d786d2d985b961135a8b0a555b">LLVMDIBuilderCreateAutoVariable</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool AlwaysPreserve, LLVMDIFlags Flags, uint32_t AlignInBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a local auto variable. <a href="#ga677811d786d2d985b961135a8b0a555b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9390bbfb5a8ea9b429b6086a6fcf957a">LLVMDIBuilderCreateParameterVariable</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Scope, const char *Name, size_t NameLen, unsigned ArgNo, LLVMMetadataRef File, unsigned LineNo, LLVMMetadataRef Ty, LLVMBool AlwaysPreserve, LLVMDIFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a function parameter variable. <a href="#ga9390bbfb5a8ea9b429b6086a6fcf957a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafddfbdaa9a85beba597ca456f2085251">LLVMGetSubprogram</a> (LLVMValueRef Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of the subprogram attached to a function. <a href="#gafddfbdaa9a85beba597ca456f2085251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3fb4cb7331aa97b2bdd91044b5c33fad">LLVMSetSubprogram</a> (LLVMValueRef Func, LLVMMetadataRef SP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the subprogram attached to a function. <a href="#ga3fb4cb7331aa97b2bdd91044b5c33fad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga233c8c86bdfa0ceaad5ddbbb5d50fa1d">LLVMDISubprogramGetLine</a> (LLVMMetadataRef Subprogram)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the line associated with a given subprogram. <a href="#ga233c8c86bdfa0ceaad5ddbbb5d50fa1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2f2db17683a598ccfcfe8b0ad33f3040">LLVMInstructionGetDebugLoc</a> (LLVMValueRef Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the debug location for the given instruction. <a href="#ga2f2db17683a598ccfcfe8b0ad33f3040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga50b4ca3bd1b86721e92ac6b411af63c8">LLVMInstructionSetDebugLoc</a> (LLVMValueRef Inst, LLVMMetadataRef Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the debug location for the given instruction. <a href="#ga50b4ca3bd1b86721e92ac6b411af63c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga71d2155ac54703ed0f1e3e230ef36065">LLVMDIBuilderCreateLabel</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef Context, const char *Name, size_t NameLen, LLVMMetadataRef File, unsigned LineNo, LLVMBool AlwaysPreserve)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new descriptor for a label. <a href="#ga71d2155ac54703ed0f1e3e230ef36065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gace19cbd43c471a934793ba8f66ec16ce">LLVMDIBuilderInsertLabelBefore</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef LabelInfo, LLVMMetadataRef Location, LLVMValueRef InsertBefore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.label intrinsic call. <a href="#gace19cbd43c471a934793ba8f66ec16ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga54eadb23779a7b2538b9a7b03d9c2630">LLVMDbgRecordRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab176ba6b04ac20f7363e3f2315dd7545">LLVMDIBuilderInsertLabelAtEnd</a> (LLVMDIBuilderRef Builder, LLVMMetadataRef LabelInfo, LLVMMetadataRef Location, LLVMBasicBlockRef InsertAtEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a new llvm.dbg.label intrinsic call. <a href="#gab176ba6b04ac20f7363e3f2315dd7545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gaf09a2cd6396ded40b1260ca98a72e434">LLVMMetadataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8794c88979fc63df9256714ddad96268">LLVMGetMetadataKind</a> (LLVMMetadataRef Metadata)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the enumerated type of a Metadata instance. <a href="#ga8794c88979fc63df9256714ddad96268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file declares the C API endpoints for generating DWARF Debug Info.</p>


<p>Note: This interface is experimental. It is <em>NOT</em> stable, and may be changed without warning.</p>


<div class="doxySectionDef">

## Typedefs

### LLVMDWARFTypeEncoding {#gad62412f52ebf888987a3d47bb92957c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned LLVMDWARFTypeEncoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An LLVM DWARF type encoding.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### LLVMMetadataKind {#gaf09a2cd6396ded40b1260ca98a72e434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned LLVMMetadataKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#ga0381ae5461ce8b139d33b6b4f4285bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of metadata nodes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMMDStringMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7ad203db64f5df42423348c437868e0c14"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMConstantAsMetadataMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7aef805e515266afb0530e8b7b4dc80aea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMLocalAsMetadataMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a5cad901a10e749f28b61920e77e22a86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDistinctMDOperandPlaceholderMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a6fa424e6b77601f5bdbb9ff1fc766127"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMMDTupleMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a40e2d20266dd80fb3243604b9756f09d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDILocationMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a67ea674f47c0ad5085d4a623a226f206"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIExpressionMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a5a9729aa7680a062ddc0d520cdc8c00a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIGlobalVariableExpressionMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a5bb7b0e9905efe70590a493f9208af48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMGenericDINodeMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a00fe33697e8adfcbb9fc8349b504669e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDISubrangeMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a96790746379fc94f21e7a303daee6f42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIEnumeratorMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7ad7a97192aa9696debbb9916c3c1b30f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIBasicTypeMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7ae899c483787b7ac15326d754e526c568"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIDerivedTypeMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a08f5a75207ff5972ea9047ef70f4ab14"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDICompositeTypeMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7ace849b4e62304a772f8b783d4f23a044"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDISubroutineTypeMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7afec21eed1dc75ae2d2786fa1a5d6762d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFileMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7ade308d61d4647525e89dcfc612e45558"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDICompileUnitMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7ac67562176e2bc44923c9adc13d7f32af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDISubprogramMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7afe6a6f9eb3ab59e6e70186a30e8d10dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDILexicalBlockMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a16432f9c657ff8485129dd40b34748f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDILexicalBlockFileMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a7b641559b82257860313446eb32eab43"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDINamespaceMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7aa22bb088955fb0800a924abcb4993431"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIModuleMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7adecf7dcb636765d827335d84a9938d50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDITemplateTypeParameterMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a8ea28e63d65178a17542e998b95f0be0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDITemplateValueParameterMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a97ac43bf3e68acccd500dab732a6a74d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIGlobalVariableMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a93f29f5f40d26806c2e62db291a2d160"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDILocalVariableMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a6261e18558927acb1a61a7a0c01338ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDILabelMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7af65f3bab1b31b71c3cd8926196db0e07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIObjCPropertyMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a98176a8521400e3860503de9b92527bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIImportedEntityMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a9155ced9aec2c162cb96b2270f5ddcc3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIMacroMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a1196d72dac7cf151c1f01364a96cf140"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIMacroFileMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a837a29f038b22a61e3ebcf17050c07f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDICommonBlockMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7af3f5f2de1e9d928722b35e1812bfe02e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIStringTypeMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7aeffde81ae7f147c87f86896d0dd0f3c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIGenericSubrangeMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7abc0e181703e2487eb1c9fa3dfabda546"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIArgListMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a89da72384eb5a76282d63ea01f1b07e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIAssignIDMetadataKind<a id="gga0381ae5461ce8b139d33b6b4f4285bb7a944605fb41d2283e9f46327b112cb875"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### LLVMDIFlags {#ga63e7a3126853c894baa1de14336a95dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LLVMDIFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug info flags.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagZero<a id="gga63e7a3126853c894baa1de14336a95ddaff75b6132df1976a7c59ecebab82c933"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagPrivate<a id="gga63e7a3126853c894baa1de14336a95dda11e412953bd8d153ed164396cb16fa28"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagProtected<a id="gga63e7a3126853c894baa1de14336a95dda342a9a57d1ae27a8b42b951766511bf9"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagPublic<a id="gga63e7a3126853c894baa1de14336a95ddaa2e72d92c4183727940d3964d5dc3c82"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagFwdDecl<a id="gga63e7a3126853c894baa1de14336a95ddada42351236c8ba39aa6d95184e9d9895"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagAppleBlock<a id="gga63e7a3126853c894baa1de14336a95dda3deb72659718be7c30cc348a6efe41a1"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagReservedBit4<a id="gga63e7a3126853c894baa1de14336a95dda9a5fd731e1b678d197502d1e52c53db3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagVirtual<a id="gga63e7a3126853c894baa1de14336a95ddaadcb4b9f8f3c5a9e8f5757e27ee4107a"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagArtificial<a id="gga63e7a3126853c894baa1de14336a95ddaa0cc7feaf0132abcbd3792c79b5ffde2"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagExplicit<a id="gga63e7a3126853c894baa1de14336a95dda79b0f8b67ff8d03a37ee99ece29db76c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagPrototyped<a id="gga63e7a3126853c894baa1de14336a95dda13336c64c83f38eb8d966256e2f327d0"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagObjcClassComplete<a id="gga63e7a3126853c894baa1de14336a95dda2d3f43089ff10f72be32d85596e4a0c7"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagObjectPointer<a id="gga63e7a3126853c894baa1de14336a95ddaf032471d6fc2c1f28813eee50df7440e"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagVector<a id="gga63e7a3126853c894baa1de14336a95ddaa8dfd9ca7c3051cbc25a6ea39a4d68ce"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagStaticMember<a id="gga63e7a3126853c894baa1de14336a95ddaa615f54d59c882b797687b288556f3db"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagLValueReference<a id="gga63e7a3126853c894baa1de14336a95ddae42bfb99d1515e5b8d0a79580eb9885f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagRValueReference<a id="gga63e7a3126853c894baa1de14336a95dda33919542573e01315de766dc27609b3d"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagReserved<a id="gga63e7a3126853c894baa1de14336a95ddac33d1f281ea00e749f3e97395b9969c5"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagSingleInheritance<a id="gga63e7a3126853c894baa1de14336a95ddab4b152a7315528dd72953579d0484f0c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagMultipleInheritance<a id="gga63e7a3126853c894baa1de14336a95dda7acb41fc17a259007dc15f293332a3d1"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagVirtualInheritance<a id="gga63e7a3126853c894baa1de14336a95ddac206798bb946cedd91d200f428251fee"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagIntroducedVirtual<a id="gga63e7a3126853c894baa1de14336a95dda368e8f929dcd67caeeb2638b31685193"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagBitField<a id="gga63e7a3126853c894baa1de14336a95dda2910ae38c5499953275c7deaf8277385"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagNoReturn<a id="gga63e7a3126853c894baa1de14336a95dda65e9b8f9625c5981a710a1928d2f7122"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagTypePassByValue<a id="gga63e7a3126853c894baa1de14336a95ddac45aeb01b9548e083e57fe0a8b911565"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagTypePassByReference<a id="gga63e7a3126853c894baa1de14336a95dda3ef26b8c89ac252450f0a0805398f819"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagEnumClass<a id="gga63e7a3126853c894baa1de14336a95ddace4750120777594579552ed7d55578ea"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagFixedEnum<a id="gga63e7a3126853c894baa1de14336a95dda5e3ba31848fee76902e9d0275e3a48ab"></a></td>
<td class="doxyEnumItemDescription"> (= LLVMDIFlagEnumClass)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagThunk<a id="gga63e7a3126853c894baa1de14336a95dda833bcfd63b49191998dd66aa748d89ad"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagNonTrivial<a id="gga63e7a3126853c894baa1de14336a95ddafbf7b072683daf3b7dc6ae6e3b7f6d36"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagBigEndian<a id="gga63e7a3126853c894baa1de14336a95dda0582fc45364ada8afd3a02f7b4a86080"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagLittleEndian<a id="gga63e7a3126853c894baa1de14336a95dda8ae8c636dce5887f4fada341ff44f833"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagIndirectVirtualBase<a id="gga63e7a3126853c894baa1de14336a95dda8561050bdbbb495fc1f20323371c572f"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 2) | (1 &lt;&lt; 5))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagAccessibility<a id="gga63e7a3126853c894baa1de14336a95dda31b76fb42959de0649d125b7b4d0951d"></a></td>
<td class="doxyEnumItemDescription">
 (= LLVMDIFlagPrivate | LLVMDIFlagProtected |
                            LLVMDIFlagPublic)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDIFlagPtrToMemberRep<a id="gga63e7a3126853c894baa1de14336a95ddaad0b79bfe539d62f8f2176d18d7266ff"></a></td>
<td class="doxyEnumItemDescription">
 (= LLVMDIFlagSingleInheritance |
                             LLVMDIFlagMultipleInheritance |
                             LLVMDIFlagVirtualInheritance)
</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### LLVMDWARFEmissionKind {#gaa41a1dcb1b6bd5caafaf78826c34ba05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LLVMDWARFEmissionKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The amount of debug information to emit.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFEmissionNone<a id="ggaa41a1dcb1b6bd5caafaf78826c34ba05ab2b0a69650b8f1050ba7220d0a0de244"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFEmissionFull<a id="ggaa41a1dcb1b6bd5caafaf78826c34ba05a681dcc8e6cde1cc7a30f101523bbbcf0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFEmissionLineTablesOnly<a id="ggaa41a1dcb1b6bd5caafaf78826c34ba05a381e6f1a5801026f29d14bed299c91e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### LLVMDWARFMacinfoRecordType {#ga14993987c05399db82db9a73c7cb557c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LLVMDWARFMacinfoRecordType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Describes the kind of macro declaration used for LLVMDIBuilderCreateMacro.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFMacinfoRecordTypeDefine<a id="gga14993987c05399db82db9a73c7cb557caf34a19a9900f91340014a1c1b058498a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFMacinfoRecordTypeMacro<a id="gga14993987c05399db82db9a73c7cb557ca98340c66d2c9bd5bf1395dda213fd368"></a></td>
<td class="doxyEnumItemDescription"> (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFMacinfoRecordTypeStartFile<a id="gga14993987c05399db82db9a73c7cb557ca05986df92cfdc1588b78445a61dccbb4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x03)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFMacinfoRecordTypeEndFile<a id="gga14993987c05399db82db9a73c7cb557ca7fb8734e3dbad5f047fc98349ac22b7d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x04)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFMacinfoRecordTypeVendorExt<a id="gga14993987c05399db82db9a73c7cb557ca30e633469901361359e40dd7e168d1e0"></a></td>
<td class="doxyEnumItemDescription"> (= 0xff)</td>
</tr>

</table>
</dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a87afc9d377fa974a25781035ac4c15d1">llvm::dwarf::MacinfoRecordType</a></p></dd>
</dl>



:::info
<p>Values are from DW_MACINFO_* constants in the DWARF specification.</p>
:::


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

### LLVMDWARFSourceLanguage {#ga4436852644d626940ee2edc2ffb65880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LLVMDWARFSourceLanguage </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source languages known by DWARF.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC89<a id="gga4436852644d626940ee2edc2ffb65880ad7120a438fe55388fa63222d0099d075"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC<a id="gga4436852644d626940ee2edc2ffb65880a28baf8c8dd102cbce551120251ad6576"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageAda83<a id="gga4436852644d626940ee2edc2ffb65880afcc5d501e50523b0ec400b5a5815dcdd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC_plus_plus<a id="gga4436852644d626940ee2edc2ffb65880a6feae8b3874a33ab4ce71aa123178f4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageCobol74<a id="gga4436852644d626940ee2edc2ffb65880a0f807bcd8f045db7a85ec0da79b2ff3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageCobol85<a id="gga4436852644d626940ee2edc2ffb65880a56e4f74a3a92b17f34c358dfda0f9b78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageFortran77<a id="gga4436852644d626940ee2edc2ffb65880aa79e086c0bf5518b622230161723bf01"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageFortran90<a id="gga4436852644d626940ee2edc2ffb65880a86f0dae2826b6d357970b21cb9a7b3fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguagePascal83<a id="gga4436852644d626940ee2edc2ffb65880aba2ce736030cfd3410f359ce79f514a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageModula2<a id="gga4436852644d626940ee2edc2ffb65880a6121f5d364eaa1e57f6d8cb9146d1c3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageJava<a id="gga4436852644d626940ee2edc2ffb65880a03314af363b90363a877901061542721"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC99<a id="gga4436852644d626940ee2edc2ffb65880a700260fb727f88a1d0fd476b81f7da1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageAda95<a id="gga4436852644d626940ee2edc2ffb65880a38b924f824d2b3ff5d55c4845e039775"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageFortran95<a id="gga4436852644d626940ee2edc2ffb65880ac987558ba262546ae534ee73861a796f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguagePLI<a id="gga4436852644d626940ee2edc2ffb65880abb0b8cc15e170f9375da1c7c0f4735fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageObjC<a id="gga4436852644d626940ee2edc2ffb65880a93c9ecddc70095dd54c1a1cb81426e80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageObjC_plus_plus<a id="gga4436852644d626940ee2edc2ffb65880ab30e815d965764aa9e7e93ac8a2102c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageUPC<a id="gga4436852644d626940ee2edc2ffb65880a0fdc395e0957f53641e13e376e104e25"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageD<a id="gga4436852644d626940ee2edc2ffb65880a49aea6e0c601393e5b296720997568cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguagePython<a id="gga4436852644d626940ee2edc2ffb65880ad91c628e525013bae3c0e8da9ef1df74"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageOpenCL<a id="gga4436852644d626940ee2edc2ffb65880a7c0e58caa62cc1371d9a05a648720c77"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageGo<a id="gga4436852644d626940ee2edc2ffb65880a8fb6d7fc23e9bc8a4d7f1fd6abd472d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageModula3<a id="gga4436852644d626940ee2edc2ffb65880a8af643aaca0ee2e27afd13b41826d6f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageHaskell<a id="gga4436852644d626940ee2edc2ffb65880af759c887cfdf0c069c1580c030751275"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC_plus_plus_03<a id="gga4436852644d626940ee2edc2ffb65880acc95f24b5b9081e43278bb400e445e7b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC_plus_plus_11<a id="gga4436852644d626940ee2edc2ffb65880af79bcc2dc5518d33a8abc2e03f57a982"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageOCaml<a id="gga4436852644d626940ee2edc2ffb65880aeeaed2b0bc7581cc812cccc31e8f768f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageRust<a id="gga4436852644d626940ee2edc2ffb65880a8302f37242d5c4876fae2e442da0e6e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC11<a id="gga4436852644d626940ee2edc2ffb65880ac1d841a509bd2863c58b0a5231409a45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageSwift<a id="gga4436852644d626940ee2edc2ffb65880a0beaf01afac39cc77411c16d5d84396e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageJulia<a id="gga4436852644d626940ee2edc2ffb65880a89d2f0c8dedd214e5aa12ebe08109212"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageDylan<a id="gga4436852644d626940ee2edc2ffb65880a17a92a6d64c75b72f69d2ca8f359e4f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC_plus_plus_14<a id="gga4436852644d626940ee2edc2ffb65880a259d328e18639c66e390edfb7ef6c037"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageFortran03<a id="gga4436852644d626940ee2edc2ffb65880a135abc7d3eb384d17dafabff39ba2e61"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageFortran08<a id="gga4436852644d626940ee2edc2ffb65880ab6fb0ee9098eb74bd6fc5a662fbb10d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageRenderScript<a id="gga4436852644d626940ee2edc2ffb65880ae1e9e8aec79f6bffa9f051c39518fd6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageBLISS<a id="gga4436852644d626940ee2edc2ffb65880a02fe7483a3f8e0af536fac6b0129d6c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageKotlin<a id="gga4436852644d626940ee2edc2ffb65880a5dab2a11204316ac31406a3ff4cf65aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageZig<a id="gga4436852644d626940ee2edc2ffb65880af0c36eb9866d419ed7da08a26f58b59f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageCrystal<a id="gga4436852644d626940ee2edc2ffb65880aed45ed2fae6badbfe599a4315edc23f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC_plus_plus_17<a id="gga4436852644d626940ee2edc2ffb65880a1a5fcd6cabe0205eb2cecad8bdaea460"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC_plus_plus_20<a id="gga4436852644d626940ee2edc2ffb65880a28f4bd52d8a23b646101420fe826486d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC17<a id="gga4436852644d626940ee2edc2ffb65880abd43c51b06ef35c3ce90fe941b6f589d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageFortran18<a id="gga4436852644d626940ee2edc2ffb65880acdd155539216298993b834432086d76c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageAda2005<a id="gga4436852644d626940ee2edc2ffb65880a153af9fdad6f8ca4980a2a4dc811504a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageAda2012<a id="gga4436852644d626940ee2edc2ffb65880a4c948218bdd50f725f7fb9a3c3f5ff69"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageHIP<a id="gga4436852644d626940ee2edc2ffb65880ab269f4822a5e3fee03945cc4e5737819"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageAssembly<a id="gga4436852644d626940ee2edc2ffb65880ae3faf6f3bbabe32ceb22d298a8eace1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageC_sharp<a id="gga4436852644d626940ee2edc2ffb65880a9af528e944035535cd63bc4db9cc5adf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageMojo<a id="gga4436852644d626940ee2edc2ffb65880a7bb1d91097d694b71a3b4a85742b70db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageGLSL<a id="gga4436852644d626940ee2edc2ffb65880a99248beab7ce71c21fee72a0e5966aff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageGLSL_ES<a id="gga4436852644d626940ee2edc2ffb65880a4ddf9c93d3259b41353cc2c8425f675c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageHLSL<a id="gga4436852644d626940ee2edc2ffb65880af8e94e9a2f96f64f50dfc6e87c450f9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageOpenCL_CPP<a id="gga4436852644d626940ee2edc2ffb65880a0609d58ad3df6edef9c0ff45485cc6de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageCPP_for_OpenCL<a id="gga4436852644d626940ee2edc2ffb65880a2d1395dd6fdb0ec119711bffadb8e78b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageSYCL<a id="gga4436852644d626940ee2edc2ffb65880ae7e782d754c50bce1ae7c6ca3c7a802c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageRuby<a id="gga4436852644d626940ee2edc2ffb65880ab2154e60933964f4ef7c2142c61cc6e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageMove<a id="gga4436852644d626940ee2edc2ffb65880a56040466f42fe49e224a2ed886c057a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageHylo<a id="gga4436852644d626940ee2edc2ffb65880a8186f262e4ac71447ce796e46ef899dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageMetal<a id="gga4436852644d626940ee2edc2ffb65880ac237d42d082d2016e851f47de3ff4970"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageMips_Assembler<a id="gga4436852644d626940ee2edc2ffb65880ab1c8379004fcae97d78aac75cbb16f17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageGOOGLE_RenderScript<a id="gga4436852644d626940ee2edc2ffb65880a0386a7925c8a94677e73bda9ebb9dad6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMDWARFSourceLanguageBORLAND_Delphi<a id="gga4436852644d626940ee2edc2ffb65880a9cdf70fec03f9059a887d30459ba8593"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMCreateDIBuilder() {#ga47bd8cf5e928bfd6e2dbbc41bef906e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDIBuilderRef LLVMCreateDIBuilder (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a builder for a module and collect unresolved nodes attached to the module in order to resolve cycles during a call to <span class="doxyComputerOutput">LLVMDIBuilderFinalize</span>.</p>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCreateDIBuilderDisallowUnresolved() {#ga3e4ab5c187c85469fa148ba496ad785c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDIBuilderRef LLVMCreateDIBuilderDisallowUnresolved (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a builder for a module, and do not allow for unresolved nodes attached to the module.</p>

<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDebugMetadataVersion() {#ga731cad87060764d2639a9b661b88f3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMDebugMetadataVersion (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current debug metadata version number.</p>

<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aeff8da57698622ba29e5228d5ffe8bf3a141a51821a2860389357334148e2fd62">llvm::DEBUG_METADATA_VERSION</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateArrayType() {#gab3c5243ec4c41efdde6efd665f31c2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateArrayType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, uint64_t Size, uint32_t AlignInBits, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Subscripts, unsigned NumSubscripts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for an array.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Array size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Element type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Subscripts</td>
<td class="doxyParamItemDescription"><p>Subscripts.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumSubscripts</td>
<td class="doxyParamItemDescription"><p>Number of subscripts.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateArtificialType() {#ga208f89cfe45c5cfe3fa2c77c9227964f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateArtificialType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a uniqued DIType* clone with FlagArtificial set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Type</td>
<td class="doxyParamItemDescription"><p>The underlying type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1053 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1556 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateAutoVariable() {#ga677811d786d2d985b961135a8b0a555b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateAutoVariable (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> AlwaysPreserve, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, uint32_t AlignInBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for a local auto variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The local scope the variable is declared in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Variable name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of variable name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this variable is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Metadata describing the type of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlwaysPreserve</td>
<td class="doxyParamItemDescription"><p>If true, this descriptor will survive optimizations.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Variable alignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1361 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1752 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateBasicType() {#gacec115e56690a95e2bbf90143b39b3a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateBasicType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, uint64_t SizeInBits, <a href="#gad62412f52ebf888987a3d47bb92957c8">LLVMDWARFTypeEncoding</a> Encoding, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a basic type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Type name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of type name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Size of the type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Encoding</td>
<td class="doxyParamItemDescription"><p>DWARF encoding code, e.g. <span class="doxyComputerOutput">LLVMDWARFTypeEncoding_float</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode optional attribute like endianity</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 724 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1346 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateBitFieldMemberType() {#ga1b2ece29856cc374fa69d6945066f332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateBitFieldMemberType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNumber, uint64_t SizeInBits, uint64_t OffsetInBits, uint64_t StorageOffsetInBits, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a bit field member.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Member scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StorageOffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member storage offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Type</td>
<td class="doxyParamItemDescription"><p>Parent type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateClassType() {#gabdc3694c6c196a2d7181860b40fb9ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateClassType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DerivedFrom, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Elements, unsigned NumElements, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> VTableHolder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> TemplateParamsNode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a class.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this class is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Class name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Name</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DerivedFrom</td>
<td class="doxyParamItemDescription"><p>Debug info of the base class of this type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Class members.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of class elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VTableHolder</td>
<td class="doxyParamItemDescription"><p>Debug info of the base class that contains vtable for this type. This is used in DW_AT_containing_type. See DWARF documentation for more info.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TemplateParamsNode</td>
<td class="doxyParamItemDescription"><p>Template type parameters.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifier</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifierLen</td>
<td class="doxyParamItemDescription"><p>Length of the unique identifier.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1038 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1536 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateCompileUnit() {#gac80c97dafb7ed1815c40df3e29ac574d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateCompileUnit (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="#ga4436852644d626940ee2edc2ffb65880">LLVMDWARFSourceLanguage</a> Lang, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> FileRef, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Producer, size_t ProducerLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> isOptimized, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Flags, size_t FlagsLen, unsigned RuntimeVer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SplitName, size_t SplitNameLen, <a href="#gaa41a1dcb1b6bd5caafaf78826c34ba05">LLVMDWARFEmissionKind</a> Kind, unsigned DWOId, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> SplitDebugInlining, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> DebugInfoForProfiling, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SysRoot, size_t SysRootLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SDK, size_t SDKLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A CompileUnit provides an anchor for all debugging information generated during this instance of compilation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Lang</td>
<td class="doxyParamItemDescription"><p>Source programming language, eg. <span class="doxyComputerOutput">LLVMDWARFSourceLanguageC99</span></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FileRef</td>
<td class="doxyParamItemDescription"><p>File info.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Producer</td>
<td class="doxyParamItemDescription"><p>Identify the producer of debugging information and code. Usually this is a compiler version string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ProducerLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Producer</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">isOptimized</td>
<td class="doxyParamItemDescription"><p>A boolean flag which indicates whether optimization is enabled or not.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>This string lists command line options. This string is directly embedded in debug info output which may be used by a tool analyzing generated debugging information.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FlagsLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Flags</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RuntimeVer</td>
<td class="doxyParamItemDescription"><p>This indicates runtime version for languages like Objective-C.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SplitName</td>
<td class="doxyParamItemDescription"><p>The name of the file that we'll split debug info out into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SplitNameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">SplitName</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The kind of debug information to generate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DWOId</td>
<td class="doxyParamItemDescription"><p>The DWOId if this is a split skeleton compile unit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SplitDebugInlining</td>
<td class="doxyParamItemDescription"><p>Whether to emit inline debug info.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugInfoForProfiling</td>
<td class="doxyParamItemDescription"><p>Whether to emit extra debug info for profile collection.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SysRoot</td>
<td class="doxyParamItemDescription"><p>The Clang system root (value of -isysroot).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SysRootLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">SysRoot</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SDK</td>
<td class="doxyParamItemDescription"><p>The SDK. On Darwin, the last component of the sysroot.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SDKLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">SDK</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a47f44483cc8b041dd1678649b750da01a7a1920d61156abc05a60135aefe8bc67">llvm::DICompileUnit::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a8fb21c837dc04c6def8040f838b51f2e">map_from_llvmDWARFsourcelanguage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateConstantValueExpression() {#gabd9e7761d1632466c41620b609381644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateConstantValueExpression (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified variable that does not have an address, but does have a constant value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Value</td>
<td class="doxyParamItemDescription"><p>The constant value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1142 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1617 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateDebugLocation() {#ga297455fb958aa499228de05966751977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateDebugLocation (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> Ctx, unsigned Line, unsigned Column, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> InlinedAt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a new DebugLocation that describes a source location.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>The line in the source file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Column</td>
<td class="doxyParamItemDescription"><p>The column in the source file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The scope in which the location resides.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InlinedAt</td>
<td class="doxyParamItemDescription"><p>The scope where this location was inlined, if at all. (optional).</p></td>
</tr>
</table>
</dd>
</dl>


:::info
<p>If the item to which this location is attached cannot be attributed to a source line, pass 0 for the line and column.</p>
:::


<p>Declaration at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1220 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateEnumerationType() {#ga0f63a87fe95c032988248173c40836e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateEnumerationType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Elements, unsigned NumElements, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> ClassTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for an enumeration.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this enumeration is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Enumeration name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of enumeration name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Enumeration elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of enumeration elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ClassTy</td>
<td class="doxyParamItemDescription"><p>Underlying type of a C++11/ObjC fixed enum.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateEnumerator() {#ga52949afcc1bb31880de9208e6a488329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateEnumerator (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, int64_t Value, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> IsUnsigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for an enumerator.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Enumerator name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of enumerator name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Value</td>
<td class="doxyParamItemDescription"><p>Enumerator value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsUnsigned</td>
<td class="doxyParamItemDescription"><p>True if the value is unsigned.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1288 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateExpression() {#ga5821133c41a6cdaea77af97a71ce2ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateExpression (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, uint64_t * Addr, size_t Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified variable which has a complex address expression for its address.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>An array of complex address operations.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Length</td>
<td class="doxyParamItemDescription"><p>Length of the address operation array.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1132 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1610 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateFile() {#gaee236259f740de70edbb17b7a274aa3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateFile (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Filename, size_t FilenameLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Directory, size_t DirectoryLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a file descriptor to hold debugging information for a file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Filename</td>
<td class="doxyParamItemDescription"><p>File name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FilenameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Filename</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Directory</td>
<td class="doxyParamItemDescription"><p>Directory.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DirectoryLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Directory</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1107 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateForwardDecl() {#ga93103e684ef975e27c124279b530f4a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateForwardDecl (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, unsigned Tag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a permanent forward-declared type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tag</td>
<td class="doxyParamItemDescription"><p>A unique tag for this type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Type name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of type name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Type scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number where this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RuntimeLang</td>
<td class="doxyParamItemDescription"><p>Indicates runtime version for languages like Objective-C.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifier</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifierLen</td>
<td class="doxyParamItemDescription"><p>Length of the unique identifier.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 961 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1463 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateFunction() {#ga16e177b130697369b80b40e2a6e4b4bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateFunction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * LinkageName, size_t LinkageNameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> IsLocalToUnit, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> IsDefinition, unsigned ScopeLine, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> IsOptimized)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified subprogram.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Function scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Function name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of enumeration name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LinkageName</td>
<td class="doxyParamItemDescription"><p>Mangled function name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LinkageNameLen</td>
<td class="doxyParamItemDescription"><p>Length of linkage name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this variable is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Function type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsLocalToUnit</td>
<td class="doxyParamItemDescription"><p>True if this function is not externally visible.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDefinition</td>
<td class="doxyParamItemDescription"><p>True if this is a function definition.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ScopeLine</td>
<td class="doxyParamItemDescription"><p>Set to the beginning of the scope this starts</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>E.g.: <span class="doxyComputerOutput">LLVMDIFlagLValueReference</span>. These flags are used to emit dwarf attributes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsOptimized</td>
<td class="doxyParamItemDescription"><p>True if optimization is ON.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a11192367cc63da8f6cd8415d7d93b56a">pack_into_DISPFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateGlobalVariableExpression() {#ga83af94c8ebc30248947274cd3c6b2b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateGlobalVariableExpression (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Linkage, size_t LinkLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> LocalToUnit, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Expr, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Decl, uint32_t AlignInBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Variable scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Name</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Linkage</td>
<td class="doxyParamItemDescription"><p>Mangled name of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LinkLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Linkage</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this variable is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Variable Type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LocalToUnit</td>
<td class="doxyParamItemDescription"><p>Boolean flag indicate whether this variable is externally visible or not.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The location of the global relative to the attached GlobalVariable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Decl</td>
<td class="doxyParamItemDescription"><p>Reference to the corresponding declaration. variables.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Variable alignment(or 0 if no alignment attr was
                   specified)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1164 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1622 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilfinalizelinkage-cpp/#ae721973516c2b86042a5127b776e2806">Linkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateImportedDeclaration() {#gaecac3bea8780aabc755043bf56ccde16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateImportedDeclaration (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Decl, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned Line, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Elements, unsigned NumElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for an imported function, type, or variable.</p>


<p>Suitable for e.g. FORTRAN-style USE declarations.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The scope this module is imported into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Decl</td>
<td class="doxyParamItemDescription"><p>The declaration (or definition) of a function, type, or variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where the declaration is located.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number of the declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>A name that uniquely identifies this imported declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Name</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Renamed elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of renamed elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1206 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateImportedModuleFromAlias() {#ga79b2014998173c73f1643a12d125f57d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateImportedModuleFromAlias (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> ImportedEntity, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned Line, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Elements, unsigned NumElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for an imported module that aliases another imported entity descriptor.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The scope this module is imported into</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ImportedEntity</td>
<td class="doxyParamItemDescription"><p>Previous imported entity to alias.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where the declaration is located.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number of the declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Renamed elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of renamed elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#af012955ffa86a4774541d3e9acd23d12">createImportedModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateImportedModuleFromModule() {#ga0fb25118742415266bc77ba402c0be3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateImportedModuleFromModule (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> M, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned Line, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Elements, unsigned NumElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for an imported module.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The scope this module is imported into</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>The module being imported here</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where the declaration is located.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number of the declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Renamed elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of renamed elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1193 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#af012955ffa86a4774541d3e9acd23d12">createImportedModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateImportedModuleFromNamespace() {#ga4bd7b93a5adab9a1c2e0115d6fd27aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateImportedModuleFromNamespace (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> NS, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned Line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for an imported namespace.</p>


<p>Suitable for e.g. C++ using declarations.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The scope this module is imported into</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where the declaration is located.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number of the declaration.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#af012955ffa86a4774541d3e9acd23d12">createImportedModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateInheritance() {#gac57bc2d6025d4be99b2e1b11c91a8904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateInheritance (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> BaseTy, uint64_t BaseOffset, uint32_t VBPtrOffset, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry to establish inheritance relationship between two types.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Original type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseTy</td>
<td class="doxyParamItemDescription"><p>Base type. Ty is inherits from base.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseOffset</td>
<td class="doxyParamItemDescription"><p>Base offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VBPtrOffset</td>
<td class="doxyParamItemDescription"><p>Virtual base pointer offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to describe inheritance attribute, e.g. private</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1453 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateLabel() {#ga71d2155ac54703ed0f1e3e230ef36065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateLabel (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> AlwaysPreserve)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for a label.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The scope to create the label in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Variable name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of variable name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>The file to create the label in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line Number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlwaysPreserve</td>
<td class="doxyParamItemDescription"><p>Preserve the label regardless of optimization.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a4c600597532d3123b025c387d90aa7df">llvm::DIBuilder::createLabel()</a></p></dd>
</dl>


<p>Declaration at line 1435 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1807 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateLexicalBlock() {#gad66fcc89d7abf993d470cc20459ac6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateLexicalBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned Line, unsigned Column)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for a lexical block with the specified parent context.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Parent lexical block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>Source file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>The line in the source file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Column</td>
<td class="doxyParamItemDescription"><p>The column in the source file.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateLexicalBlockFile() {#ga233939d145977e24bad18c7a27718fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateLexicalBlockFile (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned Discriminator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for a lexical block with a new file attached.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Lexical block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>Source file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Discriminator</td>
<td class="doxyParamItemDescription"><p>DWARF path discriminator value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateMacro() {#ga9ea606817ce85b9915297eb2de2a653d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateMacro (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> ParentMacroFile, unsigned Line, <a href="#ga14993987c05399db82db9a73c7cb557c">LLVMDWARFMacinfoRecordType</a> RecordType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Value, size_t ValueLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a macro.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParentMacroFile</td>
<td class="doxyParamItemDescription"><p>Macro parent (could be NULL).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Source line number where the macro is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#ae5fbc6e1ce3fcbb7f185ed9e7beffec7"&gt;RecordType&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>DW_MACINFO_define or DW_MACINFO_undef.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Macro name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Macro name length.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Value</td>
<td class="doxyParamItemDescription"><p>Macro value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ValueLen</td>
<td class="doxyParamItemDescription"><p>Macro value length.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1268 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateMemberPointerType() {#ga5abafa3c43023b3169fae1f22c678049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateMemberPointerType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> PointeeType, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> ClassType, uint64_t SizeInBits, uint32_t AlignInBits, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a pointer to member.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PointeeType</td>
<td class="doxyParamItemDescription"><p>Type pointed to by this pointer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ClassType</td>
<td class="doxyParamItemDescription"><p>Type for which this pointer points to members of.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1508 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateMemberType() {#gabe5507b0346c326bcbd875dec7dfca91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateMemberType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a member.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Member scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parent type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1380 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateModule() {#ga3a47cdee54f0b80f9ba952d766582f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateModule (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> ParentScope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ConfigMacros, size_t ConfigMacrosLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * IncludePath, size_t IncludePathLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * APINotesFile, size_t APINotesFileLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a new descriptor for a module with the specified parent scope.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParentScope</td>
<td class="doxyParamItemDescription"><p>The parent scope containing this module declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Module name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Name</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ConfigMacros</td>
<td class="doxyParamItemDescription"><p>A space-separated shell-quoted list of -D macro definitions as they would appear on a command line.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ConfigMacrosLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">ConfigMacros</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IncludePath</td>
<td class="doxyParamItemDescription"><p>The path to the module map file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IncludePathLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">IncludePath</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">APINotesFile</td>
<td class="doxyParamItemDescription"><p>The path to an API notes file for the module.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">APINotesFileLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">APINotestFile</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateNameSpace() {#ga28cb215b1180c262f2a29d811fef274f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateNameSpace (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> ParentScope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> ExportSymbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a new descriptor for a namespace with the specified parent scope.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The <span class="doxyComputerOutput">DIBuilder</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParentScope</td>
<td class="doxyParamItemDescription"><p>The parent scope containing this module declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>NameSpace name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Name</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExportSymbols</td>
<td class="doxyParamItemDescription"><p>Whether or not the namespace exports symbols, e.g. this is true of C++ inline namespaces.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateNullPtrType() {#gac54583c434a27a5a1cc2f1a64f1abd6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateNullPtrType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create C++11 nullptr type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 912 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1503 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateObjCIVar() {#ga00f6a1630b3771db5c911f99a4f8dca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateObjCIVar (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> PropertyNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for Objective-C instance variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Name</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OffsetInBits</td>
<td class="doxyParamItemDescription"><p>Member offset.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Parent type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PropertyNode</td>
<td class="doxyParamItemDescription"><p>Property associated with this ivar.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1408 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateObjCProperty() {#ga9cbf85a105f1c34719076b29b0830a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateObjCProperty (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * GetterName, size_t GetterNameLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SetterName, size_t SetterNameLen, unsigned PropertyAttributes, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for Objective-C property.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Property name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Name</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this property is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GetterName</td>
<td class="doxyParamItemDescription"><p>Name of the Objective C property getter selector.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GetterNameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">GetterName</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SetterName</td>
<td class="doxyParamItemDescription"><p>Name of the Objective C property setter selector.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SetterNameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">SetterName</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PropertyAttributes</td>
<td class="doxyParamItemDescription"><p>Objective C property attributes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateObjectPointerType() {#ga20ed80a8dd7b49ba6fcdd9d3d2ac20e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateObjectPointerType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Type, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> Implicit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a uniqued DIType* clone with FlagObjectPointer.</p>


<p>If <span class="doxyComputerOutput">Implicit</span> is true, then also set FlagArtificial.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Type</td>
<td class="doxyParamItemDescription"><p>The underlying type to which this pointer points.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Implicit</td>
<td class="doxyParamItemDescription"><p>Indicates whether this pointer was implicitly generated (i.e., not spelled out in source).</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1435 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateParameterVariable() {#ga9390bbfb5a8ea9b429b6086a6fcf957a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateParameterVariable (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, unsigned ArgNo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> AlwaysPreserve, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for a function parameter variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The local scope the variable is declared in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Variable name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of variable name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ArgNo</td>
<td class="doxyParamItemDescription"><p>Unique argument number for this variable; starts at 1.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this variable is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Metadata describing the type of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlwaysPreserve</td>
<td class="doxyParamItemDescription"><p>If true, this descriptor will survive optimizations.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1379 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1762 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreatePointerType() {#gafa96c20ff0708be1cabd2c06c9ce03ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreatePointerType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> PointeeTy, uint64_t SizeInBits, uint32_t AlignInBits, unsigned AddressSpace, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a pointer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PointeeTy</td>
<td class="doxyParamItemDescription"><p>Type pointed by this pointer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment. (optional, pass 0 to ignore)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AddressSpace</td>
<td class="doxyParamItemDescription"><p>DWARF address space. (optional, pass 0 to ignore)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Pointer type name. (optional)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of pointer type name. (optional)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1355 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateQualifiedType() {#ga8780f2c20339b37b01f8878401f27d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateQualifiedType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, unsigned Tag, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a qualified type, e.g.</p>


<p>'const int'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tag</td>
<td class="doxyParamItemDescription"><p>Tag identifying type, e.g. LLVMDWARFTypeQualifier_volatile_type</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Type</td>
<td class="doxyParamItemDescription"><p>Base Type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1489 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateReferenceType() {#ga3a2899f83e586e884e2c75811d911742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateReferenceType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, unsigned Tag, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a c++ style reference or rvalue reference type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tag</td>
<td class="doxyParamItemDescription"><p>Tag identifying type,</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Type</td>
<td class="doxyParamItemDescription"><p>Base Type.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1496 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateReplaceableCompositeType() {#gadcfce4b4d1ca9e120e479b56f24378d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateReplaceableCompositeType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, unsigned Tag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned Line, unsigned RuntimeLang, uint64_t SizeInBits, uint32_t AlignInBits, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * UniqueIdentifier, size_t UniqueIdentifierLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a temporary forward-declared type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tag</td>
<td class="doxyParamItemDescription"><p>A unique tag for this type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Type name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of type name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Type scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Line number where this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RuntimeLang</td>
<td class="doxyParamItemDescription"><p>Indicates runtime version for languages like Objective-C.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifier</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdentifierLen</td>
<td class="doxyParamItemDescription"><p>Length of the unique identifier.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1475 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateStaticMemberType() {#ga7c8d150bba12a1d9874e3d692fd804f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateStaticMemberType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNumber, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Type, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> ConstantVal, uint32_t AlignInBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a C++ static data member.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Member scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of member name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is declared.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Type</td>
<td class="doxyParamItemDescription"><p>Type of the static member.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ConstantVal</td>
<td class="doxyParamItemDescription"><p>Const initializer of the member.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1396 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateStructType() {#gaf293a26d4fd886befce34f6ce2a3bdf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateStructType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DerivedFrom, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Elements, unsigned NumElements, unsigned RunTimeLang, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> VTableHolder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * UniqueId, size_t UniqueIdLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a struct.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this struct is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Struct name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Struct name length.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Struct elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of struct elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RunTimeLang</td>
<td class="doxyParamItemDescription"><p>Optional parameter, Objective-C runtime version.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VTableHolder</td>
<td class="doxyParamItemDescription"><p>The object containing the vtable for the struct.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueId</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the struct.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdLen</td>
<td class="doxyParamItemDescription"><p>Length of the unique identifier for the struct.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 762 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1364 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateSubroutineType() {#ga96266a67a61ce67e77498296bbae2551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateSubroutineType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * ParameterTypes, unsigned NumParameterTypes, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create subroutine type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>The file in which the subroutine resides.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParameterTypes</td>
<td class="doxyParamItemDescription"><p>An array of subroutine parameter types. This includes return type at 0th index.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumParameterTypes</td>
<td class="doxyParamItemDescription"><p>The number of parameter types in <span class="doxyComputerOutput">ParameterTypes</span></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>E.g.: <span class="doxyComputerOutput">LLVMDIFlagLValueReference</span>. These flags are used to emit dwarf attributes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1599 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateTempGlobalVariableFwdDecl() {#ga862c55fb3e10df7538c7883a948df025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateTempGlobalVariableFwdDecl (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Linkage, size_t LnkLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a> LocalToUnit, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Decl, uint32_t AlignInBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new descriptor for the specified global variable that is temporary and meant to be RAUWed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Variable scope.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Name</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Linkage</td>
<td class="doxyParamItemDescription"><p>Mangled name of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LnkLen</td>
<td class="doxyParamItemDescription"><p>The length of the C string passed to <span class="doxyComputerOutput">Linkage</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this variable is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Variable Type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LocalToUnit</td>
<td class="doxyParamItemDescription"><p>Boolean flag indicate whether this variable is externally visible or not.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Decl</td>
<td class="doxyParamItemDescription"><p>Reference to the corresponding declaration.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Variable alignment(or 0 if no alignment attr was
                   specified)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1672 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilfinalizelinkage-cpp/#ae721973516c2b86042a5127b776e2806">Linkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateTempMacroFile() {#ga4f1086f983fe945bf4377c392ed87f4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateTempMacroFile (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> ParentMacroFile, unsigned Line, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information temporary entry for a macro file.</p>


<p>List of macro node direct children will be calculated by DIBuilder, using the <span class="doxyComputerOutput">ParentMacroFile</span> relationship.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParentMacroFile</td>
<td class="doxyParamItemDescription"><p>Macro parent (could be NULL).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Line</td>
<td class="doxyParamItemDescription"><p>Source line number where the macro file is included.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File descriptor containing the name of the macro file.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1281 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateTypedef() {#gaf237e3bbfe69ee176ae2bf8db9079346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateTypedef (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Type, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, uint32_t AlignInBits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a typedef.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Type</td>
<td class="doxyParamItemDescription"><p>Original type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Typedef name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this type is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNo</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The surrounding context for the typedef.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 924 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1443 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateUnionType() {#ga90500ff94794b86be3dd73f6d6f3a8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateUnionType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned LineNumber, uint64_t SizeInBits, uint32_t AlignInBits, <a href="#ga63e7a3126853c894baa1de14336a95dd">LLVMDIFlags</a> Flags, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Elements, unsigned NumElements, unsigned RunTimeLang, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * UniqueId, size_t UniqueIdLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a union.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>Scope in which this union is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Union name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of union name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>File where this member is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LineNumber</td>
<td class="doxyParamItemDescription"><p>Line number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SizeInBits</td>
<td class="doxyParamItemDescription"><p>Member size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Member alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>Flags to encode member attribute, e.g. private</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Union elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of union elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RunTimeLang</td>
<td class="doxyParamItemDescription"><p>Optional parameter, Objective-C runtime version.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueId</td>
<td class="doxyParamItemDescription"><p>A unique identifier for the union.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UniqueIdLen</td>
<td class="doxyParamItemDescription"><p>Length of unique identifier.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a801c923f0e508c12c7c76544bd5b790c">map_from_llvmDIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateUnspecifiedType() {#ga280cc8b0ba12ddba27a70640961d5aae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateUnspecifiedType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, size_t NameLen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a DWARF unspecified type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The unspecified type's name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLen</td>
<td class="doxyParamItemDescription"><p>Length of type name.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1391 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderCreateVectorType() {#ga5a3fc221b7877d1efe4e10fe6d586a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderCreateVectorType (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, uint64_t Size, uint32_t AlignInBits, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Ty, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Subscripts, unsigned NumSubscripts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create debugging information entry for a vector type.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Vector size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignInBits</td>
<td class="doxyParamItemDescription"><p>Alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p>Element type.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Subscripts</td>
<td class="doxyParamItemDescription"><p>Subscripts.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumSubscripts</td>
<td class="doxyParamItemDescription"><p>Number of subscripts.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderFinalize() {#ga2137b1dffc60225e2d26756f299a2223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDIBuilderFinalize (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct any deferred debug info descriptors.</p>

<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1077 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDIBuilderFinalizeSubprogram() {#gabc75effdb1e1cc44b4393c7716e7f5d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDIBuilderFinalizeSubprogram (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Subprogram)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize a specific subprogram.</p>


<p>No new variables may be added to this subprogram afterwards.</p>


<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDIBuilderGetOrCreateArray() {#ga07712e5d4d664c623674c09e03c9c011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderGetOrCreateArray (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Data, size_t NumElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an array of DI Nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The DI <a href="/web-llvm/docs/api/classes/node">Node</a> elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of DI <a href="/web-llvm/docs/api/classes/node">Node</a> elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1121 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1777 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderGetOrCreateSubrange() {#ga45454a88af46c21af848f5f95db5795c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderGetOrCreateSubrange (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, int64_t LowerBound, int64_t Count)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a descriptor for a value range.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LowerBound</td>
<td class="doxyParamItemDescription"><p>Lower bound of the subrange, e.g. 0 for C, 1 for Fortran.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Count</td>
<td class="doxyParamItemDescription"><p>Count of elements in the subrange.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1111 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1772 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderGetOrCreateTypeArray() {#gadbd363bcd72a98cc8225b11a0ea0f6fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIBuilderGetOrCreateTypeArray (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Data, size_t NumElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a type array.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The type elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of type elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1591 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderInsertDbgValueRecordAtEnd() {#gab976691ac79d65d9ff429b3c5a8f587a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDbgRecordRef LLVMDIBuilderInsertDbgValueRecordAtEnd (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> VarInfo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Expr, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DebugLoc, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true).</p>


<p>See <a href="https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes">https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes</a></p>


<p>The debug format can be switched later after inserting the records using LLVMSetIsNewDbgInfoFormat, if needed for legacy or transitionary reasons.</p>


<p>Insert a new debug record at the end of the given basic block. If the basic block has a terminator instruction, the record is inserted before that terminator instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Val</td>
<td class="doxyParamItemDescription"><p>The value of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VarInfo</td>
<td class="doxyParamItemDescription"><p>The variable's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>A complex location expression for the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugLoc</td>
<td class="doxyParamItemDescription"><p>Debug info location.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Block</td>
<td class="doxyParamItemDescription"><p>Basic block acting as a location for the new record.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1344 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1735 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderInsertDbgValueRecordBefore() {#gad502913d5fbb1891c256136560488409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDbgRecordRef LLVMDIBuilderInsertDbgValueRecordBefore (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> VarInfo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Expr, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DebugLoc, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true).</p>


<p>See <a href="https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes">https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes</a></p>


<p>The debug format can be switched later after inserting the records using LLVMSetIsNewDbgInfoFormat, if needed for legacy or transitionary reasons.</p>


<p>Insert a new debug record before the given instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Val</td>
<td class="doxyParamItemDescription"><p>The value of the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VarInfo</td>
<td class="doxyParamItemDescription"><p>The variable's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>A complex location expression for the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugLoc</td>
<td class="doxyParamItemDescription"><p>Debug info location.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Instr</td>
<td class="doxyParamItemDescription"><p>Instruction acting as a location for the new record.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1323 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1717 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderInsertDeclareRecordAtEnd() {#ga17213bad234b832c6447b97ce0a1cdfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDbgRecordRef LLVMDIBuilderInsertDeclareRecordAtEnd (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Storage, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> VarInfo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Expr, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DebugLoc, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true).</p>


<p>See <a href="https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes">https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes</a></p>


<p>The debug format can be switched later after inserting the records using LLVMSetIsNewDbgInfoFormat, if needed for legacy or transitionary reasons.</p>


<p>Insert a Declare DbgRecord at the end of the given basic block. If the basic block has a terminator instruction, the record is inserted before that terminator instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Storage</td>
<td class="doxyParamItemDescription"><p>The storage of the variable to declare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VarInfo</td>
<td class="doxyParamItemDescription"><p>The variable's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>A complex location expression for the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugLoc</td>
<td class="doxyParamItemDescription"><p>Debug info location.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Block</td>
<td class="doxyParamItemDescription"><p>Basic block acting as a location for the new record.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1304 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderInsertDeclareRecordBefore() {#gacac753a410ba2c99ab8de5a5bb6275aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDbgRecordRef LLVMDIBuilderInsertDeclareRecordBefore (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Storage, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> VarInfo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Expr, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DebugLoc, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Instr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Only use in "new debug format" (<a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga1adb5d14471960646da56e130c6a0f84">LLVMIsNewDbgInfoFormat()</a> is true).</p>


<p>See <a href="https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes">https://llvm.org/docs/RemoveDIsDebugInfo.html#c-api-changes</a></p>


<p>The debug format can be switched later after inserting the records using LLVMSetIsNewDbgInfoFormat, if needed for legacy or transitionary reasons.</p>


<p>Insert a Declare DbgRecord before the given instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Storage</td>
<td class="doxyParamItemDescription"><p>The storage of the variable to declare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VarInfo</td>
<td class="doxyParamItemDescription"><p>The variable's debug info descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>A complex location expression for the variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DebugLoc</td>
<td class="doxyParamItemDescription"><p>Debug info location.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Instr</td>
<td class="doxyParamItemDescription"><p>Instruction acting as a location for the new record.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1283 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1683 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderInsertLabelAtEnd() {#gab176ba6b04ac20f7363e3f2315dd7545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDbgRecordRef LLVMDIBuilderInsertLabelAtEnd (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> LabelInfo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Location, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> InsertAtEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new llvm.dbg.label intrinsic call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LabelInfo</td>
<td class="doxyParamItemDescription"><p>The Label's debug info descriptor</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Location</td>
<td class="doxyParamItemDescription"><p>The debug info location</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsertAtEnd</td>
<td class="doxyParamItemDescription"><p>Location for the new intrinsic.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adb6aff41bfe64d206d563112993cfb01">llvm::DIBuilder::insertLabel()</a></p></dd>
</dl>


<p>Declaration at line 1464 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1836 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIBuilderInsertLabelBefore() {#gace19cbd43c471a934793ba8f66ec16ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDbgRecordRef LLVMDIBuilderInsertLabelBefore (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> LabelInfo, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Location, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a new llvm.dbg.label intrinsic call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Builder</td>
<td class="doxyParamItemDescription"><p>The DIBuilder.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LabelInfo</td>
<td class="doxyParamItemDescription"><p>The Label's debug info descriptor</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Location</td>
<td class="doxyParamItemDescription"><p>The debug info location</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InsertBefore</td>
<td class="doxyParamItemDescription"><p>Location for the new intrinsic.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adb6aff41bfe64d206d563112993cfb01">llvm::DIBuilder::insertLabel()</a></p></dd>
</dl>


<p>Declaration at line 1450 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1817 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIFileGetDirectory() {#ga6d217da95423a5058437b10d48eb299c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMDIFileGetDirectory (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the directory of a given file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>The file object.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>The length of the returned string.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIFile::getDirectory()</p></dd>
</dl>


<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDIFileGetFilename() {#ga7080e9914e8708451283d10b69cc8edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMDIFileGetFilename (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the name of a given file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>The file object.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>The length of the returned string.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIFile::getFilename()</p></dd>
</dl>


<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDIFileGetSource() {#gae0a790e33f02c87d24b428da4d2b34ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMDIFileGetSource (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> File, unsigned * Len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the source of a given file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>The file object.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Len</td>
<td class="doxyParamItemDescription"><p>The length of the returned string.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIFile::getSource()</p></dd>
</dl>


<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDIGlobalVariableExpressionGetExpression() {#ga2d889441ac9541119cc05b65b178bcfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIGlobalVariableExpressionGetExpression (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> GVE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieves the <span class="doxyComputerOutput">DIExpression</span> associated with this global variable expression.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">GVE</td>
<td class="doxyParamItemDescription"><p>The global variable expression.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression/#ab32124e3d6178d6400abddd1213d1a11">llvm::DIGlobalVariableExpression::getExpression()</a></p></dd>
</dl>


<p>Declaration at line 1190 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1638 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIGlobalVariableExpressionGetVariable() {#ga1b9b6964e6643fc8cd61ea5b7a447ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIGlobalVariableExpressionGetVariable (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> GVE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieves the <span class="doxyComputerOutput">DIVariable</span> associated with this global variable expression.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">GVE</td>
<td class="doxyParamItemDescription"><p>The global variable expression.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression/#a851cb19a145f869f342ebb0efbe9abdd">llvm::DIGlobalVariableExpression::getVariable()</a></p></dd>
</dl>


<p>Declaration at line 1182 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1634 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDILocationGetColumn() {#ga5d3f8954443857acd2f3e63e924af5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMDILocationGetColumn (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the column number of this debug location.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Location</td>
<td class="doxyParamItemDescription"><p>The debug location.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DILocation::getColumn()</p></dd>
</dl>


<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDILocationGetInlinedAt() {#ga02154723977a1df274e6dd6cab1b3c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDILocationGetInlinedAt (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the "inline at" location associated with this debug location.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Location</td>
<td class="doxyParamItemDescription"><p>The debug location.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DILocation::getInlinedAt()</p></dd>
</dl>


<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDILocationGetLine() {#gac367fff632214b9cb6a7c72a560c6375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMDILocationGetLine (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the line number of this debug location.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Location</td>
<td class="doxyParamItemDescription"><p>The debug location.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DILocation::getLine()</p></dd>
</dl>


<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDILocationGetScope() {#ga4b79e6d86d287cbd5a2bad9d890d0cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDILocationGetScope (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Location)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the local scope associated with this debug location.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Location</td>
<td class="doxyParamItemDescription"><p>The debug location.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DILocation::getScope()</p></dd>
</dl>


<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1235 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIScopeGetFile() {#gabb1ada7b7f03079b1a3fc26d45a872c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIScopeGetFile (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Scope)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the metadata of the file associated with a given scope.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Scope</td>
<td class="doxyParamItemDescription"><p>The scope object.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIScope::getFile()</p></dd>
</dl>


<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1243 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDisposeDIBuilder() {#gaf36ccab6f24f7aa2fab88270756bf952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeDIBuilder (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gae7276221889549b4cf3b3f2297a8333e">LLVMDIBuilderRef</a> Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deallocates the <span class="doxyComputerOutput">DIBuilder</span> and everything it owns.</p>



:::info
<p>You must call <span class="doxyComputerOutput">LLVMDIBuilderFinalize</span> before this</p>
:::


<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMDisposeTemporaryMDNode() {#ga488dddd6a44fa6154d5520c2a76cab41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeTemporaryMDNode (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> TempNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deallocate a temporary node.</p>


<p>Calls <span class="doxyComputerOutput">replaceAllUsesWith(nullptr)</span> before deleting, so any remaining references will be reset.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TempNode</td>
<td class="doxyParamItemDescription"><p>The temporary metadata node.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1235 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1661 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a35e99dcd42831a0c100d6eed535eae23">llvm::MDNode::deleteTemporary</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDISubprogramGetLine() {#ga233c8c86bdfa0ceaad5ddbbb5d50fa1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMDISubprogramGetLine (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Subprogram)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the line associated with a given subprogram.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Subprogram</td>
<td class="doxyParamItemDescription"><p>The subprogram object.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DISubprogram::getLine()</p></dd>
</dl>


<p>Declaration at line 1404 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1792 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDITypeGetAlignInBits() {#ga2c1ae3a9365c49a64025df8a64086c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMDITypeGetAlignInBits (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the alignment of this DIType in bits.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DType</td>
<td class="doxyParamItemDescription"><p>The DIType.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIType::getAlignInBits()</p></dd>
</dl>


<p>Declaration at line 1087 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1579 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDITypeGetFlags() {#ga6bcea905cd35ad99a0d535721d8fe4ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDIFlags LLVMDITypeGetFlags (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the flags associated with this DIType.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DType</td>
<td class="doxyParamItemDescription"><p>The DIType.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIType::getFlags()</p></dd>
</dl>


<p>Declaration at line 1103 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1587 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#ac3f6763a7cdf20068a5eaae7373e91f7">map_to_llvmDIFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDITypeGetLine() {#ga780f4dfcebe39a69b115ae4f0d2b300f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMDITypeGetLine (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the source line where this DIType is declared.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DType</td>
<td class="doxyParamItemDescription"><p>The DIType.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIType::getLine()</p></dd>
</dl>


<p>Declaration at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1583 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDITypeGetName() {#gaef39844bc3df500ee733588158eae292}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMDITypeGetName (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DType, size_t * Length)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the name of this DIType.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DType</td>
<td class="doxyParamItemDescription"><p>The DIType.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Length</td>
<td class="doxyParamItemDescription"><p>The length of the returned string.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIType::getName()</p></dd>
</dl>


<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDITypeGetOffsetInBits() {#gae9747065099a9912fec575bd7edb7857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMDITypeGetOffsetInBits (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the offset of this DIType in bits.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DType</td>
<td class="doxyParamItemDescription"><p>The DIType.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIType::getOffsetInBits()</p></dd>
</dl>


<p>Declaration at line 1079 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1575 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDITypeGetSizeInBits() {#ga12af60f959285ba5ff8d568d27dda9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMDITypeGetSizeInBits (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> DType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the size of this DIType in bits.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DType</td>
<td class="doxyParamItemDescription"><p>The DIType.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIType::getSizeInBits()</p></dd>
</dl>


<p>Declaration at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1571 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDIVariableGetFile() {#ga7929e8886d3a6c8c121f17dcb2af1dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIVariableGetFile (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the metadata of the file associated with a given variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Var</td>
<td class="doxyParamItemDescription"><p>The variable object.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIVariable::getFile()</p></dd>
</dl>


<p>Declaration at line 1199 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1643 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDIVariableGetLine() {#gad19c6732705efa0c40e2bc0010632303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMDIVariableGetLine (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the source line where this <span class="doxyComputerOutput">DIVariable</span> is declared.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Var</td>
<td class="doxyParamItemDescription"><p>The DIVariable.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIVariable::getLine()</p></dd>
</dl>


<p>Declaration at line 1215 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1651 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMDIVariableGetScope() {#ga2ed3e2ec3f48e55ed167177139d5b14b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMDIVariableGetScope (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the metadata of the scope associated with a given variable.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Var</td>
<td class="doxyParamItemDescription"><p>The variable object.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>DIVariable::getScope()</p></dd>
</dl>


<p>Declaration at line 1207 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetDINodeTag() {#ga829c0e0a5fec733d28b736c072bec4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t LLVMGetDINodeTag (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the dwarf::Tag of a DINode.</p>

<p>Declaration at line 1174 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1561 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMGetMetadataKind() {#ga8794c88979fc63df9256714ddad96268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataKind LLVMGetMetadataKind (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Metadata)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the enumerated type of a Metadata instance.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID()</a></p></dd>
</dl>


<p>Declaration at line 1473 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1853 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="#gga0381ae5461ce8b139d33b6b4f4285bb7a00fe33697e8adfcbb9fc8349b504669e">LLVMGenericDINodeMetadataKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetModuleDebugMetadataVersion() {#ga75216df9fb21497235b8dc0da3f77cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMGetModuleDebugMetadataVersion (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> Module)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The version of debug metadata that's present in the provided <span class="doxyComputerOutput">Module</span>.</p>

<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1065 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a96bf50345388bc1f2d3727ac83477b05">llvm::getDebugMetadataVersionFromModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetSubprogram() {#gafddfbdaa9a85beba597ca456f2085251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMGetSubprogram (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the metadata of the subprogram attached to a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram()</a></p></dd>
</dl>


<p>Declaration at line 1389 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1784 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a859931f9f18bb9556861a9568be49d1e">getSubprogram</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMInstructionGetDebugLoc() {#ga2f2db17683a598ccfcfe8b0ad33f3040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMInstructionGetDebugLoc (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the debug location for the given instruction.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc()</a></p></dd>
</dl>


<p>Declaration at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1796 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstrbundle-cpp/#af44c9b089359803924e0b92bea3b6d03">getDebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMInstructionSetDebugLoc() {#ga50b4ca3bd1b86721e92ac6b411af63c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMInstructionSetDebugLoc (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Inst, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the debug location for the given instruction.</p>


<p>To clear the location metadata of the given instruction, pass NULL to <span class="doxyComputerOutput">Loc</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc()</a></p></dd>
</dl>


<p>Declaration at line 1420 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1800 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMMetadataReplaceAllUsesWith() {#ga704c67d1afa02bfe39cd02b4830c8f3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMMetadataReplaceAllUsesWith (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> TempTargetMetadata, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> Replacement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace all uses of temporary metadata.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TempTargetMetadata</td>
<td class="doxyParamItemDescription"><p>The temporary metadata node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Replacement</td>
<td class="doxyParamItemDescription"><p>The replacement metadata node.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1242 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1665 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a35e99dcd42831a0c100d6eed535eae23">llvm::MDNode::deleteTemporary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afa38484f37bc017c52d69457d3e6d2cf">unwrapDI</a>.</p>

</div>
</div>

### LLVMSetSubprogram() {#ga3fb4cb7331aa97b2bdd91044b5c33fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMSetSubprogram (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Func, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> SP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the subprogram attached to a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a05a19abc8ee11d5909275d980efa1670">llvm::Function::setSubprogram()</a></p></dd>
</dl>


<p>Declaration at line 1396 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1788 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMStripModuleDebugInfo() {#gac86aed2f5553740f151cb1905d4718ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMStripModuleDebugInfo (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> Module)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Strip debug info in the module if it exists.</p>


<p>To do this, we remove all calls to the debugger intrinsics and any named metadata for debugging. We also remove debug locations for instructions. Return true if module is modified.</p>


<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1069 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9b2f025559a0b80366b74285cf25c01e">llvm::StripDebugInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMTemporaryMDNode() {#ga68d0a34a31a878cc0452697bebf63e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMetadataRef LLVMTemporaryMDNode (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> Ctx, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab9f52d9777af781812e7bffdd491d01e">LLVMMetadataRef</a> * Data, size_t NumElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new temporary <span class="doxyComputerOutput">MDNode</span>.</p>


<p>Suitable for use in constructing cyclic <span class="doxyComputerOutput">MDNode</span> structures. A temporary <span class="doxyComputerOutput">MDNode</span> is not uniqued, may be RAUW'd, and must be manually deleted with <span class="doxyComputerOutput">LLVMDisposeTemporaryMDNode</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ctx</td>
<td class="doxyParamItemDescription"><p>The context in which to construct the temporary node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The metadata elements.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumElements</td>
<td class="doxyParamItemDescription"><p>Number of metadata elements.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1225 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/debuginfo-h">DebugInfo.h</a>, definition at line 1655 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#ac2e84f7e25af6e1de8cb811a57c6ee29">llvm::MDTuple::getTemporary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
