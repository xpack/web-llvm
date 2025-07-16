---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pointerembeddedint
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PointerEmbeddedInt` Class Template Reference

<p>Utility to embed an integer into a pointer-like type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;
class llvm::PointerEmbeddedInt&lt;IntT, Bits&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">llvm/ADT/PointerEmbeddedInt.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> : uintptr_t { <a href="#a993d4f5d1cbd6823838e5522e8cf2266">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d120b8037d5e9933d98ff076edab2d8">PointerLikeTypeTraits&lt; PointerEmbeddedInt &gt;</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad6fb45970333ed1021fa68939785950d">PointerEmbeddedInt</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a897914de7b876537cdad68a213aef272">PointerEmbeddedInt</a> (IntT I)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a984975a158156f6cf3aa00899d524fac">PointerEmbeddedInt</a> (uintptr_t Value, RawValueTag)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerembeddedint">PointerEmbeddedInt</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a797102cb5f5a1af8d001c5271068bde9">operator=</a> (IntT I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab7a40cca67f87adef44bac2e8af94428">operator IntT</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35ad3ae173111aa5de30a22f9ad343dc">Value</a> = 0</td>
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

<p>Utility to embed an integer into a pointer-like type.</p>


<p>This is specifically intended to allow embedding integers where fewer bits are required than exist in a pointer, and the integer can participate in abstractions along side other pointer-like types. For example it can be placed into a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pointersumtype">PointerSumType</a></span> or <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a></span>.</p>


<p>Note that much like pointers, an integer value of zero has special utility due to boolean conversions. For example, a non-null value can be tested for in the above abstractions without testing the particular active member. Also, the default constructed value zero initializes the integer.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a993d4f5d1cbd6823838e5522e8cf2266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uintptr_t</td>
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
<td class="doxyEnumItemName">Shift<a id="a993d4f5d1cbd6823838e5522e8cf2266af60f47ae7d04da8544f32b8a73019994"></a></td>
<td class="doxyEnumItemDescription"> (= sizeof(uintptr_t) * CHAR_BIT - Bits)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mask<a id="a993d4f5d1cbd6823838e5522e8cf2266ac16c90832f1bc5cdfae044b0416fc9dd"></a></td>
<td class="doxyEnumItemDescription"> (= static_cast&lt;uintptr_t&gt;(-1) &lt;&lt; Bits)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### PointerLikeTypeTraits&lt; PointerEmbeddedInt &gt; {#a4d120b8037d5e9933d98ff076edab2d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits">PointerLikeTypeTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pointerembeddedint">PointerEmbeddedInt</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PointerEmbeddedInt() {#ad6fb45970333ed1021fa68939785950d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PointerEmbeddedInt&lt; IntT, Bits &gt;::PointerEmbeddedInt ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>

</div>
</div>

### PointerEmbeddedInt() {#a897914de7b876537cdad68a213aef272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PointerEmbeddedInt&lt; IntT, Bits &gt;::PointerEmbeddedInt (IntT I)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### PointerEmbeddedInt() {#a984975a158156f6cf3aa00899d524fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PointerEmbeddedInt&lt; IntT, Bits &gt;::PointerEmbeddedInt (uintptr_t Value, RawValueTag)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator IntT() {#ab7a40cca67f87adef44bac2e8af94428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PointerEmbeddedInt&lt; IntT, Bits &gt;::operator IntT ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>

</div>
</div>

### operator=() {#a797102cb5f5a1af8d001c5271068bde9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerEmbeddedInt &amp; llvm::PointerEmbeddedInt&lt; IntT, Bits &gt;::operator= (IntT I)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Value {#a35ad3ae173111aa5de30a22f9ad343dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IntT, int Bits = sizeof(IntT) * CHAR_BIT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::PointerEmbeddedInt&lt; IntT, Bits &gt;::Value = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerembeddedint-h">PointerEmbeddedInt.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
