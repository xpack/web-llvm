---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/intervalmapimpl/nodebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NodeBase` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename T1, typename T2, unsigned N&gt;
class llvm::IntervalMapImpl::NodeBase&lt;T1, T2, N&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">llvm/ADT/IntervalMap.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned M&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28ff2f41afe22a42b271b12b4fb8d809">copy</a> (const NodeBase&lt; T1, T2, M &gt; &amp;Other, unsigned i, unsigned j, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>copy - Copy elements from another node. <a href="#a28ff2f41afe22a42b271b12b4fb8d809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a08e57383fde63b9c4afa84ef93dcf59b">moveLeft</a> (unsigned i, unsigned j, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>moveLeft - Move elements to the left. <a href="#a08e57383fde63b9c4afa84ef93dcf59b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac39f13dd6ea8d7bed1ca4fdeeb409a39">moveRight</a> (unsigned i, unsigned j, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>moveRight - Move elements to the right. <a href="#ac39f13dd6ea8d7bed1ca4fdeeb409a39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a01bdf3dc12c07694d5f64d8a83dc21f5">erase</a> (unsigned i, unsigned j, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>erase - Erase elements [i;j). <a href="#a01bdf3dc12c07694d5f64d8a83dc21f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac1350c0a110ad03ba5425d534c85b28d">erase</a> (unsigned i, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>erase - Erase element at i. <a href="#ac1350c0a110ad03ba5425d534c85b28d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7bbe7cab7dbadc3d8849ac3cfe4162c1">shift</a> (unsigned i, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>shift - Shift elements [i;size) 1 position to the right. <a href="#a7bbe7cab7dbadc3d8849ac3cfe4162c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f3758be51b1c7b31dd35602d524df95">transferToLeftSib</a> (unsigned Size, NodeBase &amp;Sib, unsigned SSize, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>transferToLeftSib - Transfer elements to a left sibling node. <a href="#a1f3758be51b1c7b31dd35602d524df95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abed52bd8600aaa49567ed0f533cbf1d0">transferToRightSib</a> (unsigned Size, NodeBase &amp;Sib, unsigned SSize, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>transferToRightSib - Transfer elements to a right sibling node. <a href="#abed52bd8600aaa49567ed0f533cbf1d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70a77b0f022fde493ace11aab5d70101">adjustFromLeftSib</a> (unsigned Size, NodeBase &amp;Sib, unsigned SSize, int Add)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adjustFromLeftSib - Adjust the number if elements in this node by moving elements to or from a left sibling node. <a href="#a70a77b0f022fde493ace11aab5d70101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a56d3e243604b73a27ffb7929cdf71922">first</a>[N]</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T2</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d45826116f9f6e37ceed4b3ad9c2b3e">second</a>[N]</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T1, typename T2, unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3928712e3203651240c884c838274d16">Capacity</a> = <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a></td>
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


<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### adjustFromLeftSib() {#a70a77b0f022fde493ace11aab5d70101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::adjustFromLeftSib (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase">NodeBase</a> &amp; Sib, unsigned SSize, int Add)</td>
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

<p>adjustFromLeftSib - Adjust the number if elements in this node by moving elements to or from a left sibling node.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Number of elements in this.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Sib</td>
<td class="doxyParamItemDescription"><p>Right sibling node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SSize</td>
<td class="doxyParamItemDescription"><p>Number of elements in sib.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Add</td>
<td class="doxyParamItemDescription"><p>The number of elements to add to this node, possibly &lt; 0.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Number of elements added to this node, possibly negative.</p></dd>
</dl>


<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### copy() {#a28ff2f41afe22a42b271b12b4fb8d809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned M&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::copy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase">NodeBase</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#ac16509a75e3d3fc46b9df1726be486ec">T1</a>, T2, M &gt; &amp; Other, unsigned i, unsigned j, unsigned Count)</td>
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

<p>copy - Copy elements from another node.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Other</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> elements are copied from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">i</td>
<td class="doxyParamItemDescription"><p>Beginning of the source range in other.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">j</td>
<td class="doxyParamItemDescription"><p>Beginning of the destination range in this.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Count</td>
<td class="doxyParamItemDescription"><p>Number of elements to copy.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a08e57383fde63b9c4afa84ef93dcf59b">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::moveLeft</a>, <a href="#a1f3758be51b1c7b31dd35602d524df95">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::transferToLeftSib</a> and <a href="#abed52bd8600aaa49567ed0f533cbf1d0">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::transferToRightSib</a>.</p>

</div>
</div>

### erase() {#a01bdf3dc12c07694d5f64d8a83dc21f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::erase (unsigned i, unsigned j, unsigned Size)</td>
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

<p>erase - Erase elements [i;j).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">i</td>
<td class="doxyParamItemDescription"><p>Beginning of the range to erase.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">j</td>
<td class="doxyParamItemDescription"><p>End of the range. (Exclusive).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Number of elements in node.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/intervalmap/iterator/#a3b0dc2d50cb2de5563983618a99af467">llvm::IntervalMap&lt; KeyT, ValT, N, Traits &gt;::iterator::erase</a>, <a href="#ac1350c0a110ad03ba5425d534c85b28d">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::erase</a> and <a href="#a1f3758be51b1c7b31dd35602d524df95">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::transferToLeftSib</a>.</p>

</div>
</div>

### erase() {#ac1350c0a110ad03ba5425d534c85b28d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::erase (unsigned i, unsigned Size)</td>
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

<p>erase - Erase element at i.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">i</td>
<td class="doxyParamItemDescription"><p>Index of element to erase.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Number of elements in node.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### moveLeft() {#a08e57383fde63b9c4afa84ef93dcf59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::moveLeft (unsigned i, unsigned j, unsigned Count)</td>
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

<p>moveLeft - Move elements to the left.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">i</td>
<td class="doxyParamItemDescription"><p>Beginning of the source range.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">j</td>
<td class="doxyParamItemDescription"><p>Beginning of the destination range.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Count</td>
<td class="doxyParamItemDescription"><p>Number of elements to copy.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a01bdf3dc12c07694d5f64d8a83dc21f5">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::erase</a>.</p>

</div>
</div>

### moveRight() {#ac39f13dd6ea8d7bed1ca4fdeeb409a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::moveRight (unsigned i, unsigned j, unsigned Count)</td>
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

<p>moveRight - Move elements to the right.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">i</td>
<td class="doxyParamItemDescription"><p>Beginning of the source range.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">j</td>
<td class="doxyParamItemDescription"><p>Beginning of the destination range.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Count</td>
<td class="doxyParamItemDescription"><p>Number of elements to copy.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a7bbe7cab7dbadc3d8849ac3cfe4162c1">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::shift</a> and <a href="#abed52bd8600aaa49567ed0f533cbf1d0">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::transferToRightSib</a>.</p>

</div>
</div>

### shift() {#a7bbe7cab7dbadc3d8849ac3cfe4162c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::shift (unsigned i, unsigned Size)</td>
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

<p>shift - Shift elements [i;size) 1 position to the right.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">i</td>
<td class="doxyParamItemDescription"><p>Beginning of the range to move.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Number of elements in node.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### transferToLeftSib() {#a1f3758be51b1c7b31dd35602d524df95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::transferToLeftSib (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase">NodeBase</a> &amp; Sib, unsigned SSize, unsigned Count)</td>
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

<p>transferToLeftSib - Transfer elements to a left sibling node.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Number of elements in this.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Sib</td>
<td class="doxyParamItemDescription"><p>Left sibling node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SSize</td>
<td class="doxyParamItemDescription"><p>Number of elements in sib.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Count</td>
<td class="doxyParamItemDescription"><p>Number of elements to transfer.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a70a77b0f022fde493ace11aab5d70101">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::adjustFromLeftSib</a>.</p>

</div>
</div>

### transferToRightSib() {#abed52bd8600aaa49567ed0f533cbf1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::transferToRightSib (unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase">NodeBase</a> &amp; Sib, unsigned SSize, unsigned Count)</td>
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

<p>transferToRightSib - Transfer elements to a right sibling node.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Number of elements in this.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Sib</td>
<td class="doxyParamItemDescription"><p>Right sibling node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SSize</td>
<td class="doxyParamItemDescription"><p>Number of elements in sib.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Count</td>
<td class="doxyParamItemDescription"><p>Number of elements to transfer.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Referenced by <a href="#a70a77b0f022fde493ace11aab5d70101">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::adjustFromLeftSib</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### first {#a56d3e243604b73a27ffb7929cdf71922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T1 llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::first[N]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

### second {#a4d45826116f9f6e37ceed4b3ad9c2b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T2 llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::second[N]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Capacity {#a3928712e3203651240c884c838274d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T1, typename T2, unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntervalMapImpl::NodeBase&lt; T1, T2, N &gt;::Capacity = <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a></td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
