---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/methods
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The used to link the debug information Reference

<p>Emit unit's abbreviations. <a href="#details">More...</a></p>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/diecloner">DIECloner</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo">AccelInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure keeps fields which would be used for creating accelerator table. <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AccelType : uint8_t { <a href="#ga2c708209e1c0939d50f9e70bc5708491">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2aa92c4a933559ff31416fbf591a2ebb">assignAbbrev</a> (DIEAbbrev &amp;Abbrev)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign an abbreviation number to <span class="doxyComputerOutput">Abbrev</span>. <a href="#ga2aa92c4a933559ff31416fbf591a2ebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8394ac912aa1b29344c695448138771c">generateUnitRanges</a> (CompileUnit &amp;Unit, const DWARFFile &amp;File, DebugDieValuePool &amp;AddrPool) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and emit debug ranges(.debug_aranges, .debug_ranges, .debug_rnglists) for <span class="doxyComputerOutput">Unit</span>, patch the attributes referencing it. <a href="#ga8394ac912aa1b29344c695448138771c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga54dda4f7a2eefd155f9b950467deeb3e">emitAcceleratorEntriesForUnit</a> (CompileUnit &amp;Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the accelerator entries for <span class="doxyComputerOutput">Unit</span>. <a href="#ga54dda4f7a2eefd155f9b950467deeb3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaedf18a2dd597536e4fcc81f0c746cef0">patchFrameInfoForObject</a> (LinkContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Patch the frame info for an object file and emit it. <a href="#gaedf18a2dd597536e4fcc81f0c746cef0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac50204237d93d1b18c5a6bef8e7f7a35">Allocate</a> (size_t Size, size_t Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate <em>Size</em> bytes of <em>Alignment</em> aligned memory. <a href="#gac50204237d93d1b18c5a6bef8e7f7a35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga40b8fb32acf8598697e08acfdeb9dfe6">Deallocate</a> (const void *Ptr, size_t Size, size_t Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deallocate <em>Ptr</em> to <em>Size</em> bytes of memory allocated by this allocator. <a href="#ga40b8fb32acf8598697e08acfdeb9dfe6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">AllocatorTy &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae12d36c6142e37df006ccd257fe67ed4">getThreadLocalAllocator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return allocator corresponding to the current thread. <a href="#gae12d36c6142e37df006ccd257fe67ed4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga241da07086c81f8b14f6f766defddfb0">getNumberOfAllocators</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8bace7a71275aacc0eb1a5d3529dba88">Reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset state of allocators. <a href="#ga8bace7a71275aacc0eb1a5d3529dba88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2aab65f0894500db262b9a96babdd677">getTotalMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return total memory size used by all allocators. <a href="#ga2aab65f0894500db262b9a96babdd677">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7620b54ef2853df9ff49fbe17f68c699">getBytesAllocated</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return allocated size by all allocators. <a href="#ga7620b54ef2853df9ff49fbe17f68c699">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae81580dabe11d9791d230dafbf468995">setRedZoneSize</a> (size_t NewSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set red zone for all allocators. <a href="#gae81580dabe11d9791d230dafbf468995">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gadb4c324f923536f648a97734daaeebfd">PrintStats</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print statistic for each allocator. <a href="#gadb4c324f923536f648a97734daaeebfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8b2f2eefb63daf2e6f322e1e90228a2e">warn</a> (const Twine &amp;Warning, const DWARFDie *DIE=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga654eee00b3eed07a03d37b22391d18e2">warn</a> (Error Warning, const DWARFDie *DIE=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae294385bb587a12499b98215ae8e7745">warn</a> (const Twine &amp;Warning, const DWARFDebugInfoEntry *DieEntry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab0417bf315aa0a768f1a33d55209135a">error</a> (const Twine &amp;Err, const DWARFDie *DIE=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga067b49dc851a8db06344fa2b594cb6bb">error</a> (Error Err, const DWARFDie *DIE=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3353de162ad20f4b351ce8f7f20ed0cf">setVerbosity</a> (bool Verbose) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows to generate log of linking process to the standard output. <a href="#ga3353de162ad20f4b351ce8f7f20ed0cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa6301620399ecf2b208db01a8684e685">setStatistics</a> (bool Statistics) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print statistics to standard output. <a href="#gaa6301620399ecf2b208db01a8684e685">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8729af41da30f5c338b8978beacc95b1">setVerifyInputDWARF</a> (bool Verify) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the input DWARF. <a href="#ga8729af41da30f5c338b8978beacc95b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab184213d426e7f081daf5126d4be8d0c">setNoODR</a> (bool NoODR) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not unique types according to ODR. <a href="#gab184213d426e7f081daf5126d4be8d0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8a80ebc00f7b521e86733924c74b607f">setUpdateIndexTablesOnly</a> (bool UpdateIndexTablesOnly) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update index tables <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a5782a8740ff1e91516b41b3726a3168c">only(do not modify rest of DWARF)</a>. <a href="#ga8a80ebc00f7b521e86733924c74b607f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga833ee700f8518d752a7b88225ed74996">setAllowNonDeterministicOutput</a> (bool AllowNonDeterministicOutput) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow generating valid, but non-deterministic output. <a href="#ga833ee700f8518d752a7b88225ed74996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga87f3f8572db8476d4613032daee7afb8">setKeepFunctionForStatic</a> (bool KeepFunctionForStatic) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to keep the enclosing function for a static variable. <a href="#ga87f3f8572db8476d4613032daee7afb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1f6a1429f7ebe1cca2f2dd150a0e215b">setNumThreads</a> (unsigned NumThreads) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> specified number of threads for parallel files linking. <a href="#ga1f6a1429f7ebe1cca2f2dd150a0e215b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga447b8844a29e63edeb2f8f111f9d4ed9">addAccelTableKind</a> (AccelTableKind Kind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add kind of accelerator tables to be generated. <a href="#ga447b8844a29e63edeb2f8f111f9d4ed9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac3b0a6b8f7bcd351cd401bed2d17cb7c">setPrependPath</a> (StringRef Ppath) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set prepend path for clang modules. <a href="#gac3b0a6b8f7bcd351cd401bed2d17cb7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafe8baf0ba96e0cb88ec5dd7695a2986b">setEstimatedObjfilesAmount</a> (unsigned ObjFilesNum) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set estimated objects files amount, for preliminary data allocation. <a href="#gafe8baf0ba96e0cb88ec5dd7695a2986b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga372b14880235403f9e6558e8077d7bd7">setInputVerificationHandler</a> (InputVerificationHandlerTy Handler) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set verification handler which would be used to report verification errors. <a href="#ga372b14880235403f9e6558e8077d7bd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8f0f5f298730862e2cbb1d40c00b1bd1">setSwiftInterfacesMap</a> (SwiftInterfacesMapTy *Map) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set map for Swift interfaces. <a href="#ga8f0f5f298730862e2cbb1d40c00b1bd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3fbe10652ed6870909b2ca982f8ec921">setObjectPrefixMap</a> (ObjectPrefixMapTy *Map) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set prefix map for objects. <a href="#ga3fbe10652ed6870909b2ca982f8ec921">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Error</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2814e2cc1c4cb63b8f5cf54f16c2d5f7">setTargetDWARFVersion</a> (uint16_t TargetDWARFVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set target DWARF version. <a href="#ga2814e2cc1c4cb63b8f5cf54f16c2d5f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9b4dbcbc740191455c092e2edd8afa51">emitAbbreviations</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4353067d272bae6ec1a934e5ea39f924">emitDebugInfo</a> (const Triple &amp;TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_info section for unit DIEs. <a href="#ga4353067d272bae6ec1a934e5ea39f924">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf5ad0e93c4f3b97d0e8d192675945746">emitDebugLine</a> (const Triple &amp;TargetTriple, const DWARFDebugLine::LineTable &amp;OutLineTable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_line section. <a href="#gaf5ad0e93c4f3b97d0e8d192675945746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga579ac60d76c4a3b6ca084238591d4437">emitDebugStringOffsetSection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_str_offsets section for current unit. <a href="#ga579ac60d76c4a3b6ca084238591d4437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga90690238930e2f8062b17bbea187d3b1">warn</a> (const Twine &amp;Warning)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga88ab67842e20cde2f963249cf344c2ed">error</a> (const Twine &amp;Err)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga80d3884d82a541f6f1b11931db9fc5fb">emitPubAccelerators</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_pubnames and .debug_pubtypes for <span class="doxyComputerOutput">Unit</span>. <a href="#ga80d3884d82a541f6f1b11931db9fc5fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga75da77525cf70d66af72eb9d0f4592f2">forEachAcceleratorRecord</a> (function_ref&lt; void(AccelInfo &amp;)&gt; Handler)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates accelerator data. <a href="#ga75da77525cf70d66af72eb9d0f4592f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">FoldingSet&lt; DIEAbbrev &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4848fb1c48d2177a581998f4148a79e1">AbbreviationsSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> that uniques the abbreviations. <a href="#ga4848fb1c48d2177a581998f4148a79e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; std::unique_ptr&lt; DIEAbbrev &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga28295e4595aa2e9795bafb4f988eb387">Abbreviations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage for the unique Abbreviations. <a href="#ga28295e4595aa2e9795bafb4f988eb387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; DIELoc * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4dc98e41bb74bd3034ab586cbf65825d">DIELocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> objects that need to be destructed (but not freed!). <a href="#ga4dc98e41bb74bd3034ab586cbf65825d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; DIEBlock * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3469ff79fcbde6523ed545795538932c">DIEBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dieblock">DIEBlock</a> objects that need to be destructed (but not freed!). <a href="#ga3469ff79fcbde6523ed545795538932c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BumpPtrAllocator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga173bf0b93926ea58018760bfdac46950">DIEAlloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator used for all the <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> objects. <a href="#ga173bf0b93926ea58018760bfdac46950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Emit unit's abbreviations.</p>

