---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/ve
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `VE` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::VE { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Fixups { <a href="#a3849fee8bddaabf813c7e8755415178a">...</a> }</td>
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

### Fixups {#a3849fee8bddaabf813c7e8755415178a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::VE::Fixups </td>
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
<td class="doxyEnumItemName">fixup_ve_reflong<a id="a3849fee8bddaabf813c7e8755415178aaf3cea4fe606bf2531f03ca6576c51961"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_reflong - 32-bit fixup corresponding to foo (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_srel32<a id="a3849fee8bddaabf813c7e8755415178aa060875c5f3e38d17d606f502fa3e06c1"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_srel32 - 32-bit fixup corresponding to foo for relative branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_hi32<a id="a3849fee8bddaabf813c7e8755415178aaa5364c6e73ddba627ce657e4356d0b49"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_hi32 - 32-bit fixup corresponding to foo@hi</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_lo32<a id="a3849fee8bddaabf813c7e8755415178aa78d516c790863298415e6177345d5ff8"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_lo32 - 32-bit fixup corresponding to foo@lo</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_pc_hi32<a id="a3849fee8bddaabf813c7e8755415178aa667f7a97724598853fb6d3cebb1e27d3"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_pc_hi32 - 32-bit fixup corresponding to foo@pc_hi</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_pc_lo32<a id="a3849fee8bddaabf813c7e8755415178aaaf6751559269bc22d124be47cec2bdb2"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_pc_lo32 - 32-bit fixup corresponding to foo@pc_lo</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_got_hi32<a id="a3849fee8bddaabf813c7e8755415178aa2ad67f23f486e531ca82d71890a68a01"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_got_hi32 - 32-bit fixup corresponding to foo@got_hi</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_got_lo32<a id="a3849fee8bddaabf813c7e8755415178aa5405339da89126a4026867f540e33441"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_got_lo32 - 32-bit fixup corresponding to foo@got_lo</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_gotoff_hi32<a id="a3849fee8bddaabf813c7e8755415178aa401919b7d910ed497dbe04087ffb51c0"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_gotoff_hi32 - 32-bit fixup corresponding to foo@gotoff_hi</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_gotoff_lo32<a id="a3849fee8bddaabf813c7e8755415178aa8a34234c9b623e8c9c425c81be4cb62c"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_gotoff_lo32 - 32-bit fixup corresponding to foo@gotoff_lo</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_plt_hi32<a id="a3849fee8bddaabf813c7e8755415178aade9959851c0f191c677111084c14698f"></a></td>
<td class="doxyEnumItemDescription">fixup_ve_plt_hi32/lo32</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_plt_lo32<a id="a3849fee8bddaabf813c7e8755415178aa122241fcebbf6c6cef07b513c0191a7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_tls_gd_hi32<a id="a3849fee8bddaabf813c7e8755415178aafc47658a501eaa76ba863b76fadd9735"></a></td>
<td class="doxyEnumItemDescription">fixups for Thread Local Storage</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_tls_gd_lo32<a id="a3849fee8bddaabf813c7e8755415178aafa85f01d7cc2698698e63aa36c528204"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_tpoff_hi32<a id="a3849fee8bddaabf813c7e8755415178aa0312ddb55e9fd7d4e1288f15f6ac4246"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_ve_tpoff_lo32<a id="a3849fee8bddaabf813c7e8755415178aac8d006c70ba7b24159949d6159dcf08c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="a3849fee8bddaabf813c7e8755415178aad85278ea67fe6555b51286068d496723"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="a3849fee8bddaabf813c7e8755415178aa8dc7be03c671ca8f21b54ea4f76be919"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vefixupkinds-h">VEFixupKinds.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vefixupkinds-h">VEFixupKinds.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
