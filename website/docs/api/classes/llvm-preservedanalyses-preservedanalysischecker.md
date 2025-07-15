---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/preservedanalyses/preservedanalysischecker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PreservedAnalysisChecker` Class Reference

<p>A checker object that makes it easy to query for whether an analysis or some set covering it is preserved. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PreservedAnalyses::PreservedAnalysisChecker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">llvm/IR/Analysis.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95bf63b09676aa0018e54d1592c7d912">PreservedAnalyses</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a23e26ba9eb94d4f75bc75bb459a6fa">PreservedAnalysisChecker</a> (const PreservedAnalyses &amp;PA, AnalysisKey *ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/preservedanalysischecker">PreservedAnalysisChecker</a> is tied to a particular Analysis because <span class="doxyComputerOutput"><a href="#a2f84945a09787006fe8e0c94e1de89f1">preserved()</a></span> and <span class="doxyComputerOutput"><a href="#abaaa2690a96aed712836f8f292d8128c">preservedSet()</a></span> both return false if the Analysis was abandoned. <a href="#a4a23e26ba9eb94d4f75bc75bb459a6fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f84945a09787006fe8e0c94e1de89f1">preserved</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the checker's analysis was not abandoned and either. <a href="#a2f84945a09787006fe8e0c94e1de89f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ecc8b3108b550239565f675adfd6f8">preservedWhenStateless</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the checker's analysis was not abandoned, i.e. <a href="#a48ecc8b3108b550239565f675adfd6f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisSetT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abaaa2690a96aed712836f8f292d8128c">preservedSet</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the checker's analysis was not abandoned and either. <a href="#abaaa2690a96aed712836f8f292d8128c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c91b1d13ea50f6f8d5aa54f7bff22e">PA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8403791c6f149578573745f42da4585e">ID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd4ed40f8a35fa001f31ca2c42d701f">IsAbandoned</a></td>
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

<p>A checker object that makes it easy to query for whether an analysis or some set covering it is preserved.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<div class="doxySectionDef">

## Friends

### PreservedAnalyses {#a95bf63b09676aa0018e54d1592c7d912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a> and <a href="#a95bf63b09676aa0018e54d1592c7d912">PreservedAnalyses</a>.</p>


<p>Referenced by <a href="#a95bf63b09676aa0018e54d1592c7d912">PreservedAnalyses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### PreservedAnalysisChecker() {#a4a23e26ba9eb94d4f75bc75bb459a6fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PreservedAnalyses::PreservedAnalysisChecker::PreservedAnalysisChecker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA, <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/preservedanalysischecker">PreservedAnalysisChecker</a> is tied to a particular Analysis because <span class="doxyComputerOutput"><a href="#a2f84945a09787006fe8e0c94e1de89f1">preserved()</a></span> and <span class="doxyComputerOutput"><a href="#abaaa2690a96aed712836f8f292d8128c">preservedSet()</a></span> both return false if the Analysis was abandoned.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### preserved() {#a2f84945a09787006fe8e0c94e1de89f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalyses::PreservedAnalysisChecker::preserved ()</td>
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

<p>Returns true if the checker's analysis was not abandoned and either.</p>


<ul class="doxyList ">
<li>the analysis is explicitly preserved or</li>
<li>all analyses are preserved.</li>
</ul>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

### preservedSet() {#abaaa2690a96aed712836f8f292d8128c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisSetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalyses::PreservedAnalysisChecker::preservedSet ()</td>
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

<p>Returns true if the checker's analysis was not abandoned and either.</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">AnalysisSetT</span> is explicitly preserved or</li>
<li>all analyses are preserved.</li>
</ul>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

### preservedWhenStateless() {#a48ecc8b3108b550239565f675adfd6f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalyses::PreservedAnalysisChecker::preservedWhenStateless ()</td>
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

<p>Return true if the checker's analysis was not abandoned, i.e.</p>


<p>it was not explicitly invalidated. Even if the analysis is not explicitly preserved, if the analysis is known stateless, then it is preserved.</p>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/shouldrunextrapasses/result/#afb0d98d85d8f59895de32dd450f0f0ef">llvm::ShouldRunExtraPasses&lt; MarkerTy &gt;::Result::invalidate</a> and <a href="/web-llvm/docs/api/structs/llvm/shouldrunextrapasses/result/#aa7d7720f8274811cf36bc0bfae1ec0fe">llvm::ShouldRunExtraPasses&lt; MarkerTy &gt;::Result::invalidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ID {#a8403791c6f149578573745f42da4585e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisKey* const llvm::PreservedAnalyses::PreservedAnalysisChecker::ID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

### IsAbandoned {#a9cd4ed40f8a35fa001f31ca2c42d701f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PreservedAnalyses::PreservedAnalysisChecker::IsAbandoned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

### PA {#a90c91b1d13ea50f6f8d5aa54f7bff22e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PreservedAnalyses&amp; llvm::PreservedAnalyses::PreservedAnalysisChecker::PA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
