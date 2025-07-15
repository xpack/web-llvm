---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lineeditor/completionaction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CompletionAction` Struct Reference

<p>The action to perform upon a completion request. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LineEditor::CompletionAction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">llvm/LineEditor/LineEditor.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ActionKind { <a href="#ac232b5a8e51db460ca00d6122f0db70e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac232b5a8e51db460ca00d6122f0db70e">ActionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d8e514dd4b30f8f3d0a59b0f8b989b5">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146daa7ce4b2082c567ed6f4e75c32ac">Text</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The text to insert. <a href="#a146daa7ce4b2082c567ed6f4e75c32ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5632d03f14b73ad8110f8f573c302846">Completions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of completions to show. <a href="#a5632d03f14b73ad8110f8f573c302846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The action to perform upon a completion request.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ActionKind {#ac232b5a8e51db460ca00d6122f0db70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LineEditor::CompletionAction::ActionKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_Insert<a id="ac232b5a8e51db460ca00d6122f0db70ea71f426eb85c217d0b6213c099ac405ae"></a></td>
<td class="doxyEnumItemDescription">Insert Text at the cursor position</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AK_ShowCompletions<a id="ac232b5a8e51db460ca00d6122f0db70ea44496236f3d5e0a77dc12f50d7d2d6cc"></a></td>
<td class="doxyEnumItemDescription">Show Completions, or beep if the list is empty</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Completions {#a5632d03f14b73ad8110f8f573c302846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::LineEditor::CompletionAction::Completions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of completions to show.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-lineeditor-cpp-/#a14821b1527e2996ff605a761fb0a719f">anonymous{LineEditor.cpp}::ElCompletionFn</a>.</p>

</div>
</div>

### Kind {#a5d8e514dd4b30f8f3d0a59b0f8b989b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ActionKind llvm::LineEditor::CompletionAction::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-lineeditor-cpp-/#a14821b1527e2996ff605a761fb0a719f">anonymous{LineEditor.cpp}::ElCompletionFn</a> and <a href="/web-llvm/docs/api/classes/llvm/lineeditor/#a2c9715831437239c8b4aebeb3772ba7b">llvm::LineEditor::getCompletionAction</a>.</p>

</div>
</div>

### Text {#a146daa7ce4b2082c567ed6f4e75c32ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LineEditor::CompletionAction::Text</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The text to insert.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-lineeditor-cpp-/#a14821b1527e2996ff605a761fb0a719f">anonymous{LineEditor.cpp}::ElCompletionFn</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lineeditor/lineeditor-h">LineEditor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
