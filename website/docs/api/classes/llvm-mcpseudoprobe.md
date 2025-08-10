---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcpseudoprobe
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCPseudoProbe` Class

<p>Instances of this class represent a pseudo probe instance for a pseudo probe table entry, which is created during a machine instruction is assembled and uses an address from a temporary label created at the current address in the current section. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCPseudoProbe { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">llvm/MC/MCPseudoProbe.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase">MCPseudoProbeBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a510fa767816bb9bf49b3481443e2059e">MCPseudoProbe</a> (MCSymbol *Label, uint64_t Guid, uint64_t Index, uint64_t Type, uint64_t Attributes, uint32_t Discriminator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80938ec88b3fed6ea902e4dbfc27b3f0">getGuid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a428f8085706edfc603f342290a10c9a8">getLabel</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fbe96db8448f1711fd51c4f4601c063">emit</a> (MCObjectStreamer *MCOS, const MCPseudoProbe *LastProbe) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b981addcd6dd6df2be3b3559c0fce2">Guid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ed20e3913820d50a1d8aa73a938302">Label</a></td>
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

<p>Instances of this class represent a pseudo probe instance for a pseudo probe table entry, which is created during a machine instruction is assembled and uses an address from a temporary label created at the current address in the current section.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCPseudoProbe() {#a510fa767816bb9bf49b3481443e2059e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCPseudoProbe::MCPseudoProbe (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Label, uint64_t Guid, uint64_t Index, uint64_t Type, uint64_t Attributes, uint32_t Discriminator)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a62d03dfbbe45890039b24550191312de">llvm::MCPseudoProbeBase::Attributes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#ac2962e7b46982f2148b7f1743c1ac16b">llvm::MCPseudoProbeBase::Discriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a6e8d573f07368c01f32a8160e9ca4f2a">llvm::MCPseudoProbeBase::Index</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a862d55c2dffff38a8507d9bd8d443c36">llvm::MCPseudoProbeBase::MCPseudoProbeBase</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a578a904af332f58d3a5a749936ddc40d">llvm::MCPseudoProbeBase::Type</a>.</p>


<p>Referenced by <a href="#a4fbe96db8448f1711fd51c4f4601c063">emit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a4fbe96db8448f1711fd51c4f4601c063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCPseudoProbe::emit (<a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a> * MCOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe">MCPseudoProbe</a> * LastProbe)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac921cd963df34df697fa6d656e920760a8a6af6bba3f8532a26ae3958dae60f8a">llvm::AddressDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aed79db19d00f742ef88eafad5b074be0">llvm::MCContext::allocFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a62d03dfbbe45890039b24550191312de">llvm::MCPseudoProbeBase::Attributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcobjectstreamer-cpp/#a4303712ca7aca04be8e4a7d4499c65c9">buildSymbolDiff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobetable/#ad089579699154832e852448b566c2704">llvm::MCPseudoProbeTable::DdgPrintIndent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#ac2962e7b46982f2148b7f1743c1ac16b">llvm::MCPseudoProbeBase::Discriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac46413fa6b39176f78fc9621a08af7a5">llvm::MCStreamer::emitInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af47540299db471532b82aba9314f1fc2">llvm::MCStreamer::emitInt8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e">llvm::MCStreamer::emitSLEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a866922b584e8d73ad86444255886c82c">llvm::MCObjectStreamer::getAssemblerPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a7406e132355fb05ec16185d804e04b73">llvm::MCPseudoProbeBase::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="#a428f8085706edfc603f342290a10c9a8">getLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae9dabebeb083ad5885642b5e6a84c9c0ada9b2db60a199029ae58a1acb9cb87dd">llvm::HasDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a6e8d573f07368c01f32a8160e9ca4f2a">llvm::MCPseudoProbeBase::Index</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a192529d3a199cfe369f7428545340e76">llvm::isSentinelProbe</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a510fa767816bb9bf49b3481443e2059e">MCPseudoProbe</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobebase/#a578a904af332f58d3a5a749936ddc40d">llvm::MCPseudoProbeBase::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#a803da0fccbb98b7ceaf9240f55fa69b6">llvm::MCPseudoProbeInlineTree::emit</a>.</p>

</div>
</div>

### getGuid() {#a80938ec88b3fed6ea902e4dbfc27b3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCPseudoProbe::getGuid ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#ad1246639c464dee99101df3e7c1c4dc8">llvm::MCPseudoProbeInlineTree::addPseudoProbe</a> and <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#a803da0fccbb98b7ceaf9240f55fa69b6">llvm::MCPseudoProbeInlineTree::emit</a>.</p>

</div>
</div>

### getLabel() {#a428f8085706edfc603f342290a10c9a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MCPseudoProbe::getLabel ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>


<p>Referenced by <a href="#a4fbe96db8448f1711fd51c4f4601c063">emit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Guid {#af9b981addcd6dd6df2be3b3559c0fce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MCPseudoProbe::Guid</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

### Label {#ae4ed20e3913820d50a1d8aa73a938302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCPseudoProbe::Label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcpseudoprobe-h">MCPseudoProbe.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcpseudoprobe-cpp">MCPseudoProbe.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