<div class="doxySectionDef">

## Enumerations

### AccelType {#ga2c708209e1c0939d50f9e70bc5708491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::dwarf_linker::parallel::DwarfUnit::AccelType : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
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
<td class="doxyEnumItemName">None<a id="gga2c708209e1c0939d50f9e70bc5708491a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Name<a id="gga2c708209e1c0939d50f9e70bc5708491a49ee3087348e8d44e1feda1917443987"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Namespace<a id="gga2c708209e1c0939d50f9e70bc5708491ab3ba0fe968ce39dcfc6fe8cc0f1b02da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ObjC<a id="gga2c708209e1c0939d50f9e70bc5708491adebd6b4842117b405ba901644458b32c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Type<a id="gga2c708209e1c0939d50f9e70bc5708491aa1fa27779242b4902f7ae3bdd5c6d508"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addAccelTableKind() {#ga447b8844a29e63edeb2f8f111f9d4ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::addAccelTableKind (AccelTableKind Kind)</td>
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

<p>Add kind of accelerator tables to be generated.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### Allocate() {#gac50204237d93d1b18c5a6bef8e7f7a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::Allocate (size_t Size, size_t Alignment)</td>
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

<p>Allocate <em>Size</em> bytes of <em>Alignment</em> aligned memory.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>

</div>
</div>

