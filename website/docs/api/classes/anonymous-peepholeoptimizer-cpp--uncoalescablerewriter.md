---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-peepholeoptimizer-cpp-/uncoalescablerewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UncoalescableRewriter` Class Reference

<p>Helper class to rewrite uncoalescable copy like instructions into new COPY (coalescable friendly) instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{PeepholeOptimizer.cpp}::UncoalescableRewriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac508181ecb468aa9a608f61223e92413">UncoalescableRewriter</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af703b6af11073fc6bb738c43fcbada3e">getNextRewritableSource</a> (RegSubRegPair &amp;Src, RegSubRegPair &amp;Dst) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80be5a98c25adbe31018af1aede45034">RewriteCurrentSource</a> (Register NewReg, unsigned NewSubReg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the current source with <span class="doxyComputerOutput">NewReg</span> and <span class="doxyComputerOutput">NewSubReg</span> if possible. <a href="#a80be5a98c25adbe31018af1aede45034">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982eaef7ceef5f65532a721e32859345">NumDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of defs in the bitcast. <a href="#a982eaef7ceef5f65532a721e32859345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class to rewrite uncoalescable copy like instructions into new COPY (coalescable friendly) instructions.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UncoalescableRewriter() {#ac508181ecb468aa9a608f61223e92413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PeepholeOptimizer.cpp}::UncoalescableRewriter::UncoalescableRewriter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a33607cdfed7a2110695c526b7520d224">anonymous{PeepholeOptimizer.cpp}::Rewriter::Rewriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNextRewritableSource() {#af703b6af11073fc6bb738c43fcbada3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PeepholeOptimizer.cpp}::UncoalescableRewriter::getNextRewritableSource (<a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a16005492b382a6a76abae848b4af2b83">RegSubRegPair</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a16005492b382a6a76abae848b4af2b83">RegSubRegPair</a> &amp; Dst)</td>
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
<dd><p>See <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a3fa829354b3f8b782d40175469540cab">Rewriter::getNextRewritableSource()</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ab1c94ca2fbc3e78fc30069c8d0f01680">All</a> such sources need to be considered rewritable in order to rewrite a uncoalescable copy-like instruction. This method return each definition that must be checked <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> rewritable.</p></dd>
</dl>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#a1ab74e93e550820b697e99a0dc9fdbbd">anonymous{PeepholeOptimizer.cpp}::Rewriter::CopyLike</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/rewriter/#ac58143cbdf601d044e69002face8a19b">anonymous{PeepholeOptimizer.cpp}::Rewriter::CurrentSrcIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>.</p>

</div>
</div>

### RewriteCurrentSource() {#a80be5a98c25adbe31018af1aede45034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PeepholeOptimizer.cpp}::UncoalescableRewriter::RewriteCurrentSource (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, unsigned NewSubReg)</td>
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


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NumDefs {#a982eaef7ceef5f65532a721e32859345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PeepholeOptimizer.cpp}::UncoalescableRewriter::NumDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of defs in the bitcast.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>

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
