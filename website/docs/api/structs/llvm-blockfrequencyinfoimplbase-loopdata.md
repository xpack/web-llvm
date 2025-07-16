---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/blockfrequencyinfoimplbase/loopdata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoopData` Struct Reference

<p>Data about a loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BlockFrequencyInfoImplBase::LoopData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10dc52ff31fcd31570d45b100ed2ca6b">ExitMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a6e6da6d64b5e1623157336544dd0e7a2">BlockMass</a> &gt;, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65e3fb654afaaf83662b2b46d8d20043">NodeList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a>, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bca9720bb542e351f79ffb5b4ef2a0d">HeaderMassList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a6e6da6d64b5e1623157336544dd0e7a2">BlockMass</a>, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb4a78fac5f3140664755105ac9c88d">LoopData</a> (LoopData *Parent, const BlockNode &amp;Header)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class It1, class It2&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a22d50a8b1983e65e8d2a8702a53744ec">LoopData</a> (LoopData *Parent, It1 FirstHeader, It1 LastHeader, It2 FirstOther, It2 LastOther)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f46dabedb551531591c0293403c7e21">isHeader</a> (const BlockNode &amp;Node) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a924395e7510f57f986ac032994b20f73">getHeader</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8884f4ab1dd22269ce25837403cbb726">isIrreducible</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#abaf002eb85f45e089d3bd802d8d1466b">HeaderMassList::difference_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed6828c6f5229e4099a34c13da1d2d08">getHeaderIndex</a> (const BlockNode &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">NodeList::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71009a39b531a375cc98f0ccd6929930">members_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">NodeList::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ed2496529a208a7c56b27ad11b01030">members_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">NodeList::const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee4e645edd16cde1ab617462b920ea53">members</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">LoopData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190e68049654c31350c9c3a5df2eee1d">Parent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The parent loop. <a href="#a190e68049654c31350c9c3a5df2eee1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a1365a0e73d71419aad3e55da8c2cb5">IsPackaged</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this has been packaged. <a href="#a3a1365a0e73d71419aad3e55da8c2cb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39cbaa6b41acd43e7cddcc9fa110557f">NumHeaders</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of headers. <a href="#a39cbaa6b41acd43e7cddcc9fa110557f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a10dc52ff31fcd31570d45b100ed2ca6b">ExitMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ba9de56719382167db6112ba3d0b056">Exits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Successor edges (and weights). <a href="#a2ba9de56719382167db6112ba3d0b056">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a65e3fb654afaaf83662b2b46d8d20043">NodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa694a8c0f8d2a04ac086fc4217615367">Nodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Header and the members of the loop. <a href="#aa694a8c0f8d2a04ac086fc4217615367">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9bca9720bb542e351f79ffb5b4ef2a0d">HeaderMassList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7119657849326a17e7ada6cb242c288">BackedgeMass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mass returned to each loop header. <a href="#ac7119657849326a17e7ada6cb242c288">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a6e6da6d64b5e1623157336544dd0e7a2">BlockMass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73ca2f65c4077446cdeb9c8461fd118">Mass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a5514a17c0ec3ccae841930a4f8f74f99">Scaled64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc333c186999469beac266c7b17870d">Scale</a></td>
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

<p>Data about a loop.</p>


<p>Contains the data necessary to represent a loop as a pseudo-node once it's packaged.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ExitMap {#a10dc52ff31fcd31570d45b100ed2ca6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlockFrequencyInfoImplBase::LoopData::ExitMap =  SmallVector&lt;std::pair&lt;BlockNode, BlockMass&gt;, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

### HeaderMassList {#a9bca9720bb542e351f79ffb5b4ef2a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlockFrequencyInfoImplBase::LoopData::HeaderMassList =  SmallVector&lt;BlockMass, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

### NodeList {#a65e3fb654afaaf83662b2b46d8d20043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlockFrequencyInfoImplBase::LoopData::NodeList =  SmallVector&lt;BlockNode, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoopData() {#a5bb4a78fac5f3140664755105ac9c88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BlockFrequencyInfoImplBase::LoopData::LoopData (<a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">LoopData</a> * Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a> &amp; Header)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#ac7119657849326a17e7ada6cb242c288">BackedgeMass</a>, <a href="#a5bb4a78fac5f3140664755105ac9c88d">LoopData</a>, <a href="#aa694a8c0f8d2a04ac086fc4217615367">Nodes</a> and <a href="#a190e68049654c31350c9c3a5df2eee1d">Parent</a>.</p>


<p>Referenced by <a href="#a5bb4a78fac5f3140664755105ac9c88d">LoopData</a> and <a href="#a22d50a8b1983e65e8d2a8702a53744ec">LoopData</a>.</p>

</div>
</div>

### LoopData() {#a22d50a8b1983e65e8d2a8702a53744ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class It1, class It2&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BlockFrequencyInfoImplBase::LoopData::LoopData (<a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">LoopData</a> * Parent, It1 FirstHeader, It1 LastHeader, It2 FirstOther, It2 LastOther)</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#ac7119657849326a17e7ada6cb242c288">BackedgeMass</a>, <a href="#a5bb4a78fac5f3140664755105ac9c88d">LoopData</a>, <a href="#aa694a8c0f8d2a04ac086fc4217615367">Nodes</a>, <a href="#a39cbaa6b41acd43e7cddcc9fa110557f">NumHeaders</a> and <a href="#a190e68049654c31350c9c3a5df2eee1d">Parent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getHeader() {#a924395e7510f57f986ac032994b20f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockNode llvm::BlockFrequencyInfoImplBase::LoopData::getHeader ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="#aa694a8c0f8d2a04ac086fc4217615367">Nodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/#add4c9ca63093a8270248e72b08c5302e">llvm::bfi_detail::IrreducibleGraph::addNodesInLoop</a>.</p>

</div>
</div>

### getHeaderIndex() {#aed6828c6f5229e4099a34c13da1d2d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HeaderMassList::difference_type llvm::BlockFrequencyInfoImplBase::LoopData::getHeaderIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a> &amp; B)</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a0f46dabedb551531591c0293403c7e21">isHeader</a>, <a href="#a8884f4ab1dd22269ce25837403cbb726">isIrreducible</a>, <a href="#aa694a8c0f8d2a04ac086fc4217615367">Nodes</a> and <a href="#a39cbaa6b41acd43e7cddcc9fa110557f">NumHeaders</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#adda9f21a68ad40aac3ee4e0bf3afa31d">llvm::BlockFrequencyInfoImplBase::distributeMass</a>.</p>

</div>
</div>

### isHeader() {#a0f46dabedb551531591c0293403c7e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::LoopData::isHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BlockNode</a> &amp; Node)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#a8884f4ab1dd22269ce25837403cbb726">isIrreducible</a>, <a href="#aa694a8c0f8d2a04ac086fc4217615367">Nodes</a> and <a href="#a39cbaa6b41acd43e7cddcc9fa110557f">NumHeaders</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/#a17262e1cca3f9a69224d04b3189ed90c">llvm::bfi_detail::IrreducibleGraph::addEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#aac32cd773a37b10c8f835459a23ac606">llvm::BlockFrequencyInfoImplBase::addToDist</a> and <a href="#aed6828c6f5229e4099a34c13da1d2d08">getHeaderIndex</a>.</p>

</div>
</div>

### isIrreducible() {#a8884f4ab1dd22269ce25837403cbb726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::LoopData::isIrreducible ()</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="#a39cbaa6b41acd43e7cddcc9fa110557f">NumHeaders</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#aac32cd773a37b10c8f835459a23ac606">llvm::BlockFrequencyInfoImplBase::addToDist</a>, <a href="#aed6828c6f5229e4099a34c13da1d2d08">getHeaderIndex</a> and <a href="#a0f46dabedb551531591c0293403c7e21">isHeader</a>.</p>

</div>
</div>

### members() {#aee4e645edd16cde1ab617462b920ea53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; NodeList::const_iterator &gt; llvm::BlockFrequencyInfoImplBase::LoopData::members ()</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a71009a39b531a375cc98f0ccd6929930">members_begin</a> and <a href="#a6ed2496529a208a7c56b27ad11b01030">members_end</a>.</p>

</div>
</div>

### members\_begin() {#a71009a39b531a375cc98f0ccd6929930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList::const_iterator llvm::BlockFrequencyInfoImplBase::LoopData::members_begin ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#aa694a8c0f8d2a04ac086fc4217615367">Nodes</a> and <a href="#a39cbaa6b41acd43e7cddcc9fa110557f">NumHeaders</a>.</p>


<p>Referenced by <a href="#aee4e645edd16cde1ab617462b920ea53">members</a>.</p>

</div>
</div>

### members\_end() {#a6ed2496529a208a7c56b27ad11b01030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList::const_iterator llvm::BlockFrequencyInfoImplBase::LoopData::members_end ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="#aa694a8c0f8d2a04ac086fc4217615367">Nodes</a>.</p>


<p>Referenced by <a href="#aee4e645edd16cde1ab617462b920ea53">members</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BackedgeMass {#ac7119657849326a17e7ada6cb242c288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HeaderMassList llvm::BlockFrequencyInfoImplBase::LoopData::BackedgeMass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mass returned to each loop header.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#adda9f21a68ad40aac3ee4e0bf3afa31d">llvm::BlockFrequencyInfoImplBase::distributeMass</a>, <a href="#a5bb4a78fac5f3140664755105ac9c88d">LoopData</a>, <a href="#a22d50a8b1983e65e8d2a8702a53744ec">LoopData</a> and <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a8fcc33897ff2ea4ebc874792c49497ef">llvm::BlockFrequencyInfoImplBase::updateLoopWithIrreducible</a>.</p>

</div>
</div>

### Exits {#a2ba9de56719382167db6112ba3d0b056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExitMap llvm::BlockFrequencyInfoImplBase::LoopData::Exits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Successor edges (and weights).</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#adda9f21a68ad40aac3ee4e0bf3afa31d">llvm::BlockFrequencyInfoImplBase::distributeMass</a> and <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a8fcc33897ff2ea4ebc874792c49497ef">llvm::BlockFrequencyInfoImplBase::updateLoopWithIrreducible</a>.</p>

</div>
</div>

### IsPackaged {#a3a1365a0e73d71419aad3e55da8c2cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequencyInfoImplBase::LoopData::IsPackaged = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this has been packaged.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

### Mass {#ac73ca2f65c4077446cdeb9c8461fd118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass llvm::BlockFrequencyInfoImplBase::LoopData::Mass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

### Nodes {#aa694a8c0f8d2a04ac086fc4217615367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList llvm::BlockFrequencyInfoImplBase::LoopData::Nodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Header and the members of the loop.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/#add4c9ca63093a8270248e72b08c5302e">llvm::bfi_detail::IrreducibleGraph::addNodesInLoop</a>, <a href="#a924395e7510f57f986ac032994b20f73">getHeader</a>, <a href="#aed6828c6f5229e4099a34c13da1d2d08">getHeaderIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/#abe3bf5fccbd988d1daf97da30f0b0456">llvm::bfi_detail::IrreducibleGraph::initialize</a>, <a href="#a0f46dabedb551531591c0293403c7e21">isHeader</a>, <a href="#a5bb4a78fac5f3140664755105ac9c88d">LoopData</a>, <a href="#a22d50a8b1983e65e8d2a8702a53744ec">LoopData</a>, <a href="#a71009a39b531a375cc98f0ccd6929930">members_begin</a>, <a href="#a6ed2496529a208a7c56b27ad11b01030">members_end</a> and <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a8fcc33897ff2ea4ebc874792c49497ef">llvm::BlockFrequencyInfoImplBase::updateLoopWithIrreducible</a>.</p>

</div>
</div>

### NumHeaders {#a39cbaa6b41acd43e7cddcc9fa110557f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BlockFrequencyInfoImplBase::LoopData::NumHeaders = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of headers.</p>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#aed6828c6f5229e4099a34c13da1d2d08">getHeaderIndex</a>, <a href="#a0f46dabedb551531591c0293403c7e21">isHeader</a>, <a href="#a8884f4ab1dd22269ce25837403cbb726">isIrreducible</a>, <a href="#a22d50a8b1983e65e8d2a8702a53744ec">LoopData</a> and <a href="#a71009a39b531a375cc98f0ccd6929930">members_begin</a>.</p>

</div>
</div>

### Parent {#a190e68049654c31350c9c3a5df2eee1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopData* llvm::BlockFrequencyInfoImplBase::LoopData::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The parent loop.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#a5bb4a78fac5f3140664755105ac9c88d">LoopData</a> and <a href="#a22d50a8b1983e65e8d2a8702a53744ec">LoopData</a>.</p>

</div>
</div>

### Scale {#afbc333c186999469beac266c7b17870d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scaled64 llvm::BlockFrequencyInfoImplBase::LoopData::Scale</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
