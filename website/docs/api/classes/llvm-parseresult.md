---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/parseresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ParseResult` Class

<p>This class represents success/failure for parsing-like operations that find it important to chain together failable operations with <span class="doxyComputerOutput">||</span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ParseResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">llvm/Support/LogicalResult.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents an efficient way to signal success or failure. <a href="/web-llvm/docs/api/structs/llvm/logicalresult/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8e93421614220a28c4c685de257b15">ParseResult</a> (LogicalResult Result=success())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d8feb4584f75764e82340ac35ac9a5">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Failure is true in a boolean context. <a href="#a08d8feb4584f75764e82340ac35ac9a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class represents success/failure for parsing-like operations that find it important to chain together failable operations with <span class="doxyComputerOutput">||</span>.</p>


<p>This is an extended version of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a></span> that allows for explicit conversion to bool.</p>


<p>This class should not be used for general error handling cases - we prefer to keep the logic explicit with the <span class="doxyComputerOutput">succeeded</span>/<span class="doxyComputerOutput">failed</span> predicates. However, traditional monadic-style parsing logic can sometimes get swallowed up in boilerplate without this, so we provide this for narrow cases where it is important.</p>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ParseResult() {#a1c8e93421614220a28c4c685de257b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ParseResult::ParseResult (<a href="/web-llvm/docs/api/structs/llvm/logicalresult">LogicalResult</a> Result=<a href="/web-llvm/docs/api/structs/llvm/logicalresult/#ac3732ee5a111ea78dec325ea8c561fa8">success</a>())</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/logicalresult/#ac3732ee5a111ea78dec325ea8c561fa8">llvm::LogicalResult::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a08d8feb4584f75764e82340ac35ac9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ParseResult::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Failure is true in a boolean context.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/logicalresult/#ab2850b11db804ad8b3f8fdc05c692619">llvm::LogicalResult::failed</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/logicalresult-h">LogicalResult.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
