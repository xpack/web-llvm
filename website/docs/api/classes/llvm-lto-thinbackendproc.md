---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lto/thinbackendproc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ThinBackendProc` Class

<p>This class defines the interface to the ThinLTO backend. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::lto::ThinBackendProc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">llvm/LTO/LTO.h</a>"
</div>

## Derived Classes

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend">WriteIndexesThinBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaacea6e8d474d977fc7e464426eb94c9">ThinBackendProc</a> (const Config &amp;Conf, ModuleSummaryIndex &amp;CombinedIndex, const DenseMap&lt; StringRef, GVSummaryMapTy &gt; &amp;ModuleToDefinedGVSummaries, lto::IndexWriteCallback OnWrite, bool ShouldEmitImportsFiles, ThreadPoolStrategy ThinLTOParallelism)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d66a072e69205a2268370f2e47eb98">~ThinBackendProc</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad895ec5457d927fd63e83a7ba035bdc6">start</a> (unsigned Task, BitcodeModule BM, const FunctionImporter::ImportMapTy &amp;ImportList, const FunctionImporter::ExportSetTy &amp;ExportList, const std::map&lt; GlobalValue::GUID, GlobalValue::LinkageTypes &gt; &amp;ResolvedODR, MapVector&lt; StringRef, BitcodeModule &gt; &amp;ModuleMap)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae1e279d2396c526f205fd7f593cbbc">wait</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860160f475902351c30fbe877c0e7be4">getThreadCount</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a836a6b62015c3927d426aad64d6436a7">isSensitiveToInputOrder</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a319ef14c9ce4b7ca607149680d990477">emitFiles</a> (const FunctionImporter::ImportMapTy &amp;ImportList, llvm::StringRef ModulePath, const std::string &amp;NewModulePath) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f3830862bd1bd43d296d80bb233c61">Conf</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8094ff0500eabc75ec9221b20813395">CombinedIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959a643bd488dc268286ab44d7eb0969">ModuleToDefinedGVSummaries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/lto/#a8dfcd0c2c963dcc17b900f0a7876f6b4">IndexWriteCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1ec8ab27de1059e0e0f8993e1a481a">OnWrite</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370e2865ffc9e41b3e6ee6bafc42bb6d">ShouldEmitImportsFiles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ab2b4a8794a239fc36c52ec91b23c0296">DefaultThreadPool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1103aa62b6a9fbfc1af097635151b958">BackendThreadPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e66dcc828b7111e1c77c999cd65c3e">Err</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b5156b8321a6d5dc755924fc29b55a">ErrMu</a></td>
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

<p>This class defines the interface to the ThinLTO backend.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ThinBackendProc() {#aaacea6e8d474d977fc7e464426eb94c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::lto::ThinBackendProc::ThinBackendProc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &gt; &amp; ModuleToDefinedGVSummaries, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a8dfcd0c2c963dcc17b900f0a7876f6b4">lto::IndexWriteCallback</a> OnWrite, bool ShouldEmitImportsFiles, <a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a> ThinLTOParallelism)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>References <a href="#a1103aa62b6a9fbfc1af097635151b958">BackendThreadPool</a>, <a href="#ab8094ff0500eabc75ec9221b20813395">CombinedIndex</a>, <a href="#a23f3830862bd1bd43d296d80bb233c61">Conf</a>, <a href="#a959a643bd488dc268286ab44d7eb0969">ModuleToDefinedGVSummaries</a>, <a href="#afa1ec8ab27de1059e0e0f8993e1a481a">OnWrite</a> and <a href="#a370e2865ffc9e41b3e6ee6bafc42bb6d">ShouldEmitImportsFiles</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#ad4d269b440603b90c79582e6adbb765b">anonymous{LTO.cpp}::WriteIndexesThinBackend::WriteIndexesThinBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ThinBackendProc() {#ad4d66a072e69205a2268370f2e47eb98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::lto::ThinBackendProc::~ThinBackendProc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitFiles() {#a319ef14c9ce4b7ca607149680d990477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ThinBackendProc::emitFiles (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> ModulePath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; NewModulePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>, definition at line 1390 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="#ab8094ff0500eabc75ec9221b20813395">CombinedIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1ad9f56998b03b32a1066b574125126">llvm::EmitImportsFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab60fb2b8daf585b91052154f52ce345e">llvm::gatherImportedSummariesForModule</a>, <a href="#a959a643bd488dc268286ab44d7eb0969">ModuleToDefinedGVSummaries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="#a370e2865ffc9e41b3e6ee6bafc42bb6d">ShouldEmitImportsFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#a55d36203adadf1f53c19463943f24196">anonymous{LTO.cpp}::WriteIndexesThinBackend::start</a>.</p>

</div>
</div>

### getThreadCount() {#a860160f475902351c30fbe877c0e7be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::ThinBackendProc::getThreadCount ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Reference <a href="#a1103aa62b6a9fbfc1af097635151b958">BackendThreadPool</a>.</p>

</div>
</div>

### isSensitiveToInputOrder() {#a836a6b62015c3927d426aad64d6436a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::lto::ThinBackendProc::isSensitiveToInputOrder ()</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### start() {#ad895ec5457d927fd63e83a7ba035bdc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::lto::ThinBackendProc::start (unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> BM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &amp; ExportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt; &amp; ResolvedODR, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; &amp; ModuleMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### wait() {#a6ae1e279d2396c526f205fd7f593cbbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::lto::ThinBackendProc::wait ()</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>References <a href="#a1103aa62b6a9fbfc1af097635151b958">BackendThreadPool</a>, <a href="#a38e66dcc828b7111e1c77c999cd65c3e">Err</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BackendThreadPool {#a1103aa62b6a9fbfc1af097635151b958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefaultThreadPool llvm::lto::ThinBackendProc::BackendThreadPool</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="#a860160f475902351c30fbe877c0e7be4">getThreadCount</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#a55d36203adadf1f53c19463943f24196">anonymous{LTO.cpp}::WriteIndexesThinBackend::start</a>, <a href="#aaacea6e8d474d977fc7e464426eb94c9">ThinBackendProc</a> and <a href="#a6ae1e279d2396c526f205fd7f593cbbc">wait</a>.</p>

</div>
</div>

### CombinedIndex {#ab8094ff0500eabc75ec9221b20813395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSummaryIndex&amp; llvm::lto::ThinBackendProc::CombinedIndex</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="#a319ef14c9ce4b7ca607149680d990477">emitFiles</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a403bfe19b112f4d389639e754930b37c">anonymous{LTO.cpp}::FirstRoundThinBackend::FirstRoundThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#a9b52cd9ecae71d8b395d4204a8d2b9c3">anonymous{LTO.cpp}::SecondRoundThinBackend::SecondRoundThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a>, <a href="#aaacea6e8d474d977fc7e464426eb94c9">ThinBackendProc</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#ad4d269b440603b90c79582e6adbb765b">anonymous{LTO.cpp}::WriteIndexesThinBackend::WriteIndexesThinBackend</a>.</p>

</div>
</div>

### Conf {#a23f3830862bd1bd43d296d80bb233c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Config&amp; llvm::lto::ThinBackendProc::Conf</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a403bfe19b112f4d389639e754930b37c">anonymous{LTO.cpp}::FirstRoundThinBackend::FirstRoundThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#a9b52cd9ecae71d8b395d4204a8d2b9c3">anonymous{LTO.cpp}::SecondRoundThinBackend::SecondRoundThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a>, <a href="#aaacea6e8d474d977fc7e464426eb94c9">ThinBackendProc</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#ad4d269b440603b90c79582e6adbb765b">anonymous{LTO.cpp}::WriteIndexesThinBackend::WriteIndexesThinBackend</a>.</p>

</div>
</div>

### Err {#a38e66dcc828b7111e1c77c999cd65c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Error&gt; llvm::lto::ThinBackendProc::Err</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a2c2b73979dafe07afd42a1d790f7ed8c">anonymous{LTO.cpp}::FirstRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#af0f9c1c44f600c3385ef076febf8c440">anonymous{LTO.cpp}::InProcessThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#ad3c878292daedae87b12a69a4a05c046">anonymous{LTO.cpp}::SecondRoundThinBackend::runThinLTOBackendThread</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#a55d36203adadf1f53c19463943f24196">anonymous{LTO.cpp}::WriteIndexesThinBackend::start</a> and <a href="#a6ae1e279d2396c526f205fd7f593cbbc">wait</a>.</p>

</div>
</div>

### ErrMu {#aa6b5156b8321a6d5dc755924fc29b55a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::lto::ThinBackendProc::ErrMu</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#a55d36203adadf1f53c19463943f24196">anonymous{LTO.cpp}::WriteIndexesThinBackend::start</a>.</p>

</div>
</div>

### ModuleToDefinedGVSummaries {#a959a643bd488dc268286ab44d7eb0969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt;StringRef, GVSummaryMapTy&gt;&amp; llvm::lto::ThinBackendProc::ModuleToDefinedGVSummaries</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="#a319ef14c9ce4b7ca607149680d990477">emitFiles</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/firstroundthinbackend/#a403bfe19b112f4d389639e754930b37c">anonymous{LTO.cpp}::FirstRoundThinBackend::FirstRoundThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/secondroundthinbackend/#a9b52cd9ecae71d8b395d4204a8d2b9c3">anonymous{LTO.cpp}::SecondRoundThinBackend::SecondRoundThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a>, <a href="#aaacea6e8d474d977fc7e464426eb94c9">ThinBackendProc</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#ad4d269b440603b90c79582e6adbb765b">anonymous{LTO.cpp}::WriteIndexesThinBackend::WriteIndexesThinBackend</a>.</p>

</div>
</div>

### OnWrite {#afa1ec8ab27de1059e0e0f8993e1a481a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexWriteCallback llvm::lto::ThinBackendProc::OnWrite</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#a5eaa0d8072fbaa8f8304a531ca7bc48e">anonymous{LTO.cpp}::InProcessThinBackend::start</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#a55d36203adadf1f53c19463943f24196">anonymous{LTO.cpp}::WriteIndexesThinBackend::start</a>, <a href="#aaacea6e8d474d977fc7e464426eb94c9">ThinBackendProc</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#ad4d269b440603b90c79582e6adbb765b">anonymous{LTO.cpp}::WriteIndexesThinBackend::WriteIndexesThinBackend</a>.</p>

</div>
</div>

### ShouldEmitImportsFiles {#a370e2865ffc9e41b3e6ee6bafc42bb6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::ThinBackendProc::ShouldEmitImportsFiles</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<p>Referenced by <a href="#a319ef14c9ce4b7ca607149680d990477">emitFiles</a>, <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/inprocessthinbackend/#ac623fd2d132c0a19c1b96c76a0821b92">anonymous{LTO.cpp}::InProcessThinBackend::InProcessThinBackend</a>, <a href="#aaacea6e8d474d977fc7e464426eb94c9">ThinBackendProc</a> and <a href="/web-llvm/docs/api/classes/anonymous-lto-cpp-/writeindexesthinbackend/#ad4d269b440603b90c79582e6adbb765b">anonymous{LTO.cpp}::WriteIndexesThinBackend::WriteIndexesThinBackend</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
