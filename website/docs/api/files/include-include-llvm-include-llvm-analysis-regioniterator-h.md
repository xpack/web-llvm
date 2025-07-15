---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/analysis/regioniterator-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RegionIterator.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/depthfirstiterator-h">llvm/ADT/DepthFirstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">llvm/ADT/GraphTraits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">llvm/ADT/PointerIntPair.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioninfo-h">llvm/Analysis/RegionInfo.h</a>"
#include &lt;cassert&gt;
#include &lt;iterator&gt;
#include &lt;type_traits&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rnsucciterator">RNSuccIterator&lt;NodeRef, BlockT, RegionT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hierarchical <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> successor iterator. <a href="/web-llvm/docs/api/classes/llvm/rnsucciterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">llvm::RNSuccIterator< FlatIt< NodeRef >, BlockT, RegionT ></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-e5b50eb34ec0db639bdb467f977dace6">GraphTraits&lt;RegionInfo *&gt;</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8886c086c58c5276ae31447cbb783fd1">RegionNodeGraphTraits</a>(NodeT, BlockT, RegionT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40c06b591f65fb51abca8e4a8e7bdd5">RegionGraphTraits</a>(RegionT, NodeT)&nbsp;&nbsp;&nbsp;...</td>
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


<div class="doxySectionDef">

## Macro Definitions

### RegionGraphTraits {#ad40c06b591f65fb51abca8e4a8e7bdd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RegionGraphTraits(RegionT, NodeT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  template &lt;&gt; struct GraphTraits&lt;RegionT *&gt; : public GraphTraits&lt;NodeT *&gt; {    \
    using nodes_iterator = df_iterator&lt;NodeRef&gt;;                               \
    static NodeRef getEntryNode(RegionT *R) {                                  \
      return R-&gt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>(R-&gt;getEntry());                                        \
    }                                                                          \
    static nodes_iterator nodes_begin(RegionT *R) {                            \
      return nodes_iterator::begin(getEntryNode(R));                           \
    }                                                                          \
    static nodes_iterator nodes_end(RegionT *R) {                              \
      return nodes_iterator::end(getEntryNode(R));                             \
    }                                                                          \
  };                                                                           \
  template &lt;&gt;                                                                  \
  struct GraphTraits&lt;FlatIt&lt;RegionT *&gt;&gt;                                        \
      : public GraphTraits&lt;FlatIt&lt;NodeT *&gt;&gt; {                                  \
    using nodes_iterator =                                                     \
        df_iterator&lt;NodeRef, df_iterator_default_set&lt;NodeRef&gt;, false,          \
                    GraphTraits&lt;FlatIt&lt;NodeRef&gt;&gt;&gt;;                             \
    static NodeRef getEntryNode(RegionT *R) {                                  \
      return R-&gt;getBBNode(R-&gt;getEntry());                                      \
    }                                                                          \
    static nodes_iterator nodes_begin(RegionT *R) {                            \
      return nodes_iterator::begin(getEntryNode(R));                           \
    }                                                                          \
    static nodes_iterator nodes_end(RegionT *R) {                              \
      return nodes_iterator::end(getEntryNode(R));                             \
    }                                                                          \
  }
</div>
</dd>
</dl>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">RegionIterator.h</a>.</p>

</div>
</div>

### RegionNodeGraphTraits {#a8886c086c58c5276ae31447cbb783fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RegionNodeGraphTraits(NodeT, BlockT, RegionT)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  template &lt;&gt; struct GraphTraits&lt;NodeT *&gt; {                                    \
    using NodeRef = NodeT *;                                                   \
    using ChildIteratorType = RNSuccIterator&lt;NodeRef, BlockT, RegionT&gt;;        \
    static NodeRef getEntryNode(NodeRef <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) { return <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>; }                       \
    static <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> ChildIteratorType child_begin(NodeRef <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) {                   \
      return RNSuccIterator&lt;NodeRef, BlockT, RegionT&gt;(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>);                      \
    }                                                                          \
    static <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> ChildIteratorType child_end(NodeRef <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) {                     \
      return RNSuccIterator&lt;NodeRef, BlockT, RegionT&gt;(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>);                \
    }                                                                          \
  };                                                                           \
  template &lt;&gt; struct GraphTraits&lt;FlatIt&lt;NodeT *&gt;&gt; {                            \
    using NodeRef = NodeT *;                                                   \
    using ChildIteratorType =                                                  \
        RNSuccIterator&lt;FlatIt&lt;NodeRef&gt;, BlockT, RegionT&gt;;                      \
    static NodeRef getEntryNode(NodeRef <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) { return <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>; }                       \
    static <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> ChildIteratorType child_begin(NodeRef <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) {                   \
      return RNSuccIterator&lt;FlatIt&lt;NodeRef&gt;, BlockT, RegionT&gt;(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>);              \
    }                                                                          \
    static <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> ChildIteratorType child_end(NodeRef <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) {                     \
      return RNSuccIterator&lt;FlatIt&lt;NodeRef&gt;, BlockT, RegionT&gt;(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>);        \
    }                                                                          \
  }
</div>
</dd>
</dl>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/regioniterator-h">RegionIterator.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
