---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-safepointirverifier-cpp-/instructionverifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstructionVerifier` Class

<p>It is a visitor for <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker/#aaaee927f8ed0e14bcb32091411cffe66">GCPtrTracker::verifyFunction</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SafepointIRVerifier.cpp}::InstructionVerifier { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22267ade8efa0b7987130922b9ae3c2e">verifyInstruction</a> (const GCPtrTracker *Tracker, const Instruction &amp;I, const AvailableValueSet &amp;AvailableSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb07100fa6da97f9626b004f04a6f51">hasAnyInvalidUses</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1829378ec83cd99288eb26de0c7726b7">reportInvalidUse</a> (const Value &amp;V, const Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4231b0f9a29327ce282e5744b105b7">AnyInvalidUses</a> = false</td>
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

<p>It is a visitor for <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker/#aaaee927f8ed0e14bcb32091411cffe66">GCPtrTracker::verifyFunction</a>.</p>


<p>It decides if the instruction (which uses heap reference) is legal or not, given our safepoint semantics.</p>


<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### hasAnyInvalidUses() {#aadb07100fa6da97f9626b004f04a6f51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafepointIRVerifier.cpp}::InstructionVerifier::hasAnyInvalidUses ()</td>
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



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### verifyInstruction() {#a22267ade8efa0b7987130922b9ae3c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionVerifier::verifyInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker">GCPtrTracker</a> * Tracker, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ad7ed294f6046a4e90a60bc99d532bf2f">AvailableValueSet</a> &amp; AvailableSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/basicblockstate/#aae4aa46ae04c638a851b15c0fb108c8d">anonymous{SafepointIRVerifier.cpp}::BasicBlockState::AvailableOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ab800ba52a9007ccc8b175c3c6e77f71e">containsGCPtrType</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1af3714ee13290f49c4370c3b604363523">ExclusivelyNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1a9e36aac8b3cea176f11fb1e2bd20db2b">ExclusivelySomeConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#aa831f0a1520a405a32196cb32ec24084">getBaseType</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker/#a586fa10f05ad8a9dd13b494aa2687c29">anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::getBasicBlockState</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker/#aebfa3e7437c8b24b03d5ba8db4169ea9">anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::hasLiveIncomingEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#a7bfcdb3f625a42ad35922eb75744c927">isNotExclusivelyConstantDerived</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1aec06ce126da684d1ae0a3dca04116ff2">NonConstant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### reportInvalidUse() {#a1829378ec83cd99288eb26de0c7726b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstructionVerifier::reportInvalidUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AnyInvalidUses {#a0c4231b0f9a29327ce282e5744b105b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafepointIRVerifier.cpp}::InstructionVerifier::AnyInvalidUses = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

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
