---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/deriveduser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DerivedUser` Class Reference

<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> point for the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> hierarchy. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DerivedUser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/deriveduser-h">llvm/IR/DerivedUser.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669415c3e7013700123a78ed8a10651c">DeleteValueTy</a> = void(*)(<a href="/web-llvm/docs/api/classes/llvm/deriveduser">DerivedUser</a> *)</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f2e1a4bb7547921039149d75b78c05">DerivedUser</a> (Type *Ty, unsigned VK, AllocInfo AllocInfo, DeleteValueTy DeleteValue)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a669415c3e7013700123a78ed8a10651c">DeleteValueTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75bd65f94a444586be6ddd8d097a2577">DeleteValue</a></td>
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

<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> point for the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> hierarchy.</p>


<p>All classes outside of lib/IR that wish to inherit from <a href="/web-llvm/docs/api/classes/llvm/user">User</a> should instead inherit from <a href="/web-llvm/docs/api/classes/llvm/deriveduser">DerivedUser</a> instead. Inheriting from this class is discouraged.</p>


<p>Generally speaking, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is the base of a closed class hierarchy that can't be extended by code outside of lib/IR. This class creates a loophole that allows classes outside of lib/IR to extend <a href="/web-llvm/docs/api/classes/llvm/user">User</a> to leverage its use/def list machinery.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/deriveduser-h">DerivedUser.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### DeleteValueTy {#a669415c3e7013700123a78ed8a10651c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DerivedUser::DeleteValueTy =  void (*)(DerivedUser *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/deriveduser-h">DerivedUser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Value {#aeceedf6e1a7d48a588516ce2b1983d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/deriveduser-h">DerivedUser.h</a>.</p>


<p>Reference <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a20129d55ad455c11e932d68e4bd32581">llvm::MemoryAccess::classof</a> and <a href="#aeceedf6e1a7d48a588516ce2b1983d6f">Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DerivedUser() {#a88f2e1a4bb7547921039149d75b78c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DerivedUser::DerivedUser (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned VK, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo, <a href="#a669415c3e7013700123a78ed8a10651c">DeleteValueTy</a> DeleteValue)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/deriveduser-h">DerivedUser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a282fa3e9586425313e0a954c18deee15">llvm::User::User</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryaccess/#a866e08b474db229fb44b37b329f65240">llvm::MemoryAccess::MemoryAccess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DeleteValue {#a75bd65f94a444586be6ddd8d097a2577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeleteValueTy llvm::DerivedUser::DeleteValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/deriveduser-h">DerivedUser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/deriveduser-h">DerivedUser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
