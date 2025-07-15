---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-legacypassmanager-cpp-/mppassmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MPPassManager` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager">MPPassManager</a> manages ModulePasses and function pass managers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LegacyPassManager.cpp}::MPPassManager { ... }
</div>

## Base classes

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a9a3415fcb39b9461c78a41b23ab7f">MPPassManager</a> ()</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e7d257d78a2dcb92ba6a703816a7b40">~MPPassManager</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b89931791713740e3d5af2fba2a4212">createPrinterPass</a> (raw_ostream &amp;O, const std::string &amp;Banner) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createPrinterPass - Get a module printer pass. <a href="#a2b89931791713740e3d5af2fba2a4212">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15f0d5cca56f2c4cc4f59bc85803233a">runOnModule</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>run - Execute all of the passes scheduled for execution. <a href="#a15f0d5cca56f2c4cc4f59bc85803233a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad964abda6d37530f33eddb5728f4849">getAnalysisUsage</a> (AnalysisUsage &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pass Manager itself does not invalidate any analysis info. <a href="#aad964abda6d37530f33eddb5728f4849">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452b3946fae687fe6ab129970b5f9c75">addLowerLevelRequiredPass</a> (Pass *P, Pass *RequiredPass) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add RequiredPass into list of lower level passes required by pass P. <a href="#a452b3946fae687fe6ab129970b5f9c75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a887a8078ca0523b9494da138a800bb65">getOnTheFlyPass</a> (Pass *MP, AnalysisID PI, Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return function pass corresponding to <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> PI, that is required by module pass MP. <a href="#a887a8078ca0523b9494da138a800bb65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9fe9e33c8a67a5ffd2d2bdabb22faff">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#aa9fe9e33c8a67a5ffd2d2bdabb22faff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd4ef7350f9c547bfc34170ebdc1ae8">getAsPMDataManager</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a957b3c9bb2a8b7107fa8d6b1a82598d8">getAsPass</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9d902501ce3b0da29040e896cc4a9e">dumpPassStructure</a> (unsigned Offset) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304af141af26777cf00f13742ebb8bd8">getContainedPass</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a984096e4b4d7b01034b42f67bcecd9">getPassManagerType</a> () const override</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl">legacy::FunctionPassManagerImpl</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9557f5716c80b679b636937bf38f85f6">OnTheFlyManagers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of on the fly FPPassManagers. <a href="#a9557f5716c80b679b636937bf38f85f6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae825014371eff3839ce49616375e37a5">ID</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager">MPPassManager</a> manages ModulePasses and function pass managers.</p>


<p>It batches all <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> passes and function pass managers together and sequences them to process one module.</p>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MPPassManager() {#a80a9a3415fcb39b9461c78a41b23ab7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LegacyPassManager.cpp}::MPPassManager::MPPassManager ()</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="#ae825014371eff3839ce49616375e37a5">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0da955cbb4215ccd3e153c81e415b9d5ae1d9783815f758fc0e410820cb118727">llvm::PT_PassManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MPPassManager() {#a6e7d257d78a2dcb92ba6a703816a7b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LegacyPassManager.cpp}::MPPassManager::~MPPassManager ()</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLowerLevelRequiredPass() {#a452b3946fae687fe6ab129970b5f9c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MPPassManager::addLowerLevelRequiredPass (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * RequiredPass)</td>
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

<p>Add RequiredPass into list of lower level passes required by pass P.</p>


<p>RequiredPass is run on the fly by Pass Manager when P requests it through getAnalysis interface.</p>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a11484d56af409b65a713965e27296130">llvm::legacy::FunctionPassManagerImpl::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a63192e749ba4a0ee29336a59d6a19647">llvm::Pass::getPassID</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a05cd3cab5ce2e13c7636ef21adef6e8d">llvm::Pass::getPotentialPassManagerType</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#a6f599935d3a65631f812392f94bb5775">llvm::PassInfo::isAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbad553155122a5bf541ead3e0aa5b13287">llvm::PMT_ModulePassManager</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5eab64f06a4196bd59b9b19251eefddb">llvm::PMTopLevelManager::setLastUser</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a61adb3228a4dd2685aeb402e7a4c35d3">llvm::PMDataManager::setTopLevelManager</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aaa1883b3ebb15e2de80d6f08004a8528">llvm::PMDataManager::TPM</a>.</p>

</div>
</div>

### createPrinterPass() {#a2b89931791713740e3d5af2fba2a4212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * anonymous{LegacyPassManager.cpp}::MPPassManager::createPrinterPass (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Banner)</td>
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

<p>createPrinterPass - Get a module printer pass.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acc83e523c1969f39981f64d42a1ba18a">llvm::createPrintModulePass</a> and <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>.</p>

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
<td class="doxyMemberName">virtual bool llvm::Pass::doFinalization (<a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a> &amp;)</td>
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

<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

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
<td class="doxyMemberName">virtual bool llvm::Pass::doInitialization (<a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a> &amp;)</td>
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

<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### dumpPassStructure() {#a7c9d902501ce3b0da29040e896cc4a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LegacyPassManager.cpp}::MPPassManager::dumpPassStructure (unsigned Offset)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a0ced924c11b3eddbfccd9c186f38a389">llvm::PMDataManager::dumpLastUses</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#ad2f0576ef7c9c4af40e35001c81f4922">llvm::Pass::dumpPassStructure</a>, <a href="#a304af141af26777cf00f13742ebb8bd8">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getAnalysisUsage() {#aad964abda6d37530f33eddb5728f4849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LegacyPassManager.cpp}::MPPassManager::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; Info)</td>
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

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

### getAsPass() {#a957b3c9bb2a8b7107fa8d6b1a82598d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * anonymous{LegacyPassManager.cpp}::MPPassManager::getAsPass ()</td>
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



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>.</p>

</div>
</div>

### getAsPMDataManager() {#aafd4ef7350f9c547bfc34170ebdc1ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMDataManager * anonymous{LegacyPassManager.cpp}::MPPassManager::getAsPMDataManager ()</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a04fbd0afa6857fe697dd28e93bdfec07">llvm::PMDataManager::PMDataManager</a>.</p>

</div>
</div>

### getContainedPass() {#a304af141af26777cf00f13742ebb8bd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModulePass * anonymous{LegacyPassManager.cpp}::MPPassManager::getContainedPass (unsigned N)</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a433bcef3e3a89059a3510632b640525d">llvm::PMDataManager::PassVector</a>.</p>


<p>Referenced by <a href="#a7c9d902501ce3b0da29040e896cc4a9e">dumpPassStructure</a> and <a href="#a15f0d5cca56f2c4cc4f59bc85803233a">runOnModule</a>.</p>

</div>
</div>

### getOnTheFlyPass() {#a887a8078ca0523b9494da138a800bb65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Pass *, bool &gt; MPPassManager::getOnTheFlyPass (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * MP, <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a> PI, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Return function pass corresponding to <a href="/web-llvm/docs/api/classes/llvm/passinfo">PassInfo</a> PI, that is required by module pass MP.</p>


<p>Instantiate analysis pass, by using its <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#a3985f1f39349428d17f0d2b81ebc6349">runOnFunction()</a> for function F.</p>


<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a36f417ced43a7724c39f10c67eb7d53d">llvm::PMDataManager::findAnalysisPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a35df5259dc1bc4f526a32a2d18cb3f59">llvm::legacy::FunctionPassManagerImpl::releaseMemoryOnTheFly</a> and <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a6db182b17b61e8b4053a79e7f15b03b5">llvm::legacy::FunctionPassManagerImpl::run</a>.</p>

</div>
</div>

### getPassManagerType() {#a8a984096e4b4d7b01034b42f67bcecd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManagerType anonymous{LegacyPassManager.cpp}::MPPassManager::getPassManagerType ()</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbad553155122a5bf541ead3e0aa5b13287">llvm::PMT_ModulePassManager</a>.</p>

</div>
</div>

### getPassName() {#aa9fe9e33c8a67a5ffd2d2bdabb22faff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{LegacyPassManager.cpp}::MPPassManager::getPassName ()</td>
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


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

### runOnModule() {#a15f0d5cca56f2c4cc4f59bc85803233a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MPPassManager::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>run - Execute all of the passes scheduled for execution.</p>


<p>Execute all of the passes scheduled for execution by invoking runOnModule method.</p>


<p>Keep track of whether any of the passes modifies the module, and if so, return true.</p>


<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a9e96a5db4aa64e696dfee55356b7f048">llvm::legacy::FunctionPassManagerImpl::doFinalization</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a3629e481a2aaf6f1f0bebcc4439185e8">llvm::legacy::FunctionPassManagerImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aff93635e4ea28861beb90faece603b3d">llvm::PMDataManager::dumpPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#adfe9cc105a283f4d7e4e56c6d4440adb">llvm::PMDataManager::dumpPreservedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a799e97f6f38435a58b8ecf6a85eb7399">llvm::PMDataManager::dumpRequiredSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af71955a48208ff25a6c8b5f6f2890417">llvm::PMDataManager::dumpUsedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab3115ef36979b45874f244f374e79d98">llvm::PMDataManager::emitInstrCountChangedRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a3f3116bde1268f9e1cd78d9010e4ff26">llvm::EXECUTION_MSG</a>, <a href="#a304af141af26777cf00f13742ebb8bd8">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d0285e03a80731db23ba77d291942d">llvm::getPassTimer</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a813e1d4b6102a11cad9963778f889d4d">llvm::PMDataManager::initializeAnalysisImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a579d453037e2211a02d8f50a736eff46">llvm::PMDataManager::initSizeRemarkInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp/#acc16edf21eddec420cd4b27adb3111c6">InstrCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a72e482d46273910cd5a3a02b0f65647f">llvm::MODIFICATION_MSG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a8c70bfed1eb1475d72b6473960678ad1">llvm::ON_MODULE_MSG</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a35ff10683333230676c1d3c4379b58b1">llvm::PMDataManager::recordAvailableAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a35df5259dc1bc4f526a32a2d18cb3f59">llvm::legacy::FunctionPassManagerImpl::releaseMemoryOnTheFly</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a09ac67e36db813f2a3e69173f7638037">llvm::PMDataManager::removeDeadPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af740891e192aa63a0fbbfe317301cbdb">llvm::PMDataManager::removeNotPreservedAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/modulepass/#ae9d79b12dbc2a82d5739e1c7f077dd0c">llvm::ModulePass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a86a4b032c64ea61c59d12929a76c9833">llvm::PMDataManager::verifyPreservedAnalysis</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OnTheFlyManagers {#a9557f5716c80b679b636937bf38f85f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;Pass *, legacy::FunctionPassManagerImpl *&gt; anonymous{LegacyPassManager.cpp}::MPPassManager::OnTheFlyManagers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of on the fly FPPassManagers.</p>


<p>These managers manage function passes that are required by module passes.</p>


<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ae825014371eff3839ce49616375e37a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{LegacyPassManager.cpp}::MPPassManager::ID = 0</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Referenced by <a href="#a80a9a3415fcb39b9461c78a41b23ab7f">MPPassManager</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
