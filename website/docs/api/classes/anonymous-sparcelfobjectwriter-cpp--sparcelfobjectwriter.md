---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sparcelfobjectwriter-cpp-/sparcelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SparcELFObjectWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SparcELFObjectWriter.cpp}::SparcELFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f5e0d70b3d66db689282ab31963af33">SparcELFObjectWriter</a> (bool Is64Bit, bool IsV8Plus, uint8_t OSABI)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1713ce57e1fe3c7c6fec72a9901e6eb2">~SparcELFObjectWriter</a> () override=default</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a122189d3180d72c2146b9637b59e679b">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13f03394801ae75fd84fcfbc5c2c0c56">needsRelocateWithSymbol</a> (const MCValue &amp;Val, const MCSymbol &amp;Sym, unsigned Type) const override</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcelfobjectwriter-cpp">SparcELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SparcELFObjectWriter() {#a8f5e0d70b3d66db689282ab31963af33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SparcELFObjectWriter.cpp}::SparcELFObjectWriter::SparcELFObjectWriter (bool Is64Bit, bool IsV8Plus, uint8_t OSABI)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcelfobjectwriter-cpp">SparcELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SparcELFObjectWriter() {#a1713ce57e1fe3c7c6fec72a9901e6eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SparcELFObjectWriter.cpp}::SparcELFObjectWriter::~SparcELFObjectWriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcelfobjectwriter-cpp">SparcELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#a122189d3180d72c2146b9637b59e679b">getRelocType</a> and <a href="#a13f03394801ae75fd84fcfbc5c2c0c56">needsRelocateWithSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRelocType() {#a122189d3180d72c2146b9637b59e679b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SparcELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcelfobjectwriter-cpp">SparcELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da602d9804c6b15c3eaa51cdeeeda754d2">llvm::Sparc::fixup_sparc_13</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da0ed75123c86696d6dfbbc2643828abfc">llvm::Sparc::fixup_sparc_br16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da5c2a82f403be827f912129618ce8bb07">llvm::Sparc::fixup_sparc_br19</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daa66dfa8233272b1a84f34f5732cb8ef8">llvm::Sparc::fixup_sparc_br22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4adff73a6fdb09236d160a1058cd738c">llvm::Sparc::fixup_sparc_call30</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da3e8e53769c95864f744db5c800d2452c">llvm::Sparc::fixup_sparc_got10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4bd19ebcb42069f48ac3d45dc1dc2c95">llvm::Sparc::fixup_sparc_got13</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7904709be5733140c3834f84bf9721d3">llvm::Sparc::fixup_sparc_got22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da2cfd03bdef2da2a2493359d4443ffc00">llvm::Sparc::fixup_sparc_gotdata_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dabb1e74c3b7243667280210404a2d21d3">llvm::Sparc::fixup_sparc_gotdata_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4ffe3fe32ce294fa71d496bd72924532">llvm::Sparc::fixup_sparc_gotdata_op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7cb7e71faac52ef24527a11e314e7dae">llvm::Sparc::fixup_sparc_h44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da2ed85fcf7a68bb72867d54508fdfa214">llvm::Sparc::fixup_sparc_hh</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da178d40a3cdc113de1bc4814dd67a11bc">llvm::Sparc::fixup_sparc_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da6be1cb6bff4acb2026f1107593c5bcc1">llvm::Sparc::fixup_sparc_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daf9431782a67249942ea90c9d7882ea18">llvm::Sparc::fixup_sparc_hm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dabad234abccd9064339207fe71a70c7be">llvm::Sparc::fixup_sparc_l44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da138cb8615551a89f2ced1e3a40669bdd">llvm::Sparc::fixup_sparc_lm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da02012bd04e669f47b0ca2c3ef4ec8df7">llvm::Sparc::fixup_sparc_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1665b86cbda5300143d0c72d38b18b55">llvm::Sparc::fixup_sparc_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da284cdb6a9399209232aa3c13ca8d2618">llvm::Sparc::fixup_sparc_m44</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dac6502cb4a88284870e35d967c53ac47f">llvm::Sparc::fixup_sparc_pc10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daa00d9587c28c43679ea78179d779dd85">llvm::Sparc::fixup_sparc_pc22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da7de44a4f47d68e0bb21221b59fc64104">llvm::Sparc::fixup_sparc_tls_gd_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1cb655722f351a56ac2d2d20c6d3f21c">llvm::Sparc::fixup_sparc_tls_gd_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da55d287c9fa6b9f05e7d86d910d08ef90">llvm::Sparc::fixup_sparc_tls_gd_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da6fd27a363f32a384e19d57732da83400">llvm::Sparc::fixup_sparc_tls_gd_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da81404b1c1698c400556d6db381d79b9b">llvm::Sparc::fixup_sparc_tls_ie_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da28c137eeff3f5dc170642e5313acd883">llvm::Sparc::fixup_sparc_tls_ie_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da0f86df663d98896b5c6d6d04f70b8f76">llvm::Sparc::fixup_sparc_tls_ie_ld</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dafe9a137fc276c5872c10a68d18b6a1ee">llvm::Sparc::fixup_sparc_tls_ie_ldx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da98ce1ac1905989049a13fcc997c6800c">llvm::Sparc::fixup_sparc_tls_ie_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da20876dd25f69286a4dc4c4550f06e11f">llvm::Sparc::fixup_sparc_tls_ldm_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da944eebfbe22a2c847d37530c43b3c1f3">llvm::Sparc::fixup_sparc_tls_ldm_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502daa416e524e88172a66fad9215c0aa87d2">llvm::Sparc::fixup_sparc_tls_ldm_hi22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da85b7e3dc16b048b452f479497746c819">llvm::Sparc::fixup_sparc_tls_ldm_lo10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4fc6b4d7c79e1fb07e1c82aa851d2bb9">llvm::Sparc::fixup_sparc_tls_ldo_add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da4d435f58d4d1322c2d1db3f0ca19bdd6">llvm::Sparc::fixup_sparc_tls_ldo_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da1fc5a8838faa83012242676700d3fbe9">llvm::Sparc::fixup_sparc_tls_ldo_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da26c24bbb56bdfabcd601f3763e07888c">llvm::Sparc::fixup_sparc_tls_le_hix22</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502da401542a0ee1c7424a271c196e9b70de2">llvm::Sparc::fixup_sparc_tls_le_lox10</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sparc/#a12da1d52a8de679d4e9d520de5a8502dafa321c88b1e9bb39ab5b2e09b05fe7a6">llvm::Sparc::fixup_sparc_wplt30</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#abeab46e996c332583b97b10b5feb70f0af92cd2ce45d818cf6690e01518a39b12">llvm::SparcMCExpr::VK_Sparc_R_DISP32</a>.</p>


<p>Referenced by <a href="#a1713ce57e1fe3c7c6fec72a9901e6eb2">~SparcELFObjectWriter</a>.</p>

</div>
</div>

### needsRelocateWithSymbol() {#a13f03394801ae75fd84fcfbc5c2c0c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SparcELFObjectWriter::needsRelocateWithSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, unsigned Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcelfobjectwriter-cpp">SparcELFObjectWriter.cpp</a>.</p>


<p>Referenced by <a href="#a1713ce57e1fe3c7c6fec72a9901e6eb2">~SparcELFObjectWriter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcelfobjectwriter-cpp">SparcELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
