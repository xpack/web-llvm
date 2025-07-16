---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `FunctionImport.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/functionimport-h">llvm/Transforms/IPO/FunctionImport.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/autoupgrade-h">llvm/IR/AutoUpgrade.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalobject-h">llvm/IR/GlobalObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/irreader/irreader-h">llvm/IRReader/IRReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/irmover-h">llvm/Linker/IRMover.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofreader-h">llvm/ProfileData/PGOCtxProfReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">llvm/Support/JSON.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/internalize-h">llvm/Transforms/IPO/Internalize.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">llvm/Transforms/Utils/FunctionImportUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">llvm/Transforms/Utils/ValueMapper.h</a>"
#include &lt;cassert&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;system_error&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-functionimport-cpp-">anonymous{FunctionImport.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/globalsimporter">GlobalsImporter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Import globals referenced by a function or other globals that are being imported, if importing such global is possible. <a href="/web-llvm/docs/api/classes/globalsimporter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/moduleimportsmanager">ModuleImportsManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the list of imports and exports for each module. <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/workloadimportsmanager">WorkloadImportsManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/moduleimportsmanager">ModuleImportsManager</a> that operates based on a workload definition (see -thinlto-workload-def). <a href="/web-llvm/docs/api/classes/workloadimportsmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/importstatistics">ImportStatistics</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21805cf0d5ec7bac4993364076570c0b">STATISTIC</a> (NumImportedFunctionsThinLink, "Number of functions thin link decided to import")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a040db9e0ceac76a1cb31b961e9452f23">STATISTIC</a> (NumImportedHotFunctionsThinLink, "Number of hot functions thin link decided to import")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce7860b8f01180c08bd27a9b97b7563">STATISTIC</a> (NumImportedCriticalFunctionsThinLink, "Number of critical functions thin link decided to import")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653029fa977ee38456e959db15ea0a25">STATISTIC</a> (NumImportedGlobalVarsThinLink, "Number of global variables thin link decided to import")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41f09b63be5a651e3a9bd2408a50ecb7">STATISTIC</a> (NumImportedFunctions, "Number of functions imported in backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72482562440a5f1735c6bd4518668181">STATISTIC</a> (NumImportedGlobalVars, "Number of global variables imported in backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c905e133f4f08e028ae6566aac21fa7">STATISTIC</a> (NumImportedModules, "Number of modules imported from")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af73c9358a3f01dd9f052706697e873e8">STATISTIC</a> (NumDeadSymbols, "Number of dead stripped symbols in index")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e62c84e9b2f35dc18bb717092d37bac">STATISTIC</a> (NumLiveSymbols, "Number of live symbols in index")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd36a34ea4adceda5576292e50cf883">loadFile</a> (const std::string &amp;FileName, LLVMContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95dfbc76e4eb1f6655f38f2a17e691b3">shouldSkipLocalInAnotherModule</a> (const GlobalValueSummary *RefSummary, size_t NumDefs, StringRef ImporterModule)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05678176a857aaca26eac45ab65dc3b1">qualifyCalleeCandidates</a> (const ModuleSummaryIndex &amp;Index, ArrayRef&lt; std::unique_ptr&lt; GlobalValueSummary &gt; &gt; CalleeSummaryList, StringRef CallerModulePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a list of possible callee implementation for a call site, qualify the legality of importing each. <a href="#a05678176a857aaca26eac45ab65dc3b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf7bc15ca5b5a3f6a528f4ab6d8b5c14">selectCallee</a> (const ModuleSummaryIndex &amp;Index, ArrayRef&lt; std::unique_ptr&lt; GlobalValueSummary &gt; &gt; CalleeSummaryList, unsigned Threshold, StringRef CallerModulePath, const GlobalValueSummary *&amp;TooLargeOrNoInlineSummary, FunctionImporter::ImportFailureReason &amp;Reason)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a list of possible callee implementation for a call site, select one that fits the <span class="doxyComputerOutput">Threshold</span> for function definition import. <a href="#adf7bc15ca5b5a3f6a528f4ab6d8b5c14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c93b13860b1955fb9b1359b4dea6855">getFailureName</a> (FunctionImporter::ImportFailureReason Reason)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a> (const FunctionSummary &amp;Summary, const ModuleSummaryIndex &amp;Index, const unsigned Threshold, const GVSummaryMapTy &amp;DefinedGVSummaries, function_ref&lt; bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; isPrevailing, SmallVectorImpl&lt; EdgeInfo &gt; &amp;Worklist, GlobalsImporter &amp;GVImporter, FunctionImporter::ImportMapTy &amp;ImportList, DenseMap&lt; StringRef, FunctionImporter::ExportSetTy &gt; *ExportLists, FunctionImporter::ImportThresholdsTy &amp;ImportThresholds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the list of functions to import for a given caller. <a href="#a36d763333ed81c8ff62e28b20125a95b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b9fbe728ecb449155f59118b29ec5c">isGlobalVarSummary</a> (const ModuleSummaryIndex &amp;Index, ValueInfo VI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac291695c9c0aeacdc46efc24d36905b1">isGlobalVarSummary</a> (const ModuleSummaryIndex &amp;Index, GlobalValue::GUID G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14adf9d519c34c1a98f0c2d0308af904">numGlobalVarSummaries</a> (const ModuleSummaryIndex &amp;Index, FunctionImporter::ExportSetTy &amp;ExportSet)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/structs/importstatistics">ImportStatistics</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a140fd481667fd1826f53f5bf36527552">collectImportStatistics</a> (const ModuleSummaryIndex &amp;Index, const FunctionImporter::ImportMapTy &amp;ImportList)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a9f08304751b15dd960f18bc3acddb">checkVariableImport</a> (const ModuleSummaryIndex &amp;Index, FunctionImporter::ImportListsTy &amp;ImportLists, DenseMap&lt; StringRef, FunctionImporter::ExportSetTy &gt; &amp;ExportLists)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7bfd8da79e55bf6a2b2ac4955b7f95d">dumpImportListForModule</a> (const ModuleSummaryIndex &amp;Index, StringRef ModulePath, FunctionImporter::ImportMapTy &amp;ImportList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a95835d82cdc254d43c6f1dd99f7dc">ComputeCrossModuleImportForModuleForTest</a> (StringRef ModulePath, function_ref&lt; bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; isPrevailing, const ModuleSummaryIndex &amp;Index, FunctionImporter::ImportMapTy &amp;ImportList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute all the imports for the given module using the Index. <a href="#af8a95835d82cdc254d43c6f1dd99f7dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf85fc46eef3a1f2007877aa14ae209">ComputeCrossModuleImportForModuleFromIndexForTest</a> (StringRef ModulePath, const ModuleSummaryIndex &amp;Index, FunctionImporter::ImportMapTy &amp;ImportList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark all external summaries in <span class="doxyComputerOutput">Index</span> for import into the given module. <a href="#addf85fc46eef3a1f2007877aa14ae209">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8afb9de4d8239806728ad5d82d550b87">updateValueInfoForIndirectCalls</a> (ModuleSummaryIndex &amp;Index, FunctionSummary *FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac926ba61257c2262ebca3deca2cc8c76">replaceAliasWithAliasee</a> (Module *SrcModule, GlobalAlias *GA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make alias a clone of its aliasee. <a href="#ac926ba61257c2262ebca3deca2cc8c76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b2bae54059511efe7441d4213e4add">internalizeGVsAfterImport</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cdcb957bdfaac04b4bb110298fa7625">doImportingForModuleForTest</a> (Module &amp;M, function_ref&lt; bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; isPrevailing)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11e1fe31b58ecb98c3de00a828f0ac1">ImportInstrLimit</a>("import-instr-limit", cl::init(100), cl::Hidden, cl::value_desc("N"), cl::desc("Only import functions with less than N instructions"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Limit on instruction count of imported functions. <a href="#aa11e1fe31b58ecb98c3de00a828f0ac1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56cca4c22ecf8b2e2529435d1f706a5a">ImportCutoff</a>("import-cutoff", cl::init(-1), cl::Hidden, cl::value_desc("N"), cl::desc("Only import first N functions if N>=0 (default -1)"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f7492a251bd6f9a28a5e48ac5827cb3">ForceImportAll</a>("force-import-all", cl::init(false), cl::Hidden, cl::desc("Import functions with noinline attribute"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62be59d9ee9a0672a0a7deff93eaca68">ImportInstrFactor</a>("import-instr-evolution-factor", cl::init(0.7), cl::Hidden, cl::value_desc("x"), cl::desc("As we import functions, multiply the " "`import-instr-limit` threshold by this factor " "before processing newly imported functions"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33df50484daeda83ece07399d3df7ffa">ImportHotInstrFactor</a>("import-hot-evolution-factor", cl::init(1.0), cl::Hidden, cl::value_desc("x"), cl::desc("As we import functions called from hot callsite, multiply the " "`import-instr-limit` threshold by this factor " "before processing newly imported functions"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14351bfdad8ef9b06dee96066149343c">ImportHotMultiplier</a>("import-hot-multiplier", cl::init(10.0), cl::Hidden, cl::value_desc("x"), cl::desc("Multiply the `import-instr-limit` threshold for hot callsites"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6eeb0777c696a9b4591ba2b6319481">ImportCriticalMultiplier</a>("import-critical-multiplier", cl::init(100.0), cl::Hidden, cl::value_desc("x"), cl::desc("Multiply the `import-instr-limit` threshold for critical callsites"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11c774fcfed6e4814a7f3adcdc1a2c0d">ImportColdMultiplier</a>("import-cold-multiplier", cl::init(0), cl::Hidden, cl::value_desc("N"), cl::desc("Multiply the `import-instr-limit` threshold for cold callsites"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8486e3756d8a29a80d281808828ce392">PrintImports</a>("print-imports", cl::init(false), cl::Hidden, cl::desc("Print imported functions"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9151ed4e71d344fa4c142f55d6179a5">PrintImportFailures</a>("print-import-failures", cl::init(false), cl::Hidden, cl::desc("Print information for functions rejected for importing"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafeea9390177c517e5403106c02b03f9">ComputeDead</a>("compute-dead", cl::init(true), cl::Hidden, cl::desc("Compute dead symbols"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb10e723f69af99f6257b77f7f854b2">EnableImportMetadata</a>("enable-import-metadata", cl::init(false), cl::Hidden, cl::desc("Enable import metadata like 'thinlto_src_module' and " "'thinlto_src_file'"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f1b0d44632bb5456abfa558d6a50dd">SummaryFile</a>("summary-file", cl::desc("The summary file to use for function importing."))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Summary file to use for function importing when using -function-import from the command line. <a href="#ab5f1b0d44632bb5456abfa558d6a50dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6039bb9429b2e097413f6e26bf17c70">ImportAllIndex</a>("import-all-index", cl::desc("Import all external functions in index."))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used when testing importing from distributed indexes via opt. <a href="#ab6039bb9429b2e097413f6e26bf17c70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4a0f1638bd13257d9d4a7b66cebda4">ImportDeclaration</a>("import-declaration", cl::init(false), cl::Hidden, cl::desc("If true, import function declaration as fallback if the function " "definition is not imported."))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a test-only option. <a href="#a9d4a0f1638bd13257d9d4a7b66cebda4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0290be33da33adb70977d0e595ce73">WorkloadDefinitions</a>("thinlto-workload-def", cl::desc("Pass a workload definition. This is a file containing a JSON " "dictionary. The keys are root functions, the values are lists of " "functions to import in the module defining the root. It is " "assumed -funique-internal-linkage-names was used, to ensure " "local linkage functions have unique names. For example: \n" "{\n" "  \"rootFunction_1\": [\"function_to_import_1\", " "\"function_to_import_2\"], \n" "  \"rootFunction_2\": [\"function_to_import_3\", " "\"function_to_import_4\"] \n" "}"), cl::Hidden)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> a workload description file - an example of workload would be the functions executed to satisfy a RPC request. <a href="#aae0290be33da33adb70977d0e595ce73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac99641888d5b06352c629f38485394">UseCtxProfile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"function-import"</td>
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

### checkVariableImport() {#a22a9f08304751b15dd960f18bc3acddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkVariableImport (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importliststy">FunctionImporter::ImportListsTy</a> &amp; ImportLists, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &gt; &amp; ExportLists)</td>
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



<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>.</p>

</div>
</div>

### collectImportStatistics() {#a140fd481667fd1826f53f5bf36527552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; StringRef, ImportStatistics &gt; collectImportStatistics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList)</td>
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



<p>Definition at line 1121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737acb646dd0be0c28c71a939dc87ab59340">llvm::GlobalValueSummary::Definition</a> and <a href="#a99b9fbe728ecb449155f59118b29ec5c">isGlobalVarSummary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a> and <a href="#ad7bfd8da79e55bf6a2b2ac4955b7f95d">dumpImportListForModule</a>.</p>

</div>
</div>

### ComputeCrossModuleImportForModuleForTest() {#af8a95835d82cdc254d43c6f1dd99f7dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ComputeCrossModuleImportForModuleForTest (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModulePath, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt; isPrevailing, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList)</td>
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

<p>Compute all the imports for the given module using the Index.</p>


<p><span class="doxyComputerOutput">isPrevailing</span> is a callback that will be called with a global value's GUID and summary and should return whether the module corresponding to the summary contains the linker-prevailing copy of that value.</p>


<p><span class="doxyComputerOutput">ImportList</span> will be populated with a map that can be passed to <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">FunctionImporter::importFunctions()</a> above (see description there).</p>


<p>Definition at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#a928dfa99d0b0ced1e5a2abe150a51234">ModuleImportsManager::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ad7bfd8da79e55bf6a2b2ac4955b7f95d">dumpImportListForModule</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a2cdcb957bdfaac04b4bb110298fa7625">doImportingForModuleForTest</a>.</p>

</div>
</div>

### ComputeCrossModuleImportForModuleFromIndexForTest() {#addf85fc46eef3a1f2007877aa14ae209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ComputeCrossModuleImportForModuleFromIndexForTest (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModulePath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList)</td>
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

<p>Mark all external summaries in <span class="doxyComputerOutput">Index</span> for import into the given module.</p>


<p>Used for testing the case of distributed builds using a distributed index.</p>


<p><span class="doxyComputerOutput">ImportList</span> will be populated with a map that can be passed to <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">FunctionImporter::importFunctions()</a> above (see description there).</p>


<p>Definition at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty/#a6b03ca181770e8c968749ce57cf8902a">llvm::FunctionImporter::ImportMapTy::addGUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad7bfd8da79e55bf6a2b2ac4955b7f95d">dumpImportListForModule</a>.</p>


<p>Referenced by <a href="#a2cdcb957bdfaac04b4bb110298fa7625">doImportingForModuleForTest</a>.</p>

</div>
</div>

### computeImportForFunction() {#a36d763333ed81c8ff62e28b20125a95b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeImportForFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> &amp; Summary, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned Threshold, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &amp; DefinedGVSummaries, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt; isPrevailing, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; EdgeInfo &gt; &amp; Worklist, <a href="/web-llvm/docs/api/classes/globalsimporter">GlobalsImporter</a> &amp; GVImporter, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &gt; * ExportLists, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a3422e72809280a158153b5eecdefe02a">FunctionImporter::ImportThresholdsTy</a> &amp; ImportThresholds)</td>
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

<p>Compute the list of functions to import for a given caller.</p>


<p>Mark these imported functions and the symbols they reference in their source module as exported from their source module.</p>


<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty/#a16166e6ad8ba8ad4b90cce3b4e951700">llvm::FunctionImporter::ImportMapTy::addDefinition</a>, <a href="/web-llvm/docs/api/structs/llvm/functionsummary/fflags/#aa0f84f67663c19678567a2448731a9a4">llvm::FunctionSummary::FFlags::AlwaysInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa1a3c2e99e572ec71d3820d0363d90742">llvm::CalleeInfo::Cold</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa278d01e5af56273bae1bb99a98b370cd">llvm::CalleeInfo::Critical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/functionsummary/#adf3998a7e0703c1eac651524d9d14a0d">llvm::FunctionSummary::fflags</a>, <a href="#a8f7492a251bd6f9a28a5e48ac5827cb3">ForceImportAll</a>, <a href="#a5c93b13860b1955fb9b1359b4dea6855">getFailureName</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa4194726ee334e1085d93e002837b73f0">llvm::CalleeInfo::Hot</a>, <a href="#a11c774fcfed6e4814a7f3adcdc1a2c0d">ImportColdMultiplier</a>, <a href="#a3b6eeb0777c696a9b4591ba2b6319481">ImportCriticalMultiplier</a>, <a href="#a56cca4c22ecf8b2e2529435d1f706a5a">ImportCutoff</a>, <a href="#a9d4a0f1638bd13257d9d4a7b66cebda4">ImportDeclaration</a>, <a href="#a33df50484daeda83ece07399d3df7ffa">ImportHotInstrFactor</a>, <a href="#a14351bfdad8ef9b06dee96066149343c">ImportHotMultiplier</a>, <a href="#a62be59d9ee9a0672a0a7deff93eaca68">ImportInstrFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/functionsummary/#aa1c7a4e9c5bce12a30f1fcd3c0d2e580">llvm::FunctionSummary::instCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty/#a83e0cf72fe858a39a426be7fecb325f5">llvm::FunctionImporter::ImportMapTy::maybeAddDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a453cb1f2305409dcdb9a8c0193bb620f">llvm::GlobalValueSummary::modulePath</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty/#a04d993cd3f6534692c552cfd67fddcdca4bac8cdf0a968472b519b3b295d0d48b">llvm::FunctionImporter::ImportMapTy::NoChange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baa55e82356e9721946aa9ba954733c6f0">llvm::not_supported</a>, <a href="/web-llvm/docs/api/classes/globalsimporter/#a40e5e7c43d6af77e6e3e40f4421501a8">GlobalsImporter::onImportingSummary</a>, <a href="#ac9151ed4e71d344fa4c142f55d6179a5">PrintImportFailures</a> and <a href="#adf7bc15ca5b5a3f6a528f4ab6d8b5c14">selectCallee</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#af806f9d842ec97d31bd9550eb338f678">ModuleImportsManager::computeImportForModule</a>.</p>

</div>
</div>

### doImportingForModuleForTest() {#a2cdcb957bdfaac04b4bb110298fa7625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool doImportingForModuleForTest (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt; isPrevailing)</td>
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



<p>Definition at line 1988 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="#af8a95835d82cdc254d43c6f1dd99f7dc">ComputeCrossModuleImportForModuleForTest</a>, <a href="#addf85fc46eef3a1f2007877aa14ae209">ComputeCrossModuleImportForModuleFromIndexForTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7fed2696a3bda04b9f93d8b986758b3">llvm::getModuleSummaryIndexForFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ab6039bb9429b2e097413f6e26bf17c70">ImportAllIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a>, <a href="#a8cd36a34ea4adceda5576292e50cf883">loadFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a46122434c47e17760d4c6709878a0dd6">llvm::renameModuleForThinLTO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#ab5f1b0d44632bb5456abfa558d6a50dd">SummaryFile</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionimportpass/#a4eb08e2a18ca18c8e8ee7d1a8d3de7f2">llvm::FunctionImportPass::run</a>.</p>

</div>
</div>

### dumpImportListForModule() {#ad7bfd8da79e55bf6a2b2ac4955b7f95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpImportListForModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModulePath, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList)</td>
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



<p>Definition at line 1273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="#a140fd481667fd1826f53f5bf36527552">collectImportStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a086f939e29b718dc5a01e4bcfe6af2a1">Stats</a>.</p>


<p>Referenced by <a href="#af8a95835d82cdc254d43c6f1dd99f7dc">ComputeCrossModuleImportForModuleForTest</a> and <a href="#addf85fc46eef3a1f2007877aa14ae209">ComputeCrossModuleImportForModuleFromIndexForTest</a>.</p>

</div>
</div>

### getFailureName() {#a5c93b13860b1955fb9b1359b4dea6855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getFailureName (<a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29">FunctionImporter::ImportFailureReason</a> Reason)</td>
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



<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29ab00ca28f640c35e4add68ec4f671b614">llvm::FunctionImporter::GlobalVar</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29ab56c6368422115c295458dbe410c2b2b">llvm::FunctionImporter::InterposableLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a80994c7d2e02f08efe90b214b3ab2485">llvm::FunctionImporter::LocalLinkageNotInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a3ad1a997f7605fc9ca9ca50845348e89">llvm::FunctionImporter::NoInline</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a6adf97f83acf6453d4a6a4b1070f3754">llvm::FunctionImporter::None</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a916ec32bed391fc1def53a8e263ec400">llvm::FunctionImporter::NotEligible</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a8b4579095ad9db0fd7f8a9ac46d8207d">llvm::FunctionImporter::NotLive</a> and <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a853d33bc5e409941bed899b913647310">llvm::FunctionImporter::TooLarge</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a> and <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#af806f9d842ec97d31bd9550eb338f678">ModuleImportsManager::computeImportForModule</a>.</p>

</div>
</div>

### internalizeGVsAfterImport() {#a82b2bae54059511efe7441d4213e4add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void internalizeGVsAfterImport (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 1806 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>.</p>

</div>
</div>

### isGlobalVarSummary() {#a99b9fbe728ecb449155f59118b29ec5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isGlobalVarSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> VI)</td>
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



<p>Definition at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614ca461342c05a59e66da9d6b38eaccda99a">llvm::GlobalValueSummary::GlobalVarKind</a>.</p>


<p>Referenced by <a href="#a140fd481667fd1826f53f5bf36527552">collectImportStatistics</a>, <a href="#ac291695c9c0aeacdc46efc24d36905b1">isGlobalVarSummary</a> and <a href="#a14adf9d519c34c1a98f0c2d0308af904">numGlobalVarSummaries</a>.</p>

</div>
</div>

### isGlobalVarSummary() {#ac291695c9c0aeacdc46efc24d36905b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isGlobalVarSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> G)</td>
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



<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a99b9fbe728ecb449155f59118b29ec5c">isGlobalVarSummary</a>.</p>

</div>
</div>

### loadFile() {#a8cd36a34ea4adceda5576292e50cf883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Module &gt; loadFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; FileName, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac226baa3ffd0f255a8d2b6d978b81b2">llvm::getLazyIRFileModule</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#a2cdcb957bdfaac04b4bb110298fa7625">doImportingForModuleForTest</a> and <a href="/web-llvm/docs/api/classes/anonymous-blockextractor-cpp-/blockextractor/#af35f11f63c2cd1f16c7b404ac1e9f92d">anonymous{BlockExtractor.cpp}::BlockExtractor::init</a>.</p>

</div>
</div>

### numGlobalVarSummaries() {#a14adf9d519c34c1a98f0c2d0308af904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned numGlobalVarSummaries (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &amp; ExportSet)</td>
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



<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Reference <a href="#a99b9fbe728ecb449155f59118b29ec5c">isGlobalVarSummary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>.</p>

</div>
</div>

### qualifyCalleeCandidates() {#a05678176a857aaca26eac45ab65dc3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto qualifyCalleeCandidates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> &gt; &gt; CalleeSummaryList, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CallerModulePath)</td>
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

<p>Given a list of possible callee implementation for a call site, qualify the legality of importing each.</p>


<p>The return is a range of pairs. Each pair corresponds to a candidate. The first value is the ImportFailureReason for that candidate, the second is the candidate.</p>


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29ab00ca28f640c35e4add68ec4f671b614">llvm::FunctionImporter::GlobalVar</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29ab56c6368422115c295458dbe410c2b2b">llvm::FunctionImporter::InterposableLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aabf6932ed41fc64e17c0030c44eda44e">llvm::GlobalValue::isInterposableLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a80994c7d2e02f08efe90b214b3ab2485">llvm::FunctionImporter::LocalLinkageNotInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51c7cbd21e1104ee6841c18d7daa6edb">llvm::map_range</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a6adf97f83acf6453d4a6a4b1070f3754">llvm::FunctionImporter::None</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a916ec32bed391fc1def53a8e263ec400">llvm::FunctionImporter::NotEligible</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a8b4579095ad9db0fd7f8a9ac46d8207d">llvm::FunctionImporter::NotLive</a> and <a href="#a95dfbc76e4eb1f6655f38f2a17e691b3">shouldSkipLocalInAnotherModule</a>.</p>


<p>Referenced by <a href="#adf7bc15ca5b5a3f6a528f4ab6d8b5c14">selectCallee</a>.</p>

</div>
</div>

### replaceAliasWithAliasee() {#ac926ba61257c2262ebca3deca2cc8c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * replaceAliasWithAliasee (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * SrcModule, <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * GA)</td>
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

<p>Make alias a clone of its aliasee.</p>

<p>Definition at line 1790 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a311a097af4f0f77da22ac7acddc496f5">llvm::GlobalAlias::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a28b9561d9ef3d237ef894023187fa26c">llvm::GlobalValue::getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a687973de03d041e04b50a76d19d4fd36">llvm::GlobalValue::setLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa242d8ab89216c14beab812e07009b2a">llvm::GlobalValue::setVisibility</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>.</p>

</div>
</div>

### selectCallee() {#adf7bc15ca5b5a3f6a528f4ab6d8b5c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValueSummary * selectCallee (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> &gt; &gt; CalleeSummaryList, unsigned Threshold, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CallerModulePath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *&amp; TooLargeOrNoInlineSummary, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29">FunctionImporter::ImportFailureReason</a> &amp; Reason)</td>
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

<p>Given a list of possible callee implementation for a call site, select one that fits the <span class="doxyComputerOutput">Threshold</span> for function definition import.</p>


<p>If none are found, the Reason will give the last reason for the failure (last, in the order of CalleeSummaryList entries). While looking for a callee definition, sets <span class="doxyComputerOutput">TooLargeOrNoInlineSummary</span> to the last seen too-large or noinline candidate; other modules may want to know the function summary or declaration even if a definition is not needed.</p>


<p>FIXME: select "best" instead of first that fits. But what is "best"?</p>


<ul class="doxyList ">
<li>The smallest: more likely to be inlined.</li>
<li>The one with the least outgoing edges (already well optimized).</li>
<li>One from a module already being imported from in order to reduce the number of source modules parsed/linked.</li>
<li>One that has PGO data attached.</li>
<li>[insert you fancy metric here]</li>
</ul>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a8f7492a251bd6f9a28a5e48ac5827cb3">ForceImportAll</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a3ad1a997f7605fc9ca9ca50845348e89">llvm::FunctionImporter::NoInline</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a6adf97f83acf6453d4a6a4b1070f3754">llvm::FunctionImporter::None</a>, <a href="#a05678176a857aaca26eac45ab65dc3b1">qualifyCalleeCandidates</a> and <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acbdbb2a799833253c9b3ec9e8e1e5a29a853d33bc5e409941bed899b913647310">llvm::FunctionImporter::TooLarge</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### shouldSkipLocalInAnotherModule() {#a95dfbc76e4eb1f6655f38f2a17e691b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldSkipLocalInAnotherModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> * RefSummary, size_t NumDefs, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ImporterModule)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#adc87d9100ef8fc4adba27a249123f1d6">llvm::GlobalValueSummary::linkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a453cb1f2305409dcdb9a8c0193bb620f">llvm::GlobalValueSummary::modulePath</a>.</p>


<p>Referenced by <a href="#a05678176a857aaca26eac45ab65dc3b1">qualifyCalleeCandidates</a>.</p>

</div>
</div>

### STATISTIC() {#a21805cf0d5ec7bac4993364076570c0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumImportedFunctionsThinLink, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> thin link decided to import")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a040db9e0ceac76a1cb31b961e9452f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumImportedHotFunctionsThinLink, "Number of hot <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> thin link decided to import")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a1ce7860b8f01180c08bd27a9b97b7563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumImportedCriticalFunctionsThinLink, "Number of critical <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> thin link decided to import")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a653029fa977ee38456e959db15ea0a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumImportedGlobalVarsThinLink, "Number of global variables thin link decided to import")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a41f09b63be5a651e3a9bd2408a50ecb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumImportedFunctions, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> imported in backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a72482562440a5f1735c6bd4518668181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumImportedGlobalVars, "Number of global variables imported in backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a0c905e133f4f08e028ae6566aac21fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumImportedModules, "Number of modules imported from")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#af73c9358a3f01dd9f052706697e873e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDeadSymbols, "Number of dead stripped symbols in index")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a3e62c84e9b2f35dc18bb717092d37bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumLiveSymbols, "Number of live symbols in index")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

### updateValueInfoForIndirectCalls() {#a8afb9de4d8239806728ad5d82d550b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateValueInfoForIndirectCalls (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7b5d72a4e8c39c8d0ea81cb9c547bc8c">llvm::computeDeadSymbolsAndUpdateIndirectCalls</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9a3d3d86175f9b2db2ffcd643b16ff8f">llvm::updateIndirectCalls</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ComputeDead {#aafeea9390177c517e5403106c02b03f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ComputeDead("compute-dead", cl::init(true), cl::Hidden, cl::desc("Compute dead symbols"))</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7b5d72a4e8c39c8d0ea81cb9c547bc8c">llvm::computeDeadSymbolsAndUpdateIndirectCalls</a>.</p>

</div>
</div>

### EnableImportMetadata {#a0bb10e723f69af99f6257b77f7f854b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableImportMetadata("enable-import-metadata", cl::init(false), cl::Hidden, cl::desc("Enable import metadata like 'thinlto_src_module' and " "'thinlto_src_file'"))</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>.</p>

</div>
</div>

### ForceImportAll {#a8f7492a251bd6f9a28a5e48ac5827cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForceImportAll("force-import-all", cl::init(false), cl::Hidden, cl::desc("Import functions with noinline attribute"))</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a> and <a href="#adf7bc15ca5b5a3f6a528f4ab6d8b5c14">selectCallee</a>.</p>

</div>
</div>

### ImportAllIndex {#ab6039bb9429b2e097413f6e26bf17c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ImportAllIndex("import-all-index", cl::desc("Import all external functions in index."))</td>
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

<p>Used when testing importing from distributed indexes via opt.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a2cdcb957bdfaac04b4bb110298fa7625">doImportingForModuleForTest</a>.</p>

</div>
</div>

### ImportColdMultiplier {#a11c774fcfed6e4814a7f3adcdc1a2c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; ImportColdMultiplier("import-cold-multiplier", cl::init(0), cl::Hidden, cl::value_desc("N"), cl::desc("Multiply the `import-instr-limit` threshold for cold callsites"))</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### ImportCriticalMultiplier {#a3b6eeb0777c696a9b4591ba2b6319481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; ImportCriticalMultiplier("import-critical-multiplier", cl::init(100.0), cl::Hidden, cl::value_desc("x"), cl::desc( "Multiply the `import-instr-limit` threshold for critical callsites"))</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### ImportCutoff {#a56cca4c22ecf8b2e2529435d1f706a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; ImportCutoff("import-cutoff", cl::init(-1), cl::Hidden, cl::value_desc("N"), cl::desc("Only import first N functions if N&gt;=0 (default -1)"))</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### ImportDeclaration {#a9d4a0f1638bd13257d9d4a7b66cebda4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ImportDeclaration("import-declaration", cl::init(false), cl::Hidden, cl::desc("If true, import function declaration as fallback if the function " "definition is not imported."))</td>
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

<p>This is a test-only option.</p>


<p>If this option is enabled, the ThinLTO indexing step will import each function declaration as a fallback. In a real build this may increase ram usage of the indexing step unnecessarily. TODO: Implement selective import (based on combined summary analysis) to ensure the imported function has a use case in the postlink pipeline.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### ImportHotInstrFactor {#a33df50484daeda83ece07399d3df7ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; ImportHotInstrFactor("import-hot-evolution-factor", cl::init(1.0), cl::Hidden, cl::value_desc("x"), cl::desc("As we import functions called from hot callsite, multiply the " "`import-instr-limit` threshold by this factor " "before processing newly imported functions"))</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### ImportHotMultiplier {#a14351bfdad8ef9b06dee96066149343c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; ImportHotMultiplier("import-hot-multiplier", cl::init(10.0), cl::Hidden, cl::value_desc("x"), cl::desc("Multiply the `import-instr-limit` threshold for hot callsites"))</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### ImportInstrFactor {#a62be59d9ee9a0672a0a7deff93eaca68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; ImportInstrFactor("import-instr-evolution-factor", cl::init(0.7), cl::Hidden, cl::value_desc("x"), cl::desc("As we import functions, multiply the " "`import-instr-limit` threshold by this factor " "before processing newly imported functions"))</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### ImportInstrLimit {#aa11e1fe31b58ecb98c3de00a828f0ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ImportInstrLimit("import-instr-limit", cl::init(100), cl::Hidden, cl::value_desc("N"), cl::desc("Only import functions with less than N instructions"))</td>
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

<p>Limit on instruction count of imported functions.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#af806f9d842ec97d31bd9550eb338f678">ModuleImportsManager::computeImportForModule</a>.</p>

</div>
</div>

### PrintImportFailures {#ac9151ed4e71d344fa4c142f55d6179a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintImportFailures("print-import-failures", cl::init(false), cl::Hidden, cl::desc("Print information for functions rejected for importing"))</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a> and <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#af806f9d842ec97d31bd9550eb338f678">ModuleImportsManager::computeImportForModule</a>.</p>

</div>
</div>

### PrintImports {#a8486e3756d8a29a80d281808828ce392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintImports("print-imports", cl::init(false), cl::Hidden, cl::desc("Print imported functions"))</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>.</p>

</div>
</div>

### SummaryFile {#ab5f1b0d44632bb5456abfa558d6a50dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; SummaryFile("summary-file", cl::desc("The summary file to use for function importing."))</td>
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

<p>Summary file to use for function importing when using -function-import from the command line.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#a2cdcb957bdfaac04b4bb110298fa7625">doImportingForModuleForTest</a>.</p>

</div>
</div>

### UseCtxProfile {#a5ac99641888d5b06352c629f38485394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;std::string&gt; UseCtxProfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#a928dfa99d0b0ced1e5a2abe150a51234">ModuleImportsManager::create</a> and <a href="/web-llvm/docs/api/classes/workloadimportsmanager/#a153fc7b2387346443f6c6503cc92b47d">WorkloadImportsManager::WorkloadImportsManager</a>.</p>

</div>
</div>

### WorkloadDefinitions {#aae0290be33da33adb70977d0e595ce73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; WorkloadDefinitions("thinlto-workload-def", cl::desc("Pass a workload definition. This is a file containing a JSON " "dictionary. The keys are root functions, the values are lists of " "functions to import in the module defining the root. It is " "assumed -funique-internal-linkage-names was used, to ensure " "local linkage functions have unique names. For example: \n" "{\n" "  \"rootFunction_1\": [\"function_to_import_1\", " "\"function_to_import_2\"], \n" "  \"rootFunction_2\": [\"function_to_import_3\", " "\"function_to_import_4\"] \n" "}"), cl::Hidden)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> a workload description file - an example of workload would be the functions executed to satisfy a RPC request.</p>


<p>A workload is defined by a root function and the list of functions that are (frequently) needed to satisfy it. The module that defines the root will have all those functions imported. The file contains a JSON dictionary. The keys are root functions, the values are lists of functions to import in the module defining the root. It is assumed -funique-internal-linkage-names was used, thus ensuring function names are unique even for local linkage ones.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#a928dfa99d0b0ced1e5a2abe150a51234">ModuleImportsManager::create</a> and <a href="/web-llvm/docs/api/classes/workloadimportsmanager/#a153fc7b2387346443f6c6503cc92b47d">WorkloadImportsManager::WorkloadImportsManager</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"function-import"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
