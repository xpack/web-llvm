---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Dwarf.h` File Reference

<p>This file contains constants used for implementing Dwarf debug support. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/datatypes-h">llvm/Support/DataTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadicdetails-h">llvm/Support/FormatVariadicDetails.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;limits&gt;
#include "llvm/BinaryFormat/Dwarf.def"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf">dwarf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates the starting offsets for various sections within the .debug_names section. <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">FormParams</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper struct providing information about the byte size of DW_FORM values that vary in size depending on the DWARF version, address byte size, or DWARF32/DWARF64. <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/pubindexentrydescriptor">PubIndexEntryDescriptor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describes an entry of the various gnu_pub* debug sections. <a href="/web-llvm/docs/api/structs/llvm/dwarf/pubindexentrydescriptor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/enumtraits">EnumTraits&lt;Enum&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/enumtraits-d4d6a4608d9bdfad0d50a482bb25fe07">EnumTraits&lt;Attribute&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/enumtraits-721714e03a6b04c4dc4cc54f711dac22">EnumTraits&lt;Form&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/enumtraits-bf5eaae4329c28e27b67c2f195bd3474">EnumTraits&lt;Index&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/enumtraits-5d1d22f040f78a7ad8ecb8f8946b65a0">EnumTraits&lt;Tag&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/enumtraits-feb21a03e20e06ccf11956b44c5f839a">EnumTraits&lt;LineNumberOps&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf/enumtraits-7faa5718c24e84219ca348f57583f6d0">EnumTraits&lt;LocationAtom&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/format-provider-529796c169261fe2c884ec9b378a7ff5">format_provider&lt;Enum, std::enable_if_t&lt; dwarf::EnumTraits&lt; Enum &gt;::value &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dwarf constants <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider</a>. <a href="/web-llvm/docs/api/structs/llvm/format-provider-529796c169261fe2c884ec9b378a7ff5/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cbb26ec5bb928e366fe1965e8bf60e">HANDLE_DW_TAG</a>(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;DW_TAG_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d57fedfe3914b8e5a96d4538bb2b10c">HANDLE_DW_TAG</a>(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8443b65087704cc597bc033cce391b2">HANDLE_DW_AT</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;DW_AT_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1356ad6053f0b2b4dbf9b8b7ed993dba">HANDLE_DW_FORM</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;DW_FORM_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b25d988cef67fbdaf17dad3a9f471a">HANDLE_DW_OP</a>(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  DW_OP_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab928ceddc69409abf3bd25dda56b9965">HANDLE_DW_OP_LLVM_USEROP</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_OP_LLVM_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e48abbcebbe0b2df64297889172b34a">HANDLE_DW_ATE</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;DW_ATE_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac136af35cdea904cbbfeced756ff54af">HANDLE_DW_END</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_END_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1433ab8c00b9e94cdd1cba68b9d15e52">HANDLE_DW_VIRTUALITY</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_VIRTUALITY_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674b19184f2de2674115ea235f6eac8c">HANDLE_DW_DEFAULTED</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_DEFAULTED_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70cb3c0d314e41944b65f1bfdaa6457">HANDLE_DW_LANG</a>(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  DW_LANG_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae836cf6520611c3f7271eeafa38bbc66">HANDLE_DW_LNAME</a>(ID, NAME, DESC, LOWER_BOUND)&nbsp;&nbsp;&nbsp;DW_LNAME_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54fbd19a6c99fad8fd577abc1d577357">HANDLE_DW_CC</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_CC_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68253931ea30b33bb252ff39ae9c9065">HANDLE_DW_LNS</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_LNS_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4faa8496ed4ce3df629132e26af16f">HANDLE_DW_LNE</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_LNE_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f2a63ca3bb1ec2354581db3ccef184">HANDLE_DW_LNCT</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_LNCT_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab39ee1f10fa10ef003531061b92e243">HANDLE_DW_MACRO</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_MACRO_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae0cc4f57ec628c230f63825e74a120">HANDLE_DW_MACRO_GNU</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_MACRO_GNU_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b831e2d4801073660714550d8831b38">HANDLE_DW_RLE</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_RLE_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d20ad70fd45c277a213bcf62e01116b">HANDLE_DW_LLE</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_LLE_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13955c31cd62b8fbe21d29d1327da74e">HANDLE_DW_CFA</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_CFA_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c0bbefc3ef347578862bd681838efbb">HANDLE_DW_CFA_PRED</a>(ID, NAME, ARCH)&nbsp;&nbsp;&nbsp;DW_CFA_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa855cb8f3941be85fae1836cd620b7">HANDLE_DW_APPLE_PROPERTY</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_APPLE_PROPERTY_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a64406a4f6abfd4694861a1d4d4e64d">HANDLE_DW_UT</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_UT_##NAME = ID,</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d6df5257431e9fd2cc92e443ce6360">HANDLE_DW_IDX</a>(ID, NAME)&nbsp;&nbsp;&nbsp;DW_IDX_##NAME = ID,</td>
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

## Description {#details}

<p>This file contains constants used for implementing Dwarf debug support.</p>


<p>For details on the Dwarf specfication see the latest DWARF Debugging Information Format standard document on <a href="http://www.dwarfstd.org">http://www.dwarfstd.org</a>. This file often includes support for non-released standard features.</p>


<div class="doxySectionDef">

## Macro Definitions

### HANDLE\_DW\_APPLE\_PROPERTY {#a2aa855cb8f3941be85fae1836cd620b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_APPLE_PROPERTY(ID, NAME)&nbsp;&nbsp;&nbsp;DW_APPLE_PROPERTY_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_AT {#af8443b65087704cc597bc033cce391b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_AT(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;DW_AT_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_ATE {#a1e48abbcebbe0b2df64297889172b34a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_ATE(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;DW_ATE_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_CC {#a54fbd19a6c99fad8fd577abc1d577357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_CC(ID, NAME)&nbsp;&nbsp;&nbsp;DW_CC_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_CFA {#a13955c31cd62b8fbe21d29d1327da74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_CFA(ID, NAME)&nbsp;&nbsp;&nbsp;DW_CFA_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_CFA\_PRED {#a9c0bbefc3ef347578862bd681838efbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_CFA_PRED(ID, NAME, ARCH)&nbsp;&nbsp;&nbsp;DW_CFA_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_DEFAULTED {#a674b19184f2de2674115ea235f6eac8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_DEFAULTED(ID, NAME)&nbsp;&nbsp;&nbsp;DW_DEFAULTED_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_END {#ac136af35cdea904cbbfeced756ff54af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_END(ID, NAME)&nbsp;&nbsp;&nbsp;DW_END_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_FORM {#a1356ad6053f0b2b4dbf9b8b7ed993dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_FORM(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;DW_FORM_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_IDX {#a06d6df5257431e9fd2cc92e443ce6360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_IDX(ID, NAME)&nbsp;&nbsp;&nbsp;DW_IDX_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_LANG {#aa70cb3c0d314e41944b65f1bfdaa6457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LANG(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  DW_LANG_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_LLE {#a5d20ad70fd45c277a213bcf62e01116b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LLE(ID, NAME)&nbsp;&nbsp;&nbsp;DW_LLE_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_LNAME {#ae836cf6520611c3f7271eeafa38bbc66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LNAME(ID, NAME, DESC, LOWER_BOUND)&nbsp;&nbsp;&nbsp;DW_LNAME_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_LNCT {#a01f2a63ca3bb1ec2354581db3ccef184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LNCT(ID, NAME)&nbsp;&nbsp;&nbsp;DW_LNCT_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_LNE {#a6c4faa8496ed4ce3df629132e26af16f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LNE(ID, NAME)&nbsp;&nbsp;&nbsp;DW_LNE_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_LNS {#a68253931ea30b33bb252ff39ae9c9065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LNS(ID, NAME)&nbsp;&nbsp;&nbsp;DW_LNS_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_MACRO {#aab39ee1f10fa10ef003531061b92e243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_MACRO(ID, NAME)&nbsp;&nbsp;&nbsp;DW_MACRO_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_MACRO\_GNU {#a0ae0cc4f57ec628c230f63825e74a120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_MACRO_GNU(ID, NAME)&nbsp;&nbsp;&nbsp;DW_MACRO_GNU_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_OP {#aa4b25d988cef67fbdaf17dad3a9f471a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_OP(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  DW_OP_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_OP\_LLVM\_USEROP {#ab928ceddc69409abf3bd25dda56b9965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_OP_LLVM_USEROP(ID, NAME)&nbsp;&nbsp;&nbsp;DW_OP_LLVM_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_RLE {#a3b831e2d4801073660714550d8831b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_RLE(ID, NAME)&nbsp;&nbsp;&nbsp;DW_RLE_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_TAG {#a52cbb26ec5bb928e366fe1965e8bf60e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_TAG(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;DW_TAG_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_TAG {#a7d57fedfe3914b8e5a96d4538bb2b10c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_TAG(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_TAG_##NAME:                                                          \
    return (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvsupport-h/#a0fe94e4721fb2c4dfc05937e4c71aa2c">KIND</a> == DW_KIND_TYPE);
</div>
</dd>
</dl>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_UT {#a2a64406a4f6abfd4694861a1d4d4e64d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_UT(ID, NAME)&nbsp;&nbsp;&nbsp;DW_UT_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

### HANDLE\_DW\_VIRTUALITY {#a1433ab8c00b9e94cdd1cba68b9d15e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_VIRTUALITY(ID, NAME)&nbsp;&nbsp;&nbsp;DW_VIRTUALITY_##NAME = ID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
