---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/immutablemapref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ImmutableMapRef` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;
class llvm::ImmutableMapRef&lt;KeyT, ValT, ValInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">llvm/ADT/ImmutableMap.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad26d7d77f439dba616943d9faa5f94ca">value_type</a> = typename ValInfo::value_type</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8dbc5f44eef475c415050574b9d48bb9">value_type_ref</a> = typename ValInfo::value_type_ref</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6cd5d51d23a5dd61459dd6eee1108aac">key_type</a> = typename ValInfo::key_type</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab700d7c2a24bd88743221e945e33ab59">key_type_ref</a> = typename ValInfo::key_type_ref</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a1fc3e133fafbf5af6cfe86e7fb4ed4">data_type</a> = typename ValInfo::data_type</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c27d6c9d1598c137d04bb5ea50052ed">data_type_ref</a> = typename ValInfo::data_type_ref</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a87521f853a87c008e65281ba104031e1">TreeTy</a> = <a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ValInfo &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af9f3d0458f3786682f2c809bc9b1185c">FactoryTy</a> = typename <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a744e5bd7d0965b1bb1cbc5daa85263d7">TreeTy::Factory</a></td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#adbd9d54b50810670bce88e7ad01f694b">ImmutableMapRef</a> (const TreeTy *R, FactoryTy *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a map from a pointer to a tree root. <a href="#adbd9d54b50810670bce88e7ad01f694b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af81dcaf2a8d84be022628629e0ede1b9">ImmutableMapRef</a> (const ImmutableMap&lt; KeyT, ValT &gt; &amp;X, typename ImmutableMap&lt; KeyT, ValT &gt;::Factory &amp;F)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab1985cad722cd3008061d3186dd29969">operator==</a> (const ImmutableMapRef &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a45392ccef6b9e98cbd348d42c7c43060">operator!=</a> (const ImmutableMapRef &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2086bf987f4b8d3387c65dae92eb0bd2">manualRetain</a> ()</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad92c7e5595755eda0c60b2f372cca7d3">manualRelease</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablemapref">ImmutableMapRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac3381521722a768b37a422138587f388">add</a> (key_type_ref K, data_type_ref D) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablemapref">ImmutableMapRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6769df2e96b3e3479aea6f66676163c">remove</a> (key_type_ref K) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4fd061836ead5dd901cd28d096f1a977">contains</a> (key_type_ref K) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a229acbefa27f8a7ebeac2607ac1cad2c">asImmutableMap</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a>&lt; KeyT, ValT &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27ceb5c2a83a7e95ab69f27d5004d09a">isEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a702c776c87011daa888c3d85da0dfbce">verify</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablemapref/iterator">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5d9eba31392593b708c19b418fbda4c">begin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablemapref/iterator">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5c81eec4d1af59e549d2381a852d809">end</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a5a1fc3e133fafbf5af6cfe86e7fb4ed4">data_type</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9ff3df67455679c3cf6b80aeac40ebd">lookup</a> (key_type_ref K) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad26d7d77f439dba616943d9faa5f94ca">value_type</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe1df5c17290255abbaf6b45d585caa1">getMaxElement</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMaxElement - Returns the &lt;key,value&gt; pair in the <a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a> for which key is the highest in the ordering of keys in the map. <a href="#abe1df5c17290255abbaf6b45d585caa1">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a20e29b8cba4325eced46ff90208541b2">getHeight</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ecfaa89ed010052a30391d1c0739849">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="#a87521f853a87c008e65281ba104031e1">TreeTy</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7d8641de6eaa28da6b9eb92221aa2fab">Root</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#af9f3d0458f3786682f2c809bc9b1185c">FactoryTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2c72eb0312a780c941fb9d9db7f917ce">Factory</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/immutablemapref">ImmutableMapRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a316389c852acec08fe37fa371c99ca5c">getEmptyMap</a> (FactoryTy *F)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a503e12c6874c9a2f3f62e884fb377931">Profile</a> (FoldingSetNodeID &amp;ID, const ImmutableMapRef &amp;M)</td>
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


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### data\_type {#a5a1fc3e133fafbf5af6cfe86e7fb4ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::data_type =  typename ValInfo::data_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### data\_type\_ref {#a5c27d6c9d1598c137d04bb5ea50052ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::data_type_ref =  typename ValInfo::data_type_ref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### FactoryTy {#af9f3d0458f3786682f2c809bc9b1185c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::FactoryTy =  typename TreeTy::Factory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### key\_type {#a6cd5d51d23a5dd61459dd6eee1108aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::key_type =  typename ValInfo::key_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### key\_type\_ref {#ab700d7c2a24bd88743221e945e33ab59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::key_type_ref =  typename ValInfo::key_type_ref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### TreeTy {#a87521f853a87c008e65281ba104031e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::TreeTy =  ImutAVLTree&lt;ValInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### value\_type {#ad26d7d77f439dba616943d9faa5f94ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::value_type =  typename ValInfo::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### value\_type\_ref {#a8dbc5f44eef475c415050574b9d48bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::value_type_ref =  typename ValInfo::value_type_ref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ImmutableMapRef() {#adbd9d54b50810670bce88e7ad01f694b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a87521f853a87c008e65281ba104031e1">TreeTy</a> * R, <a href="#af9f3d0458f3786682f2c809bc9b1185c">FactoryTy</a> * F)</td>
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

<p>Constructs a map from a pointer to a tree root.</p>


<p>In general one should use a Factory object to create maps instead of directly invoking the constructor, but there are cases where make this constructor public is useful.</p>


<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2c72eb0312a780c941fb9d9db7f917ce">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Factory</a> and <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>


<p>Referenced by <a href="#ac3381521722a768b37a422138587f388">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::add</a>, <a href="#a316389c852acec08fe37fa371c99ca5c">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::getEmptyMap</a>, <a href="#a45392ccef6b9e98cbd348d42c7c43060">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::operator!=</a>, <a href="#ab1985cad722cd3008061d3186dd29969">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::operator==</a>, <a href="#a503e12c6874c9a2f3f62e884fb377931">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Profile</a> and <a href="#ab6769df2e96b3e3479aea6f66676163c">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::remove</a>.</p>

</div>
</div>

### ImmutableMapRef() {#af81dcaf2a8d84be022628629e0ede1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a>&lt; KeyT, ValT &gt; &amp; X, typename <a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a>&lt; KeyT, ValT &gt;<a href="#a2c72eb0312a780c941fb9d9db7f917ce">::Factory</a> &amp; F)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2c72eb0312a780c941fb9d9db7f917ce">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Factory</a>, <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a45392ccef6b9e98cbd348d42c7c43060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablemapref">ImmutableMapRef</a> &amp; RHS)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="#adbd9d54b50810670bce88e7ad01f694b">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### operator==() {#ab1985cad722cd3008061d3186dd29969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablemapref">ImmutableMapRef</a> &amp; RHS)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="#adbd9d54b50810670bce88e7ad01f694b">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ac3381521722a768b37a422138587f388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableMapRef llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::add (<a href="#ab700d7c2a24bd88743221e945e33ab59">key_type_ref</a> K, <a href="#a5c27d6c9d1598c137d04bb5ea50052ed">data_type_ref</a> D)</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a2c72eb0312a780c941fb9d9db7f917ce">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Factory</a>, <a href="#adbd9d54b50810670bce88e7ad01f694b">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a> and <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### asImmutableMap() {#a229acbefa27f8a7ebeac2607ac1cad2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableMap&lt; KeyT, ValT &gt; llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::asImmutableMap ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="#a2c72eb0312a780c941fb9d9db7f917ce">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Factory</a> and <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### begin() {#ad5d9eba31392593b708c19b418fbda4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::begin ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### contains() {#a4fd061836ead5dd901cd28d096f1a977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::contains (<a href="#ab700d7c2a24bd88743221e945e33ab59">key_type_ref</a> K)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### end() {#af5c81eec4d1af59e549d2381a852d809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::end ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>

</div>
</div>

### getHeight() {#a20e29b8cba4325eced46ff90208541b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::getHeight ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### getMaxElement() {#abe1df5c17290255abbaf6b45d585caa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type * llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::getMaxElement ()</td>
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

<p>getMaxElement - Returns the &lt;key,value&gt; pair in the <a href="/web-llvm/docs/api/classes/llvm/immutablemap">ImmutableMap</a> for which key is the highest in the ordering of keys in the map.</p>


<p>This method returns NULL if the map is empty.</p>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### isEmpty() {#a27ceb5c2a83a7e95ab69f27d5004d09a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::isEmpty ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### lookup() {#ae9ff3df67455679c3cf6b80aeac40ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">data_type * llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::lookup (<a href="#ab700d7c2a24bd88743221e945e33ab59">key_type_ref</a> K)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### manualRelease() {#ad92c7e5595755eda0c60b2f372cca7d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::manualRelease ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### manualRetain() {#a2086bf987f4b8d3387c65dae92eb0bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::manualRetain ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### Profile() {#a3ecfaa89ed010052a30391d1c0739849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a3ecfaa89ed010052a30391d1c0739849">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Profile</a>.</p>


<p>Referenced by <a href="#a3ecfaa89ed010052a30391d1c0739849">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Profile</a>.</p>

</div>
</div>

### remove() {#ab6769df2e96b3e3479aea6f66676163c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableMapRef llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::remove (<a href="#ab700d7c2a24bd88743221e945e33ab59">key_type_ref</a> K)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="#a2c72eb0312a780c941fb9d9db7f917ce">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Factory</a>, <a href="#adbd9d54b50810670bce88e7ad01f694b">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a> and <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

### verify() {#a702c776c87011daa888c3d85da0dfbce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::verify ()</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#a7d8641de6eaa28da6b9eb92221aa2fab">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Factory {#a2c72eb0312a780c941fb9d9db7f917ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FactoryTy* llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Factory</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Referenced by <a href="#ac3381521722a768b37a422138587f388">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::add</a>, <a href="#a229acbefa27f8a7ebeac2607ac1cad2c">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::asImmutableMap</a>, <a href="#af81dcaf2a8d84be022628629e0ede1b9">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a>, <a href="#adbd9d54b50810670bce88e7ad01f694b">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a> and <a href="#ab6769df2e96b3e3479aea6f66676163c">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::remove</a>.</p>

</div>
</div>

### Root {#a7d8641de6eaa28da6b9eb92221aa2fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt;TreeTy&gt; llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Root</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Referenced by <a href="#ac3381521722a768b37a422138587f388">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::add</a>, <a href="#a229acbefa27f8a7ebeac2607ac1cad2c">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::asImmutableMap</a>, <a href="#ad5d9eba31392593b708c19b418fbda4c">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::begin</a>, <a href="#a4fd061836ead5dd901cd28d096f1a977">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::contains</a>, <a href="#a20e29b8cba4325eced46ff90208541b2">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::getHeight</a>, <a href="#abe1df5c17290255abbaf6b45d585caa1">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::getMaxElement</a>, <a href="#af81dcaf2a8d84be022628629e0ede1b9">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a>, <a href="#adbd9d54b50810670bce88e7ad01f694b">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a>, <a href="#a27ceb5c2a83a7e95ab69f27d5004d09a">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::isEmpty</a>, <a href="#ae9ff3df67455679c3cf6b80aeac40ebd">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::lookup</a>, <a href="#ad92c7e5595755eda0c60b2f372cca7d3">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::manualRelease</a>, <a href="#a2086bf987f4b8d3387c65dae92eb0bd2">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::manualRetain</a>, <a href="#a45392ccef6b9e98cbd348d42c7c43060">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::operator!=</a>, <a href="#ab1985cad722cd3008061d3186dd29969">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::operator==</a>, <a href="#ab6769df2e96b3e3479aea6f66676163c">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::remove</a> and <a href="#a702c776c87011daa888c3d85da0dfbce">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEmptyMap() {#a316389c852acec08fe37fa371c99ca5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableMapRef llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::getEmptyMap (<a href="#af9f3d0458f3786682f2c809bc9b1185c">FactoryTy</a> * F)</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#adbd9d54b50810670bce88e7ad01f694b">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a>.</p>

</div>
</div>

### Profile() {#a503e12c6874c9a2f3f62e884fb377931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValT, typename ValInfo = ImutKeyValueInfo&lt;KeyT,ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablemapref">ImmutableMapRef</a> &amp; M)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a>.</p>


<p>Reference <a href="#adbd9d54b50810670bce88e7ad01f694b">llvm::ImmutableMapRef&lt; KeyT, ValT, ValInfo &gt;::ImmutableMapRef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutablemap-h">ImmutableMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
