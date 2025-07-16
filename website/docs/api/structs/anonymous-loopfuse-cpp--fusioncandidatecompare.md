---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-loopfuse-cpp-/fusioncandidatecompare
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FusionCandidateCompare` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{LoopFuse.cpp}::FusionCandidateCompare { ... }
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9f11701fcbd34a98f7da033c725845">operator()</a> (const FusionCandidate &amp;LHS, const FusionCandidate &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparison functor to sort two Control Flow Equivalent fusion candidates into dominance order. <a href="#aea9f11701fcbd34a98f7da033c725845">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator()() {#aea9f11701fcbd34a98f7da033c725845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::FusionCandidateCompare::operator() (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> &amp; RHS)</td>
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

<p>Comparison functor to sort two Control Flow Equivalent fusion candidates into dominance order.</p>


<p>If LHS dominates RHS and RHS post-dominates LHS, return true; If RHS dominates LHS and LHS post-dominates RHS, return false; If both LHS and RHS are not dominating each other then, non-strictly post dominate check will decide the order of candidates. If RHS non-strictly post dominates LHS then, return true. If LHS non-strictly post dominates RHS then, return false. If both are non-strictly post dominate each other then, level in the post dominator tree will decide the order of candidates.</p>


<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ab73bfd7dc4d5a446db965380e340810e">llvm::DomTreeNodeBase&lt; NodeT &gt;::getLevel</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a90896a5c2c14e27297f4fdb0196e24b3">llvm::nonStrictlyPostDominate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
