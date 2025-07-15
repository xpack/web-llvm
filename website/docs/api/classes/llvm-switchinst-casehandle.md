---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/switchinst/casehandle
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CaseHandle` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SwitchInst::CaseHandle { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl">CaseHandleImpl&lt;SwitchInstT, ConstantIntT, BasicBlockT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to a particular switch case. <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b20b4802e769ff737e20dddba9002a">SwitchInst::CaseIteratorImpl&lt; CaseHandle &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dbe9e12034e9179c04df51b96f38958">CaseHandle</a> (SwitchInst *SI, ptrdiff_t Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20138a23cdfbc6a42f6341e55b78005">setValue</a> (ConstantInt *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the new value for current case. <a href="#ab20138a23cdfbc6a42f6341e55b78005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade327bd05bcf154647ea34eed5ddf354">setSuccessor</a> (BasicBlock *S) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the new successor for current case. <a href="#ade327bd05bcf154647ea34eed5ddf354">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 3249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Friends

### SwitchInst::CaseIteratorImpl&lt; CaseHandle &gt; {#a44b20b4802e769ff737e20dddba9002a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/switchinst/caseiteratorimpl">SwitchInst::CaseIteratorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandle">CaseHandle</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CaseHandle() {#a1dbe9e12034e9179c04df51b96f38958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwitchInst::CaseHandle::CaseHandle (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI, ptrdiff_t Index)</td>
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



<p>Definition at line 3254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#a5352cc734b27d0dab237a3da40195ed6">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInst, ConstantInt, BasicBlock &gt;::CaseHandleImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#a4f8a1ef29b555b75f6bcdaa5024b1889">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInst, ConstantInt, BasicBlock &gt;::Index</a> and <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#acba6eb478bcfa1355ae2310be79e0dc5">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInst, ConstantInt, BasicBlock &gt;::SI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setSuccessor() {#ade327bd05bcf154647ea34eed5ddf354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwitchInst::CaseHandle::setSuccessor (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * S)</td>
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

<p>Sets the new successor for current case.</p>

<p>Definition at line 3264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#a80c8a3151e9ef04b1595e222bdfe1cf9">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInst, ConstantInt, BasicBlock &gt;::getSuccessorIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#acba6eb478bcfa1355ae2310be79e0dc5">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInst, ConstantInt, BasicBlock &gt;::SI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a62abc2475d09c01d583ba24a487898fd">llvm::SwitchInst::addCase</a>.</p>

</div>
</div>

### setValue() {#ab20138a23cdfbc6a42f6341e55b78005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwitchInst::CaseHandle::setValue (<a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * V)</td>
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

<p>Sets the new value for current case.</p>

<p>Definition at line 3257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#ab009e4ea0d53969a9f6fb36e3da14517">llvm::SwitchInst::getNumCases</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#a4f8a1ef29b555b75f6bcdaa5024b1889">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInst, ConstantInt, BasicBlock &gt;::Index</a> and <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#acba6eb478bcfa1355ae2310be79e0dc5">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInst, ConstantInt, BasicBlock &gt;::SI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a62abc2475d09c01d583ba24a487898fd">llvm::SwitchInst::addCase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
