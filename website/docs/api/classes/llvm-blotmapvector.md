---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/blotmapvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BlotMapVector` Class Template

<p>An associative container with fast insertion-order (deterministic) iteration over its elements. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class KeyT, class ValueT&gt;
class llvm::BlotMapVector&lt;KeyT, ValueT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">Transforms/ObjCARC/BlotMapVector.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85db521a2e4d6283754774d556e682d3">iterator</a> = typename VectorTy::iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a912153f3f439c544fff1d30b80d27659">const_iterator</a> = typename VectorTy::const_iterator</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3cf5099b1dc21ec229f8ecd217c7379">MapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; KeyT, size_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map keys to indices in Vector. <a href="#aa3cf5099b1dc21ec229f8ecd217c7379">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd3a219c26395a4dacb85fe08d2fa0d1">VectorTy</a> = std::vector&lt; std::pair&lt; KeyT, ValueT &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keys and values. <a href="#abd3a219c26395a4dacb85fe08d2fa0d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ValueT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad27175e92a42efb5d1ef3a1e21c66822">operator[]</a> (const KeyT &amp;Arg)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a85db521a2e4d6283754774d556e682d3">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe9bb2d89b79c53645c7adef310b66f9">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a85db521a2e4d6283754774d556e682d3">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a858918a4b48c7fcb780817c1709c9d3f">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a912153f3f439c544fff1d30b80d27659">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3fac90fc710f50b9f95655bd691d2461">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a912153f3f439c544fff1d30b80d27659">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af70bdd912e7234bf0e3f14aa9b5a8244">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aefcc5941fbb1cf637f340540a85c0785">insert</a> (const std::pair&lt; KeyT, ValueT &gt; &amp;InsertPair) -&gt; std::pair&lt; <a href="#a85db521a2e4d6283754774d556e682d3">iterator</a>, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a85db521a2e4d6283754774d556e682d3">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73e3ded01b65ddc78347be07e1a87a29">find</a> (const KeyT &amp;Key)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a912153f3f439c544fff1d30b80d27659">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa973f914a1a1bebe77f3108084743f1">find</a> (const KeyT &amp;Key) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a447fee52003ca0e778c9fa372c3143d1">blot</a> (const KeyT &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is similar to erase, but instead of removing the element from the vector, it just zeros out the key in the vector. <a href="#a447fee52003ca0e778c9fa372c3143d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1286e28d794e6763e70dfc26fee1a35a">clear</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a955a07a15cf61e1d84d10cea781d25ce">empty</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">MapTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4731a6d26ac707a5c24afaa325275d6">Map</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class KeyT, class ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">VectorTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a64b36b906ae28d6010db18fe8c5c9c8f">Vector</a></td>
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

<p>An associative container with fast insertion-order (deterministic) iteration over its elements.</p>


<p>Plus the special blot operation.</p>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a912153f3f439c544fff1d30b80d27659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlotMapVector&lt; KeyT, ValueT &gt;::const_iterator =  typename VectorTy::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

### iterator {#a85db521a2e4d6283754774d556e682d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlotMapVector&lt; KeyT, ValueT &gt;::iterator =  typename VectorTy::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### MapTy {#aa3cf5099b1dc21ec229f8ecd217c7379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlotMapVector&lt; KeyT, ValueT &gt;::MapTy =  DenseMap&lt;KeyT, size_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map keys to indices in Vector.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

### VectorTy {#abd3a219c26395a4dacb85fe08d2fa0d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BlotMapVector&lt; KeyT, ValueT &gt;::VectorTy =  std::vector&lt;std::pair&lt;KeyT, ValueT&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keys and values.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#ad27175e92a42efb5d1ef3a1e21c66822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueT &amp; llvm::BlotMapVector&lt; KeyT, ValueT &gt;::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Arg)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#afe9bb2d89b79c53645c7adef310b66f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::BlotMapVector&lt; KeyT, ValueT &gt;::begin ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

### begin() {#a3fac90fc710f50b9f95655bd691d2461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::BlotMapVector&lt; KeyT, ValueT &gt;::begin ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

### blot() {#a447fee52003ca0e778c9fa372c3143d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BlotMapVector&lt; KeyT, ValueT &gt;::blot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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

<p>This is similar to erase, but instead of removing the element from the vector, it just zeros out the key in the vector.</p>


<p>This leaves iterators intact, but clients must be prepared for zeroed-out keys when iterating.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### clear() {#a1286e28d794e6763e70dfc26fee1a35a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BlotMapVector&lt; KeyT, ValueT &gt;::clear ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

### empty() {#a955a07a15cf61e1d84d10cea781d25ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlotMapVector&lt; KeyT, ValueT &gt;::empty ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### end() {#a858918a4b48c7fcb780817c1709c9d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::BlotMapVector&lt; KeyT, ValueT &gt;::end ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

### end() {#af70bdd912e7234bf0e3f14aa9b5a8244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::BlotMapVector&lt; KeyT, ValueT &gt;::end ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

### find() {#a73e3ded01b65ddc78347be07e1a87a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::BlotMapVector&lt; KeyT, ValueT &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### find() {#afa973f914a1a1bebe77f3108084743f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::BlotMapVector&lt; KeyT, ValueT &gt;::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> KeyT &amp; Key)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### insert() {#aefcc5941fbb1cf637f340540a85c0785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; iterator, bool &gt; llvm::BlotMapVector&lt; KeyT, ValueT &gt;::insert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; KeyT, ValueT &gt; &amp; InsertPair)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Map {#ab4731a6d26ac707a5c24afaa325275d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapTy llvm::BlotMapVector&lt; KeyT, ValueT &gt;::Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

### Vector {#a64b36b906ae28d6010db18fe8c5c9c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class KeyT, class ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorTy llvm::BlotMapVector&lt; KeyT, ValueT &gt;::Vector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/blotmapvector-h">BlotMapVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
