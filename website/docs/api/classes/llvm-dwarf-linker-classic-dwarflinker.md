---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/classic/dwarflinker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFLinker` Class

<p>The core of the Dwarf linking logic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::classic::DWARFLinker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">llvm/DWARFLinker/Classic/DWARFLinker.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase">DWARFLinkerBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base interface for <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker">DWARFLinker</a> implementations. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e60159172b5e312354fe80203b2b3e">ModuleUnitListTy</a> = std::vector&lt; RefModuleUnit &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">TraversalFlags { <a href="#a4ea254a884fa28ec31e634ddada2ec75">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags passed to DwarfLinker::lookForDIEsToKeep. <a href="#a4ea254a884fa28ec31e634ddada2ec75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">WorklistItemType { <a href="#a39f9f13cf5aa4aaff8230c8b58dac7a3">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The distinct types of work performed by the work loop. <a href="#a39f9f13cf5aa4aaff8230c8b58dac7a3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a419275b4bdc8a89c7cce1506c7f24345">DWARFLinker</a> (MessageHandlerTy ErrorHandler, MessageHandlerTy WarningHandler, std::function&lt; StringRef(StringRef)&gt; StringsTranslator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c001f01a280aefade681724cc88f7f">setOutputDWARFEmitter</a> (DwarfEmitter *Emitter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set output DWARF emitter. <a href="#ab3c001f01a280aefade681724cc88f7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58e570d50b3ef11bc8cd906ee008222">addObjectFile</a> (DWARFFile &amp;File, ObjFileLoaderTy Loader=nullptr, CompileUnitHandlerTy OnCUDieLoaded=[](const DWARFUnit &amp;) {}) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add object file to be linked. <a href="#ae58e570d50b3ef11bc8cd906ee008222">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6caebcd7dc40dea28562fde4f260414">link</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link debug info for added objFiles. Object files are linked all together. <a href="#af6caebcd7dc40dea28562fde4f260414">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d1b94dba1c04e090a344a1e31888e4">setVerbosity</a> (bool Verbose) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A number of methods setting various linking options: <a href="#ae7d1b94dba1c04e090a344a1e31888e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010ff281766fef5c1c343ba71c45f4bf">setStatistics</a> (bool Statistics) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print statistics to standard output. <a href="#a010ff281766fef5c1c343ba71c45f4bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4511f5243766afa68114a68c157c51dd">setVerifyInputDWARF</a> (bool Verify) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the input DWARF. <a href="#a4511f5243766afa68114a68c157c51dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d1c779a9536b634e8db8646a1cd0b0e">setNoODR</a> (bool NoODR) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not unique types according to ODR. <a href="#a9d1c779a9536b634e8db8646a1cd0b0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab761f2217eadcb15a3a8cd8704345951">setUpdateIndexTablesOnly</a> (bool Update) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update index tables <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a5782a8740ff1e91516b41b3726a3168c">only(do not modify rest of DWARF)</a>. <a href="#ab761f2217eadcb15a3a8cd8704345951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4c741bb835d7f1346afdf113e0ec20">setAllowNonDeterministicOutput</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow generating valid, but non-deterministic output. <a href="#a2a4c741bb835d7f1346afdf113e0ec20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33297f14d9c80430108df6e5e5f30089">setKeepFunctionForStatic</a> (bool KeepFunctionForStatic) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether to keep the enclosing function for a static variable. <a href="#a33297f14d9c80430108df6e5e5f30089">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2439e49252170de3fc15fca7752d5a58">setNumThreads</a> (unsigned NumThreads) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> specified number of threads for parallel files linking. <a href="#a2439e49252170de3fc15fca7752d5a58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5af387e6e654a7f0c2a2a9d520fd37c0">addAccelTableKind</a> (AccelTableKind Kind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add kind of accelerator tables to be generated. <a href="#a5af387e6e654a7f0c2a2a9d520fd37c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa309e19361ee14fee735cfff59d67d3a">setPrependPath</a> (StringRef Ppath) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set prepend path for clang modules. <a href="#aa309e19361ee14fee735cfff59d67d3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add2cdea32535864c9c9a750390c2d0ba">setEstimatedObjfilesAmount</a> (unsigned ObjFilesNum) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set estimated objects files amount, for preliminary data allocation. <a href="#add2cdea32535864c9c9a750390c2d0ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a017ab2d6b4a7ef8969ac4c8c85da214a">setInputVerificationHandler</a> (InputVerificationHandlerTy Handler) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set verification handler which would be used to report verification errors. <a href="#a017ab2d6b4a7ef8969ac4c8c85da214a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a216a1d8caddbc127e14e041ed76d6210">setSwiftInterfacesMap</a> (SwiftInterfacesMapTy *Map) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set map for Swift interfaces. <a href="#a216a1d8caddbc127e14e041ed76d6210">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da6af9e657fdde595f9a166ca7e4878">setObjectPrefixMap</a> (ObjectPrefixMapTy *Map) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set prefix map for objects. <a href="#a2da6af9e657fdde595f9a166ca7e4878">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac36499d5ebb7dc9994adee56cf716c4">setTargetDWARFVersion</a> (uint16_t TargetDWARFVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set target DWARF version. <a href="#aac36499d5ebb7dc9994adee56cf716c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a385669e7f2cb8235f12f3693ec123f05">verifyInput</a> (const DWARFFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the given DWARF file. <a href="#a385669e7f2cb8235f12f3693ec123f05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dfcf9d7db0a21ce196271e480750e02">needToTranslateStrings</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns true if we need to translate strings. <a href="#a9dfcf9d7db0a21ce196271e480750e02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c3c6eb2ee0857c3d6d55f8ba188646b">reportWarning</a> (const Twine &amp;Warning, const DWARFFile &amp;File, const DWARFDie *DIE=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae3d857175c82a13a192d98490e691c">reportError</a> (const Twine &amp;Warning, const DWARFFile &amp;File, const DWARFDie *DIE=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86e319465467e3ce1d7ea29415464327">copyInvariantDebugSection</a> (DWARFContext &amp;Dwarf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34590575f0376ebbae5463c3cc60c743">cleanupAuxiliarryData</a> (LinkContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called before emitting object data. <a href="#a34590575f0376ebbae5463c3cc60c743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3708da9e428050f8e282506451d8046">lookForParentDIEsToKeep</a> (unsigned AncestorIdx, CompileUnit &amp;CU, unsigned Flags, SmallVectorImpl&lt; WorklistItem &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look at the parent of the given <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and decide whether they should be kept. <a href="#ae3708da9e428050f8e282506451d8046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb439c21365779ac39a26f19cc425184">lookForChildDIEsToKeep</a> (const DWARFDie &amp;Die, CompileUnit &amp;CU, unsigned Flags, SmallVectorImpl&lt; WorklistItem &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look at the children of the given <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and decide whether they should be kept. <a href="#aeb439c21365779ac39a26f19cc425184">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e89c90434c1338539cedff8ca5b97c0">lookForRefDIEsToKeep</a> (const DWARFDie &amp;Die, CompileUnit &amp;CU, unsigned Flags, const UnitListTy &amp;Units, const DWARFFile &amp;File, SmallVectorImpl&lt; WorklistItem &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look at DIEs referenced by the given <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and decide whether they should be kept. <a href="#a1e89c90434c1338539cedff8ca5b97c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b619a56892640997c9a8d696ee161ed">markODRCanonicalDie</a> (const DWARFDie &amp;Die, CompileUnit &amp;CU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark context corresponding to the specified <span class="doxyComputerOutput">Die</span> as having canonical die, if applicable. <a href="#a8b619a56892640997c9a8d696ee161ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#ga2b4682e0fe0146440fe8826e4e67182e">lookForDIEsToKeep</a> (AddressesMap &amp;RelocMgr, const UnitListTy &amp;Units, const DWARFDie &amp;DIE, const DWARFFile &amp;File, CompileUnit &amp;CU, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively walk the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a></span> tree and look for DIEs to keep. <a href="/web-llvm/docs/api/groups/findrootdies/#ga2b4682e0fe0146440fe8826e4e67182e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#ga343cf73eec78f37be68c0f8a131a0d49">isClangModuleRef</a> (const DWARFDie &amp;CUDie, std::string &amp;PCMFile, LinkContext &amp;Context, unsigned Indent, bool Quiet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether specified <span class="doxyComputerOutput">CUDie</span> is a Clang module reference. <a href="/web-llvm/docs/api/groups/findrootdies/#ga343cf73eec78f37be68c0f8a131a0d49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#gabd5556765c8fe5426d92dc474a1e7966">registerModuleReference</a> (const DWARFDie &amp;CUDie, LinkContext &amp;Context, ObjFileLoaderTy Loader, CompileUnitHandlerTy OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this compile unit is really a skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a> that points to a clang module, register it in ClangModules and return true. <a href="/web-llvm/docs/api/groups/findrootdies/#gabd5556765c8fe5426d92dc474a1e7966">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Error</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#ga173d5c588b7bec182a851c6cfd7b3fa4">loadClangModule</a> (ObjFileLoaderTy Loader, const DWARFDie &amp;CUDie, const std::string &amp;PCMFile, LinkContext &amp;Context, CompileUnitHandlerTy OnCUDieLoaded, unsigned Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively add the debug info in this clang module .pcm file (and all the modules imported by it in a bottom-up fashion) to ModuleUnits. <a href="/web-llvm/docs/api/groups/findrootdies/#ga173d5c588b7bec182a851c6cfd7b3fa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Error</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#ga16541c95c463709f1163b52f913e6bc4">cloneModuleUnit</a> (LinkContext &amp;Context, RefModuleUnit &amp;Unit, DeclContextTree &amp;ODRContexts, OffsetsStringPool &amp;DebugStrPool, OffsetsStringPool &amp;DebugLineStrPool, DebugDieValuePool &amp;StringOffsetPool, unsigned Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone specified Clang module unit <span class="doxyComputerOutput">Unit</span>. <a href="/web-llvm/docs/api/groups/findrootdies/#ga16541c95c463709f1163b52f913e6bc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#ga24c2bcead90bfc63a47c4c1832093b10">shouldKeepDIE</a> (AddressesMap &amp;RelocMgr, const DWARFDie &amp;DIE, const DWARFFile &amp;File, CompileUnit &amp;Unit, CompileUnit::DIEInfo &amp;MyInfo, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept. <a href="/web-llvm/docs/api/groups/findrootdies/#ga24c2bcead90bfc63a47c4c1832093b10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, std::optional&lt; int64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#gaa180d20c87f7cda613a75894475ca2f0">getVariableRelocAdjustment</a> (AddressesMap &amp;RelocMgr, const DWARFDie &amp;DIE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function checks whether variable has DWARF expression containing operation referencing live address(f.e. <a href="/web-llvm/docs/api/groups/findrootdies/#gaa180d20c87f7cda613a75894475ca2f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#ga036b9988329e2d2dff7482b094cc5d63">shouldKeepVariableDIE</a> (AddressesMap &amp;RelocMgr, const DWARFDie &amp;DIE, CompileUnit::DIEInfo &amp;MyInfo, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a variable describing <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept. <a href="/web-llvm/docs/api/groups/findrootdies/#ga036b9988329e2d2dff7482b094cc5d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#gaf0bf84a58c76b6f9173903dc44014df7">shouldKeepSubprogramDIE</a> (AddressesMap &amp;RelocMgr, const DWARFDie &amp;DIE, const DWARFFile &amp;File, CompileUnit &amp;Unit, CompileUnit::DIEInfo &amp;MyInfo, unsigned Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a function describing <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> should be kept. <a href="/web-llvm/docs/api/groups/findrootdies/#gaf0bf84a58c76b6f9173903dc44014df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DWARFDie</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/findrootdies/#ga6061ea947e754c29e1a73d644b113f03">resolveDIEReference</a> (const DWARFFile &amp;File, const UnitListTy &amp;Units, const DWARFFormValue &amp;RefValue, const DWARFDie &amp;DIE, CompileUnit *&amp;RefCU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> attribute reference that has been extracted in <span class="doxyComputerOutput">RefValue</span>. <a href="/web-llvm/docs/api/groups/findrootdies/#ga6061ea947e754c29e1a73d644b113f03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga2aa92c4a933559ff31416fbf591a2ebb">assignAbbrev</a> (DIEAbbrev &amp;Abbrev)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign an abbreviation number to <span class="doxyComputerOutput">Abbrev</span>. <a href="/web-llvm/docs/api/groups/methods/#ga2aa92c4a933559ff31416fbf591a2ebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga8394ac912aa1b29344c695448138771c">generateUnitRanges</a> (CompileUnit &amp;Unit, const DWARFFile &amp;File, DebugDieValuePool &amp;AddrPool) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and emit debug ranges(.debug_aranges, .debug_ranges, .debug_rnglists) for <span class="doxyComputerOutput">Unit</span>, patch the attributes referencing it. <a href="/web-llvm/docs/api/groups/methods/#ga8394ac912aa1b29344c695448138771c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga54dda4f7a2eefd155f9b950467deeb3e">emitAcceleratorEntriesForUnit</a> (CompileUnit &amp;Unit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the accelerator entries for <span class="doxyComputerOutput">Unit</span>. <a href="/web-llvm/docs/api/groups/methods/#ga54dda4f7a2eefd155f9b950467deeb3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#gaedf18a2dd597536e4fcc81f0c746cef0">patchFrameInfoForObject</a> (LinkContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Patch the frame info for an object file and emit it. <a href="/web-llvm/docs/api/groups/methods/#gaedf18a2dd597536e4fcc81f0c746cef0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter">DwarfEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04d9d231bad7e179e7736904370fbd0">TheDwarfEmitter</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; LinkContext &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f7c983f88453183ad9f0cc7e5a653d">ObjectContexts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2932cb8d50074973bbdc9adc35d41794">EmittedCIEs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The CIEs that have been emitted in the output section. <a href="#a2932cb8d50074973bbdc9adc35d41794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad783d0a3eb256e858e99e88f912660e0">LastCIEOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset of the last CIE that has been emitted in the output .debug_frame section. <a href="#ad783d0a3eb256e858e99e88f912660e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltable">DWARF5AccelTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0395fcf056236a5537cc267e4f582db">DebugNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apple accelerator tables. <a href="#aa0395fcf056236a5537cc267e4f582db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72efa2f2b84ccbfa80b4ac7f529f0fb3">AppleNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c061d1b674ffbdcc0e1e2287f3e6891">AppleNamespaces</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestaticoffsetdata">AppleAccelTableStaticOffsetData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0f34dd0b6f04aa4ab188334b3dddb9">AppleObjc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/acceltable">AccelTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/appleacceltablestatictypedata">AppleAccelTableStaticTypeData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1440f27f336334a23a0dc4f05fc4f25d">AppleTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5cdeb7ae46271105ef46d21de94ddc4">ClangModules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping the PCM filename to the DwoId. <a href="#aa5cdeb7ae46271105ef46d21de94ddc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100e3ac356e1699f1648bfb1a5dc182c">StringsTranslator</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684d27971fce3d5980daf565c3bd9083">UniqueUnitID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> that identifies each compile unit. <a href="#a684d27971fce3d5980daf565c3bd9083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f74aeb511ba3a1f845c8790e9b0615">ErrorHandler</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df071ad3ffef1f8e8afa4655b0de021">WarningHandler</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af784ab096506152175a4d2e6cdfc200a">Options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FoldingSet&lt; DIEAbbrev &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga4848fb1c48d2177a581998f4148a79e1">AbbreviationsSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> that uniques the abbreviations. <a href="/web-llvm/docs/api/groups/methods/#ga4848fb1c48d2177a581998f4148a79e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; std::unique_ptr&lt; DIEAbbrev &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga28295e4595aa2e9795bafb4f988eb387">Abbreviations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage for the unique Abbreviations. <a href="/web-llvm/docs/api/groups/methods/#ga28295e4595aa2e9795bafb4f988eb387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; DIELoc * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga4dc98e41bb74bd3034ab586cbf65825d">DIELocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dieloc">DIELoc</a> objects that need to be destructed (but not freed!). <a href="/web-llvm/docs/api/groups/methods/#ga4dc98e41bb74bd3034ab586cbf65825d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; DIEBlock * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga3469ff79fcbde6523ed545795538932c">DIEBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/dieblock">DIEBlock</a> objects that need to be destructed (but not freed!). <a href="/web-llvm/docs/api/groups/methods/#ga3469ff79fcbde6523ed545795538932c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BumpPtrAllocator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga173bf0b93926ea58018760bfdac46950">DIEAlloc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator used for all the <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> objects. <a href="/web-llvm/docs/api/groups/methods/#ga173bf0b93926ea58018760bfdac46950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker">DWARFLinker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a978871b5919763e0bf8bfe0fbfca93e6">createLinker</a> (MessageHandlerTy ErrorHandler, MessageHandlerTy WarningHandler, std::function&lt; StringRef(StringRef)&gt; StringsTranslator=nullptr)</td>
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

<p>The core of the Dwarf linking logic.</p>


<p>The generation of the dwarf information from the object files will be driven by the selection of 'root DIEs', which are DIEs that describe variables or functions that resolves to the corresponding code section(and thus have entries in the Addresses map). All the debug information that will be generated(the DIEs, but also the line
tables, ranges, ...) is derived from that set of root DIEs.</p>


<p>The root DIEs are identified because they contain relocations that points to code section(the low_pc for a function, the location for
a variable). These relocations are called ValidRelocs in the AddressesInfo and are gathered as a very first step when we start processing a object file.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ModuleUnitListTy {#aa6e60159172b5e312354fe80203b2b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::classic::DWARFLinker::ModuleUnitListTy =  std::vector&lt;RefModuleUnit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### TraversalFlags {#a4ea254a884fa28ec31e634ddada2ec75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::dwarf_linker::classic::DWARFLinker::TraversalFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags passed to DwarfLinker::lookForDIEsToKeep.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TF_Keep<a id="a4ea254a884fa28ec31e634ddada2ec75af1dbff36d3f0145c09d40a8cc5564852"></a></td>
<td class="doxyEnumItemDescription">Mark the traversed DIEs as kept (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TF_InFunctionScope<a id="a4ea254a884fa28ec31e634ddada2ec75a4ec197ba7e11cfb89b03e175118ed3a7"></a></td>
<td class="doxyEnumItemDescription">Current scope is a function scope (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TF_DependencyWalk<a id="a4ea254a884fa28ec31e634ddada2ec75a4433a604d690b5582ca42d6785e994d5"></a></td>
<td class="doxyEnumItemDescription">Walking the dependencies of a kept <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TF_ParentWalk<a id="a4ea254a884fa28ec31e634ddada2ec75a198689d1bc624cd33d19cfd4efd4a5ad"></a></td>
<td class="doxyEnumItemDescription">Walking up the parents of a kept <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TF_ODR<a id="a4ea254a884fa28ec31e634ddada2ec75a49b5af23de9e4a7a8aa2b77654c1f931"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the ODR while keeping dependents (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TF_SkipPC<a id="a4ea254a884fa28ec31e634ddada2ec75ad86739eb568c26a46cbb34f5ab4176be"></a></td>
<td class="doxyEnumItemDescription">Skip all location attributes (= 1 &lt;&lt; 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### WorklistItemType {#a39f9f13cf5aa4aaff8230c8b58dac7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::dwarf_linker::classic::DWARFLinker::WorklistItemType </td>
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

<p>The distinct types of work performed by the work loop.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LookForDIEsToKeep<a id="a39f9f13cf5aa4aaff8230c8b58dac7a3a00f3bd202e9536bda80388d957e3fbe4"></a></td>
<td class="doxyEnumItemDescription">Given a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, look for DIEs to be kept</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LookForChildDIEsToKeep<a id="a39f9f13cf5aa4aaff8230c8b58dac7a3a7eea2219d805fb5ee87f35f288ba1c35"></a></td>
<td class="doxyEnumItemDescription">Given a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, look for children of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to be kept</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LookForRefDIEsToKeep<a id="a39f9f13cf5aa4aaff8230c8b58dac7a3a15db5729476e3d463dffed92a3edbdb1"></a></td>
<td class="doxyEnumItemDescription">Given a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, look for DIEs referencing this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to be kept</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LookForParentDIEsToKeep<a id="a39f9f13cf5aa4aaff8230c8b58dac7a3adc3110b05a8ab44a392fb0322de4723f"></a></td>
<td class="doxyEnumItemDescription">Given a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, look for parent DIEs to be kept</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UpdateChildIncompleteness<a id="a39f9f13cf5aa4aaff8230c8b58dac7a3a09d6d603a77f055293e557547eef0016"></a></td>
<td class="doxyEnumItemDescription">Given a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, update its incompleteness based on whether its children are incomplete</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UpdateRefIncompleteness<a id="a39f9f13cf5aa4aaff8230c8b58dac7a3ab01d435668eb3b4787c215df88dc3fc1"></a></td>
<td class="doxyEnumItemDescription">Given a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, update its incompleteness based on whether the DIEs it references are incomplete</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MarkODRCanonicalDie<a id="a39f9f13cf5aa4aaff8230c8b58dac7a3ace142adec4c00340472182a8034ab571"></a></td>
<td class="doxyEnumItemDescription">Given a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, mark it as ODR Canonical if applicable</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFLinker() {#a419275b4bdc8a89c7cce1506c7f24345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::classic::DWARFLinker::DWARFLinker (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> ErrorHandler, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> WarningHandler, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; StringsTranslator)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAccelTableKind() {#a5af387e6e654a7f0c2a2a9d520fd37c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::addAccelTableKind (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308">AccelTableKind</a> Kind)</td>
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

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### addObjectFile() {#ae58e570d50b3ef11bc8cd906ee008222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::addObjectFile (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#abdf3094623b3752dabeeb5bd7ceb24ad">ObjFileLoaderTy</a> Loader=nullptr, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a537122974e714f93e8ad5fa29439e856">CompileUnitHandlerTy</a> OnCUDieLoaded=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp;) {})</td>
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


<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2709 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>.</p>

</div>
</div>

### link() {#af6caebcd7dc40dea28562fde4f260414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DWARFLinker::link ()</td>
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

<p>Link debug info for added objFiles. Object files are linked all together.</p>

<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2730 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308a9f6290f4436e5a2351f12e03b6433c3c">llvm::dwarf_linker::DWARFLinkerBase::Apple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface/#ad43d0052f680e6ac08426d8821df178d">llvm::ThreadPoolInterface::async</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#ae396b319b15cbecf51ec8dc4ee2719b0">llvm::DIDumpOptions::ChildRecurseDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308a20f18d4a28570b83b8f5bd6c9d26d7b8">llvm::dwarf_linker::DWARFLinkerBase::DebugNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78afeb48a64a0f1d800ab10827de4f8b">llvm::getDebugInfoSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58c8277a8af9d4c7d299c82c95b39668">llvm::getPCMFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontexttree/#af8626f61b69ed2ebd28e34fd2a1f5379">llvm::dwarf_linker::classic::DeclContextTree::getRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/indexedvaluesmap/#a99aebbd2baa77e4f1354011f9763ca2a">llvm::dwarf_linker::IndexedValuesMap&lt; T &gt;::getValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00440f10281348fd9f7be52e23c7c874">llvm::hardware_concurrency</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a78ca7920cd1aaf69f7da553285c55308aa29bdd003ef6c0c34279807341f450f2">llvm::dwarf_linker::DWARFLinkerBase::Pub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02b44f93159b4b08e7998a4fb4d7705f">llvm::verifyKeepChain</a>, <a href="/web-llvm/docs/api/classes/llvm/singlethreadexecutor/#a4a9fc38bb7d9ff3f944e25971330cb42">llvm::SingleThreadExecutor::wait</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

### setAllowNonDeterministicOutput() {#a2a4c741bb835d7f1346afdf113e0ec20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setAllowNonDeterministicOutput (bool)</td>
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

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setEstimatedObjfilesAmount() {#add2cdea32535864c9c9a750390c2d0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setEstimatedObjfilesAmount (unsigned ObjFilesNum)</td>
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

<p>Set estimated objects files amount, for preliminary data allocation.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setInputVerificationHandler() {#a017ab2d6b4a7ef8969ac4c8c85da214a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setInputVerificationHandler (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#ac482b3b01bd8e00cd02ecfba94e88694">InputVerificationHandlerTy</a> Handler)</td>
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

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setKeepFunctionForStatic() {#a33297f14d9c80430108df6e5e5f30089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setKeepFunctionForStatic (bool KeepFunctionForStatic)</td>
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

<p>Set whether to keep the enclosing function for a static variable.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setNoODR() {#a9d1c779a9536b634e8db8646a1cd0b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setNoODR (bool NoODR)</td>
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

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setNumThreads() {#a2439e49252170de3fc15fca7752d5a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setNumThreads (unsigned NumThreads)</td>
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

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setObjectPrefixMap() {#a2da6af9e657fdde595f9a166ca7e4878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setObjectPrefixMap (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a0b10e00e608ed9bcead9c3c7bcd62b4c">ObjectPrefixMapTy</a> * Map)</td>
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

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setOutputDWARFEmitter() {#ab3c001f01a280aefade681724cc88f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setOutputDWARFEmitter (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfemitter">DwarfEmitter</a> * Emitter)</td>
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

<p>Set output DWARF emitter.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>.</p>

</div>
</div>

### setPrependPath() {#aa309e19361ee14fee735cfff59d67d3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setPrependPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Ppath)</td>
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

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setStatistics() {#a010ff281766fef5c1c343ba71c45f4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setStatistics (bool Statistics)</td>
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

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setSwiftInterfacesMap() {#a216a1d8caddbc127e14e041ed76d6210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setSwiftInterfacesMap (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#ab7230244084c9a0c89b2113444331260">SwiftInterfacesMapTy</a> * Map)</td>
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

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setTargetDWARFVersion() {#aac36499d5ebb7dc9994adee56cf716c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::dwarf_linker::classic::DWARFLinker::setTargetDWARFVersion (uint16_t TargetDWARFVersion)</td>
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

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### setUpdateIndexTablesOnly() {#ab761f2217eadcb15a3a8cd8704345951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setUpdateIndexTablesOnly (bool Update)</td>
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

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### setVerbosity() {#ae7d1b94dba1c04e090a344a1e31888e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setVerbosity (bool Verbose)</td>
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

<p>A number of methods setting various linking options:</p>


<p>Allows to generate log of linking process to the standard output.</p>


<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

### setVerifyInputDWARF() {#a4511f5243766afa68114a68c157c51dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::setVerifyInputDWARF (bool Verify)</td>
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

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a345bd69760b9ee32b3f49d4fc04120fb">Verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cleanupAuxiliarryData() {#a34590575f0376ebbae5463c3cc60c743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::cleanupAuxiliarryData (LinkContext &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called before emitting object data.</p>

<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### copyInvariantDebugSection() {#a86e319465467e3ce1d7ea29415464327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::copyInvariantDebugSection (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; Dwarf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 2689 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### lookForChildDIEsToKeep() {#aeb439c21365779ac39a26f19cc425184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::lookForChildDIEsToKeep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; CU, unsigned Flags, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; WorklistItem &gt; &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look at the children of the given <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and decide whether they should be kept.</p>

<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### lookForParentDIEsToKeep() {#ae3708da9e428050f8e282506451d8046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::lookForParentDIEsToKeep (unsigned AncestorIdx, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; CU, unsigned Flags, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; WorklistItem &gt; &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look at the parent of the given <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and decide whether they should be kept.</p>

<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 810 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### lookForRefDIEsToKeep() {#a1e89c90434c1338539cedff8ca5b97c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::lookForRefDIEsToKeep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; CU, unsigned Flags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/classic/#a15dd9ce2c2728a22611f39c0fdfce567">UnitListTy</a> &amp; Units, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; WorklistItem &gt; &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look at DIEs referenced by the given <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and decide whether they should be kept.</p>


<p>All DIEs referenced though attributes should be kept.</p>


<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### markODRCanonicalDie() {#a8b619a56892640997c9a8d696ee161ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::markODRCanonicalDie (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; Die, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit">CompileUnit</a> &amp; CU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark context corresponding to the specified <span class="doxyComputerOutput">Die</span> as having canonical die, if applicable.</p>

<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 732 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

### needToTranslateStrings() {#a9dfcf9d7db0a21ce196271e480750e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::classic::DWARFLinker::needToTranslateStrings ()</td>
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

<p>returns true if we need to translate strings.</p>

<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### reportError() {#a1ae3d857175c82a13a192d98490e691c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::reportError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Warning, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> * DIE=nullptr)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### reportWarning() {#a2c3c6eb2ee0857c3d6d55f8ba188646b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::classic::DWARFLinker::reportWarning (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Warning, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> * DIE=nullptr)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### verifyInput() {#a385669e7f2cb8235f12f3693ec123f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFLinker::verifyInput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarffile">DWARFFile</a> &amp; File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the given DWARF file.</p>

<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>, definition at line 3068 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AppleNames {#a72efa2f2b84ccbfa80b4ac7f529f0fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTable&lt;AppleAccelTableStaticOffsetData&gt; llvm::dwarf_linker::classic::DWARFLinker::AppleNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### AppleNamespaces {#a7c061d1b674ffbdcc0e1e2287f3e6891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTable&lt;AppleAccelTableStaticOffsetData&gt; llvm::dwarf_linker::classic::DWARFLinker::AppleNamespaces</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### AppleObjc {#a6b0f34dd0b6f04aa4ab188334b3dddb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTable&lt;AppleAccelTableStaticOffsetData&gt; llvm::dwarf_linker::classic::DWARFLinker::AppleObjc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### AppleTypes {#a1440f27f336334a23a0dc4f05fc4f25d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AccelTable&lt;AppleAccelTableStaticTypeData&gt; llvm::dwarf_linker::classic::DWARFLinker::AppleTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### ClangModules {#aa5cdeb7ae46271105ef46d21de94ddc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;uint64_t&gt; llvm::dwarf_linker::classic::DWARFLinker::ClangModules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping the PCM filename to the DwoId.</p>

<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### DebugNames {#aa0395fcf056236a5537cc267e4f582db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARF5AccelTable llvm::dwarf_linker::classic::DWARFLinker::DebugNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apple accelerator tables.</p>

<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### EmittedCIEs {#a2932cb8d50074973bbdc9adc35d41794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;uint32_t&gt; llvm::dwarf_linker::classic::DWARFLinker::EmittedCIEs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The CIEs that have been emitted in the output section.</p>


<p>The actual CIE data serves a the key to this <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>, this takes care of comparing the semantics of CIEs defined in different object files.</p>


<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### ErrorHandler {#a48f74aeb511ba3a1f845c8790e9b0615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MessageHandlerTy llvm::dwarf_linker::classic::DWARFLinker::ErrorHandler = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### LastCIEOffset {#ad783d0a3eb256e858e99e88f912660e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::dwarf_linker::classic::DWARFLinker::LastCIEOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset of the last CIE that has been emitted in the output .debug_frame section.</p>

<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### ObjectContexts {#ad6f7c983f88453183ad9f0cc7e5a653d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;LinkContext&gt; llvm::dwarf_linker::classic::DWARFLinker::ObjectContexts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### Options {#af784ab096506152175a4d2e6cdfc200a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::dwarf_linker::classic::DWARFLinker::DWARFLinkerOptions llvm::dwarf_linker::classic::DWARFLinker::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### StringsTranslator {#a100e3ac356e1699f1648bfb1a5dc182c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;StringRef(StringRef)&gt; llvm::dwarf_linker::classic::DWARFLinker::StringsTranslator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### TheDwarfEmitter {#af04d9d231bad7e179e7736904370fbd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfEmitter* llvm::dwarf_linker::classic::DWARFLinker::TheDwarfEmitter = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### UniqueUnitID {#a684d27971fce3d5980daf565c3bd9083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf_linker::classic::DWARFLinker::UniqueUnitID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> that identifies each compile unit.</p>

<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

### WarningHandler {#a5df071ad3ffef1f8e8afa4655b0de021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MessageHandlerTy llvm::dwarf_linker::classic::DWARFLinker::WarningHandler = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createLinker() {#a978871b5919763e0bf8bfe0fbfca93e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; DWARFLinker &gt; llvm::dwarf_linker::classic::DWARFLinker::createLinker (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> ErrorHandler, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> WarningHandler, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; StringsTranslator=nullptr)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/classic/dwarflinker-h">DWARFLinker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinker-cpp">DWARFLinker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
