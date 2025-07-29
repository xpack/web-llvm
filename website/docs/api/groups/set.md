---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/set
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# of APIs to run individual stages in isolation



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga518b1454ef0acf604aa297d534f47c5c">linkCombinedIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce the combined summary index from all the bitcode files: "thin-link". <a href="#ga518b1454ef0acf604aa297d534f47c5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac8d7927c4bf52374bb20fa31df9c5b22">promote</a> (Module &amp;Module, ModuleSummaryIndex &amp;Index, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform promotion and renaming of exported internal functions, and additionally resolve weak and linkonce symbols. <a href="#gac8d7927c4bf52374bb20fa31df9c5b22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga925598c2c1d67f25709f0fcedad5c7ec">emitImports</a> (Module &amp;Module, StringRef OutputName, ModuleSummaryIndex &amp;Index, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute and emit the imported files for module at <span class="doxyComputerOutput">ModulePath</span>. <a href="#ga925598c2c1d67f25709f0fcedad5c7ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga68e4901342bb8259cdcea4761207f967">crossModuleImport</a> (Module &amp;Module, ModuleSummaryIndex &amp;Index, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform cross-module importing for the module identified by ModuleIdentifier. <a href="#ga68e4901342bb8259cdcea4761207f967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab2e319464d561a1ba4a0a6d97ba77963">gatherImportedSummariesForModule</a> (Module &amp;Module, ModuleSummaryIndex &amp;Index, ModuleToSummariesForIndexTy &amp;ModuleToSummariesForIndex, GVSummaryPtrSet &amp;DecSummaries, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the list of summaries and the subset of declaration summaries needed for importing into module. <a href="#gab2e319464d561a1ba4a0a6d97ba77963">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaaa991901a8631f1c351289f5b59b2604">internalize</a> (Module &amp;Module, ModuleSummaryIndex &amp;Index, const lto::InputFile &amp;File)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform internalization. <a href="#gaaa991901a8631f1c351289f5b59b2604">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga123d1e01369e5a25d44c2925ee3087f4">optimize</a> (Module &amp;Module)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform post-importing ThinLTO optimizations. <a href="#ga123d1e01369e5a25d44c2925ee3087f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacacf298ae33051bd387434c4ebdd2be7">writeGeneratedObject</a> (int count, StringRef CacheEntryPath, const MemoryBuffer &amp;OutputBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write temporary object file to SavedObjectDirectoryPath, write symlink to Cache directory if needed. <a href="#gacacf298ae33051bd387434c4ebdd2be7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### crossModuleImport() {#ga68e4901342bb8259cdcea4761207f967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::crossModuleImport (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Module, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &amp; File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform cross-module importing for the module identified by ModuleIdentifier.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a7d393b2aea23317c9a423e5d99f8e477">addUsedSymbolToPreservedGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a15f963c10422e290c1e457a23a3f5866">computeDeadSymbolsInIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a6a40037606ad0f2531e3be4dcefa8c0f">computePrevailingCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a0386198cbc9986aa5b45f21b24b0902d">crossImportIntoModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a1909824782d47b2c69a0095b5d46f228">generateModuleMap</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a9a4fa55f19f0d5bb47d1fe6802e18d1a">llvm::Module::getModuleIdentifier</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a>.</p>

</div>
</div>

### emitImports() {#ga925598c2c1d67f25709f0fcedad5c7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::emitImports (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Module, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OutputName, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &amp; File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute and emit the imported files for module at <span class="doxyComputerOutput">ModulePath</span>.</p>


<p>Emit the list of files needed for importing into module.</p>


<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a7d393b2aea23317c9a423e5d99f8e477">addUsedSymbolToPreservedGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a15f963c10422e290c1e457a23a3f5866">computeDeadSymbolsInIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a6a40037606ad0f2531e3be4dcefa8c0f">computePrevailingCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1ad9f56998b03b32a1066b574125126">llvm::EmitImportsFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab60fb2b8daf585b91052154f52ce345e">llvm::gatherImportedSummariesForModule</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a9a4fa55f19f0d5bb47d1fe6802e18d1a">llvm::Module::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### gatherImportedSummariesForModule() {#gab2e319464d561a1ba4a0a6d97ba77963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::gatherImportedSummariesForModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Module, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/namespaces/llvm/#a855e9319bbdff7f7c70bb2b2c5a0650e">ModuleToSummariesForIndexTy</a> &amp; ModuleToSummariesForIndex, <a href="/web-llvm/docs/api/namespaces/llvm/#a126f52d391b28545496b57f7de17fc61">GVSummaryPtrSet</a> &amp; DecSummaries, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &amp; File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the list of summaries and the subset of declaration summaries needed for importing into module.</p>


