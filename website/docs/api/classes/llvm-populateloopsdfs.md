---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/populateloopsdfs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PopulateLoopsDFS` Class Template

<p>Populate all loop data in a stable order during a single forward DFS. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class BlockT, class LoopT&gt;
class llvm::PopulateLoopsDFS&lt;BlockT, LoopT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">llvm/Support/GenericLoopInfoImpl.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; BlockT * &gt; <a href="#a1e31cba7ca2d09e8226b854e3f7964a1">BlockTraits</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">BlockTraits::ChildIteratorType <a href="#a1c1fa10e8bc7ff7edc2ac22630619615">SuccIterTy</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3950ceb42ead22a4228f0e55230dd3bc">PopulateLoopsDFS</a> (LoopInfoBase&lt; BlockT, LoopT &gt; *li)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e730539eeda2ae79f9f308fa42597ce">traverse</a> (BlockT *EntryBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Top-level driver for the forward DFS within the loop. <a href="#a2e730539eeda2ae79f9f308fa42597ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac3d14bf8a797b33e7100f3dd8b905acf">insertIntoLoop</a> (BlockT *Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a single Block to its ancestor loops in PostOrder. <a href="#ac3d14bf8a797b33e7100f3dd8b905acf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockT, class LoopT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfobase">LoopInfoBase</a>&lt; BlockT, LoopT &gt; *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae1d190c601abd07a859438aa6a442dd1">LI</a></td>
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

<p>Populate all loop data in a stable order during a single forward DFS.</p>

<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BlockTraits {#a1e31cba7ca2d09e8226b854e3f7964a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef GraphTraits&lt;BlockT *&gt; llvm::PopulateLoopsDFS&lt; BlockT, LoopT &gt;::BlockTraits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>

</div>
</div>

### SuccIterTy {#a1c1fa10e8bc7ff7edc2ac22630619615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef BlockTraits::ChildIteratorType llvm::PopulateLoopsDFS&lt; BlockT, LoopT &gt;::SuccIterTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PopulateLoopsDFS() {#a3950ceb42ead22a4228f0e55230dd3bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PopulateLoopsDFS&lt; BlockT, LoopT &gt;::PopulateLoopsDFS (<a href="/web-llvm/docs/api/classes/llvm/loopinfobase">LoopInfoBase</a>&lt; BlockT, LoopT &gt; * li)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### traverse() {#a2e730539eeda2ae79f9f308fa42597ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PopulateLoopsDFS&lt; BlockT, LoopT &gt;::traverse (BlockT * EntryBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Top-level driver for the forward DFS within the loop.</p>

<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>References <a href="#ac3d14bf8a797b33e7100f3dd8b905acf">llvm::PopulateLoopsDFS&lt; BlockT, LoopT &gt;::insertIntoLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a41c4916e8090ce40598db1a8dd2a5d5d">llvm::post_order</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### insertIntoLoop() {#ac3d14bf8a797b33e7100f3dd8b905acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PopulateLoopsDFS&lt; BlockT, LoopT &gt;::insertIntoLoop (BlockT * Block)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a single Block to its ancestor loops in PostOrder.</p>


<p>If the block is a subloop header, add the subloop to its parent in PostOrder, then reverse the Block and Subloop vectors of the now complete subloop to achieve RPO.</p>


<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>.</p>


<p>Referenced by <a href="#a2e730539eeda2ae79f9f308fa42597ce">llvm::PopulateLoopsDFS&lt; BlockT, LoopT &gt;::traverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LI {#ae1d190c601abd07a859438aa6a442dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockT, class LoopT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfoBase&lt;BlockT, LoopT&gt;* llvm::PopulateLoopsDFS&lt; BlockT, LoopT &gt;::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericloopinfoimpl-h">GenericLoopInfoImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
