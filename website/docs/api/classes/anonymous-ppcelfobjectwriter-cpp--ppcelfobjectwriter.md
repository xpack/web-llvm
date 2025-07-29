---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcelfobjectwriter-cpp-/ppcelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCELFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCELFObjectWriter.cpp}::PPCELFObjectWriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73354500a951b97d15e8eca925bc1217">PPCELFObjectWriter</a> (bool Is64Bit, uint8_t OSABI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae19b9f8e4df7fe44b0ae56d07f88d46">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae575b7fca6d665afc97ab3f9a9c16f58">needsRelocateWithSymbol</a> (const MCValue &amp;Val, const MCSymbol &amp;Sym, unsigned Type) const override</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp">PPCELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCELFObjectWriter() {#a73354500a951b97d15e8eca925bc1217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCELFObjectWriter::PPCELFObjectWriter (bool Is64Bit, uint8_t OSABI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp">PPCELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRelocType() {#aae19b9f8e4df7fe44b0ae56d07f88d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp">PPCELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450a058440145aa9ecc1725824fc1a47d50d">llvm::PPC::fixup_ppc_br24</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450a7529efd48ae862b862618c78039c6876">llvm::PPC::fixup_ppc_br24_notoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450aeb0a8f988a6ad575c39e57767994fae9">llvm::PPC::fixup_ppc_br24abs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450a7c601a9dd02f749390ca0dc194c22e0f">llvm::PPC::fixup_ppc_brcond14</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450a2379567960e1dddd9bde02874a1d9fda">llvm::PPC::fixup_ppc_brcond14abs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450a2cd2bd91cc9938c81599c5e8828addcd">llvm::PPC::fixup_ppc_half16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450aa14de08bc8d45995199ed5b534e91b2a">llvm::PPC::fixup_ppc_half16dq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450aa91622fd93be671ff6340f4a1716fc57">llvm::PPC::fixup_ppc_half16ds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450af5b83e08ebd4d2d64ffaa1cad54eb3ba">llvm::PPC::fixup_ppc_imm34</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450ab8c5d5569d95351dc5441109ca5318d2">llvm::PPC::fixup_ppc_nofixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa53de88164b98be6cd073da9543c0450a1379c8f82d3710fa8ea6c986230cf6b3">llvm::PPC::fixup_ppc_pcrel34</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a7fa4d5bb1573ffbf54e99ae1fe36ad6e">llvm::FK_PCRel_8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp/#aa46e35fd185109152c2cece337dcb1e8">getAccessVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#af1596fcc642359d1fbb138da1910b616">llvm::MCELFObjectTargetWriter::is64Bit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a29f2a3fe672b7936fde6f04eb0284c74">llvm::MCSymbolRefExpr::VK_DTPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a97666c9a886a80de41f6ef1b61a528c7">llvm::MCSymbolRefExpr::VK_PCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0301409c32f14b13a93451a72bfd54a8">llvm::MCSymbolRefExpr::VK_PPC_DTPMOD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a557068c0a5af8551cfeeebacb4e7b50d">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a6f871b8b19a508be82e3cf5fbdd1b788">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aaf636548d803f10f5f0e3607b55100ef">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HIGH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a84017b8a3e33572c050157bbb4e364c0">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HIGHA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a00e36b4242d01a8186f89616c1d94033">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HIGHER</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a1142b930700bea9eb3c3208832552b1c">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HIGHERA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a843397ce73b687621bbe91e65e703558">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HIGHEST</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a3aab9adfef3700bea810d54e20919b3f">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_HIGHESTA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab8a6b1fa79f3b913402f58157014df7c">llvm::MCSymbolRefExpr::VK_PPC_DTPREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985acf90c1ae6ce721405baf8d6575dbbcae">llvm::MCSymbolRefExpr::VK_PPC_GOT_DTPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a154ca3222e772e0ea2d21a43d589a37a">llvm::MCSymbolRefExpr::VK_PPC_GOT_DTPREL_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a5eb3d787ca102ee3f6becd6ce18f7351">llvm::MCSymbolRefExpr::VK_PPC_GOT_DTPREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa2adbff823003ac824d4158a6c3d5a9a">llvm::MCSymbolRefExpr::VK_PPC_GOT_DTPREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a23004891138ddce80497bebc9e47c3cd">llvm::MCSymbolRefExpr::VK_PPC_GOT_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0adbb1cf9b46d88694e78fad77ebc014">llvm::MCSymbolRefExpr::VK_PPC_GOT_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ad179e874cf4e309b0e9b955967f12371">llvm::MCSymbolRefExpr::VK_PPC_GOT_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a11109fa28d94481aac762781d22c216e">llvm::MCSymbolRefExpr::VK_PPC_GOT_PCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab73442f1c191fde93198b4568cda1dfc">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8df42e2c96f1fc53644f6a6c8353f57c">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSGD_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a1328ba71b9f7ab63659fb21462a434e7">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSGD_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7fe6746f350536c8fe0392b0a6670769">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSGD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a29655f0864a4c6d617e844c2b37d6abd">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSGD_PCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ad2369968761f661db6468af845d997f9">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSLD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a11579e28bc40de8894dd92e9dabb677e">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSLD_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a89ef4dfce0cdcaae2d7a1c2e786d0775">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSLD_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a9e1d9b07e91fad292c9fd673ca12e142">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSLD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a511a0cde1ea148087a9bc31b4bd730c7">llvm::MCSymbolRefExpr::VK_PPC_GOT_TLSLD_PCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4cd5875553111c54d66aa7254d99af01">llvm::MCSymbolRefExpr::VK_PPC_GOT_TPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a10816ac7561fb1d788b69d59c4153236">llvm::MCSymbolRefExpr::VK_PPC_GOT_TPREL_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a00476eb3086a83e9f8694d17e659e246">llvm::MCSymbolRefExpr::VK_PPC_GOT_TPREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aed3c47b613307c1c3bb2e123285a324c">llvm::MCSymbolRefExpr::VK_PPC_GOT_TPREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a47f886b8180bd36339b34b696e4aceed">llvm::MCSymbolRefExpr::VK_PPC_GOT_TPREL_PCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8b7bdf367ac57c04cfe5fc65738f8746">llvm::MCSymbolRefExpr::VK_PPC_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a48fe9f2486a3c190a9f1f32063d6c6bd">llvm::MCSymbolRefExpr::VK_PPC_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a91211d602833eef75759d4d8be28ef17">llvm::MCSymbolRefExpr::VK_PPC_HIGH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a1b3b1911c7fcbf11d06e26da2a953c61">llvm::MCSymbolRefExpr::VK_PPC_HIGHA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ae9c8307d1eb21a7958aa53353d5db45b">llvm::MCSymbolRefExpr::VK_PPC_HIGHER</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a597d0a70484140ad41301e773a72f472">llvm::MCSymbolRefExpr::VK_PPC_HIGHERA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a372aaaee0e711730b3bfba5d094da61c">llvm::MCSymbolRefExpr::VK_PPC_HIGHEST</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7a924adae900e08a5ab61485f50c49f1">llvm::MCSymbolRefExpr::VK_PPC_HIGHESTA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2de16a7019f22064bed686092ccc8697">llvm::MCSymbolRefExpr::VK_PPC_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a14ae083881358216647922cedc7ae4ea">llvm::MCSymbolRefExpr::VK_PPC_LOCAL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985afaacbcfe095c753443e87af4aad33014">llvm::MCSymbolRefExpr::VK_PPC_NOTOC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a1ebb65d3581b26c6d9be3d4ff95d8648">llvm::MCSymbolRefExpr::VK_PPC_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a3af1b5ef4b41faa6d2e73935860fa3c0">llvm::MCSymbolRefExpr::VK_PPC_TLS_PCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a614a4f4a72a1a5fbf6b309990dbf9643">llvm::MCSymbolRefExpr::VK_PPC_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a55f8ba42b33462144024cc7a07194631">llvm::MCSymbolRefExpr::VK_PPC_TLSLD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa4b8b58379694eb9c24793904e2b2089">llvm::MCSymbolRefExpr::VK_PPC_TOC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a86b94af00057681fc558d5ade49f77f9">llvm::MCSymbolRefExpr::VK_PPC_TOC_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ac336aade6add02fc835b447c21d12074">llvm::MCSymbolRefExpr::VK_PPC_TOC_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a9ea61bcfe12d2dbd766d06581e5abe79">llvm::MCSymbolRefExpr::VK_PPC_TOC_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a6cd4a312e47b0e61f2dcabb3889abe66">llvm::MCSymbolRefExpr::VK_PPC_TOCBASE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa022f5ada06b78d01fc4227b09a8722a">llvm::MCSymbolRefExpr::VK_PPC_TPREL_HA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61a15f02c13a7251c97f9387c3f99ecb">llvm::MCSymbolRefExpr::VK_PPC_TPREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ad1e8fbb210d1190a9c71fc0b5c2a74bc">llvm::MCSymbolRefExpr::VK_PPC_TPREL_HIGH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a688a086d89be625bf3c11bab1e3ee549">llvm::MCSymbolRefExpr::VK_PPC_TPREL_HIGHA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a91432c86c48a7496dd9de6088182a12a">llvm::MCSymbolRefExpr::VK_PPC_TPREL_HIGHER</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a1f9254d454e21c1ea81001a7e15a0917">llvm::MCSymbolRefExpr::VK_PPC_TPREL_HIGHERA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a00a33ecfac5457b544a31d2ce8f3695a">llvm::MCSymbolRefExpr::VK_PPC_TPREL_HIGHEST</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa810324618394114d0088f1c6ce3f7e9">llvm::MCSymbolRefExpr::VK_PPC_TPREL_HIGHESTA</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a3ae3c5740fe01f98a256caeb5a1ae6f2">llvm::MCSymbolRefExpr::VK_PPC_TPREL_LO</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa12b324430d5f16b6a4e1f965048c38a">llvm::MCSymbolRefExpr::VK_TPREL</a>.</p>

</div>
</div>

### needsRelocateWithSymbol() {#ae575b7fca6d665afc97ab3f9a9c16f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCELFObjectWriter::needsRelocateWithSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, unsigned Type)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp">PPCELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a6123601d8755369a565d7a2b72de9365a768d5907f7b0389d066953a57ae8c5d2">llvm::ELF::STO_PPC64_LOCAL_MASK</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcelfobjectwriter-cpp">PPCELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
