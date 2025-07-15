---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-valuemapper-cpp-/mdnodemapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MDNodeMapper` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{ValueMapper.cpp}::MDNodeMapper { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332d6883ae1fe5af9bda81416f7bfbe0">MDNodeMapper</a> (Mapper &amp;M)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e14dd6bf8fd49e43925ade95aab06d">map</a> (const MDNode &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a metadata node (and its transitive operands). <a href="#a19e14dd6bf8fd49e43925ade95aab06d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OperandMapper&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c38ca83c916472e5580992d97616ba9">remapOperands</a> (MDNode &amp;N, OperandMapper mapOperand)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7ef8eee51633a39f3cab453baa7ff0">mapTopLevelUniquedNode</a> (const MDNode &amp;FirstN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a top-level uniqued node and the uniqued subgraph underneath it. <a href="#a7e7ef8eee51633a39f3cab453baa7ff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f5a8ab4da21b753ff41987e1b5741a">tryToMapOperand</a> (const Metadata *Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to map the operand of an <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>. <a href="#a80f5a8ab4da21b753ff41987e1b5741a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab062c4f5119fb7b9a647d4f300b2d1c5">mapDistinctNode</a> (const MDNode &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a distinct node. <a href="#ab062c4f5119fb7b9a647d4f300b2d1c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f0af01bf4f2f7b7a63d5789c1607495">getMappedOp</a> (const Metadata *Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a previously mapped node. <a href="#a8f0af01bf4f2f7b7a63d5789c1607495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dace28a02e57b477f817c9f9030a5fc">createPOT</a> (UniquedGraph &amp;G, const MDNode &amp;FirstN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a post-order traversal of an unmapped uniqued node subgraph. <a href="#a9dace28a02e57b477f817c9f9030a5fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69f6d67917f647af69d6ba7bb126ca9">visitOperands</a> (UniquedGraph &amp;G, MDNode::op_iterator &amp;I, MDNode::op_iterator E, bool &amp;HasChanged)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit the operands of a uniqued node in the POT. <a href="#af69f6d67917f647af69d6ba7bb126ca9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b664997f960985542ef30c564ec861">mapNodesInPOT</a> (UniquedGraph &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map all the nodes in the given uniqued graph. <a href="#a62b664997f960985542ef30c564ec861">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class OperandMapper&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c38ca83c916472e5580992d97616ba9">remapOperands</a> (MDNode &amp;N, OperandMapper mapOperand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remap a node's operands using the given functor. <a href="#a7c38ca83c916472e5580992d97616ba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper">Mapper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f495df041166b52263e1bee5dc4a59f">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae239bcf674a7148aa155af2d184a7902">DistinctWorklist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Worklist of distinct nodes whose operands need to be remapped. <a href="#ae239bcf674a7148aa155af2d184a7902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, Data, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af58edfe4b549831024e107cc071bf271">InfoStorage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482f4c0b884d200b1efc83bb42c51693">POTStorage</a></td>
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


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MDNodeMapper() {#a332d6883ae1fe5af9bda81416f7bfbe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ValueMapper.cpp}::MDNodeMapper::MDNodeMapper (<a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper">Mapper</a> &amp; M)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### map() {#a19e14dd6bf8fd49e43925ade95aab06d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * MDNodeMapper::map (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a metadata node (and its transitive operands).</p>


<p>Map all the (unmapped) nodes in the subgraph under <span class="doxyComputerOutput">N</span>. The iterative algorithm handles distinct nodes and uniqued node subgraphs using different strategies.</p>


<p>Distinct nodes are immediately mapped and added to <em>DistinctWorklist</em> using <em>mapDistinctNode()</em>. Their mapping can always be computed immediately without visiting operands, even if their operands change.</p>


<p>The mapping for uniqued nodes depends on whether their operands change. <em>mapTopLevelUniquedNode()</em> traverses the transitive uniqued subgraph of a node to calculate uniqued node mappings in bulk. Distinct leafs are added to <em>DistinctWorklist</em> with <em>mapDistinctNode()</em>.</p>


<p>After mapping <span class="doxyComputerOutput">N</span> itself, this function remaps the operands of the distinct nodes in <em>DistinctWorklist</em> until the entire subgraph under <span class="doxyComputerOutput">N</span> has been mapped.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#aaa122781f91b3e8bc730b2c5b7c07a05">remapOperands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da9a24bd8dba1bef2753bc3f087435ae7f">llvm::RF_NoModuleLevelChanges</a>.</p>

</div>
</div>

### remapOperands() {#a7c38ca83c916472e5580992d97616ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OperandMapper&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ValueMapper.cpp}::MDNodeMapper::remapOperands (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; N, OperandMapper mapOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createPOT() {#a9dace28a02e57b477f817c9f9030a5fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MDNodeMapper::createPOT (UniquedGraph &amp; G, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; FirstN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a post-order traversal of an unmapped uniqued node subgraph.</p>


<p>This traverses the metadata graph deeply enough to map <span class="doxyComputerOutput">FirstN</span>. It uses <em>tryToMapOperand()</em> (via <em>Mapper::mapSimplifiedNode()</em>), so any metadata that has already been mapped will not be part of the POT.</p>


<p>Each node that has a changed operand from outside the graph (e.g., a distinct node, an already-mapped uniqued node, or <em><a href="/web-llvm/docs/api/classes/llvm/constantasmetadata">ConstantAsMetadata</a></em>) is marked with <em>Data::HasChanged</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">true</span> if any nodes in <span class="doxyComputerOutput">G</span> have <em>Data::HasChanged</em>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p><span class="doxyComputerOutput">G.POT</span> is a post-order traversal ending with <span class="doxyComputerOutput">FirstN</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p><em>Data::hasChanged</em> in <span class="doxyComputerOutput">G.Info</span> indicates whether any node needs to change because of operands outside the graph.</p></dd>
</dl>


<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### getMappedOp() {#a8f0af01bf4f2f7b7a63d5789c1607495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Metadata * &gt; MDNodeMapper::getMappedOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a previously mapped node.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### mapDistinctNode() {#ab062c4f5119fb7b9a647d4f300b2d1c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDNodeMapper::mapDistinctNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a distinct node.</p>


<p>Return the mapping for the distinct node <span class="doxyComputerOutput">N</span>, saving the result in <em>DistinctWorklist</em> for later remapping.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">N</span> is not yet mapped.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">N.isDistinct()</span>.</p></dd>
</dl>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### mapNodesInPOT() {#a62b664997f960985542ef30c564ec861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MDNodeMapper::mapNodesInPOT (UniquedGraph &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map all the nodes in the given uniqued graph.</p>


<p>This visits all the nodes in <span class="doxyComputerOutput">G</span> in post-order, using the identity mapping or creating a new node depending on <em>Data::HasChanged</em>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><em>getMappedOp()</em> returns std::nullopt for nodes in <span class="doxyComputerOutput">G</span>, but not for any of their operands outside of <span class="doxyComputerOutput">G</span>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><em>Data::HasChanged</em> is true for a node in <span class="doxyComputerOutput">G</span> iff any of its operands have changed.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p><em>getMappedOp()</em> returns the mapped node for every node in <span class="doxyComputerOutput">G</span>.</p></dd>
</dl>


<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### mapTopLevelUniquedNode() {#a7e7ef8eee51633a39f3cab453baa7ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * MDNodeMapper::mapTopLevelUniquedNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; FirstN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a top-level uniqued node and the uniqued subgraph underneath it.</p>


<p>This builds up a post-order traversal of the (unmapped) uniqued subgraph underneath <span class="doxyComputerOutput">FirstN</span> and calculates the nodes' mapping. Each node uses the identity mapping (<em>Mapper::mapToSelf()</em>) as long as all of its operands uses the identity mapping.</p>


<p>The algorithm works as follows:</p>


<ol class="doxyList" type="1">
<li><em>createPOT()</em>: traverse the uniqued subgraph under <span class="doxyComputerOutput">FirstN</span> and save the post-order traversal in the given <em>UniquedGraph</em>, tracking nodes' operands change.</li>
<li><em>UniquedGraph::propagateChanges()</em>: propagate changed operands through the <em>UniquedGraph</em> until fixed point, following the rule that if a node changes, any node that references must also change.</li>
<li><em>mapNodesInPOT()</em>: map the uniqued nodes, creating new uniqued nodes (referencing new operands) where necessary.</li>
</ol>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### remapOperands() {#a7c38ca83c916472e5580992d97616ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class OperandMapper&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ValueMapper.cpp}::MDNodeMapper::remapOperands (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; N, OperandMapper mapOperand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remap a node's operands using the given functor.</p>


<p>Iterate through the operands of <span class="doxyComputerOutput">N</span> and update them in place using <span class="doxyComputerOutput">mapOperand</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>N.isDistinct() or N.isTemporary().</p></dd>
</dl>


<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### tryToMapOperand() {#a80f5a8ab4da21b753ff41987e1b5741a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Metadata * &gt; MDNodeMapper::tryToMapOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to map the operand of an <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>.</p>


<p>If <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is already mapped, return the mapping. If it's not an <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>, compute and return the mapping. If it's a distinct <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>, return the result of <em>mapDistinctNode()</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is an unmapped uniqued <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p>getMappedOp(Op) only returns std::nullopt if this returns std::nullopt.</p></dd>
</dl>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### visitOperands() {#af69f6d67917f647af69d6ba7bb126ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * MDNodeMapper::visitOperands (UniquedGraph &amp; G, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#af4fe559b6ceafad40f7144063ef2afd2">MDNode::op_iterator</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#af4fe559b6ceafad40f7144063ef2afd2">MDNode::op_iterator</a> E, bool &amp; HasChanged)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit the operands of a uniqued node in the POT.</p>


<p>Visit the operands in the range from <span class="doxyComputerOutput">I</span> to <span class="doxyComputerOutput">E</span>, returning the first uniqued node we find that isn't yet in <span class="doxyComputerOutput">G</span>. <span class="doxyComputerOutput">I</span> is always advanced to where to continue the loop through the operands.</p>


<p>This sets <span class="doxyComputerOutput">HasChanged</span> if any of the visited operands change.</p>


<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DistinctWorklist {#ae239bcf674a7148aa155af2d184a7902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MDNode *, 16&gt; anonymous{ValueMapper.cpp}::MDNodeMapper::DistinctWorklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Worklist of distinct nodes whose operands need to be remapped.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### InfoStorage {#af58edfe4b549831024e107cc071bf271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;const Metadata *, Data, 32&gt; anonymous{ValueMapper.cpp}::MDNodeMapper::InfoStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### M {#a9f495df041166b52263e1bee5dc4a59f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Mapper&amp; anonymous{ValueMapper.cpp}::MDNodeMapper::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### POTStorage {#a482f4c0b884d200b1efc83bb42c51693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MDNode *, 16&gt; anonymous{ValueMapper.cpp}::MDNodeMapper::POTStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
