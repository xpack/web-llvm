---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineregisterinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineRegisterInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> - Keep track of information for virtual and physical registers, including vreg register classes, use/def chains for registers, etc. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineRegisterInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9feaf69938609dc2a42a69d719a5d3f9">reg_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-iterator">defusechain_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reg_iterator/reg_begin/reg_end - Walk all defs and uses of the specified register. <a href="#a9feaf69938609dc2a42a69d719a5d3f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29b0f94f5dfe6f242b99eed1b65fb7d">reg_instr_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reg_instr_iterator/reg_instr_begin/reg_instr_end - Walk all defs and uses of the specified register, stepping by <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#ac29b0f94f5dfe6f242b99eed1b65fb7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247e95f4e68e0f6e43706807dfec288f">reg_bundle_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reg_bundle_iterator/reg_bundle_begin/reg_bundle_end - Walk all defs and uses of the specified register, stepping by bundle. <a href="#a247e95f4e68e0f6e43706807dfec288f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9587e60caca87452c41d6d610a047b19">reg_nodbg_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-iterator">defusechain_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reg_nodbg_iterator/reg_nodbg_begin/reg_nodbg_end - Walk all defs and uses of the specified register, skipping those marked as Debug. <a href="#a9587e60caca87452c41d6d610a047b19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcde8d5fc0b4fa2b11d258d1bd0a8fc6">reg_instr_nodbg_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reg_instr_nodbg_iterator/reg_instr_nodbg_begin/reg_instr_nodbg_end - Walk all defs and uses of the specified register, stepping by <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, skipping those marked as Debug. <a href="#afcde8d5fc0b4fa2b11d258d1bd0a8fc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d23d76e9f093bb09fa9bf20ff663d2">reg_bundle_nodbg_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reg_bundle_nodbg_iterator/reg_bundle_nodbg_begin/reg_bundle_nodbg_end - Walk all defs and uses of the specified register, stepping by bundle, skipping those marked as Debug. <a href="#a02d23d76e9f093bb09fa9bf20ff663d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd337bcbe531ea8c9ed6fa1c6999d10">def_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-iterator">defusechain_iterator</a>&lt; false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>def_iterator/def_begin/def_end - Walk all defs of the specified register. <a href="#a9bd337bcbe531ea8c9ed6fa1c6999d10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fce27fffe1304645b8734cc95ddde17">def_instr_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>def_instr_iterator/def_instr_begin/def_instr_end - Walk all defs of the specified register, stepping by MachineInst. <a href="#a1fce27fffe1304645b8734cc95ddde17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56b56deb99e1234dfb6f1bf2994a1d1">def_bundle_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>def_bundle_iterator/def_bundle_begin/def_bundle_end - Walk all defs of the specified register, stepping by bundle. <a href="#ab56b56deb99e1234dfb6f1bf2994a1d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469fa77d5399d046de268afe306a700c">use_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-iterator">defusechain_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>use_iterator/use_begin/use_end - Walk all uses of the specified register. <a href="#a469fa77d5399d046de268afe306a700c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29839970b744a5cf56a82b62dbf93f99">use_instr_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>use_instr_iterator/use_instr_begin/use_instr_end - Walk all uses of the specified register, stepping by <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#a29839970b744a5cf56a82b62dbf93f99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ad443031e43628460482d909e3c78b">use_bundle_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>use_bundle_iterator/use_bundle_begin/use_bundle_end - Walk all uses of the specified register, stepping by bundle. <a href="#a19ad443031e43628460482d909e3c78b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86266d870f45f819e901f7095c17771">use_nodbg_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-iterator">defusechain_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>use_nodbg_iterator/use_nodbg_begin/use_nodbg_end - Walk all uses of the specified register, skipping those marked as Debug. <a href="#ad86266d870f45f819e901f7095c17771">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68aafc54b240b10f9dd589105a60d4e6">use_instr_nodbg_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>use_instr_nodbg_iterator/use_instr_nodbg_begin/use_instr_nodbg_end - Walk all uses of the specified register, stepping by <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, skipping those marked as Debug. <a href="#a68aafc54b240b10f9dd589105a60d4e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb28dfbb5ac4fbebd607a82fca21b73a">use_bundle_nodbg_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/defusechain-instr-iterator">defusechain_instr_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, false, false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>use_bundle_nodbg_iterator/use_bundle_nodbg_begin/use_bundle_nodbg_end - Walk all uses of the specified register, stepping by bundle, skipping those marked as Debug. <a href="#acb28dfbb5ac4fbebd607a82fca21b73a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c7b5ec2dee232169364913334f125c">livein_iterator</a> = std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &gt;::const_iterator</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e2e47fa8d67b1463549fa46bc44a69">VRegToTypeMap</a> = <a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool, bool, bool, bool, bool, bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6aee9b8f6b0a4a4c26901e271fa6dfa7">defusechain_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool, bool, bool, bool, bool, bool&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b000c853733de927f22652f954eca68">defusechain_instr_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e736a38ebafb662ddd8645d83a1d534">MachineRegisterInfo</a> (MachineFunction *MF)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac451b8ac7ac62bfe24225bfddeb35943">MachineRegisterInfo</a> (const MachineRegisterInfo &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f7b4a4d3bc5d9c524083b7cea0649ac">operator=</a> (const MachineRegisterInfo &amp;)=delete</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6208e23829aa84a5e95a1034c68c2fd6">resetDelegate</a> (Delegate *delegate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff1430f9e38299f37b3ce2b84d5b2d8">addDelegate</a> (Delegate *delegate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8694a1d461a5b2c58bd83bf50c9f46f">noteNewVirtualRegister</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc037e4e3484a814f8258868db79c758">noteCloneVirtualRegister</a> (Register NewReg, Register SrcReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9114705d2ebd07b743776bb9288e0e93">getMF</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86dd1b4ce6ff2d4a0b4593c5f7b2a3fd">isSSA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035f850aa2492716906dbb0610e98c90">leaveSSA</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218bf4a49a8808ebb854ec9b89907904">tracksLiveness</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tracksLiveness - Returns true when tracking register liveness accurately. <a href="#a218bf4a49a8808ebb854ec9b89907904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721b3ae1a20e295cc4f1143958ad3884">invalidateLiveness</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>invalidateLiveness - Indicates that register liveness is no longer being tracked accurately. <a href="#a721b3ae1a20e295cc4f1143958ad3884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2602cf77af82396115293302557ee0">shouldTrackSubRegLiveness</a> (const TargetRegisterClass &amp;RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if liveness for register class <span class="doxyComputerOutput">RC</span> should be tracked at the subregister level. <a href="#a7f2602cf77af82396115293302557ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4214f202c6a3b5b3933489a6edc49b6b">shouldTrackSubRegLiveness</a> (Register VReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ad9eedacb98923ab00074ec4760db2">subRegLivenessEnabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3076649c65eeacac14b0aa8eaa75bcdf">isUpdatedCSRsInitialized</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the updated CSR list was initialized and false otherwise. <a href="#a3076649c65eeacac14b0aa8eaa75bcdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3dfee03e12575026fa0a0461348a756">disableCalleeSavedRegister</a> (MCRegister Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disables the register from the list of CSRs. <a href="#aa3dfee03e12575026fa0a0461348a756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae9c5d17b40aa7be0189dd4f12dc315">getCalleeSavedRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns list of callee saved registers. <a href="#a8ae9c5d17b40aa7be0189dd4f12dc315">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaefaeb20cd3228ca22ecaff2fa385f9c">setCalleeSavedRegs</a> (ArrayRef&lt; MCPhysReg &gt; CSRs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the updated Callee Saved Registers list. <a href="#aaefaeb20cd3228ca22ecaff2fa385f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7f7e5eb5b55add81ed8fe39ac83b9c2">addRegOperandToUseList</a> (MachineOperand *MO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add MO to the linked list of operands for its register. <a href="#af7f7e5eb5b55add81ed8fe39ac83b9c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6bca2d194dea4aa5634cf5c394ebdc">removeRegOperandFromUseList</a> (MachineOperand *MO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove MO from its use-def list. <a href="#aea6bca2d194dea4aa5634cf5c394ebdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557ce2bfb3c946e43d65d750b2537987">moveOperands</a> (MachineOperand *Dst, MachineOperand *Src, unsigned NumOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move NumOps operands from Src to Dst, updating use-def lists as needed. <a href="#a557ce2bfb3c946e43d65d750b2537987">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a015233fe94a42e2294533334811ab899">verifyUseList</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the sanity of the use list for Reg. <a href="#a015233fe94a42e2294533334811ab899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fa9d44c84f7cadd81bf4758a22e1e9">verifyUseLists</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the use list of all registers. <a href="#a12fa9d44c84f7cadd81bf4758a22e1e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9feaf69938609dc2a42a69d719a5d3f9">reg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e9e89a17faecbca7d2409bf9817973e">reg_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a9feaf69938609dc2a42a69d719a5d3f9">reg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ee456cc6716cfbc16261e544100b12">reg_operands</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac29b0f94f5dfe6f242b99eed1b65fb7d">reg_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29dbcf8b92514fc55ff83db9312dcec4">reg_instr_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ac29b0f94f5dfe6f242b99eed1b65fb7d">reg_instr_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7bc06ec30359044cffdc3ccd58bfacf">reg_instructions</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a247e95f4e68e0f6e43706807dfec288f">reg_bundle_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7bac2504c6f8f8bf191f3d919426095">reg_bundle_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a247e95f4e68e0f6e43706807dfec288f">reg_bundle_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e05a48717dda8a0ca99449587367660">reg_bundles</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfd94e60d64656d8b19f2ea69bb02af">reg_empty</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reg_empty - Return true if there are no instructions using or defining the specified register (it may be live-in). <a href="#aecfd94e60d64656d8b19f2ea69bb02af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9587e60caca87452c41d6d610a047b19">reg_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a5fd48b56cb883a30104fd811fd8c4">reg_nodbg_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a9587e60caca87452c41d6d610a047b19">reg_nodbg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac055593361bdcb9d0093f0881ce7f286">reg_nodbg_operands</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afcde8d5fc0b4fa2b11d258d1bd0a8fc6">reg_instr_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae43ef10e056198d73d7c688d0649c9b2">reg_instr_nodbg_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#afcde8d5fc0b4fa2b11d258d1bd0a8fc6">reg_instr_nodbg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae916811c548f67c9ed178fa8a38ac7f1">reg_nodbg_instructions</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a02d23d76e9f093bb09fa9bf20ff663d2">reg_bundle_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c62f1e9ddcab1cde851a3df8de377b">reg_bundle_nodbg_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a02d23d76e9f093bb09fa9bf20ff663d2">reg_bundle_nodbg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52760341a18bcab24705161c498aa6f5">reg_nodbg_bundles</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a666dc30b9326da6b9e69740a241df89d">reg_nodbg_empty</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reg_nodbg_empty - Return true if the only instructions using or defining Reg are Debug instructions. <a href="#a666dc30b9326da6b9e69740a241df89d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9bd337bcbe531ea8c9ed6fa1c6999d10">def_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c15f3294c62d7590bb98e4d08ddeef">def_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a9bd337bcbe531ea8c9ed6fa1c6999d10">def_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c6432877c30fca6601db52f92573998">def_operands</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1fce27fffe1304645b8734cc95ddde17">def_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d327d7e53eaaaf9bb8cbac86c819ab2">def_instr_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a1fce27fffe1304645b8734cc95ddde17">def_instr_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415a4642beaee4a3156251faaacab646">def_instructions</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab56b56deb99e1234dfb6f1bf2994a1d1">def_bundle_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa02bb7124c3907948df9957bed1e9b3">def_bundle_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab56b56deb99e1234dfb6f1bf2994a1d1">def_bundle_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad269c6964062a546ea51482abf030796">def_bundles</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f95077d52fb7c8cd08ce6338b107bcf">def_empty</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>def_empty - Return true if there are no instructions defining the specified register (it may be live-in). <a href="#a5f95077d52fb7c8cd08ce6338b107bcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed28a3ee377374468972d5ba4e5cc15f">getVRegName</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c212d531fb6d95129ce86a5491bae06">insertVRegByName</a> (StringRef Name, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d46fa856af865f8c997f97596990ec">hasOneDef</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is exactly one operand defining the specified register. <a href="#a92d46fa856af865f8c997f97596990ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564aa23c9a5cf95820535f59182aedd4">getOneDef</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the defining operand if there is exactly one operand defining the specified register, otherwise nullptr. <a href="#a564aa23c9a5cf95820535f59182aedd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a469fa77d5399d046de268afe306a700c">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab87a00eb296cb02039f5a5580a54efd1">use_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a469fa77d5399d046de268afe306a700c">use_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade188fadae5a455fcc4bd8d70142851d">use_operands</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a29839970b744a5cf56a82b62dbf93f99">use_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489d8c4ed3ae8b1ca4f68e580b074bf1">use_instr_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a29839970b744a5cf56a82b62dbf93f99">use_instr_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1c2de27f8d8c4a7de72d6415952473f">use_instructions</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a19ad443031e43628460482d909e3c78b">use_bundle_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa40a0f52d1e6d37f89c8bfe4113e15b8">use_bundle_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a19ad443031e43628460482d909e3c78b">use_bundle_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef898731887fc99f3a5e62710cb5bade">use_bundles</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae86e9004476412ca754a7de4ee8a0c">use_empty</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>use_empty - Return true if there are no instructions using the specified register. <a href="#aeae86e9004476412ca754a7de4ee8a0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a600a2d410c09a9486e828ea34e5a9566">hasOneUse</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasOneUse - Return true if there is exactly one instruction using the specified register. <a href="#a600a2d410c09a9486e828ea34e5a9566">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad86266d870f45f819e901f7095c17771">use_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ccda750131c296a86bd6dc10331a77">use_nodbg_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ad86266d870f45f819e901f7095c17771">use_nodbg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4361906d7698e8b1a912f6affc8e9151">use_nodbg_operands</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a68aafc54b240b10f9dd589105a60d4e6">use_instr_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741b5105cca6e98538c79acf275ca733">use_instr_nodbg_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a68aafc54b240b10f9dd589105a60d4e6">use_instr_nodbg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1a48aa3d3155a0e942c785932d9723">use_nodbg_instructions</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acb28dfbb5ac4fbebd607a82fca21b73a">use_bundle_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a755b516aa2acc499e777c112a93a9f2f">use_bundle_nodbg_begin</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#acb28dfbb5ac4fbebd607a82fca21b73a">use_bundle_nodbg_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa433099910dc844bc8466933779e58">use_nodbg_bundles</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea277721b4e63804715a62de87e9a72">use_nodbg_empty</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>use_nodbg_empty - Return true if there are no non-Debug instructions using the specified register. <a href="#a4ea277721b4e63804715a62de87e9a72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01bf72631b0bc836a8c07fe840b13233">hasOneNonDBGUse</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasOneNonDBGUse - Return true if there is exactly one non-Debug use of the specified register. <a href="#a01bf72631b0bc836a8c07fe840b13233">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dfb8467bcaf53e7e0215aa831985de6">hasOneNonDBGUser</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasOneNonDBGUse - Return true if there is exactly one non-Debug instruction using the specified register. <a href="#a7dfb8467bcaf53e7e0215aa831985de6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0d4a6526dc873f6af0b248247bc503">hasAtMostUserInstrs</a> (Register Reg, unsigned MaxUsers) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasAtMostUses - Return true if the given register has at most <span class="doxyComputerOutput">MaxUsers</span> non-debug user instructions. <a href="#a7a0d4a6526dc873f6af0b248247bc503">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af16c39ee36e4633f821b6820f8bd52ef">replaceRegWith</a> (Register FromReg, Register ToReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replaceRegWith - Replace all instances of FromReg with ToReg in the machine function. <a href="#af16c39ee36e4633f821b6820f8bd52ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40d954b9cf9ee8b545a78725f2549cba">getVRegDef</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getVRegDef - Return the machine instr that defines the specified virtual register or null if none is found. <a href="#a40d954b9cf9ee8b545a78725f2549cba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af988c2b4f62506108843a0fdc04b43a2">getUniqueVRegDef</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getUniqueVRegDef - Return the unique machine instr that defines the specified virtual register or null if none is found. <a href="#af988c2b4f62506108843a0fdc04b43a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3da9727b1d452d6dcab08fde547ab634">clearKillFlags</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearKillFlags - Iterate over all the uses of the given register and clear the kill flag from the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>. <a href="#a3da9727b1d452d6dcab08fde547ab634">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553593c083449cc4db546a757010a2f4">dumpUses</a> (Register RegNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe36a37a2974f73af12228bccbaef0b4">isConstantPhysReg</a> (MCRegister PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if PhysReg is unallocatable and constant throughout the function. <a href="#abe36a37a2974f73af12228bccbaef0b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/psetiterator">PSetIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1fe08378fadccbf77405721be835ae">getPressureSets</a> (Register RegUnit) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator over the pressure sets affected by the given physical or virtual register. <a href="#acc1fe08378fadccbf77405721be835ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b5ca1a1228655842826f4bad8c44c2">getRegClass</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register class of the specified virtual register. <a href="#a34b5ca1a1228655842826f4bad8c44c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa008940be15669d5b380a1423dae87c8">getRegClassOrNull</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register class of <span class="doxyComputerOutput">Reg</span>, or null if Reg has not been assigned a register class yet. <a href="#aa008940be15669d5b380a1423dae87c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5492997611db35edf27193fe170b4f06">getRegBank</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register bank of <span class="doxyComputerOutput">Reg</span>. <a href="#a5492997611db35edf27193fe170b4f06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a718b488ac3350a59380b5070f54061ca">getRegBankOrNull</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register bank of <span class="doxyComputerOutput">Reg</span>, or null if Reg has not been assigned a register bank or has been assigned a register class. <a href="#a718b488ac3350a59380b5070f54061ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a0f1def99add5e4273e839bf70f3e79ed">RegClassOrRegBank</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fd10e1bf2e5ffae96be5b2cef4d17af">getRegClassOrRegBank</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register bank or register class of <span class="doxyComputerOutput">Reg</span>. <a href="#a4fd10e1bf2e5ffae96be5b2cef4d17af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965a15cef77a97f0e17f9f26fd5be53e">setRegClass</a> (Register Reg, const TargetRegisterClass *RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setRegClass - Set the register class of the specified virtual register. <a href="#a965a15cef77a97f0e17f9f26fd5be53e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81763ced27ec9b0c42f8848f4ebe5bd1">setRegBank</a> (Register Reg, const RegisterBank &amp;RegBank)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the register bank to <span class="doxyComputerOutput">RegBank</span> for <span class="doxyComputerOutput">Reg</span>. <a href="#a81763ced27ec9b0c42f8848f4ebe5bd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ada07773b69dd6a5e99d47fe368d313">setRegClassOrRegBank</a> (Register Reg, const RegClassOrRegBank &amp;RCOrRB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85285685fc46db3f2b3b0bf90bf9184">constrainRegClass</a> (Register Reg, const TargetRegisterClass *RC, unsigned MinNumRegs=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>constrainRegClass - Constrain the register class of the specified virtual register to be a common subclass of RC and the current register class, but only if the new class has at least MinNumRegs registers. <a href="#ad85285685fc46db3f2b3b0bf90bf9184">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd28b31b311bb88a92825ed630dd4269">constrainRegAttrs</a> (Register Reg, Register ConstrainingReg, unsigned MinNumRegs=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constrain the register class or the register bank of the virtual register <span class="doxyComputerOutput">Reg</span> (and low-level type) to be a common subclass or a common bank of both registers provided respectively (and a common low-level type). <a href="#acd28b31b311bb88a92825ed630dd4269">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2786870c4807261593ac11e734db2f76">recomputeRegClass</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>recomputeRegClass - Try to find a legal super-class of Reg's register class that still satisfies the constraints from the instructions using Reg. <a href="#a2786870c4807261593ac11e734db2f76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c77792a06583e0fe7a0379ad94a2809">createVirtualRegister</a> (const TargetRegisterClass *RegClass, StringRef Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createVirtualRegister - Create and return a new virtual register in the function with the specified register class. <a href="#a5c77792a06583e0fe7a0379ad94a2809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">VRegAttrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d657bbeeb927506546fd529ebb0784b">getVRegAttrs</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns register class or bank and low level type of <span class="doxyComputerOutput">Reg</span>. <a href="#a1d657bbeeb927506546fd529ebb0784b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1a32c582ac944fc6e071f479ce6a08">createVirtualRegister</a> (VRegAttrs RegAttr, StringRef Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and return a new virtual register in the function with the specified register attributes(register class or bank and low level type). <a href="#a5a1a32c582ac944fc6e071f479ce6a08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac27689339b95eeb89bc9e40aa1e394f9">cloneVirtualRegister</a> (Register VReg, StringRef Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and return a new virtual register in the function with the same attributes as the given register. <a href="#ac27689339b95eeb89bc9e40aa1e394f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc0a32516ce31f495b440d47287028b">getType</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the low-level type of <span class="doxyComputerOutput">Reg</span> or <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>{} if Reg is not a generic (target independent) virtual register. <a href="#a5dc0a32516ce31f495b440d47287028b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d65688eb3408e2f26bf75b83a1b3448">setType</a> (Register VReg, LLT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the low-level type of <span class="doxyComputerOutput">VReg</span> to <span class="doxyComputerOutput">Ty</span>. <a href="#a8d65688eb3408e2f26bf75b83a1b3448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9694f2906cfe1d6d35bbe6742c67dff0">createGenericVirtualRegister</a> (LLT Ty, StringRef Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and return a new generic virtual register with low-level type <span class="doxyComputerOutput">Ty</span>. <a href="#a9694f2906cfe1d6d35bbe6742c67dff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d53825c081045b4e59ed65576130ec">clearVirtRegTypes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all types associated to virtual registers (after instruction selection and constraining of all generic virtual registers). <a href="#a99d53825c081045b4e59ed65576130ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ed74de0e85d45f32fe8aca572f0c63d">createIncompleteVirtualRegister</a> (StringRef Name="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new virtual register that has no register class, register bank or size assigned yet. <a href="#a7ed74de0e85d45f32fe8aca572f0c63d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73582bbbc71758dcac70cd8c56210e4">getNumVirtRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNumVirtRegs - Return the number of virtual registers created. <a href="#ae73582bbbc71758dcac70cd8c56210e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2e403e3e1f758b87c25302090c96c2">clearVirtRegs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearVirtRegs - Remove all virtual registers (after physreg assignment). <a href="#a7e2e403e3e1f758b87c25302090c96c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e27d94e24a9bc2d6c7d719bed9637e3">setRegAllocationHint</a> (Register VReg, unsigned Type, Register PrefReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setRegAllocationHint - Specify a register allocation hint for the specified virtual register. <a href="#a8e27d94e24a9bc2d6c7d719bed9637e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc82dfed5cd6e963934d2d0f8d6e7272">addRegAllocationHint</a> (Register VReg, Register PrefReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addRegAllocationHint - Add a register allocation hint to the hints vector for VReg. <a href="#abc82dfed5cd6e963934d2d0f8d6e7272">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18b5ef8a2c55e42b08affe5d0323e12">setSimpleHint</a> (Register VReg, Register PrefReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify the preferred (target independent) register allocation hint for the specified virtual register. <a href="#aa18b5ef8a2c55e42b08affe5d0323e12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7156041a724bb8620c6fe72d241b09">clearSimpleHint</a> (Register VReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc629292d5cf14604e9b35b42ac4706">getRegAllocationHint</a> (Register VReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRegAllocationHint - Return the register allocation hint for the specified virtual register. <a href="#a8bc629292d5cf14604e9b35b42ac4706">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021a3cabd072c6984bf30b0f8a3fc0a6">getSimpleHint</a> (Register VReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSimpleHint - same as getRegAllocationHint except it will only return a target independent hint. <a href="#a021a3cabd072c6984bf30b0f8a3fc0a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 4 &gt; &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae2826c4edd4248c272fa91a0a3e80f6">getRegAllocationHints</a> (Register VReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRegAllocationHints - Return a reference to the vector of all register allocation hints for VReg. <a href="#aae2826c4edd4248c272fa91a0a3e80f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213df9204c030effa8d56a05564997a7">markUsesInDebugValueAsUndef</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>markUsesInDebugValueAsUndef - Mark every DBG_VALUE referencing the specified register as undefined which causes the DBG_VALUE to be deleted during <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables">LiveDebugVariables</a> analysis. <a href="#a213df9204c030effa8d56a05564997a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af392a602d843857153b656823dad4d08">updateDbgUsersToReg</a> (MCRegister OldReg, MCRegister NewReg, ArrayRef&lt; MachineInstr * &gt; Users) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateDbgUsersToReg - Update a collection of debug instructions to refer to the designated register. <a href="#af392a602d843857153b656823dad4d08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a209ffefa8ca1df76b99fe3c2e2cc4">isPhysRegModified</a> (MCRegister PhysReg, bool SkipNoReturnDef=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified register is modified in this function. <a href="#af2a209ffefa8ca1df76b99fe3c2e2cc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd23983bb9fb4af65e27b56cc506edbc">isPhysRegUsed</a> (MCRegister PhysReg, bool SkipRegMaskTest=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified register is modified or read in this function. <a href="#afd23983bb9fb4af65e27b56cc506edbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac386aa863d0dc665f4b7da757f60054b">addPhysRegsUsedFromRegMask</a> (const uint32_t *RegMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addPhysRegsUsedFromRegMask - Mark any registers not in RegMask as used. <a href="#ac386aa863d0dc665f4b7da757f60054b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24866efe4b1cbbfe4532330064dbef04">getUsedPhysRegsMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30815e557d36373557a052fbf84263c7">freezeReservedRegs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>freezeReservedRegs - Called by the register allocator to freeze the set of reserved registers before allocation begins. <a href="#a30815e557d36373557a052fbf84263c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab490792bb2387856aeb83267a1bd55d2">reserveReg</a> (MCRegister PhysReg, const TargetRegisterInfo *TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reserveReg – Mark a register as reserved so checks like isAllocatable will not suggest using it. <a href="#ab490792bb2387856aeb83267a1bd55d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ecfe2828dd348fc0b23c8d1d73c4b75">reservedRegsFrozen</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reservedRegsFrozen - Returns true after <a href="#a30815e557d36373557a052fbf84263c7">freezeReservedRegs()</a> was called to ensure the set of reserved registers stays constant. <a href="#a5ecfe2828dd348fc0b23c8d1d73c4b75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96bb3ab76b2a615f1fac4fdb8105095a">canReserveReg</a> (MCRegister PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canReserveReg - Returns true if PhysReg can be used as a reserved register. <a href="#a96bb3ab76b2a615f1fac4fdb8105095a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a78e01b4db3aacb72ddc22debed3269">getReservedRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getReservedRegs - Returns a reference to the frozen set of reserved registers. <a href="#a5a78e01b4db3aacb72ddc22debed3269">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ca7cff9e929ba372da9780fdd44b02">isReserved</a> (MCRegister PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReserved - Returns true when PhysReg is a reserved register. <a href="#a53ca7cff9e929ba372da9780fdd44b02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7de8e2cf4949a58445f955d4d98caa">isReservedRegUnit</a> (unsigned Unit) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true when the given register unit is considered reserved. <a href="#ada7de8e2cf4949a58445f955d4d98caa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f39116ef8979cff64ea1c666228e7d9">isAllocatable</a> (MCRegister PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isAllocatable - Returns true when PhysReg belongs to an allocatable register class and it hasn't been reserved. <a href="#a7f39116ef8979cff64ea1c666228e7d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac889107f09b05137fd5964343a935a6c">addLiveIn</a> (MCRegister Reg, Register vreg=Register())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addLiveIn - Add the specified register as a live-in. <a href="#ac889107f09b05137fd5964343a935a6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a66c7b5ec2dee232169364913334f125c">livein_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade38103c28d56389d7848497aae70bba">livein_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a66c7b5ec2dee232169364913334f125c">livein_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c135f0c45228e88b1927c069fc1d88">livein_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c9eecf2b6aa6f212610a87813955328">livein_empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c5924111ebe86dd174fe793a52f327">liveins</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640f34062e7189756ce67e60d5dfd629">isLiveIn</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8826883c66d420e0b7a9dd216eeaa388">getLiveInPhysReg</a> (Register VReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLiveInPhysReg - If VReg is a live-in virtual register, return the corresponding live-in physical register. <a href="#a8826883c66d420e0b7a9dd216eeaa388">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc1aea4b14234362915bdb5c776573f">getLiveInVirtReg</a> (MCRegister PReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLiveInVirtReg - If PReg is a live-in physical register, return the corresponding live-in virtual register. <a href="#a9cc1aea4b14234362915bdb5c776573f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ddc08d3e0ee02a2a8fb36fb4c8ac18">EmitLiveInCopies</a> (MachineBasicBlock *EntryMBB, const TargetRegisterInfo &amp;TRI, const TargetInstrInfo &amp;TII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitLiveInCopies - Emit copies to initialize livein virtual registers into the given entry block. <a href="#a44ddc08d3e0ee02a2a8fb36fb4c8ac18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7e720f69b70ef3973d672936a9fa0ec">getMaxLaneMaskForVReg</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a mask covering all bits that can appear in lane masks of subregisters of the virtual register <span class="doxyComputerOutput">Reg</span>. <a href="#ab7e720f69b70ef3973d672936a9fa0ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee034baf5dd4348fc2ae26d222efaccd">getRegUseDefListHead</a> (Register RegNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRegUseDefListHead - Return the head pointer for the register use/def list for the specified virtual or physical register. <a href="#aee034baf5dd4348fc2ae26d222efaccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a029389fb7ae06438caae8f45a504c04d">getRegUseDefListHead</a> (Register RegNo) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd84ad3ee1982df28b9edf9bd627ee2">MF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/delegate">Delegate</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58db0f1b478a5edc489733c504ff2cc">TheDelegates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b5bc21b71692d9561b10434bdd140f5">TracksSubRegLiveness</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if subregister liveness is tracked. <a href="#a7b5bc21b71692d9561b10434bdd140f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a0f1def99add5e4273e839bf70f3e79ed">RegClassOrRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * &gt;, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30dba9292bb7a7ac6128317a4c6c323c">VRegInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> - Information we keep for each virtual register. <a href="#a30dba9292bb7a7ac6128317a4c6c323c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; std::string, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca2c0f5bd9620e6df335c600a20199a">VReg2Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map for recovering vreg name from vreg number. <a href="#a5ca2c0f5bd9620e6df335c600a20199a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace7c64158e3b8e757b201d4ec782dba">VRegNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a> that is used to unique vreg names. <a href="#aace7c64158e3b8e757b201d4ec782dba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd58d34022c593e7063d85383cff6c8">IsUpdatedCSRsInitialized</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The flag is true upon <span class="doxyComputerOutput">UpdatedCSRs</span> initialization and false otherwise. <a href="#a4bd58d34022c593e7063d85383cff6c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386323124a081d9eeae17685e5837a44">UpdatedCSRs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains the updated callee saved register list. <a href="#a386323124a081d9eeae17685e5837a44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 4 &gt; &gt;, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386e42aede99726bf2781edb21631f36">RegAllocHints</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegAllocHints - This vector records register allocation hints for virtual registers. <a href="#a386e42aede99726bf2781edb21631f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3fe5a3cf1b78fbe96222ce75371ad3">PhysRegUseDefLists</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PhysRegUseDefLists - This is an array of the head of the use/def list for physical registers. <a href="#a8d3fe5a3cf1b78fbe96222ce75371ad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c694e699d61413b7206005a63d2134">UsedPhysRegMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UsedPhysRegMask - Additional used physregs including aliases. <a href="#a90c694e699d61413b7206005a63d2134">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875f5fc41819ee3a88e6ac8097f030ee">ReservedRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReservedRegs - This is a bit vector of reserved registers. <a href="#a875f5fc41819ee3a88e6ac8097f030ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">VRegToTypeMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a28529fc3eb468ffe69d93d46499d6">VRegToType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map generic virtual registers to their low-level type. <a href="#a82a28529fc3eb468ffe69d93d46499d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90714962014be77e5fca78fa121bd0e8">LiveIns</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the physical registers that are live in to the function. <a href="#a90714962014be77e5fca78fa121bd0e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a9feaf69938609dc2a42a69d719a5d3f9">reg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d8edf72c1d3e14e4d2396b98e07ad72">reg_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ac29b0f94f5dfe6f242b99eed1b65fb7d">reg_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45911f3aacb9b7ea62d1fa8fc8180039">reg_instr_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a247e95f4e68e0f6e43706807dfec288f">reg_bundle_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05bea8bf7513acba82ca339c74de2de">reg_bundle_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a9587e60caca87452c41d6d610a047b19">reg_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728707da8d5c6832316ff91231f3c2ef">reg_nodbg_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#afcde8d5fc0b4fa2b11d258d1bd0a8fc6">reg_instr_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a1144eb9d753b6b682a933aa3f8f9f">reg_instr_nodbg_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a02d23d76e9f093bb09fa9bf20ff663d2">reg_bundle_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94275a1edd38ff90ce524665a268d71e">reg_bundle_nodbg_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a9bd337bcbe531ea8c9ed6fa1c6999d10">def_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa21b132afc12ed3cead7a879506f277a">def_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a1fce27fffe1304645b8734cc95ddde17">def_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54dd0a5ebf7dbe5aab5fe51979356645">def_instr_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ab56b56deb99e1234dfb6f1bf2994a1d1">def_bundle_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595a7a24c293a79d1f19a3ae2337bb49">def_bundle_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a469fa77d5399d046de268afe306a700c">use_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8347c6938efe4d9a4426b92ef57851e">use_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a29839970b744a5cf56a82b62dbf93f99">use_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a73104304bf1f9d344ad495283561b5">use_instr_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a19ad443031e43628460482d909e3c78b">use_bundle_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d9cb3eb3b146477bb4a708a246607be">use_bundle_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ad86266d870f45f819e901f7095c17771">use_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355ba266da19094cc0948311c431768e">use_nodbg_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a68aafc54b240b10f9dd589105a60d4e6">use_instr_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1fd76e39ba4dfa2c428df88bbc82c2">use_instr_nodbg_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#acb28dfbb5ac4fbebd607a82fca21b73a">use_bundle_nodbg_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacc6af82327a6f208f586e90cc48dbed">use_bundle_nodbg_end</a> ()</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14be32fb294c8c36086ff9d3f79cb6e6">getNextOperandForReg</a> (const MachineOperand *MO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next element in the use-def chain. <a href="#a14be32fb294c8c36086ff9d3f79cb6e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> - Keep track of information for virtual and physical registers, including vreg register classes, use/def chains for registers, etc.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### def\_bundle\_iterator {#ab56b56deb99e1234dfb6f1bf2994a1d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::def_bundle_iterator = 
      defusechain_instr_iterator&lt;false, true, false, false, false, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>def_bundle_iterator/def_bundle_begin/def_bundle_end - Walk all defs of the specified register, stepping by bundle.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### def\_instr\_iterator {#a1fce27fffe1304645b8734cc95ddde17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::def_instr_iterator = 
      defusechain_instr_iterator&lt;false, true, false, false, true, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>def_instr_iterator/def_instr_begin/def_instr_end - Walk all defs of the specified register, stepping by MachineInst.</p>

