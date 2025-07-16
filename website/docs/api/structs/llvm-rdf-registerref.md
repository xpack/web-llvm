---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/registerref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterRef` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::RegisterRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">llvm/CodeGen/RDFRegisters.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6355d157d6038c4e534079ea55b6ca1b">RegisterRef</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d0e76b1406156ae9aec70df17c4d8a">RegisterRef</a> (RegisterId R, LaneBitmask M=LaneBitmask::getAll())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb95e29d5f7bd2501f0f8d640c0b1e0">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2ca3eacbdd6f0f024b8b7f9b42b200">operator&lt;</a> (RegisterRef) const =delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9e15fc09af0e81b78e690c61885a95d">operator==</a> (RegisterRef) const =delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2abbc7dad4ea83d0b48dcbaf4e8d73e4">operator!=</a> (RegisterRef) const =delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e855d6b2f844f3bdce575f3d0330bb5">isReg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1bfe6203bc7a6af8e4d46af058b2f3">isUnit</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a80381a8983087ea1f89b9fadabede">isMask</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a3bdf2a3d5c33f370bc778fabaee9c">idx</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade98b6f08e1d3b9f3b304bdd0d652c72">hash</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff344ef4b411a5f449ef8839d98f1750">Reg</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad5cb9affeee19ca5894e5d950ea869">Mask</a> = <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">LaneBitmask::getNone</a>()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987ae88dea5396b51031fe9a52d8388a">isRegId</a> (unsigned Id)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa495ab731d5c7de060f932c8bbc869">isUnitId</a> (unsigned Id)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a6e00a1aed89e42fd185379d3309666">isMaskId</a> (unsigned Id)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3baa7e674ebf2b284f3aa922913b7d25">toUnitId</a> (unsigned Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade42d303ca66ea8b8c9b224edd3675f5">toIdx</a> (RegisterId Id)</td>
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


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisterRef() {#a6355d157d6038c4e534079ea55b6ca1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::RegisterRef::RegisterRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="#a2abbc7dad4ea83d0b48dcbaf4e8d73e4">operator!=</a>, <a href="#adf2ca3eacbdd6f0f024b8b7f9b42b200">operator&lt;</a> and <a href="#af9e15fc09af0e81b78e690c61885a95d">operator==</a>.</p>

</div>
</div>

### RegisterRef() {#a17d0e76b1406156ae9aec70df17c4d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::RegisterRef::RegisterRef (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a> R, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> M=<a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">LaneBitmask::getAll</a>())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="#a987ae88dea5396b51031fe9a52d8388a">isRegId</a>, <a href="#a5ad5cb9affeee19ca5894e5d950ea869">Mask</a> and <a href="#aff344ef4b411a5f449ef8839d98f1750">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#adeb95e29d5f7bd2501f0f8d640c0b1e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::RegisterRef::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="#a6e855d6b2f844f3bdce575f3d0330bb5">isReg</a>, <a href="#a5ad5cb9affeee19ca5894e5d950ea869">Mask</a> and <a href="#aff344ef4b411a5f449ef8839d98f1750">Reg</a>.</p>

</div>
</div>

### operator!=() {#a2abbc7dad4ea83d0b48dcbaf4e8d73e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterRef::operator!= (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a>)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="#a6355d157d6038c4e534079ea55b6ca1b">RegisterRef</a>.</p>

</div>
</div>

### operator&lt;() {#adf2ca3eacbdd6f0f024b8b7f9b42b200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterRef::operator&lt; (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a>)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="#a6355d157d6038c4e534079ea55b6ca1b">RegisterRef</a>.</p>

</div>
</div>

### operator==() {#af9e15fc09af0e81b78e690c61885a95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterRef::operator== (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a>)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="#a6355d157d6038c4e534079ea55b6ca1b">RegisterRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hash() {#ade98b6f08e1d3b9f3b304bdd0d652c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::rdf::RegisterRef::hash ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="#a5ad5cb9affeee19ca5894e5d950ea869">Mask</a> and <a href="#aff344ef4b411a5f449ef8839d98f1750">Reg</a>.</p>

</div>
</div>

### idx() {#a05a3bdf2a3d5c33f370bc778fabaee9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::rdf::RegisterRef::idx ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="#aff344ef4b411a5f449ef8839d98f1750">Reg</a> and <a href="#ade42d303ca66ea8b8c9b224edd3675f5">toIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#afbe9878ae041d77351364bc60fe4a3fe">llvm::rdf::PhysicalRegisterInfo::getUnits</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#ae0d37a7eb6fa39a78f3bcb706766bd73">llvm::rdf::DataFlowGraph::hasUntrackedRef</a>.</p>

</div>
</div>

### isMask() {#a75a80381a8983087ea1f89b9fadabede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterRef::isMask ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="#a7a6e00a1aed89e42fd185379d3309666">isMaskId</a> and <a href="#aff344ef4b411a5f449ef8839d98f1750">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#afbe9878ae041d77351364bc60fe4a3fe">llvm::rdf::PhysicalRegisterInfo::getUnits</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aa51570c2c0b445c77a89a0018b0670f7">llvm::rdf::RegisterAggr::hasAliasOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#abe99acebac6f58f70d09de84f5becbdf">llvm::rdf::RegisterAggr::hasCoverOf</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a23019059b3e22c404f87ee4fd36f7fae">llvm::rdf::RegisterAggr::insert</a>.</p>

</div>
</div>

### isReg() {#a6e855d6b2f844f3bdce575f3d0330bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterRef::isReg ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="#a987ae88dea5396b51031fe9a52d8388a">isRegId</a> and <a href="#aff344ef4b411a5f449ef8839d98f1750">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#afbe9878ae041d77351364bc60fe4a3fe">llvm::rdf::PhysicalRegisterInfo::getUnits</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#ae0d37a7eb6fa39a78f3bcb706766bd73">llvm::rdf::DataFlowGraph::hasUntrackedRef</a> and <a href="#adeb95e29d5f7bd2501f0f8d640c0b1e0">operator bool</a>.</p>

</div>
</div>

### isUnit() {#abf1bfe6203bc7a6af8e4d46af058b2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterRef::isUnit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="#aaaa495ab731d5c7de060f932c8bbc869">isUnitId</a> and <a href="#aff344ef4b411a5f449ef8839d98f1750">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Mask {#a5ad5cb9affeee19ca5894e5d950ea869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask llvm::rdf::RegisterRef::Mask = <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">LaneBitmask::getNone</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#afbe9878ae041d77351364bc60fe4a3fe">llvm::rdf::PhysicalRegisterInfo::getUnits</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aa51570c2c0b445c77a89a0018b0670f7">llvm::rdf::RegisterAggr::hasAliasOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#abe99acebac6f58f70d09de84f5becbdf">llvm::rdf::RegisterAggr::hasCoverOf</a>, <a href="#ade98b6f08e1d3b9f3b304bdd0d652c72">hash</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a23019059b3e22c404f87ee4fd36f7fae">llvm::rdf::RegisterAggr::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#ab895a9e549543404ea829bb14f6162c1">llvm::rdf::PhysicalRegisterInfo::mapTo</a>, <a href="#adeb95e29d5f7bd2501f0f8d640c0b1e0">operator bool</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0cef8f9dc36d8b31cbca1f5f9aa9d443">llvm::rdf::DataFlowGraph::pack</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a96b19879536810b447231e0efab10a5e">llvm::rdf::DataFlowGraph::pack</a> and <a href="#a17d0e76b1406156ae9aec70df17c4d8a">RegisterRef</a>.</p>

</div>
</div>

### Reg {#aff344ef4b411a5f449ef8839d98f1750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterId llvm::rdf::RegisterRef::Reg = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#ac020365416d380fdc2b913c0daf4691b">llvm::rdf::Liveness::computeLiveIns</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#afbe9878ae041d77351364bc60fe4a3fe">llvm::rdf::PhysicalRegisterInfo::getUnits</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aa51570c2c0b445c77a89a0018b0670f7">llvm::rdf::RegisterAggr::hasAliasOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#abe99acebac6f58f70d09de84f5becbdf">llvm::rdf::RegisterAggr::hasCoverOf</a>, <a href="#ade98b6f08e1d3b9f3b304bdd0d652c72">hash</a>, <a href="#a05a3bdf2a3d5c33f370bc778fabaee9c">idx</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a23019059b3e22c404f87ee4fd36f7fae">llvm::rdf::RegisterAggr::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab12951430f2984b5f0b26e265ccb8ac7">llvm::rdf::CopyPropagation::interpretAsCopy</a>, <a href="#a75a80381a8983087ea1f89b9fadabede">isMask</a>, <a href="#a6e855d6b2f844f3bdce575f3d0330bb5">isReg</a>, <a href="#abf1bfe6203bc7a6af8e4d46af058b2f3">isUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#ab895a9e549543404ea829bb14f6162c1">llvm::rdf::PhysicalRegisterInfo::mapTo</a>, <a href="#adeb95e29d5f7bd2501f0f8d640c0b1e0">operator bool</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0cef8f9dc36d8b31cbca1f5f9aa9d443">llvm::rdf::DataFlowGraph::pack</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a96b19879536810b447231e0efab10a5e">llvm::rdf::DataFlowGraph::pack</a> and <a href="#a17d0e76b1406156ae9aec70df17c4d8a">RegisterRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isMaskId() {#a7a6e00a1aed89e42fd185379d3309666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::rdf::RegisterRef::isMaskId (unsigned Id)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/register/#a050c8e969ce1fa8c229b074fd07be925">llvm::Register::isStackSlot</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a85c1ec2b6a80a274d6f070a19045d392">llvm::rdf::PhysicalRegisterInfo::getAliasSet</a>, <a href="#a75a80381a8983087ea1f89b9fadabede">isMask</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a1ae2387cb76daa6d4328c2cc9ab5e850">llvm::rdf::DataFlowGraph::makeRegRef</a>.</p>

</div>
</div>

### isRegId() {#a987ae88dea5396b51031fe9a52d8388a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::rdf::RegisterRef::isRegId (unsigned Id)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/register/#afacc26f29d80e10be4785a96ed6444dc">llvm::Register::isPhysicalRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a85c1ec2b6a80a274d6f070a19045d392">llvm::rdf::PhysicalRegisterInfo::getAliasSet</a>, <a href="#a6e855d6b2f844f3bdce575f3d0330bb5">isReg</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a1ae2387cb76daa6d4328c2cc9ab5e850">llvm::rdf::DataFlowGraph::makeRegRef</a> and <a href="#a17d0e76b1406156ae9aec70df17c4d8a">RegisterRef</a>.</p>

</div>
</div>

### isUnitId() {#aaaa495ab731d5c7de060f932c8bbc869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::rdf::RegisterRef::isUnitId (unsigned Id)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/register/#ac6bf744f357352cde7578931007c0b6f">llvm::Register::isVirtualRegister</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a85c1ec2b6a80a274d6f070a19045d392">llvm::rdf::PhysicalRegisterInfo::getAliasSet</a>, <a href="#abf1bfe6203bc7a6af8e4d46af058b2f3">isUnit</a> and <a href="#ade42d303ca66ea8b8c9b224edd3675f5">toIdx</a>.</p>

</div>
</div>

### toIdx() {#ade42d303ca66ea8b8c9b224edd3675f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr unsigned llvm::rdf::RegisterRef::toIdx (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a> Id)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="#aaaa495ab731d5c7de060f932c8bbc869">isUnitId</a>.</p>


<p>Referenced by <a href="#a05a3bdf2a3d5c33f370bc778fabaee9c">idx</a>.</p>

</div>
</div>

### toUnitId() {#a3baa7e674ebf2b284f3aa922913b7d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr RegisterId llvm::rdf::RegisterRef::toUnitId (unsigned Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregister/#aeaac7abf0e2e4881cc7158ab6cdb0019">llvm::MCRegister::VirtualRegFlag</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
