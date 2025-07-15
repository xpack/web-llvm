---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-slpvectorizer-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{SLPVectorizer.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{SLPVectorizer.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis">BaseShuffleAnalysis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base class for shuffle instruction emission and shuffle cost estimation. <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction">HorizontalReduction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Model horizontal reductions. <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate">InstructionsState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main data required for vectorization of instructions. <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/phihandler">PHIHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows to correctly handle operands of the phi nodes based on the <span class="doxyComputerOutput">Main</span> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> order of incoming basic blocks/values. <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/phihandler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/shuffledinsertdata">ShuffledInsertData&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data type for handling buildvector sequences with the reused scalars from other tree entries. <a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/shuffledinsertdata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/valueselect">ValueSelect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns incoming <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, if the requested type is <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * too, or a default value, otherwise. <a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/valueselect/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">UseMask { <a href="#a600545eb53de812fc4daae8ecb72199d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifies the way the mask should be analyzed for undefs/poisonous elements in the shuffle mask. <a href="#a600545eb53de812fc4daae8ecb72199d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### UseMask {#a600545eb53de812fc4daae8ecb72199d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{SLPVectorizer.cpp}::UseMask </td>
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

<p>Specifies the way the mask should be analyzed for undefs/poisonous elements in the shuffle mask.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstArg<a id="a600545eb53de812fc4daae8ecb72199da8545ba2c4d270d3cca72fb93da2a21d8"></a></td>
<td class="doxyEnumItemDescription">The mask is expected to be for permutation of 1-2 vectors, check for the mask elements for the first argument (mask indices are in range [0:VF))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SecondArg<a id="a600545eb53de812fc4daae8ecb72199da018f3de8f2e77f6f34af68e83516cb9f"></a></td>
<td class="doxyEnumItemDescription">The mask is expected to be for permutation of 2 vectors, check for the mask elements for the second argument (mask indices are in range [VF:2*VF))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UndefsAsMask<a id="a600545eb53de812fc4daae8ecb72199da3e1e09be16e530770bc81cd5f2b2edb9"></a></td>
<td class="doxyEnumItemDescription">Consider undef mask elements (-1) as placeholders for future shuffle elements and mark them as ones as being used in future</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
