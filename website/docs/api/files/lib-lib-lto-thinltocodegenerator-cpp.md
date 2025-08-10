---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/lto/thinltocodegenerator-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ThinLTOCodeGenerator.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/thinltocodegenerator-h">llvm/LTO/legacy/ThinLTOCodeGenerator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/modulesummaryanalysis-h">llvm/Analysis/ModuleSummaryAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">llvm/Bitcode/BitcodeWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriterpass-h">llvm/Bitcode/BitcodeWriterPass.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticprinter-h">llvm/IR/DiagnosticPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">llvm/IR/LLVMRemarkStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">llvm/IR/Mangler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passtiminginfo-h">llvm/IR/PassTimingInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/irreader/irreader-h">llvm/IRReader/IRReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">llvm/LTO/LTO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irobjectfile-h">llvm/Object/IRObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">llvm/Passes/StandardInstrumentations.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/hotnessthresholdparser-h">llvm/Remarks/HotnessThresholdParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cachepruning-h">llvm/Support/CachePruning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sha1-h">llvm/Support/SHA1.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smallvectormemorybuffer-h">llvm/Support/SmallVectorMemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">llvm/Support/ThreadPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">llvm/Support/Threading.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">llvm/Support/ToolOutputFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionattrs-h">llvm/Transforms/IPO/FunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">llvm/Transforms/IPO/FunctionImport.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/internalize-h">llvm/Transforms/IPO/Internalize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">llvm/Transforms/IPO/WholeProgramDevirt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/objcarc-h">llvm/Transforms/ObjCARC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">llvm/Transforms/Utils/FunctionImportUtils.h</a>"
#include &lt;numeric&gt;
#include &lt;unistd.h&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-thinltocodegenerator-cpp-">anonymous{ThinLTOCodeGenerator.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/thinltodiagnosticinfo">ThinLTODiagnosticInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry">ModuleCacheEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Manage caching for a single <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-thinltocodegenerator-cpp-/isexported">IsExported</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-thinltocodegenerator-cpp-/isprevailing">IsPrevailing</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70182ac5a86e57b12b56cb214b78a8f1">saveTempBitcode</a> (const Module &amp;TheModule, StringRef TempDir, unsigned count, StringRef Suffix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00c22607d77d29f2f949fe7a1359e5f">getFirstDefinitionForLinker</a> (const GlobalValueSummaryList &amp;GVSummaryList)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a40037606ad0f2531e3be4dcefa8c0f">computePrevailingCopies</a> (const ModuleSummaryIndex &amp;Index, DenseMap&lt; GlobalValue::GUID, const GlobalValueSummary * &gt; &amp;PrevailingCopy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1909824782d47b2c69a0095b5d46f228">generateModuleMap</a> (std::vector&lt; std::unique_ptr&lt; lto::InputFile &gt; &gt; &amp;Modules)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc72f9324d841fc9dc26f1c5acf8e7b">promoteModule</a> (Module &amp;TheModule, const ModuleSummaryIndex &amp;Index, bool ClearDSOLocalOnDeclarations)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e8066b76cac14a0fcadde226f9bf9d">verifyLoadedModule</a> (Module &amp;TheModule)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the module and strip broken debug info. <a href="#a76e8066b76cac14a0fcadde226f9bf9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec26ce8d8be46abb3008a9a8e6e9107">loadModuleFromInput</a> (lto::InputFile *Input, LLVMContext &amp;Context, bool Lazy, bool IsImporting)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0386198cbc9986aa5b45f21b24b0902d">crossImportIntoModule</a> (Module &amp;TheModule, const ModuleSummaryIndex &amp;Index, StringMap&lt; lto::InputFile * &gt; &amp;ModuleMap, const FunctionImporter::ImportMapTy &amp;ImportList, bool ClearDSOLocalOnDeclarations)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a> (Module &amp;TheModule, TargetMachine &amp;TM, unsigned OptLevel, bool Freestanding, bool DebugPassManager, ModuleSummaryIndex *Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d393b2aea23317c9a423e5d99f8e477">addUsedSymbolToPreservedGUID</a> (const lto::InputFile &amp;File, DenseSet&lt; GlobalValue::GUID &gt; &amp;PreservedGUID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a> (const lto::InputFile &amp;File, const StringSet&lt;&gt; &amp;PreservedSymbols, const Triple &amp;TheTriple, DenseSet&lt; GlobalValue::GUID &gt; &amp;GUIDs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac431323a9a7e840d80cb054493f6067">computeGUIDPreservedSymbols</a> (const lto::InputFile &amp;File, const StringSet&lt;&gt; &amp;PreservedSymbols, const Triple &amp;TheTriple)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac957aca9f39a415221ac38e85452df90">codegenModule</a> (Module &amp;TheModule, TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e7fe209b55be4dfce7921829e90180c">ProcessThinLTOModule</a> (Module &amp;TheModule, ModuleSummaryIndex &amp;Index, StringMap&lt; lto::InputFile * &gt; &amp;ModuleMap, TargetMachine &amp;TM, const FunctionImporter::ImportMapTy &amp;ImportList, const FunctionImporter::ExportSetTy &amp;ExportList, const DenseSet&lt; GlobalValue::GUID &gt; &amp;GUIDPreservedSymbols, const GVSummaryMapTy &amp;DefinedGlobals, const ThinLTOCodeGenerator::CachingOptions &amp;CacheOptions, bool DisableCodeGen, StringRef SaveTempsDir, bool Freestanding, unsigned OptLevel, unsigned count, bool DebugPassManager)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f994c8bdcdfb6263bd73746f893cc4f">resolvePrevailingInIndex</a> (ModuleSummaryIndex &amp;Index, StringMap&lt; std::map&lt; GlobalValue::GUID, GlobalValue::LinkageTypes &gt; &gt; &amp;ResolvedODR, const DenseSet&lt; GlobalValue::GUID &gt; &amp;GUIDPreservedSymbols, const DenseMap&lt; GlobalValue::GUID, const GlobalValueSummary * &gt; &amp;PrevailingCopy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve prevailing symbols. <a href="#a3f994c8bdcdfb6263bd73746f893cc4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3378f6544e8a6b129793370d1399c66a">initTMBuilder</a> (TargetMachineBuilder &amp;TMBuilder, const Triple &amp;TheTriple)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15f963c10422e290c1e457a23a3f5866">computeDeadSymbolsInIndex</a> (ModuleSummaryIndex &amp;Index, const DenseSet&lt; GlobalValue::GUID &gt; &amp;GUIDPreservedSymbols)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93a706f78069d5f23b6084d9a1fc015">ThreadCount</a>("threads", cl::init(0))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"thinlto"</td>
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

