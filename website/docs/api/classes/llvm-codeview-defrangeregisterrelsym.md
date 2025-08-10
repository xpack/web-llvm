---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/defrangeregisterrelsym
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DefRangeRegisterRelSym` Class



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::DefRangeRegisterRelSym { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">llvm/DebugInfo/CodeView/SymbolRecord.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecord">SymbolRecord</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint16_t { <a href="#a33ad0319b2102d4926f6610dbf3c9a00">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4b43bbedc3fcddd56ab6d23cdb082a">DefRangeRegisterRelSym</a> (SymbolRecordKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69032a0dfcbc688afa35da6eb1c5f20">DefRangeRegisterRelSym</a> (uint32_t RecordOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e9878bf4591ee8350b1642eda5f9179">hasSpilledUDTMember</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65d14670f390ee5befce64caa60207bc">offsetInParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba9b0352eb8f5ecfcc6e8c66fc9e4d5">getRelocationOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/defrangeregisterrelheader">DefRangeRegisterRelHeader</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b6426b1fddf2f3bb02ac863219dfd3">Hdr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codeview/localvariableaddrrange">LocalVariableAddrRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8212213d7a45b0108f59e0fe1934f6d">Range</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/localvariableaddrgap">LocalVariableAddrGap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b3a2966825eb52f7526e7d96de8ca6">Gaps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0221c510c5487994df9c2fd47bad2e6d">RecordOffset</a> = 0</td>
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


<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a33ad0319b2102d4926f6610dbf3c9a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsSubfieldFlag<a id="a33ad0319b2102d4926f6610dbf3c9a00ae78d8047bf7c826111bb1ecab1a220d4"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OffsetInParentShift<a id="a33ad0319b2102d4926f6610dbf3c9a00aad291be06fdd0c8f1581fad97b62f98d"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DefRangeRegisterRelSym() {#aff4b43bbedc3fcddd56ab6d23cdb082a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::DefRangeRegisterRelSym::DefRangeRegisterRelSym (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a718bd404e8a87ee5e1a21b0c267cde17">SymbolRecordKind</a> Kind)</td>
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



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecord/#a70c9046ac3e018331204b9f904641d13">llvm::codeview::SymbolRecord::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecord/#a51a0afc589bb5038be677a47f781d39e">llvm::codeview::SymbolRecord::SymbolRecord</a>.</p>


<p>Referenced by <a href="#ac69032a0dfcbc688afa35da6eb1c5f20">DefRangeRegisterRelSym</a>.</p>

</div>
</div>

### DefRangeRegisterRelSym() {#ac69032a0dfcbc688afa35da6eb1c5f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::DefRangeRegisterRelSym::DefRangeRegisterRelSym (uint32_t RecordOffset)</td>
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



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>References <a href="#aff4b43bbedc3fcddd56ab6d23cdb082a">DefRangeRegisterRelSym</a>, <a href="#a0221c510c5487994df9c2fd47bad2e6d">RecordOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/symbolrecord/#a51a0afc589bb5038be677a47f781d39e">llvm::codeview::SymbolRecord::SymbolRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocationOffset() {#a4ba9b0352eb8f5ecfcc6e8c66fc9e4d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::DefRangeRegisterRelSym::getRelocationOffset ()</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>Reference <a href="#a0221c510c5487994df9c2fd47bad2e6d">RecordOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab7651adf465ecbe58fce9cb202391532">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### hasSpilledUDTMember() {#a0e9878bf4591ee8350b1642eda5f9179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codeview::DefRangeRegisterRelSym::hasSpilledUDTMember ()</td>
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



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>References <a href="#a03b6426b1fddf2f3bb02ac863219dfd3">Hdr</a> and <a href="#a33ad0319b2102d4926f6610dbf3c9a00ae78d8047bf7c826111bb1ecab1a220d4">IsSubfieldFlag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab7651adf465ecbe58fce9cb202391532">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### offsetInParent() {#a65d14670f390ee5befce64caa60207bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::codeview::DefRangeRegisterRelSym::offsetInParent ()</td>
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



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>References <a href="#a03b6426b1fddf2f3bb02ac863219dfd3">Hdr</a> and <a href="#a33ad0319b2102d4926f6610dbf3c9a00aad291be06fdd0c8f1581fad97b62f98d">OffsetInParentShift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab7651adf465ecbe58fce9cb202391532">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Gaps {#aa8b3a2966825eb52f7526e7d96de8ca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;LocalVariableAddrGap&gt; llvm::codeview::DefRangeRegisterRelSym::Gaps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab7651adf465ecbe58fce9cb202391532">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### Hdr {#a03b6426b1fddf2f3bb02ac863219dfd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefRangeRegisterRelHeader llvm::codeview::DefRangeRegisterRelSym::Hdr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>Referenced by <a href="#a0e9878bf4591ee8350b1642eda5f9179">hasSpilledUDTMember</a>, <a href="#a65d14670f390ee5befce64caa60207bc">offsetInParent</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab7651adf465ecbe58fce9cb202391532">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### Range {#ad8212213d7a45b0108f59e0fe1934f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocalVariableAddrRange llvm::codeview::DefRangeRegisterRelSym::Range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbolvisitor/#ab7651adf465ecbe58fce9cb202391532">llvm::logicalview::LVSymbolVisitor::visitKnownRecord</a>.</p>

</div>
</div>

### RecordOffset {#a0221c510c5487994df9c2fd47bad2e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::codeview::DefRangeRegisterRelSym::RecordOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a>.</p>


<p>Referenced by <a href="#ac69032a0dfcbc688afa35da6eb1c5f20">DefRangeRegisterRelSym</a> and <a href="#a4ba9b0352eb8f5ecfcc6e8c66fc9e4d5">getRelocationOffset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symbolrecord-h">SymbolRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
