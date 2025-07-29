---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/addressrangesbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AddressRangesBase` Class Template

<p>The <a href="/web-llvm/docs/api/classes/llvm/addressrangesbase">AddressRangesBase</a> class presents the base functionality for the normalized address ranges collection. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
class llvm::AddressRangesBase&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">llvm/ADT/AddressRanges.h</a>"
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6fb3cf5477e75da6c988fa87c5a92b4c">Collection</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; T &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a10709aea3866b9af3b946e3b0f2cd756">operator[]</a> (size_t i) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63192c0006519daa36a88936986ffd75">operator==</a> (const AddressRangesBase&lt; T &gt; &amp;RHS) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c2b308fa3c8edb139d87739d5d670a5">clear</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abfc30f77bef6a72f6fc39a3d3d3b9b63">empty</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f7dc6877a2e9502fe7c51b9aef7ce6f">contains</a> (uint64_t Addr) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad13ee3edc9e7ee34df1e1eb20cd9ea3b">contains</a> (AddressRange Range) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a255e3188ae1aedd31cb9891a8583f6f3">reserve</a> (size_t Capacity)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af2086278ec5619ea74bad03206627f23">size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a98c9746510478a6bf94369316794e1ea">getRangeThatContains</a> (uint64_t Addr) const -&gt; std::optional&lt; T &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Collection::const_iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae192c3957dce8b86e3e9c881b04426ee">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Collection::const_iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf932d4ddadfde5194bf775efa1348f4">end</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Collection::const_iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76d0d4da8f92c8c423bae6abdbd417bf">find</a> (uint64_t Start, uint64_t End) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6fb3cf5477e75da6c988fa87c5a92b4c">Collection</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a684c16e5f330278b24651bdd96ae172f">Ranges</a></td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/addressrangesbase">AddressRangesBase</a> class presents the base functionality for the normalized address ranges collection.</p>


<p>This class keeps a sorted vector of AddressRange-like objects and can perform searches efficiently. The address ranges are always sorted and never contain any invalid, empty or intersected address ranges.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### Collection {#a6fb3cf5477e75da6c988fa87c5a92b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AddressRangesBase&lt; T &gt;::Collection =  SmallVector&lt;T&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a10709aea3866b9af3b946e3b0f2cd756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; llvm::AddressRangesBase&lt; T &gt;::operator[] (size_t i)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### operator==() {#a63192c0006519daa36a88936986ffd75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AddressRangesBase&lt; T &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/addressrangesbase">AddressRangesBase</a>&lt; T &gt; &amp; RHS)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>References <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#ae192c3957dce8b86e3e9c881b04426ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Collection::const_iterator llvm::AddressRangesBase&lt; T &gt;::begin ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>Reference <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>

</div>
</div>

### clear() {#a6c2b308fa3c8edb139d87739d5d670a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AddressRangesBase&lt; T &gt;::clear ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>Reference <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>

</div>
</div>

### contains() {#a3f7dc6877a2e9502fe7c51b9aef7ce6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AddressRangesBase&lt; T &gt;::contains (uint64_t Addr)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>References <a href="#a76d0d4da8f92c8c423bae6abdbd417bf">llvm::AddressRangesBase&lt; T &gt;::find</a> and <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### contains() {#ad13ee3edc9e7ee34df1e1eb20cd9ea3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AddressRangesBase&lt; T &gt;::contains (<a href="/web-llvm/docs/api/classes/llvm/addressrange">AddressRange</a> Range)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>References <a href="#a76d0d4da8f92c8c423bae6abdbd417bf">llvm::AddressRangesBase&lt; T &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>

</div>
</div>

### empty() {#abfc30f77bef6a72f6fc39a3d3d3b9b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AddressRangesBase&lt; T &gt;::empty ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>Reference <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>

</div>
</div>

### end() {#adf932d4ddadfde5194bf775efa1348f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Collection::const_iterator llvm::AddressRangesBase&lt; T &gt;::end ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>Reference <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>

</div>
</div>

### getRangeThatContains() {#a98c9746510478a6bf94369316794e1ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; T &gt; llvm::AddressRangesBase&lt; T &gt;::getRangeThatContains (uint64_t Addr)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>References <a href="#a76d0d4da8f92c8c423bae6abdbd417bf">llvm::AddressRangesBase&lt; T &gt;::find</a> and <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ac4560fb1d6b91d4ba6edb7e907573c1e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame</a>.</p>

</div>
</div>

### reserve() {#a255e3188ae1aedd31cb9891a8583f6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AddressRangesBase&lt; T &gt;::reserve (size_t Capacity)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>Reference <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>

</div>
</div>

### size() {#af2086278ec5619ea74bad03206627f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::AddressRangesBase&lt; T &gt;::size ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>Reference <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6ff5af16abef2f212c16d3b905726b57">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### find() {#a76d0d4da8f92c8c423bae6abdbd417bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Collection::const_iterator llvm::AddressRangesBase&lt; T &gt;::find (uint64_t Start, uint64_t End)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/addressrange/#a8569782fc5fce87556b3761438d990d9">llvm::AddressRange::end</a>, <a href="#a684c16e5f330278b24651bdd96ae172f">llvm::AddressRangesBase&lt; T &gt;::Ranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ad13ee3edc9e7ee34df1e1eb20cd9ea3b">llvm::AddressRangesBase&lt; T &gt;::contains</a>, <a href="#a3f7dc6877a2e9502fe7c51b9aef7ce6f">llvm::AddressRangesBase&lt; T &gt;::contains</a> and <a href="#a98c9746510478a6bf94369316794e1ea">llvm::AddressRangesBase&lt; T &gt;::getRangeThatContains</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Ranges {#a684c16e5f330278b24651bdd96ae172f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Collection llvm::AddressRangesBase&lt; T &gt;::Ranges</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a>.</p>


<p>Referenced by <a href="#ae192c3957dce8b86e3e9c881b04426ee">llvm::AddressRangesBase&lt; T &gt;::begin</a>, <a href="#a6c2b308fa3c8edb139d87739d5d670a5">llvm::AddressRangesBase&lt; T &gt;::clear</a>, <a href="#ad13ee3edc9e7ee34df1e1eb20cd9ea3b">llvm::AddressRangesBase&lt; T &gt;::contains</a>, <a href="#a3f7dc6877a2e9502fe7c51b9aef7ce6f">llvm::AddressRangesBase&lt; T &gt;::contains</a>, <a href="#abfc30f77bef6a72f6fc39a3d3d3b9b63">llvm::AddressRangesBase&lt; T &gt;::empty</a>, <a href="#adf932d4ddadfde5194bf775efa1348f4">llvm::AddressRangesBase&lt; T &gt;::end</a>, <a href="#a76d0d4da8f92c8c423bae6abdbd417bf">llvm::AddressRangesBase&lt; T &gt;::find</a>, <a href="#a98c9746510478a6bf94369316794e1ea">llvm::AddressRangesBase&lt; T &gt;::getRangeThatContains</a>, <a href="#a63192c0006519daa36a88936986ffd75">llvm::AddressRangesBase&lt; T &gt;::operator==</a>, <a href="#a10709aea3866b9af3b946e3b0f2cd756">llvm::AddressRangesBase&lt; T &gt;::operator[]</a>, <a href="#a255e3188ae1aedd31cb9891a8583f6f3">llvm::AddressRangesBase&lt; T &gt;::reserve</a> and <a href="#af2086278ec5619ea74bad03206627f23">llvm::AddressRangesBase&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">AddressRanges.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