### assignAbbrev() {#ga2aa92c4a933559ff31416fbf591a2ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::assignAbbrev (DIEAbbrev &amp; Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign an abbreviation number to <span class="doxyComputerOutput">Abbrev</span>.</p>


<p>Our DIEs get freed after every DebugMapObject has been processed, thus the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> we use to unique DIEAbbrevs cannot refer to the instances hold by the DIEs. When we encounter an abbreviation that we don't know, we create a permanent copy of it.</p>


<p>Declaration at line 724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1010 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### Deallocate() {#ga40b8fb32acf8598697e08acfdeb9dfe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::Deallocate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Ptr, size_t Size, size_t Alignment)</td>
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

<p>Deallocate <em>Ptr</em> to <em>Size</em> bytes of memory allocated by this allocator.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>

</div>
</div>

### emitAbbreviations() {#ga9b4dbcbc740191455c092e2edd8afa51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DwarfUnit::emitAbbreviations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a67fcda65761299e9cc1cf923fe1bc751">llvm::dwarf_linker::DebugAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aec20444d01151e8ad774f0d1354067c3">llvm::dwarf_linker::parallel::DwarfUnit::emitDwarfAbbrevEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aebc2b7745b60e26a867ba76b835c1a95">llvm::dwarf_linker::parallel::DwarfUnit::getAbbreviations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>.</p>

