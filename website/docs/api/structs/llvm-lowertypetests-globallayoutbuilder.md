---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lowertypetests/globallayoutbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GlobalLayoutBuilder` Struct Reference

<p>This class implements a layout algorithm for globals referenced by bit sets that tries to keep members of small bit sets together. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::lowertypetests::GlobalLayoutBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">llvm/Transforms/IPO/LowerTypeTests.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2354a7882002ba4c12cd5f3be8dba7dd">GlobalLayoutBuilder</a> (uint64_t NumObjects)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc53ed9289ca61898a56ea65b8a457db">addFragment</a> (const std::set&lt; uint64_t &gt; &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add F to the layout while trying to keep its indices contiguous. <a href="#abc53ed9289ca61898a56ea65b8a457db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; uint64_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d2e54b342691d69ccfc9e799d404668">Fragments</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The computed layout. <a href="#a5d2e54b342691d69ccfc9e799d404668">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3e6889c1625ade2687b7fee501f64be">FragmentMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from object index to fragment index. <a href="#ad3e6889c1625ade2687b7fee501f64be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class implements a layout algorithm for globals referenced by bit sets that tries to keep members of small bit sets together.</p>


<p>This can significantly reduce bit set sizes in many cases.</p>


<p>It works by assembling fragments of layout from sets of referenced globals. Each set of referenced globals causes the algorithm to create a new fragment, which is assembled by appending each referenced global in the set into the fragment. If a referenced global has already been referenced by an fragment created earlier, we instead delete that fragment and append its contents into the fragment we are assembling.</p>


<p>By starting with the smallest fragments, we minimize the size of the fragments that are copied into larger fragments. This is most intuitively thought about when considering the case where the globals are virtual tables and the bit sets represent their derived classes: in a single inheritance hierarchy, the optimum layout would involve a depth-first search of the class hierarchy (and in fact the computed layout ends up looking a lot like a DFS), but a naive DFS would not work well in the presence of multiple inheritance. This aspect of the algorithm ends up fitting smaller hierarchies inside larger ones where that would be beneficial.</p>


<p>For example, consider this class hierarchy:</p>


<p>A B \ / | \ C D E</p>


<p>We have five bit sets: bsA (A, C), bsB (B, C, D, E), bsC (C), bsD (D) and bsE (E). If we laid out our objects by DFS traversing B followed by A, our layout would be {B, C, D, E, A}. This is optimal for bsB as it needs to cover the only 4 objects in its hierarchy, but not for bsA as it needs to cover 5 objects, i.e. the entire layout. Our algorithm proceeds as follows:</p>


<p>Add bsC, fragments {{C}} Add bsD, fragments {{C}, {D}} Add bsE, fragments {{C}, {D}, {E}} Add bsA, fragments {{A, C}, {D}, {E}} Add bsB, fragments {{B, A, C, D, E}}</p>


<p>This layout is optimal for bsA, as it now only needs to cover two (i.e. 3 fewer) objects, at the cost of bsB needing to cover 1 more object.</p>


<p>The bit set lowering pass assigns an object index to each object that needs to be laid out, and calls addFragment for each bit set passing the object indices of its referenced globals. It then assembles a layout from the computed layout in the Fragments field.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GlobalLayoutBuilder() {#a2354a7882002ba4c12cd5f3be8dba7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::lowertypetests::GlobalLayoutBuilder::GlobalLayoutBuilder (uint64_t NumObjects)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>References <a href="#ad3e6889c1625ade2687b7fee501f64be">FragmentMap</a> and <a href="#a5d2e54b342691d69ccfc9e799d404668">Fragments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFragment() {#abc53ed9289ca61898a56ea65b8a457db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalLayoutBuilder::addFragment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::set&lt; uint64_t &gt; &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add F to the layout while trying to keep its indices contiguous.</p>


<p>If a previously seen fragment uses any of F's indices, that fragment will be laid out inside F.</p>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad3e6889c1625ade2687b7fee501f64be">FragmentMap</a> and <a href="#a5d2e54b342691d69ccfc9e799d404668">Fragments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FragmentMap {#ad3e6889c1625ade2687b7fee501f64be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::lowertypetests::GlobalLayoutBuilder::FragmentMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from object index to fragment index.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Referenced by <a href="#abc53ed9289ca61898a56ea65b8a457db">addFragment</a> and <a href="#a2354a7882002ba4c12cd5f3be8dba7dd">GlobalLayoutBuilder</a>.</p>

</div>
</div>

### Fragments {#a5d2e54b342691d69ccfc9e799d404668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;uint64_t&gt; &gt; llvm::lowertypetests::GlobalLayoutBuilder::Fragments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The computed layout.</p>


<p>Each element of this vector contains a fragment of layout (which may be empty) consisting of object indices.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a>.</p>


<p>Referenced by <a href="#abc53ed9289ca61898a56ea65b8a457db">addFragment</a> and <a href="#a2354a7882002ba4c12cd5f3be8dba7dd">GlobalLayoutBuilder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/lowertypetests-h">LowerTypeTests.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp">LowerTypeTests.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
