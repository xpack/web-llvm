---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcloopinstrformprep-cpp-/ppcloopinstrformprep
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCLoopInstrFormPrep` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> class - This class is used to implement most global optimizations. <a href="/web-llvm/docs/api/classes/llvm/functionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635dff4b525cccd46d367555c76cbd9b">PPCLoopInstrFormPrep</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7e4f499c94d07a9782f75740906ffd5">PPCLoopInstrFormPrep</a> (PPCTargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7a99b42cdfd0cf468d8963f557fe15">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a1f7a99b42cdfd0cf468d8963f557fe15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1182a1362bef2929d09ce054e8fa5d">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass. <a href="#a8d1182a1362bef2929d09ce054e8fa5d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bb2a6f3cadbdf474fda027864071f99">runOnLoop</a> (Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25df23b052ab353473317ca9535ee2aa">alreadyPrepared</a> (Loop *L, Instruction *MemI, const SCEV *BasePtrStartSCEV, const SCEV *BasePtrIncSCEV, PrepForm Form)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if required PHI node is already exist in <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> <span class="doxyComputerOutput">L</span>. <a href="#a25df23b052ab353473317ca9535ee2aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1204dfc80b689ab2cfca0acb06272fe9">getNodeForInc</a> (Loop *L, Instruction *MemI, const SCEV *BasePtrIncSCEV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the value which defines the increment <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> <span class="doxyComputerOutput">BasePtrIncSCEV</span>. <a href="#a1204dfc80b689ab2cfca0acb06272fe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad665cb1f1a04463a4585cd8dc6b6635c">chainCommoning</a> (Loop *L, SmallVector&lt; Bucket, 16 &gt; &amp;Buckets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common chains to reuse offsets for a loop to reduce register pressure. <a href="#ad665cb1f1a04463a4585cd8dc6b6635c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660c93b866af83a04d29d03b67e3eef4">prepareBasesForCommoningChains</a> (Bucket &amp;BucketChain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find out the potential commoning chains and their bases. <a href="#a660c93b866af83a04d29d03b67e3eef4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a2f635f1370ec41be0ad2b1c729354">rewriteLoadStoresForCommoningChains</a> (Loop *L, Bucket &amp;Bucket, SmallSet&lt; BasicBlock *, 16 &gt; &amp;BBChanged)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite load/store according to the common chains. <a href="#a70a2f635f1370ec41be0ad2b1c729354">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b3cd356b9f535b60366bfda134c55b">collectCandidates</a> (Loop *L, std::function&lt; bool(const Instruction *, Value *, const Type *)&gt; isValidCandidate, std::function&lt; bool(const SCEV *)&gt; isValidDiff, unsigned MaxCandidateNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect condition matched(<span class="doxyComputerOutput">isValidCandidate()</span> returns true) candidates in <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> <span class="doxyComputerOutput">L</span>. <a href="#a63b3cd356b9f535b60366bfda134c55b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705ad9c56e6917d1a2317232eab3d927">addOneCandidate</a> (Instruction *MemI, const SCEV *LSCEV, SmallVector&lt; Bucket, 16 &gt; &amp;Buckets, std::function&lt; bool(const SCEV *)&gt; isValidDiff, unsigned MaxCandidateNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a candidate to candidates <span class="doxyComputerOutput">Buckets</span> if diff between candidate and one base in <span class="doxyComputerOutput">Buckets</span> matches <span class="doxyComputerOutput">isValidDiff</span>. <a href="#a705ad9c56e6917d1a2317232eab3d927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab645740accfd1aa247ff3189033d0509">updateFormPrep</a> (Loop *L, SmallVector&lt; Bucket, 16 &gt; &amp;Buckets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare all candidates in <span class="doxyComputerOutput">Buckets</span> for update form. <a href="#ab645740accfd1aa247ff3189033d0509">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab48fc9235d7ca18ffbb7c933be3a37d7">dispFormPrep</a> (Loop *L, SmallVector&lt; Bucket, 16 &gt; &amp;Buckets, PrepForm Form)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare all candidates in <span class="doxyComputerOutput">Buckets</span> for displacement form, now for ds/dq. <a href="#ab48fc9235d7ca18ffbb7c933be3a37d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b390b7d6f0524d2eafd390cd1427f97">prepareBaseForDispFormChain</a> (Bucket &amp;BucketChain, PrepForm Form)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare for one chain <span class="doxyComputerOutput">BucketChain</span>, find the best base element and update all other elements in <span class="doxyComputerOutput">BucketChain</span> accordingly. <a href="#a0b390b7d6f0524d2eafd390cd1427f97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acefaf61a2d69796e198b22226306d4e3">prepareBaseForUpdateFormChain</a> (Bucket &amp;BucketChain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepare for one chain <span class="doxyComputerOutput">BucketChain</span>, find the best base element and update all other elements in <span class="doxyComputerOutput">BucketChain</span> accordingly. <a href="#acefaf61a2d69796e198b22226306d4e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc577bc464404eb4dea98254af382dcc">rewriteLoadStores</a> (Loop *L, Bucket &amp;BucketChain, SmallSet&lt; BasicBlock *, 16 &gt; &amp;BBChanged, PrepForm Form)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite load/store instructions in <span class="doxyComputerOutput">BucketChain</span> according to preparation. <a href="#abc577bc464404eb4dea98254af382dcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ea9d4e6203806ef851075e1ceaba0b">rewriteForBase</a> (Loop *L, const SCEVAddRecExpr *BasePtrSCEV, Instruction *BaseMemI, bool CanPreInc, PrepForm Form, SCEVExpander &amp;SCEVE, SmallPtrSet&lt; Value *, 16 &gt; &amp;DeletedPtrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite for the base load/store of a chain. <a href="#a01ea9d4e6203806ef851075e1ceaba0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f60384e6658d3aec900a308b0ef8b7">rewriteForBucketElement</a> (std::pair&lt; Instruction *, Instruction * &gt; Base, const BucketElement &amp;Element, Value *OffToBase, SmallPtrSet&lt; Value *, 16 &gt; &amp;DeletedPtrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite for the other load/stores of a chain according to the new <span class="doxyComputerOutput">Base</span>. <a href="#a68f60384e6658d3aec900a308b0ef8b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab9fa7c617c2e37b7da9323417826f14">TM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa016995df833a413e0aea9bfc0dbbc71">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9131312b67333fccbaa6e8aa3d53ab5">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abb8f221293da678ccc7d7bbc4f77bc">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6acf46a8c119504a8480f74f3b3df17">SE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6262994b83787b1d122d53aba58fa92f">PreserveLCSSA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6832fa300c3b91ffa47cea9489819ea">HasCandidateForPrepare</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45551aac6d2739298245e89f823b16f7">SuccPrepCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Successful preparation number for Update/DS/DQ form in all inner most loops. <a href="#a45551aac6d2739298245e89f823b16f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af95a2e7303cb6b2495e794c0c5735911">ID</a> = 0</td>
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


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCLoopInstrFormPrep() {#a635dff4b525cccd46d367555c76cbd9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::PPCLoopInstrFormPrep ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#af95a2e7303cb6b2495e794c0c5735911">ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc9b8c53e964842915e0ef5373b38827">llvm::initializePPCLoopInstrFormPrepPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1c5781563265f0f6f21b8cdcbd638639">llvm::createPPCLoopInstrFormPrepPass</a>.</p>

</div>
</div>

### PPCLoopInstrFormPrep() {#ab7e4f499c94d07a9782f75740906ffd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::PPCLoopInstrFormPrep (<a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> &amp; TM)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#af95a2e7303cb6b2495e794c0c5735911">ID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc9b8c53e964842915e0ef5373b38827">llvm::initializePPCLoopInstrFormPrepPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a1f7a99b42cdfd0cf468d8963f557fe15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>.</p>

</div>
</div>

### runOnFunction() {#a8d1182a1362bef2929d09ce054e8fa5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#af94c014e968489e96c7d4353a84ad7f5">llvm::Pass::getAnalysisIfAvailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e3d3c6d4e33a4f5ca579ee7939f0349">llvm::LCSSAID</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a0b4a511579939b07831db90c3fc98996">llvm::Pass::mustPreserveAnalysisID</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addOneCandidate() {#a705ad9c56e6917d1a2317232eab3d927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCLoopInstrFormPrep::addOneCandidate (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MemI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LSCEV, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a>, 16 &gt; &amp; Buckets, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *)&gt; isValidDiff, unsigned MaxCandidateNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a candidate to candidates <span class="doxyComputerOutput">Buckets</span> if diff between candidate and one base in <span class="doxyComputerOutput">Buckets</span> matches <span class="doxyComputerOutput">isValidDiff</span>.</p>

<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### alreadyPrepared() {#a25df23b052ab353473317ca9535ee2aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::alreadyPrepared (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MemI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * BasePtrStartSCEV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * BasePtrIncSCEV, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcloopinstrformprep-cpp-/#ace83c0b2fc7de869e3b41692c29c0fda">PrepForm</a> Form)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if required PHI node is already exist in <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> <span class="doxyComputerOutput">L</span>.</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### chainCommoning() {#ad665cb1f1a04463a4585cd8dc6b6635c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::chainCommoning (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a>, 16 &gt; &amp; Buckets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common chains to reuse offsets for a loop to reduce register pressure.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### collectCandidates() {#a63b3cd356b9f535b60366bfda134c55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Bucket, 16 &gt; PPCLoopInstrFormPrep::collectCandidates (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *)&gt; isValidCandidate, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *)&gt; isValidDiff, unsigned MaxCandidateNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect condition matched(<span class="doxyComputerOutput">isValidCandidate()</span> returns true) candidates in <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> <span class="doxyComputerOutput">L</span>.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### dispFormPrep() {#ab48fc9235d7ca18ffbb7c933be3a37d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::dispFormPrep (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a>, 16 &gt; &amp; Buckets, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcloopinstrformprep-cpp-/#ace83c0b2fc7de869e3b41692c29c0fda">PrepForm</a> Form)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare all candidates in <span class="doxyComputerOutput">Buckets</span> for displacement form, now for ds/dq.</p>

<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### getNodeForInc() {#a1204dfc80b689ab2cfca0acb06272fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PPCLoopInstrFormPrep::getNodeForInc (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MemI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * BasePtrIncSCEV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the value which defines the increment <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> <span class="doxyComputerOutput">BasePtrIncSCEV</span>.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### prepareBaseForDispFormChain() {#a0b390b7d6f0524d2eafd390cd1427f97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::prepareBaseForDispFormChain (<a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a> &amp; BucketChain, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcloopinstrformprep-cpp-/#ace83c0b2fc7de869e3b41692c29c0fda">PrepForm</a> Form)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare for one chain <span class="doxyComputerOutput">BucketChain</span>, find the best base element and update all other elements in <span class="doxyComputerOutput">BucketChain</span> accordingly.</p>


<p><span class="doxyComputerOutput">Form</span> is used to find the best base element. If success, best base element must be stored as the first element of <span class="doxyComputerOutput">BucketChain</span>. Return false if no base element found, otherwise return true.</p>


<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### prepareBaseForUpdateFormChain() {#acefaf61a2d69796e198b22226306d4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::prepareBaseForUpdateFormChain (<a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a> &amp; BucketChain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare for one chain <span class="doxyComputerOutput">BucketChain</span>, find the best base element and update all other elements in <span class="doxyComputerOutput">BucketChain</span> accordingly.</p>


<p>If success, best base element must be stored as the first element of <span class="doxyComputerOutput">BucketChain</span>. Return false if no base element found, otherwise return true.</p>


<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### prepareBasesForCommoningChains() {#a660c93b866af83a04d29d03b67e3eef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::prepareBasesForCommoningChains (<a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a> &amp; BucketChain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find out the potential commoning chains and their bases.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### rewriteForBase() {#a01ea9d4e6203806ef851075e1ceaba0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Instruction *, Instruction * &gt; PPCLoopInstrFormPrep::rewriteForBase (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * BasePtrSCEV, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * BaseMemI, bool CanPreInc, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcloopinstrformprep-cpp-/#ace83c0b2fc7de869e3b41692c29c0fda">PrepForm</a> Form, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; SCEVE, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt; &amp; DeletedPtrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite for the base load/store of a chain.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### rewriteForBucketElement() {#a68f60384e6658d3aec900a308b0ef8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * PPCLoopInstrFormPrep::rewriteForBucketElement (std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; Base, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucketelement">BucketElement</a> &amp; Element, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OffToBase, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt; &amp; DeletedPtrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite for the other load/stores of a chain according to the new <span class="doxyComputerOutput">Base</span>.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### rewriteLoadStores() {#abc577bc464404eb4dea98254af382dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::rewriteLoadStores (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a> &amp; BucketChain, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt; &amp; BBChanged, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcloopinstrformprep-cpp-/#ace83c0b2fc7de869e3b41692c29c0fda">PrepForm</a> Form)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite load/store instructions in <span class="doxyComputerOutput">BucketChain</span> according to preparation.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### rewriteLoadStoresForCommoningChains() {#a70a2f635f1370ec41be0ad2b1c729354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::rewriteLoadStoresForCommoningChains (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a> &amp; Bucket, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt; &amp; BBChanged)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite load/store according to the common chains.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### runOnLoop() {#a6bb2a6f3cadbdf474fda027864071f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::runOnLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### updateFormPrep() {#ab645740accfd1aa247ff3189033d0509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCLoopInstrFormPrep::updateFormPrep (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcloopinstrformprep-cpp-/bucket">Bucket</a>, 16 &gt; &amp; Buckets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prepare all candidates in <span class="doxyComputerOutput">Buckets</span> for update form.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DT {#ae9131312b67333fccbaa6e8aa3d53ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### HasCandidateForPrepare {#ac6832fa300c3b91ffa47cea9489819ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::HasCandidateForPrepare</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### LI {#a7abb8f221293da678ccc7d7bbc4f77bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### PreserveLCSSA {#a6262994b83787b1d122d53aba58fa92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::PreserveLCSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### SE {#ac6acf46a8c119504a8480f74f3b3df17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### ST {#aa016995df833a413e0aea9bfc0dbbc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCSubtarget* anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### SuccPrepCount {#a45551aac6d2739298245e89f823b16f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::SuccPrepCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Successful preparation number for Update/DS/DQ form in all inner most loops.</p>


<p>One successful preparation will put one common base out of loop, this may leads to register presure like LICM does. Make sure total preparation number can be controlled by option.</p>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

### TM {#aab9fa7c617c2e37b7da9323417826f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCTargetMachine* anonymous{PPCLoopInstrFormPrep.cpp}::PPCLoopInstrFormPrep::TM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#af95a2e7303cb6b2495e794c0c5735911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char PPCLoopInstrFormPrep::ID = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a>.</p>


<p>Referenced by <a href="#a635dff4b525cccd46d367555c76cbd9b">PPCLoopInstrFormPrep</a> and <a href="#ab7e4f499c94d07a9782f75740906ffd5">PPCLoopInstrFormPrep</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcloopinstrformprep-cpp">PPCLoopInstrFormPrep.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
