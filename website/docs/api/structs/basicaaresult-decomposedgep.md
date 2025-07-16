---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/basicaaresult/decomposedgep
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DecomposedGEP` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct BasicAAResult::DecomposedGEP { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5503232cd0270bf1b8bbc9d20d2c1929">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6a79f54408f9804ecf731ebe2897402">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57d1889b11e506f479c09fbe1e46d6b">Base</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e79baab2c3368abbb6de9d066116f90">Offset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; VariableGEPIndex, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c5c4813442dde9c6f2143f6527ab30">VarIndices</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf9633eb0bf2cfdf1aa958070d1c0a0d">NWFlags</a> = GEPNoWrapFlags::all()</td>
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


<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#a5503232cd0270bf1b8bbc9d20d2c1929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicAAResult::DecomposedGEP::dump ()</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ab6a79f54408f9804ecf731ebe2897402">llvm::BasicAAResult::DecomposedGEP::print</a>.</p>

</div>
</div>

### print() {#ab6a79f54408f9804ecf731ebe2897402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicAAResult::DecomposedGEP::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>References <a href="#ab57d1889b11e506f479c09fbe1e46d6b">llvm::BasicAAResult::DecomposedGEP::Base</a>, <a href="#abf9633eb0bf2cfdf1aa958070d1c0a0d">llvm::BasicAAResult::DecomposedGEP::NWFlags</a>, <a href="#a3e79baab2c3368abbb6de9d066116f90">llvm::BasicAAResult::DecomposedGEP::Offset</a> and <a href="#aa5c5c4813442dde9c6f2143f6527ab30">llvm::BasicAAResult::DecomposedGEP::VarIndices</a>.</p>


<p>Referenced by <a href="#a5503232cd0270bf1b8bbc9d20d2c1929">llvm::BasicAAResult::DecomposedGEP::dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Base {#ab57d1889b11e506f479c09fbe1e46d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* llvm::BasicAAResult::DecomposedGEP::Base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ab6a79f54408f9804ecf731ebe2897402">llvm::BasicAAResult::DecomposedGEP::print</a>.</p>

</div>
</div>

### NWFlags {#abf9633eb0bf2cfdf1aa958070d1c0a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::BasicAAResult::DecomposedGEP::NWFlags = GEPNoWrapFlags::all()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ab6a79f54408f9804ecf731ebe2897402">llvm::BasicAAResult::DecomposedGEP::print</a>.</p>

</div>
</div>

### Offset {#a3e79baab2c3368abbb6de9d066116f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::BasicAAResult::DecomposedGEP::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ab6a79f54408f9804ecf731ebe2897402">llvm::BasicAAResult::DecomposedGEP::print</a>.</p>

</div>
</div>

### VarIndices {#aa5c5c4813442dde9c6f2143f6527ab30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VariableGEPIndex, 4&gt; llvm::BasicAAResult::DecomposedGEP::VarIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp">BasicAliasAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#ab6a79f54408f9804ecf731ebe2897402">llvm::BasicAAResult::DecomposedGEP::print</a>.</p>

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
