---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/lto
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `lto` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::lto { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> configuration. <a href="/web-llvm/docs/api/structs/llvm/lto/config/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmdiagnostichandler">LTOLLVMDiagnosticHandler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmcontext">LTOLLVMContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A derived class of <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> that initializes itself according to a given <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> object. <a href="/web-llvm/docs/api/structs/llvm/lto/ltollvmcontext/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lto/inputfile">InputFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An input file. <a href="/web-llvm/docs/api/classes/llvm/lto/inputfile/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc">ThinBackendProc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class defines the interface to the ThinLTO backend. <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend">ThinBackend</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This type defines the behavior following the thin-link phase during ThinLTO. <a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class implements a resolution-based interface to LLVM's <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> functionality. <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution">SymbolResolution</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The resolution for a symbol. <a href="/web-llvm/docs/api/structs/llvm/lto/symbolresolution/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dfcd0c2c963dcc17b900f0a7876f6b4">IndexWriteCallback</a> = std::function&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd057e726ed7c74b8765a1934a5fa7c">ThinBackendFunction</a> = std::function&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc">ThinBackendProc</a> &gt;( <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">C</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;CombinedIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &gt; &amp;ModuleToDefinedGVSummaries, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> Cache)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callable defines the behavior of a ThinLTO backend after the thin-link phase. <a href="#aefd057e726ed7c74b8765a1934a5fa7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d269a83a714b7924ac1d67e52655c73">getThinLTODefaultCPU</a> (const Triple &amp;TheTriple)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18eabcf596deec54ada617114b818baf">getThinLTOOutputFile</a> (StringRef Path, StringRef OldPrefix, StringRef NewPrefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the original <span class="doxyComputerOutput">Path</span> to an output file, replace any path prefix matching <span class="doxyComputerOutput">OldPrefix</span> with <span class="doxyComputerOutput">NewPrefix</span>. <a href="#a18eabcf596deec54ada617114b818baf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile">ToolOutputFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf0da31fd6ca90efb2819d0f6061bd74">setupLLVMOptimizationRemarks</a> (LLVMContext &amp;Context, StringRef RemarksFilename, StringRef RemarksPasses, StringRef RemarksFormat, bool RemarksWithHotness, std::optional&lt; uint64_t &gt; RemarksHotnessThreshold=0, int Count=-1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setup optimization remarks. <a href="#adf0da31fd6ca90efb2819d0f6061bd74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile">ToolOutputFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7df2e6bd8a987ca6e4e4ced678ecbfcf">setupStatsFile</a> (StringRef StatsFilename)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setups the output file for saving statistics. <a href="#a7df2e6bd8a987ca6e4e4ced678ecbfcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace97ef2f9463e686abe5c98640efd258">generateModulesOrdering</a> (ArrayRef&lt; BitcodeModule * &gt; R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produces a container ordering for optimal multi-threaded processing. <a href="#ace97ef2f9463e686abe5c98640efd258">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9c751bcb415f1be4994bce1ef6288e">updateMemProfAttributes</a> (Module &amp;Mod, const ModuleSummaryIndex &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates MemProf attributes (and metadata) based on whether the index has recorded that we are linking with allocation libraries containing the necessary APIs for downstream transformations. <a href="#afe9c751bcb415f1be4994bce1ef6288e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend">ThinBackend</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ba26df9bcc2be206bc7c3d77162c665">createInProcessThinBackend</a> (ThreadPoolStrategy Parallelism, IndexWriteCallback OnWrite=nullptr, bool ShouldEmitIndexFiles=false, bool ShouldEmitImportsFiles=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This <a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend">ThinBackend</a> runs the individual backend jobs in-process. <a href="#a0ba26df9bcc2be206bc7c3d77162c665">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend">ThinBackend</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab71d9a6e89351ab0ad64e64a4e96f4f7">createWriteIndexesThinBackend</a> (ThreadPoolStrategy Parallelism, std::string OldPrefix, std::string NewPrefix, std::string NativeObjectPrefix, bool ShouldEmitImportsFiles, raw_fd_ostream *LinkedObjectsFile, IndexWriteCallback OnWrite)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This <a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend">ThinBackend</a> writes individual module indexes to files, instead of running the individual backend jobs. <a href="#ab71d9a6e89351ab0ad64e64a4e96f4f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3dc87f8d2d7b79aa7da2d3224f3f63d">opt</a> (const Config &amp;Conf, TargetMachine *TM, unsigned Task, Module &amp;Mod, bool IsThinLTO, ModuleSummaryIndex *ExportSummary, const ModuleSummaryIndex *ImportSummary, const std::vector&lt; uint8_t &gt; &amp;CmdArgs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs middle-end <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> optimizations on <span class="doxyComputerOutput">Mod</span>. <a href="#ae3dc87f8d2d7b79aa7da2d3224f3f63d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89ef034c1f3a70da2446c1af1d656dab">backend</a> (const Config &amp;C, AddStreamFn AddStream, unsigned ParallelCodeGenParallelismLevel, Module &amp;M, ModuleSummaryIndex &amp;CombinedIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs a regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> backend. <a href="#a89ef034c1f3a70da2446c1af1d656dab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6ff75e89240b2f2c01d3be088ca6014">thinBackend</a> (const Config &amp;C, unsigned Task, AddStreamFn AddStream, Module &amp;M, const ModuleSummaryIndex &amp;CombinedIndex, const FunctionImporter::ImportMapTy &amp;ImportList, const GVSummaryMapTy &amp;DefinedGlobals, MapVector&lt; StringRef, BitcodeModule &gt; *ModuleMap, bool CodeGenOnly, AddStreamFn IRAddStream=nullptr, const std::vector&lt; uint8_t &gt; &amp;CmdArgs=std::vector&lt; uint8_t &gt;())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Runs a ThinLTO backend. <a href="#ae6ff75e89240b2f2c01d3be088ca6014">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf9cf61a64ab2f14496104cc59a28d22">finalizeOptimizationRemarks</a> (std::unique_ptr&lt; ToolOutputFile &gt; DiagOutputFile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85cf54f25bd787c7983fe72e15233000">findThinLTOModule</a> (MutableArrayRef&lt; BitcodeModule &gt; BMs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> that is ThinLTO. <a href="#a85cf54f25bd787c7983fe72e15233000">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a740eafdbb24797d2db01e3d0ca05a89c">findThinLTOModule</a> (MemoryBufferRef MBRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Variant of the above. <a href="#a740eafdbb24797d2db01e3d0ca05a89c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86eef0f28ae21c5e2b4ace11e1592f1">initImportList</a> (const Module &amp;M, const ModuleSummaryIndex &amp;CombinedIndex, FunctionImporter::ImportMapTy &amp;ImportList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Distributed ThinLTO: collect the referenced modules based on module summary and initialize ImportList. <a href="#ac86eef0f28ae21c5e2b4ace11e1592f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### IndexWriteCallback {#a8dfcd0c2c963dcc17b900f0a7876f6b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::lto::IndexWriteCallback =  std::function&lt;void(const std::string &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### ThinBackendFunction {#aefd057e726ed7c74b8765a1934a5fa7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::lto::ThinBackendFunction =  std::function&lt;std::unique_ptr&lt;ThinBackendProc&gt;(
    const Config &amp;C, ModuleSummaryIndex &amp;CombinedIndex,
    const DenseMap&lt;StringRef, GVSummaryMapTy&gt; &amp;ModuleToDefinedGVSummaries,
    AddStreamFn AddStream, FileCache Cache)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This callable defines the behavior of a ThinLTO backend after the thin-link phase.</p>


