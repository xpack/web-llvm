---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PPCELFObjectWriter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcfixupkinds-h">MCTargetDesc/PPCFixupKinds.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcexpr-h">MCTargetDesc/PPCMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">MCTargetDesc/PPCMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcelfobjectwriter-h">llvm/MC/MCELFObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectwriter-h">llvm/MC/MCObjectWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">llvm/MC/MCSymbolELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-ppcelfobjectwriter-cpp-">anonymous{PPCELFObjectWriter.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-ppcelfobjectwriter-cpp-/ppcelfobjectwriter">PPCELFObjectWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa46e35fd185109152c2cece337dcb1e8">getAccessVariant</a> (const MCValue &amp;Target, const MCFixup &amp;Fixup)</td>
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

## Functions

### getAccessVariant() {#aa46e35fd185109152c2cece337dcb1e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolRefExpr::VariantKind getAccessVariant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp">PPCELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8b7bdf367ac57c04cfe5fc65738f8746">llvm::MCSymbolRefExpr::VK_PPC_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aead1c4a469bf794649572d583d82fb5298">llvm::PPCMCExpr::VK_PPC_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a48fe9f2486a3c190a9f1f32063d6c6bd">llvm::MCSymbolRefExpr::VK_PPC_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aeaeb7e6ae36702d248a38ef973670b1c72">llvm::PPCMCExpr::VK_PPC_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a91211d602833eef75759d4d8be28ef17">llvm::MCSymbolRefExpr::VK_PPC_HIGH</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea03aeb8c55ac38ce58e6b2e5002544ab8">llvm::PPCMCExpr::VK_PPC_HIGH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a1b3b1911c7fcbf11d06e26da2a953c61">llvm::MCSymbolRefExpr::VK_PPC_HIGHA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aeaa2d04a0ea8277a37914bc88bcb74a1fe">llvm::PPCMCExpr::VK_PPC_HIGHA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ae9c8307d1eb21a7958aa53353d5db45b">llvm::MCSymbolRefExpr::VK_PPC_HIGHER</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea3222f18d25f03f5eae1ef158e6adc662">llvm::PPCMCExpr::VK_PPC_HIGHER</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a597d0a70484140ad41301e773a72f472">llvm::MCSymbolRefExpr::VK_PPC_HIGHERA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea582641ec46c5e9d10297757c85d52f1a">llvm::PPCMCExpr::VK_PPC_HIGHERA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a372aaaee0e711730b3bfba5d094da61c">llvm::MCSymbolRefExpr::VK_PPC_HIGHEST</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea387e97ac9905a19c04eec775014d290e">llvm::PPCMCExpr::VK_PPC_HIGHEST</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7a924adae900e08a5ab61485f50c49f1">llvm::MCSymbolRefExpr::VK_PPC_HIGHESTA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea1e58d5555819cc4524917eb5d6a8f9d9">llvm::PPCMCExpr::VK_PPC_HIGHESTA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2de16a7019f22064bed686092ccc8697">llvm::MCSymbolRefExpr::VK_PPC_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aeabfdba0fefcc5a7d5598bbdf3d5ca50b2">llvm::PPCMCExpr::VK_PPC_LO</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcmcexpr/#a1ec88096dadbb5dc95ee1d2beb8f43aea7a315b6b39f6925e520bcfaf9fc8bff1">llvm::PPCMCExpr::VK_PPC_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcelfobjectwriter-cpp-/ppcelfobjectwriter/#aae19b9f8e4df7fe44b0ae56d07f88d46">anonymous{PPCELFObjectWriter.cpp}::PPCELFObjectWriter::getRelocType</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
