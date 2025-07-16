---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/thinltocodegenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ThinLTOCodeGenerator` Class Reference

<p>This class define an interface similar to the <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator">LTOCodeGenerator</a>, but adapted for ThinLTO processing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ThinLTOCodeGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">llvm/LTO/legacy/ThinLTOCodeGenerator.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae11df24f1943d8d885a6cc0f6504b25">addModule</a> (StringRef Identifier, StringRef Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add given module to the code generator. <a href="#aae11df24f1943d8d885a6cc0f6504b25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d863527fbd7b2fe4ca8dc51d6c8d525">preserveSymbol</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds to a list of all global symbols that must exist in the final generated code. <a href="#a0d863527fbd7b2fe4ca8dc51d6c8d525">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc86965bafc089b4e28d6bc3c9b71ab">crossReferenceSymbol</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds to a list of all global symbols that are cross-referenced between ThinLTO files. <a href="#a8fc86965bafc089b4e28d6bc3c9b71ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f109c8e5687e9ee05ee86648c229398">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> all the modules that were added to the code generator in parallel. <a href="#a8f109c8e5687e9ee05ee86648c229398">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f6c6916269fbca6fd4a36fa8435af4">getProducedBinaries</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the "in memory" binaries produced by the code generator. <a href="#a73f6c6916269fbca6fd4a36fa8435af4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7aef709e1748908f580b2a8427c5a0f">getProducedBinaryFiles</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the "on-disk" binaries produced by the code generator. <a href="#ab7aef709e1748908f580b2a8427c5a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/cache/#ga13ac54ea2d670ae2b55c55d552ae2d2d">setCacheDir</a> (std::string Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a path to a directory where to store the cached files for incremental build. <a href="/web-llvm/docs/api/groups/cache/#ga13ac54ea2d670ae2b55c55d552ae2d2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/cache/#ga190f2d73ac70288b5323a0881fa0c727">setCachePruningInterval</a> (int Interval)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache policy: interval (seconds) between two prunes of the cache. <a href="/web-llvm/docs/api/groups/cache/#ga190f2d73ac70288b5323a0881fa0c727">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/cache/#ga5ba128cec363595b8cb8d403509b71d7">setCacheEntryExpiration</a> (unsigned Expiration)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache policy: expiration (in seconds) for an entry. <a href="/web-llvm/docs/api/groups/cache/#ga5ba128cec363595b8cb8d403509b71d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/cache/#ga724a34dbf10eb5f09062e52237ea0e96">setMaxCacheSizeRelativeToAvailableSpace</a> (unsigned Percentage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the maximum cache size that can be persistent across build, in terms of percentage of the available space on the disk. <a href="/web-llvm/docs/api/groups/cache/#ga724a34dbf10eb5f09062e52237ea0e96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/cache/#ga755ef880ddfb2ecdf8b5cae2d611dd78">setCacheMaxSizeBytes</a> (uint64_t MaxSizeBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache policy: the maximum size for the cache directory in bytes. <a href="/web-llvm/docs/api/groups/cache/#ga755ef880ddfb2ecdf8b5cae2d611dd78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/cache/#gaca3298ccd1bd11e22a2119a0868177b4">setCacheMaxSizeFiles</a> (unsigned MaxSizeFiles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache policy: the maximum number of files in the cache directory. <a href="/web-llvm/docs/api/groups/cache/#gaca3298ccd1bd11e22a2119a0868177b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#gaa136b4093ab9375cdb985ba84b2b6a71">setSaveTempsDir</a> (std::string Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the path to a directory where to save temporaries at various stages of the processing. <a href="/web-llvm/docs/api/groups/options/#gaa136b4093ab9375cdb985ba84b2b6a71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#ga206c4e86f664ea1d9690f55146d7c437">setGeneratedObjectsDirectory</a> (std::string Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the path to a directory where to save generated object files. <a href="/web-llvm/docs/api/groups/options/#ga206c4e86f664ea1d9690f55146d7c437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#ga002b5264cecd4bf20432ffad26491a4f">setCpu</a> (std::string Cpu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CPU to use to initialize the <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>. <a href="/web-llvm/docs/api/groups/options/#ga002b5264cecd4bf20432ffad26491a4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#ga513a8c9677e0948d70ea8d5f06fb2673">setAttr</a> (std::string MAttr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtarget attributes. <a href="/web-llvm/docs/api/groups/options/#ga513a8c9677e0948d70ea8d5f06fb2673">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#ga2494878b9789334d74ebe752143c33d9">setTargetOptions</a> (TargetOptions Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> options. <a href="/web-llvm/docs/api/groups/options/#ga2494878b9789334d74ebe752143c33d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#ga61aebfd57af923c49f69294039c528f9">setFreestanding</a> (bool Enabled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable the Freestanding mode: indicate that the optimizer should not assume builtins are present on the target. <a href="/web-llvm/docs/api/groups/options/#ga61aebfd57af923c49f69294039c528f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#gacd35cc2c5ec2db6f34404daefe459982">setCodePICModel</a> (std::optional&lt; Reloc::Model &gt; Model)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/codemodel">CodeModel</a>. <a href="/web-llvm/docs/api/groups/options/#gacd35cc2c5ec2db6f34404daefe459982">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#gaf7173a7c59d405dc4c0584e34a911aba">setCodeGenOptLevel</a> (CodeGenOptLevel CGOptLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CodeGen optimization level. <a href="/web-llvm/docs/api/groups/options/#gaf7173a7c59d405dc4c0584e34a911aba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#ga334de45431629a925ce1574f8f23ef04">setOptLevel</a> (unsigned NewOptLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IR optimization level: from 0 to 3. <a href="/web-llvm/docs/api/groups/options/#ga334de45431629a925ce1574f8f23ef04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#gac980489ed9310beb8f24ce41327b39cd">setDebugPassManager</a> (unsigned Enabled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable or disable debug output for the new pass manager. <a href="/web-llvm/docs/api/groups/options/#gac980489ed9310beb8f24ce41327b39cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#ga0dc161026c3eab1a29f8d0af89900455">disableCodeGen</a> (bool Disable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable CodeGen, only run the stages till codegen and stop. <a href="/web-llvm/docs/api/groups/options/#ga0dc161026c3eab1a29f8d0af89900455">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/options/#gac882e7806c78e388ad420c5940d587e3">setCodeGenOnly</a> (bool CGOnly)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform CodeGen only: disable all other stages. <a href="/web-llvm/docs/api/groups/options/#gac882e7806c78e388ad420c5940d587e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/set/#ga518b1454ef0acf604aa297d534f47c5c">linkCombinedIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the combined summary index from all the bitcode files: "thin-link". <a href="/web-llvm/docs/api/groups/set/#ga518b1454ef0acf604aa297d534f47c5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">promote</a> (Module &amp;Module, ModuleSummaryIndex &amp;Index, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform promotion and renaming of exported internal functions, and additionally resolve weak and linkonce symbols. <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/set/#ga925598c2c1d67f25709f0fcedad5c7ec">emitImports</a> (Module &amp;Module, StringRef OutputName, ModuleSummaryIndex &amp;Index, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and emit the imported files for module at <span class="doxyComputerOutput">ModulePath</span>. <a href="/web-llvm/docs/api/groups/set/#ga925598c2c1d67f25709f0fcedad5c7ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">crossModuleImport</a> (Module &amp;Module, ModuleSummaryIndex &amp;Index, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform cross-module importing for the module identified by ModuleIdentifier. <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/set/#gab2e319464d561a1ba4a0a6d97ba77963">gatherImportedSummariesForModule</a> (Module &amp;Module, ModuleSummaryIndex &amp;Index, ModuleToSummariesForIndexTy &amp;ModuleToSummariesForIndex, GVSummaryPtrSet &amp;DecSummaries, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the list of summaries and the subset of declaration summaries needed for importing into module. <a href="/web-llvm/docs/api/groups/set/#gab2e319464d561a1ba4a0a6d97ba77963">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">internalize</a> (Module &amp;Module, ModuleSummaryIndex &amp;Index, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform internalization. <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/set/#ga123d1e01369e5a25d44c2925ee3087f4">optimize</a> (Module &amp;Module)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform post-importing ThinLTO optimizations. <a href="/web-llvm/docs/api/groups/set/#ga123d1e01369e5a25d44c2925ee3087f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/set/#gacacf298ae33051bd387434c4ebdd2be7">writeGeneratedObject</a> (int count, StringRef CacheEntryPath, const MemoryBuffer &amp;OutputBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write temporary object file to SavedObjectDirectoryPath, write symlink to Cache directory if needed. <a href="/web-llvm/docs/api/groups/set/#gacacf298ae33051bd387434c4ebdd2be7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder">ThinLTOCodeGeneratorImpl::TargetMachineBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e217ce4fe8407fc16b172f370484a4">TMBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper factory to build a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>. <a href="#ad8e217ce4fe8407fc16b172f370484a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf368ac932f7f8761ae0ec036eff6bff">ProducedBinaries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector holding the in-memory buffer containing the produced binaries, when SavedObjectsDirectoryPath isn't set. <a href="#adf368ac932f7f8761ae0ec036eff6bff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea7f0ec3700644b725b4551b2d9c2f0">ProducedBinaryFiles</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Path to generated files in the supplied SavedObjectsDirectoryPath if any. <a href="#a8ea7f0ec3700644b725b4551b2d9c2f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0701bcbb69502c7aec736ee9900e08fa">Modules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector holding the input buffers containing the bitcode modules to process. <a href="#a0701bcbb69502c7aec736ee9900e08fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854c1995ff7a992a7cbd21d06f32390c">PreservedSymbols</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of symbols that need to be preserved outside of the set of bitcode files. <a href="#a854c1995ff7a992a7cbd21d06f32390c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af07e45a625c194cf8547f1dcf3a902b3">CrossReferencedSymbols</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of symbols that are cross-referenced between bitcode files. <a href="#af07e45a625c194cf8547f1dcf3a902b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/thinltocodegenerator/cachingoptions">CachingOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d5677c6d1b189044ca2bf3438f77a9">CacheOptions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Control the caching behavior. <a href="#ad0d5677c6d1b189044ca2bf3438f77a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dbbe0e8861eed330876f6637bf94550">SaveTempsDir</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Path to a directory to save the temporary bitcode files. <a href="#a6dbbe0e8861eed330876f6637bf94550">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960ec5db31338c6e68530fe0887cfc2b">SavedObjectsDirectoryPath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Path to a directory to save the generated object files. <a href="#a960ec5db31338c6e68530fe0887cfc2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd81b366ce76e08089ae119d79f25b59">DisableCodeGen</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to enable/disable CodeGen. <a href="#acd81b366ce76e08089ae119d79f25b59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a051c5f27b8338f03e1312febbf8d8899">CodeGenOnly</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate that only the CodeGen will be performed, no cross-module importing or optimization. <a href="#a051c5f27b8338f03e1312febbf8d8899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea44ea9cded361e8dbad72662c7165f">Freestanding</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate that the optimizer should not assume builtins are present on the target. <a href="#adea44ea9cded361e8dbad72662c7165f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2a1443d327ace20ade21332bc3b219">OptLevel</a> = 3</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IR Optimization Level [0-3]. <a href="#afa2a1443d327ace20ade21332bc3b219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbc6822a176b5f63955c200740b1de16">DebugPassManager</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate whether debug output should be enabled for the new pass manager. <a href="#abbc6822a176b5f63955c200740b1de16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class define an interface similar to the <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator">LTOCodeGenerator</a>, but adapted for ThinLTO processing.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator">ThinLTOCodeGenerator</a> is not intended to be reuse for multiple compilation: the model is that the client adds modules to the generator and ask to perform the ThinLTO optimizations / codegen, and finally destroys the codegenerator.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addModule() {#aae11df24f1943d8d885a6cc0f6504b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::addModule (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add given module to the code generator.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile/#a1aa10be5e2a432c4ca74d5f70c0cd77c">llvm::lto::InputFile::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3378f6544e8a6b129793370d1399c66a">initTMBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

### crossReferenceSymbol() {#a8fc86965bafc089b4e28d6bc3c9b71ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::crossReferenceSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds to a list of all global symbols that are cross-referenced between ThinLTO files.</p>


<p>If the ThinLTO CodeGenerator can ensure that every references from a ThinLTO module to this symbol is optimized away, then the symbol can be discarded.</p>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### getProducedBinaries() {#a73f6c6916269fbca6fd4a36fa8435af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; &amp; llvm::ThinLTOCodeGenerator::getProducedBinaries ()</td>
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

<p>Return the "in memory" binaries produced by the code generator.</p>


<p>This is filled after <a href="#a8f109c8e5687e9ee05ee86648c229398">run()</a> unless <a href="/web-llvm/docs/api/groups/options/#ga206c4e86f664ea1d9690f55146d7c437">setGeneratedObjectsDirectory()</a> has been called, in which case results are available through <a href="#ab7aef709e1748908f580b2a8427c5a0f">getProducedBinaryFiles()</a>.</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### getProducedBinaryFiles() {#ab7aef709e1748908f580b2a8427c5a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::string &gt; &amp; llvm::ThinLTOCodeGenerator::getProducedBinaryFiles ()</td>
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

<p>Return the "on-disk" binaries produced by the code generator.</p>


<p>This is filled after <a href="#a8f109c8e5687e9ee05ee86648c229398">run()</a> when <a href="/web-llvm/docs/api/groups/options/#ga206c4e86f664ea1d9690f55146d7c437">setGeneratedObjectsDirectory()</a> has been called, in which case results are available through <a href="#a73f6c6916269fbca6fd4a36fa8435af4">getProducedBinaries()</a>.</p>


<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### preserveSymbol() {#a0d863527fbd7b2fe4ca8dc51d6c8d525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::preserveSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds to a list of all global symbols that must exist in the final generated code.</p>


<p>If a symbol is not listed there, it will be optimized away if it is inlined into every usage.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### run() {#a8f109c8e5687e9ee05ee86648c229398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> all the modules that were added to the code generator in parallel.</p>


<p>Client can access the resulting object files using <a href="#a73f6c6916269fbca6fd4a36fa8435af4">getProducedBinaries()</a>, unless <a href="/web-llvm/docs/api/groups/options/#ga206c4e86f664ea1d9690f55146d7c437">setGeneratedObjectsDirectory()</a> has been called, in which case results are available through <a href="#ab7aef709e1748908f580b2a8427c5a0f">getProducedBinaryFiles()</a>.</p>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a7d393b2aea23317c9a423e5d99f8e477">addUsedSymbolToPreservedGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface/#ad43d0052f680e6ac08426d8821df178d">llvm::ThreadPoolInterface::async</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ac957aca9f39a415221ac38e85452df90">codegenModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a15f963c10422e290c1e457a23a3f5866">computeDeadSymbolsInIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a6a40037606ad0f2531e3be4dcefa8c0f">computePrevailingCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab0231205adf0a10ac89540dbcfdcd2d7">llvm::sys::fs::create_directories</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a1909824782d47b2c69a0095b5d46f228">generateModuleMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ace97ef2f9463e686abe5c98640efd258">llvm::lto::generateModulesOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a4b3648156c20e8cf63c5eb07c56ab2fe">llvm::Module::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5539cdf767bc394f56b5b8374c6b17d3">llvm::hasWholeProgramVisibility</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01b0ea0a16ef9208a33017ce9399da1a">llvm::heavyweight_hardware_concurrency</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#afed705977bd3f8af4b19b0fd57c0adf4">llvm::sys::fs::is_directory</a>, <a href="/web-llvm/docs/api/groups/set/#ga518b1454ef0acf604aa297d534f47c5c">linkCombinedIndex</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#aeec26ce8d8be46abb3008a9a8e6e9107">loadModuleFromInput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18e129cc13b9fb9f4ac54d2b21e2c37f">llvm::LTODiscardValueNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5094c6f6a737f5a94596cdab0b2b449">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a8e7fe209b55be4dfce7921829e90180c">ProcessThinLTOModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8dbf0a7ff527022e0bc9313961d098d9">llvm::RemarksFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a00aed2787bd3f818d745a1ef171bf3">llvm::RemarksFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2f0e273d7dfee8425f06bc1959a6e36">llvm::RemarksHotnessThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a674af5908403fd9aa59aa8194241f">llvm::RemarksPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b19e8926f03fc73e087818aa81bcb37">llvm::RemarksWithHotness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4fcfca5f1acab67334c771877cd83a21">llvm::reportAndResetTimings</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3f994c8bdcdfb6263bd73746f893cc4f">resolvePrevailingInIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaacad3a6c1410763ede8cd4777304816">llvm::runWholeProgramDevirtOnIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a70182ac5a86e57b12b56cb214b78a8f1">saveTempBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#ab9f1ae83b6064a4d27b44857afd71100">llvm::LLVMContext::setDiscardValueNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#adf0da31fd6ca90efb2819d0f6061bd74">llvm::lto::setupLLVMOptimizationRemarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a64027585b05de2003065bb52d27f729f">llvm::thinLTOInternalizeAndPromoteInIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45395a3dca2e20d0e8dde2d0532ec401">llvm::thinLTOPropagateFunctionAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ac93a706f78069d5f23b6084d9a1fc015">ThreadCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa36dba6382bf8735dc3b034d699c1ab">llvm::timeTraceProfilerBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a549190cfe0e048f25068f4532398fc">llvm::timeTraceProfilerEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d90de68ff5b5762833013e83e14bec5">llvm::timeTraceProfilerEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec46c5d3e8bc9ca6f20307b0316a0d7">llvm::updateIndexWPDForExports</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd7183ed1f5714cb7bf4938caa56b9cf">llvm::updateVCallVisibilityInIndex</a>, <a href="/web-llvm/docs/api/groups/set/#gacacf298ae33051bd387434c4ebdd2be7">writeGeneratedObject</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CacheOptions {#ad0d5677c6d1b189044ca2bf3438f77a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CachingOptions llvm::ThinLTOCodeGenerator::CacheOptions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Control the caching behavior.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### CodeGenOnly {#a051c5f27b8338f03e1312febbf8d8899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ThinLTOCodeGenerator::CodeGenOnly = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate that only the CodeGen will be performed, no cross-module importing or optimization.</p>

<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### CrossReferencedSymbols {#af07e45a625c194cf8547f1dcf3a902b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::ThinLTOCodeGenerator::CrossReferencedSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of symbols that are cross-referenced between bitcode files.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### DebugPassManager {#abbc6822a176b5f63955c200740b1de16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ThinLTOCodeGenerator::DebugPassManager = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate whether debug output should be enabled for the new pass manager.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### DisableCodeGen {#acd81b366ce76e08089ae119d79f25b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ThinLTOCodeGenerator::DisableCodeGen = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to enable/disable CodeGen.</p>


<p>When set to true, the process stops after optimizations and a bitcode is produced.</p>


<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### Freestanding {#adea44ea9cded361e8dbad72662c7165f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ThinLTOCodeGenerator::Freestanding = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate that the optimizer should not assume builtins are present on the target.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### Modules {#a0701bcbb69502c7aec736ee9900e08fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;lto::InputFile&gt; &gt; llvm::ThinLTOCodeGenerator::Modules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector holding the input buffers containing the bitcode modules to process.</p>

<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### OptLevel {#afa2a1443d327ace20ade21332bc3b219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ThinLTOCodeGenerator::OptLevel = 3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IR Optimization Level [0-3].</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### PreservedSymbols {#a854c1995ff7a992a7cbd21d06f32390c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::ThinLTOCodeGenerator::PreservedSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of symbols that need to be preserved outside of the set of bitcode files.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### ProducedBinaries {#adf368ac932f7f8761ae0ec036eff6bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;MemoryBuffer&gt; &gt; llvm::ThinLTOCodeGenerator::ProducedBinaries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector holding the in-memory buffer containing the produced binaries, when SavedObjectsDirectoryPath isn't set.</p>

<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### ProducedBinaryFiles {#a8ea7f0ec3700644b725b4551b2d9c2f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::ThinLTOCodeGenerator::ProducedBinaryFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Path to generated files in the supplied SavedObjectsDirectoryPath if any.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### SavedObjectsDirectoryPath {#a960ec5db31338c6e68530fe0887cfc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ThinLTOCodeGenerator::SavedObjectsDirectoryPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Path to a directory to save the generated object files.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### SaveTempsDir {#a6dbbe0e8861eed330876f6637bf94550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::ThinLTOCodeGenerator::SaveTempsDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Path to a directory to save the temporary bitcode files.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

### TMBuilder {#ad8e217ce4fe8407fc16b172f370484a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThinLTOCodeGeneratorImpl::TargetMachineBuilder llvm::ThinLTOCodeGenerator::TMBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper factory to build a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