<p>It accepts a configuration <span class="doxyComputerOutput">C</span>, a combined module summary index <span class="doxyComputerOutput">CombinedIndex</span>, a map of module identifiers to global variable summaries <span class="doxyComputerOutput">ModuleToDefinedGVSummaries</span>, a function to add output streams <span class="doxyComputerOutput">AddStream</span>, and a file cache <span class="doxyComputerOutput">Cache</span>. It returns a unique pointer to a <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc">ThinBackendProc</a>, which can be used to launch backends in parallel.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### backend() {#a89ef034c1f3a70da2446c1af1d656dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::lto::backend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, unsigned ParallelCodeGenParallelismLevel, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs a regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> backend.</p>


<p>The regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> backend can also act as the regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> phase of ThinLTO, which may need to access the combined index.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a>, definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abfc7ebfffc7baaf23279854fec1412ac">createTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a388c19dd51467226753e433499a85e44">initAndLookupTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="#ae3dc87f8d2d7b79aa7da2d3224f3f63d">opt</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a2fad224b57541514de4fb5be6eb2e7f1">splitCodeGen</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### createInProcessThinBackend() {#a0ba26df9bcc2be206bc7c3d77162c665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThinBackend llvm::lto::createInProcessThinBackend (<a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a> Parallelism, <a href="#a8dfcd0c2c963dcc17b900f0a7876f6b4">IndexWriteCallback</a> OnWrite=nullptr, bool ShouldEmitIndexFiles=false, bool ShouldEmitImportsFiles=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This <a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend">ThinBackend</a> runs the individual backend jobs in-process.</p>