<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### def\_iterator {#a9bd337bcbe531ea8c9ed6fa1c6999d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::def_iterator = 
      defusechain_iterator&lt;false, true, false, true, false, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>def_iterator/def_begin/def_end - Walk all defs of the specified register.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### livein\_iterator {#a66c7b5ec2dee232169364913334f125c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::livein_iterator = 
      std::vector&lt;std::pair&lt;MCRegister,Register&gt;&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### reg\_bundle\_iterator {#a247e95f4e68e0f6e43706807dfec288f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::reg_bundle_iterator = 
      defusechain_instr_iterator&lt;true, true, false, false, false, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reg_bundle_iterator/reg_bundle_begin/reg_bundle_end - Walk all defs and uses of the specified register, stepping by bundle.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### reg\_bundle\_nodbg\_iterator {#a02d23d76e9f093bb09fa9bf20ff663d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::reg_bundle_nodbg_iterator = 
      defusechain_instr_iterator&lt;true, true, true, false, false, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reg_bundle_nodbg_iterator/reg_bundle_nodbg_begin/reg_bundle_nodbg_end - Walk all defs and uses of the specified register, stepping by bundle, skipping those marked as Debug.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### reg\_instr\_iterator {#ac29b0f94f5dfe6f242b99eed1b65fb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::reg_instr_iterator = 
      defusechain_instr_iterator&lt;true, true, false, false, true, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reg_instr_iterator/reg_instr_begin/reg_instr_end - Walk all defs and uses of the specified register, stepping by <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### reg\_instr\_nodbg\_iterator {#afcde8d5fc0b4fa2b11d258d1bd0a8fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::reg_instr_nodbg_iterator = 
      defusechain_instr_iterator&lt;true, true, true, false, true, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reg_instr_nodbg_iterator/reg_instr_nodbg_begin/reg_instr_nodbg_end - Walk all defs and uses of the specified register, stepping by <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, skipping those marked as Debug.</p>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### reg\_iterator {#a9feaf69938609dc2a42a69d719a5d3f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::reg_iterator = 
      defusechain_iterator&lt;true, true, false, true, false, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reg_iterator/reg_begin/reg_end - Walk all defs and uses of the specified register.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### reg\_nodbg\_iterator {#a9587e60caca87452c41d6d610a047b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::reg_nodbg_iterator = 
      defusechain_iterator&lt;true, true, true, true, false, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reg_nodbg_iterator/reg_nodbg_begin/reg_nodbg_end - Walk all defs and uses of the specified register, skipping those marked as Debug.</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### use\_bundle\_iterator {#a19ad443031e43628460482d909e3c78b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::use_bundle_iterator = 
      defusechain_instr_iterator&lt;true, false, false, false, false, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>use_bundle_iterator/use_bundle_begin/use_bundle_end - Walk all uses of the specified register, stepping by bundle.</p>

