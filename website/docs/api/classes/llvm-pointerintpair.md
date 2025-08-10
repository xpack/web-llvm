---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pointerintpair
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PointerIntPair` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> - This class implements a pair of a pointer and small integer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;
class llvm::PointerIntPair&lt;PointerTy, IntBits, IntType, PtrTraits, Info&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">llvm/ADT/PointerIntPair.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a935df971644d6a734a8e2dd5663465ed">InfoTy</a> = <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ad48fb0630d5c2580d123f11e76e885">PointerIntPair</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a46b276f59e317725ba314cb7342e1510">PointerIntPair</a> (PointerTy PtrVal, IntType IntVal)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a15fab532feb0a8d920e8b01b7b739e24">PointerIntPair</a> (PointerTy PtrVal)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a20c3573a9ed81c2bbe6e4c86282e6f5f">operator==</a> (const PointerIntPair &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16d9c7cb91b3a980d7b80fd51d8dca90">operator!=</a> (const PointerIntPair &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a05f876c8fba612b94afed95c06e90518">operator&lt;</a> (const PointerIntPair &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa524e70944b6b62e85d9fc77dacd0694">operator&gt;</a> (const PointerIntPair &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a604f6c454026b537c606bd923b507804">operator&lt;=</a> (const PointerIntPair &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a234c6f051143218e90222eaa6810dd">operator&gt;=</a> (const PointerIntPair &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8b55437ca130fe0c826e94e669e5d99">getPointer</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">IntType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f4f059462994b43b97b1213651fa969">getInt</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ebf24939b41850c8fe52ac40926a121">setPointer</a> (PointerTy PtrVal) &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a60c0e4f0ed13c971edabd76dceada467">setInt</a> (IntType IntVal) &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51ea96d97f0a4774267fc33ab7473df5">initWithPointer</a> (PointerTy PtrVal) &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c7149b1ad550ed8ccdec643bc0ef117">setPointerAndInt</a> (PointerTy PtrVal, IntType IntVal) &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8a4f280fe6086d53c474b506187cecb">getAddrOfPointer</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9390724a4762323ecb97c973a89e236e">getAddrOfPointer</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a74b18b03ef6cbee0e5f26c6fccee5d1d">getOpaqueValue</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbe4fe683ab04772bc446d7b8d583366">setFromOpaqueValue</a> (void *Val) &amp;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/punnedpointer">detail::PunnedPointer</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7e1cf7d0606d571ef99114a2d945bd75">Value</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8bbe13fef9fc26549110137f4ff036ce">getFromOpaqueValue</a> (void *V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1714bfd321a703bc81b54eceab84efff">getFromOpaqueValue</a> (const void *V)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> - This class implements a pair of a pointer and small integer.</p>


<p>It is designed to represent this in the space required by one pointer by bitmangling the integer into the low part of the pointer. This can only be done for small integers: typically up to 3 bits, but it depends on the number of bits available according to <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits">PointerLikeTypeTraits</a> for the type.</p>


<p>Note that <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> always puts the IntVal part in the highest bits possible. For example, PointerIntPair&lt;void*, 1, bool&gt; will put the bit for the bool into bit #2, not bit #0, which allows the low two bits to be used for something else. For example, this allows: <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt;PointerIntPair&lt;void*, 1, bool&gt;, 1, bool&gt; ... and the two bools will land in different bits.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### InfoTy {#a935df971644d6a734a8e2dd5663465ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::InfoTy =  Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PointerIntPair() {#a7ad48fb0630d5c2580d123f11e76e885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::PointerIntPair ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### PointerIntPair() {#a46b276f59e317725ba314cb7342e1510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::PointerIntPair (<a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a> PtrVal, IntType IntVal)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### PointerIntPair() {#a15fab532feb0a8d920e8b01b7b739e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::PointerIntPair (<a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a> PtrVal)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a16d9c7cb91b3a980d7b80fd51d8dca90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> &amp; RHS)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### operator&lt;() {#a05f876c8fba612b94afed95c06e90518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> &amp; RHS)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### operator&lt;=() {#a604f6c454026b537c606bd923b507804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::operator&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> &amp; RHS)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### operator==() {#a20c3573a9ed81c2bbe6e4c86282e6f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> &amp; RHS)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### operator&gt;() {#aa524e70944b6b62e85d9fc77dacd0694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> &amp; RHS)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### operator&gt;=() {#a8a234c6f051143218e90222eaa6810dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::operator&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a> &amp; RHS)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddrOfPointer() {#ac8a4f280fe6086d53c474b506187cecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerTy const  * llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getAddrOfPointer ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>Referenced by <a href="#ac8a4f280fe6086d53c474b506187cecb">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType &gt;::getAddrOfPointer</a>.</p>

</div>
</div>

### getAddrOfPointer() {#a9390724a4762323ecb97c973a89e236e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerTy * llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getAddrOfPointer ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### getInt() {#a5f4f059462994b43b97b1213651fa969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntType llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getInt ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a941c4415d0218eafdb1b1a2507160117">anonymous{CodeMoverUtils.cpp}::ControlConditions::isEquivalent</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

### getOpaqueValue() {#a74b18b03ef6cbee0e5f26c6fccee5d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getOpaqueValue ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### getPointer() {#ac8b55437ca130fe0c826e94e669e5d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerTy llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getPointer ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo/#a243c7b35c64a8a4df8f2c159f5421139">llvm::GlobalsAAResult::FunctionInfo::addFunctionInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a37ddbdd8cb4efa5072282498fdc1ac65">collectPromotionCandidates</a>, <a href="/web-llvm/docs/api/structs/llvm/aadepgraph/#a9c20fc7160687accbc260845e4b59d5c">llvm::AADepGraph::DepGetVal</a>, <a href="/web-llvm/docs/api/structs/llvm/aadepgraphnode/#a434203b3ce6a2ed6e0178f83a1dde950">llvm::AADepGraphNode::DepGetVal</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-a8d72c603246819e5ff8fe2b8d743d3d/#a1071d3a756118de6bd3a1c869764fbae">llvm::GraphTraits&lt; AADepGraphNode * &gt;::DepGetVal</a>, <a href="/web-llvm/docs/api/structs/llvm/aadepgraphnode/#a0442f4b011304216ca5fa8eb57086618">llvm::AADepGraphNode::DepGetValAA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a135ddd8bff5dd7ec257b04d1cdc9af2b">emitNonLazySymbolPointer</a>, <a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo/#ae173b2b792c9039e4fce9c0f53b963b4">llvm::GlobalsAAResult::FunctionInfo::FunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a9390724a4762323ecb97c973a89e236e">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType &gt;::getAddrOfPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a3e7ee01bba0aa270863ab1e06502f374">llvm::TargetLoweringObjectFileMachO::getCFIPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcelftargetobjectfile/#a953050dfdd0d33bc59eb08438aa5d88c">llvm::SparcELFTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a726934c33655de3d8c59b38d0e946a62">llvm::TargetLoweringObjectFileELF::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#ae41814965809c6fb6403ca6338710a25">llvm::TargetLoweringObjectFileMachO::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a941c4415d0218eafdb1b1a2507160117">anonymous{CodeMoverUtils.cpp}::ControlConditions::isEquivalent</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

### initWithPointer() {#a51ea96d97f0a4774267fc33ab7473df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::initWithPointer (<a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a> PtrVal)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>Referenced by <a href="#a15fab532feb0a8d920e8b01b7b739e24">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType &gt;::PointerIntPair</a>.</p>

</div>
</div>

### setFromOpaqueValue() {#afbe4fe683ab04772bc446d7b8d583366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::setFromOpaqueValue (void * Val)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### setInt() {#a60c0e4f0ed13c971edabd76dceada467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::setInt (IntType IntVal)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a37ddbdd8cb4efa5072282498fdc1ac65">collectPromotionCandidates</a>.</p>

</div>
</div>

### setPointer() {#a0ebf24939b41850c8fe52ac40926a121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::setPointer (<a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a> PtrVal)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

### setPointerAndInt() {#a6c7149b1ad550ed8ccdec643bc0ef117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::setPointerAndInt (<a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a> PtrVal, IntType IntVal)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/globalsaaresult/functioninfo/#a0514c42efe48f54abafb5b7550c9ae17">llvm::GlobalsAAResult::FunctionInfo::operator=</a> and <a href="#a46b276f59e317725ba314cb7342e1510">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType &gt;::PointerIntPair</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Value {#a7e1cf7d0606d571ef99114a2d945bd75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">detail::PunnedPointer&lt;PointerTy&gt; llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFromOpaqueValue() {#a8bbe13fef9fc26549110137f4ff036ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getFromOpaqueValue (void * V)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>


<p>Referenced by <a href="#a1714bfd321a703bc81b54eceab84efff">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType &gt;::getFromOpaqueValue</a>, <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits-1fe78a9776d290e591bdd1a7a3921c10/#a7f11e33eaf4c1a302913b3ec197030a7">llvm::PointerLikeTypeTraits&lt; PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits &gt; &gt;::getFromVoidPointer</a> and <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits-1fe78a9776d290e591bdd1a7a3921c10/#a7cc211743433f64471f6dbd6e31c1250">llvm::PointerLikeTypeTraits&lt; PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits &gt; &gt;::getFromVoidPointer</a>.</p>

</div>
</div>

### getFromOpaqueValue() {#a1714bfd321a703bc81b54eceab84efff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PointerTy, unsigned IntBits, typename IntType = unsigned, typename PtrTraits = PointerLikeTypeTraits&lt;PointerTy&gt;, typename Info = PointerIntPairInfo&lt;PointerTy, IntBits, PtrTraits&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getFromOpaqueValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * V)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">PointerIntPair.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
