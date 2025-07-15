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

# The `VECustomDAG.cpp` File Reference



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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772765ed3ceb45636107234f9ef229f5">REGISTER_PACKED</a>(VVP_NAME)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb57a51f610c67c0c2843e28b7c25dce">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177cec26f7d7c7a0375b54cf69ed1c0d">ADD_VVP_OP</a>(VVPNAME, ...)&nbsp;&nbsp;&nbsp;case VEISD::VVPNAME:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac405bfe9b55c2e75a8ef8538a8f23a30">ADD_UNARY_VVP_OP</a>(VVPNAME, ...)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb57a51f610c67c0c2843e28b7c25dce">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b12943e0b1a8a2d88cdebb5306452e8">ADD_BINARY_VVP_OP</a>(VVPNAME, ...)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb57a51f610c67c0c2843e28b7c25dce">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce9948e4f34616ee8f2d15b5311efe2">ADD_REDUCE_VVP_OP</a>(VVP_NAME, SDNAME)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb57a51f610c67c0c2843e28b7c25dce">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8460fcb434b47d2a3a92abc99c5034">ADD_BINARY_VVP_OP</a>(VVP_NAME, ...)&nbsp;&nbsp;&nbsp;case VEISD::VVP_NAME:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb57a51f610c67c0c2843e28b7c25dce">ADD_VVP_OP</a>(X, Y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_RED_ISD, REDUCE_ISD)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP</a>(VPOPC, VVPOPC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb57a51f610c67c0c2843e28b7c25dce">ADD_VVP_OP</a>(X, Y)</td>
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

### ADD\_BINARY\_VVP\_OP {#a9b12943e0b1a8a2d88cdebb5306452e8}

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

### ADD\_BINARY\_VVP\_OP {#a9b8460fcb434b47d2a3a92abc99c5034}

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

### ADD\_REDUCE\_VVP\_OP {#acce9948e4f34616ee8f2d15b5311efe2}

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

### ADD\_UNARY\_VVP\_OP {#ac405bfe9b55c2e75a8ef8538a8f23a30}

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

### ADD\_VVP\_OP {#aeb57a51f610c67c0c2843e28b7c25dce}

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

### ADD\_VVP\_OP {#a177cec26f7d7c7a0375b54cf69ed1c0d}

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

### ADD\_VVP\_OP {#aeb57a51f610c67c0c2843e28b7c25dce}

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

### ADD\_VVP\_OP {#aeb57a51f610c67c0c2843e28b7c25dce}

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

### ADD\_VVP\_OP {#aeb57a51f610c67c0c2843e28b7c25dce}

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

### ADD\_VVP\_OP {#aeb57a51f610c67c0c2843e28b7c25dce}

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

### ADD\_VVP\_OP {#aeb57a51f610c67c0c2843e28b7c25dce}

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

### HANDLE\_VP\_TO\_VVP {#a583d0e044035f3c45c3a392d3961e340}

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

### HANDLE\_VP\_TO\_VVP {#a583d0e044035f3c45c3a392d3961e340}

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

### HANDLE\_VP\_TO\_VVP {#a583d0e044035f3c45c3a392d3961e340}

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

### HANDLE\_VP\_TO\_VVP {#a583d0e044035f3c45c3a392d3961e340}

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

### HANDLE\_VP\_TO\_VVP {#a583d0e044035f3c45c3a392d3961e340}

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

### HANDLE\_VP\_TO\_VVP {#a583d0e044035f3c45c3a392d3961e340}

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

### HANDLE\_VP\_TO\_VVP {#a583d0e044035f3c45c3a392d3961e340}

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

### HANDLE\_VVP\_REDUCE\_TO\_SCALAR {#a1fd5c7a2346250a30165148b2e55bd97}

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

### REGISTER\_PACKED {#a772765ed3ceb45636107234f9ef229f5}

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

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