<p>The default value means to use one job per hardware core (not hyper-thread). OnWrite is callback which receives module identifier and notifies <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> user that index file for the module (and optionally imports file) was created. ShouldEmitIndexFiles being true will write sharded ThinLTO index files to the same path as the input module, with suffix ".thinlto.bc" ShouldEmitImportsFiles is true it also writes a list of imported files to a similar path with ".imports" appended instead.</p>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1705 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### createWriteIndexesThinBackend() {#ab71d9a6e89351ab0ad64e64a4e96f4f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThinBackend llvm::lto::createWriteIndexesThinBackend (<a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a> Parallelism, std::string OldPrefix, std::string NewPrefix, std::string NativeObjectPrefix, bool ShouldEmitImportsFiles, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> * LinkedObjectsFile, <a href="#a8dfcd0c2c963dcc17b900f0a7876f6b4">IndexWriteCallback</a> OnWrite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This <a href="/web-llvm/docs/api/structs/llvm/lto/thinbackend">ThinBackend</a> writes individual module indexes to files, instead of running the individual backend jobs.</p>


<p>This backend is for distributed builds where separate processes will invoke the real backends.</p>


<p>To find the path to write the index to, the backend checks if the path has a prefix of OldPrefix; if so, it replaces that prefix with NewPrefix. It then appends ".thinlto.bc" and writes the index to that path. If ShouldEmitImportsFiles is true it also writes a list of imported files to a similar path with ".imports" appended instead. LinkedObjectsFile is an output stream to write the list of object files for the final ThinLTO linking. Can be nullptr. If LinkedObjectsFile is not nullptr and NativeObjectPrefix is not empty then it replaces the prefix of the objects with NativeObjectPrefix instead of NewPrefix. OnWrite is callback which receives module identifier and notifies <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> user that index file for the module (and optionally imports file) was created.</p>


<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### finalizeOptimizationRemarks() {#abf9cf61a64ab2f14496104cc59a28d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::lto::finalizeOptimizationRemarks (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile">ToolOutputFile</a> &gt; DiagOutputFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ae6ff75e89240b2f2c01d3be088ca6014">thinBackend</a>.</p>

</div>
</div>

### findThinLTOModule() {#a85cf54f25bd787c7983fe72e15233000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitcodeModule * llvm::lto::findThinLTOModule (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; BMs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> that is ThinLTO.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a>, definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aae2bf8b46988a2fc0589e95903930c19">llvm::MutableArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a0046b3c8795f231a43ff155b23bbb36e">ThinLTOAssumeMerged</a>.</p>


<p>Referenced by <a href="#a740eafdbb24797d2db01e3d0ca05a89c">findThinLTOModule</a> and <a href="#ae6ff75e89240b2f2c01d3be088ca6014">thinBackend</a>.</p>

</div>
</div>

### findThinLTOModule() {#a740eafdbb24797d2db01e3d0ca05a89c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; BitcodeModule &gt; llvm::lto::findThinLTOModule (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> MBRef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Variant of the above.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="#a85cf54f25bd787c7983fe72e15233000">findThinLTOModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84ff19acc1b6cba55e1006e5be8e6453">llvm::getBitcodeModuleList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### generateModulesOrdering() {#ace97ef2f9463e686abe5c98640efd258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; int &gt; llvm::lto::generateModulesOrdering (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> * &gt; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produces a container ordering for optimal multi-threaded processing.</p>


<p>Returns ordered indices to elements in the input array.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 2135 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a>.</p>

</div>
</div>

