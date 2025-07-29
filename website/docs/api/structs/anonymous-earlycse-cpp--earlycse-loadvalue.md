---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-earlycse-cpp-/earlycse/loadvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LoadValue` Struct

<p>A scoped hash table of the current values of previously encountered memory locations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{EarlyCSE.cpp}::EarlyCSE::LoadValue { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a42c6c09981e7a5e38494f3cfa1134">LoadValue</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a6f41beed3f3ea1d77f05e772bc21d9">LoadValue</a> (Instruction *Inst, unsigned Generation, unsigned MatchingId, bool IsAtomic, bool IsLoad)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ffa0c8239fbd7245a120f68750d58b1">DefInst</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a517a11d604f6aaf362e2d1a5612b9917">Generation</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d1eaea1e0fd405701803f88bd9bed1">MatchingId</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe7284135c3a4337f7212152ae6b256">IsAtomic</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35d19ebfc7aae89aa6bf1fd8e9f41c4">IsLoad</a> = false</td>
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

<p>A scoped hash table of the current values of previously encountered memory locations.</p>


<p>This allows us to get efficient access to dominating loads or stores when we have a fully redundant load. In addition to the most recent load, we keep track of a generation count of the read, which is compared against the current generation count. The current generation count is incremented after every possibly writing memory operation, which ensures that we only CSE loads with other loads that have no intervening store. Ordering events (such as fences or atomic instructions) increment the generation count as well; essentially, we model these as writes to all possible locations. Note that atomic and/or volatile loads and stores can be present the table; it is the responsibility of the consumer to inspect the atomicity/volatility if needed.</p>


<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoadValue() {#a20a42c6c09981e7a5e38494f3cfa1134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{EarlyCSE.cpp}::EarlyCSE::LoadValue::LoadValue ()</td>
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



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### LoadValue() {#a5a6f41beed3f3ea1d77f05e772bc21d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{EarlyCSE.cpp}::EarlyCSE::LoadValue::LoadValue (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, unsigned Generation, unsigned MatchingId, bool IsAtomic, bool IsLoad)</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>References <a href="#a2ffa0c8239fbd7245a120f68750d58b1">DefInst</a>, <a href="#a517a11d604f6aaf362e2d1a5612b9917">Generation</a>, <a href="#a4fe7284135c3a4337f7212152ae6b256">IsAtomic</a>, <a href="#ac35d19ebfc7aae89aa6bf1fd8e9f41c4">IsLoad</a> and <a href="#a43d1eaea1e0fd405701803f88bd9bed1">MatchingId</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DefInst {#a2ffa0c8239fbd7245a120f68750d58b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{EarlyCSE.cpp}::EarlyCSE::LoadValue::DefInst = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a5a6f41beed3f3ea1d77f05e772bc21d9">LoadValue</a>.</p>

</div>
</div>

### Generation {#a517a11d604f6aaf362e2d1a5612b9917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{EarlyCSE.cpp}::EarlyCSE::LoadValue::Generation = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a5a6f41beed3f3ea1d77f05e772bc21d9">LoadValue</a>.</p>

</div>
</div>

### IsAtomic {#a4fe7284135c3a4337f7212152ae6b256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{EarlyCSE.cpp}::EarlyCSE::LoadValue::IsAtomic = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a5a6f41beed3f3ea1d77f05e772bc21d9">LoadValue</a>.</p>

</div>
</div>

### IsLoad {#ac35d19ebfc7aae89aa6bf1fd8e9f41c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{EarlyCSE.cpp}::EarlyCSE::LoadValue::IsLoad = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a5a6f41beed3f3ea1d77f05e772bc21d9">LoadValue</a>.</p>

</div>
</div>

### MatchingId {#a43d1eaea1e0fd405701803f88bd9bed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{EarlyCSE.cpp}::EarlyCSE::LoadValue::MatchingId = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a5a6f41beed3f3ea1d77f05e772bc21d9">LoadValue</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
