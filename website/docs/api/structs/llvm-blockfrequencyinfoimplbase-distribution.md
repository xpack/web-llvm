---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/blockfrequencyinfoimplbase/distribution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Distribution` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/distribution">Distribution</a> of unscaled probability weight. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BlockFrequencyInfoImplBase::Distribution { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3009a397a01cea6f6903433da6683224">WeightList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/weight">Weight</a>, 4 &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10318535dafa46543d1c1d2b67301cc8">Distribution</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6973243d687017c549e35834347f34">addLocal</a> (const BlockNode &amp;Node, uint64_t Amount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86fec7279ee04ded4052cdc9a867ea9">addExit</a> (const BlockNode &amp;Node, uint64_t Amount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4f138ccfef4b11927a51fed0aa4fbe">addBackedge</a> (const BlockNode &amp;Node, uint64_t Amount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac24f62f9ac4bff8273ed15798ea650e8">normalize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Normalize the distribution. <a href="#ac24f62f9ac4bff8273ed15798ea650e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3e6031928976b8ddbc3e58c6d9fd5f">add</a> (const BlockNode &amp;Node, uint64_t Amount, Weight::DistType Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3009a397a01cea6f6903433da6683224">WeightList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4eb3a7c89dcc532ee7aee4e2029674">Weights</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Individual successor weights. <a href="#a5e4eb3a7c89dcc532ee7aee4e2029674">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf226952008495c98bd9d9652b25cfd8">Total</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sum of all weights. <a href="#aaf226952008495c98bd9d9652b25cfd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9359948311bce04a3628b0db4376b77">DidOverflow</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <em>Total</em> did overflow. <a href="#ad9359948311bce04a3628b0db4376b77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/distribution">Distribution</a> of unscaled probability weight.</p>


<p><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/distribution">Distribution</a> of unscaled probability weight to a set of successors.</p>


<p>This class collates the successor edge weights for later processing.</p>


<p><em>DidOverflow</em> indicates whether <em>Total</em> did overflow while adding to the distribution. It should never overflow twice.</p>


<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### WeightList {#a3009a397a01cea6f6903433da6683224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlockFrequencyInfoImplBase::Distribution::WeightList =  SmallVector&lt;Weight, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Distribution() {#a10318535dafa46543d1c1d2b67301cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BlockFrequencyInfoImplBase::Distribution::Distribution ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addBackedge() {#a1f4f138ccfef4b11927a51fed0aa4fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BlockFrequencyInfoImplBase::Distribution::addBackedge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a> &amp; Node, uint64_t Amount)</td>
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



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/weight/#a929fa9e894467d1c9c49957ffcbb0a67afcb3a90b3bb851da0270e36b0ae1b2ea">llvm::BlockFrequencyInfoImplBase::Weight::Backedge</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#aac32cd773a37b10c8f835459a23ac606">llvm::BlockFrequencyInfoImplBase::addToDist</a>.</p>

</div>
</div>

### addExit() {#ac86fec7279ee04ded4052cdc9a867ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BlockFrequencyInfoImplBase::Distribution::addExit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a> &amp; Node, uint64_t Amount)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/weight/#a929fa9e894467d1c9c49957ffcbb0a67a3b492c1efd3ffe17229812461887a04f">llvm::BlockFrequencyInfoImplBase::Weight::Exit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#aac32cd773a37b10c8f835459a23ac606">llvm::BlockFrequencyInfoImplBase::addToDist</a>.</p>

</div>
</div>

### addLocal() {#afe6973243d687017c549e35834347f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BlockFrequencyInfoImplBase::Distribution::addLocal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a> &amp; Node, uint64_t Amount)</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/weight/#a929fa9e894467d1c9c49957ffcbb0a67aecdba21d3e55eb968b68883d0653abbc">llvm::BlockFrequencyInfoImplBase::Weight::Local</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#aac32cd773a37b10c8f835459a23ac606">llvm::BlockFrequencyInfoImplBase::addToDist</a> and <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#af8aa6262fff3f09a8e2076d7a76e1628">llvm::BlockFrequencyInfoImplBase::adjustLoopHeaderMass</a>.</p>

</div>
</div>

### normalize() {#ac24f62f9ac4bff8273ed15798ea650e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Distribution::normalize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Normalize the distribution.</p>


<p>Combines multiple edges to the same <em><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/weight/#a7d49b2704586051c51172cc77d4104b3">Weight::TargetNode</a></em> and scales down so that <em>Total</em> fits into 32-bits.</p>


<p>This is linear in the size of <em>Weights</em>. For the vast majority of cases, adjacent edge weights are combined by sorting <a href="#a3009a397a01cea6f6903433da6683224">WeightList</a> and combining adjacent weights. However, for very large edge lists an auxiliary hash table is used.</p>


<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#a6750f9ed35f65ba11b4c3c00d9d4fb4d">combineWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="#ad9359948311bce04a3628b0db4376b77">DidOverflow</a>, <a href="#ac24f62f9ac4bff8273ed15798ea650e8">normalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#af7b0ebc6a85830e67121d86801e54d8f">shiftRightAndRound</a>, <a href="#aaf226952008495c98bd9d9652b25cfd8">Total</a> and <a href="#a5e4eb3a7c89dcc532ee7aee4e2029674">Weights</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-blockfrequencyinfoimpl-cpp-/ditheringdistributer/#a09b288abbf093b5ee513ce99b8921c72">anonymous{BlockFrequencyInfoImpl.cpp}::DitheringDistributer::DitheringDistributer</a> and <a href="#ac24f62f9ac4bff8273ed15798ea650e8">normalize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### add() {#a7a3e6031928976b8ddbc3e58c6d9fd5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Distribution::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a> &amp; Node, uint64_t Amount, <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/weight/#a929fa9e894467d1c9c49957ffcbb0a67">Weight::DistType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DidOverflow {#ad9359948311bce04a3628b0db4376b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::Distribution::DidOverflow = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether <em>Total</em> did overflow.</p>

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#ac24f62f9ac4bff8273ed15798ea650e8">normalize</a>.</p>

</div>
</div>

### Total {#aaf226952008495c98bd9d9652b25cfd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BlockFrequencyInfoImplBase::Distribution::Total = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sum of all weights.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-blockfrequencyinfoimpl-cpp-/ditheringdistributer/#a09b288abbf093b5ee513ce99b8921c72">anonymous{BlockFrequencyInfoImpl.cpp}::DitheringDistributer::DitheringDistributer</a> and <a href="#ac24f62f9ac4bff8273ed15798ea650e8">normalize</a>.</p>

</div>
</div>

### Weights {#a5e4eb3a7c89dcc532ee7aee4e2029674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeightList llvm::BlockFrequencyInfoImplBase::Distribution::Weights</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Individual successor weights.</p>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#af8aa6262fff3f09a8e2076d7a76e1628">llvm::BlockFrequencyInfoImplBase::adjustLoopHeaderMass</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#aaa2c0a25aeaf519f9df55f422331f0db">llvm::BlockFrequencyInfoImplBase::distributeIrrLoopHeaderMass</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#adda9f21a68ad40aac3ee4e0bf3afa31d">llvm::BlockFrequencyInfoImplBase::distributeMass</a> and <a href="#ac24f62f9ac4bff8273ed15798ea650e8">normalize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
