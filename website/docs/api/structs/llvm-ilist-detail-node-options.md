---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ilist-detail/node-options
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `node_options` Struct Template Reference

<p>Traits for options for <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a></em>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;
struct llvm::ilist_detail::node_options&lt;T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">llvm/ADT/ilist_node_options.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">T <a href="#ac93434f528b0cb13adfa57caeb138133">value_type</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">T * <a href="#a0bf068b99d1f66f90dfadbbd255592c9">pointer</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">T &amp; <a href="#a76491ff8a345f408a7a84a1ca4e7a4ef">reference</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * <a href="#aab058f1f577896ad6ac31632f73a4cb1">const_pointer</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; <a href="#a389c2d2730be7106a17b29b4df549ae0">const_reference</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">TagT <a href="#afa0e6f12cc530207829aa8a197cfc5f9">tag</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">ParentTy <a href="#a3c55c6eb29f05dbe708afbd2b04e33d4">parent_ty</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-base">ilist_node_base</a>&lt; <a href="#a377b0b33bbccf3aaccf2c21f02dc176f">enable_sentinel_tracking</a>, <a href="#a3c55c6eb29f05dbe708afbd2b04e33d4">parent_ty</a> &gt; <a href="#accd83c313ba5a94d6c6299894a180352">node_base_type</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-base">ilist_base</a>&lt; <a href="#a377b0b33bbccf3aaccf2c21f02dc176f">enable_sentinel_tracking</a>, <a href="#a3c55c6eb29f05dbe708afbd2b04e33d4">parent_ty</a> &gt; <a href="#aa9dd62a7c6dd6bf0929b93c39f3edee9">list_base_type</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a377b0b33bbccf3aaccf2c21f02dc176f">enable_sentinel_tracking</a> = EnableSentinelTracking</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a770091e45cdb4fb9c3adb1771bb1e8d2">is_sentinel_tracking_explicit</a> = IsSentinelTrackingExplicit</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab1d3a4a3fe5fcb51cb91d7477c54a213">has_iterator_bits</a> = HasIteratorBits</td>
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

<p>Traits for options for <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a></em>.</p>


<p>This is usually computed via <em><a href="/web-llvm/docs/api/structs/llvm/ilist-detail/compute-node-options">compute_node_options</a></em>.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_pointer {#aab058f1f577896ad6ac31632f73a4cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef const T* llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::const_pointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### const\_reference {#a389c2d2730be7106a17b29b4df549ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef const T&amp; llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::const_reference</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### list\_base\_type {#aa9dd62a7c6dd6bf0929b93c39f3edee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef ilist_base&lt;enable_sentinel_tracking, parent_ty&gt; llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::list_base_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### node\_base\_type {#accd83c313ba5a94d6c6299894a180352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef ilist_node_base&lt;enable_sentinel_tracking, parent_ty&gt; llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::node_base_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### parent\_ty {#a3c55c6eb29f05dbe708afbd2b04e33d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef ParentTy llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::parent_ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### pointer {#a0bf068b99d1f66f90dfadbbd255592c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef T* llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::pointer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### reference {#a76491ff8a345f408a7a84a1ca4e7a4ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef T&amp; llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::reference</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### tag {#afa0e6f12cc530207829aa8a197cfc5f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef TagT llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### value\_type {#ac93434f528b0cb13adfa57caeb138133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef T llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### enable\_sentinel\_tracking {#a377b0b33bbccf3aaccf2c21f02dc176f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::enable_sentinel_tracking = EnableSentinelTracking</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### has\_iterator\_bits {#ab1d3a4a3fe5fcb51cb91d7477c54a213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::has_iterator_bits = HasIteratorBits</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

### is\_sentinel\_tracking\_explicit {#a770091e45cdb4fb9c3adb1771bb1e8d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, bool EnableSentinelTracking, bool IsSentinelTrackingExplicit, class TagT, bool HasIteratorBits, class ParentTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::ilist_detail::node_options&lt; T, EnableSentinelTracking, IsSentinelTrackingExplicit, TagT, HasIteratorBits, ParentTy &gt;::is_sentinel_tracking_explicit = IsSentinelTrackingExplicit</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
