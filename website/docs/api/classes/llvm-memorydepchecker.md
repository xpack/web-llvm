---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memorydepchecker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemoryDepChecker` Class Reference

<p>Checks memory dependences among accesses to the same underlying object to determine whether there vectorization is legal or not (and at which vectorization factor). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemoryDepChecker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">llvm/Analysis/LoopAccessAnalysis.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 1, bool &gt; <a href="#adb2762f61b5d5d514cdb7f650e23f617">MemAccessInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#adb2762f61b5d5d514cdb7f650e23f617">MemAccessInfo</a>, 8 &gt; <a href="#abc943f0e03dddf08da437eab00bcd8e6">MemAccessInfoList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses">EquivalenceClasses</a>&lt; <a href="#adb2762f61b5d5d514cdb7f650e23f617">MemAccessInfo</a> &gt; <a href="#a4eb0c14b923c59b75a82bc41e03c2575">DepCandidates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of potential dependent memory accesses. <a href="#a4eb0c14b923c59b75a82bc41e03c2575">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VectorizationSafetyStatus { <a href="#ac661dd363bcde8b1e9516390eff1c400">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> to keep track of the status of the dependence check. <a href="#ac661dd363bcde8b1e9516390eff1c400">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7610f9bf36472cdb43096b7bcafd0a89">MemoryDepChecker</a> (PredicatedScalarEvolution &amp;PSE, const Loop *L, const DenseMap&lt; Value *, const SCEV * &gt; &amp;SymbolicStrides, unsigned MaxTargetVectorWidthInBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace2c5efcbecfc5bb3e16f3948ed87a13">addAccess</a> (StoreInst *SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the location (instructions are given increasing numbers) of a write access. <a href="#ace2c5efcbecfc5bb3e16f3948ed87a13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35e34e7ae9695a3d616ee7a311d0e54">addAccess</a> (LoadInst *LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the location (instructions are given increasing numbers) of a write access. <a href="#ac35e34e7ae9695a3d616ee7a311d0e54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e54d4cd15784b0f0480ca88bcf3165f">areDepsSafe</a> (const DepCandidates &amp;AccessSets, const MemAccessInfoList &amp;CheckDeps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the dependencies between the accesses are safe. <a href="#a2e54d4cd15784b0f0480ca88bcf3165f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1dd88272c6bc2aafa940a5fd149630">isSafeForVectorization</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>No memory dependence was encountered that would inhibit vectorization. <a href="#a9a1dd88272c6bc2aafa940a5fd149630">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac812c9eca9442425b23a9cd74f14be">isSafeForAnyVectorWidth</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the number of elements that are safe to operate on simultaneously is not bounded. <a href="#a2ac812c9eca9442425b23a9cd74f14be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a934d4913d1fb6daff3365593fbf40aea">getMaxSafeVectorWidthInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of elements that are safe to operate on simultaneously, multiplied by the size of the element in bits. <a href="#a934d4913d1fb6daff3365593fbf40aea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac97acd1d293e89564fef069fff1ffdb2">shouldRetryWithRuntimeCheck</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In same cases when the dependency check fails we can still vectorize the loop with a dynamic array access check. <a href="#ac97acd1d293e89564fef069fff1ffdb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence">Dependence</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dabe7c42f40c5555034785d247b7ce1">getDependences</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the memory dependences. <a href="#a9dabe7c42f40c5555034785d247b7ce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67819b448429b42f3558c9b2e4ae4b45">clearDependences</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77779b1cb3dd7968c598f9d6de68282e">getMemoryInstructions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The vector of memory access instructions. <a href="#a77779b1cb3dd7968c598f9d6de68282e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af82d4d9d9329f2e8cac85ea493d42c09">generateInstructionOrderMap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate a mapping between the memory instructions and their indices according to program order. <a href="#af82d4d9d9329f2e8cac85ea493d42c09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac340403e4c2fd9116b74b7c2eb95633f">getInstructionsForAccess</a> (Value *Ptr, bool isWrite) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the set of instructions that read or write via <span class="doxyComputerOutput">Ptr</span>. <a href="#ac340403e4c2fd9116b74b7c2eb95633f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a130cee137466543e1484c8c8545f90c9">getOrderForAccess</a> (Value *Ptr, bool IsWrite) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the program order indices for the access location (Ptr, IsWrite). <a href="#a130cee137466543e1484c8c8545f90c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e45de3357999f3f66d85031022d82a">getInnermostLoop</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;, std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd2e14335ab61ef497866aeb6d606db">getPointerBounds</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#ae336b0e8514b99a44e73c3e2494c3cea">Dependence::DepType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38cc31094ed54fccc8089be343bf12d2">isDependent</a> (const MemAccessInfo &amp;A, unsigned AIdx, const MemAccessInfo &amp;B, unsigned BIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether there is a plausible dependence between the two accesses. <a href="#a38cc31094ed54fccc8089be343bf12d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b59be331ab8ff4d1adce10a3a04add6">couldPreventStoreLoadForward</a> (uint64_t Distance, uint64_t TypeByteSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the data dependence could prevent store-load forwarding. <a href="#a0b59be331ab8ff4d1adce10a3a04add6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703b6d9d03ea80a0a7f81bbcb83883c9">mergeInStatus</a> (VectorizationSafetyStatus S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the current safety status with <span class="doxyComputerOutput">S</span>. <a href="#a703b6d9d03ea80a0a7f81bbcb83883c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::variant&lt; <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#ae336b0e8514b99a44e73c3e2494c3cea">Dependence::DepType</a>, DepDistanceStrideAndSizeInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a931e0e5a507e69b39f01cb2ad63eb1fc">getDependenceDistanceStrideAndSize</a> (const MemAccessInfo &amp;A, Instruction *AInst, const MemAccessInfo &amp;B, Instruction *BInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the dependence distance, strides, type size and whether it is a write for the dependence between A and B. <a href="#a931e0e5a507e69b39f01cb2ad63eb1fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e702110a5b6038b4bbfcb53db983ea6">PSE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>, used to add runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks, and applies dynamic knowledge to simplify <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions and convert them to a more usable form. <a href="#a8e702110a5b6038b4bbfcb53db983ea6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b49bdd1f17113b0e7199a6a67ed2760">InnermostLoop</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09bd44b3337b35b2c3661c2a3f970dcc">SymbolicStrides</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to map of pointer values to their stride symbols, if they have a symbolic stride. <a href="#a09bd44b3337b35b2c3661c2a3f970dcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#adb2762f61b5d5d514cdb7f650e23f617">MemAccessInfo</a>, std::vector&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14384bff745334cdefb5a307a41d609c">Accesses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps access locations (ptr, read/write) to program order. <a href="#a14384bff745334cdefb5a307a41d609c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62360143e8a33bd3c96c77971ad0fbc">InstMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> access instructions in program order. <a href="#ac62360143e8a33bd3c96c77971ad0fbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd3038586aa2b47701fcdf90405ad4e">AccessIdx</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The program order index to be used for the next instruction. <a href="#a8bd3038586aa2b47701fcdf90405ad4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23801138e343fc0836e546cf1a05fff9">MinDepDistBytes</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The smallest dependence distance in bytes in the loop. <a href="#a23801138e343fc0836e546cf1a05fff9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac95d20df703b7cf86864aeed21d99799">MaxSafeVectorWidthInBits</a> = -1U</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of elements (from consecutive iterations) that are safe to operate on simultaneously, multiplied by the size of the element in bits. <a href="#ac95d20df703b7cf86864aeed21d99799">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2e32ccb94c76be878c607fcc137705">FoundNonConstantDistanceDependence</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we see a non-constant dependence distance we can still try to vectorize this loop with runtime checks. <a href="#a8a2e32ccb94c76be878c607fcc137705">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac661dd363bcde8b1e9516390eff1c400">VectorizationSafetyStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35839297be1a74cec461ee42e314f01">Status</a> = <a href="#ac661dd363bcde8b1e9516390eff1c400ac6eea0560cd6f377e78dff2c85cc9122">VectorizationSafetyStatus::Safe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Result of the dependence checks, indicating whether the checked dependences are safe for vectorization, require RT checks or are known to be unsafe. <a href="#ac35839297be1a74cec461ee42e314f01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e3c8772b520587cb7e2d7fa06c743a">RecordDependences</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence">Dependence</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba2f7b101c71ea9d0fae6ac8439fab47">Dependences</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> dependences collected during the analysis. <a href="#aba2f7b101c71ea9d0fae6ac8439fab47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b913ea0c21c016337a92b6c47809d4">MaxTargetVectorWidthInBits</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum width of a target's vector registers multiplied by 2 to also roughly account for additional interleaving. <a href="#a45b913ea0c21c016337a92b6c47809d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;, std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b8e2f63be16a1bd5d80e45749ad0ab5">PointerBounds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions to their expanded pointer bounds (pair of start and end pointer expressions). <a href="#a5b8e2f63be16a1bd5d80e45749ad0ab5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards">ScalarEvolution::LoopGuards</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a053bc112e38de6453deafe3034bdba7f">LoopGuards</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache for the loop guards of InnermostLoop. <a href="#a053bc112e38de6453deafe3034bdba7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Checks memory dependences among accesses to the same underlying object to determine whether there vectorization is legal or not (and at which vectorization factor).</p>


<p>Note: This class will compute a conservative dependence for access to different underlying pointers. Clients, such as the loop vectorizer, will sometimes deal these potential dependencies by emitting runtime checks.</p>


<p>We use the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> framework to symbolically evalutate access functions pairs. Since we currently don't restructure the loop we can rely on the program order of memory accesses to determine their safety. At the moment we will only deem accesses as safe for:</p>


<ul class="doxyList ">
<li>A negative constant distance assuming program order.

Safe: tmp = a[i + 1]; OR a[i + 1] = x; a[i] = tmp; y = a[i];

The latter case is safe because later checks guarantuee that there can't be a cycle through a phi node (that is, we check that "x" and "y" is not the same variable: a header phi can only be an induction or a reduction, a reduction can't have a memory sink, an induction can't have a memory source). This is important and must not be violated (or we have to resort to checking for cycles through memory).</li>
<li>A positive constant distance assuming program order that is bigger than the biggest memory access.

tmp = a[i] OR b[i] = x a[i+2] = tmp y = b[i+2];

Safe distance: 2 x sizeof(a[0]), and 2 x sizeof(b[0]), respectively.</li>
<li>Zero distances and all accesses have the same size.</li>
</ul>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DepCandidates {#a4eb0c14b923c59b75a82bc41e03c2575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef EquivalenceClasses&lt;MemAccessInfo&gt; llvm::MemoryDepChecker::DepCandidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of potential dependent memory accesses.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### MemAccessInfo {#adb2762f61b5d5d514cdb7f650e23f617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef PointerIntPair&lt;Value *, 1, bool&gt; llvm::MemoryDepChecker::MemAccessInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### MemAccessInfoList {#abc943f0e03dddf08da437eab00bcd8e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVector&lt;MemAccessInfo, 8&gt; llvm::MemoryDepChecker::MemAccessInfoList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### VectorizationSafetyStatus {#ac661dd363bcde8b1e9516390eff1c400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::MemoryDepChecker::VectorizationSafetyStatus </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> to keep track of the status of the dependence check.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Safe<a id="ac661dd363bcde8b1e9516390eff1c400ac6eea0560cd6f377e78dff2c85cc9122"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PossiblySafeWithRtChecks<a id="ac661dd363bcde8b1e9516390eff1c400ad1b0fb720d53739ff1265c71d6977de8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unsafe<a id="ac661dd363bcde8b1e9516390eff1c400ad3d57868b6ff9839eff631d2cc8acbce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>The order of the elements is important and has to be from most permissive to least permissive.</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemoryDepChecker() {#a7610f9bf36472cdb43096b7bcafd0a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryDepChecker::MemoryDepChecker (<a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; SymbolicStrides, unsigned MaxTargetVectorWidthInBits)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#a29795bb317fb25a2cb114309a80a19f2">llvm::MemoryDepChecker::Dependence::getDestination</a> and <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#a587c4bfaaf058747310f58b2f8d14f1c">llvm::MemoryDepChecker::Dependence::getSource</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAccess() {#ace2c5efcbecfc5bb3e16f3948ed87a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDepChecker::addAccess (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the location (instructions are given increasing numbers) of a write access.</p>

<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1658 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a99bbdbd6641e69bcad8fda4bf1726525">visitPointers</a>.</p>

</div>
</div>

### addAccess() {#ac35e34e7ae9695a3d616ee7a311d0e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDepChecker::addAccess (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the location (instructions are given increasing numbers) of a write access.</p>

<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a99bbdbd6641e69bcad8fda4bf1726525">visitPointers</a>.</p>

</div>
</div>

### areDepsSafe() {#a2e54d4cd15784b0f0480ca88bcf3165f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemoryDepChecker::areDepsSafe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4eb0c14b923c59b75a82bc41e03c2575">DepCandidates</a> &amp; AccessSets, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abc943f0e03dddf08da437eab00bcd8e6">MemAccessInfoList</a> &amp; CheckDeps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the dependencies between the accesses are safe.</p>


<p>Only checks sets with elements in <span class="doxyComputerOutput">CheckDeps</span>.</p>


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 2253 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/#a08a0899420552a8b2359ed963c77daa8">llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::findValue</a>, <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/#ac0ff4be03ce0a4d0b5b60c713db9aef3">llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::getLeaderValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#af7e624cd937996851e961d72cdca670d">llvm::MemoryDepChecker::Dependence::isSafeForVectorization</a>, <a href="#a9a1dd88272c6bc2aafa940a5fd149630">isSafeForVectorization</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a140e23deb724dfd731f7daa5dfa125a9">MaxDependences</a>, <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/#a9b2fb7a349a72d78d495c7a6af9150b2">llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::member_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/#a355ac386262a099693abd5b51c60e137">llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::member_end</a>, <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#ae336b0e8514b99a44e73c3e2494c3ceaae12470995d757ddbebbd627f397fe349">llvm::MemoryDepChecker::Dependence::NoDep</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### clearDependences() {#a67819b448429b42f3558c9b2e4ae4b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemoryDepChecker::clearDependences ()</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#ad8d62e07caf887e918be3dd7929db6ef">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::resetDepChecks</a>.</p>

</div>
</div>

### generateInstructionOrderMap() {#af82d4d9d9329f2e8cac85ea493d42c09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; Instruction *, unsigned &gt; llvm::MemoryDepChecker::generateInstructionOrderMap ()</td>
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

<p>Generate a mapping between the memory instructions and their indices according to program order.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getDependences() {#a9dabe7c42f40c5555034785d247b7ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; Dependence &gt; * llvm::MemoryDepChecker::getDependences ()</td>
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

<p>Returns the memory dependences.</p>


<p>If null is returned we exceeded the MaxDependences threshold and this information is not available.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### getInnermostLoop() {#a87e45de3357999f3f66d85031022d82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop * llvm::MemoryDepChecker::getInnermostLoop ()</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### getInstructionsForAccess() {#ac340403e4c2fd9116b74b7c2eb95633f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Instruction *, 4 &gt; MemoryDepChecker::getInstructionsForAccess (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, bool isWrite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the set of instructions that read or write via <span class="doxyComputerOutput">Ptr</span>.</p>

<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 2330 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#adb4fa2b9065093d32736f78ea43a8c8a">Access</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a615619b0b2879029152b9a20e96624bc">llvm::transform</a>.</p>

</div>
</div>

### getMaxSafeVectorWidthInBits() {#a934d4913d1fb6daff3365593fbf40aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MemoryDepChecker::getMaxSafeVectorWidthInBits ()</td>
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

<p>Return the number of elements that are safe to operate on simultaneously, multiplied by the size of the element in bits.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a8acfde41662b7ec9d592d905da1dbb22">llvm::LoopAccessInfo::print</a>.</p>

</div>
</div>

### getMemoryInstructions() {#a77779b1cb3dd7968c598f9d6de68282e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; Instruction * &gt; &amp; llvm::MemoryDepChecker::getMemoryInstructions ()</td>
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

<p>The vector of memory access instructions.</p>


<p>The indices are used as instruction identifiers in the <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence">Dependence</a> class.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#a29795bb317fb25a2cb114309a80a19f2">llvm::MemoryDepChecker::Dependence::getDestination</a>, <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#a587c4bfaaf058747310f58b2f8d14f1c">llvm::MemoryDepChecker::Dependence::getSource</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### getOrderForAccess() {#a130cee137466543e1484c8c8545f90c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; llvm::MemoryDepChecker::getOrderForAccess (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, bool IsWrite)</td>
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

<p>Return the program order indices for the access location (Ptr, IsWrite).</p>


<p>Returns an empty <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> if there are no accesses for the location.</p>


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getPointerBounds() {#aabd2e14335ab61ef497866aeb6d606db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; std::pair&lt; const SCEV *, Type * &gt;, std::pair&lt; const SCEV *, const SCEV * &gt; &gt; &amp; llvm::MemoryDepChecker::getPointerBounds ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### isSafeForAnyVectorWidth() {#a2ac812c9eca9442425b23a9cd74f14be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryDepChecker::isSafeForAnyVectorWidth ()</td>
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

<p>Return true if the number of elements that are safe to operate on simultaneously is not bounded.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a8acfde41662b7ec9d592d905da1dbb22">llvm::LoopAccessInfo::print</a>.</p>

</div>
</div>

### isSafeForVectorization() {#a9a1dd88272c6bc2aafa940a5fd149630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryDepChecker::isSafeForVectorization ()</td>
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

<p>No memory dependence was encountered that would inhibit vectorization.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Reference <a href="#ac661dd363bcde8b1e9516390eff1c400ac6eea0560cd6f377e78dff2c85cc9122">Safe</a>.</p>


<p>Referenced by <a href="#a2e54d4cd15784b0f0480ca88bcf3165f">areDepsSafe</a>.</p>

</div>
</div>

### shouldRetryWithRuntimeCheck() {#ac97acd1d293e89564fef069fff1ffdb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryDepChecker::shouldRetryWithRuntimeCheck ()</td>
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

<p>In same cases when the dependency check fails we can still vectorize the loop with a dynamic array access check.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>


<p>Reference <a href="#ac661dd363bcde8b1e9516390eff1c400ad1b0fb720d53739ff1265c71d6977de8">PossiblySafeWithRtChecks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### couldPreventStoreLoadForward() {#a0b59be331ab8ff4d1adce10a3a04add6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemoryDepChecker::couldPreventStoreLoadForward (uint64_t Distance, uint64_t TypeByteSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the data dependence could prevent store-load forwarding.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if we shouldn't vectorize at all or avoid larger vectorization factors by limiting MinDepDistBytes.</p></dd>
</dl>


<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1733 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### getDependenceDistanceStrideAndSize() {#a931e0e5a507e69b39f01cb2ad63eb1fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::variant&lt; MemoryDepChecker::Dependence::DepType, MemoryDepChecker::DepDistanceStrideAndSizeInfo &gt; MemoryDepChecker::getDependenceDistanceStrideAndSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adb2762f61b5d5d514cdb7f650e23f617">MemAccessInfo</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * AInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adb2762f61b5d5d514cdb7f650e23f617">MemAccessInfo</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * BInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the dependence distance, strides, type size and whether it is a write for the dependence between A and B.</p>


<p>Returns a DepType, if we can prove there's no dependence or the analysis fails. Outlined to lambda to limit he scope of various temporary variables, like A/BPtr, StrideA/BPtr and others. Returns either the dependence result, if it could already be determined, or a struct containing (Distance, Stride, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a>, AIsWrite, BIsWrite).</p>


<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1884 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### isDependent() {#a38cc31094ed54fccc8089be343bf12d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryDepChecker::Dependence::DepType MemoryDepChecker::isDependent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adb2762f61b5d5d514cdb7f650e23f617">MemAccessInfo</a> &amp; A, unsigned AIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adb2762f61b5d5d514cdb7f650e23f617">MemAccessInfo</a> &amp; B, unsigned BIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether there is a plausible dependence between the two accesses.</p>


<p>Access <span class="doxyComputerOutput">A</span> must happen before <span class="doxyComputerOutput">B</span> in program order. The two indices identify the index into the program order map.</p>


<p>This function checks whether there is a plausible dependence (or the absence of such can't be proved) between the two accesses. If there is a plausible dependence but the dependence distance is bigger than one element access it records this distance in <span class="doxyComputerOutput">MinDepDistBytes</span> (if this distance is smaller than any other distance encountered so far). Otherwise, this function returns true signaling a possible dependence.</p>


<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 2014 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

### mergeInStatus() {#a703b6d9d03ea80a0a7f81bbcb83883c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryDepChecker::mergeInStatus (<a href="#ac661dd363bcde8b1e9516390eff1c400">VectorizationSafetyStatus</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the current safety status with <span class="doxyComputerOutput">S</span>.</p>


<p>We can go from Safe to either PossiblySafeWithRtChecks or Unsafe and from PossiblySafeWithRtChecks to Unsafe.</p>


<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>, definition at line 1777 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Accesses {#a14384bff745334cdefb5a307a41d609c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MemAccessInfo, std::vector&lt;unsigned&gt; &gt; llvm::MemoryDepChecker::Accesses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps access locations (ptr, read/write) to program order.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### AccessIdx {#a8bd3038586aa2b47701fcdf90405ad4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemoryDepChecker::AccessIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The program order index to be used for the next instruction.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### Dependences {#aba2f7b101c71ea9d0fae6ac8439fab47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Dependence, 8&gt; llvm::MemoryDepChecker::Dependences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> dependences collected during the analysis.</p>


<p>Only valid if RecordDependences is true.</p>


<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### FoundNonConstantDistanceDependence {#a8a2e32ccb94c76be878c607fcc137705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryDepChecker::FoundNonConstantDistanceDependence = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we see a non-constant dependence distance we can still try to vectorize this loop with runtime checks.</p>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### InnermostLoop {#a1b49bdd1f17113b0e7199a6a67ed2760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop* llvm::MemoryDepChecker::InnermostLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### InstMap {#ac62360143e8a33bd3c96c77971ad0fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 16&gt; llvm::MemoryDepChecker::InstMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> access instructions in program order.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### LoopGuards {#a053bc112e38de6453deafe3034bdba7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ScalarEvolution::LoopGuards&gt; llvm::MemoryDepChecker::LoopGuards</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache for the loop guards of InnermostLoop.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### MaxSafeVectorWidthInBits {#ac95d20df703b7cf86864aeed21d99799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MemoryDepChecker::MaxSafeVectorWidthInBits = -1U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of elements (from consecutive iterations) that are safe to operate on simultaneously, multiplied by the size of the element in bits.</p>


<p>The size of the element is taken from the memory access that is most restrictive.</p>


<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### MaxTargetVectorWidthInBits {#a45b913ea0c21c016337a92b6c47809d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemoryDepChecker::MaxTargetVectorWidthInBits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum width of a target's vector registers multiplied by 2 to also roughly account for additional interleaving.</p>


<p>Is used to decide if a backwards dependence with non-constant stride should be classified as backwards-vectorizable or unknown (triggering a runtime check).</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### MinDepDistBytes {#a23801138e343fc0836e546cf1a05fff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MemoryDepChecker::MinDepDistBytes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The smallest dependence distance in bytes in the loop.</p>


<p>This may not be the same as the maximum number of bytes that are safe to operate on simultaneously.</p>


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### PointerBounds {#a5b8e2f63be16a1bd5d80e45749ad0ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const SCEV *, Type *&gt;, std::pair&lt;const SCEV *, const SCEV *&gt; &gt; llvm::MemoryDepChecker::PointerBounds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions to their expanded pointer bounds (pair of start and end pointer expressions).</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### PSE {#a8e702110a5b6038b4bbfcb53db983ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; llvm::MemoryDepChecker::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A wrapper around <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>, used to add runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks, and applies dynamic knowledge to simplify <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions and convert them to a more usable form.</p>


<p>We need this in case assumptions about <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions need to be made in order to avoid unknown dependences. For example we might assume a unit stride for a pointer in order to prove that a memory access is strided and doesn't wrap.</p>


<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### RecordDependences {#a39e3c8772b520587cb7e2d7fa06c743a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryDepChecker::RecordDependences = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### Status {#ac35839297be1a74cec461ee42e314f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorizationSafetyStatus llvm::MemoryDepChecker::Status = <a href="#ac661dd363bcde8b1e9516390eff1c400ac6eea0560cd6f377e78dff2c85cc9122">VectorizationSafetyStatus::Safe</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Result of the dependence checks, indicating whether the checked dependences are safe for vectorization, require RT checks or are known to be unsafe.</p>

<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

### SymbolicStrides {#a09bd44b3337b35b2c3661c2a3f970dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt;Value *, const SCEV *&gt;&amp; llvm::MemoryDepChecker::SymbolicStrides</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to map of pointer values to their stride symbols, if they have a symbolic stride.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">LoopAccessAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp">LoopAccessAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
