---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bitfield
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Bitfield` Struct

<p>Holds functions to get, set or test bitfields. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Bitfield { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">llvm/ADT/Bitfields.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static Bitfield::Type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3cd3d6331b8a3ea50db05696debf2075">get</a> (StorageType Packed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unpacks the field from the <span class="doxyComputerOutput">Packed</span> value. <a href="#a3cd3d6331b8a3ea50db05696debf2075">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static StorageType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad10aaa16d68da707e37334ca43baaf2b">test</a> (StorageType Packed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a non-zero value if the field is non-zero. <a href="#ad10aaa16d68da707e37334ca43baaf2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac5c44667e3b3ebe2ed424dbd12a35d5">set</a> (StorageType &amp;Packed, typename Bitfield::Type Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the typed value in the provided <span class="doxyComputerOutput">Packed</span> value. <a href="#aac5c44667e3b3ebe2ed424dbd12a35d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename A, typename B&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a706db80c3026ce5f7761347054eca6ae">isOverlapping</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether the two bitfields share common bits. <a href="#a706db80c3026ce5f7761347054eca6ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename A&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3a98703db928a3d2cb2dbc2868893f05">areContiguous</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename A, typename B, typename... Others&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d02a714f9e0a4f94961d78b7016404b">areContiguous</a> ()</td>
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

<p>Holds functions to get, set or test bitfields.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### areContiguous() {#a3a98703db928a3d2cb2dbc2868893f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename A&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::Bitfield::areContiguous ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Referenced by <a href="#a5d02a714f9e0a4f94961d78b7016404b">areContiguous</a>.</p>

</div>
</div>

### areContiguous() {#a5d02a714f9e0a4f94961d78b7016404b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename A, typename B, typename... Others&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::Bitfield::areContiguous ()</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>References <a href="#a3a98703db928a3d2cb2dbc2868893f05">areContiguous</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### get() {#a3cd3d6331b8a3ea50db05696debf2075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Bitfield::Type llvm::Bitfield::get (StorageType Packed)</td>
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

<p>Unpacks the field from the <span class="doxyComputerOutput">Packed</span> value.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a41c081604f65f65850620181db33f548">llvm::InlineAsm::Flag::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a945eeecdf3b5f4969d9c5aa1d1eacec1">llvm::InlineAsm::Flag::getMemoryConstraintID</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#ad425f5167e26c58c9849c6170450460b">llvm::InlineAsm::Flag::getNumOperandRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#aafed3f8d7e82cd37afdf3bb1cf6947dd">llvm::InlineAsm::Flag::getRegMayBeFolded</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a> and <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/selecthandspeculativity/#aa805dfd609789d10f3584ea58dc4722e">anonymous{SROA.cpp}::SelectHandSpeculativity::isSpeculatable</a>.</p>

</div>
</div>

### isOverlapping() {#a706db80c3026ce5f7761347054eca6ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename A, typename B&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::Bitfield::isOverlapping ()</td>
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

<p>Returns whether the two bitfields share common bits.</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#afbb5877d4ac72148b232c8fedb08bba5">llvm::Instruction::setSubclassData</a>.</p>

</div>
</div>

### set() {#aac5c44667e3b3ebe2ed424dbd12a35d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Bitfield::set (StorageType &amp; Packed, typename Bitfield::Type Value)</td>
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

<p>Sets the typed value in the provided <span class="doxyComputerOutput">Packed</span> value.</p>


<p>The method will asserts if the provided value is too big to fit in.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a41a1d51570ca5ad847d74f1f7b020ad0">llvm::InlineAsm::Flag::clearMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a5695f73e7e822cf666e2f47ee05fe6ce">llvm::InlineAsm::Flag::Flag</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/selecthandspeculativity/#a6209f400e7cf0f855586aba618156e4b">anonymous{SROA.cpp}::SelectHandSpeculativity::setAsSpeculatable</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a8a3a4a2d14c39019e5cd648081a33419">llvm::InlineAsm::Flag::setMatchingOp</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a8de6bf65ca1443186731a3391c02d1f9">llvm::InlineAsm::Flag::setMemConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a2cf882e839e78f88340e664afcd87e5d">llvm::InlineAsm::Flag::setRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/flag/#a15203762d44a454199820de3b1e09f20">llvm::InlineAsm::Flag::setRegMayBeFolded</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#afbb5877d4ac72148b232c8fedb08bba5">llvm::Instruction::setSubclassData</a>.</p>

</div>
</div>

### test() {#ad10aaa16d68da707e37334ca43baaf2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StorageType llvm::Bitfield::test (StorageType Packed)</td>
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

<p>Return a non-zero value if the field is non-zero.</p>


<p>It is more efficient than <span class="doxyComputerOutput">getField</span>.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
