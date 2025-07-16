---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-constraintelimination-cpp-/decompentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DecompEntry` Struct Reference

<p>Represents a (Coefficient * Variable) entry after IR decomposition. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ConstraintElimination.cpp}::DecompEntry { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792179335fbd293d8e3ea220523918bb">DecompEntry</a> (int64_t Coefficient, Value *Variable, bool IsKnownNonNegative=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20be3d83655effd76a0cd51ad81f0e0b">Coefficient</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4b60be009aba505ee7adac56bde9f9">Variable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa06d84fda5d8d8c516323bdd70150b">IsKnownNonNegative</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the variable is known positive in the current constraint. <a href="#abfa06d84fda5d8d8c516323bdd70150b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents a (Coefficient * Variable) entry after IR decomposition.</p>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DecompEntry() {#a792179335fbd293d8e3ea220523918bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ConstraintElimination.cpp}::DecompEntry::DecompEntry (int64_t Coefficient, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Variable, bool IsKnownNonNegative=false)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#a20be3d83655effd76a0cd51ad81f0e0b">Coefficient</a>, <a href="#abfa06d84fda5d8d8c516323bdd70150b">IsKnownNonNegative</a> and <a href="#a2e4b60be009aba505ee7adac56bde9f9">Variable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a3a288d8153f8bd74315b59636438d6e2">decomposeGEP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Coefficient {#a20be3d83655effd76a0cd51ad81f0e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{ConstraintElimination.cpp}::DecompEntry::Coefficient</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a792179335fbd293d8e3ea220523918bb">DecompEntry</a>.</p>

</div>
</div>

### IsKnownNonNegative {#abfa06d84fda5d8d8c516323bdd70150b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ConstraintElimination.cpp}::DecompEntry::IsKnownNonNegative</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the variable is known positive in the current constraint.</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a792179335fbd293d8e3ea220523918bb">DecompEntry</a>.</p>

</div>
</div>

### Variable {#a2e4b60be009aba505ee7adac56bde9f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{ConstraintElimination.cpp}::DecompEntry::Variable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a792179335fbd293d8e3ea220523918bb">DecompEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
