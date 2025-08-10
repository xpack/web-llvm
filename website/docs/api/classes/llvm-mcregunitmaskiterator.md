---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcregunitmaskiterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCRegUnitMaskIterator` Class

<p><a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator">MCRegUnitMaskIterator</a> enumerates a list of register units and their associated lane masks for Reg. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCRegUnitMaskIterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">llvm/MC/MCRegisterInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3053d971d351e67f85b59924c212a0d2">MCRegUnitMaskIterator</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354da5c3004b55b6143efd8272e6ab86">MCRegUnitMaskIterator</a> (MCRegister Reg, const MCRegisterInfo *MCRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an iterator that traverses the register units and their associated LaneMasks in Reg. <a href="#a354da5c3004b55b6143efd8272e6ab86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bf500e34efd04df951381e4165959b">operator*</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a (RegUnit, LaneMask) pair. <a href="#ae0bf500e34efd04df951381e4165959b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator">MCRegUnitMaskIterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a46ec035fb9f7f1bfbfad8db48988e9">operator++</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Moves to the next position. <a href="#a6a46ec035fb9f7f1bfbfad8db48988e9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73b0d1192402b944dbc7aac0db77258d">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this iterator is not yet at the end. <a href="#a73b0d1192402b944dbc7aac0db77258d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregunititerator">MCRegUnitIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb9bd0dfb27c16beb902e861fc743c4">RUIter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86929a14dbfc77f138f4a0b9b797911">MaskListIter</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator">MCRegUnitMaskIterator</a> enumerates a list of register units and their associated lane masks for Reg.</p>


<p>The register units are in ascending numerical order.</p>


<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCRegUnitMaskIterator() {#a3053d971d351e67f85b59924c212a0d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCRegUnitMaskIterator::MCRegUnitMaskIterator ()</td>
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



<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a6a46ec035fb9f7f1bfbfad8db48988e9">operator++</a>.</p>

</div>
</div>

### MCRegUnitMaskIterator() {#a354da5c3004b55b6143efd8272e6ab86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCRegUnitMaskIterator::MCRegUnitMaskIterator (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * MCRI)</td>
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

<p>Constructs an iterator that traverses the register units and their associated LaneMasks in Reg.</p>

<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a20afbbc02b58a57256a9ac9736d08838">llvm::MCRegisterInfo::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#ae0bf500e34efd04df951381e4165959b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, LaneBitmask &gt; llvm::MCRegUnitMaskIterator::operator* ()</td>
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

<p>Returns a (RegUnit, LaneMask) pair.</p>

<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### operator++() {#a6a46ec035fb9f7f1bfbfad8db48988e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegUnitMaskIterator &amp; llvm::MCRegUnitMaskIterator::operator++ ()</td>
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

<p>Moves to the next position.</p>

<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Reference <a href="#a3053d971d351e67f85b59924c212a0d2">MCRegUnitMaskIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isValid() {#a73b0d1192402b944dbc7aac0db77258d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCRegUnitMaskIterator::isValid ()</td>
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

<p>Returns true if this iterator is not yet at the end.</p>

<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae8625c1e6c9bc82f2eaef39d3fff65a8">llvm::ScheduleDAGInstrs::addSchedBarrierDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#afc6ed60b40c5c63149c23ba327a77c23">llvm::LiveRegMatrix::checkInterferenceLanes</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a8bc3d5451e079cf6bcbb2df76f71f293">llvm::rdf::PhysicalRegisterInfo::equal_to</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#aab2ae433d483c154d92c727cf7282996">foreachUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#afbe9878ae041d77351364bc60fe4a3fe">llvm::rdf::PhysicalRegisterInfo::getUnits</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aa51570c2c0b445c77a89a0018b0670f7">llvm::rdf::RegisterAggr::hasAliasOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#abe99acebac6f58f70d09de84f5becbdf">llvm::rdf::RegisterAggr::hasCoverOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a23019059b3e22c404f87ee4fd36f7fae">llvm::rdf::RegisterAggr::insert</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#addd4894584bf563edc6e3ef084b771ef">llvm::rdf::PhysicalRegisterInfo::less</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MaskListIter {#ac86929a14dbfc77f138f4a0b9b797911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LaneBitmask* llvm::MCRegUnitMaskIterator::MaskListIter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

### RUIter {#a1cb9bd0dfb27c16beb902e861fc743c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegUnitIterator llvm::MCRegUnitMaskIterator::RUIter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcregisterinfo-h">MCRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