</div>
</div>

### emitAcceleratorEntriesForUnit() {#ga54dda4f7a2eefd155f9b950467deeb3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::emitAcceleratorEntriesForUnit (CompileUnit &amp; Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the accelerator entries for <span class="doxyComputerOutput">Unit</span>.</p>

<p>Declaration at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2247 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### emitDebugInfo() {#ga4353067d272bae6ec1a934e5ea39f924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DwarfUnit::emitDebugInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_info section for unit DIEs.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24a67fcda65761299e9cc1cf923fe1bc751">llvm::dwarf_linker::DebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a33ecefa9aec7bce5d08e92138ae1be08">llvm::dwarf_linker::parallel::OutputSections::getFormParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#afbcc691dc3aee7912fd0e6f49fb1bb8a">llvm::dwarf_linker::parallel::DwarfUnit::getOutUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#aba62c3e12b7c341d64f21e98325f4082a497031794414a552435f90151ac3b54b">llvm::dwarf_linker::DWARFLinkerBase::Object</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a5a523c53d66f904a426d8b60e192fb72">llvm::dwarf_linker::parallel::DwarfUnit::OutUnitDIE</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a0756e89d8eafc4bc2503dd3976765f61">llvm::dwarf_linker::parallel::SectionDescriptor::setSizesForSectionCreatedByAsmPrinter</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>.</p>

</div>
</div>

### emitDebugLine() {#gaf5ad0e93c4f3b97d0e8d192675945746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DwarfUnit::emitDebugLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> &amp; OutLineTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_line section.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter/#a81feed7a90b5abc9e58b574e7da2a360">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>.</p>

</div>
</div>

### emitDebugStringOffsetSection() {#ga579ac60d76c4a3b6ca084238591d4437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DwarfUnit::emitDebugStringOffsetSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the .debug_str_offsets section for current unit.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a5e7ab4547b66cde4652390ba796d97a1">llvm::dwarf_linker::parallel::SectionDescriptor::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#a98241a1a7e8a7cb3c7fa4e9202a5011b">llvm::dwarf_linker::parallel::DwarfUnit::DebugStringIndexMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24aff29b8418c7593f015431386cf40b181">llvm::dwarf_linker::DebugStrOffsets</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a4954fa6faa9509d506fcedc034eb02c8">llvm::dwarf_linker::parallel::SectionDescriptor::emitIntVal</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a2b514ad5d75b2375ee443a0338d694e8">llvm::dwarf_linker::parallel::SectionDescriptor::emitOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a25a7fc71830bebb1aa3eda2441838cd6">llvm::dwarf_linker::parallel::SectionDescriptor::emitUnitLength</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a235a5f4eedbfa7b5583ba320309d408f">llvm::dwarf::FormParams::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a2c022a96c1e5b992978a5b39a946fd56">llvm::dwarf_linker::parallel::SectionDescriptorBase::getFormParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a72e4600f7a22981307da5b2a2b5acb68">llvm::dwarf_linker::parallel::OutputSections::getVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>.</p>

</div>
</div>

