---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armattributeparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMAttributeParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMAttributeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">llvm/Support/ARMAttributeParser.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elfattributeparser">ELFAttributeParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545be58faa673963fbfc0e98bd0b35c4">ARMAttributeParser</a> (ScopedPrinter *sw)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a498c870c5a55dfc5aa1c12cbafab18b8">ARMAttributeParser</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ef7f7834dda98b31831246d06fc9d1">handler</a> (uint64_t tag, bool &amp;handled) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850896ccc8e0ead540fd29b7772b99de">stringAttribute</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8e6de54eb8e25bff6a867b0334935b">CPU_arch</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878bc2e212d44e94d3a2ebcf158ef919">CPU_arch_profile</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e45323a966f541e86bfdb579e1cc79c">ARM_ISA_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1162abe3acb9d022c4e90fe6d9baadd6">THUMB_ISA_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100e22fbc5650d31489e6cb0be23a8a3">FP_arch</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06802f31d9b19b00b7521e5467dfff26">WMMX_arch</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5e338308e0f847e2b02a922782c806">Advanced_SIMD_arch</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b065cd90d0c91827a31a133a1a8958">MVE_arch</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c58bfd660b5c443ae39e8a9f9e0515">PCS_config</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefcadc0e040b1f335ab257bba9182f31">ABI_PCS_R9_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd520d80356e485e8837d9e323495e2">ABI_PCS_RW_data</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472ca942ab6d1a6e2f1b95cec2d17a6a">ABI_PCS_RO_data</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35bbdc026b82f27ea4517de8348cbbf">ABI_PCS_GOT_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac908d523b7cbeca40ef5ac543629ceff">ABI_PCS_wchar_t</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e31c32d1eeb18c5f9806414da98185c">ABI_FP_rounding</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13ba9dbbfb68a8df3675806e8319f7f">ABI_FP_denormal</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa23821cb2418a1728f6670c67da6207f">ABI_FP_exceptions</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f190a066d3eb846a285c426c5df379f">ABI_FP_user_exceptions</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace82b446455dac5cb4684e1a6918c054">ABI_FP_number_model</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d87d43a848a38c2dc353cdba2cce3b">ABI_align_needed</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3026db4fe2fde22b08b303956c7f6216">ABI_align_preserved</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17b334734a8fbc7df3781b0eb9e9832">ABI_enum_size</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6b0018be1fbbc97a6cb790f0e3f132">ABI_HardFP_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91177fe78b6ec0e61e06a419af4dab09">ABI_VFP_args</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff932a08823507faf6140e769a046071">ABI_WMMX_args</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6322e21cf10acca2ab4fdb91d517e1c3">ABI_optimization_goals</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4c23a67c99a63fe23bbda5db730b74">ABI_FP_optimization_goals</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860929559d90fa94c933d86bd4aab241">compatibility</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2d546914060e5a36950a648b973ffc">CPU_unaligned_access</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bf82cc98333e0ec27ba35f016cfa7b">FP_HP_extension</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba8fe3554e6fec07ef30fb946eabc841">ABI_FP_16bit_format</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65103fe3d6cdbfe0d0265b195f7ddc68">MPextension_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ac895702560e20d48c81e1321b2c8ba">DIV_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd83692dd0159c3c68696c3ef77a2442">DSP_extension</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213fb9814bf3f588d84db10ad5f58636">T2EE_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75b50c0283c03dc1050b8fd11454815">Virtualization_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929f915e774ce3554367d1497c457e5f">PAC_extension</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e839ff6c6c8f9c09cfd9715085668bb">BTI_extension</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eed0a08d5c084381395eefd0794d44a">PACRET_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5983a916e449aa491250baffb14205f">BTI_use</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0a8ed7e8cbfaee4883c1cfac4adfd9">nodefaults</a> (ARMBuildAttrs::AttrType tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7530a046e1e3fff7f644f40d5fd22cdf">also_compatible_with</a> (ARMBuildAttrs::AttrType tag)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DisplayHandler</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290913fed575acd7e8e3ecc71c9b1040">displayRoutines</a>[]</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMAttributeParser() {#a545be58faa673963fbfc0e98bd0b35c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARMAttributeParser::ARMAttributeParser (<a href="/web-llvm/docs/api/classes/llvm/scopedprinter">ScopedPrinter</a> * sw)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a4e104d3bf9f32e68ed3dacf1c6092931">llvm::ELFAttributeParser::ELFAttributeParser</a> and <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a967d07f3cace8ee5af66bff6585e03e7">llvm::ELFAttributeParser::sw</a>.</p>

</div>
</div>

