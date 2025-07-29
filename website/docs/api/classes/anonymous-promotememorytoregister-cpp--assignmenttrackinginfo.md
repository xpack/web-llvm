---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AssignmentTrackingInfo` Class

<p>Helper for updating assignment tracking debug info when promoting allocas. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab80aaa2bd158207080b9e7345a12fce3">init</a> (AllocaInst *AI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92fba2b8745329ee14995b36cf720f68">updateForDeletedStore</a> (StoreInst *ToDelete, DIBuilder &amp;DIB, SmallSet&lt; DbgAssignIntrinsic *, 8 &gt; *DbgAssignsToDelete, SmallSet&lt; DbgVariableRecord *, 8 &gt; *DVRAssignsToDelete) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update assignment tracking debug info given for the to-be-deleted store <span class="doxyComputerOutput">ToDelete</span> that stores to this alloca. <a href="#a92fba2b8745329ee14995b36cf720f68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56429811b5f786d2947ef28afce6b73e">updateForNewPhi</a> (PHINode *NewPhi, DIBuilder &amp;DIB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update assignment tracking debug info given for the newly inserted PHI <span class="doxyComputerOutput">NewPhi</span>. <a href="#a56429811b5f786d2947ef28afce6b73e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60f37f9638cd763faec254fc8a46bdf2">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3a4632779c2492c794b8df418b434e">empty</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c2d07a1a4daca7f60646b49b8b4a8ef">DbgAssigns</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DbgAssignIntrinsics linked to the alloca with at most one per variable fragment. <a href="#a8c2d07a1a4daca7f60646b49b8b4a8ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1b73ae0309bbe931c361a6e697a27b">DVRAssigns</a></td>
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

<p>Helper for updating assignment tracking debug info when promoting allocas.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### clear() {#a60f37f9638cd763faec254fc8a46bdf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::clear ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### empty() {#abc3a4632779c2492c794b8df418b434e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::empty ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### init() {#ab80aaa2bd158207080b9e7345a12fce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::init (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/at/#a3c90899e8f022656e511630de42b916c">llvm::at::getAssignmentMarkers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#aa992dd7420a71df6149dd3437c949245">llvm::at::getDVRAssignmentMarkers</a> and <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>.</p>

</div>
</div>

### updateForDeletedStore() {#a92fba2b8745329ee14995b36cf720f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::updateForDeletedStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * ToDelete, <a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; DIB, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic">DbgAssignIntrinsic</a> *, 8 &gt; * DbgAssignsToDelete, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *, 8 &gt; * DVRAssignsToDelete)</td>
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

<p>Update assignment tracking debug info given for the to-be-deleted store <span class="doxyComputerOutput">ToDelete</span> that stores to this alloca.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallset/#ae04ad615dfdd885e85cbddda146787c6">llvm::SmallSet&lt; T, N, C &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-promotememorytoregister-cpp-/#a9d4100416db594644cb6cd161b245636">anonymous{PromoteMemoryToRegister.cpp}::createDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b2a153b655ed78a07468297eb4c6256">llvm::for_each</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#a3c90899e8f022656e511630de42b916c">llvm::at::getAssignmentMarkers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#aa992dd7420a71df6149dd3437c949245">llvm::at::getDVRAssignmentMarkers</a> and <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>.</p>

</div>
</div>

### updateForNewPhi() {#a56429811b5f786d2947ef28afce6b73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::updateForNewPhi (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * NewPhi, <a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; DIB)</td>
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

<p>Update assignment tracking debug info given for the newly inserted PHI <span class="doxyComputerOutput">NewPhi</span>.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DbgAssigns {#a8c2d07a1a4daca7f60646b49b8b4a8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DbgVariableIntrinsic *&gt; anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::DbgAssigns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DbgAssignIntrinsics linked to the alloca with at most one per variable fragment.</p>


<p>(i.e. not be a comprehensive set if there are multiple dbg.assigns for one variable fragment).</p>


<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### DVRAssigns {#abf1b73ae0309bbe931c361a6e697a27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DbgVariableRecord *&gt; anonymous{PromoteMemoryToRegister.cpp}::AssignmentTrackingInfo::DVRAssigns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
