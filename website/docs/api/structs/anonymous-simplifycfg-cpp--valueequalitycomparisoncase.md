---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-simplifycfg-cpp-/valueequalitycomparisoncase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ValueEqualityComparisonCase` Struct Reference

<p><a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/valueequalitycomparisoncase">ValueEqualityComparisonCase</a> - Represents a case of a switch. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{SimplifyCFG.cpp}::ValueEqualityComparisonCase { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b935cc2b06bb94c85ad18681414e1e8">ValueEqualityComparisonCase</a> (ConstantInt *Value, BasicBlock *Dest)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2eb42530edb66efe5ae339eea73903">operator&lt;</a> (ValueEqualityComparisonCase RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83cca3e08c2faab34ac6657b3f12b121">operator==</a> (BasicBlock *RHSDest) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c4698c87ab764e96adc93a80f46c87">Value</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba0e937fa0ed27cb0278db8cbc46648">Dest</a></td>
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

<p><a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/valueequalitycomparisoncase">ValueEqualityComparisonCase</a> - Represents a case of a switch.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueEqualityComparisonCase() {#a6b935cc2b06bb94c85ad18681414e1e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SimplifyCFG.cpp}::ValueEqualityComparisonCase::ValueEqualityComparisonCase (<a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Value, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dest)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>References <a href="#a6ba0e937fa0ed27cb0278db8cbc46648">Dest</a> and <a href="#a98c4698c87ab764e96adc93a80f46c87">Value</a>.</p>


<p>Referenced by <a href="#abe2eb42530edb66efe5ae339eea73903">operator&lt;</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a159c35fe8089d7348efef90d098aecbe">valuesOverlap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#abe2eb42530edb66efe5ae339eea73903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyCFG.cpp}::ValueEqualityComparisonCase::operator&lt; (<a href="/web-llvm/docs/api/structs/anonymous-simplifycfg-cpp-/valueequalitycomparisoncase">ValueEqualityComparisonCase</a> RHS)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>References <a href="#a98c4698c87ab764e96adc93a80f46c87">Value</a> and <a href="#a6b935cc2b06bb94c85ad18681414e1e8">ValueEqualityComparisonCase</a>.</p>

</div>
</div>

### operator==() {#a83cca3e08c2faab34ac6657b3f12b121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyCFG.cpp}::ValueEqualityComparisonCase::operator== (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * RHSDest)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>Reference <a href="#a6ba0e937fa0ed27cb0278db8cbc46648">Dest</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Dest {#a6ba0e937fa0ed27cb0278db8cbc46648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{SimplifyCFG.cpp}::ValueEqualityComparisonCase::Dest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>Referenced by <a href="#a83cca3e08c2faab34ac6657b3f12b121">operator==</a> and <a href="#a6b935cc2b06bb94c85ad18681414e1e8">ValueEqualityComparisonCase</a>.</p>

</div>
</div>

### Value {#a98c4698c87ab764e96adc93a80f46c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt* anonymous{SimplifyCFG.cpp}::ValueEqualityComparisonCase::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a>.</p>


<p>Referenced by <a href="#abe2eb42530edb66efe5ae339eea73903">operator&lt;</a> and <a href="#a6b935cc2b06bb94c85ad18681414e1e8">ValueEqualityComparisonCase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp">SimplifyCFG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
