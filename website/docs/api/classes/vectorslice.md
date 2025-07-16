---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/vectorslice
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VectorSlice` Class Reference

<p>Helper class for "break large PHIs" (visitPHINode). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class VectorSlice { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcfe9b938404c5c07c3c426aca33199b">VectorSlice</a> (Type *Ty, unsigned Idx, unsigned NumElts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef12c412e54fb31aa597199eadc0e866">getSlicedVal</a> (BasicBlock *BB, Value *Inc, StringRef NewValName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Slice <span class="doxyComputerOutput">Inc</span> according to the information contained within this slice. <a href="#aef12c412e54fb31aa597199eadc0e866">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83d46be9cc7330b1ccc1600f7b7c4b51">Ty</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891a7aade567413c2bcf94dc3239fb15">Idx</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1a8f7a1af3bdd7443dedbc655aad350">NumElts</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5fd35a263da73de3e3a0ef18f77ef6c">NewPHI</a> = nullptr</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14a0359fa9814a75543163aed025f43">SlicedVals</a></td>
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

<p>Helper class for "break large PHIs" (visitPHINode).</p>


<p>This represents a slice of a PHI's incoming value, which is made up of:</p>


<ul class="doxyList ">
<li>The type of the slice (Ty)</li>
<li>The index in the incoming value's vector where the slice starts (Idx)</li>
<li>The number of elements in the slice (NumElts). It also keeps track of the NewPHI node inserted for this particular slice.</li>
</ul>

<p>Slice examples: &lt;4 x i64&gt; -&gt; Split into four i64 slices. -&gt; [i64, 0, 1], [i64, 1, 1], [i64, 2, 1], [i64, 3, 1] &lt;5 x i16&gt; -&gt; Split into 2 &lt;2 x i16&gt; slices + a i16 tail. -&gt; [&lt;2 x i16&gt;, 0, 2], [&lt;2 x i16&gt;, 2, 2], [i16, 4, 1]</p>


<p>Definition at line 1902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VectorSlice() {#abcfe9b938404c5c07c3c426aca33199b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorSlice::VectorSlice (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Idx, unsigned NumElts)</td>
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



<p>Definition at line 1904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="#a891a7aade567413c2bcf94dc3239fb15">Idx</a>, <a href="#af1a8f7a1af3bdd7443dedbc655aad350">NumElts</a> and <a href="#a83d46be9cc7330b1ccc1600f7b7c4b51">Ty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSlicedVal() {#aef12c412e54fb31aa597199eadc0e866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * VectorSlice::getSlicedVal (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Inc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> NewValName)</td>
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

<p>Slice <span class="doxyComputerOutput">Inc</span> according to the information contained within this slice.</p>


<p>This is cached, so if called multiple times for the same <span class="doxyComputerOutput">BB</span> &amp; <span class="doxyComputerOutput">Inc</span> pair, it returns the same Sliced value as well.</p>


<p>Note this <em>intentionally</em> does not return the same value for, say, [bb.0, %0] &amp; [bb.1, %0] as:</p>


<ul class="doxyList ">
<li>It could cause issues with dominance (e.g. if bb.1 is seen first, then the value in bb.1 may not be reachable from bb.0 if it's its predecessor.)</li>
<li>We also want to make our extract instructions as local as possible so the DAG has better chances of folding them out. Duplicating them like that is beneficial in that regard.</li>
</ul>

<p>This is both a minor optimization to avoid creating duplicate instructions, but also a requirement for correctness. It is not forbidden for a PHI node to have the same [BB, Val] pair multiple times. If we returned a new value each time, those previously identical pairs would all have different incoming values (from the same block) and it'd cause a "PHI
node has multiple entries for the same basic block with different incoming
values!" verifier error.</p>


<p>Definition at line 1932 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#a891a7aade567413c2bcf94dc3239fb15">Idx</a> and <a href="#af1a8f7a1af3bdd7443dedbc655aad350">NumElts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Idx {#a891a7aade567413c2bcf94dc3239fb15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned VectorSlice::Idx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1908 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#aef12c412e54fb31aa597199eadc0e866">getSlicedVal</a> and <a href="#abcfe9b938404c5c07c3c426aca33199b">VectorSlice</a>.</p>

</div>
</div>

### NewPHI {#ae5fd35a263da73de3e3a0ef18f77ef6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode* VectorSlice::NewPHI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1910 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>

</div>
</div>

### NumElts {#af1a8f7a1af3bdd7443dedbc655aad350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned VectorSlice::NumElts = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1909 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#aef12c412e54fb31aa597199eadc0e866">getSlicedVal</a> and <a href="#abcfe9b938404c5c07c3c426aca33199b">VectorSlice</a>.</p>

</div>
</div>

### Ty {#a83d46be9cc7330b1ccc1600f7b7c4b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* VectorSlice::Ty = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1907 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#abcfe9b938404c5c07c3c426aca33199b">VectorSlice</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SlicedVals {#ad14a0359fa9814a75543163aed025f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;std::pair&lt;BasicBlock *, Value *&gt;, Value *&gt; VectorSlice::SlicedVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1953 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp">AMDGPUCodeGenPrepare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
