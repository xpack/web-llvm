---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-basicaliasanalysis-cpp-/variablegepindex
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VariableGEPIndex` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab484b7e8c62b07c22c9fdbb7d118d5ea">hasNegatedScaleOf</a> (const VariableGEPIndex &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a488bff1f7c16c479309a8e7f76590c95">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b019f7bf1f5a21a3387649a70854c0">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue">CastedValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecadc344a5ad027665b76180d0ea3706">Val</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a160a990855e479d5538db85c3793fba0">Scale</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad914e7e54eade4bffa8b9c20567a6d78">CxtI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c698e309a9e5eac62491e9e3f23a80">IsNSW</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if all operations in this expression are NSW. <a href="#ad6c698e309a9e5eac62491e9e3f23a80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a0916b4e753daa2448c0d34c61d226">IsNegated</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the index should be subtracted rather than added. <a href="#a78a0916b4e753daa2448c0d34c61d226">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#a488bff1f7c16c479309a8e7f76590c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::dump ()</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### hasNegatedScaleOf() {#ab484b7e8c62b07c22c9fdbb7d118d5ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::hasNegatedScaleOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/variablegepindex">VariableGEPIndex</a> &amp; Other)</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a78a0916b4e753daa2448c0d34c61d226">IsNegated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a160a990855e479d5538db85c3793fba0">Scale</a>.</p>

</div>
</div>

### print() {#a78b019f7bf1f5a21a3387649a70854c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#a78a0916b4e753daa2448c0d34c61d226">IsNegated</a>, <a href="#ad6c698e309a9e5eac62491e9e3f23a80">IsNSW</a>, <a href="#a160a990855e479d5538db85c3793fba0">Scale</a> and <a href="#aecadc344a5ad027665b76180d0ea3706">Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CxtI {#ad914e7e54eade4bffa8b9c20567a6d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction* anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::CxtI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>

</div>
</div>

### IsNegated {#a78a0916b4e753daa2448c0d34c61d226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::IsNegated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the index should be subtracted rather than added.</p>


<p>We don't simply negate the Scale, to avoid losing the NSW flag: X - INT_MIN*1 may be non-wrapping, while X + INT_MIN*(-1) wraps.</p>


<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ab484b7e8c62b07c22c9fdbb7d118d5ea">hasNegatedScaleOf</a> and <a href="#a78b019f7bf1f5a21a3387649a70854c0">print</a>.</p>

</div>
</div>

### IsNSW {#ad6c698e309a9e5eac62491e9e3f23a80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::IsNSW</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if all operations in this expression are NSW.</p>

<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a78b019f7bf1f5a21a3387649a70854c0">print</a>.</p>

</div>
</div>

### Scale {#a160a990855e479d5538db85c3793fba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::Scale</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ab484b7e8c62b07c22c9fdbb7d118d5ea">hasNegatedScaleOf</a> and <a href="#a78b019f7bf1f5a21a3387649a70854c0">print</a>.</p>

</div>
</div>

### Val {#aecadc344a5ad027665b76180d0ea3706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CastedValue anonymous{BasicAliasAnalysis.cpp}::VariableGEPIndex::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a78b019f7bf1f5a21a3387649a70854c0">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