## Functions

### addUsedSymbolToPreservedGUID() {#a7d393b2aea23317c9a423e5d99f8e477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addUsedSymbolToPreservedGUID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &amp; File, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; PreservedGUID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">llvm::ThinLTOCodeGenerator::crossModuleImport</a>, <a href="/web-llvm/docs/api/groups/set/#ga925598c2c1d67f25709f0fcedad5c7ec">llvm::ThinLTOCodeGenerator::emitImports</a>, <a href="/web-llvm/docs/api/groups/set/#gab2e319464d561a1ba4a0a6d97ba77963">llvm::ThinLTOCodeGenerator::gatherImportedSummariesForModule</a>, <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a>, <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">llvm::ThinLTOCodeGenerator::promote</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### codegenModule() {#ac957aca9f39a415221ac38e85452df90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; codegenModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260a95aca07e95d9459c1bb31f4e7f9fda10">llvm::ObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager/#a2bdbe49f025814f15cd9c82aa08a389b">llvm::legacy::PassManager::run</a>.</p>


<p>Referenced by <a href="#a8e7fe209b55be4dfce7921829e90180c">ProcessThinLTOModule</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### computeDeadSymbolsInIndex() {#a15f963c10422e290c1e457a23a3f5866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeDeadSymbolsInIndex (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; GUIDPreservedSymbols)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee23fa24e474fb6e443445dd3545adf9">llvm::computeDeadSymbolsWithConstProp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac505d74d262ee1e64d87b07121199e36a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">llvm::ThinLTOCodeGenerator::crossModuleImport</a>, <a href="/web-llvm/docs/api/groups/set/#ga925598c2c1d67f25709f0fcedad5c7ec">llvm::ThinLTOCodeGenerator::emitImports</a>, <a href="/web-llvm/docs/api/groups/set/#gab2e319464d561a1ba4a0a6d97ba77963">llvm::ThinLTOCodeGenerator::gatherImportedSummariesForModule</a>, <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a>, <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">llvm::ThinLTOCodeGenerator::promote</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### computeGUIDPreservedSymbols() {#ae469e045889685a1288b208a6d85b948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeGUIDPreservedSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &amp; File, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a>&lt;&gt; &amp; PreservedSymbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; GUIDs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9f44684437922cc04a01fcdcc73215d0">llvm::GlobalValue::getGlobalIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#a5d3148194a32572950fd9e753555a101">PreservedSymbols</a>.</p>


