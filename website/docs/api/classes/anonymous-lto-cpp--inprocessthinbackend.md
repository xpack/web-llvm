---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lto-cpp-/inprocessthinbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InProcessThinBackend` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{LTO.cpp}::InProcessThinBackend { ... }
</div>

## Base class

<table class="doxyMembersIndex">

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

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend">FirstRoundThinBackend</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This backend is utilized in the first round of a two-codegen round process. <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend">SecondRoundThinBackend</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This backend operates in the second round of a two-codegen round process. <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac623fd2d132c0a19c1b96c76a0821b92">InProcessThinBackend</a> (const Config &amp;Conf, ModuleSummaryIndex &amp;CombinedIndex, ThreadPoolStrategy ThinLTOParallelism, const DenseMap&lt; StringRef, GVSummaryMapTy &gt; &amp;ModuleToDefinedGVSummaries, AddStreamFn AddStream, FileCache Cache, lto::IndexWriteCallback OnWrite, bool ShouldEmitIndexFiles, bool ShouldEmitImportsFiles)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f9c1c44f600c3385ef076febf8c440">runThinLTOBackendThread</a> (AddStreamFn AddStream, FileCache Cache, unsigned Task, BitcodeModule BM, ModuleSummaryIndex &amp;CombinedIndex, const FunctionImporter::ImportMapTy &amp;ImportList, const FunctionImporter::ExportSetTy &amp;ExportList, const std::map&lt; GlobalValue::GUID, GlobalValue::LinkageTypes &gt; &amp;ResolvedODR, const GVSummaryMapTy &amp;DefinedGlobals, MapVector&lt; StringRef, BitcodeModule &gt; &amp;ModuleMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eaa0d8072fbaa8f8304a531ca7bc48e">start</a> (unsigned Task, BitcodeModule BM, const FunctionImporter::ImportMapTy &amp;ImportList, const FunctionImporter::ExportSetTy &amp;ExportList, const std::map&lt; GlobalValue::GUID, GlobalValue::LinkageTypes &gt; &amp;ResolvedODR, MapVector&lt; StringRef, BitcodeModule &gt; &amp;ModuleMap) override</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e40a6c128332df137e020c5317ec3fc">AddStream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e940b48f058706dcb5400acec09a97d">Cache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684f94a1c1eb28cab7e18118c5915329">CfiFunctionDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73936d31a393951b426e54b14ec410de">CfiFunctionDecls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd0e51c15024cc410b847334f9acb94">ShouldEmitIndexFiles</a></td>
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


<p>Definition at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InProcessThinBackend() {#ac623fd2d132c0a19c1b96c76a0821b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a> ThinLTOParallelism, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &gt; &amp; ModuleToDefinedGVSummaries, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> Cache, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a8dfcd0c2c963dcc17b900f0a7876f6b4">lto::IndexWriteCallback</a> OnWrite, bool ShouldEmitIndexFiles, bool ShouldEmitImportsFiles)</td>
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



<p>Definition at line 1429 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="#a4e40a6c128332df137e020c5317ec3fc">AddStream</a>, <a href="#a3e940b48f058706dcb5400acec09a97d">Cache</a>, <a href="#a73936d31a393951b426e54b14ec410de">CfiFunctionDecls</a>, <a href="#a684f94a1c1eb28cab7e18118c5915329">CfiFunctionDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#ab8094ff0500eabc75ec9221b20813395">llvm::lto::ThinBackendProc::CombinedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a23f3830862bd1bd43d296d80bb233c61">llvm::lto::ThinBackendProc::Conf</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e999e4bb7297d284f931638721840e5">llvm::GlobalValue::dropLLVMManglingEscape</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a959a643bd488dc268286ab44d7eb0969">llvm::lto::ThinBackendProc::ModuleToDefinedGVSummaries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#afa1ec8ab27de1059e0e0f8993e1a481a">llvm::lto::ThinBackendProc::OnWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a370e2865ffc9e41b3e6ee6bafc42bb6d">llvm::lto::ThinBackendProc::ShouldEmitImportsFiles</a>, <a href="#a2cd0e51c15024cc410b847334f9acb94">ShouldEmitIndexFiles</a> and <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#aaacea6e8d474d977fc7e464426eb94c9">llvm::lto::ThinBackendProc::ThinBackendProc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a403bfe19b112f4d389639e754930b37c">anonymous{LTO.cpp}::FirstRoundThinBackend::FirstRoundThinBackend</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#a9b52cd9ecae71d8b395d4204a8d2b9c3">anonymous{LTO.cpp}::SecondRoundThinBackend::SecondRoundThinBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runThinLTOBackendThread() {#af0f9c1c44f600c3385ef076febf8c440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread (<a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> Cache, unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> BM, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &amp; ExportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt; &amp; ResolvedODR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &amp; DefinedGlobals, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; &amp; ModuleMap)</td>
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



<p>Definition at line 1447 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="#a4e40a6c128332df137e020c5317ec3fc">AddStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#a3e940b48f058706dcb5400acec09a97d">Cache</a>, <a href="#a73936d31a393951b426e54b14ec410de">CfiFunctionDecls</a>, <a href="#a684f94a1c1eb28cab7e18118c5915329">CfiFunctionDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#ab8094ff0500eabc75ec9221b20813395">llvm::lto::ThinBackendProc::CombinedIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a23f3830862bd1bd43d296d80bb233c61">llvm::lto::ThinBackendProc::Conf</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a319ef14c9ce4b7ca607149680d990477">llvm::lto::ThinBackendProc::emitFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a38e66dcc828b7111e1c77c999cd65c3e">llvm::lto::ThinBackendProc::Err</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a80437440e99d3bf259d0346e9f1d4eb4">llvm::BitcodeModule::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#ad91675f9de94dd24bcee05126b1d7aeb">llvm::BitcodeModule::parseModule</a>, <a href="#a2cd0e51c15024cc410b847334f9acb94">ShouldEmitIndexFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>


<p>Referenced by <a href="#a5eaa0d8072fbaa8f8304a531ca7bc48e">start</a>.</p>

</div>
</div>

### start() {#a5eaa0d8072fbaa8f8304a531ca7bc48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{LTO.cpp}::InProcessThinBackend::start (unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> BM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &amp; ExportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt; &amp; ResolvedODR, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; &amp; ModuleMap)</td>
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



<p>Definition at line 1494 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="#a4e40a6c128332df137e020c5317ec3fc">AddStream</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a1103aa62b6a9fbfc1af097635151b958">llvm::lto::ThinBackendProc::BackendThreadPool</a>, <a href="#a3e940b48f058706dcb5400acec09a97d">Cache</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#ab8094ff0500eabc75ec9221b20813395">llvm::lto::ThinBackendProc::CombinedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a23f3830862bd1bd43d296d80bb233c61">llvm::lto::ThinBackendProc::Conf</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a38e66dcc828b7111e1c77c999cd65c3e">llvm::lto::ThinBackendProc::Err</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#aa6b5156b8321a6d5dc755924fc29b55a">llvm::lto::ThinBackendProc::ErrMu</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a80437440e99d3bf259d0346e9f1d4eb4">llvm::BitcodeModule::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a959a643bd488dc268286ab44d7eb0969">llvm::lto::ThinBackendProc::ModuleToDefinedGVSummaries</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#afa1ec8ab27de1059e0e0f8993e1a481a">llvm::lto::ThinBackendProc::OnWrite</a>, <a href="#af0f9c1c44f600c3385ef076febf8c440">runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e4bd81e19cb403568eeb49955889e2b">llvm::timeTraceProfilerFinishThread</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a69b4f7af261bc6ace511b775a3cb41f6">llvm::timeTraceProfilerInitialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AddStream {#a4e40a6c128332df137e020c5317ec3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddStreamFn anonymous{LTO.cpp}::InProcessThinBackend::AddStream</td>
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



<p>Definition at line 1421 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>Referenced by <a href="#ac623fd2d132c0a19c1b96c76a0821b92">InProcessThinBackend</a>, <a href="#af0f9c1c44f600c3385ef076febf8c440">runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#a9b52cd9ecae71d8b395d4204a8d2b9c3">anonymous{LTO.cpp}::SecondRoundThinBackend::SecondRoundThinBackend</a> and <a href="#a5eaa0d8072fbaa8f8304a531ca7bc48e">start</a>.</p>

</div>
</div>

### Cache {#a3e940b48f058706dcb5400acec09a97d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCache anonymous{LTO.cpp}::InProcessThinBackend::Cache</td>
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



<p>Definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>Referenced by <a href="#ac623fd2d132c0a19c1b96c76a0821b92">InProcessThinBackend</a>, <a href="#af0f9c1c44f600c3385ef076febf8c440">runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#a9b52cd9ecae71d8b395d4204a8d2b9c3">anonymous{LTO.cpp}::SecondRoundThinBackend::SecondRoundThinBackend</a> and <a href="#a5eaa0d8072fbaa8f8304a531ca7bc48e">start</a>.</p>

</div>
</div>

### CfiFunctionDecls {#a73936d31a393951b426e54b14ec410de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;GlobalValue::GUID&gt; anonymous{LTO.cpp}::InProcessThinBackend::CfiFunctionDecls</td>
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



<p>Definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>Referenced by <a href="#ac623fd2d132c0a19c1b96c76a0821b92">InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="#af0f9c1c44f600c3385ef076febf8c440">runThinLTOBackendThread</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>.</p>

</div>
</div>

### CfiFunctionDefs {#a684f94a1c1eb28cab7e18118c5915329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;GlobalValue::GUID&gt; anonymous{LTO.cpp}::InProcessThinBackend::CfiFunctionDefs</td>
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



<p>Definition at line 1423 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>Referenced by <a href="#ac623fd2d132c0a19c1b96c76a0821b92">InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="#af0f9c1c44f600c3385ef076febf8c440">runThinLTOBackendThread</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>.</p>

</div>
</div>

### ShouldEmitIndexFiles {#a2cd0e51c15024cc410b847334f9acb94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LTO.cpp}::InProcessThinBackend::ShouldEmitIndexFiles</td>
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



<p>Definition at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>Referenced by <a href="#ac623fd2d132c0a19c1b96c76a0821b92">InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a> and <a href="#af0f9c1c44f600c3385ef076febf8c440">runThinLTOBackendThread</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
