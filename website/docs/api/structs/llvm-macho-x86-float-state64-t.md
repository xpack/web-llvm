---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/macho/x86-float-state64-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `x86_float_state64_t` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MachO::x86_float_state64_t { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3ab46b69eb251e32edf6cce53121f0">fpu_reserved</a>[2]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/fp-control-t">fp_control_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a9441c5eb266e5618bab4169e77f46">fpu_fcw</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/fp-status-t">fp_status_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced00c49fa1cd7c99ea489c20c95fa25">fpu_fsw</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5ff627b535713308dbd8473d17014a">fpu_ftw</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a5ce9ef468ebd523c5c14fee7aa0382">fpu_rsrv1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e84b2fe1251ed458e572b4387eb1af4">fpu_fop</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819f88ae7ce4a6a8cc04e5c39a9aedec">fpu_ip</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acebdbc74a5d7823a86d09346a04774bf">fpu_cs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012024feff19a809b2ed5c1cf861321a">fpu_rsrv2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a791a6fcaf3d953693fb576cf5f03f183">fpu_dp</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e2a1d75c96ebde452a1677ac229ff5">fpu_ds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad409e08f24dc85241f0220036017a88c">fpu_rsrv3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee497f30b0d68cd95a3be6dd8e15d79">fpu_mxcsr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb209388ebc0312dda09ec477f9f7dcf">fpu_mxcsrmask</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mmst-reg-t">mmst_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa0ca101cc50af4a966d3ee8f34d6851">fpu_stmm0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mmst-reg-t">mmst_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e12193f6a67b1596d4231948fc2934">fpu_stmm1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mmst-reg-t">mmst_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a6e99c5f61d417847eb7058ff446bb">fpu_stmm2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mmst-reg-t">mmst_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9006dad4b4fdf3d6bb345daff837d4e0">fpu_stmm3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mmst-reg-t">mmst_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68484dee53a146de4b6b7fb8adf3441c">fpu_stmm4</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mmst-reg-t">mmst_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774f32d83d8cfcce4b4e4145ebc66d5d">fpu_stmm5</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mmst-reg-t">mmst_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e621fadb2d05ac67d4e0e186fc1b86">fpu_stmm6</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/mmst-reg-t">mmst_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf48f450d1c7fd466593fa7a616b8702">fpu_stmm7</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d24484702686faf7ba5e117e84156d">fpu_xmm0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f8956dc41a689d5e68190eac40d148">fpu_xmm1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4baebaa6c2250418288dd764bc50d356">fpu_xmm2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30dc2d5b6cfefe7db159128c64ce88cf">fpu_xmm3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b55c3bf16a5bd3c88ca64a79046da3">fpu_xmm4</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b079cf704e7f689ccc3c83532be6b56">fpu_xmm5</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29da7c1d63019c40e95c669db767e8d">fpu_xmm6</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7df7c75b10fc2faeee5ffcd4973552">fpu_xmm7</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c3a9f7502c6bc96d9be57ae5ac0421">fpu_xmm8</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf318ddd1519b1d51315b15fbfead5fc">fpu_xmm9</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a142b5a1baa25ca7c2b3eeab05c128917">fpu_xmm10</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a164c649e557b0badb6ad114e1095b92e">fpu_xmm11</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4786343155a35e7b09acf4708152089">fpu_xmm12</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2244f0fea757394d201ec749893e2a50">fpu_xmm13</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3518bd30054f3c4d69e03abd86cd6da3">fpu_xmm14</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/xmm-reg-t">xmm_reg_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63682c933d877826fd82621f5c5286d7">fpu_xmm15</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d2e78bb126f972440db4e9ed72b6cbb">fpu_rsrv4</a>[6 *16]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e66dec120bba09075b4111ce12a5832">fpu_reserved1</a></td>
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


<p>Definition at line 1782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### fpu\_cs {#acebdbc74a5d7823a86d09346a04774bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MachO::x86_float_state64_t::fpu_cs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_dp {#a791a6fcaf3d953693fb576cf5f03f183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::x86_float_state64_t::fpu_dp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_ds {#ae9e2a1d75c96ebde452a1677ac229ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MachO::x86_float_state64_t::fpu_ds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_fcw {#a91a9441c5eb266e5618bab4169e77f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fp_control_t llvm::MachO::x86_float_state64_t::fpu_fcw</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_fop {#a7e84b2fe1251ed458e572b4387eb1af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MachO::x86_float_state64_t::fpu_fop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_fsw {#aced00c49fa1cd7c99ea489c20c95fa25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fp_status_t llvm::MachO::x86_float_state64_t::fpu_fsw</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_ftw {#a5f5ff627b535713308dbd8473d17014a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachO::x86_float_state64_t::fpu_ftw</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_ip {#a819f88ae7ce4a6a8cc04e5c39a9aedec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::x86_float_state64_t::fpu_ip</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_mxcsr {#a3ee497f30b0d68cd95a3be6dd8e15d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::x86_float_state64_t::fpu_mxcsr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_mxcsrmask {#acb209388ebc0312dda09ec477f9f7dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::x86_float_state64_t::fpu_mxcsrmask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_reserved {#a7f3ab46b69eb251e32edf6cce53121f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int32_t llvm::MachO::x86_float_state64_t::fpu_reserved[2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_reserved1 {#a2e66dec120bba09075b4111ce12a5832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MachO::x86_float_state64_t::fpu_reserved1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_rsrv1 {#a3a5ce9ef468ebd523c5c14fee7aa0382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MachO::x86_float_state64_t::fpu_rsrv1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_rsrv2 {#a012024feff19a809b2ed5c1cf861321a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MachO::x86_float_state64_t::fpu_rsrv2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_rsrv3 {#ad409e08f24dc85241f0220036017a88c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MachO::x86_float_state64_t::fpu_rsrv3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_rsrv4 {#a0d2e78bb126f972440db4e9ed72b6cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::MachO::x86_float_state64_t::fpu_rsrv4[6 *16]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_stmm0 {#afa0ca101cc50af4a966d3ee8f34d6851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmst_reg_t llvm::MachO::x86_float_state64_t::fpu_stmm0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_stmm1 {#a38e12193f6a67b1596d4231948fc2934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmst_reg_t llvm::MachO::x86_float_state64_t::fpu_stmm1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_stmm2 {#aa4a6e99c5f61d417847eb7058ff446bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmst_reg_t llvm::MachO::x86_float_state64_t::fpu_stmm2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_stmm3 {#a9006dad4b4fdf3d6bb345daff837d4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmst_reg_t llvm::MachO::x86_float_state64_t::fpu_stmm3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_stmm4 {#a68484dee53a146de4b6b7fb8adf3441c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmst_reg_t llvm::MachO::x86_float_state64_t::fpu_stmm4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_stmm5 {#a774f32d83d8cfcce4b4e4145ebc66d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmst_reg_t llvm::MachO::x86_float_state64_t::fpu_stmm5</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_stmm6 {#a68e621fadb2d05ac67d4e0e186fc1b86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmst_reg_t llvm::MachO::x86_float_state64_t::fpu_stmm6</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_stmm7 {#aaf48f450d1c7fd466593fa7a616b8702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mmst_reg_t llvm::MachO::x86_float_state64_t::fpu_stmm7</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm0 {#ac0d24484702686faf7ba5e117e84156d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm1 {#a03f8956dc41a689d5e68190eac40d148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm10 {#a142b5a1baa25ca7c2b3eeab05c128917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm11 {#a164c649e557b0badb6ad114e1095b92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm11</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm12 {#ad4786343155a35e7b09acf4708152089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm12</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm13 {#a2244f0fea757394d201ec749893e2a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm13</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm14 {#a3518bd30054f3c4d69e03abd86cd6da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm14</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm15 {#a63682c933d877826fd82621f5c5286d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm15</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm2 {#a4baebaa6c2250418288dd764bc50d356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm3 {#a30dc2d5b6cfefe7db159128c64ce88cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm4 {#af1b55c3bf16a5bd3c88ca64a79046da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm5 {#a7b079cf704e7f689ccc3c83532be6b56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm5</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm6 {#ad29da7c1d63019c40e95c669db767e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm6</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm7 {#a7c7df7c75b10fc2faeee5ffcd4973552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm7</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm8 {#a13c3a9f7502c6bc96d9be57ae5ac0421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

### fpu\_xmm9 {#abf318ddd1519b1d51315b15fbfead5fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">xmm_reg_t llvm::MachO::x86_float_state64_t::fpu_xmm9</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">MachO.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