<p>Referenced by <a href="#aac431323a9a7e840d80cb054493f6067">computeGUIDPreservedSymbols</a>, <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">llvm::ThinLTOCodeGenerator::crossModuleImport</a>, <a href="/web-llvm/docs/api/groups/set/#ga925598c2c1d67f25709f0fcedad5c7ec">llvm::ThinLTOCodeGenerator::emitImports</a>, <a href="/web-llvm/docs/api/groups/set/#gab2e319464d561a1ba4a0a6d97ba77963">llvm::ThinLTOCodeGenerator::gatherImportedSummariesForModule</a>, <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a>, <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">llvm::ThinLTOCodeGenerator::promote</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### computeGUIDPreservedSymbols() {#aac431323a9a7e840d80cb054493f6067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt; GlobalValue::GUID &gt; computeGUIDPreservedSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &amp; File, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a>&lt;&gt; &amp; PreservedSymbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="#ae469e045889685a1288b208a6d85b948">computeGUIDPreservedSymbols</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/irsymtab-cpp/#a5d3148194a32572950fd9e753555a101">PreservedSymbols</a>.</p>

</div>
</div>

### computePrevailingCopies() {#a6a40037606ad0f2531e3be4dcefa8c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computePrevailingCopies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> * &gt; &amp; PrevailingCopy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="#af00c22607d77d29f2f949fe7a1359e5f">getFirstDefinitionForLinker</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">llvm::ThinLTOCodeGenerator::crossModuleImport</a>, <a href="/web-llvm/docs/api/groups/set/#ga925598c2c1d67f25709f0fcedad5c7ec">llvm::ThinLTOCodeGenerator::emitImports</a>, <a href="/web-llvm/docs/api/groups/set/#gab2e319464d561a1ba4a0a6d97ba77963">llvm::ThinLTOCodeGenerator::gatherImportedSummariesForModule</a>, <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a>, <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">llvm::ThinLTOCodeGenerator::promote</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### crossImportIntoModule() {#a0386198cbc9986aa5b45f21b24b0902d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void crossImportIntoModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> * &gt; &amp; ModuleMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, bool ClearDSOLocalOnDeclarations)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/module/#a0beddb53641a541e2238617c5fac4be7">llvm::Module::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="#aeec26ce8d8be46abb3008a9a8e6e9107">loadModuleFromInput</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="#a76e8066b76cac14a0fcadde226f9bf9d">verifyLoadedModule</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">llvm::ThinLTOCodeGenerator::crossModuleImport</a> and <a href="#a8e7fe209b55be4dfce7921829e90180c">ProcessThinLTOModule</a>.</p>

</div>
</div>

