---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liveintervalunion
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LiveIntervalUnion` Class

<p>Union of live intervals that are strong candidates for coalescing into a single register (either physical or virtual depending on the context). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LiveIntervalUnion { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">llvm/CodeGen/LiveIntervalUnion.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955fe64963e97f1356746fbce9baeb84">SegmentIter</a> = LiveSegments::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2372af5542d002fe85ce028e06172be1">ConstSegmentIter</a> = LiveSegments::const_iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Const version of <a href="#a955fe64963e97f1356746fbce9baeb84">SegmentIter</a>. <a href="#a2372af5542d002fe85ce028e06172be1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9428cfe59ce0851615cef7e5527a01">Allocator</a> = LiveSegments::Allocator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f7ebbad70dee51c4d0be722852ca19">Map</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmap">LiveSegments</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf71c890f2bb5cbc64370457c1b1158">LiveSegments</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a70d7d591281375f770580181ca61ff">LiveIntervalUnion</a> (Allocator &amp;a)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a955fe64963e97f1356746fbce9baeb84">SegmentIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53943d0d7115be6e10debb704a13bd78">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a955fe64963e97f1356746fbce9baeb84">SegmentIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6e7a0f4a7257f1869cbaf96a585b47">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a955fe64963e97f1356746fbce9baeb84">SegmentIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b0807c8afe1c56b607a1a214f94c9b3">find</a> (SlotIndex x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2372af5542d002fe85ce028e06172be1">ConstSegmentIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38d84b05915eec436151c65c0fa41c42">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2372af5542d002fe85ce028e06172be1">ConstSegmentIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af82ccf2f57ab2fea363b336e720e019d">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2372af5542d002fe85ce028e06172be1">ConstSegmentIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58fb7d5c2477c4e30c348b28c2965dc">find</a> (SlotIndex x) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bd39cef1749176c095654a688d8166">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193933d7e0c817cff8d7b4cc84309951">startIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acece4a57a1a46acb71b962a2ac67db7a">endIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#af2f7ebbad70dee51c4d0be722852ca19">Map</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5af30eb111561b2beede640a0f4ccb6">getMap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c0a608cb0e8173b6521c236f9b52740">getTag</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTag - Return an opaque tag representing the current state of the union. <a href="#a9c0a608cb0e8173b6521c236f9b52740">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafcfe2a42c4b42df9b2ff36a7710feb8">changedSince</a> (unsigned tag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>changedSince - Return true if the union change since getTag returned tag. <a href="#aafcfe2a42c4b42df9b2ff36a7710feb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca797d7f7c91269e316f10da8d7844b">unify</a> (const LiveInterval &amp;VirtReg, const LiveRange &amp;Range)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6820515dc400890111693ed7d0c9db">extract</a> (const LiveInterval &amp;VirtReg, const LiveRange &amp;Range)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272c768c284bb45b0700a67a4da3d54a">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71126c0da12305fa8cf78f7e1d4d1a2">print</a> (raw_ostream &amp;OS, const TargetRegisterInfo *TRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6fdf89b1af8d8149da176b90559772e">verify</a> (LiveVirtRegBitSet &amp;VisitedVRegs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b6f3f99b400461f81346d88138ed01">getOneVReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NDEBUG. <a href="#a40b6f3f99b400461f81346d88138ed01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ce41b76cfb4f76fce054ddbe2268cc">Tag</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap">LiveSegments</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a5fc3746a73384a78cfbed2561ce45">Segments</a></td>
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

<p>Union of live intervals that are strong candidates for coalescing into a single register (either physical or virtual depending on the context).</p>


<p>We expect the constituent live intervals to be disjoint, although we may eventually make exceptions to handle value-based interference.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Allocator {#aec9428cfe59ce0851615cef7e5527a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveIntervalUnion::Allocator =  LiveSegments::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### ConstSegmentIter {#a2372af5542d002fe85ce028e06172be1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveIntervalUnion::ConstSegmentIter =  LiveSegments::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Const version of <a href="#a955fe64963e97f1356746fbce9baeb84">SegmentIter</a>.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### Map {#af2f7ebbad70dee51c4d0be722852ca19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveIntervalUnion::Map =  LiveSegments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### SegmentIter {#a955fe64963e97f1356746fbce9baeb84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveIntervalUnion::SegmentIter =  LiveSegments::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### LiveSegments {#aecf71c890f2bb5cbc64370457c1b1158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveIntervalUnion::LiveSegments =  IntervalMap&lt;SlotIndex, const LiveInterval *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LiveIntervalUnion() {#a2a70d7d591281375f770580181ca61ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervalUnion::LiveIntervalUnion (<a href="#aec9428cfe59ce0851615cef7e5527a01">Allocator</a> &amp; a)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/array/#a379ea73dcfa77d926ccf4a16720bd5a2">llvm::LiveIntervalUnion::Array::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/array/#a0e16dcff45ef11be19123e4e764a6e44">llvm::LiveIntervalUnion::Array::init</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#a5a7f80461ba4f83724785b271058e0f1">llvm::LiveIntervalUnion::Query::init</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/array/#a7fd855478b556b8c1ba6ddd8acd084a4">llvm::LiveIntervalUnion::Array::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/array/#ad53256968f6a56f6ec264744a78d4728">llvm::LiveIntervalUnion::Array::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#a43d99e49a3e0a5bc5ebd18a8622a012e">llvm::LiveIntervalUnion::Query::Query</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ae8729ee921fdf522087d928c9bb38af4">llvm::LiveIntervalUnion::Query::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a53943d0d7115be6e10debb704a13bd78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SegmentIter llvm::LiveIntervalUnion::begin ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### begin() {#a38d84b05915eec436151c65c0fa41c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstSegmentIter llvm::LiveIntervalUnion::begin ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### changedSince() {#aafcfe2a42c4b42df9b2ff36a7710feb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervalUnion::changedSince (unsigned tag)</td>
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

<p>changedSince - Return true if the union change since getTag returned tag.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#a5a7f80461ba4f83724785b271058e0f1">llvm::LiveIntervalUnion::Query::init</a>.</p>

</div>
</div>

### clear() {#a272c768c284bb45b0700a67a4da3d54a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervalUnion::clear ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/array/#a0e16dcff45ef11be19123e4e764a6e44">llvm::LiveIntervalUnion::Array::init</a>.</p>

</div>
</div>

### empty() {#ae2bd39cef1749176c095654a688d8166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveIntervalUnion::empty ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Referenced by <a href="#a40b6f3f99b400461f81346d88138ed01">getOneVReg</a> and <a href="#ac71126c0da12305fa8cf78f7e1d4d1a2">print</a>.</p>

</div>
</div>

### end() {#a6a6e7a0f4a7257f1869cbaf96a585b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SegmentIter llvm::LiveIntervalUnion::end ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### end() {#af82ccf2f57ab2fea363b336e720e019d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstSegmentIter llvm::LiveIntervalUnion::end ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### endIndex() {#acece4a57a1a46acb71b962a2ac67db7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervalUnion::endIndex ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### extract() {#a7b6820515dc400890111693ed7d0c9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervalUnion::extract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalunion-cpp">LiveIntervalUnion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### find() {#a2b0807c8afe1c56b607a1a214f94c9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SegmentIter llvm::LiveIntervalUnion::find (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> x)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### find() {#aa58fb7d5c2477c4e30c348b28c2965dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstSegmentIter llvm::LiveIntervalUnion::find (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> x)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### getMap() {#ad5af30eb111561b2beede640a0f4ccb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Map &amp; llvm::LiveIntervalUnion::getMap ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### getOneVReg() {#a40b6f3f99b400461f81346d88138ed01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveInterval * LiveIntervalUnion::getOneVReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NDEBUG.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalunion-cpp">LiveIntervalUnion.cpp</a>.</p>


<p>Reference <a href="#ae2bd39cef1749176c095654a688d8166">empty</a>.</p>

</div>
</div>

### getTag() {#a9c0a608cb0e8173b6521c236f9b52740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveIntervalUnion::getTag ()</td>
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

<p>getTag - Return an opaque tag representing the current state of the union.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ae8729ee921fdf522087d928c9bb38af4">llvm::LiveIntervalUnion::Query::reset</a>.</p>

</div>
</div>

### print() {#ac71126c0da12305fa8cf78f7e1d4d1a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervalUnion::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalunion-cpp">LiveIntervalUnion.cpp</a>.</p>


<p>References <a href="#ae2bd39cef1749176c095654a688d8166">empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### startIndex() {#a193933d7e0c817cff8d7b4cc84309951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveIntervalUnion::startIndex ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### unify() {#a2ca797d7f7c91269e316f10da8d7844b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervalUnion::unify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalunion-cpp">LiveIntervalUnion.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### verify() {#aa6fdf89b1af8d8149da176b90559772e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervalUnion::verify (<a href="/web-llvm/docs/api/namespaces/llvm/#a4d5f563efc65347976c99e5866e307d0">LiveVirtRegBitSet</a> &amp; VisitedVRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalunion-cpp">LiveIntervalUnion.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#a613c1e44c4e88e9a1e0be386cb5fa828">llvm::SparseBitVector&lt; ElementSize &gt;::set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Segments {#a60a5fc3746a73384a78cfbed2561ce45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveSegments llvm::LiveIntervalUnion::Segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

</div>
</div>

### Tag {#a02ce41b76cfb4f76fce054ddbe2268cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveIntervalUnion::Tag = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalunion-h">LiveIntervalUnion.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
