---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/macho/symbolset/const-symbol-iterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `const_symbol_iterator` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MachO::SymbolSet::const_symbol_iterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbolset-h">llvm/TextAPI/SymbolSet.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base">iterator_adaptor_base&lt;DerivedT, WrappedIteratorT, IteratorCategoryT, T, DifferenceTypeT, PointerT, ReferenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP base class for adapting an iterator to a different type. <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98cbc2c7f12a828ea808e2204d7dc729">const_symbol_iterator</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename U&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a93e51328ed9688ffbcc043e8bc07bf97">const_symbol_iterator</a> (U &amp;&amp;u)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base/#a9ac08db5b07aefa9e82e65806804268b">reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd0d38d3d8e5e3a5192936ac3b9bda02">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-facade-base/#ae2d9deb2dce97bf6cf45faf988c30a3b">pointer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49fea43b95417ee85317bc839830ae8c">operator-&gt;</a> () const</td>
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


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbolset-h">SymbolSet.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### const\_symbol\_iterator() {#a98cbc2c7f12a828ea808e2204d7dc729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::SymbolSet::const_symbol_iterator::const_symbol_iterator ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbolset-h">SymbolSet.h</a>.</p>

</div>
</div>

### const\_symbol\_iterator() {#a93e51328ed9688ffbcc043e8bc07bf97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::SymbolSet::const_symbol_iterator::const_symbol_iterator (U &amp;&amp; u)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbolset-h">SymbolSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a8170d24cedaf5c2a22d8fc0c986529aa">llvm::iterator_adaptor_base&lt; const_symbol_iterator, SymbolsMapType::const_iterator, std::forward_iterator_tag, const Symbol *, ptrdiff_t, const Symbol *, const Symbol * &gt;::iterator_adaptor_base</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-&gt;() {#a49fea43b95417ee85317bc839830ae8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::MachO::SymbolSet::const_symbol_iterator::operator-&gt; ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbolset-h">SymbolSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a563ec95255977c34566292cbdce193b3">llvm::iterator_adaptor_base&lt; const_symbol_iterator, SymbolsMapType::const_iterator, std::forward_iterator_tag, const Symbol *, ptrdiff_t, const Symbol *, const Symbol * &gt;::I</a>.</p>

</div>
</div>

### operator\*() {#acd0d38d3d8e5e3a5192936ac3b9bda02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::MachO::SymbolSet::const_symbol_iterator::operator* ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbolset-h">SymbolSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a563ec95255977c34566292cbdce193b3">llvm::iterator_adaptor_base&lt; const_symbol_iterator, SymbolsMapType::const_iterator, std::forward_iterator_tag, const Symbol *, ptrdiff_t, const Symbol *, const Symbol * &gt;::I</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbolset-h">SymbolSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