### getThinLTODefaultCPU() {#a7d269a83a714b7924ac1d67e52655c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringLiteral llvm::lto::getThinLTODefaultCPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">llvm::Triple::aarch64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a32dff8f6f7ea462f82443a33fdf1e4ac">llvm::Triple::isArm64e</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ab6fdf9b428bc3d57837022121c155cbf">llvm::Triple::isOSDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a3378f6544e8a6b129793370d1399c66a">initTMBuilder</a>.</p>

</div>
</div>

### getThinLTOOutputFile() {#a18eabcf596deec54ada617114b818baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::getThinLTOOutputFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OldPrefix, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NewPrefix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given the original <span class="doxyComputerOutput">Path</span> to an output file, replace any path prefix matching <span class="doxyComputerOutput">OldPrefix</span> with <span class="doxyComputerOutput">NewPrefix</span>.</p>


<p>Also, create the resulting directory if it does not yet exist.</p>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1739 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab0231205adf0a10ac89540dbcfdcd2d7">llvm::sys::fs::create_directories</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb31f2db6f0fe5eaa5b28464141223aa">llvm::sys::path::replace_path_prefix</a> and <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#a55d36203adadf1f53c19463943f24196">anonymous{LTO.cpp}::WriteIndexesThinBackend::start</a>.</p>

</div>
</div>

### initImportList() {#ac86eef0f28ae21c5e2b4ace11e1592f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::initImportList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Distributed ThinLTO: collect the referenced modules based on module summary and initialize ImportList.</p>


<p>Returns false if the operation failed.</p>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a>, definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty/#a6b03ca181770e8c968749ce57cf8902a">llvm::FunctionImporter::ImportMapTy::addGUID</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a0046b3c8795f231a43ff155b23bbb36e">ThinLTOAssumeMerged</a>.</p>

</div>
</div>

### opt() {#ae3dc87f8d2d7b79aa7da2d3224f3f63d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::opt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM, unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, bool IsThinLTO, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ImportSummary, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; uint8_t &gt; &amp; CmdArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs middle-end <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> optimizations on <span class="doxyComputerOutput">Mod</span>.</p>

<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a224082742eac946c1e886179fd48be59">EmbedBitcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a1646f93a5de6149d17f91e14a7523f7ead33347b4d20baa015bccc5548911f233">EmbedPostMergePreOptimized</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#aafc1b31eca401e3ab7a3be9d8fdb697d">isEmptyModule</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ad583f6a59d2c6c9debe64279846d7123">llvm::lto::Config::OptLevel</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ab380a759b3e8d32fc59b8f88b52fe198">llvm::lto::Config::PostOptModuleHook</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>


<p>Referenced by <a href="#a89ef034c1f3a70da2446c1af1d656dab">backend</a> and <a href="#ae6ff75e89240b2f2c01d3be088ca6014">thinBackend</a>.</p>

</div>
</div>

### setupLLVMOptimizationRemarks() {#adf0da31fd6ca90efb2819d0f6061bd74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ToolOutputFile &gt; &gt; llvm::lto::setupLLVMOptimizationRemarks (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarksFilename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarksPasses, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarksFormat, bool RemarksWithHotness, std::optional&lt; uint64_t &gt; RemarksHotnessThreshold=0, int Count=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Setup optimization remarks.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 2091 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8dbf0a7ff527022e0bc9313961d098d9">llvm::RemarksFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a00aed2787bd3f818d745a1ef171bf3">llvm::RemarksFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2f0e273d7dfee8425f06bc1959a6e36">llvm::RemarksHotnessThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a674af5908403fd9aa59aa8194241f">llvm::RemarksPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b19e8926f03fc73e087818aa81bcb37">llvm::RemarksWithHotness</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a861311f8fc18e2eb0035cccb0b1acaac">llvm::setupLLVMOptimizationRemarks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#a0662a37baac76f3ec5c6ca268ae277ac">llvm::LTOCodeGenerator::optimize</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a> and <a href="#ae6ff75e89240b2f2c01d3be088ca6014">thinBackend</a>.</p>

</div>
</div>

### setupStatsFile() {#a7df2e6bd8a987ca6e4e4ced678ecbfcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; ToolOutputFile &gt; &gt; llvm::lto::setupStatsFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StatsFilename)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Setups the output file for saving statistics.</p>

