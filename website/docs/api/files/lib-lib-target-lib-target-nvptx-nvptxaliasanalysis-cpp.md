---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `NVPTXAliasAnalysis.cpp` File Reference

<p>This is the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> address space based alias analysis pass. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-h">NVPTXAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxbaseinfo-h">MCTargetDesc/NVPTXBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptx-h">NVPTX.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32397f5ba060cd03f11386780d49d23f">INITIALIZE_PASS</a> (NVPTXAAWrapperPass, "nvptx-aa", "NVPTX Address space based Alias Analysis", false, true) INITIALIZE_PASS(NVPTXExternalAAWrapper</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ab6e89a7e272521d7641859805a0ba">getAddressSpace</a> (const Value *V, unsigned MaxLookup)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57">AliasResult::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa108193c2ff5ea46a3ada182dd7867e7">getAliasResult</a> (unsigned AS1, unsigned AS2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8150e3a71552f9e815108aba570643">isConstOrParam</a> (unsigned AS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b2bb68cc2336782f7cf85bec893b2c8">TraverseAddressSpacesLimit</a>("nvptx-traverse-address-aliasing-limit", cl::Hidden, cl::desc("Depth limit for finding address space through traversal"), cl::init(6))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">nvptx <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5380e781ad01ff3a4f3ea524aeebfea">wrapper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">nvptx <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a> NVPTX <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> space based Alias <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c896f9d23fdb4fe5de54927dc12a49">Wrapper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">nvptx <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a74b87337454200d4d33f80c4663dc5e5">aa</a> NVPTX <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> space based Alias <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7ee7c0dea91609c866acd543c4ec56">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"NVPTX-aa"</td>
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

<p>This is the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> address space based alias analysis pass.</p>

<div class="doxySectionDef">

## Functions

### getAddressSpace() {#af6ab6e89a7e272521d7641859805a0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getAddressSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned MaxLookup)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dca6c5cbbdf5d30037891306aa6f4924861">llvm::NVPTXAS::ADDRESS_SPACE_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxaaresult/#a3c6e127da93ba9d67d0f1d42a0e9827b">llvm::NVPTXAAResult::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0ac2ceaa32ba0511bb9e14e6edfbc329">llvm::MachineIRBuilder::buildGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a822fce84743a12eba6f9c83c9c719140">llvm::DataLayout::getIndexTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxaaresult/#a89e48d7cde834ecb75ae97735d23462e">llvm::NVPTXAAResult::getModRefInfoMask</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a83f29b41d37a5b66cd48c3b4ec302742">llvm::DataLayout::getPointerTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ac9fd43d241b943a864b302cdf17ae487">llvm::SITargetLowering::lowerPREFETCH</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaddressspaceimpl/#a53cdd0197a337c06817844761012a6e0">anonymous{AttributorAttributes.cpp}::AAAddressSpaceImpl::manifest</a>.</p>

</div>
</div>

### getAliasResult() {#aa108193c2ff5ea46a3ada182dd7867e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasResult::Kind getAliasResult (unsigned AS1, unsigned AS2)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/nvptxas/#ad7d00b71af84502be65ae2de3f8d91dca6c5cbbdf5d30037891306aa6f4924861">llvm::NVPTXAS::ADDRESS_SPACE_GENERIC</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a0916b614598c673c1e6a59c7312a1409">llvm::AliasResult::MayAlias</a> and <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a863ee317b92588eb2d6878af9fc98922">llvm::AliasResult::NoAlias</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxaaresult/#a3c6e127da93ba9d67d0f1d42a0e9827b">llvm::NVPTXAAResult::alias</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a32397f5ba060cd03f11386780d49d23f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/nvptxaawrapperpass">NVPTXAAWrapperPass</a>, "nvptx-aa", "NVPTX <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a> space based Alias Analysis", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>

</div>
</div>

### isConstOrParam() {#ada8150e3a71552f9e815108aba570643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstOrParam (unsigned AS)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxaaresult/#a89e48d7cde834ecb75ae97735d23462e">llvm::NVPTXAAResult::getModRefInfoMask</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#a8c7ee7c0dea91609c866acd543c4ec56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nvptx aa NVPTX Address space based Alias Analysis false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>

</div>
</div>

### TraverseAddressSpacesLimit {#a0b2bb68cc2336782f7cf85bec893b2c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TraverseAddressSpacesLimit("nvptx-traverse-address-aliasing-limit", cl::Hidden, cl::desc("Depth limit for finding address space through traversal"), cl::init(6))</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxaaresult/#a3c6e127da93ba9d67d0f1d42a0e9827b">llvm::NVPTXAAResult::alias</a> and <a href="/web-llvm/docs/api/classes/llvm/nvptxaaresult/#a89e48d7cde834ecb75ae97735d23462e">llvm::NVPTXAAResult::getModRefInfoMask</a>.</p>

</div>
</div>

### wrapper {#ab5380e781ad01ff3a4f3ea524aeebfea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nvptx aa wrapper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>

</div>
</div>

### Wrapper {#a84c896f9d23fdb4fe5de54927dc12a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nvptx aa NVPTX Address space based Alias Analysis Wrapper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"NVPTX-aa"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxaliasanalysis-cpp">NVPTXAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
