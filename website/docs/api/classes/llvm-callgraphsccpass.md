---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/callgraphsccpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CallGraphSCCPass` Class



## Declaration

<div class="doxyDeclaration">
class llvm::CallGraphSCCPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">llvm/Analysis/CallGraphSCCPass.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuannotatekernelfeatures-cpp-/amdgpuannotatekernelfeatures">AMDGPUAnnotateKernelFeatures</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuperfhintanalysis-cpp-/amdgpuperfhintanalysislegacy">AMDGPUPerfHintAnalysisLegacy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/printcallgraphpass">PrintCallGraphPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/printcallgraphpass">PrintCallGraphPass</a> - Print a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> corresponding to a call graph. <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/printcallgraphpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dummycgsccpass">DummyCGSCCPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass is required by interprocedural register allocation. <a href="/web-llvm/docs/api/classes/llvm/dummycgsccpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a480100967dadb2b532fc863b7a4a80a1">CallGraphSCCPass</a> (char &amp;pid)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5377370c7153008ccd1f5c04536051e2">createPrinterPass</a> (raw_ostream &amp;OS, const std::string &amp;Banner) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createPrinterPass - Get a pass that prints the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> corresponding to a <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a>. <a href="#a5377370c7153008ccd1f5c04536051e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad789278ad915ddf3e6d75eb29066f0b3">doInitialization</a> (CallGraph &amp;CG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialization - This method is called before the SCC's of the program has been processed, allowing the pass to do initialization as necessary. <a href="#ad789278ad915ddf3e6d75eb29066f0b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ab09f122afda68d4c0d86e8e5877465">runOnSCC</a> (CallGraphSCC &amp;SCC)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnSCC - This method should be implemented by the subclass to perform whatever action is necessary for the specified SCC. <a href="#a5ab09f122afda68d4c0d86e8e5877465">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16cd88544ab2f8740462d61471f92e5b">doFinalization</a> (CallGraph &amp;CG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doFinalization - This method is called after the SCC's of the program has been processed, allowing the pass to do final cleanup as necessary. <a href="#a16cd88544ab2f8740462d61471f92e5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6897bd5a86b78fc12f93cdfb04c9e6a">assignPassManager</a> (PMStack &amp;PMS, PassManagerType PMT) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign pass manager to manager this pass. <a href="#af6897bd5a86b78fc12f93cdfb04c9e6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f75da9a2ae556a5cdceaee11f4afaf2">getPotentialPassManagerType</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return what kind of <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager can manage this pass. <a href="#a3f75da9a2ae556a5cdceaee11f4afaf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc67c5a27b53bc940d292c0aeb6aba3">getAnalysisUsage</a> (AnalysisUsage &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - For this class, we declare that we require and preserve the call graph. <a href="#a6cc67c5a27b53bc940d292c0aeb6aba3">More...</a></p>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a978ee5e9b5b33e10cea60aea38f80788">skipSCC</a> (CallGraphSCC &amp;SCC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional passes call this function to check whether the pass should be skipped. <a href="#a978ee5e9b5b33e10cea60aea38f80788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallGraphSCCPass() {#a480100967dadb2b532fc863b7a4a80a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallGraphSCCPass::CallGraphSCCPass (char &amp; pid)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0da955cbb4215ccd3e153c81e415b9d5a4f21fd6b3164fbf13c7c1940fb00d2e6">llvm::PT_CallGraphSCC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuannotatekernelfeatures-cpp-/amdgpuannotatekernelfeatures/#a4408ddd5d3ad5a24728e0d09ff2de85c">anonymous{AMDGPUAnnotateKernelFeatures.cpp}::AMDGPUAnnotateKernelFeatures::AMDGPUAnnotateKernelFeatures</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuperfhintanalysis-cpp-/amdgpuperfhintanalysislegacy/#adfcc73531c0791acf32262f019a10e07">anonymous{AMDGPUPerfHintAnalysis.cpp}::AMDGPUPerfHintAnalysisLegacy::AMDGPUPerfHintAnalysisLegacy</a>, <a href="/web-llvm/docs/api/classes/llvm/dummycgsccpass/#a8eca94a66ab1e41a8f3d8dcf8e9f65cd">llvm::DummyCGSCCPass::DummyCGSCCPass</a> and <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/printcallgraphpass/#a37734b288fcf9e84b807065947aa7e18">anonymous{CallGraphSCCPass.cpp}::PrintCallGraphPass::PrintCallGraphPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignPassManager() {#af6897bd5a86b78fc12f93cdfb04c9e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraphSCCPass::assignPassManager (<a href="/web-llvm/docs/api/classes/llvm/pmstack">PMStack</a> &amp; PMS, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a> PMT)</td>
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

<p>Assign pass manager to manager this pass.</p>


<p>Assign pass manager to manage this pass.</p>


<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>, definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab7c7120f48a91e5972592b16ee7fd81b">llvm::PMDataManager::add</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a022d0f8afbecd48458168e3a419d2048">llvm::PMTopLevelManager::addIndirectPassManager</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a8d1f11a06b6d13adb9c09c7487ec5d5a">llvm::PMStack::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa877f351376c696b385fdeba9b93a5f1">llvm::PMDataManager::getPassManagerType</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a49d2392d2b8e3a2792ea40a12a4be5a4">llvm::PMDataManager::getTopLevelManager</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbacfbf7d6825e58faf3673dc5e5a7a2465">llvm::PMT_CallGraphPassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a4953e532d6f86ceb1f38ee2503be46a0">llvm::PMStack::pop</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a9579e452cf1995463c7e29dfeae5cc2a">llvm::PMStack::push</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a> and <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a5c88be47ebb28074149e618ba3dedaa2">llvm::PMStack::top</a>.</p>

</div>
</div>

### createPrinterPass() {#a5377370c7153008ccd1f5c04536051e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * CallGraphSCCPass::createPrinterPass (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Banner)</td>
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

<p>createPrinterPass - Get a pass that prints the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> corresponding to a <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a>.</p>

<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>, definition at line 723 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>.</p>

</div>
</div>

### doFinalization() {#a16cd88544ab2f8740462d61471f92e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::CallGraphSCCPass::doFinalization (<a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp; CG)</td>
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

<p>doFinalization - This method is called after the SCC's of the program has been processed, allowing the pass to do final cleanup as necessary.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>.</p>

</div>
</div>

### doFinalization() {#ac7811985250c75d7e2a244292d615fff}

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

<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### doInitialization() {#ad789278ad915ddf3e6d75eb29066f0b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::CallGraphSCCPass::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp; CG)</td>
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

<p>doInitialization - This method is called before the SCC's of the program has been processed, allowing the pass to do initialization as necessary.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>.</p>

</div>
</div>

### doInitialization() {#ab007d6c51634eb65e4f4f9dab4eb6a8c}

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

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a6cc67c5a27b53bc940d292c0aeb6aba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallGraphSCCPass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - For this class, we declare that we require and preserve the call graph.</p>


<p>For this class, we declare that we require and preserve the call graph.</p>


<p>If the derived class implements this method, it should always explicitly call the implementation here.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>, definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuannotatekernelfeatures-cpp-/amdgpuannotatekernelfeatures/#aafd88529f6193a278e1c5bb87943eb13">anonymous{AMDGPUAnnotateKernelFeatures.cpp}::AMDGPUAnnotateKernelFeatures::getAnalysisUsage</a>.</p>

</div>
</div>

### getPotentialPassManagerType() {#a3f75da9a2ae556a5cdceaee11f4afaf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManagerType llvm::CallGraphSCCPass::getPotentialPassManagerType ()</td>
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

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbacfbf7d6825e58faf3673dc5e5a7a2465">llvm::PMT_CallGraphPassManager</a>.</p>

</div>
</div>

### runOnSCC() {#a5ab09f122afda68d4c0d86e8e5877465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::CallGraphSCCPass::runOnSCC (<a href="/web-llvm/docs/api/classes/llvm/callgraphscc">CallGraphSCC</a> &amp; SCC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runOnSCC - This method should be implemented by the subclass to perform whatever action is necessary for the specified SCC.</p>


<p>Note that non-recursive (or only self-recursive) functions will have an SCC size of 1, where recursive portions of the call graph will have SCC size &gt; 1.</p>


<p>SCC passes that add or delete functions to the SCC are required to update the SCC list, otherwise stale pointers may be dereferenced.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### skipSCC() {#a978ee5e9b5b33e10cea60aea38f80788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallGraphSCCPass::skipSCC (<a href="/web-llvm/docs/api/classes/llvm/callgraphscc">CallGraphSCC</a> &amp; SCC)</td>
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


<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp/#a2bd4f0ba04228d5fb919734abb9ca1af">getDescription</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ad729b39eacf070a9bca84533b3c743bf">llvm::Pass::getPassName</a>, <a href="/web-llvm/docs/api/classes/llvm/optpassgate/#a0324a149fd3db35e2f789c91a4d30da4">llvm::OptPassGate::isEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/optpassgate/#a59de8deea51271200bbfc1e5be45ee3c">llvm::OptPassGate::shouldRunPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraphsccpass-h">CallGraphSCCPass.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
