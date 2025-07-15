---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/runtimecheckingptrgroup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RuntimeCheckingPtrGroup` Struct Reference

<p>A grouping of pointers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RuntimeCheckingPtrGroup { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">llvm/Analysis/LoopAccessAnalysis.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b4d56d5d22cdc51b3d993501d57816b">RuntimeCheckingPtrGroup</a> (unsigned Index, const RuntimePointerChecking &amp;RtCheck)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new pointer checking group containing a single pointer, with index <span class="doxyComputerOutput">Index</span> in RtCheck. <a href="#a4b4d56d5d22cdc51b3d993501d57816b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a9ec6fa93583e6d3806bc859a9ee94e">addPointer</a> (unsigned Index, const RuntimePointerChecking &amp;RtCheck)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to add the pointer recorded in RtCheck at index <span class="doxyComputerOutput">Index</span> to this pointer checking group. <a href="#a2a9ec6fa93583e6d3806bc859a9ee94e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c9789fd8d2eac348a6b65fad0d10d5f">addPointer</a> (unsigned Index, const SCEV *Start, const SCEV *End, unsigned AS, bool NeedsFreeze, ScalarEvolution &amp;SE)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c6c88b61312f50f0375ba8637590f5e">High</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression which represents the upper bound of all the pointers in this group. <a href="#a4c6c88b61312f50f0375ba8637590f5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac0830f0932768a1e5059fa696f1be1">Low</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression which represents the lower bound of all the pointers in this group. <a href="#afac0830f0932768a1e5059fa696f1be1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa344a8f8a75f8d9a256c7f74b2de0a2d">Members</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indices of all the pointers that constitute this grouping. <a href="#aa344a8f8a75f8d9a256c7f74b2de0a2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ba5cdd25cec4e4080aa882557b708d">AddressSpace</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Address space of the involved pointers. <a href="#a09ba5cdd25cec4e4080aa882557b708d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40187863ff624003227feed476669a14">NeedsFreeze</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the pointer needs to be frozen after expansion, e.g. <a href="#a40187863ff624003227feed476669a14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A grouping of pointers.</p>


<p>A single memcheck is required between two groups.</p>


<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RuntimeCheckingPtrGroup() {#a4b4d56d5d22cdc51b3d993501d57816b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeCheckingPtrGroup::RuntimeCheckingPtrGroup (unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking">RuntimePointerChecking</a> &amp; RtCheck)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new pointer checking group containing a single pointer, with index <span class="doxyComputerOutput">Index</span> in RtCheck.</p>

<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#a09ba5cdd25cec4e4080aa882557b708d">AddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21b1f2d0effa0506f01cb146823de6a2">llvm::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#a4c6c88b61312f50f0375ba8637590f5e">High</a>, <a href="#afac0830f0932768a1e5059fa696f1be1">Low</a>, <a href="#aa344a8f8a75f8d9a256c7f74b2de0a2d">Members</a> and <a href="#a40187863ff624003227feed476669a14">NeedsFreeze</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPointer() {#a2a9ec6fa93583e6d3806bc859a9ee94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RuntimeCheckingPtrGroup::addPointer (unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking">RuntimePointerChecking</a> &amp; RtCheck)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to add the pointer recorded in RtCheck at index <span class="doxyComputerOutput">Index</span> to this pointer checking group.</p>


<p>We can only add a pointer to a checking group if we will still be able to get the upper and lower bounds of the check. Returns true in case of success, false otherwise.</p>


<p>Declaration at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#a2a9ec6fa93583e6d3806bc859a9ee94e">addPointer</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#aa6ad96a1c2591e0a61c92e0be5776978">llvm::RuntimePointerChecking::Pointers</a>.</p>


<p>Referenced by <a href="#a2a9ec6fa93583e6d3806bc859a9ee94e">addPointer</a>.</p>

</div>
</div>

### addPointer() {#a3c9789fd8d2eac348a6b65fad0d10d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RuntimeCheckingPtrGroup::addPointer (unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * End, unsigned AS, bool NeedsFreeze, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="#a09ba5cdd25cec4e4080aa882557b708d">AddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#abfce07b67c63527dc293c398e5629066">getMinFromExprs</a>, <a href="#a4c6c88b61312f50f0375ba8637590f5e">High</a>, <a href="#afac0830f0932768a1e5059fa696f1be1">Low</a>, <a href="#aa344a8f8a75f8d9a256c7f74b2de0a2d">Members</a> and <a href="#a40187863ff624003227feed476669a14">NeedsFreeze</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddressSpace {#a09ba5cdd25cec4e4080aa882557b708d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RuntimeCheckingPtrGroup::AddressSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Address space of the involved pointers.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a3c9789fd8d2eac348a6b65fad0d10d5f">addPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a> and <a href="#a4b4d56d5d22cdc51b3d993501d57816b">RuntimeCheckingPtrGroup</a>.</p>

</div>
</div>

### High {#a4c6c88b61312f50f0375ba8637590f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* llvm::RuntimeCheckingPtrGroup::High</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression which represents the upper bound of all the pointers in this group.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a3c9789fd8d2eac348a6b65fad0d10d5f">addPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a> and <a href="#a4b4d56d5d22cdc51b3d993501d57816b">RuntimeCheckingPtrGroup</a>.</p>

</div>
</div>

### Low {#afac0830f0932768a1e5059fa696f1be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* llvm::RuntimeCheckingPtrGroup::Low</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression which represents the lower bound of all the pointers in this group.</p>

<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a3c9789fd8d2eac348a6b65fad0d10d5f">addPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a> and <a href="#a4b4d56d5d22cdc51b3d993501d57816b">RuntimeCheckingPtrGroup</a>.</p>

</div>
</div>

### Members {#aa344a8f8a75f8d9a256c7f74b2de0a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 2&gt; llvm::RuntimeCheckingPtrGroup::Members</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indices of all the pointers that constitute this grouping.</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a3c9789fd8d2eac348a6b65fad0d10d5f">addPointer</a> and <a href="#a4b4d56d5d22cdc51b3d993501d57816b">RuntimeCheckingPtrGroup</a>.</p>

</div>
</div>

### NeedsFreeze {#a40187863ff624003227feed476669a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RuntimeCheckingPtrGroup::NeedsFreeze = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the pointer needs to be frozen after expansion, e.g.</p>


<p>because it may be poison outside the loop.</p>


<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="#a3c9789fd8d2eac348a6b65fad0d10d5f">addPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a> and <a href="#a4b4d56d5d22cdc51b3d993501d57816b">RuntimeCheckingPtrGroup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
