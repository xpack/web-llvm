---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bitsrecty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BitsRecTy` Class

<p>'bits&lt;n&gt;' - Represent a fixed number of bits <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BitsRecTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">llvm/TableGen/Record.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6405c4324f711706cb823ddb60b53563">BitsRecTy</a> (RecordKeeper &amp;RK, unsigned Sz)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355299b5701f772ba4f45a5f89626452">getNumBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78744cd0f28ef73bd1db54325dd91fdf">getAsString</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26af9ff0b126b032c3c230aa0b0c0ff8">typeIsConvertibleTo</a> (const RecTy *RHS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all values of 'this' type can be converted to the specified type. <a href="#a26af9ff0b126b032c3c230aa0b0c0ff8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd25647db8af62788d2d4a9277587963">Size</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d22a3844f4363e2c19964512dfda0a">classof</a> (const RecTy *RT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitsrecty">BitsRecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d60b388546684e9c996413e10a8277">get</a> (RecordKeeper &amp;RK, unsigned Sz)</td>
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

<p>'bits&lt;n&gt;' - Represent a fixed number of bits</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### BitsRecTy() {#a6405c4324f711706cb823ddb60b53563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitsRecTy::BitsRecTy (<a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; RK, unsigned Sz)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsString() {#a78744cd0f28ef73bd1db54325dd91fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string BitsRecTy::getAsString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>

</div>
</div>

### getNumBits() {#a355299b5701f772ba4f45a5f89626452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitsRecTy::getNumBits ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### typeIsConvertibleTo() {#a26af9ff0b126b032c3c230aa0b0c0ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitsRecTy::typeIsConvertibleTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all values of 'this' type can be converted to the specified type.</p>

<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/recty/#a49953f670acd87339563c3ea7716f07daf1d5e2e84e2ab3bee666d2fa92aaccf8">llvm::RecTy::BitRecTyKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/recty/#a49953f670acd87339563c3ea7716f07dad618f0a45a62c5b48dae9cf044f865ad">llvm::RecTy::IntRecTyKind</a>, <a href="/web-llvm/docs/api/classes/llvm/recty/#a6de9b82387c10021fbe937b3e52bd9f3">llvm::RecTy::RecTy</a> and <a href="/web-llvm/docs/api/classes/llvm/recty/#a28ff8427d52e8183da03e65ad86a16a3">llvm::RecTy::typeIsConvertibleTo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Size {#afd25647db8af62788d2d4a9277587963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitsRecTy::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a53d22a3844f4363e2c19964512dfda0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BitsRecTy::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * RT)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/recty/#a49953f670acd87339563c3ea7716f07daccd899f53a22271bc819022c83c8d4b7">llvm::RecTy::BitsRecTyKind</a>, <a href="/web-llvm/docs/api/classes/llvm/recty/#a9894d44bbb655ddbc92eec56c53111b4">llvm::RecTy::getRecTyKind</a> and <a href="/web-llvm/docs/api/classes/llvm/recty/#a6de9b82387c10021fbe937b3e52bd9f3">llvm::RecTy::RecTy</a>.</p>

</div>
</div>

### get() {#a69d60b388546684e9c996413e10a8277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitsRecTy * BitsRecTy::get (<a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; RK, unsigned Sz)</td>
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



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/detail/recordkeeperimpl/#abc3aa7225f620417d5fb1e00b916c84c">llvm::detail::RecordKeeperImpl::Allocator</a> and <a href="/web-llvm/docs/api/structs/llvm/detail/recordkeeperimpl/#a686db9c9203965a09be47d948800d0fe">llvm::detail::RecordKeeperImpl::SharedBitsRecTys</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
