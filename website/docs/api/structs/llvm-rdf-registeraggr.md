---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/registeraggr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterAggr` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::RegisterAggr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">llvm/CodeGen/RDFRegisters.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6e9e7a064e512cfb0af970223f7c51">unit_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a99a6a1febf299d51eab9d14ce188afe5">BitVector::const_set_bits_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a> (const PhysicalRegisterInfo &amp;pri)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6580e43e3885b6ba30d3decdcf2f7a71">RegisterAggr</a> (const RegisterAggr &amp;RG)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe24ed31fe73055eec759c1f53ac26e">operator==</a> (const RegisterAggr &amp;A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439ca4ef61a75f350975506130fd8b49">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8550509e5a44adcccec5d4c23b1536ec">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51570c2c0b445c77a89a0018b0670f7">hasAliasOf</a> (RegisterRef RR) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe99acebac6f58f70d09de84f5becbdf">hasCoverOf</a> (RegisterRef RR) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo">PhysicalRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4662b0c4b83256efcff7c308cdcec429">getPRI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23019059b3e22c404f87ee4fd36f7fae">insert</a> (RegisterRef RR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc55e70f8fe406f0ea60336e0457ea8c">insert</a> (const RegisterAggr &amp;RG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e1f73246f7efd5f109751eba770e896">intersect</a> (RegisterRef RR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8d18996fd693bd08fc10b7e5588d0f">intersect</a> (const RegisterAggr &amp;RG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f7826f471d9245cc644656201d404d">clear</a> (RegisterRef RR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941a92851b2b569e536346cd678ec6e8">clear</a> (const RegisterAggr &amp;RG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8037343d867187c11d52da840d72f6">intersectWith</a> (RegisterRef RR) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4c4c57dcce871494c8ac465bcb0edb">clearIn</a> (RegisterRef RR) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ce85b85f9e56f8d578f6d9965723af">makeRegRef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4428329047c5c44d2157e24986cc9802">hash</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/ref-iterator">ref_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8103bea0dd94a35fcb9ce5574289046b">ref_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/ref-iterator">ref_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8e0e88e7e27bea0ff250d15b5b1368e">ref_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afe6e9e7a064e512cfb0af970223f7c51">unit_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae81eea480bae838e27985cb1dcfac4b3">unit_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afe6e9e7a064e512cfb0af970223f7c51">unit_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d3990104fca82a26fd4b695efd1a3f">unit_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/ref-iterator">ref_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1506ec20a7c8917bd3ba56eaf56916e7">refs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#afe6e9e7a064e512cfb0af970223f7c51">unit_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4e157702dac4657a6dc7e31131f04c">units</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78eabf673d28efa956f102c3f02d28a4">Units</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo">PhysicalRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd8b03375e2190737efd72eb0418126">PRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb69ff57b201dee748ce7fe7f22ff1b">isCoverOf</a> (RegisterRef RA, RegisterRef RB, const PhysicalRegisterInfo &amp;PRI)</td>
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


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### unit\_iterator {#afe6e9e7a064e512cfb0af970223f7c51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::rdf::RegisterAggr::unit_iterator =  typename BitVector::const_set_bits_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegisterAggr() {#a2f83d9bf6a4b4021b35a4a680a0ebbcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::RegisterAggr::RegisterAggr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo">PhysicalRegisterInfo</a> &amp; pri)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="#a941a92851b2b569e536346cd678ec6e8">clear</a>, <a href="#a71f7826f471d9245cc644656201d404d">clear</a>, <a href="#a5e4c4c57dcce871494c8ac465bcb0edb">clearIn</a>, <a href="#afc55e70f8fe406f0ea60336e0457ea8c">insert</a>, <a href="#a23019059b3e22c404f87ee4fd36f7fae">insert</a>, <a href="#a0f8d18996fd693bd08fc10b7e5588d0f">intersect</a>, <a href="#a9e1f73246f7efd5f109751eba770e896">intersect</a>, <a href="#aad8037343d867187c11d52da840d72f6">intersectWith</a>, <a href="#aebb69ff57b201dee748ce7fe7f22ff1b">isCoverOf</a>, <a href="#aafe24ed31fe73055eec759c1f53ac26e">operator==</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/ref-iterator/#a3342e14c1073d2f5957e38a40d13c407">llvm::rdf::RegisterAggr::ref_iterator::ref_iterator</a> and <a href="#a6580e43e3885b6ba30d3decdcf2f7a71">RegisterAggr</a>.</p>

</div>
</div>

### RegisterAggr() {#a6580e43e3885b6ba30d3decdcf2f7a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::RegisterAggr::RegisterAggr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp; RG)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#aafe24ed31fe73055eec759c1f53ac26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterAggr::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp; A)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a17c9fc217e2ec4f12e8c2a27f783bcae">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::isEqual</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a71f7826f471d9245cc644656201d404d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterAggr &amp; llvm::rdf::RegisterAggr::clear (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#a71f7826f471d9245cc644656201d404d">clear</a>, <a href="#a23019059b3e22c404f87ee4fd36f7fae">insert</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>


<p>Referenced by <a href="#a941a92851b2b569e536346cd678ec6e8">clear</a> and <a href="#a71f7826f471d9245cc644656201d404d">clear</a>.</p>

</div>
</div>

### clear() {#a941a92851b2b569e536346cd678ec6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterAggr &amp; llvm::rdf::RegisterAggr::clear (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp; RG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#a71f7826f471d9245cc644656201d404d">clear</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>

</div>
</div>

### clearIn() {#a5e4c4c57dcce871494c8ac465bcb0edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRef llvm::rdf::RegisterAggr::clearIn (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#a5e4c4c57dcce871494c8ac465bcb0edb">clearIn</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>


<p>Referenced by <a href="#a5e4c4c57dcce871494c8ac465bcb0edb">clearIn</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a>.</p>

</div>
</div>

### empty() {#a8550509e5a44adcccec5d4c23b1536ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterAggr::empty ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a>.</p>

</div>
</div>

### getPRI() {#a4662b0c4b83256efcff7c308cdcec429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PhysicalRegisterInfo &amp; llvm::rdf::RegisterAggr::getPRI ()</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### hasAliasOf() {#aa51570c2c0b445c77a89a0018b0670f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterAggr::hasAliasOf (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#aa51570c2c0b445c77a89a0018b0670f7">hasAliasOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a75a80381a8983087ea1f89b9fadabede">llvm::rdf::RegisterRef::isMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a5ad5cb9affeee19ca5894e5d950ea869">llvm::rdf::RegisterRef::Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a> and <a href="#aa51570c2c0b445c77a89a0018b0670f7">hasAliasOf</a>.</p>

</div>
</div>

### hasCoverOf() {#abe99acebac6f58f70d09de84f5becbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterAggr::hasCoverOf (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#abe99acebac6f58f70d09de84f5becbdf">hasCoverOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a75a80381a8983087ea1f89b9fadabede">llvm::rdf::RegisterRef::isMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a5ad5cb9affeee19ca5894e5d950ea869">llvm::rdf::RegisterRef::Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#af948ed7c1cd7c55a1e8cb255d8742936">llvm::rdf::Liveness::getAllReachedUses</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a> and <a href="#abe99acebac6f58f70d09de84f5becbdf">hasCoverOf</a>.</p>

</div>
</div>

### hash() {#a4428329047c5c44d2157e24986cc9802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::rdf::RegisterAggr::hash ()</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a86544e5fd2336905e43348d2fd546094">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getHashValue</a>.</p>

</div>
</div>

### insert() {#a23019059b3e22c404f87ee4fd36f7fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterAggr &amp; llvm::rdf::RegisterAggr::insert (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#a23019059b3e22c404f87ee4fd36f7fae">insert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a75a80381a8983087ea1f89b9fadabede">llvm::rdf::RegisterRef::isMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a73b0d1192402b944dbc7aac0db77258d">llvm::MCRegUnitMaskIterator::isValid</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a5ad5cb9affeee19ca5894e5d950ea869">llvm::rdf::RegisterRef::Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>


<p>Referenced by <a href="#a71f7826f471d9245cc644656201d404d">clear</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#af948ed7c1cd7c55a1e8cb255d8742936">llvm::rdf::Liveness::getAllReachedUses</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="#afc55e70f8fe406f0ea60336e0457ea8c">insert</a>, <a href="#a23019059b3e22c404f87ee4fd36f7fae">insert</a> and <a href="#a9e1f73246f7efd5f109751eba770e896">intersect</a>.</p>

</div>
</div>

### insert() {#afc55e70f8fe406f0ea60336e0457ea8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterAggr &amp; llvm::rdf::RegisterAggr::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp; RG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#a23019059b3e22c404f87ee4fd36f7fae">insert</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>

</div>
</div>

### intersect() {#a9e1f73246f7efd5f109751eba770e896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterAggr &amp; llvm::rdf::RegisterAggr::intersect (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#a23019059b3e22c404f87ee4fd36f7fae">insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a7261340c665e487c72121c8611858e16">intersect</a>, <a href="#a9e1f73246f7efd5f109751eba770e896">intersect</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>


<p>Referenced by <a href="#a0f8d18996fd693bd08fc10b7e5588d0f">intersect</a> and <a href="#a9e1f73246f7efd5f109751eba770e896">intersect</a>.</p>

</div>
</div>

### intersect() {#a0f8d18996fd693bd08fc10b7e5588d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterAggr &amp; llvm::rdf::RegisterAggr::intersect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp; RG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="#a9e1f73246f7efd5f109751eba770e896">intersect</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>

</div>
</div>

### intersectWith() {#aad8037343d867187c11d52da840d72f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRef llvm::rdf::RegisterAggr::intersectWith (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aad8037343d867187c11d52da840d72f6">intersectWith</a>, <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a> and <a href="#aad8037343d867187c11d52da840d72f6">intersectWith</a>.</p>

</div>
</div>

### makeRegRef() {#a83ce85b85f9e56f8d578f6d9965723af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRef llvm::rdf::RegisterAggr::makeRegRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a2da3bac3ad70ccb97150626385ebd6a7">llvm::BitVector::find_first</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a9941bbcdd7fadda44146fcc6f91af71f">llvm::BitVector::find_next</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a83ce85b85f9e56f8d578f6d9965723af">makeRegRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a83ce85b85f9e56f8d578f6d9965723af">makeRegRef</a>.</p>

</div>
</div>

### ref\_begin() {#a8103bea0dd94a35fcb9ce5574289046b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ref_iterator llvm::rdf::RegisterAggr::ref_begin ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="#a1506ec20a7c8917bd3ba56eaf56916e7">refs</a>.</p>

</div>
</div>

### ref\_end() {#af8e0e88e7e27bea0ff250d15b5b1368e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ref_iterator llvm::rdf::RegisterAggr::ref_end ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="#a1506ec20a7c8917bd3ba56eaf56916e7">refs</a>.</p>

</div>
</div>

### refs() {#a1506ec20a7c8917bd3ba56eaf56916e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; ref_iterator &gt; llvm::rdf::RegisterAggr::refs ()</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a8103bea0dd94a35fcb9ce5574289046b">ref_begin</a> and <a href="#af8e0e88e7e27bea0ff250d15b5b1368e">ref_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a6c8700f31ee8c2ff5f803bb291b8fd03">llvm::rdf::Liveness::resetLiveIns</a>.</p>

</div>
</div>

### size() {#a439ca4ef61a75f350975506130fd8b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::rdf::RegisterAggr::size ()</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### unit\_begin() {#ae81eea480bae838e27985cb1dcfac4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unit_iterator llvm::rdf::RegisterAggr::unit_begin ()</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="#a2f4e157702dac4657a6dc7e31131f04c">units</a>.</p>

</div>
</div>

### unit\_end() {#a61d3990104fca82a26fd4b695efd1a3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unit_iterator llvm::rdf::RegisterAggr::unit_end ()</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>Referenced by <a href="#a2f4e157702dac4657a6dc7e31131f04c">units</a>.</p>

</div>
</div>

### units() {#a2f4e157702dac4657a6dc7e31131f04c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; unit_iterator &gt; llvm::rdf::RegisterAggr::units ()</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ae81eea480bae838e27985cb1dcfac4b3">unit_begin</a> and <a href="#a61d3990104fca82a26fd4b695efd1a3f">unit_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PRI {#a6fd8b03375e2190737efd72eb0418126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PhysicalRegisterInfo&amp; llvm::rdf::RegisterAggr::PRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

### Units {#a78eabf673d28efa956f102c3f02d28a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::rdf::RegisterAggr::Units</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isCoverOf() {#aebb69ff57b201dee748ce7fe7f22ff1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::RegisterAggr::isCoverOf (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RA, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo">PhysicalRegisterInfo</a> &amp; PRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a> and <a href="#a2f83d9bf6a4b4021b35a4a680a0ebbcf">RegisterAggr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfregisters-h">RDFRegisters.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfregisters-cpp">RDFRegisters.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
