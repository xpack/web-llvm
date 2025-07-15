---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-ppcbranchcoalescing-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{PPCBranchCoalescing.cpp}` Namespace Reference

<p>Improve scheduling by coalescing branches that depend on the same condition. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace anonymous{PPCBranchCoalescing.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing">PPCBranchCoalescing</a></td>
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

<p>Improve scheduling by coalescing branches that depend on the same condition.</p>


<p>This pass looks for blocks that are guarded by the same branch condition and attempts to merge the blocks together. Such opportunities arise from the expansion of select statements in the IR.</p>


<p>This pass does not handle implicit operands on branch statements. In order to run on targets that use implicit operands, changes need to be made in the canCoalesceBranch and canMerge methods.</p>


<p>Example: the following LLVM IR</p>



<pre><code>%test = icmp eq i32 %x 0
%tmp1 = select i1 %test, double %a, double 2.000000e-03
%tmp2 = select i1 %test, double %b, double 5.000000e-03
</code></pre>


<p>expands to the following machine code:</p>


<p>bb.0: derived from LLVM BB entry liveins: f1 f3 x6 &lt;SNIP1&gt; %0 = COPY f1; F8RC:%0 %5 = CMPLWI killed %4, 0; CRRC:%5 GPRC:%4 %8 = LXSDX zero8, killed %7, implicit rm; mem:LD8[<a href="/web-llvm/docs/api/classes/llvm/constantpool">ConstantPool</a>] F8RC:%8 G8RC:%7 BCC 76, %5, &lt;bb.2&gt;; CRRC:%5 Successors according to CFG: bb.1(?%) bb.2(?%)</p>


<p>bb.1: derived from LLVM BB entry Predecessors according to CFG: bb.0 Successors according to CFG: bb.2(?%)</p>


<p>bb.2: derived from LLVM BB entry Predecessors according to CFG: bb.0 bb.1 %9 = PHI %8, &lt;bb.1&gt;, %0, &lt;bb.0&gt;; F8RC:%9,%8,%0 &lt;SNIP2&gt; BCC 76, %5, &lt;bb.4&gt;; CRRC:%5 Successors according to CFG: bb.3(?%) bb.4(?%)</p>


<p>bb.3: derived from LLVM BB entry Predecessors according to CFG: bb.2 Successors according to CFG: bb.4(?%)</p>


<p>bb.4: derived from LLVM BB entry Predecessors according to CFG: bb.2 bb.3 %13 = PHI %12, &lt;bb.3&gt;, %2, &lt;bb.2&gt;; F8RC:%13,%12,%2 &lt;SNIP3&gt; BLR8 implicit lr8, implicit rm, implicit f1</p>


<p>When this pattern is detected, branch coalescing will try to collapse it by moving code in bb.2 to bb.0 and/or bb.4 and removing bb.3.</p>


<p>If all conditions are meet, IR should collapse to:</p>


<p>bb.0: derived from LLVM BB entry liveins: f1 f3 x6 &lt;SNIP1&gt; %0 = COPY f1; F8RC:%0 %5 = CMPLWI killed %4, 0; CRRC:%5 GPRC:%4 %8 = LXSDX zero8, killed %7, implicit rm; mem:LD8[<a href="/web-llvm/docs/api/classes/llvm/constantpool">ConstantPool</a>] F8RC:%8 G8RC:%7 &lt;SNIP2&gt; BCC 76, %5, &lt;bb.4&gt;; CRRC:%5 Successors according to CFG: bb.1(0x2aaaaaaa / 0x80000000 = 33.33%) bb.4(0x55555554 / 0x80000000 = 66.67%)</p>


<p>bb.1: derived from LLVM BB entry Predecessors according to CFG: bb.0 Successors according to CFG: bb.4(0x40000000 / 0x80000000 = 50.00%)</p>


<p>bb.4: derived from LLVM BB entry Predecessors according to CFG: bb.0 bb.1 %9 = PHI %8, &lt;bb.1&gt;, %0, &lt;bb.0&gt;; F8RC:%9,%8,%0 %13 = PHI %12, &lt;bb.1&gt;, %2, &lt;bb.0&gt;; F8RC:%13,%12,%2 &lt;SNIP3&gt; BLR8 implicit lr8, implicit rm, implicit f1</p>


<p>Branch Coalescing does not split blocks, it moves everything in the same direction ensuring it does not break use/definition semantics.</p>


<p>PHI nodes and its corresponding use instructions are moved to its successor block if there are no uses within the successor block PHI nodes. PHI node ordering cannot be assumed.</p>


<p>Non-PHI can be moved up to the predecessor basic block or down to the successor basic block following any PHI instructions. Whether it moves up or down depends on whether the register(s) defined in the instructions are used in current block or in any PHI instructions at the beginning of the successor block.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
