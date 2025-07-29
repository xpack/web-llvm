---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/omp/variantmatchinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VariantMatchInfo` Struct

<p>Variant match information describes the required traits and how they are scored (via the ScoresMap). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::omp::VariantMatchInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">llvm/Frontend/OpenMP/OMPContext.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a4b99974af9aad9644042639286bf3">addTrait</a> (TraitProperty Property, StringRef RawString, APInt *Score=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the trait <span class="doxyComputerOutput">Property</span> to the required trait set. <a href="#a33a4b99974af9aad9644042639286bf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e4982abd318e0ce35e9f1759b65870">addTrait</a> (TraitSet Set, TraitProperty Property, StringRef RawString, APInt *Score=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the trait <span class="doxyComputerOutput">Property</span> which is in set <span class="doxyComputerOutput">Set</span> to the required trait set. <a href="#a60e4982abd318e0ce35e9f1759b65870">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350aec756a45652070266d41672199b8">RequiredTraits</a> = <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a>(unsigned(TraitProperty::Last) + 1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28550439283e1ce0094fa4ae13db5ccb">ISATraits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391eed61e8202859bdda749028fab76e">ConstructTraits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a>, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c13ad13f5c1ebefe7039b90868cec0">ScoreMap</a></td>
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

<p>Variant match information describes the required traits and how they are scored (via the ScoresMap).</p>


<p>In addition, the required consturct nesting is decribed as well.</p>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addTrait() {#a33a4b99974af9aad9644042639286bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::omp::VariantMatchInfo::addTrait (<a href="/web-llvm/docs/api/namespaces/llvm/omp/#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a> Property, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RawString, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> * Score=nullptr)</td>
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

<p>Add the trait <span class="doxyComputerOutput">Property</span> to the required trait set.</p>


<p><span class="doxyComputerOutput">RawString</span> is the string we parsed and derived <span class="doxyComputerOutput">Property</span> from. If <span class="doxyComputerOutput">Score</span> is not null, it recorded as well. If <span class="doxyComputerOutput">Property</span> is in the <span class="doxyComputerOutput">construct</span> set it is recorded in-order in the ConstructTraits as well.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>


<p>References <a href="#a33a4b99974af9aad9644042639286bf3">addTrait</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a6ab910ced9f2e14f0c3b7a176ab5fe45">llvm::omp::getOpenMPContextTraitSetForProperty</a>.</p>


<p>Referenced by <a href="#a33a4b99974af9aad9644042639286bf3">addTrait</a>.</p>

</div>
</div>

### addTrait() {#a60e4982abd318e0ce35e9f1759b65870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::omp::VariantMatchInfo::addTrait (<a href="/web-llvm/docs/api/namespaces/llvm/omp/#ac053ab007366c857887d939adbeea976">TraitSet</a> Set, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aed19c754b6dc51a7f084d621b4043788">TraitProperty</a> Property, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RawString, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> * Score=nullptr)</td>
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

<p>Add the trait <span class="doxyComputerOutput">Property</span> which is in set <span class="doxyComputerOutput">Set</span> to the required trait set.</p>


<p><span class="doxyComputerOutput">RawString</span> is the string we parsed and derived <span class="doxyComputerOutput">Property</span> from. If <span class="doxyComputerOutput">Score</span> is not null, it recorded as well. If <span class="doxyComputerOutput">Set</span> is the <span class="doxyComputerOutput">construct</span> set it is recorded in-order in the ConstructTraits as well.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>


<p>References <a href="#a391eed61e8202859bdda749028fab76e">ConstructTraits</a>, <a href="#a28550439283e1ce0094fa4ae13db5ccb">ISATraits</a>, <a href="#a350aec756a45652070266d41672199b8">RequiredTraits</a> and <a href="#ac9c13ad13f5c1ebefe7039b90868cec0">ScoreMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ConstructTraits {#a391eed61e8202859bdda749028fab76e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TraitProperty, 8&gt; llvm::omp::VariantMatchInfo::ConstructTraits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>


<p>Referenced by <a href="#a60e4982abd318e0ce35e9f1759b65870">addTrait</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a7e6a1be6ce8d2df306c9b6c34706610d">isStrictSubset</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>.</p>

</div>
</div>

### ISATraits {#a28550439283e1ce0094fa4ae13db5ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StringRef, 8&gt; llvm::omp::VariantMatchInfo::ISATraits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>


<p>Referenced by <a href="#a60e4982abd318e0ce35e9f1759b65870">addTrait</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>.</p>

</div>
</div>

### RequiredTraits {#a350aec756a45652070266d41672199b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::omp::VariantMatchInfo::RequiredTraits = <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a>(unsigned(TraitProperty::Last) + 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>


<p>Referenced by <a href="#a60e4982abd318e0ce35e9f1759b65870">addTrait</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a7e6a1be6ce8d2df306c9b6c34706610d">isStrictSubset</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>.</p>

</div>
</div>

### ScoreMap {#ac9c13ad13f5c1ebefe7039b90868cec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;TraitProperty, APInt&gt; llvm::omp::VariantMatchInfo::ScoreMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a>.</p>


<p>Referenced by <a href="#a60e4982abd318e0ce35e9f1759b65870">addTrait</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompcontext-h">OMPContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
