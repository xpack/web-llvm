---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/ve/veisellowering-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `VEISelLowering.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/ve-h">VE.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/veisd">VEISD</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vetargetlowering">VETargetLowering</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a773a7c72268029f3f110cbcda7ae9e1f">ADD_VVP_OP</a>(VVP_NAME, ...)&nbsp;&nbsp;&nbsp;VVP_NAME,</td>
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
<p><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</a> <span class="doxyComputerOutput">VPOPC</span> is the VP_* SDNode opcode. <a href="#a583d0e044035f3c45c3a392d3961e340">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac863858a645eeec582c2f95d63a9fcd8">ADD_UNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a773a7c72268029f3f110cbcda7ae9e1f">ADD_VVP_OP(VVPNAME,SDNAME)</a> <span class="doxyComputerOutput">VVPName</span> is a VVP SDNode operator. <a href="#ac863858a645eeec582c2f95d63a9fcd8">More...</a></p>
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
<p><a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP(VVPNAME,SDNAME)</a> <span class="doxyComputerOutput">VVPName</span> is a VVP Binary operator. <a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1529008942f2b1735c60fd1e8e3f52af">ADD_TERNARY_VVP_OP</a>(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a1529008942f2b1735c60fd1e8e3f52af">ADD_TERNARY_VVP_OP(VVPNAME,SDNAME)</a> <span class="doxyComputerOutput">VVPName</span> is a VVP Ternary operator. <a href="#a1529008942f2b1735c60fd1e8e3f52af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d27632f59ff51b5d3cdb5c59b874ef">ADD_BINARY_VVP_OP_COMPACT</a>(NAME)&nbsp;&nbsp;&nbsp;    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<p><a href="#a7706f10a95325784fcd458e2121fe08d">REGISTER_PACKED(OPC)</a> <span class="doxyComputerOutput">OPC</span> The VVP opcode of the operation. <a href="#a7706f10a95325784fcd458e2121fe08d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP(OPC)</a> <span class="doxyComputerOutput">OPC</span> The VVP opcode of the operation. <a href="#aa79de5ed521f396215dc856b99714381">More...</a></p>
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
<p>Reductions. <a href="#ad971395655d465cf3ed4946c0d9f967e">More...</a></p>
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

<p><a href="#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP(VVPNAME,SDNAME)</a> <span class="doxyComputerOutput">VVPName</span> is a VVP Binary operator.</p>

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">            <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME) \
            <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VPNAME, VVPNAME)
</div>
</dd>
</dl>


<p><span class="doxyComputerOutput">SDNAME</span> is the generic SD opcode corresponding to <span class="doxyComputerOutput">VVPName</span>.</p>

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
<td class="doxyMemberName">#define ADD_BINARY_VVP_OP_COMPACT(NAME)&nbsp;&nbsp;&nbsp;    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a11b851f7dd6ad1ef2a2fea5686df1f36">ADD_BINARY_VVP_OP</a>(VVP_##NAME,VP_##NAME,NAME)</td>
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
<td class="doxyMemberName">#define ADD_REDUCE_VVP_OP(OPC, SDNAME)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(OPC, SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP(OPC)</a> <span class="doxyComputerOutput">OPC</span> The VVP opcode of the operation.</p>


<p><span class="doxyComputerOutput">SDNAME</span> The standard opcode of the operation.</p>

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
<td class="doxyMemberName">#define ADD_TERNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a1529008942f2b1735c60fd1e8e3f52af">ADD_TERNARY_VVP_OP(VVPNAME,SDNAME)</a> <span class="doxyComputerOutput">VVPName</span> is a VVP Ternary operator.</p>


<p><span class="doxyComputerOutput">SDNAME</span> is the generic SD opcode corresponding to <span class="doxyComputerOutput">VVPName</span>.</p>

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
<td class="doxyMemberName">#define ADD_UNARY_VVP_OP(VVPNAME, SDNAME)&nbsp;&nbsp;&nbsp;            <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a1ccd992516d11e6a3a3f1958be2dcaa7">ADD_VVP_OP</a>(VVPNAME,SDNAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a773a7c72268029f3f110cbcda7ae9e1f">ADD_VVP_OP(VVPNAME,SDNAME)</a> <span class="doxyComputerOutput">VVPName</span> is a VVP SDNode operator.</p>


<p><span class="doxyComputerOutput">SDNAME</span> is the generic SD opcode corresponding to <span class="doxyComputerOutput">VVPName</span>. <a href="#ac863858a645eeec582c2f95d63a9fcd8">ADD_UNARY_VVP_OP(VVPNAME,SDNAME)</a> <span class="doxyComputerOutput">VVPName</span> is a VVP Unary operator. <span class="doxyComputerOutput">SDNAME</span> is the generic SD opcode corresponding to <span class="doxyComputerOutput">VVPName</span>.</p>

</div>
</div>

### ADD\_VVP\_OP {#a773a7c72268029f3f110cbcda7ae9e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_VVP_OP(VVP_NAME, ...)&nbsp;&nbsp;&nbsp;VVP_NAME,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-h">VEISelLowering.h</a>.</p>

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

<p><a href="#a583d0e044035f3c45c3a392d3961e340">HANDLE_VP_TO_VVP(VPOPC, VVPOPC)</a> <span class="doxyComputerOutput">VPOPC</span> is the VP_* SDNode opcode.</p>


<p><span class="doxyComputerOutput">VVPOPC</span> is the VVP_* SDNode opcode.</p>

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

<p>Reductions.</p>

<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#aa79de5ed521f396215dc856b99714381">ADD_REDUCE_VVP_OP</a>(VVP_REDUCE_##OPC,VECREDUCE_##OPC) \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a0abb17afdcc2b53ea41ddfd4f74f1784">HANDLE_VP_TO_VVP</a>(VP_REDUCE_##OPC, VVP_REDUCE_##OPC) \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp/#a1fd5c7a2346250a30165148b2e55bd97">HANDLE_VVP_REDUCE_TO_SCALAR</a>(VVP_REDUCE_##OPC, SCALAR_OPC)
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

<p><a href="#a7706f10a95325784fcd458e2121fe08d">REGISTER_PACKED(OPC)</a> <span class="doxyComputerOutput">OPC</span> The VVP opcode of the operation.</p>
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
