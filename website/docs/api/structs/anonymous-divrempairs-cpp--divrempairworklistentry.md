---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-divrempairs-cpp-/divrempairworklistentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DivRemPairWorklistEntry` Struct Reference

<p>A thin wrapper to store two values that we matched as div-rem pair. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf99e89bd3b2fb202ce45b47f937f5f">DivRemPairWorklistEntry</a> (Instruction *DivInst_, Instruction *RemInst_)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb82af2a28a92ba7ba5052d33d3636b">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for this pair, identical for both the div and rem. <a href="#a3eb82af2a28a92ba7ba5052d33d3636b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56e5ffdf57413f50d194286bd10a5ee">isSigned</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this pair signed or unsigned? <a href="#ac56e5ffdf57413f50d194286bd10a5ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958d7088b97d7c24397301cb3acdda6a">getDividend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In this pair, what are the divident and divisor? <a href="#a958d7088b97d7c24397301cb3acdda6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40942d9805e28d07cc6757498a249df9">getDivisor</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0008307062b6882f356b931cf143ba14">isRemExpanded</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6af806f9720754bc375629980e66b0a">DivInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The actual udiv/sdiv instruction. Source of truth. <a href="#ab6af806f9720754bc375629980e66b0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6707b2a44c7037ebc9ddc78d077d3033">RemInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instruction that we have matched as a remainder instruction. <a href="#a6707b2a44c7037ebc9ddc78d077d3033">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A thin wrapper to store two values that we matched as div-rem pair.</p>


<p>We want this extra indirection to avoid dealing with RAUW'ing the map keys.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DivRemPairWorklistEntry() {#a7bf99e89bd3b2fb202ce45b47f937f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry::DivRemPairWorklistEntry (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * DivInst_, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * RemInst_)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab6af806f9720754bc375629980e66b0a">DivInst</a> and <a href="#a6707b2a44c7037ebc9ddc78d077d3033">RemInst</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDividend() {#a958d7088b97d7c24397301cb3acdda6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry::getDividend ()</td>
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

<p>In this pair, what are the divident and divisor?</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<p>Reference <a href="#ab6af806f9720754bc375629980e66b0a">DivInst</a>.</p>

</div>
</div>

### getDivisor() {#a40942d9805e28d07cc6757498a249df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry::getDivisor ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<p>Reference <a href="#ab6af806f9720754bc375629980e66b0a">DivInst</a>.</p>

</div>
</div>

### getType() {#a3eb82af2a28a92ba7ba5052d33d3636b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry::getType ()</td>
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

<p>The type for this pair, identical for both the div and rem.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<p>Reference <a href="#ab6af806f9720754bc375629980e66b0a">DivInst</a>.</p>

</div>
</div>

### isRemExpanded() {#a0008307062b6882f356b931cf143ba14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry::isRemExpanded ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<p>Reference <a href="#a6707b2a44c7037ebc9ddc78d077d3033">RemInst</a>.</p>

</div>
</div>

### isSigned() {#ac56e5ffdf57413f50d194286bd10a5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry::isSigned ()</td>
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

<p>Is this pair signed or unsigned?</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<p>Reference <a href="#ab6af806f9720754bc375629980e66b0a">DivInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DivInst {#ab6af806f9720754bc375629980e66b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssertingVH&lt;Instruction&gt; anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry::DivInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The actual udiv/sdiv instruction. Source of truth.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<p>Referenced by <a href="#a7bf99e89bd3b2fb202ce45b47f937f5f">DivRemPairWorklistEntry</a>, <a href="#a958d7088b97d7c24397301cb3acdda6a">getDividend</a>, <a href="#a40942d9805e28d07cc6757498a249df9">getDivisor</a>, <a href="#a3eb82af2a28a92ba7ba5052d33d3636b">getType</a> and <a href="#ac56e5ffdf57413f50d194286bd10a5ee">isSigned</a>.</p>

</div>
</div>

### RemInst {#a6707b2a44c7037ebc9ddc78d077d3033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssertingVH&lt;Instruction&gt; anonymous{DivRemPairs.cpp}::DivRemPairWorklistEntry::RemInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The instruction that we have matched as a remainder instruction.</p>


<p>Should only be used as <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, don't introspect it.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a>.</p>


<p>Referenced by <a href="#a7bf99e89bd3b2fb202ce45b47f937f5f">DivRemPairWorklistEntry</a> and <a href="#a0008307062b6882f356b931cf143ba14">isRemExpanded</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp">DivRemPairs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