<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### use\_bundle\_nodbg\_iterator {#acb28dfbb5ac4fbebd607a82fca21b73a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::use_bundle_nodbg_iterator = 
      defusechain_instr_iterator&lt;true, false, true, false, false, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>use_bundle_nodbg_iterator/use_bundle_nodbg_begin/use_bundle_nodbg_end - Walk all uses of the specified register, stepping by bundle, skipping those marked as Debug.</p>

<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### use\_instr\_iterator {#a29839970b744a5cf56a82b62dbf93f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::use_instr_iterator = 
      defusechain_instr_iterator&lt;true, false, false, false, true, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>use_instr_iterator/use_instr_begin/use_instr_end - Walk all uses of the specified register, stepping by <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### use\_instr\_nodbg\_iterator {#a68aafc54b240b10f9dd589105a60d4e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::use_instr_nodbg_iterator = 
      defusechain_instr_iterator&lt;true, false, true, false, true, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>use_instr_nodbg_iterator/use_instr_nodbg_begin/use_instr_nodbg_end - Walk all uses of the specified register, stepping by <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, skipping those marked as Debug.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### use\_iterator {#a469fa77d5399d046de268afe306a700c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::use_iterator = 
      defusechain_iterator&lt;true, false, false, true, false, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>use_iterator/use_begin/use_end - Walk all uses of the specified register.</p>

<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### use\_nodbg\_iterator {#ad86266d870f45f819e901f7095c17771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::use_nodbg_iterator = 
      defusechain_iterator&lt;true, false, true, true, false, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>use_nodbg_iterator/use_nodbg_begin/use_nodbg_end - Walk all uses of the specified register, skipping those marked as Debug.</p>

<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### VRegToTypeMap {#a09e2e47fa8d67b1463549fa46bc44a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineRegisterInfo::VRegToTypeMap =  IndexedMap&lt;LLT, VirtReg2IndexFunctor&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### defusechain\_instr\_iterator {#a3b000c853733de927f22652f954eca68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class defusechain_instr_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### defusechain\_iterator {#a6aee9b8f6b0a4a4c26901e271fa6dfa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class defusechain_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineRegisterInfo() {#a3e736a38ebafb662ddd8645d83a1d534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo::MachineRegisterInfo (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp/#a8d8ceb9be198f4804583c7a65d838bdc">EnableSubRegLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#af946f316ed42f8b5eb99735a3b587ab5">llvm::MCRegisterInfo::getNumRegs</a> and <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>.</p>


<p>Referenced by <a href="#ac451b8ac7ac62bfe24225bfddeb35943">MachineRegisterInfo</a> and <a href="#a2f7b4a4d3bc5d9c524083b7cea0649ac">operator=</a>.</p>

</div>
</div>

### MachineRegisterInfo() {#ac451b8ac7ac62bfe24225bfddeb35943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineRegisterInfo::MachineRegisterInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="#a3e736a38ebafb662ddd8645d83a1d534">MachineRegisterInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a2f7b4a4d3bc5d9c524083b7cea0649ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo &amp; llvm::MachineRegisterInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="#a3e736a38ebafb662ddd8645d83a1d534">MachineRegisterInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDelegate() {#a8ff1430f9e38299f37b3ce2b84d5b2d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::addDelegate (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/delegate">Delegate</a> * delegate)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a5280c4cea74a327750a50fbbc7ca77d7">llvm::GCNTargetMachine::registerMachineRegisterInfoCallback</a>.</p>

</div>
</div>

### addLiveIn() {#ac889107f09b05137fd5964343a935a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::addLiveIn (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> vreg=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>())</td>
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

<p>addLiveIn - Add the specified register as a live-in.</p>


<p>Note that it is an error to add the same register to the same set more than once.</p>


<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a72971d5381ef59f4ea6c9b37e21f79be">addLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a2d1eb7b0207905141f6ddb1f228f3696">buildGitPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ace182ca668404b3d23cae8329d941ba4">llvm::MipsFunctionInfo::initGlobalBaseReg</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>.</p>

</div>
</div>

### addPhysRegsUsedFromRegMask() {#ac386aa863d0dc665f4b7da757f60054b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::addPhysRegsUsedFromRegMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * RegMask)</td>
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

<p>addPhysRegsUsedFromRegMask - Mark any registers not in RegMask as used.</p>


<p>This corresponds to the bit mask attached to register mask operands.</p>


<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### addRegAllocationHint() {#abc82dfed5cd6e963934d2d0f8d6e7272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::addRegAllocationHint (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PrefReg)</td>
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

<p>addRegAllocationHint - Add a register allocation hint to the hints vector for VReg.</p>

<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae73582bbbc71758dcac70cd8c56210e4">getNumVirtRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>

</div>
</div>

### addRegOperandToUseList() {#af7f7e5eb5b55add81ed8fe39ac83b9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::addRegOperandToUseList (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add MO to the linked list of operands for its register.</p>

<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>

</div>
</div>

### canReserveReg() {#a96bb3ab76b2a615f1fac4fdb8105095a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::canReserveReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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

<p>canReserveReg - Returns true if PhysReg can be used as a reserved register.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> register can be reserved before <a href="#a30815e557d36373557a052fbf84263c7">freezeReservedRegs()</a> is called.</p>


