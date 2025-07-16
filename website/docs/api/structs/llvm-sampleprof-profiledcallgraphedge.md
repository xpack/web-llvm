---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sampleprof/profiledcallgraphedge
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ProfiledCallGraphEdge` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::sampleprof::ProfiledCallGraphEdge { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">llvm/Transforms/IPO/ProfiledCallGraph.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3bce256b7fc8bcec5313720be8a1fb">ProfiledCallGraphEdge</a> (ProfiledCallGraphNode *Source, ProfiledCallGraphNode *Target, uint64_t Weight)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a71e9cbc21873264089de8181b5bf2">operator ProfiledCallGraphNode *</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode">ProfiledCallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb419031c00964beca4bc216d551a92">Source</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode">ProfiledCallGraphNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc59329671e9c73c6e874e528d99cb8">Target</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2bbcdc7eb00fee33abbccc81546aa19">Weight</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ProfiledCallGraphEdge() {#a7c3bce256b7fc8bcec5313720be8a1fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::ProfiledCallGraphEdge::ProfiledCallGraphEdge (<a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode">ProfiledCallGraphNode</a> * Source, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/profiledcallgraphnode">ProfiledCallGraphNode</a> * Target, uint64_t Weight)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>References <a href="#aceb419031c00964beca4bc216d551a92">Source</a>, <a href="#a2fc59329671e9c73c6e874e528d99cb8">Target</a> and <a href="#af2bbcdc7eb00fee33abbccc81546aa19">Weight</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator ProfiledCallGraphNode \*() {#a85a71e9cbc21873264089de8181b5bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::ProfiledCallGraphEdge::operator ProfiledCallGraphNode * ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Reference <a href="#a2fc59329671e9c73c6e874e528d99cb8">Target</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Source {#aceb419031c00964beca4bc216d551a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfiledCallGraphNode* llvm::sampleprof::ProfiledCallGraphEdge::Source</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Referenced by <a href="#a7c3bce256b7fc8bcec5313720be8a1fb">ProfiledCallGraphEdge</a>.</p>

</div>
</div>

### Target {#a2fc59329671e9c73c6e874e528d99cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfiledCallGraphNode* llvm::sampleprof::ProfiledCallGraphEdge::Target</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Referenced by <a href="#a85a71e9cbc21873264089de8181b5bf2">operator ProfiledCallGraphNode *</a> and <a href="#a7c3bce256b7fc8bcec5313720be8a1fb">ProfiledCallGraphEdge</a>.</p>

</div>
</div>

### Weight {#af2bbcdc7eb00fee33abbccc81546aa19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::ProfiledCallGraphEdge::Weight</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a>.</p>


<p>Referenced by <a href="#a7c3bce256b7fc8bcec5313720be8a1fb">ProfiledCallGraphEdge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">ProfiledCallGraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
