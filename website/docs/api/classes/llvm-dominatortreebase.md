---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dominatortreebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DominatorTreeBase` Class Template Reference

<p>Core dominator tree base class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename NodeT, bool IsPostDom&gt;
class llvm::DominatorTreeBase&lt;NodeT, IsPostDom&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">llvm/Support/GenericDomTree.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0276dcf6b5d94cdbe50c75fcdb0f8572">NodeTrait</a> = <a href="/web-llvm/docs/api/structs/llvm/domtreenodetraits">DomTreeNodeTraits</a>&lt; NodeT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1325ecc7c627b09e43f3f70d8c503395">NodeType</a> = typename <a href="/web-llvm/docs/api/structs/llvm/domtreenodetraits/#a3f4a8f1e3f372682f0bc52c828c28160">NodeTrait::NodeType</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abfff3c536c3e12c08405099b6884d6ef">NodePtr</a> = typename <a href="/web-llvm/docs/api/structs/llvm/domtreenodetraits/#ab6438844cf5e526b96bcfb705557326a">NodeTrait::NodePtr</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea97731925889efe03498cfdd69258b0">ParentPtr</a> = typename <a href="/web-llvm/docs/api/structs/llvm/domtreenodetraits/#ac36af8e8bb30f50952a2f054f2c355c9">NodeTrait::ParentPtr</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2bbcf466d609c6b1ccb4f2d48e92b48e">ParentType</a> = std::remove_pointer_t&lt; <a href="#aea97731925889efe03498cfdd69258b0">ParentPtr</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca76acb70a839a2462d3e9ae346e1eb0">UpdateType</a> = <a href="/web-llvm/docs/api/classes/llvm/cfg/update">cfg::Update</a>&lt; <a href="#abfff3c536c3e12c08405099b6884d6ef">NodePtr</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acbbca54fbe7104f9be97f3fad13be173">UpdateKind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/cfg/#a90f12723ad8d5cff45b6f06408a33da8">cfg::UpdateKind</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a179f78b7f204648cbed25005bf984687">root_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; NodeT * &gt;::iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iteration over roots. <a href="#a179f78b7f204648cbed25005bf984687">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85cb77e9572c7cf8147220b4f9ac6f9d">const_root_iterator</a> = typename <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; NodeT * &gt;::const_iterator</td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af915098d3120072b74f06cc22cf7e20a">DomTreeNodeStorageTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">VerificationLevel { <a href="#aad6e57a3b7c184bded15b616e790781f">...</a> }</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0233ae8f5264fce022a9b6db29350a66">DomTreeBuilder::SemiNCAInfo&lt; DominatorTreeBase &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a26d4dcbaebe4ce21eecfe0713248822a">DominatorTreeBase</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2fa12962052f52a5bd0e8c50afd6712b">DominatorTreeBase</a> (DominatorTreeBase &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a98dd047bc4e01652f2e9c74f893d6563">DominatorTreeBase</a> (const DominatorTreeBase &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a719d3b81624689833f6eb941984a61a4">operator=</a> (DominatorTreeBase &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aefc518b248a48a8eff0e62df7bd19446">operator=</a> (const DominatorTreeBase &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a148a366111761f5ae022ce034add8c20">operator[]</a> (const NodeT *BB) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See getNode. <a href="#a148a366111761f5ae022ce034add8c20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a179f78b7f204648cbed25005bf984687">root_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a94f2c1f02bd51f9e18dd2ff8b965316a">root_begin</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a85cb77e9572c7cf8147220b4f9ac6f9d">const_root_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9be5bb9c485f40e242b9db41cd383b69">root_begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a179f78b7f204648cbed25005bf984687">root_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca770ba191614b6864474cfa3d33a39e">root_end</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a85cb77e9572c7cf8147220b4f9ac6f9d">const_root_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69b8fab6118662607e2d24fcd198d745">root_end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35f8ede9f06d54f789edb2507f174701">root_size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a284b0623285554f36e7e3a80a729dd37">roots</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a179f78b7f204648cbed25005bf984687">root_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a61dc5769faa9211bf2be7fc72adbaad4">roots</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a85cb77e9572c7cf8147220b4f9ac6f9d">const_root_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a34b755d82a4dd0da864d67b8704e47d5">isPostDominator</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isPostDominator - Returns true if analysis based of postdoms <a href="#a34b755d82a4dd0da864d67b8704e47d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88c67bdca817fe534231fa231df41c03">compare</a> (const DominatorTreeBase &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>compare - Return false if the other dominator tree base matches this dominator tree base. <a href="#a88c67bdca817fe534231fa231df41c03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad8295b9b507d1d847cd46856f8255eab">getNode</a> (const NodeT *BB) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNode - return the (Post)<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> node for the specified basic block. <a href="#ad8295b9b507d1d847cd46856f8255eab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1dfeebf79b630b7c859bdbfd58a09c03">getRootNode</a> () -&gt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRootNode - This returns the entry node for the CFG of the function. <a href="#a1dfeebf79b630b7c859bdbfd58a09c03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab211785945cf62cec0011964112c8ab9">getRootNode</a> () const -&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a406e4a6b7277aab7efd423ae30a9fb12">getDescendants</a> (NodeT *R, SmallVectorImpl&lt; NodeT * &gt; &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all nodes dominated by R, including R itself. <a href="#a406e4a6b7277aab7efd423ae30a9fb12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade6d93f9485649bade540a37ec163058">properlyDominates</a> (const DomTreeNodeBase&lt; NodeT &gt; *A, const DomTreeNodeBase&lt; NodeT &gt; *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>properlyDominates - Returns true iff A dominates B and A != B. <a href="#ade6d93f9485649bade540a37ec163058">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada7b65032d37287aa8fff70763d86b51">properlyDominates</a> (const NodeT *A, const NodeT *B) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac38ddc0af660f81616d869aa2efdbd90">isReachableFromEntry</a> (const NodeT *A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReachableFromEntry - Return true if A is dominated by the entry block of the function containing it. <a href="#ac38ddc0af660f81616d869aa2efdbd90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09e95d5490dfc73c59099656002a002c">isReachableFromEntry</a> (const DomTreeNodeBase&lt; NodeT &gt; *A) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d344fb542e2d57c633f0161e3a6b231">dominates</a> (const DomTreeNodeBase&lt; NodeT &gt; *A, const DomTreeNodeBase&lt; NodeT &gt; *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dominates - Returns true iff A dominates B. <a href="#a5d344fb542e2d57c633f0161e3a6b231">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d6a0c2358ffb53de76d93e49e66ee2d">dominates</a> (const NodeT *A, const NodeT *B) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a81f7fe4844c408d799428082f599c40b">getRoot</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26cf1d2b810e0413369fda9759618123">findNearestCommonDominator</a> (NodeT *A, NodeT *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find nearest common dominator basic block for basic block A and B. <a href="#a26cf1d2b810e0413369fda9759618123">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ea608417f2f4d95c2c6734f6bb1888e">findNearestCommonDominator</a> (const NodeT *A, const NodeT *B) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae01eee1948b6c351f27a31bbe17fe1b2">isVirtualRoot</a> (const DomTreeNodeBase&lt; NodeT &gt; *A) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IteratorTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30b8af63035799a0478f6b710ce23571">findNearestCommonDominator</a> (iterator_range&lt; IteratorTy &gt; Nodes) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a470b5b573c7915fe13bd529b22c9adbc">applyUpdates</a> (ArrayRef&lt; UpdateType &gt; Updates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the dominator tree about a sequence of CFG edge insertions and deletions and perform a batch update on the tree. <a href="#a470b5b573c7915fe13bd529b22c9adbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acbf2b914f43ca98a8c1ea9bd11a92de4">applyUpdates</a> (ArrayRef&lt; UpdateType &gt; Updates, ArrayRef&lt; UpdateType &gt; PostViewUpdates)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51145a3ae24ea73b3692a17088edea7b">insertEdge</a> (NodeT *From, NodeT *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the dominator tree about a CFG edge insertion and update the tree. <a href="#a51145a3ae24ea73b3692a17088edea7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab0f09aefdf088f84a0bff7cba86454b4">deleteEdge</a> (NodeT *From, NodeT *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inform the dominator tree about a CFG edge deletion and update the tree. <a href="#ab0f09aefdf088f84a0bff7cba86454b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4211a49504539a8a37aebb00e1390370">addNewBlock</a> (NodeT *BB, NodeT *DomBB) -&gt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new node to the dominator tree information. <a href="#a4211a49504539a8a37aebb00e1390370">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92c7eca8e89b08968901a33851cbfb45">setNewRoot</a> (NodeT *BB) -&gt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new node to the forward dominator tree and make it a new root. <a href="#a92c7eca8e89b08968901a33851cbfb45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2881c226e1c102190d54c3b664330aba">changeImmediateDominator</a> (DomTreeNodeBase&lt; NodeT &gt; *N, DomTreeNodeBase&lt; NodeT &gt; *NewIDom)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>changeImmediateDominator - This method is used to update the dominator tree information when a node's immediate dominator changes. <a href="#a2881c226e1c102190d54c3b664330aba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21368d423017df379d83b5de30178a4d">changeImmediateDominator</a> (NodeT *BB, NodeT *NewBB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa6ae6629458ff4ccac821618d1677af4">eraseNode</a> (NodeT *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eraseNode - Removes a node from the dominator tree. <a href="#aa6ae6629458ff4ccac821618d1677af4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a69be708bdeb1b9aad3cf2a1918aec8b3">splitBlock</a> (NodeT *NewBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>splitBlock - BB is split and now it has one successor. <a href="#a69be708bdeb1b9aad3cf2a1918aec8b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b79243577798dfbefa6f61ff08898ea">print</a> (raw_ostream &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Convert to human readable form <a href="#a0b79243577798dfbefa6f61ff08898ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83fe54fc062eda7c1086493dd4155f8a">updateDFSNumbers</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateDFSNumbers - Assign In and Out numbers to the nodes while walking dominator tree in dfs order. <a href="#a83fe54fc062eda7c1086493dd4155f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0641ae965656ff9988d67a35140e4d9">recalculate</a> (ParentType &amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>recalculate - compute a dominator tree for the given function <a href="#aa0641ae965656ff9988d67a35140e4d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7dd2a25cb133a3d75887ea740201311d">recalculate</a> (ParentType &amp;Func, ArrayRef&lt; UpdateType &gt; Updates)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T = NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5497581592027b0e7275f3ff54735343">updateBlockNumbers</a> () -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a35a70f3171a1748822370ffb5f9324bf">GraphHasNodeNumbers</a>&lt; T * &gt;, void &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update dominator tree after renumbering blocks. <a href="#a5497581592027b0e7275f3ff54735343">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f08f2925fec05b265e540d29066b9c8">verify</a> (VerificationLevel VL=VerificationLevel::Full) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>verify - checks if the tree is correct. <a href="#a1f08f2925fec05b265e540d29066b9c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ea18603ae95be026f00ed35dc9791fa">reset</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abc2804137403eb0d17a3dbcf9b96d240">addRoot</a> (NodeT *BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a467b0f331a98739b4f1c527a468120bf">createNode</a> (NodeT *BB, DomTreeNodeBase&lt; NodeT &gt; *IDom=nullptr) -&gt; <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; *</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27b94c48d58dc48bf80e98e92e6ba7a1">Split</a> (typename GraphTraits&lt; N &gt;::NodeRef NewBB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acc761b47bbcdd0872e7f68229d41d9e5">addRoot</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a567ebbc73e143f10853c2e244fe54e0a">getNodeIndex</a> (const NodeT *BB) const -&gt; std::optional&lt; unsigned &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ea79e358f4a8b48d9cfee8162c67f98">getNodeIndexForInsert</a> (const NodeT *BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a53b94e36eaa7f6f9a836db335b22b0c2">updateBlockNumberEpoch</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a5eb6aeeee7dc9032dca053a24727fe">dominatedBySlowTreeWalk</a> (const DomTreeNodeBase&lt; NodeT &gt; *A, const DomTreeNodeBase&lt; NodeT &gt; *B) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a81ae1a3062ed4d9f8ba564d505812e9e">wipe</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wipe this tree's state without releasing any resources. <a href="#a81ae1a3062ed4d9f8ba564d505812e9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; NodeT *, IsPostDom ? 4 :1 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa25698676e6e61f93062495af7e5466f">Roots</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#af915098d3120072b74f06cc22cf7e20a">DomTreeNodeStorageTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad53b6c187c39da6d38e506fce773ee18">DomTreeNodes</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::conditional_t&lt;!<a href="/web-llvm/docs/api/namespaces/llvm/#a35a70f3171a1748822370ffb5f9324bf">GraphHasNodeNumbers</a>&lt; NodeT * &gt;, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT *, unsigned &gt;, std::tuple&lt;&gt; &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab3a0b43b8bdbd1fa76ccbccd8d71a989">NodeNumberMap</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4ff16436345011a2b44ab1df03e0f33">RootNode</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aea97731925889efe03498cfdd69258b0">ParentPtr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc022c576bec78143017832c543fe8f7">Parent</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a485fecd158249f131b1608c6e60ed946">DFSInfoValid</a> = false</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47dc8a537bf82dca8ae480c865425872">SlowQueries</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace9e6675dfef4d58007f41b71470f539">BlockNumberEpoch</a> = 0</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8dc0048261d95972fb05ebf2dd636b0">IsPostDominator</a> = IsPostDom</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/cfg/#a90f12723ad8d5cff45b6f06408a33da8">UpdateKind</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9aeeca2833810f01b20545a46fe22503">Insert</a> = UpdateKind::Insert</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/cfg/#a90f12723ad8d5cff45b6f06408a33da8">UpdateKind</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a71c91cbbfc1c0ecf9a69e10ccf739bd7">Delete</a> = UpdateKind::Delete</td>
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

<p>Core dominator tree base class.</p>


<p>This class is a generic template over graph nodes. It is instantiated for various graphs in the LLVM IR or in the code generator.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_root\_iterator {#a85cb77e9572c7cf8147220b4f9ac6f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::const_root_iterator =  typename SmallVectorImpl&lt;NodeT *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### NodePtr {#abfff3c536c3e12c08405099b6884d6ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::NodePtr =  typename NodeTrait::NodePtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### NodeTrait {#a0276dcf6b5d94cdbe50c75fcdb0f8572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::NodeTrait =  DomTreeNodeTraits&lt;NodeT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### NodeType {#a1325ecc7c627b09e43f3f70d8c503395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::NodeType =  typename NodeTrait::NodeType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### ParentPtr {#aea97731925889efe03498cfdd69258b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::ParentPtr =  typename NodeTrait::ParentPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### ParentType {#a2bbcf466d609c6b1ccb4f2d48e92b48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::ParentType =  std::remove_pointer_t&lt;ParentPtr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### root\_iterator {#a179f78b7f204648cbed25005bf984687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::root_iterator =  typename SmallVectorImpl&lt;NodeT *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iteration over roots.</p>


<p>This may include multiple blocks if we are computing post dominators. For forward dominators, this will always be a single block (the entry block).</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### UpdateKind {#acbbca54fbe7104f9be97f3fad13be173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::UpdateKind =  cfg::UpdateKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### UpdateType {#aca76acb70a839a2462d3e9ae346e1eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::UpdateType =  cfg::Update&lt;NodePtr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Typedefs

### DomTreeNodeStorageTy {#af915098d3120072b74f06cc22cf7e20a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::DomTreeNodeStorageTy = 
      SmallVector&lt;std::unique_ptr&lt;DomTreeNodeBase&lt;NodeT&gt;&gt;&gt;</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### VerificationLevel {#aad6e57a3b7c184bded15b616e790781f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DominatorTreeBase::VerificationLevel </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Fast<a id="aad6e57a3b7c184bded15b616e790781fae16b5b7f26f54214445cbe38d72c2828"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Basic<a id="aad6e57a3b7c184bded15b616e790781fa972e73b7a882d0802a4e3a16946a2f94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Full<a id="aad6e57a3b7c184bded15b616e790781fabbd47109890259c0127154db1af26c75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DomTreeBuilder::SemiNCAInfo&lt; DominatorTreeBase &gt; {#a0233ae8f5264fce022a9b6db29350a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo">DomTreeBuilder::SemiNCAInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DominatorTreeBase() {#a26d4dcbaebe4ce21eecfe0713248822a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::DominatorTreeBase ()</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DominatorTreeBase() {#a2fa12962052f52a5bd0e8c50afd6712b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::DominatorTreeBase (<a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DominatorTreeBase() {#a98dd047bc4e01652f2e9c74f893d6563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::DominatorTreeBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a148a366111761f5ae022ce034add8c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase&lt; NodeT &gt; * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * BB)</td>
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

<p>See getNode.</p>

<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### operator=() {#a719d3b81624689833f6eb941984a61a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTreeBase &amp; llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### operator=() {#aefc518b248a48a8eff0e62df7bd19446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTreeBase &amp; llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addNewBlock() {#a4211a49504539a8a37aebb00e1390370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase&lt; NodeT &gt; * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::addNewBlock (NodeT * BB, NodeT * DomBB)</td>
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

<p>Add a new node to the dominator tree information.</p>


<p>This creates a new node as a child of DomBB dominator node, linking it into the children list of the immediate dominator.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>New node in CFG.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DomBB</td>
<td class="doxyParamItemDescription"><p>CFG node that is dominator for BB.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>New dominator tree node that represents new CFG node.</p></dd>
</dl>


<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="#a27b94c48d58dc48bf80e98e92e6ba7a1">llvm::DominatorTreeBase&lt; BlockT, false &gt;::Split</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### applyUpdates() {#a470b5b573c7915fe13bd529b22c9adbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::applyUpdates (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#aca76acb70a839a2462d3e9ae346e1eb0">UpdateType</a> &gt; Updates)</td>
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

<p>Inform the dominator tree about a sequence of CFG edge insertions and deletions and perform a batch update on the tree.</p>


<p>This function should be used when there were multiple CFG updates after the last dominator tree update. It takes care of performing the updates in sync with the CFG and optimizes away the redundant operations that cancel each other. The functions expects the sequence of updates to be balanced. Eg.:</p>


<ul class="doxyList ">
<li>{{Insert, A, B}, {Delete, A, B}, {Insert, A, B}} is fine, because logically it results in a single insertions.</li>
<li>{{Insert, A, B}, {Insert, A, B}} is invalid, because it doesn't make sense to insert the same edge twice.</li>
</ul>

<p>What's more, the functions assumes that it's safe to ask every node in the CFG about its children and inverse children. This implies that deletions of CFG edges must not delete the CFG nodes before calling this function.</p>


<p>The applyUpdates function can reorder the updates and remove redundant ones internally (as long as it is done in a deterministic fashion). The batch updater is also able to detect sequences of zero and exactly one update – it's optimized to do less work in these cases.</p>


<p>Note that for postdominators it automatically takes care of applying updates on reverse edges internally (so there's no need to swap the From and To pointers when constructing <a href="#aca76acb70a839a2462d3e9ae346e1eb0">DominatorTree::UpdateType</a>). The type of updates is the same for <a href="/web-llvm/docs/api/namespaces/llvm/#a763915fd0a536cc2d1ebe99595e3eeaf">DomTreeBase&lt;T&gt;</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a42a6aebb3458a7c7e43d89338c1a6816">PostDomTreeBase&lt;T&gt;</a> with the same template parameter T.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Updates</td>
<td class="doxyParamItemDescription"><p>An ordered sequence of updates to perform. The current CFG and the reverse of these updates provides the pre-view of the CFG.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ad89ca302de455d3971f751c8d1a5bd58">llvm::MemorySSAUpdater::applyUpdates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silatebranchlowering-cpp/#a93b418512ed9bd239b221724374df852">splitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### applyUpdates() {#acbf2b914f43ca98a8c1ea9bd11a92de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::applyUpdates (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#aca76acb70a839a2462d3e9ae346e1eb0">UpdateType</a> &gt; Updates, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#aca76acb70a839a2462d3e9ae346e1eb0">UpdateType</a> &gt; PostViewUpdates)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Updates</td>
<td class="doxyParamItemDescription"><p>An ordered sequence of updates to perform. The current CFG and the reverse of these updates provides the pre-view of the CFG.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PostViewUpdates</td>
<td class="doxyParamItemDescription"><p>An ordered sequence of update to perform in order to obtain a post-view of the CFG. The DT will be updated assuming the obtained PostViewCFG is the desired end state.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### changeImmediateDominator() {#a2881c226e1c102190d54c3b664330aba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::changeImmediateDominator (<a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * N, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * NewIDom)</td>
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

<p>changeImmediateDominator - This method is used to update the dominator tree information when a node's immediate dominator changes.</p>

<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a21368d423017df379d83b5de30178a4d">llvm::DominatorTreeBase&lt; BlockT, false &gt;::changeImmediateDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="#a27b94c48d58dc48bf80e98e92e6ba7a1">llvm::DominatorTreeBase&lt; BlockT, false &gt;::Split</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-earlyifconversion-cpp-/#a35766d8bc1206e4e88ebb72f397c0296">anonymous{EarlyIfConversion.cpp}::updateDomTree</a>.</p>

</div>
</div>

### changeImmediateDominator() {#a21368d423017df379d83b5de30178a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::changeImmediateDominator (NodeT * BB, NodeT * NewBB)</td>
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



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### compare() {#a88c67bdca817fe534231fa231df41c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> &amp; Other)</td>
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

<p>compare - Return false if the other dominator tree base matches this dominator tree base.</p>


<p>Otherwise return true.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### deleteEdge() {#ab0f09aefdf088f84a0bff7cba86454b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::deleteEdge (NodeT * From, NodeT * To)</td>
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

<p>Inform the dominator tree about a CFG edge deletion and update the tree.</p>


<p>This function has to be called just after making the update on the actual CFG. An internal functions checks if the edge doesn't exist in the CFG in DEBUG mode. There cannot be any other updates that the dominator tree doesn't know about.</p>


<p>Note that for postdominators it automatically takes care of deleting a reverse edge internally (so there's no need to swap the parameters).</p>


<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### dominates() {#a5d344fb542e2d57c633f0161e3a6b231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * B)</td>
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

<p>dominates - Returns true iff A dominates B.</p>


<p>Note that this is not a constant time operation!</p>


<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a280d02be3ec3eb6527c1ea944d902775">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::analyze</a>, <a href="#ade6d93f9485649bade540a37ec163058">llvm::DominatorTreeBase&lt; BlockT, false &gt;::properlyDominates</a> and <a href="#a27b94c48d58dc48bf80e98e92e6ba7a1">llvm::DominatorTreeBase&lt; BlockT, false &gt;::Split</a>.</p>

</div>
</div>

### dominates() {#a3d6a0c2358ffb53de76d93e49e66ee2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#a73ba38b119a12eb092295458fde44f52">dominates</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>.</p>

</div>
</div>

### eraseNode() {#aa6ae6629458ff4ccac821618d1677af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::eraseNode (NodeT * BB)</td>
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

<p>eraseNode - Removes a node from the dominator tree.</p>


<p>Block must not dominate any other blocks. Removes node from its immediate dominator's children list. Deletes dominator node associated with basic block BB.</p>


<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-earlyifconversion-cpp-/#a35766d8bc1206e4e88ebb72f397c0296">anonymous{EarlyIfConversion.cpp}::updateDomTree</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a26cf1d2b810e0413369fda9759618123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::findNearestCommonDominator (NodeT * A, NodeT * B)</td>
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

<p>Find nearest common dominator basic block for basic block A and B.</p>


<p>A and B must have tree nodes.</p>


<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a3ea608417f2f4d95c2c6734f6bb1888e">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="#a30b8af63035799a0478f6b710ce23571">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a> and <a href="#a27b94c48d58dc48bf80e98e92e6ba7a1">llvm::DominatorTreeBase&lt; BlockT, false &gt;::Split</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a3ea608417f2f4d95c2c6734f6bb1888e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeT * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::findNearestCommonDominator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * B)</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a30b8af63035799a0478f6b710ce23571}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IteratorTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::findNearestCommonDominator (<a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; IteratorTy &gt; Nodes)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### getDescendants() {#a406e4a6b7277aab7efd423ae30a9fb12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getDescendants (NodeT * R, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; NodeT * &gt; &amp; Result)</td>
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

<p>Get all nodes dominated by R, including R itself.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>.</p>

</div>
</div>

### getNode() {#ad8295b9b507d1d847cd46856f8255eab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase&lt; NodeT &gt; * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * BB)</td>
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

<p>getNode - return the (Post)<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> node for the specified basic block.</p>


<p>This is the same as using operator[] on this class. The result may (but is not required to) be null for a forward (backwards) statically unreachable block.</p>


<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a4211a49504539a8a37aebb00e1390370">llvm::DominatorTreeBase&lt; BlockT, false &gt;::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a280d02be3ec3eb6527c1ea944d902775">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::analyze</a>, <a href="#a21368d423017df379d83b5de30178a4d">llvm::DominatorTreeBase&lt; BlockT, false &gt;::changeImmediateDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#add6cb3c2274e68181ab8a1b4be472b90">checkAndReplaceCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a32203e7352f128904822ee859e9ae839">checkHoistValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a544a0723e20148ceb9a3bb3210f45270">llvm::collectChildrenInLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a866163a9dbd27133c221fc2569333ddb">anonymous{CodeMoverUtils.cpp}::ControlConditions::collectControlConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a46b279956ad150f9e6ff57d03e1fe539">computeBlocksDominatingExits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#aa2cbc07e426705bbdb98c0f6ae7e3f72">containsUnconditionalCallSafepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codemoverutils-cpp/#a8b9a912d352e6ed808f954f1b40a4b58">domTreeLevelBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a61e2de2c4987a7fdaf09251933714262">eliminateConstraints</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a0dca3347facf58865b34df5e5df676f0">llvm::MustBeExecutedContextExplorer::findBackwardJoinPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a48a060decf79d58559a8e9e28df764f0">findBestInsertionSet</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#ab0cac3cc09d07bc44ffd388ff8be5e49">llvm::MustBeExecutedContextExplorer::findForwardJoinPoint</a>, <a href="#a26cf1d2b810e0413369fda9759618123">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="#a30b8af63035799a0478f6b710ce23571">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="#a406e4a6b7277aab7efd423ae30a9fb12">llvm::DominatorTreeBase&lt; BlockT, false &gt;::getDescendants</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#afd194fd0bfdd8b288bb7f1e9585a1679">getDominatees</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#a93819e91559afbcefbe8c8d90f0499ed">getDominators</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a64bba3cf05c8cb1baa848483e7150830">hoistValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a90fd91f67bf9f4e198964e4e93aaf168">isGuaranteedNotToBeUndefOrPoison</a>, <a href="#ac38ddc0af660f81616d869aa2efdbd90">llvm::DominatorTreeBase&lt; BlockT, false &gt;::isReachableFromEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="#a148a366111761f5ae022ce034add8c20">llvm::DominatorTreeBase&lt; BlockT, false &gt;::operator[]</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aecea88f231914d2a6dc7ecf19a57f583">preheader</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a37a71785c3d451d302d2cb9e108f5424">llvm::GuardWideningPass::run</a>, <a href="#a92c7eca8e89b08968901a33851cbfb45">llvm::DominatorTreeBase&lt; BlockT, false &gt;::setNewRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a6d3df5d0193e146b79c3c48601641c43">shouldSplitOnPredicatedArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1236d17bc9dd1041e95f1724eb9cfa6">llvm::sinkRegionForLoopNest</a>, <a href="#a27b94c48d58dc48bf80e98e92e6ba7a1">llvm::DominatorTreeBase&lt; BlockT, false &gt;::Split</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-earlyifconversion-cpp-/#a35766d8bc1206e4e88ebb72f397c0296">anonymous{EarlyIfConversion.cpp}::updateDomTree</a>.</p>

</div>
</div>

### getRoot() {#a81f7fe4844c408d799428082f599c40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getRoot ()</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/forwarddominancefrontierbase/#a7b11dff80facdebb843d875cee482164">llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp/#af0470a389063c0b4665f29617596051a">getFreezeInsertPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#a3ddbec9e8a91a1d6a95110e5a197cde2">nearest_common_dominatee</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>.</p>

</div>
</div>

### getRootNode() {#a1dfeebf79b630b7c859bdbfd58a09c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase&lt; NodeT &gt; * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getRootNode ()</td>
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

<p>getRootNode - This returns the entry node for the CFG of the function.</p>


<p>If this tree represents the post-dominance relations for a function, however, this root may be a node with the block == NULL. This is the case when there are multiple exit nodes from a particular function. Consumers of post-dominance information must be capable of dealing with this possibility.</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a280d02be3ec3eb6527c1ea944d902775">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::analyze</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f31979df437dc9ea1e2269fa80c9ec5c/#a8b6d899a2938f54264f315182063f909">llvm::GraphTraits&lt; DominatorTree * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-e5b377eb4ded0ce3fc60fc76e3ee48b7/#acbea0fe633ef46d1c0ddbb6cd776cb8c">llvm::GraphTraits&lt; MachineDominatorTree * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-17b04332f83e992c6c30c4bb779c89c8/#a05b7b8c8e9a2c66defce610d95d3f00c">llvm::GraphTraits&lt; PostDominatorTree * &gt;::getEntryNode</a>, <a href="#a0b79243577798dfbefa6f61ff08898ea">llvm::DominatorTreeBase&lt; BlockT, false &gt;::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#ab7fe307733ec8e501f180b78fe879980">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsoptimizepiccall-cpp-/optimizepiccall/#af8fb60c334fa1c7571459b115762b09e">anonymous{MipsOptimizePICCall.cpp}::OptimizePICCall::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzldcleanup-cpp-/systemzldcleanup/#a5ca5f9f4a18fb64aa67be317c3a963d0">anonymous{SystemZLDCleanup.cpp}::SystemZLDCleanup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a0f3b4e5e968c5ab89944989495e68799">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a> and <a href="#a83fe54fc062eda7c1086493dd4155f8a">llvm::DominatorTreeBase&lt; BlockT, false &gt;::updateDFSNumbers</a>.</p>

</div>
</div>

### getRootNode() {#ab211785945cf62cec0011964112c8ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DomTreeNodeBase&lt; NodeT &gt; * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getRootNode ()</td>
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



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### insertEdge() {#a51145a3ae24ea73b3692a17088edea7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::insertEdge (NodeT * From, NodeT * To)</td>
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

<p>Inform the dominator tree about a CFG edge insertion and update the tree.</p>


<p>This function has to be called just before or just after making the update on the actual CFG. There cannot be any other updates that the dominator tree doesn't know about.</p>


<p>Note that for postdominators it automatically takes care of inserting a reverse edge internally (so there's no need to swap the parameters).</p>


<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### isPostDominator() {#a34b755d82a4dd0da864d67b8704e47d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::isPostDominator ()</td>
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

<p>isPostDominator - Returns true if analysis based of postdoms</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a26cf1d2b810e0413369fda9759618123">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>, <a href="#ac38ddc0af660f81616d869aa2efdbd90">llvm::DominatorTreeBase&lt; BlockT, false &gt;::isReachableFromEntry</a>, <a href="#ae01eee1948b6c351f27a31bbe17fe1b2">llvm::DominatorTreeBase&lt; BlockT, false &gt;::isVirtualRoot</a> and <a href="#a92c7eca8e89b08968901a33851cbfb45">llvm::DominatorTreeBase&lt; BlockT, false &gt;::setNewRoot</a>.</p>

</div>
</div>

### isReachableFromEntry() {#ac38ddc0af660f81616d869aa2efdbd90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::isReachableFromEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * A)</td>
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

<p>isReachableFromEntry - Return true if A is dominated by the entry block of the function containing it.</p>

<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a5d344fb542e2d57c633f0161e3a6b231">llvm::DominatorTreeBase&lt; BlockT, false &gt;::dominates</a>, <a href="#ac38ddc0af660f81616d869aa2efdbd90">llvm::DominatorTreeBase&lt; BlockT, false &gt;::isReachableFromEntry</a>, <a href="#a27b94c48d58dc48bf80e98e92e6ba7a1">llvm::DominatorTreeBase&lt; BlockT, false &gt;::Split</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a297fe1e46e53629f71cc8e9b4f53b8c9">llvm::LoopBase&lt; BasicBlock, Loop &gt;::verifyLoopNest</a>.</p>

</div>
</div>

### isReachableFromEntry() {#a09e95d5490dfc73c59099656002a002c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::isReachableFromEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * A)</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### isVirtualRoot() {#ae01eee1948b6c351f27a31bbe17fe1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::isVirtualRoot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * A)</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a30b8af63035799a0478f6b710ce23571">llvm::DominatorTreeBase&lt; BlockT, false &gt;::findNearestCommonDominator</a>.</p>

</div>
</div>

### print() {#a0b79243577798dfbefa6f61ff08898ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>print - Convert to human readable form</p>

<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### properlyDominates() {#ade6d93f9485649bade540a37ec163058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::properlyDominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * B)</td>
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

<p>properlyDominates - Returns true iff A dominates B and A != B.</p>


<p>Note that this is not a constant time operation!</p>


<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a831a5dec04e512d616fccb6e1f474e79">isLoadInvariantInLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>.</p>

</div>
</div>

### properlyDominates() {#ada7b65032d37287aa8fff70763d86b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::properlyDominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#a73ba38b119a12eb092295458fde44f52">dominates</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>.</p>

</div>
</div>

### recalculate() {#aa0641ae965656ff9988d67a35140e4d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::recalculate (<a href="#a2bbcf466d609c6b1ccb4f2d48e92b48e">ParentType</a> &amp; Func)</td>
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

<p>recalculate - compute a dominator tree for the given function</p>

<p>Definition at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae54a643a9f9d83374bb4d7d22d4662d7">AddAlignmentAssumptions</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a61f3d93434dc9f576826799df553ed1b">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::doMultiRegionFunctionOutlining</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#aa06ef927da6dbc2b989bb4df7d1f5c6a">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::doSingleRegionFunctionOutlining</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#a97b6c307b527c1b857c01ac9a318ff28">llvm::OptimizationRemarkEmitter::OptimizationRemarkEmitter</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreeanalysis/#a4aa821b3dea8d981f76a77e5c099e3b5">llvm::DominatorTreeAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#adcb87ee7d8b9f08bc82da9cae1c74429">llvm::PlaceSafepointsPass::runImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineverifier-cpp/#a13500e0b51ad6dd146c75e65f00d7f4b">verifyConvergenceControl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5f1d1b7df16dee92c5b56c26e322b89">llvm::verifyVPlanIsValid</a>.</p>

</div>
</div>

### recalculate() {#a7dd2a25cb133a3d75887ea740201311d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::recalculate (<a href="#a2bbcf466d609c6b1ccb4f2d48e92b48e">ParentType</a> &amp; Func, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#aca76acb70a839a2462d3e9ae346e1eb0">UpdateType</a> &gt; Updates)</td>
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



<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### reset() {#a2ea18603ae95be026f00ed35dc9791fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::reset ()</td>
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



<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### root\_begin() {#a94f2c1f02bd51f9e18dd2ff8b965316a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">root_iterator llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::root_begin ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a284b0623285554f36e7e3a80a729dd37">llvm::DominatorTreeBase&lt; BlockT, false &gt;::roots</a> and <a href="#a61dc5769faa9211bf2be7fc72adbaad4">llvm::DominatorTreeBase&lt; BlockT, false &gt;::roots</a>.</p>

</div>
</div>

### root\_begin() {#a9be5bb9c485f40e242b9db41cd383b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_root_iterator llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::root_begin ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### root\_end() {#aca770ba191614b6864474cfa3d33a39e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">root_iterator llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::root_end ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a284b0623285554f36e7e3a80a729dd37">llvm::DominatorTreeBase&lt; BlockT, false &gt;::roots</a> and <a href="#a61dc5769faa9211bf2be7fc72adbaad4">llvm::DominatorTreeBase&lt; BlockT, false &gt;::roots</a>.</p>

</div>
</div>

### root\_end() {#a69b8fab6118662607e2d24fcd198d745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_root_iterator llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::root_end ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### root\_size() {#a35f8ede9f06d54f789edb2507f174701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::root_size ()</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/forwarddominancefrontierbase/#a7b11dff80facdebb843d875cee482164">llvm::ForwardDominanceFrontierBase&lt; BlockT &gt;::analyze</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>.</p>

</div>
</div>

### roots() {#a284b0623285554f36e7e3a80a729dd37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; root_iterator &gt; llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::roots ()</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>.</p>

</div>
</div>

### roots() {#a61dc5769faa9211bf2be7fc72adbaad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_root_iterator &gt; llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::roots ()</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### setNewRoot() {#a92c7eca8e89b08968901a33851cbfb45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase&lt; NodeT &gt; * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::setNewRoot (NodeT * BB)</td>
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

<p>Add a new node to the forward dominator tree and make it a new root.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>New node in CFG.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>New dominator tree node that represents new CFG node.</p></dd>
</dl>


<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpchain/#a6bb3a89ac6216b60c21d8815fb2fa220">anonymous{MergeICmps.cpp}::BCECmpChain::simplify</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### splitBlock() {#a69be708bdeb1b9aad3cf2a1918aec8b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::splitBlock (NodeT * NewBB)</td>
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

<p>splitBlock - BB is split and now it has one successor.</p>


<p>Update dominator tree to reflect this change.</p>


<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### updateBlockNumbers() {#a5497581592027b0e7275f3ff54735343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T = NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; GraphHasNodeNumbers&lt; T * &gt;, void &gt; llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::updateBlockNumbers ()</td>
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

<p>Update dominator tree after renumbering blocks.</p>

<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp/#ab52c873c8169af2a8b1256ace3fe7a7c">sortBlocks</a>.</p>

</div>
</div>

### updateDFSNumbers() {#a83fe54fc062eda7c1086493dd4155f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::updateDFSNumbers ()</td>
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

<p>updateDFSNumbers - Assign In and Out numbers to the nodes while walking dominator tree in dfs order.</p>

<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a5d344fb542e2d57c633f0161e3a6b231">llvm::DominatorTreeBase&lt; BlockT, false &gt;::dominates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a61e2de2c4987a7fdaf09251933714262">eliminateConstraints</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adffe8dd96d1c957f04909ca9c2cd79ba">llvm::isSafeToMoveBefore</a>.</p>

</div>
</div>

### verify() {#a1f08f2925fec05b265e540d29066b9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::verify (<a href="#aad6e57a3b7c184bded15b616e790781f">VerificationLevel</a> VL=<a href="#aad6e57a3b7c184bded15b616e790781fabbd47109890259c0127154db1af26c75">VerificationLevel::Full</a>)</td>
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

<p>verify - checks if the tree is correct.</p>


<p>There are 3 level of verification:</p>


<ul class="doxyList ">
<li>Full – verifies if the tree is correct by making sure all the properties (including the parent and the sibling property) hold. Takes O(N^3) time.</li>
<li>Basic – checks if the tree is correct, but compares it to a freshly constructed tree instead of checking the sibling property. Takes O(N^2) time.</li>
<li>Fast – checks basic tree structure and compares it with a freshly constructed tree. Takes O(N^2) time worst case, but is faster in practise (same as tree construction).</li>
</ul>

<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/fixirreducible-cpp/#ad914c82e07de4044a3314a5d03c5b85a">fixIrreducible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopboundsplitpass/#a488751cbcea1a2e3da39c4e67ecfd98c">llvm::LoopBoundSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/libcallsshrinkwrap-cpp/#a9a73c0e2e52b5f57d74bf8c8321dde88">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#a3ff905acf81e5be719752bfb2437eda7">simplifyFunctionCFG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a91d961bc77edfba4fb721c6637c0c6ed">unifyLoopExits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addRoot() {#abc2804137403eb0d17a3dbcf9b96d240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::addRoot (NodeT * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a92c7eca8e89b08968901a33851cbfb45">llvm::DominatorTreeBase&lt; BlockT, false &gt;::setNewRoot</a>.</p>

</div>
</div>

### addRoot() {#acc761b47bbcdd0872e7f68229d41d9e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; MachineBasicBlock, false &gt;::addRoot (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>

</div>
</div>

### createNode() {#a467b0f331a98739b4f1c527a468120bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase&lt; NodeT &gt; * llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::createNode (NodeT * BB, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * IDom=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a4211a49504539a8a37aebb00e1390370">llvm::DominatorTreeBase&lt; BlockT, false &gt;::addNewBlock</a> and <a href="#a92c7eca8e89b08968901a33851cbfb45">llvm::DominatorTreeBase&lt; BlockT, false &gt;::setNewRoot</a>.</p>

</div>
</div>

### Split() {#a27b94c48d58dc48bf80e98e92e6ba7a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Split (typename <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt;::NodeRef NewBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="#a69be708bdeb1b9aad3cf2a1918aec8b3">llvm::DominatorTreeBase&lt; BlockT, false &gt;::splitBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### dominatedBySlowTreeWalk() {#a8a5eb6aeeee7dc9032dca053a24727fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::dominatedBySlowTreeWalk (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; NodeT &gt; * B)</td>
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



<p>Definition at line 989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### getNodeIndex() {#a567ebbc73e143f10853c2e244fe54e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNodeIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * BB)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### getNodeIndexForInsert() {#a9ea79e358f4a8b48d9cfee8162c67f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNodeIndexForInsert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeT * BB)</td>
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



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### updateBlockNumberEpoch() {#a53b94e36eaa7f6f9a836db335b22b0c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::updateBlockNumberEpoch ()</td>
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



<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### wipe() {#a81ae1a3062ed4d9f8ba564d505812e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::wipe ()</td>
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

<p>Wipe this tree's state without releasing any resources.</p>


<p>This is essentially a post-move helper only. It leaves the object in an assignable and destroyable state, but otherwise invalid.</p>


<p>Definition at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BlockNumberEpoch {#ace9e6675dfef4d58007f41b71470f539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::BlockNumberEpoch = 0</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DFSInfoValid {#a485fecd158249f131b1608c6e60ed946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::DFSInfoValid = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### DomTreeNodes {#ad53b6c187c39da6d38e506fce773ee18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeStorageTy llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::DomTreeNodes</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### NodeNumberMap {#ab3a0b43b8bdbd1fa76ccbccd8d71a989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::conditional_t&lt;!GraphHasNodeNumbers&lt;NodeT *&gt;, DenseMap&lt;const NodeT *, unsigned&gt;, std::tuple&lt;&gt; &gt; llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::NodeNumberMap</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### Parent {#afc022c576bec78143017832c543fe8f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParentPtr llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Parent = nullptr</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#aefeadea2057e320609553f6dbe57089f">llvm::DominatorTree::DominatorTree</a>.</p>

</div>
</div>

### RootNode {#ab4ff16436345011a2b44ab1df03e0f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNodeBase&lt;NodeT&gt;* llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::RootNode = nullptr</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### Roots {#aa25698676e6e61f93062495af7e5466f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;NodeT *, IsPostDom ? 4 : 1&gt; llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Roots</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### SlowQueries {#a47dc8a537bf82dca8ae480c865425872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::SlowQueries = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Delete {#a71c91cbbfc1c0ecf9a69e10ccf739bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UpdateKind llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Delete = UpdateKind::Delete</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ad89ca302de455d3971f751c8d1a5bd58">llvm::MemorySSAUpdater::applyUpdates</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### Insert {#a9aeeca2833810f01b20545a46fe22503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UpdateKind llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Insert = UpdateKind::Insert</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ad89ca302de455d3971f751c8d1a5bd58">llvm::MemorySSAUpdater::applyUpdates</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### IsPostDominator {#af8dc0048261d95972fb05ebf2dd636b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::IsPostDominator = IsPostDom</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
