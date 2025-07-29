---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/passmanagerbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PassManagerBase` Class

<p><a href="/web-llvm/docs/api/classes/llvm/passmanagerbase">PassManagerBase</a> - An abstract interface to allow code to add passes to a pass manager without having to hard-code what kind of pass manager it is. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PassManagerBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager">FunctionPassManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager">FunctionPassManager</a> manages FunctionPasses. <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager">PassManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager">PassManager</a> manages ModulePassManagers. <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e678f968a8f574109cb78eee4d3d756">~PassManagerBase</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce2eacfa52640d3a2feb2d46d561b85">add</a> (Pass *P)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a pass to the queue of passes to run. <a href="#a2ce2eacfa52640d3a2feb2d46d561b85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/passmanagerbase">PassManagerBase</a> - An abstract interface to allow code to add passes to a pass manager without having to hard-code what kind of pass manager it is.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~PassManagerBase() {#a4e678f968a8f574109cb78eee4d3d756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">legacy::PassManagerBase::~PassManagerBase ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a2ce2eacfa52640d3a2feb2d46d561b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::legacy::PassManagerBase::add (<a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a pass to the queue of passes to run.</p>


<p>This passes ownership of the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> to the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a>. When the <a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a> is destroyed, the pass will be destroyed as well, so there is no need to delete the pass. This may even destroy the pass right away if it is found to be redundant. This implies that all passes MUST be allocated with 'new'.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">LegacyPassManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
