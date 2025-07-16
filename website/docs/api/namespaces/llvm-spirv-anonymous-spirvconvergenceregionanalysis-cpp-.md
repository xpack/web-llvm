---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/spirv/anonymous-spirvconvergenceregionanalysis-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{SPIRVConvergenceRegionAnalysis.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::SPIRV::anonymous{SPIRVConvergenceRegionAnalysis.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BasicBlockType, typename IntrinsicInstType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b1e4833f4b0eab9d719dc30d549f538">getConvergenceTokenInternal</a> (BasicBlockType *BB) -&gt; std::optional&lt; IntrinsicInstType * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregion">ConvergenceRegion</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2846f57b5b41783866a21eca418ed4b3">findParentRegion</a> (ConvergenceRegion *Start, BasicBlock *Entry)</td>
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

## Functions

### findParentRegion() {#a2846f57b5b41783866a21eca418ed4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConvergenceRegion * llvm::SPIRV::anonymous{SPIRVConvergenceRegionAnalysis.cpp}::findParentRegion (<a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregion">ConvergenceRegion</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp">SPIRVConvergenceRegionAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregion/#a03d34ea2d838e32c2f5b374a650090c7">llvm::SPIRV::ConvergenceRegion::Children</a> and <a href="#a2846f57b5b41783866a21eca418ed4b3">findParentRegion</a>.</p>


<p>Referenced by <a href="#a2846f57b5b41783866a21eca418ed4b3">findParentRegion</a>.</p>

</div>
</div>

### getConvergenceTokenInternal() {#a0b1e4833f4b0eab9d719dc30d549f538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BasicBlockType, typename IntrinsicInstType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; IntrinsicInstType * &gt; llvm::SPIRV::anonymous{SPIRVConvergenceRegionAnalysis.cpp}::getConvergenceTokenInternal (BasicBlockType * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp">SPIRVConvergenceRegionAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a0b1e4833f4b0eab9d719dc30d549f538">getConvergenceTokenInternal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cacdf8ff962c6163eb5fae1f9b2fb5142a">llvm::LLVMContext::OB_convergencectrl</a>.</p>


<p>Referenced by <a href="#a0b1e4833f4b0eab9d719dc30d549f538">getConvergenceTokenInternal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp">SPIRVConvergenceRegionAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
