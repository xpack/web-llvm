---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCPtrTracker` Class

<p>Builds <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> for each BB of the function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SafepointIRVerifier.cpp}::GCPtrTracker { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9910e63c423b9ed6890d2b551142ef92">GCPtrTracker</a> (const Function &amp;F, const DominatorTree &amp;DT, const CFGDeadness &amp;CD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfa3e7437c8b24b03d5ba8db4169ea9">hasLiveIncomingEdge</a> (const PHINode *PN, const BasicBlock *InBB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586fa10f05ad8a9dd13b494aa2687c29">getBasicBlockState</a> (const BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51872cd9e144bedf1e8d76384ec60de">getBasicBlockState</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8761236e4ec581fffafedc70194c3657">isValuePoisoned</a> (const Value *V) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3574e4de0521856572a711945fb89642">isMapped</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true for reachable and live blocks. <a href="#a3574e4de0521856572a711945fb89642">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4897fbcdf135a5e7eae27b5205a33b18">instructionMayBeSkipped</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction may be safely skipped during verification. <a href="#a4897fbcdf135a5e7eae27b5205a33b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c5ffee8e2987c70a85306a2e21b8e4">recalculateBBsStates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterates over all BBs from BlockMap and recalculates AvailableIn/Out for each of them until it converges. <a href="#a01c5ffee8e2987c70a85306a2e21b8e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1440eee87ff8a7c4443a39d14bdb36">removeValidUnrelocatedDefs</a> (const BasicBlock *BB, const BasicBlockState *BBS, AvailableValueSet &amp;Contribution)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove from Contribution all defs that legally produce unrelocated pointers and saves them to ValidUnrelocatedDefs. <a href="#abd1440eee87ff8a7c4443a39d14bdb36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22602b75ec1574d8070ab67d60512ef4">gatherDominatingDefs</a> (const BasicBlock *BB, AvailableValueSet &amp;Result, const DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather all the definitions dominating the start of BB into Result. <a href="#a22602b75ec1574d8070ab67d60512ef4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a546958d9e437ffea4926cef4b58823e9">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness">CFGDeadness</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a534cdc94325cc5e3def84bb4ad333834">CD</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93241b0aac5791601572efd04c4d1496">BSAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a973640fcc31fd773b94fc055bb1b0ed2">BlockMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f055b9fafbe398dfecdcb98ffa45b1">ValidUnrelocatedDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21eb2bfe92c53ae747c1101c91cf6c85">PoisonedDefs</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaee927f8ed0e14bcb32091411cffe66">verifyFunction</a> (GCPtrTracker &amp;&amp;Tracker, InstructionVerifier &amp;Verifier)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Traverse each BB of the function and call <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/instructionverifier/#a22267ade8efa0b7987130922b9ae3c2e">InstructionVerifier::verifyInstruction</a> for each possibly invalid instruction. <a href="#aaaee927f8ed0e14bcb32091411cffe66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0752825ced54cef85c41d417e3ff55bf">transferBlock</a> (const BasicBlock *BB, BasicBlockState &amp;BBS, bool ContributionChanged)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the AvailableOut set for BB, based on the <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> BBS, which is the <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> for BB. <a href="#a0752825ced54cef85c41d417e3ff55bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a983de336a8857e83c49161a6b6ba3">transferInstruction</a> (const Instruction &amp;I, bool &amp;Cleared, AvailableValueSet &amp;Available)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Model the effect of an instruction on the set of available values. <a href="#ac1a983de336a8857e83c49161a6b6ba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Builds <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> for each BB of the function.</p>


<p>It can traverse function for verification and provides all required information.</p>


<p>GC pointer may be in one of three states: relocated, unrelocated and poisoned. Relocated pointer may be used without any restrictions. Unrelocated pointer cannot be dereferenced, passed as argument to any call or returned. Unrelocated pointer may be safely compared against another unrelocated pointer or against a pointer exclusively derived from null. Poisoned pointers are produced when we somehow derive pointer from relocated and unrelocated pointers (e.g. phi, select). This pointers may be safely used in a very limited number of situations. Currently the only way to use it is comparison against constant exclusively derived from null. All limitations arise due to their undefined state: this pointers should be treated as relocated and unrelocated simultaneously. Rules of deriving: R + U = P - that's where the poisoned pointers come from P + X = P U + U = U R + R = R X + C = X Where "+" - any operation that somehow derive pointer, U - unrelocated, R - relocated and P - poisoned, C - constant, X - U or R or P or C or nothing (in case when "+" is unary operation). Deriving of pointers by itself is always safe. NOTE: when we are making decision on the status of instruction's result: a) for phi we need to check status of each input <em>at the end of corresponding predecessor BB</em>. b) for other instructions we need to check status of each input <em>at the current point</em>.</p>


<p>FIXME: This works fairly well except one case bb1: p = <em>some GC-ptr def</em> p1 = gep p, offset / | / | bb2: | safepoint | \ | \ | bb3: p2 = phi [p, bb2] [p1, bb1] p3 = phi [p, bb2] [p, bb1] here p and p1 is unrelocated p2 and p3 is poisoned (though they shouldn't be)</p>


<p>This leads to some weird results: cmp eq p, p2 - illegal instruction (false-positive) cmp eq p1, p2 - illegal instruction (false-positive) cmp eq p, p3 - illegal instruction (false-positive) cmp eq p, p1 - ok To fix this we need to introduce conception of generations and be able to check if two values belong to one generation or not. This way p2 will be considered to be unrelocated and no false alarm will happen.</p>


<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCPtrTracker() {#a9910e63c423b9ed6890d2b551142ef92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCPtrTracker::GCPtrTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness">CFGDeadness</a> &amp; CD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a>.</p>


<p>Referenced by <a href="#ad51872cd9e144bedf1e8d76384ec60de">getBasicBlockState</a> and <a href="#aaaee927f8ed0e14bcb32091411cffe66">verifyFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBasicBlockState() {#a586fa10f05ad8a9dd13b494aa2687c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlockState * GCPtrTracker::getBasicBlockState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<p>Referenced by <a href="#ad51872cd9e144bedf1e8d76384ec60de">getBasicBlockState</a> and <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/instructionverifier/#a22267ade8efa0b7987130922b9ae3c2e">anonymous{SafepointIRVerifier.cpp}::InstructionVerifier::verifyInstruction</a>.</p>

</div>
</div>

### getBasicBlockState() {#ad51872cd9e144bedf1e8d76384ec60de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlockState * GCPtrTracker::getBasicBlockState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<p>References <a href="#a9910e63c423b9ed6890d2b551142ef92">GCPtrTracker</a> and <a href="#a586fa10f05ad8a9dd13b494aa2687c29">getBasicBlockState</a>.</p>

</div>
</div>

### hasLiveIncomingEdge() {#aebfa3e7437c8b24b03d5ba8db4169ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::hasLiveIncomingEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InBB)</td>
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



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/instructionverifier/#a22267ade8efa0b7987130922b9ae3c2e">anonymous{SafepointIRVerifier.cpp}::InstructionVerifier::verifyInstruction</a>.</p>

</div>
</div>

### isMapped() {#a3574e4de0521856572a711945fb89642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::isMapped (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Returns true for reachable and live blocks.</p>

<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### isValuePoisoned() {#a8761236e4ec581fffafedc70194c3657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::isValuePoisoned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### gatherDominatingDefs() {#a22602b75ec1574d8070ab67d60512ef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCPtrTracker::gatherDominatingDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ad7ed294f6046a4e90a60bc99d532bf2f">AvailableValueSet</a> &amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gather all the definitions dominating the start of BB into Result.</p>


<p>This is simply the defs introduced by every dominating basic block and the function arguments.</p>


<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### instructionMayBeSkipped() {#a4897fbcdf135a5e7eae27b5205a33b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCPtrTracker::instructionMayBeSkipped (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the instruction may be safely skipped during verification.</p>

<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### recalculateBBsStates() {#a01c5ffee8e2987c70a85306a2e21b8e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCPtrTracker::recalculateBBsStates ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterates over all BBs from BlockMap and recalculates AvailableIn/Out for each of them until it converges.</p>

<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### removeValidUnrelocatedDefs() {#abd1440eee87ff8a7c4443a39d14bdb36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCPtrTracker::removeValidUnrelocatedDefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> * BBS, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ad7ed294f6046a4e90a60bc99d532bf2f">AvailableValueSet</a> &amp; Contribution)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove from Contribution all defs that legally produce unrelocated pointers and saves them to ValidUnrelocatedDefs.</p>


<p>Though Contribution should belong to BBS it is passed separately with different const-modifier in order to emphasize (and guarantee) that only Contribution will be changed. Returns true if Contribution was changed otherwise false.</p>


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockMap {#a973640fcc31fd773b94fc055bb1b0ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, BasicBlockState *&gt; anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::BlockMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### BSAllocator {#a93241b0aac5791601572efd04c4d1496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;BasicBlockState&gt; anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::BSAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### CD {#a534cdc94325cc5e3def84bb4ad333834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CFGDeadness&amp; anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::CD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### F {#a546958d9e437ffea4926cef4b58823e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function&amp; anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### PoisonedDefs {#a21eb2bfe92c53ae747c1101c91cf6c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const Value *&gt; anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::PoisonedDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### ValidUnrelocatedDefs {#a14f055b9fafbe398dfecdcb98ffa45b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const Instruction *&gt; anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::ValidUnrelocatedDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### verifyFunction() {#aaaee927f8ed0e14bcb32091411cffe66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCPtrTracker::verifyFunction (<a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker">GCPtrTracker</a> &amp;&amp; Tracker, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/instructionverifier">InstructionVerifier</a> &amp; Verifier)</td>
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

<p>Traverse each BB of the function and call <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/instructionverifier/#a22267ade8efa0b7987130922b9ae3c2e">InstructionVerifier::verifyInstruction</a> for each possibly invalid instruction.</p>


<p>It destructively modifies <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker">GCPtrTracker</a> so it's passed via rvalue reference in order to prohibit further usages of <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker">GCPtrTracker</a> as it'll be in inconsistent state.</p>


<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate/#a25ec7ec23b7d24288b14427d35772a20">anonymous{SafepointIRVerifier.cpp}::BasicBlockState::AvailableIn</a>, <a href="#a9910e63c423b9ed6890d2b551142ef92">GCPtrTracker</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae91b89e3dbb8e36d143a6efcc4d5d85a">Verifier</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae3cddd13e523553c3411ddd9b91486b9">Verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### transferBlock() {#a0752825ced54cef85c41d417e3ff55bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCPtrTracker::transferBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> &amp; BBS, bool ContributionChanged)</td>
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

<p>Compute the AvailableOut set for BB, based on the <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> BBS, which is the <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate">BasicBlockState</a> for BB.</p>


<p>ContributionChanged is set when the verifier runs for the first time (in this case Contribution was changed from 'empty' to its initial state) or when Contribution of this BB was changed since last computation.</p>


<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### transferInstruction() {#ac1a983de336a8857e83c49161a6b6ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCPtrTracker::transferInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, bool &amp; Cleared, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ad7ed294f6046a4e90a60bc99d532bf2f">AvailableValueSet</a> &amp; Available)</td>
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

<p>Model the effect of an instruction on the set of available values.</p>

<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