### ARMAttributeParser() {#a498c870c5a55dfc5aa1c12cbafab18b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARMAttributeParser::ARMAttributeParser ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a4e104d3bf9f32e68ed3dacf1c6092931">llvm::ELFAttributeParser::ELFAttributeParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ABI\_align\_needed() {#a44d87d43a848a38c2dc353cdba2cce3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_align_needed (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_align\_preserved() {#a3026db4fe2fde22b08b303956c7f6216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_align_preserved (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_enum\_size() {#aa17b334734a8fbc7df3781b0eb9e9832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_enum_size (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_FP\_16bit\_format() {#aba8fe3554e6fec07ef30fb946eabc841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_FP_16bit_format (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_FP\_denormal() {#af13ba9dbbfb68a8df3675806e8319f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_FP_denormal (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_FP\_exceptions() {#aa23821cb2418a1728f6670c67da6207f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_FP_exceptions (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_FP\_number\_model() {#ace82b446455dac5cb4684e1a6918c054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_FP_number_model (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_FP\_optimization\_goals() {#a1d4c23a67c99a63fe23bbda5db730b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_FP_optimization_goals (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_FP\_rounding() {#a9e31c32d1eeb18c5f9806414da98185c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_FP_rounding (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_FP\_user\_exceptions() {#a8f190a066d3eb846a285c426c5df379f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_FP_user_exceptions (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_HardFP\_use() {#a9b6b0018be1fbbc97a6cb790f0e3f132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_HardFP_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_optimization\_goals() {#a6322e21cf10acca2ab4fdb91d517e1c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_optimization_goals (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_PCS\_GOT\_use() {#ac35bbdc026b82f27ea4517de8348cbbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_PCS_GOT_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_PCS\_R9\_use() {#aefcadc0e040b1f335ab257bba9182f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_PCS_R9_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_PCS\_RO\_data() {#a472ca942ab6d1a6e2f1b95cec2d17a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_PCS_RO_data (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_PCS\_RW\_data() {#a0bd520d80356e485e8837d9e323495e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_PCS_RW_data (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_PCS\_wchar\_t() {#ac908d523b7cbeca40ef5ac543629ceff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_PCS_wchar_t (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_VFP\_args() {#a91177fe78b6ec0e61e06a419af4dab09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_VFP_args (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ABI\_WMMX\_args() {#aff932a08823507faf6140e769a046071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ABI_WMMX_args (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### Advanced\_SIMD\_arch() {#a6e5e338308e0f847e2b02a922782c806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::Advanced_SIMD_arch (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### also\_compatible\_with() {#a7530a046e1e3fff7f644f40d5fd22cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::also_compatible_with (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### ARM\_ISA\_use() {#a2e45323a966f541e86bfdb579e1cc79c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::ARM_ISA_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### BTI\_extension() {#a1e839ff6c6c8f9c09cfd9715085668bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::BTI_extension (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### BTI\_use() {#ad5983a916e449aa491250baffb14205f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::BTI_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### compatibility() {#a860929559d90fa94c933d86bd4aab241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::compatibility (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### CPU\_arch() {#adf8e6de54eb8e25bff6a867b0334935b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::CPU_arch (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### CPU\_arch\_profile() {#a878bc2e212d44e94d3a2ebcf158ef919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::CPU_arch_profile (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### CPU\_unaligned\_access() {#a3a2d546914060e5a36950a648b973ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::CPU_unaligned_access (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### DIV\_use() {#a1ac895702560e20d48c81e1321b2c8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::DIV_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### DSP\_extension() {#abd83692dd0159c3c68696c3ef77a2442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::DSP_extension (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### FP\_arch() {#a100e22fbc5650d31489e6cb0be23a8a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::FP_arch (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### FP\_HP\_extension() {#ae2bf82cc98333e0ec27ba35f016cfa7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::FP_HP_extension (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### handler() {#ac3ef7f7834dda98b31831246d06fc9d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::handler (uint64_t tag, bool &amp; handled)</td>
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



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### MPextension\_use() {#a65103fe3d6cdbfe0d0265b195f7ddc68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::MPextension_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### MVE\_arch() {#af3b065cd90d0c91827a31a133a1a8958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::MVE_arch (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### nodefaults() {#a0b0a8ed7e8cbfaee4883c1cfac4adfd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::nodefaults (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### PAC\_extension() {#a929f915e774ce3554367d1497c457e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::PAC_extension (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### PACRET\_use() {#a4eed0a08d5c084381395eefd0794d44a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::PACRET_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### PCS\_config() {#ac3c58bfd660b5c443ae39e8a9f9e0515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::PCS_config (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### stringAttribute() {#a850896ccc8e0ead540fd29b7772b99de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::stringAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### T2EE\_use() {#a213fb9814bf3f588d84db10ad5f58636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::T2EE_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### THUMB\_ISA\_use() {#a1162abe3acb9d022c4e90fe6d9baadd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::THUMB_ISA_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### Virtualization\_use() {#ac75b50c0283c03dc1050b8fd11454815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::Virtualization_use (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

### WMMX\_arch() {#a06802f31d9b19b00b7521e5467dfff26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error ARMAttributeParser::WMMX_arch (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#aea10ca6bf098a425d51ac7fe65d30ed6">ARMBuildAttrs::AttrType</a> tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### displayRoutines {#a290913fed575acd7e8e3ecc71c9b1040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMAttributeParser::DisplayHandler ARMAttributeParser::displayRoutines</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armattributeparser-h">ARMAttributeParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/armattributeparser-cpp">ARMAttributeParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
