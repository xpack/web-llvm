---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaanodeimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TBAANodeImpl` Class Template Reference

<p>This is a simple wrapper around an <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> which provides a higher-level interface by hiding the details of how alias analysis information is encoded in its operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename MDNodeTy&gt;
class anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt;MDNodeTy&gt; { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#adc45236131bdfc2d1b48649c63c387e6">TBAANodeImpl</a> ()=default</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad027cb3b15346a1326eb4757456109fb">TBAANodeImpl</a> (MDNodeTy *N)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4c263dd6898a1b88807a867a003a79f">getNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNode - Get the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> for this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#aed6974c4343ed0d45ee3453072a24591">TBAANode</a>. <a href="#aa4c263dd6898a1b88807a867a003a79f">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad8f7bbe399ed7df1ce28910dd5b6e9f">isNewFormat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isNewFormat - Return true iff the wrapped type node is in the new size-aware format. <a href="#aad8f7bbe399ed7df1ce28910dd5b6e9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MDNodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad598a10777eb06c93aced64710df5951">getParent</a> () const -&gt; <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaanodeimpl">TBAANodeImpl</a>&lt; MDNodeTy &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getParent - Get this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#aed6974c4343ed0d45ee3453072a24591">TBAANode</a>'s Alias tree parent. <a href="#ad598a10777eb06c93aced64710df5951">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9bbbef7a85885dd5bd420999d6f6d86c">isTypeImmutable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#aed6974c4343ed0d45ee3453072a24591">TBAANode</a> represents a type for objects which are not modified (by any means) in the context where this <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> is relevant. <a href="#a9bbbef7a85885dd5bd420999d6f6d86c">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa319b863b107d28d373122999bdc1141">Node</a> = nullptr</td>
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

<p>This is a simple wrapper around an <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> which provides a higher-level interface by hiding the details of how alias analysis information is encoded in its operands.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TBAANodeImpl() {#adc45236131bdfc2d1b48649c63c387e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; MDNodeTy &gt;::TBAANodeImpl ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### TBAANodeImpl() {#ad027cb3b15346a1326eb4757456109fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; MDNodeTy &gt;::TBAANodeImpl (MDNodeTy * N)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNode() {#aa4c263dd6898a1b88807a867a003a79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeTy * anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; MDNodeTy &gt;::getNode ()</td>
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

<p>getNode - Get the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> for this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#aed6974c4343ed0d45ee3453072a24591">TBAANode</a>.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### getParent() {#ad598a10777eb06c93aced64710df5951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TBAANodeImpl&lt; MDNodeTy &gt; anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; MDNodeTy &gt;::getParent ()</td>
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

<p>getParent - Get this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#aed6974c4343ed0d45ee3453072a24591">TBAANode</a>'s Alias tree parent.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### isNewFormat() {#aad8f7bbe399ed7df1ce28910dd5b6e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; MDNodeTy &gt;::isNewFormat ()</td>
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

<p>isNewFormat - Return true iff the wrapped type node is in the new size-aware format.</p>

<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

### isTypeImmutable() {#a9bbbef7a85885dd5bd420999d6f6d86c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; MDNodeTy &gt;::isTypeImmutable ()</td>
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

<p>Test if this <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#aed6974c4343ed0d45ee3453072a24591">TBAANode</a> represents a type for objects which are not modified (by any means) in the context where this <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> is relevant.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Node {#aa319b863b107d28d373122999bdc1141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MDNodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNodeTy* anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; MDNodeTy &gt;::Node = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
