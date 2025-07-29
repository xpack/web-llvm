---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-peepholeoptimizer-cpp-/regsequencerewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RegSequenceRewriter` Class

<p>Specialized rewriter for REG_SEQUENCE instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{PeepholeOptimizer.cpp}::RegSequenceRewriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter">Rewriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to query instructions amenable to copy rewriting. <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87532e5082e8fff97e3e6b62104c244a">RegSequenceRewriter</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67bc5de34066daeefa8468bc983e737">getNextRewritableSource</a> (RegSubRegPair &amp;Src, RegSubRegPair &amp;Dst) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1e6780b2cde967f55f56868b46c01a1">RewriteCurrentSource</a> (Register NewReg, unsigned NewSubReg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the current source with <span class="doxyComputerOutput">NewReg</span> and <span class="doxyComputerOutput">NewSubReg</span> if possible. <a href="#ad1e6780b2cde967f55f56868b46c01a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Specialized rewriter for REG_SEQUENCE instruction.</p>

<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegSequenceRewriter() {#a87532e5082e8fff97e3e6b62104c244a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PeepholeOptimizer.cpp}::RegSequenceRewriter::RegSequenceRewriter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a33607cdfed7a2110695c526b7520d224">anonymous{PeepholeOptimizer.cpp}::Rewriter::Rewriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNextRewritableSource() {#af67bc5de34066daeefa8468bc983e737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PeepholeOptimizer.cpp}::RegSequenceRewriter::getNextRewritableSource (<a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a16005492b382a6a76abae848b4af2b83">RegSubRegPair</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a16005492b382a6a76abae848b4af2b83">RegSubRegPair</a> &amp; Dst)</td>
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




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a3fa829354b3f8b782d40175469540cab">Rewriter::getNextRewritableSource()</a> Here <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a1ab74e93e550820b697e99a0dc9fdbbd">CopyLike</a> has the following form: dst = REG_SEQUENCE Src1.src1SubIdx, subIdx1, Src2.src2SubIdx, subIdx2. Each call will return a different source, walking <a href="/web-llvm/docs/api/namespaces/llvm/#a873403a2506ac332f62ad4c2d7dc1835">all</a> the <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a40cc6a0e0895fa564ee013923209aa85">available</a> source.</p></dd>
</dl>


<p>The first call returns: (SrcReg, SrcSubReg) = (Src1, src1SubIdx). (DstReg, DstSubReg) = (dst, subIdx1).</p>


<p>The second call returns: (SrcReg, SrcSubReg) = (Src2, src2SubIdx). (DstReg, DstSubReg) = (dst, subIdx2).</p>


<p>And so on, until all the sources have been traversed, then it returns false.</p>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a1ab74e93e550820b697e99a0dc9fdbbd">anonymous{PeepholeOptimizer.cpp}::Rewriter::CopyLike</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#ac58143cbdf601d044e69002face8a19b">anonymous{PeepholeOptimizer.cpp}::Rewriter::CurrentSrcIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>.</p>

</div>
</div>

### RewriteCurrentSource() {#ad1e6780b2cde967f55f56868b46c01a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PeepholeOptimizer.cpp}::RegSequenceRewriter::RewriteCurrentSource (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, unsigned NewSubReg)</td>
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

<p>Rewrite the current source with <span class="doxyComputerOutput">NewReg</span> and <span class="doxyComputerOutput">NewSubReg</span> if possible.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the rewriting was possible, false otherwise.</p></dd>
</dl>


<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a1ab74e93e550820b697e99a0dc9fdbbd">anonymous{PeepholeOptimizer.cpp}::Rewriter::CopyLike</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#ac58143cbdf601d044e69002face8a19b">anonymous{PeepholeOptimizer.cpp}::Rewriter::CurrentSrcIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a001d31fcea92be51d2999826b806606f">llvm::MachineOperand::setSubReg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
