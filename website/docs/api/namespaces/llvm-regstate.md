---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/regstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `RegState` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::RegState { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#ade26fe5c9b3fe6948def36f7ca12dfc5">...</a> }</td>
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

### anonymous enum  {#ade26fe5c9b3fe6948def36f7ca12dfc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">Define<a id="ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> definition (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Implicit<a id="ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99"></a></td>
<td class="doxyEnumItemDescription">Not emitted register (e.g. carry, or temporary result) (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Kill<a id="ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921"></a></td>
<td class="doxyEnumItemDescription">The last use of a register (= 0x8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dead<a id="ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013"></a></td>
<td class="doxyEnumItemDescription">Unused definition (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Undef<a id="ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the register doesn't matter (= 0x20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EarlyClobber<a id="ade26fe5c9b3fe6948def36f7ca12dfc5acf55f329675ba5045a4863c7a018209b"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> definition happens before uses (= 0x40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Debug<a id="ade26fe5c9b3fe6948def36f7ca12dfc5a14af644ca4aff07a3768974c824ac9d5"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> 'use' is for debugging purpose (= 0x80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InternalRead<a id="ade26fe5c9b3fe6948def36f7ca12dfc5a7fcf0a8c65265b4519b79fa537bbd8a0"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> reads a value that is defined inside the same instruction or bundle (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Renamable<a id="ade26fe5c9b3fe6948def36f7ca12dfc5a4c5b26e761294db59c1ad1cc6fc1d0ba"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> that may be renamed (= 0x200)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DefineNoRead<a id="ade26fe5c9b3fe6948def36f7ca12dfc5adb3c6bd94c0588ae581c154972651bfd"></a></td>
<td class="doxyEnumItemDescription"> (= Define | Undef)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImplicitDefine<a id="ade26fe5c9b3fe6948def36f7ca12dfc5a833922eca2ad0eab70573ba1f5fba9af"></a></td>
<td class="doxyEnumItemDescription"> (= Implicit | Define)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImplicitKill<a id="ade26fe5c9b3fe6948def36f7ca12dfc5acff74dc04327bef6824ecb2e3648d0f0"></a></td>
<td class="doxyEnumItemDescription"> (= Implicit | Kill)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
