---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/embeddedmodelrunneroptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `EmbeddedModelRunnerOptions` Struct Reference

<p><a href="/web-llvm/docs/api/classes/llvm/releasemodemodelrunner">ReleaseModeModelRunner</a> - production mode implementation of the <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::EmbeddedModelRunnerOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">llvm/Analysis/ReleaseModeModelRunner.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/embeddedmodelrunneroptions">EmbeddedModelRunnerOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c36a2b9367c802d94c57dce83515c4">setFeedPrefix</a> (StringRef Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/embeddedmodelrunneroptions">EmbeddedModelRunnerOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8390e5f901927efac57ac24e7d6161">setFetchPrefix</a> (StringRef Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/embeddedmodelrunneroptions">EmbeddedModelRunnerOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d44ed620b4d618a88eb72973575fe6">setModelSelector</a> (StringRef Value)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84969b22a5fffcd7d81cddb7bd907a12">FeedPrefix</a> = "feed_"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Feed and Fetch feature prefixes - i.e. <a href="#a84969b22a5fffcd7d81cddb7bd907a12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c43319c72ba7f5d69cb97c7c2ede15f">FetchPrefix</a> = "fetch_"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa8151e97db247a06b56baea149fa49">ModelSelector</a> = ""</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ModelSelector is the name (recognized by the AOT-ed model) of a sub-model to use. <a href="#adaa8151e97db247a06b56baea149fa49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/releasemodemodelrunner">ReleaseModeModelRunner</a> - production mode implementation of the <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a>.</p>


<p>It uses an AOT-compiled SavedModel for efficient execution.</p>


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### setFeedPrefix() {#a61c36a2b9367c802d94c57dce83515c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmbeddedModelRunnerOptions &amp; llvm::EmbeddedModelRunnerOptions::setFeedPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a>.</p>


<p>Reference <a href="#a84969b22a5fffcd7d81cddb7bd907a12">FeedPrefix</a>.</p>

</div>
</div>

### setFetchPrefix() {#afa8390e5f901927efac57ac24e7d6161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmbeddedModelRunnerOptions &amp; llvm::EmbeddedModelRunnerOptions::setFetchPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a>.</p>


<p>Reference <a href="#a3c43319c72ba7f5d69cb97c7c2ede15f">FetchPrefix</a>.</p>

</div>
</div>

### setModelSelector() {#ab7d44ed620b4d618a88eb72973575fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmbeddedModelRunnerOptions &amp; llvm::EmbeddedModelRunnerOptions::setModelSelector (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a>.</p>


<p>Reference <a href="#adaa8151e97db247a06b56baea149fa49">ModelSelector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FeedPrefix {#a84969b22a5fffcd7d81cddb7bd907a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::EmbeddedModelRunnerOptions::FeedPrefix = "feed_"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Feed and Fetch feature prefixes - i.e.</p>


<p>a feature named "foo" will be looked up as {FeedPrefix}_foo; and the output named "bar" will be looked up as {FetchPrefix}_bar</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a>.</p>


<p>Referenced by <a href="#a61c36a2b9367c802d94c57dce83515c4">setFeedPrefix</a>.</p>

</div>
</div>

### FetchPrefix {#a3c43319c72ba7f5d69cb97c7c2ede15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::EmbeddedModelRunnerOptions::FetchPrefix = "fetch_"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a>.</p>


<p>Referenced by <a href="#afa8390e5f901927efac57ac24e7d6161">setFetchPrefix</a>.</p>

</div>
</div>

### ModelSelector {#adaa8151e97db247a06b56baea149fa49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::EmbeddedModelRunnerOptions::ModelSelector = ""</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ModelSelector is the name (recognized by the AOT-ed model) of a sub-model to use.</p>


<p>"" is allowed if the model doesn't support sub-models.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a>.</p>


<p>Referenced by <a href="#ab7d44ed620b4d618a88eb72973575fe6">setModelSelector</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
