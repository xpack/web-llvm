---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/rgpassmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RGPassManager` Class Reference

<p>The pass manager to schedule RegionPasses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RGPassManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">llvm/Analysis/RegionPass.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> class - This class is used to implement most global optimizations. <a href="/web-llvm/docs/api/classes/llvm/functionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> provides the common place to manage the analysis data used by pass managers. <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9ba45cb8358d1338d7ebfb3c7e0935">RGPassManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fcc78c1f34a2d1f636b5880db631439">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute all of the passes scheduled for execution. <a href="#a8fcc78c1f34a2d1f636b5880db631439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a719c7b2402f60b585746f856372ace3a">getAnalysisUsage</a> (AnalysisUsage &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager itself does not invalidate any analysis info. <a href="#a719c7b2402f60b585746f856372ace3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eafeb43d404e5f65fba1e739e26ecef">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a0eafeb43d404e5f65fba1e739e26ecef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045021659125e4ab94763bf055c936c8">getAsPMDataManager</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a93e1a50ce3c7144c85ba0108e5811">getAsPass</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b0d682de606b00fcd4c6de1748496af">dumpPassStructure</a> (unsigned Offset) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print passes managed by this manager. <a href="#a3b0d682de606b00fcd4c6de1748496af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d8be8eb594fafcec7d5f06630783e5">getContainedPass</a> (unsigned N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get passes contained by this manager. <a href="#a41d8be8eb594fafcec7d5f06630783e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b72d51eaa87ec1972844869148c5920">getPassManagerType</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abae64ca18bdbe7ae89eddca3d015f6bd">RQ</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46ea87c99b5ad94cf9afa1306fe6860">RI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf3e18b76cd7ebacc60b59dd87893fb1">CurrentRegion</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54cd3d21f2c34100fb25d6ef4bbf881a">ID</a> = 0</td>
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

<p>The pass manager to schedule RegionPasses.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RGPassManager() {#a7b9ba45cb8358d1338d7ebfb3c7e0935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RGPassManager::RGPassManager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a> and <a href="#a54cd3d21f2c34100fb25d6ef4bbf881a">ID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dumpPassStructure() {#a3b0d682de606b00fcd4c6de1748496af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RGPassManager::dumpPassStructure (unsigned Offset)</td>
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

<p>Print passes managed by this manager.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a0ced924c11b3eddbfccd9c186f38a389">llvm::PMDataManager::dumpLastUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a41d8be8eb594fafcec7d5f06630783e5">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a719c7b2402f60b585746f856372ace3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RGPassManager::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; Info)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager itself does not invalidate any analysis info.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/rgpassmanager">RGPassManager</a> needs <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a>.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a>.</p>

</div>
</div>

### getAsPass() {#a96a93e1a50ce3c7144c85ba0108e5811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * llvm::RGPassManager::getAsPass ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>

</div>
</div>

### getAsPMDataManager() {#a045021659125e4ab94763bf055c936c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMDataManager * llvm::RGPassManager::getAsPMDataManager ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a04fbd0afa6857fe697dd28e93bdfec07">llvm::PMDataManager::PMDataManager</a>.</p>

</div>
</div>

### getContainedPass() {#a41d8be8eb594fafcec7d5f06630783e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * llvm::RGPassManager::getContainedPass (unsigned N)</td>
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

<p>Get passes contained by this manager.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a433bcef3e3a89059a3510632b640525d">llvm::PMDataManager::PassVector</a>.</p>


<p>Referenced by <a href="#a3b0d682de606b00fcd4c6de1748496af">dumpPassStructure</a> and <a href="#a8fcc78c1f34a2d1f636b5880db631439">runOnFunction</a>.</p>

</div>
</div>

### getPassManagerType() {#a7b72d51eaa87ec1972844869148c5920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManagerType llvm::RGPassManager::getPassManagerType ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebba4f3dad21748b7d8280494f0389317358">llvm::PMT_RegionPassManager</a>.</p>

</div>
</div>

### getPassName() {#a0eafeb43d404e5f65fba1e739e26ecef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::RGPassManager::getPassName ()</td>
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


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>

</div>
</div>

### runOnFunction() {#a8fcc78c1f34a2d1f636b5880db631439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RGPassManager::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Execute all of the passes scheduled for execution.</p>


<p>run - Execute all of the passes scheduled for execution.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if any of the passes modifies the function.</p></dd>
</dl>


<p>Keep track of whether any of the passes modifies the function, and if so, return true.</p>


<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp/#a1490d79fb9c17eb8f9e88808512910a1">addRegionIntoQueue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aff93635e4ea28861beb90faece603b3d">llvm::PMDataManager::dumpPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#adfe9cc105a283f4d7e4e56c6d4440adb">llvm::PMDataManager::dumpPreservedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a799e97f6f38435a58b8ecf6a85eb7399">llvm::PMDataManager::dumpRequiredSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a3f3116bde1268f9e1cd78d9010e4ff26">llvm::EXECUTION_MSG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="#a41d8be8eb594fafcec7d5f06630783e5">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d0285e03a80731db23ba77d291942d">llvm::getPassTimer</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a813e1d4b6102a11cad9963778f889d4d">llvm::PMDataManager::initializeAnalysisImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a38a662fbda7962b4e36e614ac16062c9">llvm::PMDataManager::isPassDebuggingExecutionsOrMore</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a72e482d46273910cd5a3a02b0f65647f">llvm::MODIFICATION_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a804f43dbed9325f261c320ab5bb1e73d">llvm::ON_REGION_MSG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ad469713fc40b5f0baba648041a68dfa7">llvm::PMDataManager::populateInheritedAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a35ff10683333230676c1d3c4379b58b1">llvm::PMDataManager::recordAvailableAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a09ac67e36db813f2a3e69173f7638037">llvm::PMDataManager::removeDeadPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af740891e192aa63a0fbbfe317301cbdb">llvm::PMDataManager::removeNotPreservedAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aaa1883b3ebb15e2de80d6f08004a8528">llvm::PMDataManager::TPM</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a86a4b032c64ea61c59d12929a76c9833">llvm::PMDataManager::verifyPreservedAnalysis</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentRegion {#adf3e18b76cd7ebacc60b59dd87893fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Region* llvm::RGPassManager::CurrentRegion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>

</div>
</div>

### RI {#ab46ea87c99b5ad94cf9afa1306fe6860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionInfo* llvm::RGPassManager::RI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>

</div>
</div>

### RQ {#abae64ca18bdbe7ae89eddca3d015f6bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;Region*&gt; llvm::RGPassManager::RQ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a54cd3d21f2c34100fb25d6ef4bbf881a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char RGPassManager::ID = 0</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a>.</p>


<p>Referenced by <a href="#a7b9ba45cb8358d1338d7ebfb3c7e0935">RGPassManager</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regionpass-h">RegionPass.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/regionpass-cpp">RegionPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
