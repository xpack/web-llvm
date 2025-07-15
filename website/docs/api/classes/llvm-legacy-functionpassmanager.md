---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/legacy/functionpassmanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionPassManager` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager">FunctionPassManager</a> manages FunctionPasses. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::legacy::FunctionPassManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> - An abstract interface to allow code to add passes to a pass manager without having to hard-code what kind of pass manager it is. <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6863d1a1103952a65546e85c320cf061">FunctionPassManager</a> (Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager">FunctionPassManager</a> ctor - This initializes the pass manager. <a href="#a6863d1a1103952a65546e85c320cf061">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a338724c6878e4e6352491890463a18b3">~FunctionPassManager</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bec72c759c38b748ff60434eb4d0c80">add</a> (Pass *P) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a pass to the queue of passes to run. <a href="#a1bec72c759c38b748ff60434eb4d0c80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e592cc8ca8a049fbe052f809514c73">run</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>run - Execute all of the passes scheduled for execution. <a href="#a02e592cc8ca8a049fbe052f809514c73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb64dd75fa1775aeb32cde0bc17b72a">doInitialization</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doInitialization - Run all of the initializers for the function passes. <a href="#a7cb64dd75fa1775aeb32cde0bc17b72a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabcf819b6866d85a9fc8f882ff0e9ead">doFinalization</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>doFinalization - Run all of the finalizers for the function passes. <a href="#aabcf819b6866d85a9fc8f882ff0e9ead">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl">FunctionPassManagerImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb33e901a2ec1e394e693ca7c3c3ba4d">FPM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13c4d67e67953011ef9e2a3f34dc9fc">M</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager">FunctionPassManager</a> manages FunctionPasses.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionPassManager() {#a6863d1a1103952a65546e85c320cf061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::legacy::FunctionPassManager::FunctionPassManager (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager">FunctionPassManager</a> ctor - This initializes the pass manager.</p>


<p>Create new <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> pass manager.</p>


<p>It needs, but does not take ownership of, the specified <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>, definition at line 1293 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FunctionPassManager() {#a338724c6878e4e6352491890463a18b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::legacy::FunctionPassManager::~FunctionPassManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>, definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a1bec72c759c38b748ff60434eb4d0c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::legacy::FunctionPassManager::add (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
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

<p>Add a pass to the queue of passes to run.</p>


<p>This passes ownership of the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> to the <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager">PassManager</a>. When the <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager">PassManager</a> is destroyed, the pass will be destroyed as well, so there is no need to delete the pass. This may even destroy the pass right away if it is found to be redundant. This implies that all passes MUST be allocated with 'new'.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>, definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa5e968db4987e612699b3957b125adf4">invokeFunctionPass</a> and <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#adcb87ee7d8b9f08bc82da9cae1c74429">llvm::PlaceSafepointsPass::runImpl</a>.</p>

</div>
</div>

### doFinalization() {#aabcf819b6866d85a9fc8f882ff0e9ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::legacy::FunctionPassManager::doFinalization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>doFinalization - Run all of the finalizers for the function passes.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>, definition at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa5e968db4987e612699b3957b125adf4">invokeFunctionPass</a>.</p>

</div>
</div>

### doInitialization() {#a7cb64dd75fa1775aeb32cde0bc17b72a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::legacy::FunctionPassManager::doInitialization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>doInitialization - Run all of the initializers for the function passes.</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>, definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa5e968db4987e612699b3957b125adf4">invokeFunctionPass</a>.</p>

</div>
</div>

### run() {#a02e592cc8ca8a049fbe052f809514c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::legacy::FunctionPassManager::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>run - Execute all of the passes scheduled for execution.</p>


<p>Keep track of whether any of the passes modifies the function, and if so, return true.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>, definition at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa5e968db4987e612699b3957b125adf4">invokeFunctionPass</a> and <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#adcb87ee7d8b9f08bc82da9cae1c74429">llvm::PlaceSafepointsPass::runImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FPM {#adb33e901a2ec1e394e693ca7c3c3ba4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPassManagerImpl* llvm::legacy::FunctionPassManager::FPM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>.</p>

</div>
</div>

### M {#ad13c4d67e67953011ef9e2a3f34dc9fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* llvm::legacy::FunctionPassManager::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/legacypassmanager-cpp">LegacyPassManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
