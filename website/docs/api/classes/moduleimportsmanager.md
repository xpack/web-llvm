---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/moduleimportsmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ModuleImportsManager` Class Reference

<p>Determine the list of imports and exports for each module. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ModuleImportsManager { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

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

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8972791f7ffadd05e220b4e7e09cba">ModuleImportsManager</a> (function_ref&lt; bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; IsPrevailing, const ModuleSummaryIndex &amp;Index, DenseMap&lt; StringRef, FunctionImporter::ExportSetTy &gt; *ExportLists=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a3454591a5ee718dbf250c4a95adc34">~ModuleImportsManager</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af806f9d842ec97d31bd9550eb338f678">computeImportForModule</a> (const GVSummaryMapTy &amp;DefinedGVSummaries, StringRef ModName, FunctionImporter::ImportMapTy &amp;ImportList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the list of globals defined in a module, compute the list of imports as well as the list of "exports", i.e. <a href="#af806f9d842ec97d31bd9550eb338f678">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b001539a5e6a5f85dcc886fefda5dc">IsPrevailing</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7b98ef41a696c3512fc1c3b422c4c7">Index</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &gt; *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40827647112314295abf19af886c26c5">ExportLists</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/moduleimportsmanager">ModuleImportsManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a928dfa99d0b0ced1e5a2abe150a51234">create</a> (function_ref&lt; bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; IsPrevailing, const ModuleSummaryIndex &amp;Index, DenseMap&lt; StringRef, FunctionImporter::ExportSetTy &gt; *ExportLists=nullptr)</td>
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

<p>Determine the list of imports and exports for each module.</p>

<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### ModuleImportsManager() {#aad8972791f7ffadd05e220b4e7e09cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleImportsManager::ModuleImportsManager (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt; IsPrevailing, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &gt; * ExportLists=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="#a40827647112314295abf19af886c26c5">ExportLists</a>, <a href="#abb7b98ef41a696c3512fc1c3b422c4c7">Index</a> and <a href="#a92b001539a5e6a5f85dcc886fefda5dc">IsPrevailing</a>.</p>


<p>Referenced by <a href="#a928dfa99d0b0ced1e5a2abe150a51234">create</a> and <a href="/web-llvm/docs/api/classes/workloadimportsmanager/#a153fc7b2387346443f6c6503cc92b47d">WorkloadImportsManager::WorkloadImportsManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ModuleImportsManager() {#a6a3454591a5ee718dbf250c4a95adc34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ModuleImportsManager::~ModuleImportsManager ()</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="#af806f9d842ec97d31bd9550eb338f678">computeImportForModule</a>, <a href="#a928dfa99d0b0ced1e5a2abe150a51234">create</a>, <a href="#a40827647112314295abf19af886c26c5">ExportLists</a>, <a href="#abb7b98ef41a696c3512fc1c3b422c4c7">Index</a> and <a href="#a92b001539a5e6a5f85dcc886fefda5dc">IsPrevailing</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeImportForModule() {#af806f9d842ec97d31bd9550eb338f678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleImportsManager::computeImportForModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a31671124e718a9212f15c19ac1e62515">GVSummaryMapTy</a> &amp; DefinedGVSummaries, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModName, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/importmapty">FunctionImporter::ImportMapTy</a> &amp; ImportList)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given the list of globals defined in a module, compute the list of imports as well as the list of "exports", i.e.</p>


<p>the list of symbols referenced from another module (that may require promotion).</p>


<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a40827647112314295abf19af886c26c5">ExportLists</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a5c93b13860b1955fb9b1359b4dea6855">getFailureName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21f2a6af0e8fcffa3bf64eaf6b345861">llvm::getHotnessName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#aa11e1fe31b58ecb98c3de00a828f0ac1">ImportInstrLimit</a>, <a href="#abb7b98ef41a696c3512fc1c3b422c4c7">Index</a>, <a href="#a92b001539a5e6a5f85dcc886fefda5dc">IsPrevailing</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ac9151ed4e71d344fa4c142f55d6179a5">PrintImportFailures</a>.</p>


<p>Referenced by <a href="#a6a3454591a5ee718dbf250c4a95adc34">~ModuleImportsManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ExportLists {#a40827647112314295abf19af886c26c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;StringRef, FunctionImporter::ExportSetTy&gt;* const ModuleImportsManager::ExportLists</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#af806f9d842ec97d31bd9550eb338f678">computeImportForModule</a>, <a href="#a928dfa99d0b0ced1e5a2abe150a51234">create</a>, <a href="#aad8972791f7ffadd05e220b4e7e09cba">ModuleImportsManager</a>, <a href="/web-llvm/docs/api/classes/workloadimportsmanager/#a153fc7b2387346443f6c6503cc92b47d">WorkloadImportsManager::WorkloadImportsManager</a> and <a href="#a6a3454591a5ee718dbf250c4a95adc34">~ModuleImportsManager</a>.</p>

</div>
</div>

### Index {#abb7b98ef41a696c3512fc1c3b422c4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex&amp; ModuleImportsManager::Index</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#af806f9d842ec97d31bd9550eb338f678">computeImportForModule</a>, <a href="#a928dfa99d0b0ced1e5a2abe150a51234">create</a>, <a href="#aad8972791f7ffadd05e220b4e7e09cba">ModuleImportsManager</a>, <a href="/web-llvm/docs/api/classes/workloadimportsmanager/#a153fc7b2387346443f6c6503cc92b47d">WorkloadImportsManager::WorkloadImportsManager</a> and <a href="#a6a3454591a5ee718dbf250c4a95adc34">~ModuleImportsManager</a>.</p>

</div>
</div>

### IsPrevailing {#a92b001539a5e6a5f85dcc886fefda5dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; ModuleImportsManager::IsPrevailing</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>Referenced by <a href="#af806f9d842ec97d31bd9550eb338f678">computeImportForModule</a>, <a href="#a928dfa99d0b0ced1e5a2abe150a51234">create</a>, <a href="#aad8972791f7ffadd05e220b4e7e09cba">ModuleImportsManager</a>, <a href="/web-llvm/docs/api/classes/workloadimportsmanager/#a153fc7b2387346443f6c6503cc92b47d">WorkloadImportsManager::WorkloadImportsManager</a> and <a href="#a6a3454591a5ee718dbf250c4a95adc34">~ModuleImportsManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a928dfa99d0b0ced1e5a2abe150a51234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ModuleImportsManager &gt; ModuleImportsManager::create (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt; IsPrevailing, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#acd58852b94e5cce68ad66dc3045f72f0">FunctionImporter::ExportSetTy</a> &gt; * ExportLists=nullptr)</td>
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



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a40827647112314295abf19af886c26c5">ExportLists</a>, <a href="#abb7b98ef41a696c3512fc1c3b422c4c7">Index</a>, <a href="#a92b001539a5e6a5f85dcc886fefda5dc">IsPrevailing</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aad8972791f7ffadd05e220b4e7e09cba">ModuleImportsManager</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a5ac99641888d5b06352c629f38485394">UseCtxProfile</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#aae0290be33da33adb70977d0e595ce73">WorkloadDefinitions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5bb138c27be183e4f556f94500de68d8">llvm::ComputeCrossModuleImport</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#af8a95835d82cdc254d43c6f1dd99f7dc">ComputeCrossModuleImportForModuleForTest</a> and <a href="#a6a3454591a5ee718dbf250c4a95adc34">~ModuleImportsManager</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp">FunctionImport.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
