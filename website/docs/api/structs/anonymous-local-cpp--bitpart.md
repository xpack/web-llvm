---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-local-cpp-/bitpart
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `BitPart` Struct

<p>A potential constituent of a bitreverse or bswap expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{Local.cpp}::BitPart { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#ab896f3f4307e3285fa11e20c638ffe70">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cad94d1198ae156fb92d86da87d0992">BitPart</a> (Value *P, unsigned BW)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a575fa6464c331b804833456d11e49d77">Provider</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that this is a bitreverse/bswap of. <a href="#a575fa6464c331b804833456d11e49d77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int8_t, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d55199efc0fa6aaef7c1ba0118d08a">Provenance</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The "provenance" of each bit. <a href="#a17d55199efc0fa6aaef7c1ba0118d08a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A potential constituent of a bitreverse or bswap expression.</p>


<p>See collectBitParts for a fuller explanation.</p>


<p>Definition at line 3804 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#ab896f3f4307e3285fa11e20c638ffe70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">Unset<a id="ab896f3f4307e3285fa11e20c638ffe70acb4045e015f2ff8334244fe843e91508"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 3816 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BitPart() {#a6cad94d1198ae156fb92d86da87d0992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{Local.cpp}::BitPart::BitPart (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * P, unsigned BW)</td>
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



<p>Definition at line 3805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a17d55199efc0fa6aaef7c1ba0118d08a">Provenance</a> and <a href="#a575fa6464c331b804833456d11e49d77">Provider</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa16fecc86f9853cc81abd01a5a6f1604">collectBitParts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Provenance {#a17d55199efc0fa6aaef7c1ba0118d08a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int8_t, 32&gt; anonymous{Local.cpp}::BitPart::Provenance</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The "provenance" of each bit.</p>


<p>Provenance[A] = B means that bit A in Provider becomes bit B in the result of this expression.</p>


<p>Definition at line 3814 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Referenced by <a href="#a6cad94d1198ae156fb92d86da87d0992">BitPart</a>.</p>

</div>
</div>

### Provider {#a575fa6464c331b804833456d11e49d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{Local.cpp}::BitPart::Provider</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that this is a bitreverse/bswap of.</p>

<p>Definition at line 3810 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Referenced by <a href="#a6cad94d1198ae156fb92d86da87d0992">BitPart</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