<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 2116 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5fa843ed7ad4b46e6ba9e284656eab96">llvm::EnableStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#a0662a37baac76f3ec5c6ca268ae277ac">llvm::LTOCodeGenerator::optimize</a> and <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#ada5eca1803d5afcb1005ea05ffc62636">llvm::lto::LTO::run</a>.</p>

</div>
</div>

### thinBackend() {#ae6ff75e89240b2f2c01d3be088ca6014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::lto::thinBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; C, unsigned Task, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &amp; DefinedGlobals, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; * ModuleMap, bool CodeGenOnly, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> IRAddStream=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; uint8_t &gt; &amp; CmdArgs=std::vector&lt; uint8_t &gt;())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Runs a ThinLTO backend.</p>


<p>If <span class="doxyComputerOutput">ModuleMap</span> is not nullptr, all the module files to be imported have already been mapped to memory and the corresponding <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> objects are saved in the ModuleMap. If <span class="doxyComputerOutput">ModuleMap</span> is nullptr, module files will be mapped to memory on demand and at any given time during importing, only one source module will be kept open at the most. If <span class="doxyComputerOutput">CodeGenOnly</span> is true, the backend will skip optimization and only perform code generation. If <span class="doxyComputerOutput">IRAddStream</span> is not nullptr, it will be called just before code generation to serialize the optimized IR.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abfc7ebfffc7baaf23279854fec1412ac">createTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pielevel/#ae01fe422624f3a5afd84d14146f9112ca0b4e3e20dca8947e14cee3d5fe0e4fa8">llvm::PIELevel::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a330a18768ffaafb198c726071dcfcb29">dropDeadSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a0881334358ff6ff7ff8cea5562c7988e">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end</a>, <a href="#abf9cf61a64ab2f14496104cc59a28d22">finalizeOptimizationRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a>, <a href="#a85cf54f25bd787c7983fe72e15233000">findThinLTOModule</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a388c19dd51467226753e433499a85e44">initAndLookupTarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="#ae3dc87f8d2d7b79aa7da2d3224f3f63d">opt</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ad5f3c0f8fbd4bf85381e96cc672beb13">llvm::lto::Config::PostImportModuleHook</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ace0039edf4791c66d2eb99dab50fe8f9">llvm::lto::Config::PostInternalizeModuleHook</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a929cce8a073bdcefff79d854deedb7ed">llvm::lto::Config::PostPromoteModuleHook</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a496d67358c7f1e3a328e3ba2cda26268">llvm::lto::Config::PreOptModuleHook</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a7f5add25ae56d0b0c8c3486115a6f825">llvm::lto::Config::RemarksFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#afdc99ed0043add37ba2764446dbe225e">llvm::lto::Config::RemarksFormat</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#a3fb18e2c1449a48f3ce809e398c8496c">llvm::lto::Config::RemarksHotnessThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ab6be094bc919f0a88daf638a87f35ed2">llvm::lto::Config::RemarksPasses</a>, <a href="/web-llvm/docs/api/structs/llvm/lto/config/#ad722bd2d07c784bdf48e98d88a25b214">llvm::lto::Config::RemarksWithHotness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a46122434c47e17760d4c6709878a0dd6">llvm::renameModuleForThinLTO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#aa073bf33e4e66824238bc510dcdf0f4e">llvm::cgdata::saveModuleForTwoRounds</a>, <a href="#adf0da31fd6ca90efb2819d0f6061bd74">setupLLVMOptimizationRemarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a0046b3c8795f231a43ff155b23bbb36e">ThinLTOAssumeMerged</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac69630533101ec5ba74953a63082148">llvm::thinLTOInternalizeModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="#afe9c751bcb415f1be4994bce1ef6288e">updateMemProfAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a714c6f3608e37d0dba17cdc086dc16d2">llvm::updatePublicTypeTestCalls</a> and <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a32f52ba98a64695d078f21e4c14865b9">llvm::ModuleSummaryIndex::withWholeProgramVisibility</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>.</p>

</div>
</div>

### updateMemProfAttributes() {#afe9c751bcb415f1be4994bce1ef6288e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::lto::updateMemProfAttributes (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Mod, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates MemProf attributes (and metadata) based on whether the index has recorded that we are linking with allocation libraries containing the necessary APIs for downstream transformations.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>


<p>Referenced by <a href="#ae6ff75e89240b2f2c01d3be088ca6014">thinBackend</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/ltobackend-h">LTOBackend.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