### emitPubAccelerators() {#ga80d3884d82a541f6f1b11931db9fc5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::emitPubAccelerators ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit .debug_pubnames and .debug_pubtypes for <span class="doxyComputerOutput">Unit</span>.</p>

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a5e7ab4547b66cde4652390ba796d97a1">llvm::dwarf_linker::parallel::SectionDescriptor::apply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ab9f0ac5cd82959dfec84a8c1e8bf6aaf">llvm::dwarf_linker::DebugPubNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ab177be5746b8cbbce9ae68af24455c98">llvm::dwarf_linker::DebugPubTypes</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a4954fa6faa9509d506fcedc034eb02c8">llvm::dwarf_linker::parallel::SectionDescriptor::emitIntVal</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aa5415f7dcc45583b4bb82acb6f64c73a">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAcceleratorEntry</a>, <a href="#ga75da77525cf70d66af72eb9d0f4592f2">llvm::dwarf_linker::parallel::DwarfUnit::forEachAcceleratorRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#a235a5f4eedbfa7b5583ba320309d408f">llvm::dwarf::FormParams::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptorbase/#a2c022a96c1e5b992978a5b39a946fd56">llvm::dwarf_linker::parallel::SectionDescriptorBase::getFormParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="#gga2c708209e1c0939d50f9e70bc5708491a49ee3087348e8d44e1feda1917443987">llvm::dwarf_linker::parallel::DwarfUnit::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a> and <a href="#gga2c708209e1c0939d50f9e70bc5708491aa1fa27779242b4902f7ae3bdd5c6d508">llvm::dwarf_linker::parallel::DwarfUnit::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>.</p>

</div>
</div>

### error() {#gab0417bf315aa0a768f1a33d55209135a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Twine &amp; Err, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie * DIE=nullptr)</td>
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



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4d5c28a1b468db516b750ace450138d">llvm::dwarf_linker::parallel::DwarfUnit::getUnitName</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>.</p>

</div>
</div>

### error() {#ga067b49dc851a8db06344fa2b594cb6bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::error (Error Err, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie * DIE=nullptr)</td>
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



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4d5c28a1b468db516b750ace450138d">llvm::dwarf_linker::parallel::DwarfUnit::getUnitName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### error() {#ga88ab67842e20cde2f963249cf344c2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DwarfUnit::error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Twine &amp; Err)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4d5c28a1b468db516b750ace450138d">llvm::dwarf_linker::parallel::DwarfUnit::getUnitName</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>.</p>

</div>
</div>

### forEachAcceleratorRecord() {#ga75da77525cf70d66af72eb9d0f4592f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::parallel::DwarfUnit::forEachAcceleratorRecord (function_ref&lt; void(AccelInfo &amp;)&gt; Handler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumerates accelerator data.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>.</p>

</div>
</div>

### generateUnitRanges() {#ga8394ac912aa1b29344c695448138771c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::generateUnitRanges (CompileUnit &amp; Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFFile &amp; File, DebugDieValuePool &amp; AddrPool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute and emit debug ranges(.debug_aranges, .debug_ranges, .debug_rnglists) for <span class="doxyComputerOutput">Unit</span>, patch the attributes referencing it.</p>


<p>Patch the input object file relevant debug_ranges or debug_rnglists entries and emit them in the output file.</p>


<p>Update the relevant attributes to point at the new entries.</p>


<p>Declaration at line 728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 1931 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### getBytesAllocated() {#ga7620b54ef2853df9ff49fbe17f68c699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::getBytesAllocated ()</td>
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

<p>Return allocated size by all allocators.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>


<p>Referenced by <a href="#ga7620b54ef2853df9ff49fbe17f68c699">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::getBytesAllocated</a>.</p>

</div>
</div>

### getNumberOfAllocators() {#ga241da07086c81f8b14f6f766defddfb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::getNumberOfAllocators ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>


<p>Referenced by <a href="#ga7620b54ef2853df9ff49fbe17f68c699">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::getBytesAllocated</a>, <a href="#ga2aab65f0894500db262b9a96babdd677">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::getTotalMemory</a>, <a href="#gadb4c324f923536f648a97734daaeebfd">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::PrintStats</a>, <a href="#ga8bace7a71275aacc0eb1a5d3529dba88">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::Reset</a> and <a href="#gae81580dabe11d9791d230dafbf468995">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::setRedZoneSize</a>.</p>

</div>
</div>

### getThreadLocalAllocator() {#gae12d36c6142e37df006ccd257fe67ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocatorTy &amp; llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::getThreadLocalAllocator ()</td>
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

