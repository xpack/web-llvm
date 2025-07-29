---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/align
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Align` Struct

<p>This struct is a compact representation of a valid (non-zero power of two) alignment. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Align { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">llvm/Support/Alignment.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae62a876733c422b0caac829c1781faab">MaybeAlign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The log2 of the required alignment. <a href="#ae62a876733c422b0caac829c1781faab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeea954066ece7e20dec74b2a6375e11">Log2</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the log2 of the alignment. <a href="#adeea954066ece7e20dec74b2a6375e11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc730b24f87906a69665c8a67fabf92b">operator==</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparisons operators between <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>. <a href="#adc730b24f87906a69665c8a67fabf92b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc02b5456ce0355177f1a05114dfc97">operator!=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6db2dfa4fe08c5a3bbd840f16e1a1f">operator&lt;=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17585309cb006b8efedeed790277ec6a">operator&gt;=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa760bf5ec0cd9af7363672144f4dd2ca">operator&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc33978f6d17773949cd3413077b143">operator&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071a36ee5a44b84508cee86c532d99ab">encode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a representation of the alignment that encodes undefined as 0. <a href="#a071a36ee5a44b84508cee86c532d99ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e151f9c92e7da561141ba8632ac7b10">decodeMaybeAlign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dual operation of the encode function above. <a href="#a3e151f9c92e7da561141ba8632ac7b10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default is byte-aligned. <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75228a1661e767fdcfdc98a36fb0fcb">Align</a> (const Align &amp;Other)=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not perform checks in case of copy/move construct/assign, because the checks have been performed when building <span class="doxyComputerOutput">Other</span>. <a href="#af75228a1661e767fdcfdc98a36fb0fcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a1695808aaa6d8006607a2c926b41f1">Align</a> (Align &amp;&amp;Other)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690852491ad6c8360e2ca988de32a537">Align</a> (uint64_t Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21a6468880c05c1bea5ddc1030ef4d3a">Align</a> (LogValue CA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constexpr constructor from LogValue type. <a href="#a21a6468880c05c1bea5ddc1030ef4d3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1714fca6498a7b9c43137a3b8bedbb6">operator=</a> (const Align &amp;Other)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dbdf9a282f33958ee2ce400682f9241">operator=</a> (Align &amp;&amp;Other)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80735739b49cf97a491922c8f9af2cc1">value</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a hole in the type system and should not be abused. <a href="#a80735739b49cf97a491922c8f9af2cc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a648e1baa573dcc8a550235ed44e7ae">previous</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721c5731f4c09f0784eaae1cd9a2539a">ShiftValue</a> = 0</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t kValue&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7699332a966bc646e928f780142c43a">Constant</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow constructions of constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>. <a href="#ac7699332a966bc646e928f780142c43a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35d8c4da117386fb67db052a36ecce50">Of</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow constructions of constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> from types. <a href="#a35d8c4da117386fb67db052a36ecce50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This struct is a compact representation of a valid (non-zero power of two) alignment.</p>


<p>It is suitable for use as static global constants.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<div class="doxySectionDef">

## Friends

### decodeMaybeAlign {#a3e151f9c92e7da561141ba8632ac7b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> unsigned Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dual operation of the encode function above.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> and <a href="#ae62a876733c422b0caac829c1781faab">MaybeAlign</a>.</p>


<p>Referenced by <a href="#ae62a876733c422b0caac829c1781faab">MaybeAlign</a>.</p>

</div>
</div>

### encode {#a071a36ee5a44b84508cee86c532d99ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend unsigned struct <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> A</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a representation of the alignment that encodes undefined as 0.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#ae62a876733c422b0caac829c1781faab">MaybeAlign</a>.</p>

</div>
</div>

### Log2 {#adeea954066ece7e20dec74b2a6375e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend unsigned <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> A</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the log2 of the alignment.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a>.</p>

</div>
</div>

### MaybeAlign {#ae62a876733c422b0caac829c1781faab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The log2 of the required alignment.</p>


<p>ShiftValue is less than 64 by construction.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a>, <a href="#a3e151f9c92e7da561141ba8632ac7b10">decodeMaybeAlign</a> and <a href="#ae62a876733c422b0caac829c1781faab">MaybeAlign</a>.</p>


<p>Referenced by <a href="#a3e151f9c92e7da561141ba8632ac7b10">decodeMaybeAlign</a>, <a href="#a071a36ee5a44b84508cee86c532d99ab">encode</a> and <a href="#ae62a876733c422b0caac829c1781faab">MaybeAlign</a>.</p>

</div>
</div>

### operator!= {#aedc02b5456ce0355177f1a05114dfc97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Lhs, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Rhs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>Reference <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a>.</p>

</div>
</div>

### operator&lt; {#aa760bf5ec0cd9af7363672144f4dd2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Lhs, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Rhs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>Reference <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a>.</p>

</div>
</div>

### operator&lt;= {#add6db2dfa4fe08c5a3bbd840f16e1a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Lhs, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Rhs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>Reference <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a>.</p>

</div>
</div>

### operator== {#adc730b24f87906a69665c8a67fabf92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Lhs, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Rhs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Comparisons operators between <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>Reference <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a>.</p>

</div>
</div>

### operator&gt; {#afdc33978f6d17773949cd3413077b143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Lhs, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Rhs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>Reference <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a>.</p>

</div>
</div>

### operator&gt;= {#a17585309cb006b8efedeed790277ec6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Lhs, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Rhs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>Reference <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Align() {#ae18e74b77ef6d55c8c3bd8c1a00cc2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Align::Align ()</td>
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

<p>Default is byte-aligned.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>Referenced by <a href="#a8a1695808aaa6d8006607a2c926b41f1">Align</a>, <a href="#af75228a1661e767fdcfdc98a36fb0fcb">Align</a>, <a href="#ac7699332a966bc646e928f780142c43a">Constant</a>, <a href="#a3e151f9c92e7da561141ba8632ac7b10">decodeMaybeAlign</a>, <a href="#adeea954066ece7e20dec74b2a6375e11">Log2</a>, <a href="#ae62a876733c422b0caac829c1781faab">MaybeAlign</a>, <a href="#a35d8c4da117386fb67db052a36ecce50">Of</a>, <a href="#aedc02b5456ce0355177f1a05114dfc97">operator!=</a>, <a href="#aa760bf5ec0cd9af7363672144f4dd2ca">operator&lt;</a>, <a href="#add6db2dfa4fe08c5a3bbd840f16e1a1f">operator&lt;=</a>, <a href="#a6dbdf9a282f33958ee2ce400682f9241">operator=</a>, <a href="#ad1714fca6498a7b9c43137a3b8bedbb6">operator=</a>, <a href="#adc730b24f87906a69665c8a67fabf92b">operator==</a>, <a href="#afdc33978f6d17773949cd3413077b143">operator&gt;</a>, <a href="#a17585309cb006b8efedeed790277ec6a">operator&gt;=</a> and <a href="#a0a648e1baa573dcc8a550235ed44e7ae">previous</a>.</p>

</div>
</div>

### Align() {#af75228a1661e767fdcfdc98a36fb0fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Align::Align (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; Other)</td>
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

<p>Do not perform checks in case of copy/move construct/assign, because the checks have been performed when building <span class="doxyComputerOutput">Other</span>.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### Align() {#a8a1695808aaa6d8006607a2c926b41f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Align::Align (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp;&amp; Other)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### Align() {#a690852491ad6c8360e2ca988de32a537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Align::Align (uint64_t Value)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a434f6a0d80fb13e4326e848a6391f057">llvm::isPowerOf2_64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>.</p>

</div>
</div>

### Align() {#a21a6468880c05c1bea5ddc1030ef4d3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Align::Align (LogValue CA)</td>
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

<p>Constexpr constructor from LogValue type.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ad1714fca6498a7b9c43137a3b8bedbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align &amp; llvm::Align::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; Other)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator=() {#a6dbdf9a282f33958ee2ce400682f9241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align &amp; llvm::Align::operator= (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp;&amp; Other)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### previous() {#a0a648e1baa573dcc8a550235ed44e7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::Align::previous ()</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### value() {#a80735739b49cf97a491922c8f9af2cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::Align::value ()</td>
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

<p>This is a hole in the type system and should not be abused.</p>


<p>Needed to interact with C for instance.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a9fd3cdd22c698232d4998d7b3ea7b21a">llvm::AArch64FunctionInfo::AArch64FunctionInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a65edce9c8505e3d3b9c0d90794458288">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAccessedPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a062f49b866f0e49c0dd872c2a904b5db">llvm::AttrBuilder::addAlignmentAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0ee1f18526ee78ef18612b6a86dc16fc">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAllocas</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a9099509c2ae2a88e0bb1b01fd404f40a">llvm::AttrBuilder::addStackAlignmentAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#aa4909014e5875c7b2d1cd6fdd7ab7e89">llvm::RISCVRegisterInfo::adjustReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afff5074588f0423a669618a7134e13ec">llvm::alignAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#aef3aaf3bf7c0ec3ad8ad4941b14bb846">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::AllocateSlow</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a0494e300dac616c8ca39b2dbc8b1276c">llvm::AMDGPURegisterBankInfo::applyMappingDynStackAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#adc3de6cf6278fe59671bbdd02e4c1516">llvm::HexagonFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aa5f844c0201df2446266aa977e285f5f">llvm::MachineIRBuilder::buildAssertAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ab00eba007903e9b4a69440782cd7c9c9">llvm::MachineIRBuilder::buildDynStackAlloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a4e820fafe9db53cc4c12257e709dccde">anonymous{PPCBranchSelector.cpp}::PPCBSel::computeBranchSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#abc4d6b7d638e45034130bc3ab18e5be6">llvm::MCAssembler::computeFragmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af12404037d26556e018e61366f026aaa">llvm::RuntimeDyldImpl::computeSectionStubBufSize</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#af089befa203447cdf71f665a1993a997">llvm::RuntimeDyldImpl::computeTotalAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#afa922043d31aa2d3410fe0be8791b795">llvm::IRBuilderBase::CreateMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a483f68557374e8fc58f8a294e7f1268e">llvm::IRBuilderBase::CreateMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aee07a8623893cdad858a3b5f77354375">llvm::IRBuilderBase::CreateMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aad07e3e0fa03f6c780e13d924325d8d0">llvm::IRBuilderBase::CreateMaskedStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a6159cb24e3496f5b8bd5e830e052aba1">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3068d2fa3c2556694ca3db57b7c197dd">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a0bd30ba570d7cadf1358f8054ffe4af3">emitAligningInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#afcc6f7320bff272e150ff3e6c2d34a68">llvm::AMDGPUTargetAsmStreamer::emitAMDGPULDS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#ac92f761a7db46f169f322b550dfedbb7">llvm::MCELFStreamer::emitBundleAlignMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5c9184047a9545737b7e35c9607c64df">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitCodeAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ace1de8acc8ac15962f04832273df87b1">llvm::SIFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a9c2ee381172db4d044e61d3438031d6b">llvm::HexagonDAGToDAGISel::emitFunctionEntryCode</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa905c95a461602c484dfdf155114f4c7">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac78e4ff0f9a757b578b967d5bd1f70ee">llvm::WebAssemblyFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a7dd171407e8c0e19195ea2039f3f83b6">llvm::RuntimeDyldImpl::emitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a4d3a29c0e2103ce92ec80ac1f6eee78a">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfselectiondaginfo/#ac5b54a21e5f5d3216cae433497cb16d7">llvm::BPFSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a967216a8cd485b60edd32db5b0ef2683">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/armselectiondaginfo/#a452e4db911448c4d2180e4535b03d8fe">llvm::ARMSelectionDAGInfo::EmitTargetCodeForMemset</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#acd79313d43de902e2f2f8d2c0189215c">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad865338e071057b5d2a249902281063a">llvm::MachineFunction::estimateFunctionSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/#a44391e7c48a75eb286fba96cde238ca9">anonymous{DAGCombiner.cpp}::LoadedSlice::getAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a5d36c914304ad459642fcae234d04021">getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a956dcf23a0d1926a5cbd98eebf191888">llvm::GlobalObject::getAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a4787a28914950099e7ceb1b9a27f4bae">anonymous{PPCBranchSelector.cpp}::PPCBSel::GetAlignmentAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab95d4485884d2e093f534590f24cfe0d">llvm::LegalizerHelper::getDynStackAllocTargetPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#ade886f9a8ca0106ed64320647cbc1646">getELFSectionNameForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolmacho/#a3d42cecd93e81cab0163fc6d56fba6ac">llvm::MCSymbolMachO::getEncodedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#ab0097819d1d3f4c8eca96c9d9ac4fa0d">llvm::MachineJumpTableInfo::getEntryAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a3290bcbb58f1e5d0c6006373c1e55053">llvm::LoongArchFrameLowering::getFirstSPAdjustAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a16cde5f8fc9f15e96e996e063f1dcb9c">llvm::RISCVFrameLowering::getFirstSPAdjustAmount</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a7a7d0ca18a51d0d4829fb467deed15e9">llvm::M68kFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a768d59ed528e3f461065b20571b913dc">anonymous{AddressSanitizer.cpp}::AddressSanitizer::getInterestingMemoryOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4988f54643e5c2613c9a0682ccccccbf">llvm::AMDGPU::getInterestingMemoryOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a04b3a69fabb49a792bdd785030325f89">llvm::HexagonTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/writablememorybuffer/#a4cb6ea02c3dec9abe04c03e501c60f75">llvm::WritableMemoryBuffer::getNewUninitMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a24d0c79fc6f4ac2aca2deb4d48d0605c">llvm::RISCVTargetLowering::getOptimalMemOpType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86selectiondaginfo-cpp/#a70bdf72b815f67e983ebd11418251738">getOptimalRepType</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a8d7f8a73873448dc2bae97e066450dba">llvm::NVPTXTargetLowering::getPrototype</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a2bdefa4c8e1d99d585232cf526147891">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::getShadowAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#afdb244cc3da7d9ac6bc08afcbc4e3633">llvm::RISCVTargetLowering::getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae2dcbf9f4bf17b489bfdebc4187d25d4">llvm::PPCTTIImpl::getVPMemoryOpCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2c1978d516a0154dd7f006e502ab4cfa">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::handleDynamicAllocaCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af0b80ad51fe1f4372499e354b6f2e402">llvm::AMDGPU::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af414e22c02fcc9ff3ce2d81ee8d3cfcb">llvm::AMDGPU::instrumentAddressImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#ab3c6b015437b10cfeec57b442173b6bc">isAgainstBoundary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25f1d7ccf87af8d87fcb950f7ed758b5">llvm::isAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#aec0a89ba2bd4f839f4509ff10117b85f">isBitAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a3e49ed1824b63334071840d20aab03ba">isDereferenceableAndAlignedPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/memop/#a1e6dafb4e0d2911060e49fe4de93f80c">llvm::MemOp::isDstAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a0a4718b6006abc33142947dd02f514c8">isGPRShadowAligned</a>, <a href="/web-llvm/docs/api/structs/llvm/memop/#aa6086c03242b56d4a71cf12a2fbf1049">llvm::MemOp::isSrcAligned</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8679ab19e5fd70f2011394a4923d7c43">LowerAsSplatVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#abcceb75e0f115b68f1a484fd93b19f07">llvm::SITargetLowering::LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a8308bacd5a1d10fdc7ac14c784f6ce0d">llvm::MipsTargetLowering::lowerSTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a39595844bf818c3700df1bd898912dcb">llvm::HexagonTargetLowering::LowerUnalignedLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#af699e5a47a59c1c3b1044c30f999df43">anonymous{ELFObjectWriter.cpp}::ELFWriter::maybeWriteCompression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b1c5b79ea6d5bea03c7c878cd6b12f0">llvm::operator!=</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d675cadc63d24dded8539354d0d76dc">llvm::operator&lt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-atomicexpandpass-cpp-/#a2281c88b416c0b993a48a3dd3729149a">anonymous{AtomicExpandPass.cpp}::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/alignvectors/#af86eed218a2f23e635b305f41b7776c3">anonymous{HexagonVectorCombine.cpp}::AlignVectors::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0534ca33ef8bfc25aae79bf95b50bcc2">llvm::operator&lt;=</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a46b7d0379a004ddbbf976edc4ac1c698">llvm::operator==</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57e37612bd9265fcd7972ece78a12d1c">llvm::operator&gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0183289628f1f2fb2139d2148da514cc">llvm::operator&gt;=</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-0eeacf48dfe007adc51330f03710cc90/#aa58f7404e80a6714eeb52948d566c3f7">llvm::yaml::ScalarTraits&lt; Align &gt;::output</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a355a1f30be913f4dc74c51af277fd74a">llvm::PPCRegisterInfo::prepareDynamicAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab49a74c3c0e9f35a453eb0db340424e7">llvm::MachineFrameInfo::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a4706e639e364501f6000985df1222c58">llvm::MachineMemOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adad68dd11c1995cc4f63e51986f50ce0">llvm::MachineBasicBlock::printName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8543371395854bee27033b8e24836cb0">replaceFrameSizeAndAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a7a4a4089f8f04bc4d76b68399bdb6099">llvm::RISCVMachineFunctionInfo::RISCVMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizerbinarymetadata-cpp-/machinesanitizerbinarymetadata/#a937f0d635f382c2a5befe696ddd43770">anonymous{SanitizerBinaryMetadata.cpp}::MachineSanitizerBinaryMetadata::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae29a60720e41fdf677935d16ad9d3b5b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a310a2b4f7197b620ecb3babef5637cc2">setAlignFlagsForFI</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#aa05af02ae909fc030207294fa161cd08">llvm::LoongArchAsmBackend::shouldInsertExtraNopBytesForCodeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a6df2a46541fffb2b35320ae71b7fe26c">llvm::RISCVAsmBackend::shouldInsertExtraNopBytesForCodeAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1952f8650a3b903ff78f5d5eb09c29a4">llvm::SIInstrInfo::splitMUBUFOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#afc576f8a8ddd42537a82e1cedc179ae1">tocDataChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6c91e92748e13f94700487fcac689e60">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::tryToPairLdStInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a97cbd12fcf61e3cf7db640c3661e66df">tryToShorten</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca36878e37b708e22ace80dececead61">llvm::UnknownPadding</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignfloating/#a0206ea336f22470d5fe01f65dae9eb85">anonymous{AttributorAttributes.cpp}::AAAlignFloating::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ShiftValue {#a721c5731f4c09f0784eaae1cd9a2539a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Align::ShiftValue = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Constant() {#ac7699332a966bc646e928f780142c43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t kValue&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Align llvm::Align::Constant ()</td>
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

<p>Allow constructions of constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a157580cd43622bf53270856bf51da098">llvm::CTLog2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4fcc58c4d285835e0ac6fc644012b0be">llvm::X86TargetLowering::getByValTypeAlignment</a> and <a href="#a35d8c4da117386fb67db052a36ecce50">Of</a>.</p>

</div>
</div>

### Of() {#a35d8c4da117386fb67db052a36ecce50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr Align llvm::Align::Of ()</td>
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

<p>Allow constructions of constexpr <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> from types.</p>


<p>Compile time equivalent to Align(alignof(T)).</p>


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a>.</p>


<p>References <a href="#ae18e74b77ef6d55c8c3bd8c1a00cc2f4">Align</a> and <a href="#ac7699332a966bc646e928f780142c43a">Constant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator/#a9f4abb0f59d9fd2ce9dfe8ceebffcb38">llvm::SpecificBumpPtrAllocator&lt; T &gt;::DestroyAll</a>, <a href="/web-llvm/docs/api/classes/llvm/trailing-objects-internal/trailingobjectsimpl-d5dc5f9bc1738bd42d17ac7472482035/#a4777f416777ffb24914b0d4717585dbb">llvm::trailing_objects_internal::TrailingObjectsImpl&lt; Align, BaseTy, TopTrailingObj, PrevTy, NextTy, MoreTys... &gt;::getTrailingObjectsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/trailing-objects-internal/trailingobjectsimpl-d5dc5f9bc1738bd42d17ac7472482035/#a20f5f514b0855117c9f1bf769bcb627b">llvm::trailing_objects_internal::TrailingObjectsImpl&lt; Align, BaseTy, TopTrailingObj, PrevTy, NextTy, MoreTys... &gt;::getTrailingObjectsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray/#acba42131e3ca927d799ec42499a022df">llvm::FixedStreamArray&lt; CrossModuleExport &gt;::operator[]</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab88a8b3835c1028f8fd6c2b23f396d30">llvm::BinaryStreamReader::readArray</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">Alignment.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
