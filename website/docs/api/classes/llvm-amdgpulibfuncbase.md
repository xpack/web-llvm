---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpulibfuncbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPULibFuncBase` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPULibFuncBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">Target/AMDGPU/AMDGPULibFunc.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc">AMDGPULibFunc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper class for AMDGPULIbFuncImpl. <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncimpl">AMDGPULibFuncImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EFuncId { <a href="#a1142b2c02ac329c588bf4726b61f98d3">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ENamePrefix { <a href="#a5f1a1a785d3bea7522fda8651035c2f6">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EType { <a href="#a858436a6ac3e32480363df7ec66765a8">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EPtrKind { <a href="#aac00986b9c47fed034287e1eeb01a141">...</a> }</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656ff82f4700daf658142eef8eb184d2">isMangled</a> (EFuncId Id)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a234ff52a2593b9d0f6fbd4d8aee25d11">getEPtrKindFromAddrSpace</a> (unsigned AS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2417eedd4fbca37cf773d44a0642d9">getAddrSpaceFromEPtrKind</a> (unsigned Kind)</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### EFuncId {#a1142b2c02ac329c588bf4726b61f98d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPULibFuncBase::EFuncId </td>
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
<td class="doxyEnumItemName">EI_NONE<a id="a1142b2c02ac329c588bf4726b61f98d3aad983ea959ef134ca52b0a3ec305ac32"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ABS<a id="a1142b2c02ac329c588bf4726b61f98d3a08748e3ab19024fe4af639fce69df1c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ABS_DIFF<a id="a1142b2c02ac329c588bf4726b61f98d3a4b1a2c1bf45acbb6ec8be619d6587365"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ACOS<a id="a1142b2c02ac329c588bf4726b61f98d3a64ebd7cb2e2ddbbe65bedc595ed505b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ACOSH<a id="a1142b2c02ac329c588bf4726b61f98d3a1fcbab56d02054f724d9e58c4c49f58b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ACOSPI<a id="a1142b2c02ac329c588bf4726b61f98d3acfab5cd81c45e0ec2185b36cb4ca0b88"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ADD_SAT<a id="a1142b2c02ac329c588bf4726b61f98d3abfc77ceed66baca8177cc0eedbbf1e2e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ALL<a id="a1142b2c02ac329c588bf4726b61f98d3ae27ed8a6ce1eb11e6c812e5a812d0acc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ANY<a id="a1142b2c02ac329c588bf4726b61f98d3a1d41230524e0b3e30beee2665861a453"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ASIN<a id="a1142b2c02ac329c588bf4726b61f98d3ab9167ecfbfdb3df233e4d5c55bb37c57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ASINH<a id="a1142b2c02ac329c588bf4726b61f98d3abe8ff053ab125cc4349ac586b5424afb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ASINPI<a id="a1142b2c02ac329c588bf4726b61f98d3adc64d60bbd6e41f59736e2b8ee335366"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ASYNC_WORK_GROUP_COPY<a id="a1142b2c02ac329c588bf4726b61f98d3a1bb97527c89bce10faa82649b70c7f9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ASYNC_WORK_GROUP_STRIDED_COPY<a id="a1142b2c02ac329c588bf4726b61f98d3ad00b1aac714f6144e111c18f92cab110"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATAN<a id="a1142b2c02ac329c588bf4726b61f98d3a03f7d754b99577d67a0cde1e78619e94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATAN2<a id="a1142b2c02ac329c588bf4726b61f98d3a260e663406aefa3afea43cb2263fcc83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATAN2PI<a id="a1142b2c02ac329c588bf4726b61f98d3ab4bbd1526f09d655eb3fb21de5eb65c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATANH<a id="a1142b2c02ac329c588bf4726b61f98d3a52a876775e5291c599191a9071f11833"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATANPI<a id="a1142b2c02ac329c588bf4726b61f98d3a7cbdaddf2fff263ffb500fa546dccdeb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_ADD<a id="a1142b2c02ac329c588bf4726b61f98d3a2652e880bf3d1683cc5d87b80b8f5fce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_AND<a id="a1142b2c02ac329c588bf4726b61f98d3a9603a43e89d7c68c5a093041e0301bee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_CMPXCHG<a id="a1142b2c02ac329c588bf4726b61f98d3ace4420be119b5efc18e1cb3bf5be4594"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_DEC<a id="a1142b2c02ac329c588bf4726b61f98d3aae3098860d35468ce01549c81b67bbee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_INC<a id="a1142b2c02ac329c588bf4726b61f98d3affe556b16bab73da7da1bfbc3a23e37b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_MAX<a id="a1142b2c02ac329c588bf4726b61f98d3a1d52a795f41fa944ab8676b5414d9457"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_MIN<a id="a1142b2c02ac329c588bf4726b61f98d3a18b7aaa1b4e066950bc3ac346613ce5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_OR<a id="a1142b2c02ac329c588bf4726b61f98d3af08faa62fc1276f7309418a9c654d4da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_SUB<a id="a1142b2c02ac329c588bf4726b61f98d3a542820f4bbbcef8c15808870e2f03a2c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_XCHG<a id="a1142b2c02ac329c588bf4726b61f98d3a57185e9ba1715fba3e921f4c673b3844"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ATOMIC_XOR<a id="a1142b2c02ac329c588bf4726b61f98d3a64781a92dabf2e59aab57b3820d10732"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_BITSELECT<a id="a1142b2c02ac329c588bf4726b61f98d3a39cba2666b267a49d3fcc756d96e78b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_CBRT<a id="a1142b2c02ac329c588bf4726b61f98d3a2015aaaf552cf3eecd11ae9803cde39d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_CEIL<a id="a1142b2c02ac329c588bf4726b61f98d3a0cd4c1b138d87489a1a582464de79251"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_CLAMP<a id="a1142b2c02ac329c588bf4726b61f98d3ab6b8dcfa448aab3db8080efc69dd02c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_CLZ<a id="a1142b2c02ac329c588bf4726b61f98d3a6d2ad56c0cb27cce095702b365a10be5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_COMMIT_READ_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3a91795349ee9a23bb6c9b333db6aa0175"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_COMMIT_WRITE_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3a0975f80a3125ef1f36ad7af47c96e277"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_COPYSIGN<a id="a1142b2c02ac329c588bf4726b61f98d3acf381ecf66f7217601c09feea36d6ed0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_COS<a id="a1142b2c02ac329c588bf4726b61f98d3adb71933f23940e062fc5a3eac31ccc11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_COSH<a id="a1142b2c02ac329c588bf4726b61f98d3ab42c3fd0368ecc3c9cf55f26d4d12855"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_COSPI<a id="a1142b2c02ac329c588bf4726b61f98d3a2c50d065aea9e2b8f146693bac7c26f7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_CROSS<a id="a1142b2c02ac329c588bf4726b61f98d3aa3a70b428b8ea31b7596ead856169da1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_CTZ<a id="a1142b2c02ac329c588bf4726b61f98d3a8672163b480483c13375a630d5336030"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_DEGREES<a id="a1142b2c02ac329c588bf4726b61f98d3a486e33c7b8c1cbd774b2b6c1dd4f8a9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_DISTANCE<a id="a1142b2c02ac329c588bf4726b61f98d3a3386d7b6d25be5e4a62a8a0d7a6a7e8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_DIVIDE<a id="a1142b2c02ac329c588bf4726b61f98d3ab5b311e12c491b514bb13be4a1fb4f7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_DOT<a id="a1142b2c02ac329c588bf4726b61f98d3ac0a55d46415906a49bb6a3eadb5895a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ERF<a id="a1142b2c02ac329c588bf4726b61f98d3a795f914e82976318f0fa415cd4859b0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ERFC<a id="a1142b2c02ac329c588bf4726b61f98d3a4494538ca2bb859cdb080fd90950dd3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_EXP<a id="a1142b2c02ac329c588bf4726b61f98d3a2e987433a67ea17eda081f27ecd098db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_EXP10<a id="a1142b2c02ac329c588bf4726b61f98d3acd876b65a7e15700fead4d4ba2426774"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_EXP2<a id="a1142b2c02ac329c588bf4726b61f98d3a49bd67da9ac6801dcfaa8ef97e2960d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_EXPM1<a id="a1142b2c02ac329c588bf4726b61f98d3addf1df6d45e3cb09c8e07b424c7d285c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FABS<a id="a1142b2c02ac329c588bf4726b61f98d3aa96a2dd6e72dc1ca41d42d6c44846723"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FAST_DISTANCE<a id="a1142b2c02ac329c588bf4726b61f98d3a0f326481b15b6f59d9538649fd24468b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FAST_LENGTH<a id="a1142b2c02ac329c588bf4726b61f98d3ac50eb59b151c5eb3b1114d8c89408e7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FAST_NORMALIZE<a id="a1142b2c02ac329c588bf4726b61f98d3a8d2b3a53dfeb4462af28769c106b4b10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FDIM<a id="a1142b2c02ac329c588bf4726b61f98d3a02ea2ace6a86c9967e2271d51e4a29c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FLOOR<a id="a1142b2c02ac329c588bf4726b61f98d3a058384d09ec72e7b4581eabcf6934000"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FMA<a id="a1142b2c02ac329c588bf4726b61f98d3a48fbb1e41e5234f2cb1635c540aed4c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FMAX<a id="a1142b2c02ac329c588bf4726b61f98d3a94a21632abaf14faf328a76f55125914"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FMIN<a id="a1142b2c02ac329c588bf4726b61f98d3a8491579b710e291a7d09e6a9f7c70ca0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FMOD<a id="a1142b2c02ac329c588bf4726b61f98d3a28521ea242723614bf2faa8f0654e827"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FRACT<a id="a1142b2c02ac329c588bf4726b61f98d3a4e680866ee3808aa4d8530a800116905"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FREXP<a id="a1142b2c02ac329c588bf4726b61f98d3ae5ca4d112c3e17041fcab99ec924554f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_GET_IMAGE_ARRAY_SIZE<a id="a1142b2c02ac329c588bf4726b61f98d3a5109dbc04b4726022cfaf49b663eed04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_GET_IMAGE_CHANNEL_DATA_TYPE<a id="a1142b2c02ac329c588bf4726b61f98d3af6bc065823cb9ef66b5026826e63cf3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_GET_IMAGE_CHANNEL_ORDER<a id="a1142b2c02ac329c588bf4726b61f98d3ad7d08ca9e79a65e6b7fb384a8c3c546d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_GET_IMAGE_DIM<a id="a1142b2c02ac329c588bf4726b61f98d3a3b2741bf664009a15f875a77e7e34e04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_GET_IMAGE_HEIGHT<a id="a1142b2c02ac329c588bf4726b61f98d3a10a8fcd306e7abb9fbcf229a810d49f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_GET_IMAGE_WIDTH<a id="a1142b2c02ac329c588bf4726b61f98d3ae0bf225eb859c81533e4afc41660d0e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_GET_PIPE_MAX_PACKETS<a id="a1142b2c02ac329c588bf4726b61f98d3aaec97421426d7a321de9a565fdb4d6fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_GET_PIPE_NUM_PACKETS<a id="a1142b2c02ac329c588bf4726b61f98d3aa5d17633bc53bd67ca31c88b61519dc3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_HADD<a id="a1142b2c02ac329c588bf4726b61f98d3ab9567e2b74afb7cca311747bd5fb17d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_HYPOT<a id="a1142b2c02ac329c588bf4726b61f98d3a951329199a8017ffcd2539e3f528c9c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ILOGB<a id="a1142b2c02ac329c588bf4726b61f98d3a00563f462e432bf616b18d9af25be13c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISEQUAL<a id="a1142b2c02ac329c588bf4726b61f98d3a9f1c08395873e4721825401f8093752f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISFINITE<a id="a1142b2c02ac329c588bf4726b61f98d3ad1c5e4e6680f878d1b8e137b37fb33bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISGREATER<a id="a1142b2c02ac329c588bf4726b61f98d3ab95a27c0af542d832e1ab8853329cdab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISGREATEREQUAL<a id="a1142b2c02ac329c588bf4726b61f98d3a1a001d7239e616fcdaee3f1cd82aaab0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISINF<a id="a1142b2c02ac329c588bf4726b61f98d3a8a163b32ab0a4ff1410487455f858785"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISLESS<a id="a1142b2c02ac329c588bf4726b61f98d3a9b9ebde30296401eb9ae2c8f0d1a2911"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISLESSEQUAL<a id="a1142b2c02ac329c588bf4726b61f98d3ae1018f06257a5c02320e3dc9c2954c2d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISLESSGREATER<a id="a1142b2c02ac329c588bf4726b61f98d3a0bdcfc690ede0276eab9515998c2601e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISNAN<a id="a1142b2c02ac329c588bf4726b61f98d3ad73ea8002cfde25b20c98671a454b9e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISNORMAL<a id="a1142b2c02ac329c588bf4726b61f98d3a0c3901bd3987ff89e148049df0f71030"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISNOTEQUAL<a id="a1142b2c02ac329c588bf4726b61f98d3a565440773590bfc0c1dbb09913dde7bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISORDERED<a id="a1142b2c02ac329c588bf4726b61f98d3a705aad8cd3a322d4014f651585174d06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ISUNORDERED<a id="a1142b2c02ac329c588bf4726b61f98d3af314a79c38b1e4ab160c43ccee63e557"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LDEXP<a id="a1142b2c02ac329c588bf4726b61f98d3a0eafdc097e558d07f2185458cea061c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LENGTH<a id="a1142b2c02ac329c588bf4726b61f98d3ae6af2d9a030ed244c83ad46714ae5981"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LGAMMA<a id="a1142b2c02ac329c588bf4726b61f98d3a0a2d10a8a356ef12f25a15f9896babe0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LGAMMA_R<a id="a1142b2c02ac329c588bf4726b61f98d3a38369d9c399ad6b61649e78221298a4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LOG<a id="a1142b2c02ac329c588bf4726b61f98d3ab5e69549fb42b96e18a69c438e1f9761"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LOG10<a id="a1142b2c02ac329c588bf4726b61f98d3a52a423fd81e8bb4925add23cb778498c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LOG1P<a id="a1142b2c02ac329c588bf4726b61f98d3aec907c04df6d89d33b292019eeb5d085"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LOG2<a id="a1142b2c02ac329c588bf4726b61f98d3afe8ecaad2f1178bc0a4f3e3ca266ec6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LOGB<a id="a1142b2c02ac329c588bf4726b61f98d3a07b8ba6855c41ed8da586fb40140e40b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MAD<a id="a1142b2c02ac329c588bf4726b61f98d3a8483b653f23fe91a91f1dc14f41724d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MAD24<a id="a1142b2c02ac329c588bf4726b61f98d3aa78c79ab633e90fdeed7365480989531"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MAD_HI<a id="a1142b2c02ac329c588bf4726b61f98d3aafbdf269e1bdf2833c34ed0e80695293"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MAD_SAT<a id="a1142b2c02ac329c588bf4726b61f98d3a9d3f728991906aca794e16ae8d984b27"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MAX<a id="a1142b2c02ac329c588bf4726b61f98d3a71481063650f90a090561f94815988d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MAXMAG<a id="a1142b2c02ac329c588bf4726b61f98d3a4fcedd1dbbc49c9690634cce89676ec2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MIN<a id="a1142b2c02ac329c588bf4726b61f98d3a0f71ec8e7d0f99866b2e8e55ed3ff7dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MINMAG<a id="a1142b2c02ac329c588bf4726b61f98d3a632adb855f0c2aa08dd7dcfa7f7cc771"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MIX<a id="a1142b2c02ac329c588bf4726b61f98d3aa7e9e1ad605250bb8ecb5f8fc66fb056"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MODF<a id="a1142b2c02ac329c588bf4726b61f98d3a23fdfbbda6f7f0d897ed48e54a53eb0e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MUL24<a id="a1142b2c02ac329c588bf4726b61f98d3acfa0a19a43a693efc00281926d72c4dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_MUL_HI<a id="a1142b2c02ac329c588bf4726b61f98d3a2abf7ca0ab867b1469ac706313737b3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NAN<a id="a1142b2c02ac329c588bf4726b61f98d3a82d60fe7ebecdbecde5ad6fa210b9887"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NEXTAFTER<a id="a1142b2c02ac329c588bf4726b61f98d3ae31e94fb235535c37873903f3e07d1fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NORMALIZE<a id="a1142b2c02ac329c588bf4726b61f98d3aecbfb0f58ce3d452576cce583c9c4f6b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_POPCOUNT<a id="a1142b2c02ac329c588bf4726b61f98d3a29531670bf7ad7436853a05467773243"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_POW<a id="a1142b2c02ac329c588bf4726b61f98d3af5e703d690b2fc7009da2e7ea28b038e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_POWN<a id="a1142b2c02ac329c588bf4726b61f98d3a3d6c3f390e6c5e88b199ad76ab6927f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_POWR<a id="a1142b2c02ac329c588bf4726b61f98d3a890b3d788fc247f94186955daaedaa12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_PREFETCH<a id="a1142b2c02ac329c588bf4726b61f98d3a999420877ca321a10664b1a756ec5d3f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_RADIANS<a id="a1142b2c02ac329c588bf4726b61f98d3aade76ebea0de5a0b60573a1902864ad8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_RECIP<a id="a1142b2c02ac329c588bf4726b61f98d3af47c7744369abb31a2f95599e6d32164"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_REMAINDER<a id="a1142b2c02ac329c588bf4726b61f98d3a766dbd668dbb53bcf36f0011d4413d5a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_REMQUO<a id="a1142b2c02ac329c588bf4726b61f98d3a15e462a64838f51727034ac3834063ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_RESERVE_READ_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3ab23db55ec20402bb06bcb00aa2f735c3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_RESERVE_WRITE_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3abc41a03ed9b0cc1d550dfd3d7d41dd8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_RHADD<a id="a1142b2c02ac329c588bf4726b61f98d3a3c0e2e43b7b7fcd06463d58d1a1e9e6b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_RINT<a id="a1142b2c02ac329c588bf4726b61f98d3abbfa421d45576bfd76fdee8b028c1794"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ROOTN<a id="a1142b2c02ac329c588bf4726b61f98d3a9d833f07a7a25855cf524a3dd54556fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ROTATE<a id="a1142b2c02ac329c588bf4726b61f98d3a6460b13f74bbf957e1d6887531b88ec8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_ROUND<a id="a1142b2c02ac329c588bf4726b61f98d3a8416fd02482dc92eb84c2c38eee70db7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_RSQRT<a id="a1142b2c02ac329c588bf4726b61f98d3a443810632d10d7cbc053cca01af12d4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SELECT<a id="a1142b2c02ac329c588bf4726b61f98d3aa19d0c0c8e8132861e0fb1327e4d634a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SHUFFLE<a id="a1142b2c02ac329c588bf4726b61f98d3a58ba4a871af0ce54a96355846c9b89dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SHUFFLE2<a id="a1142b2c02ac329c588bf4726b61f98d3a580af14adc5833f18a13737e53fe4c7a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SIGN<a id="a1142b2c02ac329c588bf4726b61f98d3aaa858370cfcde097e8b503779ae15a12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SIGNBIT<a id="a1142b2c02ac329c588bf4726b61f98d3a5cfcc762721f4c19f823a2371be4c480"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SIN<a id="a1142b2c02ac329c588bf4726b61f98d3a9de3a011a924c901cd12142bf48a83ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SINCOS<a id="a1142b2c02ac329c588bf4726b61f98d3a19916d6858eb73c5cafdadb79ebde8ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SINH<a id="a1142b2c02ac329c588bf4726b61f98d3ab4b8bd994713d2024deb5d2a85d48464"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SINPI<a id="a1142b2c02ac329c588bf4726b61f98d3a8033a316d573e66e8a89ec903fa4b64b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SMOOTHSTEP<a id="a1142b2c02ac329c588bf4726b61f98d3a7fd27e03cfda0995e0f69b9783d3861b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SQRT<a id="a1142b2c02ac329c588bf4726b61f98d3a2d19318cd15f1d0bc987640a6545419a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_STEP<a id="a1142b2c02ac329c588bf4726b61f98d3a804f416bbcb529b8a8cb48d7dbab8ca9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_BROADCAST<a id="a1142b2c02ac329c588bf4726b61f98d3a088ef90736bab399a90168d14e1d1c0b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_COMMIT_READ_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3a131b7c2ad2524947e0d229e6cd668b0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_COMMIT_WRITE_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3a654c4b205bce196da7a1d4eadedade6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_REDUCE_ADD<a id="a1142b2c02ac329c588bf4726b61f98d3a28b2396b9f5207d322efe9addc0e4e91"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_REDUCE_MAX<a id="a1142b2c02ac329c588bf4726b61f98d3aeb0449ae4bc1335e77af291a75ca1bd4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_REDUCE_MIN<a id="a1142b2c02ac329c588bf4726b61f98d3ae1eb088da82f796a36dce0cee4cfb45a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_RESERVE_READ_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3ab8afb648c8834c556180ad610fae1854"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_RESERVE_WRITE_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3a4a957fd5c4a0ccb4fb4b7ae3371a686f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_SCAN_EXCLUSIVE_ADD<a id="a1142b2c02ac329c588bf4726b61f98d3a6727bc9582c4bb40311f090ffecce538"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_SCAN_EXCLUSIVE_MAX<a id="a1142b2c02ac329c588bf4726b61f98d3a3c42b82d7e620a88c508c8252d702bee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_SCAN_EXCLUSIVE_MIN<a id="a1142b2c02ac329c588bf4726b61f98d3a0e321bfd9358497a708c5f1771681cc9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_SCAN_INCLUSIVE_ADD<a id="a1142b2c02ac329c588bf4726b61f98d3a7636c2beb7ca5f345bed73afcc370cf2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_SCAN_INCLUSIVE_MAX<a id="a1142b2c02ac329c588bf4726b61f98d3a2e5f021ad052efc742bf01247c7b2f51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_GROUP_SCAN_INCLUSIVE_MIN<a id="a1142b2c02ac329c588bf4726b61f98d3a36195699d76ce466eb5d889c04f2e2ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_SUB_SAT<a id="a1142b2c02ac329c588bf4726b61f98d3a0ece14273d81c17e3df3b054c2496197"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_TAN<a id="a1142b2c02ac329c588bf4726b61f98d3aa3b8c714bac2150cd9742ec5dbc5f936"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_TANH<a id="a1142b2c02ac329c588bf4726b61f98d3ad2329b67e476dad41b495394d26fa26e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_TANPI<a id="a1142b2c02ac329c588bf4726b61f98d3a6d2eb151d08967da6807ca2f791aa282"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_TGAMMA<a id="a1142b2c02ac329c588bf4726b61f98d3a60e82d51f89b268d4a061d66ad0212a1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_TRUNC<a id="a1142b2c02ac329c588bf4726b61f98d3a6a6b5da17a2e439c886a2f085ae972e9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_UPSAMPLE<a id="a1142b2c02ac329c588bf4726b61f98d3a69d15d8ad79ba515902ac59ecf084e85"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_VEC_STEP<a id="a1142b2c02ac329c588bf4726b61f98d3a410014f36118a157682a000eb9f4e6ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_VSTORE<a id="a1142b2c02ac329c588bf4726b61f98d3adece06ee4b293c04f2c21fe864f03c42"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_VSTORE16<a id="a1142b2c02ac329c588bf4726b61f98d3a2b936da79bc43bae6a3858910785761b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_VSTORE2<a id="a1142b2c02ac329c588bf4726b61f98d3a1828240c44a624b1b1f8df4dfaa56b67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_VSTORE3<a id="a1142b2c02ac329c588bf4726b61f98d3a73461835bc2c6bdae1dfe5c0bc765529"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_VSTORE4<a id="a1142b2c02ac329c588bf4726b61f98d3a7bdddaaeffc9f87d826a6ad06d41dc28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_VSTORE8<a id="a1142b2c02ac329c588bf4726b61f98d3a40d0af1e3cb648aafcd9075db892cf16"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_COMMIT_READ_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3aa4a7533d7a765d2e01e57bb0924e6e67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_COMMIT_WRITE_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3a27a50b68689dfafe398709e29fded557"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_REDUCE_ADD<a id="a1142b2c02ac329c588bf4726b61f98d3ae6b57b0494dafa75702be0d738a7528e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_REDUCE_MAX<a id="a1142b2c02ac329c588bf4726b61f98d3a53e0e6d7af38b5a55cd66a4914199c3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_REDUCE_MIN<a id="a1142b2c02ac329c588bf4726b61f98d3a864f8314f9d2ed06e6f4a04c2d122bc6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_RESERVE_READ_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3a51d5f1f755aa715af02dbf4ded504054"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_RESERVE_WRITE_PIPE<a id="a1142b2c02ac329c588bf4726b61f98d3a70ef738653a80727e964bc95c8ad3e07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_SCAN_EXCLUSIVE_ADD<a id="a1142b2c02ac329c588bf4726b61f98d3a5df9c3e0042490e2c22e12a856da4f64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_SCAN_EXCLUSIVE_MAX<a id="a1142b2c02ac329c588bf4726b61f98d3a7df11c674f758989f82719b63cb6d47c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_SCAN_EXCLUSIVE_MIN<a id="a1142b2c02ac329c588bf4726b61f98d3a02c97c6892371e01aec9e9ff2851fe4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_SCAN_INCLUSIVE_ADD<a id="a1142b2c02ac329c588bf4726b61f98d3a81524fd41059e492c994a3f6bf95ab78"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_SCAN_INCLUSIVE_MAX<a id="a1142b2c02ac329c588bf4726b61f98d3a6ecc8d29c35673f4ec9072d07f956036"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WORK_GROUP_SCAN_INCLUSIVE_MIN<a id="a1142b2c02ac329c588bf4726b61f98d3af84d70b973f1076dc6853de327b3fadb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WRITE_IMAGEF<a id="a1142b2c02ac329c588bf4726b61f98d3ac74fb18d0e09c764ec511d392a0e9e4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WRITE_IMAGEI<a id="a1142b2c02ac329c588bf4726b61f98d3aab372d1336e9c75025a35239a0c2fddb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WRITE_IMAGEUI<a id="a1142b2c02ac329c588bf4726b61f98d3aa78240a6190c3483fe846f36d8940766"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NCOS<a id="a1142b2c02ac329c588bf4726b61f98d3a4882dda175b9e6246d5212c9a5cddb0c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NEXP2<a id="a1142b2c02ac329c588bf4726b61f98d3a3e74573d665d2957769a7dd21d628978"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NFMA<a id="a1142b2c02ac329c588bf4726b61f98d3a348e881ada104c587ace561313f607f0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NLOG2<a id="a1142b2c02ac329c588bf4726b61f98d3ae0db9cb46ec4b65a52ad9dee0f16f926"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NRCP<a id="a1142b2c02ac329c588bf4726b61f98d3a91883d7f941fd5ed3c79502a7f8c5ad7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NRSQRT<a id="a1142b2c02ac329c588bf4726b61f98d3a6cdd0cf8a4be6b68e54e0399bf6fa7d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NSIN<a id="a1142b2c02ac329c588bf4726b61f98d3a9c4c88a3c8b3c4f502153a61ddd736c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_NSQRT<a id="a1142b2c02ac329c588bf4726b61f98d3ac711cdac2769081a1445b8025ddef68a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FTZ<a id="a1142b2c02ac329c588bf4726b61f98d3ab929370e7f1df17d3e80e7c9d582db09"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_FLDEXP<a id="a1142b2c02ac329c588bf4726b61f98d3a9f1427928407ee8c10d6599c3bfe996f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_CLASS<a id="a1142b2c02ac329c588bf4726b61f98d3afbb6e56ec1b1d348c07f23ecd6bb08a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_RCBRT<a id="a1142b2c02ac329c588bf4726b61f98d3a51daa7d6fe35270f50f34603d4de7ac7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_LAST_MANGLED<a id="a1142b2c02ac329c588bf4726b61f98d3a37885ffcd6337778d814ef3672e63978"></a></td>
<td class="doxyEnumItemDescription">
 (=
        EI_RCBRT)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_READ_PIPE_2<a id="a1142b2c02ac329c588bf4726b61f98d3a857a85237617df4bef89cc3b681ed391"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_READ_PIPE_4<a id="a1142b2c02ac329c588bf4726b61f98d3a2dd4b1948ce322d57d3fd12bd7234abd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WRITE_PIPE_2<a id="a1142b2c02ac329c588bf4726b61f98d3af981794446493eb20f572fc644af8a35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EI_WRITE_PIPE_4<a id="a1142b2c02ac329c588bf4726b61f98d3a16dcaa516691259b2ebf9aec3f010cda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EX_INTRINSICS_COUNT<a id="a1142b2c02ac329c588bf4726b61f98d3a7c30473a35904cb3be025e8074eb9298"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### ENamePrefix {#a5f1a1a785d3bea7522fda8651035c2f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPULibFuncBase::ENamePrefix </td>
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
<td class="doxyEnumItemName">NOPFX<a id="a5f1a1a785d3bea7522fda8651035c2f6a4e02cec40ee27126cc5262e46bd59e03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NATIVE<a id="a5f1a1a785d3bea7522fda8651035c2f6a1df3c3e4573abf56929068a57e3f4963"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HALF<a id="a5f1a1a785d3bea7522fda8651035c2f6ae221e1fe973e968bf19ac90f0cafa3a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### EPtrKind {#aac00986b9c47fed034287e1eeb01a141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPULibFuncBase::EPtrKind </td>
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
<td class="doxyEnumItemName">BYVALUE<a id="aac00986b9c47fed034287e1eeb01a141ace38fa4a412a5fe40cde9a544b2e64f3"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ADDR_SPACE<a id="aac00986b9c47fed034287e1eeb01a141ab7955061b9da9115dc37f1baf7f3cbca"></a></td>
<td class="doxyEnumItemDescription"> (= 0xF)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONST<a id="aac00986b9c47fed034287e1eeb01a141ab71327ef08041a654a35def14111691c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOLATILE<a id="aac00986b9c47fed034287e1eeb01a141a6987d7ee902a05bb1ede8f10f5956ba7"></a></td>
<td class="doxyEnumItemDescription"> (= 0x20)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

### EType {#a858436a6ac3e32480363df7ec66765a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPULibFuncBase::EType </td>
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
<td class="doxyEnumItemName">B8<a id="a858436a6ac3e32480363df7ec66765a8aef7f289d40cba38e952183b488e6745d"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">B16<a id="a858436a6ac3e32480363df7ec66765a8a530383443ddee974289016216d02d38e"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">B32<a id="a858436a6ac3e32480363df7ec66765a8a27954da45df36722e84d4d7920c160a4"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">B64<a id="a858436a6ac3e32480363df7ec66765a8a8c7290400f7627e11246a1787a9b6a69"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIZE_MASK<a id="a858436a6ac3e32480363df7ec66765a8a2830c9fe1a1e162ab0ef8053d6917a7a"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLOAT<a id="a858436a6ac3e32480363df7ec66765a8ab7c0bdf13a234a4771f7580b16fb617f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INT<a id="a858436a6ac3e32480363df7ec66765a8a5e762edbd94c2c234a799ba2954e5845"></a></td>
<td class="doxyEnumItemDescription"> (= 0x20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UINT<a id="a858436a6ac3e32480363df7ec66765a8aa58407df436b853385d7db02b81a8a22"></a></td>
<td class="doxyEnumItemDescription"> (= 0x30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BASE_TYPE_MASK<a id="a858436a6ac3e32480363df7ec66765a8a6a24c0a92d2c2714fbb15f99c0e69202"></a></td>
<td class="doxyEnumItemDescription"> (= 0x30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">U8<a id="a858436a6ac3e32480363df7ec66765a8ae8baa7f9c7af35b4306f6d225214404e"></a></td>
<td class="doxyEnumItemDescription"> (=  UINT | B8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">U16<a id="a858436a6ac3e32480363df7ec66765a8a76424308db519548eaeda3655a288bc4"></a></td>
<td class="doxyEnumItemDescription"> (=  UINT | B16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">U32<a id="a858436a6ac3e32480363df7ec66765a8a3e402cd027c568fa43f4b554c0b348b6"></a></td>
<td class="doxyEnumItemDescription"> (=  UINT | B32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">U64<a id="a858436a6ac3e32480363df7ec66765a8a8c6c6342eca81ee6609a590cdc4fcad6"></a></td>
<td class="doxyEnumItemDescription"> (=  UINT | B64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I8<a id="a858436a6ac3e32480363df7ec66765a8ad0af55ef4d18b5452d50afa947f2f150"></a></td>
<td class="doxyEnumItemDescription"> (=   INT | B8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I16<a id="a858436a6ac3e32480363df7ec66765a8a3a5514459881fc9d2444d6ac8a18a8c2"></a></td>
<td class="doxyEnumItemDescription"> (=   INT | B16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I32<a id="a858436a6ac3e32480363df7ec66765a8a8039c0339aea621d2589419bc0c7ffdf"></a></td>
<td class="doxyEnumItemDescription"> (=   INT | B32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I64<a id="a858436a6ac3e32480363df7ec66765a8aaeb097d554a6e77e61dd1dc797ea062f"></a></td>
<td class="doxyEnumItemDescription"> (=   INT | B64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F16<a id="a858436a6ac3e32480363df7ec66765a8af91b4c3fb5deff779fa5884c0d521278"></a></td>
<td class="doxyEnumItemDescription"> (= FLOAT | B16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F32<a id="a858436a6ac3e32480363df7ec66765a8af5e427970dc9c29ec50cb3f39fbcf774"></a></td>
<td class="doxyEnumItemDescription"> (= FLOAT | B32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">F64<a id="a858436a6ac3e32480363df7ec66765a8a06c2414f8276b0025f4057efce9bc562"></a></td>
<td class="doxyEnumItemDescription"> (= FLOAT | B64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMG1DA<a id="a858436a6ac3e32480363df7ec66765a8aa4a0749682012c0c912a6c67faac089f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMG1DB<a id="a858436a6ac3e32480363df7ec66765a8acdc53f4dbf399c54a795dcd836b085b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMG2DA<a id="a858436a6ac3e32480363df7ec66765a8acbd1cf99158a98160aeba7a1e350ed80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMG1D<a id="a858436a6ac3e32480363df7ec66765a8a2d2bd20792beb08e2871525ff0bd61bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMG2D<a id="a858436a6ac3e32480363df7ec66765a8a678e88a9aa9bd4cecb5a9a75f11e0b2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMG3D<a id="a858436a6ac3e32480363df7ec66765a8ad6ca04175915d03dee3f3d3d2669dfd7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SAMPLER<a id="a858436a6ac3e32480363df7ec66765a8aea0f57e5792d27177089744d2d67949c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVENT<a id="a858436a6ac3e32480363df7ec66765a8a3b58a8396e18962b04903105bb925fb4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DUMMY<a id="a858436a6ac3e32480363df7ec66765a8a3bcd722d2d045ca33574c1cd0a1ea34d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getAddrSpaceFromEPtrKind() {#a2e2417eedd4fbca37cf773d44a0642d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPULibFuncBase::getAddrSpaceFromEPtrKind (unsigned Kind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>References <a href="#aac00986b9c47fed034287e1eeb01a141ab7955061b9da9115dc37f1baf7f3cbca">ADDR_SPACE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulibfunc-cpp-/paramiterator/#af8ab60a12af8b68f2c479b9872e5c0b8">anonymous{AMDGPULibFunc.cpp}::ParamIterator::getNextParam</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulibfunc-cpp-/itaniummangler/#a015004ddb6e6b4aa985ffe6d5663ff83">anonymous{AMDGPULibFunc.cpp}::ItaniumMangler::operator()</a>.</p>

</div>
</div>

### getEPtrKindFromAddrSpace() {#a234ff52a2593b9d0f6fbd4d8aee25d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPULibFuncBase::getEPtrKindFromAddrSpace (unsigned AS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>References <a href="#aac00986b9c47fed034287e1eeb01a141ab7955061b9da9115dc37f1baf7f3cbca">ADDR_SPACE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulibfunc-cpp-/paramiterator/#af8ab60a12af8b68f2c479b9872e5c0b8">anonymous{AMDGPULibFunc.cpp}::ParamIterator::getNextParam</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>.</p>

</div>
</div>

### isMangled() {#a656ff82f4700daf658142eef8eb184d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPULibFuncBase::isMangled (<a href="#a1142b2c02ac329c588bf4726b61f98d3">EFuncId</a> Id)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a>.</p>


<p>Reference <a href="#a1142b2c02ac329c588bf4726b61f98d3a37885ffcd6337778d814ef3672e63978">EI_LAST_MANGLED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#aa1895a9c2001bdc178ac4c191ccabc14">llvm::AMDGPULibFunc::AMDGPULibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a8e662f55e8be621fac1827a2032c217a">llvm::AMDGPULibFunc::isCompatibleSignature</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncimpl/#aeaa8c9c63acfecd412c590d7142a634f">llvm::AMDGPULibFuncImpl::isMangled</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-h">AMDGPULibFunc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
