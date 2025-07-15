---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/assumptioncache/resultelem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ResultElem` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::AssumptionCache::ResultElem { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2dcf3a0d7f23cb97c77150dd58f0cea">operator Value *</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c11eb4c6cb72fc9922b742c71fe3b3">Assume</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0085dfe0ee247e594c95dbb6f768f235">Index</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>contains either ExprResultIdx or the index of the operand bundle containing the knowledge. <a href="#a0085dfe0ee247e594c95dbb6f768f235">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator Value \*() {#ac2dcf3a0d7f23cb97c77150dd58f0cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AssumptionCache::ResultElem::operator Value * ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>


<p>Reference <a href="#a14c11eb4c6cb72fc9922b742c71fe3b3">Assume</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Assume {#a14c11eb4c6cb72fc9922b742c71fe3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeakVH llvm::AssumptionCache::ResultElem::Assume</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>


<p>Referenced by <a href="#ac2dcf3a0d7f23cb97c77150dd58f0cea">operator Value *</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache/#a8137607e298da393c72cfcffb2edc352">llvm::AssumptionCache::unregisterAssumption</a> and <a href="/web-llvm/docs/api/classes/llvm/assumptioncache/#a5fa8956db34e5076680cfd8398d090dc">llvm::AssumptionCache::updateAffectedValues</a>.</p>

</div>
</div>

### Index {#a0085dfe0ee247e594c95dbb6f768f235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AssumptionCache::ResultElem::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>contains either ExprResultIdx or the index of the operand bundle containing the knowledge.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/assumptioncache/#a5fa8956db34e5076680cfd8398d090dc">llvm::AssumptionCache::updateAffectedValues</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">AssumptionCache.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
