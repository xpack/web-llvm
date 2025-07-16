---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/instraspect
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `InstrAspect` Struct Reference

<p>Legalization is decided based on an instruction's opcode, which type slot we're considering, and what the existing type is. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::InstrAspect { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">llvm/CodeGen/GlobalISel/LegacyLegalizerInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51dbb4cb930d5b9b444d2fc3372b8514">InstrAspect</a> (unsigned Opcode, LLT Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9737ca8026fefb9180f30e7af3a9da5c">InstrAspect</a> (unsigned Opcode, unsigned Idx, LLT Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3acdbe3de61b1d154667cfe79cadf9">operator==</a> (const InstrAspect &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a638726ef52ca6b3b3c100a2da460c26a">Opcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356ff22c5336071aac58e00b736a269c">Idx</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd53ad2aadf9052aa97b22bb1951529">Type</a></td>
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

<p>Legalization is decided based on an instruction's opcode, which type slot we're considering, and what the existing type is.</p>


<p>These aspects are gathered together for convenience in the <a href="/web-llvm/docs/api/structs/llvm/instraspect">InstrAspect</a> class.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrAspect() {#a51dbb4cb930d5b9b444d2fc3372b8514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrAspect::InstrAspect (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Type)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>References <a href="#a638726ef52ca6b3b3c100a2da460c26a">Opcode</a> and <a href="#a4bd53ad2aadf9052aa97b22bb1951529">Type</a>.</p>


<p>Referenced by <a href="#a1d3acdbe3de61b1d154667cfe79cadf9">operator==</a>.</p>

</div>
</div>

### InstrAspect() {#a9737ca8026fefb9180f30e7af3a9da5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrAspect::InstrAspect (unsigned Opcode, unsigned Idx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Type)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>References <a href="#a356ff22c5336071aac58e00b736a269c">Idx</a>, <a href="#a638726ef52ca6b3b3c100a2da460c26a">Opcode</a> and <a href="#a4bd53ad2aadf9052aa97b22bb1951529">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#a1d3acdbe3de61b1d154667cfe79cadf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrAspect::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instraspect">InstrAspect</a> &amp; RHS)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>References <a href="#a356ff22c5336071aac58e00b736a269c">Idx</a>, <a href="#a51dbb4cb930d5b9b444d2fc3372b8514">InstrAspect</a>, <a href="#a638726ef52ca6b3b3c100a2da460c26a">Opcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a4bd53ad2aadf9052aa97b22bb1951529">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Idx {#a356ff22c5336071aac58e00b736a269c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstrAspect::Idx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#a9737ca8026fefb9180f30e7af3a9da5c">InstrAspect</a>, <a href="#a1d3acdbe3de61b1d154667cfe79cadf9">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a9ed946c9bc8e7367d6a31582048c8570">llvm::LegacyLegalizerInfo::setAction</a>.</p>

</div>
</div>

### Opcode {#a638726ef52ca6b3b3c100a2da460c26a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstrAspect::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#a51dbb4cb930d5b9b444d2fc3372b8514">InstrAspect</a>, <a href="#a9737ca8026fefb9180f30e7af3a9da5c">InstrAspect</a>, <a href="#a1d3acdbe3de61b1d154667cfe79cadf9">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a9ed946c9bc8e7367d6a31582048c8570">llvm::LegacyLegalizerInfo::setAction</a>.</p>

</div>
</div>

### Type {#a4bd53ad2aadf9052aa97b22bb1951529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::InstrAspect::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>


<p>Referenced by <a href="#a51dbb4cb930d5b9b444d2fc3372b8514">InstrAspect</a>, <a href="#a9737ca8026fefb9180f30e7af3a9da5c">InstrAspect</a>, <a href="#a1d3acdbe3de61b1d154667cfe79cadf9">operator==</a> and <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a9ed946c9bc8e7367d6a31582048c8570">llvm::LegacyLegalizerInfo::setAction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
