---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/loongarchisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `LoongArchISD` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::LoongArchISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#a16e44310c7754d9aa2f8ef078680173d">...</a> }</td>
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

### NodeType {#a16e44310c7754d9aa2f8ef078680173d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoongArchISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a16e44310c7754d9aa2f8ef078680173daa9409a153dcb4da4dd167053ce07b78e"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="a16e44310c7754d9aa2f8ef078680173daea7e732b7ad28bd5de4822cbcbe21424"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_MEDIUM<a id="a16e44310c7754d9aa2f8ef078680173da9e54be457abe8f04aa81e8214b17eca2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_LARGE<a id="a16e44310c7754d9aa2f8ef078680173da995de542569efd8aeffa340e606fe7e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET<a id="a16e44310c7754d9aa2f8ef078680173daef4e84dbabd85304b0ab5cb2b22d41f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAIL<a id="a16e44310c7754d9aa2f8ef078680173da53b1450373a01565b0598c3679e45b74"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAIL_MEDIUM<a id="a16e44310c7754d9aa2f8ef078680173dadb4b2bff938bc0a222fb3f68d9a8742c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAIL_LARGE<a id="a16e44310c7754d9aa2f8ef078680173da5ca4184707b9b7c314b7213ba4206039"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SLL_W<a id="a16e44310c7754d9aa2f8ef078680173da3d64e3958ac74aa715a82fbd2783caf3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA_W<a id="a16e44310c7754d9aa2f8ef078680173da7627befae1ce072327ebb2e75641f99d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRL_W<a id="a16e44310c7754d9aa2f8ef078680173da8b3116bbd1f7982ce8b1b33f68aa2843"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTL_W<a id="a16e44310c7754d9aa2f8ef078680173da745a6a028e3b1bc0264e9e59601ae736"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTR_W<a id="a16e44310c7754d9aa2f8ef078680173da7d9e05bba71a558f4059d7ce968f2b27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIV_W<a id="a16e44310c7754d9aa2f8ef078680173dabb487673238b678c64d7604228efc69c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOD_W<a id="a16e44310c7754d9aa2f8ef078680173da72ef6399f346ea7d6522991771d3ab96"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIV_WU<a id="a16e44310c7754d9aa2f8ef078680173daf6d70d5108279959c2cd93c7d9d3e365"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOD_WU<a id="a16e44310c7754d9aa2f8ef078680173dafd63c389cac07eafb5003dd74d0776f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVGR2FR_W_LA64<a id="a16e44310c7754d9aa2f8ef078680173dab3deaf5c0d8d1750eca89c8f2b3fd6d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVFR2GR_S_LA64<a id="a16e44310c7754d9aa2f8ef078680173dab3d99ae88997dab6593c4e44acfefb7b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVFCSR2GR<a id="a16e44310c7754d9aa2f8ef078680173da2d832b2ed68ba866279ed35d6eba4e82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVGR2FCSR<a id="a16e44310c7754d9aa2f8ef078680173da9ef49b549f293082eee0b2be4eedfe0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FTINT<a id="a16e44310c7754d9aa2f8ef078680173da7c466bbc4d5a7ba227150e094771f3e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CLZ_W<a id="a16e44310c7754d9aa2f8ef078680173da2cdc10496ddd8976f00069295ec57cf4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CTZ_W<a id="a16e44310c7754d9aa2f8ef078680173da6ff6b5077e0f0ae40c69088f340d5b8a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSTRINS<a id="a16e44310c7754d9aa2f8ef078680173da5ae216e744fd6c5d92686d129f73ce49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BSTRPICK<a id="a16e44310c7754d9aa2f8ef078680173da07d733e4465dddd4317a2c20527166cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REVB_2H<a id="a16e44310c7754d9aa2f8ef078680173da2378eaa2a4dfe9ad0d87733456df7b9f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REVB_2W<a id="a16e44310c7754d9aa2f8ef078680173da5e1fbdb336d9a092ae95c49c23eaa95b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITREV_4B<a id="a16e44310c7754d9aa2f8ef078680173da6099f35e3a2fe882620fd5ee87687d70"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITREV_8B<a id="a16e44310c7754d9aa2f8ef078680173da425c26740bc50eb88089040f1912fe7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITREV_W<a id="a16e44310c7754d9aa2f8ef078680173dafd69c1352cb6f9c53c74cca401982531"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BREAK<a id="a16e44310c7754d9aa2f8ef078680173da96bfa62ff39817b36cc131df2902d882"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CACOP_D<a id="a16e44310c7754d9aa2f8ef078680173dad389dc62e8340658e402611dee2e0dc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CACOP_W<a id="a16e44310c7754d9aa2f8ef078680173da8c0414712618617efe3552b67a391e4f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DBAR<a id="a16e44310c7754d9aa2f8ef078680173da816f2d5f6abe9b794fc3f52064e825f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IBAR<a id="a16e44310c7754d9aa2f8ef078680173da29f6236a5a4fe7a7041a91f52d244689"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SYSCALL<a id="a16e44310c7754d9aa2f8ef078680173dac3b4c91b2dd28d014b0d81601d43584b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRC_W_B_W<a id="a16e44310c7754d9aa2f8ef078680173dab0388df0e109f74c438e59a5eec64656"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRC_W_H_W<a id="a16e44310c7754d9aa2f8ef078680173dae5aa62d4289a9bb8450eb25257d65ba3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRC_W_W_W<a id="a16e44310c7754d9aa2f8ef078680173dac7150652d3b1dbe317d8351c66d02a03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRC_W_D_W<a id="a16e44310c7754d9aa2f8ef078680173dafad00edd30940f1a1536e381dc484924"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRCC_W_B_W<a id="a16e44310c7754d9aa2f8ef078680173da4de271cfd6f2eedec8c89ae7a1cd7ecc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRCC_W_H_W<a id="a16e44310c7754d9aa2f8ef078680173da9f5e3cf1580911129d1c3fd16267889d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRCC_W_W_W<a id="a16e44310c7754d9aa2f8ef078680173da573213288ed334850c672c46fd211fc8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CRCC_W_D_W<a id="a16e44310c7754d9aa2f8ef078680173da2f508043d334b5c8ba9915dfc39dc431"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSRRD<a id="a16e44310c7754d9aa2f8ef078680173daf3a2de25eaa2b291b53217107644c140"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSRWR<a id="a16e44310c7754d9aa2f8ef078680173da276d956ade33407a64a64f9742c3084c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSRXCHG<a id="a16e44310c7754d9aa2f8ef078680173da80ed9f3139f2e6424c8767738d99f6eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOCSRRD_B<a id="a16e44310c7754d9aa2f8ef078680173dabbdb870438763a750ea0f72ddafa5dae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOCSRRD_W<a id="a16e44310c7754d9aa2f8ef078680173da7db0bd4f9163911c34dfb42b01175fe5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOCSRRD_H<a id="a16e44310c7754d9aa2f8ef078680173da8a26dee3fb18e22ebf062f7a87cb08ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOCSRRD_D<a id="a16e44310c7754d9aa2f8ef078680173da976ebfec5bfd6cc814daad7cab16f99f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOCSRWR_B<a id="a16e44310c7754d9aa2f8ef078680173dabfae4cf1558208a3879af87c4221facf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOCSRWR_H<a id="a16e44310c7754d9aa2f8ef078680173dac9225714fa939302bf0075db665a64be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOCSRWR_W<a id="a16e44310c7754d9aa2f8ef078680173da274095654256757b9c0a1b1d7421360b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOCSRWR_D<a id="a16e44310c7754d9aa2f8ef078680173da7a87afd444898b441600cc1d2546f3d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPUCFG<a id="a16e44310c7754d9aa2f8ef078680173da8c573ef6048d08099be7543585ad916f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREPLVE<a id="a16e44310c7754d9aa2f8ef078680173da4a5ff0dd039b221ac2c5a5abfe03b643"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHUF<a id="a16e44310c7754d9aa2f8ef078680173daf0ed1c6a15d777de1a0bde9a00605ef4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPICKEV<a id="a16e44310c7754d9aa2f8ef078680173dac3b4fd375759aefa46f28c222540be3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPICKOD<a id="a16e44310c7754d9aa2f8ef078680173da67e10d4f3dff22af7cb2b87199fee975"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPACKEV<a id="a16e44310c7754d9aa2f8ef078680173da0c63b5928e4b03b8b47a69e726edcbce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPACKOD<a id="a16e44310c7754d9aa2f8ef078680173da0fe8816ade0ceae2d0b3b9a2dab5158e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VILVL<a id="a16e44310c7754d9aa2f8ef078680173dae051213419b40873029b5c01234abffb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VILVH<a id="a16e44310c7754d9aa2f8ef078680173da58fa0ecc456ad423d7bf8c6b61a7e68a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHUF4I<a id="a16e44310c7754d9aa2f8ef078680173da92042f5c156fba8108f7a56ca0642550"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREPLVEI<a id="a16e44310c7754d9aa2f8ef078680173da42e5aebace7a1a880fdea431020afa17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREPLGR2VR<a id="a16e44310c7754d9aa2f8ef078680173da6b291837dcecb1ac5242b0def87d3fd8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XVPERMI<a id="a16e44310c7754d9aa2f8ef078680173dab017ef1fb859a0af55f62577f36bdc6b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPICK_SEXT_ELT<a id="a16e44310c7754d9aa2f8ef078680173da559781f9a06a7eac7b1df3a5c4e0774e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPICK_ZEXT_ELT<a id="a16e44310c7754d9aa2f8ef078680173dae1186f2a8f97f5dbc8524c0c8ab536c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALL_ZERO<a id="a16e44310c7754d9aa2f8ef078680173da88d11a995bedfa0ee4ad0cce50fc6908"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VANY_ZERO<a id="a16e44310c7754d9aa2f8ef078680173dae3dc46e9bb491a214ec2be6e8e5d8705"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALL_NONZERO<a id="a16e44310c7754d9aa2f8ef078680173dabe432eb0bdeb059d581a9ac4bd212a42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VANY_NONZERO<a id="a16e44310c7754d9aa2f8ef078680173daae3f6812976c0a1fb4d32f75cd14d75d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRECIPE<a id="a16e44310c7754d9aa2f8ef078680173da468ab4eca324aeab0cd676e2439e9adc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FRSQRTE<a id="a16e44310c7754d9aa2f8ef078680173daa21f8bd517cb679984facaac23390c28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-h">LoongArchISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
