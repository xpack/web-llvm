---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/comparison
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Comparison` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a39668000392fa4abbd587966a42db47d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0b532d7422273606194f5a113059fc">negate</a> (uint32_t Cmp)</td>
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


<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a39668000392fa4abbd587966a42db47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">Unk<a id="a39668000392fa4abbd587966a42db47daf501bf716a6d88b0199f03802cf285e2"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EQ<a id="a39668000392fa4abbd587966a42db47dab24618d660fcecfc17f88a51a8902955"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NE<a id="a39668000392fa4abbd587966a42db47da07aed9a1d212a4e0b332ebe5730377da"></a></td>
<td class="doxyEnumItemDescription"> (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">L<a id="a39668000392fa4abbd587966a42db47dae9dc5301a4703fd8f71e8ae4796d4dfe"></a></td>
<td class="doxyEnumItemDescription"> (= 0x04)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">G<a id="a39668000392fa4abbd587966a42db47da6e93116b6b71d16d2c84db906e6e5128"></a></td>
<td class="doxyEnumItemDescription"> (= 0x08)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">U<a id="a39668000392fa4abbd587966a42db47da864bce22cd44dd5acdba2abd48ada7c3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTs<a id="a39668000392fa4abbd587966a42db47da454bde71e02573055836bbc75a708a9d"></a></td>
<td class="doxyEnumItemDescription"> (= L)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LEs<a id="a39668000392fa4abbd587966a42db47da997af133cd341622cf1d0736fa06d6c1"></a></td>
<td class="doxyEnumItemDescription"> (= L | EQ)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GTs<a id="a39668000392fa4abbd587966a42db47da75b051f8578334b074df1bf61c30bac2"></a></td>
<td class="doxyEnumItemDescription"> (= G)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEs<a id="a39668000392fa4abbd587966a42db47da8ac71ce811156aca1f28c1e338fcf91d"></a></td>
<td class="doxyEnumItemDescription"> (= G | EQ)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LTu<a id="a39668000392fa4abbd587966a42db47da6464c3ac63949dcff22ac63fa20fbc43"></a></td>
<td class="doxyEnumItemDescription"> (= L      | U)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LEu<a id="a39668000392fa4abbd587966a42db47da819c2a9990f85c0eb22f86490224f635"></a></td>
<td class="doxyEnumItemDescription"> (= L | EQ | U)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GTu<a id="a39668000392fa4abbd587966a42db47daa38b3ba2c0c37924f978e4832695a51d"></a></td>
<td class="doxyEnumItemDescription"> (= G      | U)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEu<a id="a39668000392fa4abbd587966a42db47da30ff40923b1a9a198816f97761395bb9"></a></td>
<td class="doxyEnumItemDescription"> (= G | EQ | U)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### negate() {#abc0b532d7422273606194f5a113059fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::Comparison::negate (uint32_t Cmp)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a39668000392fa4abbd587966a42db47dab24618d660fcecfc17f88a51a8902955">EQ</a>, <a href="#a39668000392fa4abbd587966a42db47da6e93116b6b71d16d2c84db906e6e5128">G</a>, <a href="#a39668000392fa4abbd587966a42db47dae9dc5301a4703fd8f71e8ae4796d4dfe">L</a> and <a href="#a39668000392fa4abbd587966a42db47da07aed9a1d212a4e0b332ebe5730377da">NE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a069e11f50fb0348dacac4b0ad2715bbe">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPrp</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstevaluator/#a3a175283278a754c84b75df5e20c5796">anonymous{HexagonConstPropagation.cpp}::MachineConstEvaluator::evaluateCMPrr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonconstpropagation-cpp">HexagonConstPropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
