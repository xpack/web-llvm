---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/pattern/numericvariablematch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `NumericVariableMatch` Struct

<p>Structure representing the definition of a numeric variable in a pattern. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Pattern::NumericVariableMatch { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1ee261f94dab956e08e61aaa1eed845">DefinedNumericVariable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to class instance holding the value and matching format of the numeric variable being defined. <a href="#ae1ee261f94dab956e08e61aaa1eed845">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f94933a76053da4792be2b5c346b92">CaptureParenGroup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of the parenthesis group in RegExStr that captures the value of this numeric variable definition. <a href="#a95f94933a76053da4792be2b5c346b92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Structure representing the definition of a numeric variable in a pattern.</p>


<p>It holds the pointer to the class instance holding the value and matching format of the numeric variable whose value is being defined and the number of the parenthesis group in RegExStr to capture that value.</p>


<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CaptureParenGroup {#a95f94933a76053da4792be2b5c346b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Pattern::NumericVariableMatch::CaptureParenGroup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of the parenthesis group in RegExStr that captures the value of this numeric variable definition.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### DefinedNumericVariable {#ae1ee261f94dab956e08e61aaa1eed845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NumericVariable* llvm::Pattern::NumericVariableMatch::DefinedNumericVariable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to class instance holding the value and matching format of the numeric variable being defined.</p>

<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
