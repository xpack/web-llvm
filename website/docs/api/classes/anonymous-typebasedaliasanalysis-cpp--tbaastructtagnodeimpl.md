---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtagnodeimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TBAAStructTagNodeImpl` Class Template Reference

<p>This is a simple wrapper around an <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> which provides a higher-level interface by hiding the details of how alias analysis information is encoded in its operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename MDNodeTy&gt;
class anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt;MDNodeTy&gt; { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4aa0f92fa5df956ebd73ddafe0493e3d">TBAAStructTagNodeImpl</a> (MDNodeTy *N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">MDNodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed22d6f5db6b84f0ff4dbdd4c67e4ddd">getNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> for this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#a31ed9daca2d4d4aa3aada3e997dfb13f">TBAAStructTagNode</a>. <a href="#aed22d6f5db6b84f0ff4dbdd4c67e4ddd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac25fecbba5c84ae701f47a1f710d956">isNewFormat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isNewFormat - Return true iff the wrapped access tag is in the new size-aware format. <a href="#aac25fecbba5c84ae701f47a1f710d956">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">MDNodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd60f233755e10ec8cc8c50b56adfbbb">getBaseType</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">MDNodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91070dddd62d9b0a849104801ec8400f">getAccessType</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac0ef6a49277ded57ff3f304cd9288863">getOffset</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a17860fdaf03e300a82ca6974cb0769cc">getSize</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39bda24e1c076b046f74704651743443">isTypeImmutable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#a31ed9daca2d4d4aa3aada3e997dfb13f">TBAAStructTagNode</a> represents a type for objects which are not modified (by any means) in the context where this <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> is relevant. <a href="#a39bda24e1c076b046f74704651743443">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">MDNodeTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7fbc27c956d1369872ee1f09ab4ed252">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node should be created with createTBAAAccessTag(). <a href="#a7fbc27c956d1369872ee1f09ab4ed252">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is a simple wrapper around an <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> which provides a higher-level interface by hiding the details of how alias analysis information is encoded in its operands.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TBAAStructTagNodeImpl() {#a4aa0f92fa5df956ebd73ddafe0493e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::TBAAStructTagNodeImpl (MDNodeTy * N)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAccessType() {#a91070dddd62d9b0a849104801ec8400f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeTy * anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::getAccessType ()</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### getBaseType() {#afd60f233755e10ec8cc8c50b56adfbbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeTy * anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::getBaseType ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### getNode() {#aed22d6f5db6b84f0ff4dbdd4c67e4ddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeTy * anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::getNode ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> for this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#a31ed9daca2d4d4aa3aada3e997dfb13f">TBAAStructTagNode</a>.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### getOffset() {#ac0ef6a49277ded57ff3f304cd9288863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::getOffset ()</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### getSize() {#a17860fdaf03e300a82ca6974cb0769cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::getSize ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### isNewFormat() {#aac25fecbba5c84ae701f47a1f710d956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::isNewFormat ()</td>
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

<p>isNewFormat - Return true iff the wrapped access tag is in the new size-aware format.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### isTypeImmutable() {#a39bda24e1c076b046f74704651743443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::isTypeImmutable ()</td>
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

<p>Test if this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#a31ed9daca2d4d4aa3aada3e997dfb13f">TBAAStructTagNode</a> represents a type for objects which are not modified (by any means) in the context where this <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> is relevant.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Node {#a7fbc27c956d1369872ee1f09ab4ed252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeTy* anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; MDNodeTy &gt;::Node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This node should be created with createTBAAAccessTag().</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
