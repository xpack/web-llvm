---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/pointerintpairinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PointerIntPairInfo` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;
struct llvm::PointerIntPairInfo&lt;PointerT, IntBits, PtrTraits&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">llvm/ADT/PointerIntPair.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">MaskAndShiftConstants : uintptr_t { <a href="#a753cd347a2578a1d1a4c3a6141c238f4">...</a> }</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static PointerT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c736e50cb26f4bde4ebcc1ff2b4de0d">getPointer</a> (intptr_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static intptr_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a56b33fff03f26e5e9c2c7a93704cb237">getInt</a> (intptr_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static intptr_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe9e61c680bec7d93ec05b6cabdb5559">updatePointer</a> (intptr_t OrigValue, PointerT Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static intptr_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0cd0c01e9fcee49d4850a205f2594307">updateInt</a> (intptr_t OrigValue, intptr_t Int)</td>
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


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### MaskAndShiftConstants {#a753cd347a2578a1d1a4c3a6141c238f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PointerIntPairInfo::MaskAndShiftConstants : uintptr_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PointerBitMask<a id="a753cd347a2578a1d1a4c3a6141c238f4a3a51956fad564a5f8c9a923b17963cfa"></a></td>
<td class="doxyEnumItemDescription">
PointerBitMask - The bits that come from the pointer (=
        ~(uintptr_t)(((intptr_t)1 &lt;&lt; PtrTraits::NumLowBitsAvailable) - 1))
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntShift<a id="a753cd347a2578a1d1a4c3a6141c238f4a1dd9e7252764042009f043bb2a8ad5f7"></a></td>
<td class="doxyEnumItemDescription">IntShift - The number of low bits that we reserve for other uses, and keep zero (= (uintptr_t)PtrTraits::NumLowBitsAvailable - IntBits)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntMask<a id="a753cd347a2578a1d1a4c3a6141c238f4aadb9eb34960575d9dd59b4b765c1fd25"></a></td>
<td class="doxyEnumItemDescription">IntMask - This is the unshifted mask for valid bits of the int type (= (uintptr_t)(((intptr_t)1 &lt;&lt; IntBits) - 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ShiftedIntMask<a id="a753cd347a2578a1d1a4c3a6141c238f4a3bceb0d2563c4e0a9df22ae7b81b9387"></a></td>
<td class="doxyEnumItemDescription"> (= (uintptr_t)(IntMask &lt;&lt; IntShift))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getInt() {#a56b33fff03f26e5e9c2c7a93704cb237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">intptr_t llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::getInt (intptr_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>References <a href="#a753cd347a2578a1d1a4c3a6141c238f4aadb9eb34960575d9dd59b4b765c1fd25">llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::IntMask</a> and <a href="#a753cd347a2578a1d1a4c3a6141c238f4a1dd9e7252764042009f043bb2a8ad5f7">llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::IntShift</a>.</p>

</div>
</div>

### getPointer() {#a0c736e50cb26f4bde4ebcc1ff2b4de0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerT llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::getPointer (intptr_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>Reference <a href="#a753cd347a2578a1d1a4c3a6141c238f4a3a51956fad564a5f8c9a923b17963cfa">llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::PointerBitMask</a>.</p>

</div>
</div>

### updateInt() {#a0cd0c01e9fcee49d4850a205f2594307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">intptr_t llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::updateInt (intptr_t OrigValue, intptr_t Int)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="#a753cd347a2578a1d1a4c3a6141c238f4aadb9eb34960575d9dd59b4b765c1fd25">llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::IntMask</a>, <a href="#a753cd347a2578a1d1a4c3a6141c238f4a1dd9e7252764042009f043bb2a8ad5f7">llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::IntShift</a> and <a href="#a753cd347a2578a1d1a4c3a6141c238f4a3bceb0d2563c4e0a9df22ae7b81b9387">llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::ShiftedIntMask</a>.</p>

</div>
</div>

### updatePointer() {#afe9e61c680bec7d93ec05b6cabdb5559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerT, unsigned IntBits, typename PtrTraits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">intptr_t llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::updatePointer (intptr_t OrigValue, PointerT Ptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a753cd347a2578a1d1a4c3a6141c238f4a3a51956fad564a5f8c9a923b17963cfa">llvm::PointerIntPairInfo&lt; PointerT, IntBits, PtrTraits &gt;::PointerBitMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
