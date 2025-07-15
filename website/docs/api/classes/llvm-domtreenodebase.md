---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/domtreenodebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DomTreeNodeBase` Class Template Reference

<p>Base class for the actual dominator tree node. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class NodeT&gt;
class llvm::DomTreeNodeBase&lt;NodeT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">llvm/Support/GenericDomTree.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30e4ef842374955e9578b856783d261c">iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> *, 4 &gt;::iterator</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7d6c8d6097d77418565f21650836d66">const_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> *, 4 &gt;::const_iterator</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5d340affbaaa6825217118ea7a3e102">PostDominatorTree</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af852c191e3bb0f814b1436ace8d7485e">DominatorTreeBase&lt; NodeT, false &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe325af67f425805d8c750f3f76bcac1">DominatorTreeBase&lt; NodeT, true &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2fe262f96cca28d38b3b56dc70a9d36b">DomTreeBuilder::SemiNCAInfo&lt; DominatorTreeBase&lt; NodeT, false &gt; &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3af550ddea4eb04ecba06310b6da930e">DomTreeBuilder::SemiNCAInfo&lt; DominatorTreeBase&lt; NodeT, true &gt; &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a99bf9b3f9dbdbabeca21228dc6982d32">DomTreeNodeBase</a> (NodeT *BB, DomTreeNodeBase *iDom)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a30e4ef842374955e9578b856783d261c">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a40b8345d54ada5dab71ae11d71e89d2f">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a30e4ef842374955e9578b856783d261c">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a74111c67a831eb30b020ecf063bce406">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ac7d6c8d6097d77418565f21650836d66">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af9ed9aec3b93dd2585eb2820b78cce99">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ac7d6c8d6097d77418565f21650836d66">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1400ca3a08a4c6cc82b44dd127e03e90">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a37fdfa8b20c91ff3c8b0857190cbb225">back</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> *&amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27d85d2c8afad3268b3e0c20020f2218">back</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06c288c533e6c4fc7def0945622b26f3">children</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a30e4ef842374955e9578b856783d261c">iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac386d111af4ec81f87fab72dfdf10f53">children</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ac7d6c8d6097d77418565f21650836d66">const_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab2bf365c9f4b976adc7479576dfd5bb">getBlock</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a453de62c2dadf7b4b8df04e89f6ab4e0">getIDom</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab73bfd7dc4d5a446db965380e340810e">getLevel</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff995374cc8949a99238707eb25b7b47">addChild</a> (DomTreeNodeBase *C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25b833c85afc5c3de7c2c4e38ac6b146">isLeaf</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8428cb59df3760e4d7fdd202aaf3587b">getNumChildren</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3278a7611e78c401984c87508fc2c326">clearAllChildren</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9d0c80d71ba83d90c53591bfbbdadf44">compare</a> (const DomTreeNodeBase *Other) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d97875c33b38014d365da0193d8aa21">setIDom</a> (DomTreeNodeBase *NewIDom)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a718717ee958956ec34ed177ef0b7f2ba">getDFSNumIn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDFSNumIn/getDFSNumOut - These return the DFS visitation order for nodes in the dominator tree. <a href="#a718717ee958956ec34ed177ef0b7f2ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad7f56029a023764c65cef48f0398c9ba">getDFSNumOut</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac9efc22d6b4056fa1e016b905839068a">DominatedBy</a> (const DomTreeNodeBase *other) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a117eef4dfe2f2565936e55e657c9ab75">UpdateLevel</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19de28503afde07052f4fc6a93e41eb9">TheBB</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ece4e59676042fbfa207b02d59f64f9">IDom</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d8bcdd93543309f7024757f68977f8b">Level</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78f496ed8d05e3b15a1fc60621bb0457">Children</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39e215f22d1d5282839b5006631fbbf3">DFSNumIn</a> = ~0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba16c98011b725cc30c044798ea0bafd">DFSNumOut</a> = ~0</td>
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

<p>Base class for the actual dominator tree node.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ac7d6c8d6097d77418565f21650836d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeNodeBase&lt; NodeT &gt;::const_iterator = 
      typename SmallVector&lt;DomTreeNodeBase *, 4&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### iterator {#a30e4ef842374955e9578b856783d261c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeNodeBase&lt; NodeT &gt;::iterator =  typename SmallVector&lt;DomTreeNodeBase *, 4&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DominatorTreeBase&lt; NodeT, false &gt; {#af852c191e3bb0f814b1436ace8d7485e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; NodeT, false &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DominatorTreeBase&lt; NodeT, true &gt; {#afe325af67f425805d8c750f3f76bcac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; NodeT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DomTreeBuilder::SemiNCAInfo&lt; DominatorTreeBase&lt; NodeT, false &gt; &gt; {#a2fe262f96cca28d38b3b56dc70a9d36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo">DomTreeBuilder::SemiNCAInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; NodeT, false &gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DomTreeBuilder::SemiNCAInfo&lt; DominatorTreeBase&lt; NodeT, true &gt; &gt; {#a3af550ddea4eb04ecba06310b6da930e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo">DomTreeBuilder::SemiNCAInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; NodeT, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### PostDominatorTree {#ab5d340affbaaa6825217118ea7a3e102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DomTreeNodeBase() {#a99bf9b3f9dbdbabeca21228dc6982d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DomTreeNodeBase&lt; NodeT &gt;::DomTreeNodeBase (NodeT * BB, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> * iDom)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addChild() {#aff995374cc8949a99238707eb25b7b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeNodeBase&lt; NodeT &gt;::addChild (<a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> * C)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a467b0f331a98739b4f1c527a468120bf">llvm::DominatorTreeBase&lt; BlockT, false &gt;::createNode</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a92c7eca8e89b08968901a33851cbfb45">llvm::DominatorTreeBase&lt; BlockT, false &gt;::setNewRoot</a>.</p>

</div>
</div>

### back() {#a37fdfa8b20c91ff3c8b0857190cbb225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase *const  &amp; llvm::DomTreeNodeBase&lt; NodeT &gt;::back ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a27d85d2c8afad3268b3e0c20020f2218">llvm::DomTreeNodeBase&lt; BlockT &gt;::back</a> and <a href="#a37fdfa8b20c91ff3c8b0857190cbb225">llvm::DomTreeNodeBase&lt; BlockT &gt;::back</a>.</p>

</div>
</div>

### back() {#a27d85d2c8afad3268b3e0c20020f2218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase *&amp; llvm::DomTreeNodeBase&lt; NodeT &gt;::back ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### begin() {#a40b8345d54ada5dab71ae11d71e89d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DomTreeNodeBase&lt; NodeT &gt;::begin ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a06c288c533e6c4fc7def0945622b26f3">llvm::DomTreeNodeBase&lt; BlockT &gt;::children</a>, <a href="#ac386d111af4ec81f87fab72dfdf10f53">llvm::DomTreeNodeBase&lt; BlockT &gt;::children</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycse/#a72f98ddc07e318d4fac9e221534c4d73">anonymous{EarlyCSE.cpp}::EarlyCSE::run</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a83fe54fc062eda7c1086493dd4155f8a">llvm::DominatorTreeBase&lt; BlockT, false &gt;::updateDFSNumbers</a>.</p>

</div>
</div>

### begin() {#af9ed9aec3b93dd2585eb2820b78cce99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DomTreeNodeBase&lt; NodeT &gt;::begin ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### children() {#a06c288c533e6c4fc7def0945622b26f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::DomTreeNodeBase&lt; NodeT &gt;::children ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a544a0723e20148ceb9a3bb3210f45270">llvm::collectChildrenInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a48a060decf79d58559a8e9e28df764f0">findBestInsertionSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#afd194fd0bfdd8b288bb7f1e9585a1679">getDominatees</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>.</p>

</div>
</div>

### children() {#ac386d111af4ec81f87fab72dfdf10f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; llvm::DomTreeNodeBase&lt; NodeT &gt;::children ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### clearAllChildren() {#a3278a7611e78c401984c87508fc2c326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeNodeBase&lt; NodeT &gt;::clearAllChildren ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### compare() {#a9d0c80d71ba83d90c53591bfbbdadf44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeNodeBase&lt; NodeT &gt;::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> * Other)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### end() {#a74111c67a831eb30b020ecf063bce406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DomTreeNodeBase&lt; NodeT &gt;::end ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a06c288c533e6c4fc7def0945622b26f3">llvm::DomTreeNodeBase&lt; BlockT &gt;::children</a>, <a href="#ac386d111af4ec81f87fab72dfdf10f53">llvm::DomTreeNodeBase&lt; BlockT &gt;::children</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a> and <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycse/#a72f98ddc07e318d4fac9e221534c4d73">anonymous{EarlyCSE.cpp}::EarlyCSE::run</a>.</p>

</div>
</div>

### end() {#a1400ca3a08a4c6cc82b44dd127e03e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DomTreeNodeBase&lt; NodeT &gt;::end ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### getBlock() {#aab2bf365c9f4b976adc7479576dfd5bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT * llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#acf1f2289b1f5ffbdf55e3f5ac555fed8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::attachNewSubtree</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a714e5448566006046f747d9ec4df8241">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a866163a9dbd27133c221fc2569333ddb">anonymous{CodeMoverUtils.cpp}::ControlConditions::collectControlConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a46b279956ad150f9e6ff57d03e1fe539">computeBlocksDominatingExits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#aa2cbc07e426705bbdb98c0f6ae7e3f72">containsUnconditionalCallSafepoint</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae046f3782a1242c97fe9fe937793fa3f">anonymous{DeadStoreElimination.cpp}::DSEState::dominatingConditionImpliesValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a48a060decf79d58559a8e9e28df764f0">findBestInsertionSet</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/loopfinder/#ac7e76dcb7cf9c36d512e2c8b2056f55e">anonymous{SILowerI1Copies.cpp}::LoopFinder::findLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a26cf1d2b810e0413369fda9759618123">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a8824d1bacc5dcc91688d442dce6822e0">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasProperSupport</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aecea88f231914d2a6dc7ecf19a57f583">preheader</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a6ab30bb387a6e7086235e9ff7ad01941">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a6196ab5eb2faa09361ac7e663765ac88">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsBeforeInsertion</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4714e88fbf38f2aaf7fd427dfb17a3a0">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyLevels</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>.</p>

</div>
</div>

### getDFSNumIn() {#a718717ee958956ec34ed177ef0b7f2ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeNodeBase&lt; NodeT &gt;::getDFSNumIn ()</td>
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

<p>getDFSNumIn/getDFSNumOut - These return the DFS visitation order for nodes in the dominator tree.</p>


<p>They are only guaranteed valid if updateDFSNumbers() has been called.</p>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a714e5448566006046f747d9ec4df8241">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/structs/llvm/valuedfs-compare/#a58a6da5fa5e7c0c7a745f3fd51e620cc">llvm::ValueDFS_Compare::comparePHIRelated</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aba197972422fd98e9318e22f0419e0a8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyDFSNumbers</a>.</p>

</div>
</div>

### getDFSNumOut() {#ad7f56029a023764c65cef48f0398c9ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeNodeBase&lt; NodeT &gt;::getDFSNumOut ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### getIDom() {#a453de62c2dadf7b4b8df04e89f6ab4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase * llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a866163a9dbd27133c221fc2569333ddb">anonymous{CodeMoverUtils.cpp}::ControlConditions::collectControlConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a46b279956ad150f9e6ff57d03e1fe539">computeBlocksDominatingExits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#aa2cbc07e426705bbdb98c0f6ae7e3f72">containsUnconditionalCallSafepoint</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a48a060decf79d58559a8e9e28df764f0">findBestInsertionSet</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/loopfinder/#ac7e76dcb7cf9c36d512e2c8b2056f55e">anonymous{SILowerI1Copies.cpp}::LoopFinder::findLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a90fd91f67bf9f4e198964e4e93aaf168">isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aecea88f231914d2a6dc7ecf19a57f583">preheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a04bc1c8d9cc3496359247eb5f4fa71c4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateInsertion</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a6196ab5eb2faa09361ac7e663765ac88">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsBeforeInsertion</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4714e88fbf38f2aaf7fd427dfb17a3a0">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyLevels</a>.</p>

</div>
</div>

### getLevel() {#ab73bfd7dc4d5a446db965380e340810e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeNodeBase&lt; NodeT &gt;::getLevel ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a714e5448566006046f747d9ec4df8241">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a82b22baa3199208282b8771c811301bf">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteReachable</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a26cf1d2b810e0413369fda9759618123">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidatecompare/#aea9f11701fcbd34a98f7da033c725845">anonymous{LoopFuse.cpp}::FusionCandidateCompare::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a04bc1c8d9cc3496359247eb5f4fa71c4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateInsertion</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4714e88fbf38f2aaf7fd427dfb17a3a0">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyLevels</a>.</p>

</div>
</div>

### getNumChildren() {#a8428cb59df3760e4d7fdd202aaf3587b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::DomTreeNodeBase&lt; NodeT &gt;::getNumChildren ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a9d0c80d71ba83d90c53591bfbbdadf44">llvm::DomTreeNodeBase&lt; BlockT &gt;::compare</a>.</p>

</div>
</div>

### isLeaf() {#a25b833c85afc5c3de7c2c4e38ac6b146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeNodeBase&lt; NodeT &gt;::isLeaf ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>.</p>

</div>
</div>

### setIDom() {#a2d97875c33b38014d365da0193d8aa21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeNodeBase&lt; NodeT &gt;::setIDom (<a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> * NewIDom)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a6ab30bb387a6e7086235e9ff7ad01941">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a04bc1c8d9cc3496359247eb5f4fa71c4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateInsertion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### DominatedBy() {#ac9efc22d6b4056fa1e016b905839068a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeNodeBase&lt; NodeT &gt;::DominatedBy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a> * other)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### UpdateLevel() {#a117eef4dfe2f2565936e55e657c9ab75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeNodeBase&lt; NodeT &gt;::UpdateLevel ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Children {#a78f496ed8d05e3b15a1fc60621bb0457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DomTreeNodeBase *, 4&gt; llvm::DomTreeNodeBase&lt; NodeT &gt;::Children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DFSNumIn {#a39e215f22d1d5282839b5006631fbbf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeNodeBase&lt; NodeT &gt;::DFSNumIn = ~0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DFSNumOut {#aba16c98011b725cc30c044798ea0bafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeNodeBase&lt; NodeT &gt;::DFSNumOut = ~0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### IDom {#a0ece4e59676042fbfa207b02d59f64f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase* llvm::DomTreeNodeBase&lt; NodeT &gt;::IDom</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### Level {#a1d8bcdd93543309f7024757f68977f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DomTreeNodeBase&lt; NodeT &gt;::Level</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### TheBB {#a19de28503afde07052f4fc6a93e41eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT* llvm::DomTreeNodeBase&lt; NodeT &gt;::TheBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
