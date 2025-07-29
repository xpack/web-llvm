---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/intervalmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IntervalMap` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;
class llvm::IntervalMap&lt;KeyT, ValT, N, Traits&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6b645fcc5ae44b9a8e2fef275890ae4b">Allocator</a> = typename <a href="/web-llvm/docs/api/structs/llvm/intervalmapimpl/nodesizer/#a8cd3b17214907efcbfe21077a4d57f05">Sizer::Allocator</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76ba65860e508d04c8f5cfa727359e72">KeyType</a> = KeyT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89e72edced18cc76aae0ce4bd5bc9bf4">ValueType</a> = ValT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8791e5bdb2be4f0516a955879f6b15a4">KeyTraits</a> = Traits</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee3827eaa00bb424b5678c6e5c856d38">Sizer</a> = <a href="/web-llvm/docs/api/structs/llvm/intervalmapimpl/nodesizer">IntervalMapImpl::NodeSizer</a>&lt; KeyT, ValT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#accc20417c4c3bfeb1d3fafc91b8ceaa8">Leaf</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode">IntervalMapImpl::LeafNode</a>&lt; KeyT, ValT, Sizer::LeafSize, Traits &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d8bb9530e362497e7329394ad6ed507">Branch</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/branchnode">IntervalMapImpl::BranchNode</a>&lt; KeyT, ValT, <a href="/web-llvm/docs/api/structs/llvm/intervalmapimpl/nodesizer/#a20e25986129ca221c7471ea0d5e9a34ba79ed6f627e6df1b1833064f6ead08c97">Sizer::BranchSize</a>, Traits &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac26b79d8bd36cb9a20265483d3d7d118">RootLeaf</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode">IntervalMapImpl::LeafNode</a>&lt; KeyT, ValT, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, Traits &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21e61627a797bc463cf16356cd33db5e">IdxPair</a> = <a href="/web-llvm/docs/api/namespaces/llvm/intervalmapimpl/#ab92974e292699af764f4bd02d1f44448">IntervalMapImpl::IdxPair</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae64c08bf08fed2cff6a0afc433e39540">RootBranch</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/branchnode">IntervalMapImpl::BranchNode</a>&lt; KeyT, ValT, RootBranchCap, Traits &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"> { <a href="#af5087a2855e6bd8c9c9f002819383127">...</a> }</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac220ce1c155db1ac44146c12d178056f">const_iterator</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a67171474c4da6cc8efe0c7fafefd2b2d">iterator</a></td>
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

## Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab3a25c5fc8d6adf9e35acf595ccef3ff">IntervalMap</a> (IntervalMap const &amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7a36c8abe1f37a3a3466182223823a37">IntervalMap</a> (IntervalMap &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aef5470188803d9a8cdda0ad4f98e1699">IntervalMap</a> (Allocator &amp;a)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a6ab94f5053820bc64fbe8cb04c09b1d0">~IntervalMap</a> ()</td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a649d8dfaa8be526aa5a7dace01d6df69">operator=</a> (IntervalMap const &amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c239d5fc5f9d04aa3c4a174a7d05539">operator=</a> (IntervalMap &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac631b4af10a30255067fc77ab6c193d8">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>empty - Return true when no intervals are mapped. <a href="#ac631b4af10a30255067fc77ab6c193d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">KeyT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad94606da831de9baa7df66b6c92953ea">start</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>start - Return the smallest mapped key in a non-empty map. <a href="#ad94606da831de9baa7df66b6c92953ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">KeyT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a43fd35cfdcd02e29805382e2d5dfedd3">stop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>stop - Return the largest mapped key in a non-empty map. <a href="#a43fd35cfdcd02e29805382e2d5dfedd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ValT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f416a0fa27beff86ce0f442161e3a3a">lookup</a> (KeyT x, ValT NotFound=ValT()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lookup - Return the mapped value at x or NotFound. <a href="#a3f416a0fa27beff86ce0f442161e3a3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a377d82c7830c58e7034baf6a9cf38ba3">insert</a> (KeyT a, KeyT b, ValT y)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insert - Add a mapping of [a;b] to y, coalesce with adjacent intervals. <a href="#a377d82c7830c58e7034baf6a9cf38ba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aecbd7712a5e471d6821af772a8e55f85">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Remove all entries. <a href="#aecbd7712a5e471d6821af772a8e55f85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30a86f92a3d8d04852d53bfd89ce89c2">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a281133d02e9939c431a4f005ccc9cbeb">begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd1abf2a3bff454bb98fb7598f251a5a">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f207a7ea5e716ddd6e894086b593941">end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a29f1f6b44eb828055aad218617a0f1">find</a> (KeyT x) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find - Return an iterator pointing to the first interval ending at or after x, or <a href="#a9f207a7ea5e716ddd6e894086b593941">end()</a>. <a href="#a8a29f1f6b44eb828055aad218617a0f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff3d62f75e0ac5cade591e295c5b03d7">find</a> (KeyT x)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4b4075554919795e770660d7f13bb21">overlaps</a> (KeyT a, KeyT b) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>overlaps(a, b) - Return true if the intervals in this map overlap with the interval [a;b]. <a href="#ab4b4075554919795e770660d7f13bb21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode">RootLeaf</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c0517d41b775461ff789c9881e2127c">rootLeaf</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode">RootLeaf</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3eb94393c687a66492c5f6b3800ede6">rootLeaf</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RootBranchData &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae46f67639edc008e0a5754fb138091b0">rootBranchData</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RootBranchData &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83be4b4699bc07455d0efb6d03b10b91">rootBranchData</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/branchnode">RootBranch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a68dd1c572e9731c936a536c4ad62ad22">rootBranch</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/branchnode">RootBranch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a468e353d039ac13b5dff0fa105a6a573">rootBranch</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">KeyT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0c2f7971c7c14f899e8a66af15877654">rootBranchStart</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">KeyT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab14bd53e2271492eda735639ae041ea6">rootBranchStart</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a77ad89527436de575d4dd0193fe851ad">newNode</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adc281ed5094b5db6cf675722e869c41f">deleteNode</a> (NodeT *P)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">IdxPair</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a659801aaddfabc4675cf7c5866b427ea">branchRoot</a> (unsigned Position)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">IdxPair</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a36993cd3e0ca495f4e9dcb2a453ced7b">splitRoot</a> (unsigned Position)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a238a548778cce60c0b24675d45d14dc9">switchRootToBranch</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88b2a79f0757cd8f9cf06e99f64a07fd">switchRootToLeaf</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd651ecfc247b976c8fb9d09f31b4690">branched</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ValT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf9db326b2f9f739872353e8e47bafcd">treeSafeLookup</a> (KeyT x, ValT NotFound) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>treeSafeLookup - Return the mapped value at x or NotFound, assuming a branched root. <a href="#abf9db326b2f9f739872353e8e47bafcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ff29cc36977d99acba56f29da60b20f">visitNodes</a> (void(IntervalMap::*f)(IntervalMapImpl::NodeRef, unsigned Level))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>visitNodes - Visit each external node. <a href="#a0ff29cc36977d99acba56f29da60b20f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a18d5bb648596a840dc8d34216315503f">deleteNode</a> (IntervalMapImpl::NodeRef Node, unsigned Level)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode">RootLeaf</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2ca2ac99610417e4b68debafe2185d2">leaf</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RootBranchData</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa6d4a2adbadd03649e53bdb466936a96">branchData</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/intervalmap">llvm::IntervalMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5190b954f44ed5323e39594a76ec9cd"></a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad81b3ad305b8f6e272db26bb869b34de">height</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a049f90b5b9457b90a17a42900e3ed7c6">rootSize</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a6b645fcc5ae44b9a8e2fef275890ae4b">Allocator</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25637e2b7517cad7cd2e62bce8546b8e">allocator</a> = nullptr</td>
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


<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Allocator {#a6b645fcc5ae44b9a8e2fef275890ae4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::Allocator =  typename Sizer::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 962 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### KeyTraits {#a8791e5bdb2be4f0516a955879f6b15a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::KeyTraits =  Traits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### KeyType {#a76ba65860e508d04c8f5cfa727359e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::KeyType =  KeyT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### ValueType {#a89e72edced18cc76aae0ce4bd5bc9bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::ValueType =  ValT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### Branch {#a3d8bb9530e362497e7329394ad6ed507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::Branch = 
      IntervalMapImpl::BranchNode&lt;KeyT, ValT, Sizer::BranchSize, Traits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### IdxPair {#a21e61627a797bc463cf16356cd33db5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::IdxPair =  IntervalMapImpl::IdxPair</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 942 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### Leaf {#accc20417c4c3bfeb1d3fafc91b8ceaa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::Leaf =  IntervalMapImpl::LeafNode&lt;KeyT, ValT, Sizer::LeafSize, Traits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 938 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### RootBranch {#ae64c08bf08fed2cff6a0afc433e39540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::RootBranch = 
      IntervalMapImpl::BranchNode&lt;KeyT, ValT, RootBranchCap, Traits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### RootLeaf {#ac26b79d8bd36cb9a20265483d3d7d118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::RootLeaf =  IntervalMapImpl::LeafNode&lt;KeyT, ValT, N, Traits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### Sizer {#aee3827eaa00bb424b5678c6e5c856d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::Sizer =  IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#af5087a2855e6bd8c9c9f002819383127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DesiredRootBranchCap<a id="af5087a2855e6bd8c9c9f002819383127a519cc21cbde66983ae991e0815ef9e6e"></a></td>
<td class="doxyEnumItemDescription">
 (= (sizeof(RootLeaf) - sizeof(KeyT)) /
      (sizeof(KeyT) + sizeof(IntervalMapImpl::NodeRef)))
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RootBranchCap<a id="af5087a2855e6bd8c9c9f002819383127adec84d8fd95b9bba7482de8554b61d93"></a></td>
<td class="doxyEnumItemDescription"> (= DesiredRootBranchCap ? DesiredRootBranchCap : 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### const\_iterator {#ac220ce1c155db1ac44146c12d178056f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### iterator {#a67171474c4da6cc8efe0c7fafefd2b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### IntervalMap() {#ab3a25c5fc8d6adf9e35acf595ccef3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::IntervalMap (<a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; RHS)</td>
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




<p>NOTE: The moved-from or copied-from object's allocator needs to have a lifetime equal to or exceeding the moved-to or copied-to object to avoid undefined behaviour.</p>


<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### IntervalMap() {#a7a36c8abe1f37a3a3466182223823a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::IntervalMap (<a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 1063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IntervalMap() {#aef5470188803d9a8cdda0ad4f98e1699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::IntervalMap (<a href="#a6b645fcc5ae44b9a8e2fef275890ae4b">Allocator</a> &amp; a)</td>
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



<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~IntervalMap() {#a6ab94f5053820bc64fbe8cb04c09b1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::~IntervalMap ()</td>
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



<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operators

### operator=() {#a649d8dfaa8be526aa5a7dace01d6df69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalMap &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; RHS)</td>
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



<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### operator=() {#a6c239d5fc5f9d04aa3c4a174a7d05539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalMap &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a30a86f92a3d8d04852d53bfd89ce89c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::begin ()</td>
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



<p>Definition at line 1146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a315447cd8d049de76d99af3f9cda45a2">tryToShortenBegin</a>.</p>

</div>
</div>

### begin() {#a281133d02e9939c431a4f005ccc9cbeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::begin ()</td>
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



<p>Definition at line 1152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### clear() {#aecbd7712a5e471d6821af772a8e55f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clear - Remove all entries.</p>

<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### empty() {#ac631b4af10a30255067fc77ab6c193d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::empty ()</td>
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

<p>empty - Return true when no intervals are mapped.</p>

<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#afceb7703f48842eea9acf024ce0bd865">anonymous{DeadStoreElimination.cpp}::DSEState::removePartiallyOverlappedStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a315447cd8d049de76d99af3f9cda45a2">tryToShortenBegin</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aac40904307eb0bd89cfc9d73039ba8e0">tryToShortenEnd</a>.</p>

</div>
</div>

### end() {#acd1abf2a3bff454bb98fb7598f251a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::end ()</td>
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



<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aac40904307eb0bd89cfc9d73039ba8e0">tryToShortenEnd</a>.</p>

</div>
</div>

### end() {#a9f207a7ea5e716ddd6e894086b593941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::end ()</td>
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



<p>Definition at line 1164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### find() {#a8a29f1f6b44eb828055aad218617a0f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::find (KeyT x)</td>
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

<p>find - Return an iterator pointing to the first interval ending at or after x, or <a href="#a9f207a7ea5e716ddd6e894086b593941">end()</a>.</p>

<p>Definition at line 1172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### find() {#aff3d62f75e0ac5cade591e295c5b03d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::find (KeyT x)</td>
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



<p>Definition at line 1178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### insert() {#a377d82c7830c58e7034baf6a9cf38ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::insert (KeyT a, KeyT b, ValT y)</td>
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

<p>insert - Add a mapping of [a;b] to y, coalesce with adjacent intervals.</p>


<p>It is assumed that no key in the interval is mapped to another value, but overlapping intervals already mapped to y will be coalesced.</p>


<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### lookup() {#a3f416a0fa27beff86ce0f442161e3a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValT llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::lookup (KeyT x, ValT NotFound=ValT())</td>
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

<p>lookup - Return the mapped value at x or NotFound.</p>

<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### overlaps() {#ab4b4075554919795e770660d7f13bb21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::overlaps (KeyT a, KeyT b)</td>
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

<p>overlaps(a, b) - Return true if the intervals in this map overlap with the interval [a;b].</p>

<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### start() {#ad94606da831de9baa7df66b6c92953ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyT llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::start ()</td>
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

<p>start - Return the smallest mapped key in a non-empty map.</p>

<p>Definition at line 1106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#a26702c94eead6ac6eac6da14b653d824">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStart</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#ae84496bee4aead957e3193cfbe5ce3e8">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStop</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#a6c05bf6b202a8fe6d84f071b3b10ef9d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setValue</a>.</p>

</div>
</div>

### stop() {#a43fd35cfdcd02e29805382e2d5dfedd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyT llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::stop ()</td>
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

<p>stop - Return the largest mapped key in a non-empty map.</p>

<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#a26702c94eead6ac6eac6da14b653d824">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStart</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#ae84496bee4aead957e3193cfbe5ce3e8">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setStop</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#a6c05bf6b202a8fe6d84f071b3b10ef9d">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::setValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### branched() {#acd651ecfc247b976c8fb9d09f31b4690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::branched ()</td>
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



<p>Definition at line 1033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### branchRoot() {#a659801aaddfabc4675cf7c5866b427ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalMapImpl::IdxPair llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::branchRoot (unsigned Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### deleteNode() {#adc281ed5094b5db6cf675722e869c41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::deleteNode (NodeT * P)</td>
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



<p>Definition at line 1013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### deleteNode() {#a18d5bb648596a840dc8d34216315503f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::deleteNode (<a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">IntervalMapImpl::NodeRef</a> Node, unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### newNode() {#a77ad89527436de575d4dd0193fe851ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT * llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::newNode ()</td>
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



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootBranch() {#a68dd1c572e9731c936a536c4ad62ad22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RootBranch &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootBranch ()</td>
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



<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootBranch() {#a468e353d039ac13b5dff0fa105a6a573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootBranch &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootBranch ()</td>
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



<p>Definition at line 1005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootBranchData() {#ae46f67639edc008e0a5754fb138091b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RootBranchData &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootBranchData ()</td>
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



<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootBranchData() {#a83be4b4699bc07455d0efb6d03b10b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootBranchData &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootBranchData ()</td>
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



<p>Definition at line 999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootBranchStart() {#a0c2f7971c7c14f899e8a66af15877654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyT llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootBranchStart ()</td>
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



<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootBranchStart() {#ab14bd53e2271492eda735639ae041ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyT &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootBranchStart ()</td>
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



<p>Definition at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootLeaf() {#a9c0517d41b775461ff789c9881e2127c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RootLeaf &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootLeaf ()</td>
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



<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootLeaf() {#aa3eb94393c687a66492c5f6b3800ede6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootLeaf &amp; llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootLeaf ()</td>
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



<p>Definition at line 990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### splitRoot() {#a36993cd3e0ca495f4e9dcb2a453ced7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntervalMapImpl::IdxPair llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::splitRoot (unsigned Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### switchRootToBranch() {#a238a548778cce60c0b24675d45d14dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::switchRootToBranch ()</td>
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



<p>Definition at line 1021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### switchRootToLeaf() {#a88b2a79f0757cd8f9cf06e99f64a07fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::switchRootToLeaf ()</td>
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



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### treeSafeLookup() {#abf9db326b2f9f739872353e8e47bafcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValT llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::treeSafeLookup (KeyT x, ValT NotFound)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>treeSafeLookup - Return the mapped value at x or NotFound, assuming a branched root.</p>

<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### visitNodes() {#a0ff29cc36977d99acba56f29da60b20f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::visitNodes (void(IntervalMap::*)(<a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">IntervalMapImpl::NodeRef</a>, unsigned Level) f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>visitNodes - Visit each external node.</p>

<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### branchData {#aa6d4a2adbadd03649e53bdb466936a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootBranchData llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::branchData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### leaf {#ad2ca2ac99610417e4b68debafe2185d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RootLeaf llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::leaf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intervalmap/const-iterator/#a3b8e82aa59078f5275fc515e1a6ed7c4">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::const_iterator::operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#aa5190b954f44ed5323e39594a76ec9cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::IntervalMap llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 972 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### allocator {#a25637e2b7517cad7cd2e62bce8546b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Allocator* llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::allocator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### height {#ad81b3ad305b8f6e272db26bb869b34de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::height = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### rootSize {#a049f90b5b9457b90a17a42900e3ed7c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, unsigned N = IntervalMapImpl::NodeSizer&lt;KeyT, ValT&gt;::LeafSize, typename Traits = IntervalMapInfo&lt;KeyT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::rootSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
