---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/pointertype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PointerType` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::PointerType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">llvm/SandboxIR/Type.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Just like <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> these are immutable, unique, never get freed and can only be created via static factory methods. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6339a17772e61656c08fd77a488c9a50">get</a> (Context &amp;Ctx, unsigned AddressSpace)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1216d52d8d739088660964729affd967">classof</a> (const Type *From)</td>
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


<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### classof() {#a1216d52d8d739088660964729affd967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::PointerType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * From)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a330bbaf89b90196df6960be4724513c6">llvm::sandboxir::Type::LLVMTy</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a386a56204d7dd7077ca711aff3c78d55">llvm::sandboxir::Type::Type</a>.</p>

</div>
</div>

### get() {#a6339a17772e61656c08fd77a488c9a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * PointerType::get (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx, unsigned AddressSpace)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::Type::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#ae616c2dab17f3dc139020928ef67ecaa">llvm::sandboxir::Type::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#abb7721cfea46ef9d51188ae7df27cf17">llvm::sandboxir::Type::PointerType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/type-h">Type.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