<p>Compute the list of summaries needed for importing into module.</p>


<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a7d393b2aea23317c9a423e5d99f8e477">addUsedSymbolToPreservedGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a15f963c10422e290c1e457a23a3f5866">computeDeadSymbolsInIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a6a40037606ad0f2531e3be4dcefa8c0f">computePrevailingCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab60fb2b8daf585b91052154f52ce345e">llvm::gatherImportedSummariesForModule</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a9a4fa55f19f0d5bb47d1fe6802e18d1a">llvm::Module::getModuleIdentifier</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a>.</p>

</div>
</div>

### internalize() {#gaaa991901a8631f1c351289f5b59b2604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::internalize (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &amp; File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform internalization.</p>


<p>Index is updated to reflect linkage changes.</p>


<p>Runs promote and internalization together. Index is updated to reflect linkage changes.</p>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 848 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a7d393b2aea23317c9a423e5d99f8e477">addUsedSymbolToPreservedGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a15f963c10422e290c1e457a23a3f5866">computeDeadSymbolsInIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a6a40037606ad0f2531e3be4dcefa8c0f">computePrevailingCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a9a4fa55f19f0d5bb47d1fe6802e18d1a">llvm::Module::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3378f6544e8a6b129793370d1399c66a">initTMBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#afbc72f9324d841fc9dc26f1c5acf8e7b">promoteModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3f994c8bdcdfb6263bd73746f893cc4f">resolvePrevailingInIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a64027585b05de2003065bb52d27f729f">llvm::thinLTOInternalizeAndPromoteInIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac69630533101ec5ba74953a63082148">llvm::thinLTOInternalizeModule</a>.</p>

</div>
</div>

### linkCombinedIndex() {#ga518b1454ef0acf604aa297d534f47c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ModuleSummaryIndex &gt; ThinLTOCodeGenerator::linkCombinedIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produce the combined summary index from all the bitcode files: "thin-link".</p>

<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### optimize() {#ga123d1e01369e5a25d44c2925ee3087f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::optimize (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Module)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform post-importing ThinLTO optimizations.</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3378f6544e8a6b129793370d1399c66a">initTMBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>.</p>

</div>
</div>

### promote() {#gac8d7927c4bf52374bb20fa31df9c5b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThinLTOCodeGenerator::promote (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &amp; File)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform promotion and renaming of exported internal functions, and additionally resolve weak and linkonce symbols.</p>


<p>Perform promotion and renaming of exported internal functions.</p>


<p>Index is updated to reflect linkage changes from weak resolution.</p>


<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a7d393b2aea23317c9a423e5d99f8e477">addUsedSymbolToPreservedGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a15f963c10422e290c1e457a23a3f5866">computeDeadSymbolsInIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a6a40037606ad0f2531e3be4dcefa8c0f">computePrevailingCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a9a4fa55f19f0d5bb47d1fe6802e18d1a">llvm::Module::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#afbc72f9324d841fc9dc26f1c5acf8e7b">promoteModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3f994c8bdcdfb6263bd73746f893cc4f">resolvePrevailingInIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a64027585b05de2003065bb52d27f729f">llvm::thinLTOInternalizeAndPromoteInIndex</a>.</p>

</div>
</div>

### writeGeneratedObject() {#gacacf298ae33051bd387434c4ebdd2be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ThinLTOCodeGenerator::writeGeneratedObject (int count, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CacheEntryPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; OutputBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write temporary object file to SavedObjectDirectoryPath, write symlink to Cache directory if needed.</p>


<p>Write out the generated object file, either from CacheEntryPath or from <a href="/web-llvm/docs/api/classes/outputbuffer">OutputBuffer</a>, preferring hard-link when possible.</p>


<p>Returns the path to the generated file in SavedObjectsDirectoryPath.</p>


<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">ThinLTOCodeGenerator.h</a>, definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ade4b8410fbe0406fc61d1db65d1cfa12">llvm::SmallString&lt; InternalLen &gt;::c_str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#abe768b38d21bfc2bc91a1c1d09cd84de">llvm::sys::fs::copy_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a7b6517c7c19fb371459c1aae5cacdcf6">llvm::sys::fs::create_hard_link</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a645a607ffcccb12f16a5736db991e7d9">llvm::sys::fs::exists</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#a8ab399f586318b61b6a38a18adbb098f">OutputBuffer::getBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
