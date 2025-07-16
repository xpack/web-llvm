---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lto-cpp-/writeindexesthinbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WriteIndexesThinBackend` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{LTO.cpp}::WriteIndexesThinBackend { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d269b440603b90c79582e6adbb765b">WriteIndexesThinBackend</a> (const Config &amp;Conf, ModuleSummaryIndex &amp;CombinedIndex, ThreadPoolStrategy ThinLTOParallelism, const DenseMap&lt; StringRef, GVSummaryMapTy &gt; &amp;ModuleToDefinedGVSummaries, std::string OldPrefix, std::string NewPrefix, std::string NativeObjectPrefix, bool ShouldEmitImportsFiles, raw_fd_ostream *LinkedObjectsFile, lto::IndexWriteCallback OnWrite)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d36203adadf1f53c19463943f24196">start</a> (unsigned Task, BitcodeModule BM, const FunctionImporter::ImportMapTy &amp;ImportList, const FunctionImporter::ExportSetTy &amp;ExportList, const std::map&lt; GlobalValue::GUID, GlobalValue::LinkageTypes &gt; &amp;ResolvedODR, MapVector&lt; StringRef, BitcodeModule &gt; &amp;ModuleMap) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a5033930a09bdc4a119c26bfc908df9">isSensitiveToInputOrder</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5af14724913aa8dcb380f6e102758c9">OldPrefix</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45bdd8edc812cc239201fc32dd69fd6f">NewPrefix</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657595b32954f23ecf82cf1844ee84e8">NativeObjectPrefix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021eff27e8e476d0cbe9715f1ab718f7">LinkedObjectsFile</a></td>
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


<p>Definition at line 1756 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WriteIndexesThinBackend() {#ad4d269b440603b90c79582e6adbb765b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LTO.cpp}::WriteIndexesThinBackend::WriteIndexesThinBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> &amp; Conf, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; CombinedIndex, <a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a> ThinLTOParallelism, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &gt; &amp; ModuleToDefinedGVSummaries, std::string OldPrefix, std::string NewPrefix, std::string NativeObjectPrefix, bool ShouldEmitImportsFiles, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> * LinkedObjectsFile, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a8dfcd0c2c963dcc17b900f0a7876f6b4">lto::IndexWriteCallback</a> OnWrite)</td>
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



<p>Definition at line 1761 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#ab8094ff0500eabc75ec9221b20813395">llvm::lto::ThinBackendProc::CombinedIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a23f3830862bd1bd43d296d80bb233c61">llvm::lto::ThinBackendProc::Conf</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a959a643bd488dc268286ab44d7eb0969">llvm::lto::ThinBackendProc::ModuleToDefinedGVSummaries</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#afa1ec8ab27de1059e0e0f8993e1a481a">llvm::lto::ThinBackendProc::OnWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a370e2865ffc9e41b3e6ee6bafc42bb6d">llvm::lto::ThinBackendProc::ShouldEmitImportsFiles</a> and <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#aaacea6e8d474d977fc7e464426eb94c9">llvm::lto::ThinBackendProc::ThinBackendProc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isSensitiveToInputOrder() {#a4a5033930a09bdc4a119c26bfc908df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LTO.cpp}::WriteIndexesThinBackend::isSensitiveToInputOrder ()</td>
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



<p>Definition at line 1817 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### start() {#a55d36203adadf1f53c19463943f24196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{LTO.cpp}::WriteIndexesThinBackend::start (unsigned Task, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> BM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &amp; ExportList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt; &amp; ResolvedODR, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt; &amp; ModuleMap)</td>
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



<p>Definition at line 1774 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a1103aa62b6a9fbfc1af097635151b958">llvm::lto::ThinBackendProc::BackendThreadPool</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a319ef14c9ce4b7ca607149680d990477">llvm::lto::ThinBackendProc::emitFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#a38e66dcc828b7111e1c77c999cd65c3e">llvm::lto::ThinBackendProc::Err</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#aa6b5156b8321a6d5dc755924fc29b55a">llvm::lto::ThinBackendProc::ErrMu</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a80437440e99d3bf259d0346e9f1d4eb4">llvm::BitcodeModule::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a18eabcf596deec54ada617114b818baf">llvm::lto::getThinLTOOutputFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/lto/thinbackendproc/#afa1ec8ab27de1059e0e0f8993e1a481a">llvm::lto::ThinBackendProc::OnWrite</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LinkedObjectsFile {#a021eff27e8e476d0cbe9715f1ab718f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream* anonymous{LTO.cpp}::WriteIndexesThinBackend::LinkedObjectsFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### NativeObjectPrefix {#a657595b32954f23ecf82cf1844ee84e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{LTO.cpp}::WriteIndexesThinBackend::NativeObjectPrefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### NewPrefix {#a45bdd8edc812cc239201fc32dd69fd6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{LTO.cpp}::WriteIndexesThinBackend::NewPrefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

</div>
</div>

### OldPrefix {#ab5af14724913aa8dcb380f6e102758c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{LTO.cpp}::WriteIndexesThinBackend::OldPrefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1757 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp">LTO.cpp</a>.</p>

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
