---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFLinkerImpl` Class Reference

<p>This class links debug info. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DWARFLinkerImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinker/Parallel/DWARFLinkerImpl.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinker">DWARFLinker</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StringDestinationKind : uint8_t { <a href="#a22541637e4c53e4b8498769b01fec8b4">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34523416baa5fa2100aa1f138a868300">DependencyTracker</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef75f38cdc5c7015fe251728c47c9d9">DWARFLinkerImpl</a> (MessageHandlerTy ErrorHandler, MessageHandlerTy WarningHandler)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab732f1d39ccd237bcf728ca5bb48ce14">addObjectFile</a> (DWARFFile &amp;File, ObjFileLoaderTy Loader=nullptr, CompileUnitHandlerTy OnCUDieLoaded=[](const DWARFUnit &amp;) {}) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add object file to be linked. <a href="#ab732f1d39ccd237bcf728ca5bb48ce14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42302ab883ef8ec7e51b00701d626ce4">link</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link debug info for added files. <a href="#a42302ab883ef8ec7e51b00701d626ce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9d371d27517ff11d4e9c7ccdf17a8e">setOutputDWARFHandler</a> (const Triple &amp;TargetTriple, SectionHandlerTy SectionHandler) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set output DWARF handler. <a href="#abb9d371d27517ff11d4e9c7ccdf17a8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga3353de162ad20f4b351ce8f7f20ed0cf">setVerbosity</a> (bool Verbose) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows to generate log of linking process to the standard output. <a href="/web-llvm/docs/api/groups/methods/#ga3353de162ad20f4b351ce8f7f20ed0cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#gaa6301620399ecf2b208db01a8684e685">setStatistics</a> (bool Statistics) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print statistics to standard output. <a href="/web-llvm/docs/api/groups/methods/#gaa6301620399ecf2b208db01a8684e685">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga8729af41da30f5c338b8978beacc95b1">setVerifyInputDWARF</a> (bool Verify) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the input DWARF. <a href="/web-llvm/docs/api/groups/methods/#ga8729af41da30f5c338b8978beacc95b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#gab184213d426e7f081daf5126d4be8d0c">setNoODR</a> (bool NoODR) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not unique types according to ODR. <a href="/web-llvm/docs/api/groups/methods/#gab184213d426e7f081daf5126d4be8d0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga8a80ebc00f7b521e86733924c74b607f">setUpdateIndexTablesOnly</a> (bool UpdateIndexTablesOnly) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update index tables <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a5782a8740ff1e91516b41b3726a3168c">only(do not modify rest of DWARF)</a>. <a href="/web-llvm/docs/api/groups/methods/#ga8a80ebc00f7b521e86733924c74b607f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga833ee700f8518d752a7b88225ed74996">setAllowNonDeterministicOutput</a> (bool AllowNonDeterministicOutput) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow generating valid, but non-deterministic output. <a href="/web-llvm/docs/api/groups/methods/#ga833ee700f8518d752a7b88225ed74996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga87f3f8572db8476d4613032daee7afb8">setKeepFunctionForStatic</a> (bool KeepFunctionForStatic) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to keep the enclosing function for a static variable. <a href="/web-llvm/docs/api/groups/methods/#ga87f3f8572db8476d4613032daee7afb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga1f6a1429f7ebe1cca2f2dd150a0e215b">setNumThreads</a> (unsigned NumThreads) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> specified number of threads for parallel files linking. <a href="/web-llvm/docs/api/groups/methods/#ga1f6a1429f7ebe1cca2f2dd150a0e215b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga447b8844a29e63edeb2f8f111f9d4ed9">addAccelTableKind</a> (AccelTableKind Kind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add kind of accelerator tables to be generated. <a href="/web-llvm/docs/api/groups/methods/#ga447b8844a29e63edeb2f8f111f9d4ed9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#gac3b0a6b8f7bcd351cd401bed2d17cb7c">setPrependPath</a> (StringRef Ppath) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set prepend path for clang modules. <a href="/web-llvm/docs/api/groups/methods/#gac3b0a6b8f7bcd351cd401bed2d17cb7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#gafe8baf0ba96e0cb88ec5dd7695a2986b">setEstimatedObjfilesAmount</a> (unsigned ObjFilesNum) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set estimated objects files amount, for preliminary data allocation. <a href="/web-llvm/docs/api/groups/methods/#gafe8baf0ba96e0cb88ec5dd7695a2986b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga372b14880235403f9e6558e8077d7bd7">setInputVerificationHandler</a> (InputVerificationHandlerTy Handler) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set verification handler which would be used to report verification errors. <a href="/web-llvm/docs/api/groups/methods/#ga372b14880235403f9e6558e8077d7bd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga8f0f5f298730862e2cbb1d40c00b1bd1">setSwiftInterfacesMap</a> (SwiftInterfacesMapTy *Map) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set map for Swift interfaces. <a href="/web-llvm/docs/api/groups/methods/#ga8f0f5f298730862e2cbb1d40c00b1bd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga3fbe10652ed6870909b2ca982f8ec921">setObjectPrefixMap</a> (ObjectPrefixMapTy *Map) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set prefix map for objects. <a href="/web-llvm/docs/api/groups/methods/#ga3fbe10652ed6870909b2ca982f8ec921">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Error</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga2814e2cc1c4cb63b8f5cf54f16c2d5f7">setTargetDWARFVersion</a> (uint16_t TargetDWARFVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set target DWARF version. <a href="/web-llvm/docs/api/groups/methods/#ga2814e2cc1c4cb63b8f5cf54f16c2d5f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a901080a7f2755abf0fc90c2d0d9da87f">verifyInput</a> (const DWARFFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify input DWARF file. <a href="#a901080a7f2755abf0fc90c2d0d9da87f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49eedb8f4407a04a750f0b63384f8217">validateAndUpdateOptions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Validate specified options. <a href="#a49eedb8f4407a04a750f0b63384f8217">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71330a23d2feee283a26bc08a32a412c">glueCompileUnitsAndWriteToTheOutput</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take already linked compile units and glue them into single file. <a href="#a71330a23d2feee283a26bc08a32a412c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d82740af65d76898c3580c88ef460a">assignOffsets</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all compile units and assign offsets to their sections and strings. <a href="#a41d82740af65d76898c3580c88ef460a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a503780ae68db06781462184c877ba5ad">assignOffsetsToSections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all compile units and assign offsets to their sections. <a href="#a503780ae68db06781462184c877ba5ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8a25a460f1104b2e1128879d9173d9">assignOffsetsToStrings</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all compile units and assign offsets to their strings. <a href="#a3c8a25a460f1104b2e1128879d9173d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557d8187b93bd54d7263d4755c5e99e5">printStatistic</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print statistic for processed Debug Info. <a href="#a557d8187b93bd54d7263d4755c5e99e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba93286151b2e53982f5e74695b42a24">forEachOutputString</a> (function_ref&lt; void(StringDestinationKind, const StringEntry *)&gt; StringHandler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates all strings. <a href="#aba93286151b2e53982f5e74695b42a24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a8083cc3c516a879074fa43a7b70a51">forEachObjectSectionsSet</a> (function_ref&lt; void(OutputSections &amp;SectionsSet)&gt; SectionsSetHandler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates sections for modules, invariant for object files, compile units. <a href="#a1a8083cc3c516a879074fa43a7b70a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9582267f462865c7f0de3c9e9aed93b5">forEachCompileAndTypeUnit</a> (function_ref&lt; void(DwarfUnit *CU)&gt; UnitHandler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates all compile and type units. <a href="#a9582267f462865c7f0de3c9e9aed93b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392cf645fc5b9f664baf4a278c0cd5b3">forEachCompileUnit</a> (function_ref&lt; void(CompileUnit *CU)&gt; UnitHandler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates all comple units. <a href="#a392cf645fc5b9f664baf4a278c0cd5b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05462e5991a1325a9944da1b5d1d5b9">patchOffsetsAndSizes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates all patches and update them with the correct values. <a href="#af05462e5991a1325a9944da1b5d1d5b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c9b6d8ca3948e29ec1511b6037cdcf">emitCommonSectionsAndWriteCompileUnitsToTheOutput</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit debug sections common for all input files. <a href="#ac8c9b6d8ca3948e29ec1511b6037cdcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3ab4bc92e5a22d3ab1a70e63e04251">emitAppleAcceleratorSections</a> (const Triple &amp;TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit apple accelerator sections. <a href="#a7c3ab4bc92e5a22d3ab1a70e63e04251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267b3ad88431cb638221b36a45f7600f">emitDWARFv5DebugNamesSection</a> (const Triple &amp;TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_names section. <a href="#a267b3ad88431cb638221b36a45f7600f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d569b5d160f74ec5712bf4c3be31c60">emitStringSections</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit string sections. <a href="#a9d569b5d160f74ec5712bf4c3be31c60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba43fbeec79fbb09310fc06354a9f74a">cleanupDataAfterDWARFOutputIsWritten</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cleanup <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data(string pools)</a> after output sections are generated. <a href="#aba43fbeec79fbb09310fc06354a9f74a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4feb28330f8c865244bec30383d1a9">writeCompileUnitsToTheOutput</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all compile units and put their data into the output stream. <a href="#a2e4feb28330f8c865244bec30383d1a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5b872efe54c2815cd80e6f96280e0b">writeCommonSectionsToTheOutput</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate common sections and put their data into the output stream. <a href="#a4b5b872efe54c2815cd80e6f96280e0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga33e8e6d22f8dc53ca6e43b03464cb669">UniqueUnitID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for compile unit. <a href="/web-llvm/docs/api/groups/data/#ga33e8e6d22f8dc53ca6e43b03464cb669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">StringMap&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#gaee4878daad7f1fae48bef91eaf49685f">ClangModules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping the PCM filename to the DwoId. <a href="/web-llvm/docs/api/groups/data/#gaee4878daad7f1fae48bef91eaf49685f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#gab1d3ac01513e2f54ae9a9d98f4141ee2">ClangModulesMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; TypeUnit &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">ArtificialTypeUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> unit. <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LinkingGlobalData</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">StringEntryToDwarfStringPoolEntryMap</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DwarfStringPoolEntries for .debug_str section. <a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">StringEntryToDwarfStringPoolEntryMap</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga6990299c0e834de5dff8181b883da306">DebugLineStrStrings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DwarfStringPoolEntries for .debug_line_str section. <a href="/web-llvm/docs/api/groups/data/#ga6990299c0e834de5dff8181b883da306">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SmallVector&lt; std::unique_ptr&lt; LinkContext &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">ObjectContexts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps all linking contexts. <a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">OutputSections</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">CommonSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common sections. <a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SectionHandlerTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga7a05179a9b937ed748b2048984414169">SectionHandler</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hanler for output sections. <a href="/web-llvm/docs/api/groups/data/#ga7a05179a9b937ed748b2048984414169">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/data/#ga51eaaa95c9ad291f71a711dea6bedfb4">OverallNumberOfCU</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overall compile units number. <a href="/web-llvm/docs/api/groups/data/#ga51eaaa95c9ad291f71a711dea6bedfb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class links debug info.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### StringDestinationKind {#a22541637e4c53e4b8498769b01fec8b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::dwarf_linker::parallel::DWARFLinkerImpl::StringDestinationKind : uint8_t</td>
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


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DebugStr<a id="a22541637e4c53e4b8498769b01fec8b4a65685728791963bdf24b429a5a686d2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DebugLineStr<a id="a22541637e4c53e4b8498769b01fec8b4aa9750e7d55675f2f78eaa9b93848dff4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DependencyTracker {#a34523416baa5fa2100aa1f138a868300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker">DependencyTracker</a></td>
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


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="#a34523416baa5fa2100aa1f138a868300">DependencyTracker</a>.</p>


<p>Referenced by <a href="#a34523416baa5fa2100aa1f138a868300">DependencyTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFLinkerImpl() {#aaef75f38cdc5c7015fe251728c47c9d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFLinkerImpl::DWARFLinkerImpl (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> ErrorHandler, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> WarningHandler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">CommonSections</a>, <a href="/web-llvm/docs/api/groups/data/#ga6990299c0e834de5dff8181b883da306">DebugLineStrStrings</a>, <a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp/#a170a641ca785d873866fb901dfcb7591">ErrorHandler</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a> and <a href="/web-llvm/docs/api/groups/data/#ga33e8e6d22f8dc53ca6e43b03464cb669">UniqueUnitID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addObjectFile() {#ab732f1d39ccd237bcf728ca5bb48ce14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::addObjectFile (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#abdf3094623b3752dabeeb5bd7ceb24ad">ObjFileLoaderTy</a> Loader=nullptr, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a537122974e714f93e8ad5fa29439e856">CompileUnitHandlerTy</a> OnCUDieLoaded=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp;) {})</td>
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

<p>Add object file to be linked.</p>


<p>Pre-load compile unit die. Call <span class="doxyComputerOutput">OnCUDieLoaded</span> for each compile unit die. If specified <span class="doxyComputerOutput">File</span> has reference to the Clang module then such module would be pre-loaded by <span class="doxyComputerOutput">Loader</span> for !Update case.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>NoODR, Update options should be set before call to addObjectFile.</p></dd>
</dl>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#gaee4878daad7f1fae48bef91eaf49685f">ClangModules</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a>, <a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">ObjectContexts</a>, <a href="/web-llvm/docs/api/groups/data/#ga51eaaa95c9ad291f71a711dea6bedfb4">OverallNumberOfCU</a> and <a href="/web-llvm/docs/api/groups/data/#ga33e8e6d22f8dc53ca6e43b03464cb669">UniqueUnitID</a>.</p>

</div>
</div>

### link() {#a42302ab883ef8ec7e51b00701d626ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFLinkerImpl::link ()</td>
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

<p>Link debug info for added files.</p>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a6892519cfb3ec739ebd611d7bd82ea2e">llvm::dwarf::FormParams::AddrSize</a>, <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">ArtificialTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface/#ad43d0052f680e6ac08426d8821df178d">llvm::ThreadPoolInterface::async</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#ae396b319b15cbecf51ec8dc4ee2719b0">llvm::DIDumpOptions::ChildRecurseDepth</a>, <a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">CommonSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a>, <a href="#a71330a23d2feee283a26bc08a32a412c">glueCompileUnitsAndWriteToTheOutput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00440f10281348fd9f7be52e23c7c874">llvm::hardware_concurrency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#a1780893d4361a1d80fbc26a6e38ded70">llvm::dwarf_linker::parallel::isODRLanguage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::native</a>, <a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">ObjectContexts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a879dd68b6ab547079c3ef8b7a7e39277">llvm::optimal_concurrency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/groups/data/#ga51eaaa95c9ad291f71a711dea6bedfb4">OverallNumberOfCU</a>, <a href="/web-llvm/docs/api/classes/llvm/parallel/taskgroup/#a5f936d7e589b0615fccac0a4c0cb8d97">llvm::parallel::TaskGroup::spawn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a68f04a4e2c26fa6b9cd7517dced50729">llvm::parallel::strategy</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>, <a href="/web-llvm/docs/api/groups/data/#ga33e8e6d22f8dc53ca6e43b03464cb669">UniqueUnitID</a>, <a href="#a49eedb8f4407a04a750f0b63384f8217">validateAndUpdateOptions</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>, <a href="#a901080a7f2755abf0fc90c2d0d9da87f">verifyInput</a> and <a href="/web-llvm/docs/api/classes/llvm/singlethreadexecutor/#a4a9fc38bb7d9ff3f944e25971330cb42">llvm::SingleThreadExecutor::wait</a>.</p>

</div>
</div>

### setOutputDWARFHandler() {#abb9d371d27517ff11d4e9c7ccdf17a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setOutputDWARFHandler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#a6f049fdf3c9f69b0817f13b00ce1140a">SectionHandlerTy</a> SectionHandler)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set output DWARF handler.</p>


<p>May be not set if output generation is not necessary.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a> and <a href="/web-llvm/docs/api/groups/data/#ga7a05179a9b937ed748b2048984414169">SectionHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### assignOffsets() {#a41d82740af65d76898c3580c88ef460a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::assignOffsets ()</td>
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

<p>Enumerate all compile units and assign offsets to their sections and strings.</p>

<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="#a503780ae68db06781462184c877ba5ad">assignOffsetsToSections</a>, <a href="#a3c8a25a460f1104b2e1128879d9173d9">assignOffsetsToStrings</a> and <a href="/web-llvm/docs/api/classes/llvm/parallel/taskgroup/#a5f936d7e589b0615fccac0a4c0cb8d97">llvm::parallel::TaskGroup::spawn</a>.</p>


<p>Referenced by <a href="#a71330a23d2feee283a26bc08a32a412c">glueCompileUnitsAndWriteToTheOutput</a>.</p>

</div>
</div>

### assignOffsetsToSections() {#a503780ae68db06781462184c877ba5ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::assignOffsetsToSections ()</td>
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

<p>Enumerate all compile units and assign offsets to their sections.</p>

<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 989 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#abf76888e84a79bf369b5b06117b6a814">llvm::dwarf_linker::parallel::OutputSections::assignSectionsOffsetAndAccumulateSize</a> and <a href="#a1a8083cc3c516a879074fa43a7b70a51">forEachObjectSectionsSet</a>.</p>


<p>Referenced by <a href="#a41d82740af65d76898c3580c88ef460a">assignOffsets</a>.</p>

</div>
</div>

### assignOffsetsToStrings() {#a3c8a25a460f1104b2e1128879d9173d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::assignOffsetsToStrings ()</td>
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

<p>Enumerate all compile units and assign offsets to their strings.</p>

<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a22541637e4c53e4b8498769b01fec8b4aa9750e7d55675f2f78eaa9b93848dff4">DebugLineStr</a>, <a href="/web-llvm/docs/api/groups/data/#ga6990299c0e834de5dff8181b883da306">DebugLineStrStrings</a>, <a href="#a22541637e4c53e4b8498769b01fec8b4a65685728791963bdf24b429a5a686d2d">DebugStr</a>, <a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a>, <a href="#aba93286151b2e53982f5e74695b42a24">forEachOutputString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="#a41d82740af65d76898c3580c88ef460a">assignOffsets</a>.</p>

</div>
</div>

### cleanupDataAfterDWARFOutputIsWritten() {#aba43fbeec79fbb09310fc06354a9f74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::cleanupDataAfterDWARFOutputIsWritten ()</td>
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

<p>Cleanup <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data(string pools)</a> after output sections are generated.</p>

<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga6990299c0e834de5dff8181b883da306">DebugLineStrStrings</a>, <a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a> and <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a>.</p>


<p>Referenced by <a href="#a71330a23d2feee283a26bc08a32a412c">glueCompileUnitsAndWriteToTheOutput</a>.</p>

</div>
</div>

### emitAppleAcceleratorSections() {#a7c3ab4bc92e5a22d3ab1a70e63e04251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::emitAppleAcceleratorSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
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

<p>Emit apple accelerator sections.</p>

<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1210 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a4b28d128dbdad12e4407e5632cefdb19">llvm::dwarf_linker::AppleNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a99af17d0ec1a04c04d4f1d5813abac1a">llvm::dwarf_linker::AppleNamespaces</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a7d5ee33d695df637fdd33d81513c6ac2">llvm::dwarf_linker::AppleObjC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a0ecb25f167d49c0869bea3f18310fe88">llvm::dwarf_linker::AppleTypes</a>, <a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">CommonSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#addd759aec534bc0671ea60c8e9779e5da5209d785d6f9540a65239398210353f9">llvm::dwarf::DW_FLAG_type_implementation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="#a9582267f462865c7f0de3c9e9aed93b5">forEachCompileAndTypeUnit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a49ee3087348e8d44e1feda1917443987">llvm::dwarf_linker::parallel::DwarfUnit::Name</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491ab3ba0fe968ce39dcfc6fe8cc0f1b02da">llvm::dwarf_linker::parallel::DwarfUnit::Namespace</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a6adf97f83acf6453d4a6a4b1070f3754">llvm::dwarf_linker::parallel::DwarfUnit::None</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491adebd6b4842117b405ba901644458b32c">llvm::dwarf_linker::parallel::DwarfUnit::ObjC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b">llvm::dwarf_linker::DWARFLinkerBase::Object</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a0756e89d8eafc4bc2503dd3976765f61">llvm::dwarf_linker::parallel::SectionDescriptor::setSizesForSectionCreatedByAsmPrinter</a> and <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491aa1fa27779242b4902f7ae3bdd5c6d508">llvm::dwarf_linker::parallel::DwarfUnit::Type</a>.</p>


<p>Referenced by <a href="#ac8c9b6d8ca3948e29ec1511b6037cdcf">emitCommonSectionsAndWriteCompileUnitsToTheOutput</a>.</p>

</div>
</div>

### emitCommonSectionsAndWriteCompileUnitsToTheOutput() {#ac8c9b6d8ca3948e29ec1511b6037cdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::emitCommonSectionsAndWriteCompileUnitsToTheOutput ()</td>
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

<p>Emit debug sections common for all input files.</p>

<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308a9f6290f4436e5a2351f12e03b6433c3c">llvm::dwarf_linker::DWARFLinkerBase::Apple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a4b28d128dbdad12e4407e5632cefdb19">llvm::dwarf_linker::AppleNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a99af17d0ec1a04c04d4f1d5813abac1a">llvm::dwarf_linker::AppleNamespaces</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a7d5ee33d695df637fdd33d81513c6ac2">llvm::dwarf_linker::AppleObjC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a0ecb25f167d49c0869bea3f18310fe88">llvm::dwarf_linker::AppleTypes</a>, <a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">CommonSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac627686806c4fab189ff691f8331f01e">llvm::dwarf_linker::DebugLineStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a20f18d4a28570b83b8f5bd6c9d26d7b8">llvm::dwarf_linker::DebugNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308a20f18d4a28570b83b8f5bd6c9d26d7b8">llvm::dwarf_linker::DWARFLinkerBase::DebugNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ad46cdbe68b494ca6f426b0ca5269f6a4">llvm::dwarf_linker::DebugStr</a>, <a href="#a7c3ab4bc92e5a22d3ab1a70e63e04251">emitAppleAcceleratorSections</a>, <a href="#a267b3ad88431cb638221b36a45f7600f">emitDWARFv5DebugNamesSection</a>, <a href="#a9d569b5d160f74ec5712bf4c3be31c60">emitStringSections</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/parallel/taskgroup/#a5f936d7e589b0615fccac0a4c0cb8d97">llvm::parallel::TaskGroup::spawn</a> and <a href="#a2e4feb28330f8c865244bec30383d1a9">writeCompileUnitsToTheOutput</a>.</p>


<p>Referenced by <a href="#a71330a23d2feee283a26bc08a32a412c">glueCompileUnitsAndWriteToTheOutput</a>.</p>

</div>
</div>

### emitDWARFv5DebugNamesSection() {#a267b3ad88431cb638221b36a45f7600f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::emitDWARFv5DebugNamesSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
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

<p>Emit .debug_names section.</p>

<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">CommonSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a20f18d4a28570b83b8f5bd6c9d26d7b8">llvm::dwarf_linker::DebugNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308a20f18d4a28570b83b8f5bd6c9d26d7b8">llvm::dwarf_linker::DWARFLinkerBase::DebugNames</a>, <a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="#a9582267f462865c7f0de3c9e9aed93b5">forEachCompileAndTypeUnit</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491a49ee3087348e8d44e1feda1917443987">llvm::dwarf_linker::parallel::DwarfUnit::Name</a>, <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491ab3ba0fe968ce39dcfc6fe8cc0f1b02da">llvm::dwarf_linker::parallel::DwarfUnit::Namespace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b">llvm::dwarf_linker::DWARFLinkerBase::Object</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a0756e89d8eafc4bc2503dd3976765f61">llvm::dwarf_linker::parallel::SectionDescriptor::setSizesForSectionCreatedByAsmPrinter</a> and <a href="/web-llvm/docs/api/groups/methods/#gga2c708209e1c0939d50f9e70bc5708491aa1fa27779242b4902f7ae3bdd5c6d508">llvm::dwarf_linker::parallel::DwarfUnit::Type</a>.</p>


<p>Referenced by <a href="#ac8c9b6d8ca3948e29ec1511b6037cdcf">emitCommonSectionsAndWriteCompileUnitsToTheOutput</a>.</p>

</div>
</div>

### emitStringSections() {#a9d569b5d160f74ec5712bf4c3be31c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::emitStringSections ()</td>
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

<p>Emit string sections.</p>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">CommonSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac627686806c4fab189ff691f8331f01e">llvm::dwarf_linker::DebugLineStr</a>, <a href="#a22541637e4c53e4b8498769b01fec8b4aa9750e7d55675f2f78eaa9b93848dff4">DebugLineStr</a>, <a href="/web-llvm/docs/api/groups/data/#ga6990299c0e834de5dff8181b883da306">DebugLineStrStrings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ad46cdbe68b494ca6f426b0ca5269f6a4">llvm::dwarf_linker::DebugStr</a>, <a href="#a22541637e4c53e4b8498769b01fec8b4a65685728791963bdf24b429a5a686d2d">DebugStr</a>, <a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a>, <a href="#aba93286151b2e53982f5e74695b42a24">forEachOutputString</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#a0f63507e2c65d915e897f80e1f121091">llvm::DwarfStringPoolEntry::isIndexed</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#aa406c884c8fb2d9b2fee2aa3865d832d">llvm::DwarfStringPoolEntry::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring/#ad9753ce2d5673ac4b4acd65ed68daa88">llvm::DwarfStringPoolEntryWithExtString::String</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="#ac8c9b6d8ca3948e29ec1511b6037cdcf">emitCommonSectionsAndWriteCompileUnitsToTheOutput</a>.</p>

</div>
</div>

### forEachCompileAndTypeUnit() {#a9582267f462865c7f0de3c9e9aed93b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::forEachCompileAndTypeUnit (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit">DwarfUnit</a> *CU)&gt; UnitHandler)</td>
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

<p>Enumerates all compile and type units.</p>

<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1073 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">ArtificialTypeUnit</a>, <a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">ObjectContexts</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883ad9c8f187972e6320a34e9c40b4cba605">llvm::dwarf_linker::parallel::CompileUnit::Skipped</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/refmoduleunit/#a9ed3724a2c9ce77f034408ef50cae6d5">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::RefModuleUnit::Unit</a>.</p>


<p>Referenced by <a href="#a7c3ab4bc92e5a22d3ab1a70e63e04251">emitAppleAcceleratorSections</a> and <a href="#a267b3ad88431cb638221b36a45f7600f">emitDWARFv5DebugNamesSection</a>.</p>

</div>
</div>

### forEachCompileUnit() {#a392cf645fc5b9f664baf4a278c0cd5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::forEachCompileUnit (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a> *CU)&gt; UnitHandler)</td>
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

<p>Enumerates all comple units.</p>

<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">ObjectContexts</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883ad9c8f187972e6320a34e9c40b4cba605">llvm::dwarf_linker::parallel::CompileUnit::Skipped</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/refmoduleunit/#a9ed3724a2c9ce77f034408ef50cae6d5">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::RefModuleUnit::Unit</a>.</p>


<p>Referenced by <a href="#aba93286151b2e53982f5e74695b42a24">forEachOutputString</a>.</p>

</div>
</div>

### forEachObjectSectionsSet() {#a1a8083cc3c516a879074fa43a7b70a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::forEachObjectSectionsSet (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections">OutputSections</a> &amp;SectionsSet)&gt; SectionsSetHandler)</td>
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

<p>Enumerates sections for modules, invariant for object files, compile units.</p>

<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">ArtificialTypeUnit</a>, <a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">ObjectContexts</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ac8f9de0c8d86b73c76368b681f0d7883ad9c8f187972e6320a34e9c40b4cba605">llvm::dwarf_linker::parallel::CompileUnit::Skipped</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/refmoduleunit/#a9ed3724a2c9ce77f034408ef50cae6d5">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::RefModuleUnit::Unit</a>.</p>


<p>Referenced by <a href="#a503780ae68db06781462184c877ba5ad">assignOffsetsToSections</a>, <a href="#af05462e5991a1325a9944da1b5d1d5b9">patchOffsetsAndSizes</a> and <a href="#a2e4feb28330f8c865244bec30383d1a9">writeCompileUnitsToTheOutput</a>.</p>

</div>
</div>

### forEachOutputString() {#aba93286151b2e53982f5e74695b42a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::forEachOutputString (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="#a22541637e4c53e4b8498769b01fec8b4">StringDestinationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> *)&gt; StringHandler)</td>
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

<p>Enumerates all strings.</p>

<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">ArtificialTypeUnit</a>, <a href="#a22541637e4c53e4b8498769b01fec8b4aa9750e7d55675f2f78eaa9b93848dff4">DebugLineStr</a>, <a href="#a22541637e4c53e4b8498769b01fec8b4a65685728791963bdf24b429a5a686d2d">DebugStr</a>, <a href="#a392cf645fc5b9f664baf4a278c0cd5b3">forEachCompileUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/debugstrpatch/#a879b5a35af86c2414da97bb10a132000">llvm::dwarf_linker::parallel::DebugStrPatch::String</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>


<p>Referenced by <a href="#a3c8a25a460f1104b2e1128879d9173d9">assignOffsetsToStrings</a> and <a href="#a9d569b5d160f74ec5712bf4c3be31c60">emitStringSections</a>.</p>

</div>
</div>

### glueCompileUnitsAndWriteToTheOutput() {#a71330a23d2feee283a26bc08a32a412c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::glueCompileUnitsAndWriteToTheOutput ()</td>
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

<p>Take already linked compile units and glue them into single file.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">ArtificialTypeUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a41d82740af65d76898c3580c88ef460a">assignOffsets</a>, <a href="#aba43fbeec79fbb09310fc06354a9f74a">cleanupDataAfterDWARFOutputIsWritten</a>, <a href="#ac8c9b6d8ca3948e29ec1511b6037cdcf">emitCommonSectionsAndWriteCompileUnitsToTheOutput</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a>, <a href="#af05462e5991a1325a9944da1b5d1d5b9">patchOffsetsAndSizes</a>, <a href="#a557d8187b93bd54d7263d4755c5e99e5">printStatistic</a>, <a href="/web-llvm/docs/api/groups/data/#ga7a05179a9b937ed748b2048984414169">SectionHandler</a> and <a href="#a4b5b872efe54c2815cd80e6f96280e0b">writeCommonSectionsToTheOutput</a>.</p>


<p>Referenced by <a href="#a42302ab883ef8ec7e51b00701d626ce4">link</a>.</p>

</div>
</div>

### patchOffsetsAndSizes() {#af05462e5991a1325a9944da1b5d1d5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::patchOffsetsAndSizes ()</td>
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

<p>Enumerates all patches and update them with the correct values.</p>

<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1106 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a09b5d1027676907c7bc194a865ffe0df">llvm::dwarf_linker::parallel::OutputSections::applyPatches</a>, <a href="/web-llvm/docs/api/groups/data/#ga83a3aaddca0607d7b14c89dcf9dd0ccd">ArtificialTypeUnit</a>, <a href="/web-llvm/docs/api/groups/data/#ga6990299c0e834de5dff8181b883da306">DebugLineStrStrings</a>, <a href="/web-llvm/docs/api/groups/data/#gaa8ca7922927481c9c031e92763e35bbd">DebugStrStrings</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#aae15d3fd865c24112c03b48e951d71e8">llvm::dwarf_linker::parallel::OutputSections::forEach</a> and <a href="#a1a8083cc3c516a879074fa43a7b70a51">forEachObjectSectionsSet</a>.</p>


<p>Referenced by <a href="#a71330a23d2feee283a26bc08a32a412c">glueCompileUnitsAndWriteToTheOutput</a>.</p>

</div>
</div>

### printStatistic() {#a557d8187b93bd54d7263d4755c5e99e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::printStatistic ()</td>
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

<p>Print statistic for processed Debug Info.</p>

<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">ObjectContexts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a71330a23d2feee283a26bc08a32a412c">glueCompileUnitsAndWriteToTheOutput</a>.</p>

</div>
</div>

### validateAndUpdateOptions() {#a49eedb8f4407a04a750f0b63384f8217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFLinkerImpl::validateAndUpdateOptions ()</td>
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

<p>Validate specified options.</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a42302ab883ef8ec7e51b00701d626ce4">link</a>.</p>

</div>
</div>

### verifyInput() {#a901080a7f2755abf0fc90c2d0d9da87f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::verifyInput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File)</td>
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

<p>Verify input DWARF file.</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">GlobalData</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#ace64c2107df2ab7fcbf17e0b6017d9dc">llvm::DIDumpOptions::noImplicitRecursion</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="#a42302ab883ef8ec7e51b00701d626ce4">link</a>.</p>

</div>
</div>

### writeCommonSectionsToTheOutput() {#a4b5b872efe54c2815cd80e6f96280e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::writeCommonSectionsToTheOutput ()</td>
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

<p>Enumerate common sections and put their data into the output stream.</p>

<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#gacdf65b146e52dc91522d73d43113f388">CommonSections</a> and <a href="/web-llvm/docs/api/groups/data/#ga7a05179a9b937ed748b2048984414169">SectionHandler</a>.</p>


<p>Referenced by <a href="#a71330a23d2feee283a26bc08a32a412c">glueCompileUnitsAndWriteToTheOutput</a>.</p>

</div>
</div>

### writeCompileUnitsToTheOutput() {#a2e4feb28330f8c865244bec30383d1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::writeCompileUnitsToTheOutput ()</td>
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

<p>Enumerate all compile units and put their data into the output stream.</p>

<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 1406 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#aae15d3fd865c24112c03b48e951d71e8">llvm::dwarf_linker::parallel::OutputSections::forEach</a>, <a href="#a1a8083cc3c516a879074fa43a7b70a51">forEachObjectSectionsSet</a> and <a href="/web-llvm/docs/api/groups/data/#ga7a05179a9b937ed748b2048984414169">SectionHandler</a>.</p>


<p>Referenced by <a href="#ac8c9b6d8ca3948e29ec1511b6037cdcf">emitCommonSectionsAndWriteCompileUnitsToTheOutput</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
