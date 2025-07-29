---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `VECustomDAG.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>"
#include "VVPNodes.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"vecustomdag"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VPOPC, VVPNAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac863858a645eeec582c2f95d63a9fcd8">ADD_UNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1529008942f2b1735c60fd1e8e3f52af">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d27632f59ff51b5d3cdb5c59b874ef">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7706f10a95325784fcd458e2121fe08d">REGISTER_PACKED</a>(OPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad971395655d465cf3ed4946c0d9f967e">HELPER_REDUCTION</a>(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b43e5f1f6fe3614f5954c11ba07c344">REGISTER_PACKED</a>(VVP_NAME)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6b13aaba52fe6c4c62bdd8e732c252">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637bb05d351f87c34c012f587b257827">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a1e6572cb4b95fd99696be7e3ce61a9">ADD_UNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb564f0f8c0ac7abdecc228ccc7c681">ADD_BINARY_VVP_OP</a>(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa75a808e5ac0262706fe09c1d85fbda2">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4828a2ca7c564b5ec296b54f47a9e0d">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d4fa96192752b68861131612aa102d">ADD_REDUCE_VVP_OP</a>(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad57eb259779ffb46aef55598b7056db0">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa241cb60272c3e50fd3ab73b3eed9a65">HELPER_REDUCTION</a>(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab874d480b73f5c4a2b601917bcadb736">ADD_VVP_OP</a>(VVPNAME, ...)&nbsp;&nbsp;&nbsp;case VEISD::VVPNAME:</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d1ee223194030c05d3f094632cd67a">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade19593ab6fbe2acc77cc224c0121000">ADD_UNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8063759f52bcc19668fb6ad8371716be">ADD_BINARY_VVP_OP</a>(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d0431bf6568440849ba95088de7a2d">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e1cd0b2c6aa10c5b81592cb7c72ada0">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726a016769500326a36a0fa6ca353775">REGISTER_PACKED</a>(OPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5bbd81b7dea50b7d0c9ee97574f79d">ADD_REDUCE_VVP_OP</a>(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888312c48ad53a3549d180a09a3168b8">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5bfd2e78aff709eae836f12b619844a">HELPER_REDUCTION</a>(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ef19ebb682d19333b0b00a0d7ba8eb">ADD_UNARY_VVP_OP</a>(VVPNAME, ...)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0374a6149bc421c65da6b2c51c848a23">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a132d14a28ac9359b3f9fd7a098d02b5c">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa826ae910f0d1bb7c73c49119a6d2dab">ADD_BINARY_VVP_OP</a>(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9516f14fe7521af552384decbff1f9d4">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1dd2968e9bb1d1bd5a7805cd728599d">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30c09aba22157602c0c0234547031818">REGISTER_PACKED</a>(OPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c4a2e6b2b831145aaad21a178744a0">ADD_REDUCE_VVP_OP</a>(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9754342c1793f71b65ad4b3ddfe72179">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fdc19c8e1f3c12627923bac829da788">HELPER_REDUCTION</a>(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89fc220dac898349bf7088d2f41635d7">ADD_BINARY_VVP_OP</a>(VVPNAME, ...)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2693462f365b44bcd65c23e78527148b">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b38674c1771d40862d3edfae0b9a97">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeaef44a13194da6ae2cb3eafb90fd26">ADD_UNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dbfd4d48c16aa3261657bb317228dcb">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bac2f3229a3e7b411985bb0e1b2641b">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75056aa36af9884e05e0a69fd42b1727">REGISTER_PACKED</a>(OPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9068fa5ccd89f8db6bd1a25f7a8fb080">ADD_REDUCE_VVP_OP</a>(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ad79de202cac5c2855f171ac90d5db">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62ef229da43f53d3b7ebc419bb0009e">HELPER_REDUCTION</a>(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a612fc10c4a09cd9e7d17206da19a893d">ADD_REDUCE_VVP_OP</a>(VVP_NAME, SDNAME)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4ca7c884db512a1a5fda53c9b16fb4">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af29ac2b2ee484fbc810eea0e2418fc">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756f5c1a8a539a19927ec46db7bc965c">ADD_UNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f3e7a64e8ab6f1559a739e06441b81">ADD_BINARY_VVP_OP</a>(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0fa23ca383b59e9c645cf9e8d850079">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9533b723997f5bdc401a4d219cdbf7fe">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905d9b4139af2f501a6b929c92b90503">REGISTER_PACKED</a>(OPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d16c8dc602d49ff76e1d86cd41dac9">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40fd40c93a4f4771ae073dd56bdf09a">HELPER_REDUCTION</a>(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaf2653e465d4e44e7554a8f713fc360">ADD_BINARY_VVP_OP</a>(VVP_NAME, ...)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae625979988cb94731b8e058e4a620d5">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7bf6b5b9f4b0290eb578cb92119ebf8">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f093a31e3e094af7c0f5d5760bcbbf">ADD_UNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3388655214ee328446aca206a894c4ef">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11d98c371bc0e859358417d21f6cc1b">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a7d4c500d600fc7ab92c6196ce81b5">REGISTER_PACKED</a>(OPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67367a4f645672a1f29ca723f366a2ce">ADD_REDUCE_VVP_OP</a>(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac15ba5729a3e0670da5f38eb8f2ae141">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc8b13eae2ecc917b6f20694de24024">HELPER_REDUCTION</a>(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f01efa830d5f1c292deb6bc702c5dcd">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52e6c667860d8c754b5da04b862b2425">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d14cc6f68cb73574700146581bc6187">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a621d8365be2802e7083b2d269306d">ADD_UNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8836965bbf30d3e186e4be1eb0aa0bab">ADD_BINARY_VVP_OP</a>(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f94cec68c01b7a4e368f009a3f6ec7">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d32808bf3c23c8ec62612712dffb902">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8db5335ab9cd9b990c7486df4c6942">REGISTER_PACKED</a>(OPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f4fd34fc5fcd164b111220b9f95a24">ADD_REDUCE_VVP_OP</a>(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055e8dd6cf3e3b2e33a468292314e0ab">HELPER_REDUCTION</a>(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### ADD\_BINARY\_VVP\_OP {#a11b851f7dd6ad1ef2a2fea5686df1f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME) \
            <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VPNAME, VVPNAME)
</div>
</dd>
</dl>
</div>
</div>

### ADD\_BINARY\_VVP\_OP {#abeb564f0f8c0ac7abdecc228ccc7c681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME) \
            <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VPNAME, VVPNAME)
</div>
</dd>
</dl>
</div>
</div>

### ADD\_BINARY\_VVP\_OP {#a8063759f52bcc19668fb6ad8371716be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME) \
            <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VPNAME, VVPNAME)
</div>
</dd>
</dl>
</div>
</div>

### ADD\_BINARY\_VVP\_OP {#aa826ae910f0d1bb7c73c49119a6d2dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME) \
            <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VPNAME, VVPNAME)
</div>
</dd>
</dl>
</div>
</div>

### ADD\_BINARY\_VVP\_OP {#a89fc220dac898349bf7088d2f41635d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP(VVPNAME, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case VEISD::VVPNAME:                                                         \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### ADD\_BINARY\_VVP\_OP {#ac6f3e7a64e8ab6f1559a739e06441b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME) \
            <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VPNAME, VVPNAME)
</div>
</dd>
</dl>
</div>
</div>

### ADD\_BINARY\_VVP\_OP {#acaf2653e465d4e44e7554a8f713fc360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP(VVP_NAME, ...)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### ADD\_BINARY\_VVP\_OP {#a8836965bbf30d3e186e4be1eb0aa0bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP(VVPNAME, VPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME) \
            <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VPNAME, VVPNAME)
</div>
</dd>
</dl>
</div>
</div>

### ADD\_BINARY\_VVP\_OP\_COMPACT {#a61d27632f59ff51b5d3cdb5c59b874ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_BINARY\_VVP\_OP\_COMPACT {#aa4828a2ca7c564b5ec296b54f47a9e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_BINARY\_VVP\_OP\_COMPACT {#a9e1cd0b2c6aa10c5b81592cb7c72ada0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_BINARY\_VVP\_OP\_COMPACT {#ae1dd2968e9bb1d1bd5a7805cd728599d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_BINARY\_VVP\_OP\_COMPACT {#a2bac2f3229a3e7b411985bb0e1b2641b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_BINARY\_VVP\_OP\_COMPACT {#a9533b723997f5bdc401a4d219cdbf7fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_BINARY\_VVP\_OP\_COMPACT {#ad11d98c371bc0e859358417d21f6cc1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_BINARY\_VVP\_OP\_COMPACT {#a2d32808bf3c23c8ec62612712dffb902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_REDUCE\_VVP\_OP {#aa79de5ed521f396215dc856b99714381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_REDUCE\_VVP\_OP {#aa0d4fa96192752b68861131612aa102d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_REDUCE\_VVP\_OP {#a4e5bbd81b7dea50b7d0c9ee97574f79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_REDUCE\_VVP\_OP {#aa1c4a2e6b2b831145aaad21a178744a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_REDUCE\_VVP\_OP {#a9068fa5ccd89f8db6bd1a25f7a8fb080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_REDUCE\_VVP\_OP {#a612fc10c4a09cd9e7d17206da19a893d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(VVP_NAME, SDNAME)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### ADD\_REDUCE\_VVP\_OP {#a67367a4f645672a1f29ca723f366a2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_REDUCE\_VVP\_OP {#ac0f4fd34fc5fcd164b111220b9f95a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_TERNARY\_VVP\_OP {#a1529008942f2b1735c60fd1e8e3f52af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_TERNARY\_VVP\_OP {#aa75a808e5ac0262706fe09c1d85fbda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_TERNARY\_VVP\_OP {#a52d0431bf6568440849ba95088de7a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_TERNARY\_VVP\_OP {#a9516f14fe7521af552384decbff1f9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_TERNARY\_VVP\_OP {#a3dbfd4d48c16aa3261657bb317228dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_TERNARY\_VVP\_OP {#aa0fa23ca383b59e9c645cf9e8d850079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_TERNARY\_VVP\_OP {#a3388655214ee328446aca206a894c4ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_TERNARY\_VVP\_OP {#a45f94cec68c01b7a4e368f009a3f6ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_UNARY\_VVP\_OP {#ac863858a645eeec582c2f95d63a9fcd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_UNARY\_VVP\_OP {#a2a1e6572cb4b95fd99696be7e3ce61a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_UNARY\_VVP\_OP {#ade19593ab6fbe2acc77cc224c0121000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_UNARY\_VVP\_OP {#af9ef19ebb682d19333b0b00a0d7ba8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case VEISD::VVPNAME:                                                         \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;
</div>
</dd>
</dl>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### ADD\_UNARY\_VVP\_OP {#adeaef44a13194da6ae2cb3eafb90fd26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_UNARY\_VVP\_OP {#a756f5c1a8a539a19927ec46db7bc965c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_UNARY\_VVP\_OP {#a23f093a31e3e094af7c0f5d5760bcbbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_UNARY\_VVP\_OP {#a77a621d8365be2802e7083b2d269306d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_VVP\_OP {#a1ccd992516d11e6a3a3f1958be2dcaa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case VEISD::VVPNAME:                                                         \
  case ISD::SDNAME:                                                            \
    return VEISD::VVPNAME;
</div>
</dd>
</dl>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### ADD\_VVP\_OP {#a637bb05d351f87c34c012f587b257827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(X, Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_VVP\_OP {#ab874d480b73f5c4a2b601917bcadb736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(VVPNAME, ...)&nbsp;&nbsp;&nbsp;case VEISD::VVPNAME:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### ADD\_VVP\_OP {#a132d14a28ac9359b3f9fd7a098d02b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(X, Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_VVP\_OP {#a22b38674c1771d40862d3edfae0b9a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(X, Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_VVP\_OP {#a6af29ac2b2ee484fbc810eea0e2418fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(X, Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_VVP\_OP {#ae7bf6b5b9f4b0290eb578cb92119ebf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(X, Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### ADD\_VVP\_OP {#a4d14cc6f68cb73574700146581bc6187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(X, Y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"vecustomdag"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### HANDLE\_VP\_TO\_VVP {#a0abb17afdcc2b53ea41ddfd4f74f1784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VP_TO_VVP(VPOPC, VVPNAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case ISD::VPOPC:                                                             \
    return VEISD::VVPNAME;
</div>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### HANDLE\_VP\_TO\_VVP {#a5d6b13aaba52fe6c4c62bdd8e732c252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VP\_TO\_VVP {#ad7d1ee223194030c05d3f094632cd67a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VP\_TO\_VVP {#a0374a6149bc421c65da6b2c51c848a23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VP\_TO\_VVP {#a2693462f365b44bcd65c23e78527148b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VP\_TO\_VVP {#a6f4ca7c884db512a1a5fda53c9b16fb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VP\_TO\_VVP {#aae625979988cb94731b8e058e4a620d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VP\_TO\_VVP {#a52e6c667860d8c754b5da04b862b2425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#a1fd5c7a2346250a30165148b2e55bd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VVP_REDUCE_TO_SCALAR(VVP_RED_ISD, REDUCE_ISD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#ad57eb259779ffb46aef55598b7056db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VVP_REDUCE_TO_SCALAR(VVP_RED_ISD, REDUCE_ISD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#a888312c48ad53a3549d180a09a3168b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VVP_REDUCE_TO_SCALAR(VVP_RED_ISD, REDUCE_ISD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#a9754342c1793f71b65ad4b3ddfe72179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VVP_REDUCE_TO_SCALAR(VVP_RED_ISD, REDUCE_ISD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#a37ad79de202cac5c2855f171ac90d5db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VVP_REDUCE_TO_SCALAR(VVP_RED_ISD, REDUCE_ISD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#a88d16c8dc602d49ff76e1d86cd41dac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VVP_REDUCE_TO_SCALAR(VVP_RED_ISD, REDUCE_ISD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#ac15ba5729a3e0670da5f38eb8f2ae141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VVP_REDUCE_TO_SCALAR(VVP_RED_ISD, REDUCE_ISD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#a4f01efa830d5f1c292deb6bc702c5dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VVP_REDUCE_TO_SCALAR(VVP_RED_ISD, REDUCE_ISD)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case VEISD::VVP_RED_ISD:                                                     \
    return ISD::REDUCE_ISD;
</div>
</dd>
</dl>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### HELPER\_REDUCTION {#ad971395655d465cf3ed4946c0d9f967e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HELPER_REDUCTION(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
</div>
</dd>
</dl>
</div>
</div>

### HELPER\_REDUCTION {#aa241cb60272c3e50fd3ab73b3eed9a65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HELPER_REDUCTION(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
</div>
</dd>
</dl>
</div>
</div>

### HELPER\_REDUCTION {#ad5bfd2e78aff709eae836f12b619844a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HELPER_REDUCTION(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
</div>
</dd>
</dl>
</div>
</div>

### HELPER\_REDUCTION {#a8fdc19c8e1f3c12627923bac829da788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HELPER_REDUCTION(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
</div>
</dd>
</dl>
</div>
</div>

### HELPER\_REDUCTION {#ac62ef229da43f53d3b7ebc419bb0009e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HELPER_REDUCTION(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
</div>
</dd>
</dl>
</div>
</div>

### HELPER\_REDUCTION {#ad40fd40c93a4f4771ae073dd56bdf09a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HELPER_REDUCTION(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
</div>
</dd>
</dl>
</div>
</div>

### HELPER\_REDUCTION {#a1fc8b13eae2ecc917b6f20694de24024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HELPER_REDUCTION(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
</div>
</dd>
</dl>
</div>
</div>

### HELPER\_REDUCTION {#a055e8dd6cf3e3b2e33a468292314e0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HELPER_REDUCTION(OPC, SCALAR_OPC)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
</div>
</dd>
</dl>
</div>
</div>

### REGISTER\_PACKED {#a7706f10a95325784fcd458e2121fe08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGISTER_PACKED(OPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### REGISTER\_PACKED {#a9b43e5f1f6fe3614f5954c11ba07c344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGISTER_PACKED(VVP_NAME)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>

</div>
</div>

### REGISTER\_PACKED {#a726a016769500326a36a0fa6ca353775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGISTER_PACKED(OPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### REGISTER\_PACKED {#a30c09aba22157602c0c0234547031818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGISTER_PACKED(OPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### REGISTER\_PACKED {#a75056aa36af9884e05e0a69fd42b1727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGISTER_PACKED(OPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### REGISTER\_PACKED {#a905d9b4139af2f501a6b929c92b90503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGISTER_PACKED(OPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### REGISTER\_PACKED {#a80a7d4c500d600fc7ab92c6196ce81b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGISTER_PACKED(OPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

### REGISTER\_PACKED {#a0c8db5335ab9cd9b990c7486df4c6942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGISTER_PACKED(OPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
