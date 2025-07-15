---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-calledvaluepropagation-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{CalledValuePropagation.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{CalledValuePropagation.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticefunc">CVPLatticeFunc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The custom lattice function used by the generic sparse propagation solver. <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticefunc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval">CVPLatticeVal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The lattice value type used by our custom lattice function. <a href="/web-llvm/docs/api/classes/anonymous-calledvaluepropagation-cpp-/cvplatticeval/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f1b84f271a81d82529c9325b602ac5">CVPLatticeKey</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 2, <a href="#a5f10072974ec01bdf70a2f2215f44b23">IPOGrouping</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Our LatticeKeys are PointerIntPairs composed of LLVM values and groupings. <a href="#ad7f1b84f271a81d82529c9325b602ac5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">IPOGrouping { <a href="#a5f10072974ec01bdf70a2f2215f44b23">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To enable interprocedural analysis, we assign LLVM values to the following groups. <a href="#a5f10072974ec01bdf70a2f2215f44b23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### CVPLatticeKey {#ad7f1b84f271a81d82529c9325b602ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{CalledValuePropagation.cpp}::CVPLatticeKey =  PointerIntPair&lt;Value *, 2, IPOGrouping&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Our LatticeKeys are PointerIntPairs composed of LLVM values and groupings.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### IPOGrouping {#a5f10072974ec01bdf70a2f2215f44b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{CalledValuePropagation.cpp}::IPOGrouping </td>
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

<p>To enable interprocedural analysis, we assign LLVM values to the following groups.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="a5f10072974ec01bdf70a2f2215f44b23a0ba7583639a274c434bbe6ef797115a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Return<a id="a5f10072974ec01bdf70a2f2215f44b23a988fd738de9c6d177440c5dcf69e73ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Memory<a id="a5f10072974ec01bdf70a2f2215f44b23a4789f23283b3a61f858b641a1bef19a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>The register group represents SSA registers, the return group represents the return values of functions, and the memory group represents in-memory values. An LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> can technically be in more than one group. It's necessary to distinguish these groups so we can, for example, track a global variable separately from the value stored at its location.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/calledvaluepropagation-cpp">CalledValuePropagation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