<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a> and <a href="#a5ecfe2828dd348fc0b23c8d1d73c4b75">reservedRegsFrozen</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a6e2d4106e3ee3d0463f29dea987d698f">llvm::MipsRegisterInfo::canRealignStack</a>.</p>

</div>
</div>

### clearKillFlags() {#a3da9727b1d452d6dcab08fde547ab634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::clearKillFlags (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clearKillFlags - Iterate over all the uses of the given register and clear the kill flag from the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>.</p>


<p>This function is used by optimization passes which extend register lifetimes and need only preserve conservative kill flag information.</p>


<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>Reference <a href="#ade188fadae5a455fcc4bd8d70142851d">use_operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand/#a9899e618878cac6bb75eafe4d46810f4">anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::convertToSDWA</a>.</p>

</div>
</div>

### clearSimpleHint() {#ada7156041a724bb8620c6fe72d241b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::clearSimpleHint (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
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



<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### clearVirtRegs() {#a7e2e403e3e1f758b87c25302090c96c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::clearVirtRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clearVirtRegs - Remove all virtual registers (after physreg assignment).</p>

<p>Declaration at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#ae73582bbbc71758dcac70cd8c56210e4">getNumVirtRegs</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="#aa7bc06ec30359044cffdc3ccd58bfacf">reg_instructions</a> and <a href="#a015233fe94a42e2294533334811ab899">verifyUseList</a>.</p>

</div>
</div>

### clearVirtRegTypes() {#a99d53825c081045b4e59ed65576130ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::clearVirtRegTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all types associated to virtual registers (after instruction selection and constraining of all generic virtual registers).</p>

<p>Declaration at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-resetmachinefunctionpass-cpp-/resetmachinefunction/#a1ca062be17e509ab43e062b6ccbed2e1">anonymous{ResetMachineFunctionPass.cpp}::ResetMachineFunction::runOnMachineFunction</a>.</p>

</div>
</div>

### cloneVirtualRegister() {#ac27689339b95eeb89bc9e40aa1e394f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineRegisterInfo::cloneVirtualRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create and return a new virtual register in the function with the same attributes as the given register.</p>

<p>Declaration at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#a7ed74de0e85d45f32fe8aca572f0c63d">createIncompleteVirtualRegister</a>, <a href="#a5dc0a32516ce31f495b440d47287028b">getType</a>, <a href="#adc037e4e3484a814f8258868db79c758">noteCloneVirtualRegister</a> and <a href="#a8d65688eb3408e2f26bf75b83a1b3448">setType</a>.</p>

</div>
</div>

### constrainRegAttrs() {#acd28b31b311bb88a92825ed630dd4269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::constrainRegAttrs (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ConstrainingReg, unsigned MinNumRegs=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constrain the register class or the register bank of the virtual register <span class="doxyComputerOutput">Reg</span> (and low-level type) to be a common subclass or a common bank of both registers provided respectively (and a common low-level type).</p>


<p>Do nothing if any of the attributes (classes, banks, or low-level types) of the registers are deemed incompatible, or if the resulting register will have a class smaller than before and of size less than <span class="doxyComputerOutput">MinNumRegs</span>. Return true if such register attributes exist, false otherwise.</p>



:::info
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this method instead of constrainRegClass and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a1cfd8b1df608cb89b0acb94d29d447b3">RegisterBankInfo::constrainGenericRegister</a> everywhere but <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> ISel / <a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> and GlobalISel's <a href="/web-llvm/docs/api/classes/llvm/instructionselect">InstructionSelect</a> pass respectively.</p>
:::


<p>Declaration at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad85285685fc46db3f2b3b0bf90bf9184">constrainRegClass</a>, <a href="#a4fd10e1bf2e5ffae96be5b2cef4d17af">getRegClassOrRegBank</a>, <a href="#a5dc0a32516ce31f495b440d47287028b">getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="#a5ada07773b69dd6a5e99d47fe368d313">setRegClassOrRegBank</a> and <a href="#a8d65688eb3408e2f26bf75b83a1b3448">setType</a>.</p>

</div>
</div>

### constrainRegClass() {#ad85285685fc46db3f2b3b0bf90bf9184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * MachineRegisterInfo::constrainRegClass (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned MinNumRegs=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>constrainRegClass - Constrain the register class of the specified virtual register to be a common subclass of RC and the current register class, but only if the new class has at least MinNumRegs registers.</p>


<p>Return the new register class, or NULL if no such class exists. This should only be used when the constraint is known to be trivial, like GR32 -&gt; GR32_NOSP. Beware of increasing register pressure.</p>



:::info
<p>Assumes that the register has a register class assigned. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a1cfd8b1df608cb89b0acb94d29d447b3">RegisterBankInfo::constrainGenericRegister</a> in GlobalISel's <a href="/web-llvm/docs/api/classes/llvm/instructionselect">InstructionSelect</a> pass and constrainRegAttrs in every other pass, including non-select passes of GlobalISel, instead.</p>
:::


<p>Declaration at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>Reference <a href="#a34b5ca1a1228655842826f4bad8c44c2">getRegClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="#acd28b31b311bb88a92825ed630dd4269">constrainRegAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### createGenericVirtualRegister() {#a9694f2906cfe1d6d35bbe6742c67dff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineRegisterInfo::createGenericVirtualRegister (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create and return a new generic virtual register with low-level type <span class="doxyComputerOutput">Ty</span>.</p>

<p>Declaration at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#a7ed74de0e85d45f32fe8aca572f0c63d">createIncompleteVirtualRegister</a>, <a href="#aa8694a1d461a5b2c58bd83bf50c9f46f">noteNewVirtualRegister</a> and <a href="#a8d65688eb3408e2f26bf75b83a1b3448">setType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af6aed1d3b2cf7133b73cf8bfa5122186">llvm::MachineIRBuilder::buildMaskLowPtrBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0f2bb4d63ad6914f3783967bf881a14b">llvm::MachineIRBuilder::materializePtrAdd</a>.</p>

</div>
</div>

### createIncompleteVirtualRegister() {#a7ed74de0e85d45f32fe8aca572f0c63d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineRegisterInfo::createIncompleteVirtualRegister (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a new virtual register that has no register class, register bank or size assigned yet.</p>


<p>This is only allowed to be used temporarily while constructing machine instructions. Most operations are undefined on an incomplete register until one of <a href="#a965a15cef77a97f0e17f9f26fd5be53e">setRegClass()</a>, <a href="#a81763ced27ec9b0c42f8848f4ebe5bd1">setRegBank()</a> or setSize() has been called on it.</p>


<p>Declaration at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#ae73582bbbc71758dcac70cd8c56210e4">getNumVirtRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a> and <a href="#a0c212d531fb6d95129ce86a5491bae06">insertVRegByName</a>.</p>


<p>Referenced by <a href="#ac27689339b95eeb89bc9e40aa1e394f9">cloneVirtualRegister</a>, <a href="#a9694f2906cfe1d6d35bbe6742c67dff0">createGenericVirtualRegister</a>, <a href="#a5c77792a06583e0fe7a0379ad94a2809">createVirtualRegister</a> and <a href="#a5a1a32c582ac944fc6e071f479ce6a08">createVirtualRegister</a>.</p>

</div>
</div>

### createVirtualRegister() {#a5c77792a06583e0fe7a0379ad94a2809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineRegisterInfo::createVirtualRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RegClass, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createVirtualRegister - Create and return a new virtual register in the function with the specified register class.</p>

<p>Declaration at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7ed74de0e85d45f32fe8aca572f0c63d">createIncompleteVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a68b1cbd38847abc3e56eca6df316d5a1">llvm::TargetRegisterClass::isAllocatable</a> and <a href="#aa8694a1d461a5b2c58bd83bf50c9f46f">noteNewVirtualRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a72971d5381ef59f4ea6c9b37e21f79be">addLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4280c0cdf83d31309a8ad8d0d6815e66">llvm::SPIRVGlobalRegistry::buildConstantSampler</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a27a80b2fc0f8820ecab9d99312bb4607">llvm::AArch64FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a6f318a4b1d38e66b324c0748304e60de">llvm::ARMBaseRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a1e101bcf68a4448908d194d220029861">llvm::SystemZRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a4c17381dc1cacb65f1dd6d31d15100e0">emitThumbRegPlusImmInReg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyfixbrtabledefaults-cpp-/#ab7b6f5214428c621e8b32582fd5efe62">anonymous{WebAssemblyFixBrTableDefaults.cpp}::fixBrTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a4f8c7b0497e80fd8c5028d2b564c0c3f">llvm::MipsFunctionInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a0d65d879a707f0fcaa221e60be3a1a54">llvm::SPIRVGlobalRegistry::getOrCreateGlobalVariableWithBinding</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ae27fd47ee099b4aba7fe2bc84be97ff8">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::improveSimpleJumpintoIf</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aa90550e5d59f68a547e28c8beeefb3ed">llvm::PPCRegisterInfo::lowerCRBitRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a38572a53736b568d95a5adc23bcd67f0">llvm::PPCRegisterInfo::lowerCRBitSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a7f3c8b41556bad389b00bd408c9b969f">llvm::PPCRegisterInfo::lowerCRRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a49453cd92df6e63d0c2c45e1d5ace04b">llvm::PPCRegisterInfo::lowerCRSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4d0bcb536bd3b6491c535f206275ad89">llvm::PPCRegisterInfo::lowerDynamicAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab2c246f45a8786eb5745c6cd9664d088">llvm::PPCRegisterInfo::lowerWACCRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ae7ec7dfcb6babc9f95a9d27ca37dddcc">llvm::PPCRegisterInfo::lowerWACCSpilling</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a497ba80da227001f952a7d30cfe0552f">llvm::RISCVRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a355a1f30be913f4dc74c51af277fd74a">llvm::PPCRegisterInfo::prepareDynamicAlloca</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#acb75d3ebfc904675aed50ee39f619373">llvm::ThumbRegisterInfo::rewriteFrameIndex</a> and <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#af1389c2a1baf930223956103b615a838">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectInlineAsmMemoryOperand</a>.</p>

</div>
</div>

### createVirtualRegister() {#a5a1a32c582ac944fc6e071f479ce6a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineRegisterInfo::createVirtualRegister (<a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">VRegAttrs</a> RegAttr, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create and return a new virtual register in the function with the specified register attributes(register class or bank and low level type).</p>

<p>Declaration at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#a7ed74de0e85d45f32fe8aca572f0c63d">createIncompleteVirtualRegister</a>, <a href="#aa8694a1d461a5b2c58bd83bf50c9f46f">noteNewVirtualRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs/#a2352f26ad25623549ee3b0623858ae95">llvm::MachineRegisterInfo::VRegAttrs::RCOrRB</a>, <a href="#a8d65688eb3408e2f26bf75b83a1b3448">setType</a> and <a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs/#a00ae234cc56f2437d0aa645cecfb44d9">llvm::MachineRegisterInfo::VRegAttrs::Ty</a>.</p>

</div>
</div>

### def\_begin() {#a56c15f3294c62d7590bb98e4d08ddeef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">def_iterator llvm::MachineRegisterInfo::def_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a5f95077d52fb7c8cd08ce6338b107bcf">def_empty</a>, <a href="#a8c6432877c30fca6601db52f92573998">def_operands</a>, <a href="#a564aa23c9a5cf95820535f59182aedd4">getOneDef</a>, <a href="#af2a209ffefa8ca1df76b99fe3c2e2cc4">isPhysRegModified</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a69189b7d95c4b78145d9dc25a3de148b">MustSaveLR</a>.</p>

</div>
</div>

### def\_bundle\_begin() {#afa02bb7124c3907948df9957bed1e9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">def_bundle_iterator llvm::MachineRegisterInfo::def_bundle_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ad269c6964062a546ea51482abf030796">def_bundles</a>.</p>

</div>
</div>

### def\_bundles() {#ad269c6964062a546ea51482abf030796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; def_bundle_iterator &gt; llvm::MachineRegisterInfo::def_bundles (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#afa02bb7124c3907948df9957bed1e9b3">def_bundle_begin</a>, <a href="#a595a7a24c293a79d1f19a3ae2337bb49">def_bundle_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### def\_empty() {#a5f95077d52fb7c8cd08ce6338b107bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::def_empty (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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

<p>def_empty - Return true if there are no instructions defining the specified register (it may be live-in).</p>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a56c15f3294c62d7590bb98e4d08ddeef">def_begin</a> and <a href="#aa21b132afc12ed3cead7a879506f277a">def_end</a>.</p>


<p>Referenced by <a href="#af988c2b4f62506108843a0fdc04b43a2">getUniqueVRegDef</a> and <a href="#abe36a37a2974f73af12228bccbaef0b4">isConstantPhysReg</a>.</p>

</div>
</div>

### def\_instr\_begin() {#a5d327d7e53eaaaf9bb8cbac86c819ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">def_instr_iterator llvm::MachineRegisterInfo::def_instr_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a415a4642beaee4a3156251faaacab646">def_instructions</a>, <a href="#af988c2b4f62506108843a0fdc04b43a2">getUniqueVRegDef</a> and <a href="#a40d954b9cf9ee8b545a78725f2549cba">getVRegDef</a>.</p>

</div>
</div>

### def\_instructions() {#a415a4642beaee4a3156251faaacab646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; def_instr_iterator &gt; llvm::MachineRegisterInfo::def_instructions (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a5d327d7e53eaaaf9bb8cbac86c819ab2">def_instr_begin</a>, <a href="#a54dd0a5ebf7dbe5aab5fe51979356645">def_instr_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### def\_operands() {#a8c6432877c30fca6601db52f92573998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; def_iterator &gt; llvm::MachineRegisterInfo::def_operands (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a56c15f3294c62d7590bb98e4d08ddeef">def_begin</a>, <a href="#aa21b132afc12ed3cead7a879506f277a">def_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a92d46fa856af865f8c997f97596990ec">hasOneDef</a>.</p>

</div>
</div>

### disableCalleeSavedRegister() {#aa3dfee03e12575026fa0a0461348a756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::disableCalleeSavedRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disables the register from the list of CSRs.</p>


<p>I.e. the register will not appear as part of the CSR mask.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>UpdatedCalleeSavedRegs.</p></dd>
</dl>


<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### dumpUses() {#a553593c083449cc4db546a757010a2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineRegisterInfo::dumpUses (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ab1c2de27f8d8c4a7de72d6415952473f">use_instructions</a>.</p>

</div>
</div>

