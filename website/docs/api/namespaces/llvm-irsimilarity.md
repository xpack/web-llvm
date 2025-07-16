---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/irsimilarity
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `IRSimilarity` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::IRSimilarity { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This provides the utilities for hashing an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to an unsigned integer. <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatatraits">IRInstructionDataTraits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper">IRInstructionMapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper struct for converting the Instructions in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> into a vector of unsigned integers. <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a class that wraps a range of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> from one point to another in the vector of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>, which is a region of the program. <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier">IRSimilarityIdentifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class puts all the pieces of the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper">IRInstructionMapper</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> together. <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> *, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &gt; &gt; <a href="#a571ce20405d1f17def16f22f09dda2f3">CandidateGVNMapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &gt; <a href="#a2198f86ce16da838bdeea4de7e59ef31">SimilarityGroup</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="#a2198f86ce16da838bdeea4de7e59ef31">SimilarityGroup</a> &gt; <a href="#a1e2d2e59b2467bacdc6db54dcc9bc4a1">SimilarityGroupList</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InstrType { <a href="#af46430106334db52bfa7a4107e53a0bd">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents what is and is not supported when finding similarity in Instructions. <a href="#af46430106334db52bfa7a4107e53a0bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7518d710d81c7c4c04cc6a61e7d65bc">isClose</a> (const IRInstructionData &amp;A, const IRInstructionData &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare one <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> class to another <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> class for whether they are performing a the same operation, and can mapped to the same value. <a href="#ad7518d710d81c7c4c04cc6a61e7d65bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### CandidateGVNMapping {#a571ce20405d1f17def16f22f09dda2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef DenseMap&lt;IRSimilarityCandidate *, DenseMap&lt;unsigned, DenseSet&lt;unsigned&gt; &gt; &gt; llvm::IRSimilarity::CandidateGVNMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### SimilarityGroup {#a2198f86ce16da838bdeea4de7e59ef31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;IRSimilarityCandidate&gt; llvm::IRSimilarity::SimilarityGroup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### SimilarityGroupList {#a1e2d2e59b2467bacdc6db54dcc9bc4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;SimilarityGroup&gt; llvm::IRSimilarity::SimilarityGroupList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### InstrType {#af46430106334db52bfa7a4107e53a0bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::IRSimilarity::InstrType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This represents what is and is not supported when finding similarity in Instructions.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Legal<a id="af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Illegal<a id="af46430106334db52bfa7a4107e53a0bda16a84ba67d52e1c64fb48ce437b569ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invisible<a id="af46430106334db52bfa7a4107e53a0bda47b7bba75c0c242b40fece427c2bfefa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Legal Instructions are considered when looking at similarity between Instructions.</p>


<p>Illegal Instructions cannot be considered when looking for similarity between Instructions. They act as boundaries between similarity regions.</p>


<p>Invisible Instructions are skipped over during analysis.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### isClose() {#ad7518d710d81c7c4c04cc6a61e7d65bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::isClose (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare one <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> class to another <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> class for whether they are performing a the same operation, and can mapped to the same value.</p>


<p>For regular instructions if the hash value is the same, then they will also be close.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- The first <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> class to compare</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">B</td>
<td class="doxyParamItemDescription"><p>- The second <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> class to compare</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> are similar enough to be mapped to the same value.</p></dd>
</dl>


<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a2d2b8c755a8e7b54f4680d27cd40d244">llvm::IRSimilarity::IRSimilarityCandidate::compareStructure</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatatraits/#aa90a0f17e48708b50476fc417398d2a0">llvm::IRSimilarity::IRInstructionDataTraits::isEqual</a> and <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a23d2b4941adb672f1a2ce945399065e3">llvm::IRSimilarity::IRSimilarityCandidate::isSimilar</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
