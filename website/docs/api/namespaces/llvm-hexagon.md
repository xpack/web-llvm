---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/hexagon
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `Hexagon` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::Hexagon { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hexagon/packetiterator">PacketIterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ArchEnum { <a href="#ac51913459c748e1d7176ab02946c4436">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#acf8436e28b183b48eecf6b8564536c7a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Fixups { <a href="#a6fdd89bf2fcdd5502331328b94f4bd4f">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">FixupBitmaps : unsigned { <a href="#a8c653dc2a2c3e5b778bc59fccaf4fb16">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#ac51913459c748e1d7176ab02946c4436">Hexagon::ArchEnum</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5440e15db345bf9daf9a8961192663">getCpu</a> (StringRef CPU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29950c043a46c5916188a0305b25a90">StartPacket</a> = 0x1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a809581007d9606439cd605eefab3a095">EndPacket</a> = 0x2</td>
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

### anonymous enum  {#acf8436e28b183b48eecf6b8564536c7a}

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
<td class="doxyEnumItemName">ps_sub_lo<a id="acf8436e28b183b48eecf6b8564536c7aa4c96233dec1eedf779c37f230f6d8c10"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ps_sub_hi<a id="acf8436e28b183b48eecf6b8564536c7aa7e62627fded515ebb9ff5d0ec9571d95"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonregisterinfo-h">HexagonRegisterInfo.h</a>.</p>

</div>
</div>

### ArchEnum {#ac51913459c748e1d7176ab02946c4436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::Hexagon::ArchEnum </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">NoArch<a id="ac51913459c748e1d7176ab02946c4436a31ca3cae0b846c9a58d52c656d28b5e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Generic<a id="ac51913459c748e1d7176ab02946c4436a8045a0a6c688b0635e3caccc408a1446"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V5<a id="ac51913459c748e1d7176ab02946c4436a8cff5423006469332e8ae5e3a8c8559c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V55<a id="ac51913459c748e1d7176ab02946c4436a7e2f25174ce09de028190095cc693a5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V60<a id="ac51913459c748e1d7176ab02946c4436a8336608773c499fd7e37000fac2f9cfd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V62<a id="ac51913459c748e1d7176ab02946c4436a113b0d77002193057e4a99b66ceb8264"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V65<a id="ac51913459c748e1d7176ab02946c4436aa7903c0ef33fd8000b9fded2bd20f6cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V66<a id="ac51913459c748e1d7176ab02946c4436a2267b8c0f3b8c12c5bbbf66978544a0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V67<a id="ac51913459c748e1d7176ab02946c4436a0db1fd5100de9dcbc5f2949df2a2dbf7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V68<a id="ac51913459c748e1d7176ab02946c4436a52cd6998d793235c390b570fba7d206c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V69<a id="ac51913459c748e1d7176ab02946c4436a08c198530a951b0d1adc8c0f38967bb1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V71<a id="ac51913459c748e1d7176ab02946c4436a21f8c41b215c6879bfc46b10e506d2d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V73<a id="ac51913459c748e1d7176ab02946c4436a4084fbfbf7c3d3e99fcda5f126a1e494"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V75<a id="ac51913459c748e1d7176ab02946c4436ab1cab2dc211faa7bcebb331fd40454fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">V79<a id="ac51913459c748e1d7176ab02946c4436a98a8f93c2a6e174b45fc01e59ccf8ffe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagondeparch-h">HexagonDepArch.h</a>.</p>

</div>
</div>

### FixupBitmaps {#a8c653dc2a2c3e5b778bc59fccaf4fb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Hexagon::FixupBitmaps : unsigned</td>
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
<td class="doxyEnumItemName">Word8<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16aca9d109bb52922d62ac1360f6c245430"></a></td>
<td class="doxyEnumItemDescription"> (= 0xff)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word16<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16af5deb2c9fa39e76fe600cc15eeb906ff"></a></td>
<td class="doxyEnumItemDescription"> (= 0xffff)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16affa3e1d1df2355a0ffd85ea780f2bfdc"></a></td>
<td class="doxyEnumItemDescription"> (= 0xffffffff)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_LO<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16a5f7eb415278f77283cce259d9d24eb95"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00c03fff)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_HL<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16a6c8c63e43b2e72589aa21b8ae4cf9d6f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_GP<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16ac62f5ab87b94784e37c032d3b017adc2"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_B7<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16a7d40fcd363ac46a36895b71557813d41"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00001f18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_B9<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16a5bd3bfde148e4996714caa1253181708"></a></td>
<td class="doxyEnumItemDescription"> (= 0x003000fe)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_B13<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16ab336784618a49f1012abab88c2ee2ce9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00202ffe)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_B15<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16afcf4d8412054486defa361117357ef12"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00df20fe)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_B22<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16a95197cd78c5f47d30f5aa6a1c747d367"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01ff3ffe)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_R6<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16ad6b43dd2812fd2ca1afe240f9f5fc4ca"></a></td>
<td class="doxyEnumItemDescription"> (= 0x000007e0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_U6<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16a4ca761661613260604234891e7f9908e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_U16<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16a856313e9c05314a8c54badd71b85d5b1"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Word32_X26<a id="a8c653dc2a2c3e5b778bc59fccaf4fb16afd71ab505948dae24b20d14bf5ca8662"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0fff3fff)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonfixupkinds-h">HexagonFixupKinds.h</a>.</p>

</div>
</div>

### Fixups {#a6fdd89bf2fcdd5502331328b94f4bd4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Hexagon::Fixups </td>
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
<td class="doxyEnumItemName">fixup_Hexagon_B22_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa9d43956f2ba0ad2b6a14b6f15d8a9d1b"></a></td>
<td class="doxyEnumItemDescription"> (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B15_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa8e7f405b8420c4b38d640cd008c0f1b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B7_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4faec512985edaee90285f046598a99c063"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa62fc0b99badda962b2f1bcdd1367ff13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa9ac1d082837fe4e072372d5479ecd945"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa0a49adb0d61b7f58450fa61d489c9de5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa983047fe1d9d76db3ea8ada08e1a1761"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_8<a id="a6fdd89bf2fcdd5502331328b94f4bd4facd53bc898ef0ddc41efd51d392581b89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GPREL16_0<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa9138381af1cca4c3b1b6d704b99a1264"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GPREL16_1<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa8772f6b3894ea2528dd63a9b18d486c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GPREL16_2<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa86787739672c42f914e9cff84b54fd08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GPREL16_3<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa09ee45819d307cd444ef760ba4b4a839"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_HL16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa79ef6386750168ee03339b4d203ec396"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B13_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa3892bebaed52b6bb7704fb4705bfd3ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B9_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa8433e062504192a5113a2e9d08e911e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B32_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa659fb706c1401f9541effc64fa54ba68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa8d74109744840889ca2b701dfcdac096"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B22_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fadfd8c0fda1dc285ceabeb34ddcd3a226"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B15_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fadba6b69224d9575e3845b5a1d5fbf437"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B13_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa5742fbb01e95827aa1d4fed0e8bf49db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B9_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4faf7ad305a417f6572f3ecc7d3d73179ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_B7_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa2fc452a2d9e80df1f68ec27693e9632c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa1238f42b1826506b29adb8d7e79b6881"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_12_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa4a4308781cf42caa5826013ce7196fa5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_11_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fab6c0d1722606ba0c87cf23facac8cf9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_10_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fad99ecf031674f184411b22dc55e59659"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_9_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fac2aefbd0a7d3415735342e0b3dd7607d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_8_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa1752309db082a3eaf850e6478cb6e2ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_7_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa88a5681b1be1d10a65270e11a9680a51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa75669d3838a8248efdcecdf57ea4eaee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_32_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa58d886d876663e910bb42d4711cd3a47"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_COPY<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa1e3c630a7c5b5dc7c5329435a6b41a97"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GLOB_DAT<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa27b6bfa00bdafea93c099b82427a4825"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_JMP_SLOT<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa170d14cf0c7d0e241f21dde3baf09d24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_RELATIVE<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa85cc680592aabe5903faee5dbe52a293"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_PLT_B22_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa5de78d76e447c09d64aff72960145cd2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOTREL_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fabfc9bbd4439da18ba02014c0034ab906"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOTREL_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa58f925e6ea2b9418e5f060c7a20db09e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOTREL_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa886678bbd3b53e49c1e613b69345eb82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOT_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa6983463228ac808d9fdb72f996efd344"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOT_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa0bd79ef1d1a6a62fb91a9f28447b1e3c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOT_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa1650494cb02ba11cae46812eab294dd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOT_16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa10325a6488d2667fde692f8168f36536"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_DTPMOD_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa3e900a9a202bbab42a492fa01de22593"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_DTPREL_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa8a0fc945427de25d74ac06fbfec27455"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_DTPREL_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa3ad50b0feaad604ba6c3e1bb12d5d53e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_DTPREL_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa877c2ee214a59923396a49df10525171"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_DTPREL_16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa7380060dd15e7fae6a660465c0c0215a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_PLT_B22_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa9a689f3ed64b9083dc9b5b9d8cfaaf68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_PLT_B22_PCREL<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa1d78e3d110cd9b108eae5c7dfe20b9c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_GOT_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa71ffeb67d2bb37d7ca90058c88c87d7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_GOT_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa0bd2f6d5a9ddac2ae30d825a7c9c0aff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_GOT_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa95aa368cc3aa0efc85295e5e0fda662e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_GOT_16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa5bddf1f4c7df22f46a83d1ffeec2d9dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_GOT_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fab96a52b0f2dd5f94298e3a0c2b292498"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_GOT_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa46d5b5f65f0c34f1df0dc1d127bb267b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_GOT_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fae835cb5b9d766d2a38aa6dc318ead74c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_GOT_16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa8f23abef486b6e149287dd187f4a1774"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4faf702bce95b626ec4b9882426369264e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa640f88cd125f9b795bf9ea5637c1af80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa96cfce497d5a8ffbc24e234b6b5b65dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa47a387a1776b251aaf360a6dce6c506a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_GOT_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa3eee608f87c662e714399c4da1bcdfe0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_GOT_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fac7156b443277048d58471fe1abd746e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_GOT_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa9ad1ee188faef46ac49cd93b07a0e805"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_GOT_16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fab8ade61a33bbfaa4d5a25268acc2b601"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_TPREL_LO16<a id="a6fdd89bf2fcdd5502331328b94f4bd4faa504ba238a35d3921438a7cc482d33ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_TPREL_HI16<a id="a6fdd89bf2fcdd5502331328b94f4bd4faa5df11702270e9d9efea4564ee46ebeb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_TPREL_32<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa51750857d8c467426b78cf2b3335ba92"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_TPREL_16<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa404621dd8b91539d09de1373561a5443"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_6_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa94c391478d4495def35b608d8d49aecd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOTREL_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4faf1153ccc22742ec0464cb1b9927eecc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOTREL_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fafa196a1c11f392e0d0778479cbdcb390"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOTREL_11_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fad4fc2083e1517b0cf6dfd085231fbd89"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOT_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fac97b8f66ee281a6286efcebc4697e7ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOT_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa5b53b6d46a35711771f21d6988e00bc6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GOT_11_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fad2f0d42bcf2a8b8d8cc55870ea4f968a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_DTPREL_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa703bfe0936ee91755b39ec64dceed58b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_DTPREL_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fad98d188763eb82743804f9487e2aa1e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_DTPREL_11_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa824c46bf71f91ca5c47d28f611512b25"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_GOT_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa46bb2621d89288ade28fc1ef2bcd0d7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_GOT_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa698984f6e98ef90a74f4ffb1110c8e83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_GOT_11_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa69dd3f3b5eee56c84b9d3d753f9f3696"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_GOT_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4faab1514b556208cf0151233da6d70a0c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_GOT_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa8e2d48cfc26356af4a52ab9738e813de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_GOT_11_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fad2c0c2014c24cb796bfcbeebd7bc8a02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fae0bfea17caa1f1375f045bc52c812870"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa762facc50089208c6007d89f6935c99b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_GOT_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa59c78c64a975df3e44624569e8142127"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_GOT_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa1437ba334dcf5bdf60eed35e439eeccd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_IE_GOT_11_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fae412b909dd6c896523c05e3d7f1315d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_TPREL_32_6_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa27a221e1c9b48f060c699ffef2bc3784"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_TPREL_16_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa2a2067c1eb00e35133f5d83164e77267"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_TPREL_11_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fabb0a4c45ae086959ca277bb07406f6ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_23_REG<a id="a6fdd89bf2fcdd5502331328b94f4bd4faf45ac0138cce02b717e60b43ac920e06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_27_REG<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa105e484db4846fe2f4433677246b78e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_PLT_B22_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa95bb47d6433e0d1496f52a00247731dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_GD_PLT_B32_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa72100ecf8c35b05ed173bdb24b6cd01e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_PLT_B22_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa43847e6cd11cfe076051a9997931709a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fixup_Hexagon_LD_PLT_B32_PCREL_X<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa07f492a937c5572b112d66da7966073c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="a6fdd89bf2fcdd5502331328b94f4bd4fab984de158fd26c0a47bca080dc502c6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="a6fdd89bf2fcdd5502331328b94f4bd4fa6ae0c38cd8fb6d8505e1d6008bd48f50"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonfixupkinds-h">HexagonFixupKinds.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getCpu() {#afd5440e15db345bf9daf9a8961192663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Hexagon::ArchEnum &gt; llvm::Hexagon::getCpu (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagondeparch-h">HexagonDepArch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="#ac51913459c748e1d7176ab02946c4436a8cff5423006469332e8ae5e3a8c8559c">V5</a>, <a href="#ac51913459c748e1d7176ab02946c4436a7e2f25174ce09de028190095cc693a5e">V55</a>, <a href="#ac51913459c748e1d7176ab02946c4436a8336608773c499fd7e37000fac2f9cfd">V60</a>, <a href="#ac51913459c748e1d7176ab02946c4436a113b0d77002193057e4a99b66ceb8264">V62</a>, <a href="#ac51913459c748e1d7176ab02946c4436aa7903c0ef33fd8000b9fded2bd20f6cb">V65</a>, <a href="#ac51913459c748e1d7176ab02946c4436a2267b8c0f3b8c12c5bbbf66978544a0d">V66</a>, <a href="#ac51913459c748e1d7176ab02946c4436a0db1fd5100de9dcbc5f2949df2a2dbf7">V67</a>, <a href="#ac51913459c748e1d7176ab02946c4436a52cd6998d793235c390b570fba7d206c">V68</a>, <a href="#ac51913459c748e1d7176ab02946c4436a08c198530a951b0d1adc8c0f38967bb1">V69</a>, <a href="#ac51913459c748e1d7176ab02946c4436a21f8c41b215c6879bfc46b10e506d2d4">V71</a>, <a href="#ac51913459c748e1d7176ab02946c4436a4084fbfbf7c3d3e99fcda5f126a1e494">V73</a>, <a href="#ac51913459c748e1d7176ab02946c4436ab1cab2dc211faa7bcebb331fd40454fb">V75</a> and <a href="#ac51913459c748e1d7176ab02946c4436a98a8f93c2a6e174b45fc01e59ccf8ffe">V79</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a8377a5a0fe394aab78e4bc5b6b0ce059">isCPUValid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EndPacket {#a809581007d9606439cd605eefab3a095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned int llvm::Hexagon::EndPacket = 0x2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinefunctioninfo-h">HexagonMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmachinefunctioninfo/#a2b982d230004776391b728c0a3b8bef1">llvm::HexagonMachineFunctionInfo::isEndPacket</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmachinefunctioninfo/#a37f91c0f5e3d3c9245c0a2772b085914">llvm::HexagonMachineFunctionInfo::setEndPacket</a>.</p>

</div>
</div>

### StartPacket {#aa29950c043a46c5916188a0305b25a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned int llvm::Hexagon::StartPacket = 0x1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinefunctioninfo-h">HexagonMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonmachinefunctioninfo/#a29586224d5a5337dfc6544def4d19c76">llvm::HexagonMachineFunctionInfo::isStartPacket</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonmachinefunctioninfo/#a2547946f8777966953e13b56e395fec8">llvm::HexagonMachineFunctionInfo::setStartPacket</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagondeparch-h">HexagonDepArch.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinefunctioninfo-h">HexagonMachineFunctionInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonregisterinfo-h">HexagonRegisterInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonfixupkinds-h">HexagonFixupKinds.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
