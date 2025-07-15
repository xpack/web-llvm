---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-safepointirverifier-cpp-/basicblockstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BasicBlockState` Struct Reference

<p>State we compute and track per basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{SafepointIRVerifier.cpp}::BasicBlockState { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ad7ed294f6046a4e90a60bc99d532bf2f">AvailableValueSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ec7ec23b7d24288b14427d35772a20">AvailableIn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ad7ed294f6046a4e90a60bc99d532bf2f">AvailableValueSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4aa46ae04c638a851b15c0fb108c8d">AvailableOut</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ad7ed294f6046a4e90a60bc99d532bf2f">AvailableValueSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad54cb72f82ecbd438f5f47c7cfc4a9a8">Contribution</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545d981ea1359b77c93ef93bf227e2ca">Cleared</a> = false</td>
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

<p>State we compute and track per basic block.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### AvailableIn {#a25ec7ec23b7d24288b14427d35772a20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValueSet anonymous{SafepointIRVerifier.cpp}::BasicBlockState::AvailableIn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/gcptrtracker/#aaaee927f8ed0e14bcb32091411cffe66">anonymous{SafepointIRVerifier.cpp}::GCPtrTracker::verifyFunction</a>.</p>

</div>
</div>

### AvailableOut {#aae4aa46ae04c638a851b15c0fb108c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValueSet anonymous{SafepointIRVerifier.cpp}::BasicBlockState::AvailableOut</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/instructionverifier/#a22267ade8efa0b7987130922b9ae3c2e">anonymous{SafepointIRVerifier.cpp}::InstructionVerifier::verifyInstruction</a>.</p>

</div>
</div>

### Cleared {#a545d981ea1359b77c93ef93bf227e2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SafepointIRVerifier.cpp}::BasicBlockState::Cleared = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

### Contribution {#ad54cb72f82ecbd438f5f47c7cfc4a9a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValueSet anonymous{SafepointIRVerifier.cpp}::BasicBlockState::Contribution</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp">SafepointIRVerifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
