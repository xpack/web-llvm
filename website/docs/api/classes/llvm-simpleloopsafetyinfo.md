---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/simpleloopsafetyinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SimpleLoopSafetyInfo` Class

<p>Simple and conservative implementation of <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> that can give false-positive answers to its queries in order to avoid complicated analysis. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SimpleLoopSafetyInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">llvm/Analysis/MustExecute.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Captures loop safety information. <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa597e2048da52105c845e3402b082f5b">blockMayThrow</a> (const BasicBlock *BB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff the block <span class="doxyComputerOutput">BB</span> potentially may throw exception. <a href="#aa597e2048da52105c845e3402b082f5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1b6a065ad4fde175bf904917241cba9">anyBlockMayThrow</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff any block of the loop for which this info is contains an instruction that may throw or otherwise exit abnormally. <a href="#aa1b6a065ad4fde175bf904917241cba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a262c2df9639d3f71b8d2a8158b819809">computeLoopSafetyInfo</a> (const Loop *CurLoop) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes safety information for a loop checks loop body &amp; header for the possibility of may throw exception, it takes <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> and loop as argument. <a href="#a262c2df9639d3f71b8d2a8158b819809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d72ea03ecc07b164934986286ea086d">isGuaranteedToExecute</a> (const Instruction &amp;Inst, const DominatorTree *DT, const Loop *CurLoop) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction in a loop is guaranteed to execute at least once. <a href="#a0d72ea03ecc07b164934986286ea086d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed1484cb025091a2969839d8eb6c193">MayThrow</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a08377118b2a44fe912cf7451b46412">HeaderMayThrow</a> = false</td>
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

<p>Simple and conservative implementation of <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> that can give false-positive answers to its queries in order to avoid complicated analysis.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### anyBlockMayThrow() {#aa1b6a065ad4fde175bf904917241cba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimpleLoopSafetyInfo::anyBlockMayThrow ()</td>
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

<p>Returns true iff any block of the loop for which this info is contains an instruction that may throw or otherwise exit abnormally.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>Referenced by <a href="#aa597e2048da52105c845e3402b082f5b">blockMayThrow</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a02e1ff75cab81386059f88d395054b1c">llvm::isSafeToUnrollAndJam</a>.</p>

</div>
</div>

### blockMayThrow() {#aa597e2048da52105c845e3402b082f5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimpleLoopSafetyInfo::blockMayThrow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Returns true iff the block <span class="doxyComputerOutput">BB</span> potentially may throw exception.</p>


<p>It can be false-positive in cases when we want to avoid complex analysis.</p>


<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>Reference <a href="#aa1b6a065ad4fde175bf904917241cba9">anyBlockMayThrow</a>.</p>

</div>
</div>

### computeLoopSafetyInfo() {#a262c2df9639d3f71b8d2a8158b819809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SimpleLoopSafetyInfo::computeLoopSafetyInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurLoop)</td>
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

<p>Computes safety information for a loop checks loop body &amp; header for the possibility of may throw exception, it takes <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> and loop as argument.</p>


<p>Updates safety information in <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a> argument. Note: This is defined to clear and reinitialize an already initialized <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo">LoopSafetyInfo</a>. Some callers rely on this fact.</p>


<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BlockT, LoopT &gt;::blocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a183e3a3a68925c5689cd2149c940f59e">llvm::LoopSafetyInfo::computeBlockColors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac94e1f7398df9df2508957f58a82279a">llvm::LoopBase&lt; BlockT, LoopT &gt;::getBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abff5a423c1f45e23958dde8ee695c9a9">llvm::isGuaranteedToTransferExecutionToSuccessor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#aa4c6b9df27c53571f2a5d32e59f07a4d">isMustExecuteIn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a02e1ff75cab81386059f88d395054b1c">llvm::isSafeToUnrollAndJam</a>.</p>

</div>
</div>

### isGuaranteedToExecute() {#a0d72ea03ecc07b164934986286ea086d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SimpleLoopSafetyInfo::isGuaranteedToExecute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * CurLoop)</td>
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

<p>Returns true if the instruction in a loop is guaranteed to execute at least once.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a0937bbe895c7ed05d32c861b0f9e0f97">llvm::LoopSafetyInfo::allLoopPathsLeadToBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#aa4c6b9df27c53571f2a5d32e59f07a4d">isMustExecuteIn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HeaderMayThrow {#a4a08377118b2a44fe912cf7451b46412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SimpleLoopSafetyInfo::HeaderMayThrow = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### MayThrow {#abed1484cb025091a2969839d8eb6c193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SimpleLoopSafetyInfo::MayThrow = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
