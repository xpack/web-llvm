---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PtrState.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/dependencyanalysis-h">DependencyAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarc-h">ObjCARC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">llvm/Analysis/ObjCARCAnalysisUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcinstkind-h">llvm/Analysis/ObjCARCInstKind.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcutil-h">llvm/Analysis/ObjCARCUtil.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;iterator&gt;
#include &lt;utility&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306d">Sequence</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c7014451484f9784e68d42412d1b9c">MergeSeqs</a> (Sequence A, Sequence B, bool TopDown)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"objc-arc-ptr-state"</td>
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


<div class="doxySectionDef">

## Functions

### MergeSeqs() {#a01c7014451484f9784e68d42412d1b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Sequence MergeSeqs (<a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306d">Sequence</a> A, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306d">Sequence</a> B, bool TopDown)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da8902051603b385fb4587620a0650b4f7">llvm::objcarc::S_CanRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daff34dfb06d8316048c533bac105bfbe6">llvm::objcarc::S_MovableRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da6e431a7ec0fee74cc2ae9a79bd965122">llvm::objcarc::S_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daac10e4a5d85a196bcb2578c2700f3ff3">llvm::objcarc::S_Retain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daadd43d88dff4dfb5f9620f2151822b64">llvm::objcarc::S_Stop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da8e1b337cadca1fc899129d307df7d68e">llvm::objcarc::S_Use</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#adf8b72d488312f8c7229b2beee07e28d">llvm::objcarc::PtrState::Merge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"objc-arc-ptr-state"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