### generateModuleMap() {#a1909824782d47b2c69a0095b5d46f228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt; lto::InputFile * &gt; generateModuleMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> &gt; &gt; &amp; Modules)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a5bdab9e85b82bae5a3470d4fa0cf574c">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">llvm::ThinLTOCodeGenerator::crossModuleImport</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### getFirstDefinitionForLinker() {#af00c22607d77d29f2f949fe7a1359e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValueSummary * getFirstDefinitionForLinker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a192f4adb1918a2fb2b951e0d99762568">GlobalValueSummaryList</a> &amp; GVSummaryList)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a578061260691a59a9e7b0455fd68359c">llvm::GlobalValue::isAvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac0495132fc83c026033c62c59b30489f">llvm::GlobalValue::isWeakForLinker</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilfinalizelinkage-cpp/#ae721973516c2b86042a5127b776e2806">Linkage</a>.</p>


<p>Referenced by <a href="#a6a40037606ad0f2531e3be4dcefa8c0f">computePrevailingCopies</a>.</p>

</div>
</div>

### initTMBuilder() {#a3378f6544e8a6b129793370d1399c66a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initTMBuilder (<a href="/web-llvm/docs/api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder">TargetMachineBuilder</a> &amp; TMBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a7d269a83a714b7924ac1d67e52655c73">llvm::lto::getThinLTODefaultCPU</a>, <a href="/web-llvm/docs/api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder/#a06cf12c8177f10834c0aead2763f9120">llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::MCpu</a> and <a href="/web-llvm/docs/api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder/#a3d090359baa2bc30408e907adda03fac">llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::TheTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#aae11df24f1943d8d885a6cc0f6504b25">llvm::ThinLTOCodeGenerator::addModule</a>, <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a> and <a href="/web-llvm/docs/api/groups/set/#ga123d1e01369e5a25d44c2925ee3087f4">llvm::ThinLTOCodeGenerator::optimize</a>.</p>

</div>
</div>

### loadModuleFromInput() {#aeec26ce8d8be46abb3008a9a8e6e9107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Module &gt; loadModuleFromInput (<a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> * Input, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, bool Lazy, bool IsImporting)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#a76e8066b76cac14a0fcadde226f9bf9d">verifyLoadedModule</a>.</p>


<p>Referenced by <a href="#a0386198cbc9986aa5b45f21b24b0902d">crossImportIntoModule</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### optimizeModule() {#ae1b1fc686e5285c37b8f51cab4d213f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void optimizeModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, unsigned OptLevel, bool Freestanding, bool DebugPassManager, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a13293a681188ed79fb799b7f9c173b83">CGAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a0beddb53641a541e2238617c5fac4be7">llvm::Module::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a7cfe61417446ebb812e81293bde22a29">LAM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions/#af94d30491218ab25314dbff8123a9de7">llvm::PipelineTuningOptions::LoopVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#acfab17afad8d19eb90de02e684900ccd">llvm::OptimizationLevel::O1</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a9c0836ff9219a0b737a11979991c3389">llvm::OptimizationLevel::O2</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a097296a5feaefc188dafa71b19204714">llvm::OptimizationLevel::O3</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a> and <a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions/#a2e37acc197f406344af4c2f1c94998dc">llvm::PipelineTuningOptions::SLPVectorization</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#ga123d1e01369e5a25d44c2925ee3087f4">llvm::ThinLTOCodeGenerator::optimize</a> and <a href="#a8e7fe209b55be4dfce7921829e90180c">ProcessThinLTOModule</a>.</p>

</div>
</div>

