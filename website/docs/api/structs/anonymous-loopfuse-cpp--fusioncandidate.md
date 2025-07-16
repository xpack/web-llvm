---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-loopfuse-cpp-/fusioncandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FusionCandidate` Struct Reference

<p>This class is used to represent a candidate for loop fusion. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{LoopFuse.cpp}::FusionCandidate { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a> (Loop *L, DominatorTree &amp;DT, const PostDominatorTree *PDT, OptimizationRemarkEmitter &amp;ORE, TTI::PeelingPreferences PP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if all members of the class are valid. <a href="#a516640cfe68e1b63251dd7d87c3adaa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that all members are in sync with the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> object. <a href="#a3d79b9453c59df95d134afd2902af5b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05db6896587c2826dd97fa443a8e260">getEntryBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the entry block for this fusion candidate. <a href="#af05db6896587c2826dd97fa443a8e260">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bfc82c01ea0b8dc8261f4017d429287">updateAfterPeeling</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After Peeling the loop is modified quite a bit, hence all of the Blocks need to be updated accordingly. <a href="#a8bfc82c01ea0b8dc8261f4017d429287">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9422bc7988a8d974f4477d56a94b58">getNonLoopBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a guarded loop, get the successor of the guard that is not in the loop. <a href="#a3f9422bc7988a8d974f4477d56a94b58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4392517c22c653d59c5deead6ccfffb7">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f677960b0a306e237ee9fa3b838639d">isEligibleForFusion</a> (ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if a fusion candidate (representing a loop) is eligible for fusion. <a href="#a1f677960b0a306e237ee9fa3b838639d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2737ea2a00e0c202291f2231f8068830">invalidate</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf0c5f361b960c4583e75dd47287b09">reportInvalidCandidate</a> (llvm::Statistic &amp;Stat) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache of parts of the loop used throughout loop fusion. <a href="#adc8c271beba911eb5fa45d229afc43c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca41b3283414bbe68b662ea7afacafb">Header</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Header of the loop this candidate represents. <a href="#a1ca41b3283414bbe68b662ea7afacafb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef066e3bf3c078c1a230bcb65860219">ExitingBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocks in the loop that exit the loop. <a href="#a1ef066e3bf3c078c1a230bcb65860219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa216f276b8d0c8a38aa269b0087d98ea">ExitBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The successor block of this loop (where the exiting blocks go to) <a href="#aa216f276b8d0c8a38aa269b0087d98ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf4116319c12ae1bd66f99b21137070">Latch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Latch of the loop. <a href="#a1cf4116319c12ae1bd66f99b21137070">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4cd533fe25fea3f12356b39ebd7922c">L</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop that this fusion candidate represents. <a href="#ad4cd533fe25fea3f12356b39ebd7922c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a385ce5cbf5dba34bbefaf04c2895d516">MemReads</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector of instructions in this loop that read from memory. <a href="#a385ce5cbf5dba34bbefaf04c2895d516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a460b3a88f2ee12615defbeed51ffa425">MemWrites</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector of instructions in this loop that write to memory. <a href="#a460b3a88f2ee12615defbeed51ffa425">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac933e75323cc3809335d479ef4305898">Valid</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Are all of the members of this fusion candidate still valid. <a href="#ac933e75323cc3809335d479ef4305898">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac941dd6cb39bf15cf131fdb815204058">GuardBranch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Guard branch of the loop, if it exists. <a href="#ac941dd6cb39bf15cf131fdb815204058">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences">TTI::PeelingPreferences</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f8aa5307907f3efaf56c2b2548f2aa">PP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Peeling Paramaters of the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>. <a href="#a17f8aa5307907f3efaf56c2b2548f2aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab44ba37ede787300af76d483de2cced2">AbleToPeel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can you Peel this <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>? <a href="#ab44ba37ede787300af76d483de2cced2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232c3295dd67d2e2c2c758b3c8f4c04d">Peeled</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has this loop been Peeled. <a href="#a232c3295dd67d2e2c2c758b3c8f4c04d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e172dbe8ae6427270033a0864a9fcb">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dominator and PostDominator trees are needed for the <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidatecompare">FusionCandidateCompare</a> function, required by <a href="/web-llvm/docs/api/namespaces/anonymous-loopfuse-cpp-/#a8974eb1cd0d99da470c576c3b3388bf6">FusionCandidateSet</a> to determine where the <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> should be inserted into the set. <a href="#ac9e172dbe8ae6427270033a0864a9fcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ead8eb312bdb4310bfab1487d623dc">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db53013438babe322cef241c773389a">ORE</a></td>
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

<p>This class is used to represent a candidate for loop fusion.</p>


<p>When it is constructed, it checks the conditions for loop fusion to ensure that it represents a valid candidate. It caches several parts of a loop that are used throughout loop fusion (e.g., loop preheader, loop header, etc) instead of continually querying the underlying <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> to retrieve these values. It is assumed these will not change throughout loop fusion.</p>


<p>The invalidate method should be used to indicate that the <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> is no longer a valid candidate for fusion. Similarly, the <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid()</a> method can be used to ensure that the <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> is still valid for fusion.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FusionCandidate() {#a0a8bbbf9ec7c7e88b08172862188e530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopFuse.cpp}::FusionCandidate::FusionCandidate (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/peelingpreferences">TTI::PeelingPreferences</a> PP)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="#ab44ba37ede787300af76d483de2cced2">AbleToPeel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3aea1e78510aa7469457aade10808e51">llvm::canPeel</a>, <a href="#ac9e172dbe8ae6427270033a0864a9fcb">DT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aa216f276b8d0c8a38aa269b0087d98ea">ExitBlock</a>, <a href="#a1ef066e3bf3c078c1a230bcb65860219">ExitingBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>, <a href="#ac941dd6cb39bf15cf131fdb815204058">GuardBranch</a>, <a href="#a1ca41b3283414bbe68b662ea7afacafb">Header</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad4cd533fe25fea3f12356b39ebd7922c">L</a>, <a href="#a1cf4116319c12ae1bd66f99b21137070">Latch</a>, <a href="#a385ce5cbf5dba34bbefaf04c2895d516">MemReads</a>, <a href="#a460b3a88f2ee12615defbeed51ffa425">MemWrites</a>, <a href="#a7db53013438babe322cef241c773389a">ORE</a>, <a href="#a83ead8eb312bdb4310bfab1487d623dc">PDT</a>, <a href="#a232c3295dd67d2e2c2c758b3c8f4c04d">Peeled</a>, <a href="#a17f8aa5307907f3efaf56c2b2548f2aa">PP</a>, <a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codemoverutils-cpp/#a134ee84d052b18522fd2d6bca5cf0778">reportInvalidCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> and <a href="#ac933e75323cc3809335d479ef4305898">Valid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a4392517c22c653d59c5deead6ccfffb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void anonymous{LoopFuse.cpp}::FusionCandidate::dump ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa216f276b8d0c8a38aa269b0087d98ea">ExitBlock</a>, <a href="#a1ef066e3bf3c078c1a230bcb65860219">ExitingBlock</a>, <a href="#af05db6896587c2826dd97fa443a8e260">getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#ac941dd6cb39bf15cf131fdb815204058">GuardBranch</a>, <a href="#a1ca41b3283414bbe68b662ea7afacafb">Header</a>, <a href="#a1cf4116319c12ae1bd66f99b21137070">Latch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a>.</p>

</div>
</div>

### getEntryBlock() {#af05db6896587c2826dd97fa443a8e260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * anonymous{LoopFuse.cpp}::FusionCandidate::getEntryBlock ()</td>
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

<p>Get the entry block for this fusion candidate.</p>


<p>If this fusion candidate represents a guarded loop, the entry block is the loop guard block. If it represents an unguarded loop, the entry block is the preheader of the loop.</p>


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="#ac941dd6cb39bf15cf131fdb815204058">GuardBranch</a> and <a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a>.</p>


<p>Referenced by <a href="#a4392517c22c653d59c5deead6ccfffb7">dump</a>.</p>

</div>
</div>

### getNonLoopBlock() {#a3f9422bc7988a8d974f4477d56a94b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * anonymous{LoopFuse.cpp}::FusionCandidate::getNonLoopBlock ()</td>
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

<p>Given a guarded loop, get the successor of the guard that is not in the loop.</p>


<p>This method returns the successor of the loop guard that is not located within the loop (i.e., the successor of the guard that is not the preheader). This method is only valid for guarded loops.</p>


<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac941dd6cb39bf15cf131fdb815204058">GuardBranch</a>, <a href="#a232c3295dd67d2e2c2c758b3c8f4c04d">Peeled</a> and <a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a>.</p>

</div>
</div>

### isEligibleForFusion() {#a1f677960b0a306e237ee9fa3b838639d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::FusionCandidate::isEligibleForFusion (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Determine if a fusion candidate (representing a loop) is eligible for fusion.</p>


<p>Note that this only checks whether a single loop can be fused - it does not check whether it is <em>legal</em> to fuse two loops together.</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aa216f276b8d0c8a38aa269b0087d98ea">ExitBlock</a>, <a href="#a1ef066e3bf3c078c1a230bcb65860219">ExitingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a91ac801aa45c78e0d0edbc36115ef054">llvm::ScalarEvolution::hasLoopInvariantBackedgeTakenCount</a>, <a href="#a1ca41b3283414bbe68b662ea7afacafb">Header</a>, <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>, <a href="#ad4cd533fe25fea3f12356b39ebd7922c">L</a>, <a href="#a1cf4116319c12ae1bd66f99b21137070">Latch</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a>.</p>

</div>
</div>

### isValid() {#a516640cfe68e1b63251dd7d87c3adaa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::FusionCandidate::isValid ()</td>
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

<p>Check if all members of the class are valid.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="#aa216f276b8d0c8a38aa269b0087d98ea">ExitBlock</a>, <a href="#a1ef066e3bf3c078c1a230bcb65860219">ExitingBlock</a>, <a href="#a1ca41b3283414bbe68b662ea7afacafb">Header</a>, <a href="#ad4cd533fe25fea3f12356b39ebd7922c">L</a>, <a href="#a1cf4116319c12ae1bd66f99b21137070">Latch</a>, <a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a> and <a href="#ac933e75323cc3809335d479ef4305898">Valid</a>.</p>


<p>Referenced by <a href="#a1f677960b0a306e237ee9fa3b838639d">isEligibleForFusion</a> and <a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a>.</p>

</div>
</div>

### updateAfterPeeling() {#a8bfc82c01ea0b8dc8261f4017d429287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::FusionCandidate::updateAfterPeeling ()</td>
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

<p>After Peeling the loop is modified quite a bit, hence all of the Blocks need to be updated accordingly.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="#aa216f276b8d0c8a38aa269b0087d98ea">ExitBlock</a>, <a href="#a1ef066e3bf3c078c1a230bcb65860219">ExitingBlock</a>, <a href="#a1ca41b3283414bbe68b662ea7afacafb">Header</a>, <a href="#ad4cd533fe25fea3f12356b39ebd7922c">L</a>, <a href="#a1cf4116319c12ae1bd66f99b21137070">Latch</a>, <a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a> and <a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a>.</p>

</div>
</div>

### verify() {#a3d79b9453c59df95d134afd2902af5b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::FusionCandidate::verify ()</td>
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

<p>Verify that all members are in sync with the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> object.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa216f276b8d0c8a38aa269b0087d98ea">ExitBlock</a>, <a href="#a1ef066e3bf3c078c1a230bcb65860219">ExitingBlock</a>, <a href="#a1ca41b3283414bbe68b662ea7afacafb">Header</a>, <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>, <a href="#ad4cd533fe25fea3f12356b39ebd7922c">L</a>, <a href="#a1cf4116319c12ae1bd66f99b21137070">Latch</a> and <a href="#adc8c271beba911eb5fa45d229afc43c7">Preheader</a>.</p>


<p>Referenced by <a href="#a8bfc82c01ea0b8dc8261f4017d429287">updateAfterPeeling</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### invalidate() {#a2737ea2a00e0c202291f2231f8068830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopFuse.cpp}::FusionCandidate::invalidate ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

### reportInvalidCandidate() {#a9bf0c5f361b960c4583e75dd47287b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::FusionCandidate::reportInvalidCandidate (<a href="/web-llvm/docs/api/namespaces/llvm/#a6412c3ea6550f1aeab7571b6d38a2bf3">llvm::Statistic</a> &amp; Stat)</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AbleToPeel {#ab44ba37ede787300af76d483de2cced2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::FusionCandidate::AbleToPeel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can you Peel this <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>?</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>.</p>

</div>
</div>

### DT {#ac9e172dbe8ae6427270033a0864a9fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{LoopFuse.cpp}::FusionCandidate::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dominator and PostDominator trees are needed for the <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidatecompare">FusionCandidateCompare</a> function, required by <a href="/web-llvm/docs/api/namespaces/anonymous-loopfuse-cpp-/#a8974eb1cd0d99da470c576c3b3388bf6">FusionCandidateSet</a> to determine where the <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate">FusionCandidate</a> should be inserted into the set.</p>


<p>These are used to establish ordering of the FusionCandidates based on dominance.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>.</p>

</div>
</div>

### ExitBlock {#aa216f276b8d0c8a38aa269b0087d98ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{LoopFuse.cpp}::FusionCandidate::ExitBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The successor block of this loop (where the exiting blocks go to)</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a4392517c22c653d59c5deead6ccfffb7">dump</a>, <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>, <a href="#a1f677960b0a306e237ee9fa3b838639d">isEligibleForFusion</a>, <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>, <a href="#a8bfc82c01ea0b8dc8261f4017d429287">updateAfterPeeling</a> and <a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a>.</p>

</div>
</div>

### ExitingBlock {#a1ef066e3bf3c078c1a230bcb65860219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{LoopFuse.cpp}::FusionCandidate::ExitingBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocks in the loop that exit the loop.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a4392517c22c653d59c5deead6ccfffb7">dump</a>, <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>, <a href="#a1f677960b0a306e237ee9fa3b838639d">isEligibleForFusion</a>, <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>, <a href="#a8bfc82c01ea0b8dc8261f4017d429287">updateAfterPeeling</a> and <a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a>.</p>

</div>
</div>

### GuardBranch {#ac941dd6cb39bf15cf131fdb815204058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst* anonymous{LoopFuse.cpp}::FusionCandidate::GuardBranch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Guard branch of the loop, if it exists.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a4392517c22c653d59c5deead6ccfffb7">dump</a>, <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>, <a href="#af05db6896587c2826dd97fa443a8e260">getEntryBlock</a> and <a href="#a3f9422bc7988a8d974f4477d56a94b58">getNonLoopBlock</a>.</p>

</div>
</div>

### Header {#a1ca41b3283414bbe68b662ea7afacafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{LoopFuse.cpp}::FusionCandidate::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Header of the loop this candidate represents.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a4392517c22c653d59c5deead6ccfffb7">dump</a>, <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>, <a href="#a1f677960b0a306e237ee9fa3b838639d">isEligibleForFusion</a>, <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>, <a href="#a8bfc82c01ea0b8dc8261f4017d429287">updateAfterPeeling</a> and <a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a>.</p>

</div>
</div>

### L {#ad4cd533fe25fea3f12356b39ebd7922c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopFuse.cpp}::FusionCandidate::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop that this fusion candidate represents.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>, <a href="#a1f677960b0a306e237ee9fa3b838639d">isEligibleForFusion</a>, <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>, <a href="#a8bfc82c01ea0b8dc8261f4017d429287">updateAfterPeeling</a> and <a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a>.</p>

</div>
</div>

### Latch {#a1cf4116319c12ae1bd66f99b21137070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{LoopFuse.cpp}::FusionCandidate::Latch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Latch of the loop.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a4392517c22c653d59c5deead6ccfffb7">dump</a>, <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>, <a href="#a1f677960b0a306e237ee9fa3b838639d">isEligibleForFusion</a>, <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>, <a href="#a8bfc82c01ea0b8dc8261f4017d429287">updateAfterPeeling</a> and <a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a>.</p>

</div>
</div>

### MemReads {#a385ce5cbf5dba34bbefaf04c2895d516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 16&gt; anonymous{LoopFuse.cpp}::FusionCandidate::MemReads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector of instructions in this loop that read from memory.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>.</p>

</div>
</div>

### MemWrites {#a460b3a88f2ee12615defbeed51ffa425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 16&gt; anonymous{LoopFuse.cpp}::FusionCandidate::MemWrites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector of instructions in this loop that write to memory.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>.</p>

</div>
</div>

### ORE {#a7db53013438babe322cef241c773389a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter&amp; anonymous{LoopFuse.cpp}::FusionCandidate::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>.</p>

</div>
</div>

### PDT {#a83ead8eb312bdb4310bfab1487d623dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PostDominatorTree* anonymous{LoopFuse.cpp}::FusionCandidate::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>.</p>

</div>
</div>

### Peeled {#a232c3295dd67d2e2c2c758b3c8f4c04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::FusionCandidate::Peeled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has this loop been Peeled.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a> and <a href="#a3f9422bc7988a8d974f4477d56a94b58">getNonLoopBlock</a>.</p>

</div>
</div>

### PP {#a17f8aa5307907f3efaf56c2b2548f2aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::PeelingPreferences anonymous{LoopFuse.cpp}::FusionCandidate::PP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Peeling Paramaters of the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>.</p>

</div>
</div>

### Preheader {#adc8c271beba911eb5fa45d229afc43c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{LoopFuse.cpp}::FusionCandidate::Preheader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache of parts of the loop used throughout loop fusion.</p>


<p>These should not need to change throughout the analysis and transformation. These parts are cached to avoid repeatedly looking up in the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> class. Preheader of the loop this candidate represents</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a4392517c22c653d59c5deead6ccfffb7">dump</a>, <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a>, <a href="#af05db6896587c2826dd97fa443a8e260">getEntryBlock</a>, <a href="#a3f9422bc7988a8d974f4477d56a94b58">getNonLoopBlock</a>, <a href="#a1f677960b0a306e237ee9fa3b838639d">isEligibleForFusion</a>, <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>, <a href="#a8bfc82c01ea0b8dc8261f4017d429287">updateAfterPeeling</a> and <a href="#a3d79b9453c59df95d134afd2902af5b2">verify</a>.</p>

</div>
</div>

### Valid {#ac933e75323cc3809335d479ef4305898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopFuse.cpp}::FusionCandidate::Valid</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Are all of the members of this fusion candidate still valid.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopfuse-cpp">LoopFuse.cpp</a>.</p>


<p>Referenced by <a href="#a0a8bbbf9ec7c7e88b08172862188e530">FusionCandidate</a> and <a href="#a516640cfe68e1b63251dd7d87c3adaa1">isValid</a>.</p>

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