<p>Return allocator corresponding to the current thread.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>

</div>
</div>

### getTotalMemory() {#ga2aab65f0894500db262b9a96babdd677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::getTotalMemory ()</td>
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

<p>Return total memory size used by all allocators.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>


<p>Referenced by <a href="#ga2aab65f0894500db262b9a96babdd677">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::getTotalMemory</a>.</p>

</div>
</div>

### patchFrameInfoForObject() {#gaedf18a2dd597536e4fcc81f0c746cef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::patchFrameInfoForObject (LinkContext &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Patch the frame info for an object file and emit it.</p>


<p>Read the frame info stored in the object, and emit the patched frame descriptions for the resulting file.</p>


<p>This is actually pretty easy as the data of the CIEs and FDEs can be considered as black boxes and moved as is. The only thing to do is to patch the addresses in the headers.</p>


<p>Declaration at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2306 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### PrintStats() {#gadb4c324f923536f648a97734daaeebfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::PrintStats ()</td>
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

<p>Print statistic for each allocator.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>

</div>
</div>

### Reset() {#ga8bace7a71275aacc0eb1a5d3529dba88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::Reset ()</td>
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

<p>Reset state of allocators.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>


<p>Referenced by <a href="#ga8bace7a71275aacc0eb1a5d3529dba88">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::Reset</a>.</p>

</div>
</div>

### setAllowNonDeterministicOutput() {#ga833ee700f8518d752a7b88225ed74996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setAllowNonDeterministicOutput (bool AllowNonDeterministicOutput)</td>
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