### EmitLiveInCopies() {#a44ddc08d3e0ee02a2a8fb36fb4c8ac18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::EmitLiveInCopies (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * EntryMBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitLiveInCopies - Emit copies to initialize livein virtual registers into the given entry block.</p>

<p>Declaration at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acce9c12cc977a88dc7bc51493ce7681c">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="#a4ea277721b4e63804715a62de87e9a72">use_nodbg_empty</a>.</p>

</div>
</div>

### freezeReservedRegs() {#a30815e557d36373557a052fbf84263c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::freezeReservedRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>freezeReservedRegs - Called by the register allocator to freeze the set of reserved registers before allocation begins.</p>

<p>Declaration at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a82390447c4d818e9ba87147186f2bc9a">llvm::TargetRegisterInfo::getReservedRegs</a> and <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#acb76fa37c3f506da974ee1932b37eeaa">createFrameHelperMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07e9067b95ae52ee880a08c7d132fd56">llvm::TargetLoweringBase::finalizeLowering</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a82bfae004546453f47c217784928e0a5">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::runOnMachineFunction</a>.</p>

</div>
</div>

### getCalleeSavedRegs() {#a8ae9c5d17b40aa7be0189dd4f12dc315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * MachineRegisterInfo::getCalleeSavedRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns list of callee saved registers.</p>


<p>The function returns the updated CSR list (after taking into account registers that are disabled from the CSR list).</p>


<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad71b5bc0aa81f5dec06cbfecaf2f7183">llvm::TargetRegisterInfo::getCalleeSavedRegs</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a0ad5cb616fdce8d90db0927dbdf0533c">llvm::SIFrameLowering::determinePrologEpilogSGPRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a03593d957e11a83c25fbe9aeddacf19c">getLiveRegsForEntryMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp/#a80a3dc6dc764547a5cd15ad955c3a50f">isACalleeSavedRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a8109e774fb19e0ec57444aa577358ef4">llvm::X86MachineFunctionInfo::setRestoreBasePointer</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a5c3e3a37235c2c68008bbe931bfd10e8">llvm::SIMachineFunctionInfo::splitWWMSpillRegisters</a>.</p>

</div>
</div>

### getLiveInPhysReg() {#a8826883c66d420e0b7a9dd216eeaa388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister MachineRegisterInfo::getLiveInPhysReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLiveInPhysReg - If VReg is a live-in virtual register, return the corresponding live-in physical register.</p>

<p>Declaration at line 1026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>Reference <a href="#a74c5924111ebe86dd174fe793a52f327">liveins</a>.</p>

</div>
</div>

### getLiveInVirtReg() {#a9cc1aea4b14234362915bdb5c776573f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineRegisterInfo::getLiveInVirtReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLiveInVirtReg - If PReg is a live-in physical register, return the corresponding live-in virtual register.</p>


<p>getLiveInVirtReg - If PReg is a live-in physical register, return the corresponding live-in physical register.</p>


<p>Declaration at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#a74c5924111ebe86dd174fe793a52f327">liveins</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### getMaxLaneMaskForVReg() {#ab7e720f69b70ef3973d672936a9fa0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask MachineRegisterInfo::getMaxLaneMaskForVReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a mask covering all bits that can appear in lane masks of subregisters of the virtual register <span class="doxyComputerOutput">Reg</span>.</p>

<p>Declaration at line 1040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#ac4b4e4e2660b0fcd4f92c1d35c29d1c0">llvm::TargetRegisterClass::getLaneMask</a> and <a href="#a34b5ca1a1228655842826f4bad8c44c2">getRegClass</a>.</p>

</div>
</div>

### getMF() {#a9114705d2ebd07b743776bb9288e0e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction &amp; llvm::MachineRegisterInfo::getMF ()</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### getNumVirtRegs() {#ae73582bbbc71758dcac70cd8c56210e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineRegisterInfo::getNumVirtRegs ()</td>
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

<p>getNumVirtRegs - Return the number of virtual registers created.</p>

<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#abc82dfed5cd6e963934d2d0f8d6e7272">addRegAllocationHint</a>, <a href="#a7e2e403e3e1f758b87c25302090c96c2">clearVirtRegs</a>, <a href="#a7ed74de0e85d45f32fe8aca572f0c63d">createIncompleteVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aac0431719235a7ccda58a3df4894d130">llvm::SPIRV::lowerBuiltinType</a>, <a href="#a8e27d94e24a9bc2d6c7d719bed9637e3">setRegAllocationHint</a> and <a href="#a12fa9d44c84f7cadd81bf4758a22e1e9">verifyUseLists</a>.</p>

</div>
</div>

### getOneDef() {#a564aa23c9a5cf95820535f59182aedd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand * llvm::MachineRegisterInfo::getOneDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Returns the defining operand if there is exactly one operand defining the specified register, otherwise nullptr.</p>

<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a56c15f3294c62d7590bb98e4d08ddeef">def_begin</a>, <a href="#aa21b132afc12ed3cead7a879506f277a">def_end</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getPressureSets() {#acc1fe08378fadccbf77405721be835ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PSetIterator llvm::MachineRegisterInfo::getPressureSets (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegUnit)</td>
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

<p>Get an iterator over the pressure sets affected by the given physical or virtual register.</p>


<p>If RegUnit is physical, it must be a register unit (from <a href="/web-llvm/docs/api/classes/llvm/mcregunititerator">MCRegUnitIterator</a>).</p>


<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### getRegAllocationHint() {#a8bc629292d5cf14604e9b35b42ac4706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, Register &gt; llvm::MachineRegisterInfo::getRegAllocationHint (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
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

<p>getRegAllocationHint - Return the register allocation hint for the specified virtual register.</p>


<p>If there are many hints, this returns the one with the greatest weight.</p>


<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#afcfb1380ec9ff3f6106193a6ea9313c6">llvm::Register::id</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>


<p>Referenced by <a href="#a021a3cabd072c6984bf30b0f8a3fc0a6">getSimpleHint</a>.</p>

</div>
</div>

### getRegAllocationHints() {#aae2826c4edd4248c272fa91a0a3e80f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::pair&lt; unsigned, SmallVector&lt; Register, 4 &gt; &gt; * llvm::MachineRegisterInfo::getRegAllocationHints (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
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

<p>getRegAllocationHints - Return a reference to the vector of all register allocation hints for VReg.</p>

<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>

</div>
</div>

### getRegBank() {#a5492997611db35edf27193fe170b4f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBank * llvm::MachineRegisterInfo::getRegBank (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Return the register bank of <span class="doxyComputerOutput">Reg</span>.</p>


<p>This shouldn't be used directly unless <span class="doxyComputerOutput">Reg</span> has a register bank.</p>


