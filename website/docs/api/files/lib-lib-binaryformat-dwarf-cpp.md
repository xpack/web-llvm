---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/binaryformat/dwarf-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Dwarf.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "llvm/BinaryFormat/Dwarf.def"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac731b1d070861b2be39a32d61d885c82">LlvmUserOperationEncodingString</a> (unsigned Encoding)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4343b39231fb6db37ae8b55d21245386">getLlvmUserOperationEncoding</a> (StringRef LlvmUserOperationEncodingString)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cbb26ec5bb928e366fe1965e8bf60e">HANDLE_DW_TAG</a>(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d57fedfe3914b8e5a96d4538bb2b10c">HANDLE_DW_TAG</a>(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;  .Case("DW_TAG_" #NAME, DW_TAG_##NAME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785882b403a247f28125e59bfdc7ad2e">HANDLE_DW_TAG</a>(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2de1f57ad11f9fa2f98f88184564f6a8">HANDLE_DW_TAG</a>(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8443b65087704cc597bc033cce391b2">HANDLE_DW_AT</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449044036ab88466c3eb49c3710028e6">HANDLE_DW_AT</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a079ad233f8dbab59643ee035b4fa60f7">HANDLE_DW_AT</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1356ad6053f0b2b4dbf9b8b7ed993dba">HANDLE_DW_FORM</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a032f4601a8d3e6aa806012bdabbef311">HANDLE_DW_FORM</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20cc2c2c7d7f7f2e4494f487aaa52aee">HANDLE_DW_FORM</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b25d988cef67fbdaf17dad3a9f471a">HANDLE_DW_OP</a>(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad122873d9dbf4cd0d4c74356fb71d3b0">HANDLE_DW_OP</a>(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  .Case("DW_OP_" #NAME, DW_OP_##NAME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab928ceddc69409abf3bd25dda56b9965">HANDLE_DW_OP_LLVM_USEROP</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf593e36a87908fda806256e222ac77">HANDLE_DW_OP_LLVM_USEROP</a>(ID, NAME)&nbsp;&nbsp;&nbsp;.Case(#NAME, DW_OP_LLVM_##NAME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525f33dfb48b1f49b007789ff4fb3867">HANDLE_DW_OP</a>(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ac3f1099cf151f5803a4428f1b8a13">HANDLE_DW_OP</a>(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dde6ced67c7e78e7e79b749d7ef6141">HANDLE_DW_OP</a>(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0c23307ca40b131eaf8784e9086acf">HANDLE_DW_OP</a>(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e48abbcebbe0b2df64297889172b34a">HANDLE_DW_ATE</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df3801923ab480f3a77a754d0eb976c">HANDLE_DW_ATE</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  .Case("DW_ATE_" #NAME, DW_ATE_##NAME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abecef955802718741f43259a1a3a14b0">HANDLE_DW_ATE</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2930eee009a2e506268be719938b84d9">HANDLE_DW_ATE</a>(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1433ab8c00b9e94cdd1cba68b9d15e52">HANDLE_DW_VIRTUALITY</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6c3be33c955031aa4b30004d4b7d27">HANDLE_DW_VIRTUALITY</a>(ID, NAME)&nbsp;&nbsp;&nbsp;  .Case("DW_VIRTUALITY_" #NAME, DW_VIRTUALITY_##NAME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70cb3c0d314e41944b65f1bfdaa6457">HANDLE_DW_LANG</a>(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9bde42f9e025684d465104636dff585">HANDLE_DW_LANG</a>(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  .Case("DW_LANG_" #NAME, DW_LANG_##NAME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4455362a9b3535452f07740f8a26e9">HANDLE_DW_LANG</a>(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e88d649e5d49df2fca6c2abcfc24e6d">HANDLE_DW_LANG</a>(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae79c6bb67656cc6eebafd3ca9591adf4">HANDLE_DW_LANG</a>(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae836cf6520611c3f7271eeafa38bbc66">HANDLE_DW_LNAME</a>(ID, NAME, DESC, LOWER_BOUND)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54fbd19a6c99fad8fd577abc1d577357">HANDLE_DW_CC</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affc27bcc105b429518acd31c4d797ce0">HANDLE_DW_CC</a>(ID, NAME)&nbsp;&nbsp;&nbsp;.Case("DW_CC_" #NAME, DW_CC_##NAME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68253931ea30b33bb252ff39ae9c9065">HANDLE_DW_LNS</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4faa8496ed4ce3df629132e26af16f">HANDLE_DW_LNE</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab39ee1f10fa10ef003531061b92e243">HANDLE_DW_MACRO</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae0cc4f57ec628c230f63825e74a120">HANDLE_DW_MACRO_GNU</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac09375db4d0510e2826556d10f4592f3">HANDLE_DW_MACRO</a>(ID, NAME)&nbsp;&nbsp;&nbsp;.Case("DW_MACRO_" #NAME, ID)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b831e2d4801073660714550d8831b38">HANDLE_DW_RLE</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d20ad70fd45c277a213bcf62e01116b">HANDLE_DW_LLE</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781f991b2c23372223e057b11b00231c">SELECT_AARCH64</a>&nbsp;&nbsp;&nbsp;(Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a> || Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67588d848127735cc4123d1cfec95c88">SELECT_MIPS64</a>&nbsp;&nbsp;&nbsp;Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">llvm::Triple::mips64</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4c1d3ee9db2a3046eeeb971b854a6f">SELECT_SPARC</a>&nbsp;&nbsp;&nbsp;(Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">llvm::Triple::sparc</a> || Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">llvm::Triple::sparcv9</a>)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b9e0da0ce0a5a1f08eb0855169b934">SELECT_X86</a>&nbsp;&nbsp;&nbsp;(Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> || Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13955c31cd62b8fbe21d29d1327da74e">HANDLE_DW_CFA</a>(ID, NAME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46cfacf8dd96b117a3a522f77a694fd">HANDLE_DW_CFA_PRED</a>(ID, NAME, PRED)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a690af458b878e3e9f969884e60139">HANDLE_DW_CFA_PRED</a>(ID, NAME, PRED)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a6420fadb12688d9f12ddb186d1db0">HANDLE_DW_CFA</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa855cb8f3941be85fae1836cd620b7">HANDLE_DW_APPLE_PROPERTY</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a64406a4f6abfd4694861a1d4d4e64d">HANDLE_DW_UT</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d6df5257431e9fd2cc92e443ce6360">HANDLE_DW_IDX</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee18baf47f2a4df665dd9c224079ca86">HANDLE_DW_RLE</a>(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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

## Functions

### getLlvmUserOperationEncoding() {#a4343b39231fb6db37ae8b55d21245386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getLlvmUserOperationEncoding (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LlvmUserOperationEncodingString)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="#ac731b1d070861b2be39a32d61d885c82">LlvmUserOperationEncodingString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga183a5264c7ee13f65123fc83fb0c923c">llvm::dwarf::getSubOperationEncoding</a>.</p>

</div>
</div>

### LlvmUserOperationEncodingString() {#ac731b1d070861b2be39a32d61d885c82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LlvmUserOperationEncodingString (unsigned Encoding)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a4343b39231fb6db37ae8b55d21245386">getLlvmUserOperationEncoding</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga5f3afab9bb796a171a9433e9b8ccbfcd">llvm::dwarf::SubOperationEncodingString</a>.</p>

</div>
</div>

</div>

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
<td class="doxyMemberName">#define HANDLE_DW_APPLE_PROPERTY(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_APPLE_PROPERTY_##NAME:                                               \
    return "DW_APPLE_PROPERTY_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_AT(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_AT_##NAME:                                                           \
    return "DW_AT_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_AT {#a449044036ab88466c3eb49c3710028e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_AT(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_AT_##NAME:                                                           \
    return VERSION;
</div>
</dd>
</dl>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_AT {#a079ad233f8dbab59643ee035b4fa60f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_AT(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_AT_##NAME:                                                           \
    return DWARF_VENDOR_##VENDOR;
</div>
</dd>
</dl>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_ATE(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_ATE_##NAME:                                                          \
    return "DW_ATE_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_ATE {#a0df3801923ab480f3a77a754d0eb976c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_ATE(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  .Case("DW_ATE_" #NAME, DW_ATE_##NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_ATE {#abecef955802718741f43259a1a3a14b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_ATE(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_ATE_##NAME:                                                          \
    return VERSION;
</div>
</dd>
</dl>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_ATE {#a2930eee009a2e506268be719938b84d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_ATE(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_ATE_##NAME:                                                          \
    return DWARF_VENDOR_##VENDOR;
</div>
</dd>
</dl>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_CC(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_CC_##NAME:                                                           \
    return "DW_CC_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_CC {#affc27bcc105b429518acd31c4d797ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_CC(ID, NAME)&nbsp;&nbsp;&nbsp;.Case("DW_CC_" #NAME, DW_CC_##NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_CFA(ID, NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_CFA {#a98a6420fadb12688d9f12ddb186d1db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_CFA(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_CFA_##NAME:                                                          \
    return "DW_CFA_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_CFA\_PRED {#ab46cfacf8dd96b117a3a522f77a694fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_CFA_PRED(ID, NAME, PRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (ID == Encoding &amp;&amp; PRED) \
    return "DW_CFA_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_CFA\_PRED {#af8a690af458b878e3e9f969884e60139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_CFA_PRED(ID, NAME, PRED)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_FORM(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_FORM_##NAME:                                                         \
    return "DW_FORM_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_FORM {#a032f4601a8d3e6aa806012bdabbef311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_FORM(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_FORM_##NAME:                                                         \
    return VERSION;
</div>
</dd>
</dl>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_FORM {#a20cc2c2c7d7f7f2e4494f487aaa52aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_FORM(ID, NAME, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_FORM_##NAME:                                                         \
    return DWARF_VENDOR_##VENDOR;
</div>
</dd>
</dl>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_IDX(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_IDX_##NAME:                                                          \
    return "DW_IDX_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_LANG(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_LANG_##NAME:                                                         \
    return "DW_LANG_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_LANG {#ae9bde42f9e025684d465104636dff585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LANG(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  .Case("DW_LANG_" #NAME, DW_LANG_##NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_LANG {#adb4455362a9b3535452f07740f8a26e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LANG(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_LANG_##NAME:                                                         \
    return VERSION;
</div>
</dd>
</dl>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_LANG {#a2e88d649e5d49df2fca6c2abcfc24e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LANG(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_LANG_##NAME:                                                         \
    return DWARF_VENDOR_##VENDOR;
</div>
</dd>
</dl>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_LANG {#ae79c6bb67656cc6eebafd3ca9591adf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_LANG(ID, NAME, LOWER_BOUND, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_LANG_##NAME:                                                         \
    return LOWER_BOUND;
</div>
</dd>
</dl>

<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_LLE(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_LLE_##NAME:                                                          \
    return "DW_LLE_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_LNAME(ID, NAME, DESC, LOWER_BOUND)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_LNAME_##NAME:                                                        \
    return <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>;
</div>
</dd>
</dl>

<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_LNE(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_LNE_##NAME:                                                          \
    return "DW_LNE_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_LNS(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_LNS_##NAME:                                                          \
    return "DW_LNS_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_MACRO(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_MACRO_##NAME:                                                        \
    return "DW_MACRO_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_MACRO {#ac09375db4d0510e2826556d10f4592f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_MACRO(ID, NAME)&nbsp;&nbsp;&nbsp;.Case("DW_MACRO_" #NAME, ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_MACRO_GNU(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_MACRO_GNU_##NAME:                                                    \
    return "DW_MACRO_GNU_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_OP(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_OP_##NAME:                                                           \
    return "DW_OP_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_OP {#ad122873d9dbf4cd0d4c74356fb71d3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_OP(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;  .Case("DW_OP_" #NAME, DW_OP_##NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_OP {#a525f33dfb48b1f49b007789ff4fb3867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_OP(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_OP_##NAME:                                                           \
    return VERSION;
</div>
</dd>
</dl>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_OP {#aa6ac3f1099cf151f5803a4428f1b8a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_OP(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_OP_##NAME:                                                           \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (OPERANDS == -1)                                                        \
      return std::nullopt;                                                     \
    return OPERANDS;
</div>
</dd>
</dl>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_OP {#a3dde6ced67c7e78e7e79b749d7ef6141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_OP(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_OP_##NAME:                                                           \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (ARITY == -1)                                                           \
      return std::nullopt;                                                     \
    return ARITY;
</div>
</dd>
</dl>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_OP {#aef0c23307ca40b131eaf8784e9086acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_OP(ID, NAME, OPERANDS, ARITY, VERSION, VENDOR)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_OP_##NAME:                                                           \
    return DWARF_VENDOR_##VENDOR;
</div>
</dd>
</dl>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_OP_LLVM_USEROP(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_OP_LLVM_##NAME:                                                      \
    return "DW_OP_LLVM_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_OP\_LLVM\_USEROP {#abaf593e36a87908fda806256e222ac77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_OP_LLVM_USEROP(ID, NAME)&nbsp;&nbsp;&nbsp;.Case(#NAME, DW_OP_LLVM_##NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_RLE(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_RLE_##NAME:                                                          \
    return "DW_RLE_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_RLE {#aee18baf47f2a4df665dd9c224079ca86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_RLE(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_RLE_##NAME:                                                          \
    return "DW_RLE_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
    return "DW_TAG_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_TAG(ID, NAME, VERSION, VENDOR, KIND)&nbsp;&nbsp;&nbsp;  .Case("DW_TAG_" #NAME, DW_TAG_##NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_TAG {#a785882b403a247f28125e59bfdc7ad2e}

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
    return VERSION;
</div>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_TAG {#a2de1f57ad11f9fa2f98f88184564f6a8}

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
    return DWARF_VENDOR_##VENDOR;
</div>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_UT(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_UT_##NAME:                                                           \
    return "DW_UT_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

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
<td class="doxyMemberName">#define HANDLE_DW_VIRTUALITY(ID, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case DW_VIRTUALITY_##NAME:                                                   \
    return "DW_VIRTUALITY_" #NAME;
</div>
</dd>
</dl>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### HANDLE\_DW\_VIRTUALITY {#a7b6c3be33c955031aa4b30004d4b7d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_DW_VIRTUALITY(ID, NAME)&nbsp;&nbsp;&nbsp;  .Case("DW_VIRTUALITY_" #NAME, DW_VIRTUALITY_##NAME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### SELECT\_AARCH64 {#a781f991b2c23372223e057b11b00231c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SELECT_AARCH64&nbsp;&nbsp;&nbsp;(Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a6d5df0cfd7a0b0c0854555554396efd9">llvm::Triple::aarch64_be</a> || Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### SELECT\_MIPS64 {#a67588d848127735cc4123d1cfec95c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SELECT_MIPS64&nbsp;&nbsp;&nbsp;Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">llvm::Triple::mips64</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### SELECT\_SPARC {#a3f4c1d3ee9db2a3046eeeb971b854a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SELECT_SPARC&nbsp;&nbsp;&nbsp;(Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ebafd1adc05a751215ae959f2891752">llvm::Triple::sparc</a> || Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a34e8fe940082d534b3957f06616c8227">llvm::Triple::sparcv9</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

### SELECT\_X86 {#a09b9e0da0ce0a5a1f08eb0855169b934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SELECT_X86&nbsp;&nbsp;&nbsp;(Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> || Arch == <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp">Dwarf.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
