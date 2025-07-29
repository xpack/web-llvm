---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/armisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `ARMISD` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::ARMISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType : unsigned { <a href="#a4097c262adca175c068cc59fa984dc38">...</a> }</td>
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

### NodeType {#a4097c262adca175c068cc59fa984dc38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMISD::NodeType : unsigned</td>
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
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a4097c262adca175c068cc59fa984dc38a2da4296d7bd9b77819b2684f456cb3ab"></a></td>
<td class="doxyEnumItemDescription"> (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Wrapper<a id="a4097c262adca175c068cc59fa984dc38a029f48a0b5e0d471de85baca7745d1a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WrapperPIC<a id="a4097c262adca175c068cc59fa984dc38a6a715cec66d0a16ea7b9fde9958f1546"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WrapperJT<a id="a4097c262adca175c068cc59fa984dc38a114c5ea64df684330a0ec619fed19ffd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COPY_STRUCT_BYVAL<a id="a4097c262adca175c068cc59fa984dc38a58ca12649e834dcfac522cec82df3793"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="a4097c262adca175c068cc59fa984dc38a2af8075cd139f844ae07ed7988cbb2b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_PRED<a id="a4097c262adca175c068cc59fa984dc38ace024bb2e9c3935008e16e7be869af98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL_NOLINK<a id="a4097c262adca175c068cc59fa984dc38ab204e019469f4548ac436586a605f41f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tSECALL<a id="a4097c262adca175c068cc59fa984dc38af37e43d1efe2f7cdddcd4a7626fb5612"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">t2CALL_BTI<a id="a4097c262adca175c068cc59fa984dc38a11eb299481204e113f0518f48d6ad65d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRCOND<a id="a4097c262adca175c068cc59fa984dc38a4621d333784e3cd8c9f92a1443013dbe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR_JT<a id="a4097c262adca175c068cc59fa984dc38a8dfd4ea5a4e33bdb35fcafb11d1073cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BR2_JT<a id="a4097c262adca175c068cc59fa984dc38abacb1d6d27b76e9aeb011e2302033470"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="a4097c262adca175c068cc59fa984dc38a672872cbaad3c84753f0d5a8f70ae17d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SERET_GLUE<a id="a4097c262adca175c068cc59fa984dc38aa8f29efa4adf770c4f955fc8f0da06dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INTRET_GLUE<a id="a4097c262adca175c068cc59fa984dc38ad1ceedbd26427868e0370cbbeed597f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PIC_ADD<a id="a4097c262adca175c068cc59fa984dc38a5bc71a39554a14104bfd1011dffbed0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASRL<a id="a4097c262adca175c068cc59fa984dc38ae943be65cd3ae29f0032ad56a3875c42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSRL<a id="a4097c262adca175c068cc59fa984dc38ab729d2ded9bb455206f7944e09444c73"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSLL<a id="a4097c262adca175c068cc59fa984dc38a3e9bf86bbbfea029b1f065cc6fbab978"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMP<a id="a4097c262adca175c068cc59fa984dc38aaed0e0931ede9056a03d792401e655a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMN<a id="a4097c262adca175c068cc59fa984dc38a73bd03dfbab0f65cbd59365be36c9637"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPZ<a id="a4097c262adca175c068cc59fa984dc38ab7f9acd96e942ca625335c36de28e60e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPFP<a id="a4097c262adca175c068cc59fa984dc38acefb30e98102150caa66322bfa40dd50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPFPE<a id="a4097c262adca175c068cc59fa984dc38a3bfec195f10a9950076570fda7745484"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPFPw0<a id="a4097c262adca175c068cc59fa984dc38a28ca54417ad23eee114779d2bb800ff0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPFPEw0<a id="a4097c262adca175c068cc59fa984dc38af8ad86574b674ce3ed7a491df714b3d1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMSTAT<a id="a4097c262adca175c068cc59fa984dc38a6b4121a8201ef54013a43cce7972b532"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMOV<a id="a4097c262adca175c068cc59fa984dc38aee74cff1cb1ea095617b5fa044e342db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSAT<a id="a4097c262adca175c068cc59fa984dc38aa173c041ee452fcdffb797075a892b84"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USAT<a id="a4097c262adca175c068cc59fa984dc38ae60ed52746753eeb5502fcfceb13f2fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BCC_i64<a id="a4097c262adca175c068cc59fa984dc38a93de4757f6b73b98f83df6c84ba335fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSLS<a id="a4097c262adca175c068cc59fa984dc38a84182cd89ac8df2cb9309ad6e30181fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSRS1<a id="a4097c262adca175c068cc59fa984dc38a5aef4524ffbb7e5e7ccd6a073c9f6a2c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASRS1<a id="a4097c262adca175c068cc59fa984dc38a2bb669fe5faf69d683427c11ccea256f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RRX<a id="a4097c262adca175c068cc59fa984dc38ae14aa6c4f09a840b110709145e862660"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDC<a id="a4097c262adca175c068cc59fa984dc38a41f4297f00dc6d8d7445d13daf7eba26"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDE<a id="a4097c262adca175c068cc59fa984dc38a38281aedc70f7c707027367acd3234cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBC<a id="a4097c262adca175c068cc59fa984dc38a9cfc13d8dfcbb7d035be110b619ea741"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUBE<a id="a4097c262adca175c068cc59fa984dc38a06e89dbcfaf0ceca94295988d35809c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOVRRD<a id="a4097c262adca175c068cc59fa984dc38a7f93dc1b4123a3d49e2a544960758ef1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOVDRR<a id="a4097c262adca175c068cc59fa984dc38a0791f9172a1b74506504d1f22d81f389"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOVSR<a id="a4097c262adca175c068cc59fa984dc38a240b00dd73991507ba0171aaad5613c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_SETJMP<a id="a4097c262adca175c068cc59fa984dc38ac40d2d97a5232355c7e4356a5b1b348f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_LONGJMP<a id="a4097c262adca175c068cc59fa984dc38a9060e4d9fd2c82efb5271a282b477e6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EH_SJLJ_SETUP_DISPATCH<a id="a4097c262adca175c068cc59fa984dc38a415b28d48c69281b494b5676513b9729"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TC_RETURN<a id="a4097c262adca175c068cc59fa984dc38ae8db6245139cf9e51bf5d85ddb4aa40f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">THREAD_POINTER<a id="a4097c262adca175c068cc59fa984dc38a663f1912d43363b57a06adfaabf0fedb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DYN_ALLOC<a id="a4097c262adca175c068cc59fa984dc38a91cab2531250dcbe6ff4002d96ba1f5a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMBARRIER_MCR<a id="a4097c262adca175c068cc59fa984dc38a7a2ddf62b8434c6d91a878826c541dad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRELOAD<a id="a4097c262adca175c068cc59fa984dc38a07da1ed30667d9280b73a46ef24e5fac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WIN__CHKSTK<a id="a4097c262adca175c068cc59fa984dc38a6143acc30126957cfa4330ffa4383ba5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WIN__DBZCHK<a id="a4097c262adca175c068cc59fa984dc38a62d363916df0556c38dd1014c45b7a46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WLS<a id="a4097c262adca175c068cc59fa984dc38a83135d8a8ab6d3b2bdc77560e7088a36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WLSSETUP<a id="a4097c262adca175c068cc59fa984dc38ac09bfe85bbfd03505987fdae620a20bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOOP_DEC<a id="a4097c262adca175c068cc59fa984dc38a4dee32244ce74164a053c8c25bea9226"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LE<a id="a4097c262adca175c068cc59fa984dc38adaeab816ead72a28ed9c4282edcf2130"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PREDICATE_CAST<a id="a4097c262adca175c068cc59fa984dc38a1e452bb26851eafc6364ba340c36ecf0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VECTOR_REG_CAST<a id="a4097c262adca175c068cc59fa984dc38a40f2efa7d8c9b15db57cc3500bba1f09"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MVESEXT<a id="a4097c262adca175c068cc59fa984dc38a9326d7ebc2b118b134db7934f6fa4713"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MVEZEXT<a id="a4097c262adca175c068cc59fa984dc38ad0fc91cb6c69b2e9e9ef67d896bd76a5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MVETRUNC<a id="a4097c262adca175c068cc59fa984dc38afcd7b69a3ab8e9b9c40b7a973d961b05"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCMP<a id="a4097c262adca175c068cc59fa984dc38a7c288956c8c8e43434e6ae8633daab64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCMPZ<a id="a4097c262adca175c068cc59fa984dc38a4ca5c4fa27f6ef68b659e9deaf7545c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTST<a id="a4097c262adca175c068cc59fa984dc38a5878903e0ec87cb695f22d4851889df4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHLs<a id="a4097c262adca175c068cc59fa984dc38a1a032e767ce6dc5a014b6cb6a980e15f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHLu<a id="a4097c262adca175c068cc59fa984dc38a051f7f7ea4fa4d22680fe300119e3b46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHLIMM<a id="a4097c262adca175c068cc59fa984dc38aee85fe37c0da86af1536a98c888f9150"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHRsIMM<a id="a4097c262adca175c068cc59fa984dc38a1eb3012ff65d306c3bfcda64ca53a17c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSHRuIMM<a id="a4097c262adca175c068cc59fa984dc38ac2cc71438511eab862a4040d7dbdedc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRSHRsIMM<a id="a4097c262adca175c068cc59fa984dc38ae43d68e08454b25bde1237df049d4bfc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRSHRuIMM<a id="a4097c262adca175c068cc59fa984dc38aeb906d5db57d71d1b2adf555f95ced45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VRSHRNIMM<a id="a4097c262adca175c068cc59fa984dc38a88fe6ff9aa04ed53f2d31971d85523c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQSHLsIMM<a id="a4097c262adca175c068cc59fa984dc38a0cd0628ba1ee0cbe2f3b27056d84e31d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQSHLuIMM<a id="a4097c262adca175c068cc59fa984dc38a49f0f08f662ff51ecc3221cee92c5ede"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQSHLsuIMM<a id="a4097c262adca175c068cc59fa984dc38adf824fd0265a67f9e20a992536543787"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQSHRNsIMM<a id="a4097c262adca175c068cc59fa984dc38a9cecd45f88e494fe8828dd3b7e566547"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQSHRNuIMM<a id="a4097c262adca175c068cc59fa984dc38a1241f4af5ed5a4f37eed9e1490a3754e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQSHRNsuIMM<a id="a4097c262adca175c068cc59fa984dc38a1f8d979594f9d98e26744923151e7248"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQRSHRNsIMM<a id="a4097c262adca175c068cc59fa984dc38a3bed0337c3e72d48b7acb7d944bc92a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQRSHRNuIMM<a id="a4097c262adca175c068cc59fa984dc38a28fd5ec0d2731c2711f5019e65ea17fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQRSHRNsuIMM<a id="a4097c262adca175c068cc59fa984dc38a8bbaf9840d99cfe346344a0fccf67870"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSLIIMM<a id="a4097c262adca175c068cc59fa984dc38a1d077dec7708f42d7317b676157efc93"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VSRIIMM<a id="a4097c262adca175c068cc59fa984dc38aa51bd387b70ce9454c4a1360f3479e1c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VGETLANEu<a id="a4097c262adca175c068cc59fa984dc38ad78d1cfc271b51dc1c87c91401b87c57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VGETLANEs<a id="a4097c262adca175c068cc59fa984dc38a29bc6cd8219e70572b8b113c230fea6e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOVIMM<a id="a4097c262adca175c068cc59fa984dc38a5efe47c12d5ebca8c56bd48eb9d612fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMVNIMM<a id="a4097c262adca175c068cc59fa984dc38ae3708ea7a9abaabaa0a7ae12fa5b5c4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOVFPIMM<a id="a4097c262adca175c068cc59fa984dc38a242d9487902c3ae2a3d9c3d1355f8246"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOVrh<a id="a4097c262adca175c068cc59fa984dc38a3b1cd1c01c04128536b9cbe473629904"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOVhr<a id="a4097c262adca175c068cc59fa984dc38acb6fa97139e090fff02bc421e02451ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VDUP<a id="a4097c262adca175c068cc59fa984dc38a50bbb022c555743f1805d3df3ee98adb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VDUPLANE<a id="a4097c262adca175c068cc59fa984dc38a64c0bb0345ba1b69528dd52da797f6a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEXT<a id="a4097c262adca175c068cc59fa984dc38ad428215f2bb2c30a97d6de6d14d6ccdf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREV64<a id="a4097c262adca175c068cc59fa984dc38aed9adca906655e17ad5db993e80cc90f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREV32<a id="a4097c262adca175c068cc59fa984dc38a96babbe11f5e86cf3b02a0064c03c84e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VREV16<a id="a4097c262adca175c068cc59fa984dc38a612cd894d3df73b6e47707d1fc1da974"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VZIP<a id="a4097c262adca175c068cc59fa984dc38a2ce278a3ff293b574f11d4ee0276770d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VUZP<a id="a4097c262adca175c068cc59fa984dc38a3d175a42f3d21e9d95bc684768de999a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTRN<a id="a4097c262adca175c068cc59fa984dc38a78557d58c18ae631207ea472be421497"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTBL1<a id="a4097c262adca175c068cc59fa984dc38a23b7689832a24fd3eea55be8583bee87"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VTBL2<a id="a4097c262adca175c068cc59fa984dc38abf641d085a1191fdfe9f91624d8078a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMOVN<a id="a4097c262adca175c068cc59fa984dc38ac2f455684efb89d120029b7a65acd013"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQMOVNs<a id="a4097c262adca175c068cc59fa984dc38a883cd6fb091beb1d5da94e6bf2eb086a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQMOVNu<a id="a4097c262adca175c068cc59fa984dc38af1218b9767cbe26dbbbd375286b55c0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTN<a id="a4097c262adca175c068cc59fa984dc38a9a82260a4232967f7e3cf177fa2e8ced"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VCVTL<a id="a4097c262adca175c068cc59fa984dc38a99edb50eab987b63533cb44fe744a28e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VIDUP<a id="a4097c262adca175c068cc59fa984dc38a6fb8d68b511745372ea9df95347a6ea4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMULLs<a id="a4097c262adca175c068cc59fa984dc38af545e63f1ef20c06d5a6dbe6c1ec2097"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMULLu<a id="a4097c262adca175c068cc59fa984dc38af8c95bf2b6ad98c19fbaeaef1e82dd28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VQDMULH<a id="a4097c262adca175c068cc59fa984dc38a0ea65604b43fdf53982b2e0c2622abcc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDVs<a id="a4097c262adca175c068cc59fa984dc38a2c3d99682d5c725adcbe430bc69b9c99"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDVu<a id="a4097c262adca175c068cc59fa984dc38ada29df039613d536f11af709cf7691ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDVps<a id="a4097c262adca175c068cc59fa984dc38a4c7e4505cb2d2b464754f62cd8656c5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDVpu<a id="a4097c262adca175c068cc59fa984dc38a242d064c1ca083654f87ca5f7278fff9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDLVs<a id="a4097c262adca175c068cc59fa984dc38a7f60e06779eb757bcaadbbc7f1b38de2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDLVu<a id="a4097c262adca175c068cc59fa984dc38a28b0ceeefba427b139e09b5850ab9389"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDLVAs<a id="a4097c262adca175c068cc59fa984dc38a359ec09c5b0bea8d8e73795738c74b8f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDLVAu<a id="a4097c262adca175c068cc59fa984dc38ac255df83083c0579aa5acc39a0a53b92"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDLVps<a id="a4097c262adca175c068cc59fa984dc38add9d7dd92c2e0454947271184f9cea92"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDLVpu<a id="a4097c262adca175c068cc59fa984dc38adeeb8ac961b16f30b10b1dc668788211"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDLVAps<a id="a4097c262adca175c068cc59fa984dc38a245dab1b37a3890669c0d774172abfe7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VADDLVApu<a id="a4097c262adca175c068cc59fa984dc38a148d0603e46bd5ffddda6bbc2c835158"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLAVs<a id="a4097c262adca175c068cc59fa984dc38a67e82cfd8b584d35f5de2e40870dbde5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLAVu<a id="a4097c262adca175c068cc59fa984dc38a5ba46f411106d2444bd93b563cf6da00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLAVps<a id="a4097c262adca175c068cc59fa984dc38ae82b066f510c369e1b2547cb8a79e1da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLAVpu<a id="a4097c262adca175c068cc59fa984dc38a0fe5e78ddb0f285dc76fcb5205114739"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLALVs<a id="a4097c262adca175c068cc59fa984dc38a214985f7b88b1d15a7103b432dba2dbb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLALVu<a id="a4097c262adca175c068cc59fa984dc38ab4543c9ea891307c00d497963828365c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLALVps<a id="a4097c262adca175c068cc59fa984dc38a57f53fc571f810653378d8d37eac942f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLALVpu<a id="a4097c262adca175c068cc59fa984dc38aed2014a73c494554ab58c7e78e321c0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLALVAs<a id="a4097c262adca175c068cc59fa984dc38aa21f7a01a26f04604b61652864d577c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLALVAu<a id="a4097c262adca175c068cc59fa984dc38a3fe835d935b0d36f42b92c9da35f3d03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLALVAps<a id="a4097c262adca175c068cc59fa984dc38a9ae951d2026826f66fdf04140182f172"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMLALVApu<a id="a4097c262adca175c068cc59fa984dc38a0577099955f7fe7aa79056f0806e05b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMINVu<a id="a4097c262adca175c068cc59fa984dc38a7c4161403878bfbc24c4d805a52f86a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMINVs<a id="a4097c262adca175c068cc59fa984dc38a7f9beb5d6e4fe4922bf922562b678d54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMAXVu<a id="a4097c262adca175c068cc59fa984dc38a78c333b77e384722c73b2f1ecf172160"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VMAXVs<a id="a4097c262adca175c068cc59fa984dc38a609627e5fb4559af076d1b1dbb0ff536"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMULWB<a id="a4097c262adca175c068cc59fa984dc38aed7b9527784ba4e06dcf95704002dc24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMULWT<a id="a4097c262adca175c068cc59fa984dc38a8193c5897199f248b53c6fff20ce18f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMLAL<a id="a4097c262adca175c068cc59fa984dc38a8d9d96ad008a475ebbff8e366bbc1eb6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLAL<a id="a4097c262adca175c068cc59fa984dc38aa174d9797327e782f169f497338fac95"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMAAL<a id="a4097c262adca175c068cc59fa984dc38ac3dd723ee353ee1368f2ff900ed799b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLALBB<a id="a4097c262adca175c068cc59fa984dc38a5faaa77b1082966846b8847f5d53479d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLALBT<a id="a4097c262adca175c068cc59fa984dc38a9982953b4608d6356bd7fe3c4c4fe9c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLALTB<a id="a4097c262adca175c068cc59fa984dc38a7304a9dad68e35cedd3286fc2d51bee5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLALTT<a id="a4097c262adca175c068cc59fa984dc38a33ecfe3938a12d2b6b83a69094a33d29"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLALD<a id="a4097c262adca175c068cc59fa984dc38a644e5045736cf38a240f0dfca62326a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLALDX<a id="a4097c262adca175c068cc59fa984dc38a5641512dd01cc6fe498224ca1eba86fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLSLD<a id="a4097c262adca175c068cc59fa984dc38a480659fe96e678969ce3c1a631e48bb0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMLSLDX<a id="a4097c262adca175c068cc59fa984dc38adb2fe2066e41ba120b8fb629da865cfd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMMLAR<a id="a4097c262adca175c068cc59fa984dc38a729d32c1741fc630eb5a56a1b49a82ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SMMLSR<a id="a4097c262adca175c068cc59fa984dc38a3987385722cf9bbe7ea0d090bc06b722"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QADD8b<a id="a4097c262adca175c068cc59fa984dc38af914da04c6db0f9697158bf86d51bd02"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QSUB8b<a id="a4097c262adca175c068cc59fa984dc38a41ec5a4a3fcc7e41263a4bc0b6a69c65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QADD16b<a id="a4097c262adca175c068cc59fa984dc38a83728aad1cd6a81514525c49fc23ce17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QSUB16b<a id="a4097c262adca175c068cc59fa984dc38aad9651faf4a6694a93228858973219b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UQADD8b<a id="a4097c262adca175c068cc59fa984dc38a2ffd7790f42a2c3092b83e37c7fe3da9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UQSUB8b<a id="a4097c262adca175c068cc59fa984dc38ae378627a128dd34c938348e5552bd468"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UQADD16b<a id="a4097c262adca175c068cc59fa984dc38ad0f2aceb3ee7cd23f8b352d8580169a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UQSUB16b<a id="a4097c262adca175c068cc59fa984dc38aeff71ef40fdc565429b4de72440a8500"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BUILD_VECTOR<a id="a4097c262adca175c068cc59fa984dc38a9b3b5c8aca58fc851520aab312b46637"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BFI<a id="a4097c262adca175c068cc59fa984dc38a109dda4df2be3a46022e3600484f4efb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VORRIMM<a id="a4097c262adca175c068cc59fa984dc38a4fdb743470b16a85839369a93cc26368"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VBICIMM<a id="a4097c262adca175c068cc59fa984dc38aeb5a51baba9276b3e2ea25b7ac5b8806"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VBSP<a id="a4097c262adca175c068cc59fa984dc38acc417089525086253ff4296bd2f07f0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMCPY<a id="a4097c262adca175c068cc59fa984dc38aec586817cf51a463ca101fab0ce085da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMCPYLOOP<a id="a4097c262adca175c068cc59fa984dc38a98b514a4c87eb38220d1b8636145e6b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMSETLOOP<a id="a4097c262adca175c068cc59fa984dc38a8de12fac953b4c453629b726bc9e1f5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSINV<a id="a4097c262adca175c068cc59fa984dc38a7fa873eda688ec241983ec07abb187bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSNEG<a id="a4097c262adca175c068cc59fa984dc38a2f975a28397d8aaddaf658d8f09f0086"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSINC<a id="a4097c262adca175c068cc59fa984dc38abc844212c86a5d4665e522f7a7de6610"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_MEMORY_OPCODE<a id="a4097c262adca175c068cc59fa984dc38aaf8a4de44ba3bf301fc2e0a53b21ddaf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD1DUP<a id="a4097c262adca175c068cc59fa984dc38a736037fbdc5e0e5d5c0fff76584255d4"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_MEMORY_OPCODE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD2DUP<a id="a4097c262adca175c068cc59fa984dc38a81b77974c326f91d888b4f7c7346440d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD3DUP<a id="a4097c262adca175c068cc59fa984dc38aeb8a7ec48dfdbb30f676f1f9ed78515e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD4DUP<a id="a4097c262adca175c068cc59fa984dc38a682019fb60ebfdcb1b6c12bef90e81d1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD1_UPD<a id="a4097c262adca175c068cc59fa984dc38aeb657e0aaf4405a13d3379c9ef08c5e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD2_UPD<a id="a4097c262adca175c068cc59fa984dc38a3e74c01534bbe58a9716c4ed9afb552b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD3_UPD<a id="a4097c262adca175c068cc59fa984dc38a2dcef9e9a88a5601e3615bd024f89ebc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD4_UPD<a id="a4097c262adca175c068cc59fa984dc38acbc76b0e9da47cff86f227b76a101877"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD2LN_UPD<a id="a4097c262adca175c068cc59fa984dc38aef111725b7a6bc348025dbe88c610e52"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD3LN_UPD<a id="a4097c262adca175c068cc59fa984dc38ad1a20b1fad0a456eeea32953e3711d67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD4LN_UPD<a id="a4097c262adca175c068cc59fa984dc38af06cac064eb63dda89fc54210230c6c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD1DUP_UPD<a id="a4097c262adca175c068cc59fa984dc38a78c1ef042ed87df90fd74a2b0aa328af"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD2DUP_UPD<a id="a4097c262adca175c068cc59fa984dc38aeecdd98f156fccc64b091ed05e2a7fa2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD3DUP_UPD<a id="a4097c262adca175c068cc59fa984dc38a55c84e4b70ccda76faa80ac003a66b86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD4DUP_UPD<a id="a4097c262adca175c068cc59fa984dc38a8cae6c5ad12cf66a9b86fe48082bd9d1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD1x2_UPD<a id="a4097c262adca175c068cc59fa984dc38a45f54d04d055263cfafa769c509612fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD1x3_UPD<a id="a4097c262adca175c068cc59fa984dc38a0d8581feb563228efaea68ab27e9c4d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VLD1x4_UPD<a id="a4097c262adca175c068cc59fa984dc38a3b00cfff1a8708169d95c639b46e54ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST1_UPD<a id="a4097c262adca175c068cc59fa984dc38a66260b6c8cb9ac5ae51cb28d85f8609a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST2_UPD<a id="a4097c262adca175c068cc59fa984dc38af6a4c6bf81470b0f47fb5ea7d02c9422"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST3_UPD<a id="a4097c262adca175c068cc59fa984dc38a46ce1e04c61117e5b760e27351c2c209"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST4_UPD<a id="a4097c262adca175c068cc59fa984dc38a8994129f9ac9818ba7865a6df6194a15"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST2LN_UPD<a id="a4097c262adca175c068cc59fa984dc38a4fb391704986986d277b0e9f9defe47d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST3LN_UPD<a id="a4097c262adca175c068cc59fa984dc38a0e4c9035a762f061faadf268d28ed841"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST4LN_UPD<a id="a4097c262adca175c068cc59fa984dc38a1d949f0d6adbeca42c5d9084223611fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST1x2_UPD<a id="a4097c262adca175c068cc59fa984dc38aec8fdde21c8237d416596c48a6c860b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST1x3_UPD<a id="a4097c262adca175c068cc59fa984dc38ae328404e440614fcb54df7ac51f11044"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VST1x4_UPD<a id="a4097c262adca175c068cc59fa984dc38a38899d122ffababe99e5c66ba98a5c4a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LDRD<a id="a4097c262adca175c068cc59fa984dc38af367450e974cd6c5a4d38caf2ac57f40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRD<a id="a4097c262adca175c068cc59fa984dc38a8a90f7542d552553f83027180bce5ca8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_MEMORY_OPCODE<a id="a4097c262adca175c068cc59fa984dc38a10b8940aa5146883d97beb2f1b728168"></a></td>
<td class="doxyEnumItemDescription"> (= STRD)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-h">ARMISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
