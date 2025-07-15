---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-peepholeoptimizer-cpp-/copyrewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CopyRewriter` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter">Rewriter</a> for COPY instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{PeepholeOptimizer.cpp}::CopyRewriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad38fdd50746fc9bc7e8f08e886415d5">CopyRewriter</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1010de8183acda10ae33d13c5168dd19">~CopyRewriter</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a7bff7d1f79439d9cef76fd17c6688">getNextRewritableSource</a> (RegSubRegPair &amp;Src, RegSubRegPair &amp;Dst) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next rewritable source (SrcReg, SrcSubReg) and the related value that it affects (DstReg, DstSubReg). <a href="#af6a7bff7d1f79439d9cef76fd17c6688">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50cda2940b3e3a92753c912202296de4">RewriteCurrentSource</a> (Register NewReg, unsigned NewSubReg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the current source with <span class="doxyComputerOutput">NewReg</span> and <span class="doxyComputerOutput">NewSubReg</span> if possible. <a href="#a50cda2940b3e3a92753c912202296de4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter">Rewriter</a> for COPY instructions.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CopyRewriter() {#aad38fdd50746fc9bc7e8f08e886415d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PeepholeOptimizer.cpp}::CopyRewriter::CopyRewriter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a33607cdfed7a2110695c526b7520d224">anonymous{PeepholeOptimizer.cpp}::Rewriter::Rewriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CopyRewriter() {#a1010de8183acda10ae33d13c5168dd19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{PeepholeOptimizer.cpp}::CopyRewriter::~CopyRewriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNextRewritableSource() {#af6a7bff7d1f79439d9cef76fd17c6688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PeepholeOptimizer.cpp}::CopyRewriter::getNextRewritableSource (<a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a16005492b382a6a76abae848b4af2b83">RegSubRegPair</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a16005492b382a6a76abae848b4af2b83">RegSubRegPair</a> &amp; Dst)</td>
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

<p>Get the next rewritable source (SrcReg, SrcSubReg) and the related value that it affects (DstReg, DstSubReg).</p>


<p>A source is considered rewritable if its register class and the register class of the related DstReg may not be register coalescer friendly. In other words, given a copy-like instruction not all the arguments may be returned at rewritable source, since some arguments are none to be register coalescer friendly.</p>


<p>Each call of this method moves the current source to the next rewritable source. For instance, let CopyLike be the instruction to rewrite. CopyLike has one definition and one source: dst.dstSubIdx = CopyLike src.srcSubIdx.</p>


<p>The first call will give the first rewritable source, i.e., the only source this instruction has: (SrcReg, SrcSubReg) = (src, srcSubIdx). This source defines the whole definition, i.e., (DstReg, DstSubReg) = (dst, dstSubIdx).</p>


<p>The second and subsequent calls will return false, as there is only one rewritable source.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if a rewritable source has been found, false otherwise. The output arguments are valid if and only if true is returned.</p></dd>
</dl>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a1ab74e93e550820b697e99a0dc9fdbbd">anonymous{PeepholeOptimizer.cpp}::Rewriter::CopyLike</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#ac58143cbdf601d044e69002face8a19b">anonymous{PeepholeOptimizer.cpp}::Rewriter::CurrentSrcIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>.</p>

</div>
</div>

### RewriteCurrentSource() {#a50cda2940b3e3a92753c912202296de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PeepholeOptimizer.cpp}::CopyRewriter::RewriteCurrentSource (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, unsigned NewSubReg)</td>
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


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
