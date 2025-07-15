---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/logicalresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LogicalResult` Struct Reference

<p>This class represents an efficient way to signal success or failure. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LogicalResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">llvm/Support/LogicalResult.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parseresult">ParseResult</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents success/failure for parsing-like operations that find it important to chain together failable operations with <span class="doxyComputerOutput">||</span>. <a href="/web-llvm/docs/api/classes/llvm/parseresult/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ecb25522fc56b4e4ff02cc6448f4851">LogicalResult</a> (bool IsSuccess)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf1ae0e1c0d3c1c912fa7c39419072c8">succeeded</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the provided <a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a> corresponds to a success value. <a href="#aaf1ae0e1c0d3c1c912fa7c39419072c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2850b11db804ad8b3f8fdc05c692619">failed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the provided <a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a> corresponds to a failure value. <a href="#ab2850b11db804ad8b3f8fdc05c692619">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7b2d29fdd79e3da2918b4b2248243d">IsSuccess</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> indicating if this is a success result, if false this is a failure result. <a href="#a4e7b2d29fdd79e3da2918b4b2248243d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3732ee5a111ea78dec325ea8c561fa8">success</a> (bool IsSuccess=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If isSuccess is true a <span class="doxyComputerOutput">success</span> result is generated, otherwise a 'failure' result is generated. <a href="#ac3732ee5a111ea78dec325ea8c561fa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a365f10ef68d4a6974526994913150d">failure</a> (bool IsFailure=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If isFailure is true a <span class="doxyComputerOutput">failure</span> result is generated, otherwise a 'success' result is generated. <a href="#a3a365f10ef68d4a6974526994913150d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class represents an efficient way to signal success or failure.</p>


<p>It should be preferred over the use of <span class="doxyComputerOutput">bool</span> when appropriate, as it avoids all of the ambiguity that arises in interpreting a boolean result. This class is marked as NODISCARD to ensure that the result is processed. Users may explicitly discard a result by using <span class="doxyComputerOutput">(void)</span>, e.g. <span class="doxyComputerOutput">(void)functionThatReturnsALogicalResult();</span>. Given the intended nature of this class, it generally shouldn't be used as the result of functions that very frequently have the result ignored. This class is intended to be used in conjunction with the utility functions below.</p>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### LogicalResult() {#a3ecb25522fc56b4e4ff02cc6448f4851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LogicalResult::LogicalResult (bool IsSuccess)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### failed() {#ab2850b11db804ad8b3f8fdc05c692619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LogicalResult::failed ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the provided <a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a> corresponds to a failure value.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/parseresult/#a08d8feb4584f75764e82340ac35ac9a5">llvm::ParseResult::operator bool</a>.</p>

</div>
</div>

### succeeded() {#aaf1ae0e1c0d3c1c912fa7c39419072c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LogicalResult::succeeded ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the provided <a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a> corresponds to a success value.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsSuccess {#a4e7b2d29fdd79e3da2918b4b2248243d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LogicalResult::IsSuccess</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> indicating if this is a success result, if false this is a failure result.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### failure() {#a3a365f10ef68d4a6974526994913150d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LogicalResult llvm::LogicalResult::failure (bool IsFailure=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If isFailure is true a <span class="doxyComputerOutput">failure</span> result is generated, otherwise a 'success' result is generated.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a392cb1caa3784e15ca37df8e6897df42">llvm::failure</a>.</p>

</div>
</div>

### success() {#ac3732ee5a111ea78dec325ea8c561fa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LogicalResult llvm::LogicalResult::success (bool IsSuccess=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If isSuccess is true a <span class="doxyComputerOutput">success</span> result is generated, otherwise a 'failure' result is generated.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/parseresult/#a1c8e93421614220a28c4c685de257b15">llvm::ParseResult::ParseResult</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aea6e51b13067f27d5b9bd39d1f44b670">llvm::success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
