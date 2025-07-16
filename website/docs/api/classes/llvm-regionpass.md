---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regionpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegionPass` Class Reference

<p>A pass that runs on each <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> in a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegionPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">llvm/Analysis/RegionPass.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> interface - Implemented by all 'passes'. <a href="/web-llvm/docs/api/classes/llvm/pass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-regionpass-cpp-/printregionpass">PrintRegionPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass">StructurizeCFGLegacyPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64960c9ccfcfac1e3562564564c30c51">RegionPass</a> (char &amp;pid)</td>
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

## To be implemented by every RegionPass Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf6dc4e02bc6a1f544af50b8921ec2c">runOnRegion</a> (Region *R, RGPassManager &amp;RGM)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the pass on a specific <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>. <a href="#aebf6dc4e02bc6a1f544af50b8921ec2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9791a6c4ebc5fc6ab6cd26d739ce965">createPrinterPass</a> (raw_ostream &amp;O, const std::string &amp;Banner) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pass to print the LLVM IR in the region. <a href="#af9791a6c4ebc5fc6ab6cd26d739ce965">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d163acd3f3ae6afb96fc3d144dc1285">doInitialization</a> (Region *R, RGPassManager &amp;RGM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a851d1da395a59ef6201cd098b71f431e">doFinalization</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab007d6c51634eb65e4f4f9dab4eb6a8c">doInitialization</a> (Module &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run. <a href="#ab007d6c51634eb65e4f4f9dab4eb6a8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7811985250c75d7e2a244292d615fff">doFinalization</a> (Module &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doFinalization - Virtual method overriden by subclasses to do any necessary clean up after all passes have run. <a href="#ac7811985250c75d7e2a244292d615fff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## PassManager API Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2713ee0f2a6f78c9084cd7fc55afb303">preparePassManager</a> (PMStack &amp;PMS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if available pass managers are suitable for this pass or not. <a href="#a2713ee0f2a6f78c9084cd7fc55afb303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e838f42384fc223a2768b68ecd12d7e">assignPassManager</a> (PMStack &amp;PMS, PassManagerType PMT=PMT_RegionPassManager) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign pass manager to manage this pass. <a href="#a2e838f42384fc223a2768b68ecd12d7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa6ea683a4f2873dd6b2fca918f3ed6c">getPotentialPassManagerType</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return what kind of <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager can manage this pass. <a href="#aaa6ea683a4f2873dd6b2fca918f3ed6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a3749e0f47aa3b73df3ac0e66a78771">skipRegion</a> (Region &amp;R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional passes call this function to check whether the pass should be skipped. <a href="#a2a3749e0f47aa3b73df3ac0e66a78771">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A pass that runs on each <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> in a function.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/regionpass">RegionPass</a> is managed by <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager">RGPassManager</a>.</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegionPass() {#a64960c9ccfcfac1e3562564564c30c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegionPass::RegionPass (char &amp; pid)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0da955cbb4215ccd3e153c81e415b9d5a36f81b217fc99f02606d6c1e44e04815">llvm::PT_Region</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regionpass-cpp-/printregionpass/#a8219fddb814e0a807ff09532a10a9e64">anonymous{RegionPass.cpp}::PrintRegionPass::PrintRegionPass</a> and <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#a06e9447b0c70f1a7ac8289a0e4e75ce7">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::StructurizeCFGLegacyPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## To be implemented by every RegionPass

### createPrinterPass {#af9791a6c4ebc5fc6ab6cd26d739ce965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * RegionPass::createPrinterPass (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Banner)</td>
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

<p>Get a pass to print the LLVM IR in the region.</p>


<p>Get the printer pass.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The output stream to print the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Banner</td>
<td class="doxyParamItemDescription"><p>The banner to separate different printed passes.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The pass to print the LLVM IR in the region.</p></dd>
</dl>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>.</p>

</div>
</div>

### doFinalization {#a851d1da395a59ef6201cd098b71f431e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RegionPass::doFinalization ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>

</div>
</div>

### doFinalization {#ac7811985250c75d7e2a244292d615fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Pass::doFinalization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>doFinalization - Virtual method overriden by subclasses to do any necessary clean up after all passes have run.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### doInitialization {#a9d163acd3f3ae6afb96fc3d144dc1285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RegionPass::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * R, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager">RGPassManager</a> &amp; RGM)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>

</div>
</div>

### doInitialization {#ab007d6c51634eb65e4f4f9dab4eb6a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Pass::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>doInitialization - Virtual method overridden by subclasses to do any necessary initialization before any pass is run.</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### runOnRegion {#aebf6dc4e02bc6a1f544af50b8921ec2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::RegionPass::runOnRegion (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * R, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager">RGPassManager</a> &amp; RGM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run the pass on a specific <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p>


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
<td class="doxyParamItemDescription"><p>The RegionPassManager that manages this <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the pass modifies this <a href="/web-llvm/docs/api/classes/llvm/region">Region</a>.</p></dd>
</dl>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#ac7811985250c75d7e2a244292d615fff">llvm::Pass::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ab007d6c51634eb65e4f4f9dab4eb6a8c">llvm::Pass::doInitialization</a> and <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## PassManager API

### assignPassManager {#a2e838f42384fc223a2768b68ecd12d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionPass::assignPassManager (<a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> &amp; PMS, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a> PMT=<a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebba4f3dad21748b7d8280494f0389317358">PMT_RegionPassManager</a>)</td>
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

<p>Assign pass manager to manage this pass.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab7c7120f48a91e5972592b16ee7fd81b">llvm::PMDataManager::add</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a022d0f8afbecd48458168e3a419d2048">llvm::PMTopLevelManager::addIndirectPassManager</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a8d1f11a06b6d13adb9c09c7487ec5d5a">llvm::PMStack::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa877f351376c696b385fdeba9b93a5f1">llvm::PMDataManager::getPassManagerType</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a49d2392d2b8e3a2792ea40a12a4be5a4">llvm::PMDataManager::getTopLevelManager</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebba4f3dad21748b7d8280494f0389317358">llvm::PMT_RegionPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a4953e532d6f86ceb1f38ee2503be46a0">llvm::PMStack::pop</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ad469713fc40b5f0baba648041a68dfa7">llvm::PMDataManager::populateInheritedAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a9579e452cf1995463c7e29dfeae5cc2a">llvm::PMStack::push</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a> and <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a5c88be47ebb28074149e618ba3dedaa2">llvm::PMStack::top</a>.</p>

</div>
</div>

### getPotentialPassManagerType {#aaa6ea683a4f2873dd6b2fca918f3ed6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManagerType llvm::RegionPass::getPotentialPassManagerType ()</td>
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

<p>Return what kind of <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager can manage this pass.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebba4f3dad21748b7d8280494f0389317358">llvm::PMT_RegionPassManager</a>.</p>

</div>
</div>

### preparePassManager {#a2713ee0f2a6f78c9084cd7fc55afb303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegionPass::preparePassManager (<a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> &amp;)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if available pass managers are suitable for this pass or not.</p>

<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a8d1f11a06b6d13adb9c09c7487ec5d5a">llvm::PMStack::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa877f351376c696b385fdeba9b93a5f1">llvm::PMDataManager::getPassManagerType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebba4f3dad21748b7d8280494f0389317358">llvm::PMT_RegionPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a4953e532d6f86ceb1f38ee2503be46a0">llvm::PMStack::pop</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa2fd2b9e450d0a3dc5255cc52151b7ff">llvm::PMDataManager::preserveHigherLevelAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a5c88be47ebb28074149e618ba3dedaa2">llvm::PMStack::top</a>.</p>

</div>
</div>

### skipRegion {#a2a3749e0f47aa3b73df3ac0e66a78771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegionPass::skipRegion (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> &amp; R)</td>
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

<p>Optional passes call this function to check whether the pass should be skipped.</p>


<p>This is the case when optimization bisect is over the limit.</p>


<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp/#a2bd4f0ba04228d5fb919734abb9ca1af">getDescription</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ad729b39eacf070a9bca84533b3c743bf">llvm::Pass::getPassName</a>, <a href="/web-llvm/docs/api/classes/llvm/optpassgate/#a0324a149fd3db35e2f789c91a4d30da4">llvm::OptPassGate::isEnabled</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/optpassgate/#a59de8deea51271200bbfc1e5be45ee3c">llvm::OptPassGate::shouldRunPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
