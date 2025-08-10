---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/virtreginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `VirtRegInfo` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/virtreginfo">VirtRegInfo</a> - Information about a virtual register used by a set of operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VirtRegInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">llvm/CodeGen/MachineInstrBundle.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0066fe4418e8c4c6c08dd9a9f2ee70e7">Reads</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads - One of the operands read the virtual register. <a href="#a0066fe4418e8c4c6c08dd9a9f2ee70e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf7a0d275502415bb724169baf061638">Writes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes - One of the operands writes the virtual register. <a href="#acf7a0d275502415bb724169baf061638">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a3349f5396be814b455f5f3a01f4efe">Tied</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tied - Uses and defs must use the same register. <a href="#a5a3349f5396be814b455f5f3a01f4efe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/virtreginfo">VirtRegInfo</a> - Information about a virtual register used by a set of operands.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Reads {#a0066fe4418e8c4c6c08dd9a9f2ee70e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VirtRegInfo::Reads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reads - One of the operands read the virtual register.</p>


<p>This does not include undef or internal use operands, see MO::readsReg().</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>.</p>

</div>
</div>

### Tied {#a5a3349f5396be814b455f5f3a01f4efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VirtRegInfo::Tied</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tied - Uses and defs must use the same register.</p>


<p>This can be because of a two-address constraint, or there may be a partial redefinition of a sub-register.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a>.</p>

</div>
</div>

### Writes {#acf7a0d275502415bb724169baf061638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VirtRegInfo::Writes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes - One of the operands writes the virtual register.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
