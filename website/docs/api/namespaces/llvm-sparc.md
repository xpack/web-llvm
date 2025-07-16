---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/sparc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `Sparc` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::Sparc { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Fixups { <a href="#a12da1d52a8de679d4e9d520de5a8502d">...</a> }</td>
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

### Fixups {#a12da1d52a8de679d4e9d520de5a8502d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Sparc::Fixups </td>
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
<td class="doxyEnumItemName">fixup_sparc_call30<a id="a12da1d52a8de679d4e9d520de5a8502da4adff73a6fdb09236d160a1058cd738c"></a></td>
<td class="doxyEnumItemDescription"> (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_br22<a id="a12da1d52a8de679d4e9d520de5a8502daa66dfa8233272b1a84f34f5732cb8ef8"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_br22 - 22-bit PC relative relocation for branches</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_br19<a id="a12da1d52a8de679d4e9d520de5a8502da5c2a82f403be827f912129618ce8bb07"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_br19 - 19-bit PC relative relocation for branches on icc/xcc</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_br16<a id="a12da1d52a8de679d4e9d520de5a8502da0ed75123c86696d6dfbbc2643828abfc"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_bpr - 16-bit fixup for bpr</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_13<a id="a12da1d52a8de679d4e9d520de5a8502da602d9804c6b15c3eaa51cdeeeda754d2"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_13 - 13-bit fixup</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_hi22<a id="a12da1d52a8de679d4e9d520de5a8502da178d40a3cdc113de1bc4814dd67a11bc"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_hi22 - 22-bit fixup corresponding to hi(foo) for sethi</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_lo10<a id="a12da1d52a8de679d4e9d520de5a8502da02012bd04e669f47b0ca2c3ef4ec8df7"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_lo10 - 10-bit fixup corresponding to lo(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_h44<a id="a12da1d52a8de679d4e9d520de5a8502da7cb7e71faac52ef24527a11e314e7dae"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_h44 - 22-bit fixup corresponding to h44(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_m44<a id="a12da1d52a8de679d4e9d520de5a8502da284cdb6a9399209232aa3c13ca8d2618"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_m44 - 10-bit fixup corresponding to m44(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_l44<a id="a12da1d52a8de679d4e9d520de5a8502dabad234abccd9064339207fe71a70c7be"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_l44 - 12-bit fixup corresponding to l44(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_hh<a id="a12da1d52a8de679d4e9d520de5a8502da2ed85fcf7a68bb72867d54508fdfa214"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_hh - 22-bit fixup corresponding to hh(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_hm<a id="a12da1d52a8de679d4e9d520de5a8502daf9431782a67249942ea90c9d7882ea18"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_hm - 10-bit fixup corresponding to hm(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_lm<a id="a12da1d52a8de679d4e9d520de5a8502da138cb8615551a89f2ced1e3a40669bdd"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_lm - 22-bit fixup corresponding to lm(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_pc22<a id="a12da1d52a8de679d4e9d520de5a8502daa00d9587c28c43679ea78179d779dd85"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_pc22 - 22-bit fixup corresponding to pc22(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_pc10<a id="a12da1d52a8de679d4e9d520de5a8502dac6502cb4a88284870e35d967c53ac47f"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_pc10 - 10-bit fixup corresponding to pc10(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_got22<a id="a12da1d52a8de679d4e9d520de5a8502da7904709be5733140c3834f84bf9721d3"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_got22 - 22-bit fixup corresponding to got22(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_got10<a id="a12da1d52a8de679d4e9d520de5a8502da3e8e53769c95864f744db5c800d2452c"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_got10 - 10-bit fixup corresponding to got10(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_got13<a id="a12da1d52a8de679d4e9d520de5a8502da4bd19ebcb42069f48ac3d45dc1dc2c95"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_got13 - 13-bit fixup corresponding to got13(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_wplt30<a id="a12da1d52a8de679d4e9d520de5a8502dafa321c88b1e9bb39ab5b2e09b05fe7a6"></a></td>
<td class="doxyEnumItemDescription">fixup_sparc_wplt30</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_gd_hi22<a id="a12da1d52a8de679d4e9d520de5a8502da55d287c9fa6b9f05e7d86d910d08ef90"></a></td>
<td class="doxyEnumItemDescription">fixups for Thread Local Storage</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_gd_lo10<a id="a12da1d52a8de679d4e9d520de5a8502da6fd27a363f32a384e19d57732da83400"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_gd_add<a id="a12da1d52a8de679d4e9d520de5a8502da7de44a4f47d68e0bb21221b59fc64104"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_gd_call<a id="a12da1d52a8de679d4e9d520de5a8502da1cb655722f351a56ac2d2d20c6d3f21c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ldm_hi22<a id="a12da1d52a8de679d4e9d520de5a8502daa416e524e88172a66fad9215c0aa87d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ldm_lo10<a id="a12da1d52a8de679d4e9d520de5a8502da85b7e3dc16b048b452f479497746c819"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ldm_add<a id="a12da1d52a8de679d4e9d520de5a8502da20876dd25f69286a4dc4c4550f06e11f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ldm_call<a id="a12da1d52a8de679d4e9d520de5a8502da944eebfbe22a2c847d37530c43b3c1f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ldo_hix22<a id="a12da1d52a8de679d4e9d520de5a8502da4d435f58d4d1322c2d1db3f0ca19bdd6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ldo_lox10<a id="a12da1d52a8de679d4e9d520de5a8502da1fc5a8838faa83012242676700d3fbe9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ldo_add<a id="a12da1d52a8de679d4e9d520de5a8502da4fc6b4d7c79e1fb07e1c82aa851d2bb9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ie_hi22<a id="a12da1d52a8de679d4e9d520de5a8502da28c137eeff3f5dc170642e5313acd883"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ie_lo10<a id="a12da1d52a8de679d4e9d520de5a8502da98ce1ac1905989049a13fcc997c6800c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ie_ld<a id="a12da1d52a8de679d4e9d520de5a8502da0f86df663d98896b5c6d6d04f70b8f76"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ie_ldx<a id="a12da1d52a8de679d4e9d520de5a8502dafe9a137fc276c5872c10a68d18b6a1ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_ie_add<a id="a12da1d52a8de679d4e9d520de5a8502da81404b1c1698c400556d6db381d79b9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_le_hix22<a id="a12da1d52a8de679d4e9d520de5a8502da26c24bbb56bdfabcd601f3763e07888c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_tls_le_lox10<a id="a12da1d52a8de679d4e9d520de5a8502da401542a0ee1c7424a271c196e9b70de2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_hix22<a id="a12da1d52a8de679d4e9d520de5a8502da6be1cb6bff4acb2026f1107593c5bcc1"></a></td>
<td class="doxyEnumItemDescription">22-bit fixup corresponding to hix(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_lox10<a id="a12da1d52a8de679d4e9d520de5a8502da1665b86cbda5300143d0c72d38b18b55"></a></td>
<td class="doxyEnumItemDescription">13-bit fixup corresponding to lox(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_gotdata_hix22<a id="a12da1d52a8de679d4e9d520de5a8502da2cfd03bdef2da2a2493359d4443ffc00"></a></td>
<td class="doxyEnumItemDescription">22-bit fixup corresponding to gdop_hix22(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_gotdata_lox10<a id="a12da1d52a8de679d4e9d520de5a8502dabb1e74c3b7243667280210404a2d21d3"></a></td>
<td class="doxyEnumItemDescription">13-bit fixup corresponding to gdop_lox10(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_sparc_gotdata_op<a id="a12da1d52a8de679d4e9d520de5a8502da4ffe3fe32ce294fa71d496bd72924532"></a></td>
<td class="doxyEnumItemDescription">32-bit fixup corresponding to gdop(foo)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="a12da1d52a8de679d4e9d520de5a8502da2c32a353a624229cf9f0ea55990e194e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="a12da1d52a8de679d4e9d520de5a8502da85b47a97f9775429e859bea2e8898426"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcfixupkinds-h">SparcFixupKinds.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcfixupkinds-h">SparcFixupKinds.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
