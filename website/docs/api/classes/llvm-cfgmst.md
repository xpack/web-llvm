---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cfgmst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CFGMST` Class Template

<p>An union-find based Minimum Spanning Tree for CFG. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class Edge, class BBInfo&gt;
class llvm::CFGMST&lt;Edge, BBInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">llvm/Transforms/Instrumentation/CFGMST.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aadbf6fcebe9363050984331d3b84cc9f">CFGMST</a> (Function &amp;Func, bool InstrumentFuncEntry, bool InstrumentLoopEntries, BranchProbabilityInfo *BPI=nullptr, BlockFrequencyInfo *BFI=nullptr, LoopInfo *LI=nullptr)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6d53cb002b3fe8f7c4b7a7c3323e4c0">dumpEdges</a> (raw_ostream &amp;OS, const Twine &amp;Message) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Edge &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24f7f9f853bca2105355b7637dfefa51">addEdge</a> (BasicBlock *Src, BasicBlock *Dest, uint64_t W)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a267cdc4a586557f3a11db067a56e009d">allEdges</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::unique_ptr&lt; Edge &gt; &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0cb1049742ea64dbd6759f8613806671">allEdges</a> () -&gt; std::vector&lt; std::unique_ptr&lt; Edge &gt; &gt; &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa06eb66d09ca342144d906a13b4d79ef">numEdges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a887ac951e5bafca7f5ba383ccfcb1bfe">bbInfoSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BBInfo &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acbbc178bee3824add820cff379b1e9c2">getBBInfo</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BBInfo *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd77a1566a97b3eb363f266e07204335">findBBInfo</a> (const BasicBlock *BB) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BBInfo *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae74f78ece8f2c28e62e7e1cd2929ac74">findAndCompressGroup</a> (BBInfo *G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab186c33dfd6f51ec2212fb75d1e4929c">unionGroups</a> (const BasicBlock *BB1, const BasicBlock *BB2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac83775d0d9572ce3ca013becfb283ea5">handleCoroSuspendEdge</a> (Edge *E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2bc67452f50b7ab72f58e9aa9878235a">buildEdges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1805a00c72f15c5a30d0d45b2e84a8e9">sortEdgesByWeight</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0092638aad2ba5dc0f1102e9f3527fcb">computeMinimumSpanningTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e564287ab110b152dbd3c9ff1a38d33">validateLoopEntryInstrumentation</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a87f3b4fd07f67b07c88bea3306c63cac">F</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; Edge &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f5c3cf1b796e8a06de4665e74349bf9">AllEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, std::unique_ptr&lt; BBInfo &gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad6e6d6f54fcae7b985c43108e544d274">BBInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28f128873f655594f882b3d9f3989184">ExitBlockFound</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6ac86a1ee9ad8933cbc3f200ad70c4d8">BPI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae4e8af50047472b05574794849e3f9c8">BFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae5bddf2dbfb58bfb02b49900f8f9cf7d">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7025fcc1973663f0accfd2088c124bea">InstrumentFuncEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Edge, class BBInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff0b71da206531be4c46602341427184">InstrumentLoopEntries</a></td>
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

<p>An union-find based Minimum Spanning Tree for CFG.</p>


<p>Implements a Union-find algorithm to compute Minimum Spanning Tree for a given CFG.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CFGMST() {#aadbf6fcebe9363050984331d3b84cc9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CFGMST&lt; Edge, BBInfo &gt;::CFGMST (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Func, bool InstrumentFuncEntry, bool InstrumentLoopEntries, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI=nullptr)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEdge() {#a24f7f9f853bca2105355b7637dfefa51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge &amp; llvm::CFGMST&lt; Edge, BBInfo &gt;::addEdge (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dest, uint64_t W)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#ab74216e0ce40d85e6c843637018ce553">getInstrBB</a>.</p>

</div>
</div>

### allEdges() {#a267cdc4a586557f3a11db067a56e009d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; std::unique_ptr&lt; Edge &gt; &gt; &amp; llvm::CFGMST&lt; Edge, BBInfo &gt;::allEdges ()</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#aab8715e66e20531c058b46a9e22ca221">dumpEdges</a>.</p>

</div>
</div>

### allEdges() {#a0cb1049742ea64dbd6759f8613806671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt; Edge &gt; &gt; &amp; llvm::CFGMST&lt; Edge, BBInfo &gt;::allEdges ()</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### bbInfoSize() {#a887ac951e5bafca7f5ba383ccfcb1bfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::CFGMST&lt; Edge, BBInfo &gt;::bbInfoSize ()</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### dumpEdges() {#af6d53cb002b3fe8f7c4b7a7c3323e4c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CFGMST&lt; Edge, BBInfo &gt;::dumpEdges (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message)</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#acbbc178bee3824add820cff379b1e9c2">llvm::CFGMST&lt; Edge, BBInfo &gt;::getBBInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>

</div>
</div>

### findBBInfo() {#abd77a1566a97b3eb363f266e07204335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBInfo * llvm::CFGMST&lt; Edge, BBInfo &gt;::findBBInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### getBBInfo() {#acbbc178bee3824add820cff379b1e9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBInfo &amp; llvm::CFGMST&lt; Edge, BBInfo &gt;::getBBInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#af6d53cb002b3fe8f7c4b7a7c3323e4c0">llvm::CFGMST&lt; Edge, BBInfo &gt;::dumpEdges</a>.</p>

</div>
</div>

### numEdges() {#aa06eb66d09ca342144d906a13b4d79ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::CFGMST&lt; Edge, BBInfo &gt;::numEdges ()</td>
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



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildEdges() {#a2bc67452f50b7ab72f58e9aa9878235a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CFGMST&lt; Edge, BBInfo &gt;::buildEdges ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### computeMinimumSpanningTree() {#a0092638aad2ba5dc0f1102e9f3527fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CFGMST&lt; Edge, BBInfo &gt;::computeMinimumSpanningTree ()</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### findAndCompressGroup() {#ae74f78ece8f2c28e62e7e1cd2929ac74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBInfo * llvm::CFGMST&lt; Edge, BBInfo &gt;::findAndCompressGroup (BBInfo * G)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### handleCoroSuspendEdge() {#ac83775d0d9572ce3ca013becfb283ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CFGMST&lt; Edge, BBInfo &gt;::handleCoroSuspendEdge (Edge * E)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### sortEdgesByWeight() {#a1805a00c72f15c5a30d0d45b2e84a8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CFGMST&lt; Edge, BBInfo &gt;::sortEdgesByWeight ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### unionGroups() {#ab186c33dfd6f51ec2212fb75d1e4929c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CFGMST&lt; Edge, BBInfo &gt;::unionGroups (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB2)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### validateLoopEntryInstrumentation() {#a4e564287ab110b152dbd3c9ff1a38d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CFGMST&lt; Edge, BBInfo &gt;::validateLoopEntryInstrumentation ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllEdges {#a4f5c3cf1b796e8a06de4665e74349bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Edge&gt; &gt; llvm::CFGMST&lt; Edge, BBInfo &gt;::AllEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### BBInfos {#ad6e6d6f54fcae7b985c43108e544d274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, std::unique_ptr&lt;BBInfo&gt; &gt; llvm::CFGMST&lt; Edge, BBInfo &gt;::BBInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### BFI {#ae4e8af50047472b05574794849e3f9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* const llvm::CFGMST&lt; Edge, BBInfo &gt;::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### BPI {#a6ac86a1ee9ad8933cbc3f200ad70c4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfo* const llvm::CFGMST&lt; Edge, BBInfo &gt;::BPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### ExitBlockFound {#a28f128873f655594f882b3d9f3989184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CFGMST&lt; Edge, BBInfo &gt;::ExitBlockFound = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### F {#a87f3b4fd07f67b07c88bea3306c63cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; llvm::CFGMST&lt; Edge, BBInfo &gt;::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### InstrumentFuncEntry {#a7025fcc1973663f0accfd2088c124bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::CFGMST&lt; Edge, BBInfo &gt;::InstrumentFuncEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### InstrumentLoopEntries {#aff0b71da206531be4c46602341427184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::CFGMST&lt; Edge, BBInfo &gt;::InstrumentLoopEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

### LI {#ae5bddf2dbfb58bfb02b49900f8f9cf7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Edge, class BBInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* const llvm::CFGMST&lt; Edge, BBInfo &gt;::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/cfgmst-h">CFGMST.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
