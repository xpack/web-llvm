---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfdebugaranges
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFDebugAranges` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DWARFDebugAranges { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">llvm/DebugInfo/DWARF/DWARFDebugAranges.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a16d220958a0421f43c8304bb8ec52a">RangeColl</a> = std::vector&lt; Range &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef8a7c12035bb372fe524cc34ed2805">RangeCollIterator</a> = RangeColl::const_iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc33f3dabfc507904e9fdfa7b0d81b51">generate</a> (DWARFContext *CTX)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5bd8d6e5b48e67cdd897f650afeda9f">findAddress</a> (uint64_t Address) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b354147c43a3222f8b37950f4f8127a">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8addde2668cd0f7afac10babaf2f98">extract</a> (DWARFDataExtractor DebugArangesData, function_ref&lt; void(Error)&gt; RecoverableErrorHandler, function_ref&lt; void(Error)&gt; WarningHandler)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae558e99597701d19c1ef7aa186b13a3b">appendRange</a> (uint64_t CUOffset, uint64_t LowPC, uint64_t HighPC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call appendRange multiple times and then call construct. <a href="#ae558e99597701d19c1ef7aa186b13a3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f67b92af47aa81c4c82ffae87e5954f">construct</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; RangeEndpoint &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad0db13cab5a594b2c5bd1a98bd7152">Endpoints</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RangeColl</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa3c57ca6ff724bd991fdddabedadd3">Aranges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3042ccd95dd23d586107e7de0e1d1084">ParsedCUOffsets</a></td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### RangeColl {#a1a16d220958a0421f43c8304bb8ec52a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFDebugAranges::RangeColl =  std::vector&lt;Range&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>.</p>

</div>
</div>

### RangeCollIterator {#a0ef8a7c12035bb372fe524cc34ed2805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFDebugAranges::RangeCollIterator =  RangeColl::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findAddress() {#ad5bd8d6e5b48e67cdd897f650afeda9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DWARFDebugAranges::findAddress (uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugaranges-cpp">DWARFDebugAranges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a327a399b9f6ef414a29ddeffba934d26">llvm::partition_point</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a000efe430c85d8454e4ff9e74acb30bf">llvm::DWARFContext::getCompileUnitForCodeAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a3a5cda98effd5b8f70b493af97124ff6">llvm::DWARFContext::getCompileUnitForDataAddress</a>.</p>

</div>
</div>

### generate() {#acc33f3dabfc507904e9fdfa7b0d81b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugAranges::generate (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> * CTX)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugaranges-cpp">DWARFDebugAranges.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a3505e8caa8aebc427a28a104a4eb22b2">llvm::DWARFContext::compile_units</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/loopextractor-cpp/#a84dff14934298a71113ab11312c243f6">extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#afee257479a32521e9a8c72609226214f">llvm::DWARFObject::getArangesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#af5ebc989c207cabcabe0e9943938ddf1">llvm::DWARFContext::getDWARFObj</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a111bc257b974cfaa4070a8707a1b34c7">llvm::DWARFContext::getRecoverableErrorHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a66f6b3d43cb69feb1c0bfd1ab00d99b1">llvm::DWARFContext::getWarningHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a6810400ced4f9fd81a2a0f16a6d71de7">llvm::DWARFContext::isLittleEndian</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### appendRange() {#ae558e99597701d19c1ef7aa186b13a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugAranges::appendRange (uint64_t CUOffset, uint64_t LowPC, uint64_t HighPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call appendRange multiple times and then call construct.</p>

<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugaranges-cpp">DWARFDebugAranges.cpp</a>.</p>

</div>
</div>

### clear() {#a2b354147c43a3222f8b37950f4f8127a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugAranges::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugaranges-cpp">DWARFDebugAranges.cpp</a>.</p>

</div>
</div>

### construct() {#a1f67b92af47aa81c4c82ffae87e5954f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugAranges::construct ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugaranges-cpp">DWARFDebugAranges.cpp</a>.</p>

</div>
</div>

### extract() {#add8addde2668cd0f7afac10babaf2f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDebugAranges::extract (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> DebugArangesData, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; WarningHandler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugaranges-cpp">DWARFDebugAranges.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Aranges {#a4fa3c57ca6ff724bd991fdddabedadd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RangeColl llvm::DWARFDebugAranges::Aranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>.</p>

</div>
</div>

### Endpoints {#a9ad0db13cab5a594b2c5bd1a98bd7152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;RangeEndpoint&gt; llvm::DWARFDebugAranges::Endpoints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>.</p>

</div>
</div>

### ParsedCUOffsets {#a3042ccd95dd23d586107e7de0e1d1084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;uint64_t&gt; llvm::DWARFDebugAranges::ParsedCUOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdebugaranges-h">DWARFDebugAranges.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugaranges-cpp">DWARFDebugAranges.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
