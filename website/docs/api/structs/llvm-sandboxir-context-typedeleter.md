---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sandboxir/context/typedeleter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TypeDeleter` Struct

<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> has a protected destructor to prohibit the user from managing the lifetime of the <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> objects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::sandboxir::Context::TypeDeleter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">llvm/SandboxIR/Context.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8c5479a004039c52b83410ca34f8a3">operator()</a> (Type *Ty)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> has a protected destructor to prohibit the user from managing the lifetime of the <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> objects.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> is friend of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a>, and this custom deleter can destroy <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a>.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator()() {#a1b8c5479a004039c52b83410ca34f8a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::Context::TypeDeleter::operator() (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * Ty)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a18dba29b4f3e91d6d2bc53472a6bb7cc">llvm::sandboxir::Context::Type</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">Context.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
