---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lto-cpp-/secondroundthinbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SecondRoundThinBackend` Class Reference

<p>This backend operates in the second round of a two-codegen round process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LTO.cpp}::SecondRoundThinBackend { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b52cd9ecae71d8b395d4204a8d2b9c3">SecondRoundThinBackend</a> (const Config &amp;Conf, ModuleSummaryIndex &amp;CombinedIndex, ThreadPoolStrategy ThinLTOParallelism, const DenseMap&lt; StringRef, GVSummaryMapTy &gt; &amp;ModuleToDefinedGVSummaries, AddStreamFn AddStream, FileCache Cache, std::unique_ptr&lt; SmallVector&lt; StringRef &gt; &gt; IRFiles, stable_hash CombinedCGDataHash)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3c878292daedae87b12a69a4a05c046">runThinLTOBackendThread</a> (AddStreamFn AddStream, FileCache Cache, unsigned Task, BitcodeModule BM, ModuleSummaryIndex &amp;CombinedIndex, const FunctionImporter::ImportMapTy &amp;ImportList, const FunctionImporter::ExportSetTy &amp;ExportList, const std::map&lt; GlobalValue::GUID, GlobalValue::LinkageTypes &gt; &amp;ResolvedODR, const GVSummaryMapTy &amp;DefinedGlobals, MapVector&lt; StringRef, BitcodeModule &gt; &amp;ModuleMap) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93bfb84c3c9c5900e096cbcd8d15507">IRFiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61aa18197a1bdca0596e1b807782a1c7">CombinedCGDataHash</a></td>
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

<p>This backend operates in the second round of a two-codegen round process.</p>


<p>It starts by reading the optimized bitcode files that were saved during the first round. The backend then executes the codegen only to further optimize the code, utilizing the codegen data merged from the first round. Finally, it writes the resulting object files as usual.</p>


<p>Definition at line 1636 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SecondRoundThinBackend() {#a9b52cd9ecae71d8b395d4204a8d2b9c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LTO.cpp}::SecondRoundThinBackend::SecondRoundThinBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a> ThinLTOParallelism, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &gt; &amp; ModuleToDefinedGVSummaries, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> Cache, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt; IRFiles, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> CombinedCGDataHash)</td>
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



<p>Definition at line 1641 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a4e40a6c128332df137e020c5317ec3fc">anonymous{LTO.cpp}::InProcessThinBackend::AddStream</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a3e940b48f058706dcb5400acec09a97d">anonymous{LTO.cpp}::InProcessThinBackend::Cache</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#ab8094ff0500eabc75ec9221b20813395">llvm::lto::ThinBackendProc::CombinedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a23f3830862bd1bd43d296d80bb233c61">llvm::lto::ThinBackendProc::Conf</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a959a643bd488dc268286ab44d7eb0969">llvm::lto::ThinBackendProc::ModuleToDefinedGVSummaries</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runThinLTOBackendThread() {#ad3c878292daedae87b12a69a4a05c046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread (<a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, <a href="/web-llvm/docs/api/structs/llvm/filecache">FileCache</a> Cache, unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> BM, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &amp; ExportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt; &amp; ResolvedODR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &amp; DefinedGlobals, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; &amp; ModuleMap)</td>
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



<p>Definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a4e40a6c128332df137e020c5317ec3fc">anonymous{LTO.cpp}::InProcessThinBackend::AddStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a3e940b48f058706dcb5400acec09a97d">anonymous{LTO.cpp}::InProcessThinBackend::Cache</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a73936d31a393951b426e54b14ec410de">anonymous{LTO.cpp}::InProcessThinBackend::CfiFunctionDecls</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a684f94a1c1eb28cab7e18118c5915329">anonymous{LTO.cpp}::InProcessThinBackend::CfiFunctionDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#ab8094ff0500eabc75ec9221b20813395">llvm::lto::ThinBackendProc::CombinedIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a23f3830862bd1bd43d296d80bb233c61">llvm::lto::ThinBackendProc::Conf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a38e66dcc828b7111e1c77c999cd65c3e">llvm::lto::ThinBackendProc::Err</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a80437440e99d3bf259d0346e9f1d4eb4">llvm::BitcodeModule::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#aedbd5b8bb99f2c1816738f4687a3b43a">llvm::cgdata::loadModuleForTwoRounds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a711692a20f5aa35bff597391ea3666fa">llvm::recomputeLTOCacheKey</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CombinedCGDataHash {#a61aa18197a1bdca0596e1b807782a1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">stable_hash anonymous{LTO.cpp}::SecondRoundThinBackend::CombinedCGDataHash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1638 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### IRFiles {#ad93bfb84c3c9c5900e096cbcd8d15507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SmallVector&lt;StringRef&gt; &gt; anonymous{LTO.cpp}::SecondRoundThinBackend::IRFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1637 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
