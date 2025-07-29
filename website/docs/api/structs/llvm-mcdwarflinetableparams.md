---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcdwarflinetableparams
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MCDwarfLineTableParams` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::MCDwarfLineTableParams { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa098ab41af3f8cee8b1939003d55a776">DWARF2LineOpcodeBase</a> = 13</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>First special line opcode - leave room for the standard opcodes. <a href="#aa098ab41af3f8cee8b1939003d55a776">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afddded28f79b1eccb3a948a4bdd0f6a3">DWARF2LineBase</a> = -5</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Minimum line offset in a special line info. <a href="#afddded28f79b1eccb3a948a4bdd0f6a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75e30002379b9f61625bc8d2b4b1919">DWARF2LineRange</a> = 14</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Range of line offsets in a special line info. opcode. <a href="#ac75e30002379b9f61625bc8d2b4b1919">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### DWARF2LineBase {#afddded28f79b1eccb3a948a4bdd0f6a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int8_t llvm::MCDwarfLineTableParams::DWARF2LineBase = -5</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Minimum line offset in a special line info.</p>


<p>opcode. The value -5 was chosen to give a reasonable range of values.</p>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#ae0f19d1d97309d2c250054dae4569622">llvm::MCDwarfLineAddr::encode</a>.</p>

</div>
</div>

### DWARF2LineOpcodeBase {#aa098ab41af3f8cee8b1939003d55a776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MCDwarfLineTableParams::DWARF2LineOpcodeBase = 13</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>First special line opcode - leave room for the standard opcodes.</p>


<p>Note: If you want to change this, you'll have to update the "StandardOpcodeLengths" table that is emitted in <span class="doxyComputerOutput">Emit()</span>.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a90af7c354814308d90b77d5e412f02b4">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#ae0f19d1d97309d2c250054dae4569622">llvm::MCDwarfLineAddr::encode</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1a45bf6d0fbef0afa6304a0a90d4cc7c">SpecialAddr</a>.</p>

</div>
</div>

### DWARF2LineRange {#ac75e30002379b9f61625bc8d2b4b1919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MCDwarfLineTableParams::DWARF2LineRange = 14</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Range of line offsets in a special line info. opcode.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#ae0f19d1d97309d2c250054dae4569622">llvm::MCDwarfLineAddr::encode</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1a45bf6d0fbef0afa6304a0a90d4cc7c">SpecialAddr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
