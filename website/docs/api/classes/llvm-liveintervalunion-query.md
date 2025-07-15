---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liveintervalunion/query
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Query` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query">Query</a> interferences between a single live virtual register and a live interval union. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LiveIntervalUnion::Query { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">llvm/CodeGen/LiveIntervalUnion.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879c61bc050d5945d4d3c8f17f8bb7e4">Query</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d99e49a3e0a5bc5ebd18a8622a012e">Query</a> (const LiveRange &amp;LR, const LiveIntervalUnion &amp;LIU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09fb3089f7923ced11b4b03fcab0211">Query</a> (const Query &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query">Query</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119567c626d07eaa07c96fbcc337df17">operator=</a> (const Query &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8729ee921fdf522087d928c9bb38af4">reset</a> (unsigned NewUserTag, const LiveRange &amp;NewLR, const LiveIntervalUnion &amp;NewLiveUnion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a7f80461ba4f83724785b271058e0f1">init</a> (unsigned NewUserTag, const LiveRange &amp;NewLR, const LiveIntervalUnion &amp;NewLiveUnion)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7eacb4ff3e11e61bbe97acaf46d47d8">checkInterference</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d5858ffe61498c3109205046a16a98b">interferingVRegs</a> (unsigned MaxInterferingRegs=std::numeric_limits&lt; unsigned &gt;::max())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae024a1a4bad6fca69c5e0cf0a2ec6dd4">collectInterferingVRegs</a> (unsigned MaxInterferingRegs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d85c17ef2adfcdbf06a4049a6297e0">isSeenInterference</a> (const LiveInterval *VirtReg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8773b0a7af653f16c990773560b65e">LiveUnion</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95248a359b8de2f619bc496695e887f2">LR</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange/#a3fc869c7f6d53c3fbb4e572b7821dd05">LiveRange::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d6f28d99158c19f392addb277d6947b">LRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>current position in LR <a href="#a2d6f28d99158c19f392addb277d6947b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#a2372af5542d002fe85ce028e06172be1">ConstSegmentIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c85bcaa6b741ff263b11755e4b62c39">LiveUnionI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>current position in LiveUnion <a href="#a8c85bcaa6b741ff263b11755e4b62c39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d9e18d83752dc944b05de212610b8eb">InterferingVRegs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3f40bdd96c713e281e520b987cc1eeb">CheckedFirstInterference</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9281e857ace86509857fda9752d50929">SeenAllInterferences</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fe544cd0e620196cd374c6861f9720">Tag</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4cd0ccc3a7e2b12bf81729ed28ef1a">UserTag</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query">Query</a> interferences between a single live virtual register and a live interval union.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Query() {#a879c61bc050d5945d4d3c8f17f8bb7e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervalUnion::Query::Query ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Referenced by <a href="#a119567c626d07eaa07c96fbcc337df17">operator=</a> and <a href="#af09fb3089f7923ced11b4b03fcab0211">Query</a>.</p>

</div>
</div>

### Query() {#a43d99e49a3e0a5bc5ebd18a8622a012e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervalUnion::Query::Query (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> &amp; LIU)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#a2a70d7d591281375f770580181ca61ff">llvm::LiveIntervalUnion::LiveIntervalUnion</a>.</p>

</div>
</div>

### Query() {#af09fb3089f7923ced11b4b03fcab0211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervalUnion::Query::Query (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query">Query</a> &amp;)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Reference <a href="#a879c61bc050d5945d4d3c8f17f8bb7e4">Query</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a119567c626d07eaa07c96fbcc337df17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Query &amp; llvm::LiveIntervalUnion::Query::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query">Query</a> &amp;)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Reference <a href="#a879c61bc050d5945d4d3c8f17f8bb7e4">Query</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkInterference() {#ab7eacb4ff3e11e61bbe97acaf46d47d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervalUnion::Query::checkInterference ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#ab0ec56bd57b2676e33aa9f1b0213f0a4">llvm::RegAllocEvictionAdvisor::canReassign</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ad064f1e4af82a7f4251434afde29b0b5">llvm::LiveRegMatrix::checkInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ab9e855199959852351ae2761ae4302be">llvm::LiveRegMatrix::checkInterference</a> and <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#afc6ed60b40c5c63149c23ba327a77c23">llvm::LiveRegMatrix::checkInterferenceLanes</a>.</p>

</div>
</div>

### init() {#a5a7f80461ba4f83724785b271058e0f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervalUnion::Query::init (unsigned NewUserTag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; NewLR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> &amp; NewLiveUnion)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#aafcfe2a42c4b42df9b2ff36a7710feb8">llvm::LiveIntervalUnion::changedSince</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#a2a70d7d591281375f770580181ca61ff">llvm::LiveIntervalUnion::LiveIntervalUnion</a> and <a href="#ae8729ee921fdf522087d928c9bb38af4">reset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#a7c79a2c92779f3c549dee89406ccdfc1">llvm::LiveRegMatrix::query</a>.</p>

</div>
</div>

### interferingVRegs() {#a6d5858ffe61498c3109205046a16a98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; const LiveInterval * &gt; &amp; llvm::LiveIntervalUnion::Query::interferingVRegs (unsigned MaxInterferingRegs=std::numeric_limits&lt; unsigned &gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>())</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>.</p>

</div>
</div>

### reset() {#ae8729ee921fdf522087d928c9bb38af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervalUnion::Query::reset (unsigned NewUserTag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; NewLR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> &amp; NewLiveUnion)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#aa1555194b9f176612b04fbd38f49b40d">llvm::LiveRange::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#a9c0a608cb0e8173b6521c236f9b52740">llvm::LiveIntervalUnion::getTag</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#a2a70d7d591281375f770580181ca61ff">llvm::LiveIntervalUnion::LiveIntervalUnion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ab9e855199959852351ae2761ae4302be">llvm::LiveRegMatrix::checkInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#afc6ed60b40c5c63149c23ba327a77c23">llvm::LiveRegMatrix::checkInterferenceLanes</a> and <a href="#a5a7f80461ba4f83724785b271058e0f1">init</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectInterferingVRegs() {#ae024a1a4bad6fca69c5e0cf0a2ec6dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveIntervalUnion::Query::collectInterferingVRegs (unsigned MaxInterferingRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalunion-cpp">LiveIntervalUnion.cpp</a>.</p>

</div>
</div>

### isSeenInterference() {#a26d85c17ef2adfcdbf06a4049a6297e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveIntervalUnion::Query::isSeenInterference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalunion-cpp">LiveIntervalUnion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CheckedFirstInterference {#ab3f40bdd96c713e281e520b987cc1eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervalUnion::Query::CheckedFirstInterference = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### InterferingVRegs {#a8d9e18d83752dc944b05de212610b8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const LiveInterval *, 4&gt; llvm::LiveIntervalUnion::Query::InterferingVRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### LiveUnion {#a9b8773b0a7af653f16c990773560b65e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveIntervalUnion* llvm::LiveIntervalUnion::Query::LiveUnion = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### LiveUnionI {#a8c85bcaa6b741ff263b11755e4b62c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstSegmentIter llvm::LiveIntervalUnion::Query::LiveUnionI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>current position in LiveUnion</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### LR {#a95248a359b8de2f619bc496695e887f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveRange* llvm::LiveIntervalUnion::Query::LR = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### LRI {#a2d6f28d99158c19f392addb277d6947b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange::const_iterator llvm::LiveIntervalUnion::Query::LRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>current position in LR</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### SeenAllInterferences {#a9281e857ace86509857fda9752d50929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervalUnion::Query::SeenAllInterferences = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### Tag {#a57fe544cd0e620196cd374c6861f9720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveIntervalUnion::Query::Tag = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### UserTag {#a2c4cd0ccc3a7e2b12bf81729ed28ef1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveIntervalUnion::Query::UserTag = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalunion-cpp">LiveIntervalUnion.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
