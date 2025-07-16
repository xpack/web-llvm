---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf/formparams
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FormParams` Struct Reference

<p>A helper struct providing information about the byte size of DW_FORM values that vary in size depending on the DWARF version, address byte size, or DWARF32/DWARF64. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf::FormParams { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942d3c0f09928a13c3ec46d656ae8255">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6385ddcd0042b7b98875ab684a115f2e">getRefAddrByteSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The definition of the size of form DW_FORM_ref_addr depends on the version. <a href="#a6385ddcd0042b7b98875ab684a115f2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a235a5f4eedbfa7b5583ba320309d408f">getDwarfOffsetByteSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The size of a reference is determined by the DWARF 32/64-bit format. <a href="#a235a5f4eedbfa7b5583ba320309d408f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b29c3ef444fa08597f89401a2ba1e8">Version</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6892519cfb3ec739ebd611d7bd82ea2e">AddrSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1240b89e7d83c52d9b2dc05ad8824269">Format</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e72e5d6b3bf30f8a73b227907d3b071">DwarfUsesRelocationsAcrossSections</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if DWARF v2 output generally uses relocations for references to other .debug_* sections. <a href="#a0e72e5d6b3bf30f8a73b227907d3b071">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A helper struct providing information about the byte size of DW_FORM values that vary in size depending on the DWARF version, address byte size, or DWARF32/DWARF64.</p>

<p>Definition at line 1084 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator bool() {#a942d3c0f09928a13c3ec46d656ae8255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf::FormParams::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>References <a href="#a6892519cfb3ec739ebd611d7bd82ea2e">AddrSize</a> and <a href="#ae6b29c3ef444fa08597f89401a2ba1e8">Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDwarfOffsetByteSize() {#a235a5f4eedbfa7b5583ba320309d408f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::dwarf::FormParams::getDwarfOffsetByteSize ()</td>
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

<p>The size of a reference is determined by the DWARF 32/64-bit format.</p>

<p>Definition at line 1102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>References <a href="#a1240b89e7d83c52d9b2dc05ad8824269">Format</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter/#a81feed7a90b5abc9e58b574e7da2a360">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa03b0ad8792b784269332332eb61d8ad">llvm::dwarf::getFixedFormByteSize</a>, <a href="#a6385ddcd0042b7b98875ab684a115f2e">getRefAddrByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/diedelta/#a9c2b9bacaa9feebc952cf7bfdfad55bc">llvm::DIEDelta::sizeOf</a>, <a href="/web-llvm/docs/api/classes/llvm/dieexpr/#ae0988a2004d446c7a2124ee802eb6b62">llvm::DIEExpr::sizeOf</a>, <a href="/web-llvm/docs/api/classes/llvm/dielabel/#ab97161e774404eb79c753041676ee5fc">llvm::DIELabel::sizeOf</a>, <a href="/web-llvm/docs/api/classes/llvm/dieloclist/#a85cc7db4ff8a76c90c52e9d232250f18">llvm::DIELocList::sizeOf</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>.</p>

</div>
</div>

### getRefAddrByteSize() {#a6385ddcd0042b7b98875ab684a115f2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::dwarf::FormParams::getRefAddrByteSize ()</td>
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

<p>The definition of the size of form DW_FORM_ref_addr depends on the version.</p>


<p>In DWARF v2 it's the size of an address; after that, it's the size of a reference.</p>


<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>References <a href="#a6892519cfb3ec739ebd611d7bd82ea2e">AddrSize</a>, <a href="#a235a5f4eedbfa7b5583ba320309d408f">getDwarfOffsetByteSize</a> and <a href="#ae6b29c3ef444fa08597f89401a2ba1e8">Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa03b0ad8792b784269332332eb61d8ad">llvm::dwarf::getFixedFormByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dieentry/#a9ef2361da2ab2fbae77c373feac0dd97">llvm::DIEEntry::sizeOf</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddrSize {#a6892519cfb3ec739ebd611d7bd82ea2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::dwarf::FormParams::AddrSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa03b0ad8792b784269332332eb61d8ad">llvm::dwarf::getFixedFormByteSize</a>, <a href="#a6385ddcd0042b7b98875ab684a115f2e">getRefAddrByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="#a942d3c0f09928a13c3ec46d656ae8255">operator bool</a>, <a href="/web-llvm/docs/api/classes/llvm/dielabel/#ab97161e774404eb79c753041676ee5fc">llvm::DIELabel::sizeOf</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>.</p>

</div>
</div>

### DwarfUsesRelocationsAcrossSections {#a0e72e5d6b3bf30f8a73b227907d3b071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf::FormParams::DwarfUsesRelocationsAcrossSections = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if DWARF v2 output generally uses relocations for references to other .debug_* sections.</p>

<p>Definition at line 1090 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diestring/#ab3e002a61d2a5203c2f67221b69172be">llvm::DIEString::sizeOf</a>.</p>

</div>
</div>

### Format {#a1240b89e7d83c52d9b2dc05ad8824269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfFormat llvm::dwarf::FormParams::Format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#ad43ae71d8137d5a78d559644f17eb162">llvm::dwarf_linker::classic::DwarfStreamer::emitLineTableForUnit</a>, <a href="#a235a5f4eedbfa7b5583ba320309d408f">getDwarfOffsetByteSize</a> and <a href="/web-llvm/docs/api/classes/llvm/dieloclist/#a85cc7db4ff8a76c90c52e9d232250f18">llvm::DIELocList::sizeOf</a>.</p>

</div>
</div>

### Version {#ae6b29c3ef444fa08597f89401a2ba1e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::dwarf::FormParams::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a>.</p>


<p>Referenced by <a href="#a6385ddcd0042b7b98875ab684a115f2e">getRefAddrByteSize</a> and <a href="#a942d3c0f09928a13c3ec46d656ae8255">operator bool</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">Dwarf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
