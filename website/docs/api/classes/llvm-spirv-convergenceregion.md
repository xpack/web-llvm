---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/spirv/convergenceregion
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConvergenceRegion` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SPIRV::ConvergenceRegion { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">Target/SPIRV/Analysis/SPIRVConvergenceRegionAnalysis.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed1395df753af15056035fe68c4acb0">ConvergenceRegion</a> (DominatorTree &amp;DT, LoopInfo &amp;LI, Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac06e60ad5f60770d22626f7fbf863fe4">ConvergenceRegion</a> (DominatorTree &amp;DT, LoopInfo &amp;LI, std::optional&lt; IntrinsicInst * &gt; ConvergenceToken, BasicBlock *Entry, SmallPtrSet&lt; BasicBlock *, 8 &gt; &amp;&amp;Blocks, SmallPtrSet&lt; BasicBlock *, 2 &gt; &amp;&amp;Exits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3bf5af33af2e926d63f735559cff913">ConvergenceRegion</a> (ConvergenceRegion &amp;&amp;CR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d1e3ce3b0c0c6633ef8f49f90d9ea4">ConvergenceRegion</a> (const ConvergenceRegion &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a622eb583c2292b211678d544bc64b27b">contains</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7594f834562fb173b770d52be8664b31">releaseMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6eb6acc7b5f83f84cc7c05ca69edbb">dump</a> (const unsigned IndentSize=0) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregion">ConvergenceRegion</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb69d9d2c4abebdcfe778fb8d337559">Parent</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregion">ConvergenceRegion</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03d34ea2d838e32c2f5b374a650090c7">Children</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7521fb98b8985d4f9746a6c36cdeaeb0">ConvergenceToken</a> = std::nullopt</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c675ed896d4263b41685bc71b2fa7f">Entry</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e6b5913e784f02d6394854bfa298fff">Exits</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa22070b4f97f878349b3537b3ca915b">Blocks</a> = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a7dca7efc2a09e0f731d22ea32ce4d">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac07fef9cda53351fe5dd08a55449aad8">LI</a></td>
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


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConvergenceRegion() {#aeed1395df753af15056035fe68c4acb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SPIRV::ConvergenceRegion::ConvergenceRegion (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp">SPIRVConvergenceRegionAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#afa22070b4f97f878349b3537b3ca915b">Blocks</a>, <a href="#a7521fb98b8985d4f9746a6c36cdeaeb0">ConvergenceToken</a>, <a href="#ac3c675ed896d4263b41685bc71b2fa7f">Entry</a>, <a href="#a6e6b5913e784f02d6394854bfa298fff">Exits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#ae640f704e888becca0cafd83b07021ae">llvm::SPIRV::getConvergenceToken</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#aaeb69d9d2c4abebdcfe778fb8d337559">Parent</a>.</p>


<p>Referenced by <a href="#a69d1e3ce3b0c0c6633ef8f49f90d9ea4">ConvergenceRegion</a> and <a href="#ab3bf5af33af2e926d63f735559cff913">ConvergenceRegion</a>.</p>

</div>
</div>

### ConvergenceRegion() {#ac06e60ad5f60770d22626f7fbf863fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SPIRV::ConvergenceRegion::ConvergenceRegion (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * &gt; ConvergenceToken, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Entry, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 8 &gt; &amp;&amp; Blocks, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 2 &gt; &amp;&amp; Exits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp">SPIRVConvergenceRegionAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afa22070b4f97f878349b3537b3ca915b">Blocks</a>, <a href="#a7521fb98b8985d4f9746a6c36cdeaeb0">ConvergenceToken</a>, <a href="#ac3c675ed896d4263b41685bc71b2fa7f">Entry</a>, <a href="#a6e6b5913e784f02d6394854bfa298fff">Exits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### ConvergenceRegion() {#ab3bf5af33af2e926d63f735559cff913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SPIRV::ConvergenceRegion::ConvergenceRegion (<a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregion">ConvergenceRegion</a> &amp;&amp; CR)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>References <a href="#afa22070b4f97f878349b3537b3ca915b">Blocks</a>, <a href="#a03d34ea2d838e32c2f5b374a650090c7">Children</a>, <a href="#aeed1395df753af15056035fe68c4acb0">ConvergenceRegion</a>, <a href="#a7521fb98b8985d4f9746a6c36cdeaeb0">ConvergenceToken</a>, <a href="#ac3c675ed896d4263b41685bc71b2fa7f">Entry</a>, <a href="#a6e6b5913e784f02d6394854bfa298fff">Exits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#aaeb69d9d2c4abebdcfe778fb8d337559">Parent</a>.</p>

</div>
</div>

### ConvergenceRegion() {#a69d1e3ce3b0c0c6633ef8f49f90d9ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SPIRV::ConvergenceRegion::ConvergenceRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregion">ConvergenceRegion</a> &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>Reference <a href="#aeed1395df753af15056035fe68c4acb0">ConvergenceRegion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### contains() {#a622eb583c2292b211678d544bc64b27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SPIRV::ConvergenceRegion::contains (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>Reference <a href="#afa22070b4f97f878349b3537b3ca915b">Blocks</a>.</p>

</div>
</div>

### dump() {#acb6eb6acc7b5f83f84cc7c05ca69edbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRV::ConvergenceRegion::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned IndentSize=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp">SPIRVConvergenceRegionAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#afa22070b4f97f878349b3537b3ca915b">Blocks</a>, <a href="#a03d34ea2d838e32c2f5b374a650090c7">Children</a>, <a href="#a7521fb98b8985d4f9746a6c36cdeaeb0">ConvergenceToken</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac3c675ed896d4263b41685bc71b2fa7f">Entry</a>, <a href="#a6e6b5913e784f02d6394854bfa298fff">Exits</a> and <a href="#aaeb69d9d2c4abebdcfe778fb8d337559">Parent</a>.</p>

</div>
</div>

### releaseMemory() {#a7594f834562fb173b770d52be8664b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRV::ConvergenceRegion::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp">SPIRVConvergenceRegionAnalysis.cpp</a>.</p>


<p>References <a href="#a03d34ea2d838e32c2f5b374a650090c7">Children</a> and <a href="#aaeb69d9d2c4abebdcfe778fb8d337559">Parent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Blocks {#afa22070b4f97f878349b3537b3ca915b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;BasicBlock *, 8&gt; llvm::SPIRV::ConvergenceRegion::Blocks = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>Referenced by <a href="#a622eb583c2292b211678d544bc64b27b">contains</a>, <a href="#ab3bf5af33af2e926d63f735559cff913">ConvergenceRegion</a>, <a href="#aeed1395df753af15056035fe68c4acb0">ConvergenceRegion</a>, <a href="#ac06e60ad5f60770d22626f7fbf863fe4">ConvergenceRegion</a>, <a href="#acb6eb6acc7b5f83f84cc7c05ca69edbb">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-spirvstructurizer-cpp-/#ad68d3778af08f64cd91522da2bb7fe86">llvm::anonymous{SPIRVStructurizer.cpp}::getExitFor</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#ab6f626d7c6ac0566eb109ca95019549f">llvm::SPIRVMergeRegionExitTargets::runOnConvergenceRegionNoRecurse</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#acfe976c548c22cd8ced77067f5413881">llvm::SPIRVMergeRegionExitTargets::validateRegionExits</a>.</p>

</div>
</div>

### Children {#a03d34ea2d838e32c2f5b374a650090c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ConvergenceRegion *&gt; llvm::SPIRV::ConvergenceRegion::Children = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>Referenced by <a href="#ab3bf5af33af2e926d63f735559cff913">ConvergenceRegion</a>, <a href="#acb6eb6acc7b5f83f84cc7c05ca69edbb">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/anonymous-spirvconvergenceregionanalysis-cpp-/#a2846f57b5b41783866a21eca418ed4b3">llvm::SPIRV::anonymous{SPIRVConvergenceRegionAnalysis.cpp}::findParentRegion</a>, <a href="#a7594f834562fb173b770d52be8664b31">releaseMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#a3d5989dfd2ec8d890a429b55c3051009">llvm::SPIRVMergeRegionExitTargets::runOnConvergenceRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#acfe976c548c22cd8ced77067f5413881">llvm::SPIRVMergeRegionExitTargets::validateRegionExits</a>.</p>

</div>
</div>

### ConvergenceToken {#a7521fb98b8985d4f9746a6c36cdeaeb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;IntrinsicInst *&gt; llvm::SPIRV::ConvergenceRegion::ConvergenceToken = std::nullopt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>Referenced by <a href="#ab3bf5af33af2e926d63f735559cff913">ConvergenceRegion</a>, <a href="#aeed1395df753af15056035fe68c4acb0">ConvergenceRegion</a>, <a href="#ac06e60ad5f60770d22626f7fbf863fe4">ConvergenceRegion</a> and <a href="#acb6eb6acc7b5f83f84cc7c05ca69edbb">dump</a>.</p>

</div>
</div>

### Entry {#ac3c675ed896d4263b41685bc71b2fa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::SPIRV::ConvergenceRegion::Entry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>Referenced by <a href="#ab3bf5af33af2e926d63f735559cff913">ConvergenceRegion</a>, <a href="#aeed1395df753af15056035fe68c4acb0">ConvergenceRegion</a>, <a href="#ac06e60ad5f60770d22626f7fbf863fe4">ConvergenceRegion</a>, <a href="#acb6eb6acc7b5f83f84cc7c05ca69edbb">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#ab6f626d7c6ac0566eb109ca95019549f">llvm::SPIRVMergeRegionExitTargets::runOnConvergenceRegionNoRecurse</a>.</p>

</div>
</div>

### Exits {#a6e6b5913e784f02d6394854bfa298fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;BasicBlock *, 2&gt; llvm::SPIRV::ConvergenceRegion::Exits = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>Referenced by <a href="#ab3bf5af33af2e926d63f735559cff913">ConvergenceRegion</a>, <a href="#aeed1395df753af15056035fe68c4acb0">ConvergenceRegion</a>, <a href="#ac06e60ad5f60770d22626f7fbf863fe4">ConvergenceRegion</a>, <a href="#acb6eb6acc7b5f83f84cc7c05ca69edbb">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-spirvstructurizer-cpp-/#ad68d3778af08f64cd91522da2bb7fe86">llvm::anonymous{SPIRVStructurizer.cpp}::getExitFor</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#ab6f626d7c6ac0566eb109ca95019549f">llvm::SPIRVMergeRegionExitTargets::runOnConvergenceRegionNoRecurse</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#acfe976c548c22cd8ced77067f5413881">llvm::SPIRVMergeRegionExitTargets::validateRegionExits</a>.</p>

</div>
</div>

### Parent {#aaeb69d9d2c4abebdcfe778fb8d337559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConvergenceRegion* llvm::SPIRV::ConvergenceRegion::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>


<p>Referenced by <a href="#ab3bf5af33af2e926d63f735559cff913">ConvergenceRegion</a>, <a href="#aeed1395df753af15056035fe68c4acb0">ConvergenceRegion</a>, <a href="#acb6eb6acc7b5f83f84cc7c05ca69edbb">dump</a>, <a href="#a7594f834562fb173b770d52be8664b31">releaseMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#ab6f626d7c6ac0566eb109ca95019549f">llvm::SPIRVMergeRegionExitTargets::runOnConvergenceRegionNoRecurse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DT {#a18a7dca7efc2a09e0f731d22ea32ce4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; llvm::SPIRV::ConvergenceRegion::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>

</div>
</div>

### LI {#ac07fef9cda53351fe5dd08a55449aad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo&amp; llvm::SPIRV::ConvergenceRegion::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-cpp">SPIRVConvergenceRegionAnalysis.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/analysis/spirvconvergenceregionanalysis-h">SPIRVConvergenceRegionAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