### ProcessThinLTOModule() {#a8e7fe209b55be4dfce7921829e90180c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; ProcessThinLTOModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">lto::InputFile</a> * &gt; &amp; ModuleMap, <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &amp; ExportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; GUIDPreservedSymbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &amp; DefinedGlobals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/thinltocodegenerator/cachingoptions">ThinLTOCodeGenerator::CachingOptions</a> &amp; CacheOptions, bool DisableCodeGen, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SaveTempsDir, bool Freestanding, unsigned OptLevel, unsigned count, bool DebugPassManager)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>, <a href="#ac957aca9f39a415221ac38e85452df90">codegenModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="#a0386198cbc9986aa5b45f21b24b0902d">crossImportIntoModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pielevel/#ae01fe422624f3a5afd84d14146f9112ca0b4e3e20dca8947e14cee3d5fe0e4fa8">llvm::PIELevel::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#af3295ffffcff40d7c95aa9fb4d13256a">llvm::Module::getPIELevel</a>, <a href="#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="#afbc72f9324d841fc9dc26f1c5acf8e7b">promoteModule</a>, <a href="#a70182ac5a86e57b12b56cb214b78a8f1">saveTempBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a80596ea56fa14ea5a773d303ee64293c">llvm::StringMapImpl::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac69630533101ec5ba74953a63082148">llvm::thinLTOInternalizeModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a714c6f3608e37d0dba17cdc086dc16d2">llvm::updatePublicTypeTestCalls</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### promoteModule() {#afbc72f9324d841fc9dc26f1c5acf8e7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void promoteModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, bool ClearDSOLocalOnDeclarations)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a46122434c47e17760d4c6709878a0dd6">llvm::renameModuleForThinLTO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a>, <a href="#a8e7fe209b55be4dfce7921829e90180c">ProcessThinLTOModule</a> and <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">llvm::ThinLTOCodeGenerator::promote</a>.</p>

</div>
</div>

### resolvePrevailingInIndex() {#a3f994c8bdcdfb6263bd73746f893cc4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void resolvePrevailingInIndex (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt; &gt; &amp; ResolvedODR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; GUIDPreservedSymbols, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> * &gt; &amp; PrevailingCopy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Resolve prevailing symbols.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> resolutions in the <span class="doxyComputerOutput">ResolvedODR</span> map for caching, and in the <span class="doxyComputerOutput">Index</span> for application during the ThinLTO backends. This is needed for correctness for exported symbols (ensure at least one copy kept) and a compile-time optimization (to drop duplicate copies when possible).</p>


<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8fe180d4941e5904b897d39db5c25796">llvm::thinLTOResolvePrevailingInIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a>, <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">llvm::ThinLTOCodeGenerator::promote</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### saveTempBitcode() {#a70182ac5a86e57b12b56cb214b78a8f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void saveTempBitcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TempDir, unsigned count, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Suffix)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>


<p>Referenced by <a href="#a8e7fe209b55be4dfce7921829e90180c">ProcessThinLTOModule</a> and <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### verifyLoadedModule() {#a76e8066b76cac14a0fcadde226f9bf9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void verifyLoadedModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the module and strip broken debug info.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aad03ef5cfbe6e7cad076d9e45ba06592">llvm::LLVMContext::diagnose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a0beddb53641a541e2238617c5fac4be7">llvm::Module::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b2f025559a0b80366b74285cf25c01e">llvm::StripDebugInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/thinltodiagnosticinfo/#abac1d7492cb02cfcb72002ac598aca73">anonymous{ThinLTOCodeGenerator.cpp}::ThinLTODiagnosticInfo::ThinLTODiagnosticInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af8c14262d42a312c9026452162c9e0a6">llvm::verifyModule</a>.</p>


<p>Referenced by <a href="#a0386198cbc9986aa5b45f21b24b0902d">crossImportIntoModule</a> and <a href="#aeec26ce8d8be46abb3008a9a8e6e9107">loadModuleFromInput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ThreadCount {#ac93a706f78069d5f23b6084d9a1fc015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; ThreadCount("threads", cl::init(0))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a00440f10281348fd9f7be52e23c7c874">llvm::hardware_concurrency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01b0ea0a16ef9208a33017ce9399da1a">llvm::heavyweight_hardware_concurrency</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>, <a href="/web-llvm/docs/api/classes/llvm/singlethreadexecutor/#a3a0e760e0380aa0023a27372d5ffd4dc">llvm::SingleThreadExecutor::SingleThreadExecutor</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a2fad224b57541514de4fb5be6eb2e7f1">splitCodeGen</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"thinlto"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp">ThinLTOCodeGenerator.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