<p>Allow generating valid, but non-deterministic output.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setEstimatedObjfilesAmount() {#gafe8baf0ba96e0cb88ec5dd7695a2986b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFLinkerImpl::setEstimatedObjfilesAmount (unsigned ObjFilesNum)</td>
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

<p>Set estimated objects files amount, for preliminary data allocation.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp">DWARFLinkerImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga57b26f33c0c25d1960ef1af6c0bb9789">llvm::dwarf_linker::parallel::DWARFLinkerImpl::ObjectContexts</a>.</p>

</div>
</div>

### setInputVerificationHandler() {#ga372b14880235403f9e6558e8077d7bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setInputVerificationHandler (InputVerificationHandlerTy Handler)</td>
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

<p>Set verification handler which would be used to report verification errors.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setKeepFunctionForStatic() {#ga87f3f8572db8476d4613032daee7afb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setKeepFunctionForStatic (bool KeepFunctionForStatic)</td>
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

<p>Set to keep the enclosing function for a static variable.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setNoODR() {#gab184213d426e7f081daf5126d4be8d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setNoODR (bool NoODR)</td>
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

<p>Do not unique types according to ODR.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setNumThreads() {#ga1f6a1429f7ebe1cca2f2dd150a0e215b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setNumThreads (unsigned NumThreads)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> specified number of threads for parallel files linking.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setObjectPrefixMap() {#ga3fbe10652ed6870909b2ca982f8ec921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setObjectPrefixMap (ObjectPrefixMapTy * Map)</td>
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

<p>Set prefix map for objects.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setPrependPath() {#gac3b0a6b8f7bcd351cd401bed2d17cb7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setPrependPath (StringRef Ppath)</td>
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

<p>Set prepend path for clang modules.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setRedZoneSize() {#gae81580dabe11d9791d230dafbf468995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::parallel::PerThreadAllocator&lt; AllocatorTy &gt;::setRedZoneSize (size_t NewSize)</td>
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

<p>Set red zone for all allocators.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>


<p>Referenced by <a href="#gae81580dabe11d9791d230dafbf468995">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::setRedZoneSize</a>.</p>

</div>
</div>

### setStatistics() {#gaa6301620399ecf2b208db01a8684e685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setStatistics (bool Statistics)</td>
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

<p>Print statistics to standard output.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setSwiftInterfacesMap() {#ga8f0f5f298730862e2cbb1d40c00b1bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setSwiftInterfacesMap (SwiftInterfacesMapTy * Map)</td>
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

<p>Set map for Swift interfaces.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setTargetDWARFVersion() {#ga2814e2cc1c4cb63b8f5cf54f16c2d5f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::dwarf_linker::parallel::DWARFLinkerImpl::setTargetDWARFVersion (uint16_t TargetDWARFVersion)</td>
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

<p>Set target DWARF version.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### setUpdateIndexTablesOnly() {#ga8a80ebc00f7b521e86733924c74b607f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setUpdateIndexTablesOnly (bool UpdateIndexTablesOnly)</td>
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

<p>Update index tables <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a5782a8740ff1e91516b41b3726a3168c">only(do not modify rest of DWARF)</a>.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a>.</p>

</div>
</div>

### setVerbosity() {#ga3353de162ad20f4b351ce8f7f20ed0cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setVerbosity (bool Verbose)</td>
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

<p>Allows to generate log of linking process to the standard output.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

### setVerifyInputDWARF() {#ga8729af41da30f5c338b8978beacc95b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DWARFLinkerImpl::setVerifyInputDWARF (bool Verify)</td>
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

<p>Verify the input DWARF.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-h">DWARFLinkerImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/data/#ga2c981717283fff014f2fc47ec9febc66">llvm::dwarf_linker::parallel::DWARFLinkerImpl::GlobalData</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a345bd69760b9ee32b3f49d4fc04120fb">Verify</a>.</p>

</div>
</div>

### warn() {#ga8b2f2eefb63daf2e6f322e1e90228a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::warn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Twine &amp; Warning, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie * DIE=nullptr)</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4d5c28a1b468db516b750ace450138d">llvm::dwarf_linker::parallel::DwarfUnit::getUnitName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a53949973d752a1d918687b758424714a">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>.</p>

</div>
</div>

### warn() {#ga654eee00b3eed07a03d37b22391d18e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::warn (Error Warning, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDie * DIE=nullptr)</td>
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



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4d5c28a1b468db516b750ace450138d">llvm::dwarf_linker::parallel::DwarfUnit::getUnitName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

### warn() {#gae294385bb587a12499b98215ae8e7745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::warn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Twine &amp; Warning, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DWARFDebugInfoEntry * DieEntry)</td>
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



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/helper/#ga4a7a4b7dd835a0d0791b13322e3b5679">llvm::dwarf_linker::parallel::CompileUnit::getOrigUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4d5c28a1b468db516b750ace450138d">llvm::dwarf_linker::parallel::DwarfUnit::getUnitName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

### warn() {#ga90690238930e2f8062b17bbea187d3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DwarfUnit::warn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Twine &amp; Warning)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#ab4d5c28a1b468db516b750ace450138d">llvm::dwarf_linker::parallel::DwarfUnit::getUnitName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Abbreviations {#ga28295e4595aa2e9795bafb4f988eb387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;DIEAbbrev&gt; &gt; llvm::dwarf_linker::classic::DWARFLinker::Abbreviations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Storage for the unique Abbreviations.</p>


<p>This is passed to <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa1be0c2d757c08ab5a681f4cf1c675aa">AsmPrinter::emitDwarfAbbrevs()</a>, thus it cannot be changed to a vector of unique_ptrs.</p>


<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### AbbreviationsSet {#ga4848fb1c48d2177a581998f4148a79e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;DIEAbbrev&gt; llvm::dwarf_linker::classic::DWARFLinker::AbbreviationsSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> that uniques the abbreviations.</p>

<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### DIEAlloc {#ga173bf0b93926ea58018760bfdac46950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::dwarf_linker::classic::DWARFLinker::DIEAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocator used for all the <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> objects.</p>

<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### DIEBlocks {#ga3469ff79fcbde6523ed545795538932c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DIEBlock *&gt; llvm::dwarf_linker::classic::DWARFLinker::DIEBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/dieblock">DIEBlock</a> objects that need to be destructed (but not freed!).</p>

<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### DIELocs {#ga4dc98e41bb74bd3034ab586cbf65825d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DIELoc *&gt; llvm::dwarf_linker::classic::DWARFLinker::DIELocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> objects that need to be destructed (but not freed!).</p>

<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
