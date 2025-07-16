---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lppassmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LPPassManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LPPassManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">llvm/Analysis/LoopPass.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb5f46582c10632d8ade1b742fdcb2e">LPPassManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3255b0b3ab79ad0d1b93ce3da675f240">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>run - Execute all of the passes scheduled for execution. <a href="#a3255b0b3ab79ad0d1b93ce3da675f240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0634789ad2f8cfd833fd112e442b673">getAnalysisUsage</a> (AnalysisUsage &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager itself does not invalidate any analysis info. <a href="#af0634789ad2f8cfd833fd112e442b673">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab330db94614e271ddf1917b9fcda942a">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#ab330db94614e271ddf1917b9fcda942a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pmdatamanager">PMDataManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78b739f40fe028fb23063683a95e541">getAsPMDataManager</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ce0ea9ab8fea4e7a4e703168a700fb">getAsPass</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65a4ed6b290a5d717266585050528047">dumpPassStructure</a> (unsigned Offset) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print passes managed by this manager. <a href="#a65a4ed6b290a5d717266585050528047">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/looppass">LoopPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec82063d9514c697c7a721f257740646">getContainedPass</a> (unsigned N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e2ab86262accd296eb1b0e07967cdb">getPassManagerType</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f0da3d3400c893b1d8142685ccdc9e">addLoop</a> (Loop &amp;L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef47cc6f59b91bf5a1392975366e758">markLoopAsDeleted</a> (Loop &amp;L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335d3e49c3ce9ebf43f00adfc41bdcef">LQ</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93613d1fe35fb631aae96de7b1bc3fb">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab47ef2683fcfa2b4065372668c2c1927">CurrentLoop</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5f67284fe7001c9c544f2826b7eaa1">CurrentLoopDeleted</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1224693d1bc6f86b718b4f80379b6f47">ID</a> = 0</td>
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


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LPPassManager() {#afeb5f46582c10632d8ade1b742fdcb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LPPassManager::LPPassManager ()</td>
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



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/looppass-cpp">LoopPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a> and <a href="#a1224693d1bc6f86b718b4f80379b6f47">ID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLoop() {#ac8f0da3d3400c893b1d8142685ccdc9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LPPassManager::addLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/looppass-cpp">LoopPass.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afe8e2e0edcd7756ff5985b8798270c5d">llvm::cloneLoop</a>.</p>

</div>
</div>

### dumpPassStructure() {#a65a4ed6b290a5d717266585050528047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LPPassManager::dumpPassStructure (unsigned Offset)</td>
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

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/looppass-cpp">LoopPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a0ced924c11b3eddbfccd9c186f38a389">llvm::PMDataManager::dumpLastUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#aec82063d9514c697c7a721f257740646">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getAnalysisUsage() {#af0634789ad2f8cfd833fd112e442b673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LPPassManager::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; Info)</td>
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

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/looppass-cpp">LoopPass.cpp</a>.</p>

</div>
</div>

### getAsPass() {#a40ce0ea9ab8fea4e7a4e703168a700fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pass * llvm::LPPassManager::getAsPass ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/looppass/#a726cb7795e83c8e4fa0ee16af164f62b">llvm::LoopPass::assignPassManager</a>.</p>

</div>
</div>

### getAsPMDataManager() {#ac78b739f40fe028fb23063683a95e541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PMDataManager * llvm::LPPassManager::getAsPMDataManager ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a04fbd0afa6857fe697dd28e93bdfec07">llvm::PMDataManager::PMDataManager</a>.</p>

</div>
</div>

### getContainedPass() {#aec82063d9514c697c7a721f257740646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopPass * llvm::LPPassManager::getContainedPass (unsigned N)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a433bcef3e3a89059a3510632b640525d">llvm::PMDataManager::PassVector</a>.</p>


<p>Referenced by <a href="#a65a4ed6b290a5d717266585050528047">dumpPassStructure</a> and <a href="#a3255b0b3ab79ad0d1b93ce3da675f240">runOnFunction</a>.</p>

</div>
</div>

### getPassManagerType() {#a75e2ab86262accd296eb1b0e07967cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassManagerType llvm::LPPassManager::getPassManagerType ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3948b4d0759f9852502b466d6cfb4ebba261546b9459b573317e1beb417384b71">llvm::PMT_LoopPassManager</a>.</p>

</div>
</div>

### getPassName() {#ab330db94614e271ddf1917b9fcda942a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::LPPassManager::getPassName ()</td>
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


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>

</div>
</div>

### markLoopAsDeleted() {#a8ef47cc6f59b91bf5a1392975366e758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LPPassManager::markLoopAsDeleted (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/looppass-cpp">LoopPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopunrollpass-cpp-/loopunroll/#a176b0f7a9dc90d996cae2767b3aea0ca">anonymous{LoopUnrollPass.cpp}::LoopUnroll::runOnLoop</a>.</p>

</div>
</div>

### runOnFunction() {#a3255b0b3ab79ad0d1b93ce3da675f240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LPPassManager::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>run - Execute all of the passes scheduled for execution.</p>


<p>Keep track of whether any of the passes modifies the module, and if so, return true.</p>


<p>Keep track of whether any of the passes modifies the function, and if so, return true.</p>


<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/looppass-cpp">LoopPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/looppass-cpp/#a7bf4e13745727358c085cb143db4978f">addLoopIntoQueue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aff93635e4ea28861beb90faece603b3d">llvm::PMDataManager::dumpPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#adfe9cc105a283f4d7e4e56c6d4440adb">llvm::PMDataManager::dumpPreservedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a799e97f6f38435a58b8ecf6a85eb7399">llvm::PMDataManager::dumpRequiredSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab3115ef36979b45874f244f374e79d98">llvm::PMDataManager::emitInstrCountChangedRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a3f3116bde1268f9e1cd78d9010e4ff26">llvm::EXECUTION_MSG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a9ded95b3d23d780dbaf94c287465f69a">llvm::PMDataManager::freePass</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="#aec82063d9514c697c7a721f257740646">getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aa37440cfb2bd92a0b361cb2a6e1232e2">llvm::PMDataManager::getNumContainedPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d0285e03a80731db23ba77d291942d">llvm::getPassTimer</a>, <a href="/web-llvm/docs/api/structs/llvm/lcssaverificationpass/#a1d7088de549291fdf77d045bd3f6a691">llvm::LCSSAVerificationPass::ID</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a813e1d4b6102a11cad9963778f889d4d">llvm::PMDataManager::initializeAnalysisImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a579d453037e2211a02d8f50a736eff46">llvm::PMDataManager::initSizeRemarkInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp/#acc16edf21eddec420cd4b27adb3111c6">InstrCount</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a72e482d46273910cd5a3a02b0f65647f">llvm::MODIFICATION_MSG</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a0b4a511579939b07831db90c3fc98996">llvm::Pass::mustPreserveAnalysisID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e7283c48f393f907c761d39cb7f0b51a3e546b8cb5a3e5e11ad3895f0542dfc4">llvm::ON_LOOP_MSG</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ad469713fc40b5f0baba648041a68dfa7">llvm::PMDataManager::populateInheritedAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a35ff10683333230676c1d3c4379b58b1">llvm::PMDataManager::recordAvailableAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a09ac67e36db813f2a3e69173f7638037">llvm::PMDataManager::removeDeadPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#af740891e192aa63a0fbbfe317301cbdb">llvm::PMDataManager::removeNotPreservedAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aaa1883b3ebb15e2de80d6f08004a8528">llvm::PMDataManager::TPM</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a86a4b032c64ea61c59d12929a76c9833">llvm::PMDataManager::verifyPreservedAnalysis</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentLoop {#ab47ef2683fcfa2b4065372668c2c1927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::LPPassManager::CurrentLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>

</div>
</div>

### CurrentLoopDeleted {#a2e5f67284fe7001c9c544f2826b7eaa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LPPassManager::CurrentLoopDeleted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>

</div>
</div>

### LI {#af93613d1fe35fb631aae96de7b1bc3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::LPPassManager::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>

</div>
</div>

### LQ {#a335d3e49c3ce9ebf43f00adfc41bdcef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt;Loop *&gt; llvm::LPPassManager::LQ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a1224693d1bc6f86b718b4f80379b6f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char LPPassManager::ID = 0</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a>.</p>


<p>Referenced by <a href="#afeb5f46582c10632d8ade1b742fdcb2e">LPPassManager</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/looppass-h">LoopPass.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/looppass-cpp">LoopPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
