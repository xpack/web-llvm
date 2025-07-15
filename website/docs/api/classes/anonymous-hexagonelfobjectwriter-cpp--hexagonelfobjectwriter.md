---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonelfobjectwriter-cpp-/hexagonelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonELFObjectWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonELFObjectWriter.cpp}::HexagonELFObjectWriter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41f88fd90ff25b85f0800d948db49644">HexagonELFObjectWriter</a> (uint8_t OSABI, StringRef C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78b32c3792c457ebc7638e3d590f63d">getRelocType</a> (MCContext &amp;Ctx, MCValue const &amp;Target, MCFixup const &amp;Fixup, bool IsPCRel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab451fe875188c3164f73c0cd4e756010">CPU</a></td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonelfobjectwriter-cpp">HexagonELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonELFObjectWriter() {#a41f88fd90ff25b85f0800d948db49644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonELFObjectWriter::HexagonELFObjectWriter (uint8_t OSABI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonelfobjectwriter-cpp">HexagonELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocType() {#aa78b32c3792c457ebc7638e3d590f63d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HexagonELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Fixup, bool IsPCRel)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonelfobjectwriter-cpp">HexagonELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad99ecf031674f184411b22dc55e59659">llvm::Hexagon::fixup_Hexagon_10_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fab6c0d1722606ba0c87cf23facac8cf9a">llvm::Hexagon::fixup_Hexagon_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa4a4308781cf42caa5826013ce7196fa5">llvm::Hexagon::fixup_Hexagon_12_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa983047fe1d9d76db3ea8ada08e1a1761">llvm::Hexagon::fixup_Hexagon_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1238f42b1826506b29adb8d7e79b6881">llvm::Hexagon::fixup_Hexagon_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf45ac0138cce02b717e60b43ac920e06">llvm::Hexagon::fixup_Hexagon_23_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa105e484db4846fe2f4433677246b78e3">llvm::Hexagon::fixup_Hexagon_27_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa0a49adb0d61b7f58450fa61d489c9de5">llvm::Hexagon::fixup_Hexagon_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8d74109744840889ca2b701dfcdac096">llvm::Hexagon::fixup_Hexagon_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa58d886d876663e910bb42d4711cd3a47">llvm::Hexagon::fixup_Hexagon_32_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa94c391478d4495def35b608d8d49aecd">llvm::Hexagon::fixup_Hexagon_6_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa75669d3838a8248efdcecdf57ea4eaee">llvm::Hexagon::fixup_Hexagon_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa88a5681b1be1d10a65270e11a9680a51">llvm::Hexagon::fixup_Hexagon_7_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4facd53bc898ef0ddc41efd51d392581b89">llvm::Hexagon::fixup_Hexagon_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1752309db082a3eaf850e6478cb6e2ac">llvm::Hexagon::fixup_Hexagon_8_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fac2aefbd0a7d3415735342e0b3dd7607d">llvm::Hexagon::fixup_Hexagon_9_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3892bebaed52b6bb7704fb4705bfd3ea">llvm::Hexagon::fixup_Hexagon_B13_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5742fbb01e95827aa1d4fed0e8bf49db">llvm::Hexagon::fixup_Hexagon_B13_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e7f405b8420c4b38d640cd008c0f1b5">llvm::Hexagon::fixup_Hexagon_B15_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadba6b69224d9575e3845b5a1d5fbf437">llvm::Hexagon::fixup_Hexagon_B15_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9d43956f2ba0ad2b6a14b6f15d8a9d1b">llvm::Hexagon::fixup_Hexagon_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fadfd8c0fda1dc285ceabeb34ddcd3a226">llvm::Hexagon::fixup_Hexagon_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa659fb706c1401f9541effc64fa54ba68">llvm::Hexagon::fixup_Hexagon_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faec512985edaee90285f046598a99c063">llvm::Hexagon::fixup_Hexagon_B7_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa2fc452a2d9e80df1f68ec27693e9632c">llvm::Hexagon::fixup_Hexagon_B7_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8433e062504192a5113a2e9d08e911e2">llvm::Hexagon::fixup_Hexagon_B9_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf7ad305a417f6572f3ecc7d3d73179ca">llvm::Hexagon::fixup_Hexagon_B9_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1e3c630a7c5b5dc7c5329435a6b41a97">llvm::Hexagon::fixup_Hexagon_COPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3e900a9a202bbab42a492fa01de22593">llvm::Hexagon::fixup_Hexagon_DTPMOD_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa824c46bf71f91ca5c47d28f611512b25">llvm::Hexagon::fixup_Hexagon_DTPREL_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa7380060dd15e7fae6a660465c0c0215a">llvm::Hexagon::fixup_Hexagon_DTPREL_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad98d188763eb82743804f9487e2aa1e7">llvm::Hexagon::fixup_Hexagon_DTPREL_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa877c2ee214a59923396a49df10525171">llvm::Hexagon::fixup_Hexagon_DTPREL_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa703bfe0936ee91755b39ec64dceed58b">llvm::Hexagon::fixup_Hexagon_DTPREL_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3ad50b0feaad604ba6c3e1bb12d5d53e">llvm::Hexagon::fixup_Hexagon_DTPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8a0fc945427de25d74ac06fbfec27455">llvm::Hexagon::fixup_Hexagon_DTPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa69dd3f3b5eee56c84b9d3d753f9f3696">llvm::Hexagon::fixup_Hexagon_GD_GOT_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5bddf1f4c7df22f46a83d1ffeec2d9dc">llvm::Hexagon::fixup_Hexagon_GD_GOT_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa698984f6e98ef90a74f4ffb1110c8e83">llvm::Hexagon::fixup_Hexagon_GD_GOT_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa95aa368cc3aa0efc85295e5e0fda662e">llvm::Hexagon::fixup_Hexagon_GD_GOT_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa46bb2621d89288ade28fc1ef2bcd0d7d">llvm::Hexagon::fixup_Hexagon_GD_GOT_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa0bd2f6d5a9ddac2ae30d825a7c9c0aff">llvm::Hexagon::fixup_Hexagon_GD_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa71ffeb67d2bb37d7ca90058c88c87d7a">llvm::Hexagon::fixup_Hexagon_GD_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9a689f3ed64b9083dc9b5b9d8cfaaf68">llvm::Hexagon::fixup_Hexagon_GD_PLT_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa95bb47d6433e0d1496f52a00247731dd">llvm::Hexagon::fixup_Hexagon_GD_PLT_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa72100ecf8c35b05ed173bdb24b6cd01e">llvm::Hexagon::fixup_Hexagon_GD_PLT_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa27b6bfa00bdafea93c099b82427a4825">llvm::Hexagon::fixup_Hexagon_GLOB_DAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad2f0d42bcf2a8b8d8cc55870ea4f968a">llvm::Hexagon::fixup_Hexagon_GOT_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa10325a6488d2667fde692f8168f36536">llvm::Hexagon::fixup_Hexagon_GOT_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5b53b6d46a35711771f21d6988e00bc6">llvm::Hexagon::fixup_Hexagon_GOT_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1650494cb02ba11cae46812eab294dd4">llvm::Hexagon::fixup_Hexagon_GOT_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fac97b8f66ee281a6286efcebc4697e7ed">llvm::Hexagon::fixup_Hexagon_GOT_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa0bd79ef1d1a6a62fb91a9f28447b1e3c">llvm::Hexagon::fixup_Hexagon_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa6983463228ac808d9fdb72f996efd344">llvm::Hexagon::fixup_Hexagon_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad4fc2083e1517b0cf6dfd085231fbd89">llvm::Hexagon::fixup_Hexagon_GOTREL_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fafa196a1c11f392e0d0778479cbdcb390">llvm::Hexagon::fixup_Hexagon_GOTREL_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa886678bbd3b53e49c1e613b69345eb82">llvm::Hexagon::fixup_Hexagon_GOTREL_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf1153ccc22742ec0464cb1b9927eecc9">llvm::Hexagon::fixup_Hexagon_GOTREL_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa58f925e6ea2b9418e5f060c7a20db09e">llvm::Hexagon::fixup_Hexagon_GOTREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fabfc9bbd4439da18ba02014c0034ab906">llvm::Hexagon::fixup_Hexagon_GOTREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9138381af1cca4c3b1b6d704b99a1264">llvm::Hexagon::fixup_Hexagon_GPREL16_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8772f6b3894ea2528dd63a9b18d486c0">llvm::Hexagon::fixup_Hexagon_GPREL16_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa86787739672c42f914e9cff84b54fd08">llvm::Hexagon::fixup_Hexagon_GPREL16_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa09ee45819d307cd444ef760ba4b4a839">llvm::Hexagon::fixup_Hexagon_GPREL16_3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9ac1d082837fe4e072372d5479ecd945">llvm::Hexagon::fixup_Hexagon_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa79ef6386750168ee03339b4d203ec396">llvm::Hexagon::fixup_Hexagon_HL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa762facc50089208c6007d89f6935c99b">llvm::Hexagon::fixup_Hexagon_IE_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa96cfce497d5a8ffbc24e234b6b5b65dd">llvm::Hexagon::fixup_Hexagon_IE_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fae0bfea17caa1f1375f045bc52c812870">llvm::Hexagon::fixup_Hexagon_IE_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fae412b909dd6c896523c05e3d7f1315d9">llvm::Hexagon::fixup_Hexagon_IE_GOT_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fab8ade61a33bbfaa4d5a25268acc2b601">llvm::Hexagon::fixup_Hexagon_IE_GOT_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1437ba334dcf5bdf60eed35e439eeccd">llvm::Hexagon::fixup_Hexagon_IE_GOT_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa9ad1ee188faef46ac49cd93b07a0e805">llvm::Hexagon::fixup_Hexagon_IE_GOT_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa59c78c64a975df3e44624569e8142127">llvm::Hexagon::fixup_Hexagon_IE_GOT_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fac7156b443277048d58471fe1abd746e9">llvm::Hexagon::fixup_Hexagon_IE_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa3eee608f87c662e714399c4da1bcdfe0">llvm::Hexagon::fixup_Hexagon_IE_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa640f88cd125f9b795bf9ea5637c1af80">llvm::Hexagon::fixup_Hexagon_IE_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faf702bce95b626ec4b9882426369264e4">llvm::Hexagon::fixup_Hexagon_IE_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa170d14cf0c7d0e241f21dde3baf09d24">llvm::Hexagon::fixup_Hexagon_JMP_SLOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fad2c0c2014c24cb796bfcbeebd7bc8a02">llvm::Hexagon::fixup_Hexagon_LD_GOT_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8f23abef486b6e149287dd187f4a1774">llvm::Hexagon::fixup_Hexagon_LD_GOT_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa8e2d48cfc26356af4a52ab9738e813de">llvm::Hexagon::fixup_Hexagon_LD_GOT_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fae835cb5b9d766d2a38aa6dc318ead74c">llvm::Hexagon::fixup_Hexagon_LD_GOT_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faab1514b556208cf0151233da6d70a0c1">llvm::Hexagon::fixup_Hexagon_LD_GOT_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa46d5b5f65f0c34f1df0dc1d127bb267b">llvm::Hexagon::fixup_Hexagon_LD_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fab96a52b0f2dd5f94298e3a0c2b292498">llvm::Hexagon::fixup_Hexagon_LD_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa1d78e3d110cd9b108eae5c7dfe20b9c3">llvm::Hexagon::fixup_Hexagon_LD_PLT_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa43847e6cd11cfe076051a9997931709a">llvm::Hexagon::fixup_Hexagon_LD_PLT_B22_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa07f492a937c5572b112d66da7966073c">llvm::Hexagon::fixup_Hexagon_LD_PLT_B32_PCREL_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa62fc0b99badda962b2f1bcdd1367ff13">llvm::Hexagon::fixup_Hexagon_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa5de78d76e447c09d64aff72960145cd2">llvm::Hexagon::fixup_Hexagon_PLT_B22_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa85cc680592aabe5903faee5dbe52a293">llvm::Hexagon::fixup_Hexagon_RELATIVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fabb0a4c45ae086959ca277bb07406f6ee">llvm::Hexagon::fixup_Hexagon_TPREL_11_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa404621dd8b91539d09de1373561a5443">llvm::Hexagon::fixup_Hexagon_TPREL_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa2a2067c1eb00e35133f5d83164e77267">llvm::Hexagon::fixup_Hexagon_TPREL_16_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa51750857d8c467426b78cf2b3335ba92">llvm::Hexagon::fixup_Hexagon_TPREL_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4fa27a221e1c9b48f060c699ffef2bc3784">llvm::Hexagon::fixup_Hexagon_TPREL_32_6_X</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faa5df11702270e9d9efea4564ee46ebeb">llvm::Hexagon::fixup_Hexagon_TPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#a6fdd89bf2fcdd5502331328b94f4bd4faa504ba238a35d3921438a7cc482d33ad">llvm::Hexagon::fixup_Hexagon_TPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a29f2a3fe672b7936fde6f04eb0284c74">llvm::MCSymbolRefExpr::VK_DTPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a52a066155dc6bd5c75e077d7fd2d619c">llvm::MCSymbolRefExpr::VK_GOTREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7de84847ab4ad2a218fefb78e952e6ab">llvm::MCSymbolRefExpr::VK_Hexagon_GD_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a76148043f2fa1509f2b55b6472eeac7f">llvm::MCSymbolRefExpr::VK_Hexagon_IE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab09b72e3f9139ae88ba205eabfb79c4a">llvm::MCSymbolRefExpr::VK_Hexagon_IE_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ae2423d201933ce84129fd857e083d3d3">llvm::MCSymbolRefExpr::VK_Hexagon_LD_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a97666c9a886a80de41f6ef1b61a528c7">llvm::MCSymbolRefExpr::VK_PCREL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa12b324430d5f16b6a4e1f965048c38a">llvm::MCSymbolRefExpr::VK_TPREL</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CPU {#ab451fe875188c3164f73c0cd4e756010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{HexagonELFObjectWriter.cpp}::HexagonELFObjectWriter::CPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonelfobjectwriter-cpp">HexagonELFObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonelfobjectwriter-cpp">HexagonELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
