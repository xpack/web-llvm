---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/looptraversal
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopTraversal` Class Reference

<p>This class provides the basic blocks traversal order used by passes like <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix">ExecutionDomainFix</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopTraversal { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">llvm/CodeGen/LoopTraversal.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/looptraversal/traversedmbbinfo">TraversedMBBInfo</a>, 4 &gt; <a href="#adb30e4144436f66defa2ce2454e0fde8">TraversalOrder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifies basic blocks that are part of loops and should to be visited twice and returns efficient traversal order for all the blocks. <a href="#adb30e4144436f66defa2ce2454e0fde8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1fcea688cf5f056fe49852f4690cd10">MBBInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; MBBInfo, 4 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7577edd85546c2abaa7f58d5ae1142">LoopTraversal</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adb30e4144436f66defa2ce2454e0fde8">TraversalOrder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87cd9704fc800af5dddb87f26badfb3a">traverse</a> (MachineFunction &amp;MF)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f7e1c4b29321529e6098c173d509e8">isBlockDone</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returens true if the block is ready for its final round of processing. <a href="#ae7f7e1c4b29321529e6098c173d509e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">MBBInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe07efa093639990a2a9f1ae434f7044">MBBInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helps keep track if we proccessed this block and all its predecessors. <a href="#abe07efa093639990a2a9f1ae434f7044">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class provides the basic blocks traversal order used by passes like <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> and <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix">ExecutionDomainFix</a>.</p>


<p>It identifies basic blocks that are part of loops and should to be visited twice and returns efficient traversal order for all the blocks.</p>


<p>We want to visit every instruction in every basic block in order to update it's execution domain or collect clearance information. However, for the clearance calculation, we need to know clearances from all predecessors (including any backedges), therfore we need to visit some blocks twice. As an example, consider the following loop.</p>


<p>PH -&gt; A -&gt; B (xmm&lt;Undef&gt; -&gt; xmm&lt;Def&gt;) -&gt; C -&gt; D -&gt; EXIT ^ | +-------------------------------—+</p>


<p>The iteration order this pass will return is as follows: Optimized: PH A B C A' B' C' D</p>


<p>The basic block order is constructed as follows: Once we finish processing some block, we update the counters in MBBInfos and re-process any successors that are now 'done'. We call a block that is ready for its final round of processing <span class="doxyComputerOutput">done</span> (isBlockDone), e.g. when all predecessor information is known.</p>


<p>Note that a naive traversal order would be to do two complete passes over all basic blocks/instructions, the first for recording clearances, the second for updating clearance based on backedges. However, for functions without backedges, or functions with a lot of straight-line code, and a small loop, that would be a lot of unnecessary work (since only the BBs that are part of the loop require two passes).</p>


<p>E.g., the naive iteration order for the above exmple is as follows: Naive: PH A B C D A' B' C' D'</p>


<p>In the optimized approach we avoid processing D twice, because we can entirely process the predecessors before getting to D.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">LoopTraversal.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TraversalOrder {#adb30e4144436f66defa2ce2454e0fde8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVector&lt;TraversedMBBInfo, 4&gt; llvm::LoopTraversal::TraversalOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifies basic blocks that are part of loops and should to be visited twice and returns efficient traversal order for all the blocks.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">LoopTraversal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### MBBInfoMap {#ab1fcea688cf5f056fe49852f4690cd10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopTraversal::MBBInfoMap =  SmallVector&lt;MBBInfo, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">LoopTraversal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoopTraversal() {#a7c7577edd85546c2abaa7f58d5ae1142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopTraversal::LoopTraversal ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">LoopTraversal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### traverse() {#a87cd9704fc800af5dddb87f26badfb3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopTraversal::TraversalOrder LoopTraversal::traverse (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">LoopTraversal.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/looptraversal-cpp">LoopTraversal.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa22424ba23740b6a748e8d0c239b7e4c">llvm::MachineFunction::getNumBlockIDs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a5418eaa6c605a696a952bf86c829fe71">llvm::ReachingDefAnalysis::init</a> and <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix/#aa90dd7f08ca467a5d6dc3215fb98ee51">llvm::ExecutionDomainFix::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isBlockDone() {#ae7f7e1c4b29321529e6098c173d509e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopTraversal::isBlockDone (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returens true if the block is ready for its final round of processing.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">LoopTraversal.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/looptraversal-cpp">LoopTraversal.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MBBInfos {#abe07efa093639990a2a9f1ae434f7044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBInfoMap llvm::LoopTraversal::MBBInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helps keep track if we proccessed this block and all its predecessors.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">LoopTraversal.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/looptraversal-h">LoopTraversal.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/looptraversal-cpp">LoopTraversal.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
