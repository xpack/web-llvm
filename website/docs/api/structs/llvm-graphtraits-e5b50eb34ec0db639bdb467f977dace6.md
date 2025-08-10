---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/graphtraits-e5b50eb34ec0db639bdb467f977dace6
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `GraphTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::GraphTraits&lt;RegionInfo *&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">llvm/Analysis/RegionIterator.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits&lt;GraphType&gt;</a></td>
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

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-f3f97e3a720012d251f1ecf6267c5354">GraphTraits&lt;RegionInfoPass *&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9270a6c86d578d96d4aff31bd0720f44">nodes_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/df-iterator">df_iterator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a>, <a href="/web-llvm/docs/api/structs/llvm/df-iterator-default-set">df_iterator_default_set</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a> &gt;, false, <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/flatit">FlatIt</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a> &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a> = typename <a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> *::UnknownGraphTypeError</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a710c99843f3d7a43e0752e7e9655a8">getEntryNode</a> (RegionInfo *RI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a9270a6c86d578d96d4aff31bd0720f44">nodes_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11df11acd85a517e92e7817dd61d6d2f">nodes_begin</a> (RegionInfo *RI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a9270a6c86d578d96d4aff31bd0720f44">nodes_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd01a176b5cb653d71fbb71e2fe1c2c">nodes_end</a> (RegionInfo *RI)</td>
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


<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">RegionIterator.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NodeRef {#a741f7d63af17a7bd0bcf63f68e8658bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; RegionInfo * &gt;::NodeRef = </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">GraphTraits.h</a>.</p>

</div>
</div>

### nodes\_iterator {#a9270a6c86d578d96d4aff31bd0720f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; RegionInfo * &gt;::nodes_iterator = 
      df_iterator&lt;NodeRef, df_iterator_default_set&lt;NodeRef&gt;, false,
                  GraphTraits&lt;FlatIt&lt;NodeRef&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">RegionIterator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEntryNode() {#a9a710c99843f3d7a43e0752e7e9655a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::GraphTraits&lt; RegionInfo * &gt;::getEntryNode (<a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * RI)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">RegionIterator.h</a>.</p>


<p>References <a href="#a9a710c99843f3d7a43e0752e7e9655a8">getEntryNode</a> and <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a5e825c7a51956c5d602ebff45036b1a9">llvm::RegionInfoBase&lt; Tr &gt;::getTopLevelRegion</a>.</p>


<p>Referenced by <a href="#a9a710c99843f3d7a43e0752e7e9655a8">getEntryNode</a>, <a href="#a11df11acd85a517e92e7817dd61d6d2f">nodes_begin</a> and <a href="#a3fd01a176b5cb653d71fbb71e2fe1c2c">nodes_end</a>.</p>

</div>
</div>

### nodes\_begin() {#a11df11acd85a517e92e7817dd61d6d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nodes_iterator llvm::GraphTraits&lt; RegionInfo * &gt;::nodes_begin (<a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * RI)</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">RegionIterator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/df-iterator/#a083211af95132a32cc37f469c3d28789">llvm::df_iterator&lt; NodeRef, df_iterator_default_set&lt; NodeRef &gt;, false, GraphTraits&lt; FlatIt&lt; NodeRef &gt; &gt; &gt;::begin</a> and <a href="#a9a710c99843f3d7a43e0752e7e9655a8">getEntryNode</a>.</p>

</div>
</div>

### nodes\_end() {#a3fd01a176b5cb653d71fbb71e2fe1c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nodes_iterator llvm::GraphTraits&lt; RegionInfo * &gt;::nodes_end (<a href="/web-llvm/docs/api/classes/llvm/regioninfo">RegionInfo</a> * RI)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">RegionIterator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/df-iterator/#a2dc340448997a15e59d5c05c634bb2fe">llvm::df_iterator&lt; NodeRef, df_iterator_default_set&lt; NodeRef &gt;, false, GraphTraits&lt; FlatIt&lt; NodeRef &gt; &gt; &gt;::end</a> and <a href="#a9a710c99843f3d7a43e0752e7e9655a8">getEntryNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">GraphTraits.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">RegionIterator.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
