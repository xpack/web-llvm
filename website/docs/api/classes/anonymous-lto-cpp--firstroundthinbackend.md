---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lto-cpp-/firstroundthinbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FirstRoundThinBackend` Class

<p>This backend is utilized in the first round of a two-codegen round process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LTO.cpp}::FirstRoundThinBackend { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend">InProcessThinBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403bfe19b112f4d389639e754930b37c">FirstRoundThinBackend</a> (const Config &amp;Conf, ModuleSummaryIndex &amp;CombinedIndex, ThreadPoolStrategy ThinLTOParallelism, const DenseMap&lt; StringRef, GVSummaryMapTy &gt; &amp;ModuleToDefinedGVSummaries, AddStreamFn CGAddStream, FileCache CGCache, AddStreamFn IRAddStream, FileCache IRCache)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2b73979dafe07afd42a1d790f7ed8c">runThinLTOBackendThread</a> (AddStreamFn CGAddStream, FileCache CGCache, unsigned Task, BitcodeModule BM, ModuleSummaryIndex &amp;CombinedIndex, const FunctionImporter::ImportMapTy &amp;ImportList, const FunctionImporter::ExportSetTy &amp;ExportList, const std::map&lt; GlobalValue::GUID, GlobalValue::LinkageTypes &gt; &amp;ResolvedODR, const GVSummaryMapTy &amp;DefinedGlobals, MapVector&lt; StringRef, BitcodeModule &gt; &amp;ModuleMap) override</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc208b1ea759578f498606a1651ef045">IRAddStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c800dc48b8dea93cb661fcdf89e68be">IRCache</a></td>
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

<p>This backend is utilized in the first round of a two-codegen round process.</p>


<p>It first saves optimized bitcode files to disk before the codegen process begins. After codegen, it stores the resulting object files in a scratch buffer. Note the codegen data stored in the scratch buffer will be extracted and merged in the subsequent step.</p>


<p>Definition at line 1542 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FirstRoundThinBackend() {#a403bfe19b112f4d389639e754930b37c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LTO.cpp}::FirstRoundThinBackend::FirstRoundThinBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a> ThinLTOParallelism, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &gt; &amp; ModuleToDefinedGVSummaries, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> CGAddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> CGCache, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> IRAddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> IRCache)</td>
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



<p>Definition at line 1547 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#ab8094ff0500eabc75ec9221b20813395">llvm::lto::ThinBackendProc::CombinedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a23f3830862bd1bd43d296d80bb233c61">llvm::lto::ThinBackendProc::Conf</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a959a643bd488dc268286ab44d7eb0969">llvm::lto::ThinBackendProc::ModuleToDefinedGVSummaries</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runThinLTOBackendThread() {#a2c2b73979dafe07afd42a1d790f7ed8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread (<a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> CGAddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> CGCache, unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> BM, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &amp; ExportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt; &amp; ResolvedODR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &amp; DefinedGlobals, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; &amp; ModuleMap)</td>
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



<p>Definition at line 1560 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a73936d31a393951b426e54b14ec410de">anonymous{LTO.cpp}::InProcessThinBackend::CfiFunctionDecls</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a684f94a1c1eb28cab7e18118c5915329">anonymous{LTO.cpp}::InProcessThinBackend::CfiFunctionDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#ab8094ff0500eabc75ec9221b20813395">llvm::lto::ThinBackendProc::CombinedIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a23f3830862bd1bd43d296d80bb233c61">llvm::lto::ThinBackendProc::Conf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a319ef14c9ce4b7ca607149680d990477">llvm::lto::ThinBackendProc::emitFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a38e66dcc828b7111e1c77c999cd65c3e">llvm::lto::ThinBackendProc::Err</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a80437440e99d3bf259d0346e9f1d4eb4">llvm::BitcodeModule::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/structs/llvm/filecache/#a6e2b3e84fbaf88d816e12ace2237f5d9">llvm::FileCache::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#ad91675f9de94dd24bcee05126b1d7aeb">llvm::BitcodeModule::parseModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a711692a20f5aa35bff597391ea3666fa">llvm::recomputeLTOCacheKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a2cd0e51c15024cc410b847334f9acb94">anonymous{LTO.cpp}::InProcessThinBackend::ShouldEmitIndexFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IRAddStream {#adc208b1ea759578f498606a1651ef045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddStreamFn anonymous{LTO.cpp}::FirstRoundThinBackend::IRAddStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1543 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### IRCache {#a3c800dc48b8dea93cb661fcdf89e68be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCache anonymous{LTO.cpp}::FirstRoundThinBackend::IRCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1544 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
