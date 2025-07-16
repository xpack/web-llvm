---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcdwarflineentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCDwarfLineEntry` Class Reference

<p>Instances of this class represent the line information for the dwarf line table entries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCDwarfLineEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdwarfloc">MCDwarfLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instances of this class represent the information from a dwarf .loc directive. <a href="/web-llvm/docs/api/classes/llvm/mcdwarfloc/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dcfa3ab1adc342583880115c513acbe">MCDwarfLineEntry</a> (MCSymbol *label, const MCDwarfLoc loc, MCSymbol *lineStreamLabel=nullptr, SMLoc streamLabelDefLoc={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542e541deb89a458ca210c97a9bca553">getLabel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a306f5bdb6bb0809cff6c23583704323a">setEndLabel</a> (MCSymbol *EndLabel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b8eac47c222ca5ec0b30b563ad69bd0">LineStreamLabel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22ac922757cac95073f6efe2f8a081b">StreamLabelDefLoc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7173f6f1f9c86ab353cd63bdb89e0ded">IsEndEntry</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46645f9c349e15d8174decf486de2c8e">Label</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7c37719e68c7bf9e494110a30cad90">make</a> (MCStreamer *MCOS, MCSection *Section)</td>
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

<p>Instances of this class represent the line information for the dwarf line table entries.</p>


<p>Which is created after a machine instruction is assembled and uses an address from a temporary label created at the current address in the current section and the info from the last .loc directive seen as stored in the context.</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCDwarfLineEntry() {#a6dcfa3ab1adc342583880115c513acbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCDwarfLineEntry::MCDwarfLineEntry (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * label, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdwarfloc">MCDwarfLoc</a> loc, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * lineStreamLabel=nullptr, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> streamLabelDefLoc={})</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#a7e7c37719e68c7bf9e494110a30cad90">make</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getLabel() {#a542e541deb89a458ca210c97a9bca553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MCDwarfLineEntry::getLabel ()</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### setEndLabel() {#a306f5bdb6bb0809cff6c23583704323a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCDwarfLineEntry::setEndLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EndLabel)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Reference <a href="#a7173f6f1f9c86ab353cd63bdb89e0ded">IsEndEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsEndEntry {#a7173f6f1f9c86ab353cd63bdb89e0ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfLineEntry::IsEndEntry = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<p>Referenced by <a href="#a306f5bdb6bb0809cff6c23583704323a">setEndLabel</a>.</p>

</div>
</div>

### LineStreamLabel {#a7b8eac47c222ca5ec0b30b563ad69bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCDwarfLineEntry::LineStreamLabel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### StreamLabelDefLoc {#aa22ac922757cac95073f6efe2f8a081b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::MCDwarfLineEntry::StreamLabelDefLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Label {#a46645f9c349e15d8174decf486de2c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCDwarfLineEntry::Label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### make() {#a7e7c37719e68c7bf9e494110a30cad90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDwarfLineEntry::make (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section)</td>
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



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mclinesection/#adb3f95e8068932c0460a81a45224d0c5">llvm::MCLineSection::addLineEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a533301811e7317a14fd07d84073590ee">llvm::MCContext::clearDwarfLocSeen</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae2fe3b101fb1f6389502b5d4f99c0640">llvm::MCContext::getCurrentDwarfLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a6aabd162418263d017e3559978931451">llvm::MCContext::getDwarfCompileUnitID</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a285982216c5eb361f38a33f46ed2f124">llvm::MCContext::getDwarfLocSeen</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a62f7e21c9dac9e7acb4fdd713e712d20">llvm::MCContext::getMCDwarfLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a66906cd74b89bb0c1599d37b1188f820">llvm::MCDwarfLineTable::getMCLineSections</a> and <a href="#a6dcfa3ab1adc342583880115c513acbe">MCDwarfLineEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#ae7819cf4c91db139508a49f5e0401243">llvm::DwarfDebug::beginCodeAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a66d51c3585e4733b99bb8d3e3eb2bb81">llvm::MCObjectStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#afbf8b87c2743700b4bc2f187d06c9a28">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ac90a78b45f28148cbab53747e0eba695">llvm::MCObjectStreamer::emitDwarfLocDirective</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a161ac460fefc16f98a8dd1a9f019af9a">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
