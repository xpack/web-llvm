---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/mips16hardfloatinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `Mips16HardFloatInfo` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::Mips16HardFloatInfo { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mips16hardfloatinfo/funcnamesignature">FuncNameSignature</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mips16hardfloatinfo/funcsignature">FuncSignature</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FPReturnVariant { <a href="#a5387065378850a0af9c83c6c9be194c8">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FPParamVariant { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0e">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mips16hardfloatinfo/funcsignature">FuncSignature</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69fe9395c105f669ee4e8e7b03b4c3ca">findFuncSignature</a> (const char *name)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mips16hardfloatinfo/funcnamesignature">FuncNameSignature</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a17ce96c65b223071f9bd4adae70786">PredefinedFuncs</a>[] = ...</td>
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


<div class="doxySectionDef">

## Enumerations

### FPParamVariant {#a08000664dd01b3bba7f8e1f3ea82fe0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Mips16HardFloatInfo::FPParamVariant </td>
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
<td class="doxyEnumItemName">FSig<a id="a08000664dd01b3bba7f8e1f3ea82fe0ea7a0fd2febd2b3b785846818b0343f36b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFSig<a id="a08000664dd01b3bba7f8e1f3ea82fe0ea7ecf5de7b2393d57bac8ec92e9458aa4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FDSig<a id="a08000664dd01b3bba7f8e1f3ea82fe0ea521fdddc5840cfeeb309b025392a8f6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DSig<a id="a08000664dd01b3bba7f8e1f3ea82fe0ea3c7c0b406890b364d5c285eef26c1bf9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DDSig<a id="a08000664dd01b3bba7f8e1f3ea82fe0eac47e64362f0ede647e7b827114532f1e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DFSig<a id="a08000664dd01b3bba7f8e1f3ea82fe0ea36a79d29d28813351423e868e8ce4066"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoSig<a id="a08000664dd01b3bba7f8e1f3ea82fe0ea588ff0078c93ca869477f457b49a918f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloatinfo-h">Mips16HardFloatInfo.h</a>.</p>

</div>
</div>

### FPReturnVariant {#a5387065378850a0af9c83c6c9be194c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Mips16HardFloatInfo::FPReturnVariant </td>
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
<td class="doxyEnumItemName">FRet<a id="a5387065378850a0af9c83c6c9be194c8ab9054550919cf82ebf34b55671cb1f7b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DRet<a id="a5387065378850a0af9c83c6c9be194c8a21b21e3ae7f13048c51cc3bd7ea6eea4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CFRet<a id="a5387065378850a0af9c83c6c9be194c8a70d46a5a855a959d7b1f10e1709cb18a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CDRet<a id="a5387065378850a0af9c83c6c9be194c8a704eca2e16df05e8422e57a85d57761c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoFPRet<a id="a5387065378850a0af9c83c6c9be194c8a70dd5cfcc7bd5984882132b19405aaaf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloatinfo-h">Mips16HardFloatInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### findFuncSignature() {#a69fe9395c105f669ee4e8e7b03b4c3ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncSignature const  * llvm::Mips16HardFloatInfo::findFuncSignature (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloatinfo-cpp">Mips16HardFloatInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> and <a href="#a1a17ce96c65b223071f9bd4adae70786">PredefinedFuncs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### PredefinedFuncs {#a1a17ce96c65b223071f9bd4adae70786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FuncNameSignature llvm::Mips16HardFloatInfo::PredefinedFuncs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  { "__floatdidf", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea588ff0078c93ca869477f457b49a918f">NoSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a21b21e3ae7f13048c51cc3bd7ea6eea4">DRet</a> } },
  { "__floatdisf", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea588ff0078c93ca869477f457b49a918f">NoSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8ab9054550919cf82ebf34b55671cb1f7b">FRet</a> } },
  { "__floatundidf", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea588ff0078c93ca869477f457b49a918f">NoSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a21b21e3ae7f13048c51cc3bd7ea6eea4">DRet</a> } },
  { "__fixsfdi", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea7a0fd2febd2b3b785846818b0343f36b">FSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a70dd5cfcc7bd5984882132b19405aaaf">NoFPRet</a> } },
  { "__fixunsdfsi", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea3c7c0b406890b364d5c285eef26c1bf9">DSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a70dd5cfcc7bd5984882132b19405aaaf">NoFPRet</a> } },
  { "__fixunsdfdi", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea3c7c0b406890b364d5c285eef26c1bf9">DSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a70dd5cfcc7bd5984882132b19405aaaf">NoFPRet</a> } },
  { "__fixdfdi", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea3c7c0b406890b364d5c285eef26c1bf9">DSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a70dd5cfcc7bd5984882132b19405aaaf">NoFPRet</a> } },
  { "__fixunssfsi", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea7a0fd2febd2b3b785846818b0343f36b">FSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a70dd5cfcc7bd5984882132b19405aaaf">NoFPRet</a> } },
  { "__fixunssfdi", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea7a0fd2febd2b3b785846818b0343f36b">FSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a70dd5cfcc7bd5984882132b19405aaaf">NoFPRet</a> } },
  { "__floatundisf", { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea588ff0078c93ca869477f457b49a918f">NoSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8ab9054550919cf82ebf34b55671cb1f7b">FRet</a> } },
  { nullptr, { <a href="#a08000664dd01b3bba7f8e1f3ea82fe0ea588ff0078c93ca869477f457b49a918f">NoSig</a>, <a href="#a5387065378850a0af9c83c6c9be194c8a70dd5cfcc7bd5984882132b19405aaaf">NoFPRet</a> } }
}
</div>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloatinfo-cpp">Mips16HardFloatInfo.cpp</a>.</p>


<p>Referenced by <a href="#a69fe9395c105f669ee4e8e7b03b4c3ca">findFuncSignature</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloatinfo-cpp">Mips16HardFloatInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloatinfo-h">Mips16HardFloatInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
