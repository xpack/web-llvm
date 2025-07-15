---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/legalizeactionstep
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LegalizeActionStep` Struct Reference

<p>The result of a query. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LegalizeActionStep { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">llvm/CodeGen/GlobalISel/LegalizerInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc655fcd2857e783f1695a7aa55908cd">LegalizeActionStep</a> (LegalizeAction Action, unsigned TypeIdx, const LLT NewType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24f30dfb027fd8d99607a723476154d">LegalizeActionStep</a> (LegacyLegalizeActionStep Step)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8322fca8f6bb875b6dc706aa7532149">operator==</a> (const LegalizeActionStep &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad3bef7dbfe7e650af077cede882b93">Action</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The action to take or the final answer. <a href="#a1ad3bef7dbfe7e650af077cede882b93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafa2d5d36d517a05b8f11d2c96a86de7">TypeIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If describing an action, the type index to change. Otherwise zero. <a href="#aafa2d5d36d517a05b8f11d2c96a86de7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa08931577871b9d39ac4ec02e02291b">NewType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If describing an action, the new type for TypeIdx. Otherwise <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>{}. <a href="#aaa08931577871b9d39ac4ec02e02291b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The result of a query.</p>


<p>It either indicates a final answer of Legal or Unsupported or describes an action that must be taken to make an operation more legal.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LegalizeActionStep() {#acc655fcd2857e783f1695a7aa55908cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LegalizeActionStep::LegalizeActionStep (<a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654">LegalizeAction</a> Action, unsigned TypeIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NewType)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a1ad3bef7dbfe7e650af077cede882b93">Action</a>, <a href="#aaa08931577871b9d39ac4ec02e02291b">NewType</a> and <a href="#aafa2d5d36d517a05b8f11d2c96a86de7">TypeIdx</a>.</p>


<p>Referenced by <a href="#af8322fca8f6bb875b6dc706aa7532149">operator==</a>.</p>

</div>
</div>

### LegalizeActionStep() {#aa24f30dfb027fd8d99607a723476154d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LegalizeActionStep::LegalizeActionStep (<a href="/web-llvm/docs/api/structs/llvm/legacylegalizeactionstep">LegacyLegalizeActionStep</a> Step)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/legacylegalizeactionstep/#a695d326dc57441ca67a0c3615ce5f7a5">llvm::LegacyLegalizeActionStep::Action</a>, <a href="#aaa08931577871b9d39ac4ec02e02291b">NewType</a> and <a href="#aafa2d5d36d517a05b8f11d2c96a86de7">TypeIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#af8322fca8f6bb875b6dc706aa7532149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LegalizeActionStep::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalizeactionstep">LegalizeActionStep</a> &amp; RHS)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>References <a href="#a1ad3bef7dbfe7e650af077cede882b93">Action</a>, <a href="#acc655fcd2857e783f1695a7aa55908cd">LegalizeActionStep</a>, <a href="#aaa08931577871b9d39ac4ec02e02291b">NewType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#aafa2d5d36d517a05b8f11d2c96a86de7">TypeIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Action {#a1ad3bef7dbfe7e650af077cede882b93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeAction llvm::LegalizeActionStep::Action</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The action to take or the final answer.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#af3687eafb2772c29aa67ce722c2081fd">llvm::LegalizerInfo::getAction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#ad428f375c93fc982020034661f54f3b9">llvm::LegalizerInfo::isLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a0a8787f1cdd43e53ef6aad1c28faa505">llvm::LegalizerInfo::isLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a83cf4c51d6ae07b6018d800c0b32d97b">llvm::LegalizerInfo::isLegalOrCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a74bae640f12a6585646720ff477266ea">llvm::LegalizerInfo::isLegalOrCustom</a>, <a href="#acc655fcd2857e783f1695a7aa55908cd">LegalizeActionStep</a>, <a href="#af8322fca8f6bb875b6dc706aa7532149">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a9ef6fa1f344222ac170e33582b82c482">llvm::LegalizationArtifactCombiner::tryCombineUnmergeValues</a>.</p>

</div>
</div>

### NewType {#aaa08931577871b9d39ac4ec02e02291b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::LegalizeActionStep::NewType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If describing an action, the new type for TypeIdx. Otherwise <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>{}.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#aa24f30dfb027fd8d99607a723476154d">LegalizeActionStep</a>, <a href="#acc655fcd2857e783f1695a7aa55908cd">LegalizeActionStep</a> and <a href="#af8322fca8f6bb875b6dc706aa7532149">operator==</a>.</p>

</div>
</div>

### TypeIdx {#aafa2d5d36d517a05b8f11d2c96a86de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LegalizeActionStep::TypeIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If describing an action, the type index to change. Otherwise zero.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#aa24f30dfb027fd8d99607a723476154d">LegalizeActionStep</a>, <a href="#acc655fcd2857e783f1695a7aa55908cd">LegalizeActionStep</a>, <a href="#af8322fca8f6bb875b6dc706aa7532149">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a9ef6fa1f344222ac170e33582b82c482">llvm::LegalizationArtifactCombiner::tryCombineUnmergeValues</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
