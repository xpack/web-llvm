---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/stablefunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `StableFunction` Struct Reference

<p>A stable function is a function with a stable hash while tracking the locations of ignored operands and their hashes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::StableFunction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">llvm/CGData/StableFunctionMap.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4061031e97978bb2f1829ef1daa9b4">StableFunction</a> (stable_hash Hash, const std::string FunctionName, const std::string ModuleName, unsigned InstCount, IndexOperandHashVecType &amp;&amp;IndexOperandHashes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3847314bbdcaac61b35e4e54f7a21f28">StableFunction</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4160d6e77dbb5b25f23b6f1f6d9b4f83">Hash</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The combined stable hash of the function. <a href="#a4160d6e77dbb5b25f23b6f1f6d9b4f83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de5f1f3ae4e36aaa15aec79a93d995a">FunctionName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name of the function. <a href="#a7de5f1f3ae4e36aaa15aec79a93d995a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93885e24acc70053d70cf42811702fd0">ModuleName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name of the module the function is in. <a href="#a93885e24acc70053d70cf42811702fd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b231c403b8117798c42f645234a9df">InstCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of instructions. <a href="#a26b231c403b8117798c42f645234a9df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a52a608ceb0e77670a4eee81bbe3065dc">IndexOperandHashVecType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dad29ce5f34b56acee9abf3266c8a9d">IndexOperandHashes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A vector of pairs of <a href="/web-llvm/docs/api/namespaces/llvm/#aac5c174796045b79a15a2bd17ced0d6f">IndexPair</a> and operand hash which was skipped. <a href="#a7dad29ce5f34b56acee9abf3266c8a9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A stable function is a function with a stable hash while tracking the locations of ignored operands and their hashes.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StableFunction() {#a3f4061031e97978bb2f1829ef1daa9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StableFunction::StableFunction (<a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> Hash, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string FunctionName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string ModuleName, unsigned InstCount, <a href="/web-llvm/docs/api/namespaces/llvm/#a52a608ceb0e77670a4eee81bbe3065dc">IndexOperandHashVecType</a> &amp;&amp; IndexOperandHashes)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>References <a href="#a7de5f1f3ae4e36aaa15aec79a93d995a">FunctionName</a>, <a href="#a4160d6e77dbb5b25f23b6f1f6d9b4f83">Hash</a>, <a href="#a7dad29ce5f34b56acee9abf3266c8a9d">IndexOperandHashes</a>, <a href="#a26b231c403b8117798c42f645234a9df">InstCount</a>, <a href="#a93885e24acc70053d70cf42811702fd0">ModuleName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### StableFunction() {#a3847314bbdcaac61b35e4e54f7a21f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StableFunction::StableFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FunctionName {#a7de5f1f3ae4e36aaa15aec79a93d995a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::StableFunction::FunctionName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The name of the function.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a3f4061031e97978bb2f1829ef1daa9b4">StableFunction</a>.</p>

</div>
</div>

### Hash {#a4160d6e77dbb5b25f23b6f1f6d9b4f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">stable_hash llvm::StableFunction::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The combined stable hash of the function.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a3f4061031e97978bb2f1829ef1daa9b4">StableFunction</a>.</p>

</div>
</div>

### IndexOperandHashes {#a7dad29ce5f34b56acee9abf3266c8a9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexOperandHashVecType llvm::StableFunction::IndexOperandHashes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A vector of pairs of <a href="/web-llvm/docs/api/namespaces/llvm/#aac5c174796045b79a15a2bd17ced0d6f">IndexPair</a> and operand hash which was skipped.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a3f4061031e97978bb2f1829ef1daa9b4">StableFunction</a>.</p>

</div>
</div>

### InstCount {#a26b231c403b8117798c42f645234a9df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StableFunction::InstCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of instructions.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a3f4061031e97978bb2f1829ef1daa9b4">StableFunction</a>.</p>

</div>
</div>

### ModuleName {#a93885e24acc70053d70cf42811702fd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::StableFunction::ModuleName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The name of the module the function is in.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a3f4061031e97978bb2f1829ef1daa9b4">StableFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
