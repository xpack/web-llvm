---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/intervalmapimpl/path
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Path` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::IntervalMapImpl::Path { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52e51cf4adf67639b89131b0f4244728">node</a> (unsigned Level) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf18dbdc3e5f4395cb816b7cfc28df87">size</a> (unsigned Level) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50067a0fc5557d9b4e98b7b457d09b06">offset</a> (unsigned Level) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b828a38a5db2eb63cd610307ff8830">offset</a> (unsigned Level)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">NodeT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a19245dbb7c612c9c17129a5063d3b5de">leaf</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a676bf16fc5e497ea459b6a92218ef00b">leafSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a501c71de1700afc4ea47b5bf67fbfdd9">leafOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af403c5847a00050e07024707ff3390ee">leafOffset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b2cb75a028a3053dea9d50565cdef34">valid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>valid - Return true if path is at a valid node, not at end(). <a href="#a0b2cb75a028a3053dea9d50565cdef34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c1cd93b8e8aebba51515cb531df6877">height</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>height - Return the height of the tree corresponding to this path. <a href="#a7c1cd93b8e8aebba51515cb531df6877">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6b9bc0a599f8d7071efbe343ffb5c06">subtree</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>subtree - Get the subtree referenced from Level. <a href="#af6b9bc0a599f8d7071efbe343ffb5c06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b3124c4f83510dd0e86c97580bedcdf">reset</a> (unsigned Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset - Reset cached information about node(Level) from subtree(Level -1). <a href="#a0b3124c4f83510dd0e86c97580bedcdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18dce9b09fd23b653e19a42e8d066a8">push</a> (NodeRef Node, unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>push - Add entry to path. <a href="#af18dce9b09fd23b653e19a42e8d066a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a8bbc180b0fb593af60a451bec9c8d6">pop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>pop - Remove the last path entry. <a href="#a8a8bbc180b0fb593af60a451bec9c8d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a984b07539b0e770760b2cfa8b2474fd8">setSize</a> (unsigned Level, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setSize - Set the size of a node both in the path and in the tree. <a href="#a984b07539b0e770760b2cfa8b2474fd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad7abf532bcf6e64587359c9e5321f6">setRoot</a> (void *Node, unsigned Size, unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setRoot - Clear the path and set a new root node. <a href="#a4ad7abf532bcf6e64587359c9e5321f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0045511f2217fb2722053df480ca93d4">replaceRoot</a> (void *Root, unsigned Size, IdxPair Offsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replaceRoot - Replace the current root node with two new entries after the tree height has increased. <a href="#a0045511f2217fb2722053df480ca93d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c13157576c73d4ad7c0c849a2e44115">getLeftSibling</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLeftSibling - Get the left sibling node at Level, or a null <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a>. <a href="#a1c13157576c73d4ad7c0c849a2e44115">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae878a804adbd190aad9c23df62b0f352">moveLeft</a> (unsigned Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>moveLeft - Move path to the left sibling at Level. <a href="#ae878a804adbd190aad9c23df62b0f352">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab252ce944fb2315d923f0d2f36523f0f">fillLeft</a> (unsigned Height)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>fillLeft - Grow path to Height by taking leftmost branches. <a href="#ab252ce944fb2315d923f0d2f36523f0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa06e158d1edb782965a6507afab5ae47">getRightSibling</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLeftSibling - Get the left sibling node at Level, or a null <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a>. <a href="#aa06e158d1edb782965a6507afab5ae47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8186267aca496ea543bd8d2ec77660f7">moveRight</a> (unsigned Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>moveRight - Move path to the left sibling at Level. <a href="#a8186267aca496ea543bd8d2ec77660f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2f5fce1c933649d3452413a22cbadb">atBegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>atBegin - Return true if path is at begin(). <a href="#a6b2f5fce1c933649d3452413a22cbadb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ba6ded8cd555da8c752ac6f029fb06">atLastEntry</a> (unsigned Level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>atLastEntry - Return true if the path is at the last entry of the node at Level. <a href="#a53ba6ded8cd555da8c752ac6f029fb06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9434bd7ee08975d3ed2adca806f2096">legalizeForInsert</a> (unsigned Level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>legalizeForInsert - Prepare the path for an insertion at Level. <a href="#ab9434bd7ee08975d3ed2adca806f2096">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; Entry, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80487b75be12a4872c06ddfaf1b4d2c6">path</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>path - The path entries, path[0] is the root node, path.back() is a leaf. <a href="#a80487b75be12a4872c06ddfaf1b4d2c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### atBegin() {#a6b2f5fce1c933649d3452413a22cbadb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMapImpl::Path::atBegin ()</td>
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

<p>atBegin - Return true if path is at begin().</p>

<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#a50067a0fc5557d9b4e98b7b457d09b06">offset</a>.</p>

</div>
</div>

### atLastEntry() {#a53ba6ded8cd555da8c752ac6f029fb06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMapImpl::Path::atLastEntry (unsigned Level)</td>
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

<p>atLastEntry - Return true if the path is at the last entry of the node at Level.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to examine.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#aa06e158d1edb782965a6507afab5ae47">getRightSibling</a> and <a href="#a8186267aca496ea543bd8d2ec77660f7">moveRight</a>.</p>

</div>
</div>

### fillLeft() {#ab252ce944fb2315d923f0d2f36523f0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::fillLeft (unsigned Height)</td>
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

<p>fillLeft - Grow path to Height by taking leftmost branches.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Height</td>
<td class="doxyParamItemDescription"><p>The target height.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a7c1cd93b8e8aebba51515cb531df6877">height</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a720622fc32fd2435f7726d832d851ea6">push</a> and <a href="#af6b9bc0a599f8d7071efbe343ffb5c06">subtree</a>.</p>

</div>
</div>

### getLeftSibling() {#a1c13157576c73d4ad7c0c849a2e44115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::IntervalMapImpl::Path::getLeftSibling (unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLeftSibling - Get the left sibling node at Level, or a null <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>Get the sibling to node(Level).</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Left sibling, or NodeRef().</p></dd>
</dl>


<p>Declaration at line 875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/support/intervalmap-cpp">IntervalMap.cpp</a>.</p>


<p>References <a href="#a50067a0fc5557d9b4e98b7b457d09b06">offset</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#a24a489c9ec9744fa38c9e3d295e87e55">llvm::IntervalMapImpl::NodeRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#ad56a61be137a6adfe4327233a4e492f9">llvm::IntervalMapImpl::NodeRef::subtree</a>.</p>

</div>
</div>

### getRightSibling() {#aa06e158d1edb782965a6507afab5ae47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::IntervalMapImpl::Path::getRightSibling (unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLeftSibling - Get the left sibling node at Level, or a null <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>Get the sibling to node(Level).</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Left sibling, or NodeRef().</p></dd>
</dl>


<p>Declaration at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/intervalmap-cpp">IntervalMap.cpp</a>.</p>


<p>References <a href="#a53ba6ded8cd555da8c752ac6f029fb06">atLastEntry</a>, <a href="#a50067a0fc5557d9b4e98b7b457d09b06">offset</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#ad56a61be137a6adfe4327233a4e492f9">llvm::IntervalMapImpl::NodeRef::subtree</a>.</p>

</div>
</div>

### height() {#a7c1cd93b8e8aebba51515cb531df6877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMapImpl::Path::height ()</td>
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

<p>height - Return the height of the tree corresponding to this path.</p>


<p>This matches map-&gt;height in a full path.</p>


<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#ab252ce944fb2315d923f0d2f36523f0f">fillLeft</a> and <a href="#ae878a804adbd190aad9c23df62b0f352">moveLeft</a>.</p>

</div>
</div>

### leaf() {#a19245dbb7c612c9c17129a5063d3b5de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT &amp; llvm::IntervalMapImpl::Path::leaf ()</td>
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



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="#a52e51cf4adf67639b89131b0f4244728">node</a>.</p>

</div>
</div>

### leafOffset() {#a501c71de1700afc4ea47b5bf67fbfdd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMapImpl::Path::leafOffset ()</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### leafOffset() {#af403c5847a00050e07024707ff3390ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned &amp; llvm::IntervalMapImpl::Path::leafOffset ()</td>
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



<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### leafSize() {#a676bf16fc5e497ea459b6a92218ef00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMapImpl::Path::leafSize ()</td>
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



<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### legalizeForInsert() {#ab9434bd7ee08975d3ed2adca806f2096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::legalizeForInsert (unsigned Level)</td>
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

<p>legalizeForInsert - Prepare the path for an insertion at Level.</p>


<p>When the path is at end(), node(Level) may not be a legal node. legalizeForInsert ensures that node(Level) is real by moving back to the last node at Level, and setting offset(Level) to size(Level) if required.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>The level where an insertion is about to take place.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 919 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#ae878a804adbd190aad9c23df62b0f352">moveLeft</a> and <a href="#a0b2cb75a028a3053dea9d50565cdef34">valid</a>.</p>

</div>
</div>

### moveLeft() {#ae878a804adbd190aad9c23df62b0f352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::moveLeft (unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>moveLeft - Move path to the left sibling at Level.</p>


<p>Leave nodes below Level unaltered.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>Move node(Level).</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/support/intervalmap-cpp">IntervalMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7c1cd93b8e8aebba51515cb531df6877">height</a>, <a href="#a50067a0fc5557d9b4e98b7b457d09b06">offset</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#a24a489c9ec9744fa38c9e3d295e87e55">llvm::IntervalMapImpl::NodeRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#ad56a61be137a6adfe4327233a4e492f9">llvm::IntervalMapImpl::NodeRef::subtree</a>, <a href="#af6b9bc0a599f8d7071efbe343ffb5c06">subtree</a> and <a href="#a0b2cb75a028a3053dea9d50565cdef34">valid</a>.</p>


<p>Referenced by <a href="#ab9434bd7ee08975d3ed2adca806f2096">legalizeForInsert</a>.</p>

</div>
</div>

### moveRight() {#a8186267aca496ea543bd8d2ec77660f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::moveRight (unsigned Level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>moveRight - Move path to the left sibling at Level.</p>


<p>Leave nodes below Level unaltered.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>Move node(Level).</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/support/intervalmap-cpp">IntervalMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a53ba6ded8cd555da8c752ac6f029fb06">atLastEntry</a>, <a href="#a50067a0fc5557d9b4e98b7b457d09b06">offset</a>, <a href="#abf18dbdc3e5f4395cb816b7cfc28df87">size</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#ad56a61be137a6adfe4327233a4e492f9">llvm::IntervalMapImpl::NodeRef::subtree</a> and <a href="#af6b9bc0a599f8d7071efbe343ffb5c06">subtree</a>.</p>

</div>
</div>

### node() {#a52e51cf4adf67639b89131b0f4244728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeT &amp; llvm::IntervalMapImpl::Path::node (unsigned Level)</td>
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



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a19245dbb7c612c9c17129a5063d3b5de">leaf</a>.</p>

</div>
</div>

### offset() {#a50067a0fc5557d9b4e98b7b457d09b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMapImpl::Path::offset (unsigned Level)</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a6b2f5fce1c933649d3452413a22cbadb">atBegin</a>, <a href="#a1c13157576c73d4ad7c0c849a2e44115">getLeftSibling</a>, <a href="#aa06e158d1edb782965a6507afab5ae47">getRightSibling</a>, <a href="#ae878a804adbd190aad9c23df62b0f352">moveLeft</a>, <a href="#a8186267aca496ea543bd8d2ec77660f7">moveRight</a>, <a href="#a0b3124c4f83510dd0e86c97580bedcdf">reset</a> and <a href="#af6b9bc0a599f8d7071efbe343ffb5c06">subtree</a>.</p>

</div>
</div>

### offset() {#a04b828a38a5db2eb63cd610307ff8830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned &amp; llvm::IntervalMapImpl::Path::offset (unsigned Level)</td>
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



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### pop() {#a8a8bbc180b0fb593af60a451bec9c8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::pop ()</td>
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

<p>pop - Remove the last path entry.</p>

<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### push() {#af18dce9b09fd23b653e19a42e8d066a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::push (<a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a> Node, unsigned Offset)</td>
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

<p>push - Add entry to path.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/node"&gt;Node&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> to add, should be subtree(path.size()-1).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>Offset into <a href="/web-llvm/docs/api/classes/node">Node</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### replaceRoot() {#a0045511f2217fb2722053df480ca93d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::replaceRoot (void * Root, unsigned Size, <a href="/web-llvm/docs/api/namespaces/llvm/intervalmapimpl/#ab92974e292699af764f4bd02d1f44448">IdxPair</a> Offsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>replaceRoot - Replace the current root node with two new entries after the tree height has increased.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Root</td>
<td class="doxyParamItemDescription"><p>The new root node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Number of entries in the new root.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offsets</td>
<td class="doxyParamItemDescription"><p>Offsets into the root and first branch nodes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/intervalmap-cpp">IntervalMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#af6b9bc0a599f8d7071efbe343ffb5c06">subtree</a>.</p>

</div>
</div>

### reset() {#a0b3124c4f83510dd0e86c97580bedcdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::reset (unsigned Level)</td>
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

<p>reset - Reset cached information about node(Level) from subtree(Level -1).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>1..height. The node to update after parent node changed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a50067a0fc5557d9b4e98b7b457d09b06">offset</a> and <a href="#af6b9bc0a599f8d7071efbe343ffb5c06">subtree</a>.</p>

</div>
</div>

### setRoot() {#a4ad7abf532bcf6e64587359c9e5321f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::setRoot (void * Node, unsigned Size, unsigned Offset)</td>
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

<p>setRoot - Clear the path and set a new root node.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/node"&gt;Node&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>New root node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>New root size.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>Offset into root node.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### setSize() {#a984b07539b0e770760b2cfa8b2474fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::Path::setSize (unsigned Level, unsigned Size)</td>
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

<p>setSize - Set the size of a node both in the path and in the tree.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>0..height. Note that setting the root size won't change map-&gt;rootSize.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>New node size.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#af6b9bc0a599f8d7071efbe343ffb5c06">subtree</a>.</p>

</div>
</div>

### size() {#abf18dbdc3e5f4395cb816b7cfc28df87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMapImpl::Path::size (unsigned Level)</td>
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



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a8186267aca496ea543bd8d2ec77660f7">moveRight</a>.</p>

</div>
</div>

### subtree() {#af6b9bc0a599f8d7071efbe343ffb5c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef &amp; llvm::IntervalMapImpl::Path::subtree (unsigned Level)</td>
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

<p>subtree - Get the subtree referenced from Level.</p>


<p>When the path is consistent, node(Level + 1) == subtree(Level).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Level</td>
<td class="doxyParamItemDescription"><p>0..height-1. The leaves have no subtrees.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>References <a href="#a50067a0fc5557d9b4e98b7b457d09b06">offset</a> and <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef/#ad56a61be137a6adfe4327233a4e492f9">llvm::IntervalMapImpl::NodeRef::subtree</a>.</p>


<p>Referenced by <a href="#ab252ce944fb2315d923f0d2f36523f0f">fillLeft</a>, <a href="#ae878a804adbd190aad9c23df62b0f352">moveLeft</a>, <a href="#a8186267aca496ea543bd8d2ec77660f7">moveRight</a>, <a href="#a0045511f2217fb2722053df480ca93d4">replaceRoot</a>, <a href="#a0b3124c4f83510dd0e86c97580bedcdf">reset</a> and <a href="#a984b07539b0e770760b2cfa8b2474fd8">setSize</a>.</p>

</div>
</div>

### valid() {#a0b2cb75a028a3053dea9d50565cdef34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntervalMapImpl::Path::valid ()</td>
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

<p>valid - Return true if path is at a valid node, not at end().</p>

<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#ab9434bd7ee08975d3ed2adca806f2096">legalizeForInsert</a> and <a href="#ae878a804adbd190aad9c23df62b0f352">moveLeft</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### path {#a80487b75be12a4872c06ddfaf1b4d2c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Entry, 4&gt; llvm::IntervalMapImpl::Path::path</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>path - The path entries, path[0] is the root node, path.back() is a leaf.</p>

<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/intervalmap-cpp">IntervalMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
