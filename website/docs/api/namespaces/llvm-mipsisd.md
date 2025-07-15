---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/mipsisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `MipsISD` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::MipsISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#a422daf9aa810935178671306b651d69b">...</a> }</td>
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

### NodeType {#a422daf9aa810935178671306b651d69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MipsISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a422daf9aa810935178671306b651d69ba91597fd627e43769c09cc532f7178473"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JmpLink<a id="a422daf9aa810935178671306b651d69ba6ffe3943947d5e215a842c92b923f785"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TailCall<a id="a422daf9aa810935178671306b651d69ba84922260d1582a0d4f6f0925cef648d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Highest<a id="a422daf9aa810935178671306b651d69ba230674684da59830e4af773e6393d1dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Higher<a id="a422daf9aa810935178671306b651d69ba304da432eae1d8e75d89594afb3d6f18"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Hi<a id="a422daf9aa810935178671306b651d69ba71e1753b225b38eb88e67626f6cfbff0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lo<a id="a422daf9aa810935178671306b651d69bae687521fe85a8c2b4490bba6464f5be3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GotHi<a id="a422daf9aa810935178671306b651d69ba47b57f516892e576e8800508d9991339"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TlsHi<a id="a422daf9aa810935178671306b651d69ba4a9abd1fa2b1eafc3e1cef7e2547a697"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GPRel<a id="a422daf9aa810935178671306b651d69ba48209a7d98dfb59cfd87fcdfde836d0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThreadPointer<a id="a422daf9aa810935178671306b651d69ba6658af4b0a62ee48eb164fca20224aa5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMS<a id="a422daf9aa810935178671306b651d69ba98f59986149fc5d24607be353a82c842"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPBrcond<a id="a422daf9aa810935178671306b651d69ba92a649fd8568f6f1cffd11b0886e03cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPCmp<a id="a422daf9aa810935178671306b651d69ba44b9c5d5769578c3a6689c52c3c9b1c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FAbs<a id="a422daf9aa810935178671306b651d69ba4f09e5b9ab57b1d72349caeba37a0dc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSELECT<a id="a422daf9aa810935178671306b651d69bad16ee478dfa940adbd84aae36ce08eb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MTC1_D64<a id="a422daf9aa810935178671306b651d69ba32857b3b378b466787e3e75c6c09d770"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMovFP_T<a id="a422daf9aa810935178671306b651d69ba828cbd76d0b9af6de505d186f3011b79"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMovFP_F<a id="a422daf9aa810935178671306b651d69ba3a6a21a2d276a42c197770044394d028"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TruncIntFP<a id="a422daf9aa810935178671306b651d69baabe596117d9a980304cfe3a090863974"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ret<a id="a422daf9aa810935178671306b651d69ba366e1eac31eeb1a1892d62ccfc0c8cf8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ERet<a id="a422daf9aa810935178671306b651d69baf71ae49db5c9512a30d897ef7dff5e1e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_RETURN<a id="a422daf9aa810935178671306b651d69baac73ab8f8ec895ed89445f3e6a203921"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFHI<a id="a422daf9aa810935178671306b651d69ba2a748b4e6332ee6f1fcdef61e71112ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MFLO<a id="a422daf9aa810935178671306b651d69bae4189aa234aa339a28c96ba4619b6127"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MTLOHI<a id="a422daf9aa810935178671306b651d69baaa3a89a99b8de6901fca06b0a8ef6fc7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mult<a id="a422daf9aa810935178671306b651d69ba489c5c03b43333daa30af69d887fc1f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Multu<a id="a422daf9aa810935178671306b651d69baa9e622d1e702caa06bf51a57db994824"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAdd<a id="a422daf9aa810935178671306b651d69bae4ae06d8231c915d3a38cdaa566f19e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAddu<a id="a422daf9aa810935178671306b651d69ba024ac538f26dc815e5003dbfc7d0327b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSub<a id="a422daf9aa810935178671306b651d69ba5a3db6784c014740498303318623d822"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSubu<a id="a422daf9aa810935178671306b651d69bac72d871382f44009d2a1e136610dfb40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DivRem<a id="a422daf9aa810935178671306b651d69ba78f756a9d54535a9d5c68a0566b59623"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DivRemU<a id="a422daf9aa810935178671306b651d69ba0631b78a3ec3f07b63c0813fc261f1f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DivRem16<a id="a422daf9aa810935178671306b651d69ba2de1b8d6037bc7e75328df25ee7ca7a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DivRemU16<a id="a422daf9aa810935178671306b651d69ba6178329f87bb3b3fb8fd249cff4578b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BuildPairF64<a id="a422daf9aa810935178671306b651d69ba88ffa8113b6c4225bf003666059d414d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExtractElementF64<a id="a422daf9aa810935178671306b651d69ba1545eb8951c999495303a078459ca3e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Wrapper<a id="a422daf9aa810935178671306b651d69bab66c1ce49361a050c152c59394d0e394"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DynAlloc<a id="a422daf9aa810935178671306b651d69ba01f63ea4f5784b419988cabeb1028e47"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sync<a id="a422daf9aa810935178671306b651d69bab5291bce1e8881a9f3f1ee9981b422ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ext<a id="a422daf9aa810935178671306b651d69ba88a797f57846adb2c382b3732b471913"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ins<a id="a422daf9aa810935178671306b651d69bad5006873d15f9569d1cf09deef3c6363"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CIns<a id="a422daf9aa810935178671306b651d69ba9e5ce4da69f90c2676e11b3f1571c808"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTP<a id="a422daf9aa810935178671306b651d69ba6ffafd27acd561721645cf9062649650"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTPDP<a id="a422daf9aa810935178671306b651d69ba160d807a08cfa50f0fe067d7b507cd4f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTR_S_H<a id="a422daf9aa810935178671306b651d69bad3624e2c68f103c6a257d2ca46ea1150"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTR_W<a id="a422daf9aa810935178671306b651d69baf2e111b735626a02f75856148ac05069"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTR_R_W<a id="a422daf9aa810935178671306b651d69bab21c1416d9487cf068d978d1e33c8081"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EXTR_RS_W<a id="a422daf9aa810935178671306b651d69ba9a915233797c186132f7f0be8e219d12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHILO<a id="a422daf9aa810935178671306b651d69ba27b6ac874e312b5f37fbc649f966c9c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MTHLIP<a id="a422daf9aa810935178671306b651d69ba3bc20adbd2089ad5a30d82f50be7f7fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULSAQ_S_W_PH<a id="a422daf9aa810935178671306b651d69ba27f29ec16a5aaa356f96ff1c1205002f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAQ_S_W_PHL<a id="a422daf9aa810935178671306b651d69ba1063fbee44d8aea14d4569b43ce16170"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAQ_S_W_PHR<a id="a422daf9aa810935178671306b651d69ba56b7f3af4e2ee597ed9534143bf901ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAQ_SA_W_PHL<a id="a422daf9aa810935178671306b651d69baee8772bc7c72109e060df72d0493f1f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAQ_SA_W_PHR<a id="a422daf9aa810935178671306b651d69ba87e9e312ebaabf1a9c472bc9138120ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPAU_H_QBL<a id="a422daf9aa810935178671306b651d69bae452b9b2a62c6666e17c1391a08b318d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPAU_H_QBR<a id="a422daf9aa810935178671306b651d69ba54dd2a2b5a29f17b022c436a563a6df1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPSU_H_QBL<a id="a422daf9aa810935178671306b651d69bab2e20f4730b6dee393b525d5a73449f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPSU_H_QBR<a id="a422daf9aa810935178671306b651d69ba304cd83316b5db1f958489ec4e3347e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPAQ_S_W_PH<a id="a422daf9aa810935178671306b651d69baf9bd57cd73be476056c3fa256791db13"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPSQ_S_W_PH<a id="a422daf9aa810935178671306b651d69ba6fb87fbe4a280ff588b31530e8e1aed7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPAQ_SA_L_W<a id="a422daf9aa810935178671306b651d69ba0a2ea41a49ec7e1c17c4761b99d264f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPSQ_SA_L_W<a id="a422daf9aa810935178671306b651d69babd56ae0a2e1453041b199a1ca7d6123a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPA_W_PH<a id="a422daf9aa810935178671306b651d69ba5012e99fb35a23c09158acee6c102aef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPS_W_PH<a id="a422daf9aa810935178671306b651d69ba5e93986f8d0b530a4b0daa3c0063fa7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPAQX_S_W_PH<a id="a422daf9aa810935178671306b651d69babc1c128d43a0149d14663608966c5e05"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPAQX_SA_W_PH<a id="a422daf9aa810935178671306b651d69ba3272b07f2ea401b4fd0f830266b8ddb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPAX_W_PH<a id="a422daf9aa810935178671306b651d69bac4dd4476003819ed217c5e0829b30c58"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPSX_W_PH<a id="a422daf9aa810935178671306b651d69ba2d0562c15823fed62c781badcb3a11c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPSQX_S_W_PH<a id="a422daf9aa810935178671306b651d69ba769886f6ebeb03d592f12792b84129cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DPSQX_SA_W_PH<a id="a422daf9aa810935178671306b651d69baf79474ce1a2019cdcf1ad68585f5c1d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULSA_W_PH<a id="a422daf9aa810935178671306b651d69baefd22c0d0f61706ab6dbd97011972a82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULT<a id="a422daf9aa810935178671306b651d69ba2ba8e90b1a8dff465d899e33a6404a81"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MULTU<a id="a422daf9aa810935178671306b651d69baef631f9b0e1ee2e3c46a1a448d2d3efb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MADD_DSP<a id="a422daf9aa810935178671306b651d69ba178be7a8cb8b7f4cefe8887e8b8ab0ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MADDU_DSP<a id="a422daf9aa810935178671306b651d69ba89c071e5a8c88386c138c430b31a95ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSUB_DSP<a id="a422daf9aa810935178671306b651d69ba70ad31600a42c92a4924e177020fc54d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSUBU_DSP<a id="a422daf9aa810935178671306b651d69ba92ddaeff1e7d980c97e9ce423c230a44"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHLL_DSP<a id="a422daf9aa810935178671306b651d69ba8ff274ae7e92745980a867ebc2695d0d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHRA_DSP<a id="a422daf9aa810935178671306b651d69ba99372f35f6f83b69470648eb845e07ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHRL_DSP<a id="a422daf9aa810935178671306b651d69ba2b96b034c5babbcef2b044ccd4144eee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETCC_DSP<a id="a422daf9aa810935178671306b651d69ba8ed1313249b5f0f1b44c728bf17ce2d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECT_CC_DSP<a id="a422daf9aa810935178671306b651d69ba3115ebc375dd4e98b09907fee318dbd1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALL_ZERO<a id="a422daf9aa810935178671306b651d69ba88698c97bacd6aef8d438a130203c69a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VANY_ZERO<a id="a422daf9aa810935178671306b651d69bac346b4950388fdb4201196c03533fd5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALL_NONZERO<a id="a422daf9aa810935178671306b651d69ba94a8fbea394947cfd85ab7939f931378"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VANY_NONZERO<a id="a422daf9aa810935178671306b651d69baf1cbc3b8a8f6b83397cba66e989e8bd2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCEQ<a id="a422daf9aa810935178671306b651d69ba5ac3089162d80f74ee295dfbf1cfcafb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCLE_S<a id="a422daf9aa810935178671306b651d69ba9e01e7638de924f0942d420c5ff4d604"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCLE_U<a id="a422daf9aa810935178671306b651d69bafc6b3d5974ca43368eb99e8558202394"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCLT_S<a id="a422daf9aa810935178671306b651d69ba7533897bc18887557911e1c835948d5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCLT_U<a id="a422daf9aa810935178671306b651d69ba74bc5737732b04f461f372dadf6ec16b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHF<a id="a422daf9aa810935178671306b651d69bafb6a806352c26482752f729ff5843752"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHF<a id="a422daf9aa810935178671306b651d69baad35f47170b3dabe28b51462d40ba212"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ILVEV<a id="a422daf9aa810935178671306b651d69ba66d3e593d4b5d9355845418ce07b8093"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ILVOD<a id="a422daf9aa810935178671306b651d69ba7480b95bf7e21f17e79e3ef6f26b2090"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ILVL<a id="a422daf9aa810935178671306b651d69ba1559a6a52ea1b86e53852f0c4e11fe0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ILVR<a id="a422daf9aa810935178671306b651d69ba4ace0dc4a4017232cc502e6a7e238038"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCKEV<a id="a422daf9aa810935178671306b651d69ba721b30ace12bdac89b93684865ee6941"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCKOD<a id="a422daf9aa810935178671306b651d69ba059c603e586f238f5ec78c99c6dc1eaa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INSVE<a id="a422daf9aa810935178671306b651d69badceba4e61f97a26798aac5824e2fcd4f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VNOR<a id="a422daf9aa810935178671306b651d69bae2495da6743e7ab111e7a6d58fc9260b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEXTRACT_SEXT_ELT<a id="a422daf9aa810935178671306b651d69bae92303a8af654541359884ddfc76af00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEXTRACT_ZEXT_ELT<a id="a422daf9aa810935178671306b651d69ba6f1d5020c110223d3bb85a6e82e3b618"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DOUBLE_SELECT_I<a id="a422daf9aa810935178671306b651d69bac9b0dd713fedef231f6934be939701f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DOUBLE_SELECT_I64<a id="a422daf9aa810935178671306b651d69ba3a1817f931bce782df97320107134c00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_MEMORY_OPCODE<a id="a422daf9aa810935178671306b651d69ba5b6a508b5e09e0634a4110883b0784dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LWL<a id="a422daf9aa810935178671306b651d69bafe575bccaad054f296d74a527463714a"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_MEMORY_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LWR<a id="a422daf9aa810935178671306b651d69ba00d989ef11bb6ca53e1669a0780109e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SWL<a id="a422daf9aa810935178671306b651d69ba606a3ada58afda41f8d8fa0dea24762b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SWR<a id="a422daf9aa810935178671306b651d69ba912bbd12a43c7565b673301ed0e0b92e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDL<a id="a422daf9aa810935178671306b651d69ba7c9bd3f26365a95215ef02f178696ca1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDR<a id="a422daf9aa810935178671306b651d69baa0686bd3f7b2056b4fc76d2b4ec46e17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDL<a id="a422daf9aa810935178671306b651d69ba802783759d8d5f51e58652e651a2f543"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SDR<a id="a422daf9aa810935178671306b651d69ba98e5728321f3e1a33ebf7881011faf03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_MEMORY_OPCODE<a id="a422daf9aa810935178671306b651d69ba54ba77ed9c65e892eb951e3142bd63d7"></a></td>
<td class="doxyEnumItemDescription"> (= SDR)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-h">MipsISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