<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getRegBankOrNull() {#a718b488ac3350a59380b5070f54061ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBank * llvm::MachineRegisterInfo::getRegBankOrNull (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Return the register bank of <span class="doxyComputerOutput">Reg</span>, or null if Reg has not been assigned a register bank or has been assigned a register class.</p>



:::info
<p>It is possible to get the register bank from the register class via <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9a3a4079fc2830c334da4406288bce24">RegisterBankInfo::getRegBankFromRegClass</a>.</p>
:::


<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getRegClass() {#a34b5ca1a1228655842826f4bad8c44c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * llvm::MachineRegisterInfo::getRegClass (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Return the register class of the specified virtual register.</p>


<p>This shouldn't be used directly unless <span class="doxyComputerOutput">Reg</span> has a register class.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#aa008940be15669d5b380a1423dae87c8">getRegClassOrNull</a> when this might happen.</p></dd>
</dl>


<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ad85285685fc46db3f2b3b0bf90bf9184">constrainRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/allocationorder/#a1d17986988f0819f29d78d1be8555c9e">llvm::AllocationOrder::create</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a75eb4d99ebf26777f16034567505166b">GetCostForDef</a>, <a href="#ab7e720f69b70ef3973d672936a9fa0ec">getMaxLaneMaskForVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#ad12ad3638ef83e9281c5cab4a99f60b0">getRegTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#abed37e9eeb67324751569d54ac13c0ef">isNonFoldablePartialRegisterLoad</a>, <a href="#a2786870c4807261593ac11e734db2f76">recomputeRegClass</a> and <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#af1389c2a1baf930223956103b615a838">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectInlineAsmMemoryOperand</a>.</p>

</div>
</div>

### getRegClassOrNull() {#aa008940be15669d5b380a1423dae87c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * llvm::MachineRegisterInfo::getRegClassOrNull (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Return the register class of <span class="doxyComputerOutput">Reg</span>, or null if Reg has not been assigned a register class yet.</p>



:::info
<p>A null register class can only happen when these two conditions are met:</p>


<ol class="doxyList" type="1">
<li>Generic virtual registers are created.</li>
<li>The machine function has not completely been through the instruction selection process. None of this condition is possible without GlobalISel for now. In other words, if GlobalISel is not used or if the query happens after the select pass, using getRegClass is safe.</li>
</ol>
:::


<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a7907102e3fee77f3105915033fa318a8">getRegClass</a> and <a href="#a4214f202c6a3b5b3933489a6edc49b6b">shouldTrackSubRegLiveness</a>.</p>

</div>
</div>

### getRegClassOrRegBank() {#a4fd10e1bf2e5ffae96be5b2cef4d17af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegClassOrRegBank &amp; llvm::MachineRegisterInfo::getRegClassOrRegBank (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Return the register bank or register class of <span class="doxyComputerOutput">Reg</span>.</p>



:::info
<p>Before the register bank gets assigned (i.e., before the <a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a> pass) <span class="doxyComputerOutput">Reg</span> may not have either.</p>
:::


<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#acd28b31b311bb88a92825ed630dd4269">constrainRegAttrs</a> and <a href="#a1d657bbeeb927506546fd529ebb0784b">getVRegAttrs</a>.</p>

</div>
</div>

### getReservedRegs() {#a5a78e01b4db3aacb72ddc22debed3269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector &amp; llvm::MachineRegisterInfo::getReservedRegs ()</td>
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

<p>getReservedRegs - Returns a reference to the frozen set of reserved registers.</p>


<p>This method should always be preferred to calling TRI::getReservedRegs() when possible.</p>


<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a5ecfe2828dd348fc0b23c8d1d73c4b75">reservedRegsFrozen</a>.</p>


<p>Referenced by <a href="#a53ca7cff9e929ba372da9780fdd44b02">isReserved</a>.</p>

</div>
</div>

### getSimpleHint() {#a021a3cabd072c6984bf30b0f8a3fc0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::MachineRegisterInfo::getSimpleHint (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
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

<p>getSimpleHint - same as getRegAllocationHint except it will only return a target independent hint.</p>

<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8bc629292d5cf14604e9b35b42ac4706">getRegAllocationHint</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### getTargetRegisterInfo() {#ab79ea5367e2539a9cca11f9db6f92c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo * llvm::MachineRegisterInfo::getTargetRegisterInfo ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a7e2e403e3e1f758b87c25302090c96c2">clearVirtRegs</a>, <a href="#aa3dfee03e12575026fa0a0461348a756">disableCalleeSavedRegister</a>, <a href="#a30815e557d36373557a052fbf84263c7">freezeReservedRegs</a>, <a href="#a8ae9c5d17b40aa7be0189dd4f12dc315">getCalleeSavedRegs</a>, <a href="#a7f39116ef8979cff64ea1c666228e7d9">isAllocatable</a>, <a href="#abe36a37a2974f73af12228bccbaef0b4">isConstantPhysReg</a>, <a href="#af2a209ffefa8ca1df76b99fe3c2e2cc4">isPhysRegModified</a>, <a href="#afd23983bb9fb4af65e27b56cc506edbc">isPhysRegUsed</a>, <a href="#ada7de8e2cf4949a58445f955d4d98caa">isReservedRegUnit</a>, <a href="#a3e736a38ebafb662ddd8645d83a1d534">MachineRegisterInfo</a>, <a href="#a2786870c4807261593ac11e734db2f76">recomputeRegClass</a>, <a href="#af16c39ee36e4633f821b6820f8bd52ef">replaceRegWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-detectdeadlanes-cpp-/detectdeadlanes/#ab75c3fd209b61d1137b0b8d70aa25a75">anonymous{DetectDeadLanes.cpp}::DetectDeadLanes::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-implicitnullchecks-cpp-/implicitnullchecks/#adfa9682269920db0fdac767478243124">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-initundef-cpp-/initundef/#a932a9e4598154d44a042dd542e33e77d">anonymous{InitUndef.cpp}::InitUndef::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>, <a href="#af392a602d843857153b656823dad4d08">updateDbgUsersToReg</a>, <a href="#a015233fe94a42e2294533334811ab899">verifyUseList</a> and <a href="#a12fa9d44c84f7cadd81bf4758a22e1e9">verifyUseLists</a>.</p>

</div>
</div>

### getType() {#a5dc0a32516ce31f495b440d47287028b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::MachineRegisterInfo::getType (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Get the low-level type of <span class="doxyComputerOutput">Reg</span> or <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>{} if Reg is not a generic (target independent) virtual register.</p>

<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ac27689339b95eeb89bc9e40aa1e394f9">cloneVirtualRegister</a>, <a href="#acd28b31b311bb88a92825ed630dd4269">constrainRegAttrs</a> and <a href="#a1d657bbeeb927506546fd529ebb0784b">getVRegAttrs</a>.</p>

</div>
</div>

### getUniqueVRegDef() {#af988c2b4f62506108843a0fdc04b43a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * MachineRegisterInfo::getUniqueVRegDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getUniqueVRegDef - Return the unique machine instr that defines the specified virtual register or null if none is found.</p>


<p>If there are multiple definitions or no definition, return null.</p>


<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#a5f95077d52fb7c8cd08ce6338b107bcf">def_empty</a>, <a href="#a5d327d7e53eaaaf9bb8cbac86c819ab2">def_instr_begin</a>, <a href="#a54dd0a5ebf7dbe5aab5fe51979356645">def_instr_end</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a69f73e1b5f8a3e376c63293408b6786e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeByOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acbccd3fb66e9075690f45dea7440cf9e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a4cdd09538b5a878eff565f40b9c5776a">GetSpirvImageTypeName</a>.</p>

</div>
</div>

### getUsedPhysRegsMask() {#a24866efe4b1cbbfe4532330064dbef04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector &amp; llvm::MachineRegisterInfo::getUsedPhysRegsMask ()</td>
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



<p>Definition at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### getVRegAttrs() {#a1d657bbeeb927506546fd529ebb0784b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VRegAttrs llvm::MachineRegisterInfo::getVRegAttrs (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Returns register class or bank and low level type of <span class="doxyComputerOutput">Reg</span>.</p>


<p>Always safe to use. Special values are returned when <span class="doxyComputerOutput">Reg</span> does not have some of the attributes.</p>


<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a4fd10e1bf2e5ffae96be5b2cef4d17af">getRegClassOrRegBank</a>, <a href="#a5dc0a32516ce31f495b440d47287028b">getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### getVRegDef() {#a40d954b9cf9ee8b545a78725f2549cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * MachineRegisterInfo::getVRegDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getVRegDef - Return the machine instr that defines the specified virtual register or null if none is found.</p>


<p>This assumes that the code is in SSA form, so there should only be one definition.</p>


<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5d327d7e53eaaaf9bb8cbac86c819ab2">def_instr_begin</a>, <a href="#a54dd0a5ebf7dbe5aab5fe51979356645">def_instr_end</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyfixbrtabledefaults-cpp-/#ab7b6f5214428c621e8b32582fd5efe62">anonymous{WebAssemblyFixBrTableDefaults.cpp}::fixBrTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8cdc39b963a62003cd157541feca56f6">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a> and <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a54b7b0b7ba267226509dfe6c2824951f">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::ValueIsPHI</a>.</p>

</div>
</div>

### getVRegName() {#aed28a3ee377374468972d5ba4e5cc15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MachineRegisterInfo::getVRegName (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### hasAtMostUserInstrs() {#a7a0d4a6526dc873f6af0b248247bc503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::hasAtMostUserInstrs (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned MaxUsers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>hasAtMostUses - Return true if the given register has at most <span class="doxyComputerOutput">MaxUsers</span> non-debug user instructions.</p>

<p>Declaration at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3b24ebd69d40090a23b6a2717a896625">llvm::hasNItemsOrLess</a>, <a href="#a741b5105cca6e98538c79acf275ca733">use_instr_nodbg_begin</a> and <a href="#afb1fd76e39ba4dfa2c428df88bbc82c2">use_instr_nodbg_end</a>.</p>

</div>
</div>

### hasOneDef() {#a92d46fa856af865f8c997f97596990ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::hasOneDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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

<p>Return true if there is exactly one operand defining the specified register.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a8c6432877c30fca6601db52f92573998">def_operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a88027543aef5a9bc0d82bc5e5e3506c3">llvm::hasSingleElement</a>.</p>

</div>
</div>

### hasOneNonDBGUse() {#a01bf72631b0bc836a8c07fe840b13233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::hasOneNonDBGUse (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>hasOneNonDBGUse - Return true if there is exactly one non-Debug use of the specified register.</p>

<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a88027543aef5a9bc0d82bc5e5e3506c3">llvm::hasSingleElement</a> and <a href="#a4361906d7698e8b1a912f6affc8e9151">use_nodbg_operands</a>.</p>

</div>
</div>

### hasOneNonDBGUser() {#a7dfb8467bcaf53e7e0215aa831985de6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::hasOneNonDBGUser (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>hasOneNonDBGUse - Return true if there is exactly one non-Debug instruction using the specified register.</p>


<p>Said instruction may have multiple uses.</p>


<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a88027543aef5a9bc0d82bc5e5e3506c3">llvm::hasSingleElement</a> and <a href="#a8c1a48aa3d3155a0e942c785932d9723">use_nodbg_instructions</a>.</p>

</div>
</div>

### hasOneUse() {#a600a2d410c09a9486e828ea34e5a9566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::hasOneUse (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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

<p>hasOneUse - Return true if there is exactly one instruction using the specified register.</p>

<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a88027543aef5a9bc0d82bc5e5e3506c3">llvm::hasSingleElement</a> and <a href="#ade188fadae5a455fcc4bd8d70142851d">use_operands</a>.</p>

</div>
</div>

### insertVRegByName() {#a0c212d531fb6d95129ce86a5491bae06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::insertVRegByName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a7ed74de0e85d45f32fe8aca572f0c63d">createIncompleteVirtualRegister</a>.</p>

</div>
</div>

### invalidateLiveness() {#a721b3ae1a20e295cc4f1143958ad3884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::invalidateLiveness ()</td>
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

<p>invalidateLiveness - Indicates that register liveness is no longer being tracked accurately.</p>


<p>This should be called by late passes that invalidate the liveness information.</p>


<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a0020348b08bb4cccecf3241eac999d8a">llvm::MachineFunctionProperties::TracksLiveness</a>.</p>

</div>
</div>

### isAllocatable() {#a7f39116ef8979cff64ea1c666228e7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::isAllocatable (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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

<p>isAllocatable - Returns true when PhysReg belongs to an allocatable register class and it hasn't been reserved.</p>


<p>Allocatable registers may show up in the allocation order of some virtual register, so a register allocator needs to track its liveness and availability.</p>


<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#af2f8f83c931fa084058914c65af13984">llvm::TargetRegisterInfo::isInAllocatableClass</a> and <a href="#a53ca7cff9e929ba372da9780fdd44b02">isReserved</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/coalescing/#a68a07c5954404c20c6abe9a6791f19c2">anonymous{RegAllocPBQP.cpp}::Coalescing::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aaeae02cd060afb658b3e1e17ad7e42c5">llvm::PPCRegisterInfo::getCalleeSavedRegs</a> and <a href="#abe36a37a2974f73af12228bccbaef0b4">isConstantPhysReg</a>.</p>

</div>
</div>

### isConstantPhysReg() {#abe36a37a2974f73af12228bccbaef0b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::isConstantPhysReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if PhysReg is unallocatable and constant throughout the function.</p>


<p>Writing to a constant register has no effect.</p>


<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5f95077d52fb7c8cd08ce6338b107bcf">def_empty</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="#a7f39116ef8979cff64ea1c666228e7d9">isAllocatable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#adab6a6e130a565c2cb11ef465fac90e7">llvm::MCRegister::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### isLiveIn() {#a640f34062e7189756ce67e60d5dfd629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::isLiveIn (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>Reference <a href="#a74c5924111ebe86dd174fe793a52f327">liveins</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab63a202288b59ede08326547a2126c8a">getPrologueDeath</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3bbbc37b2cd9470b51560df8c20e66e2">llvm::M68kFrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### isPhysRegModified() {#af2a209ffefa8ca1df76b99fe3c2e2cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::isPhysRegModified (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, bool SkipNoReturnDef=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified register is modified in this function.</p>


<p>This checks that no defining machine operands exist for the register or any of its aliases. Definitions found on functions marked noreturn are ignored, to consider them pass 'true' for optional parameter SkipNoReturnDef. The register is also considered modified when it is set in the UsedPhysRegMask.</p>


<p>Declaration at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#a56c15f3294c62d7590bb98e4d08ddeef">def_begin</a>, <a href="#aa21b132afc12ed3cead7a879506f277a">def_end</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp/#ac0001ca0e66f6badb71cca036c24cab0">isNoReturnDef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### isPhysRegUsed() {#afd23983bb9fb4af65e27b56cc506edbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::isPhysRegUsed (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, bool SkipRegMaskTest=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified register is modified or read in this function.</p>


<p>This checks that no machine operands exist for the register or any of its aliases. If SkipRegMaskTest is false, the register is considered used when it is set in the UsedPhysRegMask.</p>


<p>Declaration at line 912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="#a666dc30b9326da6b9e69740a241df89d">reg_nodbg_empty</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>.</p>

</div>
</div>

### isReserved() {#a53ca7cff9e929ba372da9780fdd44b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::isReserved (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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

<p>isReserved - Returns true when PhysReg is a reserved register.</p>


<p>Reserved registers may belong to an allocatable register class, but the target has explicitly requested that they are not used.</p>


<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a5a78e01b4db3aacb72ddc22debed3269">getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="#a7f39116ef8979cff64ea1c666228e7d9">isAllocatable</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a5c4a909a1725cc86437f4f350ab35cdb">llvm::SIRegisterInfo::isAsmClobberable</a>.</p>

</div>
</div>

### isReservedRegUnit() {#ada7de8e2cf4949a58445f955d4d98caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::isReservedRegUnit (unsigned Unit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true when the given register unit is considered reserved.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> units are considered reserved when for at least one of their root registers, the root register and all super registers are reserved. This currently iterates the register hierarchy and may be slower than expected.</p>


<p>Declaration at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitrootiterator/#abd29ecab24058fdf823addcad29c6939">llvm::MCRegUnitRootIterator::isValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### isSSA() {#a86dd1b4ce6ff2d4a0b4593c5f7b2a3fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::isSSA ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96">llvm::MachineFunctionProperties::IsSSA</a>.</p>

</div>
</div>

### isUpdatedCSRsInitialized() {#a3076649c65eeacac14b0aa8eaa75bcdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::isUpdatedCSRsInitialized ()</td>
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

<p>Returns true if the updated CSR list was initialized and false otherwise.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### leaveSSA() {#a035f850aa2492716906dbb0610e98c90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::leaveSSA ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96">llvm::MachineFunctionProperties::IsSSA</a>.</p>

</div>
</div>

### livein\_begin() {#ade38103c28d56389d7848497aae70bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">livein_iterator llvm::MachineRegisterInfo::livein_begin ()</td>
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



<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### livein\_empty() {#a1c9eecf2b6aa6f212610a87813955328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::livein_empty ()</td>
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



<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### livein\_end() {#aa5c135f0c45228e88b1927c069fc1d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">livein_iterator llvm::MachineRegisterInfo::livein_end ()</td>
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



<p>Definition at line 1015 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### liveins() {#a74c5924111ebe86dd174fe793a52f327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; MCRegister, Register &gt; &gt; llvm::MachineRegisterInfo::liveins ()</td>
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



<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a8826883c66d420e0b7a9dd216eeaa388">getLiveInPhysReg</a>, <a href="#a9cc1aea4b14234362915bdb5c776573f">getLiveInVirtReg</a> and <a href="#a640f34062e7189756ce67e60d5dfd629">isLiveIn</a>.</p>

</div>
</div>

### markUsesInDebugValueAsUndef() {#a213df9204c030effa8d56a05564997a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::markUsesInDebugValueAsUndef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>markUsesInDebugValueAsUndef - Mark every DBG_VALUE referencing the specified register as undefined which causes the DBG_VALUE to be deleted during <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables">LiveDebugVariables</a> analysis.</p>

<p>Declaration at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="#ab1c2de27f8d8c4a7de72d6415952473f">use_instructions</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### moveOperands() {#a557ce2bfb3c946e43d65d750b2537987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::moveOperands (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * Src, unsigned NumOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move NumOps operands from Src to Dst, updating use-def lists as needed.</p>


<p>The Dst range is assumed to be uninitialized memory. (Or it may contain operands that won't be destroyed, which is OK because the MO destructor is trivial anyway).</p>


<p>The Src and Dst ranges may overlap.</p>


<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>

</div>
</div>

### noteCloneVirtualRegister() {#adc037e4e3484a814f8258868db79c758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::noteCloneVirtualRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ac27689339b95eeb89bc9e40aa1e394f9">cloneVirtualRegister</a>.</p>

</div>
</div>

### noteNewVirtualRegister() {#aa8694a1d461a5b2c58bd83bf50c9f46f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::noteNewVirtualRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a9694f2906cfe1d6d35bbe6742c67dff0">createGenericVirtualRegister</a>, <a href="#a5c77792a06583e0fe7a0379ad94a2809">createVirtualRegister</a> and <a href="#a5a1a32c582ac944fc6e071f479ce6a08">createVirtualRegister</a>.</p>

</div>
</div>

### recomputeRegClass() {#a2786870c4807261593ac11e734db2f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineRegisterInfo::recomputeRegClass (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>recomputeRegClass - Try to find a legal super-class of Reg's register class that still satisfies the constraints from the instructions using Reg.</p>


<p>Returns true if Reg was upgraded.</p>


<p>This method can be used after constraints have been removed from a virtual register, for example after removing instructions or splitting the live range.</p>


<p>Declaration at line 746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#a34b5ca1a1228655842826f4bad8c44c2">getRegClass</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ac055593361bdcb9d0093f0881ce7f286">reg_nodbg_operands</a>, <a href="#a965a15cef77a97f0e17f9f26fd5be53e">setRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### reg\_begin() {#a3e9e89a17faecbca7d2409bf9817973e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_iterator llvm::MachineRegisterInfo::reg_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aecfd94e60d64656d8b19f2ea69bb02af">reg_empty</a> and <a href="#a26ee456cc6716cfbc16261e544100b12">reg_operands</a>.</p>

</div>
</div>

### reg\_bundle\_begin() {#aa7bac2504c6f8f8bf191f3d919426095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_bundle_iterator llvm::MachineRegisterInfo::reg_bundle_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a0e05a48717dda8a0ca99449587367660">reg_bundles</a>.</p>

</div>
</div>

### reg\_bundle\_nodbg\_begin() {#a38c62f1e9ddcab1cde851a3df8de377b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_bundle_nodbg_iterator llvm::MachineRegisterInfo::reg_bundle_nodbg_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a52760341a18bcab24705161c498aa6f5">reg_nodbg_bundles</a>.</p>

</div>
</div>

### reg\_bundles() {#a0e05a48717dda8a0ca99449587367660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; reg_bundle_iterator &gt; llvm::MachineRegisterInfo::reg_bundles (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#aa7bac2504c6f8f8bf191f3d919426095">reg_bundle_begin</a> and <a href="#ab05bea8bf7513acba82ca339c74de2de">reg_bundle_end</a>.</p>

</div>
</div>

### reg\_empty() {#aecfd94e60d64656d8b19f2ea69bb02af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::reg_empty (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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

<p>reg_empty - Return true if there are no instructions using or defining the specified register (it may be live-in).</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a3e9e89a17faecbca7d2409bf9817973e">reg_begin</a> and <a href="#a1d8edf72c1d3e14e4d2396b98e07ad72">reg_end</a>.</p>

</div>
</div>

### reg\_instr\_begin() {#a29dbcf8b92514fc55ff83db9312dcec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_instr_iterator llvm::MachineRegisterInfo::reg_instr_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aa7bc06ec30359044cffdc3ccd58bfacf">reg_instructions</a>.</p>

</div>
</div>

### reg\_instr\_nodbg\_begin() {#ae43ef10e056198d73d7c688d0649c9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_instr_nodbg_iterator llvm::MachineRegisterInfo::reg_instr_nodbg_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ae916811c548f67c9ed178fa8a38ac7f1">reg_nodbg_instructions</a>.</p>

</div>
</div>

### reg\_instructions() {#aa7bc06ec30359044cffdc3ccd58bfacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; reg_instr_iterator &gt; llvm::MachineRegisterInfo::reg_instructions (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a29dbcf8b92514fc55ff83db9312dcec4">reg_instr_begin</a> and <a href="#a45911f3aacb9b7ea62d1fa8fc8180039">reg_instr_end</a>.</p>


<p>Referenced by <a href="#a7e2e403e3e1f758b87c25302090c96c2">clearVirtRegs</a>.</p>

</div>
</div>

### reg\_nodbg\_begin() {#a04a5fd48b56cb883a30104fd811fd8c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_nodbg_iterator llvm::MachineRegisterInfo::reg_nodbg_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a666dc30b9326da6b9e69740a241df89d">reg_nodbg_empty</a> and <a href="#ac055593361bdcb9d0093f0881ce7f286">reg_nodbg_operands</a>.</p>

</div>
</div>

### reg\_nodbg\_bundles() {#a52760341a18bcab24705161c498aa6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; reg_bundle_nodbg_iterator &gt; llvm::MachineRegisterInfo::reg_nodbg_bundles (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a38c62f1e9ddcab1cde851a3df8de377b">reg_bundle_nodbg_begin</a> and <a href="#a94275a1edd38ff90ce524665a268d71e">reg_bundle_nodbg_end</a>.</p>

</div>
</div>

### reg\_nodbg\_empty() {#a666dc30b9326da6b9e69740a241df89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::reg_nodbg_empty (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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

<p>reg_nodbg_empty - Return true if the only instructions using or defining Reg are Debug instructions.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a04a5fd48b56cb883a30104fd811fd8c4">reg_nodbg_begin</a> and <a href="#a728707da8d5c6832316ff91231f3c2ef">reg_nodbg_end</a>.</p>


<p>Referenced by <a href="#afd23983bb9fb4af65e27b56cc506edbc">isPhysRegUsed</a>.</p>

</div>
</div>

### reg\_nodbg\_instructions() {#ae916811c548f67c9ed178fa8a38ac7f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; reg_instr_nodbg_iterator &gt; llvm::MachineRegisterInfo::reg_nodbg_instructions (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#ae43ef10e056198d73d7c688d0649c9b2">reg_instr_nodbg_begin</a> and <a href="#a29a1144eb9d753b6b682a933aa3f8f9f">reg_instr_nodbg_end</a>.</p>

</div>
</div>

### reg\_nodbg\_operands() {#ac055593361bdcb9d0093f0881ce7f286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; reg_nodbg_iterator &gt; llvm::MachineRegisterInfo::reg_nodbg_operands (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a04a5fd48b56cb883a30104fd811fd8c4">reg_nodbg_begin</a> and <a href="#a728707da8d5c6832316ff91231f3c2ef">reg_nodbg_end</a>.</p>


<p>Referenced by <a href="#a2786870c4807261593ac11e734db2f76">recomputeRegClass</a>.</p>

</div>
</div>

### reg\_operands() {#a26ee456cc6716cfbc16261e544100b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; reg_iterator &gt; llvm::MachineRegisterInfo::reg_operands (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a3e9e89a17faecbca7d2409bf9817973e">reg_begin</a> and <a href="#a1d8edf72c1d3e14e4d2396b98e07ad72">reg_end</a>.</p>


<p>Referenced by <a href="#af16c39ee36e4633f821b6820f8bd52ef">replaceRegWith</a> and <a href="#a015233fe94a42e2294533334811ab899">verifyUseList</a>.</p>

</div>
</div>

### removeRegOperandFromUseList() {#aea6bca2d194dea4aa5634cf5c394ebdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::removeRegOperandFromUseList (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove MO from its use-def list.</p>

<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>

</div>
</div>

### replaceRegWith() {#af16c39ee36e4633f821b6820f8bd52ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::replaceRegWith (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FromReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ToReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>replaceRegWith - Replace all instances of FromReg with ToReg in the machine function.</p>


<p>This is like llvm-level X-&gt;replaceAllUsesWith(Y), except that it also changes any definitions of the register as well.</p>


<p>Note that it is usually necessary to first constrain ToReg's register class and register bank to match the FromReg constraints using one of the methods:</p>


<p>constrainRegClass(ToReg, getRegClass(FromReg)) constrainRegAttrs(ToReg, FromReg) <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a1cfd8b1df608cb89b0acb94d29d447b3">RegisterBankInfo::constrainGenericRegister</a>(ToReg, *MRI.getRegClass(FromReg), MRI)</p>


<p>These functions will return a falsy result if the virtual registers have incompatible constraints.</p>


<p>Note that if ToReg is a physical register the function will replace and apply sub registers to ToReg in order to obtain a final/proper physical register.</p>


<p>This is like llvm-level X-&gt;replaceAllUsesWith(Y), except that it also changes any definitions of the register as well. If ToReg is a physical register we apply the sub register to obtain the final/proper physical register.</p>


<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="#a26ee456cc6716cfbc16261e544100b12">reg_operands</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### reservedRegsFrozen() {#a5ecfe2828dd348fc0b23c8d1d73c4b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::reservedRegsFrozen ()</td>
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

<p>reservedRegsFrozen - Returns true after <a href="#a30815e557d36373557a052fbf84263c7">freezeReservedRegs()</a> was called to ensure the set of reserved registers stays constant.</p>

<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a96bb3ab76b2a615f1fac4fdb8105095a">canReserveReg</a>, <a href="#a5a78e01b4db3aacb72ddc22debed3269">getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a> and <a href="#ab490792bb2387856aeb83267a1bd55d2">reserveReg</a>.</p>

</div>
</div>

### reserveReg() {#ab490792bb2387856aeb83267a1bd55d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::reserveReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>reserveReg – Mark a register as reserved so checks like isAllocatable will not suggest using it.</p>


<p>This should not be used during the middle of a function walk, or when liveness info is available.</p>


<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ecfe2828dd348fc0b23c8d1d73c4b75">reservedRegsFrozen</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### resetDelegate() {#a6208e23829aa84a5e95a1034c68c2fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::resetDelegate (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/delegate">Delegate</a> * delegate)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setCalleeSavedRegs() {#aaefaeb20cd3228ca22ecaff2fa385f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::setCalleeSavedRegs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; CSRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the updated Callee Saved Registers list.</p>


<p>Notice that it will override ant previously disabled/saved CSRs.</p>


<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a776852734c11ae705971ee8d39e589c6">llvm::AArch64RegisterInfo::UpdateCustomCalleeSavedRegs</a>.</p>

</div>
</div>

### setRegAllocationHint() {#a8e27d94e24a9bc2d6c7d719bed9637e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::setRegAllocationHint (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, unsigned Type, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PrefReg)</td>
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

<p>setRegAllocationHint - Specify a register allocation hint for the specified virtual register.</p>


<p>This is typically used by target, and in case of an earlier hint it will be overwritten.</p>


<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae73582bbbc71758dcac70cd8c56210e4">getNumVirtRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>


<p>Referenced by <a href="#aa18b5ef8a2c55e42b08affe5d0323e12">setSimpleHint</a>.</p>

</div>
</div>

### setRegBank() {#a81763ced27ec9b0c42f8848f4ebe5bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::setRegBank (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; RegBank)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the register bank to <span class="doxyComputerOutput">RegBank</span> for <span class="doxyComputerOutput">Reg</span>.</p>

<p>Declaration at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>

</div>
</div>

### setRegClass() {#a965a15cef77a97f0e17f9f26fd5be53e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::setRegClass (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setRegClass - Set the register class of the specified virtual register.</p>

<p>Declaration at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a68b1cbd38847abc3e56eca6df316d5a1">llvm::TargetRegisterClass::isAllocatable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a> and <a href="#a2786870c4807261593ac11e734db2f76">recomputeRegClass</a>.</p>

</div>
</div>

### setRegClassOrRegBank() {#a5ada07773b69dd6a5e99d47fe368d313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::setRegClassOrRegBank (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a0f1def99add5e4273e839bf70f3e79ed">RegClassOrRegBank</a> &amp; RCOrRB)</td>
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



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#acd28b31b311bb88a92825ed630dd4269">constrainRegAttrs</a>.</p>

</div>
</div>

### setSimpleHint() {#aa18b5ef8a2c55e42b08affe5d0323e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::setSimpleHint (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PrefReg)</td>
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

<p>Specify the preferred (target independent) register allocation hint for the specified virtual register.</p>

<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="#a8e27d94e24a9bc2d6c7d719bed9637e3">setRegAllocationHint</a>.</p>

</div>
</div>

### setType() {#a8d65688eb3408e2f26bf75b83a1b3448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::setType (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the low-level type of <span class="doxyComputerOutput">VReg</span> to <span class="doxyComputerOutput">Ty</span>.</p>

<p>Declaration at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abcfc092d297e085e5b5390b5b1656236">allocateVGPR32Input</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="#ac27689339b95eeb89bc9e40aa1e394f9">cloneVirtualRegister</a>, <a href="#acd28b31b311bb88a92825ed630dd4269">constrainRegAttrs</a>, <a href="#a9694f2906cfe1d6d35bbe6742c67dff0">createGenericVirtualRegister</a> and <a href="#a5a1a32c582ac944fc6e071f479ce6a08">createVirtualRegister</a>.</p>

</div>
</div>

### shouldTrackSubRegLiveness() {#a7f2602cf77af82396115293302557ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::shouldTrackSubRegLiveness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC)</td>
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

<p>Returns true if liveness for register class <span class="doxyComputerOutput">RC</span> should be tracked at the subregister level.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a5f091eb46b984dbf525c6ac041f6af95">llvm::TargetRegisterClass::HasDisjunctSubRegs</a> and <a href="#a48ad9eedacb98923ab00074ec4760db2">subRegLivenessEnabled</a>.</p>


<p>Referenced by <a href="#a4214f202c6a3b5b3933489a6edc49b6b">shouldTrackSubRegLiveness</a>.</p>

</div>
</div>

### shouldTrackSubRegLiveness() {#a4214f202c6a3b5b3933489a6edc49b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::shouldTrackSubRegLiveness (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa008940be15669d5b380a1423dae87c8">getRegClassOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a> and <a href="#a7f2602cf77af82396115293302557ee0">shouldTrackSubRegLiveness</a>.</p>

</div>
</div>

### subRegLivenessEnabled() {#a48ad9eedacb98923ab00074ec4760db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::subRegLivenessEnabled ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a7f2602cf77af82396115293302557ee0">shouldTrackSubRegLiveness</a>.</p>

</div>
</div>

### tracksLiveness() {#a218bf4a49a8808ebb854ec9b89907904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::tracksLiveness ()</td>
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

<p>tracksLiveness - Returns true when tracking register liveness accurately.</p>


<p>(see MachineFUnctionProperties::Property description for details)</p>


<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a0020348b08bb4cccecf3241eac999d8a">llvm::MachineFunctionProperties::TracksLiveness</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a4a8c56807dfa1a49f37218084fb6c044">findRenameRegForSameLdStRegPair</a> and <a href="/web-llvm/docs/api/classes/llvm/branchfolder/#aa0d50fee4d0d41ccf591e29de109786f">llvm::BranchFolder::OptimizeFunction</a>.</p>

</div>
</div>

### updateDbgUsersToReg() {#af392a602d843857153b656823dad4d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineRegisterInfo::updateDbgUsersToReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> OldReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> NewReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; Users)</td>
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

<p>updateDbgUsersToReg - Update a collection of debug instructions to refer to the designated register.</p>

<p>Definition at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a>.</p>

</div>
</div>

### use\_begin() {#ab87a00eb296cb02039f5a5580a54efd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_iterator llvm::MachineRegisterInfo::use_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aeae86e9004476412ca754a7de4ee8a0c">use_empty</a> and <a href="#ade188fadae5a455fcc4bd8d70142851d">use_operands</a>.</p>

</div>
</div>

### use\_bundle\_begin() {#aa40a0f52d1e6d37f89c8bfe4113e15b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_bundle_iterator llvm::MachineRegisterInfo::use_bundle_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aef898731887fc99f3a5e62710cb5bade">use_bundles</a>.</p>

</div>
</div>

### use\_bundle\_nodbg\_begin() {#a755b516aa2acc499e777c112a93a9f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_bundle_nodbg_iterator llvm::MachineRegisterInfo::use_bundle_nodbg_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a5aa433099910dc844bc8466933779e58">use_nodbg_bundles</a>.</p>

</div>
</div>

### use\_bundles() {#aef898731887fc99f3a5e62710cb5bade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_bundle_iterator &gt; llvm::MachineRegisterInfo::use_bundles (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#aa40a0f52d1e6d37f89c8bfe4113e15b8">use_bundle_begin</a> and <a href="#a6d9cb3eb3b146477bb4a708a246607be">use_bundle_end</a>.</p>

</div>
</div>

### use\_empty() {#aeae86e9004476412ca754a7de4ee8a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::use_empty (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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

<p>use_empty - Return true if there are no instructions using the specified register.</p>

<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#ab87a00eb296cb02039f5a5580a54efd1">use_begin</a> and <a href="#ac8347c6938efe4d9a4426b92ef57851e">use_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#aad707aff5fcbdc8180deb9e6695f0c32">llvm::NVPTXFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcbranchselector-cpp/#a6ce9d801876c8c6c8d4653a1dcf18acd">GetInitialOffset</a>.</p>

</div>
</div>

### use\_instr\_begin() {#a489d8c4ed3ae8b1ca4f68e580b074bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_instr_iterator llvm::MachineRegisterInfo::use_instr_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ab1c2de27f8d8c4a7de72d6415952473f">use_instructions</a>.</p>

</div>
</div>

### use\_instr\_nodbg\_begin() {#a741b5105cca6e98538c79acf275ca733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_instr_nodbg_iterator llvm::MachineRegisterInfo::use_instr_nodbg_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a7a0d4a6526dc873f6af0b248247bc503">hasAtMostUserInstrs</a> and <a href="#a8c1a48aa3d3155a0e942c785932d9723">use_nodbg_instructions</a>.</p>

</div>
</div>

### use\_instructions() {#ab1c2de27f8d8c4a7de72d6415952473f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_instr_iterator &gt; llvm::MachineRegisterInfo::use_instructions (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a489d8c4ed3ae8b1ca4f68e580b074bf1">use_instr_begin</a> and <a href="#a7a73104304bf1f9d344ad495283561b5">use_instr_end</a>.</p>


<p>Referenced by <a href="#a553593c083449cc4db546a757010a2f4">dumpUses</a> and <a href="#a213df9204c030effa8d56a05564997a7">markUsesInDebugValueAsUndef</a>.</p>

</div>
</div>

### use\_nodbg\_begin() {#a03ccda750131c296a86bd6dc10331a77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_nodbg_iterator llvm::MachineRegisterInfo::use_nodbg_begin (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a4ea277721b4e63804715a62de87e9a72">use_nodbg_empty</a> and <a href="#a4361906d7698e8b1a912f6affc8e9151">use_nodbg_operands</a>.</p>

</div>
</div>

### use\_nodbg\_bundles() {#a5aa433099910dc844bc8466933779e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_bundle_nodbg_iterator &gt; llvm::MachineRegisterInfo::use_nodbg_bundles (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a755b516aa2acc499e777c112a93a9f2f">use_bundle_nodbg_begin</a> and <a href="#aacc6af82327a6f208f586e90cc48dbed">use_bundle_nodbg_end</a>.</p>

</div>
</div>

### use\_nodbg\_empty() {#a4ea277721b4e63804715a62de87e9a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::use_nodbg_empty (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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

<p>use_nodbg_empty - Return true if there are no non-Debug instructions using the specified register.</p>

<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="#a03ccda750131c296a86bd6dc10331a77">use_nodbg_begin</a> and <a href="#a355ba266da19094cc0948311c431768e">use_nodbg_end</a>.</p>


<p>Referenced by <a href="#a44ddc08d3e0ee02a2a8fb36fb4c8ac18">EmitLiveInCopies</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyfixbrtabledefaults-cpp-/#ab7b6f5214428c621e8b32582fd5efe62">anonymous{WebAssemblyFixBrTableDefaults.cpp}::fixBrTableIndex</a> and <a href="/web-llvm/docs/api/classes/anonymous-nvptxreplaceimagehandles-cpp-/nvptxreplaceimagehandles/#a60464340b4cda7f63baffe1279e80b68">anonymous{NVPTXReplaceImageHandles.cpp}::NVPTXReplaceImageHandles::runOnMachineFunction</a>.</p>

</div>
</div>

### use\_nodbg\_instructions() {#a8c1a48aa3d3155a0e942c785932d9723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_instr_nodbg_iterator &gt; llvm::MachineRegisterInfo::use_nodbg_instructions (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a741b5105cca6e98538c79acf275ca733">use_instr_nodbg_begin</a> and <a href="#afb1fd76e39ba4dfa2c428df88bbc82c2">use_instr_nodbg_end</a>.</p>


<p>Referenced by <a href="#a7dfb8467bcaf53e7e0215aa831985de6">hasOneNonDBGUser</a>.</p>

</div>
</div>

### use\_nodbg\_operands() {#a4361906d7698e8b1a912f6affc8e9151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_nodbg_iterator &gt; llvm::MachineRegisterInfo::use_nodbg_operands (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#a03ccda750131c296a86bd6dc10331a77">use_nodbg_begin</a> and <a href="#a355ba266da19094cc0948311c431768e">use_nodbg_end</a>.</p>


<p>Referenced by <a href="#a01bf72631b0bc836a8c07fe840b13233">hasOneNonDBGUse</a>.</p>

</div>
</div>

### use\_operands() {#ade188fadae5a455fcc4bd8d70142851d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; use_iterator &gt; llvm::MachineRegisterInfo::use_operands (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="#ab87a00eb296cb02039f5a5580a54efd1">use_begin</a> and <a href="#ac8347c6938efe4d9a4426b92ef57851e">use_end</a>.</p>


<p>Referenced by <a href="#a3da9727b1d452d6dcab08fde547ab634">clearKillFlags</a> and <a href="#a600a2d410c09a9486e828ea34e5a9566">hasOneUse</a>.</p>

</div>
</div>

### verifyUseList() {#a015233fe94a42e2294533334811ab899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::verifyUseList (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the sanity of the use list for Reg.</p>

<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a> and <a href="#a26ee456cc6716cfbc16261e544100b12">reg_operands</a>.</p>


<p>Referenced by <a href="#a7e2e403e3e1f758b87c25302090c96c2">clearVirtRegs</a> and <a href="#a12fa9d44c84f7cadd81bf4758a22e1e9">verifyUseLists</a>.</p>

</div>
</div>

### verifyUseLists() {#a12fa9d44c84f7cadd81bf4758a22e1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineRegisterInfo::verifyUseLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the use list of all registers.</p>

<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a>.</p>


<p>References <a href="#ae73582bbbc71758dcac70cd8c56210e4">getNumVirtRegs</a>, <a href="#ab79ea5367e2539a9cca11f9db6f92c06">getTargetRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a> and <a href="#a015233fe94a42e2294533334811ab899">verifyUseList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getRegUseDefListHead() {#aee034baf5dd4348fc2ae26d222efaccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand *&amp; llvm::MachineRegisterInfo::getRegUseDefListHead (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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

<p>getRegUseDefListHead - Return the head pointer for the register use/def list for the specified virtual or physical register.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### getRegUseDefListHead() {#a029389fb7ae06438caae8f45a504c04d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand * llvm::MachineRegisterInfo::getRegUseDefListHead (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsUpdatedCSRsInitialized {#a4bd58d34022c593e7063d85383cff6c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineRegisterInfo::IsUpdatedCSRsInitialized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The flag is true upon <span class="doxyComputerOutput">UpdatedCSRs</span> initialization and false otherwise.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### LiveIns {#a90714962014be77e5fca78fa121bd0e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;MCRegister, Register&gt; &gt; llvm::MachineRegisterInfo::LiveIns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the physical registers that are live in to the function.</p>


<p>Live in values are typically arguments in registers. LiveIn values are allowed to have virtual registers associated with them, stored in the second element.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### MF {#afcd84ad3ee1982df28b9edf9bd627ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::MachineRegisterInfo::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### PhysRegUseDefLists {#a8d3fe5a3cf1b78fbe96222ce75371ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MachineOperand *[]&gt; llvm::MachineRegisterInfo::PhysRegUseDefLists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PhysRegUseDefLists - This is an array of the head of the use/def list for physical registers.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### RegAllocHints {#a386e42aede99726bf2781edb21631f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;std::pair&lt;unsigned, SmallVector&lt;Register, 4&gt; &gt;, VirtReg2IndexFunctor&gt; llvm::MachineRegisterInfo::RegAllocHints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RegAllocHints - This vector records register allocation hints for virtual registers.</p>


<p>For each virtual register, it keeps a pair of hint type and hints vector making up the allocation hints. Only the first hint may be target specific, and in that case this is reflected by the first member of the pair being non-zero. If the hinted register is virtual, it means the allocator should prefer the physical register allocated to it if any.</p>


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### ReservedRegs {#a875f5fc41819ee3a88e6ac8097f030ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::MachineRegisterInfo::ReservedRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReservedRegs - This is a bit vector of reserved registers.</p>


<p>The target may change its mind about which registers should be reserved. This vector is the frozen set of reserved registers when register allocation started.</p>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### TheDelegates {#ad58db0f1b478a5edc489733c504ff2cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Delegate *, 1&gt; llvm::MachineRegisterInfo::TheDelegates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### TracksSubRegLiveness {#a7b5bc21b71692d9561b10434bdd140f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::MachineRegisterInfo::TracksSubRegLiveness</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if subregister liveness is tracked.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### UpdatedCSRs {#a386323124a081d9eeae17685e5837a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MCPhysReg, 16&gt; llvm::MachineRegisterInfo::UpdatedCSRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains the updated callee saved register list.</p>


<p>As opposed to the static list defined in register info, all registers that were disabled are removed from the list.</p>


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### UsedPhysRegMask {#a90c694e699d61413b7206005a63d2134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::MachineRegisterInfo::UsedPhysRegMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UsedPhysRegMask - Additional used physregs including aliases.</p>


<p>This bit vector represents all the registers clobbered by function calls.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### VReg2Name {#a5ca2c0f5bd9620e6df335c600a20199a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;std::string, VirtReg2IndexFunctor&gt; llvm::MachineRegisterInfo::VReg2Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map for recovering vreg name from vreg number.</p>


<p>This map is used by the MIR Printer.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### VRegInfo {#a30dba9292bb7a7ac6128317a4c6c323c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;std::pair&lt;RegClassOrRegBank, MachineOperand *&gt;, VirtReg2IndexFunctor&gt; llvm::MachineRegisterInfo::VRegInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/vreginfo">VRegInfo</a> - Information we keep for each virtual register.</p>


<p>Each element in this list contains the register class of the vreg and the start of the use/def list for the register.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### VRegNames {#aace7c64158e3b8e757b201d4ec782dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::MachineRegisterInfo::VRegNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a> that is used to unique vreg names.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

### VRegToType {#a82a28529fc3eb468ffe69d93d46499d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VRegToTypeMap llvm::MachineRegisterInfo::VRegToType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map generic virtual registers to their low-level type.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### def\_bundle\_end() {#a595a7a24c293a79d1f19a3ae2337bb49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">def_bundle_iterator llvm::MachineRegisterInfo::def_bundle_end ()</td>
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



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ad269c6964062a546ea51482abf030796">def_bundles</a>.</p>

</div>
</div>

### def\_end() {#aa21b132afc12ed3cead7a879506f277a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">def_iterator llvm::MachineRegisterInfo::def_end ()</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a5f95077d52fb7c8cd08ce6338b107bcf">def_empty</a>, <a href="#a8c6432877c30fca6601db52f92573998">def_operands</a>, <a href="#a564aa23c9a5cf95820535f59182aedd4">getOneDef</a>, <a href="#af2a209ffefa8ca1df76b99fe3c2e2cc4">isPhysRegModified</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a69189b7d95c4b78145d9dc25a3de148b">MustSaveLR</a>.</p>

</div>
</div>

### def\_instr\_end() {#a54dd0a5ebf7dbe5aab5fe51979356645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">def_instr_iterator llvm::MachineRegisterInfo::def_instr_end ()</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a415a4642beaee4a3156251faaacab646">def_instructions</a>, <a href="#af988c2b4f62506108843a0fdc04b43a2">getUniqueVRegDef</a> and <a href="#a40d954b9cf9ee8b545a78725f2549cba">getVRegDef</a>.</p>

</div>
</div>

### reg\_bundle\_end() {#ab05bea8bf7513acba82ca339c74de2de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_bundle_iterator llvm::MachineRegisterInfo::reg_bundle_end ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a0e05a48717dda8a0ca99449587367660">reg_bundles</a>.</p>

</div>
</div>

### reg\_bundle\_nodbg\_end() {#a94275a1edd38ff90ce524665a268d71e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_bundle_nodbg_iterator llvm::MachineRegisterInfo::reg_bundle_nodbg_end ()</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a52760341a18bcab24705161c498aa6f5">reg_nodbg_bundles</a>.</p>

</div>
</div>

### reg\_end() {#a1d8edf72c1d3e14e4d2396b98e07ad72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_iterator llvm::MachineRegisterInfo::reg_end ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aecfd94e60d64656d8b19f2ea69bb02af">reg_empty</a> and <a href="#a26ee456cc6716cfbc16261e544100b12">reg_operands</a>.</p>

</div>
</div>

### reg\_instr\_end() {#a45911f3aacb9b7ea62d1fa8fc8180039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_instr_iterator llvm::MachineRegisterInfo::reg_instr_end ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aa7bc06ec30359044cffdc3ccd58bfacf">reg_instructions</a>.</p>

</div>
</div>

### reg\_instr\_nodbg\_end() {#a29a1144eb9d753b6b682a933aa3f8f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_instr_nodbg_iterator llvm::MachineRegisterInfo::reg_instr_nodbg_end ()</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ae916811c548f67c9ed178fa8a38ac7f1">reg_nodbg_instructions</a>.</p>

</div>
</div>

### reg\_nodbg\_end() {#a728707da8d5c6832316ff91231f3c2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg_nodbg_iterator llvm::MachineRegisterInfo::reg_nodbg_end ()</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a666dc30b9326da6b9e69740a241df89d">reg_nodbg_empty</a> and <a href="#ac055593361bdcb9d0093f0881ce7f286">reg_nodbg_operands</a>.</p>

</div>
</div>

### use\_bundle\_end() {#a6d9cb3eb3b146477bb4a708a246607be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_bundle_iterator llvm::MachineRegisterInfo::use_bundle_end ()</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aef898731887fc99f3a5e62710cb5bade">use_bundles</a>.</p>

</div>
</div>

### use\_bundle\_nodbg\_end() {#aacc6af82327a6f208f586e90cc48dbed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_bundle_nodbg_iterator llvm::MachineRegisterInfo::use_bundle_nodbg_end ()</td>
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



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a5aa433099910dc844bc8466933779e58">use_nodbg_bundles</a>.</p>

</div>
</div>

### use\_end() {#ac8347c6938efe4d9a4426b92ef57851e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_iterator llvm::MachineRegisterInfo::use_end ()</td>
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



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#aeae86e9004476412ca754a7de4ee8a0c">use_empty</a> and <a href="#ade188fadae5a455fcc4bd8d70142851d">use_operands</a>.</p>

</div>
</div>

### use\_instr\_end() {#a7a73104304bf1f9d344ad495283561b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_instr_iterator llvm::MachineRegisterInfo::use_instr_end ()</td>
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



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ab1c2de27f8d8c4a7de72d6415952473f">use_instructions</a>.</p>

</div>
</div>

### use\_instr\_nodbg\_end() {#afb1fd76e39ba4dfa2c428df88bbc82c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_instr_nodbg_iterator llvm::MachineRegisterInfo::use_instr_nodbg_end ()</td>
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



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a7a0d4a6526dc873f6af0b248247bc503">hasAtMostUserInstrs</a> and <a href="#a8c1a48aa3d3155a0e942c785932d9723">use_nodbg_instructions</a>.</p>

</div>
</div>

### use\_nodbg\_end() {#a355ba266da19094cc0948311c431768e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">use_nodbg_iterator llvm::MachineRegisterInfo::use_nodbg_end ()</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a4ea277721b4e63804715a62de87e9a72">use_nodbg_empty</a> and <a href="#a4361906d7698e8b1a912f6affc8e9151">use_nodbg_operands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getNextOperandForReg() {#a14be32fb294c8c36086ff9d3f79cb6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand * llvm::MachineRegisterInfo::getNextOperandForReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO)</td>
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

<p>Get the next element in the use-def chain.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">MachineRegisterInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp">MachineRegisterInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
