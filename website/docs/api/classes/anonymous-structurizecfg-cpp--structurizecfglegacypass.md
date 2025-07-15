---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StructurizeCFGLegacyPass` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionpass">RegionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pass that runs on each <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> in a function. <a href="/web-llvm/docs/api/classes/llvm/regionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e9447b0c70f1a7ac8289a0e4e75ce7">StructurizeCFGLegacyPass</a> (bool SkipUniformRegions_=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecbd421c713f3803e5d34d14db2b4409">runOnRegion</a> (Region *R, RGPassManager &amp;RGM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the pass on a specific Region. <a href="#aecbd421c713f3803e5d34d14db2b4409">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad829c0856e0d08f2258ee38ad1e049c5">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#ad829c0856e0d08f2258ee38ad1e049c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe30a2c7f18e2cb17df9295407d6c22c">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#abe30a2c7f18e2cb17df9295407d6c22c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73778c8e9dc6607eaa7f53d56c3ba62">SkipUniformRegions</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65cbf65210c5e8e3fd2eae8080223800">ID</a> = 0</td>
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


<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StructurizeCFGLegacyPass() {#a06e9447b0c70f1a7ac8289a0e4e75ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::StructurizeCFGLegacyPass (bool SkipUniformRegions_=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#ade844ffde89c7113e3fcbdf2c1300720">anonymous{StructurizeCFG.cpp}::ForceSkipUniformRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a65cbf65210c5e8e3fd2eae8080223800">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a585c08a8817ef3bb09680baec46542f6">llvm::initializeStructurizeCFGLegacyPassPass</a> and <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a64960c9ccfcfac1e3562564564c30c51">llvm::RegionPass::RegionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb815c8f9920e07c3ab6bfc0e144658">llvm::createStructurizeCFGPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#abe30a2c7f18e2cb17df9295407d6c22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/pass/#a6590d0486104165ca40c7df0707f7b9e">llvm::Pass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#ad829c0856e0d08f2258ee38ad1e049c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### runOnRegion() {#aecbd421c713f3803e5d34d14db2b4409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::runOnRegion (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * R, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager">RGPassManager</a> &amp; RGM)</td>
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

<p>Run the pass on a specific Region.</p>


<p>Accessing regions not contained in the current region is not allowed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">R</td>
<td class="doxyParamItemDescription"><p>The region this pass is run on.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RGM</td>
<td class="doxyParamItemDescription"><p>The RegionPassManager that manages this Pass.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the pass modifies this Region.</p></dd>
</dl>


<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfg/#a88fa969de8279bbac9d3718775723b50">anonymous{StructurizeCFG.cpp}::StructurizeCFG::init</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfg/#aa2ebb8b48e7c632966b1cda5d79a257a">anonymous{StructurizeCFG.cpp}::StructurizeCFG::makeUniformRegion</a> and <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfg/#aa5aa23c5169a9bc1cf14f6ed750717e8">anonymous{StructurizeCFG.cpp}::StructurizeCFG::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SkipUniformRegions {#ae73778c8e9dc6607eaa7f53d56c3ba62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::SkipUniformRegions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a65cbf65210c5e8e3fd2eae8080223800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char StructurizeCFGLegacyPass::ID = 0</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>Referenced by <a href="#a06e9447b0c70f1a7ac8289a0e4e75ce7">StructurizeCFGLegacyPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
