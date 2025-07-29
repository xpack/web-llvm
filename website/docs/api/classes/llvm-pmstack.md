---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pmstack
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PMStack` Class

<p><a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> - This class implements a stack data structure of <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> pointers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PMStack { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">llvm/IR/LegacyPassManagers.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> * &gt;::const_reverse_iterator <a href="#a38ad4fdcb069771fa70b351b53288d27">iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a38ad4fdcb069771fa70b351b53288d27">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12dc8c89fe6957d38096afb85cb2c66">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a38ad4fdcb069771fa70b351b53288d27">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d319066143df160d427a991c7d8f5d">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4953e532d6f86ceb1f38ee2503be46a0">pop</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c88be47ebb28074149e618ba3dedaa2">top</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9579e452cf1995463c7e29dfeae5cc2a">push</a> (PMDataManager *PM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1f11a06b6d13adb9c09c7487ec5d5a">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2231cd95fe50f516610c506f57cbc6">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520a9b5e37575812f9307843edf4c9aa">S</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> - This class implements a stack data structure of <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> pointers.</p>


<p>Top level pass managers (see PassManager.cpp) maintain active <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Managers using <a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a>. Each <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> implements assignPassManager() to connect itself with appropriate manager. assignPassManager() walks <a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> to find suitable manager.</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a38ad4fdcb069771fa70b351b53288d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;PMDataManager*&gt;::const_reverse_iterator llvm::PMStack::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#af12dc8c89fe6957d38096afb85cb2c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::PMStack::begin ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### dump() {#a5d2231cd95fe50f516610c506f57cbc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void PMStack::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1691 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### empty() {#a8d1f11a06b6d13adb9c09c7487ec5d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PMStack::empty ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a0d8f33dd4b6aa73a06a2f7dd50cb3d68">llvm::LoopPass::preparePassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2713ee0f2a6f78c9084cd7fc55afb303">llvm::RegionPass::preparePassManager</a> and <a href="#a9579e452cf1995463c7e29dfeae5cc2a">push</a>.</p>

</div>
</div>

### end() {#a56d319066143df160d427a991c7d8f5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::PMStack::end ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

### pop() {#a4953e532d6f86ceb1f38ee2503be46a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMStack::pop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1658 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a9a49f833e36d81021facdf5f4dbd84de">llvm::PMDataManager::initializeAnalysisInfo</a> and <a href="#a5c88be47ebb28074149e618ba3dedaa2">top</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a748922f143f2da9a13b0b15ff6a3dd22">llvm::FunctionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/modulepass/#ac1b24f1323a72168f8b9c8610da56949">llvm::ModulePass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a0d8f33dd4b6aa73a06a2f7dd50cb3d68">llvm::LoopPass::preparePassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2713ee0f2a6f78c9084cd7fc55afb303">llvm::RegionPass::preparePassManager</a>.</p>

</div>
</div>

### push() {#a9579e452cf1995463c7e29dfeae5cc2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PMStack::push (<a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> * PM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>, definition at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a022d0f8afbecd48458168e3a419d2048">llvm::PMTopLevelManager::addIndirectPassManager</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8d1f11a06b6d13adb9c09c7487ec5d5a">empty</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a414502197da1d779b5bed1aa04e65804">llvm::PMDataManager::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa877f351376c696b385fdeba9b93a5f1">llvm::PMDataManager::getPassManagerType</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a49d2392d2b8e3a2792ea40a12a4be5a4">llvm::PMDataManager::getTopLevelManager</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbaf92a84a9aa3cca1378d1a12fc3664396">llvm::PMT_FunctionPassManager</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbad553155122a5bf541ead3e0aa5b13287">llvm::PMT_ModulePassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a1d280b5b00775044d94b527cac5ef7bb">llvm::PMDataManager::setDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a61adb3228a4dd2685aeb402e7a4c35d3">llvm::PMDataManager::setTopLevelManager</a> and <a href="#a5c88be47ebb28074149e618ba3dedaa2">top</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a748922f143f2da9a13b0b15ff6a3dd22">llvm::FunctionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a> and <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a>.</p>

</div>
</div>

### top() {#a5c88be47ebb28074149e618ba3dedaa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMDataManager * llvm::PMStack::top ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callgraphsccpass/#af6897bd5a86b78fc12f93cdfb04c9e6a">llvm::CallGraphSCCPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a748922f143f2da9a13b0b15ff6a3dd22">llvm::FunctionPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/modulepass/#ac1b24f1323a72168f8b9c8610da56949">llvm::ModulePass::assignPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2e838f42384fc223a2768b68ecd12d7e">llvm::RegionPass::assignPassManager</a>, <a href="#a4953e532d6f86ceb1f38ee2503be46a0">pop</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a0d8f33dd4b6aa73a06a2f7dd50cb3d68">llvm::LoopPass::preparePassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/regionpass/#a2713ee0f2a6f78c9084cd7fc55afb303">llvm::RegionPass::preparePassManager</a> and <a href="#a9579e452cf1995463c7e29dfeae5cc2a">push</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### S {#a520a9b5e37575812f9307843edf4c9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PMDataManager *&gt; llvm::PMStack::S</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanagers-h">LegacyPassManagers.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
