---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/legacy/passmanagerimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PassManagerImpl` Class

<p><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl">PassManagerImpl</a> manages MPPassManagers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::legacy::PassManagerImpl { ... }
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager">PMTopLevelManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager">PMTopLevelManager</a> manages LastUser info and collects common APIs used by top level pass managers. <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fe001798819fa40f548ade3fde03df">PassManagerImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d27e9f9118eddcf4ee25bd89991eb4">add</a> (Pass *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a pass to the queue of passes to run. <a href="#a34d27e9f9118eddcf4ee25bd89991eb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59d53abe9eb1035e1c37319f925eb29">createPrinterPass</a> (raw_ostream &amp;O, const std::string &amp;Banner) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createPrinterPass - Get a module printer pass. <a href="#ae59d53abe9eb1035e1c37319f925eb29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ae04b5379a8cdfe46595e2b00a182d">run</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>run - Execute all of the passes scheduled for execution. <a href="#a87ae04b5379a8cdfe46595e2b00a182d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcfb8af22875ea5e45d7a9fb44da7d2">getAnalysisUsage</a> (AnalysisUsage &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager itself does not invalidate any analysis info. <a href="#a0fcfb8af22875ea5e45d7a9fb44da7d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8faf41effdf1dda0eaa99b29ef111534">getAsPMDataManager</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d2e27c8764b7c8b90d8fab007d6244">getAsPass</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0da216a943d6f73e31c46422f225ed39">getTopLevelPassManagerType</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MPPassManager *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa361fb3ab0c9da9975f3df18f57e2d5a">getContainedManager</a> (unsigned N)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a572ee708832d73d05b374fd86dc0131c">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57dc687ab84ee7891f71a236b64a306a">ID</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl">PassManagerImpl</a> manages MPPassManagers.</p>

<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PassManagerImpl() {#a99fe001798819fa40f548ade3fde03df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::legacy::PassManagerImpl::PassManagerImpl ()</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="#a57dc687ab84ee7891f71a236b64a306a">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#adc80432cc11960e6cf7fcae1a64c07a5">llvm::PMTopLevelManager::PMTopLevelManager</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0da955cbb4215ccd3e153c81e415b9d5ae1d9783815f758fc0e410820cb118727">llvm::PT_PassManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a34d27e9f9118eddcf4ee25bd89991eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::legacy::PassManagerImpl::add (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
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

<p>Add a pass to the queue of passes to run.</p>


<p>This passes ownership of the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> to the <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager">PassManager</a>. When the <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager">PassManager</a> is destroyed, the pass will be destroyed as well, so there is no need to delete the pass. This may even destroy the pass right away if it is found to be redundant. This implies that all passes MUST be allocated with 'new'.</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a> and <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5fb719fc8062d116b93091d9c9addd43">llvm::PMTopLevelManager::schedulePass</a>.</p>

</div>
</div>

### createPrinterPass() {#ae59d53abe9eb1035e1c37319f925eb29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * llvm::legacy::PassManagerImpl::createPrinterPass (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Banner)</td>
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

<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


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

<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

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

<p>Declaration at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">Pass.h</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a0fcfb8af22875ea5e45d7a9fb44da7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::legacy::PassManagerImpl::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; Info)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager itself does not invalidate any analysis info.</p>

<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

### getAsPass() {#a36d2e27c8764b7c8b90d8fab007d6244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * llvm::legacy::PassManagerImpl::getAsPass ()</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pass/#a16baa169d062524be5a6b67609266174">llvm::Pass::Pass</a>.</p>

</div>
</div>

### getAsPMDataManager() {#a8faf41effdf1dda0eaa99b29ef111534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMDataManager * llvm::legacy::PassManagerImpl::getAsPMDataManager ()</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a04fbd0afa6857fe697dd28e93bdfec07">llvm::PMDataManager::PMDataManager</a>.</p>

</div>
</div>

### getContainedManager() {#aa361fb3ab0c9da9975f3df18f57e2d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MPPassManager * llvm::legacy::PassManagerImpl::getContainedManager (unsigned N)</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a62f1c43ba247efb9b876c45fe2356eea">llvm::PMTopLevelManager::PassManagers</a>.</p>


<p>Referenced by <a href="#a87ae04b5379a8cdfe46595e2b00a182d">run</a>.</p>

</div>
</div>

### getTopLevelPassManagerType() {#a0da216a943d6f73e31c46422f225ed39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManagerType llvm::legacy::PassManagerImpl::getTopLevelPassManagerType ()</td>
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



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebbad553155122a5bf541ead3e0aa5b13287">llvm::PMT_ModulePassManager</a>.</p>

</div>
</div>

### run() {#a87ae04b5379a8cdfe46595e2b00a182d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::legacy::PassManagerImpl::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>run - Execute all of the passes scheduled for execution.</p>


<p>Keep track of whether any of the passes modifies the module, and if so, return true.</p>


<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a9bcf6682702cbde1eeeb006b7e49cf62">llvm::PMTopLevelManager::dumpArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#aa58716ef5ab4c044f1f90f257bf91e6a">llvm::PMTopLevelManager::dumpPasses</a>, <a href="#aa361fb3ab0c9da9975f3df18f57e2d5a">getContainedManager</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#ad8b44da91c0acd3bd2263f5f1c071696">llvm::PMTopLevelManager::getImmutablePasses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#ad3b4cd4b801ce3601afffa97acc8991d">llvm::PMTopLevelManager::getNumContainedManagers</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#ad54000cb15d4de5f1cccee55f29e6ab1">llvm::PMTopLevelManager::initializeAllAnalysisInfo</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h/#a926189935285d6e5df83fc0f45bf9b36">UseNewDbgInfoFormat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a572ee708832d73d05b374fd86dc0131c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::legacy::PassManagerImpl::anchor ()</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a57dc687ab84ee7891f71a236b64a306a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::legacy::PassManagerImpl::ID = 0</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Referenced by <a href="#a99fe001798819fa40f548ade3fde03df">PassManagerImpl</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
