---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcxcoffobjectwriter-cpp-/ppcxcoffobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCXCOFFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCXCOFFObjectWriter.cpp}::PPCXCOFFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcxcoffobjecttargetwriter">MCXCOFFObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d642befe9d81205e6bde083d7ff7965">PPCXCOFFObjectWriter</a> (bool Is64Bit)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; uint8_t, uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc93394c5603441fbdd9cc42141e792">getRelocTypeAndSignSize</a> (const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a3fbd1138feb03acbad125909015fe">SignBitMask</a> = 0x80</td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcxcoffobjectwriter-cpp">PPCXCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCXCOFFObjectWriter() {#a7d642befe9d81205e6bde083d7ff7965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCXCOFFObjectWriter::PPCXCOFFObjectWriter (bool Is64Bit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcxcoffobjectwriter-cpp">PPCXCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcxcoffobjecttargetwriter/#a0c0616aa242b0a66dbbc2e2f0ce64fdd">llvm::MCXCOFFObjectTargetWriter::MCXCOFFObjectTargetWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocTypeAndSignSize() {#a3dc93394c5603441fbdd9cc42141e792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; uint8_t, uint8_t &gt; PPCXCOFFObjectWriter::getRelocTypeAndSignSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcxcoffobjectwriter-cpp">PPCXCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450a058440145aa9ecc1725824fc1a47d50d">llvm::PPC::fixup_ppc_br24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450aeb0a8f988a6ad575c39e57767994fae9">llvm::PPC::fixup_ppc_br24abs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450a2cd2bd91cc9938c81599c5e8828addcd">llvm::PPC::fixup_ppc_half16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450aa14de08bc8d45995199ed5b534e91b2a">llvm::PPC::fixup_ppc_half16dq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450aa91622fd93be671ff6340f4a1716fc57">llvm::PPC::fixup_ppc_half16ds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450ab8c5d5569d95351dc5441109ca5318d2">llvm::PPC::fixup_ppc_nofixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aa5697ac4313fa05e5b1ca39e698ae0fbc">llvm::XCOFF::R_POS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aa5f580cdb49fb297a3e1b2bad00e7e6f8">llvm::XCOFF::R_RBA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aa04c13cb7fcc803870970c4b75b5c9905">llvm::XCOFF::R_RBR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aab32b714a6085785700777cab84db430f">llvm::XCOFF::R_REF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aae4144a827fe3865e989169e1fdfd3ede">llvm::XCOFF::R_TLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aa88aba99cf6b633d97e0cdd24fec5d0f5">llvm::XCOFF::R_TLS_IE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aadbc74cd663a943131b0e174006b6b581">llvm::XCOFF::R_TLS_LD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aae54c065150485a9445e07674fb43c3a7">llvm::XCOFF::R_TLS_LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aa8b5d41ca43ab37f8160e4b56ec25c03e">llvm::XCOFF::R_TLSM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aa2bf3c877a5a2835a5e55ac54ddedccd6">llvm::XCOFF::R_TLSML</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aa126bbcaab291460be1722fe8a2490530">llvm::XCOFF::R_TOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aac47fa14749515f1a3a0d88c51f854aa7">llvm::XCOFF::R_TOCL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a7309c911b619149e89a825cd78010c8aacb6f8892a6761a91f9e29cdafb33a7c8">llvm::XCOFF::R_TOCU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a45ef9ce5642cace4f318f108b42e11e6">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a5f3745b2d55b8cb0de42cb6c62fe0ca9">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSGDM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a6c66e7ad14399948694612a5891021c3">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSIE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985af0042f0eb9fb8dba8f49e4bedf5e9e10">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSLD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985afd7d09055e7b976b23804658655b5184">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSLE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a02e865dbaa6698cd599a034b55630829">llvm::MCSymbolRefExpr::VK_PPC_AIX_TLSML</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2e024b4ca6a06e62e43f54816758e59e">llvm::MCSymbolRefExpr::VK_PPC_L</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a357bed48651388b3b7882ed32f085ec1">llvm::MCSymbolRefExpr::VK_PPC_U</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### SignBitMask {#a80a3fbd1138feb03acbad125909015fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{PPCXCOFFObjectWriter.cpp}::PPCXCOFFObjectWriter::SignBitMask = 0x80</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcxcoffobjectwriter-cpp">PPCXCOFFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcxcoffobjectwriter-cpp">PPCXCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
