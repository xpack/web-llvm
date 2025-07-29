---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/preservedanalysischecker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PreservedAnalysisChecker` Class

<p>A checker object that makes it easy to query for whether an analysis or some set covering it is preserved. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PreservedAnalysisChecker { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78527a465153f3d7cc889f34582d255">PreservedAnalysisChecker</a> (const PreservedAnalyses &amp;PA, AnalysisKey *ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/preservedanalysischecker">PreservedAnalysisChecker</a> is tied to a particular Analysis because <span class="doxyComputerOutput"><a href="#a96eee8e68a03f258b63510d47436a9f7">preserved()</a></span> and <span class="doxyComputerOutput"><a href="#ad5c5895ea2f2d754cb17aa57faa20836">preservedSet()</a></span> both return false if the Analysis was abandoned. <a href="#ad78527a465153f3d7cc889f34582d255">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96eee8e68a03f258b63510d47436a9f7">preserved</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the checker's analysis was not abandoned and either. <a href="#a96eee8e68a03f258b63510d47436a9f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51961e5eef7b750b19a4107498ab0f6">preservedWhenStateless</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the checker's analysis was not abandoned, i.e. <a href="#ad51961e5eef7b750b19a4107498ab0f6">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5c5895ea2f2d754cb17aa57faa20836">preservedSet</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the checker's analysis was not abandoned and either. <a href="#ad5c5895ea2f2d754cb17aa57faa20836">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a95bf63b09676aa0018e54d1592c7d912">PreservedAnalyses</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0cd761cb1a9c556126040064e36184">PA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eaaa70882c0dffce850cb5855107fbb">ID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dbebb5c085cca678ed87c5046958add">IsAbandoned</a></td>
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
<td class="doxyMemberName">friend class PreservedAnalyses</td>
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

### PreservedAnalysisChecker() {#ad78527a465153f3d7cc889f34582d255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PreservedAnalysisChecker::PreservedAnalysisChecker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a95bf63b09676aa0018e54d1592c7d912">PreservedAnalyses</a> &amp; PA, <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/preservedanalysischecker">PreservedAnalysisChecker</a> is tied to a particular Analysis because <span class="doxyComputerOutput"><a href="#a96eee8e68a03f258b63510d47436a9f7">preserved()</a></span> and <span class="doxyComputerOutput"><a href="#ad5c5895ea2f2d754cb17aa57faa20836">preservedSet()</a></span> both return false if the Analysis was abandoned.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### preserved() {#a96eee8e68a03f258b63510d47436a9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalysisChecker::preserved ()</td>
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

### preservedSet() {#ad5c5895ea2f2d754cb17aa57faa20836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisSetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalysisChecker::preservedSet ()</td>
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

### preservedWhenStateless() {#ad51961e5eef7b750b19a4107498ab0f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalysisChecker::preservedWhenStateless ()</td>
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

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ID {#a5eaaa70882c0dffce850cb5855107fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisKey* const llvm::PreservedAnalysisChecker::ID</td>
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

### IsAbandoned {#a0dbebb5c085cca678ed87c5046958add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::PreservedAnalysisChecker::IsAbandoned</td>
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

### PA {#ada0cd761cb1a9c556126040064e36184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PreservedAnalyses&amp; llvm::PreservedAnalysisChecker::PA</td>
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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
