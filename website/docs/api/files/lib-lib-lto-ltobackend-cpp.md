---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/lto/ltobackend-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LTOBackend.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">llvm/LTO/LTOBackend.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">llvm/Analysis/CGSCCPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/modulesummaryanalysis-h">llvm/Analysis/ModuleSummaryAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">llvm/Bitcode/BitcodeWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendata-h">llvm/CGData/CodeGenData.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmremarkstreamer-h">llvm/IR/LLVMRemarkStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">llvm/LTO/LTO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">llvm/Object/ModuleSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passplugin-h">llvm/Passes/PassPlugin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">llvm/Passes/StandardInstrumentations.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/program-h">llvm/Support/Program.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threadpool-h">llvm/Support/ThreadPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">llvm/Support/ToolOutputFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/wholeprogramdevirt-h">llvm/Transforms/IPO/WholeProgramDevirt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">llvm/Transforms/Scalar/LoopPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">llvm/Transforms/Utils/FunctionImportUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/splitmodule-h">llvm/Transforms/Utils/SplitModule.h</a>"
#include &lt;optional&gt;
#include "llvm/Support/Extension.def"
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

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LTOBitcodeEmbedding { <a href="#a1646f93a5de6149d17f91e14a7523f7e">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041e682560afc980462e5ca47deb1f24">reportOpenError</a> (StringRef Path, Twine Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f32ac9aec23e32f0a216c1277ab34d">RegisterPassPlugins</a> (ArrayRef&lt; std::string &gt; PassPlugins, PassBuilder &amp;PB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a> (const Config &amp;Conf, const Target *TheTarget, Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a> (const Config &amp;Conf, Module &amp;Mod, TargetMachine *TM, unsigned OptLevel, bool IsThinLTO, ModuleSummaryIndex *ExportSummary, const ModuleSummaryIndex *ImportSummary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc1b31eca401e3ab7a3be9d8fdb697d">isEmptyModule</a> (const Module &amp;Mod)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889b75e55af23f854f7f597b0e912b98">codegen</a> (const Config &amp;Conf, TargetMachine *TM, AddStreamFn AddStream, unsigned Task, Module &amp;Mod, const ModuleSummaryIndex &amp;CombinedIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fad224b57541514de4fb5be6eb2e7f1">splitCodeGen</a> (const Config &amp;C, TargetMachine *TM, AddStreamFn AddStream, unsigned ParallelCodeGenParallelismLevel, Module &amp;Mod, const ModuleSummaryIndex &amp;CombinedIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a388c19dd51467226753e433499a85e44">initAndLookupTarget</a> (const Config &amp;C, Module &amp;Mod)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330a18768ffaafb198c726071dcfcb29">dropDeadSymbols</a> (Module &amp;Mod, const GVSummaryMapTy &amp;DefinedGlobals, const ModuleSummaryIndex &amp;Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#a1646f93a5de6149d17f91e14a7523f7e">LTOBitcodeEmbedding</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224082742eac946c1e886179fd48be59">EmbedBitcode</a>("lto-embed-bitcode", cl::init(LTOBitcodeEmbedding::DoNotEmbed), cl::values(clEnumValN(LTOBitcodeEmbedding::DoNotEmbed, "none", "Do not embed"), clEnumValN(LTOBitcodeEmbedding::EmbedOptimized, "optimized", "Embed after all optimization passes"), clEnumValN(LTOBitcodeEmbedding::EmbedPostMergePreOptimized, "post-merge-pre-opt", "Embed post merge, but before optimizations")), cl::desc("Embed LLVM bitcode in object files produced by LTO"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0046b3c8795f231a43ff155b23bbb36e">ThinLTOAssumeMerged</a>("thinlto-assume-merged", cl::init(false), cl::desc("Assume the input has already undergone ThinLTO function " "importing and the other pre-optimization pipeline changes."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"lto-backend"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a521c1789df77ba08d88ca195c68d3bfc">HANDLE_EXTENSION</a>(Ext)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/structs/llvm/passpluginlibraryinfo">llvm::PassPluginLibraryInfo</a> get##Ext##PluginInfo();</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66a776546f945e750f1892354116ee9">HANDLE_EXTENSION</a>(Ext)&nbsp;&nbsp;&nbsp;  get##Ext##PluginInfo().RegisterPassBuilderCallbacks(<a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>);</td>
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

## Enumerations

### LTOBitcodeEmbedding {#a1646f93a5de6149d17f91e14a7523f7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class LTOBitcodeEmbedding </td>
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
<td class="doxyEnumItemName">DoNotEmbed<a id="a1646f93a5de6149d17f91e14a7523f7ea20dade34d645bcdd032c02dd7d53a4e1"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EmbedOptimized<a id="a1646f93a5de6149d17f91e14a7523f7ea38d294901a8d7c03dcc7462c6c0dd633"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EmbedPostMergePreOptimized<a id="a1646f93a5de6149d17f91e14a7523f7ead33347b4d20baa015bccc5548911f233"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### codegen() {#a889b75e55af23f854f7f597b0e912b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void codegen (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex)</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager/#a0b57c8c0b51669836bd9adc00b2e8f40">llvm::legacy::PassManager::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#af31b6979bcc0505621c4d905ec5c6a2a">llvm::lto::Config::CGFileType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab0231205adf0a10ac89540dbcfdcd2d7">llvm::sys::fs::create_directories</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf72d0dceefdaac29af9b9504612fd2c">llvm::createImmutableModuleSummaryIndexWrapperPass</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a7c554b4240d5088684a7ab7637749d93">llvm::lto::Config::DwoDir</a>, <a href="#a224082742eac946c1e886179fd48be59">EmbedBitcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="#a1646f93a5de6149d17f91e14a7523f7ea38d294901a8d7c03dcc7462c6c0dd633">EmbedOptimized</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#aafc1b31eca401e3ab7a3be9d8fdb697d">isEmptyModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ae36f72183fdb505c21cc4ca6bd48a860">llvm::lto::Config::PreCodeGenModuleHook</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a534b265d050d27ea55a86b1a473b9515">llvm::lto::Config::PreCodeGenPassesHook</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager/#a2bdbe49f025814f15cd9c82aa08a389b">llvm::legacy::PassManager::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#aa4f390c0f5cbd46df4734ccd229f36ec">llvm::lto::Config::SplitDwarfFile</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#aacd13a77ae60a12f2f22018c0b7bd719">llvm::lto::Config::SplitDwarfOutput</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### createTargetMachine() {#a020a49618af317a9da7a8193a54338e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; TargetMachine &gt; createTargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> * TheTarget, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#af579a881fa0a6fe785ecf91fcc9ccaaa">llvm::SubtargetFeatures::AddFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a6783034dde920cf6c0187877581c72ce">llvm::lto::Config::CGOptLevel</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a4a143b2765089504057036d723110b48">llvm::lto::Config::CodeModel</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a787c0462fab83a3c31d543240378fe78">llvm::lto::Config::CPU</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a97b31e68ba164458a37e49e7d1053fc1">llvm::Target::createTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a5a24823d504d2c91c152e69250b2197d">llvm::SubtargetFeatures::getDefaultSubtargetFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#aaa9679917091c7e93f866894599f923e">llvm::SubtargetFeatures::getString</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a5a1e8e55e81b4c203d49bbbd0bce8a51">llvm::lto::Config::MAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6ba2ca71e846d9899d1a3e297367c86e6b2">llvm::PICLevel::NotPIC</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#aa2df4a4590f315d98041339341d9e469">llvm::lto::Config::Options</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">llvm::Reloc::PIC_</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ae561eb0b1d21dcefd1c59988684fe403">llvm::lto::Config::RelocModel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>.</p>

</div>
</div>

### dropDeadSymbols() {#a330a18768ffaafb198c726071dcfcb29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dropDeadSymbols (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &amp; DefinedGlobals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index)</td>
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



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### initAndLookupTarget() {#a388c19dd51467226753e433499a85e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const Target * &gt; initAndLookupTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod)</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a89ef034c1f3a70da2446c1af1d656dab">llvm::lto::backend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### isEmptyModule() {#aafc1b31eca401e3ab7a3be9d8fdb697d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isEmptyModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>.</p>


<p>Referenced by <a href="#a889b75e55af23f854f7f597b0e912b98">codegen</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae3dc87f8d2d7b79aa7da2d3224f3f63d">llvm::lto::opt</a>.</p>

</div>
</div>

### RegisterPassPlugins() {#ac9f32ac9aec23e32f0a216c1277ab34d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterPassPlugins (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt; PassPlugins, <a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> &amp; PB)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passplugin/#a16bba9d356b9f317678e118c6de531da">llvm::PassPlugin::Load</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>, <a href="/web-llvm/docs/api/classes/llvm/passplugin/#a4527a2b697878c3dc1017ab1793664b1">llvm::PassPlugin::registerPassBuilderCallbacks</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### reportOpenError() {#a041e682560afc980462e5ca47deb1f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reportOpenError (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> Msg)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a4395f06e55f4b727fe0b685074821644">llvm::lto::Config::addSaveTemps</a>.</p>

</div>
</div>

### runNewPMPasses() {#af5d1d807d38250523b2335cec221c2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void runNewPMPasses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM, unsigned OptLevel, bool IsThinLTO, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ImportSummary)</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a4c0096e74a84beee8fa9676008520c87">llvm::lto::Config::AAPipeline</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a345a10e4235f0a90822f39c3cbe56ae8">llvm::lto::Config::AddFSDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a13293a681188ed79fb799b7f9c173b83">CGAM</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#acf3f319824303e495d7326e35538b250ad626f6abde9ca8fb0a8e97125114f11c">llvm::PGOOptions::CSIRInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#adffa7a90c82e1d7aa0aead0e6f74786b">llvm::lto::Config::CSIRProfile</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#acf3f319824303e495d7326e35538b250a0003b9f9d3be4b2a2bef9c7ceec1d77b">llvm::PGOOptions::CSIRUse</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a2e7d3a91d656d9f1d3c374429f883166">llvm::lto::Config::DebugPassManager</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#af4530e1e6451953635146d6119977bb2a7a1920d61156abc05a60135aefe8bc67">llvm::PGOOptions::Default</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a59454d5a628381f0c1ce63819aa25b25">llvm::lto::Config::DisableVerify</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#af662fcf728cd50f9a546a5a3ba7c1961">llvm::lto::Config::Freestanding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfs/#a9878c6a5a53d24e17c7c1002be31364c">llvm::vfs::getRealFileSystem</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a0c03d67d2ee41484066dade662f2fca5">llvm::PGOOptions::IRUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a7cfe61417446ebb812e81293bde22a29">LAM</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a5c70c58ba2d09ff71654a055ea617020">llvm::PGOOptions::NoAction</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#acf3f319824303e495d7326e35538b250a3f7a9bea8b72b3ad453ccf95bcbca22b">llvm::PGOOptions::NoCSAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a971321e9917182d182097c2f3ffc475c">llvm::NoPGOWarnMismatch</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a6ca9e4f5478a77fa91fc56e1f1f6ba24">llvm::OptimizationLevel::O0</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#acfab17afad8d19eb90de02e684900ccd">llvm::OptimizationLevel::O1</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a9c0836ff9219a0b737a11979991c3389">llvm::OptimizationLevel::O2</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationlevel/#a097296a5feaefc188dafa71b19204714">llvm::OptimizationLevel::O3</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#abe426c024bc5082714ea582cd739210e">llvm::lto::Config::OptPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#addd6c05e7f9781702cd583680b21da07">llvm::lto::Config::PassPlugins</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#aeb2fc95c3f63546728703c4e587e46cc">llvm::lto::Config::PGOWarnMismatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a155889188eb0c299a1b2c69930bc9e2b">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::printPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab70eaee2becdf78aa37613deabe8668f">llvm::PrintPipelinePasses</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a9dc5e1dacdffb8158529596000b3b411">llvm::lto::Config::ProfileRemapping</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a6c489480556941aaffb99ac11d530ceb">llvm::lto::Config::PTO</a>, <a href="#ac9f32ac9aec23e32f0a216c1277ab34d">RegisterPassPlugins</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ac05157b80afde0ee192d5be6978c5dba">llvm::lto::Config::RunCSIRInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#afd1d4183a0d4ae2e704610be044010b0">llvm::lto::Config::SampleProfile</a>, <a href="/web-llvm/docs/api/structs/llvm/pgooptions/#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">llvm::PGOOptions::SampleUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a647ccc8efe422fa8ac5d5242ccf8bbdb">llvm::lto::Config::VerifyEach</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae3dc87f8d2d7b79aa7da2d3224f3f63d">llvm::lto::opt</a>.</p>

</div>
</div>

### splitCodeGen() {#a2fad224b57541514de4fb5be6eb2e7f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void splitCodeGen (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, unsigned ParallelCodeGenParallelismLevel, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex)</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/threadpoolinterface/#ad43d0052f680e6ac08426d8821df178d">llvm::ThreadPoolInterface::async</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abfc7ebfffc7baaf23279854fec1412ac">createTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01b0ea0a16ef9208a33017ce9399da1a">llvm::heavyweight_hardware_concurrency</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a170525c5f5e06bd2555d40a0499b8b6d">llvm::parseBitcodeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61553b705fc9be3d8d0a18a8af1bc152">llvm::SplitModule</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ac93a706f78069d5f23b6084d9a1fc015">ThreadCount</a>, <a href="/web-llvm/docs/api/classes/llvm/singlethreadexecutor/#a4a9fc38bb7d9ff3f944e25971330cb42">llvm::SingleThreadExecutor::wait</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a89ef034c1f3a70da2446c1af1d656dab">llvm::lto::backend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EmbedBitcode {#a224082742eac946c1e886179fd48be59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; LTOBitcodeEmbedding &gt; EmbedBitcode("lto-embed-bitcode", cl::init(LTOBitcodeEmbedding::DoNotEmbed), cl::values(clEnumValN(LTOBitcodeEmbedding::DoNotEmbed, "none", "Do not embed"), clEnumValN(LTOBitcodeEmbedding::EmbedOptimized, "optimized", "Embed after all optimization passes"), clEnumValN(LTOBitcodeEmbedding::EmbedPostMergePreOptimized, "post-merge-pre-opt", "Embed post merge, but before optimizations")), cl::desc("Embed LLVM bitcode in object files produced by LTO"))</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>Referenced by <a href="#a889b75e55af23f854f7f597b0e912b98">codegen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae3dc87f8d2d7b79aa7da2d3224f3f63d">llvm::lto::opt</a>.</p>

</div>
</div>

### ThinLTOAssumeMerged {#a0046b3c8795f231a43ff155b23bbb36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ThinLTOAssumeMerged("thinlto-assume-merged", cl::init(false), cl::desc("Assume the input has already undergone ThinLTO function " "importing and the other pre-optimization pipeline changes."))</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a85cf54f25bd787c7983fe72e15233000">llvm::lto::findThinLTOModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ac86eef0f28ae21c5e2b4ace11e1592f1">llvm::lto::initImportList</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"lto-backend"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>

</div>
</div>

### HANDLE\_EXTENSION {#a521c1789df77ba08d88ca195c68d3bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_EXTENSION(Ext)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/structs/llvm/passpluginlibraryinfo">llvm::PassPluginLibraryInfo</a> get##Ext##PluginInfo();</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>

</div>
</div>

### HANDLE\_EXTENSION {#af66a776546f945e750f1892354116ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_EXTENSION(Ext)&nbsp;&nbsp;&nbsp;  get##Ext##PluginInfo().RegisterPassBuilderCallbacks(<a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
