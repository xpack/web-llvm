---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/machobuilder/reloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Reloc` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::MachOBuilder::Reloc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">llvm/ExecutionEngine/Orc/MachOBuilder.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info">relocation_info</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84dbd555a755b7aff282a736b861afdb">Reloc</a> (int32_t Offset, RelocTarget Target, bool PCRel, unsigned Length, unsigned Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info">MachO::relocation_info</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16c52622e48afe689105f6d761f4f8d">rawStruct</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget">RelocTarget</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a881574cbed62b2466a0caa5e9b08fa91">Target</a></td>
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


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Reloc() {#a84dbd555a755b7aff282a736b861afdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Reloc::Reloc (int32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/orc/machobuilder/reloctarget">RelocTarget</a> Target, bool PCRel, unsigned Length, unsigned Type)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info/#afae7745c0dbeaba604d0e6871ff6ff94">llvm::MachO::relocation_info::r_address</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info/#a2e5895317d1febfec8fd6cf44069ca30">llvm::MachO::relocation_info::r_extern</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info/#ad718c499097adbe1f3b1906f6cbf79f5">llvm::MachO::relocation_info::r_length</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info/#a2036c0144fe63c94a74720c7c105cbd5">llvm::MachO::relocation_info::r_pcrel</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info/#ae8634f4afac899abde624f4f32698a9d">llvm::MachO::relocation_info::r_symbolnum</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info/#a564ac171976e46aeee433cb4e2c7d34e">llvm::MachO::relocation_info::r_type</a> and <a href="#a881574cbed62b2466a0caa5e9b08fa91">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Reloc::Target</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### rawStruct() {#aa16c52622e48afe689105f6d761f4f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::relocation_info &amp; llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Reloc::rawStruct ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Target {#a881574cbed62b2466a0caa5e9b08fa91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RelocTarget llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Reloc::Target</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a>.</p>


<p>Referenced by <a href="#a84dbd555a755b7aff282a736b861afdb">llvm::orc::MachOBuilder&lt; MachOTraits &gt;::Reloc::Reloc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machobuilder-h">MachOBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
