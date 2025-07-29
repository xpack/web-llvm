---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/funcmergeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FuncMergeInfo` Struct

<p>Tuple to hold function info to process merging. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct FuncMergeInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2096b0c132a6a66c31391b7794725754">FuncMergeInfo</a> (StableFunctionMap::StableFunctionEntry *SF, Function *F, IndexInstrMap *IndexInstruction)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionMap::StableFunctionEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab0f44651c414878be6e7589dd4a6aec">SF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbc07e203c7a5d23a2cb6a3e5e77ed1a">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a439bd5f3a661cbf4b5e546a765998732">IndexInstrMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5af8ad15a95ec53c20682996d936686">IndexInstruction</a></td>
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

<p>Tuple to hold function info to process merging.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp">GlobalMergeFunctions.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FuncMergeInfo() {#a2096b0c132a6a66c31391b7794725754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncMergeInfo::FuncMergeInfo (<a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap/stablefunctionentry">StableFunctionMap::StableFunctionEntry</a> * SF, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/namespaces/llvm/#a439bd5f3a661cbf4b5e546a765998732">IndexInstrMap</a> * IndexInstruction)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp">GlobalMergeFunctions.cpp</a>.</p>


<p>References <a href="#abbc07e203c7a5d23a2cb6a3e5e77ed1a">F</a>, <a href="#ae5af8ad15a95ec53c20682996d936686">IndexInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#aab0f44651c414878be6e7589dd4a6aec">SF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### F {#abbc07e203c7a5d23a2cb6a3e5e77ed1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* FuncMergeInfo::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp">GlobalMergeFunctions.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a> and <a href="#a2096b0c132a6a66c31391b7794725754">FuncMergeInfo</a>.</p>

</div>
</div>

### IndexInstruction {#ae5af8ad15a95ec53c20682996d936686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexInstrMap* FuncMergeInfo::IndexInstruction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp">GlobalMergeFunctions.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a> and <a href="#a2096b0c132a6a66c31391b7794725754">FuncMergeInfo</a>.</p>

</div>
</div>

### SF {#aab0f44651c414878be6e7589dd4a6aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StableFunctionMap::StableFunctionEntry* FuncMergeInfo::SF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp">GlobalMergeFunctions.cpp</a>.</p>


<p>Referenced by <a href="#a2096b0c132a6a66c31391b7794725754">FuncMergeInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp">GlobalMergeFunctions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
