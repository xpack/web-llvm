---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-openmpopt-cpp-/ompinformationcache
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `OMPInformationCache` Struct

<p>OpenMP specific information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{OpenMPOpt.cpp}::OMPInformationCache { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/informationcache">InformationCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data structure to hold cached (LLVM-IR) information. <a href="/web-llvm/docs/api/structs/llvm/informationcache/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4654342457e24974e89aeb382212159">OMPInformationCache</a> (Module &amp;M, AnalysisGetter &amp;AG, BumpPtrAllocator &amp;Allocator, SetVector&lt; Function * &gt; *CGSCC, bool OpenMPPostLink)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d76d2bce303ce0af946f28de77d445">initializeInternalControlVars</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to initialize all internal control variable information for those defined in OMPKinds.def. <a href="#a63d76d2bce303ce0af946f28de77d445">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f06c6063c3a34171f47246e4c94ce8">collectUses</a> (RuntimeFunctionInfo &amp;RFI, bool CollectStats=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c4037cfc6e6773c2c2d7faf7d33a8ee">recollectUsesForFunction</a> (RuntimeFunction RTF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a580882ca6acde97ca9e012fe5a206d08">recollectUses</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4085e5e5acca78ad7d76140bbe0f36f9">setCallingConvention</a> (FunctionCallee Callee, CallInst *CI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0b41d4bbaf15bfb701ed8eebd2a5c2">runtimeFnsAvailable</a> (ArrayRef&lt; RuntimeFunction &gt; Fns)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72800a43846823ae6cd2d57ac8b886c">initializeRuntimeFunctions</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to initialize all runtime function information for those defined in OpenMPKinds.def. <a href="#af72800a43846823ae6cd2d57ac8b886c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af358e5a643dd21f130e147c7b399bc20">OMPBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An OpenMP-IR-Builder instance. <a href="#af358e5a643dd21f130e147c7b399bc20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enumeratedarray">EnumeratedArray</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo">RuntimeFunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">RuntimeFunction</a>, RuntimeFunction::OMPRTL___last &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d7ac74714aff72e78b7638152e948d6">RFIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from runtime function kind to the runtime function description. <a href="#a5d7ac74714aff72e78b7638152e948d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">RuntimeFunction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda08d1ed27f41e396dc0ede68b92590">RuntimeFunctionIDMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from function declarations/definitions to their runtime enum type. <a href="#abda08d1ed27f41e396dc0ede68b92590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enumeratedarray">EnumeratedArray</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/internalcontrolvarinfo">InternalControlVarInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4608c581e6f18962661f7fc39ea88da2">InternalControlVar</a>, InternalControlVar::ICV___last &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5577456d10dd62c3604fbbed8fe2081">ICVs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from ICV kind to the ICV description. <a href="#ab5577456d10dd62c3604fbbed8fe2081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae19612665dba846449dd96f24f6fd7fa">RTLFunctions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of known OpenMP runtime functions.. <a href="#ae19612665dba846449dd96f24f6fd7fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318ad323e3d4d0fa83725eb95f6f84d3">OpenMPPostLink</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if we have already linked in the OpenMP device library. <a href="#a318ad323e3d4d0fa83725eb95f6f84d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bbf7be621bd7377f3f4a7498010f98a">declMatchesRTFTypes</a> (Function *F, Type *RTFRetType, SmallVector&lt; Type *, 8 &gt; &amp;RTFArgTypes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the function declaration <span class="doxyComputerOutput">F</span> matches the runtime function types, that is, return type <span class="doxyComputerOutput">RTFRetType</span>, and argument types <span class="doxyComputerOutput">RTFArgTypes</span>. <a href="#a0bbf7be621bd7377f3f4a7498010f98a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>OpenMP specific information.</p>


<p>For now, stores RFIs and ICVs also needed for Attributor runs.</p>


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OMPInformationCache() {#aa4654342457e24974e89aeb382212159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{OpenMPOpt.cpp}::OMPInformationCache::OMPInformationCache (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/llvm/analysisgetter">AnalysisGetter</a> &amp; AG, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; * CGSCC, bool OpenMPPostLink)</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#a0dc69ed9f5596c2678f459a6a439203e">llvm::InformationCache::CGSCC</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#aa5327518f157a2460d7c23d62d0fbbac">llvm::InformationCache::InformationCache</a>, <a href="#a63d76d2bce303ce0af946f28de77d445">initializeInternalControlVars</a>, <a href="#af72800a43846823ae6cd2d57ac8b886c">initializeRuntimeFunctions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a138a1ab10971c55c181b7f23b60e4582">llvm::omp::isOpenMPDevice</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae06ff88d5da98b63a6b4397fcb7a6050">llvm::Triple::nvptx</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">llvm::Triple::nvptx64</a>, <a href="#af358e5a643dd21f130e147c7b399bc20">OMPBuilder</a>, <a href="#a318ad323e3d4d0fa83725eb95f6f84d3">OpenMPPostLink</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectUses() {#a86f06c6063c3a34171f47246e4c94ce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{OpenMPOpt.cpp}::OMPInformationCache::collectUses (<a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo">RuntimeFunctionInfo</a> &amp; RFI, bool CollectStats=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/informationcache/#a0dc69ed9f5596c2678f459a6a439203e">llvm::InformationCache::CGSCC</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo/#aa1f41f63221df559d1e2733cc5d09920">anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionInfo::Declaration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aba0055050d741f60b6e0523507a2c79f">llvm::Value::getNumUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo/#a866fc2273ccd554a6ab5d7c58d93aa4c">anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionInfo::getOrCreateUseVector</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo/#adea71ed63c1ba6dadba489aa5f8466ab">anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionInfo::Kind</a>, <a href="#af358e5a643dd21f130e147c7b399bc20">OMPBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a1c4037cfc6e6773c2c2d7faf7d33a8ee">recollectUsesForFunction</a>.</p>

</div>
</div>

### initializeInternalControlVars() {#a63d76d2bce303ce0af946f28de77d445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OpenMPOpt.cpp}::OMPInformationCache::initializeInternalControlVars ()</td>
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

<p>Helper to initialize all internal control variable information for those defined in OMPKinds.def.</p>

<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#aa4654342457e24974e89aeb382212159">OMPInformationCache</a>.</p>

</div>
</div>

### initializeRuntimeFunctions() {#af72800a43846823ae6cd2d57ac8b886c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OpenMPOpt.cpp}::OMPInformationCache::initializeRuntimeFunctions (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Helper to initialize all runtime function information for those defined in OpenMPKinds.def.</p>

<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a138a1ab10971c55c181b7f23b60e4582">llvm::omp::isOpenMPDevice</a>.</p>


<p>Referenced by <a href="#aa4654342457e24974e89aeb382212159">OMPInformationCache</a>.</p>

</div>
</div>

### recollectUses() {#a580882ca6acde97ca9e012fe5a206d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OpenMPOpt.cpp}::OMPInformationCache::recollectUses ()</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="#a1c4037cfc6e6773c2c2d7faf7d33a8ee">recollectUsesForFunction</a> and <a href="#a5d7ac74714aff72e78b7638152e948d6">RFIs</a>.</p>

</div>
</div>

### recollectUsesForFunction() {#a1c4037cfc6e6773c2c2d7faf7d33a8ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OpenMPOpt.cpp}::OMPInformationCache::recollectUsesForFunction (<a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">RuntimeFunction</a> RTF)</td>
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



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="#a86f06c6063c3a34171f47246e4c94ce8">collectUses</a> and <a href="#a5d7ac74714aff72e78b7638152e948d6">RFIs</a>.</p>


<p>Referenced by <a href="#a580882ca6acde97ca9e012fe5a206d08">recollectUses</a>.</p>

</div>
</div>

### runtimeFnsAvailable() {#afd0b41d4bbaf15bfb701ed8eebd2a5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::OMPInformationCache::runtimeFnsAvailable (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">RuntimeFunction</a> &gt; Fns)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo/#aa1f41f63221df559d1e2733cc5d09920">anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionInfo::Declaration</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="#a318ad323e3d4d0fa83725eb95f6f84d3">OpenMPPostLink</a> and <a href="#a5d7ac74714aff72e78b7638152e948d6">RFIs</a>.</p>

</div>
</div>

### setCallingConvention() {#a4085e5e5acca78ad7d76140bbe0f36f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OpenMPOpt.cpp}::OMPInformationCache::setCallingConvention (<a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> Callee, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
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



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ICVs {#ab5577456d10dd62c3604fbbed8fe2081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EnumeratedArray&lt;InternalControlVarInfo, InternalControlVar, InternalControlVar::ICV___last&gt; anonymous{OpenMPOpt.cpp}::OMPInformationCache::ICVs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from ICV kind to the ICV description.</p>

<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### OMPBuilder {#af358e5a643dd21f130e147c7b399bc20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder anonymous{OpenMPOpt.cpp}::OMPInformationCache::OMPBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An OpenMP-IR-Builder instance.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a86f06c6063c3a34171f47246e4c94ce8">collectUses</a> and <a href="#aa4654342457e24974e89aeb382212159">OMPInformationCache</a>.</p>

</div>
</div>

### OpenMPPostLink {#a318ad323e3d4d0fa83725eb95f6f84d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::OMPInformationCache::OpenMPPostLink = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates if we have already linked in the OpenMP device library.</p>

<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#aa4654342457e24974e89aeb382212159">OMPInformationCache</a> and <a href="#afd0b41d4bbaf15bfb701ed8eebd2a5c2">runtimeFnsAvailable</a>.</p>

</div>
</div>

### RFIs {#a5d7ac74714aff72e78b7638152e948d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EnumeratedArray&lt;RuntimeFunctionInfo, RuntimeFunction, RuntimeFunction::OMPRTL___last&gt; anonymous{OpenMPOpt.cpp}::OMPInformationCache::RFIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from runtime function kind to the runtime function description.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a627bfd890830868bb678904545f95d63">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::findPotentialRemovedFreeCalls</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#ab0a8c344bd57a953ec6b9327a443b2b0">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::getValueForCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="#a580882ca6acde97ca9e012fe5a206d08">recollectUses</a>, <a href="#a1c4037cfc6e6773c2c2d7faf7d33a8ee">recollectUsesForFunction</a> and <a href="#afd0b41d4bbaf15bfb701ed8eebd2a5c2">runtimeFnsAvailable</a>.</p>

</div>
</div>

### RTLFunctions {#ae19612665dba846449dd96f24f6fd7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const Function *&gt; anonymous{OpenMPOpt.cpp}::OMPInformationCache::RTLFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of known OpenMP runtime functions..</p>

<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### RuntimeFunctionIDMap {#abda08d1ed27f41e396dc0ede68b92590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Function *, RuntimeFunction&gt; anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionIDMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from function declarations/definitions to their runtime enum type.</p>

<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecallcallsitereturned/#a4ef5420ebe7c75b26c668ce810ddf6fb">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCallCallSiteReturned::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#ab0859b33717bfc3149f2b4051949b5cb">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### declMatchesRTFTypes() {#a0bbf7be621bd7377f3f4a7498010f98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::OMPInformationCache::declMatchesRTFTypes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RTFRetType, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 8 &gt; &amp; RTFArgTypes)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the function declaration <span class="doxyComputerOutput">F</span> matches the runtime function types, that is, return type <span class="doxyComputerOutput">RTFRetType</span>, and argument types <span class="doxyComputerOutput">RTFArgTypes</span>.</p>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
