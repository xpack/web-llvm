---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CGPassManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{CallGraphSCCPass.cpp}::CGPassManager { ... }
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> class - This class is used to implement unstructured interprocedural optimizations and analyses. <a href="/web-llvm/docs/api/classes/llvm/modulepass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46813b9b0cc8e92d425a4051629a6faf">CGPassManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f2ac01d6e79a5eff1623936ef49847c">runOnModule</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute all of the passes scheduled for execution. <a href="#a1f2ac01d6e79a5eff1623936ef49847c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2330998b675c05167dc0a94a9f197599">doInitialization</a> (CallGraph &amp;CG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize CG. <a href="#a2330998b675c05167dc0a94a9f197599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8841a51c6b06a2a29e8e51024e9bc19">doFinalization</a> (CallGraph &amp;CG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize CG. <a href="#ae8841a51c6b06a2a29e8e51024e9bc19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf630d8224dd75b3d7126b5570583993">getAnalysisUsage</a> (AnalysisUsage &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pass Manager itself does not invalidate any analysis info. <a href="#adf630d8224dd75b3d7126b5570583993">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4de0a330feac0dfbe56a432708a4466b">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a4de0a330feac0dfbe56a432708a4466b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be65bf69e5ca2c5991ce27de19edfd2">getAsPMDataManager</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3cbde4fa9325acf3d46bcd036e7fc87">getAsPass</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4efbb82e436e90c66cc02d1630c0c528">dumpPassStructure</a> (unsigned Offset) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1bfae8468f5272b17dbfa99b21d8cf">getContainedPass</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebb">PassManagerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc34f807b2f181d7bec482d48e573b1e">getPassManagerType</a> () const override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c20f5c586261232135305bc59c47a38">RunAllPassesOnSCC</a> (CallGraphSCC &amp;CurSCC, CallGraph &amp;CG, bool &amp;DevirtualizedCall)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute the body of the entire pass manager on the specified SCC. <a href="#a9c20f5c586261232135305bc59c47a38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd54f93ecba68838bdd995e5198c152">RunPassOnSCC</a> (Pass *P, CallGraphSCC &amp;CurSCC, CallGraph &amp;CG, bool &amp;CallGraphUpToDate, bool &amp;DevirtualizedCall)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232124c5d47b0600826c871de8854619">RefreshCallGraph</a> (const CallGraphSCC &amp;CurSCC, CallGraph &amp;CG, bool IsCheckingMode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the functions in the specified CFG and resync the callgraph with the call sites found in it. <a href="#a232124c5d47b0600826c871de8854619">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64242286713b4f504b054b1e13f87aaf">ID</a> = 0</td>
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


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CGPassManager() {#a46813b9b0cc8e92d425a4051629a6faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CallGraphSCCPass.cpp}::CGPassManager::CGPassManager ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="#a64242286713b4f504b054b1e13f87aaf">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/modulepass/#a723659a08d210f4f566887bda3f9f976">llvm::ModulePass::ModulePass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doFinalization() {#ae8841a51c6b06a2a29e8e51024e9bc19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CGPassManager::doFinalization (<a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp; CG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize CG.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0be65bf69e5ca2c5991ce27de19edfd2">getAsPMDataManager</a>, <a href="#a4b1bfae8468f5272b17dbfa99b21d8cf">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraph/#ac6148a4c6df56af41c63c0c3a798c447">llvm::CallGraph::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa877f351376c696b385fdeba9b93a5f1">llvm::PMDataManager::getPassManagerType</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a04fbd0afa6857fe697dd28e93bdfec07">llvm::PMDataManager::PMDataManager</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbaf92a84a9aa3cca1378d1a12fc3664396">llvm::PMT_FunctionPassManager</a>.</p>


<p>Referenced by <a href="#a1f2ac01d6e79a5eff1623936ef49847c">runOnModule</a>.</p>

</div>
</div>

### doInitialization() {#a2330998b675c05167dc0a94a9f197599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CGPassManager::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp; CG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize CG.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0be65bf69e5ca2c5991ce27de19edfd2">getAsPMDataManager</a>, <a href="#a4b1bfae8468f5272b17dbfa99b21d8cf">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraph/#ac6148a4c6df56af41c63c0c3a798c447">llvm::CallGraph::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa877f351376c696b385fdeba9b93a5f1">llvm::PMDataManager::getPassManagerType</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a04fbd0afa6857fe697dd28e93bdfec07">llvm::PMDataManager::PMDataManager</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbaf92a84a9aa3cca1378d1a12fc3664396">llvm::PMT_FunctionPassManager</a>.</p>


<p>Referenced by <a href="#a1f2ac01d6e79a5eff1623936ef49847c">runOnModule</a>.</p>

</div>
</div>

### dumpPassStructure() {#a4efbb82e436e90c66cc02d1630c0c528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CallGraphSCCPass.cpp}::CGPassManager::dumpPassStructure (unsigned Offset)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a0ced924c11b3eddbfccd9c186f38a389">llvm::PMDataManager::dumpLastUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a4b1bfae8468f5272b17dbfa99b21d8cf">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>.</p>

</div>
</div>

### getAnalysisUsage() {#adf630d8224dd75b3d7126b5570583993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CallGraphSCCPass.cpp}::CGPassManager::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; Info)</td>
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

<p>Pass Manager itself does not invalidate any analysis info.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>

</div>
</div>

### getAsPass() {#ab3cbde4fa9325acf3d46bcd036e7fc87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * anonymous{CallGraphSCCPass.cpp}::CGPassManager::getAsPass ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>.</p>

</div>
</div>

### getAsPMDataManager() {#a0be65bf69e5ca2c5991ce27de19edfd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMDataManager * anonymous{CallGraphSCCPass.cpp}::CGPassManager::getAsPMDataManager ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a04fbd0afa6857fe697dd28e93bdfec07">llvm::PMDataManager::PMDataManager</a>.</p>


<p>Referenced by <a href="#ae8841a51c6b06a2a29e8e51024e9bc19">doFinalization</a> and <a href="#a2330998b675c05167dc0a94a9f197599">doInitialization</a>.</p>

</div>
</div>

### getContainedPass() {#a4b1bfae8468f5272b17dbfa99b21d8cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * anonymous{CallGraphSCCPass.cpp}::CGPassManager::getContainedPass (unsigned N)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a433bcef3e3a89059a3510632b640525d">llvm::PMDataManager::PassVector</a>.</p>


<p>Referenced by <a href="#ae8841a51c6b06a2a29e8e51024e9bc19">doFinalization</a>, <a href="#a2330998b675c05167dc0a94a9f197599">doInitialization</a> and <a href="#a4efbb82e436e90c66cc02d1630c0c528">dumpPassStructure</a>.</p>

</div>
</div>

### getPassManagerType() {#abc34f807b2f181d7bec482d48e573b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManagerType anonymous{CallGraphSCCPass.cpp}::CGPassManager::getPassManagerType ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbacfbf7d6825e58faf3673dc5e5a7a2465">llvm::PMT_CallGraphPassManager</a>.</p>

</div>
</div>

### getPassName() {#a4de0a330feac0dfbe56a432708a4466b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{CallGraphSCCPass.cpp}::CGPassManager::getPassName ()</td>
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


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>

</div>
</div>

### runOnModule() {#a1f2ac01d6e79a5eff1623936ef49847c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CGPassManager::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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


<p>Keep track of whether any of the passes modifies the module, and if so, return true.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ae8841a51c6b06a2a29e8e51024e9bc19">doFinalization</a>, <a href="#a2330998b675c05167dc0a94a9f197599">doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphscc/#a87e1b8515d22eb833375761e19a2d0fe">llvm::CallGraphSCC::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/scc-iterator/#a7d6ec03718a5e48f3ec7ce22fefcb91d">llvm::scc_iterator&lt; GraphT, GT &gt;::isAtEnd</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec6409a70645bde7c81ab78a13ddbf62">llvm::MaxDevirtIterations</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3c1a67796e24a843db8a6766baa54c21">llvm::scc_begin</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### RefreshCallGraph() {#a232124c5d47b0600826c871de8854619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CGPassManager::RefreshCallGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callgraphscc">CallGraphSCC</a> &amp; CurSCC, <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp; CG, bool CheckingMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan the functions in the specified CFG and resync the callgraph with the call sites found in it.</p>


<p>This is used after FunctionPasses have potentially munged the callgraph, and can be used after <a href="/web-llvm/docs/api/classes/llvm/callgraphscc">CallGraphSCC</a> passes to verify that they correctly updated the callgraph.</p>


<p>This function returns true if it devirtualized an existing function call, meaning it turned an indirect call into a direct call. This happens when a function pass like GVN optimizes away stuff feeding the indirect call. This never happens in checking mode.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>

</div>
</div>

### RunAllPassesOnSCC() {#a9c20f5c586261232135305bc59c47a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CGPassManager::RunAllPassesOnSCC (<a href="/web-llvm/docs/api/classes/llvm/callgraphscc">CallGraphSCC</a> &amp; CurSCC, <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp; CG, bool &amp; DevirtualizedCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Execute the body of the entire pass manager on the specified SCC.</p>


<p>This keeps track of whether a function pass devirtualizes any calls and returns it in DevirtualizedCall.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>

</div>
</div>

### RunPassOnSCC() {#abcd54f93ecba68838bdd995e5198c152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CGPassManager::RunPassOnSCC (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/classes/llvm/callgraphscc">CallGraphSCC</a> &amp; CurSCC, <a href="/web-llvm/docs/api/classes/llvm/callgraph">CallGraph</a> &amp; CG, bool &amp; CallGraphUpToDate, bool &amp; DevirtualizedCall)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a64242286713b4f504b054b1e13f87aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char CGPassManager::ID = 0</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a>.</p>


<p>Referenced by <a href="#a46813b9b0cc8e92d425a4051629a6faf">CGPassManager</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/callgraphsccpass-cpp">CallGraphSCCPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
